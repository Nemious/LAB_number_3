# LAB_number_3
____
__Испольнитель:__
*Вершинина Вероника фт - 220008*
# Игра в шахматы
### Описание
Я создала игру в шахматы на __pycharm__ с помощью __pygame___. Сейчас я в кратце изложу свои шаги.
### Шаг №1:
Для начала вам нужно установить __pygame__ (покажу на примере __pycharm__, так как игру писала на нем). Нажимаете на правую кнопку мыши на иконку __"File"__ и зайти в __“Settings“__. 
Затем вы можете увидеть на скриншоте __"+"__. Нажимаете на него. 

![image](https://github.com/Nemious/LAB_number_3/assets/146121558/8dd74c0b-a76e-4a1f-a9bc-61f08617caef)

Перед вами поисковая строка. Пишите __"pygame"__ и выбираете его, нажимаете на __"Install Package"__.

![image](https://github.com/Nemious/LAB_number_3/blob/master/images/2.png?raw=true)

Чтобы запустить работу в __pygame__ , нужно сделать кое-что ещё. А именно, импортировать его в сам проект и код вручную.

![image](https://github.com/Nemious/LAB_number_3/blob/master/images/3.png?raw=true)

### Шаг №2:
Далее переходим к самой разработке. В начале я сделала необходимое мне по размерам окошко, где будет сама игра, также ввела данные на размер слов 
(так проще потом вписывать нужно строчки, поэтому я разделила на medium и big). Кроме того, добавила фпс и разметку фигур. 

![image](https://github.com/Nemious/LAB_number_3/blob/master/images/5.png?raw=true)

### Шаг №2:
Теперь загрузка иконок фигур из папки. Папку с ними я создала в самом проекте, указала путь.

![image](https://github.com/Nemious/LAB_number_3/blob/master/images/6.png?raw=true)

### Шаг №3:
Создала функцию для доски (текст, который видит пользователь), фигур, окончания игры, траекторий и остального

![image](https://github.com/Nemious/LAB_number_3/blob/master/images/7.png?raw=true)

### Шаг №4:
Прописала сам цикл игры (запуск, окончание)

![image](https://github.com/Nemious/LAB_number_3/blob/master/images/8.png?raw=true)

![image](https://github.com/Nemious/LAB_number_3/blob/master/images/9.png?raw=true)

![image](https://github.com/Nemious/LAB_number_3/blob/master/images/10.png?raw=true)

### Шаг №5:
Окончание самого окна __pygame__

![image](https://github.com/Nemious/LAB_number_3/blob/master/images/4.png?raw=true)

### Тест:
__1)__ Начало игры

![image](https://github.com/Nemious/LAB_number_3/blob/master/images/%D1%82%D0%B5%D1%81%D1%82%201.png?raw=true)

__2)__ В случае, если нажать на кнопку __"Сдаюсь"__

Белые сдаються:

![image](https://github.com/Nemious/LAB_number_3/blob/master/images/%D1%82%D0%B5%D1%81%D1%82%202.png?raw=true)

Черные сдаються:

![image](https://github.com/Nemious/LAB_number_3/blob/master/images/%D1%82%D0%B5%D1%81%D1%82%202.1.png?raw=true)

__3)__ Траектория ходов

![image](https://github.com/Nemious/LAB_number_3/blob/master/images/%D1%82%D0%B5%D1%81%D1%82%203.png?raw=true)
![image](https://github.com/Nemious/LAB_number_3/blob/master/images/%D1%82%D0%B5%D1%81%D1%82%204.png?raw=true)

__4)__ В случае угрозы королю

Белые:

![image](https://github.com/Nemious/LAB_number_3/blob/master/images/%D1%82%D0%B5%D1%81%D1%82%206.png?raw=true)

Черные:

![image](https://github.com/Nemious/LAB_number_3/blob/master/images/%D1%82%D0%B5%D1%81%D1%82%207.png?raw=true)

__5)__ В правом столбце отображаются "съеденные" фигуры

![image](https://github.com/Nemious/LAB_number_3/blob/master/images/%D1%82%D0%B5%D1%81%D1%82%208.png?raw=true)

### Запуск:
Запустить игру можно через __pygame__ (инструкция описана в первом шаге) 


