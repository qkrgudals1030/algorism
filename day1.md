백준 문제 풀이(입출력과 사칙연산)

1. Hello World!를 출력하시오.
~~~c
#include<stdio.h>

int main()
{
    printf("Hello World!");
        
    return 0;
}
~~~
2. 대회를 뜰 줄 모르는 지박령 kriii를 위해서 격려의 문구를 출력해주자.
~~~c
#include<stdio.h>

int main()
{
    printf("강한친구 대한육군\n");
    printf("강한친구 대한육군\n");
    
    return 0;
}
~~~
3. 고양이를 출력한다.
 ~~~c
 #include<stdio.h>
 int main()
 {
     printf("\\    /\\\n");
     printf(" )  ( ')\n");
     printf("(  /  )\n");
     printf(" \\(__)|\n");
   
     return 0;
 }
 ~~~
 4. 개를 출력하시오.
~~~c
#include<stdio.h>
int main()
{
    printf("|\\_/|\n");
    printf("|q p|   /}\n");
    printf("( 0 )\"\"\"\\\n");
    printf("|\"^\"`    |\n");
    printf("||_/=\\\\__|\n");

    return 0;
}
~~~
5. 두 정수 A와 B를 입력받은 다음, A+B를 출력하는 프로그램을 작성하시오.

~~~c
#include<stdio.h>
int main()
{
    int a, b;
    scanf("%d %d", &a, &b);
    printf("%d", a+b);
 
    return 0;
}
~~~
