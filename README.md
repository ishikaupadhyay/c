# c

#include <stdio.h>

int main()
{
    int a, b; // If values in decimAL, then use float,double....!!!....
    printf("ENTER 1ST NUMBER : ");
    scanf("%d", &a);
    printf("ENTER 2NDT NUMBER : ");
    scanf("%d", &b);

    // Arithnetic Operators.|

    printf("a+b =%d\n", a + b);
    printf("a-b =%d\n", a - b);
    printf("a*b =%d\n", a * b);
    printf("a/b =%d\n", a / b);
    printf("a%b =%d\n", a % b);

    printf("a+b =%d\n", a == b); // Relational operators(if a =b then returns 1 otherwise 0)
    printf("a+b =%d\n", a && b); // Logical operAtors.   ....(&&)
    printf("a+b =%d\n", a || b); // Logical operAtors.   ....(||)
    printf("a+b =%d\n", !b);     // Logical operAtors.   ....(!)  It converts 1 to 0 and vice versa....1 means any non zero value :)
    printf("Bitwise operator =%d\n", a&b);     // Bitwise operAtors.  &,|,^(XOR)...
    return 0;
}
