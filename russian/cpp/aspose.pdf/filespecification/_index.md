---
title: "Aspose::Pdf::FileSpecification класс"
linktitle: "FileSpecification"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::FileSpecification класс. Класс, представляющий встроенный файл в C++."
type: docs
weight: 5500
url: /ru/cpp/aspose.pdf/filespecification/
---
## FileSpecification class


Класс, представляющий встроенный файл.

```cpp
class FileSpecification : public System::IDisposable
```

## Методы

| Метод | Описание |
| --- | --- |
| [Dispose](./dispose/)() override | Освободить содержимое. |
| [FileSpecification](./filespecification/)(const System::String\&) | Конструктор для [FileSpecification](./). |
| [FileSpecification](./filespecification/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&) | Конструктор для спецификации файла. |
| [FileSpecification](./filespecification/)(const System::String\&, const System::String\&) | Конструктор для [FileSpecification](./). |
| [FileSpecification](./filespecification/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&, const System::String\&) | Конструктор для [FileSpecification](./). |
| [FileSpecification](./filespecification/)(const System::String\&, const System::SharedPtr\<Annotations::Annotation\>\&) | Конструктор для [FileSpecification](./). |
| [FileSpecification](./filespecification/)() | Создать новую пустую спецификацию файла. |
| [get_AFRelationship](./get_afrelationship/)() | Связанное отношение файла. |
| [get_CollectionItem](./get_collectionitem/)() | Получает элемент коллекции спецификации файла. |
| [get_Contents](./get_contents/)() | Получает файл содержимого. Это свойство возвращает данные, загруженные в память, что может вызвать исключение Out of memory при больших данных. Чтобы уменьшить использование памяти, пожалуйста, используйте StreamContents. |
| [get_Description](./get_description/)() | Получает текст, связанный со спецификацией файла. |
| [get_Encoding](./get_encoding/)() const | Получает формат кодирования. Возможные значения: Zip — файл сжат с помощью ZIP, None — файл не сжат. |
| [get_EncryptedPayload](./get_encryptedpayload/)() | Получает зашифрованные данные. |
| [get_FileSystem](./get_filesystem/)() | Получает имя файловой системы. |
| [get_IncludeContents](./get_includecontents/)() const | Если true, содержимое файла будет включено в спецификацию файла. |
| [get_MIMEType](./get_mimetype/)() | Получает подтип встроенного файла. |
| [get_Name](./get_name/)() | Получает имя спецификации файла. |
| [get_Params](./get_params/)() | Получает параметры файла. |
| [get_StreamContents](./get_streamcontents/)() | Получает содержимое файла как поток. Содержимое не загружается в память, что позволяет уменьшить использование памяти. Однако этот поток не поддерживает позиционирование и свойство Length. Если вам нужны эти возможности, пожалуйста, используйте свойство Contents вместо него. |
| [get_UnicodeName](./get_unicodename/)() | Получает Unicode‑имя спецификации файла. |
| [GetValue](./getvalue/)(const System::String\&) | Получает параметр, специфичный для приложения. |
| [set_AFRelationship](./set_afrelationship/)(Aspose::Pdf::AFRelationship) | Связанное отношение файла. |
| [set_Contents](./set_contents/)(const System::SharedPtr\<System::IO::Stream\>\&) | Устанавливает файл содержимого. Это свойство возвращает данные, загруженные в память, что может вызвать исключение Out of memory при больших объёмах данных. Чтобы уменьшить использование памяти, пожалуйста, используйте StreamContents. |
| [set_Description](./set_description/)(const System::String\&) | Устанавливает текст, связанный со спецификацией файла. |
| [set_Encoding](./set_encoding/)(FileEncoding) | Устанавливает формат кодирования. Возможные значения: Zip — файл сжат с помощью ZIP, None — файл не сжат. |
| [set_FileSystem](./set_filesystem/)(const System::String\&) | Устанавливает имя файловой системы. |
| [set_IncludeContents](./set_includecontents/)(bool) | Если true, содержимое файла будет включено в спецификацию файла. |
| [set_MIMEType](./set_mimetype/)(const System::String\&) | Получает подтип встроенного файла. |
| [set_Name](./set_name/)(const System::String\&) | Устанавливает имя спецификации файла. |
| [set_Params](./set_params/)(const System::SharedPtr\<FileParams\>\&) | Получает параметры файла. |
| [set_UnicodeName](./set_unicodename/)(const System::String\&) | Устанавливает Unicode‑имя спецификации файла. |
| [SetValue](./setvalue/)(const System::String\&, const System::String\&) | Устанавливает параметр, специфичный для приложения. |
## См. также

* Class [IDisposable](../../system/idisposable/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
