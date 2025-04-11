---
title: PdfFileEditor.TrySplitFromFirst
second_title: Aspose.PDF for .NET API Reference
description: Método PdfFileEditor. Divide o arquivo Pdf da primeira página até o local especificado e salva a parte da frente como um novo arquivo
type: docs
weight: 460
url: /pt/net/aspose.pdf.facades/pdffileeditor/trysplitfromfirst/
---
## TrySplitFromFirst(string, int, string) {#trysplitfromfirst_1}

Divide o arquivo Pdf da primeira página até o local especificado e salva a parte da frente como um novo arquivo.

```csharp
public bool TrySplitFromFirst(string inputFile, int location, string outputFile)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputFile | String | Arquivo Pdf de origem. |
| location | Int32 | O ponto de divisão. |
| outputFile | String | Arquivo Pdf de saída. |

### Valor de Retorno

Verdadeiro para sucesso, ou falso.

## Observações

O método TrySplitFromFirst é como o método SplitFromFirst, exceto que o método TrySplitFromFirst não lança uma exceção se a operação falhar.

## Exemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TrySplitFromFirst("input.pdf", 5, "out.pdf");
```

### Veja Também

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TrySplitFromFirst(Stream, int, Stream) {#trysplitfromfirst}

Divide do início até o local especificado e salva a parte da frente no Stream de saída.

```csharp
public bool TrySplitFromFirst(Stream inputStream, int location, Stream outputStream)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputStream | Stream | Stream do arquivo Pdf de origem. |
| location | Int32 | O ponto de divisão. |
| outputStream | Stream | Stream do arquivo de saída. |

### Valor de Retorno

Verdadeiro para sucesso, ou falso.

## Observações

Os streams NÃO são fechados após esta operação. O método TrySplitFromFirst é como o método SplitFromFirst, exceto que o método TrySplitFromFirst não lança uma exceção se a operação falhar.

## Exemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.TrySplitFromFirst(sourceStream, 5, outStream);
```

### Veja Também

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


## TrySplitFromFirst(string, int, HttpResponse) {#trysplitfromfirst_3}

Divide o documento da primeira página até o local e salva o resultado em objetos HttpResponse.

```csharp
public bool TrySplitFromFirst(string inputFile, int location, HttpResponse response)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputFile | String | Nome do arquivo de origem. |
| location | Int32 | Ponto de divisão. |
| response | HttpResponse | Objetos HttpResponse. |

### Valor de Retorno

verdadeiro se a operação for concluída com sucesso; caso contrário, falso.

## Observações

O método TrySplitFromFirst é como o método SplitFromFirst, exceto que o método TrySplitFromFirst não lança uma exceção se a operação falhar.

### Veja Também

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TrySplitFromFirst(Stream, int, HttpResponse) {#trysplitfromfirst_1}

Divide o documento do início até o local especificado e armazena o resultado no objeto HttpResponse.

```csharp
public bool TrySplitFromFirst(Stream inputStream, int location, HttpResponse response)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputStream | Stream | Stream do documento de origem. |
| location | Int32 | O ponto de divisão. |
| response | HttpResponse | Objeto HttpResponse onde o resultado será armazenado. |

### Valor de Retorno

verdadeiro se a operação for concluída com sucesso; caso contrário, falso.

## Observações

O método TrySplitFromFirst é como o método SplitFromFirst, exceto que o método TrySplitFromFirst não lança uma exceção se a operação falhar.

### Veja Também

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)