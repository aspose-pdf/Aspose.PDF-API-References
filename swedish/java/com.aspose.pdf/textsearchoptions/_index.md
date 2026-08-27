---
title: "TextSearchOptions"
linktitle: "TextSearchOptions"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar alternativ för textsökning"
type: docs
weight: 5290
url: /sv/java/com.aspose.pdf/textsearchoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextOptions com.aspose.pdf.TextSearchOptions, com.aspose.pdf.TextOptions, com.aspose.pdf.TextSearchOptions

```
public final class TextSearchOptions extends TextOptions
```

Representerar alternativ för textsökning

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [TextSearchOptions](#TextSearchOptions-boolean-) | Initierar en ny instans av {@code TextSearchOptions}-objektet. Anger läge för användning av reguljära uttryck. |
| [TextSearchOptions](#TextSearchOptions-com.aspose.pdf.Rectangle-) | Initierar en ny instans av TextSearchOptions-objektet. Anger rektangel som avgränsar den sökta texten. |
| [TextSearchOptions](#TextSearchOptions-com.aspose.pdf.Rectangle-boolean-) | Initierar en ny instans av TextSearchOptions-objektet. Anger rektangel som avgränsar den sökta texten och läge för användning av reguljära uttryck. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getExcludeRectangles](#getExcludeRectangles--) | Hämtar eller anger rektanglar vars kanter utesluter text från sökningen. |
| [getIgnoreResourceFontErrors](#getIgnoreResourceFontErrors--) | Hämtar eller anger indikation på att fel relaterade till avsaknad av teckensnitt kommer att ignoreras av text (fragment) absorberaren. true - betyder att fel på avsaknad av teckensnitt kommer att ignoreras. Textsegment som refererar till felaktiga resurser kommer att hoppas över under bearbetning. false (standard) - fel om avsaknad av teckensnitt kommer att avsluta bearbetning genom att kasta ett undantag. |
| [getLimitToPageBounds](#getLimitToPageBounds--) | Hämtar indikation på att text söks inom sidans gränser. |
| [getLogTextExtractionErrors](#getLogTextExtractionErrors--) | Hämtar eller anger indikation på att fel vid textextraktion (avkodning) kommer att loggas i text (fragment) absorberaren. true - betyder att fel vid textextraktion (avkodning) kommer att loggas. Det kan minska prestanda. false (standard) - ingen felloggning. |
| [getRectangle](#getRectangle--) | Hämtar rektangeln som avgränsar den sökta texten. Egenskapen kan användas om det krävs att avgränsa textextraktion eller textersättningsområde. |
| [getSearchForTextRelatedGraphics](#getSearchForTextRelatedGraphics--) | Hämtar eller anger värdet som tillåter sökning efter textrelaterad grafik (understrykning, bakgrund osv.) under textsökning. true - sökning efter textrelaterad grafik kommer att utföras (standardvärde). false - grafiska element som kan finnas i källdokumentet kommer att ignoreras. Ställ in detta vid prestandaproblem eller om det inte behövs att hantera understrykning, bakgrund eller beskärning. |
| [getStoredGraphicElementsMaxCount](#getStoredGraphicElementsMaxCount--) | Hämtar värdet som begränsar sökningen efter textrelaterad grafik (understrykning, bakgrund osv.) på en sida till det angivna antalet element. Standardvärdet är 250. Ange ett lägre värde vid prestandaproblem, prova ett högre värde om vissa grafiska element inte hittades. |
| [getUseFontEngineEncoding](#getUseFontEngineEncoding--) | Hämtar indikation på att text kommer att sökas med teckensnittsmotorns kodning. true - betyder att teckensnittsmotorns kodning kommer att användas (prova detta om textsökning misslyckas på grund av bristfällig kodning i dokumentet). false - betyder att dokumentets teckensnittskodning kommer att användas (standardvärde). |
| [isDotallMode](#isDotallMode--) | <p> I dotall‑läge matchar uttrycket <tt>.</tt> vilket tecken som helst, inklusive en radavslutare. Som standard matchar detta uttryck inte radavslutare. |
| [isIgnoreShadowText](#isIgnoreShadowText--) | Hämtar eller anger indikation på att textfragment som representerar skugga av normal text kommer att ignoreras under sökning. true - betyder att skuggtext inte kommer att hittas (prova detta om textsökning returnerar duplicerade fragment på nära positioner). false - betyder att skuggtext kommer att hittas liksom normal text (standardvärde). |
| [isRegularExpressionUsed](#isRegularExpressionUsed--) | Anger om reguljärt uttryck används eller inte |
| [isSearchInAnnotations](#isSearchInAnnotations--) | Hämtar eller anger värdet som tillåter sökning efter text i Annotations. true - text kommer att sökas i Annotations. false - text i Annotations kommer inte att parsas av TextFragmentAbsorber. |
| [setDotallMode](#setDotallMode-boolean-) | Aktiverar dotall‑läge. <p> I dotall‑läge matchar uttrycket <tt>.</tt> vilket tecken som helst, inklusive en radavslutare. Som standard matchar detta uttryck inte radavslutare. |
| [setExcludeRectangles](#setExcludeRectangles-com.aspose.pdf.Rectangle:A-) | Hämtar eller anger rektanglar vars kanter utesluter text från sökningen. |
| [setIgnoreResourceFontErrors](#setIgnoreResourceFontErrors-boolean-) | Hämtar eller anger indikation på att fel relaterade till avsaknad av teckensnitt kommer att ignoreras av text (fragment) absorberaren. true - betyder att fel på avsaknad av teckensnitt kommer att ignoreras. Textsegment som refererar till felaktiga resurser kommer att hoppas över under bearbetning. false (standard) - fel om avsaknad av teckensnitt kommer att avsluta bearbetning genom att kasta ett undantag. |
| [setIgnoreShadowText](#setIgnoreShadowText-boolean-) | Hämtar eller anger indikation på att textfragment som representerar skugga av normal text kommer att ignoreras under sökning. true - betyder att skuggtext inte kommer att hittas (prova detta om textsökning returnerar duplicerade fragment på nära positioner). false - betyder att skuggtext kommer att hittas liksom normal text (standardvärde). |
| [setLimitToPageBounds](#setLimitToPageBounds-boolean-) | Anger indikation på att text söks inom sidans gränser. |
| [setLogTextExtractionErrors](#setLogTextExtractionErrors-boolean-) | Hämtar eller anger indikation på att fel vid textextraktion (avkodning) kommer att loggas i text (fragment) absorberaren. true - betyder att fel vid textextraktion (avkodning) kommer att loggas. Det kan minska prestanda. false (standard) - ingen felloggning. |
| [setRectangle](#setRectangle-com.aspose.pdf.Rectangle-) | Anger rektangeln som avgränsar den sökta texten. Egenskapen kan användas om det krävs att avgränsa textextraktion eller textersättningsområde. |
| [setRegularExpressionUsed](#setRegularExpressionUsed-boolean-) | Anger om reguljärt uttryck används eller inte |
| [setSearchForTextRelatedGraphics](#setSearchForTextRelatedGraphics-boolean-) | Hämtar eller anger värdet som tillåter sökning efter textrelaterad grafik (understrykning, bakgrund osv.) under textsökning. true - sökning efter textrelaterad grafik kommer att utföras (standardvärde). false - grafiska element som kan finnas i källdokumentet kommer att ignoreras. Ställ in detta vid prestandaproblem eller om det inte behövs att hantera understrykning, bakgrund eller beskärning. |
| [setSearchInAnnotations](#setSearchInAnnotations-boolean-) | Hämtar eller anger värdet som tillåter sökning efter text i Annotations. true - text kommer att sökas i Annotations. false - text i Annotations kommer inte att parsas av TextFragmentAbsorber. |
| [setStoredGraphicElementsMaxCount](#setStoredGraphicElementsMaxCount-int-) | Anger värdet som begränsar sökningen efter textrelaterad grafik (understrykning, bakgrund osv.) på en sida till det angivna antalet element. Standardvärdet är 250. Ange ett lägre värde vid prestandaproblem, prova ett högre värde om vissa grafiska element inte hittades. |
| [setUseFontEngineEncoding](#setUseFontEngineEncoding-boolean-) | Anger indikation på att text kommer att sökas med teckensnittsmotorns kodning. true - betyder att teckensnittsmotorns kodning kommer att användas (prova detta om textsökning misslyckas på grund av bristfällig kodning i dokumentet). false - betyder att dokumentets teckensnittskodning kommer att användas (standardvärde). |

### TextSearchOptions {#TextSearchOptions-boolean-}
```
public TextSearchOptions(boolean isRegularExpressionUsed)
```

Initierar en ny instans av {@code TextSearchOptions}-objektet. Anger läge för användning av reguljära uttryck.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| isRegularExpressionUsed |  | Värde som indikerar att reguljärt uttryck används. |

### TextSearchOptions {#TextSearchOptions-com.aspose.pdf.Rectangle-}
Initierar en ny instans av TextSearchOptions-objektet. Anger rektangel som avgränsar den sökta texten.

### TextSearchOptions {#TextSearchOptions-com.aspose.pdf.Rectangle-boolean-}
Initierar en ny instans av TextSearchOptions-objektet. Anger rektangel som avgränsar den sökta texten och läge för användning av reguljära uttryck.

### getExcludeRectangles {#getExcludeRectangles--}
```
public final Rectangle [] getExcludeRectangles()
```

Hämtar eller anger rektanglar vars kanter utesluter text från sökningen.

**Returns:**
array av Rectangle‑instanser

### getIgnoreResourceFontErrors {#getIgnoreResourceFontErrors--}
```
public final boolean getIgnoreResourceFontErrors()
```

Hämtar eller anger indikation på att fel relaterade till avsaknad av teckensnitt kommer att ignoreras av text (fragment) absorberaren. true - betyder att fel på avsaknad av teckensnitt kommer att ignoreras. Textsegment som refererar till felaktiga resurser kommer att hoppas över under bearbetning. false (standard) - fel om avsaknad av teckensnitt kommer att avsluta bearbetning genom att kasta ett undantag.

**Returns:**
booleskt värde

### getLimitToPageBounds {#getLimitToPageBounds--}
```
public boolean getLimitToPageBounds()
```

Hämtar indikation på att text söks inom sidans gränser.

**Returns:**
booleskt värde

### getLogTextExtractionErrors {#getLogTextExtractionErrors--}
```
public boolean getLogTextExtractionErrors()
```

Hämtar eller anger indikation på att fel vid textextraktion (avkodning) kommer att loggas i text (fragment) absorberaren. true - betyder att fel vid textextraktion (avkodning) kommer att loggas. Det kan minska prestanda. false (standard) - ingen felloggning.

**Returns:**
booleskt värde

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Hämtar rektangeln som avgränsar den sökta texten. Egenskapen kan användas om det krävs att avgränsa textextraktion eller textersättningsområde.

**Returns:**
Rektangelvärde

### getSearchForTextRelatedGraphics {#getSearchForTextRelatedGraphics--}
```
public final boolean getSearchForTextRelatedGraphics()
```

Hämtar eller anger värdet som tillåter sökning efter textrelaterad grafik (understrykning, bakgrund osv.) under textsökning. true - sökning efter textrelaterad grafik kommer att utföras (standardvärde). false - grafiska element som kan finnas i källdokumentet kommer att ignoreras. Ställ in detta vid prestandaproblem eller om det inte behövs att hantera understrykning, bakgrund eller beskärning.

**Returns:**
booleskt värde

### getStoredGraphicElementsMaxCount {#getStoredGraphicElementsMaxCount--}
```
public final int getStoredGraphicElementsMaxCount()
```

Hämtar värdet som begränsar sökningen efter textrelaterad grafik (understrykning, bakgrund osv.) på en sida till det angivna antalet element. Standardvärdet är 250. Ange ett lägre värde vid prestandaproblem, prova ett högre värde om vissa grafiska element inte hittades.

**Returns:**
int‑värde

### getUseFontEngineEncoding {#getUseFontEngineEncoding--}
```
public boolean getUseFontEngineEncoding()
```

Hämtar indikation på att text kommer att sökas med teckensnittsmotorns kodning. true - betyder att teckensnittsmotorns kodning kommer att användas (prova detta om textsökning misslyckas på grund av bristfällig kodning i dokumentet). false - betyder att dokumentets teckensnittskodning kommer att användas (standardvärde).

**Returns:**
booleskt värde

### isDotallMode {#isDotallMode--}
```
public static boolean isDotallMode()
```

<p> I dotall‑läge matchar uttrycket <tt>.</tt> vilket tecken som helst, inklusive en radavslutare. Som standard matchar detta uttryck inte radavslutare.

**Returns:**
booleskt värde

### isIgnoreShadowText {#isIgnoreShadowText--}
```
public boolean isIgnoreShadowText()
```

Hämtar eller anger indikation på att textfragment som representerar skugga av normal text kommer att ignoreras under sökning. true - betyder att skuggtext inte kommer att hittas (prova detta om textsökning returnerar duplicerade fragment på nära positioner). false - betyder att skuggtext kommer att hittas liksom normal text (standardvärde).

**Returns:**
booleskt värde

### isRegularExpressionUsed {#isRegularExpressionUsed--}
```
public boolean isRegularExpressionUsed()
```

Anger om reguljärt uttryck används eller inte

**Returns:**
booleskt värde

### isSearchInAnnotations {#isSearchInAnnotations--}
```
public final boolean isSearchInAnnotations()
```

Hämtar eller anger värdet som tillåter sökning efter text i Annotations. true - text kommer att sökas i Annotations. false - text i Annotations kommer inte att parsas av TextFragmentAbsorber.

**Returns:**
booleskt värde

### setDotallMode {#setDotallMode-boolean-}
```
public static void setDotallMode(boolean dotallMode)
```

Aktiverar dotall‑läge. <p> I dotall‑läge matchar uttrycket <tt>.</tt> vilket tecken som helst, inklusive en radavslutare. Som standard matchar detta uttryck inte radavslutare.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dotallMode |  | booleskt värde |

### setExcludeRectangles {#setExcludeRectangles-com.aspose.pdf.Rectangle:A-}
Hämtar eller anger rektanglar vars kanter utesluter text från sökningen.

### setIgnoreResourceFontErrors {#setIgnoreResourceFontErrors-boolean-}
```
public final void setIgnoreResourceFontErrors(boolean value)
```

Hämtar eller anger indikation på att fel relaterade till avsaknad av teckensnitt kommer att ignoreras av text (fragment) absorberaren. true - betyder att fel på avsaknad av teckensnitt kommer att ignoreras. Textsegment som refererar till felaktiga resurser kommer att hoppas över under bearbetning. false (standard) - fel om avsaknad av teckensnitt kommer att avsluta bearbetning genom att kasta ett undantag.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setIgnoreShadowText {#setIgnoreShadowText-boolean-}
```
public void setIgnoreShadowText(boolean value)
```

Hämtar eller anger indikation på att textfragment som representerar skugga av normal text kommer att ignoreras under sökning. true - betyder att skuggtext inte kommer att hittas (prova detta om textsökning returnerar duplicerade fragment på nära positioner). false - betyder att skuggtext kommer att hittas liksom normal text (standardvärde).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setLimitToPageBounds {#setLimitToPageBounds-boolean-}
```
public void setLimitToPageBounds(boolean value)
```

Anger indikation på att text söks inom sidans gränser.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setLogTextExtractionErrors {#setLogTextExtractionErrors-boolean-}
```
public void setLogTextExtractionErrors(boolean value)
```

Hämtar eller anger indikation på att fel vid textextraktion (avkodning) kommer att loggas i text (fragment) absorberaren. true - betyder att fel vid textextraktion (avkodning) kommer att loggas. Det kan minska prestanda. false (standard) - ingen felloggning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setRectangle {#setRectangle-com.aspose.pdf.Rectangle-}
Anger rektangeln som avgränsar den sökta texten. Egenskapen kan användas om det krävs att avgränsa textextraktion eller textersättningsområde.

### setRegularExpressionUsed {#setRegularExpressionUsed-boolean-}
```
public void setRegularExpressionUsed(boolean value)
```

Anger om reguljärt uttryck används eller inte

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setSearchForTextRelatedGraphics {#setSearchForTextRelatedGraphics-boolean-}
```
public final void setSearchForTextRelatedGraphics(boolean value)
```

Hämtar eller anger värdet som tillåter sökning efter textrelaterad grafik (understrykning, bakgrund osv.) under textsökning. true - sökning efter textrelaterad grafik kommer att utföras (standardvärde). false - grafiska element som kan finnas i källdokumentet kommer att ignoreras. Ställ in detta vid prestandaproblem eller om det inte behövs att hantera understrykning, bakgrund eller beskärning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setSearchInAnnotations {#setSearchInAnnotations-boolean-}
```
public final void setSearchInAnnotations(boolean value)
```

Hämtar eller anger värdet som tillåter sökning efter text i Annotations. true - text kommer att sökas i Annotations. false - text i Annotations kommer inte att parsas av TextFragmentAbsorber.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setStoredGraphicElementsMaxCount {#setStoredGraphicElementsMaxCount-int-}
```
public final void setStoredGraphicElementsMaxCount(int value)
```

Anger värdet som begränsar sökningen efter textrelaterad grafik (understrykning, bakgrund osv.) på en sida till det angivna antalet element. Standardvärdet är 250. Ange ett lägre värde vid prestandaproblem, prova ett högre värde om vissa grafiska element inte hittades.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde |

### setUseFontEngineEncoding {#setUseFontEngineEncoding-boolean-}
```
public void setUseFontEngineEncoding(boolean value)
```

Anger indikation på att text kommer att sökas med teckensnittsmotorns kodning. true - betyder att teckensnittsmotorns kodning kommer att användas (prova detta om textsökning misslyckas på grund av bristfällig kodning i dokumentet). false - betyder att dokumentets teckensnittskodning kommer att användas (standardvärde).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |
