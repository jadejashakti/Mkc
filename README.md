#include <stdio.h>


int main() {
    int fno1,ad1,fno2;
    
 printf("you can know about any one at a time if you need to know more than just press run or play button\n\n\n\n\n");
    
    
printf("enter 1 if you want to know about admin \n enter 2 if you wanna know about members\n");
printf("Enter number:\n"); scanf("%d",&fno1);
    
switch(fno1){
        
 case 1:
        printf("you have entered 1 admin\n");
         printf("there are three admin in gc\n");
         printf("1.kunth\n 2.ichigo \n3.krix\n");
         printf("enter any number from above to get information about admin \n:");
         scanf("%d",&ad1);
         
switch(ad1){
             
    case 1:
             printf("you have entered 1 kunth\n");
             printf("kunth is owner of the gc\n he is 15 years old\n he is from rajsthan\n ");
             
             break;
             
     case 2:
             printf("you have entered 2 ichigo\n");
             printf("ichigo is admin of the gc\n he is 18 years old\n he is from Gujarat\n ");
             
             break;
      case 3:
            printf("you have entered 3 krix\n");
             printf("krix is admin of the gc\n he is 22 years old\n he is from delhi\n");
             
             break;
             default:
             printf("please enter valid number\n");
             
             break;
     }
         
    break;
             
         
         
  case 2:
       printf("you have entered 2 members\n");
       printf("there are many members in gc\n 1.shaktisinh\n 2.ayush\n 3.bhavya\n");
       printf("enter number to get information:\n");
       scanf("%d",&fno2);
          
switch(fno2){
              
           case 1:
           printf("you have entered 1 Shaktisinh\n");
           printf("Shaktisinh is the first memeber of the gc\n he is 18 years old \n he is from Gujarat");
           break;
        
          case 2:
           printf("you have entered 2 ayush\n");
           printf("ayush is the second memeber of the gc\n he is 15 years old \n he is from rajsthan");
           break;
              
          case 3:
           printf("you have entered 3 bhavya\n");
           printf("bhvya is  memeber of the gc\n he is 22 years old \n he is from Maharashtra");
           break;
           default:
       printf("please enter valid number");
       break;
              
          }
       
       break;

       default:
       printf("please enter valid number");
       break;
  }
}

