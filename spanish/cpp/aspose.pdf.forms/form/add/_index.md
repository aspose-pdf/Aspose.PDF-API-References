---
title: "Método Aspose::Pdf::Forms::Form::Add"
linktitle: "Add"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método Aspose::Pdf::Forms::Form::Add. Añade un campo al formulario en C++."
type: docs
weight: 100
url: /es/cpp/aspose.pdf.forms/form/add/
---
## Form::Add(const System::SharedPtr\<Field\>\&) method


Añade un campo al formulario.

```cpp
void Aspose::Pdf::Forms::Form::Add(const System::SharedPtr<Field> &field)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| field | const System::SharedPtr\<Field\>\& | [Field](../../field/) que debe añadirse. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Field](../../field/)
* Class [Form](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## Form::Add(const System::SharedPtr\<Field\>\&, int32_t) method


Añade un campo al formulario.

```cpp
void Aspose::Pdf::Forms::Form::Add(const System::SharedPtr<Field> &field, int32_t pageNumber)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| field | const System::SharedPtr\<Field\>\& | [Field](../../field/) que debe añadirse. |
| pageNumber | int32_t | [Page](../../../aspose.pdf/page/) índice donde se colocará el campo añadido. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Field](../../field/)
* Class [Form](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## Form::Add(System::SharedPtr\<Field\>, const System::String\&, int32_t) method


Añade un nuevo campo al formulario; si este campo ya está colocado en otro formulario o en este, se crea una copia del campo.

```cpp
System::SharedPtr<Field> Aspose::Pdf::Forms::Form::Add(System::SharedPtr<Field> field, const System::String &partialName, int32_t pageNumber)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| field | System::SharedPtr\<Field\> | [Field](../../field/) nombre. |
| partialName | const System::String\& | Nombre del campo en el formulario. |
| pageNumber | int32_t | [Page](../../../aspose.pdf/page/) número donde se añadirá el campo. |

### ReturnValue

Campo añadido devuelto. Si se creó una copia del campo, será devuelta.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Field](../../field/)
* Class [String](../../../system/string/)
* Class [Form](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
