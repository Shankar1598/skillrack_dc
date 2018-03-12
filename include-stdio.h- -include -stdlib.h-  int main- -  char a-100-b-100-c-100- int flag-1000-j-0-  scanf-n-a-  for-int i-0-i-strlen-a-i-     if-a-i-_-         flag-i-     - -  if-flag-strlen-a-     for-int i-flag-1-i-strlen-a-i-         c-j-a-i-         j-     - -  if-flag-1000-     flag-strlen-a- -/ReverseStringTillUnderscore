#include<stdio.h>
#include <stdlib.h>

int main()
{

char a[100],b[100],c[100];
int flag=1000,j=0;

scanf("%[^\n]",a);

for(int i=0;i<strlen(a);i++){
    if(a[i]=='_'){
        flag=i;
    }
}

if(flag<strlen(a)){
    for(int i=flag+1;i<strlen(a);i++){
        c[j]=a[i];
        j++;
    }
}

if(flag==1000){
    flag=strlen(a);
}

// printf("%d",flag);

for(int i=0;i<flag;i++){
    b[i]=a[flag-1-i];
}
if(flag<strlen(a)){
    b[strlen(b)]='_';
}
if(flag==0){
    b[0]='_';
    b[1]='\0';
}

printf("%s",b);

if(flag<strlen(a)-1){
    printf("%s",c);
}

}
