---
title: "System::Drawing::Font::Font конструктор"
linktitle: "Font"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Drawing::Font::Font конструктор. Создаёт новый экземпляр класса Font, представляющий указанный существующий шрифт с указанным стилем шрифта в C++."
type: docs
weight: 100
url: /ru/cpp/system.drawing/font/font/
---
## Font::Font(const SharedPtr\<Font\>\&, FontStyle) constructor


Создаёт новый экземпляр класса [Font](../) class that represents the specified existing font with the specified font style.

```cpp
System::Drawing::Font::Font(const SharedPtr<Font> &prototype, FontStyle new_style)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| прототип | const SharedPtr\<Font\>\& | Существующий шрифт, из которого создаётся новый |
| new_style | FontStyle | Стиль шрифта, который следует применить к новому шрифту |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Font](../)
* Enum [FontStyle](../../fontstyle/)
* Class [Font](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Font::Font(const SharedPtr\<FontFamily\>\&, float, FontStyle, GraphicsUnit, uint8_t, bool) constructor


Создаёт новый экземпляр класса [Font](../).

```cpp
System::Drawing::Font::Font(const SharedPtr<FontFamily> &family, float em_size, FontStyle style, GraphicsUnit unit=GraphicsUnit::Point, uint8_t gdi_charset=1, bool gdi_vertical_font=false)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| семейство | const SharedPtr\<FontFamily\>\& | Семейство шрифта нового шрифта |
| em_size | float | Размер em нового шрифта в единицах, указанных параметром **unit** |
| style | FontStyle | Стиль нового шрифта |
| unit | GraphicsUnit | Единицы измерения нового шрифта |
| gdi_charset | uint8_t | Набор символов GDI, используемый для нового шрифта |
| gdi_vertical_font | bool | True, если новый шрифт получен из вертикального шрифта GDI |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [FontFamily](../../fontfamily/)
* Enum [FontStyle](../../fontstyle/)
* Enum [GraphicsUnit](../../graphicsunit/)
* Class [Font](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Font::Font(const SharedPtr\<FontFamily\>\&, float, GraphicsUnit) constructor


Создаёт новый экземпляр класса [Font](../).

```cpp
System::Drawing::Font::Font(const SharedPtr<FontFamily> &family, float em_size, GraphicsUnit unit=GraphicsUnit::Point)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| семейство | const SharedPtr\<FontFamily\>\& | Семейство шрифта нового шрифта |
| em_size | float | Размер em нового шрифта в единицах, указанных параметром **unit** |
| unit | GraphicsUnit | Единицы измерения нового шрифта |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [FontFamily](../../fontfamily/)
* Enum [GraphicsUnit](../../graphicsunit/)
* Class [Font](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Font::Font(const String\&, float, FontStyle, GraphicsUnit, uint8_t, bool) constructor


Создаёт новый экземпляр класса [Font](../).

```cpp
System::Drawing::Font::Font(const String &family_name, float em_size, FontStyle style, GraphicsUnit unit=GraphicsUnit::Point, uint8_t gdi_charset=1, bool gdi_vertical_font=false)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| family_name | const String\& | Имя семейства нового шрифта |
| em_size | float | Размер em нового шрифта в единицах, указанных параметром **unit** |
| style | FontStyle | Стиль нового шрифта |
| unit | GraphicsUnit | Единицы измерения нового шрифта |
| gdi_charset | uint8_t | Набор символов GDI, используемый для нового шрифта |
| gdi_vertical_font | bool | True, если новый шрифт получен из вертикального шрифта GDI |

## См. также

* Class [String](../../../system/string/)
* Enum [FontStyle](../../fontstyle/)
* Enum [GraphicsUnit](../../graphicsunit/)
* Class [Font](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Font::Font(const String\&, float, GraphicsUnit) constructor


Создаёт новый экземпляр класса [Font](../).

```cpp
System::Drawing::Font::Font(const String &family_name, float em_size, GraphicsUnit unit=GraphicsUnit::Point)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| family_name | const String\& | Имя семейства нового шрифта |
| em_size | float | Размер em нового шрифта в единицах, указанных параметром **unit** |
| unit | GraphicsUnit | Единицы измерения нового шрифта |

## См. также

* Class [String](../../../system/string/)
* Enum [GraphicsUnit](../../graphicsunit/)
* Class [Font](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
