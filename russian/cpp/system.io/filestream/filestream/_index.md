---
title: "Конструктор System::IO::FileStream::FileStream"
linktitle: "FileStream"
second_title: "Справочник API Aspose.PDF для C++"
description: "Как использовать конструктор FileStream класса System::IO::FileStream в C++."
type: docs
weight: 100
url: /ru/cpp/system.io/filestream/filestream/
---
## FileStream::FileStream(const FileStream\&) constructor




```cpp
System::IO::FileStream::FileStream(const FileStream &)=delete
```

## См. также

* Class [FileStream](../)
* Class [FileStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## FileStream::FileStream(const String\&, FileMode) constructor


Создаёт новый экземпляр класса [FileStream](../) и инициализирует его указанными параметрами.

```cpp
System::IO::FileStream::FileStream(const String &path, FileMode mode)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| путь | const String\& | Путь к файлу, который нужно открыть. |
| режим | FileMode | Указывает режим, в котором открывать файл. |

## См. также

* Class [String](../../../system/string/)
* Enum [FileMode](../../filemode/)
* Class [FileStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## FileStream::FileStream(const String\&, FileMode, FileAccess, FileShare, int32_t, bool) constructor


Создаёт новый экземпляр класса [FileStream](../) и инициализирует его указанными параметрами.

```cpp
System::IO::FileStream::FileStream(const String &path, FileMode mode, FileAccess access, FileShare share, int32_t buffer_size, bool useAsync)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| путь | const String\& | Путь к файлу, который нужно открыть. |
| режим | FileMode | Указывает режим, в котором открывать файл. |
| доступ | FileAccess | Запрашиваемый тип доступа. |
| share | FileShare | Тип доступа, который другие объекты [FileStream](../) имеют к открытому файлу. |
| buffer_size | int32_t | Количество байтов, буферизуемых во время операций чтения и записи. |
| useAsync | bool | Указывает, использовать ли асинхронный ввод-вывод или синхронный ввод-вывод. |
## Примечания



Подлежащая операционная система может не поддерживать асинхронный ввод-вывод.

## См. также

* Class [String](../../../system/string/)
* Enum [FileMode](../../filemode/)
* Enum [FileAccess](../../fileaccess/)
* Enum [FileShare](../../fileshare/)
* Class [FileStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## FileStream::FileStream(const String\&, FileMode, FileAccess, FileShare, int32_t, FileOptions) constructor


Создаёт новый экземпляр класса [FileStream](../) и инициализирует его указанными параметрами.

```cpp
System::IO::FileStream::FileStream(const String &path, FileMode mode, FileAccess access, FileShare share=FileShare::Read, int32_t buffer_size=DefaultBufferSize, FileOptions options=FileOptions::SequentialScan)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| путь | const String\& | Путь к файлу, который нужно открыть. |
| режим | FileMode | Указывает режим, в котором открывать файл. |
| доступ | FileAccess | Запрашиваемый тип доступа. |
| share | FileShare | Тип доступа, который другие объекты [FileStream](../) имеют к открытому файлу. |
| buffer_size | int32_t | Количество байтов, буферизуемых во время операций чтения и записи. |
| опции | FileOptions | Дополнительные параметры. |

## См. также

* Class [String](../../../system/string/)
* Enum [FileMode](../../filemode/)
* Enum [FileAccess](../../fileaccess/)
* Enum [FileShare](../../fileshare/)
* Enum [FileOptions](../../fileoptions/)
* Class [FileStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
