---
title: "Clase Aspose::Pdf::ExportFieldsOptions"
linktitle: "ExportFieldsOptions"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::ExportFieldsOptions. Representa la clase base de opciones para exportar campos de formulario en C++."
type: docs
weight: 4800
url: /es/cpp/aspose.pdf/exportfieldsoptions/
---
## ExportFieldsOptions class


Representa la clase base de opciones para exportar campos de formulario.

```cpp
class ExportFieldsOptions : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [ExportFieldsOptions](./exportfieldsoptions/)() |  |
| [get_ExportPasswordValue](./get_exportpasswordvalue/)() const | Obtiene un valor que indica si el valor de la contraseña debe exportarse. |
| [get_FieldSelector](./get_fieldselector/)() const | Obtiene un delegado que determina si un campo particular debe exportarse. Si el delegado es **null**, todos los campos se exportan (el comportamiento predeterminado). |
| [set_ExportPasswordValue](./set_exportpasswordvalue/)(bool) | Establece un valor que indica si el valor de la contraseña debe exportarse. |
| [set_FieldSelector](./set_fieldselector/)(System::Predicate\<System::SharedPtr\<Forms::Field\>\>) | Establece un delegado que determina si un campo particular debe exportarse. Si el delegado es **null**, todos los campos se exportan (el comportamiento predeterminado). |
## Ver también

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
