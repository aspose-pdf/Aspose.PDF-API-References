---
title: "System::String::String конструктор"
linktitle: "String"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::String::String конструктор. Конструктор по умолчанию. Создаёт объект строки, который считается null в C++."
type: docs
weight: 100
url: /ru/cpp/system/string/string/
---
## String::String() constructor


Конструктор по умолчанию. Создаёт объект строки, который считается null.

```cpp
System::String::String()
```

## См. также

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::String(codeporting_icu::UnicodeString\&&) constructor


Конструктор перемещения.

```cpp
System::String::String(codeporting_icu::UnicodeString &&str) noexcept
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| str | codeporting_icu::UnicodeString\&& | UnicodeString для обёртывания в [String](../). |

## См. также

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::String(const ArrayPtr\<char16_t\>\&) constructor


Преобразует весь массив символов в строку.

```cpp
System::String::String(const ArrayPtr<char16_t> &arr)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| arr | const ArrayPtr\<char16_t\>\& | [Array](../../array/) для преобразования в строку. |

## См. также

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::String(const ArrayPtr\<char16_t\>\&, int, int) constructor


Преобразует поддиапазон массива символов в строку. Если параметры выходят за границы массива, создаётся пустая строка.

```cpp
System::String::String(const ArrayPtr<char16_t> &arr, int offset, int len)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| arr | const ArrayPtr\<char16_t\>\& | Массив символов. |
| смещение | int | Индекс начала подмассива. |
| len | int | Длина подмассива. |

## См. также

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::String(const char *, int) constructor


Создаёт строку из указателя на строку символов и явной длины.

```cpp
System::String::String(const char *str, int length)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| str | const char * | [String](../) указатель на данные UTF8, может быть литералом или массивом. |
| длина | int | Явная длина строки |

## См. также

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::String(const char16_t *, int) constructor


Создаёт строку из указателя на строку символов и явной длины.

```cpp
System::String::String(const char16_t *str, int length)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| str | const char16_t * | [String](../) указатель, может быть литералом или массивом. |
| длина | int | Явная длина строки |

## См. также

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::String(const char16_t *, int, int) constructor


Создаёт строку из указателя на строку символов, начиная с позиции, используя длину.

```cpp
System::String::String(const char16_t *str, int start, int length)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| str | const char16_t * | [String](../) указатель, может быть литералом или массивом. |
| начало | int | Начальная позиция. |
| length | int | [String](../) длина. |

## См. также

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::String(const char16_t, int) constructor


Заполняющий конструктор.

```cpp
System::String::String(const char16_t ch, int count)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| ch | const char16_t | Заполняющий символ. |
| count | int | Целевая длина. |

## См. также

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::String(const codeporting_icu::UnicodeString\&) constructor


Оборачивает UnicodeString в [String](../).

```cpp
System::String::String(const codeporting_icu::UnicodeString &str)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| str | const codeporting_icu::UnicodeString\& | UnicodeString для обёртывания в [String](../). |

## См. также

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::String(const ReadOnlySpan\<char16_t\>\&) constructor


Инициализирует новый экземпляр класса [System.String](../) символами Unicode, указанными в заданном только для чтения диапазоне.

```cpp
System::String::String(const ReadOnlySpan<char16_t> &value)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const ReadOnlySpan\<char16_t\>\& | Только для чтения диапазон символов Unicode. |

## См. также

* Class [ReadOnlySpan](../../readonlyspan/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::String(const std::string\&) constructor


Создает [String](../) из строки std::string, представленной в формате UTF-8.

```cpp
System::String::String(const std::string &utf8str)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| utf8str | const std::string\& | Строка std::string для преобразования в [String](../). |

## См. также

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::String(const std::u16string\&) constructor


Создает [String](../) из строки utf16.

```cpp
System::String::String(const std::u16string &str)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| str | const std::u16string\& | Строка Utf16 для преобразования в [String](../). |

## См. также

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::String(const std::u32string\&) constructor


Создает [String](../) из строки std::u32string.

```cpp
System::String::String(const std::u32string &u32str)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| u32str | const std::u32string\& | Строка std::u32string для преобразования в [String](../). |

## См. также

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::String(const std::wstring\&) constructor


Создает [String](../) из widestring.

```cpp
System::String::String(const std::wstring &str)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| str | const std::wstring\& | Widestring для преобразования в [String](../). |

## См. также

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::String(const String\&) constructor


Конструктор копирования.

```cpp
System::String::String(const String &str)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| str | const String\& | [String](../) для копирования. |

