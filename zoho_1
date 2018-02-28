#include<stdio.h>

int main()
{
   int org_num,n,num,i=0,j,arr[15],arr_len,ref;
   scanf("%d %d",&org_num,&n);
   num = org_num;
   
   while(num > 0)
   {
       arr[i] = num%10;
       num = num/10;
       i++;
   }
   
   arr_len = i;
   
   for(i=0 ; i<n ; i++)
   {
       ref = arr[arr_len-1];
       for(j=arr_len-2 ; j>=0 ; j--)
       {
           arr[j+1] = arr[j];
       }
       arr[0] = ref;
   }

    for(i=arr_len-1 ; i>=0 ; i--)
    {
        printf("%d",arr[i]);
    }
}
