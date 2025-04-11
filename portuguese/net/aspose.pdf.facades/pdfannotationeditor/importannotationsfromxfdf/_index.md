---
title: PdfAnnotationEditor.ImportAnnotationsFromXfdf
second_title: Aspose.PDF for .NET API Reference
description: Método PdfAnnotationEditor. Importa todas as anotações do arquivo XFDF
type: docs
weight: 110
url: /pt/net/aspose.pdf.facades/pdfannotationeditor/importannotationsfromxfdf/
---
## ImportAnnotationsFromXfdf(string) {#importannotationsfromxfdf_1}

Importa todas as anotações do arquivo XFDF.

```csharp
public void ImportAnnotationsFromXfdf(string xfdfFile)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| xfdfFile | String | O arquivo XFDF de entrada. |

## Exemplos

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.ImportAnnotationsFromXfdf("annots.xfdf");
editor.Save("example_out.pdf");
```

### Veja Também

* classe [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ImportAnnotationsFromXfdf(Stream) {#importannotationsfromxfdf}

Importa todas as anotações do fluxo de dados XFDF.

```csharp
public void ImportAnnotationsFromXfdf(Stream xfdfStream)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| xfdfStream | Stream | O fluxo de dados XFDF de entrada. |

## Exemplos

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.ImportAnnotationsFromXfdf(File.OpenRead("annots.xfdf"));
editor.Save("example_out.pdf");
```

### Veja Também

* classe [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)