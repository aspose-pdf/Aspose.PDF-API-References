---
title: "Aspose::Pdf::ToUnicodeProcessingRules class"
linktitle: "ToUnicodeProcessingRules"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::ToUnicodeProcessingRules. Esta clase describe reglas que pueden usarse para resolver el error de Adobe Preflight \"Text cannot be mapped to Unicode\" en C++."
type: docs
weight: 18700
url: /es/cpp/aspose.pdf/tounicodeprocessingrules/
---
## ToUnicodeProcessingRules class


Esta clase describe reglas que pueden usarse para resolver el error de Adobe Preflight "Text cannot be mapped to Unicode".

```cpp
class ToUnicodeProcessingRules : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_MapNonLinkedSymbolsOnSpace](./get_mapnonlinkedsymbolsonspace/)() const | Algunas fuentes no proporcionan información sobre unicodes para algunos símbolos de texto. Esta falta de información genera un error "Text cannot be mapped to Unicode". Use esta bandera para mapear símbolos no vinculados al unicode "space" (código 32). |
| [get_RemoveSpacesFromCMapNames](./get_removespacesfromcmapnames/)() const | Algunas fuentes tienen mapas de códigos de caracteres ToUnicode con espacios en los nombres. Estos espacios podrían provocar errores con el mapeo de texto unicode. Esta bandera indica eliminar los espacios de los nombres de los mapas de códigos de caracteres ToUnicode. Por defecto es false. |
| [set_MapNonLinkedSymbolsOnSpace](./set_mapnonlinkedsymbolsonspace/)(bool) | Algunas fuentes no proporcionan información sobre unicodes para algunos símbolos de texto. Esta falta de información genera un error "Text cannot be mapped to Unicode". Use esta bandera para mapear símbolos no vinculados al unicode "space" (código 32). |
| [set_RemoveSpacesFromCMapNames](./set_removespacesfromcmapnames/)(bool) | Algunas fuentes tienen mapas de códigos de caracteres ToUnicode con espacios en los nombres. Estos espacios podrían provocar errores con el mapeo de texto unicode. Esta bandera indica eliminar los espacios de los nombres de los mapas de códigos de caracteres ToUnicode. Por defecto es false. |
| [ToUnicodeProcessingRules](./tounicodeprocessingrules/)() | Inicializa una nueva instancia de la clase [ToUnicodeProcessingRules](./). |
| [ToUnicodeProcessingRules](./tounicodeprocessingrules/)(bool) | Inicializa una nueva instancia de la clase [ToUnicodeProcessingRules](./) con la opción especificada para eliminar espacios de los nombres de CMap. |
| [ToUnicodeProcessingRules](./tounicodeprocessingrules/)(bool, bool) | Inicializa una nueva instancia de la clase [ToUnicodeProcessingRules](./) con opciones especificadas. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
