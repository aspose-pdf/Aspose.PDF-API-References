---
title: AddPageNumber
second_title: Aspose.PDF для справочника API .NET
description: Добавить номер страницы в файл. Текст номера страницы может содержать знак  который будет заменен номером страницы. Номер страницы размещается внизу страницы по центру горизонтально.
type: docs
weight: 170
url: /ru/net/aspose.pdf.facades/pdffilestamp/addpagenumber/
---
## AddPageNumber(string) {#addpagenumber_4}

Добавить номер страницы в файл. Текст номера страницы может содержать знак #, который будет заменен номером страницы. Номер страницы размещается внизу страницы по центру горизонтально.

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
| formattedText | FormattedText | Строка формата для номера страницы представлена как FormattedText. |

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
| position | Int32 | Позиция, в которой номер страницы будет размещен на странице. 0-внизу посередине, 1-внизу справа, 2-вверху справа, 3-боки справа, 4-вверху посередине,5-внизу слева,6-боки слева,7-вверху слева. Можно использовать следующие константы: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |
| leftMargin | Single | Поля по левому краю страницы. |
| rightMargin | Single | Поля по правому краю страницы. |
| topMargin | Single | Поля по верхнему краю страницы. |
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

Добавляет номер страницы в указанную позицию на странице.

```csharp
public void AddPageNumber(string formatString, float x, float y)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| formatString | String | Строка формата. Строка формата может содержать знак #, который будет заменен номером страницы. |
| x | Single | X-координата номера страницы. |
| y | Single | Координата Y номера страницы. |

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
| formattedText | FormattedText | Объект FormattedText, который представляет формат номера страницы и свойства текста. |
| position | Int32 | Позиция, в которой номер страницы будет размещен на странице. 0-внизу посередине, 1-внизу справа, 2-вверху справа, 3-боки справа, 4-вверху посередине,5-внизу слева,6-боки слева,7-вверху слева. Можно использовать следующие константы: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |
| leftMargin | Single | Поля по левому краю страницы. |
| rightMargin | Single | Поля по правому краю страницы. |
| topMargin | Single | Поля по верхнему краю страницы. |
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

Добавляет номер страницы в указанную позицию на странице.

```csharp
public void AddPageNumber(FormattedText formattedText, float x, float y)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| formattedText | FormattedText | Форматированный текст, который представляет формат номера страницы и свойства текста. Строка формата может содержать знак #, который будет заменен номером страницы. |
| x | Single | X-координата номера страницы. |
| y | Single | Координата Y номера страницы. |

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
| position | Int32 | Позиция, в которой номер страницы будет размещен на странице. 0-внизу посередине, 1-внизу справа, 2-вверху справа, 3-боки справа, 4-вверху посередине,5-внизу слева,6-боки слева,7-вверху слева. Можно использовать следующие константы: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |

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
| formattedText | FormattedText | Объект FormattedText, который содержит формат номера страницы и свойства текста. Этот текст может содержать #, который будет заменен номером страницы. |
| position | Int32 | Позиция, в которой номер страницы будет размещен на странице. 0-внизу посередине, 1-внизу справа, 2-вверху справа, 3-боки справа, 4-вверху посередине,5-внизу слева,6-боки слева,7-вверху слева. Можно использовать следующие константы: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |

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
