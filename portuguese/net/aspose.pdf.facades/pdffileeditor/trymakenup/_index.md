---
title: PdfFileEditor.TryMakeNUp
second_title: Aspose.PDF for .NET API Reference
description: Método PdfFileEditor. Cria um documento NUp do firstInputFile para outputFile
type: docs
weight: 440
url: /pt/net/aspose.pdf.facades/pdffileeditor/trymakenup/
---
## TryMakeNUp(string, string, int, int) {#trymakenup_4}

Cria um documento N-up e armazena o resultado no objeto HttpResponse.

```csharp
public bool TryMakeNUp(string inputFile, int x, int y, PageSize pageSize, HttpResponse response)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputFile | String | Caminho para o arquivo de origem. |
| x | Int32 | Número de colunas. |
| y | Int32 | Número de linhas. |
| pageSize | PageSize | Tamanho da página no arquivo de resultado. |
| response | HttpResponse | Objeto HttpResponse onde o resultado será armazenado. |

### Valor de Retorno

true se a operação foi concluída com sucesso; caso contrário, false.

## Observações

O método TryMakeNUp é semelhante ao método MakeNUp, exceto que o método TryMakeNUp não lança uma exceção se a operação falhar.

### Veja Também

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, int, int, PageSize, HttpResponse) {#trymakenup}

Cria um documento N-up e armazena o resultado no objeto HttpResponse.

```csharp
public bool TryMakeNUp(Stream inputStream, int x, int y, PageSize pageSize, HttpResponse response)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputStream | Stream | Stream do documento de origem. |
| x | Int32 | Número de colunas. |
| y | Int32 | Número de linhas. |
| pageSize | PageSize | Tamanho da página no arquivo de resultado. |
| response | HttpResponse | Objeto HttpResponse onde o resultado será armazenado. |

### Valor de Retorno

true se a operação foi concluída com sucesso; caso contrário, false.

## Observações

O método TryMakeNUp é semelhante ao método MakeNUp, exceto que o método TryMakeNUp não lança uma exceção se a operação falhar.

