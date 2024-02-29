# hack_zavod_TalentMatch
Установка и запуск

1. Установите JDK для корректной работы парсеров документов:
```
apt-get install -y default-jdk
``` 

2. Установите зависимости:
```
pip install -r requirements.txt
```

3. Установите pytorch с поддержкой cuda в соответствии с вашими системными требованиями:
https://pytorch.org/get-started/locally/

4. Запуск приложения:
```
uvicorn main:app --host 0.0.0.0 --port 8081
```

Для полноценной работы требуется доступ к интернету для загрузки весов модели
