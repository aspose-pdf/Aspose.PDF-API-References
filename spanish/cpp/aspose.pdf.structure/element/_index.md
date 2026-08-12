---
title: "Aspose::Pdf::Structure::Element class"
linktitle: "Elemento"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Structure::Element class. Clase que representa el elemento base de la estructura lógica en C++."
type: docs
weight: 100
url: /es/cpp/aspose.pdf.structure/element/
---
## Element class


Clase que representa el elemento base de la estructura lógica.

```cpp
class Element : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [get_ActualText](./get_actualtext/)() | (Opcional; PDF 1.4) [Text](../../aspose.pdf.text/) que es un reemplazo exacto del elemento de estructura y sus hijos. Este texto de reemplazo (que debe aplicarse a la menor cantidad posible de contenido) es útil al extraer el contenido del documento en apoyo a la accesibilidad de usuarios con discapacidades o para otros propósitos. |
| virtual [get_Alt](./get_alt/)() | (Opcional) Una descripción alternativa del elemento de estructura y sus hijos en forma legible por humanos, que es útil al extraer el contenido del documento en apoyo a la accesibilidad de usuarios con discapacidades o para otros propósitos. |
| [get_Children](./get_children/)() | Obtiene la colección de elementos hijos. |
| virtual [get_E](./get_e/)() | (Opcional; PDF 1.5) La forma expandida de una abreviatura. |
| virtual [get_Lang](./get_lang/)() | (Opcional; PDF 1.4) Un idioma que especifica la lengua natural para todo el texto en el elemento de estructura, excepto donde sea sobrescrito por especificaciones de idioma para elementos de estructura anidados o contenido marcado. |
| [Remove](./remove/)() | Eliminar elemento. |
| virtual [set_ActualText](./set_actualtext/)(System::String) | (Opcional; PDF 1.4) [Text](../../aspose.pdf.text/) que es un reemplazo exacto del elemento de estructura y sus hijos. Este texto de reemplazo (que debe aplicarse a la menor cantidad posible de contenido) es útil al extraer el contenido del documento en apoyo a la accesibilidad de usuarios con discapacidades o para otros propósitos. |
| virtual [set_Alt](./set_alt/)(System::String) | (Opcional) Una descripción alternativa del elemento de estructura y sus hijos en forma legible por humanos, que es útil al extraer el contenido del documento en apoyo a la accesibilidad de usuarios con discapacidades o para otros propósitos. |
| virtual [set_E](./set_e/)(System::String) | (Opcional; PDF 1.5) La forma expandida de una abreviatura. |
| virtual [set_Lang](./set_lang/)(System::String) | (Opcional; PDF 1.4) Un idioma que especifica la lengua natural para todo el texto en el elemento de estructura, excepto donde sea sobrescrito por especificaciones de idioma para elementos de estructura anidados o contenido marcado. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Structure](../)
* Library [Aspose.PDF for C++](../../)
