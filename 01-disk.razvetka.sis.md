Начнём выполнение задания

С помощью команд создадим файл-образ на 1 ГБ и подключим его как loop-устройство

<img width="266" height="86" alt="image" src="https://github.com/user-attachments/assets/9604d4ec-68eb-43cc-84da-070e0f4ffd89" />

Теперь мы можем сделать разделы и разметку

<img width="483" height="157" alt="image" src="https://github.com/user-attachments/assets/aa021157-be20-4842-b17c-27fe3a0146b1" />

Следующим шагом создадим файловую систему

<img width="736" height="579" alt="image" src="https://github.com/user-attachments/assets/020d10bb-c556-4cba-b868-c28a0da6af5e" />

И как финальный этап проведём монтирование

<img width="621" height="127" alt="image" src="https://github.com/user-attachments/assets/612685eb-ca2b-46c5-b49a-77dde57a72d1" />

Почему раздел сразу занят?
Потому что на него сразу размещаются служебные структуры такие как супер блок, группы блоков с inode и другие.