## См. также

* Class [String](../)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::String(const T\&, typename std::enable_if\<IsStringPointer\<T, char\>::value\>::type *) constructor


Создаёт строку на основе указателя на строку символов. Рассматривает указываемую строку как нуль-терминированную в UTF8, вычисляет длину целевой строки на основе нулевого символа.

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<IsStringPointer<T, char>::value>::type *=nullptr)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const T\& | Указатель на строку символов. |

## См. также

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::String(const T\&, typename std::enable_if\<IsStringPointer\<T, char16_t\>::value\>::type *) constructor


Создаёт строку на основе указателя на строку символов. Рассматривает указываемую строку как нуль-терминированную, вычисляет длину целевой строки на основе нулевого символа.

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<IsStringPointer<T, char16_t>::value>::type *=nullptr)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const T\& | Указатель на строку символов. |

## См. также

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::String(const T\&, typename std::enable_if\<IsStringPointer\<T, wchar_t\>::value\>::type *) constructor


Создаёт строку на основе указателя на строку широких символов. Рассматривает указанную строку как нуль-терминированную, вычисляет длину целевой строки на основе нулевого символа. Преобразование из wchar_t занимает много времени на некоторых платформах, поэтому не допускаются неявные преобразования.

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<IsStringPointer<T, wchar_t>::value>::type *=nullptr)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const T\& | Указатель на строку символов. |

## См. также

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::String(const T\&, typename std::enable_if\<std::is_same\<T, std::nullptr_t\>::value\>::type *) constructor


Конструктор nullptr. Объявлен как шаблон для разрешения приоритетов с другими шаблонными конструкторами.

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<std::is_same<T, std::nullptr_t>::value>::type *=nullptr)
```


| Параметр | Описание |
| --- | --- |
| T | Должно быть nullptr_t |

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const T\& | nullptr |

## См. также

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::String(const wchar_t *, int) constructor


Создаёт строку из указателя на строку широких символов и явной длины. Преобразование из wchar_t занимает много времени на некоторых платформах, поэтому не допускаются неявные преобразования.

```cpp
System::String::String(const wchar_t *str, int length)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| str | const wchar_t * | [String](../) указатель, может быть литералом или массивом. |
| длина | int | Явная длина строки |

## См. также

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::String(const wchar_t, int) constructor


Заполняющий конструктор. Преобразование из wchar_t занимает много времени на некоторых платформах, поэтому не допускаются неявные преобразования.

```cpp
System::String::String(const wchar_t ch, int count=1)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| ch | const wchar_t | Заполняющий символ. |
| count | int | Целевая длина. |

## См. также

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::String(String\&&) constructor


Конструктор перемещения.

```cpp
System::String::String(String &&str) noexcept
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| str | String\&& | [String](../) для перемещения данных из. |

## См. также

* Class [String](../)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::String(T\&, typename std::enable_if\<IsStringLiteral\<T, char\>::value\>::type *) constructor


Создаёт строку на основе строкового литерала. Считает литерал нуль-терминированной строкой в UTF8, вычисляет длину целевой строки на основе размера литерала.

```cpp
template<typename T> System::String::String(T &value, typename std::enable_if<IsStringLiteral<T, char>::value>::type *=nullptr)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| value | T\& | Указатель на литерал [String](../). |

## См. также

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::String(T\&, typename std::enable_if\<IsStringLiteral\<T, char16_t\>::value\>::type *) constructor


Создаёт строку на основе строкового литерала. Считает литерал нуль-терминированной строкой, вычисляет длину целевой строки на основе размера литерала.

```cpp
template<typename T> System::String::String(T &value, typename std::enable_if<IsStringLiteral<T, char16_t>::value>::type *=nullptr)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| value | T\& | Указатель на литерал [String](../). |

## См. также

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::String(T\&, typename std::enable_if\<IsStringLiteral\<T, wchar_t\>::value\>::type *) constructor


Создаёт строку на основе литерала широких строк. Считает литерал нуль-терминированной строкой, вычисляет длину целевой строки на основе размера литерала. Преобразование из wchar_t занимает много времени на некоторых платформах, поэтому не допускаются неявные преобразования.

```cpp
template<typename T> System::String::String(T &value, typename std::enable_if<IsStringLiteral<T, wchar_t>::value>::type *=nullptr)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| value | T\& | Указатель на литерал [String](../). |

## См. также

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
