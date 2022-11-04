# LR6
Лабораторная работа №6 Ход выполнения лабораторной работы:

После регистрации на GitHub и установки Git создаётся копия выданного репозитория в личное хранилище (Значек Fork).
Затем настраивается клиент git, вводится имя и email с помощью команд git config --global user.name и git config --global user.email (Рис.1)
![рис.1](https://github.com/Sonchello/_LR_6/blob/otchet/otchet/1.jpg)

 Далее клонируется удаленный репозиторий на компьютер командой git clone <url>(Рис.2)
  ![рис.2](https://github.com/Sonchello/_LR_6/blob/otchet/otchet/2.png)
  
  Добавляем файл через интерфейс GitHub (Рис.3)
  ![рис.3](https://github.com/Sonchello/_LR_6/blob/otchet/otchet/3.png)
  
 При помощи команды git pull продтягиваются изменения в локальный репозиторий(Рис.4)
 ![рис.4](https://github.com/Sonchello/_LR_6/blob/otchet/otchet/4.png)
 
 Истории операций для веток просматриваются при помощи команды git log(Рис.5,Рис.6)
 ![рис.5](https://github.com/Sonchello/_LR_6/blob/otchet/otchet/5.png)
  ![рис.6](https://github.com/Sonchello/_LR_6/blob/otchet/otchet/6.png)
 
 Переключение веток с помощью git checkout (Рис.7)
 
  ![рис.7](https://github.com/Sonchello/_LR_6/blob/otchet/otchet/10.png)
 
 Просмотр последних изменений осуществляется посредством команды git show. Для ветки master (Рис.8) и для branch1  (Рис.9)
 ![рис.8](https://github.com/Sonchello/_LR_6/blob/otchet/otchet/7.png)
  ![рис.9](https://github.com/Sonchello/_LR_6/blob/otchet/otchet/8.png)
   ![рис.10](https://github.com/Sonchello/_LR_6/blob/otchet/otchet/9.png)
 
Выполнение слияния в ветку master происходит с помощью команды git merge <branch> (Рис.10)
  ![рис.11](https://github.com/Sonchello/_LR_6/blob/otchet/otchet/11.png)
 
 Происхдит конфликт
 
 ![рис.12](https://github.com/Sonchello/_LR_6/blob/otchet/otchet/12.png)
 
 Для решения вручную изменяется содержимое файла. Затем применяется команда git add(Рис.11) и git commit(Рис.12).
 ![рис.13](https://github.com/Sonchello/_LR_6/blob/otchet/otchet/13.png)
 
  ![рис.14](https://github.com/Sonchello/_LR_6/blob/otchet/otchet/14.png)
 
 Тогда команда git merge сработает и объединит все в ветку master(рис.13).
  ![рис.15](https://github.com/Sonchello/_LR_6/blob/otchet/otchet/15.png)
 
 После слияния удаляется ветка branch1 командой git branch -d branch1 (Рис.14)
  ![рис.16](https://github.com/Sonchello/_LR_6/blob/otchet/otchet/16.png)
 
 Внесение изменений и их фиксация происходит при помощи изменений в файлах вручную и команд git add и git commit. Первый коммит (Рис.15), второй  (Рис.16)
 
   ![рис.17](https://github.com/Sonchello/_LR_6/blob/otchet/otchet/17.png)
    ![рис.18](https://github.com/Sonchello/_LR_6/blob/otchet/otchet/18.png)
 
 Откат изменений второго коммита производится при помощи команды git reset(Рис.17)
  ![рис.19](https://github.com/Sonchello/_LR_6/blob/otchet/otchet/19.png)
 
 Создание новой ветки для отчета происходит при помощи команды git checkout(рис.18)
 ![рис.20](https://github.com/Sonchello/_LR_6/blob/otchet/otchet/20.png)
 
 Файлы для отчета размещены в папке "for README", которая добавлена в папку "_LR_6". Добавление папки с картинками (Рис.19)
  ![рис.21](https://github.com/Sonchello/_LR_6/blob/otchet/otchet/21.png)
 
 Получение истории операций в форматированном виде производится посредством команды git log(Hис.20)
  ![рис.22](https://github.com/Sonchello/_LR_6/blob/otchet/otchet/22.png)
 
 
 
 
