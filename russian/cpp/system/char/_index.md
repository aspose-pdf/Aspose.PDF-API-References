---
title: "System::Char класс"
linktitle: "Char"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Char класс. Предоставляет методы для работы с символами, представленными в виде кодовых единиц UTF-16. Это статический тип без сервисов экземпляра. Вы никогда не должны создавать его экземпляры каким-либо способом в C++."
type: docs
weight: 1300
url: /ru/cpp/system/char/
---
## Char class


Предоставляет методы для манипуляции символами, представленными в виде кодовых единиц UTF-16. Это статический тип без сервисов экземпляров. Вы никогда не должны создавать его экземпляры никаким способом.

```cpp
class Char
```

## Методы

| Метод | Описание |
| --- | --- |
| static [ConvertFromUtf32](./convertfromutf32/)(uint32_t) | Преобразует кодовую единицу UTF-32 в экземпляр класса [System::String](../string/). |
| static [ConvertToUtf32](./converttoutf32/)(char_t, char_t) | Преобразует указанную пару суррогатов UTF-16 в кодовую единицу UTF-32. |
| static [ConvertToUtf32](./converttoutf32/)(const String\&, int) | Преобразует значение символа, закодированного в UTF-16, или пары суррогатов в указанной позиции строки в кодовую единицу UTF-32. |
| static [GetNumericValue](./getnumericvalue/)(char_t) | Преобразует указанный символ UTF-16 в числовое значение двойной точности с плавающей запятой. |
| static [GetUnicodeCategory](./getunicodecategory/)(char_t) | Возвращает значение, представляющее категорию Unicode указанного символа. |
| static [IsAsciiWhiteSpace](./isasciiwhitespace/)(char_t) | Определяет, классифицируется ли указанный символ как символ пробела ASCII. |
| static [IsControl](./iscontrol/)(const char_t *, int) | Определяет, классифицируется ли символ в указанном индексе заданного буфера символов как управляющий символ Unicode. |
| static [IsControl](./iscontrol/)(char_t) | Определяет, классифицируется ли указанный символ как управляющий символ Unicode. |
| static [IsDigit](./isdigit/)(const char_t *, int) | Определяет, классифицируется ли символ в указанном индексе заданного буфера символов как десятичная цифра. |
| static [IsDigit](./isdigit/)(const String\&, const int32_t) | Определяет, классифицируется ли символ в указанном индексе заданной строки как десятичная цифра. |
| static [IsDigit](./isdigit/)(char_t) | Определяет, классифицируется ли указанный символ как десятичная цифра. |
| static [IsHighSurrogate](./ishighsurrogate/)(const String\&, int) | Определяет, является ли символ в указанном индексе заданной строки старшим суррогатом UTF-16. |
| static [IsHighSurrogate](./ishighsurrogate/)(const char_t *, int) | Определяет, является ли символ в указанном индексе заданного буфера символов старшим суррогатом. |
| static [IsHighSurrogate](./ishighsurrogate/)(char_t) | Определяет, является ли указанный символ старшим суррогатом. |
| static [IsLetter](./isletter/)(const char_t *, int) | Определяет, классифицируется ли символ в указанном индексе заданного буфера символов как буква Unicode. |
| static [IsLetter](./isletter/)(char_t) | Определяет, классифицируется ли указанный символ как буква Unicode. |
| static [IsLetterOrDigit](./isletterordigit/)(const char_t *, int) | Определяет, классифицируется ли символ в указанном индексе заданного буфера символов как буква Unicode или десятичная цифра. |
| static [IsLetterOrDigit](./isletterordigit/)(char_t) | Определяет, классифицируется ли указанный символ как буква Unicode или десятичная цифра. |
| static [IsLower](./islower/)(const char_t *, int) | Определяет, классифицируется ли символ в указанном индексе заданного буфера символов как строчная буква. |
| static [IsLower](./islower/)(char_t) | Определяет, классифицируется ли указанный символ как строчная буква. |
| static [IsLower](./islower/)(const String\&, int) | Определяет, классифицируется ли символ в указанном индексе заданной строки как строчная буква. |
| static [IsLowSurrogate](./islowsurrogate/)(const char_t *, int) | Определяет, является ли символ в указанном индексе заданного буфера символов низким суррогатом. |
| static [IsLowSurrogate](./islowsurrogate/)(char_t) | Определяет, является ли указанный символ низким суррогатом. |
| static [IsNumber](./isnumber/)(const char_t *, int) | Определяет, классифицируется ли символ в указанном индексе заданного буфера символов как число. |
| static [IsNumber](./isnumber/)(char_t) | Определяет, классифицируется ли указанный символ как число. |
| static [IsPunctuation](./ispunctuation/)(const char_t *, int) | Определяет, классифицируется ли символ в указанном индексе заданного буфера символов как символ пунктуации. |
| static [IsPunctuation](./ispunctuation/)(char_t) | Определяет, классифицируется ли указанный символ как символ пунктуации. |
| static [IsSeparator](./isseparator/)(const char_t *, int) | Определяет, является ли символ в указанном индексе в указанном буфере символов классифицированным как разделительный символ. |
| static [IsSeparator](./isseparator/)(char_t) | Определяет, является ли указанный символ классифицированным как разделительный символ. |
| static [IsSurrogate](./issurrogate/)(char_t) | Определяет, является ли указанный символ кодовой единицей суррогата UTF-16. |
| static [IsSurrogate](./issurrogate/)(const String\&, int) | Определяет, является ли символ в указанном индексе в указанной строке кодовой единицей суррогата UTF-16. |
| static [IsSurrogatePair](./issurrogatepair/)(char_t, char_t) | Определяет, являются ли два указанных символа парой суррогатов UTF-16. |
| static [IsSurrogatePair](./issurrogatepair/)(const String\&, int) | Определяет, являются ли два последовательных символа в указанном буфере символов парой суррогатов. |
| static [IsSymbol](./issymbol/)(const char_t *, int) | Определяет, является ли символ в указанном индексе в указанном буфере символов классифицированным как символ. |
| static [IsSymbol](./issymbol/)(char_t) | Определяет, является ли указанный символ классифицированным как символ. |
| static [IsUpper](./isupper/)(const String\&, int) | Определяет, является ли символ в указанном индексе в указанной строке классифицированным как заглавная буква. |
| static [IsUpper](./isupper/)(const char_t *, int) | Определяет, является ли символ в указанном индексе в указанном буфере символов классифицированным как заглавная буква. |
| static [IsUpper](./isupper/)(char_t) | Определяет, является ли указанный символ классифицированным как заглавная буква. |
| static [IsWhiteSpace](./iswhitespace/)(const char_t *, int) | Определяет, является ли символ в указанном индексе в указанном буфере символов классифицированным как пробельный символ. |
| static [IsWhiteSpace](./iswhitespace/)(char_t) | Определяет, является ли указанный символ классифицированным как пробельный символ. |
| static [IsWhiteSpace](./iswhitespace/)(const String\&, int) | Определяет, является ли символ в указанном индексе в указанной строке классифицированным как пробельный символ. |
| static [Parse](./parse/)(const String\&) | Преобразует первый и единственный символ указанной строки в значение типа char_t. |
| static [ToLower](./tolower/)(char_t) | Преобразует указанный символ в нижний регистр. |
| static [ToLower](./tolower/)(char_t, const SharedPtr\<Globalization::CultureInfo\>\&) | Преобразует указанный символ в нижний регистр. |
| static [ToLowerInvariant](./tolowerinvariant/)(char_t) | Преобразует указанный символ в нижний регистр. |
| static [ToUpper](./toupper/)(char_t) | Преобразует указанный символ в верхний регистр. |
| static [ToUpper](./toupper/)(char_t, const SharedPtr\<Globalization::CultureInfo\>\&) | Преобразует указанный символ в верхний регистр. |
| static [ToUpperInvariant](./toupperinvariant/)(char_t) | Преобразует указанный символ в верхний регистр. |
| static [TryParse](./tryparse/)(const System::String\&, char_t\&) | Пытается преобразовать строку, состоящую из одного символа, в символ UTF-16. Функция завершается успешно только когда входная строка не равна null и имеет длину ровно один символ. |
## См. также

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
