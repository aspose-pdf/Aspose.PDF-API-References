---
title: AddImage
second_title: Aspose.PDF per .NET API Reference
description: Aggiunge limmagine alla pagina specificata del documento PDF alle coordinate specificate.
type: docs
weight: 50
url: /it/net/aspose.pdf.facades/pdffilemend/addimage/
---
## AddImage(Stream, int, float, float, float, float) {#addimage}

Aggiunge l'immagine alla pagina specificata del documento PDF alle coordinate specificate.

```csharp
public bool AddImage(Stream imageStream, int pageNum, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| imageStream | Stream | Input flusso di immagini. |
| pageNum | Int32 | Il numero di pagine che riceverà l'immagine. |
| lowerLeftX | Single | La x in basso a sinistra del rettangolo dell'immagine. |
| lowerLeftY | Single | La y in basso a sinistra del rettangolo dell'immagine. |
| upperRightX | Single | La x in alto a destra del rettangolo dell'immagine. |
| upperRightY | Single | La y in alto a destra del rettangolo dell'immagine. |

### Valore di ritorno

Vero se successo falso altrimenti.

### Esempi

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
using (Stream stream = File.OpenRead("picture.jpg"))
{
    mendor.AddImage(stream, 1, 10, 10, 100, 100);
}
mendor.Close();
```

### Guarda anche

* class [PdfFileMend](../../pdffilemend)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffilemend)
* assemblea [Aspose.PDF](../../../)

---

## AddImage(Stream, int, float, float, float, float, CompositingParameters) {#addimage_1}

Aggiunge l'immagine alla pagina specificata del documento PDF alle coordinate specificate.

```csharp
public bool AddImage(Stream imageStream, int pageNum, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| imageStream | Stream | Input flusso di immagini. |
| pageNum | Int32 | Il numero di pagine che riceverà l'immagine. |
| lowerLeftX | Single | La x in basso a sinistra del rettangolo dell'immagine. |
| lowerLeftY | Single | La y in basso a sinistra del rettangolo dell'immagine. |
| upperRightX | Single | La x in alto a destra del rettangolo dell'immagine. |
| upperRightY | Single | La y in alto a destra del rettangolo dell'immagine. |
| compositingParameters | CompositingParameters | I parametri di composizione grafica per l'immagine. |

### Valore di ritorno

Vero se successo falso altrimenti.

### Esempi

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
using (Stream stream = File.OpenRead("picture.jpg"))
{
    mendor.AddImage(stream, 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply);
}
mendor.Close();
```

### Guarda anche

* class [CompositingParameters](../../../aspose.pdf/compositingparameters)
* class [PdfFileMend](../../pdffilemend)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffilemend)
* assemblea [Aspose.PDF](../../../)

---

## AddImage(Stream, int[], float, float, float, float) {#addimage_2}

Aggiunge l'immagine alle pagine specificate del documento PDF alle coordinate specificate.

```csharp
public bool AddImage(Stream imageStream, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| imageStream | Stream | Input flusso di immagini. |
| pageNums | Int32[] | Il numero di pagine che riceveranno l'immagine. |
| lowerLeftX | Single | La x in basso a sinistra del rettangolo dell'immagine. |
| lowerLeftY | Single | La y in basso a sinistra del rettangolo dell'immagine. |
| upperRightX | Single | La x in alto a destra del rettangolo dell'immagine. |
| upperRightY | Single | La y in alto a destra del rettangolo dell'immagine. |

### Valore di ritorno

Vero se successo falso altrimenti.

### Esempi

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
using (Stream stream = File.OpenRead("picture.jpg"))
{
    mendor.AddImage(stream, new int[]{1, 2}, 10, 10, 100, 100);
}
mendor.Close();
```

### Guarda anche

* class [PdfFileMend](../../pdffilemend)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffilemend)
* assemblea [Aspose.PDF](../../../)

---

## AddImage(Stream, int[], float, float, float, float, CompositingParameters) {#addimage_3}

Aggiunge l'immagine alle pagine specificate del documento PDF alle coordinate specificate.

```csharp
public bool AddImage(Stream imageStream, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| imageStream | Stream | Input flusso di immagini. |
| pageNums | Int32[] | Il numero di pagine che riceveranno l'immagine. |
| lowerLeftX | Single | La x in basso a sinistra del rettangolo dell'immagine. |
| lowerLeftY | Single | La y in basso a sinistra del rettangolo dell'immagine. |
| upperRightX | Single | La x in alto a destra del rettangolo dell'immagine. |
| upperRightY | Single | La y in alto a destra del rettangolo dell'immagine. |
| compositingParameters | CompositingParameters | I parametri di composizione grafica per le immagini. |

### Valore di ritorno

Vero se successo falso altrimenti.

### Esempi

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
using (Stream stream = File.OpenRead("picture.jpg"))
{
    mendor.AddImage(stream, new int[]{1, 2}, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply);
}
mendor.Close();
```

