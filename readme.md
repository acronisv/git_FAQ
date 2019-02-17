git clone git@github.com:acronisv/324721-sedona.git

//Отслеживание изменений
git status

//Добавление под версионный контроль новых файлов
git add {file} или git add .

//Запись изменений в репозиторий
git commit -m "{comment}"

//Отправка изменений в удаленный репозиторий
git push origin

//Получение данных из репозитория
git pull

//Переключение на ветку {name}
git checkout {name}

//Создание новой ветки
git checkout -b {name}  

//Добавление нового удаленного репозитория под именем-сокращением {name} с адресом {адрес}.git
git remote add {name} {адрес}.git

//Показывает с какими внешними репозиториями связан локальный репозиторий
git remote -v
