---
title: DocumentPrivilege
second_title: Aspose.PDF для справочника API .NET
description: Представляет привилегии для доступа к файлу Pdf. См.PdfFileSecurity./pdffilesecurity. Существует 4 способа использования этого класса 1. Прямое использование предопределенных привилегий. 2. На основе предопределенных привилегий и изменения некоторых конкретных разрешений. 3. На основе предопределенных привилегий и изменения некоторых конкретных комбинаций разрешений Adobe Professional. 4. Смешивает путь2 и путь3.
type: docs
weight: 2240
url: /ru/net/aspose.pdf.facades/documentprivilege/
---
## DocumentPrivilege class

Представляет привилегии для доступа к файлу Pdf. См.[`PdfFileSecurity`](../pdffilesecurity). Существует 4 способа использования этого класса: 1. Прямое использование предопределенных привилегий. 2. На основе предопределенных привилегий и изменения некоторых конкретных разрешений. 3. На основе предопределенных привилегий и изменения некоторых конкретных комбинаций разрешений Adobe Professional. 4. Смешивает путь2 и путь3.

```csharp
public sealed class DocumentPrivilege : IComparable<object>
```

## Характеристики

| Имя | Описание |
| --- | --- |
| static [AllowAll](../../aspose.pdf.facades/documentprivilege/allowall) { get; } | Все разрешено. |
| static [Assembly](../../aspose.pdf.facades/documentprivilege/assembly) { get; } | Позволяет собирать файл. |
| static [Copy](../../aspose.pdf.facades/documentprivilege/copy) { get; } | Позволяет копировать файл. |
| static [DegradedPrinting](../../aspose.pdf.facades/documentprivilege/degradedprinting) { get; } | Разрешает печать с ухудшением качества. |
| static [FillIn](../../aspose.pdf.facades/documentprivilege/fillin) { get; } | Позволяет заполнять формы в файле. |
| static [ForbidAll](../../aspose.pdf.facades/documentprivilege/forbidall) { get; } | Все запрещено. |
| static [ModifyAnnotations](../../aspose.pdf.facades/documentprivilege/modifyannotations) { get; } | Позволяет изменять аннотации файла. |
| static [ModifyContents](../../aspose.pdf.facades/documentprivilege/modifycontents) { get; } | Позволяет изменять файл. |
| static [Print](../../aspose.pdf.facades/documentprivilege/print) { get; } | Позволяет распечатать файл. |
| static [ScreenReaders](../../aspose.pdf.facades/documentprivilege/screenreaders) { get; } | Позволяет читать только на экране. |
| [AllowAssembly](../../aspose.pdf.facades/documentprivilege/allowassembly) { get; set; } | Устанавливает разрешение, разрешающее сборку или нет. true разрешает, false запрещает. |
| [AllowCopy](../../aspose.pdf.facades/documentprivilege/allowcopy) { get; set; } | Устанавливает разрешение, разрешающее или запрещающее копирование. true разрешает, false запрещает. |
| [AllowDegradedPrinting](../../aspose.pdf.facades/documentprivilege/allowdegradedprinting) { get; set; } | Устанавливает разрешение, разрешающее печать с ухудшением качества или нет. true разрешает, false запрещает. |
| [AllowFillIn](../../aspose.pdf.facades/documentprivilege/allowfillin) { get; set; } | Устанавливает разрешение, позволяющее заполнять формы или нет. true разрешает, false запрещает. |
| [AllowModifyAnnotations](../../aspose.pdf.facades/documentprivilege/allowmodifyannotations) { get; set; } | Устанавливает разрешение, позволяющее изменять аннотации или нет. true разрешает, false запрещает. |
| [AllowModifyContents](../../aspose.pdf.facades/documentprivilege/allowmodifycontents) { get; set; } | Устанавливает разрешение, позволяющее изменять содержимое или нет. true разрешает, false запрещает. |
| [AllowPrint](../../aspose.pdf.facades/documentprivilege/allowprint) { get; set; } | Устанавливает разрешение, позволяющее печатать или нет. true разрешает, false запрещает. |
| [AllowScreenReaders](../../aspose.pdf.facades/documentprivilege/allowscreenreaders) { get; set; } | Устанавливает разрешение, разрешающее или запрещающее чтение с экрана. true разрешает, false запрещает. |
| [ChangeAllowLevel](../../aspose.pdf.facades/documentprivilege/changeallowlevel) { set; } | Устанавливает уровень изменения привилегий документа. Так же, как настройки разрешенных изменений Adobe Professional. 0:Нет. 1:Вставка, удаление и поворот страниц. 2:Заполнение полей формы и подписание существующих полей подписи. 3:Комментирование, заполнение полей формы и подписание существующих полей подписи. 4:Любые, кроме извлечения страниц. |
| [CopyAllowLevel](../../aspose.pdf.facades/documentprivilege/copyallowlevel) { set; } | Устанавливает уровень прав копирования документа. Так же, как настройки разрешений Adobe Professional. 0:Нет. 1:Разрешить доступ к тексту для устройств чтения с экрана для слабовидящих. 2:Включить копирование текста, изображений и другого контента. |
| [PrintAllowLevel](../../aspose.pdf.facades/documentprivilege/printallowlevel) { set; } | Устанавливает уровень привилегий печати документа. Так же, как настройки разрешенной печати Adobe Professional. 0:Нет. 1:Низкое разрешение (150 dpi). 2:Высокое разрешение. |

## Методы

| Имя | Описание |
| --- | --- |
| [CompareTo](../../aspose.pdf.facades/documentprivilege/compareto)(object) | Сравнивает два объекта[`DocumentPrivilege`](../documentprivilege).  Объект для сравнения.  Целое число со знаком, указывающее относительные значения этого экземпляра и значения. Меньше нуля этот экземпляр меньше значения. Ноль этого экземпляра равен значению. Больше нуля этот экземпляр больше значения. |

### Примеры

```csharp
[C#]	
 //Способ 1: прямое использование предопределенной привилегии.
DocumentPrivilege privilege = DocumentPrivilege.Print;

 //Способ 2: на основе предопределенной привилегии и изменения некоторых конкретных разрешений.
DocumentPrivilege privilege = DocumentPrivilege.AllowAll;
privilege.AllowPrint = false;
privilege.AllowModifyContents = false;

//Способ 3: на основе предопределенной привилегии и изменения определенной комбинации разрешений Adobe Professional.
DocumentPrivilege privilege = DocumentPrivilege.ForbidAll;
privilege.ChangeAllowLevel = 1;
privilege.PrintAllowLevel = 2;

 //Way4: смешивает way2 и way3
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

### Смотрите также

* пространство имен [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* сборка [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
