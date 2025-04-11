---
title: PdfFileEditor.SplitToPages
second_title: Aspose.PDF for .NET API Reference
description: Método PdfFileEditor. Divide o arquivo PDF em documentos de página única
type: docs
weight: 370
url: /pt/net/aspose.pdf.facades/pdffileeditor/splittopages/
---
## SplitToPages(string) {#splittopages_1}

Divide o arquivo PDF em documentos de página única.

```csharp
public MemoryStream[] SplitToPages(string inputFile)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputFile | String | Nome do arquivo PDF de entrada. |

### Valor de Retorno

Fluxos PDF de saída, cada fluxo armazena um documento PDF de página única.

### Veja Também

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SplitToPages(Stream) {#splittopages}

Divide o arquivo Pdf em documentos de página única.

```csharp
public MemoryStream[] SplitToPages(Stream inputStream)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputStream | Stream | Fluxo Pdf de entrada. |

### Valor de Retorno

Array de fluxos de memória que contêm as páginas do documento.

### Veja Também

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SplitToPages(string, string) {#splittopages_3}

Divide o arquivo Pdf em documentos de página única e o salva no caminho especificado. O caminho é especificado pelo nome do campo template.

```csharp
public void SplitToPages(string inputFile, string fileNameTemplate)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputFile | String | Nome do arquivo de entrada. |
| fileNameTemplate | String | Template do nome do arquivo resultante. Deve conter %NUM% que é substituído pelo número da página. Por exemplo, se c:/dir/page%NUM%.pdf for especificado, os arquivos resultantes terão os seguintes nomes: c:/dir/page1.pdf, c:/dir/page2.pdf etc. |

### Veja Também

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SplitToPages(Stream, string) {#splittopages_2}

Divide o arquivo Pdf em documentos de página única e o salva no caminho especificado. O caminho é especificado pelo nome do campo template.

```csharp
public void SplitToPages(Stream inputStream, string fileNameTemplate)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputStream | Stream | Fluxo do documento de origem. |
| fileNameTemplate | String | Template do nome do arquivo resultante. Deve conter %NUM% que é substituído pelo número da página. Por exemplo, se c:/dir/page%NUM%.pdf for especificado, os arquivos resultantes terão os seguintes nomes: c:/dir/page1.pdf, c:/dir/page2.pdf etc. |

### Veja Também

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)