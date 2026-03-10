# Anastasia Galkovskaya 
![photo]("E:\web\foto.jpg") 

## Content 
- [Contacts](#Contacts)
- [About me](#About-me) 
- [Skills](#Skills) 
- [Code Example](#Code-Example)
- [Experience ](#Experience)
- [Courses](#Courses)
- [English](#English)
---
## Contacts 
- **Phone:** [+1234567890](tel: +1234567890)
- **Email:** [anastasia@gmail.com](mailto:anastasia@gmail.com)
- **instagram:** [@blum.chick](https://www.instagram.com/blum.chick/ )

---
## About me
I am a student at the Belarusian-Russian University, studying in the PMR-241 group. In the future, I want to become a good specialist.
--- 
## Skills
1.Python 
2.HTML 
--- 
## Code Example 
``` 
#define _CRT_SECURE_NO_WARNINGS
        #include &ltstdio.h&lt
        #include &ltstdlib.h&lt
        #define SIZE 6
        int main()
        {
        int a[SIZE][SIZE]; // матрица связей
        int d[SIZE]; // минимальное расстояние
        int v[SIZE]; // посещенные вершины
        int temp, minindex, min;
        int begin_index = 0;
        system("chcp 1251");
        system("cls");
        // Инициализация матрицы связей
        for (int i = 0; i &lt SIZE; i++)
        {
            a[i][i] = 0;
            for (int j = i + 1; j &lt SIZE; j++) {
            printf("Введите расстояние %d - %d: ", i + 1, j + 1);
            scanf("%d", &temp);
            a[i][j] = temp;
            a[j][i] = temp;
            }
        }
        // Вывод матрицы связей
        for (int i = 0; i &lt SIZE; i++)
        {
            for (int j = 0; j &lt SIZE; j++)
            printf("%5d ", a[i][j]);
            printf("\n");
        }
        //Инициализация вершин и расстояний
        for (int i = 0; i &lt SIZE; i++)
        {
            d[i] = 10000;
            v[i] = 1;
        }
        return 0;
        }
```
---
## Experience 
* course work in discrete mathematics 
     * Skills:Python, solving examples 
* coursework on differential equations 
    * Skills:solving examples
--- 
_Copyright by Galkovskaya Anastasia_
