---
title: "Aspose::Pdf::License::SetLicense метод"
linktitle: "SetLicense"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::License::SetLicense метод. Лицензирует компонент в C++."
type: docs
weight: 600
url: /ru/cpp/aspose.pdf/license/setlicense/
---
## License::SetLicense(const System::SharedPtr\<System::IO::Stream\>\&) method


Лицензирует компонент.

```cpp
void Aspose::Pdf::License::SetLicense(const System::SharedPtr<System::IO::Stream> &stream)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| поток | const System::SharedPtr\<System::IO::Stream\>\& | Поток, содержащий лицензию. |
## Примечания



Используйте этот метод для загрузки лицензии из потока.

[Java] void setLicense(java.io.InputStream stream) 
## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [License](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## License::SetLicense(const System::String\&) method


Лицензирует компонент.

```cpp
void Aspose::Pdf::License::SetLicense(const System::String &licenseName)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| licenseName | const System::String\& | Может быть полным или коротким именем файла или именем встроенного ресурса. Используйте пустую строку для перехода в режим оценки. |
## Примечания


Пытается найти лицензию в следующих местах:

1. Явный путь.

2. Папка, содержащая сборку компонента **Aspose**.

3. Папка, содержащая вызывающую сборку клиента.

4. Папка, содержащая входную (запускную) сборку.

5. Встроенный ресурс в вызывающей сборке клиента.

**[Note](../../note/):**On the .NET Compact Framework, tries to find the license only in these locations:

1. Явный путь.

2. Встроенный ресурс в вызывающей сборке клиента.

[Java] 

2. Папка, содержащая JAR‑файл компонента **Aspose**.

3. Папка, содержащая вызывающий JAR‑файл клиента.

## См. также

* Class [String](../../../system/string/)
* Class [License](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
