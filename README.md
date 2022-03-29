# Laba01-Report
Задание №1 
Скачайте библиотеку boost с помощью утилиты wget. Адрес для скачивания https://sourceforge.net/projects/boost/files/boost/1.69.0/boost_1_69_0.tar.gz
```
sudo wget https://sourceforge.net/projects/boost/files/boost/1.69.0/boost_1_69_0.tar.gz
```
Задание №2 
Разархивируйте скаченный файл в директорию ~/boost_1_69_0 __Жирный текст (bold)__
```
tar -xvf boost_1_69_0.tar.gz
```
Задание №3 
Подсчитайте количество файлов в директории ~/boost_1_69_0 не включая вложенные директории.
```
tree boost_1_69_0 -L 1
```
Задание №4
Подсчитайте количество файлов в директории ~/boost_1_69_0 включая вложенные директории.
```
tree
```
Задание №5
Подсчитайте количество заголовочных файлов, файлов с расширением .cpp, сколько остальных файлов (не заголовочных и не .cpp).
```
find -name "*.cpp" | wc -l
find -name "*.hpp" | wc -l
find -name "*.h" | wc -l
find . -not \( -name "*.h" -o -name "*.hpp" -o -name "*.cpp" \) | wc -l
```
Задание №6
Найдите полный пусть до файла any.hpp внутри библиотеки boost.
```
find -name "any.hpp"
```
Задание №7
```
sudo wget https://sourceforge.net/projects/boost/files/boost/1.69.0/boost_1_69_0.tar.gz
```
Задание №8
```
sudo wget https://sourceforge.net/projects/boost/files/boost/1.69.0/boost_1_69_0.tar.gz
```
Задание №9
```
sudo wget https://sourceforge.net/projects/boost/files/boost/1.69.0/boost_1_69_0.tar.gz
```
Задание №10
```
sudo wget https://sourceforge.net/projects/boost/files/boost/1.69.0/boost_1_69_0.tar.gz
```
Задание №11
```
sudo wget https://sourceforge.net/projects/boost/files/boost/1.69.0/boost_1_69_0.tar.gz
```
