---
title: "System::Drawing::Graphics::MeasureString método"
linktitle: "MeasureString"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Drawing::Graphics::MeasureString método. Devuelve un tamaño de la cadena especificada cuando se dibuja con la fuente especificada en el formato especificado en C++."
type: docs
weight: 6500
url: /es/cpp/system.drawing/graphics/measurestring/
---
## Graphics::MeasureString(String const\&, System::SharedPtr\<Font\> const\&, int, System::SharedPtr\<StringFormat\> const\&) const method


Devuelve el tamaño de la cadena especificada cuando se dibuja con la fuente especificada en el formato especificado.

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, int width, System::SharedPtr<StringFormat> const &stringFormat=nullptr) const
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str | String const\& | La cadena cuyo tamaño se debe calcular |
| font | System::SharedPtr\<Font\> const\& | La fuente utilizada para dibujar la cadena |
| ancho | int | El ancho máximo de la cadena |
| stringFormat | System::SharedPtr\<StringFormat\> const\& | Especifica el formato de la cadena |

### ReturnValue

Un objeto [SizeF](../../sizef/) que representa el tamaño de la cadena en las unidades de medida especificadas por la propiedad PageUnit del objeto Grapphics actual.

## Ver también

* Class [SizeF](../../sizef/)
* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Font](../../font/)
* Class [StringFormat](../../stringformat/)
* Class [Graphics](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Graphics::MeasureString(String const\&, System::SharedPtr\<Font\> const\&, PointF const\&, System::SharedPtr\<StringFormat\> const\&) const method


Devuelve el tamaño de la cadena especificada cuando se dibuja con la fuente especificada en el formato especificado.

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, PointF const &origin=PointF(0, 0), System::SharedPtr<StringFormat> const &stringFormat=nullptr) const
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str | String const\& | La cadena cuyo tamaño se debe calcular |
| font | System::SharedPtr\<Font\> const\& | La fuente utilizada para dibujar la cadena |
| origin | PointF const\& | Especifica la ubicación de la esquina superior izquierda de la cadena |
| stringFormat | System::SharedPtr\<StringFormat\> const\& | Especifica el formato de la cadena |

### ReturnValue

Un objeto [SizeF](../../sizef/) que representa el tamaño de la cadena en las unidades de medida especificadas por la propiedad PageUnit del objeto Grapphics actual.

## Ver también

* Class [SizeF](../../sizef/)
* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Font](../../font/)
* Class [PointF](../../pointf/)
* Class [StringFormat](../../stringformat/)
* Class [Graphics](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Graphics::MeasureString(String const\&, System::SharedPtr\<Font\> const\&, SizeF const\&, System::SharedPtr\<StringFormat\> const\&, int\&, int\&) const method


NO IMPLEMENTADO.

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, SizeF const &layoutArea, System::SharedPtr<StringFormat> const &stringFormat, int &charactersFitted, int &linesFilled) const
```


## Ver también

* Class [SizeF](../../sizef/)
* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Font](../../font/)
* Class [StringFormat](../../stringformat/)
* Class [Graphics](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Graphics::MeasureString(String const\&, System::SharedPtr\<Font\> const\&, SizeF const\&, System::SharedPtr\<StringFormat\> const\&) const method


Devuelve el tamaño de la cadena especificada cuando se dibuja con la fuente especificada en el formato especificado.

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, SizeF const &layoutArea, System::SharedPtr<StringFormat> const &stringFormat=nullptr) const
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str | String const\& | La cadena cuyo tamaño se debe calcular |
| font | System::SharedPtr\<Font\> const\& | La fuente utilizada para dibujar la cadena |
| layoutArea | SizeF const\& | El área de diseño máxima de la cadena |
| stringFormat | System::SharedPtr\<StringFormat\> const\& | Especifica el formato de la cadena |

### ReturnValue

Un objeto [SizeF](../../sizef/) que representa el tamaño de la cadena en las unidades de medida especificadas por la propiedad PageUnit del objeto Grapphics actual.

## Ver también

* Class [SizeF](../../sizef/)
* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Font](../../font/)
* Class [StringFormat](../../stringformat/)
* Class [Graphics](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
