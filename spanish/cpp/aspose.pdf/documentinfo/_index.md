---
title: "Clase Aspose::Pdf::DocumentInfo"
linktitle: "DocumentInfo"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::DocumentInfo. Representa la información meta de un documento PDF en C++."
type: docs
weight: 4200
url: /es/cpp/aspose.pdf/documentinfo/
---
## DocumentInfo class


Representa la información meta de un documento PDF.

```cpp
class DocumentInfo : public System::Collections::Generic::Dictionary<System::String, System::String>
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Add](./add/)(const System::String\&, const System::String\&) override | Agrega un elemento con la clave y el valor especificados a la colección. |
| [Clear](./clear/)() override | Borra la información del documento. |
| [ClearCustomData](./clearcustomdata/)() | Borra solo los datos personalizados, dejando todos los demás valores predefinidos (Title, Author, etc.). |
| [DocumentInfo](./documentinfo/)(const System::SharedPtr\<Document\>\&) | Inicializa la instancia de [DocumentInfo](./). |
| [get_Author](./get_author/)() | Obtiene el autor del documento. |
| [get_CreationDate](./get_creationdate/)() | Obtiene la fecha de creación del documento. |
| [get_CreationTimeZone](./get_creationtimezone/)() | Zona horaria de la fecha de creación. |
| [get_Creator](./get_creator/)() | Obtiene el creador del documento. |
| [get_Keywords](./get_keywords/)() | Obtiene o establece las palabras clave del documento. |
| [get_ModDate](./get_moddate/)() | Obtiene la fecha de modificación del documento. |
| [get_ModTimeZone](./get_modtimezone/)() | Zona horaria de la fecha de modificación. |
| [get_Producer](./get_producer/)() | Obtiene el productor del documento. |
| [get_Subject](./get_subject/)() | Obtiene el asunto del documento. |
| [get_Title](./get_title/)() | Obtiene el título del documento. |
| [get_Trapped](./get_trapped/)() | Obtiene la bandera trapped. |
| [idx_get](./idx_get/)(const System::String\&) const override | Obtiene el valor asociado con la clave especificada. |
| [idx_set](./idx_set/)(const System::String\&, System::String) override | Establece el valor asociado con la clave especificada. |
| static [IsPredefinedKey](./ispredefinedkey/)(const System::String\&) | Determina si la clave está predefinida (Title, Author, etc.), no es personalizada. |
| [Remove](./remove/)(const System::String\&) override | Elimina el elemento con la clave especificada de la colección. |
| [set_Author](./set_author/)(const System::String\&) | Establece el autor del documento. |
| [set_CreationDate](./set_creationdate/)(System::DateTime) | Establece la fecha de creación del documento. |
| [set_CreationTimeZone](./set_creationtimezone/)(System::TimeSpan) | Zona horaria de la fecha de creación. |
| [set_Creator](./set_creator/)(const System::String\&) | Establece el creador del documento. |
| [set_Keywords](./set_keywords/)(const System::String\&) | Obtiene o establece las palabras clave del documento. |
| [set_ModDate](./set_moddate/)(System::DateTime) | Establece la fecha de modificación del documento. |
| [set_ModTimeZone](./set_modtimezone/)(System::TimeSpan) | Zona horaria de la fecha de modificación. |
| [set_Producer](./set_producer/)(const System::String\&) | Establece el productor del documento. |
| [set_Subject](./set_subject/)(const System::String\&) | Establece el asunto del documento. |
| [set_Title](./set_title/)(const System::String\&) | Establece el título del documento. |
| [set_Trapped](./set_trapped/)(const System::String\&) | Establece la bandera de atrapado. |
| [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) override | Establece el n‑ésimo argumento de plantilla como un puntero débil (en lugar de compartido). Permite cambiar los punteros en contenedores al modo débil. |
## Ver también

* Class [Dictionary](../../system.collections.generic/dictionary/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
