---
title: "PdfFileStamp.AddHeader"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод PdfFileStamp. Добавляет заголовок на страницу"
type: docs
weight: 120
url: /ru/net/aspose.pdf.facades/pdffilestamp/addheader/
---
## AddHeader(FormattedText, float) {#addheader}

Добавляет заголовок на страницу.

```csharp
public void AddHeader(FormattedText formattedText, float topMargin)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| formattedText | FormattedText | Текст для заголовка и свойства текста. |
| topMargin | Single | Отступ в верхней части страницы. |

## Примеры

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddHeader(new FormattedText("Head of the page"), 50);
fileStamp.Close();
```

### См. также

* class [FormattedText](../../formattedtext/)
* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddHeader(FormattedText, float, float, float) {#addheader_1}

Добавляет заголовок на страницы файла.

```csharp
public void AddHeader(FormattedText formattedText, float topMargin, float leftMargin, 
    float rightMargin)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| formattedText | FormattedText | Объект Formatted text, который содержит текст страницы и его свойства. |
| topMargin | Single | Отступ в верхней части страницы. |
| leftMargin | Single | Отступ слева от страницы. |
| rightMargin | Single | Отступ справа от страницы. |

## Примеры

```csharp
PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf");
stamp.AddHeader(new FormattedText("Head of the page"), 10, 50, 50);
```

### См. также

* class [FormattedText](../../formattedtext/)
* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddHeader(string, float) {#addheader_4}

Добавляет изображение в качестве заголовка на страницы файла.

```csharp
public void AddHeader(string imageFile, float topMargin)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| imageFile | String | Путь к файлу изображения. |
| topMargin | Single | Отступ в верхней части страницы. |

## Примеры

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddHeader("image.jpg", 50);
fileStamp.Close();
```

### См. также

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddHeader(string, float, float, float) {#addheader_5}

Добавляет изображение в качестве заголовка на страницах.

```csharp
public void AddHeader(string imageFile, float topMargin, float leftMargin, float rightMargin)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| imageFile | String | Путь к файлу изображения. |
| topMargin | Single | Отступ в верхней части страницы. |
| leftMargin | Single | Отступ слева от страницы. |
| rightMargin | Single | Отступ справа от страницы. |

## Примеры

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddHeader("image.jpg", 50, 100, 100);
fileStamp.Close();
```

### См. также

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddHeader(Stream, float) {#addheader_2}

Добавляет изображение в качестве заголовка на страницах.

```csharp
public void AddHeader(Stream imageStream, float topMargin)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| imageStream | Stream | Поток изображения. |
| topMargin | Single | Отступ в верхней части страницы. |

## Примеры

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddHeader(new FileStream("image.jpg", FileMode.Open, FileAccess.Read), 50);
fileStamp.Close();
```

### См. также

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddHeader(Stream, float, float, float) {#addheader_3}

Добавляет изображение в верхнюю часть страницы.

```csharp
public void AddHeader(Stream inputStream, float topMargin, float leftMargin, float rightMargin)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Поток, содержащий данные изображения. |
| topMargin | Single | Отступ в верхней части страницы. |
| leftMargin | Single | Отступ слева от страницы. |
| rightMargin | Single | Отступ справа от страницы. |

## Примеры

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddHeader(new FileStream("image.jpg", FileMode.Open, FileAccess.Read), 50, 100, 100);
fileStamp.Close();
```

### См. также

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


