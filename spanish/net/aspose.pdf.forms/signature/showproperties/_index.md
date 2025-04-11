---
title: Signature.ShowProperties
second_title: Aspose.PDF for .NET API Reference
description: Propiedad de firma. Fuerza a mostrar/ocultar propiedades de la firma. En caso de que ShowProperties sea verdadero, el campo de firma tiene un formato predefinido de cadenas de apariencia para representar Digitally signed by certificate subject Date signature.Date Reason signature.Reason Location signature.Location donde X es un marcador de posición para el valor X. Además, la firma puede tener una imagen, en este caso las cadenas listadas se colocan sobre la imagen. ShowProperties es verdadero por defecto.
type: docs
weight: 130
url: /es/net/aspose.pdf.forms/signature/showproperties/
---
## Propiedad Signature.ShowProperties

Fuerza a mostrar/ocultar propiedades de la firma. En caso de que ShowProperties sea verdadero, el campo de firma tiene un formato predefinido de apariencia (cadenas para representar): ------------------------------------------- Digitally signed by {certificate subject} Date: {signature.Date} Reason: {signature.Reason} Location: {signature.Location} ------------------------------------------- donde {X} es un marcador de posición para el valor X. Además, la firma puede tener una imagen, en este caso las cadenas listadas se colocan sobre la imagen. ShowProperties es verdadero por defecto.

```csharp
public bool ShowProperties { get; set; }
```

### Ver También

* clase [Signature](../)
* espacio de nombres [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* ensamblaje [Aspose.PDF](../../../)