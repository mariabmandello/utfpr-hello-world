# Trabalho 
## Matéria: Introdução a Engenharia de Software

    *Exercício 1071 URI
#include<stdio.h>
int main()

{
    int x, y, i, s=0, t, stop = 0;

    while (stop = 1)
    {
        scanf("%d %d",&x,&y);
        if (x > y)
        {
            t = y;
            y = x;
            x = t;
        }

        if (x < y)
        {
            for (i = x + 1; i < y; i++)
            {
                if (i % 2 != 0)
                    s += i;
            }
            printf("%d\n",s);
        }
        scanf ("%d\n", &stop);
        break;
    }
    return 0;
}
