---
title: "System::Net::Http::Headers::ContentDispositionHeaderValue класс"
linktitle: "ContentDispositionHeaderValue"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Net::Http::Headers::ContentDispositionHeaderValue класс. Представляет значение заголовка ''Content-Disposition''. Объекты этого класса должны выделяться только с помощью функции System::MakeObject() function. Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 300
url: /ru/cpp/system.net.http.headers/contentdispositionheadervalue/
---
## ContentDispositionHeaderValue class


Представляет значение заголовка 'Content-Disposition'. Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/) . Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class ContentDispositionHeaderValue : public System::ICloneable
```

## Методы

| Метод | Описание |
| --- | --- |
| [ContentDispositionHeaderValue](./contentdispositionheadervalue/)() | Создаёт новый экземпляр. |
| [ContentDispositionHeaderValue](./contentdispositionheadervalue/)(String) | Создаёт новый экземпляр. |
| [Equals](./equals/)(System::SharedPtr\<Object\>) override | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| [get_CreationDate](./get_creationdate/)() | Получает дату создания файла. |
| [get_DispositionType](./get_dispositiontype/)() | Информация RTTI. |
| [get_FileName](./get_filename/)() | Получает значение, определяющее, как сформировать имя файла для хранения полезных данных сообщения. Используется, когда сущность отсоединена и сохраняется в отдельном файле. |
| [get_FileNameStar](./get_filenamestar/)() | Получает значение, определяющее, как сформировать имена файлов для хранения полезных данных сообщения. Используется, когда сущности отсоединены и сохраняются в отдельных файлах. |
| [get_ModificationDate](./get_modificationdate/)() | Получает дату изменения файла. |
| [get_Name](./get_name/)() | Получает имя части тела содержимого. |
| [get_Parameters](./get_parameters/)() | Возвращает коллекцию параметров заголовка 'Content-Disposition'. |
| [get_ReadDate](./get_readdate/)() | Получает дату последнего чтения файла. |
| [get_Size](./get_size/)() | Получает приблизительный размер файла. |
| static [GetDispositionTypeLength](./getdispositiontypelength/)(String, int32_t, System::SharedPtr\<Object\>\&) | Преобразует переданную строку, начиная с указанного индекса, в экземпляр класса [ContentDispositionHeaderValue](./). |
| [GetHashCode](./gethashcode/)() const override | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| static [Parse](./parse/)(String) | Преобразует переданную строку в экземпляр класса [ContentDispositionHeaderValue](./). |
| [set_CreationDate](./set_creationdate/)(Nullable\<DateTimeOffset\>) | Устанавливает дату создания файла. |
| [set_DispositionType](./set_dispositiontype/)(String) | Устанавливает тип диспозиции. |
| [set_FileName](./set_filename/)(String) | Устанавливает значение, определяющее, как сформировать имя файла для хранения полезных данных сообщения. Используется, когда сущность отсоединена и сохраняется в отдельном файле. |
| [set_FileNameStar](./set_filenamestar/)(String) | Устанавливает значение, определяющее, как сформировать имена файлов для хранения полезных данных сообщения. Используется, когда сущности отсоединены и сохраняются в отдельных файлах. |
| [set_ModificationDate](./set_modificationdate/)(Nullable\<DateTimeOffset\>) | Устанавливает дату изменения файла. |
| [set_Name](./set_name/)(String) | Устанавливает имя части тела содержимого. |
| [set_ReadDate](./set_readdate/)(Nullable\<DateTimeOffset\>) | Устанавливает дату последнего чтения файла. |
| [set_Size](./set_size/)(Nullable\<int64_t\>) | Устанавливает приблизительный размер файла. |
| [ToString](./tostring/)() const override | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static [TryParse](./tryparse/)(String, System::SharedPtr\<ContentDispositionHeaderValue\>\&) | Пытается преобразовать переданную строку в экземпляр класса [ContentDispositionHeaderValue](./). |
## См. также

* Class [ICloneable](../../system/icloneable/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PDF for C++](../../)
