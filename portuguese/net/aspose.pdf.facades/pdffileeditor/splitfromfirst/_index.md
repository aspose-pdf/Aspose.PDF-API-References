---
title: PdfFileEditor.SplitFromFirst
second_title: Aspose.PDF for .NET API Reference
description: Método PdfFileEditor. Divide o arquivo Pdf da primeira página até o local especificado e salva a parte da frente como um novo arquivo
type: docs
weight: 340
url: /pt/net/aspose.pdf.facades/pdffileeditor/splitfromfirst/
---
## SplitFromFirst(string, int, string) {#splitfromfirst_1}

Divide o arquivo Pdf da primeira página até o local especificado e salva a parte da frente como um novo arquivo.

```csharp
public bool SplitFromFirst(string inputFile, int location, string outputFile)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputFile | String | Arquivo Pdf de origem. |
| location | Int32 | O ponto de divisão. |
| outputFile | String | Arquivo Pdf de saída. |

### Valor de Retorno

Verdadeiro para sucesso, ou falso.

## Exemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.SplitFromFirst("input.pdf", 5, "out.pdf");
```

### Veja Também

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SplitFromFirst(Stream, int, Stream) {#splitfromfirst}

Divide do início até o local especificado e salva a parte da frente no Stream de saída.

```csharp
public bool SplitFromFirst(Stream inputStream, int location, Stream outputStream)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputStream | Stream | Stream do arquivo Pdf de origem. |
| location | Int32 | O ponto de divisão. |
| outputStream | Stream | Stream do arquivo de saída. |

### Valor de Retorno

Verdadeiro para sucesso, ou falso.

## Observações

Os streams NÃO são fechados após esta operação.

## Exemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.SplitFromFirst(sourceStream, 5, outStream);
```

### Veja Também

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)