# primality-check
Small header file for fast 64 bits primality check

## Usage example

```c
#include <stdlib.h>
#include <stdio.h>

#include "isprime64.h"

int main(int argc, char *argv[]) {
	uint64_t n = 173299173648191741;
	if (isprime64(n)) printf("%llu is prime\n", n);
	else printf("%llu is not prime\n", n);
}
```
