---
title: Aspose::Pdf::Annotations::GoToAction::GoToAction constructor
linktitle: GoToAction
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Annotations::GoToAction::GoToAction constructor. Constructor in C++.'
type: docs
weight: 100
url: /cpp/aspose.pdf.annotations/gotoaction/gotoaction/
---
## GoToAction::GoToAction() constructor


Constructor.

```cpp
Aspose::Pdf::Annotations::GoToAction::GoToAction()
```


## Deprecated
Use constructors with parameters. 

## See Also

* Class [GoToAction](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
## GoToAction::GoToAction(int32_t) constructor


Constructor for [GoToAction](../) class.

```cpp
Aspose::Pdf::Annotations::GoToAction::GoToAction(int32_t page)
```


| Parameter | Type | Description |
| --- | --- | --- |
| page | int32_t | The destination page number to jump to. |

## Deprecated
Use constructor with Aspose.Pdf.Page parameter instead of this one. Reason: if to use this constructor there is the problem with the document when to resave it in Adobe Acrobat. 

## See Also

* Class [GoToAction](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
## GoToAction::GoToAction(System::SharedPtr\<Document\>, System::String) constructor


Action which linked with Named Destination.

```cpp
Aspose::Pdf::Annotations::GoToAction::GoToAction(System::SharedPtr<Document> doc, System::String name)
```


| Parameter | Type | Description |
| --- | --- | --- |
| doc | System::SharedPtr\<Document\> | [Document](../../../aspose.pdf/document/) where action will be created. |
| name | System::String | Name of the destination. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../../aspose.pdf/document/)
* Class [String](../../../system/string/)
* Class [GoToAction](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
## GoToAction::GoToAction(System::SharedPtr\<ExplicitDestination\>) constructor


Constructor.

```cpp
Aspose::Pdf::Annotations::GoToAction::GoToAction(System::SharedPtr<ExplicitDestination> destination)
```


| Parameter | Type | Description |
| --- | --- | --- |
| destination | System::SharedPtr\<ExplicitDestination\> | Explicit destination. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ExplicitDestination](../../explicitdestination/)
* Class [GoToAction](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
## GoToAction::GoToAction(System::SharedPtr\<Page\>) constructor


Constructor for [GoToAction](../) class.

```cpp
Aspose::Pdf::Annotations::GoToAction::GoToAction(System::SharedPtr<Page> page)
```


| Parameter | Type | Description |
| --- | --- | --- |
| page | System::SharedPtr\<Page\> | [Aspose.Pdf.Page](../../../aspose.pdf/page/) destination object to jump to. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Page](../../../aspose.pdf/page/)
* Class [GoToAction](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
## GoToAction::GoToAction(System::SharedPtr\<Page\>, ExplicitDestinationType, const System::ArrayPtr\<double\>\&) constructor


Constructor for [GoToAction](../) class.

```cpp
Aspose::Pdf::Annotations::GoToAction::GoToAction(System::SharedPtr<Page> page, ExplicitDestinationType type, const System::ArrayPtr<double> &values)
```


| Parameter | Type | Description |
| --- | --- | --- |
| page | System::SharedPtr\<Page\> | Destination page. |
| type | ExplicitDestinationType | Destination type. |
| values | const System::ArrayPtr\<double\>\& | Action parameters. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Page](../../../aspose.pdf/page/)
* Enum [ExplicitDestinationType](../../explicitdestinationtype/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [GoToAction](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
