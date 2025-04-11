---
title: PdfFileEditor.Insert
second_title: Aspose.PDF for .NET API Reference
description: Método PdfFileEditor. Insere páginas de outro arquivo no arquivo Pdf em uma posição
type: docs
weight: 290
url: /pt/net/aspose.pdf.facades/pdffileeditor/insert/
---
## Insert(string, int, string, int, int, string) {#insert_2}

Insere páginas de outro arquivo no arquivo Pdf em uma posição.

```csharp
public bool Insert(string inputFile, int insertLocation, string portFile, int startPage, 
    int endPage, string outputFile)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputFile | String | Arquivo Pdf de entrada. |
| insertLocation | Int32 | Posição no arquivo de entrada. |
| portFile | String | O arquivo Pdf de portabilidade. |
| startPage | Int32 | Posição inicial no portFile. |
| endPage | Int32 | Posição final no portFile. |
| outputFile | String | Arquivo Pdf de saída. |

### Valor de Retorno

Verdadeiro para sucesso, ou falso.

## Exemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Insert("file1.pdf", 1, "file2.pdf", 2, 6, "out.pdf");
```

### Veja Também

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Insert(Stream, int, Stream, int, int, Stream) {#insert}

Insere páginas de outro arquivo no arquivo Pdf de entrada.

```csharp
public bool Insert(Stream inputStream, int insertLocation, Stream portStream, int startPage, 
    int endPage, Stream outputStream)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputStream | Stream | Stream de entrada do arquivo Pdf. |
| insertLocation | Int32 | Posição de inserção no arquivo de entrada. |
| portStream | Stream | Stream do arquivo Pdf para páginas. |
| startPage | Int32 | De qual página começar. |
| endPage | Int32 | Até qual página terminar. |
| outputStream | Stream | Stream de saída. |

### Valor de Retorno

Verdadeiro para sucesso, ou falso.

## Exemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream insertedStream = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.Insert(sourceStream, 1, insertedStream, 2, 6, outStream);
```

### Veja Também

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Insert(string, int, string, int[], string) {#insert_3}

Insere páginas de outro arquivo no arquivo Pdf de entrada.

```csharp
public bool Insert(string inputFile, int insertLocation, string portFile, int[] pageNumber, 
    string outputFile)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputFile | String | Arquivo Pdf de entrada. |
| insertLocation | Int32 | Posição de inserção no arquivo de entrada. |
| portFile | String | Páginas do arquivo Pdf. |
| pageNumber | Int32[] | O número da página do portado no portFile. |
| outputFile | String | Arquivo Pdf de saída. |

### Valor de Retorno

Verdadeiro para sucesso, ou falso.

## Exemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Insert("file1.pdf", 1, "file2.pdf", new int[] { 2, 6 }, "out.pdf");
```

### Veja Também

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Insert(Stream, int, Stream, int[], Stream) {#insert_1}

Insere páginas de outro arquivo no arquivo Pdf de entrada.

```csharp
public bool Insert(Stream inputStream, int insertLocation, Stream portStream, int[] pageNumber, 
    Stream outputStream)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputStream | Stream | Stream de entrada do arquivo Pdf. |
| insertLocation | Int32 | Posição de inserção no arquivo de entrada. |
| portStream | Stream | Stream do arquivo Pdf para páginas. |
| pageNumber | Int32[] | O número da página do portado no portFile. |
| outputStream | Stream | Stream de saída. |

### Valor de Retorno

Verdadeiro se a operação foi bem-sucedida.

## Exemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream insertedStream = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.Insert(sourceStream, 1, insertedStream, new int[] { 3, 4, 5}, outStream);
```

### Veja Também

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)