---
title: "Aspose::Pdf::Text::FontSubstitutionCollection class"
linktitle: "FontSubstitutionCollection"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Text::FontSubstitutionCollection class. Representa la colección de estrategias de sustitución de fuentes en C++."
type: docs
weight: 1600
url: /es/cpp/aspose.pdf.text/fontsubstitutioncollection/
---
## FontSubstitutionCollection class


Representa la colección de estrategias de sustitución de fuentes.

```cpp
class FontSubstitutionCollection : public System::Collections::Generic::ICollection<System::SharedPtr<FontSubstitution>>
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Add](./add/)(const System::SharedPtr\<FontSubstitution\>\&) override | Agrega un nuevo objeto de sustitución de fuentes a la colección. |
| [Clear](./clear/)() override | Limpia la colección de sustitución de fuentes. |
| [Contains](./contains/)(const System::SharedPtr\<FontSubstitution\>\&) const override | Determina si un elemento está en la colección. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::SharedPtr\<FontSubstitution\>\>, int32_t) override | Copia toda la colección a una Matriz unidimensional compatible, comenzando en el índice especificado de la matriz de destino. |
| [get_Count](./get_count/)() const override | Obtiene el número de elementos de objeto [Font](../font/) realmente contenidos en la colección. |
| [get_IsSynchronized](./get_issynchronized/)() | Obtiene un valor que indica si el acceso a la colección está sincronizado (seguro para subprocesos). |
| [get_SyncRoot](./get_syncroot/)() const | Obtiene un objeto que puede usarse para sincronizar el acceso a la colección. |
| [GetEnumerator](./getenumerator/)() override | Devuelve un enumerador para toda la colección. |
| [idx_get](./idx_get/)(int32_t) | Obtiene el elemento de fuente en el índice especificado. |
| [Remove](./remove/)(const System::SharedPtr\<FontSubstitution\>\&) override | Elimina el elemento de sustitución de fuentes. |
## Ver también

* Class [ICollection](../../system.collections.generic/icollection/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
