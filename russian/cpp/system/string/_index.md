---
title: "System::String класс"
linktitle: "String"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::String класс. Класс String используется по всей библиотеке. Является заменой C# System.String при переводе кода. По причинам оптимизации не считается подклассом Object. Этот тип должен быть выделен в стеке и передаваться в функции по значению или по ссылке. Никогда не используйте класс System::SmartPtr для управления объектами этого типа в C++."
type: docs
weight: 6100
url: /ru/cpp/system/string/
---
## String class


[String](./) class used across the library. Is a substitute for C# [System.String](./) when translating code. For optimization reasons, isn't considered an [Object](../object/) subclass. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](../smartptr/) class to manage objects of this type.

```cpp
class String
```

## Методы

| Метод | Описание |
| --- | --- |
| [begin](./begin/)() const | Возвращает указатель на начало фактического буфера строки. Никогда ничего не переаллочирует. Не гарантирует, что буфер будет нуль-терминирован. |
| [Clone](./clone/)() const | Создаёт копию текущей строки. |
| static [Compare](./compare/)(const String\&, int, const String\&, int, int, bool) | Less-equal-greater-compares два подстрока. |
| static [Compare](./compare/)(const String\&, int, const String\&, int, int, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) | Less-equal-greater-compares два подстрока. |
| static [Compare](./compare/)(const String\&, const String\&, System::StringComparison) | Less-equal-greater-compares два строки. |
| static [Compare](./compare/)(const String\&, int, const String\&, int, int, System::StringComparison) | Less-equal-greater-compares два строки. |
| static [Compare](./compare/)(const String\&, const String\&, bool) | Less-equal-greater-compares два строки. |
| static [Compare](./compare/)(const String\&, const String\&, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) | Less-equal-greater-compares два строки. |
| static [CompareOrdinal](./compareordinal/)(const String\&, const String\&) | Less-equal-greater-compares два строки с использованием ординального режима. |
| static [CompareOrdinal](./compareordinal/)(const String\&, int, const String\&, int, int) | Less-equal-greater-compares два строки с использованием ординального режима. |
| [CompareTo](./compareto/)(const String\&) const | Сравнивает два строки в стиле 'less-equals-more'. Использует текущую культуру. |
| static [Concat](./concat/)(const ArrayPtr\<String\>\&) | Конкатенирует строки. |
| static [Concat](./concat/)(const String\&, const String\&) | Конкатенирует строки. |
| static [Concat](./concat/)(const String\&, const String\&, const String\&) | Конкатенирует строки. |
| static [Concat](./concat/)(const String\&, const String\&, const String\&, const String\&) | Конкатенирует строки. |
| [Contains](./contains/)(const String\&) const | Проверяет, является ли str подстрокой текущей строки. |
| [Contains](./contains/)(char16_t) const | Проверяет, содержит ли строка заданный символ. |
| static [Copy](./copy/)(const String\&) | Создаёт копию строки. |
| [CopyTo](./copyto/)(int, const ArrayPtr\<char_t\>\&, int, int) const | Копирует символы строки в существующие элементы массива. Изменение размера не производится. |
| [end](./end/)() const | Возвращает указатель на конец фактического буфера строки. Никогда ничего не переаллочирует. Не гарантирует, что буфер будет нуль-терминирован. |
| [EndsWith](./endswith/)(const String\&) const | Проверяет, заканчивается ли строка указанной подстрокой. |
| [EndsWith](./endswith/)(const String\&, System::StringComparison) const | Проверяет, заканчивается ли строка указанной подстрокой. |
| [EndsWith](./endswith/)(const String\&, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) const | Проверяет, заканчивается ли строка указанной подстрокой. |
| [Equals](./equals/)(const String\&, System::StringComparison) const | [String](./) сравнение на равенство. Поддерживаются несколько режимов, предоставляемых перечислением [StringComparison](../stringcomparison/). |
| [Equals](./equals/)(const String\&) const | [String](./) сравнение на равенство. Использует режим сравнения [System::StringComparison::Ordinal](../stringcomparison/). |
| static [Equals](./equals/)(const String\&, const String\&) | Сравнивает два строки на равенство, используя режим сравнения Ordial. |
| static [Equals](./equals/)(const String\&, const String\&, System::StringComparison) | Сравнивает два строки на равенство. |
| [FastToAscii](./fasttoascii/)(char, int) const | Пытается преобразовать [String](./) в ASCII‑строку. |
| static [Format](./format/)(const SharedPtr\<IFormatProvider\>\&, const String\&, const Args\&...) | Форматирует строку в стиле C#. |
| static [Format](./format/)(std::nullptr_t, const String\&, const Args\&...) | Форматирует строку в стиле C#. |
| static [Format](./format/)(std::nullptr_t, const char16_t(&), const Args\&...) | Форматирует строку в стиле C#. |
| static [Format](./format/)(const String\&, const Args\&...) | Форматирует строку в стиле C#. |
| static [Format](./format/)(const String\&, const System::ArrayPtr\<T\>\&) | Форматирует строку в стиле C#. |
| static [FromAscii](./fromascii/)(const char *) | Создаёт [String](./) из ASCII‑строки. |
| static [FromAscii](./fromascii/)(const char *, int) | Создаёт [String](./) из ASCII‑строки. |
| static [FromAscii](./fromascii/)(const std::string\&) | Создаёт [String](./) из ASCII‑строки. |
| static [FromUtf16](./fromutf16/)(const std::u16string\&) | Создаёт [String](./) из строки utf16. |
| static [FromUtf32](./fromutf32/)(const uint32_t *, int32_t) | Создаёт [String](./) из строки utf32. |
| static [FromUtf8](./fromutf8/)(const char *) | Создаёт [String](./) из строки utf8. |
| static [FromUtf8](./fromutf8/)(const char *, int) | Создаёт [String](./) из строки utf8. |
| static [FromUtf8](./fromutf8/)(const uint8_t *) | Создаёт [String](./) из строки utf8. |
| static [FromUtf8](./fromutf8/)(const std::string\&) | Создаёт [String](./) из строки utf8. |
| static [FromWCS](./fromwcs/)(const std::wstring\&) | Создаёт [String](./) из widestring. |
| [get_Length](./get_length/)() const | Получает длину строки. |
| [GetHashCode](./gethashcode/)() const | Вычисляет хеш содержащейся строки. Реализовано в ICU, не совпадает с хешами в C#. |
| [IndexOf](./indexof/)(const String\&, System::StringComparison) const | Прямой поиск подстроки. |
| [IndexOf](./indexof/)(char_t, int) const | Прямой поиск символа. |
| [IndexOf](./indexof/)(char_t, int, int) const | Прямой поиск символа в подстроке. |
| [IndexOf](./indexof/)(const String\&, int) const | Прямой поиск подстроки. |
| [IndexOf](./indexof/)(const String\&, int, System::StringComparison) const | Прямой поиск подстроки. |
| [IndexOf](./indexof/)(const String\&, int, int, System::StringComparison) const | Прямой поиск подстроки. |
| [IndexOf](./indexof/)(const String\&, int, int) const | Прямой поиск подстроки. |
| [IndexOfAny](./indexofany/)(char_t, int) const | Прямой поиск символа. |
| [IndexOfAny](./indexofany/)(const String\&, int) const | Соответственно ищет все символы строки str в данном объекте. Если найден первый символ, возвращается его позиция, иначе ищется второй и так далее. |
| [IndexOfAny](./indexofany/)(const ArrayPtr\<char_t\>\&) const | Ищет любой из переданных символов во всей строке. Сравнивает первый символ строки со всеми символами в anyOf, затем сравнивает второй и так далее. Возвращает индекс первого символа, совпавшего с любым из целевых символов. |
| [IndexOfAny](./indexofany/)(const ArrayPtr\<char_t\>\&, int32_t) const | Ищет любой из переданных символов в подстроке. Сравнивает первый символ строки со всеми символами в anyOf, затем сравнивает второй и так далее. Возвращает индекс первого символа, совпавшего с любым из целевых символов. |
| [IndexOfAny](./indexofany/)(const ArrayPtr\<char_t\>\&, int32_t, int32_t) const | Ищет любой из переданных символов в подстроке. Сравнивает первый символ строки со всеми символами в anyOf, затем сравнивает второй и так далее. Возвращает индекс первого символа, совпавшего с любым из целевых символов. |
| [Insert](./insert/)(int, const String\&) const | Вставляет подстроку в указанную позицию. |
| [Is](./is/)(const System::TypeInfo\&) const | Проверяет, является ли объект строки типом, указанным в переданном [TypeInfo](../typeinfo/). |
| [IsAsciiString](./isasciistring/)() const | Указывает, содержит ли [String](./) только ASCII‑символы. |
| [IsEmpty](./isempty/)() const | Проверяет, что строка не null и пуста. |
| [IsNormalized](./isnormalized/)(System::Text::NormalizationForm) const | Проверяет, нормализована ли Unicode‑строка с использованием указанной формы нормализации. |
| [IsNull](./isnull/)() const | Проверяет, считается ли строка null. [String](./) считается null только если она создана через конструктор [String()](./string/), перемещена, скопирована или присвоена из null‑строки, либо был вызван метод [reset()](./reset/). |
| [IsNullOrEmpty](./isnullorempty/)() const | Проверяет, пустая ли строка или считается ли она null. |
| static [IsNullOrEmpty](./isnullorempty/)(const String\&) | Проверяет, является ли переданная строка null или пустой. |
| static [IsNullOrWhiteSpace](./isnullorwhitespace/)(const String\&) | Указывает, является ли указанная строка null, пустой или состоит только из пробельных символов. |
| static [Join](./join/)(const String\&, const ArrayPtr\<String\>\&, int, int) | Объединяет массив, используя строку в качестве разделителя. |
| static [Join](./join/)(const String\&, const System::Details::ArrayView\<String\>\&, int, int) | Объединяет массив, используя строку в качестве разделителя. |
| static [Join](./join/)(const String\&, const SharedPtr\<System::Collections::Generic::IEnumerable\<String\>\>\&) | Объединяет массив, используя строку в качестве разделителя. |
| static [Join](./join/)(const String\&, const ArrayPtr\<SharedPtr\<Object\>\>\&) | Объединяет массив, используя строку в качестве разделителя. |
| [LastIndexOf](./lastindexof/)(const String\&, int) const | Обратный поиск подстроки. |
| [LastIndexOf](./lastindexof/)(const String\&, System::StringComparison) const | Обратный поиск подстроки. |
| [LastIndexOf](./lastindexof/)(const String\&, int, System::StringComparison) const | Обратный поиск подстроки. |
| [LastIndexOf](./lastindexof/)(const String\&, int, int, StringComparison) const | Обратный поиск подстроки. |
| [LastIndexOf](./lastindexof/)(char_t) const | Обратный поиск символа. |
| [LastIndexOf](./lastindexof/)(char_t, int32_t) const | Обратный поиск символа. |
| [LastIndexOf](./lastindexof/)(char_t, int32_t, int32_t) const | Обратный поиск символа. |
| [LastIndexOfAny](./lastindexofany/)(const ArrayPtr\<char_t\>\&) const | Ищет любой из переданных символов по всей строке в обратном порядке. Сравнивает последний символ строки со всеми символами в anyOf, затем сравнивает предыдущий и так далее. Возвращает индекс первого найденного совпадения. |
| [LastIndexOfAny](./lastindexofany/)(const ArrayPtr\<char_t\>\&, int32_t) const | Ищет любой из переданных символов в подстроке в обратном порядке. Сравнивает последний символ строки со всеми символами в anyOf, затем сравнивает предыдущий и так далее. Возвращает индекс первого найденного совпадения. |
| [LastIndexOfAny](./lastindexofany/)(const ArrayPtr\<char_t\>\&, int32_t, int32_t) const | Ищет любой из переданных символов в подстроке в обратном порядке. Сравнивает последний символ строки со всеми символами в anyOf, затем сравнивает предыдущий и так далее. Возвращает индекс первого найденного совпадения. |
| [Normalize](./normalize/)(System::Text::NormalizationForm) const | Нормализует Unicode-строку, используя указанную форму нормализации. |
| [operator ReadOnlySpan< char16_t >](./operatorreadonlyspan_char16_t_/)() const | Преобразует строку в неизменяемый span. |
| [operator!=](./operator!=/)(const String\&) const | Оператор сравнения на неравенство. |
| [operator!=](./operator!=/)(std::nullptr_t) const | Проверяет, что строка не null. Применяет ту же логику, что и вызов [IsNull()](./isnull/). |
| [operator+](./operator+/)(const String\&) const | [String](./) оператор конкатенации. |
| [operator+](./operator+/)(const T\&) const | [String](./) конкатенация со строковым литералом или указателем на строку символов. |
| [operator+](./operator+/)(char_t) const | Добавляет символ в конец строки. |
| [operator+](./operator+/)(int) const | Добавляет строковое представление целочисленного значения в конец строки. |
| [operator+](./operator+/)(uint32_t) const | Добавляет строковое представление беззнакового целого значения в конец строки. |
| [operator+](./operator+/)(double) const | Добавляет строковое представление числа с плавающей точкой в конец строки. |
| [operator+](./operator+/)(int64_t) const | Добавляет строковое представление целочисленного значения в конец строки. |
| [operator+](./operator+/)(const T\&) const | Добавляет строковое представление объекта ссылочного типа в конец строки. |
| [operator+](./operator+/)(const T\&) const | Добавляет строковое представление объекта ссылочного типа в конец строки. |
| [operator+](./operator+/)(T) const | Добавляет строковое представление логического значения в конец строки. |
| [operator+=](./operator+=/)(char_t) | Оператор присваивания с конкатенацией. |
| [operator+=](./operator+=/)(const String\&) | Оператор присваивания с конкатенацией. |
| [operator+=](./operator+=/)(double) | Оператор присваивания с конкатенацией. |
| [operator+=](./operator+=/)(uint8_t) | Оператор присваивания с конкатенацией. |
| [operator+=](./operator+=/)(int16_t) | Оператор присваивания с конкатенацией. |
| [operator+=](./operator+=/)(uint16_t) | Оператор присваивания с конкатенацией. |
| [operator+=](./operator+=/)(int32_t) | Оператор присваивания с конкатенацией. |
| [operator+=](./operator+=/)(uint32_t) | Оператор присваивания с конкатенацией. |
| [operator+=](./operator+=/)(int64_t) | Оператор присваивания с конкатенацией. |
| [operator+=](./operator+=/)(uint64_t) | Оператор присваивания с конкатенацией. |
| [operator+=](./operator+=/)(T) | Оператор присваивания с конкатенацией. |
| [operator<](./operator_/)(const String\&) const | Сравнивает строки по порядку. |
| [operator=](./operator=/)(const String\&) | Оператор присваивания. |
| [operator=](./operator=/)(String\&&) | Оператор перемещающего присваивания. |
| [operator==](./operator==/)(const String\&) const | Оператор сравнения на равенство. |
| [operator==](./operator==/)(std::nullptr_t) const | Проверяет, является ли строка null. Применяет ту же логику, что и вызов [IsNull()](./isnull/). |
| [operator>](./operator_/)(const String\&) const | Сравнивает строки по порядку. |
| [operator[]](./operator[]/)(int) const | Получает символ в указанной позиции. |
| [PadLeft](./padleft/)(int, char_t) const | Добавляет заполнение слева от исходной строки. |
| [PadRight](./padright/)(int, char_t) const | Добавляет заполнение справа от исходной строки. |
| [rbegin](./rbegin/)() const | Возвращает обратный итератор к последнему символу (если он есть) фактического буфера строки. |
| [Remove](./remove/)(int32_t, int32_t) const | Извлекает всё, кроме подстроки, из текущей строки. |
| [rend](./rend/)() const | Возвращает обратный итератор к позиции перед первым символом (если он есть) фактического буфера строки. |
| [Replace](./replace/)(char_t, char_t) const | Заменяет все вхождения символа в строке. |
| [Replace](./replace/)(const String\&, const String\&) const | Заменяет все вхождения lookup в этой строке. |
| [reset](./reset/)() | Устанавливает строку в null. Аналогично выражению 'string_variable_name = null' в C#. |
| [SetCharAt](./setcharat/)(int, char_t) | Устанавливает символ в указанной позиции. |
| [Split](./split/)(char_t, StringSplitOptions) const | Разбивает строку по символу. |
| [Split](./split/)(char_t, int32_t, StringSplitOptions) const | Разбивает строку по символу. |
| [Split](./split/)(char_t, char_t, StringSplitOptions) const | Разбивает строку по одному из двух символов. |
| [Split](./split/)(const ArrayPtr\<char_t\>\&, StringSplitOptions) const | Разбивает строку по одному из указанных символов. |
| [Split](./split/)(const ArrayPtr\<char_t\>\&, int32_t, StringSplitOptions) const | Разбивает строку по одному из указанных символов. |
| [Split](./split/)(const String\&, StringSplitOptions) const | Разбивает строку по подстроке. |
| [Split](./split/)(const String\&, int, StringSplitOptions) const | Разбивает строку по подстроке. |
| [Split](./split/)(const ArrayPtr\<String\>\&, StringSplitOptions) const | Разбивает строку по подстроке. |
| [Split](./split/)(const ArrayPtr\<String\>\&, int, StringSplitOptions) const | Разбивает строку по подстроке. В настоящее время поддерживает массив разделителей из нуля или одного элемента. |
| [StartsWith](./startswith/)(const String\&) const | Проверяет, начинается ли строка с указанной подстроки. |
| [StartsWith](./startswith/)(const String\&, System::StringComparison) const | Проверяет, начинается ли строка с указанной подстроки. |
| [StartsWith](./startswith/)(const String\&, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) const | Проверяет, начинается ли строка с указанной подстроки. |
| [String](./string/)() | Конструктор по умолчанию. Создаёт объект строки, который считается null. |
| [String](./string/)(T\&, typename std::enable_if\<IsStringLiteral\<T, char16_t\>::value\>::type *) | Создаёт строку на основе строкового литерала. Считает литерал нуль-терминированной строкой, вычисляет длину целевой строки на основе размера литерала. |
| [String](./string/)(const T\&, typename std::enable_if\<IsStringPointer\<T, char16_t\>::value\>::type *) | Создаёт строку на основе указателя на строку символов. Рассматривает указываемую строку как нуль-терминированную, вычисляет длину целевой строки на основе нулевого символа. |
| explicit [String](./string/)(T\&, typename std::enable_if\<IsStringLiteral\<T, char\>::value\>::type *) | Создаёт строку на основе строкового литерала. Считает литерал нуль-терминированной строкой в UTF8, вычисляет длину целевой строки на основе размера литерала. |
| explicit [String](./string/)(const T\&, typename std::enable_if\<IsStringPointer\<T, char\>::value\>::type *) | Создаёт строку на основе указателя на строку символов. Рассматривает указываемую строку как нуль-терминированную в UTF8, вычисляет длину целевой строки на основе нулевого символа. |
| [String](./string/)(const char16_t *, int) | Создаёт строку из указателя на строку символов и явной длины. |
| [String](./string/)(const ReadOnlySpan\<char16_t\>\&) | Инициализирует новый экземпляр класса [System.String](./) Unicode‑символами, указанными в заданном только для чтения span. |
| [String](./string/)(const char *, int) | Создаёт строку из указателя на строку символов и явной длины. |
| [String](./string/)(const char16_t *, int, int) | Создаёт строку из указателя на строку символов, начиная с позиции, используя длину. |
| explicit [String](./string/)(const char16_t, int) | Заполняющий конструктор. |
| [String](./string/)(const T\&, typename std::enable_if\<std::is_same\<T, std::nullptr_t\>::value\>::type *) | Конструктор nullptr. Объявлен как шаблон для разрешения приоритетов с другими шаблонными конструкторами. |
| explicit [String](./string/)(T\&, typename std::enable_if\<IsStringLiteral\<T, wchar_t\>::value\>::type *) | Создаёт строку на основе литерала широких строк. Считает литерал нуль-терминированной строкой, вычисляет длину целевой строки на основе размера литерала. Преобразование из wchar_t занимает много времени на некоторых платформах, поэтому не допускаются неявные преобразования. |
| explicit [String](./string/)(const T\&, typename std::enable_if\<IsStringPointer\<T, wchar_t\>::value\>::type *) | Создаёт строку на основе указателя на строку широких символов. Рассматривает указанную строку как нуль-терминированную, вычисляет длину целевой строки на основе нулевого символа. Преобразование из wchar_t занимает много времени на некоторых платформах, поэтому не допускаются неявные преобразования. |
| explicit [String](./string/)(const wchar_t *, int) | Создаёт строку из указателя на строку широких символов и явной длины. Преобразование из wchar_t занимает много времени на некоторых платформах, поэтому не допускаются неявные преобразования. |
| explicit [String](./string/)(const wchar_t, int) | Заполняющий конструктор. Преобразование из wchar_t занимает много времени на некоторых платформах, поэтому не допускаются неявные преобразования. |
| [String](./string/)(const String\&) | Конструктор копирования. |
| [String](./string/)(String\&&) | Конструктор перемещения. |
| [String](./string/)(const ArrayPtr\<char16_t\>\&) | Преобразует весь массив символов в строку. |
| [String](./string/)(const ArrayPtr\<char16_t\>\&, int, int) | Преобразует поддиапазон массива символов в строку. Если параметры выходят за границы массива, создаётся пустая строка. |
| explicit [String](./string/)(const codeporting_icu::UnicodeString\&) | Оборачивает UnicodeString в [String](./). |
| explicit [String](./string/)(codeporting_icu::UnicodeString\&&) | Конструктор перемещения. |
| explicit [String](./string/)(const std::wstring\&) | Создаёт [String](./) из widestring. |
| explicit [String](./string/)(const std::u16string\&) | Создаёт [String](./) из строки utf16. |
| explicit [String](./string/)(const std::string\&) | Создаёт [String](./) из строки std::string, представленной в формате UTF-8. |
| explicit [String](./string/)(const std::u32string\&) | Создаёт [String](./) из строки std::u32string. |
| [Substring](./substring/)(int32_t) const | Извлекает подстроку. |
| [Substring](./substring/)(int32_t, int32_t) const | Извлекает подстроку. |
| [ToAsciiString](./toasciistring/)() const | Преобразует строку в std::string. Использует кодировку ASCII. |
| [ToByteArray](./tobytearray/)(int32_t, int32_t, bool) const | Преобразует строку или подстроку в массив байтов. |
| [ToCharArray](./tochararray/)(int32_t, int32_t) const | Преобразует строку или подстроку в массив символов. |
| [ToLower](./tolower/)() const | Преобразует все символы строки в нижний регистр. |
| [ToLower](./tolower/)(const SharedPtr\<System::Globalization::CultureInfo\>\&) const | Преобразует все символы строки в нижний регистр, используя конкретную культуру. |
| [ToLowerInvariant](./tolowerinvariant/)() const | Преобразует все символы строки в нижний регистр, используя инвариантную культуру. |
| [ToString](./tostring/)() const | Обёртка для работы с классом [String](./) в контекстах, где вызывается [ToString()](./tostring/) у объектов значимых типов. |
| [ToString](./tostring/)(const SharedPtr\<IFormatProvider\>\&) const | Обёртка для работы с классом [String](./) в контекстах, где вызывается [ToString()](./tostring/) у объектов значимых типов. |
| [ToU16Str](./tou16str/)() const | Преобразует строку в std::u16string. |
| [ToU32Str](./tou32str/)() const | Преобразует строку в std::u32string. |
| [ToUpper](./toupper/)() const | Преобразует все символы строки в верхний регистр. |
| [ToUpper](./toupper/)(const SharedPtr\<System::Globalization::CultureInfo\>\&) const | Преобразует все символы строки в верхний регистр, используя конкретную культуру. |
| [ToUpperInvariant](./toupperinvariant/)() const | Преобразует все символы строки в верхний регистр, используя инвариантную культуру. |
| [ToUtf8String](./toutf8string/)() const | Преобразует строку в std::string. Использует кодировку UTF-8. |
| [ToWCS](./towcs/)() const | Преобразует строку в std::wstring. |
| [Trim](./trim/)() const | Удаляет все пробельные символы как в начале, так и в конце строки. |
| [Trim](./trim/)(char_t) const | Удаляет все вхождения переданного символа как в начале, так и в конце строки. |
| [Trim](./trim/)(const String\&) const | Удаляет все вхождения переданных символов как в начале, так и в конце строки. |
| [Trim](./trim/)(const ArrayPtr\<char_t\>\&) const | Удаляет все вхождения переданных символов как в начале, так и в конце строки. |
| [TrimEnd](./trimend/)() const | Удаляет все пробельные символы с конца строки. |
| [TrimEnd](./trimend/)(char_t) const | Удаляет все вхождения переданного символа с конца строки. |
| [TrimEnd](./trimend/)(const String\&) const | Удаляет все вхождения переданных символов с конца строки. |
| [TrimEnd](./trimend/)(const ArrayPtr\<char_t\>\&) const | Удаляет все вхождения переданных символов с конца строки. |
| [TrimStart](./trimstart/)() const | Удаляет все пробельные символы с начала строки. |
| [TrimStart](./trimstart/)(char_t) const | Удаляет все вхождения переданного символа с начала строки. |
| [TrimStart](./trimstart/)(const String\&) const | Удаляет все вхождения переданных символов с начала строки. |
| [TrimStart](./trimstart/)(const ArrayPtr\<char_t\>\&) const | Удаляет все вхождения переданных символов с начала строки. |
| [u_str](./u_str/)() const | Возвращает буфер, завершающийся нулём, в стиле ICU. Может переаллочировать строку. |
| [~String](./~string/)() | Деструктор. |
## Поля

