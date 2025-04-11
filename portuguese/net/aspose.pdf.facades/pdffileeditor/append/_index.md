---
title: PdfFileEditor.Append
second_title: Aspose.PDF for .NET API Reference
description: Método PdfFileEditor. Anexa páginas escolhidas de um array de documentos em portStreams. O documento resultante inclui firstInputFile e todas as páginas dos documentos portStreams no intervalo de startPage a endPage.
type: docs
weight: 250
url: /pt/net/aspose.pdf.facades/pdffileeditor/append/
---
## Append(Stream, Stream[], int, int, Stream) {#append_1}

Anexa páginas, que são escolhidas de um array de documentos em portStreams. O documento resultante inclui firstInputFile e todas as páginas dos documentos portStreams no intervalo de startPage a endPage.

```csharp
public bool Append(Stream inputStream, Stream[] portStreams, int startPage, int endPage, 
    Stream outputStream)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputStream | Stream | Fluxo Pdf de entrada. |
| portStreams | Stream[] | Documentos de onde copiar páginas. |
| startPage | Int32 | A página começa nos documentos portStreams. |
| endPage | Int32 | A página termina nos documentos portStreams. |
| outputStream | Stream | Fluxo Pdf de saída. |

### Valor de Retorno

Verdadeiro para sucesso, ou falso.

## Exemplos

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream instream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Append(instream, new Stream[] { stream1, stream2}, 3, 5, outstream);
```

### Veja Também

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Append(string, string[], int, int, string) {#append_3}

Anexa páginas, que são escolhidas dos documentos portFiles. O documento resultante inclui firstInputFile e todas as páginas dos documentos portFiles no intervalo de startPage a endPage.

```csharp
public bool Append(string inputFile, string[] portFiles, int startPage, int endPage, 
    string outputFile)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputFile | String | Arquivo Pdf de entrada. |
| portFiles | String[] | Documentos de onde copiar páginas. |
| startPage | Int32 | A página começa nos documentos portFiles. |
| endPage | Int32 | A página termina nos documentos portFiles. |
| outputFile | String | Documento Pdf de saída. |

### Valor de Retorno

Verdadeiro se a operação foi bem-sucedida.

## Exemplos

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.Append("input.pdf", new string[] { "file1.pdf", "file2.pdf"}, 3, 5, "outfile.pdf");
```

### Veja Também

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Append(string, string, int, int, string) {#append_2}

Anexa páginas, que são escolhidas do portFile dentro do intervalo de startPage a endPage, no portFile ao final do firstInputFile.

```csharp
public bool Append(string inputFile, string portFile, int startPage, int endPage, string outputFile)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputFile | String | Arquivo Pdf de entrada. |
| portFile | String | Páginas do arquivo Pdf. |
| startPage | Int32 | A página começa no portFile. |
| endPage | Int32 | A página termina no portFile. |
| outputFile | String | Documento Pdf de saída. |

### Valor de Retorno

Verdadeiro se a operação foi bem-sucedida.

## Exemplos

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.Append("input.pdf", "file1.pdf",  3, 5, "outfile.pdf");
```

### Veja Também

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Append(Stream, Stream, int, int, Stream) {#append}

Anexa páginas, que são escolhidas do portStream dentro do intervalo de startPage a endPage, no portStream ao final do firstInputStream.

```csharp
public bool Append(Stream inputStream, Stream portStream, int startPage, int endPage, 
    Stream outputStream)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputStream | Stream | Fluxo de arquivo de entrada. |
| portStream | Stream | Páginas do fluxo de arquivo Pdf. |
| startPage | Int32 | A página começa no fluxo do portFile. |
| endPage | Int32 | A página termina no fluxo do portFile. |
| outputStream | Stream | Fluxo de arquivo Pdf de saída. |

### Valor de Retorno

Verdadeiro para sucesso, ou falso.

## Exemplos

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream instream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Append(instream, stream1,  3, 5, "outfile.pdf");
```

### Veja Também

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)