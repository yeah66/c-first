# c-first
c语言初级学习
#inculde<stdio.h>

int main（）
{
    printf（"hello world\n");
    return 0;

}
第一天学习c语言，感受到计算机的魅力
main 主函数 程序的入口 （必须有main函数）入口 只有一个main函数
框架#inculde<stdio.h>    std -标准 standard input output 

         int main （）       int整形的意思     main前面的int表示main函数调用之后返回一个整型                     void mian （）过时的写法
       {
                  这里完成任务
                  屏幕上打出hello world
                  函数 printf         print- function 打印函数
                  库函数c语言本身提供给我们使用的函数
                  别人的东西-打招呼 ---- #inculde<stdio.h>
                   printf("hello cyuyan\n“）；
                   return 0;      返回0
        }
数据类型 
char  字符数据类型  char ch=‘A’ 内存 存字符A
                   printf("%c\n",ch);    %c--打印字符格式的数据
short 短整型
int     整形      int age=20;
                  printf("%d\n",age);    %d--打印整形十进制数据
long 长整型
longlong 更长的整形
float  单精度浮点数
double 双精度浮点数
