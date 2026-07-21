---
title: "Aspose::Pdf::Operators::ShowText class"
linktitle: "ShowText"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Operators::ShowText class. Clase que representa el operador Tj (mostrar texto) en C++."
type: docs
weight: 7700
url: /es/cpp/aspose.pdf.operators/showtext/
---
## ShowText class


Clase que representa el operador Tj (mostrar texto).

```cpp
class ShowText : public Aspose::Pdf::Operators::TextShowOperator
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Accept](./accept/)(const System::SharedPtr\<IOperatorSelector\>\&) override | Acepta un objeto visitante para procesar el operador. |
| [get_Text](./get_text/)() override | [Text](../../aspose.pdf.text/) del operador. |
| [set_Text](./set_text/)(System::String) override | [Text](../../aspose.pdf.text/) del operador. |
| [ShowText](./showtext/)(int32_t, const System::String\&) | Inicializa el operador Tj. |
| [ShowText](./showtext/)(const System::String\&) | Inicializa el operador Tj. |
| [ShowText](./showtext/)(const System::String\&, const System::SharedPtr\<Text::Font\>\&) | Inicializa el operador Tj. |
| [ShowText](./showtext/)() | Inicializa el operador Tj. |
| [ToString](./tostring/)() const override | Produce el código de texto del operador. |
## Ver también

* Class [TextShowOperator](../textshowoperator/)
* Namespace [Aspose::Pdf::Operators](../)
* Library [Aspose.PDF for C++](../../)
