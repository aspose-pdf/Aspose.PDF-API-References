---
title: "System::IO::File класс"
linktitle: "File"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::IO::File класс. Предоставляет методы для работы с файлами. Это статический тип без сервисов экземпляров. Вы никогда не должны создавать его экземпляры какими бы то ни было способами в C++."
type: docs
weight: 1300
url: /ru/cpp/system.io/file/
---
## File class


Предоставляет методы для работы с файлами. Это статический тип без сервисов экземпляра. Вы никогда не должны создавать его экземпляры каким-либо способом.

```cpp
class File
```

## Методы

| Метод | Описание |
| --- | --- |
| static [AppendAllLines](./appendalllines/)(const String\&, const SharedPtr\<Collections::Generic::IEnumerable\<String\>\>\&, const EncodingPtr\&) | Добавляет строки из указанной коллекции строк в указанный файл, используя указанную кодировку, записывая каждую строку в новой строке. Если указанный файл не существует, он будет создан. Файл закрывается после записи всех строк. |
| static [AppendAllText](./appendalltext/)(const String\&, const String\&, const EncodingPtr\&) | Добавляет указанную строку в указанный файл, используя указанную кодировку. |
| static [AppendText](./appendtext/)(const String\&) | Создаёт объект [StreamWriter](../streamwriter/), который добавляет текст в указанный файл, используя кодировку UTF-8. Если указанный файл не существует, он будет создан. |
| static [Copy](./copy/)(const String\&, const String\&, bool) | Копирует указанный файл в указанное место. Если файл назначения уже существует, параметр указывает, следует ли его перезаписать. |
| static [Create](./create/)(const String\&, int32_t, FileOptions) | Создаёт новый файл (или перезаписывает существующий) и открывает его для чтения и записи, используя указанный размер буфера и параметры. |
| static [CreateText](./createtext/)(const String\&) | Создает новый файл или открывает существующий файл для записи текста в кодировке UTF-8. |
| static [Decrypt](./decrypt/)(const String\&) | НЕ РЕАЛИЗОВАНО. |
| static [Delete](./delete/)(const String\&) | Удаляет указанный файл или каталог. |
| static [Encrypt](./encrypt/)(const String\&) | НЕ РЕАЛИЗОВАНО. |
| static [Exists](./exists/)(const String\&) | Определяет, указывает ли указанный путь на существующий файл. |
| static [GetAttributes](./getattributes/)(const String\&) | Возвращает атрибуты указанной сущности. |
| static [GetCreationTime](./getcreationtime/)(const String\&) | Возвращает время создания указанной сущности в локальном времени. |
| static [GetCreationTimeUtc](./getcreationtimeutc/)(const String\&) | Возвращает время создания указанной сущности в формате UTC. |
| static [GetLastAccessTime](./getlastaccesstime/)(const String\&) | Возвращает время последнего доступа к указанной сущности в локальном времени. |
| static [GetLastAccessTimeUtc](./getlastaccesstimeutc/)(const String\&) | Возвращает время последнего доступа к указанной сущности в формате UTC. |
| static [GetLastWriteTime](./getlastwritetime/)(const String\&) | Возвращает время последней записи указанной сущности в локальном времени. |
| static [GetLastWriteTimeUtc](./getlastwritetimeutc/)(const String\&) | Возвращает время последней записи указанной сущности в формате UTC. |
| static [Move](./move/)(const String\&, const String\&) | Перемещает указанный файл в новое место. |
| static [Open](./open/)(const String\&, FileMode) | Открывает указанный файл в указанном режиме для чтения и записи без общего доступа. |
| static [Open](./open/)(const String\&, FileMode, FileAccess, FileShare) | Открывает указанный файл в указанном режиме, с указанным типом доступа и параметром совместного использования. |
| static [OpenRead](./openread/)(const String\&) | Открывает указанный файл только для чтения в режиме 'Open' с совместным доступом для чтения. |
| static [OpenText](./opentext/)(const String\&, const EncodingPtr\&) | Открывает указанный существующий файл для чтения текста с использованием кодировки UTF-8 без общего доступа. |
| static [OpenWrite](./openwrite/)(const String\&) | Открывает указанный файл только для записи в режиме 'OpenOrCreate' без общего доступа. |
| static [ReadAllBytes](./readallbytes/)(const String\&) | Считывает содержимое указанного бинарного файла в массив байтов. |
| static [ReadAllLines](./readalllines/)(const String\&, const EncodingPtr\&) | Считывает содержимое указанного текстового файла построчно в массив строк, используя указанную кодировку символов. |
| static [ReadAllText](./readalltext/)(const String\&, const EncodingPtr\&) | Считывает содержимое указанного текстового файла в один объект [String](../../system/string/) , используя указанную кодировку символов. |
| static [ReadLines](./readlines/)(const String\&, const EncodingPtr\&) | Считывает содержимое указанного текстового файла построчно, используя указанную кодировку символов, и возвращает перечисляемую коллекцию строк, каждая из которых представляет отдельную строку содержимого файла. |
| static [Replace](./replace/)(const String\&, const String\&, const String\&, bool) | Заменяет содержимое одного файла другим и создает резервную копию заменённого файла. |
| static [SetAttributes](./setattributes/)(const String\&, FileAttributes) | Устанавливает указанные атрибуты для указанного файла. |
| static [SetCreationTime](./setcreationtime/)(const String\&, DateTime) | НЕ РЕАЛИЗОВАНО. |
| static [SetCreationTimeUtc](./setcreationtimeutc/)(const String\&, DateTime) | НЕ РЕАЛИЗОВАНО. |
| static [SetLastAccessTime](./setlastaccesstime/)(const String\&, DateTime) | НЕ РЕАЛИЗОВАНО. |
| static [SetLastAccessTimeUtc](./setlastaccesstimeutc/)(const String\&, DateTime) | НЕ РЕАЛИЗОВАНО. |
| static [SetLastWriteTime](./setlastwritetime/)(const String\&, DateTime) | Устанавливает время последней записи указанной сущности в локальном времени. |
| static [SetLastWriteTimeUtc](./setlastwritetimeutc/)(const String\&, DateTime) | Устанавливает время последней записи указанной сущности в формате UTC. |
| static [WriteAllBytes](./writeallbytes/)(const String\&, const ArrayPtr\<uint8_t\>\&) | Перезаписывает указанный бинарный файл и записывает в него указанные байты. |
| static [WriteAllLines](./writealllines/)(const String\&, const SharedPtr\<Collections::Generic::IEnumerable\<String\>\>\&, const EncodingPtr\&) | Создает новый текстовый файл или перезаписывает существующий и записывает все строки из указанной перечислимой коллекции строк в него, каждую строку на новой строке, используя указанную кодировку. |
| static [WriteAllLines](./writealllines/)(const String\&, const ArrayPtr\<String\>\&, const EncodingPtr\&) | Создает новый текстовый файл или перезаписывает существующий и записывает все строки из указанного массива строк в него, каждую строку на новой строке, используя указанную кодировку. |
| static [WriteAllText](./writealltext/)(const String\&, const String\&, const EncodingPtr\&) | Создает новый текстовый файл или перезаписывает существующий и записывает содержимое указанной строки в него, используя указанную кодировку. |
## Поля

| Поле | Описание |
| --- | --- |
| static [DefaultBufferSize](./defaultbuffersize/) | Значение по умолчанию количества байтов, буферизуемых при чтении из файла и записи в файл. |
## См. также

* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
