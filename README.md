# Huawei License Parser
Simple script to parse XML license files and match them with serial numbers of Huawei devices

In dir license put xml files \
Fill Excel table (table.xlsx) with hostname and S/N

Execute script


## How this script happened?

The customer received a list of licenses from the vendor in xml format and provided them as part of the project.\
The task was to upload licenses for switches.\
The list of files was huge and it was hard to find which one was related to a specific piece of hardware. \
In order not to suffer and manually search for the serial number in the file, then compare it with the serial number of the equipment,\
it was decided to write a script.\

That's the whole story, most likely a very special case, but maybe someone will find it useful.

```aiignore
Заказчик получил список лицензий от вендора в xml виде и предоставил их в рамках проекта.
Задача стояла залить лицензии на коммутаторы.
Список файлов был огромный и было тяжело найти, какой именно относится к конкретной железке. 
Чтобы не мучаться и руками не искать в файле серийник, потом сопостовлять с серийником оборудования - решено было написать скрипт.
Dот и вся история, скорее всего частный случай очень, но вдруг кому-то пригодится.
```