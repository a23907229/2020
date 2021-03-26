##反序數字
#include <stdio.h>
int f(int n)
{
	int p;
	int m=0;
	
	while(n>0)
	{
		p=n%10;
		n=n/10;
		m=p+m*10;
	}
	return m;
}
int main()
{
	int n,m;
	scanf("%d", &n);
	printf("%d+%d=%d\n", n, f(m), n+f(m));




}
##絕對值函數
#include <stdio.h>
int f(int n)
{
	
	if(n<0)
		return -n;
	else 
		return n;
	

}


int main(void)
{
	int n;
	scanf("%d",&n);
	printf("[%d]",f(n));
	return 0;
}
##N數之和
#include <stdio.h>
int main()
{
	int a[10];
	int n;
	scanf("%d", &n);
	int b;
	for (int i=0; i<n; i++){
		scanf("%d", &a[i]);
		b=b+a[i];
	}

	printf("%d\n", b-n);
	
}
##三數極大
#include <stdio.h>
int main()
{
	int a, b , c;
	scanf("%d%d%d", &a, &b, &c);
	
	if(a>b && a>c)printf("%d", a);
	else if(b>a && b>c)printf("%d", b);
	else if(c>a && c>b)printf("%d", c);
	printf("\n");

}
##計算商數
#include <stdio.h>
int main()
{
	int a, b;
	scanf("%d%d", &a, &b);
	
	printf("%d", a/b);
	printf("\n");



}
