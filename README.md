# else-if
年龄代表的人生阶段
#define _CRT_SECURE_NO_WARNINGS
#include<stdio.h>
int main()
{
	int A;
	printf("请输入年龄\n");
	scanf("%d", &A);
	if (A < 18)
		printf("未成年人\n");
	else if (A >= 18 && A < 28)
		printf("青年人\n");
	else if (A >= 28 && A < 50)
		printf("壮年\n");
	else if (A >= 50 && A < 100)
		printf("老年人\n");
	else if (A >= 100)
		printf("长寿人\n");
}
