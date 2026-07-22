---
title: "Aspose::Pdf::Annotations::GoToAction::GoToAction konstruktor"
linktitle: "GoToAction"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Annotations::GoToAction::GoToAction konstruktor. Konstruktor i C++."
type: docs
weight: 100
url: /sv/cpp/aspose.pdf.annotations/gotoaction/gotoaction/
---
## GoToAction::GoToAction() constructor


Konstruktor.

```cpp
Aspose::Pdf::Annotations::GoToAction::GoToAction()
```


## Deprecated
Använd konstruktorer med parametrar.

## Se även

* Class [GoToAction](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
## GoToAction::GoToAction(const System::SharedPtr\<Document\>\&, const System::String\&) constructor


Åtgärd som är länkad till namngiven destination.

```cpp
Aspose::Pdf::Annotations::GoToAction::GoToAction(const System::SharedPtr<Document> &doc, const System::String &name)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| doc | const System::SharedPtr\<Document\>\& | [Document](../../../aspose.pdf/document/) där åtgärden kommer att skapas. |
| namn | const System::String\& | Namn på destinationen. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../../aspose.pdf/document/)
* Class [String](../../../system/string/)
* Class [GoToAction](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
## GoToAction::GoToAction(const System::SharedPtr\<ExplicitDestination\>\&) constructor


Konstruktor.

```cpp
Aspose::Pdf::Annotations::GoToAction::GoToAction(const System::SharedPtr<ExplicitDestination> &destination)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| destination | const System::SharedPtr\<ExplicitDestination\>\& | Explicit destination. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ExplicitDestination](../../explicitdestination/)
* Class [GoToAction](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
## GoToAction::GoToAction(const System::SharedPtr\<Page\>\&) constructor


Konstruktor för [GoToAction](../) klass.

```cpp
Aspose::Pdf::Annotations::GoToAction::GoToAction(const System::SharedPtr<Page> &page)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| page | const System::SharedPtr\<Page\>\& | [Aspose.Pdf.Page](../../../aspose.pdf/page/) destinationsobjekt att hoppa till. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Page](../../../aspose.pdf/page/)
* Class [GoToAction](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
## GoToAction::GoToAction(const System::SharedPtr\<Page\>\&, ExplicitDestinationType, const System::ArrayPtr\<double\>\&) constructor


Konstruktor för [GoToAction](../) klass.

```cpp
Aspose::Pdf::Annotations::GoToAction::GoToAction(const System::SharedPtr<Page> &page, ExplicitDestinationType type, const System::ArrayPtr<double> &values)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sida | const System::SharedPtr\<Page\>\& | Destinationssida. |
| typ | ExplicitDestinationType | Destinationstyp. |
| värden | const System::ArrayPtr\<double\>\& | Åtgärdsparametrar. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Page](../../../aspose.pdf/page/)
* Enum [ExplicitDestinationType](../../explicitdestinationtype/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [GoToAction](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
## GoToAction::GoToAction(int32_t) constructor


Konstruktor för [GoToAction](../) klass.

```cpp
Aspose::Pdf::Annotations::GoToAction::GoToAction(int32_t page)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sida | int32_t | Det sidnummer för destinationen att hoppa till. |

## Deprecated
Använd konstruktor med Aspose.Pdf.Page-parameter istället för den här. Orsak: om du använder den här konstruktorn uppstår ett problem med dokumentet när du sparar om det i Adobe Acrobat.

## Se även

* Class [GoToAction](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
