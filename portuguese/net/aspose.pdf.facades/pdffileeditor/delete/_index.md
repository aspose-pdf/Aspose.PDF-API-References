---
title: PdfFileEditor.Delete
second_title: Aspose.PDF for .NET API Reference
description: Método PdfFileEditor. Exclui páginas especificadas por um array de números do arquivo de entrada e salva como um novo arquivo Pdf
type: docs
weight: 270
url: /pt/net/aspose.pdf.facades/pdffileeditor/delete/
---
## Delete(string, int[], string) {#delete_1}

Exclui páginas especificadas por um array de números do arquivo de entrada, salva como um novo arquivo Pdf.

```csharp
public bool Delete(string inputFile, int[] pageNumber, string outputFile)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputFile | String | Caminho do arquivo de entrada. |
| pageNumber | Int32[] | Índice da página no arquivo de entrada. |
| outputFile | String | Caminho do arquivo de saída. |

### Valor de Retorno

Verdadeiro se a operação foi bem-sucedida.

## Exemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Delete("input.pdf", new int[] { 2, 3 }, "out.pdf");
```

### Veja Também

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Delete(Stream, int[], Stream) {#delete}

Exclui páginas especificadas por um array de números do arquivo de entrada, salva como um novo arquivo Pdf.

```csharp
public bool Delete(Stream inputStream, int[] pageNumber, Stream outputStream)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputStream | Stream | Stream do arquivo de entrada. |
| pageNumber | Int32[] | Índice da página no arquivo de entrada. |
| outputStream | Stream | Stream do arquivo de saída. |

### Valor de Retorno

Verdadeiro para sucesso, ou falso.

## Exemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream intputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.Delete(inputStream, new int[] { 2, 3 }, outputStream);
```

### Veja Também

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)