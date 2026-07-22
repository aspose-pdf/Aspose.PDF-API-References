---
title: "System::IO::BasicSystemOStreamWrapper-klass"
linktitle: "BasicSystemOStreamWrapper"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::IO::BasicSystemOStreamWrapper-klass. Representerar ett std::ostream-liknande omslag som använde BasicSystemIOStreamBuf som intern buffert i C++."
type: docs
weight: 700
url: /sv/cpp/system.io/basicsystemostreamwrapper/
---
## BasicSystemOStreamWrapper class


Representerar ett std::ostream-liknande omslag som använde [BasicSystemIOStreamBuf](../basicsystemiostreambuf/) som intern buffert.

```cpp
template<typename Elem,typename Traits>class BasicSystemOStreamWrapper : public std::basic_ostream<Elem, std::char_traits<Elem>>
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [AssignRV](./assignrv/)(BasicSystemOStreamWrapper\&&) | Används i flyttkonstruktorn och flytttilldelningsoperatorn för att återställa pekare och anropa [swap()](./swap/). |
| [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/)(SharedPtr\<Stream\>, SystemIOStreamWrappingMode) | Skapar en ny instans av [BasicSystemOStreamWrapper](./). |
| [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/)(const BasicSystemOStreamWrapper\&) | Kopieringskonstruktor. Borttagen. |
| [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/)(BasicSystemOStreamWrapper\&&) | Flyttkonstruktor. |
| [operator=](./operator=/)(const BasicSystemOStreamWrapper\&) | Kopieringsoperator för tilldelning. Borttagen. |
| [operator=](./operator=/)(BasicSystemOStreamWrapper\&&) | Flyttilldelningsoperator. |
| [swap](./swap/)(BasicSystemOStreamWrapper\&) | Anrop för att byta *this och **right**, om de inte är lika. |
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
