---
title: PdfFileEditor.MakeBooklet
second_title: Aspose.PDF for .NET API Reference
description: Método PdfFileEditor. Cria um livreto a partir do arquivo de entrada para o arquivo de saída
type: docs
weight: 300
url: /pt/net/aspose.pdf.facades/pdffileeditor/makebooklet/
---
## MakeBooklet(string, string) {#makebooklet_4}

Cria um livreto a partir do arquivo de entrada para o arquivo de saída.

```csharp
public bool MakeBooklet(string inputFile, string outputFile)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputFile | String | Caminho e nome do arquivo pdf de entrada. |
| outputFile | String | Caminho e nome do arquivo pdf de saída. |

### Valor de Retorno

boolean - Verdadeiro para sucesso, ou falso.

## Exemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeBooklet("input.pdf", "output.pdf");
```

### Veja Também

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, Stream) {#makebooklet}

Cria um livreto a partir do InputStream para o outputStream.

```csharp
public bool MakeBooklet(Stream inputStream, Stream outputStream)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputStream | Stream | Stream pdf de entrada. |
| outputStream | Stream | stream pdf de saída. |

### Valor de Retorno

Verdadeiro se a operação foi bem-sucedida.

## Exemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeBooklet(inputStream, outputStream);
```

### Veja Também

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeBooklet(string, string, PageSize) {#makebooklet_5}

Cria um livreto a partir do inputFile para o outputFile.

```csharp
public bool MakeBooklet(string inputFile, string outputFile, PageSize pageSize)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputFile | String | Caminho e nome do arquivo pdf de entrada. |
| outputFile | String | Caminho e nome do arquivo pdf de saída. |
| pageSize | PageSize | O tamanho da página do arquivo pdf de saída. |

### Valor de Retorno

Verdadeiro se a operação foi bem-sucedida.

## Exemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeBooklet("input.pdf", "output.pdf", PageSize.A4);
```

### Veja Também

* classe [PageSize](../../../aspose.pdf/pagesize/)
* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, Stream, PageSize) {#makebooklet_1}

Cria um livreto a partir do stream de entrada e salva o resultado no stream de saída.

```csharp
public bool MakeBooklet(Stream inputStream, Stream outputStream, PageSize pageSize)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputStream | Stream | Stream PDF de entrada. |
| outputStream | Stream | stream pdf de saída. |
| pageSize | PageSize | O tamanho da página do arquivo pdf de saída. |

### Valor de Retorno

Verdadeiro se a operação foi bem-sucedida.

## Exemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeBooklet(inputStream, outputStream, PageSize.A4);
```

### Veja Também

* classe [PageSize](../../../aspose.pdf/pagesize/)
* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeBooklet(string, string, int[], int[]) {#makebooklet_7}

Cria um livreto personalizado a partir do firstInputFile para o outputFile.

```csharp
public bool MakeBooklet(string inputFile, string outputFile, int[] leftPages, int[] rightPages)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputFile | String | O arquivo de entrada. |
| outputFile | String | Caminho e nome do arquivo pdf de saída. |
| leftPages | Int32[] | As páginas da esquerda do livreto. |
| rightPages | Int32[] | As páginas da direita do livreto. |

### Valor de Retorno

boolean - Verdadeiro para sucesso, ou falso.

## Exemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeBooklet("input.pdf", "output.pdf", new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Veja Também

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, Stream, int[], int[]) {#makebooklet_3}

Cria um livreto personalizado a partir do firstInputStream para o outputStream.

```csharp
public bool MakeBooklet(Stream inputStream, Stream outputStream, int[] leftPages, int[] rightPages)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputStream | Stream | O stream de entrada. |
| outputStream | Stream | stream pdf de saída. |
| leftPages | Int32[] | As páginas da esquerda. |
| rightPages | Int32[] | As páginas da direita. |

### Valor de Retorno

boolean - Verdadeiro para sucesso, ou falso.

## Exemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeBooklet(inputStream, outputStream, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Veja Também

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeBooklet(string, string, PageSize, int[], int[]) {#makebooklet_6}

Cria um livreto personalizado a partir do firstInputFile para o outputFile.

```csharp
public bool MakeBooklet(string inputFile, string outputFile, PageSize pageSize, int[] leftPages, 
    int[] rightPages)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputFile | String | O arquivo de entrada. |
| outputFile | String | Caminho e nome do arquivo pdf de saída. |
| pageSize | PageSize | O tamanho da página do arquivo pdf de saída. |
| leftPages | Int32[] | As páginas da esquerda. |
| rightPages | Int32[] | As páginas da direita. |

### Valor de Retorno

boolean - Verdadeiro para sucesso, ou falso.

## Exemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeBooklet("input.pdf", "output.pdf", PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Veja Também

* classe [PageSize](../../../aspose.pdf/pagesize/)
* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, Stream, PageSize, int[], int[]) {#makebooklet_2}

Cria um livreto a partir do firstInputStream para o outputStream.

```csharp
public bool MakeBooklet(Stream inputStream, Stream outputStream, PageSize pageSize, 
    int[] leftPages, int[] rightPages)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputStream | Stream | O stream de entrada. |
| outputStream | Stream | stream pdf de saída. |
| pageSize | PageSize | O tamanho da página do arquivo pdf de saída. |
| leftPages | Int32[] | As páginas da esquerda. |
| rightPages | Int32[] | As páginas da direita. |

### Valor de Retorno

boolean - Verdadeiro para sucesso, ou falso.

## Exemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeBooklet(inputStream, outputStream, PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Veja Também

* classe [PageSize](../../../aspose.pdf/pagesize/)
* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


## MakeBooklet(string, PageSize, int[], int[], HttpResponse) {#makebooklet_6}

Cria um livreto a partir do arquivo de origem e armazena o resultado em objetos HttpResponse.

```csharp
public bool MakeBooklet(string inputFile, PageSize pageSize, int[] leftPages, int[] rightPages, 
    HttpResponse response)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputFile | String | Caminho do arquivo de origem. |
| pageSize | PageSize | Tamanho da página desejado. |
| leftPages | Int32[] | Array de números de páginas a serem colocadas à esquerda. |
| rightPages | Int32[] | Array de números de páginas a serem colocadas à direita. |
| response | HttpResponse | Objeto HttpResponse onde o resultado será armazenado. |

### Valor de Retorno

Verdadeiro se a operação foi bem-sucedida.

### Veja Também

* classe [PageSize](../../../aspose.pdf/pagesize/)
* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, PageSize, int[], int[], HttpResponse) {#makebooklet}

Cria um livreto a partir do arquivo PDF e o armazena em HttpResponse.

```csharp
public bool MakeBooklet(Stream inputStream, PageSize pageSize, int[] leftPages, int[] rightPages, 
    HttpResponse response)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputStream | Stream | Stream do documento de entrada. |
| pageSize | PageSize | Tamanho da página desejado. |
| leftPages | Int32[] | Array de números de páginas que serão colocadas à esquerda. |
| rightPages | Int32[] | Array de números de páginas que serão colocadas à direita. |
| response | HttpResponse | Objeto HttpResponse. |

### Valor de Retorno

Verdadeiro se a operação foi bem-sucedida.

### Veja Também

* classe [PageSize](../../../aspose.pdf/pagesize/)
* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeBooklet(string, PageSize, HttpResponse) {#makebooklet_7}

Cria um livreto a partir do arquivo de origem e armazena o resultado em objetos HttpResponse.

```csharp
public bool MakeBooklet(string inputFile, PageSize pageSize, HttpResponse response)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputFile | String | Caminho do arquivo de origem. |
| pageSize | PageSize | Tamanho da página desejado no arquivo de saída. |
| response | HttpResponse | Objeto HttpResponse onde o resultado será armazenado. |

### Valor de Retorno

Verdadeiro se a operação foi bem-sucedida.

### Veja Também

* classe [PageSize](../../../aspose.pdf/pagesize/)
* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, PageSize, HttpResponse) {#makebooklet_1}

Cria um livreto a partir do arquivo de origem e armazena o resultado em HttpResponse.

```csharp
public bool MakeBooklet(Stream inputStream, PageSize pageSize, HttpResponse response)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputStream | Stream | Stream do documento de entrada. |
| pageSize | PageSize | Tamanho da página desejado no arquivo de saída. |
| response | HttpResponse | Objeto Respose onde o resultado será salvo. |

### Valor de Retorno

verdadeiro se o livreto foi construído com sucesso.

### Veja Também

* classe [PageSize](../../../aspose.pdf/pagesize/)
* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)