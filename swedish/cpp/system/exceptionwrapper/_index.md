---
title: "System::ExceptionWrapper-klass"
linktitle: "ExceptionWrapper"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::ExceptionWrapper-klass. Mall som representerar en omslag för undantag som är härledda från Exception-klass i C++."
type: docs
weight: 2700
url: /sv/cpp/system/exceptionwrapper/
---
## ExceptionWrapper class


Mall som representerar en omslag för undantag som är härledda från [Exception](../exception/)-klass.

```cpp
template<typename T>class ExceptionWrapper
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [ExceptionWrapper](./exceptionwrapper/)(std::nullptr_t) | Skapar en null-instans av [ExceptionWrapper](./)-klassen som inte representerar något undantag. |
| [ExceptionWrapper](./exceptionwrapper/)(const ExceptionPtr\&) | Skapar en instans av [ExceptionWrapper](./)-klassen som innehåller den överförda pekaren. |
| [ExceptionWrapper](./exceptionwrapper/)(const ExceptionWrapper\&) | Kopieringskonstruktor. |
| [ExceptionWrapper](./exceptionwrapper/)(ExceptionWrapper\&&) | Flyttkonstruktor. |
| explicit [ExceptionWrapper](./exceptionwrapper/)(Args\&&...) | Konstruktor som vidarebefordrar parametrar till [Exception](../exception/)-klassens konstruktorer och skapar en smart pekare som håller en ny [Exception](../exception/)-klassinstans. |
| static [operator new](./operatornew/)(std::size_t) |  |
| static [operator new[]](./operatornew[]/)(std::size_t) |  |
| [operator SharedPtr< Object >](./operatorsharedptr_object_/)() | Implicit typomvandlingsoperator till [SharedPtr<Object>](../sharedptr/) |
| [operator->](./operator-_/)() const | Tillåter åtkomst till medlemmar i [Exception](../exception/)-objektet. |
| [operator=](./operator=/)(const ExceptionWrapper\&) | Tilldelningsoperator. |
| [operator=](./operator=/)(ExceptionWrapper\&&) | Flyttilldelningsoperator. |
| static [Type](./type/)() | Genväg för att hämta [System::TypeInfo](../typeinfo/)-objektet för [Exception](../exception/)-typen. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [ExceptionType](./exceptiontype/) | Används för typomvandlingsfunktioner. |
## Se även

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
