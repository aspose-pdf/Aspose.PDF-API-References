---
title: Class DocumentPrivilege
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Facades.DocumentPrivilege. Представляет привилегии для доступа к файлу Pdf. Смотрите PdfFileSecurity. Существует 4 способа использования этого класса: 1. Использование предопределенной привилегии напрямую. 2. На основе предопределенной привилегии и изменение некоторых специфических разрешений. 3. На основе предопределенной привилегии и изменение некоторых специфических комбинаций разрешений Adobe Professional. 4. Смешивает способ 2 и способ 3.
type: docs
weight: 4230
url: /ru/net/aspose.pdf.facades/documentprivilege/
---
## Класс DocumentPrivilege

Представляет привилегии для доступа к файлу Pdf. Смотрите [`PdfFileSecurity`](../pdffilesecurity/). Существует 4 способа использования этого класса: 1. Использование предопределенной привилегии напрямую. 2. На основе предопределенной привилегии и изменение некоторых специфических разрешений. 3. На основе предопределенной привилегии и изменение некоторых специфических комбинаций разрешений Adobe Professional. 4. Смешивает способ 2 и способ 3.

```csharp
public sealed class DocumentPrivilege : IComparable<object>
```

## Свойства

| Имя | Описание |
| --- | --- |
| static [AllowAll](../../aspose.pdf.facades/documentprivilege/allowall/) { get; } | Все разрешено. |
| static [Assembly](../../aspose.pdf.facades/documentprivilege/assembly/) { get; } | Разрешает сборку файла. |
| static [Copy](../../aspose.pdf.facades/documentprivilege/copy/) { get; } | Разрешает копирование файла. |
| static [DegradedPrinting](../../aspose.pdf.facades/documentprivilege/degradedprinting/) { get; } | Разрешает деградированную печать. |
| static [FillIn](../../aspose.pdf.facades/documentprivilege/fillin/) { get; } | Разрешает заполнение форм в файле. |
| static [ForbidAll](../../aspose.pdf.facades/documentprivilege/forbidall/) { get; } | Все запрещено. |
| static [ModifyAnnotations](../../aspose.pdf.facades/documentprivilege/modifyannotations/) { get; } | Разрешает изменение аннотаций файла. |
| static [ModifyContents](../../aspose.pdf.facades/documentprivilege/modifycontents/) { get; } | Разрешает изменение файла. |
| static [Print](../../aspose.pdf.facades/documentprivilege/print/) { get; } | Разрешает печать файла. |
| static [ScreenReaders](../../aspose.pdf.facades/documentprivilege/screenreaders/) { get; } | Разрешает чтение только на экране. |
| [AllowAssembly](../../aspose.pdf.facades/documentprivilege/allowassembly/) { get; set; } | Устанавливает разрешение, которое позволяет сборку или нет. true - разрешено, false - запрещено. |
| [AllowCopy](../../aspose.pdf.facades/documentprivilege/allowcopy/) { get; set; } | Устанавливает разрешение, которое позволяет копирование или нет. true - разрешено, false - запрещено. |
| [AllowDegradedPrinting](../../aspose.pdf.facades/documentprivilege/allowdegradedprinting/) { get; set; } | Устанавливает разрешение, которое позволяет деградированную печать или нет. true - разрешено, false - запрещено. |
| [AllowFillIn](../../aspose.pdf.facades/documentprivilege/allowfillin/) { get; set; } | Устанавливает разрешение, которое позволяет заполнение форм или нет. true - разрешено, false - запрещено. |
| [AllowModifyAnnotations](../../aspose.pdf.facades/documentprivilege/allowmodifyannotations/) { get; set; } | Устанавливает разрешение, которое позволяет изменение аннотаций или нет. true - разрешено, false - запрещено. |
| [AllowModifyContents](../../aspose.pdf.facades/documentprivilege/allowmodifycontents/) { get; set; } | Устанавливает разрешение, которое позволяет изменение содержимого или нет. true - разрешено, false - запрещено. |
| [AllowPrint](../../aspose.pdf.facades/documentprivilege/allowprint/) { get; set; } | Устанавливает разрешение, которое позволяет печать или нет. true - разрешено, false - запрещено. |
| [AllowScreenReaders](../../aspose.pdf.facades/documentprivilege/allowscreenreaders/) { get; set; } | Устанавливает разрешение, которое позволяет экранным считывателям или нет. true - разрешено, false - запрещено. |
| [ChangeAllowLevel](../../aspose.pdf.facades/documentprivilege/changeallowlevel/) { get; set; } | Получает и устанавливает уровень изменения привилегий документа. Так же, как настройки Изменения разрешены в Adobe Professional. 0: Нет. 1: Вставка, удаление и поворот страниц. 2: Заполнение полей формы и подписание существующих полей подписи. 3: Комментирование, заполнение полей формы и подписание существующих полей подписи. 4: Любое, кроме извлечения страниц. |
| [CopyAllowLevel](../../aspose.pdf.facades/documentprivilege/copyallowlevel/) { get; set; } | Получает и устанавливает уровень копирования привилегий документа. Так же, как настройки разрешений Adobe Professional. 0: Нет. 1: Включить доступ к тексту для устройств экранного чтения для людей с нарушениями зрения. 2: Включить копирование текста, изображений и другого содержимого. |
| [PrintAllowLevel](../../aspose.pdf.facades/documentprivilege/printallowlevel/) { get; set; } | Получает и устанавливает уровень печати привилегий документа. Так же, как настройки Разрешенная печать в Adobe Professional. 0: Нет. 1: Низкое разрешение (150 dpi). 2: Высокое разрешение. |

