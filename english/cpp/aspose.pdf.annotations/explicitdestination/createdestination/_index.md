---
title: Aspose::Pdf::Annotations::ExplicitDestination::CreateDestination method
linktitle: CreateDestination
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Annotations::ExplicitDestination::CreateDestination method. Creates instances of ExplicitDestination descendant classes in C++.'
type: docs
weight: 400
url: /cpp/aspose.pdf.annotations/explicitdestination/createdestination/
---
## ExplicitDestination::CreateDestination(int32_t, ExplicitDestinationType, const System::ArrayPtr\<double\>\&) method


Creates instances of [ExplicitDestination](../) descendant classes.

```cpp
static System::SharedPtr<ExplicitDestination> Aspose::Pdf::Annotations::ExplicitDestination::CreateDestination(int32_t pageNumber, ExplicitDestinationType type, const System::ArrayPtr<double> &values)
```


| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | int32_t | The destination page number. |
| type | ExplicitDestinationType | The type of explicit destination. |
| values | const System::ArrayPtr\<double\>\& | Array of double values. |

### ReturnValue

The explicit destination object.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ExplicitDestination](../)
* Enum [ExplicitDestinationType](../../explicitdestinationtype/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ExplicitDestination](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
## ExplicitDestination::CreateDestination(System::SharedPtr\<Aspose::Pdf::Page\>, ExplicitDestinationType, const System::ArrayPtr\<double\>\&) method


Creates instances of [ExplicitDestination](../) descendant classes.

```cpp
static System::SharedPtr<ExplicitDestination> Aspose::Pdf::Annotations::ExplicitDestination::CreateDestination(System::SharedPtr<Aspose::Pdf::Page> page, ExplicitDestinationType type, const System::ArrayPtr<double> &values)
```


| Parameter | Type | Description |
| --- | --- | --- |
| page | System::SharedPtr\<Aspose::Pdf::Page\> | The object of destination page. |
| type | ExplicitDestinationType | The type of explicit destination. |
| values | const System::ArrayPtr\<double\>\& | Array of double values. |

### ReturnValue

The explicit destination object.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ExplicitDestination](../)
* Class [Page](../../../aspose.pdf/page/)
* Enum [ExplicitDestinationType](../../explicitdestinationtype/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ExplicitDestination](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
## ExplicitDestination::CreateDestination(System::SharedPtr\<Document\>, int32_t, ExplicitDestinationType, const System::ArrayPtr\<double\>\&) method


Creates instances of [ExplicitDestination](../) descendant classes.

```cpp
static System::SharedPtr<ExplicitDestination> Aspose::Pdf::Annotations::ExplicitDestination::CreateDestination(System::SharedPtr<Document> doc, int32_t pageNumber, ExplicitDestinationType type, const System::ArrayPtr<double> &values)
```


| Parameter | Type | Description |
| --- | --- | --- |
| doc | System::SharedPtr\<Document\> | [Document](../../../aspose.pdf/document/) where destination will be created. |
| pageNumber | int32_t | Number of the page. |
| type | ExplicitDestinationType | Destionatyion type. |
| values | const System::ArrayPtr\<double\>\& | Array of destination specific values. |

### ReturnValue

The explicit destination object.

## Deprecated
Use the method without Document argument. 

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ExplicitDestination](../)
* Class [Document](../../../aspose.pdf/document/)
* Enum [ExplicitDestinationType](../../explicitdestinationtype/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ExplicitDestination](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
