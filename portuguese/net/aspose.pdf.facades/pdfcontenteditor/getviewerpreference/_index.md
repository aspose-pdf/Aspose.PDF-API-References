---
title: PdfContentEditor.GetViewerPreference
second_title: Aspose.PDF for .NET API Reference
description: Método PdfContentEditor. Retorna a preferência de visualização
type: docs
weight: 390
url: /pt/net/aspose.pdf.facades/pdfcontenteditor/getviewerpreference/
---
## Método PdfContentEditor.GetViewerPreference

Retorna a preferência de visualização.

```csharp
public int GetViewerPreference()
```

### Valor de Retorno

Retorna um conjunto de flags de ViewerPreference

## Exemplos

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
int prefValue = editor.GetViewerPreference();
if ((prefValue & ViewerPreference.PageModeUseOutline) != 0)
{ // ... }
```

### Veja Também

* classe [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)