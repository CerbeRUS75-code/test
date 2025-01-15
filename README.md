### GO
## ООП в Golang
 __"Как реализовано ООП в go?"__

__Ответ:__
 
 В go нет классической реализация ООП, так как он не объектно-ориентированный язык.

__"Как реализовано наследование?"__

__Ответ:__

Как такового наследования в go нет, но при этом у нас есть структуры - это специальные типы, в которые мы можем включать другие типы, в том числе такие же структуры. При этом методы дочерних структур родительская структура также будет наследовать.

__"Что будет, если и в родительской и дочерней структуре есть реализация методов с одинаковым названием?"__

__Ответ:__ 

"Реализация родительского метода будет переписана реализацией дочернего метода".
![image](https://github.com/user-attachments/assets/7b57598b-cbcb-4b68-92ca-f4a06298ec66)

__"Как реализована Инкапсуляция в go?"__
![image](https://github.com/user-attachments/assets/a0a2fcdf-cbfa-41e1-9a15-e05e192ac52d)

__"Как реализован полиморфизм в go?"__
![image](https://github.com/user-attachments/assets/760a22a1-c7bf-409e-b082-1ee78646d924)

## Области видимости в Golang

__"Что такое пакеты в go?"__

![image](https://github.com/user-attachments/assets/17b38eee-e519-4d5f-8426-88cac0716021)

__"Что такое глобальная переменная?"__

![image](https://github.com/user-attachments/assets/c02124eb-573f-4faf-8810-ff903a98497d)

__"Что такое фигурные скобки с не объявленным оператором в go функции?"__

![image](https://github.com/user-attachments/assets/de408c9f-ac2c-4618-8f1b-080b58c10631)

## Операторы в Golang

 __"В go есть оператор switch case, можно ли выполнить несколько условий в одном объявленном операторе?"__

![image](https://github.com/user-attachments/assets/1789587c-0738-467c-841d-ef4beb3981cd)

## Strings в Golang

__"Что представляют из себя строки в go?"__

![image](https://github.com/user-attachments/assets/7cd7137b-892b-4d4a-9b5f-e77d663f67d5)

__"Как можно оперировать строками?"__

![image](https://github.com/user-attachments/assets/59cffe1f-78c7-4a97-b943-ad4feb7c2fd1)

__"Что будет если сложить строки?"__

![image](https://github.com/user-attachments/assets/9ddf46cd-6cd1-4752-bf60-2b78ccf15c63)

__"Как определить количество символов для строки?" или "Какие есть нюансы при итерации по строке?"__

![image](https://github.com/user-attachments/assets/0c4588e8-0fb0-41a1-9875-2726b3c92fad)

## Int в Golang

__"Какие численные типы есть в go?"__

![image](https://github.com/user-attachments/assets/fbc7ec98-6f67-42c2-bfee-efe35238e3bb)

__"Чем отличается int от uint?"__

![image](https://github.com/user-attachments/assets/1dcf8376-d389-4907-be22-d6b6c1a6db48)

__"Что такое обычный int и какие есть нюансы его реализации?"__

![image](https://github.com/user-attachments/assets/315ac159-5b38-4f62-a8bc-cfadf115976e)

__"Как преобразовать строку в int и наоборот? Можно ли сделать int(string) и string(int) соответственно?"__

![image](https://github.com/user-attachments/assets/bacc83f3-726b-49e2-a8f9-0783acc04111)

__"Сколько в памяти занимают реализации int32 и int64?"__

![image](https://github.com/user-attachments/assets/d9d67b42-124a-4024-bc42-6817982685e9)

__"Какой результат получим если разделить int на 0 и float на 0?"__

![image](https://github.com/user-attachments/assets/dc2cdc36-e86d-48f6-b52b-9699dd589f1b)

## Const в Golang

__"Что такое константы и можно ли их изменять?"__

![image](https://github.com/user-attachments/assets/0b100571-23f7-49a9-93ee-e1ee609daaa8)

__"Что такое iota?"__

![image](https://github.com/user-attachments/assets/db3c4935-b526-439d-bda9-a80b7dd25277)

## Array и slice в Golang

__"Что такое слайс и чем он отличается от массива?"__

![image](https://github.com/user-attachments/assets/6a26359a-2056-4a8f-9833-f23d8a2866cb)

__"Как работает базовая функция append для go?"__

![image](https://github.com/user-attachments/assets/5547a2c6-98e7-4f72-b40b-6b10019902a0)

__"Какой размер массива выделяется под слайс при его расширении за рамки его емкости?"__

![image](https://github.com/user-attachments/assets/8847fe0d-b2fb-4130-9693-f43f6f59353b)

## Map в Golang

__"Как реализована map(карта) go?"__

![image](https://github.com/user-attachments/assets/d3a2ba0c-058c-4d8a-bfa5-949b02086571)

__"Почему нельзя брать ссылку на значение, хранящееся по ключу в map?"__

![image](https://github.com/user-attachments/assets/62a77b5a-d454-4daa-b6c4-d447d0ae09bf)

__"Что такое эвакуация, и в каком случае она будет происходить?"__

![image](https://github.com/user-attachments/assets/8c7436c9-ac03-458e-995e-08badccf294d)

__"Какие есть особенности синтаксиса получения и записи значений в map?"__

![image](https://github.com/user-attachments/assets/1077e4d9-ddb3-4256-9fe1-d4e818548ab6)

__"Как происходит поиск по ключу в map?__

![image](https://github.com/user-attachments/assets/605bdcda-4afd-4259-8ff3-7647bd7612f7)

## Интерфейсы в Golang

![image](https://github.com/user-attachments/assets/362df6ee-bf47-46ef-933d-92250dc93607)


























