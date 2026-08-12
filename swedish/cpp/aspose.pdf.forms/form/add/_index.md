---
title: "Aspose::Pdf::Forms::Form::Add method"
linktitle: "Add"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Forms::Form::Add method. Lägger till ett fält i formuläret i C++."
type: docs
weight: 100
url: /sv/cpp/aspose.pdf.forms/form/add/
---
## Form::Add(const System::SharedPtr\<Field\>\&) method


Lägger till fält på formuläret.

```cpp
void Aspose::Pdf::Forms::Form::Add(const System::SharedPtr<Field> &field)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| field | const System::SharedPtr\<Field\>\& | [Field](../../field/) som måste läggas till. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Field](../../field/)
* Class [Form](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## Form::Add(const System::SharedPtr\<Field\>\&, int32_t) method


Lägger till fält på formuläret.

```cpp
void Aspose::Pdf::Forms::Form::Add(const System::SharedPtr<Field> &field, int32_t pageNumber)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| field | const System::SharedPtr\<Field\>\& | [Field](../../field/) som måste läggas till. |
| pageNumber | int32_t | [Page](../../../aspose.pdf/page/) index där det tillagda fältet kommer att placeras. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Field](../../field/)
* Class [Form](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## Form::Add(System::SharedPtr\<Field\>, const System::String\&, int32_t) method


Lägger till ett nytt fält till formuläret; Om detta fält redan är placerat på ett annat eller detta formulär, skapas en kopia av fältet.

```cpp
System::SharedPtr<Field> Aspose::Pdf::Forms::Form::Add(System::SharedPtr<Field> field, const System::String &partialName, int32_t pageNumber)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| field | System::SharedPtr\<Field\> | [Field](../../field/) namn. |
| partialName | const System::String\& | Namn på fältet i formuläret. |
| pageNumber | int32_t | [Page](../../../aspose.pdf/page/) nummer där fältet kommer att läggas till. |

### ReturnValue

Tillagt fält returneras. Om en kopia av fältet skapades kommer den att returneras.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Field](../../field/)
* Class [String](../../../system/string/)
* Class [Form](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
