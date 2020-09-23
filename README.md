<div align="center">

## string to integer to double


</div>

### Description

Converts a numeric string to integer and then to double. Demonstrates the use of atoi() and atof().
 
### More Info
 
Basic but nifty beginner stuff. Hope it is useful to someone. Please vote!!


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Tom Gerhard](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/tom-gerhard.md)
**Level**          |Beginner
**User Rating**    |5.0 (10 globes from 2 users)
**Compatibility**  |C
**Category**       |[Strings](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/strings__3-26.md)
**World**          |[C / C\+\+](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/c-c.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/tom-gerhard-string-to-integer-to-double__3-7281/archive/master.zip)

### API Declarations

```
#include<stdio.h>
#include<stdlib.h>
```


### Source Code

```
#include<stdio.h>
#include<stdlib.h>
#include<string.h>
int main()
{
  char word[80];
  puts("\nEnter an integer string: ");
  gets(word);
  /* atoi() : converts its argument, a series of numbers used
   * as a string, in to an integer value and returns it. The
   * statement after the conversion statement shows how unsigned
   * long i has been converted and can now be used.
  */
  unsigned long i = atoi(word);
  printf("\nThe string '%s' converted to integer is %u.\n", word, i);
  printf("The converted string squared is %u.\n", i * i);
  /* atol(): converts its string argument to a double value. The
   * statement following the conversion shows how it can be used.
  */
  double f = atol(word);
  printf("\nThe string '%s' converted to double is %.2f.\n", word, f);
  printf("The converted string divided by 3 is %.3f.\n\n", f / 3);
  /* play and enjoy! */
  system("PAUSE");
  return 0;
}
```

