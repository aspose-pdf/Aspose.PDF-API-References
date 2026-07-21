---
title: "Aspose::Pdf::HtmlFragment class"
linktitle: "HtmlFragment"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::HtmlFragment class. Representa un fragmento html en C++."
type: docs
weight: 7100
url: /es/cpp/aspose.pdf/htmlfragment/
---
## HtmlFragment class


Representa un fragmento HTML.

```cpp
class HtmlFragment : public Aspose::Pdf::FormattedFragment
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Clone](./clone/)() override | Clona el fragmento html. |
| [get_HtmlLoadOptions](./get_htmlloadoptions/)() const | Obtiene [HtmlLoadOptions](../htmlloadoptions/) que se utilizarán para cargar (y renderizar) HTML en esta instancia de la clase. Por favor, utilícelo cuando sea necesario usar una configuración específica para la importación de HTML para esta u otra instancia (p. ej. cuando esta u otra instancia deba usar una BasePath específica para el HTML importado o deba usar un cargador específico de recursos externos). Si el parámetro es predeterminado (null), se usarán las opciones estándar de carga de HTML. |
| [get_IsBreakWords](./get_isbreakwords/)() const | Obtiene la ruptura de palabras. |
| [get_IsParagraphHasMargin](./get_isparagraphhasmargin/)() const | Obtiene si el párrafo tiene margen predeterminado, de lo contrario el margen es 0. |
| [get_Rectangle](./get_rectangle/)() const | Obtiene el rectángulo del [HtmlFragment](./). |
| [get_TextState](./get_textstate/)() const | Obtiene la fuente. |
| [HtmlFragment](./htmlfragment/)(const System::String\&) | Inicializa una nueva instancia de la clase [HtmlFragment](./). |
| [set_HtmlLoadOptions](./set_htmlloadoptions/)(const System::SharedPtr\<Aspose::Pdf::HtmlLoadOptions\>\&) | Establece [HtmlLoadOptions](../htmlloadoptions/) que se utilizarán para cargar (y renderizar) HTML en esta instancia de la clase. Por favor, utilícelo cuando sea necesario usar una configuración específica para la importación de HTML para esta u otra instancia (p. ej. cuando esta u otra instancia deba usar una BasePath específica para el HTML importado o deba usar un cargador específico de recursos externos). Si el parámetro es predeterminado (null), se usarán las opciones estándar de carga de HTML. |
| [set_IsBreakWords](./set_isbreakwords/)(bool) | Establece la ruptura de palabras. |
| [set_IsParagraphHasMargin](./set_isparagraphhasmargin/)(bool) | Establece si el párrafo tiene margen predeterminado; de lo contrario, el margen es 0. |
| [set_TextState](./set_textstate/)(const System::SharedPtr\<Aspose::Pdf::Text::TextState\>\&) | Establece la fuente. |
## Ver también

* Class [FormattedFragment](../formattedfragment/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
