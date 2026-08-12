---
title: "Clase Aspose::Pdf::Text::TextEditOptions"
linktitle: "TextEditOptions"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::Text::TextEditOptions. Describe las opciones de operaciones de edición de texto en C++."
type: docs
weight: 3800
url: /es/cpp/aspose.pdf.text/texteditoptions/
---
## TextEditOptions class


Describe las opciones de operaciones de edición de texto.

```cpp
class TextEditOptions : public Aspose::Pdf::Text::TextOptions
```

## Enums

| Enumeración | Descripción |
| --- | --- |
| [ClippingPathsProcessingMode](./clippingpathsprocessingmode/) | Modos de procesamiento de rutas de recorte. |
| [FontReplace](./fontreplace/) | Comportamiento de sustitución de [Font](../font/). |
| [LanguageTransformation](./languagetransformation/) | Modos de transformación de idioma. |
| [NoCharacterAction](./nocharacteraction/) | Acción a realizar si la fuente no contiene el carácter requerido. |
## Métodos

| Método | Descripción |
| --- | --- |
| [get_AllowLanguageTransformation](./get_allowlanguagetransformation/)() const | Obtiene el valor que permite el uso de la transformación de idioma al agregar o editar texto. true - la transformación de idioma se aplicará si es necesario (valor predeterminado). false - la transformación de idioma NO se aplicará. |
| [get_ClippingPathsProcessing](./get_clippingpathsprocessing/)() const | Obtiene el modo para procesar la ruta de recorte del texto editado. |
| [get_FontReplaceBehavior](./get_fontreplacebehavior/)() const | Obtiene el modo que define el comportamiento para escenarios de sustitución de fuentes. |
| [get_LanguageTransformationBehavior](./get_languagetransformationbehavior/)() const | Obtiene el modo que define el comportamiento para escenarios de transformación de idioma. |
| [get_NoCharacterBehavior](./get_nocharacterbehavior/)() const | Obtiene el modo que define el comportamiento en caso de que las fuentes no contengan los caracteres solicitados. |
| [get_ReplacementFont](./get_replacementfont/)() const | Obtiene la fuente utilizada para la sustitución si la fuente del usuario no contiene el carácter requerido. |
| [get_ToAttemptGetUnderlineFromSource](./get_toattemptgetunderlinefromsource/)() const | Obtiene el valor que permite buscar subrayado de texto en la página del documento fuente. (Obsoleto) Por favor, use TextSearchOptions.SearchForTextRelatedGraphics en su lugar. |
| [set_AllowLanguageTransformation](./set_allowlanguagetransformation/)(bool) | Establece el valor que permite el uso de la transformación de idioma al agregar o editar texto. true - la transformación de idioma se aplicará si es necesario (valor predeterminado). false - la transformación de idioma NO se aplicará. |
| [set_ClippingPathsProcessing](./set_clippingpathsprocessing/)(TextEditOptions::ClippingPathsProcessingMode) | Obtiene el modo para procesar la ruta de recorte del texto editado. |
| [set_FontReplaceBehavior](./set_fontreplacebehavior/)(TextEditOptions::FontReplace) | Obtiene el modo que define el comportamiento para escenarios de sustitución de fuentes. |
| [set_LanguageTransformationBehavior](./set_languagetransformationbehavior/)(TextEditOptions::LanguageTransformation) | Obtiene el modo que define el comportamiento para escenarios de transformación de idioma. |
| [set_NoCharacterBehavior](./set_nocharacterbehavior/)(TextEditOptions::NoCharacterAction) | Establece el modo que define el comportamiento en caso de que las fuentes no contengan los caracteres solicitados. |
| [set_ReplacementFont](./set_replacementfont/)(const System::SharedPtr\<Font\>\&) | Establece la fuente utilizada para la sustitución si la fuente del usuario no contiene el carácter requerido. |
| [set_ToAttemptGetUnderlineFromSource](./set_toattemptgetunderlinefromsource/)(bool) | Establece el valor que permite buscar subrayado de texto en la página del documento fuente. (Obsoleto) Por favor, use TextSearchOptions.SearchForTextRelatedGraphics en su lugar. |
| [TextEditOptions](./texteditoptions/)(TextEditOptions::NoCharacterAction) | Inicializa una nueva instancia del objeto [TextEditOptions](./) para el modo de comportamiento sin caracteres especificado. |
| [TextEditOptions](./texteditoptions/)(TextEditOptions::FontReplace) | Inicializa una nueva instancia del objeto [TextEditOptions](./) para el modo de comportamiento de sustitución de fuentes especificado. |
| [TextEditOptions](./texteditoptions/)(bool) | Inicializa una nueva instancia del objeto [TextEditOptions](./) para el permiso de transformación de idioma especificado. |
| [TextEditOptions](./texteditoptions/)(TextEditOptions::LanguageTransformation) | Inicializa una nueva instancia del objeto [TextEditOptions](./) para el modo de comportamiento de transformación de idioma especificado. |
## Ver también

* Class [TextOptions](../textoptions/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
