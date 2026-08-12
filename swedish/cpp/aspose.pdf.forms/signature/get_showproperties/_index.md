---
title: "Aspose::Pdf::Forms::Signature::get_ShowProperties metod"
linktitle: "get_ShowProperties"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Forms::Signature::get_ShowProperties metod. Tvingar att visa/dölja signaturens egenskaper i C++."
type: docs
weight: 1300
url: /sv/cpp/aspose.pdf.forms/signature/get_showproperties/
---
## Signature::get_ShowProperties method


Tvinga att visa/dölja signaturegenskaper.

```cpp
bool Aspose::Pdf::Forms::Signature::get_ShowProperties() const
```

## Anmärkningar


## In case ShowProperties is true signature field has predefined format of appearance (strings to represent): 



Digitalt signerat av {certificate subject} Datum: {signature.Date} Orsak: {signature.Reason} ## Plats: {signature.Location}



där {X} är platshållare för X-värdet. Signaturen kan också ha en bild, i så fall placeras de listade strängarna över bilden. ShowProperties är true som standard.
## Se även

* Class [Signature](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
