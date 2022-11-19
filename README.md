# LENGTH-OF-A-STRING



//input string and print that 
#include <stdio.h>
#include <string.h>

int main() {
    char str[10]="PRESHU";
    printf("ENTER STRING\n");
    scanf("%s", &str);
    int len=strlen(str);
    printf("LENGTH OF A STRING IS%d", len);

    return 0;
}

//WITHOUT USING STRLEN FUNCTION




#include<stdio.h>
void main()
{
     char str[100] = "PRESHU SAXENA";
     int i,count =0;
     for(i=0;str[i]!='\0';i++)
     {
      count ++;
     }
     printf("Length is %d",count);
}
