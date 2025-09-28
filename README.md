## 🚀 Как работать с этим репозиторием
### 📦 Установка

1. Клонируйте репозиторий:

```
git clone https://github.com/gorop51-2/Data-Science-For-Beginners-from-scratch-SENATOROV.git
cd REPO_NAME
```
                  
2. (Рекомендуется) создайте виртуальное окружение:

```
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
```
                  
3. Установите зависимости:

```
pip install -r requirements.txt
```
                  
### 🧪 Запуск тестов (если есть)

```
pytest
```
                  
### 📚 Генерация документации (Sphinx)

1. Перейдите в папку документации:

```
cd docs
```
                  
2. Сгенерируйте HTML-документацию:

```
make html
```
                  
3. Откройте в браузере:

```
open _build/html/index.html  # Windows: start _build/html/index.html
```
                  
### 🚀 Автопубликация документации

Документация автоматически собирается и публикуется на GitHub Pages при каждом коммите в ветку main.


**Ссылка на документацию**:<br>👉 https://gorop51-2.github.io/Data-Science-For-Beginners-from-scratch-SENATOROV/

### 🛠️ Основные команды разработки

|Цель                            |Команда                          |
| ------------------------------ | ------------------------------- |
|Установка зависимостей          |`pip install -r requirements.txt`|
|Запуск тестов                   |`pytest`                         |
|Сборка документации             |`cd docs && make html`           |
|Локальный просмотр доков	открыть|`docs/_build/html/index.html`    |

project_root<br>
├── requirements.txt          # зависимости проекта<br>
├── setup.py                  # (если проект - пакет)<br>
├── README.md                 # описание проекта<br>
└── LICENSE                   # лицензия
