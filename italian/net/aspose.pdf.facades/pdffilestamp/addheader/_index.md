---
title: PdfFileStamp.AddHeader
second_title: Aspose.PDF for .NET API Reference
description: Metodo PdfFileStamp. Aggiunge un'intestazione alla pagina
type: docs
weight: 120
url: /it/net/aspose.pdf.facades/pdffilestamp/addheader/
---
## AddHeader(FormattedText, float) {#addheader}

Aggiunge un'intestazione alla pagina.

```csharp
public void AddHeader(FormattedText formattedText, float topMargin)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| formattedText | FormattedText | Testo per l'intestazione e proprietà del testo. |
| topMargin | Single | Margine in cima alla pagina. |

## Esempi

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddHeader(new FormattedText("Head of the page"), 50);
fileStamp.Close();
```

### Vedi Anche

* classe [FormattedText](../../formattedtext/)
* classe [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddHeader(FormattedText, float, float, float) {#addheader_1}

Aggiunge un'intestazione alle pagine del file.

```csharp
public void AddHeader(FormattedText formattedText, float topMargin, float leftMargin, 
    float rightMargin)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| formattedText | FormattedText | Oggetto di testo formattato che contiene il testo della pagina e le sue proprietà. |
| topMargin | Single | Margine in cima alla pagina. |
| leftMargin | Single | Margine a sinistra della pagina. |
| rightMargin | Single | Margine a destra della pagina. |

## Esempi

```csharp
PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf");
stamp.AddHeader(new FormattedText("Head of the page"), 10, 50, 50);
```

### Vedi Anche

* classe [FormattedText](../../formattedtext/)
* classe [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddHeader(string, float) {#addheader_4}

Aggiunge un'immagine come intestazione alle pagine del file.

```csharp
public void AddHeader(string imageFile, float topMargin)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| imageFile | String | Percorso del file immagine. |
| topMargin | Single | Margine in cima alla pagina. |

## Esempi

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddHeader("image.jpg", 50);
fileStamp.Close();
```

### Vedi Anche

* classe [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddHeader(string, float, float, float) {#addheader_5}

Aggiunge un'immagine come intestazione sulle pagine.

```csharp
public void AddHeader(string imageFile, float topMargin, float leftMargin, float rightMargin)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| imageFile | String | Percorso del file immagine. |
| topMargin | Single | Margine in cima alla pagina. |
| leftMargin | Single | Margine a sinistra della pagina. |
| rightMargin | Single | Margine a destra della pagina. |

## Esempi

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddHeader("image.jpg", 50, 100, 100);
fileStamp.Close();
```

### Vedi Anche

* classe [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddHeader(Stream, float) {#addheader_2}

Aggiunge un'immagine come intestazione sulle pagine.

```csharp
public void AddHeader(Stream imageStream, float topMargin)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| imageStream | Stream | Stream dell'immagine. |
| topMargin | Single | Margine in cima alla pagina. |

## Esempi

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddHeader(new FileStream("image.jpg", FileMode.Open, FileAccess.Read), 50);
fileStamp.Close();
```

### Vedi Anche

* classe [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddHeader(Stream, float, float, float) {#addheader_3}

Aggiunge un'immagine in cima alla pagina.

```csharp
public void AddHeader(Stream inputStream, float topMargin, float leftMargin, float rightMargin)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStream | Stream | Stream che contiene i dati dell'immagine. |
| topMargin | Single | Margine in cima alla pagina. |
| leftMargin | Single | Margine a sinistra della pagina. |
| rightMargin | Single | Margine a destra della pagina. |

## Esempi

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddHeader(new FileStream("image.jpg", FileMode.Open, FileAccess.Read), 50, 100, 100);
fileStamp.Close();
```

### Vedi Anche

* classe [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)