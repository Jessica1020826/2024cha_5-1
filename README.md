# 2024cha_5-1
  #include <stdio.h>
int area(int h,int w){
    return h * w;
}

int main()
{
    int h,w;
    printf("please input int h:\n");
    scanf("%d",&h);
    printf("please input int w:\n");
    scanf("%d",&w);
    printf("area = %d\n", area(h,w));
    return 0;
}
