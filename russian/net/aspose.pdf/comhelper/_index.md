---
title: Class ComHelper
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.ComHelper. Предоставляет методы для COM-клиентов для загрузки документа в Aspose.Pdf
type: docs
weight: 3130
url: /ru/net/aspose.pdf/comhelper/
---
## Класс ComHelper

Предоставляет методы для COM-клиентов для загрузки документа в Aspose.Pdf.

```csharp
public class ComHelper
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [ComHelper](comhelper/)() | Конструктор по умолчанию. |

## Методы

| Имя | Описание |
| --- | --- |
| [OpenFile](../../aspose.pdf/comhelper/openfile/#openfile)(string) | Просто создайте и верните Document, используя *filename*. То же самое, что и [`Document`](../document/document/). |
| [OpenFile](../../aspose.pdf/comhelper/openfile/#openfile_1)(string, LoadOptions) | Откройте существующий документ из файла, предоставив необходимые параметры конвертации для получения pdf документа. |
| [OpenFile](../../aspose.pdf/comhelper/openfile/#openfile_2)(string, string) | Инициализируйте и верните новый экземпляр класса [`Document`](../document/) для работы с зашифрованным документом. |
| [OpenFile](../../aspose.pdf/comhelper/openfile/#openfile_3)(string, string, bool) | Инициализируйте новый экземпляр класса [`Document`](../document/) для работы с зашифрованным документом. |
| [OpenStream](../../aspose.pdf/comhelper/openstream/#openstream)(Stream) | Инициализируйте и верните новый экземпляр Document из *входного* потока. |
| [OpenStream](../../aspose.pdf/comhelper/openstream/#openstream_2)(Stream, bool) | Инициализируйте и верните новый экземпляр Document из *входного* потока. |
| [OpenStream](../../aspose.pdf/comhelper/openstream/#openstream_1)(Stream, LoadOptions) | Откройте и верните существующий документ из потока, предоставив необходимые параметры конвертации для получения pdf документа. |
| [OpenStream](../../aspose.pdf/comhelper/openstream/#openstream_3)(Stream, string) | Инициализируйте и верните новый экземпляр Document из *входного* потока. |
| [OpenStream](../../aspose.pdf/comhelper/openstream/#openstream_4)(Stream, string, bool) | Инициализируйте и верните новый экземпляр Document из *входного* потока. |

## Замечания

Используйте класс ComHelper для загрузки документа из файла или потока в объект Document в COM-приложении. Класс Document предоставляет конструктор по умолчанию для создания нового документа, а также предоставляет перегруженные конструкторы для загрузки документа из файла или потока. Если вы используете Aspose.Words из .NET-приложения, вы можете использовать все конструкторы Document напрямую, но если вы используете Aspose.Pdf из COM-приложения, доступен только конструктор Document по умолчанию.

### См. также

* пространство имен [Aspose.Pdf](../../aspose.pdf/)
* сборка [Aspose.PDF](../../)