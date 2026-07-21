---
title: "Aspose::Pdf::Annotations::AppearanceDictionary::idx_get método"
linktitle: "idx_get"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Annotations::AppearanceDictionary::idx_get método. Representa una forma conveniente de obtener flujos de apariencia en C++."
type: docs
weight: 1400
url: /es/cpp/aspose.pdf.annotations/appearancedictionary/idx_get/
---
## AppearanceDictionary::idx_get method


Representa una forma conveniente de obtener flujos de apariencia.

```cpp
System::SharedPtr<XForm> Aspose::Pdf::Annotations::AppearanceDictionary::idx_get(const System::String &key) const override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| key | const System::String\& | Representa la ruta al flujo de apariencia. Si el diccionario de apariencia tiene subdiccionarios, entonces la ruta debe contener 2 partes ([Keys](../)), de lo contrario la ruta tiene solo una parte. |

### ReturnValue

[XForm](../../../aspose.pdf/xform/) object (appearance stream) which corresponds to the given key.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XForm](../../../aspose.pdf/xform/)
* Class [String](../../../system/string/)
* Class [AppearanceDictionary](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
