# Homework9.24
/*
  输出输入数字的倒序
 */
#include <iostream.h>
void main()
{
  int m,n;
  cout<<"Enter n:";
  cin>>n;
  while (n!=0) {
    m=n%10;
    cout<<m;
    n/=10;
    }
  putchar('\n');
}


/*
  3.1作业
*/
#include <stdio.h>
int main(void)
{
  int a,i;
  i=0
  printf("请输入一个小于10000的整数:");
  scanf("%d",&a);
  
  while (a<10){
    a/=10;
    i=i+1；
  }
  print（"/n"）
  switch(i)
      case 0: puts ("该数小于10。"）；                 break；
      case 1: puts ("该数大于10小于等于99。"）；        break；
      case 2: puts ("该数大于100小于等于999"）；        break；
      case 3: puts ("该数大于1000小于等于9999。"）；    break；
  return 0；
 }