## Методы

| Имя | Описание |
| --- | --- |
| [CompareTo](../../aspose.pdf.facades/documentprivilege/compareto/)(object) | Сравнивает два объекта `DocumentPrivilege`. Объект для сравнения. Целое число со знаком, которое указывает относительные значения этого экземпляра и значения. Меньше нуля - этот экземпляр меньше значения. Ноль - этот экземпляр равен значению. Больше нуля - этот экземпляр больше значения. |

## Примеры

```csharp
[C#]	
//Way1: Using predefined privilege directly.
DocumentPrivilege privilege = DocumentPrivilege.Print;

//Way2: Based on a predefined privilege and change some specifical permissions.
DocumentPrivilege privilege = DocumentPrivilege.AllowAll;
privilege.AllowPrint = false;
privilege.AllowModifyContents = false;

//Way3: Based on a predefined privilege and change some specifical Adobe Professional permissions combination.
DocumentPrivilege privilege = DocumentPrivilege.ForbidAll;
privilege.ChangeAllowLevel = 1;
privilege.PrintAllowLevel = 2;

//Way4: Mixes the way2 and way3
DocumentPrivilege privilege = DocumentPrivilege.ForbidAll;
privilege.ChangeAllowLevel = 1;
privilege.AllowPrint = true;

[Visual Basic]
'Way1: Using predefined privilege directly.
Dim privilege As DocumentPrivilege =  DocumentPrivilege.Print 

'Way2: Based on a predefined privilege and change some specifical permissions.
Dim privilege As DocumentPrivilege =  DocumentPrivilege.AllowAll 
privilege.AllowPrint = False
privilege.AllowModifyContents = False

'Way3: Based on a predefined privilege and change some specifical Adobe Professional permissions combination.
Dim privilege As DocumentPrivilege =  DocumentPrivilege.ForbidAll 
privilege.ChangeAllowLevel = 1
privilege.PrintAllowLevel = 2

'Way4: Mixes the way2 and way3
Dim privilege As DocumentPrivilege =  DocumentPrivilege.ForbidAll 
privilege.ChangeAllowLevel = 1
privilege.AllowPrint = True
```

### См. также

* пространство имен [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../)