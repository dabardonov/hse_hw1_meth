# hse_hw1_meth

## Colab
https://github.com/dabardonov/hse_hw1_meth/blob/main/HW1_meth.ipynb

## Сравнение отчетов FastQC для бисульфитного секвенирования и РНК

| Параметр | Бисульфитное секвенирование | РНК | Комментарий |
| ------------- | ------------- |--------------------| ----- |
|Per base sequence content| ![image](https://user-images.githubusercontent.com/93095449/154854645-3bb705b6-f7b0-4bdd-9c7d-d2f74b447822.png)   | ![image](https://user-images.githubusercontent.com/93095449/154854677-ccfb2f18-69f9-46ab-8c75-6ff79899764e.png)    | В РНК содержание всех нуклеотидов примерно одинаковое, тогда как в BS-seq заметно больше тимин и заметно меньше цитозина (что не удивительно, учитывая трансформация неметилированных цитозинов в тимин в ходе BS-seq) |
| Per sequence GC content | ![image](https://user-images.githubusercontent.com/93095449/154854737-a6163b89-c9f1-4926-aad1-c75470f3f692.png)  | ![image](https://user-images.githubusercontent.com/93095449/154854816-bb8517fb-0f89-48c1-8833-611d9a097d6c.png) | Содержание GC в BS-seq заметно отличается от нормального (хотя бы наличием двух пиков); в РНК примерно в два раза больше GC   |
