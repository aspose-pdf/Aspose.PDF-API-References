---
title: "Класс DocumentPrivilege"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Aspose.Pdf.Facades.DocumentPrivilege class. Представляет привилегии для доступа к файлу Pdf. См. PdfFileSecurity. Существует 4 способа использования этого класса: 1. Использовать предопределённую привилегию напрямую. 2. На основе предопределённой привилегии изменить некоторые конкретные разрешения. 3. На основе предопределённой привилегии изменить комбинацию некоторых конкретных разрешений Adobe Professional. 4. Сочетать способ 2 и способ 3."
type: docs
weight: 4350
url: /ru/net/aspose.pdf.facades/documentprivilege/
---
## DocumentPrivilege class

Представляет привилегии для доступа к PDF‑файлу. См. [`PdfFileSecurity`](../pdffilesecurity/). Существует 4 способа использования этого класса: 1. Использовать предопределённую привилегию напрямую. 2. На основе предопределённой привилегии изменить некоторые конкретные разрешения. 3. На основе предопределённой привилегии изменить комбинацию конкретных разрешений Adobe Professional. 4. Смешать способ2 и способ3.

```csharp
public sealed class DocumentPrivilege : IComparable<object>
```

## Свойства

| Имя | Описание |
| --- | --- |
| static [AllowAll](../../aspose.pdf.facades/documentprivilege/allowall/) { get; } | Все разрешено. |
| static [Assembly](../../aspose.pdf.facades/documentprivilege/assembly/) { get; } | Разрешает сборку файла. |
| static [Copy](../../aspose.pdf.facades/documentprivilege/copy/) { get; } | Разрешает копирование файла. |
| static [DegradedPrinting](../../aspose.pdf.facades/documentprivilege/degradedprinting/) { get; } | Разрешает печать с пониженным качеством. |
| static [FillIn](../../aspose.pdf.facades/documentprivilege/fillin/) { get; } | Разрешает заполнение форм в файле. |
| static [ForbidAll](../../aspose.pdf.facades/documentprivilege/forbidall/) { get; } | Все запрещено. |
| static [ModifyAnnotations](../../aspose.pdf.facades/documentprivilege/modifyannotations/) { get; } | Разрешает изменение аннотаций файла. |
| static [ModifyContents](../../aspose.pdf.facades/documentprivilege/modifycontents/) { get; } | Разрешает изменение файла. |
| static [Print](../../aspose.pdf.facades/documentprivilege/print/) { get; } | Разрешает печать файла. |
| static [ScreenReaders](../../aspose.pdf.facades/documentprivilege/screenreaders/) { get; } | Разрешает только чтение на экране. |
| [AllowAssembly](../../aspose.pdf.facades/documentprivilege/allowassembly/) { get; set; } | Устанавливает разрешение, позволяющее сборку или нет. true — разрешено, false — запрещено. |
| [AllowCopy](../../aspose.pdf.facades/documentprivilege/allowcopy/) { get; set; } | Устанавливает разрешение, позволяющее копирование или нет. true — разрешено, false — запрещено. |
| [AllowDegradedPrinting](../../aspose.pdf.facades/documentprivilege/allowdegradedprinting/) { get; set; } | Устанавливает разрешение, позволяющее печать с пониженным качеством или нет. true — разрешено, false — запрещено. |
| [AllowFillIn](../../aspose.pdf.facades/documentprivilege/allowfillin/) { get; set; } | Устанавливает разрешение, позволяющее заполнение форм или нет. true — разрешено, false — запрещено. |
| [AllowModifyAnnotations](../../aspose.pdf.facades/documentprivilege/allowmodifyannotations/) { get; set; } | Устанавливает разрешение, позволяющее изменение аннотаций или нет. true — разрешено, false — запрещено. |
| [AllowModifyContents](../../aspose.pdf.facades/documentprivilege/allowmodifycontents/) { get; set; } | Устанавливает разрешение, позволяющее изменение содержимого или нет. true — разрешено, false — запрещено. |
| [AllowPrint](../../aspose.pdf.facades/documentprivilege/allowprint/) { get; set; } | Устанавливает разрешение, позволяющее печать или нет. true — разрешено, false — запрещено. |
| [AllowScreenReaders](../../aspose.pdf.facades/documentprivilege/allowscreenreaders/) { get; set; } | Устанавливает разрешение, позволяющее использование экранных читалок или нет. true — разрешено, false — запрещено. |
| [ChangeAllowLevel](../../aspose.pdf.facades/documentprivilege/changeallowlevel/) { get; set; } | Получает и задает уровень изменения привилегий Document. Точно так же, как настройки Changes Allowed в Adobe Professional. 0: Нет. 1: Вставка, удаление и вращение страниц. 2: Заполнение полей форм и подпись существующих полей подписи. 3: Комментирование, заполнение полей форм и подпись существующих полей подписи. 4: Всё, кроме извлечения страниц. |
| [CopyAllowLevel](../../aspose.pdf.facades/documentprivilege/copyallowlevel/) { get; set; } | Получает и задает уровень копирования привилегий Document. Точно так же, как настройки разрешений в Adobe Professional. 0: Нет. 1: Разрешить доступ к тексту для устройств экранных читалок для людей с нарушением зрения. 2: Разрешить копирование текста, изображений и другого контента. |
| [PrintAllowLevel](../../aspose.pdf.facades/documentprivilege/printallowlevel/) { get; set; } | Получает и задает уровень печати привилегий Document. Точно так же, как настройки Printing Allowed в Adobe Professional. 0: Нет. 1: Низкое разрешение (150 dpi). 2: Высокое разрешение. |

## Методы

| Имя | Описание |
| --- | --- |
| [CompareTo](../../aspose.pdf.facades/documentprivilege/compareto/)(object) | Сравнивает два объекта `DocumentPrivilege`.  Объект, с которым сравнивают. Подписанное целое число, указывающее относительные значения этого экземпляра и значения. Менее нуля этот экземпляр меньше значения. Ноль — экземпляр равен значению. Больше нуля этот экземпляр больше значения. |

## Примеры

```csharp
[C#]	
//Способ1: Использовать предопределённую привилегию напрямую.
DocumentPrivilege privilege = DocumentPrivilege.Print;

//Способ2: На основе предопределённой привилегии изменить некоторые конкретные разрешения.
DocumentPrivilege privilege = DocumentPrivilege.AllowAll;
privilege.AllowPrint = false;
privilege.AllowModifyContents = false;

//Way3: На основе предопределённой привилегии и изменяет некоторую специфическую комбинацию разрешений Adobe Professional.
DocumentPrivilege privilege = DocumentPrivilege.ForbidAll;
privilege.ChangeAllowLevel = 1;
privilege.PrintAllowLevel = 2;

//Way4: Сочетает way2 и way3
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

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


