---
title: Stamp.BindPdf
second_title: Aspose.PDF for .NET API Reference
description: Método Stamp. Define o arquivo PDF e o número da página que será usado como carimbo
type: docs
weight: 120
url: /pt/net/aspose.pdf.facades/stamp/bindpdf/
---
## BindPdf(string, int) {#bindpdf_1}

Define o arquivo PDF e o número da página que será usado como carimbo.

```csharp
public void BindPdf(string pdfFile, int pageNumber)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pdfFile | String | Caminho para o arquivo PDF. |
| pageNumber | Int32 | Número da página no arquivo PDF |

## Exemplos

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Stamp();
//First page will be used as stamp.
stamp.BindPdf("stamp.pdf", 1);
stamp.IsBackground = true;
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### Veja Também

* classe [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## BindPdf(Stream, int) {#bindpdf}

Define o arquivo PDF e o número da página que será usado como carimbo.

```csharp
public void BindPdf(Stream pdfStream, int pageNumber)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pdfStream | Stream | Stream que contém o documento PDF. |
| pageNumber | Int32 | Índice da página do documento que será usado como carimbo. |

## Exemplos

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Stamp();
//First page will be used as stamp.
Stream stream = new FileStream("stamp.pdf", FileMode.Open, FileAccess.Read);
stamp.BindPdf(stream, 1);
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### Veja Também

* classe [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)