---
title: "Aspose::Pdf::ComHelper-klass"
linktitle: "ComHelper"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::ComHelper-klass. Tillhandahåller metoder för COM-klienter att läsa in ett dokument i Aspose.Pdf i C++."
type: docs
weight: 3100
url: /sv/cpp/aspose.pdf/comhelper/
---
## ComHelper class


Tillhandahåller metoder för COM-klienter att läsa in ett dokument i [Aspose.Pdf](../).

```cpp
class ComHelper : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [OpenFile](./openfile/)(const System::String\&) | Skapa bara och returnera [Document](../document/) med *filename*. Samma som [Document(Stream)](../). |
| [OpenFile](./openfile/)(const System::String\&, const System::String\&) | Initiera och returnera en ny instans av [Document](../document/)-klassen för att arbeta med ett krypterat dokument. |
| [OpenFile](./openfile/)(const System::String\&, const System::String\&, bool) | Initiera en ny instans av [Document](../document/)-klassen för att arbeta med ett krypterat dokument. |
| [OpenFile](./openfile/)(const System::String\&, const System::SharedPtr\<LoadOptions\>\&) | Öppna ett befintligt dokument från en fil och tillhandahåll nödvändiga konverteringsalternativ för att få ett pdf-dokument. |
| [OpenStream](./openstream/)(const System::SharedPtr\<System::IO::Stream\>\&) | Initiera och returnera en ny [Document](../document/)-instans från *input*-strömmen. |
| [OpenStream](./openstream/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&) | Initiera och returnera en ny [Document](../document/)-instans från *input*-strömmen. |
| [OpenStream](./openstream/)(const System::SharedPtr\<System::IO::Stream\>\&, bool) | Initiera och returnera en ny [Document](../document/)-instans från *input*-strömmen. |
| [OpenStream](./openstream/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&, bool) | Initiera och returnera en ny [Document](../document/)-instans från *input*-strömmen. |
| [OpenStream](./openstream/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<LoadOptions\>\&) | Öppna och returnera ett befintligt dokument från en ström och tillhandahåll nödvändig konvertering för att få ett pdf-dokument. |
## Anmärkningar


Använd klassen [ComHelper](./) för att läsa in ett dokument från en fil eller ström till ett [Document](../document/)-objekt i en COM-applikation. Klassen [Document](../document/) tillhandahåller en standardkonstruktor för att skapa ett nytt dokument och erbjuder även överlagrade konstruktorer för att läsa in ett dokument från en fil eller ström. Om du använder Aspose.Words från en .NET-applikation kan du använda alla [Document](../document/)-konstruktorer direkt, men om du använder [Aspose.Pdf](../) från en COM-applikation är endast standardkonstruktorn för [Document](../document/) tillgänglig.
## Se även

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
