# git

include <stdio.h>
include <math.h>

main()
{
  float x, y;
  
  printf("Solve the equation y=x-10/x*10\n");
  printf("Enter x value\n");
  scanf("%f", &x);
  
  y=x-10/x*10;
  printf("Result y = %f", y);
  
  y=y/2;
  printf("New result y = %f", y);
  
  system("pause");
}
