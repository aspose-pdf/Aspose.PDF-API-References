---
title: "ImageDeleteAction"
second_title: "Aspose.PDF för Python via .NET API‑referens"
description: "Åtgärd som utförs med bildobjektet när bilden tas bort från samlingen. Om bildobjektet tas bort"
type: docs
weight: 6450
url: /sv/python-net/aspose.pdf/imagedeleteaction/
---

## ImageDeleteAction enumeration

Åtgärd som utförs med bildobjektet när bilden tas bort från samlingen. Om bildobjektet tas bort

## Members
| Medlemsnamn | Beskrivning |
| :- | :- |
| KEEP_CONTENTS | Bilden kommer att tas bort från samlingen. Om sidinnehållet innehåller referenser till bilden kommer de inte att tas bort. Dokumentet kan bli ogiltigt. |
| NONE | Bilden kommer att tas bort från samlingen och från sidinnehållet, men bildobjektet kommer inte att raderas. Filstorleken kommer inte att minskas. |
| FORCE_DELETE | Bilden kommer att tas bort från samlingen och bildobjektet kommer att tas bort från dokumentet. Om andra referenser till samma objekt finns kan dokumentet bli korrupt. |
| CHECK | Bilden kommer att tas bort från samlingen och bildobjektet kommer endast att tas bort om det inte finns några andra referenser till bilden från andra sidor. Detta kan kräva mer tid jämfört med alternativet ForceDelete. |

### Se även

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

