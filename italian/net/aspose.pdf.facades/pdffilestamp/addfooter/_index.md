---
title: PdfFileStamp.AddFooter
second_title: Aspose.PDF for .NET API Reference
description: PdfFileStamp method. Adds footer to the pages of the document
type: docs
weight: 110
url: /it/net/aspose.pdf.facades/pdffilestamp/addfooter/
---
## AddFooter(FormattedText, float) {#addfooter}

Aggiunge un piè di pagina alle pagine del documento.

```csharp
public void AddFooter(FormattedText formattedText, float bottomMargin)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| formattedText | FormattedText | Oggetto FormattedText che contiene il testo del piè di pagina e le proprietà del testo. |
| bottomMargin | Single | Margine nella parte superiore della pagina. |

## Esempi

```csharp
PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf");
stamp.AddFooter(new FormattedText("Foot of the page"), 10);
```

### Vedi Anche

* class [FormattedText](../../formattedtext/)
* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddFooter(FormattedText, float, float, float) {#addfooter_1}

Aggiunge un piè di pagina alle pagine del documento.

```csharp
public void AddFooter(FormattedText formattedText, float bottomMargin, float leftMargin, 
    float rightMargin)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| formattedText | FormattedText | Oggetto FormattedText che contiene il testo del piè di pagina e le proprietà del testo. |
| bottomMargin | Single | Margine nella parte inferiore della pagina. |
| leftMargin | Single | Margine sul lato sinistro della pagina. |
| rightMargin | Single | Margine sul lato destro della pagina. |

## Esempi

```csharp
PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf");
stamp.AddFooter(new FormattedText("Foot of the page"), 10, 50, 50);
```

### Vedi Anche

* class [FormattedText](../../formattedtext/)
* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddFooter(string, float) {#addfooter_4}

Aggiunge un'immagine come piè di pagina alle pagine del documento.

```csharp
public void AddFooter(string imageFile, float bottomMargin)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| imageFile | String | Nome e percorso del file immagine. |
| bottomMargin | Single | Margine nella parte inferiore della pagina. |

## Esempi

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddFooter("image.jpg", 50);
fileStamp.Close();
```

### Vedi Anche

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddFooter(string, float, float, float) {#addfooter_5}

Aggiunge un'immagine come piè di pagina delle pagine.

```csharp
public void AddFooter(string imageFile, float bottomMargin, float leftMargin, float rightMargin)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| imageFile | String | Nome e percorso del file immagine. |
| bottomMargin | Single | Margine nella parte inferiore della pagina. |
| leftMargin | Single | Margine sul lato sinistro della pagina. |
| rightMargin | Single | Margine sul lato destro della pagina. |

## Esempi

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddFooter("image.jpg", 50, 100, 100);
fileStamp.Close();
```

### Vedi Anche

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddFooter(Stream, float) {#addfooter_2}

Aggiunge un'immagine come piè di pagina della pagina.

```csharp
public void AddFooter(Stream imageStream, float bottomMargin)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| imageStream | Stream | Stream che contiene i dati dell'immagine. |
| bottomMargin | Single | Margine nella parte inferiore della pagina. |

## Esempi

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddFooter(new FileStream("image.jpg", FileMode.Open, FileAccess.Read), 50);
fileStamp.Close();
```

### Vedi Anche

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddFooter(Stream, float, float, float) {#addfooter_3}

Aggiunge un'immagine come piè di pagina della pagina.

```csharp
public void AddFooter(Stream imageStream, float bottomMargin, float leftMargin, float rightMargin)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| imageStream | Stream | Stream che contiene i dati dell'immagine. |
| bottomMargin | Single | Margine nella parte inferiore della pagina. |
| leftMargin | Single | Margine sul lato sinistro della pagina. |
| rightMargin | Single | Margine sul lato destro della pagina. |

## Esempi

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddFooter(new FileStream("image.jpg", FileMode.Open, FileAccess.Read), 50, 50, 50);
fileStamp.Close();
```

### Vedi Anche

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)