#include <stdio.h>
int main(){
  
  float area_f, side_f;
  double area_d, side_d;
  
  scanf("%f", &side_f);
  
  side_d = side_f;
  
  area_f = side_f * side_f;
  area_d = side_d * side_d;
  
  printf("%.6f cm\n", area_f);
  printf("%.6lf cm", area_d);
  
  return 0;
}