### Guarda anche

* class [CompositingParameters](../../../aspose.pdf/compositingparameters)
* class [PdfFileMend](../../pdffilemend)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffilemend)
* assemblea [Aspose.PDF](../../../)

---

## AddImage(string, int, float, float, float, float) {#addimage_4}

Aggiunge l'immagine alla pagina specificata del documento PDF alle coordinate specificate.

```csharp
public bool AddImage(string imageName, int pageNum, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| imageName | String | Il percorso del file immagine di input. |
| pageNum | Int32 | Il numero di pagine che riceverà l'immagine. |
| lowerLeftX | Single | La x in basso a sinistra del rettangolo dell'immagine. |
| lowerLeftY | Single | La y in basso a sinistra del rettangolo dell'immagine. |
| upperRightX | Single | La x in alto a destra del rettangolo dell'immagine. |
| upperRightY | Single | La y in alto a destra del rettangolo dell'immagine. |

### Valore di ritorno

Vero se successo falso altrimenti.

### Esempi

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100);
mendor.Close();
```

### Guarda anche

* class [PdfFileMend](../../pdffilemend)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffilemend)
* assemblea [Aspose.PDF](../../../)

---

## AddImage(string, int, float, float, float, float, CompositingParameters) {#addimage_5}

Aggiunge l'immagine alla pagina specificata del documento PDF alle coordinate specificate.

```csharp
public bool AddImage(string imageName, int pageNum, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| imageName | String | Il percorso del file immagine di input. |
| pageNum | Int32 | Il numero di pagine che riceverà l'immagine. |
| lowerLeftX | Single | La x in basso a sinistra del rettangolo dell'immagine. |
| lowerLeftY | Single | La y in basso a sinistra del rettangolo dell'immagine. |
| upperRightX | Single | La x in alto a destra del rettangolo dell'immagine. |
| upperRightY | Single | La y in alto a destra del rettangolo dell'immagine. |
| compositingParameters | CompositingParameters | I parametri di composizione grafica per le immagini. |

### Valore di ritorno

Vero se successo falso altrimenti.

### Esempi

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply));
mendor.Close();
```

### Guarda anche

* class [CompositingParameters](../../../aspose.pdf/compositingparameters)
* class [PdfFileMend](../../pdffilemend)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffilemend)
* assemblea [Aspose.PDF](../../../)

---

## AddImage(string, int[], float, float, float, float) {#addimage_6}

Aggiunge l'immagine alle pagine specificate del documento PDF alle coordinate specificate.

```csharp
public bool AddImage(string imageName, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| imageName | String | Il percorso del file immagine di input. |
| pageNums | Int32[] | Il numero di pagine che riceveranno l'immagine. |
| lowerLeftX | Single | La x in basso a sinistra del rettangolo dell'immagine. |
| lowerLeftY | Single | La y in basso a sinistra del rettangolo dell'immagine. |
| upperRightX | Single | La x in alto a destra del rettangolo dell'immagine. |
| upperRightY | Single | La y in alto a destra del rettangolo dell'immagine. |

### Valore di ritorno

Vero se successo falso altrimenti.

### Esempi

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100);
mendor.Close();
```

### Guarda anche

* class [PdfFileMend](../../pdffilemend)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffilemend)
* assemblea [Aspose.PDF](../../../)

---

## AddImage(string, int[], float, float, float, float, CompositingParameters) {#addimage_7}

Aggiunge l'immagine alle pagine specificate del documento PDF alle coordinate specificate.

```csharp
public bool AddImage(string imageName, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| imageName | String | Il percorso del file immagine di input. |
| pageNums | Int32[] | Il numero di pagine che riceveranno l'immagine. |
| lowerLeftX | Single | La x in basso a sinistra del rettangolo dell'immagine. |
| lowerLeftY | Single | La y in basso a sinistra del rettangolo dell'immagine. |
| upperRightX | Single | La x in alto a destra del rettangolo dell'immagine. |
| upperRightY | Single | La y in alto a destra del rettangolo dell'immagine. |
| compositingParameters | CompositingParameters | I parametri di composizione grafica per le immagini. |

### Valore di ritorno

Vero se successo falso altrimenti.

### Esempi

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply));
mendor.Close();
```

### Guarda anche

* class [CompositingParameters](../../../aspose.pdf/compositingparameters)
* class [PdfFileMend](../../pdffilemend)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffilemend)
* assemblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
