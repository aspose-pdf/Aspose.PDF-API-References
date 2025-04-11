---
title: PdfFileEditor.TryMakeBooklet
second_title: Aspose.PDF for .NET API Reference
description: Método PdfFileEditor. Cria um livreto a partir do arquivo de entrada para o arquivo de saída
type: docs
weight: 430
url: /pt/net/aspose.pdf.facades/pdffileeditor/trymakebooklet/
---
## TryMakeBooklet(string, string) {#trymakebooklet_4}

Cria um livreto a partir do arquivo fonte e armazena o resultado em objetos HttpResponse.

```csharp
public bool TryMakeBooklet(string inputFile, PageSize pageSize, int[] leftPages, int[] rightPages, 
    HttpResponse response)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputFile | String | Caminho do arquivo fonte. |
| pageSize | PageSize | Tamanho de página desejado. |
| leftPages | Int32[] | Array de números de páginas a serem colocadas à esquerda. |
| rightPages | Int32[] | Array de números de páginas a serem colocadas à direita. |
| response | HttpResponse | Objeto HttpResponse onde o resultado será armazenado. |

### Valor de Retorno

true se a operação for concluída com sucesso; caso contrário, false.

## Observações

O método TryMakeBooklet é semelhante ao método MakeBooklet, exceto que o método TryMakeBooklet não lança uma exceção se a operação falhar.

### Veja Também

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, PageSize, int[], int[], HttpResponse) {#trymakebooklet}

Cria um livreto a partir do arquivo PDF e o armazena em HttpResponse.

```csharp
public bool TryMakeBooklet(Stream inputStream, PageSize pageSize, int[] leftPages, 
    int[] rightPages, HttpResponse response)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputStream | Stream | Fluxo de documento de entrada. |
| pageSize | PageSize | Tamanho de página desejado. |
| leftPages | Int32[] | Array de números de páginas que serão colocadas à esquerda. |
| rightPages | Int32[] | Array de números de páginas que serão colocadas à direita. |
| response | HttpResponse | Objeto HttpResponse. |

### Valor de Retorno

true se a operação for concluída com sucesso; caso contrário, false.

## Observações

O método TryMakeBooklet é semelhante ao método MakeBooklet, exceto que o método TryMakeBooklet não lança uma exceção se a operação falhar.

### Veja Também

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, PageSize, HttpResponse) {#trymakebooklet_7}

Cria um livreto a partir do arquivo fonte e armazena o resultado em objetos HttpResponse.

```csharp
public bool TryMakeBooklet(string inputFile, PageSize pageSize, HttpResponse response)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputFile | String | Caminho do arquivo fonte. |
| pageSize | PageSize | Tamanho de página desejado no arquivo de saída. |
| response | HttpResponse | Objeto HttpResponse onde o resultado será armazenado. |

### Valor de Retorno

True se a operação for bem-sucedida.

## Observações

O método TryMakeBooklet é semelhante ao método MakeBooklet, exceto que o método TryMakeBooklet não lança uma exceção se a operação falhar.

### Veja Também

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, PageSize, HttpResponse) {#trymakebooklet_1}

Cria um livreto a partir do arquivo fonte e armazena o resultado em HttpResponse.

```csharp
public bool TryMakeBooklet(Stream inputStream, PageSize pageSize, HttpResponse response)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputStream | Stream | Fluxo de documento de entrada. |
| pageSize | PageSize | Tamanho de página desejado no arquivo de saída. |
| response | HttpResponse | Objeto Respose onde o resultado será salvo. |

### Valor de Retorno

true se o livreto foi construído com sucesso.

## Observações

O método TryMakeBooklet é semelhante ao método MakeBooklet, exceto que o método TryMakeBooklet não lança uma exceção se a operação falhar.

### Veja Também

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string) {#trymakebooklet_8}

Cria um livreto a partir do arquivo de entrada para o arquivo de saída.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputFile | String | Caminho e nome do arquivo PDF de entrada. |
| outputFile | String | Caminho e nome do arquivo PDF de saída. |

### Valor de Retorno

true se a operação for concluída com sucesso; caso contrário, false.

## Observações

O método TryMakeBooklet é semelhante ao método MakeBooklet, exceto que o método TryMakeBooklet não lança uma exceção se a operação falhar.

## Exemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf");
```

### Veja Também

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream) {#trymakebooklet}

Cria um livreto a partir do InputStream para outputStream.

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputStream | Stream | Fluxo PDF de entrada. |
| outputStream | Stream | fluxo PDF de saída. |

### Valor de Retorno

true se a operação for concluída com sucesso; caso contrário, false.

## Observações

O método TryMakeBooklet é semelhante ao método MakeBooklet, exceto que o método TryMakeBooklet não lança uma exceção se a operação falhar.

## Exemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream);
```

### Veja Também

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string, PageSize) {#trymakebooklet_5}

Cria um livreto a partir do inputFile para outputFile.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile, PageSize pageSize)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputFile | String | Caminho e nome do arquivo PDF de entrada. |
| outputFile | String | Caminho e nome do arquivo PDF de saída. |
| pageSize | PageSize | O tamanho da página do arquivo PDF de saída. |

