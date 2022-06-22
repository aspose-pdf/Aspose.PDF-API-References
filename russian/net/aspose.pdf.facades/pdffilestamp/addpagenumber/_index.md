---
title: AddPageNumber
second_title: Aspose.PDF для справочника API .NET
description: Добавить номер страницы в файл. Текст номера страницы может содержать знак  который будет заменен номером страницы. Номер страницы помещается внизу страницы по центру по горизонтали.
type: docs
weight: 170
url: /ru/net/aspose.pdf.facades/pdffilestamp/addpagenumber/
---
## AddPageNumber(string) {#addpagenumber_4}

Добавить номер страницы в файл. Текст номера страницы может содержать знак #, который будет заменен номером страницы. Номер страницы помещается внизу страницы по центру по горизонтали.

```csharp
public void AddPageNumber(string formatString)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| formatString | String | Текст номера страницы |

### Примеры

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #");
fileStamp.Close();
```

### Смотрите также

* class [PdfFileStamp](../../pdffilestamp)
* пространство имен [Aspose.Pdf.Facades](../../pdffilestamp)
* сборка [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText) {#addpagenumber}

Добавляет номер страницы к странице. Номер страницы может содержать знак #, который будет заменен номером страницы. Номер страницы помещается внизу страницы по центру по горизонтали.

```csharp
public void AddPageNumber(FormattedText formattedText)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| formattedText | FormattedText | Строка формата для номера страницы представляется как FormattedText. |

### Примеры

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page #"));
fileStamp.Close();
```

### Смотрите также

* class [FormattedText](../../formattedtext)
* class [PdfFileStamp](../../pdffilestamp)
* пространство имен [Aspose.Pdf.Facades](../../pdffilestamp)
* сборка [Aspose.PDF](../../../)

---

## AddPageNumber(string, int, float, float, float, float) {#addpagenumber_6}

Добавляет номер страницы к страницам документа.

```csharp
public void AddPageNumber(string formatString, int position, float leftMargin, float rightMargin, 
    float topMargin, float bottomMargin)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| formatString | String | Строка формата для номера страницы. |
| position | Int32 | Позиция, в которой будет размещен номер страницы на странице. 0-нижний средний, 1-нижний правый, 2-верхний правый, 3 - боковые справа, 4 - верхний средний, 5 - нижний левый, 6 - боковые левые, 7 - верхний левый. Можно использовать следующие константы: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |
| leftMargin | Single | Поле на левом краю страницы. |
| rightMargin | Single | Поле по правому краю страницы. |
| topMargin | Single | Поле по верхнему краю страницы. |
| bottomMargin | Single | Поле по нижнему краю страницы. |

### Примеры

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #", PdfFileStamp.PosBottomLeft, 100, 100, 200, 200);
fileStamp.Close();
```

### Смотрите также

* class [PdfFileStamp](../../pdffilestamp)
* пространство имен [Aspose.Pdf.Facades](../../pdffilestamp)
* сборка [Aspose.PDF](../../../)

---

## AddPageNumber(string, float, float) {#addpagenumber_7}

Добавляет номер страницы в указанной позиции на странице.

```csharp
public void AddPageNumber(string formatString, float x, float y)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| formatString | String | Строка формата. Строка формата может содержать знак #, который будет заменен номером страницы. |
| x | Single | X координата номера страницы. |
| y | Single | Y координата номера страницы. |

### Примеры

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page  #"), 123, 357);
fileStamp.Close();
```

### Смотрите также

* class [PdfFileStamp](../../pdffilestamp)
* пространство имен [Aspose.Pdf.Facades](../../pdffilestamp)
* сборка [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText, int, float, float, float, float) {#addpagenumber_2}

Добавляет номер страницы к страницам документа.

```csharp
public void AddPageNumber(FormattedText formattedText, int position, float leftMargin, 
    float rightMargin, float topMargin, float bottomMargin)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| formattedText | FormattedText | FormattedText Объект, представляющий формат номера страницы и свойства текста. |
| position | Int32 | Позиция, в которой будет размещен номер страницы на странице. 0-нижний средний, 1-нижний правый, 2-верхний правый, 3 - боковые справа, 4 - верхний средний, 5 - нижний левый, 6 - боковые левые, 7 - верхний левый. Можно использовать следующие константы: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |
| leftMargin | Single | Поле на левом краю страницы. |
| rightMargin | Single | Поле по правому краю страницы. |
| topMargin | Single | Поле по верхнему краю страницы. |
| bottomMargin | Single | Поле по нижнему краю страницы. |

### Примеры

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page #"), PdfFileStamp.PosBottomLeft, 100, 100, 200, 200);
fileStamp.Close();
```

### Смотрите также

* class [FormattedText](../../formattedtext)
* class [PdfFileStamp](../../pdffilestamp)
* пространство имен [Aspose.Pdf.Facades](../../pdffilestamp)
* сборка [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText, float, float) {#addpagenumber_3}

Добавляет номер страницы в указанной позиции на странице.

```csharp
public void AddPageNumber(FormattedText formattedText, float x, float y)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| formattedText | FormattedText | Форматированный текст, который представляет формат номера страницы и свойства текста. Строка формата может содержать знак #, который будет заменен номером страницы. |
| x | Single | X координата номера страницы. |
| y | Single | Y координата номера страницы. |

### Примеры

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page  #"), 123, 357);
fileStamp.Close();
```

### Смотрите также

* class [FormattedText](../../formattedtext)
* class [PdfFileStamp](../../pdffilestamp)
* пространство имен [Aspose.Pdf.Facades](../../pdffilestamp)
* сборка [Aspose.PDF](../../../)

---

## AddPageNumber(string, int) {#addpagenumber_5}

Добавляет номер страницы к страницам.

```csharp
public void AddPageNumber(string formatString, int position)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| formatString | String | Формат номера страницы. Этот текст может содержать #, который будет заменен номером страницы. |
| position | Int32 | Позиция, в которой будет размещен номер страницы на странице. 0-нижний средний, 1-нижний правый, 2-верхний правый, 3 - боковые справа, 4 - верхний средний, 5 - нижний левый, 6 - боковые левые, 7 - верхний левый. Можно использовать следующие константы: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |

### Примеры

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #", PdfFileStamp.PosUpperRight);
fileStamp.Close();
```

### Смотрите также

* class [PdfFileStamp](../../pdffilestamp)
* пространство имен [Aspose.Pdf.Facades](../../pdffilestamp)
* сборка [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText, int) {#addpagenumber_1}

Добавляет номер страницы к страницам.

```csharp
public void AddPageNumber(FormattedText formattedText, int position)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| formattedText | FormattedText | FormattedText Объект, содержащий формат номера страницы и свойства текста. Этот текст может содержать #, который будет заменен номером страницы. |
| position | Int32 | Позиция, в которой будет размещен номер страницы на странице. 0-нижний средний, 1-нижний правый, 2-верхний правый, 3 - боковые справа, 4 - верхний средний, 5 - нижний левый, 6 - боковые левые, 7 - верхний левый. Можно использовать следующие константы: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |

### Примеры

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #", PdfFileStamp.PosUpperRight);
fileStamp.Close();
```

### Смотрите также

* class [FormattedText](../../formattedtext)
* class [PdfFileStamp](../../pdffilestamp)
* пространство имен [Aspose.Pdf.Facades](../../pdffilestamp)
* сборка [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
