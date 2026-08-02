---
title: "PdfFileStamp.AddPageNumber"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод PdfFileStamp. Добавляет номер страницы в файл. Текст номера страницы может содержать знак #, который будет заменён номером страницы. Номер страницы размещается в нижней части страницы, центрирован по горизонтали."
type: docs
weight: 130
url: /ru/net/aspose.pdf.facades/pdffilestamp/addpagenumber/
---
## AddPageNumber(string) {#addpagenumber_4}

Добавляет номер страницы в файл. Текст номера страницы может содержать знак #, который будет заменён номером страницы. Номер страницы размещается в нижней части страницы, центрирован по горизонтали.

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

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText) {#addpagenumber}

Добавляет номер страницы к странице. Номер страницы может содержать знак #, который будет заменён номером страницы. Номер страницы размещается в нижней части страницы, центрирован по горизонтали.

```csharp
public void AddPageNumber(FormattedText formattedText)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| formattedText | FormattedText | Строка формата для номера страницы представлена как FormattedText. |

## Примеры

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page #"));
fileStamp.Close();
```

### См. также

* class [FormattedText](../../formattedtext/)
* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

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
| позиция | Int32 | Позиция, в которой номер страницы будет размещён на странице. 0‑нижняя средняя, 1‑нижний правый, 2‑верхний правый, 3‑правый боковой, 4‑верхняя средняя, 5‑нижний левый, 6‑левый боковой, 7‑верхний левый. Можно использовать следующие константы: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |
| leftMargin | Single | Отступ по левому краю страницы. |
| rightMargin | Single | Отступ по правому краю страницы. |
| topMargin | Single | Отступ по верхнему краю страницы. |
| bottomMargin | Single | Отступ по нижнему краю страницы. |

## Примеры

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #", PdfFileStamp.PosBottomLeft, 100, 100, 200, 200);
fileStamp.Close();
```

### См. также

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddPageNumber(string, float, float) {#addpagenumber_7}

Добавляет номер страницы в указанной позиции на странице.

```csharp
public void AddPageNumber(string formatString, float x, float y)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| formatString | String | Строка формата. Строка формата может содержать знак #, который будет заменён номером страницы. |
| x | Single | Координата X номера страницы. |
| y | Single | Координата Y номера страницы. |

## Примеры

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page  #"), 123, 357);
fileStamp.Close();
```

### См. также

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText, int, float, float, float, float) {#addpagenumber_2}

Добавляет номер страницы к страницам документа.

```csharp
public void AddPageNumber(FormattedText formattedText, int position, float leftMargin, 
    float rightMargin, float topMargin, float bottomMargin)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| formattedText | FormattedText | Объект FormattedText, представляющий формат номера страницы и свойства текста. |
| позиция | Int32 | Позиция, в которой номер страницы будет размещён на странице. 0‑нижняя средняя, 1‑нижний правый, 2‑верхний правый, 3‑правый боковой, 4‑верхняя средняя, 5‑нижний левый, 6‑левый боковой, 7‑верхний левый. Можно использовать следующие константы: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |
| leftMargin | Single | Отступ по левому краю страницы. |
| rightMargin | Single | Отступ по правому краю страницы. |
| topMargin | Single | Отступ по верхнему краю страницы. |
| bottomMargin | Single | Отступ по нижнему краю страницы. |

## Примеры

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page #"), PdfFileStamp.PosBottomLeft, 100, 100, 200, 200);
fileStamp.Close();
```

### См. также

* class [FormattedText](../../formattedtext/)
* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText, float, float) {#addpagenumber_3}

Добавляет номер страницы в указанной позиции на странице.

```csharp
public void AddPageNumber(FormattedText formattedText, float x, float y)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| formattedText | FormattedText | Отформатированный текст, представляющий формат номера страницы и свойства текста. Строка формата может содержать символ #, который будет заменён номером страницы. |
| x | Single | Координата X номера страницы. |
| y | Single | Координата Y номера страницы. |

## Примеры

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page  #"), 123, 357);
fileStamp.Close();
```

### См. также

* class [FormattedText](../../formattedtext/)
* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddPageNumber(string, int) {#addpagenumber_5}

Добавляет номер страницы к страницам.

```csharp
public void AddPageNumber(string formatString, int position)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| formatString | String | Формат номера страницы. Этот текст может содержать #, который будет заменён номером страницы. |
| позиция | Int32 | Позиция, в которой номер страницы будет размещён на странице. 0‑нижняя средняя, 1‑нижний правый, 2‑верхний правый, 3‑правый боковой, 4‑верхняя средняя, 5‑нижний левый, 6‑левый боковой, 7‑верхний левый. Можно использовать следующие константы: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |

## Примеры

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #", PdfFileStamp.PosUpperRight);
fileStamp.Close();
```

### См. также

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText, int) {#addpagenumber_1}

Добавляет номер страницы к страницам.

```csharp
public void AddPageNumber(FormattedText formattedText, int position)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| formattedText | FormattedText | Объект FormattedText, содержащий формат номера страницы и свойства текста. Этот текст может содержать #, который будет заменён номером страницы. |
| позиция | Int32 | Позиция, в которой номер страницы будет размещён на странице. 0‑нижняя средняя, 1‑нижний правый, 2‑верхний правый, 3‑правый боковой, 4‑верхняя средняя, 5‑нижний левый, 6‑левый боковой, 7‑верхний левый. Можно использовать следующие константы: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |

## Примеры

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #", PdfFileStamp.PosUpperRight);
fileStamp.Close();
```

### См. также

* class [FormattedText](../../formattedtext/)
* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


