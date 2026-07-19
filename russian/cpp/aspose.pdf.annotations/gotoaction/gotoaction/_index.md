---
title: "Aspose::Pdf::Annotations::GoToAction::GoToAction конструктор"
linktitle: "GoToAction"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Annotations::GoToAction::GoToAction конструктор. Конструктор в C++."
type: docs
weight: 100
url: /ru/cpp/aspose.pdf.annotations/gotoaction/gotoaction/
---
## GoToAction::GoToAction() constructor


Конструктор.

```cpp
Aspose::Pdf::Annotations::GoToAction::GoToAction()
```


## Deprecated
Используйте конструкторы с параметрами.

## См. также

* Class [GoToAction](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
## GoToAction::GoToAction(const System::SharedPtr\<Document\>\&, const System::String\&) constructor


Действие, связанное с именованным назначением.

```cpp
Aspose::Pdf::Annotations::GoToAction::GoToAction(const System::SharedPtr<Document> &doc, const System::String &name)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| doc | const System::SharedPtr\<Document\>\& | [Документ](../../../aspose.pdf/document/) где будет создано действие. |
| имя | const System::String\& | Имя назначения. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../../aspose.pdf/document/)
* Class [String](../../../system/string/)
* Class [GoToAction](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
## GoToAction::GoToAction(const System::SharedPtr\<ExplicitDestination\>\&) constructor


Конструктор.

```cpp
Aspose::Pdf::Annotations::GoToAction::GoToAction(const System::SharedPtr<ExplicitDestination> &destination)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| destination | const System::SharedPtr\<ExplicitDestination\>\& | Явное назначение. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ExplicitDestination](../../explicitdestination/)
* Class [GoToAction](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
## GoToAction::GoToAction(const System::SharedPtr\<Page\>\&) constructor


Конструктор для класса [GoToAction](../).

```cpp
Aspose::Pdf::Annotations::GoToAction::GoToAction(const System::SharedPtr<Page> &page)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| page | const System::SharedPtr\<Page\>\& | [Aspose.Pdf.Page](../../../aspose.pdf/page/) объект назначения для перехода. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Page](../../../aspose.pdf/page/)
* Class [GoToAction](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
## GoToAction::GoToAction(const System::SharedPtr\<Page\>\&, ExplicitDestinationType, const System::ArrayPtr\<double\>\&) constructor


Конструктор для класса [GoToAction](../).

```cpp
Aspose::Pdf::Annotations::GoToAction::GoToAction(const System::SharedPtr<Page> &page, ExplicitDestinationType type, const System::ArrayPtr<double> &values)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| страница | const System::SharedPtr\<Page\>\& | Страница назначения. |
| тип | ExplicitDestinationType | Тип назначения. |
| значения | const System::ArrayPtr\<double\>\& | Параметры действия. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Page](../../../aspose.pdf/page/)
* Enum [ExplicitDestinationType](../../explicitdestinationtype/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [GoToAction](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
## GoToAction::GoToAction(int32_t) constructor


Конструктор для класса [GoToAction](../).

```cpp
Aspose::Pdf::Annotations::GoToAction::GoToAction(int32_t page)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| страница | int32_t | Номер страницы назначения для перехода. |

## Deprecated
Используйте конструктор с параметром Aspose.Pdf.Page вместо этого. Причина: при использовании этого конструктора возникает проблема с документом при повторном сохранении в Adobe Acrobat.

## См. также

* Class [GoToAction](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
