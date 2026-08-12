---
title: "Aspose::Pdf::PageExtensions::DuplicateIntersectingGraphics‑metod"
linktitle: "DuplicateIntersectingGraphics"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::PageExtensions::DuplicateIntersectingGraphics‑metod. Hittar alla vektorgrafikelement som skär den angivna regionen och skapar deras kopior med förskjutning från de ursprungliga positionerna i C++."
type: docs
weight: 100
url: /sv/cpp/aspose.pdf/pageextensions/duplicateintersectinggraphics/
---
## PageExtensions::DuplicateIntersectingGraphics method


Hittar alla vektorgrafikelement som skär den angivna regionen och skapar deras kopior med förskjutning från originalpositionerna.

```cpp
static void Aspose::Pdf::PageExtensions::DuplicateIntersectingGraphics(const System::SharedPtr<Page> &page, const System::SharedPtr<Rectangle> &region, double deltaX, double deltaY)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sida | const System::SharedPtr\<Page\>\& | Sidan där grafikelement söks och kopieras till. |
| region | const System::SharedPtr\<Rectangle\>\& | Det rektangulära området för att söka efter skärande element. |
| deltaX | double | Förskjutning längs X‑axeln för kopierade element. |
| deltaY | double | Förskjutning längs Y‑axeln för kopierade element. |
## Anmärkningar



Denna metod fungerar endast med vektorgrafik (linjer, former, Bézierkurvor osv.). Rasterbilder och andra typer av element behandlas inte. Varje kopierat element kommer att förskjutas med de angivna dx‑ och dy‑värdena i förhållande till sin ursprungliga position. De ursprungliga elementen förblir oförändrade.
## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Page](../../page/)
* Class [Rectangle](../../rectangle/)
* Class [PageExtensions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
