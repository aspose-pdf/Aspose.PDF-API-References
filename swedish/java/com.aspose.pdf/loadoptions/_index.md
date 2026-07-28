---
title: "LoadOptions"
linktitle: "LoadOptions"
second_title: "Aspose.PDF för Java API-referens"
description: "LoadOptions-typen håller abstraktionsnivå på individuella laddningsalternativ"
type: docs
weight: 2790
url: /sv/java/com.aspose.pdf/loadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions

```
public abstract class LoadOptions extends Object
```

LoadOptions-typen håller abstraktionsnivå på individuella laddningsalternativ

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [LoadOptions](#LoadOptions--) |  |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getLoadFormat](#getLoadFormat--) | Representerar filformat som {@code LoadOptions} beskriver. |
| [getWarningHandler](#getWarningHandler--) | Återanrop för att hantera eventuella genererade varningar. WarningHandler returnerar ReturnAction‑enum‑element som specificerar antingen Continue eller Abort. Continue är standardåtgärden och Load‑operationen fortsätter, men användaren kan också returnera Abort, varvid Load‑operationen ska avbrytas. |
| [isDisableFontLicenseVerifications](#isDisableFontLicenseVerifications--) | Hämtar eller anger en flagga för att inaktivera alla licensrestriktioner för alla teckensnitt vid inläsning av filen. När {@code } tillåts att utföra operationer med ett teckensnitt som är förbjudet av teckensnittets licens, till exempel att bädda in ett teckensnitt i ett PDF‑dokument även om licensreglerna förbjuder inbäddning av detta teckensnitt. Som standard {@code }. Var försiktig när du använder denna flagga. När den är satt betyder det att personen som sätter flaggan tar fullt ansvar för eventuella licens‑/lagöverträdelser på sig själv. Så han gör det på egen risk. Det rekommenderas starkt att endast använda denna flagga när du är helt säker på att du inte bryter mot upphovsrättslagen. |
| [setDisableFontLicenseVerifications](#setDisableFontLicenseVerifications-boolean-) | Hämtar eller anger en flagga för att inaktivera alla licensrestriktioner för alla teckensnitt vid inläsning av filen. När {@code } tillåts att utföra operationer med ett teckensnitt som är förbjudet av teckensnittets licens, till exempel att bädda in ett teckensnitt i ett PDF‑dokument även om licensreglerna förbjuder inbäddning av detta teckensnitt. Som standard {@code }. Var försiktig när du använder denna flagga. När den är satt betyder det att personen som sätter flaggan tar fullt ansvar för eventuella licens‑/lagöverträdelser på sig själv. Så han gör det på egen risk. Det rekommenderas starkt att endast använda denna flagga när du är helt säker på att du inte bryter mot upphovsrättslagen. |
| [setWarningHandler](#setWarningHandler-com.aspose.pdf.WarningCallback-) | Återanrop för att hantera eventuella genererade varningar. WarningHandler returnerar ReturnAction‑enum‑element som specificerar antingen Continue eller Abort. Continue är standardåtgärden och Load‑operationen fortsätter, men användaren kan också returnera Abort, varvid Load‑operationen ska avbrytas. |

### LoadOptions {#LoadOptions--}
```
public LoadOptions()
```



### getLoadFormat {#getLoadFormat--}
```
public LoadFormat getLoadFormat()
```

Representerar filformat som {@code LoadOptions} beskriver.

**Returns:**
LoadFormat element @see LoadFormat

### getWarningHandler {#getWarningHandler--}
```
public WarningCallback getWarningHandler()
```

Återanrop för att hantera eventuella genererade varningar. WarningHandler returnerar ReturnAction‑enum‑element som specificerar antingen Continue eller Abort. Continue är standardåtgärden och Load‑operationen fortsätter, men användaren kan också returnera Abort, varvid Load‑operationen ska avbrytas.

**Returns:**
IWarningCallback‑värde

### isDisableFontLicenseVerifications {#isDisableFontLicenseVerifications--}
```
public final boolean isDisableFontLicenseVerifications()
```

Hämtar eller anger en flagga för att inaktivera alla licensrestriktioner för alla teckensnitt vid inläsning av filen. När {@code } tillåts att utföra operationer med ett teckensnitt som är förbjudet av teckensnittets licens, till exempel att bädda in ett teckensnitt i ett PDF‑dokument även om licensreglerna förbjuder inbäddning av detta teckensnitt. Som standard {@code }. Var försiktig när du använder denna flagga. När den är satt betyder det att personen som sätter flaggan tar fullt ansvar för eventuella licens‑/lagöverträdelser på sig själv. Så han gör det på egen risk. Det rekommenderas starkt att endast använda denna flagga när du är helt säker på att du inte bryter mot upphovsrättslagen.

**Returns:**
booleskt värde

### setDisableFontLicenseVerifications {#setDisableFontLicenseVerifications-boolean-}
```
public final void setDisableFontLicenseVerifications(boolean value)
```

Hämtar eller anger en flagga för att inaktivera alla licensrestriktioner för alla teckensnitt vid inläsning av filen. När {@code } tillåts att utföra operationer med ett teckensnitt som är förbjudet av teckensnittets licens, till exempel att bädda in ett teckensnitt i ett PDF‑dokument även om licensreglerna förbjuder inbäddning av detta teckensnitt. Som standard {@code }. Var försiktig när du använder denna flagga. När den är satt betyder det att personen som sätter flaggan tar fullt ansvar för eventuella licens‑/lagöverträdelser på sig själv. Så han gör det på egen risk. Det rekommenderas starkt att endast använda denna flagga när du är helt säker på att du inte bryter mot upphovsrättslagen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setWarningHandler {#setWarningHandler-com.aspose.pdf.WarningCallback-}
Återanrop för att hantera eventuella genererade varningar. WarningHandler returnerar ReturnAction‑enum‑element som specificerar antingen Continue eller Abort. Continue är standardåtgärden och Load‑operationen fortsätter, men användaren kan också returnera Abort, varvid Load‑operationen ska avbrytas.
