---
title: "Aspose::Pdf::Forms::Signature::set_ShowProperties método"
linktitle: "set_ShowProperties"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Forms::Signature::set_ShowProperties método. Fuerza a mostrar/ocultar las propiedades de la firma en C++."
type: docs
weight: 2700
url: /es/cpp/aspose.pdf.forms/signature/set_showproperties/
---
## Signature::set_ShowProperties method


Forzar mostrar/ocultar las propiedades de la firma.

```cpp
void Aspose::Pdf::Forms::Signature::set_ShowProperties(bool value)
```

## Observaciones


## In case ShowProperties is true signature field has predefined format of appearance (strings to represent): 



Firmado digitalmente por {certificate subject} Fecha: {signature.Date} Motivo: {signature.Reason} ## Ubicación: {signature.Location}



donde {X} es un marcador de posición para el valor X. Además, la firma puede tener una imagen; en este caso, las cadenas enumeradas se colocan sobre la imagen. ShowProperties es verdadero por defecto.
## Ver también

* Class [Signature](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
