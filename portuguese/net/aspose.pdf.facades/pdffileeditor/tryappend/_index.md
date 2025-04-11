---
title: PdfFileEditor.TryAppend
second_title: Aspose.PDF for .NET API Reference
description: Método PdfFileEditor. Anexa páginas escolhidas de um array de documentos em portStreams. O documento resultante inclui firstInputFile e todas as páginas dos documentos portStreams no intervalo de startPage a endPage
type: docs
weight: 380
url: /pt/net/aspose.pdf.facades/pdffileeditor/tryappend/
---
## TryAppend(Stream, Stream[], int, int, Stream) {#tryappend}

Anexa páginas, que são escolhidas de um array de documentos em portStreams. O documento resultante inclui firstInputFile e todas as páginas dos documentos portStreams no intervalo de startPage a endPage.

```csharp
public bool TryAppend(Stream inputStream, Stream[] portStreams, int startPage, int endPage, 
    Stream outputStream)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputStream | Stream | Stream Pdf de entrada. |
| portStreams | Stream[] | Documentos de onde copiar páginas. |
| startPage | Int32 | Página inicial nos documentos portStreams. |
| endPage | Int32 | Página final nos documentos portStreams. |
| outputStream | Stream | Stream Pdf de saída. |

### Valor de Retorno

Verdadeiro para sucesso, ou falso.

## Observações

O método TryAppend é como o método Append, exceto que o método TryAppend não lança uma exceção se a operação falhar.

## Exemplos

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream instream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
bool result = fileEditor.TryAppend(instream, new Stream[] { stream1, stream2}, 3, 5, outstream);
```

### Veja Também

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryAppend(string, string[], int, int, string) {#tryappend_1}

Anexa páginas, que são escolhidas de documentos portFiles. O documento resultante inclui firstInputFile e todas as páginas dos documentos portFiles no intervalo de startPage a endPage.

```csharp
public bool TryAppend(string inputFile, string[] portFiles, int startPage, int endPage, 
    string outputFile)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputFile | String | Arquivo Pdf de entrada. |
| portFiles | String[] | Documentos de onde copiar páginas. |
| startPage | Int32 | Página inicial nos documentos portFiles. |
| endPage | Int32 | Página final nos documentos portFiles. |
| outputFile | String | Documento Pdf de saída. |

### Valor de Retorno

verdadeiro se a operação for concluída com sucesso; caso contrário, falso.

## Observações

O método TryAppend é como o método Append, exceto que o método TryAppend não lança uma exceção se a operação falhar.

## Exemplos

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
bool result = fileEditor.TryAppend("input.pdf", new string[] { "file1.pdf", "file2.pdf"}, 3, 5, "outfile.pdf");
```

### Veja Também

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


## TryAppend(Stream, Stream[], int, int, HttpResponse) {#tryappend_1}

Anexa documentos ao documento de origem e salva o resultado no objeto de resposta.

```csharp
public bool TryAppend(Stream inputStream, Stream[] portStreams, int startPage, int endPage, 
    HttpResponse response)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputStream | Stream | Stream que contém o documento de origem. |
| portStreams | Stream[] | Array de streams com documentos a serem anexados. |
| startPage | Int32 | Página inicial da página anexada. |
| endPage | Int32 | Página final das páginas anexadas. |
| response | HttpResponse | Objeto de resposta onde o documento será salvo. |

### Valor de Retorno

verdadeiro se a operação for concluída com sucesso; caso contrário, falso.

## Observações

O método TryAppend é como o método Append, exceto que o método TryAppend não lança uma exceção se a operação falhar.

### Veja Também

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryAppend(string, string[], int, int, HttpResponse) {#tryappend_3}

Anexa documentos ao documento de origem e salva o resultado no objeto HttpResponse.

```csharp
public bool TryAppend(string inputFile, string[] portFiles, int startPage, int endPage, 
    HttpResponse response)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputFile | String | Nome do arquivo contendo o documento de origem. |
| portFiles | String[] | Array de nomes de arquivos contendo documentos anexados. |
| startPage | Int32 | Página inicial das páginas anexadas. |
| endPage | Int32 | Página final das páginas anexadas. |
| response | HttpResponse | Objeto de resposta onde o documento será salvo. |

### Valor de Retorno

verdadeiro se a operação for concluída com sucesso; caso contrário, falso.

## Observações

O método TryAppend é como o método Append, exceto que o método TryAppend não lança uma exceção se a operação falhar.

### Veja Também

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)