# C-Module-5
# Program 1:
## AIM: 
To write a C program to multiply three numbers using pointers. 
## ALGORITHM: 
```
1) Get three numbers as inputs from the user. 
2) Assign pointer variables for each inputs. 
3) print the result of multiplication using printf() function.
```
## PROGRAM: 
``` 
#include<stdio.h> 
int main() 
{ 
int num1,num2,num3; 
scanf("%d %d %d",&num1,&num2,&num3); 
int *ptr1=&num1,*ptr2=&num2,*ptr3=&num3; 
printf("%d * %d * %d= %d",num1,num2,num3,*ptr1**ptr2**ptr3); 
} 
``` 
## OUTPUT: 
<img width="445" height="238" alt="Screenshot 2025-10-20 195814" 
src="https://github.com/user-attachments/assets/e9d873c5-1f40-44b4-b25c-f29ded6d9e4b" 
/> 
## RESULT: 
Thus the C program to multiply three numbers using pointers is executed successfully. 
# Program 2:
## AIM: 
To write a c program to swap two numbers using pointers. 
## ALGORITHM: 
```
1) Get two numbers as input from the user. 
2) swap the values of two variables and print the result using printf() function.
```
## PROGRAM: 
``` 
#include<stdio.h> 
int main() 
{ 
    int a,b; 
    int *pa=&a,*pb=&b; 
    scanf("%d %d",&a,&b); 
    printf("m is %d, n is %d\n",*pa,*pb);  
    if(*pa!=*pb) 
    { 
        *pa=*pa+*pb; 
        *pb=*pa-*pb; 
        *pa=*pa-*pb; 
    } 
    printf("m is %d, n is %d",*pa,*pb); 
} 
``` 
## OUTPUT: 
<img width="485" height="263" alt="Screenshot 2025-10-20 201027" 
src="https://github.com/user-attachments/assets/49414a80-348b-4c97-94e5-a3230da13d76" 
/> 
## RESULT: 
Thus the C program to swap two numbers is successfully executed. 
# Program 3:
## AIM: 
To write a C program to find the sum of opposite diagonal elements of a given matrix. 
## ALGORITHM: 
```
1) Get a matrix as an input from the user. 
2) Find the sum of diagonal elements using for loop anf if else statements. 
3) print the result using printf() function.
```
## PROGRAM: 
``` 
#include <stdio.h> 
 
int main() 
{ 
    int n1,n2; 
    scanf("%d %d",&n1,&n2); 
    int mat[n1][n2]; 
    for(int i=0;i<n1;i++) 
    { 
        for(int j=0;j<n2;j++) 
        { 
            scanf("%d",&mat[i][j]); 
        } 
    } 
    int sum=0; 
    for(int i=0;i<n1;i++) 
    { 
        for(int j=0;j<=n2;j++) 
        { 
            if(i+j==2){ 
            printf("%d ",mat[i][j]); 
            sum+=mat[i][j];} 
        }printf("\n"); 
    }printf("The Sum of Opposite Diagonal Elements of a Matrix =  %d",sum);   
    return 0; 
} 
 
``` 
## OUTPUT: 
<img width="1096" height="280" alt="Screenshot 2025-10-20 201924" 
src="https://github.com/user-attachments/assets/04ecb789-b123-4ae4-b5b6-1efa6a5b8619" 
/> 
## RESULT:  
Thus the C program to find the sum of opposite diagonal elements of a given matrix is 
executed successfully. 
# Program 4: 
## AIM: 
To write a c program to count the number of alphabets in a given string. 
## ALGORITHM: 
```
1) Get a string as an input fromm the user. 
2) Count the number of alphabets in the string using for loop. 
3) print the result using printf() function. 
```
## PROGRAM: 
``` 
#include<stdio.h> 
#include<ctype.h> 
#include<string.h> 
int main() 
{ 
    char str[100]; 
    int count=0; 
    fgets(str,sizeof(str),stdin); 
    for(int i=0;str[i]!='\0';i++) 
    { 
        if((str[i]>=60&&str[i]<=90)||(str[i]>=97&&str[i]<=122)) 
        count++; 
    } 
    printf("Number of Alphabets in the string is : %d",count); 
} 
``` 
## OUTPUT: 
<img width="1133" height="104" alt="Screenshot 2025-10-20 203346" 
src="https://github.com/user-attachments/assets/471982d1-a802-4f26-9f06-64e276d01641" 
/> 
## RESULT: 
Thus the C program to count the number of alphabets in the given string is executed 
successfully. 
# Program 5:
## AIM: 
To write a C program to check ahether the givern character is digit or not. 
## ALGORITHM: 
```
1) Get a character as input from the user. 
2) Check whether the given character is digit or not using ASCII value. 
3) print the result using printf() function. 
```
## PROGRAM: 
``` 
 
#include<stdio.h> 
int main() 
{ 
    char ch; 
    scanf("%c ",&ch); 
    if(ch<='9') 
    printf("the given character is digit: %c",ch); 
    else 
    printf("the given character is not digit: %c",ch);  
} 
``` 
## OUTPUT: 
<img width="834" height="146" alt="Screenshot 2025-10-20 204657" 
src="https://github.com/user-attachments/assets/83505dd7-2940-420d-a44d-1aac5f581db5" 
/> 
## RESULT: 
Thus the C program to check whether the given character is digit or not is executed 
successfully. 

 
