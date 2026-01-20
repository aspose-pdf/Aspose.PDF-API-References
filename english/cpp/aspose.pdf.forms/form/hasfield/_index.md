---
title: Aspose::Pdf::Forms::Form::HasField method
linktitle: HasField
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Forms::Form::HasField method. Check if the form already has specified field in C++.'
type: docs
weight: 2600
url: /cpp/aspose.pdf.forms/form/hasfield/
---
## Form::HasField(System::SharedPtr\<Field\>) method


Check if the form already has specified field.

```cpp
bool Aspose::Pdf::Forms::Form::HasField(System::SharedPtr<Field> field)
```


| Parameter | Type | Description |
| --- | --- | --- |
| field | System::SharedPtr\<Field\> | [Field](../../field/) to check. |

### ReturnValue

**true** if the specified field name added to [Form](../); otherwise, **false**.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Field](../../field/)
* Class [Form](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## Form::HasField(System::String) method


Determines if the field with specified name already added to the [Form](../).

```cpp
bool Aspose::Pdf::Forms::Form::HasField(System::String fieldName)
```


| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | System::String | [Field::PartialName](../) or [Annotation::FullName](../) of the field. |

### ReturnValue

**true**
## Remarks



if the specified field name added to [Form](../); otherwise, **false**

. 
## See Also

* Class [String](../../../system/string/)
* Class [Form](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## Form::HasField(System::String, bool) method


Determines if the field with specified name already added to the [Form](../), with ability to look into children hierarchy of fields.

```cpp
bool Aspose::Pdf::Forms::Form::HasField(System::String fieldName, bool searchChildren)
```


| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | System::String | [Field::PartialName](../) or [Annotation::FullName](../) of the field. |
| searchChildren | bool | When set to **true**

the whole hierarchy of form fields would be searched for the requested *fieldName*  (note that in this case the [Annotation::FullName](../) of the required field should be passed as *fieldName* ). |

### ReturnValue

**true**
## Remarks



if the specified field name added to [Form](../); otherwise, **false**

. 
## See Also

* Class [String](../../../system/string/)
* Class [Form](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
