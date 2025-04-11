---
title: PdfFileEditor.Extract
second_title: Aspose.PDF for .NET API Reference
description: Método PdfFileEditor. Extrai páginas de arquivos de entrada e salva como um novo arquivo Pdf
type: docs
weight: 280
url: /pt/net/aspose.pdf.facades/pdffileeditor/extract/
---
## Extract(string, int, int, string) {#extract_2}

Extrai páginas do arquivo de entrada, salva como um novo arquivo Pdf.

```csharp
public bool Extract(string inputFile, int startPage, int endPage, string outputFile)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputFile | String | Caminho do arquivo Pdf de entrada. |
| startPage | Int32 | Número da página inicial. |
| endPage | Int32 | Número da página final. |
| outputFile | String | Caminho do arquivo Pdf de saída. |

### Valor de Retorno

Verdadeiro para sucesso, ou falso.

## Exemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Extract("input.pdf", 3, 7, "output.pdf");
```

### Veja Também

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Extract(string, int[], string) {#extract_3}

Extrai páginas especificadas por um array de números, salva como um novo arquivo PDF.

```csharp
public bool Extract(string inputFile, int[] pageNumber, string outputFile)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputFile | String | Caminho do arquivo de entrada. |
| pageNumber | Int32[] | Índice da página do arquivo de entrada. |
| outputFile | String | Caminho do arquivo de saída. |

### Valor de Retorno

Verdadeiro se a operação foi bem-sucedida.

## Exemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Extract("input.pdf", new int[] { 3, 5, 7 }, "output.pdf");
```

### Veja Também

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Extract(Stream, int, int, Stream) {#extract}

Extrai páginas do arquivo de entrada, salva como um novo arquivo Pdf.

```csharp
public bool Extract(Stream inputStream, int startPage, int endPage, Stream outputStream)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputStream | Stream | Stream do arquivo de entrada. |
| startPage | Int32 | Número da página inicial. |
| endPage | Int32 | Número da página final. |
| outputStream | Stream | Stream do arquivo Pdf de saída. |

### Valor de Retorno

Verdadeiro para sucesso, ou falso.

## Exemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.Extract(sourceStream, 1, 3, 6, outStream);
```

### Veja Também

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Extract(Stream, int[], Stream) {#extract_1}

Extrai páginas especificadas por um array de números, salva como um novo arquivo Pdf.

```csharp
public bool Extract(Stream inputStream, int[] pageNumber, Stream outputStream)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputStream | Stream | Stream do arquivo de entrada. |
| pageNumber | Int32[] | Índice da página do arquivo de entrada. |
| outputStream | Stream | Stream do arquivo de saída. |

### Valor de Retorno

Verdadeiro para sucesso, ou falso.

## Exemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.Extract(sourceStream, new int[] { 3, 5, 8 }, outStream);
```

### Veja Também

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)