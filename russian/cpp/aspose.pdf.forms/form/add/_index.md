---
title: "Метод Aspose::Pdf::Forms::Form::Add"
linktitle: "Add"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод Aspose::Pdf::Forms::Form::Add. Добавляет поле в форму в C++."
type: docs
weight: 100
url: /ru/cpp/aspose.pdf.forms/form/add/
---
## Form::Add(const System::SharedPtr\<Field\>\&) method


Добавляет поле в форму.

```cpp
void Aspose::Pdf::Forms::Form::Add(const System::SharedPtr<Field> &field)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| field | const System::SharedPtr\<Field\>\& | [Field](../../field/) которое должно быть добавлено. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Field](../../field/)
* Class [Form](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## Form::Add(const System::SharedPtr\<Field\>\&, int32_t) method


Добавляет поле в форму.

```cpp
void Aspose::Pdf::Forms::Form::Add(const System::SharedPtr<Field> &field, int32_t pageNumber)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| field | const System::SharedPtr\<Field\>\& | [Field](../../field/) которое должно быть добавлено. |
| pageNumber | int32_t | [Page](../../../aspose.pdf/page/) индекс, где будет размещено добавленное поле. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Field](../../field/)
* Class [Form](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## Form::Add(System::SharedPtr\<Field\>, const System::String\&, int32_t) method


Добавляет новое поле в форму; если это поле уже размещено в другой или этой форме, создаётся копия поля.

```cpp
System::SharedPtr<Field> Aspose::Pdf::Forms::Form::Add(System::SharedPtr<Field> field, const System::String &partialName, int32_t pageNumber)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| field | System::SharedPtr\<Field\> | Имя [Field](../../field/). |
| partialName | const System::String\& | Имя поля в форме. |
| pageNumber | int32_t | Номер [Page](../../../aspose.pdf/page/), где будет добавлено поле. |

### ReturnValue

Возвращено добавленное поле. Если была создана копия поля, будет возвращена она.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Field](../../field/)
* Class [String](../../../system/string/)
* Class [Form](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
