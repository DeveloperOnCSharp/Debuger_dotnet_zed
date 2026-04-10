# Настройка debugger для проектов на DotNet ( ZED ide)
### Необходимые пакеты
1. Dotnet x.x версии
2. Компилятор https://rustup.rs/ 
3. Установить через Visual Studio => Средства => Получить средства и компоненты
* Выбрать классическое "Разработка классического приложения c++"
* Дополнительно поставить галочку "MSVC version 143" и "Пакет DSK для windows 11"
4. Скачать debugger 

`   git clone https://github.com/qwadrox/zed-netcoredbg.git `

`   cd zed-netcoredbg` 

`   cargo build --release`


5. В корне нашего проекта создать файл .zed и добавить 2 json-файла
