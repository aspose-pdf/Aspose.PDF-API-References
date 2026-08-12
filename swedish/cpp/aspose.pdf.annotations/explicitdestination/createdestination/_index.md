---
title: "Aspose::Pdf::Annotations::ExplicitDestination::CreateDestination‑metod"
linktitle: "CreateDestination"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Annotations::ExplicitDestination::CreateDestination‑metod. Skapar instanser av ExplicitDestination‑avledda klasser i C++."
type: docs
weight: 400
url: /sv/cpp/aspose.pdf.annotations/explicitdestination/createdestination/
---
## ExplicitDestination::CreateDestination(const System::SharedPtr\<Aspose::Pdf::Page\>\&, ExplicitDestinationType, const System::ArrayPtr\<double\>\&) method


Skapar instanser av [ExplicitDestination](../)-avledda klasser.

```cpp
static System::SharedPtr<ExplicitDestination> Aspose::Pdf::Annotations::ExplicitDestination::CreateDestination(const System::SharedPtr<Aspose::Pdf::Page> &page, ExplicitDestinationType type, const System::ArrayPtr<double> &values)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sida | const System::SharedPtr\<Aspose::Pdf::Page\>\& | Objektet för destinationssidan. |
| typ | ExplicitDestinationType | Typen av explicit destination. |
| värden | const System::ArrayPtr\<double\>\& | Array av dubbelvärden. |

### ReturnValue

Det explicita destinationsobjektet.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ExplicitDestination](../)
* Class [Page](../../../aspose.pdf/page/)
* Enum [ExplicitDestinationType](../../explicitdestinationtype/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ExplicitDestination](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
## ExplicitDestination::CreateDestination(const System::SharedPtr\<Document\>\&, int32_t, ExplicitDestinationType, const System::ArrayPtr\<double\>\&) method


Skapar instanser av [ExplicitDestination](../)-avledda klasser.

```cpp
static System::SharedPtr<ExplicitDestination> Aspose::Pdf::Annotations::ExplicitDestination::CreateDestination(const System::SharedPtr<Document> &doc, int32_t pageNumber, ExplicitDestinationType type, const System::ArrayPtr<double> &values)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| doc | const System::SharedPtr\<Document\>\& | [Document](../../../aspose.pdf/document/) där destinationen kommer att skapas. |
| pageNumber | int32_t | Sidnummer. |
| typ | ExplicitDestinationType | Destinationstyp. |
| värden | const System::ArrayPtr\<double\>\& | Array av destinationsspecifika värden. |

### ReturnValue

Det explicita destinationsobjektet.

## Deprecated
Använd metoden utan Document‑argument.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ExplicitDestination](../)
* Class [Document](../../../aspose.pdf/document/)
* Enum [ExplicitDestinationType](../../explicitdestinationtype/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ExplicitDestination](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
## ExplicitDestination::CreateDestination(int32_t, ExplicitDestinationType, const System::ArrayPtr\<double\>\&) method


Skapar instanser av [ExplicitDestination](../)-avledda klasser.

```cpp
static System::SharedPtr<ExplicitDestination> Aspose::Pdf::Annotations::ExplicitDestination::CreateDestination(int32_t pageNumber, ExplicitDestinationType type, const System::ArrayPtr<double> &values)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pageNumber | int32_t | Numret på destinationssidan. |
| typ | ExplicitDestinationType | Typen av explicit destination. |
| värden | const System::ArrayPtr\<double\>\& | Array av dubbelvärden. |

### ReturnValue

Det explicita destinationsobjektet.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ExplicitDestination](../)
* Enum [ExplicitDestinationType](../../explicitdestinationtype/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ExplicitDestination](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
