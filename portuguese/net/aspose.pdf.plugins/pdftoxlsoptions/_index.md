---
title: Class PdfToXlsOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Plugins.PdfToXlsOptions. Representa opções de conversão de PDF para XLSX para o plugin XlsConverter
type: docs
weight: 9150
url: /pt/net/aspose.pdf.plugins/pdftoxlsoptions/
---
## Classe PdfToXlsOptions

Representa opções de conversão de PDF para XLSX para o plugin [`XlsConverter`](../xlsconverter/).

```csharp
public sealed class PdfToXlsOptions : PdfConverterOptions
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [PdfToXlsOptions](pdftoxlsoptions/)() | O construtor padrão. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [Format](../../aspose.pdf.plugins/pdftoxlsoptions/format/) { get; set; } | Formato de saída. |
| [Inputs](../../aspose.pdf.plugins/pdfconverteroptions/inputs/) { get; } | Retorna a coleção de dados do plugin PdfConverterOptions. |
| [InsertBlankColumnAtFirst](../../aspose.pdf.plugins/pdftoxlsoptions/insertblankcolumnatfirst/) { get; set; } | Defina como verdadeiro se precisar inserir uma coluna em branco como a primeira coluna da planilha. O valor padrão é falso; isso significa que a coluna em branco não será inserida. |
| [MinimizeTheNumberOfWorksheets](../../aspose.pdf.plugins/pdftoxlsoptions/minimizethenumberofworksheets/) { get; set; } | Defina como verdadeiro se precisar minimizar o número de planilhas no livro de trabalho resultante. O valor padrão é falso; isso significa salvar cada página PDF como uma planilha separada. |
| override [OperationName](../../aspose.pdf.plugins/pdftoxlsoptions/operationname/) { get; } | Obtém o nome da operação. |
| [Outputs](../../aspose.pdf.plugins/pdfconverteroptions/outputs/) { get; } | Obtém a coleção de alvos adicionados para salvar os resultados da operação. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdfconverteroptions/addinput/)(IDataSource) | Adiciona nova fonte de dados à coleção de dados do plugin PdfConverter. |
| [AddOutput](../../aspose.pdf.plugins/pdfconverteroptions/addoutput/)(IDataSource) | Adiciona nova fonte de dados à coleção de dados do plugin PdfToXLSXConverterOptions. |

## Outros Membros

| Nome | Descrição |
| --- | --- |
| enum [ExcelFormat](../../aspose.pdf.plugins/pdftoxlsoptions.excelformat) | Permite especificar o formato de arquivo .xlsx, .xls/xml ou csv. O valor padrão é XLSX. |

### Veja Também

* classe [PdfConverterOptions](../pdfconverteroptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)