---
title: "XImage.TrySetAlternativeText"
second_title: "Aspose.PDF för .NET API‑referens"
description: "XImage-metod. Ställer in alternativ text för en XImage på sidan"
type: docs
weight: 180
url: /sv/net/aspose.pdf/ximage/trysetalternativetext/
---
## XImage.TrySetAlternativeText method

Ställer in alternativ text för en XImage på sidan.

```csharp
public bool TrySetAlternativeText(string alternativeText, Page page)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| alternativeText | String | Den alternativa texten som ska specificeras. |
| sida | Page | Sida där XImage är placerad. |

### Returvärde

Sant om alternativeText för XImage är angivet. Falskt om alternativeText för XImage inte är angivet.

## Anmärkningar

Metoden returnerar falskt i följande fall: - XImage hittas inte på den angivna sidan. - XImage förekommer flera gånger på sidan med olika strukturella element, vilket gör det oklart vilken instans som ska få den alternativa texten.

### Se även

* class [Page](../../page/)
* class [XImage](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


