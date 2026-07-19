---
title: "Метод System::Text::RegularExpressions::Regex::Replace"
linktitle: "Заменить"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Text::RegularExpressions::Regex::Replace. Заменяет все совпадения регулярного выражения в строке строкой‑заменой в C++."
type: docs
weight: 800
url: /ru/cpp/system.text.regularexpressions/regex/replace/
---
## Regex::Replace(const String\&, const char_t *) method


Заменяет все совпадения regex в строке строкой‑заменой.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const char_t *replacement)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const String\& | Входная строка. |
| замена | const char_t * | Строка замены. |

### ReturnValue

Входная строка, в которой все совпадения регулярного выражения заменены строкой‑заменой.

## См. также

* Class [String](../../../system/string/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PDF for C++](../../../)
## Regex::Replace(const String\&, const MatchEvaluator\&) method


Заменяет все совпадения в строке строками‑заменами, сгенерированными делегатом.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const MatchEvaluator &evaluator)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const String\& | Входная строка. |
| оценщик | const MatchEvaluator\& | Делегат для генерации строк‑замен на основе совпадений. |

### ReturnValue

Входные строки со всеми заменёнными совпадениями.

## См. также

* Class [String](../../../system/string/)
* Typedef [MatchEvaluator](../../matchevaluator/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PDF for C++](../../../)
## Regex::Replace(const String\&, const MatchEvaluator\&, int) method


Заменяет все совпадения в строке строками‑заменами, сгенерированными делегатом.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const MatchEvaluator &evaluator, int count)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const String\& | Входная строка. |
| оценщик | const MatchEvaluator\& | Делегат для генерации строк‑замен на основе совпадений. |
| count | int | Ограничение количества замен. |

### ReturnValue

Входные строки со всеми заменёнными совпадениями.

## См. также

* Class [String](../../../system/string/)
* Typedef [MatchEvaluator](../../matchevaluator/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PDF for C++](../../../)
## Regex::Replace(const String\&, const MatchEvaluator\&, int, int) method


Заменяет все совпадения в строке строками‑заменами, сгенерированными делегатом.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const MatchEvaluator &evaluator, int count, int startat)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const String\& | Входная строка. |
| оценщик | const MatchEvaluator\& | Делегат для генерации строк‑замен на основе совпадений. |
| count | int | Ограничение количества замен. |
| startat | int | [Index](../../../system/index/) в строке ввода, с которой начинать замену. |

### ReturnValue

Входные строки со всеми заменёнными совпадениями.

## См. также

* Class [String](../../../system/string/)
* Typedef [MatchEvaluator](../../matchevaluator/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PDF for C++](../../../)
## Regex::Replace(const String\&, const String\&) method


Заменяет все совпадения regex в строке строкой‑заменой.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &replacement)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const String\& | Входная строка. |
| замена | const String\& | Строка замены. |

### ReturnValue

Входная строка, в которой все совпадения регулярного выражения заменены строкой‑заменой.

## См. также

* Class [String](../../../system/string/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PDF for C++](../../../)
## Regex::Replace(const String\&, const String\&, int) method


Заменяет подстроки в строке. Не реализовано.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &replacement, int count)
```

## См. также

* Class [String](../../../system/string/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PDF for C++](../../../)
## Regex::Replace(const String\&, const String\&, int, int) method


Заменяет подстроки в строке. Не реализовано.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &replacement, int count, int startat)
```

## См. также

* Class [String](../../../system/string/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PDF for C++](../../../)
## Regex::Replace(const String\&, const char_t *, const char_t *) method


Заменяет все совпадения regex в строке строкой‑заменой.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const char_t *pattern, const char_t *replacement)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const String\& | Входная строка. |
| pattern | const char_t * | [Regex](../) шаблон. |
| замена | const char_t * | Строка замены. |

### ReturnValue

Входная строка, в которой все совпадения регулярного выражения заменены строкой‑заменой.

## См. также

* Class [String](../../../system/string/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PDF for C++](../../../)
## Regex::Replace(const String\&, const String\&, const char_t *) method


Заменяет все совпадения regex в строке строкой‑заменой.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const char_t *replacement)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const String\& | Входная строка. |
| pattern | const String\& | [Regex](../) шаблон. |
| замена | const char_t * | Строка замены. |

### ReturnValue

Входная строка, в которой все совпадения регулярного выражения заменены строкой‑заменой.

## См. также

* Class [String](../../../system/string/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PDF for C++](../../../)
## Regex::Replace(const String\&, const String\&, const MatchEvaluator\&) method


Заменяет совпадения regex.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const MatchEvaluator &evaluator)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const String\& | Входная строка. |
| шаблон | const String\& | Шаблон Regexp. |
| оценщик | const MatchEvaluator\& | Делегат для генерации строки замены для каждого совпадения. |

### ReturnValue

[String](../../../system/string/) with all matches replaced.

## См. также

* Class [String](../../../system/string/)
* Typedef [MatchEvaluator](../../matchevaluator/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PDF for C++](../../../)
## Regex::Replace(const String\&, const String\&, const MatchEvaluator\&, RegexOptions) method


Заменяет все совпадения в строке строками‑заменами, сгенерированными делегатом (статическая функция).

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const MatchEvaluator &evaluator, RegexOptions options)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const String\& | Входная строка. |
| pattern | const String\& | [Regex](../) шаблон. |
| оценщик | const MatchEvaluator\& | Делегат для генерации строк‑замен на основе совпадений. |
| options | RegexOptions | [Regex](../) параметры. |

### ReturnValue

Входные строки со всеми заменёнными совпадениями.

## См. также

* Class [String](../../../system/string/)
* Typedef [MatchEvaluator](../../matchevaluator/)
* Enum [RegexOptions](../../regexoptions/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PDF for C++](../../../)
## Regex::Replace(const String\&, const String\&, const String\&) method


Заменяет совпадения regex.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const String &replacement)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const String\& | Входная строка. |
| шаблон | const String\& | Шаблон Regexp. |
| замена | const String\& | Строка замены. |

### ReturnValue

[String](../../../system/string/) with all matches replaced.

## См. также

* Class [String](../../../system/string/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PDF for C++](../../../)
## Regex::Replace(const String\&, const String\&, const String\&, RegexOptions) method


Заменяет все совпадения regex в строке строкой‑заменой.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const String &replacement, RegexOptions options)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const String\& | Входная строка. |
| pattern | const String\& | [Regex](../) шаблон. |
| замена | const String\& | Строка замены. |
| options | RegexOptions | [Regex](../) параметры. |

### ReturnValue

Входная строка, в которой все совпадения регулярного выражения заменены строкой‑заменой.

## См. также

* Class [String](../../../system/string/)
* Enum [RegexOptions](../../regexoptions/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PDF for C++](../../../)
