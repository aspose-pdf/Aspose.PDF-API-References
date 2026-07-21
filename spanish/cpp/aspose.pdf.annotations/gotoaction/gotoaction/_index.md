---
title: "Aspose::Pdf::Annotations::GoToAction::GoToAction constructor"
linktitle: "GoToAction"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Annotations::GoToAction::GoToAction constructor. Constructor en C++."
type: docs
weight: 100
url: /es/cpp/aspose.pdf.annotations/gotoaction/gotoaction/
---
## GoToAction::GoToAction() constructor


Constructor.

```cpp
Aspose::Pdf::Annotations::GoToAction::GoToAction()
```


## Deprecated
Utilice constructores con parámetros.

## Ver también

* Class [GoToAction](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
## GoToAction::GoToAction(const System::SharedPtr\<Document\>\&, const System::String\&) constructor


Acción vinculada con Destino nombrado.

```cpp
Aspose::Pdf::Annotations::GoToAction::GoToAction(const System::SharedPtr<Document> &doc, const System::String &name)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| doc | const System::SharedPtr\<Document\>\& | [Document](../../../aspose.pdf/document/) donde se creará la acción. |
| nombre | const System::String\& | Nombre del destino. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../../aspose.pdf/document/)
* Class [String](../../../system/string/)
* Class [GoToAction](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
## GoToAction::GoToAction(const System::SharedPtr\<ExplicitDestination\>\&) constructor


Constructor.

```cpp
Aspose::Pdf::Annotations::GoToAction::GoToAction(const System::SharedPtr<ExplicitDestination> &destination)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| destination | const System::SharedPtr\<ExplicitDestination\>\& | Destino explícito. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ExplicitDestination](../../explicitdestination/)
* Class [GoToAction](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
## GoToAction::GoToAction(const System::SharedPtr\<Page\>\&) constructor


Constructor para la clase [GoToAction](../).

```cpp
Aspose::Pdf::Annotations::GoToAction::GoToAction(const System::SharedPtr<Page> &page)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| page | const System::SharedPtr\<Page\>\& | Objeto de destino [Aspose.Pdf.Page](../../../aspose.pdf/page/) al que saltar. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Page](../../../aspose.pdf/page/)
* Class [GoToAction](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
## GoToAction::GoToAction(const System::SharedPtr\<Page\>\&, ExplicitDestinationType, const System::ArrayPtr\<double\>\&) constructor


Constructor para la clase [GoToAction](../).

```cpp
Aspose::Pdf::Annotations::GoToAction::GoToAction(const System::SharedPtr<Page> &page, ExplicitDestinationType type, const System::ArrayPtr<double> &values)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| página | const System::SharedPtr\<Page\>\& | Página de destino. |
| tipo | ExplicitDestinationType | Tipo de destino. |
| valores | const System::ArrayPtr\<double\>\& | Parámetros de la acción. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Page](../../../aspose.pdf/page/)
* Enum [ExplicitDestinationType](../../explicitdestinationtype/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [GoToAction](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
## GoToAction::GoToAction(int32_t) constructor


Constructor para la clase [GoToAction](../).

```cpp
Aspose::Pdf::Annotations::GoToAction::GoToAction(int32_t page)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| página | int32_t | El número de página de destino al que saltar. |

## Deprecated
Utilice el constructor con el parámetro Aspose.Pdf.Page en lugar de este. Razón: si se usa este constructor hay un problema con el documento al volver a guardarlo en Adobe Acrobat.

## Ver también

* Class [GoToAction](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
