---
title: "System::Drawing::CopyPixelOperation‑enum"
linktitle: "CopyPixelOperation"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Drawing::CopyPixelOperation‑enum. Anger hur källfärgen i en pixelkopieringsoperation kombineras med destinationsfärgen för att resultera i en slutgiltig färg i C++."
type: docs
weight: 3000
url: /sv/cpp/system.drawing/copypixeloperation/
---
## CopyPixelOperation enum


Anger hur källfärgen i en pixelkopieringsoperation kombineras med mål‑färgen för att resultera i en slutlig färg.

```cpp
enum class CopyPixelOperation
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| NoMirrorBitmap | n/a | Bitmap‑bilden är inte speglad. |
| Blackness | 66 | Destinationsregionen fylls genom att använda färgen med index 0 i den fysiska paletten. |
| NotSourceErase | 1114278 | Käll- och destinationsfärgerna OR‑as och den resulterande färgen inverteras sedan. |
| NotSourceCopy | 3342344 | Källområdet inverteras och kopieras sedan till destinationen. |
| SourceErase | 4457256 | De inverterade färgerna i destinationsområdet ANDas med färgerna i källområdet. |
| DestinationInvert | 5570569 | Destinationsområdet inverteras. |
| PatInvert | 5898313 | Färgerna på den för närvarande valda penseln i destinationsenhetens kontext XORas med färgerna i destinationen. |
| SourceInvert | 6684742 | Färgerna i käll- och destinationsområdena XORas. |
| SourceAnd | 8913094 | Färgerna i käll- och destinationsområdena ANDas. |
| MergePaint | 12255782 | Färgerna i det inverterade källområdet ORas med färgerna i destinationsområdet. |
| MergeCopy | 12583114 | Färgerna i källområdet ANDas med färgerna på den valda penseln i destinationsenhetens kontext. |
| SourceCopy | 13369376 | Källområdet kopieras direkt till målområdet. |
| SourcePaint | 15597702 | Färgerna i käll- och målområdena kombineras med OR. |
| PatCopy | 15728673 | Penseln som för närvarande är vald i mål‑enhetens kontext kopieras till mål‑bitmapen. |
| PatPaint | 16452105 | Färgerna på penseln som för närvarande är vald i mål‑enhetens kontext kombineras med färgerna i det inverterade källområdet med OR. Resultatet av denna operation kombineras med färgerna i målområdet med OR. |
| Whiteness | 16711778 | Målområdet fylls genom att använda färgen med index 1 i den fysiska paletten. |
| CaptureBlt | 1073741824 | [Windows](../../system.windows/) som är lagrade ovanpå applikationens fönster inkluderas i den resulterande bilden. |

## Se även

* Namespace [System::Drawing](../)
* Library [Aspose.PDF for C++](../../)
