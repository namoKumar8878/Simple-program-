# Simple-program-
Mathematics program 

#include<stdio.h>

float area_of_trigal(float bace,float hight);

float area_of_trigal(float bace,float hight){
    return 0.5*bace*hight;
    }
int main()
{    
    float bace,hight;
    
    printf("enter the bace : ");
    scanf("%f",&bace);
    
    printf("enter the hight : ");
    scanf("%f",&hight);
    
    printf("the area of trigal is %0.2f cm²",area_of_trigal(bace,hight));
    
    return 0;
}
