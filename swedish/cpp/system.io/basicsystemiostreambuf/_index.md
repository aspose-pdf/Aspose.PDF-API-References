---
title: "System::IO::BasicSystemIOStreamBuf klass"
linktitle: "BasicSystemIOStreamBuf"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::IO::BasicSystemIOStreamBuf-klass. Representerar en buffert som omsluter System::IO::Stream-liknande strömmar och tillåter dem att användas som en intern buffert för std::iostream-liknande strömmar i C++."
type: docs
weight: 400
url: /sv/cpp/system.io/basicsystemiostreambuf/
---
## BasicSystemIOStreamBuf class


Representerar en buffert som omsluter [System::IO::Stream](../stream/)-liknande strömmar och tillåter dem att användas som en intern buffert för std::iostream-liknande strömmar.

```cpp
template<typename Elem,typename Traits>class BasicSystemIOStreamBuf : public std::basic_streambuf<Elem, std::char_traits<Elem>>
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [AssignRV](./assignrv/)(BasicSystemIOStreamBuf\&&) | Används i flyttkonstruktorn och flytttilldelningsoperatorn för att återställa pekare och anropa [swap()](./swap/). |
| explicit [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)() | Skapar en ny instans av [BasicSystemIOStreamBuf](./). |
| explicit [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)(const SharedPtr\<Stream\>\&, SystemIOStreamWrappingMode, const std::locale\&) | Skapar en ny instans av [BasicSystemIOStreamBuf](./). |
| [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)(const BasicSystemIOStreamBuf\&) | Kopieringskonstruktor. Borttagen. |
| [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)(BasicSystemIOStreamBuf\&&) | Flyttkonstruktor. |
| [operator=](./operator=/)(const BasicSystemIOStreamBuf\&) | Kopieringsoperator för tilldelning. Borttagen. |
| [operator=](./operator=/)(BasicSystemIOStreamBuf\&&) | Flyttilldelningsoperator. |
| [swap](./swap/)(BasicSystemIOStreamBuf\&) | Anrop för att byta *this och right, om de inte är lika. |
| [~BasicSystemIOStreamBuf](./~basicsystemiostreambuf/)() override | Destruktor. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [char_type](./char_type/) |  |
| [int_type](./int_type/) |  |
| [Mysb](./mysb/) |  |
| [off_type](./off_type/) |  |
| [pos_type](./pos_type/) |  |
| [traits_type](./traits_type/) |  |
## Se även

* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
