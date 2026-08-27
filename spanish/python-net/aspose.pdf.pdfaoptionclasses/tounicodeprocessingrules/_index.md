---
title: "ToUnicodeProcessingRules"
second_title: "Referencia de API de Aspose.PDF para Python vía .NET"
description: "Esta clase describe reglas que pueden usarse para resolver el error de Adobe Preflight <br/>            \"El texto no se puede mapear a Unicode\"."
type: docs
weight: 20
url: /es/python-net/aspose.pdf.pdfaoptionclasses/tounicodeprocessingrules/
---

## ToUnicodeProcessingRules class

Esta clase describe reglas que pueden usarse para resolver el error de Adobe Preflight <br/>            "El texto no se puede mapear a Unicode".

El tipo ToUnicodeProcessingRules expone los siguientes miembros:
## Constructores
| Nombre | Descripción |
| :- | :- |
| ToUnicodeProcessingRules() | Constructor |
| ToUnicodeProcessingRules(remove_spaces) | Inicializa una nueva instancia de la clase ToUnicodeProcessingRules |
| ToUnicodeProcessingRules(remove_spaces, map_non_linked_unicodes_on_space) | Inicializa una nueva instancia de la clase ToUnicodeProcessingRules |
## Propiedades
| Nombre | Descripción |
| :- | :- |
| remove_spaces_from_c_map_names | Algunas fuentes tienen mapas de códigos de caracteres ToUnicode con espacios en los nombres. Estos espacios podrían generar errores<br/>            con el mapeo de texto Unicode. Esta bandera indica eliminar los espacios de los nombres de los mapas de códigos de caracteres ToUnicode.<br/>            Por defecto false. |
| map_non_linked_symbols_on_space | Algunas fuentes no proporcionan información sobre unicodes para algunos símbolos de texto. <br/>            Esta falta de información genera un error "Text cannot be mapped to Unicode".<br/>            Use esta bandera para mapear símbolos no vinculados al unicode "space" (código 32). |

### Ver también

* namespace [aspose.pdf.pdfaoptionclasses](/pdf/python-net/aspose.pdf.pdfaoptionclasses/)
* assembly [Aspose.PDF](/pdf/python-net/)

