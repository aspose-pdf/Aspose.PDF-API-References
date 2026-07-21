---
title: "Aspose::Pdf::BaseParagraph clase"
linktitle: "BaseParagraph"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::BaseParagraph class. Representa un objeto base abstracto que puede añadirse a la página (doc.Paragraphs.Add()) en C++."
type: docs
weight: 1000
url: /es/cpp/aspose.pdf/baseparagraph/
---
## BaseParagraph class


Representa un objeto base abstracto que puede añadirse a la página (doc.Paragraphs.Add()).

```cpp
class BaseParagraph : public System::ICloneable
```

## Métodos

| Método | Descripción |
| --- | --- |
| [BaseParagraph](./baseparagraph/)() |  |
| [Clone](./clone/)() override | Clona esta instancia. Método virtual. Siempre devuelve null. |
| virtual [get_HorizontalAlignment](./get_horizontalalignment/)() | Obtiene la alineación horizontal del párrafo. |
| virtual [get_Hyperlink](./get_hyperlink/)() | Obtiene el hipervínculo del fragmento (para generador de pdf). |
| [get_IsFirstParagraphInColumn](./get_isfirstparagraphincolumn/)() const | Obtiene un valor booleano que indica si este párrafo estará en la siguiente columna. El valor predeterminado es false. (para generación de pdf) |
| [get_IsInLineParagraph](./get_isinlineparagraph/)() const | Obtiene si un párrafo está en línea. El valor predeterminado es false. (para generación de pdf) |
| [get_IsInNewPage](./get_isinnewpage/)() const | Obtiene un valor booleano que fuerza que este párrafo se genere en una nueva página. El valor predeterminado es false. (para generación de pdf) |
| [get_IsKeptWithNext](./get_iskeptwithnext/)() const | Obtiene un valor booleano que indica si el párrafo actual permanece en la misma página junto con el siguiente párrafo. El valor predeterminado es false. (para generación de pdf) |
| [get_Margin](./get_margin/)() | Obtiene un margen externo para el párrafo (para generación de pdf) |
| virtual [get_VerticalAlignment](./get_verticalalignment/)() | Obtiene la alineación vertical del párrafo. |
| [get_ZIndex](./get_zindex/)() const | Obtiene un valor entero que indica el orden Z del gráfico. Un gráfico con ZIndex mayor se colocará sobre el gráfico con ZIndex menor. ZIndex puede ser negativo. Un gráfico con ZIndex negativo se colocará detrás del texto en la página. |
| virtual [set_HorizontalAlignment](./set_horizontalalignment/)(Aspose::Pdf::HorizontalAlignment) | Establece la alineación horizontal del párrafo. |
| virtual [set_Hyperlink](./set_hyperlink/)(System::SharedPtr\<Aspose::Pdf::Hyperlink\>) | Establece el hipervínculo del fragmento (para generador de pdf). |
| [set_IsFirstParagraphInColumn](./set_isfirstparagraphincolumn/)(bool) | Establece un valor booleano que indica si este párrafo estará en la siguiente columna. El valor predeterminado es false. (para generación de pdf) |
| [set_IsInLineParagraph](./set_isinlineparagraph/)(bool) | Establece si un párrafo está en línea. El valor predeterminado es false. (para generación de pdf) |
| [set_IsInNewPage](./set_isinnewpage/)(bool) | Establece un valor booleano que fuerza que este párrafo se genere en una nueva página. El valor predeterminado es false. (para generación de pdf) |
| [set_IsKeptWithNext](./set_iskeptwithnext/)(bool) | Establece un valor booleano que indica si el párrafo actual permanece en la misma página junto con el siguiente párrafo. El valor predeterminado es false. (para generación de pdf) |
| [set_Margin](./set_margin/)(const System::SharedPtr\<MarginInfo\>\&) | Establece un margen externo para el párrafo (para generación de pdf) |
| virtual [set_VerticalAlignment](./set_verticalalignment/)(Aspose::Pdf::VerticalAlignment) | Establece una alineación vertical del párrafo. |
| [set_ZIndex](./set_zindex/)(int32_t) | Establece un valor entero que indica el orden Z del gráfico. Un gráfico con ZIndex mayor se colocará sobre el gráfico con ZIndex menor. ZIndex puede ser negativo. Un gráfico con ZIndex negativo se colocará detrás del texto en la página. |
## Ver también

* Class [ICloneable](../../system/icloneable/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
