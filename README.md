# switch-case
#include <stdio.h>

int main() {
  int number,a,b;
  printf("enter your number (0-4) :");
  scanf("%d%d%d",&number,&a,&b);
  switch( number){
      case 1:
            a+=b;
            printf("%d",a);
            break;
      case 2:
            a-=b;
            printf("%d",a);
            break;
      case 3:
            a*=b;
            printf("%d",a);
            break;
      case 4:
            a/=b;
            printf("%d",a);
            break;
            default:
                printf("plz enter correct number:");
            }
  
    return 0;
}
