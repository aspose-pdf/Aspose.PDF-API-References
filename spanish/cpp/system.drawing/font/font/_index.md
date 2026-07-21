---
title: "System::Drawing::Font::Font constructor"
linktitle: "Fuente"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Drawing::Font::Font constructor. Construye una nueva instancia de la clase Font que representa la fuente existente especificada con el estilo de fuente especificado en C++."
type: docs
weight: 100
url: /es/cpp/system.drawing/font/font/
---
## Font::Font(const SharedPtr\<Font\>\&, FontStyle) constructor


Construye una nueva instancia de la clase [Font](../) que representa la fuente existente especificada con el estilo de fuente especificado.

```cpp
System::Drawing::Font::Font(const SharedPtr<Font> &prototype, FontStyle new_style)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| prototype | const SharedPtr\<Font\>\& | La fuente existente de la cual crear la nueva |
| new_style | FontStyle | Un estilo de fuente para aplicar a la nueva fuente |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Font](../)
* Enum [FontStyle](../../fontstyle/)
* Class [Font](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Font::Font(const SharedPtr\<FontFamily\>\&, float, FontStyle, GraphicsUnit, uint8_t, bool) constructor


Construye una nueva instancia de la clase [Font](../).

```cpp
System::Drawing::Font::Font(const SharedPtr<FontFamily> &family, float em_size, FontStyle style, GraphicsUnit unit=GraphicsUnit::Point, uint8_t gdi_charset=1, bool gdi_vertical_font=false)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| familia | const SharedPtr\<FontFamily\>\& | La familia de fuentes de la nueva fuente |
| em_size | float | El tamaño em de la nueva fuente en las unidades especificadas por el parámetro **unit** |
| estilo | FontStyle | El estilo de la nueva fuente |
| unit | GraphicsUnit | Las unidades de medida de la nueva fuente |
| gdi_charset | uint8_t | Un conjunto de caracteres GDI para usar con la nueva fuente |
| gdi_vertical_font | bool | Verdadero si la nueva fuente se deriva de una fuente vertical GDI |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [FontFamily](../../fontfamily/)
* Enum [FontStyle](../../fontstyle/)
* Enum [GraphicsUnit](../../graphicsunit/)
* Class [Font](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Font::Font(const SharedPtr\<FontFamily\>\&, float, GraphicsUnit) constructor


Construye una nueva instancia de la clase [Font](../).

```cpp
System::Drawing::Font::Font(const SharedPtr<FontFamily> &family, float em_size, GraphicsUnit unit=GraphicsUnit::Point)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| familia | const SharedPtr\<FontFamily\>\& | La familia de fuentes de la nueva fuente |
| em_size | float | El tamaño em de la nueva fuente en las unidades especificadas por el parámetro **unit** |
| unit | GraphicsUnit | Las unidades de medida de la nueva fuente |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [FontFamily](../../fontfamily/)
* Enum [GraphicsUnit](../../graphicsunit/)
* Class [Font](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Font::Font(const String\&, float, FontStyle, GraphicsUnit, uint8_t, bool) constructor


Construye una nueva instancia de la clase [Font](../).

```cpp
System::Drawing::Font::Font(const String &family_name, float em_size, FontStyle style, GraphicsUnit unit=GraphicsUnit::Point, uint8_t gdi_charset=1, bool gdi_vertical_font=false)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| family_name | const String\& | El nombre de la familia de fuentes de la nueva fuente |
| em_size | float | El tamaño em de la nueva fuente en las unidades especificadas por el parámetro **unit** |
| estilo | FontStyle | El estilo de la nueva fuente |
| unit | GraphicsUnit | Las unidades de medida de la nueva fuente |
| gdi_charset | uint8_t | Un conjunto de caracteres GDI para usar con la nueva fuente |
| gdi_vertical_font | bool | Verdadero si la nueva fuente se deriva de una fuente vertical GDI |

## Ver también

* Class [String](../../../system/string/)
* Enum [FontStyle](../../fontstyle/)
* Enum [GraphicsUnit](../../graphicsunit/)
* Class [Font](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Font::Font(const String\&, float, GraphicsUnit) constructor


Construye una nueva instancia de la clase [Font](../).

```cpp
System::Drawing::Font::Font(const String &family_name, float em_size, GraphicsUnit unit=GraphicsUnit::Point)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| family_name | const String\& | El nombre de la familia de fuentes de la nueva fuente |
| em_size | float | El tamaño em de la nueva fuente en las unidades especificadas por el parámetro **unit** |
| unit | GraphicsUnit | Las unidades de medida de la nueva fuente |

## Ver también

* Class [String](../../../system/string/)
* Enum [GraphicsUnit](../../graphicsunit/)
* Class [Font](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
