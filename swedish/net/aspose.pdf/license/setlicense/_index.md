---
title: License.SetLicense
second_title: Aspose.PDF for .NET API Reference
description: Licensmetod. Licensierar komponenten
type: docs
weight: 20
url: /sv/net/aspose.pdf/license/setlicense/
---
## SetLicense(string) {#setlicense_1}

Licensierar komponenten.

```csharp
public void SetLicense(string licenseName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| licenseName | Sträng | Kan vara ett fullständigt eller kort filnamn eller namnet på en inbäddad resurs. Använd en tom sträng för att växla till utvärderingsläge. |

## Kommentarer

Försöker hitta licensen på följande platser:

1. Explicit sökväg.

2. Mappen som innehåller Aspose-komponentens sammansättning.

3. Mappen som innehåller klientens anropande sammansättning.

4. Mappen som innehåller ingångs- (start) sammansättningen.

5. En inbäddad resurs i klientens anropande sammansättning.

**Obs:** På .NET Compact Framework försöker den endast hitta licensen på dessa platser:

1. Explicit sökväg.

2. En inbäddad resurs i klientens anropande sammansättning.

[Java]

2. Mappen som innehåller Aspose-komponentens JAR-fil.

3. Mappen som innehåller klientens anropande JAR-fil.

### Se Även

* klass [License](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* sammansättning [Aspose.PDF](../../../)

---

## SetLicense(Stream) {#setlicense}

Licensierar komponenten.

```csharp
public void SetLicense(Stream stream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | Ström | En ström som innehåller licensen. |

## Kommentarer

Använd denna metod för att ladda en licens från en ström.

### Se Även

* klass [License](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* sammansättning [Aspose.PDF](../../../)