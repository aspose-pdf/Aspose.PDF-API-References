---
title: "System::IO::BasicSystemIOStreamWrapper klass"
linktitle: "BasicSystemIOStreamWrapper"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::IO::BasicSystemIOStreamWrapper klass. Representerar ett std::iostream-liknande omslag som använde BasicSystemIOStreamBuf som intern buffert i C++."
type: docs
weight: 500
url: /sv/cpp/system.io/basicsystemiostreamwrapper/
---
## BasicSystemIOStreamWrapper class


Representerar ett std::iostream-liknande omslag som använde [BasicSystemIOStreamBuf](../basicsystemiostreambuf/) som intern buffert.

```cpp
template<typename Elem,typename Traits>class BasicSystemIOStreamWrapper : public std::basic_iostream<Elem, std::char_traits<Elem>>
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [AssignRV](./assignrv/)(BasicSystemIOStreamWrapper\&&) | Används i flyttkonstruktorn och flytttilldelningsoperatorn för att återställa pekare och anropa [swap()](./swap/). |
| [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/)(SharedPtr\<Stream\>, SystemIOStreamWrappingMode) | Skapar en ny instans av [BasicSystemIOStreamWrapper](./). |
| [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/)(const BasicSystemIOStreamWrapper\&) | Kopieringskonstruktor. Borttagen. |
| [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/)(BasicSystemIOStreamWrapper\&&) | Flyttkonstruktor. |
| [operator=](./operator=/)(const BasicSystemIOStreamWrapper\&) | Kopieringsoperator för tilldelning. Borttagen. |
| [operator=](./operator=/)(BasicSystemIOStreamWrapper\&&) | Flyttilldelningsoperator. |
| [swap](./swap/)(BasicSystemIOStreamWrapper\&) | Anrop för att byta *this och **right**, om de inte är lika. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [char_type](./char_type/) |  |
| [Mybase](./mybase/) |  |
| [Mysb](./mysb/) |  |
| [traits_type](./traits_type/) |  |
## Se även

* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
