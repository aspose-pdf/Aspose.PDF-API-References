---
title: "Aspose::Pdf::Text::TextFragmentAbsorber::TextFragmentAbsorber konstruktor"
linktitle: "TextFragmentAbsorber"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Text::TextFragmentAbsorber::TextFragmentAbsorber konstruktor. Initierar en ny instans av TextFragmentAbsorber som utför sökning av alla textsegment i dokumentet eller sidan i C++."
type: docs
weight: 100
url: /sv/cpp/aspose.pdf.text/textfragmentabsorber/textfragmentabsorber/
---
## TextFragmentAbsorber::TextFragmentAbsorber() constructor


Initierar en ny instans av [TextFragmentAbsorber](../) som utför sökning av alla textsegment i dokumentet eller sidan.

```cpp
Aspose::Pdf::Text::TextFragmentAbsorber::TextFragmentAbsorber()
```

## Anmärkningar


Utför textsökning och ger åtkomst till sökresultaten via [TextFragmentAbsorber::TextFragments](../) samling.
## Se även

* Class [TextFragmentAbsorber](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## TextFragmentAbsorber::TextFragmentAbsorber(const System::ArrayPtr\<System::SharedPtr\<System::Text::RegularExpressions::Regex\>\>\&, const System::SharedPtr\<Aspose::Pdf::Text::TextSearchOptions\>\&) constructor


Initierar en ny instans av [TextFragmentAbsorber](../) klassen för den angivna textfrasen och textsökningsalternativen.

```cpp
Aspose::Pdf::Text::TextFragmentAbsorber::TextFragmentAbsorber(const System::ArrayPtr<System::SharedPtr<System::Text::RegularExpressions::Regex>> &regexes, const System::SharedPtr<Aspose::Pdf::Text::TextSearchOptions> &textSearchOptions)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| regexes | const System::ArrayPtr\<System::SharedPtr\<System::Text::RegularExpressions::Regex\>\>\& | Array av [System.Text.RegularExpressions.Regex](../../../system.text.regularexpressions/regex/) klassobjekt som [TextFragmentAbsorber](../) söker efter. |
| textSearchOptions | const System::SharedPtr\<Aspose::Pdf::Text::TextSearchOptions\>\& | [Text](../../) sökalternativ (Tillåter att aktivera vissa sökfunktioner.). |
## Anmärkningar


Utför textsökning av den angivna arrayen av fraser och ger åtkomst till sökresultaten via [TextFragmentAbsorber::RegexResults](../) ordbok.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Regex](../../../system.text.regularexpressions/regex/)
* Class [TextSearchOptions](../../textsearchoptions/)
* Class [TextFragmentAbsorber](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## TextFragmentAbsorber::TextFragmentAbsorber(const System::SharedPtr\<Aspose::Pdf::Text::TextEditOptions\>\&) constructor


Initierar en ny instans av [TextFragmentAbsorber](../) med textredigeringsalternativ, som utför sökning av alla textsegment i dokumentet eller sidan.

```cpp
Aspose::Pdf::Text::TextFragmentAbsorber::TextFragmentAbsorber(const System::SharedPtr<Aspose::Pdf::Text::TextEditOptions> &textEditOptions)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| textEditOptions | const System::SharedPtr\<Aspose::Pdf::Text::TextEditOptions\>\& | [Text](../../) redigeringsalternativ (Tillåter att aktivera vissa redigeringsfunktioner). |
## Anmärkningar


Utför textsökning och ger åtkomst till sökresultaten via [TextFragmentAbsorber::TextFragments](../) samling.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [TextEditOptions](../../texteditoptions/)
* Class [TextFragmentAbsorber](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## TextFragmentAbsorber::TextFragmentAbsorber(const System::SharedPtr\<System::Text::RegularExpressions::Regex\>\&) constructor


Initierar en ny instans av [TextFragmentAbsorber](../) klassen för det angivna [System.Text.RegularExpressions.Regex](../../../system.text.regularexpressions/regex/) klassobjektet.

```cpp
Aspose::Pdf::Text::TextFragmentAbsorber::TextFragmentAbsorber(const System::SharedPtr<System::Text::RegularExpressions::Regex> &regex)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| regex | const System::SharedPtr\<System::Text::RegularExpressions::Regex\>\& | [System.Text.RegularExpressions.Regex](../../../system.text.regularexpressions/regex/) klassobjekt som [TextFragmentAbsorber](../) söker. |
## Anmärkningar


Utför textsökning av den angivna frasen och ger åtkomst till sökresultat via [TextFragmentAbsorber::TextFragments](../) samling.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Regex](../../../system.text.regularexpressions/regex/)
* Class [TextFragmentAbsorber](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## TextFragmentAbsorber::TextFragmentAbsorber(const System::SharedPtr\<System::Text::RegularExpressions::Regex\>\&, const System::SharedPtr\<Aspose::Pdf::Text::TextEditOptions\>\&) constructor


Initierar en ny instans av klassen [TextFragmentAbsorber](../) för den angivna textfrasen och alternativ för textredigering.

```cpp
Aspose::Pdf::Text::TextFragmentAbsorber::TextFragmentAbsorber(const System::SharedPtr<System::Text::RegularExpressions::Regex> &regex, const System::SharedPtr<Aspose::Pdf::Text::TextEditOptions> &textEditOptions)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| regex | const System::SharedPtr\<System::Text::RegularExpressions::Regex\>\& | [System.Text.RegularExpressions.Regex](../../../system.text.regularexpressions/regex/) klassobjekt som [TextFragmentAbsorber](../) söker. |
| textEditOptions | const System::SharedPtr\<Aspose::Pdf::Text::TextEditOptions\>\& | [Text](../../) redigeringsalternativ (Tillåter att aktivera vissa redigeringsfunktioner). |
## Anmärkningar


Utför textsökning av den angivna frasen och ger åtkomst till sökresultat via [TextFragmentAbsorber::TextFragments](../) samling.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Regex](../../../system.text.regularexpressions/regex/)
* Class [TextEditOptions](../../texteditoptions/)
* Class [TextFragmentAbsorber](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## TextFragmentAbsorber::TextFragmentAbsorber(const System::SharedPtr\<System::Text::RegularExpressions::Regex\>\&, const System::SharedPtr\<Aspose::Pdf::Text::TextSearchOptions\>\&) constructor


Initierar en ny instans av [TextFragmentAbsorber](../) klassen för den angivna textfrasen och textsökningsalternativen.

```cpp
Aspose::Pdf::Text::TextFragmentAbsorber::TextFragmentAbsorber(const System::SharedPtr<System::Text::RegularExpressions::Regex> &regex, const System::SharedPtr<Aspose::Pdf::Text::TextSearchOptions> &textSearchOptions)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| regex | const System::SharedPtr\<System::Text::RegularExpressions::Regex\>\& | [System.Text.RegularExpressions.Regex](../../../system.text.regularexpressions/regex/) klassobjekt som [TextFragmentAbsorber](../) söker. |
| textSearchOptions | const System::SharedPtr\<Aspose::Pdf::Text::TextSearchOptions\>\& | [Text](../../) sökalternativ (Tillåter att aktivera vissa sökfunktioner.) |
## Anmärkningar


Utför textsökning av den angivna frasen och ger åtkomst till sökresultat via [TextFragmentAbsorber::TextFragments](../) samling.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Regex](../../../system.text.regularexpressions/regex/)
* Class [TextSearchOptions](../../textsearchoptions/)
* Class [TextFragmentAbsorber](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## TextFragmentAbsorber::TextFragmentAbsorber(const System::String\&) constructor


Initierar en ny instans av klassen [TextFragmentAbsorber](../) för den angivna textfrasen.

```cpp
Aspose::Pdf::Text::TextFragmentAbsorber::TextFragmentAbsorber(const System::String &phrase)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| phrase | const System::String\& | Fras som [TextFragmentAbsorber](../) söker efter |
## Anmärkningar


Utför textsökning av den angivna frasen och ger åtkomst till sökresultat via [TextFragmentAbsorber::TextFragments](../) samling.

## Se även

* Class [String](../../../system/string/)
* Class [TextFragmentAbsorber](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## TextFragmentAbsorber::TextFragmentAbsorber(const System::String\&, const System::SharedPtr\<Aspose::Pdf::Text::TextEditOptions\>\&) constructor


Initierar en ny instans av klassen [TextFragmentAbsorber](../) för den angivna textfrasen och alternativ för textredigering.

```cpp
Aspose::Pdf::Text::TextFragmentAbsorber::TextFragmentAbsorber(const System::String &phrase, const System::SharedPtr<Aspose::Pdf::Text::TextEditOptions> &textEditOptions)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| phrase | const System::String\& | Fras som [TextFragmentAbsorber](../) söker efter |
| textEditOptions | const System::SharedPtr\<Aspose::Pdf::Text::TextEditOptions\>\& | [Text](../../) redigeringsalternativ (Tillåter att aktivera vissa redigeringsfunktioner). |
## Anmärkningar


Utför textsökning av den angivna frasen och ger åtkomst till sökresultat via [TextFragmentAbsorber::TextFragments](../) samling.

## Se även

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [TextEditOptions](../../texteditoptions/)
* Class [TextFragmentAbsorber](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## TextFragmentAbsorber::TextFragmentAbsorber(const System::String\&, const System::SharedPtr\<Aspose::Pdf::Text::TextSearchOptions\>\&) constructor


Initierar en ny instans av [TextFragmentAbsorber](../) klassen för den angivna textfrasen och textsökningsalternativen.

```cpp
Aspose::Pdf::Text::TextFragmentAbsorber::TextFragmentAbsorber(const System::String &phrase, const System::SharedPtr<Aspose::Pdf::Text::TextSearchOptions> &textSearchOptions)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| phrase | const System::String\& | Fras som [TextFragmentAbsorber](../) söker efter |
| textSearchOptions | const System::SharedPtr\<Aspose::Pdf::Text::TextSearchOptions\>\& | [Text](../../) sökalternativ (Tillåter att aktivera vissa sökfunktioner. Till exempel, sök med reguljära uttryck) |
## Anmärkningar


Utför textsökning av den angivna frasen och ger åtkomst till sökresultat via [TextFragmentAbsorber::TextFragments](../) samling.

## Se även

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [TextSearchOptions](../../textsearchoptions/)
* Class [TextFragmentAbsorber](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## TextFragmentAbsorber::TextFragmentAbsorber(const System::String\&, const System::SharedPtr\<Aspose::Pdf::Text::TextSearchOptions\>\&, const System::SharedPtr\<Aspose::Pdf::Text::TextEditOptions\>\&) constructor


Initierar en ny instans av klassen [TextFragmentAbsorber](../) för den angivna textfrasen, sökalternativ för text och alternativ för textredigering.

```cpp
Aspose::Pdf::Text::TextFragmentAbsorber::TextFragmentAbsorber(const System::String &phrase, const System::SharedPtr<Aspose::Pdf::Text::TextSearchOptions> &textSearchOptions, const System::SharedPtr<Aspose::Pdf::Text::TextEditOptions> &textEditOptions)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| phrase | const System::String\& | Fras som [TextFragmentAbsorber](../) söker efter |
| textSearchOptions | const System::SharedPtr\<Aspose::Pdf::Text::TextSearchOptions\>\& | [Text](../../) sökalternativ (Tillåter att aktivera vissa sökfunktioner. Till exempel, sök med reguljära uttryck) |
| textEditOptions | const System::SharedPtr\<Aspose::Pdf::Text::TextEditOptions\>\& | [Text](../../) redigeringsalternativ (Tillåter att aktivera vissa redigeringsfunktioner). |
## Anmärkningar


Utför textsökning av den angivna frasen och ger åtkomst till sökresultat via [TextFragmentAbsorber::TextFragments](../) samling.

## Se även

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [TextSearchOptions](../../textsearchoptions/)
* Class [TextEditOptions](../../texteditoptions/)
* Class [TextFragmentAbsorber](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
