# План обучения DataScience Python

# План обучения DataScience Python

Если вы хотите изучить Data Science с использованием языка программирования Python, необходимо придерживаться плана обучения, который позволит вам освоить все необходимые навыки. Ниже представлены основные шаги, которые необходимо выполнить для достижения этой цели.

## Шаг 1: Основы Python

Перед тем, как начать работать с Data Science, вам необходимо освоить основы языка Python. Для этого можно использовать онлайн-курсы или книги по Python. Основные темы, которые необходимо изучить, включают в себя синтаксис, типы данных, функции, циклы и условные операторы.

### Ссылки

### Онлайн материалы для изучения основ языка

1. [Пульс. Основы Python](https://hr.sberbank.ru/platform/catalog/9ca4d787-f428-4b59-885d-b65a3377e8e9)
2. [Stepic. "Поколение Python": курс для начинающих](https://stepik.org/course/58852/promo)
3. [Stepic. Программирование: Python](https://stepik.org/course/102141/promo?search=2259175737)
4. [Pythonworld. Самоучитель](https://pythonworld.ru/samouchitel-python)
5. [Youtube. Уроки Python с нуля](https://www.youtube.com/watch?v=ML5tP8m6SHw&list=PLDyJYA6aTY1lPWXBPk0gw6gR8fEtPDGKa&index=3)

### Книги

1. [Python без проблем: решаем реальные задачи и пишем полезный код](https://hr.sberbank.ru/platform/catalog/b2f6c657-2e32-4014-b65a-b3ed1bdb841d)
2. [Марк Лутц. Изучаем Python (Том 1, 5-е издание)](https://do.sch24.ru:88/%D0%A3%D0%A7%D0%95%D0%91%D0%9D%D0%98%D0%9A%D0%98/%D0%BA%D0%BE%D0%BC%D0%BF%D1%8C%D1%8E%D1%82%D0%B5%D1%80%D1%8B/%D0%9F%D1%80%D0%BE%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5/Python/%D0%98%D0%B7%D1%83%D1%87%D0%B0%D0%B5%D0%BC%20Python.%205-%D0%B5%20%D0%B8%D0%B7%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5%20%D0%A2%D0%BE%D0%BC%201.pdf)
3. [Зед Шоу. Легкий способ выучить Python 3](https://codernet.ru/books/python/legkij_sposob_vyuchit_python3/)
4. [Уэс Маккинни. Python и анализ данных](https://vk.com/doc74080069_572328132?hash=DJCuHZ9rvHDRNiPZQ9RQTOqZbE8ZZ5H1VyDYH2FAE3g)

### Ссылки на онлайн интерпритаторы

1. [Online Python](https://www.online-python.com/)
2. [Online GDB](https://www.onlinegdb.com/online_python_compiler)

### Необходимые программы

*Ссылки ведут на SberUserSoft*

1. [Anaconda3](https://sberusersoft/#program/s/1077)
2. [PyCharm](https://sberusersoft/#program/s/62)
3. [Python](https://sberusersoft/#program/s/168)

## 2. **Обзор Jupyter Notebook**

Jupyter Notebook - это интерактивная среда для написания и выполнения кода, часто используемая для анализа данных, научных исследований и образовательных целей. Он позволяет пользователям создавать документы, содержащие код, текст, формулы и визуализации, и делиться ими с коллегами.

### **2.1. Установка Jupyter Notebook**

**Способ 1**. Если на вашем компьютере уже [установлен Питон](https://www.dmitrymakarov.ru/python/script-13/#0-ustanovka-pitona-na-windows), то установить Jupyter Notebook можно через менеджер пакетов pip.

**Способ 2** (рекомендуется). Кроме того, Jupyter Notebook входит в дистрибутив Питона под названием Anaconda.

1. [Anaconda3](https://sberusersoft/#program/s/1077) ссылка на SberUserSoft
2. [Anaconda.com](https://www.anaconda.com/download) ссылка на официальный сайт

# **Anaconda**

Anaconda — это дистрибутив Питона и репозиторий пакетов, специально предназначенных для анализа данных и машинного обучения.

![https://www.dmitrymakarov.ru/wp-content/uploads/2022/02/anaconda-logo.png](https://www.dmitrymakarov.ru/wp-content/uploads/2022/02/anaconda-logo.png)

[Подробнее про запуск Jupyter Notebook в **Anaconda**](https://github.com/Waso-python/Learn_python_data_analysis/blob/main/2.1%20Anaconda_and_Jupiter_Notebook.md)

### **2.2. Знакомство с интерфейсом Jupyter Notebook**

### **Код на Python**

В целом мы пишем обычный код на Питоне.

### **Вкладка Cell**

Для управления запуском или исполнением ячеек можно использовать вкладку Cell.

![https://www.dmitrymakarov.ru/wp-content/uploads/2022/05/jupyter-cell-tab-1024x636.jpg](https://www.dmitrymakarov.ru/wp-content/uploads/2022/05/jupyter-cell-tab-1024x636.jpg)

Здесь мы можем, в частности:

- Запускать ячейку и оставаться в ней же через **Run Cells**
- Исполнять все ячейки в ноутбуке, выбрав **Run All**
- Исполнять все ячейки выше (**Run All Above**) или ниже текущей (**Run All Below**)
- Очистить вывод ячеек, нажав **All Output → Clear**

### **Вкладка Kernel**

Командами вкладки Kernel мы управляем ядром (kernel) или вычислительным «движком» ноутбука.

![https://www.dmitrymakarov.ru/wp-content/uploads/2022/05/jupyter-kernel-tab-1024x645.jpg](https://www.dmitrymakarov.ru/wp-content/uploads/2022/05/jupyter-kernel-tab-1024x645.jpg)

В этой вкладке мы можем, в частности:

- Прервать исполнение ячейки командой **Interrupt**. Это бывает полезно, если, например, исполнение кода занимает слишком много времени или в коде есть ошибка и исполнение кода не прервется самостоятельно.
- Перезапустить kernel можно командой **Restart**. Кроме того, можно
    - очистить вывод (**Restart & Clear Output**) и
    - заново запустить все ячейки (**Restart & Run All**)

### **Установка новых пакетов**

Установить новые пакеты в Anaconda можно непосредственно в ячейке, введя **!pip install <package_name>**. Например, попробуем установить Numpy.

![https://www.dmitrymakarov.ru/wp-content/uploads/2022/05/pip-install-jupyter-1024x134.jpg](https://www.dmitrymakarov.ru/wp-content/uploads/2022/05/pip-install-jupyter-1024x134.jpg)

Система сообщила нам, что такой пакет уже установлен. Более того, мы видим путь к папке внутри дистрибутива Anaconda, в которой Jupyter «нашел» Numpy.

### **2.3. Markdown в Jupyter Notebook**


Помимо ячеек с кодом, можно использовать текстовые ячейки, в которых поддерживается язык разметки Markdown.

ссылка на описание синтаксиса разметки Markdown - [Описание синтаксиса](https://docs.github.com/ru/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

Примеры синтаксиса в **[документе](https://github.com/Waso-python/Learn_python_data_analysis/blob/main/2.3%20Markdown_on_Jupyter_Notebook.md)**

## **3. Обзор и использование библиотеки Pandas**

### **3.1. Импорт данных в Pandas DataFrame**

- Материал: [Официальная документация Pandas по импорту данных](https://pandas.pydata.org/pandas-docs/stable/reference/io.html)
- Примеры:
    - Импорт данных из CSV-файла
    - Импорт данных из Excel-файла
    - Импорт данных из JSON-файла
- Задача: Импортировать датасет из файла CSV и Excel, просмотреть первые и последние строки датасета с помощью методов head и tail.
- [Ссылка на ноутбук](https://github.com/Waso-python/Learn_python_data_analysis/blob/main/3.1%20Data_import.ipynb)

### **3.2. Основы работы с данными: выбор данных, фильтрация, сортировка**

- Материал: [Официальная документация Pandas по выбору данных, фильтрации и сортировке](https://pandas.pydata.org/pandas-docs/stable/user_guide/basics.html)
- Примеры:
    - Приведение типов столбцов
    - Выбор столбцов и строк
    - Замена значений в данных
    - Удаление столбцов
    - Фильтрация данных по условию
    - Сортировка данных по определенному столбцу
    - Создание новых столбцов на основе существующих:
- Задача: Выбрать определенные столбцы из датасета, отфильтровать строки по определенному условию и отсортировать результаты.
- [Ссылка на ноутбук](https://github.com/Waso-python/Learn_python_data_analysis/blob/main/3.2%20Data_basics.ipynb)

### **3.3. Основные функции агрегации и группировки данных**

- Материал: [Официальная документация Pandas по агрегации и группировке данных](https://pandas.pydata.org/pandas-docs/stable/user_guide/groupby.html)
- Примеры:
    - Применение функций к данным
    - Вычисление среднего, медианы, минимального и максимального значения
    - Группировка данных по определенному столбцу и применение агрегирующих функций к этим группам
- Задача: Применить группировку к датасету по определенному признаку и подсчитать статистику по другим столбцам в каждой группе.
- [Ссылка на ноутбук](https://github.com/Waso-python/Learn_python_data_analysis/blob/main/3.3.%20Data_agg_and_grouping.ipynb)


## 4. Подробнее о функциях Pandas

### **4.1. Подробное изучение Series и DataFrame**

- Материал: [Официальная документация Pandas по Series и DataFrame](https://pandas.pydata.org/pandas-docs/stable/user_guide/dsintro.html)
- Примеры:
    - Создание Series и DataFrame из различных структур данных
    - Основные методы и атрибуты Series и DataFrame
- Задача: Создать Series и DataFrame из списка, словаря и numpy массива. Применить основные методы и атрибуты.
- [Ссылка на ноутбук](https://github.com/Waso-python/Learn_python_data_analysis/blob/main/4.1%20Series%20and%20DataFrame%20detailed.ipynb)

### **4.2. Обработка пропущенных данных**

- Материал: [Официальная документация Pandas по обработке пропущенных данных](https://pandas.pydata.org/pandas-docs/stable/user_guide/missing_data.html)
- Примеры:
    - Определение пропущенных значений в данных
    - Заполнение пропущенных значений средним, медианой, модой и т.д.
    - Удаление строк или столбцов с пропущенными данными
- Задача: Загрузить датасет, содержащий пропущенные значения, определить их и обработать различными способами.
- [Ссылка на ноутбук](https://github.com/Waso-python/Learn_python_data_analysis/blob/main/4.2.%20Processing%20missing%20data.ipynb)

### **4.3. Слияние, объединение и изменение формы данных**

- Материал: [Официальная документация Pandas по слиянию, объединению и изменению формы данных](https://pandas.pydata.org/pandas-docs/stable/user_guide/merging.html)
- Примеры:
    - Слияние двух DataFrame с помощью merge
    - Объединение двух DataFrame с помощью concat
    - Изменение формы данных с помощью melt и pivot
- Задача: Слияние и объединение двух DataFrame, а также изменение формы датасета с помощью методов melt и pivot.
- [Ссылка на ноутбук](https://github.com/Waso-python/Learn_python_data_analysis/blob/main/4.3.%20Reshaping,%20merge%20and%20pivot%20tables.ipynb)

## **5. Продвинутый анализ данных с Pandas**

### **5.1. Работа с временными рядами в Pandas**

- Материал: [Официальная документация Pandas по работе с временными рядами](https://pandas.pydata.org/pandas-docs/stable/user_guide/timeseries.html)
- Примеры:
    - Создание временных рядов
    - Ресемплинг, сдвиг и скользящее окно
- Задача: Загрузите датасет с временными данными, преобразуйте дату в индекс, а затем выполните операции ресемплинга и вычисления скользящего среднего.
- [Ссылка на ноутбук](https://github.com/Waso-python/Learn_python_data_analysis/blob/main/5.1%20Time%20Series%20in%20Pandas.ipynb)

### **5.2. Применение функций и методов apply и map**

- Материал: [Официальная документация Pandas по методам apply и map](https://pandas.pydata.org/pandas-docs/stable/user_guide/basics.html)
- Примеры:
    - Применение функции к каждому элементу столбца с помощью map
    - Применение функции к каждой строке или столбцу DataFrame с помощью apply
- Задача: Создайте функцию, которая преобразует элементы в столбце, а затем примените ее с помощью методов apply или map.
- [Ссылка на ноутбук](https://github.com/Waso-python/Learn_python_data_analysis/blob/main/5.2.%20Using%20apply%20and%20map%20functions%20and%20methods.ipynb)

### **5.3. Использование мультииндексации**

- Материал: [Официальная документация Pandas по мультииндексации]((https://pandas.pydata.org/pandas-docs/stable/user_guide/basics.html))
- Примеры:
    - Создание мультииндексного DataFrame
    - Выбор данных с использованием мультииндекса
- Задача: Создайте мультииндексный DataFrame и попрактикуйтесь в выборе данных с его помощью.
- [Ссылка на ноутбук](https://github.com/Waso-python/Learn_python_data_analysis/blob/main/5.3%20Using%20multi-indexing%20in%20Pandas.ipynb)

**Заключение**: 
В этом учебном пособии мы рассмотрели основы работы с библиотекой **Pandas**, а также ряд продвинутых тем, которые помогут вам проводить эффективный анализ данных. Если у вас возникнут вопросы или потребуется помощь, не стесняйтесь обращаться . Кроме того, буду рад получить ваши предложения и замечания относительно этого материала, чтобы сделать его еще лучше и полезнее для всех нас. Давайте вместе улучшать наши навыки в анализе данных с использованием Pandas! 
