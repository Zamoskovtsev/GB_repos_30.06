# **Инструкция для работы с GIT**  с изменениями

* **git init** – инициализация локального репозитория
* **git status** – получить информацию от git о его текущем состоянии
* **git add .**– добавить все файлы папки или файлы к следующему    коммиту
* **git add имя файла с расширением** - добавить файл
* **git commit -m "Комментарий"** - зафиксировать версию файла lf
* **git log** – вывод на экран истории всех коммитов с их хэш тегами
* **git checkout** – переход от одного коммита к другому
* **git checkout master** – вернуться к актуальному состоянию и продолжить работу
* **git diff** – увидеть разницу между текущим файлом и закоммиченным файлом
*  **git clone** - Клонирование репозитория в новый каталог
*  **git mv** - Переместить или переименовать файл, каталог или симлинк
*  **git restore** - Восстановить файлы рабочего дерева
*  **git rm** - Удалить файлы из рабочего дерева и из индекса
*  **git bisect** - Используйте двоичный поиск, чтобы найти коммит, в котором появилась ошибка.
*  **git grep** - Вывести строки, соответствующие шаблону
*  **git show** - Показать различные типы объектов
*  **git branch** - Выводить на экран, создавать или удалять дополнительные ветви и не только
*  **git merge** - Объединить две или более истории разработки вместе
*  **git rebase** - Переназначить коммиты поверх другой базовой вершины
*  **git reset** - Сбросить текущий HEAD в указанное состояние
*  **git switch** - Переключить ветки
*  **git tag** - Создать, перечислить, удалить или проверить объект тега, подписанный GPG
*  **git fetch** - Загружать объекты и ссылки из другого хранилища
*  **git pull** - Получить из другого репозитория или локальной ветки и интегрировать с ним
*  **git push** - Обновление удаленных ссылок вместе с соответствующими объектами
*  **git clone** - клонирование удаленного репозитория к себе.

# **Параграфы и разрывы строк (paragraphs and line breaks)**

Чтобы поделить текст на параграфы, между ними нужно оставить пустую строку. Строка считается пустой, даже если в ней есть пробелы и табуляции. Если же строки находятся рядом, то они автоматически склеиваются в одну.

Для переноса строки внутри одного параграфа есть три метода:

поставить в конце строки два или больше пробела   
поставить в конце строки обратную косую черту \
использовать HTML-тег <br>

# Заголовок первого уровня
## Заголовок второго уровня ##
### Заголовок третьего уровня
#### Заголовок четвёртого уровня #
##### Заголовок пятого уровня ############
###### Заголовок шестого уровня
# Выделение текста 
*Текст курсивом*   -обрамить текст звездочками **  
# Выделение текста
*Текст курсивом*   курсив это красиво звездами или _  
_Текст курсивом_  
**Текст жирным**  - выделения текста жирным в двойную **   
***Текст жирным курсивом***   
___Текст жирным курсивом___    
~~Зачёркнутый текст~~    
<u>Подчёркнутый текст</u> фиг знает но работает

<u>Подчёркнутый текст</u> заключаев в фиг знает что, но работает
# Цитаты   
> Оформление цитатой
последовательных строк
внутри одного параграфа  
> # Заголовок
> Первый параграф
>
> Второй параграф
>
> > Вложенная цитата
> > > Цитата третьего уровня
>
> Продолжение основной цитаты   
1. Первый пункт
2. Второй пункт
3. Третий пункт

# Нумерованные списки
1. Первый пункт
2. Второй пункт
3. Третий пункт


1. Первый пункт
1. Второй пункт
1. Третий пункт


1. Первый пункт
73. Второй пункт
5. Третий пункт
# Не нумерованные списки
* Первый пункт
* Второй пункт
* Третий пункт
- Первый пункт
- Второй пункт
- Третий пункт
+ Первый пункт
+ Второй пункт
+ Третий пункт
# Чекбоксы
- [x] Отмеченный пункт
- [ ] Неотмеченный пункт
# Вложения
1. Пункт
	1. Подпункт
		1. Подподпункт

- Пункт
	- Подпункт
		- Подподпункт


1. Пункт
	- Подпункт
		* Подподпункт

+ Пункт
	1. Подпункт

- Пункт
  - [x] Отмеченный подпункт
  - [ ] Неотмеченный подпункт
    1. Подподпункт
# Другие элементы внутри списков
1. Первый пункт
	> Цитата внутри первого пункта
1. Второй пункт
 	
    Параграф внутри второго пункта
1. Третий пункт
# Ссылки
<https://skillbox.ru/media/code/>   
[Skillbox Media](https://skillbox.ru/media/) без подсказки  
[Skillbox Media](https://skillbox.ru/media/ "Всплывающая подсказка") с подсказкой  
[Skillbox Media][1]

[Раздел «Код»][code]


[1]: https://skillbox.ru/media "Всплывающая подсказка"
[code]: https://skillbox.ru/media/code/
# Картинки
![Изображение](https://yt3.ggpht.com/ytc/AKedOLQNoeVYgQOiDEtaeGTHKS_DhWN7Msl7EsoUcmloxg=s900-c-k-c0x00ffffff-no-rj "Game Over")

# Вставка кода
Функция `print (x)` выводит содержимое переменной ```x```.

```
#include <stdio.h>
int main() {
   printf("Hello, World!");
   return 0;
}
```

	let x = 12;
	let y = 6;
	console.log(x + y);

Если обрамлять код тремя обратными апострофами, то после первой тройки можно указать язык программирования — тогда Markdown правильно подсветит элементы кода.
  
  ```python
if x > 0:
	print (x)
else:
	print ('Hello, World!')
```

```c
#include <stdio.h>
int main() {
   printf("Hello, World!");
   return 0;
}
```

```javascript
let x = 12;
let y = 6;
console.log(x + y);
```
# Таблицы
|Столбец 1|Столбец 2|Столбец 3|
|-|--------|---|
|Длинная запись в первом столбце|Запись в столбце 2|Запись в столбце 3|
|Кртк зпс| |Слева нет записи|

|Столбец 1|Столбец 2|Столбец 3|
|:-|:-:|-:|
|Равнение по левому краю|Равнение по центру|Равнение по правому краю|
|Запись|Запись|Запись|

# Как использовать Markdown в мессенджерах
Как мы уже писали, принципы Markdown используются при разметке текста во многих мессенджерах. Обычно он используется для выделения текста, при этом синтаксис у каждой платформы свой.

**Жирный:**

**Telegram и Discord** — **две звёздочки с двух сторон**  
**WhatsApp и Viber** — **одна звёздочка с двух сторон**.  

*Курсив:*

*Telegram* — два нижних подчёркивания с двух сторон  
*WhatsApp и Viber* — _одно нижнее подчёркивание с двух сторон_  
*Discord* — *одна звёздочка с двух сторон* или _одно нижнее подчёркивание с двух сторон_.

Подчёркнутый:

<u>~Discord<u> — два нижних подчёркивания с двух сторон.  

~~Зачёркнутый:~~

~~WhatsApp и Viber~~ — ~одна тильда с двух сторон~;  
~~Discord~~ — ~~две тильды с двух сторон~~.  

Моноширинный (используется для вставки кода):

Telegram, WhatsApp, Viber и Discord — ```три обратных апострофа с двух сторон```;
в Discord точно так же, как и в Markdown, можно указывать язык программирования для подсветки синтаксиса.

Спойлер:

Telegram и Discord — ||две вертикальные черты с двух сторон||.
