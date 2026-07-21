---
title: "Aspose::Pdf::XImage::TrySetAlternativeText método"
linktitle: "TrySetAlternativeText"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::XImage::TrySetAlternativeText método. Establece texto alternativo para un XImage en la página en C++."
type: docs
weight: 1900
url: /es/cpp/aspose.pdf/ximage/trysetalternativetext/
---
## XImage::TrySetAlternativeText method


Establece texto alternativo para un [XImage](../) en la página.

```cpp
bool Aspose::Pdf::XImage::TrySetAlternativeText(const System::String &alternativeText, const System::SharedPtr<Aspose::Pdf::Page> &page)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| alternativeText | const System::String\& | El texto alternativo a especificar. |
| page | const System::SharedPtr\<Aspose::Pdf::Page\>\& | [Page](../../page/) donde se encuentra el [XImage](../). |

### ReturnValue

Verdadero si alternativeText para [XImage](../) está establecido. Falso si alternativeText para [XImage](../) no está establecido.
## Observaciones



El método devuelve false en los siguientes casos:* El [XImage](../) no se encuentra en la página especificada.
* The [XImage](../) appears multiple times on the page with different structural elements, making it ambiguous which instance should receive the alternative text.


## Ver también

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Page](../../page/)
* Class [XImage](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
