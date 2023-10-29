# Цифровой прорыв: Сезон ИИ, Пермь (ПФО)
## Кейс: МЧС "Прогнозирование опасностей и рисков Пермского края"
## Команда: hacks
* Артём Гордеев
* Дамадан Шавлуков
* Вячеслав Исаев
* Александр Куличенко
* Андрей Кукушкин
## Навигация по репозиторию
* research - папка с jupyter notebook с изучением, обработкой данных, тренировкой и валидацией моделей
* fronhacks - папка с frontend веб-сервиса
* backhacks - папка с backend веб-сервиса
## Поднятие backend веб-сервисa
### Требования
* Python 3.x, x >= 9
### Команды
```commandline
cd backhacks
pip install -r requirements.txt
uvicorn main:app --reload 
```
### Итог
Поднят backend по адресу `http://127.0.0.1:8000/`

## Поднятие frontend веб-сервисa
### Требования
* npm (менеджер пакетов)
### Команды
```commandline
cd fronthacks
npm i
npm run dev
```
### Итог
Поднят frontend по адресу `http://localhost:5173/`
