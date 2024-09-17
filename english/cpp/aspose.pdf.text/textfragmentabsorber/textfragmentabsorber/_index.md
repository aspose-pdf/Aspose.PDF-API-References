---
title: Aspose::Pdf::Text::TextFragmentAbsorber::TextFragmentAbsorber constructor
linktitle: TextFragmentAbsorber
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Text::TextFragmentAbsorber::TextFragmentAbsorber constructor. Initializes a new instance of the TextFragmentAbsorber that performs search of all text segments of the document or page in C++.'
type: docs
weight: 1700
url: /cpp/aspose.pdf.text/textfragmentabsorber/textfragmentabsorber/
---
## TextFragmentAbsorber::TextFragmentAbsorber() constructor


Initializes a new instance of the [TextFragmentAbsorber](../) that performs search of all text segments of the document or page.

```cpp
ASPOSE_PDF_SHARED_API Aspose::Pdf::Text::TextFragmentAbsorber::TextFragmentAbsorber()
```

## Remarks


Performs text search and provides access to search results via [TextFragmentAbsorber::TextFragments](../) collection. 
## See Also

* Class [TextFragmentAbsorber](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## TextFragmentAbsorber::TextFragmentAbsorber(System::SharedPtr\<Aspose::Pdf::Text::TextEditOptions\>) constructor


Initializes a new instance of the [TextFragmentAbsorber](../) with text edit options, that performs search of all text segments of the document or page.

```cpp
ASPOSE_PDF_SHARED_API Aspose::Pdf::Text::TextFragmentAbsorber::TextFragmentAbsorber(System::SharedPtr<Aspose::Pdf::Text::TextEditOptions> textEditOptions)
```


| Parameter | Type | Description |
| --- | --- | --- |
| textEditOptions | System::SharedPtr\<Aspose::Pdf::Text::TextEditOptions\> | [Text](../../) edit options (Allows to turn on some edit features). |
## Remarks


Performs text search and provides access to search results via [TextFragmentAbsorber::TextFragments](../) collection. 

<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>textEditOptions</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="namespace_aspose_1_1_pdf_1_1_text" kindref="compound">Text</ref> edit options (Allows to turn on some edit features).</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [TextEditOptions](../../texteditoptions/)
* Class [TextFragmentAbsorber](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## TextFragmentAbsorber::TextFragmentAbsorber(System::String) constructor


Initializes a new instance of the [TextFragmentAbsorber](../) class for the specified text phrase.

```cpp
ASPOSE_PDF_SHARED_API Aspose::Pdf::Text::TextFragmentAbsorber::TextFragmentAbsorber(System::String phrase)
```


| Parameter | Type | Description |
| --- | --- | --- |
| phrase | System::String | Phrase that the [TextFragmentAbsorber](../) searches |
## Remarks


Performs text search of the specified phrase and provides access to search results via [TextFragmentAbsorber::TextFragments](../) collection. 

<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>phrase</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Phrase that the <ref refid="class_aspose_1_1_pdf_1_1_text_1_1_text_fragment_absorber" kindref="compound">TextFragmentAbsorber</ref> searches</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [TextFragmentAbsorber](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## TextFragmentAbsorber::TextFragmentAbsorber(System::SharedPtr\<System::Text::RegularExpressions::Regex\>) constructor


Initializes a new instance of the [TextFragmentAbsorber](../) class for the specified **System.Text.RegularExpressions.Regex** class object.

```cpp
ASPOSE_PDF_SHARED_API Aspose::Pdf::Text::TextFragmentAbsorber::TextFragmentAbsorber(System::SharedPtr<System::Text::RegularExpressions::Regex> regex)
```


| Parameter | Type | Description |
| --- | --- | --- |
| regex | System::SharedPtr\<System::Text::RegularExpressions::Regex\> | **System.Text.RegularExpressions.Regex** class object that the [TextFragmentAbsorber](../) searches |
## Remarks


Performs text search of the specified phrase and provides access to search results via [TextFragmentAbsorber::TextFragments](../) collection. 

<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>regex</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="class_system_1_1_text_1_1_regular_expressions_1_1_regex" kindref="compound">System.Text.RegularExpressions.Regex</ref> class object that the <ref refid="class_aspose_1_1_pdf_1_1_text_1_1_text_fragment_absorber" kindref="compound">TextFragmentAbsorber</ref> searches</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [TextFragmentAbsorber](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## TextFragmentAbsorber::TextFragmentAbsorber(System::String, System::SharedPtr\<Aspose::Pdf::Text::TextSearchOptions\>) constructor


Initializes a new instance of the [TextFragmentAbsorber](../) class for the specified text phrase and text search options.

```cpp
ASPOSE_PDF_SHARED_API Aspose::Pdf::Text::TextFragmentAbsorber::TextFragmentAbsorber(System::String phrase, System::SharedPtr<Aspose::Pdf::Text::TextSearchOptions> textSearchOptions)
```


| Parameter | Type | Description |
| --- | --- | --- |
| phrase | System::String | Phrase that the [TextFragmentAbsorber](../) searches |
| textSearchOptions | System::SharedPtr\<Aspose::Pdf::Text::TextSearchOptions\> | [Text](../../) search options (Allows to turn on some search features. For example, search with regular expression) |
## Remarks


Performs text search of the specified phrase and provides access to search results via [TextFragmentAbsorber::TextFragments](../) collection. 

<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>phrase</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Phrase that the <ref refid="class_aspose_1_1_pdf_1_1_text_1_1_text_fragment_absorber" kindref="compound">TextFragmentAbsorber</ref> searches</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>textSearchOptions</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="namespace_aspose_1_1_pdf_1_1_text" kindref="compound">Text</ref> search options (Allows to turn on some search features. For example, search with regular expression)</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [TextSearchOptions](../../textsearchoptions/)
* Class [TextFragmentAbsorber](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## TextFragmentAbsorber::TextFragmentAbsorber(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::SharedPtr\<Aspose::Pdf::Text::TextSearchOptions\>) constructor


Initializes a new instance of the [TextFragmentAbsorber](../) class for the specified text phrase and text search options.

```cpp
ASPOSE_PDF_SHARED_API Aspose::Pdf::Text::TextFragmentAbsorber::TextFragmentAbsorber(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::SharedPtr<Aspose::Pdf::Text::TextSearchOptions> textSearchOptions)
```


| Parameter | Type | Description |
| --- | --- | --- |
| regex | System::SharedPtr\<System::Text::RegularExpressions::Regex\> | **System.Text.RegularExpressions.Regex** class object that the [TextFragmentAbsorber](../) searches |
| textSearchOptions | System::SharedPtr\<Aspose::Pdf::Text::TextSearchOptions\> | [Text](../../) search options (Allows to turn on some search features.) |
## Remarks


Performs text search of the specified phrase and provides access to search results via [TextFragmentAbsorber::TextFragments](../) collection. 

<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>regex</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="class_system_1_1_text_1_1_regular_expressions_1_1_regex" kindref="compound">System.Text.RegularExpressions.Regex</ref> class object that the <ref refid="class_aspose_1_1_pdf_1_1_text_1_1_text_fragment_absorber" kindref="compound">TextFragmentAbsorber</ref> searches</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>textSearchOptions</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="namespace_aspose_1_1_pdf_1_1_text" kindref="compound">Text</ref> search options (Allows to turn on some search features.)</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [TextSearchOptions](../../textsearchoptions/)
* Class [TextFragmentAbsorber](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## TextFragmentAbsorber::TextFragmentAbsorber(System::ArrayPtr\<System::SharedPtr\<System::Text::RegularExpressions::Regex\>\>, System::SharedPtr\<Aspose::Pdf::Text::TextSearchOptions\>) constructor


Initializes a new instance of the [TextFragmentAbsorber](../) class for the specified text phrase and text search options.

```cpp
ASPOSE_PDF_SHARED_API Aspose::Pdf::Text::TextFragmentAbsorber::TextFragmentAbsorber(System::ArrayPtr<System::SharedPtr<System::Text::RegularExpressions::Regex>> regexes, System::SharedPtr<Aspose::Pdf::Text::TextSearchOptions> textSearchOptions)
```


| Parameter | Type | Description |
| --- | --- | --- |
| regexes | System::ArrayPtr\<System::SharedPtr\<System::Text::RegularExpressions::Regex\>\> | Array of **System.Text.RegularExpressions.Regex** class object that the [TextFragmentAbsorber](../) searches. |
| textSearchOptions | System::SharedPtr\<Aspose::Pdf::Text::TextSearchOptions\> | [Text](../../) search options (Allows to turn on some search features.). |
## Remarks


Performs text search of the specified array of phrases and provides access to search results via [TextFragmentAbsorber::RegexResults](../) dictionary. 

<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>regexes</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Array of <ref refid="class_system_1_1_text_1_1_regular_expressions_1_1_regex" kindref="compound">System.Text.RegularExpressions.Regex</ref> class object that the <ref refid="class_aspose_1_1_pdf_1_1_text_1_1_text_fragment_absorber" kindref="compound">TextFragmentAbsorber</ref> searches.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>textSearchOptions</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="namespace_aspose_1_1_pdf_1_1_text" kindref="compound">Text</ref> search options (Allows to turn on some search features.).</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [TextSearchOptions](../../textsearchoptions/)
* Class [TextFragmentAbsorber](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## TextFragmentAbsorber::TextFragmentAbsorber(System::String, System::SharedPtr\<Aspose::Pdf::Text::TextSearchOptions\>, System::SharedPtr\<Aspose::Pdf::Text::TextEditOptions\>) constructor


Initializes a new instance of the [TextFragmentAbsorber](../) class for the specified text phrase, text search options and text edit options.

```cpp
ASPOSE_PDF_SHARED_API Aspose::Pdf::Text::TextFragmentAbsorber::TextFragmentAbsorber(System::String phrase, System::SharedPtr<Aspose::Pdf::Text::TextSearchOptions> textSearchOptions, System::SharedPtr<Aspose::Pdf::Text::TextEditOptions> textEditOptions)
```


| Parameter | Type | Description |
| --- | --- | --- |
| phrase | System::String | Phrase that the [TextFragmentAbsorber](../) searches |
| textSearchOptions | System::SharedPtr\<Aspose::Pdf::Text::TextSearchOptions\> | [Text](../../) search options (Allows to turn on some search features. For example, search with regular expression) |
| textEditOptions | System::SharedPtr\<Aspose::Pdf::Text::TextEditOptions\> | [Text](../../) edit options (Allows to turn on some edit features). |
## Remarks


Performs text search of the specified phrase and provides access to search results via [TextFragmentAbsorber::TextFragments](../) collection. 

<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>phrase</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Phrase that the <ref refid="class_aspose_1_1_pdf_1_1_text_1_1_text_fragment_absorber" kindref="compound">TextFragmentAbsorber</ref> searches</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>textSearchOptions</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="namespace_aspose_1_1_pdf_1_1_text" kindref="compound">Text</ref> search options (Allows to turn on some search features. For example, search with regular expression)</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>textEditOptions</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="namespace_aspose_1_1_pdf_1_1_text" kindref="compound">Text</ref> edit options (Allows to turn on some edit features).</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [TextSearchOptions](../../textsearchoptions/)
* Class [TextEditOptions](../../texteditoptions/)
* Class [TextFragmentAbsorber](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## TextFragmentAbsorber::TextFragmentAbsorber(System::String, System::SharedPtr\<Aspose::Pdf::Text::TextEditOptions\>) constructor


Initializes a new instance of the [TextFragmentAbsorber](../) class for the specified text phrase and text edit options.

```cpp
ASPOSE_PDF_SHARED_API Aspose::Pdf::Text::TextFragmentAbsorber::TextFragmentAbsorber(System::String phrase, System::SharedPtr<Aspose::Pdf::Text::TextEditOptions> textEditOptions)
```


| Parameter | Type | Description |
| --- | --- | --- |
| phrase | System::String | Phrase that the [TextFragmentAbsorber](../) searches |
| textEditOptions | System::SharedPtr\<Aspose::Pdf::Text::TextEditOptions\> | [Text](../../) edit options (Allows to turn on some edit features). |
## Remarks


Performs text search of the specified phrase and provides access to search results via [TextFragmentAbsorber::TextFragments](../) collection. 

<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>phrase</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Phrase that the <ref refid="class_aspose_1_1_pdf_1_1_text_1_1_text_fragment_absorber" kindref="compound">TextFragmentAbsorber</ref> searches</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>textEditOptions</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="namespace_aspose_1_1_pdf_1_1_text" kindref="compound">Text</ref> edit options (Allows to turn on some edit features).</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [TextEditOptions](../../texteditoptions/)
* Class [TextFragmentAbsorber](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## TextFragmentAbsorber::TextFragmentAbsorber(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::SharedPtr\<Aspose::Pdf::Text::TextEditOptions\>) constructor


Initializes a new instance of the [TextFragmentAbsorber](../) class for the specified text phrase and text edit options.

```cpp
ASPOSE_PDF_SHARED_API Aspose::Pdf::Text::TextFragmentAbsorber::TextFragmentAbsorber(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::SharedPtr<Aspose::Pdf::Text::TextEditOptions> textEditOptions)
```


| Parameter | Type | Description |
| --- | --- | --- |
| regex | System::SharedPtr\<System::Text::RegularExpressions::Regex\> | **System.Text.RegularExpressions.Regex** class object that the [TextFragmentAbsorber](../) searches |
| textEditOptions | System::SharedPtr\<Aspose::Pdf::Text::TextEditOptions\> | [Text](../../) edit options (Allows to turn on some edit features). |
## Remarks


Performs text search of the specified phrase and provides access to search results via [TextFragmentAbsorber::TextFragments](../) collection. 

<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>regex</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="class_system_1_1_text_1_1_regular_expressions_1_1_regex" kindref="compound">System.Text.RegularExpressions.Regex</ref> class object that the <ref refid="class_aspose_1_1_pdf_1_1_text_1_1_text_fragment_absorber" kindref="compound">TextFragmentAbsorber</ref> searches</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>textEditOptions</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="namespace_aspose_1_1_pdf_1_1_text" kindref="compound">Text</ref> edit options (Allows to turn on some edit features).</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [TextEditOptions](../../texteditoptions/)
* Class [TextFragmentAbsorber](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
