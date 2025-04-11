---
title: PdfPageEditor.GetPageSize
second_title: Aspose.PDF for .NET API Reference
description: Método PdfPageEditor. Retorna o tamanho da página da página especificada
type: docs
weight: 160
url: /pt/net/aspose.pdf.facades/pdfpageeditor/getpagesize/
---
## Método PdfPageEditor.GetPageSize

Retorna o tamanho da página da página especificada.

```csharp
public PageSize GetPageSize(int page)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| page | Int32 | Índice da página. As páginas do documento são numeradas a partir de 1. |

### Valor de Retorno

O resultado é uma instância de PageSize. Use as propriedades Width e Height do objeto retornado para obter a largura e a altura da página.

## Exemplos

O exemplo a seguir demonstra o uso do método GetPageSize:

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
PageSize size = editor.GetPageSize(1);
Console.WriteLine("Size of 1st page : " + size.Width + " x " + size.Height);
```

### Veja Também

* classe [PageSize](../../../aspose.pdf/pagesize/)
* classe [PdfPageEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)