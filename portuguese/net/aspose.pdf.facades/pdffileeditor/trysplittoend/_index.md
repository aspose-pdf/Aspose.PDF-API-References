---
title: PdfFileEditor.TrySplitToEnd
second_title: Aspose.PDF for .NET API Reference
description: Método PdfFileEditor. Divide a partir da localização e salva a parte traseira como um novo arquivo
type: docs
weight: 470
url: /pt/net/aspose.pdf.facades/pdffileeditor/trysplittoend/
---
## TrySplitToEnd(string, int, string) {#trysplittoend_1}

Divide a partir da localização e salva a parte traseira como um novo arquivo.

```csharp
public bool TrySplitToEnd(string inputFile, int location, string outputFile)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputFile | String | Arquivo Pdf de origem. |
| location | Int32 | A posição de divisão. |
| outputFile | String | Caminho do arquivo Pdf de saída. |

### Valor de Retorno

Verdadeiro para sucesso, ou falso.

## Observações

O método TrySplitToEnd é como o método SplitToEnd, exceto que o método TrySplitToEnd não lança uma exceção se a operação falhar.

## Exemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TrySplitToEnd("input.pdf", 5, "out.pdf");
```

### Veja Também

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TrySplitToEnd(Stream, int, Stream) {#trysplittoend}

Divide a partir da localização especificada e salva a parte traseira como um novo arquivo Stream.

```csharp
public bool TrySplitToEnd(Stream inputStream, int location, Stream outputStream)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputStream | Stream | Stream do arquivo Pdf de origem. |
| location | Int32 | A posição de divisão. |
| outputStream | Stream | Stream do arquivo Pdf de saída. |

### Valor de Retorno

Verdadeiro para sucesso, ou falso.

## Observações

Os streams NÃO são fechados após esta operação, a menos que CloseConcatedStreams seja especificado. O método TrySplitToEnd é como o método SplitToEnd, exceto que o método TrySplitToEnd não lança uma exceção se a operação falhar.

## Exemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TrySplitToEnd(sourceStream, 5, outStream);
```

### Veja Também

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


## TrySplitToEnd(Stream, int, HttpResponse) {#trysplittoend_1}

Divide a partir da localização especificada e salva a parte traseira no objeto HttpResponse.

```csharp
public bool TrySplitToEnd(Stream inputStream, int location, HttpResponse response)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputStream | Stream | Stream do documento de origem. |
| location | Int32 | Ponto de divisão. |
| response | HttpResponse | Objeto HttpResponse. |

### Valor de Retorno

verdadeiro se a operação foi concluída com sucesso; caso contrário, falso.

## Observações

O método TrySplitToEnd é como o método SplitToEnd, exceto que o método TrySplitToEnd não lança uma exceção se a operação falhar.

### Veja Também

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TrySplitToEnd(string, int, HttpResponse) {#trysplittoend_3}

Divide a partir da localização especificada e salva a parte traseira no objeto HttpResponse.

```csharp
public bool TrySplitToEnd(string inputFile, int location, HttpResponse response)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputFile | String | nome do arquivo de origem. |
| location | Int32 | Ponto de divisão. |
| response | HttpResponse | Objetos HttpResponse. |

### Valor de Retorno

verdadeiro se a operação foi concluída com sucesso; caso contrário, falso.

## Observações

O método TrySplitToEnd é como o método SplitToEnd, exceto que o método TrySplitToEnd não lança uma exceção se a operação falhar.

### Veja Também

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)