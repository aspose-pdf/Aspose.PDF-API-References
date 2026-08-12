---
title: "Aspose::Pdf::Annotations::AppearanceDictionary::idx_set método"
linktitle: "idx_set"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Annotations::AppearanceDictionary::idx_set método. Representa una forma conveniente de obtener flujos de apariencia en C++."
type: docs
weight: 1500
url: /es/cpp/aspose.pdf.annotations/appearancedictionary/idx_set/
---
## AppearanceDictionary::idx_set method


Representa una forma conveniente de obtener flujos de apariencia.

```cpp
void Aspose::Pdf::Annotations::AppearanceDictionary::idx_set(const System::String &key, System::SharedPtr<XForm> value) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| key | const System::String\& | Representa la ruta al flujo de apariencia. Si el diccionario de apariencia tiene subdiccionarios, entonces la ruta debe contener 2 partes ([Keys](../)), de lo contrario la ruta tiene solo una parte. |

### ReturnValue

[XForm](../../../aspose.pdf/xform/) object (appearance stream) which corresponds to the given key.

## Ver también

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XForm](../../../aspose.pdf/xform/)
* Class [AppearanceDictionary](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
