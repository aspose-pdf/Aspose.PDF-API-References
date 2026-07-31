---
title: "PdfConverter.BindPdf"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo PdfConverter. Associa un file Pdf per la conversione."
type: docs
weight: 110
url: /it/net/aspose.pdf.facades/pdfconverter/bindpdf/
---
## BindPdf(string) {#bindpdf_2}

Associa un file Pdf per la conversione.

```csharp
public override void BindPdf(string inputFile)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputFile | String | Il file pdf. |

### Vedi anche

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## BindPdf(Stream) {#bindpdf_1}

Associa uno stream Pdf per la conversione.

```csharp
public override void BindPdf(Stream inputStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStream | Stream | Lo stream pdf. |

### Vedi anche

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## BindPdf(Document) {#bindpdf}

Associa un documento PDF all'istanza [`PdfConverter`](../) per ulteriori elaborazioni.

```csharp
public override void BindPdf(Document srcDoc)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| srcDoc | Document | L'oggetto [`Document`](../../../aspose.pdf/document/) che rappresenta il PDF di origine da associare. |

## Osservazioni

Questo metodo inizializza il [`PdfConverter`](../) con il documento PDF specificato. Elabora anche i moduli XFA dinamici all'interno del documento, se presenti.

### Vedi anche

* class [Document](../../../aspose.pdf/document/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


