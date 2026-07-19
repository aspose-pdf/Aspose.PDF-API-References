---
title: "метод Aspose::Pdf::Text::TextFragmentAbsorber::ApplyForAllFragments"
linktitle: "ApplyForAllFragments"
second_title: "Справочник API Aspose.PDF для C++"
description: "метод Aspose::Pdf::Text::TextFragmentAbsorber::ApplyForAllFragments. Применяет шрифт ко всем фрагментам текста, которые были поглощены. Это работает быстрее, чем перебор фрагментов, если все фрагменты на странице(ах) были поглощены. В противном случае работает аналогично перебору в C++."
type: docs
weight: 200
url: /ru/cpp/aspose.pdf.text/textfragmentabsorber/applyforallfragments/
---
## TextFragmentAbsorber::ApplyForAllFragments(const System::SharedPtr\<Font\>\&) method


Применяет шрифт ко всем поглощённым текстовым фрагментам. Это работает быстрее, чем перебор фрагментов, если все фрагменты на странице(ах) были поглощены. В противном случае работает аналогично перебору.

```cpp
void Aspose::Pdf::Text::TextFragmentAbsorber::ApplyForAllFragments(const System::SharedPtr<Font> &font)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| font | const System::SharedPtr\<Font\>\& | [Font](../../font/) текста. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Font](../../font/)
* Class [TextFragmentAbsorber](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## TextFragmentAbsorber::ApplyForAllFragments(const System::SharedPtr\<Font\>\&, float) method


Применяет шрифт и размер ко всем поглощённым текстовым фрагментам. Это работает быстрее, чем перебор фрагментов, если все фрагменты на странице(ах) были поглощены. В противном случае работает аналогично перебору.

```cpp
void Aspose::Pdf::Text::TextFragmentAbsorber::ApplyForAllFragments(const System::SharedPtr<Font> &font, float fontSize)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| font | const System::SharedPtr\<Font\>\& | [Font](../../font/) текста. |
| fontSize | float | [Font](../../font/) размер текста. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Font](../../font/)
* Class [TextFragmentAbsorber](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## TextFragmentAbsorber::ApplyForAllFragments(float) method


Применяет размер шрифта ко всем поглощённым текстовым фрагментам. Это работает быстрее, чем перебор фрагментов, если все фрагменты на странице(ах) были поглощены. В противном случае работает аналогично перебору.

```cpp
void Aspose::Pdf::Text::TextFragmentAbsorber::ApplyForAllFragments(float fontSize)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| fontSize | float | [Font](../../font/) размер текста. |

## См. также

* Class [TextFragmentAbsorber](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
