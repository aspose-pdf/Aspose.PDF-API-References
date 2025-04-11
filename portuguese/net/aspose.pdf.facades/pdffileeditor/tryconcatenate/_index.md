---
title: PdfFileEditor.TryConcatenate
second_title: Aspose.PDF for .NET API Reference
description: Método PdfFileEditor. Concatena dois arquivos
type: docs
weight: 390
url: /pt/net/aspose.pdf.facades/pdffileeditor/tryconcatenate/
---
## TryConcatenate(string, string, string) {#tryconcatenate_3}

Concatena dois arquivos.

```csharp
public bool TryConcatenate(string firstInputFile, string secInputFile, string outputFile)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| firstInputFile | String | Primeiro arquivo a ser concatenado. |
| secInputFile | String | Segundo arquivo a ser concatenado. |
| outputFile | String | Arquivo de saída. |

### Valor de Retorno

true se a operação for concluída com sucesso; caso contrário, false.

## Observações

O método TryConcatenate é como o método Concatenate, exceto que o método TryConcatenate não lança uma exceção se a operação falhar.

## Exemplos

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
bool result = fileEditor.TryConcatenate("file1.pdf", "file2.pdf", "outfile.pdf");
```

### Veja Também

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryConcatenate(Document[], Document) {#tryconcatenate}

Concatena documentos.

```csharp
public bool TryConcatenate(Document[] src, Document dest)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| src | Document[] | Array de documentos de origem. |
| dest | Document | Documento de destino. |

### Valor de Retorno

true se a operação for concluída com sucesso; caso contrário, false.

## Observações

O método TryConcatenate é como o método Concatenate, exceto que o método TryConcatenate não lança uma exceção se a operação falhar.

### Veja Também

* class [Document](../../../aspose.pdf/document/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryConcatenate(string[], string) {#tryconcatenate_5}

Concatena arquivos em um único arquivo.

```csharp
public bool TryConcatenate(string[] inputFiles, string outputFile)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputFiles | String[] | Array de arquivos a serem concatenados. |
| outputFile | String | Nome do arquivo de saída. |

### Valor de Retorno

true se a operação for concluída com sucesso; caso contrário, false.

## Observações

O método TryConcatenate é como o método Concatenate, exceto que o método TryConcatenate não lança uma exceção se a operação falhar.

## Exemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryConcatenate(new string[] { "src1.pdf", "src2.pdf" }, "dest.pdf");
```

### Veja Também

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryConcatenate(Stream[], Stream) {#tryconcatenate_2}

Concatena arquivos

```csharp
public bool TryConcatenate(Stream[] inputStream, Stream outputStream)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputStream | Stream[] | Array de streams a serem concatenados. |
| outputStream | Stream | Stream onde o arquivo resultante será armazenado. |

### Valor de Retorno

true se a operação for concluída com sucesso; caso contrário, false.

## Observações

O método TryConcatenate é como o método Concatenate, exceto que o método TryConcatenate não lança uma exceção se a operação falhar.

## Exemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryConcatenate(new Stream[] { stream1, stream2 } , outstream);
```

### Veja Também

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryConcatenate(string, string, string, string) {#tryconcatenate_4}

Mescla dois documentos Pdf em um novo documento Pdf com páginas de maneiras alternadas e preenche os espaços em branco com páginas em branco. por exemplo: document1 tem 5 páginas: p1, p2, p3, p4, p5. document2 tem 3 páginas: p1', p2', p3'. Mesclando os dois documentos Pdf produzirá o documento resultante com páginas: p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage.

```csharp
public bool TryConcatenate(string firstInputFile, string secInputFile, string blankPageFile, 
    string outputFile)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| firstInputFile | String | Primeiro arquivo. |
| secInputFile | String | Segundo arquivo. |
| blankPageFile | String | Arquivo PDF com página em branco. |
| outputFile | String | Arquivo resultante. |

### Valor de Retorno

true se a operação for concluída com sucesso; caso contrário, false.

## Observações

O método TryConcatenate é como o método Concatenate, exceto que o método TryConcatenate não lança uma exceção se a operação falhar.

## Exemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryConcatenate("src1.pdf", "src2.pdf", "blank.pdf", "dest.pdf");
```

### Veja Também

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryConcatenate(Stream, Stream, Stream, Stream) {#tryconcatenate_1}

Mescla dois documentos Pdf em um novo documento Pdf com páginas de maneiras alternadas e preenche os espaços em branco com páginas em branco. por exemplo: document1 tem 5 páginas: p1, p2, p3, p4, p5. document2 tem 3 páginas: p1', p2', p3'. Mesclando os dois documentos Pdf produzirá o documento resultante com páginas: p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage.

```csharp
public bool TryConcatenate(Stream firstInputStream, Stream secInputStream, Stream blankPageStream, 
    Stream outputStream)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| firstInputStream | Stream | O primeiro Stream Pdf. |
| secInputStream | Stream | O segundo Stream Pdf. |
| blankPageStream | Stream | O Stream Pdf com página em branco. |
| outputStream | Stream | Stream Pdf de saída. |

### Valor de Retorno

true se a operação for concluída com sucesso; caso contrário, false.

## Observações

O método TryConcatenate é como o método Concatenate, exceto que o método TryConcatenate não lança uma exceção se a operação falhar.

## Exemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream blank = new FileStream("blank.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryConcatenate(new Stream[] { stream1, stream2, blank } , outstream);
```

### Veja Também

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


## TryConcatenate(string[], HttpResponse) {#tryconcatenate_7}

Concatena arquivos e salva o resultado no objeto HttpResponse.

```csharp
public bool TryConcatenate(string[] inputFiles, HttpResponse response)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputFiles | String[] | Array de arquivos a serem concatenados. |
| response | HttpResponse | Objeto de resposta. |

### Valor de Retorno

true se a operação for concluída com sucesso; caso contrário, false.

## Observações

O método TryConcatenate é como o método Concatenate, exceto que o método TryConcatenate não lança uma exceção se a operação falhar.

### Veja Também

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryConcatenate(Stream[], HttpResponse) {#tryconcatenate_3}

Concatena arquivos e armazena o resultado no objeto HttpResponse.

```csharp
public bool TryConcatenate(Stream[] inputStream, HttpResponse response)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputStream | Stream[] | Array de streams que contêm arquivos a serem concatenados. |
| response | HttpResponse | Objeto de resposta. |

### Valor de Retorno

true se a operação for concluída com sucesso; caso contrário, false.

## Observações

O método TryConcatenate é como o método Concatenate, exceto que o método TryConcatenate não lança uma exceção se a operação falhar.

### Veja Também

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)