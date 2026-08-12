---
title: "Constructor Aspose::Pdf::Text::TextFragmentAbsorber::TextFragmentAbsorber"
linktitle: "TextFragmentAbsorber"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Constructor Aspose::Pdf::Text::TextFragmentAbsorber::TextFragmentAbsorber. Inicializa una nueva instancia de TextFragmentAbsorber que realiza la búsqueda de todos los segmentos de texto del documento o página en C++."
type: docs
weight: 100
url: /es/cpp/aspose.pdf.text/textfragmentabsorber/textfragmentabsorber/
---
## TextFragmentAbsorber::TextFragmentAbsorber() constructor


Inicializa una nueva instancia de [TextFragmentAbsorber](../) que realiza la búsqueda de todos los segmentos de texto del documento o página.

```cpp
Aspose::Pdf::Text::TextFragmentAbsorber::TextFragmentAbsorber()
```

## Observaciones


Realiza una búsqueda de texto y proporciona acceso a los resultados de la búsqueda mediante la colección [TextFragmentAbsorber::TextFragments](../).
## Ver también

* Class [TextFragmentAbsorber](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## TextFragmentAbsorber::TextFragmentAbsorber(const System::ArrayPtr\<System::SharedPtr\<System::Text::RegularExpressions::Regex\>\>\&, const System::SharedPtr\<Aspose::Pdf::Text::TextSearchOptions\>\&) constructor


Inicializa una nueva instancia de la clase [TextFragmentAbsorber](../) para la frase de texto especificada y las opciones de búsqueda de texto.

```cpp
Aspose::Pdf::Text::TextFragmentAbsorber::TextFragmentAbsorber(const System::ArrayPtr<System::SharedPtr<System::Text::RegularExpressions::Regex>> &regexes, const System::SharedPtr<Aspose::Pdf::Text::TextSearchOptions> &textSearchOptions)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| regexes | const System::ArrayPtr\<System::SharedPtr\<System::Text::RegularExpressions::Regex\>\>\& | Matriz de objetos de la clase [System.Text.RegularExpressions.Regex](../../../system.text.regularexpressions/regex/) que busca el [TextFragmentAbsorber](../). |
| textSearchOptions | const System::SharedPtr\<Aspose::Pdf::Text::TextSearchOptions\>\& | Opciones de búsqueda de [Text](../../) (Permite activar algunas funciones de búsqueda.). |
## Observaciones


Realiza una búsqueda de texto del conjunto especificado de frases y proporciona acceso a los resultados de la búsqueda mediante el diccionario [TextFragmentAbsorber::RegexResults](../).

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Regex](../../../system.text.regularexpressions/regex/)
* Class [TextSearchOptions](../../textsearchoptions/)
* Class [TextFragmentAbsorber](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## TextFragmentAbsorber::TextFragmentAbsorber(const System::SharedPtr\<Aspose::Pdf::Text::TextEditOptions\>\&) constructor


Inicializa una nueva instancia de [TextFragmentAbsorber](../) con opciones de edición de texto, que realiza la búsqueda de todos los segmentos de texto del documento o página.

```cpp
Aspose::Pdf::Text::TextFragmentAbsorber::TextFragmentAbsorber(const System::SharedPtr<Aspose::Pdf::Text::TextEditOptions> &textEditOptions)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| textEditOptions | const System::SharedPtr\<Aspose::Pdf::Text::TextEditOptions\>\& | Opciones de edición de [Text](../../) (Permite activar algunas funciones de edición). |
## Observaciones


Realiza una búsqueda de texto y proporciona acceso a los resultados de la búsqueda mediante la colección [TextFragmentAbsorber::TextFragments](../).

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [TextEditOptions](../../texteditoptions/)
* Class [TextFragmentAbsorber](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## TextFragmentAbsorber::TextFragmentAbsorber(const System::SharedPtr\<System::Text::RegularExpressions::Regex\>\&) constructor


Inicializa una nueva instancia de la clase [TextFragmentAbsorber](../) para el objeto de la clase [System.Text.RegularExpressions.Regex](../../../system.text.regularexpressions/regex/) especificado.

```cpp
Aspose::Pdf::Text::TextFragmentAbsorber::TextFragmentAbsorber(const System::SharedPtr<System::Text::RegularExpressions::Regex> &regex)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| regex | const System::SharedPtr\<System::Text::RegularExpressions::Regex\>\& | Objeto de la clase [System.Text.RegularExpressions.Regex](../../../system.text.regularexpressions/regex/) que busca el [TextFragmentAbsorber](../). |
## Observaciones


Realiza una búsqueda de texto de la frase especificada y proporciona acceso a los resultados de la búsqueda mediante la colección [TextFragmentAbsorber::TextFragments](../).

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Regex](../../../system.text.regularexpressions/regex/)
* Class [TextFragmentAbsorber](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## TextFragmentAbsorber::TextFragmentAbsorber(const System::SharedPtr\<System::Text::RegularExpressions::Regex\>\&, const System::SharedPtr\<Aspose::Pdf::Text::TextEditOptions\>\&) constructor


Inicializa una nueva instancia de la clase [TextFragmentAbsorber](../) para la frase de texto especificada y las opciones de edición de texto.

```cpp
Aspose::Pdf::Text::TextFragmentAbsorber::TextFragmentAbsorber(const System::SharedPtr<System::Text::RegularExpressions::Regex> &regex, const System::SharedPtr<Aspose::Pdf::Text::TextEditOptions> &textEditOptions)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| regex | const System::SharedPtr\<System::Text::RegularExpressions::Regex\>\& | Objeto de la clase [System.Text.RegularExpressions.Regex](../../../system.text.regularexpressions/regex/) que busca el [TextFragmentAbsorber](../). |
| textEditOptions | const System::SharedPtr\<Aspose::Pdf::Text::TextEditOptions\>\& | Opciones de edición de [Text](../../) (Permite activar algunas funciones de edición). |
## Observaciones


Realiza una búsqueda de texto de la frase especificada y proporciona acceso a los resultados de la búsqueda mediante la colección [TextFragmentAbsorber::TextFragments](../).

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Regex](../../../system.text.regularexpressions/regex/)
* Class [TextEditOptions](../../texteditoptions/)
* Class [TextFragmentAbsorber](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## TextFragmentAbsorber::TextFragmentAbsorber(const System::SharedPtr\<System::Text::RegularExpressions::Regex\>\&, const System::SharedPtr\<Aspose::Pdf::Text::TextSearchOptions\>\&) constructor


Inicializa una nueva instancia de la clase [TextFragmentAbsorber](../) para la frase de texto especificada y las opciones de búsqueda de texto.

```cpp
Aspose::Pdf::Text::TextFragmentAbsorber::TextFragmentAbsorber(const System::SharedPtr<System::Text::RegularExpressions::Regex> &regex, const System::SharedPtr<Aspose::Pdf::Text::TextSearchOptions> &textSearchOptions)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| regex | const System::SharedPtr\<System::Text::RegularExpressions::Regex\>\& | Objeto de la clase [System.Text.RegularExpressions.Regex](../../../system.text.regularexpressions/regex/) que busca el [TextFragmentAbsorber](../). |
| textSearchOptions | const System::SharedPtr\<Aspose::Pdf::Text::TextSearchOptions\>\& | Opciones de búsqueda de [Text](../../) (Permite activar algunas funciones de búsqueda.) |
## Observaciones


Realiza una búsqueda de texto de la frase especificada y proporciona acceso a los resultados de la búsqueda mediante la colección [TextFragmentAbsorber::TextFragments](../).

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Regex](../../../system.text.regularexpressions/regex/)
* Class [TextSearchOptions](../../textsearchoptions/)
* Class [TextFragmentAbsorber](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## TextFragmentAbsorber::TextFragmentAbsorber(const System::String\&) constructor


Inicializa una nueva instancia de la clase [TextFragmentAbsorber](../) para la frase de texto especificada.

```cpp
Aspose::Pdf::Text::TextFragmentAbsorber::TextFragmentAbsorber(const System::String &phrase)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| phrase | const System::String\& | Frase que busca el [TextFragmentAbsorber](../). |
## Observaciones


Realiza una búsqueda de texto de la frase especificada y proporciona acceso a los resultados de la búsqueda mediante la colección [TextFragmentAbsorber::TextFragments](../).

## Ver también

* Class [String](../../../system/string/)
* Class [TextFragmentAbsorber](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## TextFragmentAbsorber::TextFragmentAbsorber(const System::String\&, const System::SharedPtr\<Aspose::Pdf::Text::TextEditOptions\>\&) constructor


Inicializa una nueva instancia de la clase [TextFragmentAbsorber](../) para la frase de texto especificada y las opciones de edición de texto.

```cpp
Aspose::Pdf::Text::TextFragmentAbsorber::TextFragmentAbsorber(const System::String &phrase, const System::SharedPtr<Aspose::Pdf::Text::TextEditOptions> &textEditOptions)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| phrase | const System::String\& | Frase que busca el [TextFragmentAbsorber](../). |
| textEditOptions | const System::SharedPtr\<Aspose::Pdf::Text::TextEditOptions\>\& | Opciones de edición de [Text](../../) (Permite activar algunas funciones de edición). |
## Observaciones


Realiza una búsqueda de texto de la frase especificada y proporciona acceso a los resultados de la búsqueda mediante la colección [TextFragmentAbsorber::TextFragments](../).

## Ver también

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [TextEditOptions](../../texteditoptions/)
* Class [TextFragmentAbsorber](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## TextFragmentAbsorber::TextFragmentAbsorber(const System::String\&, const System::SharedPtr\<Aspose::Pdf::Text::TextSearchOptions\>\&) constructor


Inicializa una nueva instancia de la clase [TextFragmentAbsorber](../) para la frase de texto especificada y las opciones de búsqueda de texto.

```cpp
Aspose::Pdf::Text::TextFragmentAbsorber::TextFragmentAbsorber(const System::String &phrase, const System::SharedPtr<Aspose::Pdf::Text::TextSearchOptions> &textSearchOptions)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| phrase | const System::String\& | Frase que busca el [TextFragmentAbsorber](../). |
| textSearchOptions | const System::SharedPtr\<Aspose::Pdf::Text::TextSearchOptions\>\& | Opciones de búsqueda de [Text](../../) (Permite activar algunas funciones de búsqueda. Por ejemplo, búsqueda con expresión regular) |
## Observaciones


Realiza una búsqueda de texto de la frase especificada y proporciona acceso a los resultados de la búsqueda mediante la colección [TextFragmentAbsorber::TextFragments](../).

## Ver también

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [TextSearchOptions](../../textsearchoptions/)
* Class [TextFragmentAbsorber](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## TextFragmentAbsorber::TextFragmentAbsorber(const System::String\&, const System::SharedPtr\<Aspose::Pdf::Text::TextSearchOptions\>\&, const System::SharedPtr\<Aspose::Pdf::Text::TextEditOptions\>\&) constructor


Inicializa una nueva instancia de la clase [TextFragmentAbsorber](../) para la frase de texto especificada, las opciones de búsqueda de texto y las opciones de edición de texto.

```cpp
Aspose::Pdf::Text::TextFragmentAbsorber::TextFragmentAbsorber(const System::String &phrase, const System::SharedPtr<Aspose::Pdf::Text::TextSearchOptions> &textSearchOptions, const System::SharedPtr<Aspose::Pdf::Text::TextEditOptions> &textEditOptions)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| phrase | const System::String\& | Frase que busca el [TextFragmentAbsorber](../). |
| textSearchOptions | const System::SharedPtr\<Aspose::Pdf::Text::TextSearchOptions\>\& | Opciones de búsqueda de [Text](../../) (Permite activar algunas funciones de búsqueda. Por ejemplo, búsqueda con expresión regular) |
| textEditOptions | const System::SharedPtr\<Aspose::Pdf::Text::TextEditOptions\>\& | Opciones de edición de [Text](../../) (Permite activar algunas funciones de edición). |
## Observaciones


Realiza una búsqueda de texto de la frase especificada y proporciona acceso a los resultados de la búsqueda mediante la colección [TextFragmentAbsorber::TextFragments](../).

## Ver también

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [TextSearchOptions](../../textsearchoptions/)
* Class [TextEditOptions](../../texteditoptions/)
* Class [TextFragmentAbsorber](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
