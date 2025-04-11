---
title: PdfFileStamp.AddPageNumber
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfFileStamp. Добавить номер страницы в файл. Текст номера страницы может содержать знак #, который будет заменен на номер страницы. Номер страницы размещается внизу страницы по центру.
type: docs
weight: 130
url: /ru/net/aspose.pdf.facades/pdffilestamp/addpagenumber/
---
## AddPageNumber(string) {#addpagenumber_4}

Добавляет номер страницы в файл. Текст номера страницы может содержать знак #, который будет заменен на номер страницы. Номер страницы размещается внизу страницы по центру.

```csharp
public void AddPageNumber(string formatString)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| formatString | String | Текст номера страницы |

## Примеры

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #");
fileStamp.Close();
```

### См. также

* класс [PdfFileStamp](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText) {#addpagenumber}

Добавляет номер страницы на страницу. Номер страницы может содержать знак #, который будет заменен на номер страницы. Номер страницы размещается внизу страницы по центру.

```csharp
public void AddPageNumber(FormattedText formattedText)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| formattedText | FormattedText | Форматированная строка для номера страницы, представленная как FormattedText. |

## Примеры

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page #"));
fileStamp.Close();
```

### См. также

* класс [FormattedText](../../formattedtext/)
* класс [PdfFileStamp](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## AddPageNumber(string, int, float, float, float, float) {#addpagenumber_6}

Добавляет номер страницы на страницы документа.

```csharp
public void AddPageNumber(string formatString, int position, float leftMargin, float rightMargin, 
    float topMargin, float bottomMargin)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| formatString | String | Форматированная строка для номера страницы. |
| position | Int32 | Позиция, где будет размещен номер страницы. 0 - внизу по центру, 1 - внизу справа, 2 - вверху справа, 3 - справа по бокам, 4 - вверху по центру, 5 - внизу слева, 6 - слева по бокам, 7 - вверху слева. Вы можете использовать следующие константы: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |
| leftMargin | Single | Поля на левом краю страницы. |
| rightMargin | Single | Поля на правом краю страницы. |
| topMargin | Single | Поля на верхнем крае страницы. |
| bottomMargin | Single | Поля на нижнем крае страницы. |

## Примеры

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #", PdfFileStamp.PosBottomLeft, 100, 100, 200, 200);
fileStamp.Close();
```

### См. также

* класс [PdfFileStamp](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## AddPageNumber(string, float, float) {#addpagenumber_7}

Добавляет номер страницы в указанной позиции на странице.

```csharp
public void AddPageNumber(string formatString, float x, float y)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| formatString | String | Форматированная строка. Форматированная строка может содержать знак #, который будет заменен на номер страницы. |
| x | Single | Координата X номера страницы. |
| y | Single | Координата Y номера страницы. |

## Примеры

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page  #"), 123, 357);
fileStamp.Close();
```

### См. также

* класс [PdfFileStamp](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText, int, float, float, float, float) {#addpagenumber_2}

Добавляет номер страницы на страницы документа.

```csharp
public void AddPageNumber(FormattedText formattedText, int position, float leftMargin, 
    float rightMargin, float topMargin, float bottomMargin)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| formattedText | FormattedText | Объект FormattedText, который представляет формат номера страницы и свойства текста. |
| position | Int32 | Позиция, где будет размещен номер страницы. 0 - внизу по центру, 1 - внизу справа, 2 - вверху справа, 3 - справа по бокам, 4 - вверху по центру, 5 - внизу слева, 6 - слева по бокам, 7 - вверху слева. Вы можете использовать следующие константы: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |
| leftMargin | Single | Поля на левом крае страницы. |
| rightMargin | Single | Поля на правом крае страницы. |
| topMargin | Single | Поля на верхнем крае страницы. |
| bottomMargin | Single | Поля на нижнем крае страницы. |

## Примеры

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page #"), PdfFileStamp.PosBottomLeft, 100, 100, 200, 200);
fileStamp.Close();
```

### См. также

* класс [FormattedText](../../formattedtext/)
* класс [PdfFileStamp](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText, float, float) {#addpagenumber_3}

Добавляет номер страницы в указанной позиции на странице.

```csharp
public void AddPageNumber(FormattedText formattedText, float x, float y)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| formattedText | FormattedText | Форматированный текст, который представляет формат номера страницы и свойства текста. Форматированная строка может содержать знак #, который будет заменен на номер страницы. |
| x | Single | Координата X номера страницы. |
| y | Single | Координата Y номера страницы. |

## Примеры

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page  #"), 123, 357);
fileStamp.Close();
```

### См. также

* класс [FormattedText](../../formattedtext/)
* класс [PdfFileStamp](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## AddPageNumber(string, int) {#addpagenumber_5}

Добавляет номер страницы на страницы.

```csharp
public void AddPageNumber(string formatString, int position)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| formatString | String | Формат номера страницы. Этот текст может содержать #, который будет заменен на номер страницы. |
| position | Int32 | Позиция, где будет размещен номер страницы. 0 - внизу по центру, 1 - внизу справа, 2 - вверху справа, 3 - справа по бокам, 4 - вверху по центру, 5 - внизу слева, 6 - слева по бокам, 7 - вверху слева. Вы можете использовать следующие константы: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |

## Примеры

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #", PdfFileStamp.PosUpperRight);
fileStamp.Close();
```

### См. также

* класс [PdfFileStamp](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText, int) {#addpagenumber_1}

Добавляет номер страницы на страницы.

```csharp
public void AddPageNumber(FormattedText formattedText, int position)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| formattedText | FormattedText | Объект FormattedText, который содержит формат номера страницы и свойства текста. Этот текст может содержать #, который будет заменен на номер страницы. |
| position | Int32 | Позиция, где будет размещен номер страницы. 0 - внизу по центру, 1 - внизу справа, 2 - вверху справа, 3 - справа по бокам, 4 - вверху по центру, 5 - внизу слева, 6 - слева по бокам, 7 - вверху слева. Вы можете использовать следующие константы: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |

## Примеры

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #", PdfFileStamp.PosUpperRight);
fileStamp.Close();
```

### См. также

* класс [FormattedText](../../formattedtext/)
* класс [PdfFileStamp](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)