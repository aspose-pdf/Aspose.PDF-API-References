---
title: "System::Drawing::Rectangle::Inflate metod"
linktitle: "Inflate"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Drawing::Rectangle::Inflate metod. Ökar bredden och höjden på den rektangel som representeras av det aktuella objektet, samtidigt som placeringen av rektangelns geometriska centrum bibehålls. Både bredden och höjden ökas i båda riktningarna med de mängder som anges av bredd- och höjdvärdena i det angivna storleksobjektet, i C++."
type: docs
weight: 1600
url: /sv/cpp/system.drawing/rectangle/inflate/
---
## Rectangle::Inflate(const Size\&) method


Ökar bredden och höjden på rektangeln som representeras av det aktuella objektet, samtidigt som den geometriska mittens position bibehålls. Bredden och höjden ökas i båda riktningarna med de mängder som motsvarar bredd- och höjdvärden i det angivna storleksobjektet.

```cpp
void System::Drawing::Rectangle::Inflate(const Size &size)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| size | const Size\& | Det [Size](../../size/) objektet som specificerar mängderna för att öka rektangelns bredd och höjd med |

## Se även

* Class [Size](../../size/)
* Class [Rectangle](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Rectangle::Inflate(int, int) method


Ökar bredden och höjden på rektangeln som representeras av det aktuella objektet, samtidigt som den geometriska mittens position bibehålls. Bredden och höjden ökas i båda riktningarna med de angivna mängderna.

```cpp
void System::Drawing::Rectangle::Inflate(int width, int height)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bredd | int | Mängden med vilken rektangelns bredd ska ökas i båda riktningarna |
| höjd | int | Det belopp med vilket rektangelns höjd ska ökas i båda riktningarna |

## Se även

* Class [Rectangle](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Rectangle::Inflate(const Rectangle\&, int, int) method


Ökar bredden och höjden på rektangeln som representeras av det angivna objektet, samtidigt som den geometriska mittens position bibehålls. Bredden och höjden ökas i båda riktningarna med de angivna mängderna.

```cpp
static Rectangle System::Drawing::Rectangle::Inflate(const Rectangle &rect, int x, int y)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | const Rectangle\& | En rektangel att blåsa upp |
| x | int | Mängden med vilken rektangelns bredd ska ökas i båda riktningarna |
| y | int | Det belopp med vilket rektangelns höjd ska ökas i båda riktningarna |

### ReturnValue

Det [Rectangle](../) objektet som representerar den förstorade rektangeln

## Se även

* Class [Rectangle](../)
* Class [Rectangle](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
