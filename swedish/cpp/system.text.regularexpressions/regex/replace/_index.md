---
title: "System::Text::RegularExpressions::Regex::Replace metod"
linktitle: "Ersätt"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Text::RegularExpressions::Regex::Replace metod. Ersätter alla regex‑matchningar i en sträng med ersättningssträngen i C++."
type: docs
weight: 800
url: /sv/cpp/system.text.regularexpressions/regex/replace/
---
## Regex::Replace(const String\&, const char_t *) method


Ersätter alla träffar av regex i strängen med ersättningssträngen.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const char_t *replacement)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inmatning | const String\& | Indata-sträng. |
| ersättning | const char_t * | Ersättningssträng. |

### ReturnValue

Indatasträng med alla regex‑matchningar ersatta med ersättningssträngen.

## Se även

* Class [String](../../../system/string/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PDF for C++](../../../)
## Regex::Replace(const String\&, const MatchEvaluator\&) method


Ersätter alla träffar i strängen med delegatgenererade ersättningssträngar.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const MatchEvaluator &evaluator)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inmatning | const String\& | Indata-sträng. |
| utvärderare | const MatchEvaluator\& | Delegat för att generera ersättningssträngar baserat på träffar. |

### ReturnValue

Indatasträngar med alla träffar ersatta.

## Se även

* Class [String](../../../system/string/)
* Typedef [MatchEvaluator](../../matchevaluator/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PDF for C++](../../../)
## Regex::Replace(const String\&, const MatchEvaluator\&, int) method


Ersätter alla träffar i strängen med delegatgenererade ersättningssträngar.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const MatchEvaluator &evaluator, int count)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inmatning | const String\& | Indata-sträng. |
| utvärderare | const MatchEvaluator\& | Delegat för att generera ersättningssträngar baserat på träffar. |
| count | int | Gräns för antal ersättningar. |

### ReturnValue

Indatasträngar med alla träffar ersatta.

## Se även

* Class [String](../../../system/string/)
* Typedef [MatchEvaluator](../../matchevaluator/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PDF for C++](../../../)
## Regex::Replace(const String\&, const MatchEvaluator\&, int, int) method


Ersätter alla träffar i strängen med delegatgenererade ersättningssträngar.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const MatchEvaluator &evaluator, int count, int startat)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inmatning | const String\& | Indata-sträng. |
| utvärderare | const MatchEvaluator\& | Delegat för att generera ersättningssträngar baserat på träffar. |
| count | int | Gräns för antal ersättningar. |
| startat | int | [Index](../../../system/index/) i indatasträngen för att starta ersättningen vid. |

### ReturnValue

Indatasträngar med alla träffar ersatta.

## Se även

* Class [String](../../../system/string/)
* Typedef [MatchEvaluator](../../matchevaluator/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PDF for C++](../../../)
## Regex::Replace(const String\&, const String\&) method


Ersätter alla träffar av regex i strängen med ersättningssträngen.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &replacement)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inmatning | const String\& | Indata-sträng. |
| ersättning | const String\& | Ersättningssträng. |

### ReturnValue

Indatasträng med alla regex‑matchningar ersatta med ersättningssträngen.

## Se även

* Class [String](../../../system/string/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PDF for C++](../../../)
## Regex::Replace(const String\&, const String\&, int) method


Ersätter delsträngar i strängen. Ej implementerat.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &replacement, int count)
```

## Se även

* Class [String](../../../system/string/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PDF for C++](../../../)
## Regex::Replace(const String\&, const String\&, int, int) method


Ersätter delsträngar i strängen. Ej implementerat.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &replacement, int count, int startat)
```

## Se även

* Class [String](../../../system/string/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PDF for C++](../../../)
## Regex::Replace(const String\&, const char_t *, const char_t *) method


Ersätter alla träffar av regex i strängen med ersättningssträngen.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const char_t *pattern, const char_t *replacement)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inmatning | const String\& | Indata-sträng. |
| pattern | const char_t * | [Regex](../) mönster. |
| ersättning | const char_t * | Ersättningssträng. |

### ReturnValue

Indatasträng med alla regex‑matchningar ersatta med ersättningssträngen.

## Se även

* Class [String](../../../system/string/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PDF for C++](../../../)
## Regex::Replace(const String\&, const String\&, const char_t *) method


Ersätter alla träffar av regex i strängen med ersättningssträngen.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const char_t *replacement)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inmatning | const String\& | Indata-sträng. |
| pattern | const String\& | [Regex](../) mönster. |
| ersättning | const char_t * | Ersättningssträng. |

### ReturnValue

Indatasträng med alla regex‑matchningar ersatta med ersättningssträngen.

## Se även

* Class [String](../../../system/string/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PDF for C++](../../../)
## Regex::Replace(const String\&, const String\&, const MatchEvaluator\&) method


Ersätter regex-träffar.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const MatchEvaluator &evaluator)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inmatning | const String\& | Indata-sträng. |
| mönster | const String\& | Regexp-mönster. |
| utvärderare | const MatchEvaluator\& | Delegat för att generera ersättningssträng för varje träff. |

### ReturnValue

[String](../../../system/string/) with all matches replaced.

## Se även

* Class [String](../../../system/string/)
* Typedef [MatchEvaluator](../../matchevaluator/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PDF for C++](../../../)
## Regex::Replace(const String\&, const String\&, const MatchEvaluator\&, RegexOptions) method


Ersätter alla träffar i strängen med delegatgenererade ersättningssträngar (statisk funktion).

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const MatchEvaluator &evaluator, RegexOptions options)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inmatning | const String\& | Indata-sträng. |
| pattern | const String\& | [Regex](../) mönster. |
| utvärderare | const MatchEvaluator\& | Delegat för att generera ersättningssträngar baserat på träffar. |
| options | RegexOptions | [Regex](../) alternativ. |

### ReturnValue

Indatasträngar med alla träffar ersatta.

## Se även

* Class [String](../../../system/string/)
* Typedef [MatchEvaluator](../../matchevaluator/)
* Enum [RegexOptions](../../regexoptions/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PDF for C++](../../../)
## Regex::Replace(const String\&, const String\&, const String\&) method


Ersätter regex-träffar.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const String &replacement)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inmatning | const String\& | Indata-sträng. |
| mönster | const String\& | Regexp-mönster. |
| ersättning | const String\& | Ersättningssträng. |

### ReturnValue

[String](../../../system/string/) with all matches replaced.

## Se även

* Class [String](../../../system/string/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PDF for C++](../../../)
## Regex::Replace(const String\&, const String\&, const String\&, RegexOptions) method


Ersätter alla träffar av regex i strängen med ersättningssträngen.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const String &replacement, RegexOptions options)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inmatning | const String\& | Indata-sträng. |
| pattern | const String\& | [Regex](../) mönster. |
| ersättning | const String\& | Ersättningssträng. |
| options | RegexOptions | [Regex](../) alternativ. |

### ReturnValue

Indatasträng med alla regex‑matchningar ersatta med ersättningssträngen.

## Se även

* Class [String](../../../system/string/)
* Enum [RegexOptions](../../regexoptions/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PDF for C++](../../../)
