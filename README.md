# Data-Structure-CSA0316-
sum of matrix
~~~
//Addition of two Matrics
#include<stdio.h>
int main(){
	printf("Name: Philip Gracian Sanova\nReg no: 192324023\n");
	int r,c,i,j;
	printf("Enter the rows and columns of the Matrices:");
	scanf("%d %d",&r,&c);
	
	printf("\nEnter the elements of Matrix 1:\n");
	int mat1[r][c];
	for(i=0;i<r;i++){
		for(j=0;j<c;j++)
		scanf("%d",&mat1[i][j]);
	}
	printf("\nEnter the elements of Matrix 2:\n");
	int mat2[r][c];
	for(i=0;i<r;i++){
		for(j=0;j<c;j++)
		scanf("%d",&mat2[i][j]);
	}
	int mat3[r][c];
	for(i=0;i<r;i++){
		for(j=0;j<c;j++)
		mat3[i][j]=mat1[i][j]+mat2[i][j];
	}
	printf("\nThe sum of the two matrices is \n");
	for(i=0;i<r;i++){
		for(j=0;j<c;j++){
			printf("%d  ",mat3[i][j]);
		}
		printf("\n");
	}
	return 0;
}
~~~
![Screenshot (1)](https://github.com/DivyaDhAA/Data-Structure-CSA0316-/assets/154417160/d6d55d7e-59fe-48ac-82e9-7c44ee202da3)
