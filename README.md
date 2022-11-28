# 21.-odev

//hem veri almay�p hem veri d�nd�rmeyen toplama fonksiyonu �rne�i

#include<stdio.h>
void topla1(void);
int main(void)
{
	topla1();
	return 0;
}

void topla1(void)
{
	int i,s,x;
	s=0;
	printf("bir tam sayi giriniz: ");
	scanf("%d" , &x);
	for(i=1;i<=x;i++)
	{
		s=s+i;
	}
	printf("toplam=%d" , s);
}
