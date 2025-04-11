---
title: PdfPageEditor.GetPageBoxSize
second_title: Aspose.PDF for .NET API Reference
description: Método PdfPageEditor. Retorna o tamanho da caixa especificada no documento
type: docs
weight: 130
url: /pt/net/aspose.pdf.facades/pdfpageeditor/getpageboxsize/
---
## Método PdfPageEditor.GetPageBoxSize

Retorna o tamanho da caixa especificada no documento.

```csharp
public Rectangle GetPageBoxSize(int page, string pageBoxName)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| page | Int32 | Índice da página. As páginas do documento são numeradas a partir de 1. |
| pageBoxName | String | Nome do tipo de caixa. Os valores válidos são: "art", "bleed", "crop", "media", "trim". |

### Valor de Retorno

Retângulo que contém a caixa solicitada.

## Exemplos

O exemplo a seguir demonstra como obter a caixa de mídia da 1ª página:

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
System.Drawing.Rectangle rect = editor.GetBoxSize(1, "media");
```

### Veja Também

* classe [PdfPageEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)