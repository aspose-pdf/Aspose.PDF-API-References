---
title: "Método Aspose::Pdf::Forms::Form::HasField"
linktitle: "HasField"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método Aspose::Pdf::Forms::Form::HasField. Verifica si el formulario ya tiene el campo especificado en C++."
type: docs
weight: 2600
url: /es/cpp/aspose.pdf.forms/form/hasfield/
---
## Form::HasField(const System::SharedPtr\<Field\>\&) method


Comprueba si el formulario ya tiene el campo especificado.

```cpp
bool Aspose::Pdf::Forms::Form::HasField(const System::SharedPtr<Field> &field)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| field | const System::SharedPtr\<Field\>\& | [Field](../../field/) para verificar. |

### ReturnValue

**true** if the specified field name added to [Form](../); otherwise, **false**.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Field](../../field/)
* Class [Form](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## Form::HasField(const System::String\&) method


Determina si el campo con el nombre especificado ya se ha añadido al [Form](../).

```cpp
bool Aspose::Pdf::Forms::Form::HasField(const System::String &fieldName)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fieldName | const System::String\& | [Field::PartialName](../) o [Annotation::FullName](../) del campo. |

### ReturnValue

**true**
## Observaciones



si el nombre del campo especificado se añadió al [Form](../); de lo contrario, **false**

.
## Ver también

* Class [String](../../../system/string/)
* Class [Form](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## Form::HasField(const System::String\&, bool) method


Determina si el campo con el nombre especificado ya se ha añadido al [Form](../), con la capacidad de buscar en la jerarquía de campos hijos.

```cpp
bool Aspose::Pdf::Forms::Form::HasField(const System::String &fieldName, bool searchChildren)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fieldName | const System::String\& | [Field::PartialName](../) o [Annotation::FullName](../) del campo. |
|  | searchChildren | bool | Cuando se establece en **true** |

se buscará en toda la jerarquía de campos del formulario el *fieldName* solicitado (tenga en cuenta que en este caso el [Annotation::FullName](../) del campo requerido debe pasarse como *fieldName* ). |

### ReturnValue

**true**
## Observaciones



si el nombre del campo especificado se añadió al [Form](../); de lo contrario, **false**

.
## Ver también

* Class [String](../../../system/string/)
* Class [Form](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
