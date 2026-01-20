---
title: Aspose::Pdf::Forms::Signature::get_ShowProperties method
linktitle: get_ShowProperties
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Forms::Signature::get_ShowProperties method. Force to show/hide signature properties in C++.'
type: docs
weight: 1300
url: /cpp/aspose.pdf.forms/signature/get_showproperties/
---
## Signature::get_ShowProperties method


Force to show/hide signature properties.

```cpp
bool Aspose::Pdf::Forms::Signature::get_ShowProperties() const
```

## Remarks


## In case ShowProperties is true signature field has predefined format of appearance (strings to represent): 



Digitally signed by {certificate subject} Date: {signature.Date} Reason: {signature.Reason} ## Location: {signature.Location} 



where {X} is placeholder for X value. Also signature can have image, in this case listed strings are placed over image. ShowProperties is true by default. 
## See Also

* Class [Signature](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
