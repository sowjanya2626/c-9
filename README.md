# c-9
Hollow rhombus pattern
#include<stdio.h>
int main()
{
	int i,j,n,s;
	printf("enter the rows:");
	scanf("%d",&n);
	for(i=1;i<=n;i++){
		for(s=1;s<=n-i;s++){
			printf("  "); 
		}
		for(j=1;j<=(2*i-1);j++){
			if(j==1||j==(2*i-1)){
			printf("* ");
		}else{
			printf("  ");
		}
	}
		printf("\n");
	}
	for(i=n-1;i>=1;i--){
		for(s=1;s<=n-i;s++){
			printf("  ");
		}
		for(j=1;j<=(2*i-1);j++){
			if(j==1||j==(2*i-1)){
				printf("* ");
			}else{
			printf("  ");
		}
	}
	printf("\n");
}
return 0;
}
