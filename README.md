# Javapoint_Function_Example.1
//DOCUMENTATION SECTION 
/*SHARVIN KUMAR ARUMUGAM
DATE : 28/02/2022
DISCRIPTION : JAVATPOINT(FUNCTION )
without argument and return value*/

//PRE-PROCESSOR SECTION
#include<stdio.h>

//GLOBAL VARIABLE SECTION
void sum();

//MAIN FUNCTION SECTION
void main(){

    printf("\nGoing to Calculate The Sum of two Number ");
    sum(); 
}
//USE-DEFINED SECTION
void sum(){
    int a,b;

    printf("\nEnter two Number : ");
    scanf("%d%d",&a,&b);
    
    printf("\nSum is %d ",a+b);
}
