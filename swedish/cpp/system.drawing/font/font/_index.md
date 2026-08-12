---
title: "System::Drawing::Font::Font konstruktor"
linktitle: "Typsnitt"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Drawing::Font::Font konstruktor. Skapar en ny instans av Font‑klassen som representerar det angivna befintliga teckensnittet med den angivna teckensnittsstilen i C++."
type: docs
weight: 100
url: /sv/cpp/system.drawing/font/font/
---
## Font::Font(const SharedPtr\<Font\>\&, FontStyle) constructor


Skapar en ny instans av [Font](../)-klassen som representerar det angivna befintliga teckensnittet med den angivna teckensnittsstilen.

```cpp
System::Drawing::Font::Font(const SharedPtr<Font> &prototype, FontStyle new_style)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| prototyp | const SharedPtr\<Font\>\& | Det befintliga teckensnittet att skapa det nya från |
| new_style | FontStyle | En teckensnittsstil att tillämpa på det nya teckensnittet |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Font](../)
* Enum [FontStyle](../../fontstyle/)
* Class [Font](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Font::Font(const SharedPtr\<FontFamily\>\&, float, FontStyle, GraphicsUnit, uint8_t, bool) constructor


Skapar en ny instans av klassen [Font](../).

```cpp
System::Drawing::Font::Font(const SharedPtr<FontFamily> &family, float em_size, FontStyle style, GraphicsUnit unit=GraphicsUnit::Point, uint8_t gdi_charset=1, bool gdi_vertical_font=false)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| familj | const SharedPtr\<FontFamily\>\& | Teckensnittsfamiljen för det nya teckensnittet |
| em_size | float | Em-storleken för det nya teckensnittet i de enheter som anges av parametern **unit** |
| stil | FontStyle | Stilen för det nya teckensnittet |
| unit | GraphicsUnit | Mäteenheterna för det nya teckensnittet |
| gdi_charset | uint8_t | En GDI-teckenuppsättning att använda för det nya teckensnittet |
| gdi_vertical_font | bool | Sant om det nya teckensnittet är härlett från ett vertikalt GDI-teckensnitt |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [FontFamily](../../fontfamily/)
* Enum [FontStyle](../../fontstyle/)
* Enum [GraphicsUnit](../../graphicsunit/)
* Class [Font](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Font::Font(const SharedPtr\<FontFamily\>\&, float, GraphicsUnit) constructor


Skapar en ny instans av klassen [Font](../).

```cpp
System::Drawing::Font::Font(const SharedPtr<FontFamily> &family, float em_size, GraphicsUnit unit=GraphicsUnit::Point)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| familj | const SharedPtr\<FontFamily\>\& | Teckensnittsfamiljen för det nya teckensnittet |
| em_size | float | Em-storleken för det nya teckensnittet i de enheter som anges av parametern **unit** |
| unit | GraphicsUnit | Mäteenheterna för det nya teckensnittet |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [FontFamily](../../fontfamily/)
* Enum [GraphicsUnit](../../graphicsunit/)
* Class [Font](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Font::Font(const String\&, float, FontStyle, GraphicsUnit, uint8_t, bool) constructor


Skapar en ny instans av klassen [Font](../).

```cpp
System::Drawing::Font::Font(const String &family_name, float em_size, FontStyle style, GraphicsUnit unit=GraphicsUnit::Point, uint8_t gdi_charset=1, bool gdi_vertical_font=false)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| family_name | const String\& | Namnet på det nya teckensnittets teckensnittsfamilj |
| em_size | float | Em-storleken för det nya teckensnittet i de enheter som anges av parametern **unit** |
| stil | FontStyle | Stilen för det nya teckensnittet |
| unit | GraphicsUnit | Mäteenheterna för det nya teckensnittet |
| gdi_charset | uint8_t | En GDI-teckenuppsättning att använda för det nya teckensnittet |
| gdi_vertical_font | bool | Sant om det nya teckensnittet är härlett från ett vertikalt GDI-teckensnitt |

## Se även

* Class [String](../../../system/string/)
* Enum [FontStyle](../../fontstyle/)
* Enum [GraphicsUnit](../../graphicsunit/)
* Class [Font](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Font::Font(const String\&, float, GraphicsUnit) constructor


Skapar en ny instans av klassen [Font](../).

```cpp
System::Drawing::Font::Font(const String &family_name, float em_size, GraphicsUnit unit=GraphicsUnit::Point)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| family_name | const String\& | Namnet på det nya teckensnittets teckensnittsfamilj |
| em_size | float | Em-storleken för det nya teckensnittet i de enheter som anges av parametern **unit** |
| unit | GraphicsUnit | Mäteenheterna för det nya teckensnittet |

## Se även

* Class [String](../../../system/string/)
* Enum [GraphicsUnit](../../graphicsunit/)
* Class [Font](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
