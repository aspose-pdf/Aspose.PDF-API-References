---
title: "Aspose::Pdf::Facades::ReplaceTextStrategy class"
linktitle: "ReplaceTextStrategy"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Facades::ReplaceTextStrategy class. Esta clase contiene parámetros que definen el comportamiento de PdfContentEditor cuando se realiza la operación ReplaceText en C++."
type: docs
weight: 3200
url: /es/cpp/aspose.pdf.facades/replacetextstrategy/
---
## ReplaceTextStrategy class


Esta clase contiene parámetros que definen el comportamiento de [PdfContentEditor](../pdfcontenteditor/) cuando se realiza la operación ReplaceText.

```cpp
class ReplaceTextStrategy : public System::Object
```

## Enums

| Enumeración | Descripción |
| --- | --- |
| [NoCharacterAction](./nocharacteraction/) | Acción a realizar si la fuente no contiene el carácter requerido. |
| [Scope](./scope/) | [Scope](./scope/) donde se aplica la operación de reemplazo de texto REPLACE_FIRST por defecto. |
## Métodos

| Método | Descripción |
| --- | --- |
| [get_IsRegularExpressionUsed](./get_isregularexpressionused/)() const | Si es false, la cadena a buscar es un texto simple. Si es true, la cadena a buscar es una expresión regular. |
| [get_NoCharacterBehavior](./get_nocharacterbehavior/)() const | Acción que se realiza cuando no se encuentra una fuente apropiada para el texto modificado (Lanzar excepción / Sustituir por otra fuente / Reemplazar de todos modos). |
| [get_ReplaceScope](./get_replacescope/)() const | [Scope](./scope/) de la operación de reemplazo (reemplazar la primera ocurrencia o reemplazar todas las ocurrencias). |
| [ReplaceTextStrategy](./replacetextstrategy/)() |  |
| [set_IsRegularExpressionUsed](./set_isregularexpressionused/)(bool) | Si es false, la cadena a buscar es un texto simple. Si es true, la cadena a buscar es una expresión regular. |
| [set_NoCharacterBehavior](./set_nocharacterbehavior/)(ReplaceTextStrategy::NoCharacterAction) | Acción que se realiza cuando no se encuentra una fuente apropiada para el texto modificado (Lanzar excepción / Sustituir por otra fuente / Reemplazar de todos modos). |
| [set_ReplaceScope](./set_replacescope/)(ReplaceTextStrategy::Scope) | [Scope](./scope/) de la operación de reemplazo (reemplazar la primera ocurrencia o reemplazar todas las ocurrencias). |
## Ver también

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
