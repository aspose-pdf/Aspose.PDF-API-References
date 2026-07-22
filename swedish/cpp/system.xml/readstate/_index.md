---
title: "System::Xml::ReadState enum"
linktitle: "ReadState"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::ReadState enum. Anger läsarens tillstånd i C++."
type: docs
weight: 5300
url: /sv/cpp/system.xml/readstate/
---
## ReadState enum


Anger läsarens tillstånd.

```cpp
enum class ReadState
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Initial | 0 | Metoden [XmlReader::Read](../xmlreader/read/) har inte anropats. |
| Interactive | 1 | Metoden [XmlReader::Read](../xmlreader/read/) har anropats. Ytterligare metoder kan anropas på läsaren. |
| Error | 2 | Ett fel inträffade som hindrar läsoperationen från att fortsätta. |
| EndOfFile | 3 | Slutet av filen har nåtts framgångsrikt. |
| Closed | 4 | Metoden [XmlReader::Close](../xmlreader/close/) har anropats. |

## Se även

* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
