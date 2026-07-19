---
title: "Aspose::Pdf::Forms::Form::HasField метод"
linktitle: "HasField"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод Aspose::Pdf::Forms::Form::HasField. Проверяет, содержит ли форма уже указанное поле в C++."
type: docs
weight: 2600
url: /ru/cpp/aspose.pdf.forms/form/hasfield/
---
## Form::HasField(const System::SharedPtr\<Field\>\&) method


Проверьте, есть ли у формы указанное поле.

```cpp
bool Aspose::Pdf::Forms::Form::HasField(const System::SharedPtr<Field> &field)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| field | const System::SharedPtr\<Field\>\& | [Field](../../field/) для проверки. |

### ReturnValue

**true** if the specified field name added to [Form](../); otherwise, **false**.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Field](../../field/)
* Class [Form](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## Form::HasField(const System::String\&) method


Определяет, было ли поле с указанным именем уже добавлено в [Form](../).

```cpp
bool Aspose::Pdf::Forms::Form::HasField(const System::String &fieldName)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | const System::String\& | [Field::PartialName](../) или [Annotation::FullName](../) поля. |

### ReturnValue

**true**
## Примечания



если указанное имя поля добавлено в [Form](../); иначе, **false**

.
## См. также

* Class [String](../../../system/string/)
* Class [Form](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## Form::HasField(const System::String\&, bool) method


Определяет, было ли поле с указанным именем уже добавлено в [Form](../), с возможностью просматривать иерархию дочерних полей.

```cpp
bool Aspose::Pdf::Forms::Form::HasField(const System::String &fieldName, bool searchChildren)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | const System::String\& | [Field::PartialName](../) или [Annotation::FullName](../) поля. |
|  | searchChildren | bool | Когда установлено в **true** |

вся иерархия полей формы будет просматриваться в поисках запрошенного *fieldName* (заметьте, что в этом случае [Annotation::FullName](../) требуемого поля должно быть передано как *fieldName* ). |

### ReturnValue

**true**
## Примечания



если указанное имя поля добавлено в [Form](../); иначе, **false**

.
## См. также

* Class [String](../../../system/string/)
* Class [Form](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
