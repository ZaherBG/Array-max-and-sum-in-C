#include <stdio.h>

int Max(int T[], int L){
	int i = 0;
int max = T[i];
	for(i=0;i<L;i++){
		if(max<T[i]){
			max = T[i];
		}
	}
return max;
}

int Sum(int T[], int L){
	int i = 0;
	int sum = 0;
	while(i<L){
		sum=sum+T[i];
		i++;
	}
return sum;
}

int main(){
	int myA[10] = {10, 15, 25, 35, 7, 28, 17, 20, 43, 50};
	int m = Max(myA, 10);
	printf("the max value is %d", m);
	printf("\n");
	int s = Sum(myA, 10);
        printf("the sum value is %d", s);
	printf("\n");       
	return 0;
}
