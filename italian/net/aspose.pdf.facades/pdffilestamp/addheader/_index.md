---
title: "PdfFileStamp.AddHeader"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo PdfFileStamp. Aggiunge l'intestazione alla pagina"
type: docs
weight: 120
url: /it/net/aspose.pdf.facades/pdffilestamp/addheader/
---
## AddHeader(FormattedText, float) {#addheader}

Aggiunge un'intestazione alla page.

```csharp
public void AddHeader(FormattedText formattedText, float topMargin)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| formattedText | FormattedText | Testo per l'intestazione e proprietà del testo. |
| topMargin | Single | Margine nella parte superiore della pagina. |

## Esempi

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddHeader(new FormattedText("Head of the page"), 50);
fileStamp.Close();
```

### Vedi anche

* class [FormattedText](../../formattedtext/)
* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddHeader(FormattedText, float, float, float) {#addheader_1}

Aggiunge un'intestazione alle pages del file.

```csharp
public void AddHeader(FormattedText formattedText, float topMargin, float leftMargin, 
    float rightMargin)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| formattedText | FormattedText | Oggetto FormattedText che contiene il testo della pagina e le sue proprietà. |
| topMargin | Single | Margine nella parte superiore della pagina. |
| leftMargin | Single | Margine sul lato sinistro della pagina. |
| rightMargin | Single | Margine sul lato destro della pagina. |

## Esempi

```csharp
PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf");
stamp.AddHeader(new FormattedText("Head of the page"), 10, 50, 50);
```

### Vedi anche

* class [FormattedText](../../formattedtext/)
* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddHeader(string, float) {#addheader_4}

Aggiunge un'immagine come intestazione alle pages del file.

```csharp
public void AddHeader(string imageFile, float topMargin)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| imageFile | String | Percorso del file immagine. |
| topMargin | Single | Margine nella parte superiore della pagina. |

## Esempi

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddHeader("image.jpg", 50);
fileStamp.Close();
```

### Vedi anche

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddHeader(string, float, float, float) {#addheader_5}

Aggiunge un'immagine come intestazione sulle pages.

```csharp
public void AddHeader(string imageFile, float topMargin, float leftMargin, float rightMargin)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| imageFile | String | Percorso del file immagine. |
| topMargin | Single | Margine nella parte superiore della pagina. |
| leftMargin | Single | Margine sul lato sinistro della pagina. |
| rightMargin | Single | Margine sul lato destro della pagina. |

## Esempi

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddHeader("image.jpg", 50, 100, 100);
fileStamp.Close();
```

### Vedi anche

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddHeader(Stream, float) {#addheader_2}

Aggiunge un'immagine come intestazione sulle pages.

```csharp
public void AddHeader(Stream imageStream, float topMargin)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| imageStream | Stream | Stream dell'immagine. |
| topMargin | Single | Margine nella parte superiore della pagina. |

## Esempi

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddHeader(new FileStream("image.jpg", FileMode.Open, FileAccess.Read), 50);
fileStamp.Close();
```

### Vedi anche

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddHeader(Stream, float, float, float) {#addheader_3}

Aggiunge un'immagine nella parte superiore della page.

```csharp
public void AddHeader(Stream inputStream, float topMargin, float leftMargin, float rightMargin)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStream | Stream | Stream che contiene i dati dell'immagine. |
| topMargin | Single | Margine nella parte superiore della pagina. |
| leftMargin | Single | Margine sul lato sinistro della pagina. |
| rightMargin | Single | Margine sul lato destro della pagina. |

## Esempi

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddHeader(new FileStream("image.jpg", FileMode.Open, FileAccess.Read), 50, 100, 100);
fileStamp.Close();
```

### Vedi anche

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


