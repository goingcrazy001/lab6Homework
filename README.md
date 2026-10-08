# Домашнее задание к работе 6
## Условие задачи
1. Две окружности заданы координатами своих центров и радиусами. Определить, пересекаются ли они.
2. Составить программу, которая проверяет принадлежит ли заданная пользователем точка с координатами (х, у) заданным закрашенным (заштрихованным) областям, показанным на рисунках в табл., и выводит на экран сообщение.
<img width="384" height="372" alt="image" src="https://github.com/user-attachments/assets/b959f73d-e709-4e94-a433-2d357174569b" />

## Алгоритм и блок-схема
### Задание 1
### Алгоритм
1. Начало
2. Ввести значение переменных `x1`, `y1`, `r1`, `x2`, `y2`, `r2`.
3. Вычислить значение `d=sqrt((x2 - x1) * (x2 - x1) + (y2 - y1) * (y2 - y1))`
4. Проверка условий пересечения: `d <= r1 + r2 && d >= fabs(r1 - r2))`
5. Вывод результата
6. Конец
### Блок-схема
<img width="687" height="854" alt="image" src="https://github.com/user-attachments/assets/0ee86731-64b7-4019-925d-8e4604d89dc2" />
[Ссылка на блок-схему](https://viewer.diagrams.net/?tags=%7B%7D&lightbox=1&highlight=0000ff&edit=_blank&layers=1&nav=1&dark=auto#R%3Cmxfile%3E%3Cdiagram%20name%3D%22Page-1%22%20id%3D%220%22%3E7Vpbj5s4FP41kdKVEnEnPOba3WpajXa62vZp5QGHsAXMGGeS9NevbQzYQC5lMjNttyONsY8v2N853%2FGxycCcJ%2Fu3GGSb9yiA8cDQgv3AXAwMQ%2Fcskz6Y5FBIDNOyCkmIo0C0qgV30VcohJqQbqMA5kpDglBMokwV%2BihNoU8UGcAY7dRmaxSrb81ACFuCOx%2FEbenfUUA2hXRiuLX8dxiFm%2FLNuuMVNQkoG4uV5BsQoJ0kMpcDc44RIkUu2c9hzNArcSn6rY7UVhPDMCWXdMgJwKTdSYyTk0O5ZNqNoksLs90mIvAuAz6r2VENU9mGJDEt6TS7juJ4jmKEeT9zPfGh71N5TjD6UsFlsJYoJSuQRDEzg49RQjVqaB%2FgjqZ%2FogSktEkxjUcQb8U0Bgtt4C14qrF06tZ5b8bTpegEMYF7aTkCgLcQJZDgA22ykXQ0EQrZ1frUHSETo5il%2BQmzHZmaEABhT2E1dg05zQjUuzUQpdn2Ig1QU8lYlrYCcQxjFGKQUIwyiCl2BOJm3W1d8Y1KC2w4CaxOpeUFGbWxbpqaY9m6oxueZhqGTSsx2qYBZAvTaAnEUUiVuPDpovgkeinccGIKySyIHhU4nIct48hMyYXiyXvkGR2xqwvHYpQzMEY%2BimPA7XrKFIBhDvEjPDkuW0XnuKxiVODDBjP0bN850J7qds7MSDyxeO4NIRdPXC2e2lDxVnUmVFwssiXmaJXSHmzw2mwwNVthg2G6Y1vlg25fgQ8wDX40fzQVfqf2TTb3TU4v7F277Ykmpz2Ra14DeAEyDFqbX1sRaIv90i%2FVW4ikn4vBpL1DSBq%2BsI0QhjEg0aM6s6csdzPf3Pzlz2%2F%2F8T6O0tsP1ujm3Wpk9oMgzOarmRN8cjZ%2FeNk703uY6w%2BjDpulw96JIsJkg0KUgnhZSxsOtG5zg1Am7PlfSMhBhERgS5Bq7W1MO9epd%2FjZ10O9tOafHnb3%2B4K9J%2BF%2FONgnrwX7KaTOBHut3UladhkJJvuQHbDG6xjt%2FA31wuMA%2BlEeofTIttjYC%2FV7oMNy55P3SP5X7ZFSjaY5y%2BnqVJxGQ6gjAdMa%2BGq81LUrSMHS%2BQhLn4gIix70%2BBSZMGY76SgA%2BMsQh%2FdDw3KLaMpgp06ese03IsBi9bZdiev6N52BGw1MqKdyQMKwLEItNjsewNGKmYjZtHLh91iCouhVpO1iq72mvCysX7YG9%2FmQv3HE30fnejZKVJTSIyQxtHY8aJhqTFLFLeWh3rhCTNJJZ6Of2zq1Eb6225IOgd%2FL5nCJl1KR%2BLZAHOr0lOl2ORnPcU3gnHIylx7BdO%2FIEYxNOX%2FAZDhkhy7OpL1OiaT9Rv%2BbsoLZw0MpPdQtZdlxHvZgnG52Ma46cVWc08dGg3bPxTr7EoOgSySq1ruMQtV4ilLYMA8hal0gMBAjH8RTUZFEQdBByeezG364s8SV0xXV3aHtxuVTdRlV6tl9LkU7vxQtFC2f5Y%2FfxTyLum33pdTtXqLu13L0PHA5psa1uF6YypGSaDAHuQ%2BCCNCq9yhFzeoixGoYg5f1vFB8megzw1FK1kOporp1mk0HFPmJxlOTSxyecgueLblc5ym%2FsZpNGGQss%2BKpXXav8nqZLwanaTH4shykGnA1sOdS3C7vgkcuJ58ajXZcTra8pcoey3ku9kx%2Bsed%2FzJ6FYMlPRqbGbbNtvBSb9J73r6c2NvlolwZT9vWXRRoxyPPIV6mn8hTuI%2FKJ5ce2KH0W7Vh%2BsZeaLQ5lIaUwiE6WXgo%2Bc4FmTUpB3ZmXlN7SVzspxpEPi9UXkrNHRVnR5beZzuOjpH1bVf5IG%2BuWYx1XOH8rhRUcpAYZomzLpUndMoHkn63GBwyt8Zm60b4y0%2B72NFPM4EjvRuzsWg0DLmxJ9DoxDcvsnkY1UKGm1kCcDJVensAP64r8mLwyPxR2nGHGa5HgagbvNE3wjMHbRyztMoN3GvGP4%2FU0%2BOa0nSZzehs8Lda%2Fcima1z8WMpf%2FAQ%3D%3D%3C%2Fdiagram%3E%3C%2Fmxfile%3E)
### Задание 2
### Алгоритм
1. Начало
2. Ввести значение переменных `x`, `y`.
3. Проверка условий принадлежности: `y <= 0 && y >= 1.5 * x - 6 && y >= -1.5 * x - 6`
4. Вывод результата
5. Конец
### Блок-схема

[Ссылка на блок-схему](https://viewer.diagrams.net/?tags=%7B%7D&lightbox=1&highlight=0000ff&edit=_blank&layers=1&nav=1&dark=auto#R%3Cmxfile%3E%3Cdiagram%20name%3D%22Page-1%22%20id%3D%220%22%3E7Vrtb9soGP9rIrUnJbLxW%2FyxSdrdTdtUXXe67dOJ2cTxzTEuJk2yv%2F4Agw22k2VeumynViqGh4cHeN74GWfkzNe7VwQWq7c4RtkIWPFu5CxGANiWY7EHp%2BwlJQhBRUlIGktaQ3hIvyA1VFI3aYxKg5FinNG0MIkRznMUUYMGCcFbk22JM3PWAiaoQ3iIYNal%2Fp3GdFVRpyBo6L%2BjNFmpmW0%2FrHrWUDHLnZQrGOOtRnJuR86cYEyr2no3RxnXntJLNe7uQG%2B9MIJyesqAkkJCu4OknJLu1ZbZMKZd1phtVylFDwWMeM%2BWWZjRVnSdsZbNqss0y%2BY4w0SMc5bTCEURo5eU4M%2B1ugDnxDm9g%2Bs0427wPl0ziwLrHdqy8k%2B8hjljqZbxBLONXMZoYY3ChSgtXt4ETT2cifJWDkKEop22HamAVwivESV7xrLSbDSVBtk29rR9SZNSHOV%2B0m3HjiUJUPpTUstuVM4qUuv9FkjzYnOSBZirFLzKuGCWoQwnBK6ZjgpEmO4oIu2%2B%2B6bjG40We2gau71GK6tgtCa241i%2B69m%2BDULLAcBjnQRv8hjxjVmsBbM0YUZcRGxTYhGDDA78jKlkFqdPhjr8xw2PkZlRS%2BRTjCgLJrFviNDFuOTKGEc4y6Dw6xtuAIJKRJ7QUbl8F71yece40g8XBuxi1ytox2w7524kn0Q%2Bd0DS5ZPUm2c%2BVM1qroSRq012yEJbijogGsJuNDiWZ0QDcIKJZ8aD7Z0hHlAe%2F2r56EbmnSY3eSI3%2BYN0H3jdTDQ9nol8%2FxyKl0pGcefw6xoCb0ik8lJzhGj2OVmZbHSCaCsXdjVEUAZp%2BmSu7Hu2u5qv3vwVze%2F%2FCd%2BP8%2Ft37vjN67uxM0wFSTG%2Fm%2FnxB3%2F1R1i8dsLHuf047vFZJvZBNjGhK5zgHGa3DbWVQBueNxgX0p%2F%2FRZTuJSSCG4pNb%2B%2FqtHefdk%2BevZzWlTf%2F79Ue%2FFxqHxjwv5zap5dS%2BzFNfQXsdU4nbdsKCa53CX%2FBmiwzvI1WLAtPYhSlZYrzA8di6yy0P0EbqZNPPyPFX31Gaj2W5d%2Fe3B3DaQxCtfGIIB3CS0t5RnDExLrgmq9TMsxhGcE4hazrLc5xu3sY%2Bouq3fD5Mn7ojmNIPl%2BR5NOVVcEu9biWKIz1AE8S9cr19Vlgou0cgIl7XSMVsONi%2BPosNcknok1bcVZlt9nht4wJkmYCm%2BM66zcBN4A1Zv%2F%2Bc0857p1zIPjtccE2dQAsA1YXEwPHxGU1dpO4rL6wOHvuBsNS9zEwcOnUrb0I%2FywH5CmZ2tTEt72MIJu9aQd9iTb0Awf6xxLtyfklPJBf%2BJLLR0KvrviLp4i5nX0to7BNGwEevld7Rd03nDrt%2BmDQDog42%2BmLuPqts445ewJaYfdcUeed4hBsi9S0ep9TmBbPcY5a7iFJnUsUrsQ0gtmN7FincdwTks%2FnN%2BIF15XXbmc0d4%2B1Wxdw9YWcsnPwXIb2XwwtDa3fZxy%2Bj3oWc3vBjzJ3cIq5L5XoLwKffxXMDtxAAnLXUcjcM5C7V5Ob%2FvMg90NxU5A0p8srraMKHlbObkfMPabio8VMXBvOOJxnvN4ELIUMXqmPUQM8C%2FY7IaCqT0W5kGJ4KdLyTEw4EzE78xUnGwWUkEANYUTVZYhldU%2Btl5VAm2KhlVVvqMRWTVtbQzWFraYQwhmzN891tc0r2C%2Fuvg8jiMvA%2Fp6b8M6xZKYp9xyXscfuMV7S1Eua%2Bpbz3bpAnqpxw0va%2BmnSVusjkgd%2BVN6yB35WOYbV9NuKPL7hP%2Brg4DmDZZlGZpIzMyLapfQDr0882foo%2BXh9sdPYFnvVyJka5CDXVoSPgmC5U0VoBouWMVr7GK%2FBdv3%2Bo%2F7w%2BdXbD93Q6pNr742IZn3PNP7Ymtiu7x42uJiVqRXuNYYCs4xRaou65wTtJHT7v0s2zlNJ7B8NWq93gdtyyMo35KhGbEeQ67QEtX%2BnUam9I0g4d63n7%2FB394z%2BPr2wvxve%2FhVPv5RTn82Bff%2BoA3f4ve9yeL%2F9GT8c6PCdZbcjZ7DDs2bzY7SKvflNn3P7Hw%3D%3D%3C%2Fdiagram%3E%3C%2Fmxfile%3E)
## Реализация программы
Программа написана на языке C++
```ccp
#include <stdio.h>
#include <math.h>
#include <locale.h>
int main()
{

}
int zadanie1()
{
    setlocale(LC_ALL, "RUS");

    double x1, y1, r1, x2, y2, r2, d;

    // ввод данных
    printf("Введите координаты центра первой окружности: ");
    scanf("%lf %lf", &x1, &y1);
    printf("Введите радиус первой окружности: ");
    scanf("%lf", &r1);
    printf("Введите координаты центра второй окружности: ");
    scanf("%lf %lf", &x2, &y2);
    printf("Введите радиус второй окружности: ");
    scanf("%lf", &r2);
    d = sqrt((x2 - x1) * (x2 - x1) + (y2 - y1) * (y2 - y1)); // расстояние между центрами окружностей

    if (d <= r1 + r2 && d >= fabs(r1 - r2))                // первое выражение проверяет далеко ли находится одна окружность от другой, 
        //второе - находится ли одна окружность внутри другой
        printf("Окружности пересекаются\n");
    else
        printf("Окружности не пересекаются\n");

    return 0;
}
int zadanie2()
{
    setlocale(LC_ALL, "RUS");
    double x, y;
    printf("Введите координату x: ");
    scanf("%lf", &x);
    printf("Введите координату y: ");
    scanf("%lf", &y);
    if (y <= 0 && y >= 1.5 * x - 6 && y >= -1.5 * x - 6)
    {
        printf("Точка (%.2f;%.2f) принадлежит заштрихованной области \n", x, y);
    }
    else {
        printf("Точка (%.2f;%.2f) НЕ принадлежит заштрихованной области \n", x, y);
    }
    return 1;
}
```
## Результат работы программы
```
Введите координаты центра первой окружности: 2 3
Введите радиус первой окружности: 5
Введите координаты центра второй окружности: 1 1
Введите радиус второй окружности: 3
Окружности пересекаются
```

```
Введите координату x: -2
Введите координату y: -3
Точка (-2,00;-3,00) принадлежит заштрихованной области
```
## Информация о разработчике
```
Имя: Харитонов Дмитрий Олегович
Группа: бИЦТ-261
Вариант: 28
