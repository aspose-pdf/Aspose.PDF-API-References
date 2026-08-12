---
title: "Aspose::Pdf::License::SetLicense metod"
linktitle: "SetLicense"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::License::SetLicense metod. Licensierar komponenten i C++."
type: docs
weight: 600
url: /sv/cpp/aspose.pdf/license/setlicense/
---
## License::SetLicense(const System::SharedPtr\<System::IO::Stream\>\&) method


Licensierar komponenten.

```cpp
void Aspose::Pdf::License::SetLicense(const System::SharedPtr<System::IO::Stream> &stream)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | const System::SharedPtr\<System::IO::Stream\>\& | En ström som innehåller licensen. |
## Anmärkningar



Använd den här metoden för att läsa in en licens från en ström.

[Java] void setLicense(java.io.InputStream stream) 
## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [License](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## License::SetLicense(const System::String\&) method


Licensierar komponenten.

```cpp
void Aspose::Pdf::License::SetLicense(const System::String &licenseName)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| licenseName | const System::String\& | Kan vara ett fullt eller kort filnamn eller namn på en inbäddad resurs. Använd en tom sträng för att växla till utvärderingsläge. |
## Anmärkningar


Försöker hitta licensen på följande platser:

1. Explicit sökväg.

2. Mappen som innehåller **Aspose**-komponentens assembly.

3. Mappen som innehåller klientens anropande assembly.

4. Mappen som innehåller entry (startup)-assemblyn.

5. En inbäddad resurs i klientens anropande assembly.

**[Note](../../note/):**On the .NET Compact Framework, tries to find the license only in these locations:

1. Explicit sökväg.

2. En inbäddad resurs i klientens anropande assembly.

[Java] 

2. Mappen som innehåller **Aspose**-komponentens JAR-fil.

3. Mappen som innehåller klientens anropande JAR-fil.

## Se även

* Class [String](../../../system/string/)
* Class [License](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
