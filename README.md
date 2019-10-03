#include <stdio.h>
#include <math.h>

int main()
{
    float x,y,z;
    printf("Input Number = ");
    scanf ("%f",&x);
    y = log10(x);
    z = sqrt(x);
    printf ("Logarithm is = %.2f",y);
    printf ("Square Root is = %.2f",z);
    return 0;
}
