---
title: PdfFileEditor.TryDelete
second_title: Aspose.PDF for .NET API Reference
description: Método PdfFileEditor. Exclui páginas especificadas por um array de números do arquivo de entrada e salva como um novo arquivo Pdf
type: docs
weight: 400
url: /pt/net/aspose.pdf.facades/pdffileeditor/trydelete/
---
## TryDelete(string, int[], string) {#trydelete_1}

Exclui páginas especificadas por um array de números do arquivo de entrada, salva como um novo arquivo Pdf.

```csharp
public bool TryDelete(string inputFile, int[] pageNumber, string outputFile)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputFile | String | Caminho do arquivo de entrada. |
| pageNumber | Int32[] | Índice da página do arquivo de entrada. |
| outputFile | String | Caminho do arquivo de saída. |

### Valor de Retorno

true se a operação for concluída com sucesso; caso contrário, false.

## Observações

O método TryDelete é semelhante ao método Delete, exceto que o método TryDelete não lança uma exceção se a operação falhar.

## Exemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryDelete("input.pdf", new int[] { 2, 3 }, "out.pdf");
```

### Veja Também

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryDelete(Stream, int[], Stream) {#trydelete}

Exclui páginas especificadas por um array de números do arquivo de entrada, salva como um novo arquivo Pdf.

```csharp
public bool TryDelete(Stream inputStream, int[] pageNumber, Stream outputStream)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputStream | Stream | Stream do arquivo de entrada. |
| pageNumber | Int32[] | Índice da página do arquivo de entrada. |
| outputStream | Stream | Stream do arquivo de saída. |

### Valor de Retorno

True para sucesso, ou false.

## Observações

O método TryDelete é semelhante ao método Delete, exceto que o método TryDelete não lança uma exceção se a operação falhar.

## Exemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream intputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryDelete(inputStream, new int[] { 2, 3 }, outputStream);
```

### Veja Também

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


## TryDelete(string, int[], HttpResponse) {#trydelete_3}

Exclui páginas especificadas do documento e armazena o resultado no objeto HttpResponse.

```csharp
public bool TryDelete(string inputFile, int[] pageNumber, HttpResponse response)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputFile | String | Caminho do arquivo fonte. |
| pageNumber | Int32[] | Array de números das páginas que devem ser excluídas. |
| response | HttpResponse | Objeto de resposta onde o documento resultante será armazenado. |

### Valor de Retorno

true se a operação for concluída com sucesso; caso contrário, false.

## Observações

O método TryDelete é semelhante ao método Delete, exceto que o método TryDelete não lança uma exceção se a operação falhar.

### Veja Também

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryDelete(Stream, int[], HttpResponse) {#trydelete_1}

Exclui páginas especificadas do documento e salva o resultado no objeto HttpResponse.

```csharp
public bool TryDelete(Stream inputStream, int[] pageNumber, HttpResponse response)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputStream | Stream | Stream do documento fonte. |
| pageNumber | Int32[] | Array de números das páginas que serão excluídas. |
| response | HttpResponse | Objeto HttpResponse |

### Valor de Retorno

true se a operação for concluída com sucesso; caso contrário, false.

## Observações

O método TryDelete é semelhante ao método Delete, exceto que o método TryDelete não lança uma exceção se a operação falhar.

### Veja Também

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)