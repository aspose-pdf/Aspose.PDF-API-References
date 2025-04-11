---
title: PdfPageEditor.GetPageRotation
second_title: Aspose.PDF for .NET API Reference
description: Método PdfPageEditor. Retorna a rotação da página especificada
type: docs
weight: 140
url: /pt/net/aspose.pdf.facades/pdfpageeditor/getpagerotation/
---
## Método PdfPageEditor.GetPageRotation

Retorna a rotação da página especificada.

```csharp
public int GetPageRotation(int page)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| page | Int32 | Índice da página. As páginas do documento são numeradas a partir de 1. |

### Valor de Retorno

Rotação da página em graus.

## Exemplos

O exemplo a seguir demonstra como obter a rotação da página:

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
int rotation = editor.GetPageSize(1);
Console.WriteLine("Rotation of 1st page : " + rotation + " degrees");        
```

### Veja Também

* classe [PdfPageEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)