#include <stdio.h>
void main(){
float p,c,m,percentage;

printf("Enter the marks of Physics ");
scanf("%f",&p);
printf("Enter the marks of Chemistry");
scanf("%f",&c);
printf("Enter the marks of Mathematics ");
scanf("%f",&m);
percentage=(p+c+m)/3.0;
printf("\n %.2f is the percentage of overall subject", percentage );

if (percentage >= 50 && percentage < 60)
{
    printf("\n Grade is D");
}
else if (percentage >= 60 && percentage < 70)
{
    printf("\n Grade is C");
}
else if (percentage >= 70 && percentage < 80)
{
    printf("\n Grade is B");
}
else if(percentage >= 80 && percentage <= 100)
{
    printf("\n Grade is A");
}
else
{
    printf("\n FAIL");
}
}
