# clang-format-config

A copy of my .clang-format [configuration][1] file for C.

## Description

The formatting looks like this:

``` c
#include <stdio.h>
#include <stdlib.h>

int main(int argc, char *argv)
{
    if (argc < 2) {
        fprintf(stderr, "Usage: %s <input-path>", argc[0]);
        return EXIT_FAILURE;
    }

    switch (argc) {
    case 2: /* handle case 2 */ break;
    case 3: /* handle case 4 */ break;
    case 4: /* handle case 4 */ break;
    default: /* handle default case */ break;
    }

    return EXIT_SUCCESS;
}
```

[1]: https://clang.llvm.org/docs/ClangFormatStyleOptions.html
