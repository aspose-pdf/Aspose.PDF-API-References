---
title: Aspose::Pdf::Text::TextFragmentAbsorber::TextFragmentAbsorber constructor
linktitle: TextFragmentAbsorber
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Text::TextFragmentAbsorber::TextFragmentAbsorber constructor. Initializes a new instance of the TextFragmentAbsorber that performs search of all text segments of the document or page in C++.'
type: docs
weight: 100
url: /cpp/aspose.pdf.text/textfragmentabsorber/textfragmentabsorber/
---
## TextFragmentAbsorber::TextFragmentAbsorber() constructor


Initializes a new instance of the [TextFragmentAbsorber](../) that performs search of all text segments of the document or page.

```cpp
Aspose::Pdf::Text::TextFragmentAbsorber::TextFragmentAbsorber()
```

## Remarks


Performs text search and provides access to search results via [TextFragmentAbsorber::TextFragments](../) collection. 
## See Also

* Class [TextFragmentAbsorber](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## TextFragmentAbsorber::TextFragmentAbsorber(System::ArrayPtr\<System::SharedPtr\<System::Text::RegularExpressions::Regex\>\>, System::SharedPtr\<Aspose::Pdf::Text::TextSearchOptions\>) constructor


Initializes a new instance of the [TextFragmentAbsorber](../) class for the specified text phrase and text search options.

```cpp
Aspose::Pdf::Text::TextFragmentAbsorber::TextFragmentAbsorber(System::ArrayPtr<System::SharedPtr<System::Text::RegularExpressions::Regex>> regexes, System::SharedPtr<Aspose::Pdf::Text::TextSearchOptions> textSearchOptions)
```


| Parameter | Type | Description |
| --- | --- | --- |
| regexes | System::ArrayPtr\<System::SharedPtr\<System::Text::RegularExpressions::Regex\>\> | Array of [System.Text.RegularExpressions.Regex](../../../system.text.regularexpressions/regex/) class object that the [TextFragmentAbsorber](../) searches. |
| textSearchOptions | System::SharedPtr\<Aspose::Pdf::Text::TextSearchOptions\> | [Text](../../) search options (Allows to turn on some search features.). |
## Remarks


Performs text search of the specified array of phrases and provides access to search results via [TextFragmentAbsorber::RegexResults](../) dictionary. 

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Regex](../../../system.text.regularexpressions/regex/)
* Class [TextSearchOptions](../../textsearchoptions/)
* Class [TextFragmentAbsorber](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## TextFragmentAbsorber::TextFragmentAbsorber(System::SharedPtr\<Aspose::Pdf::Text::TextEditOptions\>) constructor


Initializes a new instance of the [TextFragmentAbsorber](../) with text edit options, that performs search of all text segments of the document or page.

```cpp
Aspose::Pdf::Text::TextFragmentAbsorber::TextFragmentAbsorber(System::SharedPtr<Aspose::Pdf::Text::TextEditOptions> textEditOptions)
```


| Parameter | Type | Description |
| --- | --- | --- |
| textEditOptions | System::SharedPtr\<Aspose::Pdf::Text::TextEditOptions\> | [Text](../../) edit options (Allows to turn on some edit features). |
## Remarks


Performs text search and provides access to search results via [TextFragmentAbsorber::TextFragments](../) collection. 

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [TextEditOptions](../../texteditoptions/)
* Class [TextFragmentAbsorber](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## TextFragmentAbsorber::TextFragmentAbsorber(System::SharedPtr\<System::Text::RegularExpressions::Regex\>) constructor


Initializes a new instance of the [TextFragmentAbsorber](../) class for the specified [System.Text.RegularExpressions.Regex](../../../system.text.regularexpressions/regex/) class object.

```cpp
Aspose::Pdf::Text::TextFragmentAbsorber::TextFragmentAbsorber(System::SharedPtr<System::Text::RegularExpressions::Regex> regex)
```


| Parameter | Type | Description |
| --- | --- | --- |
| regex | System::SharedPtr\<System::Text::RegularExpressions::Regex\> | [System.Text.RegularExpressions.Regex](../../../system.text.regularexpressions/regex/) class object that the [TextFragmentAbsorber](../) searches |
## Remarks


Performs text search of the specified phrase and provides access to search results via [TextFragmentAbsorber::TextFragments](../) collection. 

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Regex](../../../system.text.regularexpressions/regex/)
* Class [TextFragmentAbsorber](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## TextFragmentAbsorber::TextFragmentAbsorber(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::SharedPtr\<Aspose::Pdf::Text::TextEditOptions\>) constructor


Initializes a new instance of the [TextFragmentAbsorber](../) class for the specified text phrase and text edit options.

```cpp
Aspose::Pdf::Text::TextFragmentAbsorber::TextFragmentAbsorber(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::SharedPtr<Aspose::Pdf::Text::TextEditOptions> textEditOptions)
```


| Parameter | Type | Description |
| --- | --- | --- |
| regex | System::SharedPtr\<System::Text::RegularExpressions::Regex\> | [System.Text.RegularExpressions.Regex](../../../system.text.regularexpressions/regex/) class object that the [TextFragmentAbsorber](../) searches |
| textEditOptions | System::SharedPtr\<Aspose::Pdf::Text::TextEditOptions\> | [Text](../../) edit options (Allows to turn on some edit features). |
## Remarks


Performs text search of the specified phrase and provides access to search results via [TextFragmentAbsorber::TextFragments](../) collection. 

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Regex](../../../system.text.regularexpressions/regex/)
* Class [TextEditOptions](../../texteditoptions/)
* Class [TextFragmentAbsorber](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## TextFragmentAbsorber::TextFragmentAbsorber(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::SharedPtr\<Aspose::Pdf::Text::TextSearchOptions\>) constructor


Initializes a new instance of the [TextFragmentAbsorber](../) class for the specified text phrase and text search options.

```cpp
Aspose::Pdf::Text::TextFragmentAbsorber::TextFragmentAbsorber(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::SharedPtr<Aspose::Pdf::Text::TextSearchOptions> textSearchOptions)
```


| Parameter | Type | Description |
| --- | --- | --- |
| regex | System::SharedPtr\<System::Text::RegularExpressions::Regex\> | [System.Text.RegularExpressions.Regex](../../../system.text.regularexpressions/regex/) class object that the [TextFragmentAbsorber](../) searches |
| textSearchOptions | System::SharedPtr\<Aspose::Pdf::Text::TextSearchOptions\> | [Text](../../) search options (Allows to turn on some search features.) |
## Remarks


Performs text search of the specified phrase and provides access to search results via [TextFragmentAbsorber::TextFragments](../) collection. 

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Regex](../../../system.text.regularexpressions/regex/)
* Class [TextSearchOptions](../../textsearchoptions/)
* Class [TextFragmentAbsorber](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## TextFragmentAbsorber::TextFragmentAbsorber(System::String) constructor


Initializes a new instance of the [TextFragmentAbsorber](../) class for the specified text phrase.

```cpp
Aspose::Pdf::Text::TextFragmentAbsorber::TextFragmentAbsorber(System::String phrase)
```


| Parameter | Type | Description |
| --- | --- | --- |
| phrase | System::String | Phrase that the [TextFragmentAbsorber](../) searches |
## Remarks


Performs text search of the specified phrase and provides access to search results via [TextFragmentAbsorber::TextFragments](../) collection. 

## See Also

* Class [String](../../../system/string/)
* Class [TextFragmentAbsorber](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## TextFragmentAbsorber::TextFragmentAbsorber(System::String, System::SharedPtr\<Aspose::Pdf::Text::TextEditOptions\>) constructor


Initializes a new instance of the [TextFragmentAbsorber](../) class for the specified text phrase and text edit options.

```cpp
Aspose::Pdf::Text::TextFragmentAbsorber::TextFragmentAbsorber(System::String phrase, System::SharedPtr<Aspose::Pdf::Text::TextEditOptions> textEditOptions)
```


| Parameter | Type | Description |
| --- | --- | --- |
| phrase | System::String | Phrase that the [TextFragmentAbsorber](../) searches |
| textEditOptions | System::SharedPtr\<Aspose::Pdf::Text::TextEditOptions\> | [Text](../../) edit options (Allows to turn on some edit features). |
## Remarks


Performs text search of the specified phrase and provides access to search results via [TextFragmentAbsorber::TextFragments](../) collection. 

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [TextEditOptions](../../texteditoptions/)
* Class [TextFragmentAbsorber](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## TextFragmentAbsorber::TextFragmentAbsorber(System::String, System::SharedPtr\<Aspose::Pdf::Text::TextSearchOptions\>) constructor


Initializes a new instance of the [TextFragmentAbsorber](../) class for the specified text phrase and text search options.

```cpp
Aspose::Pdf::Text::TextFragmentAbsorber::TextFragmentAbsorber(System::String phrase, System::SharedPtr<Aspose::Pdf::Text::TextSearchOptions> textSearchOptions)
```


| Parameter | Type | Description |
| --- | --- | --- |
| phrase | System::String | Phrase that the [TextFragmentAbsorber](../) searches |
| textSearchOptions | System::SharedPtr\<Aspose::Pdf::Text::TextSearchOptions\> | [Text](../../) search options (Allows to turn on some search features. For example, search with regular expression) |
## Remarks


Performs text search of the specified phrase and provides access to search results via [TextFragmentAbsorber::TextFragments](../) collection. 

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [TextSearchOptions](../../textsearchoptions/)
* Class [TextFragmentAbsorber](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## TextFragmentAbsorber::TextFragmentAbsorber(System::String, System::SharedPtr\<Aspose::Pdf::Text::TextSearchOptions\>, System::SharedPtr\<Aspose::Pdf::Text::TextEditOptions\>) constructor


Initializes a new instance of the [TextFragmentAbsorber](../) class for the specified text phrase, text search options and text edit options.

```cpp
Aspose::Pdf::Text::TextFragmentAbsorber::TextFragmentAbsorber(System::String phrase, System::SharedPtr<Aspose::Pdf::Text::TextSearchOptions> textSearchOptions, System::SharedPtr<Aspose::Pdf::Text::TextEditOptions> textEditOptions)
```


| Parameter | Type | Description |
| --- | --- | --- |
| phrase | System::String | Phrase that the [TextFragmentAbsorber](../) searches |
| textSearchOptions | System::SharedPtr\<Aspose::Pdf::Text::TextSearchOptions\> | [Text](../../) search options (Allows to turn on some search features. For example, search with regular expression) |
| textEditOptions | System::SharedPtr\<Aspose::Pdf::Text::TextEditOptions\> | [Text](../../) edit options (Allows to turn on some edit features). |
## Remarks


Performs text search of the specified phrase and provides access to search results via [TextFragmentAbsorber::TextFragments](../) collection. 

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [TextSearchOptions](../../textsearchoptions/)
* Class [TextEditOptions](../../texteditoptions/)
* Class [TextFragmentAbsorber](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