| Поле | Описание |
| --- | --- |
| static [Empty](./empty/) | Пустая строка. |
| static [Null](./null/) | Нулевая строка. |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [reverse_iterator](./reverse_iterator/) | Тип обратного итератора. |
## Примечания



```cpp
#include "system/string.h"
#include <iostream>

int main()
{
  // Создайте строку из массива символов и выведите её.
  const auto chars = {u'h', u'e', u'l', u'l', u'o'};
  const System::String string1(chars);
  std::cout << string1 << std::endl;

  // Создайте строку из массива байтов и выведите её.
  const uint8_t bytes[] = {0x77, 0x6f, 0x72, 0x6c, 0x64, 0x0};
  const auto string2 = System::String::FromUtf8(bytes);
  std::cout << string2 << std::endl;

  // Обрежьте строку ниже и выведите её.
  const System::String string3(u"   This string contains whitespaces in the beginning and at the end.   ");
  std::cout << '"' << string3.Trim() << '"' << std::endl;

  // Выведите количество слов в .
  std::cout << "Number of words: " << string3.Trim().Split(' ')->get_Length() << std::endl;

  return 0;
}
/*
This code example produces the following output:
hello
world
"This string contains whitespaces in the beginning and at the end."
Number of words: 11
*/
```

## См. также

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
