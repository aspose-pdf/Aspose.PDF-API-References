---
title: "PdfFileStamp.AddFooter"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод PdfFileStamp. Добавляет нижний колонтитул на страницы документа"
type: docs
weight: 110
url: /ru/net/aspose.pdf.facades/pdffilestamp/addfooter/
---
## AddFooter(FormattedText, float) {#addfooter}

Добавляет нижний колонтитул на страницы документа.

```csharp
public void AddFooter(FormattedText formattedText, float bottomMargin)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| formattedText | FormattedText | Объект FormattedText, который содержит текст нижнего колонтитула и свойства текста. |
| bottomMargin | Single | Отступ в верхней части страницы. |

## Примеры

```csharp
PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf");
stamp.AddFooter(new FormattedText("Foot of the page"), 10);
```

### См. также

* class [FormattedText](../../formattedtext/)
* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddFooter(FormattedText, float, float, float) {#addfooter_1}

Добавляет нижний колонтитул на страницы документа.

```csharp
public void AddFooter(FormattedText formattedText, float bottomMargin, float leftMargin, 
    float rightMargin)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| formattedText | FormattedText | Объект FormattedText, который содержит текст нижнего колонтитула и свойства текста. |
| bottomMargin | Single | Отступ в нижней части страницы. |
| leftMargin | Single | Отступ слева от страницы. |
| rightMargin | Single | Отступ справа от страницы. |

## Примеры

```csharp
PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf");
stamp.AddFooter(new FormattedText("Foot of the page"), 10, 50, 50);
```

### См. также

* class [FormattedText](../../formattedtext/)
* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddFooter(string, float) {#addfooter_4}

Добавляет изображение в качестве нижнего колонтитула на страницы документа.

```csharp
public void AddFooter(string imageFile, float bottomMargin)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| imageFile | String | Имя файла изображения и путь. |
| bottomMargin | Single | Отступ в нижней части страницы. |

## Примеры

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddFooter("image.jpg", 50);
fileStamp.Close();
```

### См. также

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddFooter(string, float, float, float) {#addfooter_5}

Добавляет изображение в качестве нижнего колонтитула страниц.

```csharp
public void AddFooter(string imageFile, float bottomMargin, float leftMargin, float rightMargin)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| imageFile | String | Имя файла Iamge и путь. |
| bottomMargin | Single | Отступ в нижней части страницы. |
| leftMargin | Single | Отступ слева от страницы. |
| rightMargin | Single | Отступ справа от страницы. |

## Примеры

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddFooter("image.jpg", 50, 100, 100);
fileStamp.Close();
```

### См. также

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddFooter(Stream, float) {#addfooter_2}

Добавляет изображение в качестве нижнего колонтитула страницы.

```csharp
public void AddFooter(Stream imageStream, float bottomMargin)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| imageStream | Stream | Поток содержит данные изображения. |
| bottomMargin | Single | Отступ в нижней части страницы. |

## Примеры

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddFooter(new FileStream("image.jpg", FileMode.Open, FileAccess.Read), 50);
fileStamp.Close();
```

### См. также

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddFooter(Stream, float, float, float) {#addfooter_3}

Добавляет изображение в качестве нижнего колонтитула страницы.

```csharp
public void AddFooter(Stream imageStream, float bottomMargin, float leftMargin, float rightMargin)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| imageStream | Stream | Поток содержит данные изображения. |
| bottomMargin | Single | Отступ в нижней части страницы. |
| leftMargin | Single | Отступ слева от страницы. |
| rightMargin | Single | Отступ справа от страницы. |

## Примеры

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddFooter(new FileStream("image.jpg", FileMode.Open, FileAccess.Read), 50, 50, 50);
fileStamp.Close();
```

### См. также

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


