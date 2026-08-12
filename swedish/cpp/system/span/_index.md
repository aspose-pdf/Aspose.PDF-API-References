---
title: "System::Span-klass"
linktitle: "Span"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Span-klass. Representerar ett sammanhängande område av godtyckligt minne, liknande C++20:s std::span i C++."
type: docs
weight: 6000
url: /sv/cpp/system/span/
---
## Span class


Representerar ett sammanhängande område av godtyckligt minne, liknande C++20:s std::span.

```cpp
template<typename T>class Span : public System::Details::SpanCore<T, Span<T>, Span<T>>
```


| Parameter | Beskrivning |
| --- | --- |
| T | Typen av element i spanen. Denna klass tillhandahåller ett typsäkert sätt att arbeta med sammanhängande sekvenser av objekt. Den kan användas för att omsluta arrayer, stack-arrayer eller råpekare samtidigt som gränskontroller upprätthålls. [Span](./) äger inte minnet den pekar på – den är bara en vy över befintligt minne. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Clear](./clear/)() const | Rensar innehållet i spanen genom att sätta alla element till standardvärdet. |
| [Fill](./fill/)(const T\&) const | Fyller spanen med det angivna värdet. |
| static [to_Span](./to_span/)(const typename BaseType::ArrayPtrT\&) | Konverterar en array till en [Span](./). |

## Se även

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
