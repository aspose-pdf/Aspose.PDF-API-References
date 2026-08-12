---
title: "Aspose::Pdf::Forms::Signature::get_ShowProperties método"
linktitle: "get_ShowProperties"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Forms::Signature::get_ShowProperties método. Obliga a mostrar/ocultar las propiedades de la firma en C++."
type: docs
weight: 1300
url: /es/cpp/aspose.pdf.forms/signature/get_showproperties/
---
## Signature::get_ShowProperties method


Forzar mostrar/ocultar las propiedades de la firma.

```cpp
bool Aspose::Pdf::Forms::Signature::get_ShowProperties() const
```

## Observaciones


## In case ShowProperties is true signature field has predefined format of appearance (strings to represent): 



Firmado digitalmente por {certificate subject} Fecha: {signature.Date} Motivo: {signature.Reason} ## Ubicación: {signature.Location}



donde {X} es un marcador de posición para el valor X. Además, la firma puede tener una imagen; en este caso, las cadenas enumeradas se colocan sobre la imagen. ShowProperties es verdadero por defecto.
## Ver también

* Class [Signature](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
