---
title: "System::IO::FileSystemInfo класс"
linktitle: "FileSystemInfo"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::IO::FileSystemInfo класс. Базовый класс для FileInfo и DirectoryInfo. Объекты этого класса должны выделяться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 1600
url: /ru/cpp/system.io/filesysteminfo/
---
## FileSystemInfo class


Базовый класс для [FileInfo](../fileinfo/) и [DirectoryInfo](../directoryinfo/). Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class FileSystemInfo : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual [Delete](./delete/)() | Удаляет объект, представленный текущим экземпляром. |
| virtual [Finalize](./finalize/)() | Ничего не делает. |
| [get_Attributes](./get_attributes/)() | Возвращает атрибуты сущности, представленной текущим объектом. |
| [get_CreationTime](./get_creationtime/)() | Возвращает время создания сущности, представленной текущим объектом, в локальном времени. |
| [get_CreationTimeUtc](./get_creationtimeutc/)() | Возвращает время создания сущности, представленной текущим объектом, в формате UTC. |
| virtual [get_Exists](./get_exists/)() | Определяет, существует ли сущность, на которую указывает путь, представленный текущим объектом. |
| [get_Extension](./get_extension/)() | Возвращает расширение файла, представленного текущим объектом. |
| virtual [get_FullName](./get_fullname/)() | Возвращает полное имя (включая путь) сущности, представленной текущим объектом. |
| [get_LastAccessTime](./get_lastaccesstime/)() | Возвращает время последнего доступа к сущности, представленной текущим объектом, в локальном времени. |
| [get_LastAccessTimeUtc](./get_lastaccesstimeutc/)() | Возвращает время последнего доступа к сущности, представленной текущим объектом, в формате UTC. |
| [get_LastWriteTime](./get_lastwritetime/)() | Возвращает время последней записи сущности, представленной текущим объектом, в локальном времени. |
| [get_LastWriteTimeUtc](./get_lastwritetimeutc/)() | Возвращает время последней записи сущности, представленной текущим объектом, в формате UTC. |
| virtual [get_Name](./get_name/)() | Возвращает имя сущности, представленной текущим объектом. |
| [Refresh](./refresh/)() | Обновляет состояние текущего объекта. |
| [set_Attributes](./set_attributes/)(FileAttributes) | Устанавливает указанные атрибуты для сущности, представленной текущим объектом. |
| [set_CreationTime](./set_creationtime/)(DateTime) | Устанавливает время создания сущности, представленной текущим объектом, в локальном времени. |
| [set_CreationTimeUtc](./set_creationtimeutc/)(DateTime) | Устанавливает время создания сущности, представленной текущим объектом, в формате UTC. |
| [set_LastAccessTime](./set_lastaccesstime/)(DateTime) | Устанавливает время последнего доступа к сущности, представленной текущим объектом, в локальном времени. |
| [set_LastAccessTimeUtc](./set_lastaccesstimeutc/)(DateTime) | Устанавливает время последнего доступа к сущности, представленной текущим объектом, в формате UTC. |
| [set_LastWriteTime](./set_lastwritetime/)(DateTime) | Устанавливает время последней записи сущности, представленной текущим объектом, в локальном времени. |
| [set_LastWriteTimeUtc](./set_lastwritetimeutc/)(DateTime) | Устанавливает время последней записи сущности, представленной текущим объектом, в формате UTC. |
## См. также

* Class [Object](../../system/object/)
* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
