---
title: "PdfConverter.BindPdf"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод PdfConverter. Привязывает файл Pdf для конвертации"
type: docs
weight: 110
url: /ru/net/aspose.pdf.facades/pdfconverter/bindpdf/
---
## BindPdf(string) {#bindpdf_2}

Привязывает PDF‑файл для конвертации.

```csharp
public override void BindPdf(string inputFile)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | String | Файл pdf. |

### См. также

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## BindPdf(Stream) {#bindpdf_1}

Привязывает поток Pdf для конвертации.

```csharp
public override void BindPdf(Stream inputStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Поток pdf. |

### См. также

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## BindPdf(Document) {#bindpdf}

Привязывает документ PDF к экземпляру [`PdfConverter`](../) для дальнейшей обработки.

```csharp
public override void BindPdf(Document srcDoc)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcDoc | Document | Объект [`Document`](../../../aspose.pdf/document/) , представляющий исходный PDF, который будет привязан. |

## Примечания

Этот метод инициализирует [`PdfConverter`](../) указанным документом PDF. Он также обрабатывает динамические формы XFA в документе, если они присутствуют.

### См. также

* class [Document](../../../aspose.pdf/document/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


