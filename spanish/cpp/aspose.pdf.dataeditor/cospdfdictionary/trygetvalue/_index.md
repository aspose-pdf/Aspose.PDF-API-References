---
title: "Aspose::Pdf::DataEditor::CosPdfDictionary::TryGetValue método"
linktitle: "TryGetValue"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::DataEditor::CosPdfDictionary::TryGetValue método. Para acceder a tipos de datos simples como string, name, bool, number. Devuelve null para otros tipos en C++."
type: docs
weight: 1700
url: /es/cpp/aspose.pdf.dataeditor/cospdfdictionary/trygetvalue/
---
## CosPdfDictionary::TryGetValue method


Para acceder a tipos de datos simples como string, name, bool, number. Devuelve null para otros tipos.

```cpp
bool Aspose::Pdf::DataEditor::CosPdfDictionary::TryGetValue(const System::String &key, System::SharedPtr<ICosPdfPrimitive> &value) const override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| clave | const System::String\& | Valor de la clave |
| value | System::SharedPtr\<ICosPdfPrimitive\>\& | devuelve [ICosPdfPrimitive](../../icospdfprimitive/) para la clave o null. |

### ReturnValue

Devuelve true si [ICosPdfPrimitive](../../icospdfprimitive/) es como string, name, bool, number. Devuelve false para todos los demás tipos.

## Ver también

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICosPdfPrimitive](../../icospdfprimitive/)
* Class [CosPdfDictionary](../)
* Namespace [Aspose::Pdf::DataEditor](../../)
* Library [Aspose.PDF for C++](../../../)
