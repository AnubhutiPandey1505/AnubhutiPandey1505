#include <stdio.h>
struct student
{
 char name[20];
 char dept[20];
 char specialization[20];
 int regno;
};
 int main() 
 {
 struct student a;
printf(" Enter student details :\n ");
 printf("------------\n");
printf(" Enter Name     : ");
scanf("%s" , a.name);
printf("Enter Department : ") ;
scanf("%s", a.dept) ;
printf("Enter Specialization: ") ;
scanf("%s", a.specialization) ;
printf("Enter Registration No : ") ;
scanf("%d", &a.regno);
printf("-----------------") ;
printf("\Students Details:\n----------\n") ;
printf("Name   :%s\n", a.name) ;
printf(" Department  :%s\n", a.dept);
printf("Specialization :% s\n", a.specialization) ;
printf("Registration No : %d\n", a.regno);
return 0;
}
