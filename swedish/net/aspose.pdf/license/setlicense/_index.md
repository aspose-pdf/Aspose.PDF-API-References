---
title: "License.SetLicense"
second_title: "Aspose.PDF för .NET API‑referens"
description: "License-metod. Licensierar komponenten."
type: docs
weight: 40
url: /sv/net/aspose.pdf/license/setlicense/
---
## SetLicense(string) {#setlicense_1}

Licensierar komponenten.

```csharp
public void SetLicense(string licenseName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| licenseName | String | Kan vara ett fullständigt eller kort filnamn eller namn på en inbäddad resurs. Använd en tom sträng för att växla till utvärderingsläge. |

## Anmärkningar

Försöker hitta licensen på följande platser:

1. Explicit sökväg.

2. Mappen som innehåller Aspose-komponentens assembly.

3. Mappen som innehåller klientens anropande assembly.

4. Mappen som innehåller entry (startup)-assemblyn.

5. En inbäddad resurs i klientens anropande assembly.

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. Explicit sökväg.

2. En inbäddad resurs i klientens anropande assembly.

[Java]

2. Mappen som innehåller Aspose-komponentens JAR‑fil.

3. Mappen som innehåller klientens anropande JAR‑fil.

### Se även

* class [License](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SetLicense(Stream) {#setlicense}

Licensierar komponenten.

```csharp
public void SetLicense(Stream stream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | Stream | En ström som innehåller licensen. |

## Anmärkningar

Använd den här metoden för att läsa in en licens från en ström.

### Se även

* class [License](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


