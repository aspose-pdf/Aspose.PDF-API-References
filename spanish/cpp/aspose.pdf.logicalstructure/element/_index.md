---
title: "Clase Aspose::Pdf::LogicalStructure::Element"
linktitle: "Elemento"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::LogicalStructure::Element. Representa una clase base para elementos en la estructura lógica en C++."
type: docs
weight: 1500
url: /es/cpp/aspose.pdf.logicalstructure/element/
---
## Element class


Representa una clase base para el elemento en la estructura lógica.

```cpp
class Element : public virtual System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [AppendChild](./appendchild/)(const System::SharedPtr\<Element\>\&, bool) | Agregar [T:/Aspose::Pdf::LogicalStructure::Element](../) a la colección de hijos. |
| [ClearChilds](./clearchilds/)() | Borrar todos los hijos. |
| [FindElements](./findelements/)(bool) | Buscar elementos de un tipo dado. |
| [get_ChildElements](./get_childelements/)() | Obtiene la colección de hijos de objetos [T:/Aspose::Pdf::LogicalStructure::Element](../). |
| [get_ParentElement](./get_parentelement/)() const | Obtener elemento padre. |
| [InsertChild](./insertchild/)(const System::SharedPtr\<Element\>\&, int32_t, bool) | Insertar [T:/Aspose::Pdf::LogicalStructure::Element](../) en la colección de hijos en el índice especificado. |
| [RemoveChild](./removechild/)(int32_t) | Eliminar hijo en. |
| virtual [Tag](./tag/)(System::SharedPtr\<Operators::BDC\>) | Vincular un elemento de estructura al operador BDC del flujo de contenido. |
| virtual [Tag](./tag/)(System::SharedPtr\<XForm\>) | Vincular un elemento de estructura al flujo de contenido [XForm](../../aspose.pdf/xform/). |
| virtual [Tag](./tag/)(System::SharedPtr\<XImage\>) | Vincular un elemento de estructura al [XImage](../../aspose.pdf/ximage/). |
| virtual [Tag](./tag/)(System::SharedPtr\<Artifact\>) | Vincular un elemento de estructura al [Artifact](../../aspose.pdf/artifact/). |
| virtual [Tag](./tag/)(System::SharedPtr\<Annotations::Annotation\>) | Vincular un elemento de estructura a la anotación. |
| [ToString](./tostring/)() const override | Devuelve una cadena que representa el objeto actual. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::LogicalStructure](../)
* Library [Aspose.PDF for C++](../../)
