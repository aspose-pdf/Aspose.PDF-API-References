---
title: "Метод Aspose::Pdf::Facades::PdfFileStamp::AddPageNumber"
linktitle: "AddPageNumber"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод Aspose::Pdf::Facades::PdfFileStamp::AddPageNumber. Добавляет номер страницы на страницу. Номер страницы может содержать символ #, который будет заменён номером страницы. Номер страницы размещается в нижней части страницы, центрирован по горизонтали в C++."
type: docs
weight: 400
url: /ru/cpp/aspose.pdf.facades/pdffilestamp/addpagenumber/
---
## PdfFileStamp::AddPageNumber(const System::SharedPtr\<FormattedText\>\&) method


Добавляет номер страницы на страницу. Номер [Page](../../../aspose.pdf/page/) может содержать символ #, который будет заменён номером страницы. Номер [Page](../../../aspose.pdf/page/) размещается в нижней части страницы, центрирован по горизонтали.

```cpp
void Aspose::Pdf::Facades::PdfFileStamp::AddPageNumber(const System::SharedPtr<FormattedText> &formattedText)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| formattedText | const System::SharedPtr\<FormattedText\>\& | Строка формата для номера страницы представлена как [FormattedText](../../formattedtext/). |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [FormattedText](../../formattedtext/)
* Class [PdfFileStamp](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileStamp::AddPageNumber(const System::SharedPtr\<FormattedText\>\&, float, float) method


Добавляет номер страницы в указанном положении на странице.

```cpp
void Aspose::Pdf::Facades::PdfFileStamp::AddPageNumber(const System::SharedPtr<FormattedText> &formattedText, float x, float y)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| formattedText | const System::SharedPtr\<FormattedText\>\& | Отформатированный текст, представляющий формат номера страницы и свойства текста. Строка формата может содержать символ #, который будет заменён номером страницы. |
| x | float | Координата X номера страницы. |
| y | float | Координата Y номера страницы. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [FormattedText](../../formattedtext/)
* Class [PdfFileStamp](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileStamp::AddPageNumber(const System::SharedPtr\<FormattedText\>\&, int32_t) method


Добавляет номер страницы к страницам.

```cpp
void Aspose::Pdf::Facades::PdfFileStamp::AddPageNumber(const System::SharedPtr<FormattedText> &formattedText, int32_t position)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| formattedText | const System::SharedPtr\<FormattedText\>\& | Объект [FormattedText](../../formattedtext/), содержащий формат номера страницы и свойства текста. Этот текст может содержать #, который будет заменён номером страницы. |
| позиция | int32_t | Позиция, в которой номер страницы будет размещён на странице. 0‑нижний центр, 1‑нижний правый, 2‑верхний правый, 3‑правый боковой, 4‑верхний центр, 5‑нижний левый, 6‑левый боковой, 7‑верхний левый. Вы можете использовать следующие константы: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [FormattedText](../../formattedtext/)
* Class [PdfFileStamp](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileStamp::AddPageNumber(const System::SharedPtr\<FormattedText\>\&, int32_t, float, float, float, float) method


Добавляет номер страницы к страницам документа.

```cpp
void Aspose::Pdf::Facades::PdfFileStamp::AddPageNumber(const System::SharedPtr<FormattedText> &formattedText, int32_t position, float leftMargin, float rightMargin, float topMargin, float bottomMargin)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| formattedText | const System::SharedPtr\<FormattedText\>\& | Объект [FormattedText](../../formattedtext/), представляющий формат номера страницы и свойства текста. |
| позиция | int32_t | Позиция, в которой номер страницы будет размещён на странице. 0‑нижний центр, 1‑нижний правый, 2‑верхний правый, 3‑правый боковой, 4‑верхний центр, 5‑нижний левый, 6‑левый боковой, 7‑верхний левый. Вы можете использовать следующие константы: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |
| leftMargin | float | Отступ слева от края страницы. |
| rightMargin | float | Отступ справа от края страницы. |
| topMargin | float | Отступ сверху от края страницы. |
| bottomMargin | float | Отступ снизу от края страницы. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [FormattedText](../../formattedtext/)
* Class [PdfFileStamp](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileStamp::AddPageNumber(const System::String\&) method


Добавить номер страницы в файл. Текст номера [Page](../../../aspose.pdf/page/) может содержать символ #, который будет заменён номером страницы. Номер [Page](../../../aspose.pdf/page/) размещается в нижней части страницы, центрирован по горизонтали.

```cpp
void Aspose::Pdf::Facades::PdfFileStamp::AddPageNumber(const System::String &formatString)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| formatString | const System::String\& | [Text](../../../aspose.pdf.text/) номера страницы |

## См. также

* Class [String](../../../system/string/)
* Class [PdfFileStamp](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileStamp::AddPageNumber(const System::String\&, float, float) method


Добавляет номер страницы в указанном положении на странице.

```cpp
void Aspose::Pdf::Facades::PdfFileStamp::AddPageNumber(const System::String &formatString, float x, float y)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| formatString | const System::String\& | Строка формата. Строка формата может содержать символ #, который будет заменён номером страницы. |
| x | float | Координата X номера страницы. |
| y | float | Координата Y номера страницы. |

## См. также

* Class [String](../../../system/string/)
* Class [PdfFileStamp](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileStamp::AddPageNumber(const System::String\&, int32_t) method


Добавляет номер страницы к страницам.

```cpp
void Aspose::Pdf::Facades::PdfFileStamp::AddPageNumber(const System::String &formatString, int32_t position)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| formatString | const System::String\& | Формат номера страницы. Этот текст может содержать #, который будет заменён номером страницы. |
| позиция | int32_t | Позиция, в которой номер страницы будет размещён на странице. 0‑нижний центр, 1‑нижний правый, 2‑верхний правый, 3‑правый боковой, 4‑верхний центр, 5‑нижний левый, 6‑левый боковой, 7‑верхний левый. Вы можете использовать следующие константы: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |

## См. также

* Class [String](../../../system/string/)
* Class [PdfFileStamp](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileStamp::AddPageNumber(const System::String\&, int32_t, float, float, float, float) method


Добавляет номер страницы к страницам документа.

```cpp
void Aspose::Pdf::Facades::PdfFileStamp::AddPageNumber(const System::String &formatString, int32_t position, float leftMargin, float rightMargin, float topMargin, float bottomMargin)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| formatString | const System::String\& | Строка формата для номера страницы. |
| позиция | int32_t | Позиция, в которой номер страницы будет размещён на странице. 0‑нижний центр, 1‑нижний правый, 2‑верхний правый, 3‑правый боковой, 4‑верхний центр, 5‑нижний левый, 6‑левый боковой, 7‑верхний левый. Вы можете использовать следующие константы: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |
| leftMargin | float | Отступ слева от края страницы. |
| rightMargin | float | Отступ справа от края страницы. |
| topMargin | float | Отступ сверху от края страницы. |
| bottomMargin | float | Отступ снизу от края страницы. |

## См. также

* Class [String](../../../system/string/)
* Class [PdfFileStamp](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
