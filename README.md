# hse_hw1_meth

## Colab
https://github.com/dabardonov/hse_hw1_meth/blob/main/HW1_meth.ipynb

## Сравнение отчетов FastQC для бисульфитного секвенирования и РНК

| Параметр | Бисульфитное секвенирование | РНК | Комментарий |
| ------------- | ------------- |--------------------| ----- |
|Per base sequence content| ![image](https://user-images.githubusercontent.com/93095449/154854645-3bb705b6-f7b0-4bdd-9c7d-d2f74b447822.png)   | ![image](https://user-images.githubusercontent.com/93095449/154854677-ccfb2f18-69f9-46ab-8c75-6ff79899764e.png)    | В РНК содержание всех нуклеотидов примерно одинаковое, тогда как в BS-seq заметно больше тимин и заметно меньше цитозина (что не удивительно, учитывая трансформацию неметилированных цитозинов в тимин в ходе BS-seq) |
| Per sequence GC content | ![image](https://user-images.githubusercontent.com/93095449/154854737-a6163b89-c9f1-4926-aad1-c75470f3f692.png)  | ![image](https://user-images.githubusercontent.com/93095449/154854816-bb8517fb-0f89-48c1-8833-611d9a097d6c.png) | Содержание GC в BS-seq заметно отличается от нормального (хотя бы наличием двух пиков); в РНК примерно в два раза больше GC   |

## Количество ридов и степень дедупликации

| Стадия развития\Регион | 11347700-11367700 | 40185800-40195800 | Степень дедупликации |
| ------------- | ------------- |--------------------| ----- |
| 8_cell | 1090 | 464 | 81.69% |
| Epiblast | 2328 | 1062 | 97.08% |
| ICM | 1456 | 630 | 90.92% |

## M-bias plots

| Стадия развития| Скриншот 1 | Скриншот 2 | Комментарий |
| ------------- | ------------- |--------------------| ----- |
| 8_cell | ![image](https://user-images.githubusercontent.com/93095449/155022941-856e5d8e-3574-40b1-ba2c-aa864846d95e.png) | ![image](https://user-images.githubusercontent.com/93095449/155022977-73eab6e1-b097-41ac-b355-16c509e0e41f.png) | |
| ICM | ![image](https://user-images.githubusercontent.com/93095449/155023097-0662392c-023e-4ba2-a0a6-ab7e35964891.png) | ![image](https://user-images.githubusercontent.com/93095449/155023139-318480d8-d927-45fa-b0b4-38994ace0614.png) | |
| Epiblast | ![image](https://user-images.githubusercontent.com/93095449/155023213-f36c68c2-eb3e-4acb-b58b-33862a650e54.png) | ![image](https://user-images.githubusercontent.com/93095449/155023251-9870006c-3c80-4334-a8c1-86e54628fbbc.png) | |

## Распределение метилирования цитозинов

| Стадия развития| Гистограмма |
| ------------- | ------------- |
| 8_cell | ![](img/8 cell.png) |
| ICM | ![](img/ICM.png) |
| Epiblast | ![](img/epi.png) |

Вывод: на стадии 8_cell доли неметилированных и полностью метилированных цитозинов примерно равны, на стадии ICM большинство цитозинов совсем не метилированы, на стадии Epiblast большая часть цитозинов 100% метилированы. Эти результаты сходятся с полученными из M-bias plots/





