# LR6
Лабораторная работа №6
Цель лабораторной работы:
Изучение базовых возможностей системы управления версиями, опыт работы с Git Api, опыт работы с локальным и удаленным репозиторием.
Ход работы:
1) В начале создается аккаунт на GitHub
2) Создаём копию в личное хранилище из https://github.com/Kurtyanik/LR6/ (Fork).
3) Устанавливаем Git
4) Настраиваем клиент Git, вводим (Группа Фамилия И.О.) и email.
  для этого вводим команды:
  git config user.name "<имя>"
  git config user.email "<почта>"
  ![](https://github.com/LorDanielle/LR6/blob/master/Screenshots/1.jpg)
5) Клонируем свой личный удалённый репозиторий на компьютер.  
   для этого вводим команды (перед этим перейдя в католог, где будет репозиторий):  
   git clone <ссылкаНаРепозиторий>  
   ![](https://github.com/LorDanielle/LR6/blob/master/Screenshots/2.png)
6) Добавляем файл через интерфейс GitHub. Подтягиваем изменения в локальный репозиторий.  
  Для подтягивания изменений в локальный репозиторий вводим команду:  
  git pull  
  ![](https://github.com/LorDanielle/LR6/blob/master/Screenshots/3.png)  
  ![](https://github.com/LorDanielle/LR6/blob/master/Screenshots/4.png)  
  ![](https://github.com/LorDanielle/LR6/blob/master/Screenshots/5.png)  
  ![](https://github.com/LorDanielle/LR6/blob/master/Screenshots/6.png)  
7) Получаем историю операций для каждой из веток.  
  Для этого вводим команду:  
  git log  
  ![](https://github.com/LorDanielle/LR6/blob/master/Screenshots/7.png)  
  Для смены ветки вводим команду:  
  git checkout branch1  
  ![](https://github.com/LorDanielle/LR6/blob/master/Screenshots/8.png)  
8) Просматриваем последние изменения.  
  Для этого вводим команду:  
  git log  
  ![](https://github.com/LorDanielle/LR6/blob/master/Screenshots/9.png)  
9) Выполняем слияние в ветку master, разрешив конфликт.  
  Для этого вводим 
