---
title: Aspose::Pdf::Forms::Signature::set_ShowProperties method
linktitle: set_ShowProperties
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Forms::Signature::set_ShowProperties method. Force to show/hide signature properties in C++.'
type: docs
weight: 2700
url: /cpp/aspose.pdf.forms/signature/set_showproperties/
---
## Signature::set_ShowProperties method


Force to show/hide signature properties.

```cpp
void Aspose::Pdf::Forms::Signature::set_ShowProperties(bool value)
```

## Remarks


## In case ShowProperties is true signature field has predefined format of appearance (strings to represent): 



Digitally signed by {certificate subject} Date: {signature.Date} Reason: {signature.Reason} ## Location: {signature.Location} 



where {X} is placeholder for X value. Also signature can have image, in this case listed strings are placed over image. ShowProperties is true by default. 
## See Also

* Class [Signature](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
