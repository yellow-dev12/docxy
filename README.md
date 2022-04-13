# docxy

_docxy_ - это программа для создания докладов из информации взятой из википедии. Она написана на python с использованием сторонних библиотек.

для запуска нужно: python (от 2.7 до самых новых версий), библиотеки python, консоль

**библиотеки:**
  1. python-docx
  2. icrawler
  3. shutil
  4. requests
  5. pillow
  6. beautifulsoup4
(если что-то пойдёт не так то загуглите ошибку при запуске программы)

**КОММАНДА ДЛЯ УСТАНОВКИ ВСЕХ БИБЛИОТЕК ОДНО ВРЕМЕННО: *pip install python-docx icrawler requests pillow beautifulsoup4__**

**_Настройка программы:_**
Настройка происходит в самом коде в начале. У каждого пункта есть подпись

**_Работа программы:_**
Программа создаёт папку в расположении файла кода которая названа темой доклада. Там она скачивает с гугла фотографии по теме, ложит их в папку images, а позже собирает столько документов, сколько вы указали в настройках.