---
title: "System::IO::BasicSystemIStreamWrapper klass"
linktitle: "BasicSystemIStreamWrapper"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::IO::BasicSystemIStreamWrapper klass. Representerar ett std::istream-liknande omslag som använde BasicSystemIOStreamBuf som intern buffert i C++."
type: docs
weight: 600
url: /sv/cpp/system.io/basicsystemistreamwrapper/
---
## BasicSystemIStreamWrapper class


Representerar ett std::istream-liknande omslag som använde [BasicSystemIOStreamBuf](../basicsystemiostreambuf/) som intern buffert.

```cpp
template<typename Elem,typename Traits>class BasicSystemIStreamWrapper : public std::basic_istream<Elem, std::char_traits<Elem>>
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [AssignRV](./assignrv/)(BasicSystemIStreamWrapper\&&) | Används i flyttkonstruktorn och flytttilldelningsoperatorn för att återställa pekare och anropa [swap()](./swap/). |
| [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/)(SharedPtr\<Stream\>, SystemIOStreamWrappingMode) | Skapar en ny instans av [BasicSystemIStreamWrapper](./). |
| [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/)(const BasicSystemIStreamWrapper\&) | Kopieringskonstruktor. Borttagen. |
| [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/)(BasicSystemIStreamWrapper\&&) | Flyttkonstruktor. |
| [operator=](./operator=/)(const BasicSystemIStreamWrapper\&) | Kopieringsoperator för tilldelning. Borttagen. |
| [operator=](./operator=/)(BasicSystemIStreamWrapper\&&) | Flyttilldelningsoperator. |
| [swap](./swap/)(BasicSystemIStreamWrapper\&) | Anrop för att byta *this och **right**, om de inte är lika. |
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
