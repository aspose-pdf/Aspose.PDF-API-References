---
title: "Aspose::Pdf::LowCode::TimestampOptions::TimestampOptions konstruktor"
linktitle: "TimestampOptions"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::LowCode::TimestampOptions::TimestampOptions konstruktor. Skapar en ny instans med standardvärden. Används för att signera TSA med en PFX-fil i C++."
type: docs
weight: 100
url: /sv/cpp/aspose.pdf.lowcode/timestampoptions/timestampoptions/
---
## TimestampOptions::TimestampOptions() constructor


Skapar en ny instans med standardvärden. Används för att signera TSA med en PFX‑fil.

```cpp
Aspose::Pdf::LowCode::TimestampOptions::TimestampOptions()
```

## Se även

* Class [TimestampOptions](../)
* Namespace [Aspose::Pdf::LowCode](../../)
* Library [Aspose.PDF for C++](../../../)
## TimestampOptions::TimestampOptions(const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&) constructor


Skapar en ny instans med en PFX‑ström och lösenord.

```cpp
Aspose::Pdf::LowCode::TimestampOptions::TimestampOptions(const System::SharedPtr<System::IO::Stream> &pfxStream, const System::String &password)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pfxStream | const System::SharedPtr\<System::IO::Stream\>\& | Ström som innehåller PFX-data. |
| password | const System::String\& | Lösenord för PFX. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Class [TimestampOptions](../)
* Namespace [Aspose::Pdf::LowCode](../../)
* Library [Aspose.PDF for C++](../../../)
## TimestampOptions::TimestampOptions(const System::String\&, const System::String\&) constructor


Skapar en ny instans med en PFX‑filväg och lösenord.

```cpp
Aspose::Pdf::LowCode::TimestampOptions::TimestampOptions(const System::String &pfxPath, const System::String &password)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pfxPath | const System::String\& | Sökväg till PFX-filen. |
| password | const System::String\& | Lösenord för PFX-filen. |

## Se även

* Class [String](../../../system/string/)
* Class [TimestampOptions](../)
* Namespace [Aspose::Pdf::LowCode](../../)
* Library [Aspose.PDF for C++](../../../)
