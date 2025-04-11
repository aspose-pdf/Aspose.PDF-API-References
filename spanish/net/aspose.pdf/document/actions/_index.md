---
title: Document.Actions
second_title: Aspose.PDF for .NET API Reference
description: Propiedad del documento. Obtiene acciones del documento. Esta propiedad es una instancia de la clase DocumentActions que permite obtener/establecer acciones BeforClosing, BeforSaving, etc.
type: docs
weight: 30
url: /es/net/aspose.pdf/document/actions/
---
## Propiedad Document.Actions

Obtiene acciones del documento. Esta propiedad es una instancia de la clase DocumentActions que permite obtener/establecer acciones BeforClosing, BeforSaving, etc.

```csharp
public DocumentActionCollection Actions { get; }
```

## Ejemplos

Este ejemplo demuestra cómo obtener la acción después de abrir el documento:

```csharp
Aspose.Pdf.Document document = new Aspose.Pdf.Document("d:\\work\\aspose\\aspose.pdf.kit.net.new\\trunk\\testdata\\Aspose.Pdf\\PdfWithOpenAction.pdf");
Aspose.Pdf.Annotations.DocumentActionCollection actions = document.Actions;
Aspose.Pdf.Annotations.PdfAction afterSavingAction = actions.AfterSaving;
```

### Ver También

* clase [DocumentActionCollection](../../../aspose.pdf.annotations/documentactioncollection/)
* clase [Document](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../../)