#include <stdio.h>
void main ()
{
    int x,y,z;
    printf ("Type a number\n");
    scanf ("%d", &x);
    if (x > 5 && x < 30)
    {
        y = x % 5;
        z = x /30;
        if (y==z)
        {
            printf ("0,5,10,15,20*\n");
        }
        else
        printf ("error");
    }
 return 0;
}
