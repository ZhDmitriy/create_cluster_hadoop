Запустим MapReduce задание в кластере Hadoop. 

Для этого установим утилиту awscli: `sudo qpt install -y awscli` на ранее созданном кластере Hadoop в Яндекс.Облаке: 

![image](https://github.com/user-attachments/assets/5ecf9181-4664-420a-8ba2-c5618846643b)

Скачаем два файла: 
1. `wget -o alice.txt https://www.gutenberg.org/files/11/11-0.txt`
2. `wget -o frank.txt https://www.gutenberg.org/files/84/84-0.txt`

![image](https://github.com/user-attachments/assets/d884b893-9b0b-47a0-a8e8-8268475970a6)

Положим скаченные файлы в папку на HDFS: 
![image](https://github.com/user-attachments/assets/14b7898f-a77a-4a55-9b20-bc8222f7a239)
