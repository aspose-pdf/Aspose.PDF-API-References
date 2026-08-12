---
title: "Метод Aspose::Pdf::Facades::FormEditor::CopyOuterField"
linktitle: "CopyOuterField"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод Aspose::Pdf::Facades::FormEditor::CopyOuterField. Копирует существующее поле из одного PDF‑документа в другой документ с сохранением оригинального номера страницы и координат. Примечание: только для полей AcroForm (исключая радиокнопки) в C++."
type: docs
weight: 800
url: /ru/cpp/aspose.pdf.facades/formeditor/copyouterfield/
---
## FormEditor::CopyOuterField(const System::String\&, const System::String\&) method


Копирует существующее поле из одного PDF‑документа в другой документ с оригинальными номером страницы и координатами. Примечание: только для полей AcroForm (исключая переключатели).

```cpp
void Aspose::Pdf::Facades::FormEditor::CopyOuterField(const System::String &srcFileName, const System::String &fieldName)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| srcFileName | const System::String\& | Имя PDF‑документа, содержащего поле, которое нужно скопировать. |
| fieldName | const System::String\& | Исходное полностью квалифицированное имя поля. |

## См. также

* Class [String](../../../system/string/)
* Class [FormEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## FormEditor::CopyOuterField(const System::String\&, const System::String\&, int32_t) method


Копирует существующее поле из одного PDF‑документа в другой документ с указанным номером страницы и оригинальными координатами. Примечание: только для полей AcroForm (исключая переключатели).

```cpp
void Aspose::Pdf::Facades::FormEditor::CopyOuterField(const System::String &srcFileName, const System::String &fieldName, int32_t pageNum)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| srcFileName | const System::String\& | Имя PDF‑документа, содержащего поле, которое нужно скопировать. |
| fieldName | const System::String\& | Исходное полностью квалифицированное имя поля. |
| pageNum | int32_t | Номер страницы, на которой будет размещено новое поле. Если -1, новое поле будет скопировано на ту же страницу, что и старое. |

## См. также

* Class [String](../../../system/string/)
* Class [FormEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## FormEditor::CopyOuterField(const System::String\&, const System::String\&, int32_t, float, float) method


Копирует существующее поле из одного PDF‑документа в другой документ с указанным номером страницы и координатами. Примечание: только для полей AcroForm (исключая переключатели).

```cpp
void Aspose::Pdf::Facades::FormEditor::CopyOuterField(const System::String &srcFileName, const System::String &fieldName, int32_t pageNum, float abscissa, float ordinate)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| srcFileName | const System::String\& | Имя PDF‑документа, содержащего поле, которое нужно скопировать. |
| fieldName | const System::String\& | Исходное полностью квалифицированное имя поля. |
| pageNum | int32_t | Номер страницы, на которой будет размещено новое поле. Если -1, новое поле будет скопировано на ту же страницу, что и старое. |
| abscissa | float | Абсцисса нового поля. Если -1, абсцисса будет равна оригинальной. |
| ордината | float | Оордината нового поля. Если -1, ордината будет равна исходной. |

## См. также

* Class [String](../../../system/string/)
* Class [FormEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
