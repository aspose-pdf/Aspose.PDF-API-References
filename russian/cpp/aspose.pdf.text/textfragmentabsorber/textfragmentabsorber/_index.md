---
title: "Aspose::Pdf::Text::TextFragmentAbsorber::TextFragmentAbsorber конструктор"
linktitle: "TextFragmentAbsorber"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Text::TextFragmentAbsorber::TextFragmentAbsorber конструктор. Инициализирует новый экземпляр TextFragmentAbsorber, который выполняет поиск всех текстовых сегментов документа или страницы в C++."
type: docs
weight: 100
url: /ru/cpp/aspose.pdf.text/textfragmentabsorber/textfragmentabsorber/
---
## TextFragmentAbsorber::TextFragmentAbsorber() constructor


Инициализирует новый экземпляр [TextFragmentAbsorber](../), который выполняет поиск всех текстовых сегментов документа или страницы.

```cpp
Aspose::Pdf::Text::TextFragmentAbsorber::TextFragmentAbsorber()
```

## Примечания


Выполняет поиск текста и предоставляет доступ к результатам поиска через коллекцию [TextFragmentAbsorber::TextFragments](../).
## См. также

* Class [TextFragmentAbsorber](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## TextFragmentAbsorber::TextFragmentAbsorber(const System::ArrayPtr\<System::SharedPtr\<System::Text::RegularExpressions::Regex\>\>\&, const System::SharedPtr\<Aspose::Pdf::Text::TextSearchOptions\>\&) constructor


Инициализирует новый экземпляр класса [TextFragmentAbsorber](../) для указанной текстовой фразы и параметров поиска текста.

```cpp
Aspose::Pdf::Text::TextFragmentAbsorber::TextFragmentAbsorber(const System::ArrayPtr<System::SharedPtr<System::Text::RegularExpressions::Regex>> &regexes, const System::SharedPtr<Aspose::Pdf::Text::TextSearchOptions> &textSearchOptions)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| regexes | const System::ArrayPtr\<System::SharedPtr\<System::Text::RegularExpressions::Regex\>\>\& | Массив объектов класса [System.Text.RegularExpressions.Regex](../../../system.text.regularexpressions/regex/), которые ищет [TextFragmentAbsorber](../). |
| textSearchOptions | const System::SharedPtr\<Aspose::Pdf::Text::TextSearchOptions\>\& | [Text](../../) параметры поиска (Позволяют включить некоторые функции поиска.). |
## Примечания


Выполняет поиск текста по указанному массиву фраз и предоставляет доступ к результатам поиска через словарь [TextFragmentAbsorber::RegexResults](../).

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Regex](../../../system.text.regularexpressions/regex/)
* Class [TextSearchOptions](../../textsearchoptions/)
* Class [TextFragmentAbsorber](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## TextFragmentAbsorber::TextFragmentAbsorber(const System::SharedPtr\<Aspose::Pdf::Text::TextEditOptions\>\&) constructor


Инициализирует новый экземпляр [TextFragmentAbsorber](../) с параметрами редактирования текста, который выполняет поиск всех текстовых сегментов документа или страницы.

```cpp
Aspose::Pdf::Text::TextFragmentAbsorber::TextFragmentAbsorber(const System::SharedPtr<Aspose::Pdf::Text::TextEditOptions> &textEditOptions)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| textEditOptions | const System::SharedPtr\<Aspose::Pdf::Text::TextEditOptions\>\& | [Text](../../) параметры редактирования (Позволяют включить некоторые функции редактирования). |
## Примечания


Выполняет поиск текста и предоставляет доступ к результатам поиска через коллекцию [TextFragmentAbsorber::TextFragments](../).

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [TextEditOptions](../../texteditoptions/)
* Class [TextFragmentAbsorber](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## TextFragmentAbsorber::TextFragmentAbsorber(const System::SharedPtr\<System::Text::RegularExpressions::Regex\>\&) constructor


Инициализирует новый экземпляр класса [TextFragmentAbsorber](../) для указанного объекта класса [System.Text.RegularExpressions.Regex](../../../system.text.regularexpressions/regex/).

```cpp
Aspose::Pdf::Text::TextFragmentAbsorber::TextFragmentAbsorber(const System::SharedPtr<System::Text::RegularExpressions::Regex> &regex)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| regex | const System::SharedPtr\<System::Text::RegularExpressions::Regex\>\& | Объект класса [System.Text.RegularExpressions.Regex](../../../system.text.regularexpressions/regex/), который ищет [TextFragmentAbsorber](../). |
## Примечания


Выполняет поиск текста указанной фразы и предоставляет доступ к результатам поиска через коллекцию [TextFragmentAbsorber::TextFragments](../).

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Regex](../../../system.text.regularexpressions/regex/)
* Class [TextFragmentAbsorber](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## TextFragmentAbsorber::TextFragmentAbsorber(const System::SharedPtr\<System::Text::RegularExpressions::Regex\>\&, const System::SharedPtr\<Aspose::Pdf::Text::TextEditOptions\>\&) constructor


Создаёт новый экземпляр класса [TextFragmentAbsorber](../) для указанной текстовой фразы и параметров редактирования текста.

```cpp
Aspose::Pdf::Text::TextFragmentAbsorber::TextFragmentAbsorber(const System::SharedPtr<System::Text::RegularExpressions::Regex> &regex, const System::SharedPtr<Aspose::Pdf::Text::TextEditOptions> &textEditOptions)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| regex | const System::SharedPtr\<System::Text::RegularExpressions::Regex\>\& | Объект класса [System.Text.RegularExpressions.Regex](../../../system.text.regularexpressions/regex/), который ищет [TextFragmentAbsorber](../). |
| textEditOptions | const System::SharedPtr\<Aspose::Pdf::Text::TextEditOptions\>\& | [Text](../../) параметры редактирования (Позволяют включить некоторые функции редактирования). |
## Примечания


Выполняет поиск текста указанной фразы и предоставляет доступ к результатам поиска через коллекцию [TextFragmentAbsorber::TextFragments](../).

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Regex](../../../system.text.regularexpressions/regex/)
* Class [TextEditOptions](../../texteditoptions/)
* Class [TextFragmentAbsorber](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## TextFragmentAbsorber::TextFragmentAbsorber(const System::SharedPtr\<System::Text::RegularExpressions::Regex\>\&, const System::SharedPtr\<Aspose::Pdf::Text::TextSearchOptions\>\&) constructor


Инициализирует новый экземпляр класса [TextFragmentAbsorber](../) для указанной текстовой фразы и параметров поиска текста.

```cpp
Aspose::Pdf::Text::TextFragmentAbsorber::TextFragmentAbsorber(const System::SharedPtr<System::Text::RegularExpressions::Regex> &regex, const System::SharedPtr<Aspose::Pdf::Text::TextSearchOptions> &textSearchOptions)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| regex | const System::SharedPtr\<System::Text::RegularExpressions::Regex\>\& | Объект класса [System.Text.RegularExpressions.Regex](../../../system.text.regularexpressions/regex/), который ищет [TextFragmentAbsorber](../). |
| textSearchOptions | const System::SharedPtr\<Aspose::Pdf::Text::TextSearchOptions\>\& | [Text](../../) параметры поиска (Позволяет включать некоторые функции поиска.) |
## Примечания


Выполняет поиск текста указанной фразы и предоставляет доступ к результатам поиска через коллекцию [TextFragmentAbsorber::TextFragments](../).

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Regex](../../../system.text.regularexpressions/regex/)
* Class [TextSearchOptions](../../textsearchoptions/)
* Class [TextFragmentAbsorber](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## TextFragmentAbsorber::TextFragmentAbsorber(const System::String\&) constructor


Создаёт новый экземпляр класса [TextFragmentAbsorber](../) для указанной текстовой фразы.

```cpp
Aspose::Pdf::Text::TextFragmentAbsorber::TextFragmentAbsorber(const System::String &phrase)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| phrase | const System::String\& | Фраза, которую ищет [TextFragmentAbsorber](../). |
## Примечания


Выполняет поиск текста указанной фразы и предоставляет доступ к результатам поиска через коллекцию [TextFragmentAbsorber::TextFragments](../).

## См. также

* Class [String](../../../system/string/)
* Class [TextFragmentAbsorber](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## TextFragmentAbsorber::TextFragmentAbsorber(const System::String\&, const System::SharedPtr\<Aspose::Pdf::Text::TextEditOptions\>\&) constructor


Создаёт новый экземпляр класса [TextFragmentAbsorber](../) для указанной текстовой фразы и параметров редактирования текста.

```cpp
Aspose::Pdf::Text::TextFragmentAbsorber::TextFragmentAbsorber(const System::String &phrase, const System::SharedPtr<Aspose::Pdf::Text::TextEditOptions> &textEditOptions)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| phrase | const System::String\& | Фраза, которую ищет [TextFragmentAbsorber](../). |
| textEditOptions | const System::SharedPtr\<Aspose::Pdf::Text::TextEditOptions\>\& | [Text](../../) параметры редактирования (Позволяют включить некоторые функции редактирования). |
## Примечания


Выполняет поиск текста указанной фразы и предоставляет доступ к результатам поиска через коллекцию [TextFragmentAbsorber::TextFragments](../).

## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [TextEditOptions](../../texteditoptions/)
* Class [TextFragmentAbsorber](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## TextFragmentAbsorber::TextFragmentAbsorber(const System::String\&, const System::SharedPtr\<Aspose::Pdf::Text::TextSearchOptions\>\&) constructor


Инициализирует новый экземпляр класса [TextFragmentAbsorber](../) для указанной текстовой фразы и параметров поиска текста.

```cpp
Aspose::Pdf::Text::TextFragmentAbsorber::TextFragmentAbsorber(const System::String &phrase, const System::SharedPtr<Aspose::Pdf::Text::TextSearchOptions> &textSearchOptions)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| phrase | const System::String\& | Фраза, которую ищет [TextFragmentAbsorber](../). |
| textSearchOptions | const System::SharedPtr\<Aspose::Pdf::Text::TextSearchOptions\>\& | [Text](../../) параметры поиска (Позволяет включать некоторые функции поиска. Например, поиск с использованием регулярных выражений.) |
## Примечания


Выполняет поиск текста указанной фразы и предоставляет доступ к результатам поиска через коллекцию [TextFragmentAbsorber::TextFragments](../).

## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [TextSearchOptions](../../textsearchoptions/)
* Class [TextFragmentAbsorber](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## TextFragmentAbsorber::TextFragmentAbsorber(const System::String\&, const System::SharedPtr\<Aspose::Pdf::Text::TextSearchOptions\>\&, const System::SharedPtr\<Aspose::Pdf::Text::TextEditOptions\>\&) constructor


Создаёт новый экземпляр класса [TextFragmentAbsorber](../) для указанной текстовой фразы, параметров поиска текста и параметров редактирования текста.

```cpp
Aspose::Pdf::Text::TextFragmentAbsorber::TextFragmentAbsorber(const System::String &phrase, const System::SharedPtr<Aspose::Pdf::Text::TextSearchOptions> &textSearchOptions, const System::SharedPtr<Aspose::Pdf::Text::TextEditOptions> &textEditOptions)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| phrase | const System::String\& | Фраза, которую ищет [TextFragmentAbsorber](../). |
| textSearchOptions | const System::SharedPtr\<Aspose::Pdf::Text::TextSearchOptions\>\& | [Text](../../) параметры поиска (Позволяет включать некоторые функции поиска. Например, поиск с использованием регулярных выражений.) |
| textEditOptions | const System::SharedPtr\<Aspose::Pdf::Text::TextEditOptions\>\& | [Text](../../) параметры редактирования (Позволяют включить некоторые функции редактирования). |
## Примечания


Выполняет поиск текста указанной фразы и предоставляет доступ к результатам поиска через коллекцию [TextFragmentAbsorber::TextFragments](../).

## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [TextSearchOptions](../../textsearchoptions/)
* Class [TextEditOptions](../../texteditoptions/)
* Class [TextFragmentAbsorber](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
