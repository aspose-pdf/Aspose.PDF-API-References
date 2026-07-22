---
title: "Aspose::Pdf::Forms::Form::HasField metod"
linktitle: "HasField"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Forms::Form::HasField metod. Kontrollerar om formuläret redan har det angivna fältet i C++."
type: docs
weight: 2600
url: /sv/cpp/aspose.pdf.forms/form/hasfield/
---
## Form::HasField(const System::SharedPtr\<Field\>\&) method


Kontrollera om formuläret redan har det angivna fältet.

```cpp
bool Aspose::Pdf::Forms::Form::HasField(const System::SharedPtr<Field> &field)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| field | const System::SharedPtr\<Field\>\& | [Field](../../field/) att kontrollera. |

### ReturnValue

**true** if the specified field name added to [Form](../); otherwise, **false**.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Field](../../field/)
* Class [Form](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## Form::HasField(const System::String\&) method


Bestämmer om fältet med angivet namn redan har lagts till i [Form](../).

```cpp
bool Aspose::Pdf::Forms::Form::HasField(const System::String &fieldName)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | const System::String\& | [Field::PartialName](../) eller [Annotation::FullName](../) för fältet. |

### ReturnValue

**true**
## Anmärkningar



om det angivna fältnamnet har lagts till i [Form](../); annars, **false**

.
## Se även

* Class [String](../../../system/string/)
* Class [Form](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## Form::HasField(const System::String\&, bool) method


Bestämmer om fältet med angivet namn redan har lagts till i [Form](../), med möjlighet att söka i fältens underordnade hierarki.

```cpp
bool Aspose::Pdf::Forms::Form::HasField(const System::String &fieldName, bool searchChildren)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | const System::String\& | [Field::PartialName](../) eller [Annotation::FullName](../) för fältet. |
|  | searchChildren | bool | När den är inställd på **true** |

hela hierarkin av formulärfält skulle sökas efter det begärda *fieldName* (observera att i detta fall [Annotation::FullName](../) för det önskade fältet bör skickas som *fieldName* ). |

### ReturnValue

**true**
## Anmärkningar



om det angivna fältnamnet har lagts till i [Form](../); annars, **false**

.
## Se även

* Class [String](../../../system/string/)
* Class [Form](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
