---
title: PdfFileEditor.TryExtract
second_title: Aspose.PDF for .NET API Reference
description: Método PdfFileEditor. Extrai páginas de arquivos de entrada e salva como um novo arquivo Pdf
type: docs
weight: 410
url: /pt/net/aspose.pdf.facades/pdffileeditor/tryextract/
---
## TryExtract(string, int, int, string) {#tryextract_1}

Extrai páginas do arquivo de entrada, salva como um novo arquivo Pdf.

```csharp
public bool TryExtract(string inputFile, int startPage, int endPage, string outputFile)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputFile | String | Caminho do arquivo Pdf de entrada. |
| startPage | Int32 | Número da página inicial. |
| endPage | Int32 | Número da página final. |
| outputFile | String | Caminho do arquivo Pdf de saída. |

### Valor de Retorno

Verdadeiro para sucesso, ou falso.

## Observações

O método TryExtract é semelhante ao método Extract, exceto que o método TryExtract não lança uma exceção se a operação falhar.

## Exemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryExtract("input.pdf", 3, 7, "output.pdf");
```

### Veja Também

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryExtract(string, int[], string) {#tryextract_2}

Extrai páginas especificadas por um array de números, salva como um novo arquivo PDF.

```csharp
public bool TryExtract(string inputFile, int[] pageNumber, string outputFile)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputFile | String | Caminho do arquivo de entrada. |
| pageNumber | Int32[] | Índice da página do arquivo de entrada. |
| outputFile | String | Caminho do arquivo de saída. |

### Valor de Retorno

verdadeiro se a operação foi concluída com sucesso; caso contrário, falso.

## Observações

O método TryExtract é semelhante ao método Extract, exceto que o método TryExtract não lança uma exceção se a operação falhar.

## Exemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryExtract("input.pdf", new int[] { 3, 5, 7 }, "output.pdf");
```

### Veja Também

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryExtract(Stream, int[], Stream) {#tryextract}

Extrai páginas especificadas por um array de números, salva como um novo arquivo Pdf.

```csharp
public bool TryExtract(Stream inputStream, int[] pageNumber, Stream outputStream)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputStream | Stream | Stream do arquivo de entrada. |
| pageNumber | Int32[] | Índice da página do arquivo de entrada. |
| outputStream | Stream | Stream do arquivo de saída. |

### Valor de Retorno

Verdadeiro para sucesso, ou falso.

## Observações

O método TryExtract é semelhante ao método Extract, exceto que o método TryExtract não lança uma exceção se a operação falhar.

## Exemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryExtract(sourceStream, new int[] { 3, 5, 8 }, outStream);
```

### Veja Também

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


## TryExtract(Stream, int[], HttpResponse) {#tryextract_1}

Extrai páginas especificadas do arquivo de origem e armazena o resultado no objeto HttpResponse.

```csharp
public bool TryExtract(Stream inputStream, int[] pageNumber, HttpResponse response)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputStream | Stream | Stream do documento de origem. |
| pageNumber | Int32[] | Array de números de páginas que serão extraídas. |
| response | HttpResponse | Objeto HttpResponse onde o resultado será armazenado. |

### Valor de Retorno

verdadeiro se a operação foi concluída com sucesso; caso contrário, falso.

## Observações

O método TryExtract é semelhante ao método Extract, exceto que o método TryExtract não lança uma exceção se a operação falhar.

### Veja Também

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryExtract(string, int[], HttpResponse) {#tryextract_4}

Extrai páginas especificadas do arquivo de origem e armazena o resultado no objeto HttpResponse.

```csharp
public bool TryExtract(string inputFile, int[] pageNumber, HttpResponse response)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputFile | String | Caminho do arquivo de origem. |
| pageNumber | Int32[] | Array de números de páginas que serão extraídas. |
| response | HttpResponse | Objeto HttpResponse onde o resultado será armazenado. |

### Valor de Retorno

verdadeiro se a operação foi concluída com sucesso; caso contrário, falso.

## Observações

O método TryExtract é semelhante ao método Extract, exceto que o método TryExtract não lança uma exceção se a operação falhar.

### Veja Também

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)