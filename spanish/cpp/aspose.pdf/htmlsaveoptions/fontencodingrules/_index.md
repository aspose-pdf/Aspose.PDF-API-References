---
title: "Aspose::Pdf::HtmlSaveOptions::FontEncodingRules enum"
linktitle: "FontEncodingRules"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Enum Aspose::Pdf::HtmlSaveOptions::FontEncodingRules. Esta enumeración define reglas que afinan la lógica de codificación en C++."
type: docs
weight: 5200
url: /es/cpp/aspose.pdf/htmlsaveoptions/fontencodingrules/
---
## FontEncodingRules enum


Esta enumeración define reglas que afinan la lógica de codificación.

```cpp
enum class FontEncodingRules : uint8_t
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Predeterminado | 0 | Dejar la lógica de codificación \"tal cual\" - de acuerdo con la especificación PDF. |
| DecreaseToUnicodePriorityLevel | 1 | ToUnicode es un mecanismo especial que ayuda a decodificar códigos de entrada a símbolos Unicode. Según la especificación, debe ser el primer mecanismo utilizado para obtener símbolos Unicode para un código de entrada específico. Pero algunos documentos tienen fuentes no estándar y, para convertir estos documentos correctamente, puede ser necesario disminuir la prioridad de ToUnicode y usar otros mecanismos para decodificar los códigos de entrada. |

## Ver también

* Class [HtmlSaveOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
