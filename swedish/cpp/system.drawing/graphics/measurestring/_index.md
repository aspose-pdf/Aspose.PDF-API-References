---
title: "System::Drawing::Graphics::MeasureString metod"
linktitle: "MeasureString"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Drawing::Graphics::MeasureString metod. Returnerar en storlek för den angivna strängen när den ritas med det angivna teckensnittet i det angivna formatet i C++."
type: docs
weight: 6500
url: /sv/cpp/system.drawing/graphics/measurestring/
---
## Graphics::MeasureString(String const\&, System::SharedPtr\<Font\> const\&, int, System::SharedPtr\<StringFormat\> const\&) const method


Returnerar storleken på den angivna strängen när den ritas med det angivna typsnittet i det angivna formatet.

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, int width, System::SharedPtr<StringFormat> const &stringFormat=nullptr) const
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str | String const\& | Strängen vars storlek ska beräknas |
| teckensnitt | System::SharedPtr\<Font\> const\& | Teckensnittet som används för att rita strängen |
| bredd | int | Den maximala bredden på strängen |
| stringFormat | System::SharedPtr\<StringFormat\> const\& | Anger strängformatet |

### ReturnValue

Ett [SizeF](../../sizef/)‑objekt som representerar storleken på strängen i de mätenheter som anges av PageUnit‑egenskapen för det aktuella Grapphics‑objektet.

## Se även

* Class [SizeF](../../sizef/)
* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Font](../../font/)
* Class [StringFormat](../../stringformat/)
* Class [Graphics](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Graphics::MeasureString(String const\&, System::SharedPtr\<Font\> const\&, PointF const\&, System::SharedPtr\<StringFormat\> const\&) const method


Returnerar storleken på den angivna strängen när den ritas med det angivna typsnittet i det angivna formatet.

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, PointF const &origin=PointF(0, 0), System::SharedPtr<StringFormat> const &stringFormat=nullptr) const
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str | String const\& | Strängen vars storlek ska beräknas |
| teckensnitt | System::SharedPtr\<Font\> const\& | Teckensnittet som används för att rita strängen |
| origin | PointF const\\& | Anger platsen för strängens övre vänstra hörn |
| stringFormat | System::SharedPtr\<StringFormat\> const\& | Anger strängformatet |

### ReturnValue

Ett [SizeF](../../sizef/)‑objekt som representerar storleken på strängen i de mätenheter som anges av PageUnit‑egenskapen för det aktuella Grapphics‑objektet.

## Se även

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


INTE IMPLEMENTERAD.

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, SizeF const &layoutArea, System::SharedPtr<StringFormat> const &stringFormat, int &charactersFitted, int &linesFilled) const
```


## Se även

* Class [SizeF](../../sizef/)
* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Font](../../font/)
* Class [StringFormat](../../stringformat/)
* Class [Graphics](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Graphics::MeasureString(String const\&, System::SharedPtr\<Font\> const\&, SizeF const\&, System::SharedPtr\<StringFormat\> const\&) const method


Returnerar storleken på den angivna strängen när den ritas med det angivna typsnittet i det angivna formatet.

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, SizeF const &layoutArea, System::SharedPtr<StringFormat> const &stringFormat=nullptr) const
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str | String const\& | Strängen vars storlek ska beräknas |
| teckensnitt | System::SharedPtr\<Font\> const\& | Teckensnittet som används för att rita strängen |
| layoutArea | SizeF const\\& | Det maximala layout‑området för strängen |
| stringFormat | System::SharedPtr\<StringFormat\> const\& | Anger strängformatet |

### ReturnValue

Ett [SizeF](../../sizef/)‑objekt som representerar storleken på strängen i de mätenheter som anges av PageUnit‑egenskapen för det aktuella Grapphics‑objektet.

## Se även

* Class [SizeF](../../sizef/)
* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Font](../../font/)
* Class [StringFormat](../../stringformat/)
* Class [Graphics](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