### Valor de Retorno

True se a operação for bem-sucedida.

## Observações

O método TryMakeBooklet é semelhante ao método MakeBooklet, exceto que o método TryMakeBooklet não lança uma exceção se a operação falhar.

## Exemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf", PageSize.A4);
```

### Veja Também

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream, PageSize) {#trymakebooklet_1}

Cria um livreto a partir do fluxo de entrada e salva o resultado no fluxo de saída.

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream, PageSize pageSize)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputStream | Stream | Fluxo PDF de entrada. |
| outputStream | Stream | fluxo PDF de saída. |
| pageSize | PageSize | O tamanho da página do arquivo PDF de saída. |

### Valor de Retorno

true se a operação for concluída com sucesso; caso contrário, false.

## Observações

O método TryMakeBooklet é semelhante ao método MakeBooklet, exceto que o método TryMakeBooklet não lança uma exceção se a operação falhar.

## Exemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream, PageSize.A4);
```

### Veja Também

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string, int[], int[]) {#trymakebooklet_7}

Cria um livreto personalizado a partir do firstInputFile para outputFile.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile, int[] leftPages, int[] rightPages)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputFile | String | O arquivo de entrada. |
| outputFile | String | Caminho e nome do arquivo PDF de saída. |
| leftPages | Int32[] | As páginas da esquerda do livreto. |
| rightPages | Int32[] | As páginas da direita do livreto. |

### Valor de Retorno

true se a operação for concluída com sucesso; caso contrário, false.

## Observações

O método TryMakeBooklet é semelhante ao método MakeBooklet, exceto que o método TryMakeBooklet não lança uma exceção se a operação falhar.

## Exemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf", new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Veja Também

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream, int[], int[]) {#trymakebooklet_3}

Cria um livreto personalizado a partir do firstInputStream para outputStream.

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream, int[] leftPages, 
    int[] rightPages)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputStream | Stream | O fluxo de entrada. |
| outputStream | Stream | fluxo PDF de saída. |
| leftPages | Int32[] | As páginas da esquerda. |
| rightPages | Int32[] | As páginas da direita. |

### Valor de Retorno

true se a operação for concluída com sucesso; caso contrário, false.

## Observações

O método TryMakeBooklet é semelhante ao método MakeBooklet, exceto que o método TryMakeBooklet não lança uma exceção se a operação falhar.

## Exemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Veja Também

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string, PageSize, int[], int[]) {#trymakebooklet_6}

Cria um livreto personalizado a partir do firstInputFile para outputFile.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile, PageSize pageSize, int[] leftPages, 
    int[] rightPages)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputFile | String | O arquivo de entrada. |
| outputFile | String | Caminho e nome do arquivo PDF de saída. |
| pageSize | PageSize | O tamanho da página do arquivo PDF de saída. |
| leftPages | Int32[] | As páginas da esquerda. |
| rightPages | Int32[] | As páginas da direita. |

### Valor de Retorno

true se a operação for concluída com sucesso; caso contrário, false.

## Observações

O método TryMakeBooklet é semelhante ao método MakeBooklet, exceto que o método TryMakeBooklet não lança uma exceção se a operação falhar.

## Exemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf", PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Veja Também

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream, PageSize, int[], int[]) {#trymakebooklet_2}

Cria um livreto a partir do firstInputStream para outputStream.

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream, PageSize pageSize, 
    int[] leftPages, int[] rightPages)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputStream | Stream | O fluxo de entrada. |
| outputStream | Stream | fluxo PDF de saída. |
| pageSize | PageSize | O tamanho da página do arquivo PDF de saída. |
| leftPages | Int32[] | As páginas da esquerda. |
| rightPages | Int32[] | As páginas da direita. |

### Valor de Retorno

true se a operação for concluída com sucesso; caso contrário, false.

## Observações

O método TryMakeBooklet é semelhante ao método MakeBooklet, exceto que o método TryMakeBooklet não lança uma exceção se a operação falhar.

## Exemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream, PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Veja Também

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)