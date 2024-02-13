#Решение домашних заданий на интенсиве Яндекса на Django
![main workflow](https://gitlab.crja72.ru/django/2024/spring/course
/students/153317-islamishtalbagamaev27-gmail.com-course-1112)


## Активация виртуального окружения
```bash
python3 -m venv venv
source venv/bin/activate
```


## Установка зависимостей
```bash
pip3 install -r requirements/prod.txt
```


### Для разработки необходимо дополнительно установить зависимости из `requirements/dev.txt`
bash
pip3 install -r requirements/dev.txt



### Для запуска тестов зависимости перечислены `requirements/text.txt`
```bash
pip3 install -r requirements/test.txt
```



## Настройка переменных окружения
Скопируйте файл 'config.env' в '.env', если нужно, отредактируйте значение
переменных.
```bash
cp config.env .env
```


## Запуск
```bash
python3 manage.py runserver
```