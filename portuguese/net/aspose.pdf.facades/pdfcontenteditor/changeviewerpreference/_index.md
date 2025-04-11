---
title: PdfContentEditor.ChangeViewerPreference
second_title: Aspose.PDF for .NET API Reference
description: Método PdfContentEditor. Altera a preferência de visualização
type: docs
weight: 90
url: /pt/net/aspose.pdf.facades/pdfcontenteditor/changeviewerpreference/
---
## Método PdfContentEditor.ChangeViewerPreference

Altera a preferência de visualização.

```csharp
public void ChangeViewerPreference(int viewerAttribution)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| viewerAttribution | Int32 | A atribuição de visualização definida na classe ViewerPreference. |

## Exemplos

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.ChangeViewerPreference(ViewerPreference.HideMenubar);
editor.ChangeViewerPreference(ViewerPreference.PageModeUseNone);
editor.Save("example_out.pdf");
```

### Veja Também

* classe [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)