---
title: PdfFileEditor.MakeNUp
second_title: Aspose.PDF for .NET API Reference
description: Método PdfFileEditor. Cria um documento NUp a partir dos dois fluxos PDF de entrada para outputStream
type: docs
weight: 310
url: /pt/net/aspose.pdf.facades/pdffileeditor/makenup/
---
## MakeNUp(Stream, Stream, Stream) {#makenup_2}

Cria um documento N-Up a partir do firstInputFile para outputFile.

```csharp
public bool MakeNUp(string inputFile, string outputFile, int x, int y)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputFile | String | Caminho e nome do arquivo pdf de entrada. |
| outputFile | String | Caminho e nome do arquivo pdf de saída. |
| x | Int32 | Número de colunas. |
| y | Int32 | Número de linhas. |

### Valor de Retorno

boolean - Verdadeiro para sucesso, ou falso.

## Exemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp("input.pdf", "output.pdf", 3, 3);
```

### Veja Também

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(Stream, Stream, int, int) {#makenup_2}

Cria um documento N-Up a partir do fluxo de entrada e salva o resultado no fluxo de saída.

```csharp
public bool MakeNUp(Stream inputStream, Stream outputStream, int x, int y)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputStream | Stream | Fluxo pdf de entrada. |
| outputStream | Stream | Fluxo pdf de saída. |
| x | Int32 | Número de colunas. |
| y | Int32 | Número de linhas. |

### Valor de Retorno

boolean - Verdadeiro para sucesso, ou falso.

## Exemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeNUp(inputStream, outputStream, 3, 3);
```

### Veja Também

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(Stream, Stream, int, int, PageSize) {#makenup_3}

Cria um documento N-Up a partir do primeiro fluxo de entrada para o fluxo de saída.

```csharp
public bool MakeNUp(Stream inputStream, Stream outputStream, int x, int y, PageSize pageSize)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputStream | Stream | Fluxo pdf de entrada. |
| outputStream | Stream | Fluxo pdf de saída. |
| x | Int32 | Número de colunas. |
| y | Int32 | Número de linhas. |
| pageSize | PageSize | O tamanho da página do arquivo pdf de saída. |

### Valor de Retorno

Verdadeiro se a operação foi bem-sucedida.

## Exemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeNUp(inputStream, outputStream, 3, 3, PageSize.A4);
```

### Veja Também

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(string, string, string) {#makenup_10}

Cria um documento N-Up a partir dos dois arquivos PDF de entrada para outputFile. Cada página do outputFile conterá duas páginas, uma página é do primeiro arquivo de entrada e outra é do segundo arquivo de entrada. As duas páginas são empilhadas horizontalmente.

```csharp
public bool MakeNUp(string firstInputFile, string secondInputFile, string outputFile)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| firstInputFile | String | primeiro arquivo de entrada. |
| secondInputFile | String | segundo arquivo de entrada. |
| outputFile | String | Caminho e nome do arquivo pdf de saída. |

### Valor de Retorno

boolean - Verdadeiro para sucesso, ou falso.

## Exemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp("input1.pdf", "input2.pdf", "output.pdf");
```

### Veja Também

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(Stream, Stream, Stream) {#makenup_4}

Cria um documento N-Up a partir dos dois fluxos PDF de entrada para outputStream.

```csharp
public bool MakeNUp(Stream firstInputStream, Stream secondInputStream, Stream outputStream)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| firstInputStream | Stream | primeiro fluxo de entrada. |
| secondInputStream | Stream | segundo fluxo de entrada. |
| outputStream | Stream | Fluxo pdf de saída. |

### Valor de Retorno

boolean - Verdadeiro para sucesso, ou falso.

## Exemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream input1 = new FileStream("input1.pdf", FileMode.Open, FileAccess.Read);
Stream input2 = new FileStream("input2.pdf", FileMode.Open, FileAccess.Read);
Stream output = new FileStream("output.pdf");
pfe.MakeNUp(input1, input2, output);
```

### Veja Também

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(string[], string, bool) {#makenup_7}

Cria um documento N-Up a partir dos múltiplos arquivos PDF de entrada para outputFile. Cada página do outputFile conterá várias páginas, que são combinações com páginas nos arquivos de entrada do mesmo número de página. As múltiplas páginas são empilhadas horizontalmente se isSidewise for verdadeiro e empilhadas verticalmente se isSidewise for falso.

```csharp
public bool MakeNUp(string[] inputFiles, string outputFile, bool isSidewise)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputFiles | String[] | Arquivos Pdf de entrada. |
| outputFile | String | Caminho e nome do arquivo pdf de saída. |
| isSidewise | Boolean | Modo de empilhamento, verdadeiro para horizontalmente e falso para verticalmente. |

### Valor de Retorno

boolean - Verdadeiro para sucesso, ou falso.

## Exemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp(new string[] { "input1.pdf", "input2.pdf", "input3.pdf" }, "output.pdf", false);
```

### Veja Também

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(Stream[], Stream, bool) {#makenup_3}

Cria um documento N-Up a partir dos múltiplos fluxos PDF de entrada para outputStream. Cada página do outputStream conterá várias páginas, que são combinações com páginas nos fluxos de entrada do mesmo número de página. As múltiplas páginas são empilhadas horizontalmente se isSidewise for verdadeiro e empilhadas verticalmente se isSidewise for falso.

```csharp
public bool MakeNUp(Stream[] inputStreams, Stream outputStream, bool isSidewise)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputStreams | Stream[] | Fluxos Pdf de entrada. |
| outputStream | Stream | Fluxo pdf de saída. |
| isSidewise | Boolean | Modo de empilhamento, verdadeiro para horizontalmente e falso para verticalmente. |

### Valor de Retorno

boolean - Verdadeiro para sucesso, ou falso.

## Exemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream stream1 = new FileStream("input1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("input2.pdf", FileMode.Open, FileAccess.Read);
Stream stream3 = new FileStream("input3.pdf", FileMode.Open, FileAccess.Read);
Stream output = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeNUp(new Stream[] { stream1, stream2, stream3 }, output, false);
```

### Veja Também

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(string, string, int, int, PageSize) {#makenup_5}

Cria um documento N-Up a partir do arquivo de entrada para outputFile.

```csharp
public bool MakeNUp(string inputFile, string outputFile, int x, int y, PageSize pageSize)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputFile | String | Caminho e nome do arquivo pdf de entrada. |
| outputFile | String | Caminho e nome do arquivo pdf de saída. |
| x | Int32 | Número de colunas. |
| y | Int32 | Número de linhas. |
| pageSize | PageSize | O tamanho da página do arquivo pdf de saída. |

### Valor de Retorno

boolean - Verdadeiro para sucesso, ou falso.

## Exemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp("input.pdf", "output.pdf", 3, 3, PageSize.A4);
```

### Veja Também

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(string, string, int, int) {#makenup_4}

Cria um documento N-Up a partir do firstInputFile para outputFile.

```csharp
public bool MakeNUp(string inputFile, string outputFile, int x, int y)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputFile | String | Caminho e nome do arquivo pdf de entrada. |
| outputFile | String | Caminho e nome do arquivo pdf de saída. |
| x | Int32 | Número de colunas. |
| y | Int32 | Número de linhas. |

### Valor de Retorno

boolean - Verdadeiro para sucesso, ou falso.

## Exemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp("input.pdf", "output.pdf", 3, 3);
```

### Veja Também

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(Stream, Stream, int, int) {#makenup}

Cria um documento N-Up a partir do fluxo de entrada e salva o resultado no fluxo de saída.

```csharp
public bool MakeNUp(Stream inputStream, Stream outputStream, int x, int y)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputStream | Stream | Fluxo pdf de entrada. |
| outputStream | Stream | Fluxo pdf de saída. |
| x | Int32 | Número de colunas. |
| y | Int32 | Número de linhas. |

### Valor de Retorno

boolean - Verdadeiro para sucesso, ou falso.

## Exemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeNUp(inputStream, outputStream, 3, 3);
```

### Veja Também

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(Stream, Stream, int, int, PageSize) {#makenup_1}

Cria um documento N-Up a partir do primeiro fluxo de entrada para o fluxo de saída.

```csharp
public bool MakeNUp(Stream inputStream, Stream outputStream, int x, int y, PageSize pageSize)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputStream | Stream | Fluxo pdf de entrada. |
| outputStream | Stream | Fluxo pdf de saída. |
| x | Int32 | Número de colunas. |
| y | Int32 | Número de linhas. |
| pageSize | PageSize | O tamanho da página do arquivo pdf de saída. |

### Valor de Retorno

Verdadeiro se a operação foi bem-sucedida.

## Exemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeNUp(inputStream, outputStream, 3, 3, PageSize.A4);
```

### Veja Também

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(string, string, string) {#makenup_6}

Cria um documento N-Up a partir dos dois arquivos PDF de entrada para outputFile. Cada página do outputFile conterá duas páginas, uma página é do primeiro arquivo de entrada e outra é do segundo arquivo de entrada. As duas páginas são empilhadas horizontalmente.

```csharp
public bool MakeNUp(string firstInputFile, string secondInputFile, string outputFile)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| firstInputFile | String | primeiro arquivo de entrada. |
| secondInputFile | String | segundo arquivo de entrada. |
| outputFile | String | Caminho e nome do arquivo pdf de saída. |

### Valor de Retorno

boolean - Verdadeiro para sucesso, ou falso.

## Exemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp("input1.pdf", "input2.pdf", "output.pdf");
```

### Veja Também

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)