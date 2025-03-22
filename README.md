#include <stdio.h>
#include <math.h>

int main() {
    double num;
    printf("Enter a number: ");
    scanf("%lf", &num);
    double ceiling_val = ceil(num);
    double abs_val = fabs(num);
    printf("Ceiling of %.2lf is %.2lf\n", num, ceiling_val);
    printf("Absolute value of %.2lf is %.2lf\n", num, abs_val);
    return 0;
}