### Veja Também

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(string, int, int, HttpResponse) {#trymakenup_7}

Cria um documento N-up e armazena o resultado no HttpResponse.

```csharp
public bool TryMakeNUp(string inputFile, int x, int y, HttpResponse response)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputFile | String | Nome do arquivo de origem. |
| x | Int32 | Número de colunas. |
| y | Int32 | Número de linhas. |
| response | HttpResponse | Objeto HttpResponse onde o resultado será armazenado. |

### Valor de Retorno

true se a operação foi concluída com sucesso; caso contrário, false.

## Observações

O método TryMakeNUp é semelhante ao método MakeNUp, exceto que o método TryMakeNUp não lança uma exceção se a operação falhar.

### Veja Também

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, int, int, HttpResponse) {#trymakenup_1}

Cria um documento N-up e armazena o resultado no HttpResponse.

```csharp
public bool TryMakeNUp(Stream inputStream, int x, int y, HttpResponse response)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputStream | Stream | Stream do documento de entrada. |
| x | Int32 | Número de colunas. |
| y | Int32 | Número de linhas. |
| response | HttpResponse | HttpResponse onde o resultado será armazenado. |

### Valor de Retorno

true se a operação foi concluída com sucesso; caso contrário, false.

## Observações

O método TryMakeNUp é semelhante ao método MakeNUp, exceto que o método TryMakeNUp não lança uma exceção se a operação falhar.

### Veja Também

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(string, string, int, int) {#trymakenup_8}

Cria um documento N-Up do firstInputFile para outputFile.

```csharp
public bool TryMakeNUp(string inputFile, string outputFile, int x, int y)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputFile | String | Caminho e nome do arquivo pdf de entrada. |
| outputFile | String | Caminho e nome do arquivo pdf de saída. |
| x | Int32 | Número de colunas. |
| y | Int32 | Número de linhas. |

### Valor de Retorno

true se a operação foi concluída com sucesso; caso contrário, false.

## Observações

O método TryMakeNUp é semelhante ao método MakeNUp, exceto que o método TryMakeNUp não lança uma exceção se a operação falhar.

## Exemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp("input.pdf", "output.pdf", 3, 3);
```

### Veja Também

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, Stream, int, int) {#trymakenup}

Cria um documento N-Up do stream de entrada e salva o resultado no stream de saída.

```csharp
public bool TryMakeNUp(Stream inputStream, Stream outputStream, int x, int y)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputStream | Stream | Stream pdf de entrada. |
| outputStream | Stream | Stream pdf de saída. |
| x | Int32 | Número de colunas. |
| y | Int32 | Número de linhas. |

### Valor de Retorno

true se a operação foi concluída com sucesso; caso contrário, false.

## Observações

O método TryMakeNUp é semelhante ao método MakeNUp, exceto que o método TryMakeNUp não lança uma exceção se a operação falhar.

## Exemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeNUp(inputStream, outputStream, 3, 3);
```

### Veja Também

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, Stream, int, int, PageSize) {#trymakenup_1}

Cria um documento N-Up do primeiro stream de entrada para o stream de saída.

```csharp
public bool TryMakeNUp(Stream inputStream, Stream outputStream, int x, int y, PageSize pageSize)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputStream | Stream | Stream pdf de entrada. |
| outputStream | Stream | Stream pdf de saída. |
| x | Int32 | Número de colunas. |
| y | Int32 | Número de linhas. |
| pageSize | PageSize | O tamanho da página do arquivo pdf de saída. |

### Valor de Retorno

true se a operação foi concluída com sucesso; caso contrário, false.

## Observações

O método TryMakeNUp é semelhante ao método MakeNUp, exceto que o método TryMakeNUp não lança uma exceção se a operação falhar.

## Exemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeNUp(inputStream, outputStream, 3, 3, PageSize.A4);
```

### Veja Também

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(string, string, string) {#trymakenup_6}

Cria um documento N-Up a partir dos dois arquivos PDF de entrada para outputFile. Cada página do outputFile conterá duas páginas, uma página é do primeiro arquivo de entrada e outra é do segundo arquivo de entrada. As duas páginas são empilhadas horizontalmente.

```csharp
public bool TryMakeNUp(string firstInputFile, string secondInputFile, string outputFile)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| firstInputFile | String | primeiro arquivo de entrada. |
| secondInputFile | String | segundo arquivo de entrada. |
| outputFile | String | Caminho e nome do arquivo pdf de saída. |

### Valor de Retorno

true se a operação foi concluída com sucesso; caso contrário, false

## Observações

O método TryMakeNUp é semelhante ao método MakeNUp, exceto que o método TryMakeNUp não lança uma exceção se a operação falhar.

## Exemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp("input1.pdf", "input2.pdf", "output.pdf");
```

### Veja Também

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, Stream, Stream) {#trymakenup_2}

Cria um documento N-Up a partir dos dois streams PDF de entrada para outputStream.

```csharp
public bool TryMakeNUp(Stream firstInputStream, Stream secondInputStream, Stream outputStream)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| firstInputStream | Stream | primeiro stream de entrada. |
| secondInputStream | Stream | segundo stream de entrada. |
| outputStream | Stream | Stream pdf de saída. |

### Valor de Retorno

true se a operação foi concluída com sucesso; caso contrário, false

## Observações

O método TryMakeNUp é semelhante ao método MakeNUp, exceto que o método TryMakeNUp não lança uma exceção se a operação falhar.

## Exemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream input1 = new FileStream("input1.pdf", FileMode.Open, FileAccess.Read);
Stream input2 = new FileStream("input2.pdf", FileMode.Open, FileAccess.Read);
Stream output = new FileStream("output.pdf");
bool result = pfe.TryMakeNUp(input1, input2, output);
```

### Veja Também

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(string[], string, bool) {#trymakenup_7}

Cria um documento N-Up a partir dos múltiplos arquivos PDF de entrada para outputFile. Cada página do outputFile conterá várias páginas, que são combinações de páginas nos arquivos de entrada do mesmo número de página. As múltiplas páginas são empilhadas horizontalmente se isSidewise for true e empilhadas verticalmente se isSidewise for false.

```csharp
public bool TryMakeNUp(string[] inputFiles, string outputFile, bool isSidewise)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputFiles | String[] | Arquivos Pdf de entrada. |
| outputFile | String | Caminho e nome do arquivo pdf de saída. |
| isSidewise | Boolean | Forma de empilhamento, true para horizontalmente e false para verticalmente. |

### Valor de Retorno

true se a operação foi concluída com sucesso; caso contrário, false.

## Observações

O método TryMakeNUp é semelhante ao método MakeNUp, exceto que o método TryMakeNUp não lança uma exceção se a operação falhar.

## Exemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp(new string[] { "input1.pdf", "input2.pdf", "input3.pdf" }, "output.pdf", false);
```

### Veja Também

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream[], Stream, bool) {#trymakenup_3}

Cria um documento N-Up a partir dos múltiplos streams PDF de entrada para outputStream. Cada página do outputStream conterá várias páginas, que são combinações de páginas nos streams de entrada do mesmo número de página. As múltiplas páginas são empilhadas horizontalmente se isSidewise for true e empilhadas verticalmente se isSidewise for false.

```csharp
public bool TryMakeNUp(Stream[] inputStreams, Stream outputStream, bool isSidewise)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputStreams | Stream[] | Streams Pdf de entrada. |
| outputStream | Stream | Stream pdf de saída. |
| isSidewise | Boolean | Forma de empilhamento, true para horizontalmente e false para verticalmente. |

### Valor de Retorno

true se a operação foi concluída com sucesso; caso contrário, false.

## Observações

O método TryMakeNUp é semelhante ao método MakeNUp, exceto que o método TryMakeNUp não lança uma exceção se a operação falhar.

## Exemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream stream1 = new FileStream("input1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("input2.pdf", FileMode.Open, FileAccess.Read);
Stream stream3 = new FileStream("input3.pdf", FileMode.Open, FileAccess.Read);
Stream output = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeNUp(new Stream[] { stream1, stream2, stream3 }, output, false);
```

### Veja Também

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(string, string, int, int, PageSize) {#trymakenup_5}

Cria um documento N-Up do arquivo de entrada para outputFile.

```csharp
public bool TryMakeNUp(string inputFile, string outputFile, int x, int y, PageSize pageSize)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputFile | String | Caminho e nome do arquivo pdf de entrada. |
| outputFile | String | Caminho e nome do arquivo pdf de saída. |
| x | Int32 | Número de colunas. |
| y | Int32 | Número de linhas. |
| pageSize | PageSize | O tamanho da página do arquivo pdf de saída. |

### Valor de Retorno

true se a operação foi concluída com sucesso; caso contrário, false.

## Observações

O método TryMakeNUp é semelhante ao método MakeNUp, exceto que o método TryMakeNUp não lança uma exceção se a operação falhar.

## Exemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp("input.pdf", "output.pdf", 3, 3, PageSize.A4);
```

### Veja Também

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)