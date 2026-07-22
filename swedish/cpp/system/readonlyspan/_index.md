---
title: "System::ReadOnlySpan‑klass"
linktitle: "ReadOnlySpan"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::ReadOnlySpan‑klass. Avsedd för användning inom Span‑klassen i C++."
type: docs
weight: 5600
url: /sv/cpp/system/readonlyspan/
---
## ReadOnlySpan class


Avsedd för användning inom [Span](../span/)‑klassen.

```cpp
template<typename T>class ReadOnlySpan : public System::Details::SpanCore<const T, ReadOnlySpan<T>, Span<T>>
```


| Parameter | Beskrivning |
| --- | --- |
| T | Typen av element i spannen. Denna klass tillhandahåller ett typsäkert sätt att arbeta med sammanhängande sekvenser av objekt i skrivskyddat läge. Den kan användas för att omsluta arrayer, stack‑arrayer eller råpekare samtidigt som gränskontroller upprätthålls. [ReadOnlySpan](./) äger inte minnet den pekar på – det är bara en vy över befintligt minne. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [ReadOnlySpan](./readonlyspan/)(const Span\<T\>\&) | Skapar en skrivskyddad span från en vanlig span. |
| static [to_ReadOnlySpan](./to_readonlyspan/)(const typename BaseType::ArrayPtrT\&) | Konverterar en array till en [ReadOnlySpan](./). |
## Anmärkningar


Representerar ett skrivskyddat sammanhängande område av godtyckligt minne.

## Se även

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
