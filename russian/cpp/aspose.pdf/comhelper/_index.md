---
title: "Aspose::Pdf::ComHelper класс"
linktitle: "ComHelper"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::ComHelper класс. Предоставляет методы для COM‑клиентов для загрузки документа в Aspose.Pdf на C++."
type: docs
weight: 3100
url: /ru/cpp/aspose.pdf/comhelper/
---
## ComHelper class


Предоставляет методы для COM‑клиентов для загрузки документа в [Aspose.Pdf](../).

```cpp
class ComHelper : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [OpenFile](./openfile/)(const System::String\&) | Просто создайте и верните [Document](../document/), используя *filename*. То же самое, что [Document(Stream)](../). |
| [OpenFile](./openfile/)(const System::String\&, const System::String\&) | Инициализируйте и верните новый экземпляр класса [Document](../document/) для работы с зашифрованным документом. |
| [OpenFile](./openfile/)(const System::String\&, const System::String\&, bool) | Инициализируйте новый экземпляр класса [Document](../document/) для работы с зашифрованным документом. |
| [OpenFile](./openfile/)(const System::String\&, const System::SharedPtr\<LoadOptions\>\&) | Откройте существующий документ из файла, предоставив необходимые параметры преобразования для получения PDF‑документа. |
| [OpenStream](./openstream/)(const System::SharedPtr\<System::IO::Stream\>\&) | Инициализируйте и верните новый экземпляр [Document](../document/) из *input* потока. |
| [OpenStream](./openstream/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&) | Инициализируйте и верните новый экземпляр [Document](../document/) из *input* потока. |
| [OpenStream](./openstream/)(const System::SharedPtr\<System::IO::Stream\>\&, bool) | Инициализируйте и верните новый экземпляр [Document](../document/) из *input* потока. |
| [OpenStream](./openstream/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&, bool) | Инициализируйте и верните новый экземпляр [Document](../document/) из *input* потока. |
| [OpenStream](./openstream/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<LoadOptions\>\&) | Откройте и верните существующий документ из потока, предоставив необходимые преобразования для получения PDF‑документа. |
## Примечания


Используйте класс [ComHelper](./) для загрузки документа из файла или потока в объект [Document](../document/) в COM‑приложении. Класс [Document](../document/) предоставляет конструктор по умолчанию для создания нового документа, а также перегруженные конструкторы для загрузки документа из файла или потока. Если вы используете Aspose.Words в .NET‑приложении, вы можете напрямую использовать все конструкторы [Document](../document/), но если вы используете [Aspose.Pdf](../) в COM‑приложении, доступен только конструктор [Document](../document/) по умолчанию.
## См. также

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
