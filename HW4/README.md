
Original file line number	Original file line	Diff line number	Diff line change
@@ -0,0 +1,19 @@
Ссылка на [google disc](https://drive.google.com/drive/folders/1QNsrhsCeoiA5cVAls-EaS0qJq-6Oa4OK?usp=sharing)

Все правки выполнялись из директории [**scripts**](https://github.com/pohbl4/MLops-HW-2semester/tree/main/HW4/scripts)

Последовательность команд:

1. ```git clone```  - клонирование репозитория
2. ```pip install pandas numpy catboost``` - установка зависимостей
3. ```cd scripts``` - переход в директорию с python-скриптами
4. ```python|python3 get_data.py``` - модификация данных #0 - получение данных датасета *titanic*
5. ```python|python3 delete_data.py``` - если данные нужно удалить *(опционально)*
6. ```python|python3 modificator_1.py``` - модификация данных #1 - заполнение колонки **Age** средним значением
7. ```python|python3 modificator_2.py``` - модификация данных #2 - применение *one-hot-encoding* для колонки **Sex**
8. ```dvc push``` - после каждой модификации данных - отправка на google disk через *dvc*