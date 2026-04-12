#include<stdio.h>
#include<string.h>
int main(){
printf("25331A05E9\n");

char str1 [50] = "Hello";
char str2 [50] = "priya";
char str3 [50];
    int length;

    
    length = strlen(str1);
    printf("Length of str1 ('%s'): %d\n", str1, length);

    strcpy(str3, str1);
    printf("After strcpy, str3: %s\n", str3);

    
    strcat(str1, " ");
    strcat(str1, str2); 
    printf("After strcat, str1: %s\n", str1);

    
    if (strcmp(str3, "Hello") == 0) {
        printf("str3 and 'Hello' are equal.\n");
    } else {
        printf("str3 and 'Hello' are not equal.\n");
    }

    return 0;
}
