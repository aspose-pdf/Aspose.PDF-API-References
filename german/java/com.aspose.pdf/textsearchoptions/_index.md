---
title: "TextSearchOptions"
linktitle: "TextSearchOptions"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt Textsuchoptionen dar"
type: docs
weight: 5290
url: /de/java/com.aspose.pdf/textsearchoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextOptions com.aspose.pdf.TextSearchOptions, com.aspose.pdf.TextOptions, com.aspose.pdf.TextSearchOptions

```
public final class TextSearchOptions extends TextOptions
```

Stellt Textsuchoptionen dar

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [TextSearchOptions](#TextSearchOptions-boolean-) | Initialisiert eine neue Instanz des {@code TextSearchOptions}-Objekts. Gibt den Modus der Verwendung regulärer Ausdrücke an. |
| [TextSearchOptions](#TextSearchOptions-com.aspose.pdf.Rectangle-) | Initialisiert eine neue Instanz des TextSearchOptions-Objekts. Gibt das Rechteck an, das den gesuchten Text begrenzt. |
| [TextSearchOptions](#TextSearchOptions-com.aspose.pdf.Rectangle-boolean-) | Initialisiert eine neue Instanz des TextSearchOptions-Objekts. Gibt das Rechteck an, das den gesuchten Text begrenzt, und den Modus der regulären Ausdrucksnutzung an. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getExcludeRectangles](#getExcludeRectangles--) | Liest oder setzt Rechtecke, deren Ränder Text von der Suche ausschließen. |
| [getIgnoreResourceFontErrors](#getIgnoreResourceFontErrors--) | Liest oder setzt den Hinweis, dass Fehler im Zusammenhang mit fehlenden Schriftarten vom Text (Fragment) Absorber ignoriert werden. true - bedeutet, dass Fehler wegen fehlender Schriftart ignoriert werden. Textsegmente, die sich auf falsche Ressourcen beziehen, werden während der Verarbeitung übersprungen. false (Standard) - ein Fehler wegen fehlender Schriftart beendet die Verarbeitung durch Auslösen einer Ausnahme. |
| [getLimitToPageBounds](#getLimitToPageBounds--) | Liest den Hinweis, dass Text innerhalb der Seitenränder gesucht wird. |
| [getLogTextExtractionErrors](#getLogTextExtractionErrors--) | Liest oder setzt den Hinweis, dass Fehler bei der Textextraktion (Dekodierung) im Text (Fragment) Absorber protokolliert werden. true - bedeutet, dass Fehler bei der Textextraktion (Dekodierung) protokolliert werden. Es kann die Leistung verringern. false (Standard) - keine Fehlerprotokollierung. |
| [getRectangle](#getRectangle--) | Ermittelt das Rechteck, das den gesuchten Text begrenzt. Die Eigenschaft kann verwendet werden, falls es erforderlich ist, den Textauszug oder den Textaustauschbereich abzugrenzen. |
| [getSearchForTextRelatedGraphics](#getSearchForTextRelatedGraphics--) | Liest oder setzt den Wert, der die Suche nach textbezogenen Grafiken (Unterstreichungen, Hintergrund usw.) während der Textsuche erlaubt. true – die Suche nach textbezogenen Grafiken wird durchgeführt (Standardwert). false – grafische Elemente, die im Quelldokument vorhanden sein können, werden ignoriert. Aktivieren Sie dies bei Leistungsproblemen oder wenn Unterstreichungen, Hintergrund oder Beschneidung nicht benötigt werden. |
| [getStoredGraphicElementsMaxCount](#getStoredGraphicElementsMaxCount--) | Ermittelt den Wert, der die Suche nach textbezogenen Grafiken (Unterstreichungen, Hintergrund usw.) auf einer Seite auf die angegebene Anzahl von Elementen begrenzt. Der Standardwert ist 250. Setzen Sie einen kleineren Wert bei Leistungsproblemen, probieren Sie einen größeren Wert, falls einige grafische Elemente nicht gefunden wurden. |
| [getUseFontEngineEncoding](#getUseFontEngineEncoding--) | Ermittelt die Angabe, dass der Text mit der Schrift-Engine-Kodierung durchsucht wird. true – bedeutet, dass die Schrift-Engine-Kodierung verwendet wird (versuchen Sie dies, wenn die Textsuche wegen fehlerhafter Kodierung im Dokument fehlschlägt). false – bedeutet, dass die Dokumenten-Schriftkodierung verwendet wird (Standardwert). |
| [isDotallMode](#isDotallMode--) | <p> Im Dotall‑Modus stimmt der Ausdruck <tt>.</tt> mit jedem Zeichen überein, einschließlich eines Zeilenumbruchs. Standardmäßig stimmt dieser Ausdruck nicht mit Zeilenumbrüchen überein. |
| [isIgnoreShadowText](#isIgnoreShadowText--) | Liest oder setzt die Angabe, dass Textfragmente, die den Schatten von normalem Text darstellen, bei der Suche ignoriert werden. true – bedeutet, dass Schatten‑Text nicht gefunden wird (versuchen Sie dies, wenn die Textsuche duplizierte Fragmente an nahen Positionen zurückgibt). false – bedeutet, dass Schatten‑Text ebenso wie normaler Text gefunden wird (Standardwert). |
| [isRegularExpressionUsed](#isRegularExpressionUsed--) | Gibt an, ob ein regulärer Ausdruck verwendet wird oder nicht. |
| [isSearchInAnnotations](#isSearchInAnnotations--) | Liest oder setzt den Wert, der die Suche nach Text in Anmerkungen erlaubt. true – Text wird in Anmerkungen gesucht. false – Text in Anmerkungen wird vom TextFragmentAbsorber nicht analysiert. |
| [setDotallMode](#setDotallMode-boolean-) | Aktiviert den Dotall‑Modus. <p> Im Dotall‑Modus stimmt der Ausdruck <tt>.</tt> mit jedem Zeichen überein, einschließlich eines Zeilenumbruchs. Standardmäßig stimmt dieser Ausdruck nicht mit Zeilenumbrüchen überein. |
| [setExcludeRectangles](#setExcludeRectangles-com.aspose.pdf.Rectangle:A-) | Liest oder setzt Rechtecke, deren Ränder Text von der Suche ausschließen. |
| [setIgnoreResourceFontErrors](#setIgnoreResourceFontErrors-boolean-) | Liest oder setzt den Hinweis, dass Fehler im Zusammenhang mit fehlenden Schriftarten vom Text (Fragment) Absorber ignoriert werden. true - bedeutet, dass Fehler wegen fehlender Schriftart ignoriert werden. Textsegmente, die sich auf falsche Ressourcen beziehen, werden während der Verarbeitung übersprungen. false (Standard) - ein Fehler wegen fehlender Schriftart beendet die Verarbeitung durch Auslösen einer Ausnahme. |
| [setIgnoreShadowText](#setIgnoreShadowText-boolean-) | Liest oder setzt die Angabe, dass Textfragmente, die den Schatten von normalem Text darstellen, bei der Suche ignoriert werden. true – bedeutet, dass Schatten‑Text nicht gefunden wird (versuchen Sie dies, wenn die Textsuche duplizierte Fragmente an nahen Positionen zurückgibt). false – bedeutet, dass Schatten‑Text ebenso wie normaler Text gefunden wird (Standardwert). |
| [setLimitToPageBounds](#setLimitToPageBounds-boolean-) | Setzt die Angabe, dass der Text innerhalb der Seitenbegrenzungen durchsucht wird. |
| [setLogTextExtractionErrors](#setLogTextExtractionErrors-boolean-) | Liest oder setzt den Hinweis, dass Fehler bei der Textextraktion (Dekodierung) im Text (Fragment) Absorber protokolliert werden. true - bedeutet, dass Fehler bei der Textextraktion (Dekodierung) protokolliert werden. Es kann die Leistung verringern. false (Standard) - keine Fehlerprotokollierung. |
| [setRectangle](#setRectangle-com.aspose.pdf.Rectangle-) | Setzt das Rechteck, das den gesuchten Text begrenzt. Die Eigenschaft kann verwendet werden, falls es erforderlich ist, den Textauszug oder den Textaustauschbereich abzugrenzen. |
| [setRegularExpressionUsed](#setRegularExpressionUsed-boolean-) | Gibt an, ob ein regulärer Ausdruck verwendet wird oder nicht. |
| [setSearchForTextRelatedGraphics](#setSearchForTextRelatedGraphics-boolean-) | Liest oder setzt den Wert, der die Suche nach textbezogenen Grafiken (Unterstreichungen, Hintergrund usw.) während der Textsuche erlaubt. true – die Suche nach textbezogenen Grafiken wird durchgeführt (Standardwert). false – grafische Elemente, die im Quelldokument vorhanden sein können, werden ignoriert. Aktivieren Sie dies bei Leistungsproblemen oder wenn Unterstreichungen, Hintergrund oder Beschneidung nicht benötigt werden. |
| [setSearchInAnnotations](#setSearchInAnnotations-boolean-) | Liest oder setzt den Wert, der die Suche nach Text in Anmerkungen erlaubt. true – Text wird in Anmerkungen gesucht. false – Text in Anmerkungen wird vom TextFragmentAbsorber nicht analysiert. |
| [setStoredGraphicElementsMaxCount](#setStoredGraphicElementsMaxCount-int-) | Setzt den Wert, der die Suche nach textbezogenen Grafiken (Unterstreichungen, Hintergrund usw.) auf einer Seite auf die angegebene Anzahl von Elementen begrenzt. Der Standardwert ist 250. Setzen Sie einen kleineren Wert bei Leistungsproblemen, probieren Sie einen größeren Wert, falls einige grafische Elemente nicht gefunden wurden. |
| [setUseFontEngineEncoding](#setUseFontEngineEncoding-boolean-) | Setzt die Angabe, dass der Text mit der Schrift‑Engine‑Kodierung durchsucht wird. true – bedeutet, dass die Schrift‑Engine‑Kodierung verwendet wird (versuchen Sie dies, wenn die Textsuche wegen fehlerhafter Kodierung im Dokument fehlschlägt). false – bedeutet, dass die Dokumenten‑Schriftkodierung verwendet wird (Standardwert). |

### TextSearchOptions {#TextSearchOptions-boolean-}
```
public TextSearchOptions(boolean isRegularExpressionUsed)
```

Initialisiert eine neue Instanz des {@code TextSearchOptions}-Objekts. Gibt den Modus der Verwendung regulärer Ausdrücke an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| isRegularExpressionUsed |  | Wert, der angibt, dass ein regulärer Ausdruck verwendet wird. |

### TextSearchOptions {#TextSearchOptions-com.aspose.pdf.Rectangle-}
Initialisiert eine neue Instanz des TextSearchOptions-Objekts. Gibt das Rechteck an, das den gesuchten Text begrenzt.

### TextSearchOptions {#TextSearchOptions-com.aspose.pdf.Rectangle-boolean-}
Initialisiert eine neue Instanz des TextSearchOptions-Objekts. Gibt das Rechteck an, das den gesuchten Text begrenzt, und den Modus der regulären Ausdrucksnutzung an.

### getExcludeRectangles {#getExcludeRectangles--}
```
public final Rectangle [] getExcludeRectangles()
```

Liest oder setzt Rechtecke, deren Ränder Text von der Suche ausschließen.

**Returns:**
Array von Rectangle‑Instanzen

### getIgnoreResourceFontErrors {#getIgnoreResourceFontErrors--}
```
public final boolean getIgnoreResourceFontErrors()
```

Liest oder setzt den Hinweis, dass Fehler im Zusammenhang mit fehlenden Schriftarten vom Text (Fragment) Absorber ignoriert werden. true - bedeutet, dass Fehler wegen fehlender Schriftart ignoriert werden. Textsegmente, die sich auf falsche Ressourcen beziehen, werden während der Verarbeitung übersprungen. false (Standard) - ein Fehler wegen fehlender Schriftart beendet die Verarbeitung durch Auslösen einer Ausnahme.

**Returns:**
boolescher Wert

### getLimitToPageBounds {#getLimitToPageBounds--}
```
public boolean getLimitToPageBounds()
```

Liest den Hinweis, dass Text innerhalb der Seitenränder gesucht wird.

**Returns:**
boolescher Wert

### getLogTextExtractionErrors {#getLogTextExtractionErrors--}
```
public boolean getLogTextExtractionErrors()
```

Liest oder setzt den Hinweis, dass Fehler bei der Textextraktion (Dekodierung) im Text (Fragment) Absorber protokolliert werden. true - bedeutet, dass Fehler bei der Textextraktion (Dekodierung) protokolliert werden. Es kann die Leistung verringern. false (Standard) - keine Fehlerprotokollierung.

**Returns:**
boolescher Wert

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Ermittelt das Rechteck, das den gesuchten Text begrenzt. Die Eigenschaft kann verwendet werden, falls es erforderlich ist, den Textauszug oder den Textaustauschbereich abzugrenzen.

**Returns:**
Rechteckwert

### getSearchForTextRelatedGraphics {#getSearchForTextRelatedGraphics--}
```
public final boolean getSearchForTextRelatedGraphics()
```

Liest oder setzt den Wert, der die Suche nach textbezogenen Grafiken (Unterstreichungen, Hintergrund usw.) während der Textsuche erlaubt. true – die Suche nach textbezogenen Grafiken wird durchgeführt (Standardwert). false – grafische Elemente, die im Quelldokument vorhanden sein können, werden ignoriert. Aktivieren Sie dies bei Leistungsproblemen oder wenn Unterstreichungen, Hintergrund oder Beschneidung nicht benötigt werden.

**Returns:**
boolescher Wert

### getStoredGraphicElementsMaxCount {#getStoredGraphicElementsMaxCount--}
```
public final int getStoredGraphicElementsMaxCount()
```

Ermittelt den Wert, der die Suche nach textbezogenen Grafiken (Unterstreichungen, Hintergrund usw.) auf einer Seite auf die angegebene Anzahl von Elementen begrenzt. Der Standardwert ist 250. Setzen Sie einen kleineren Wert bei Leistungsproblemen, probieren Sie einen größeren Wert, falls einige grafische Elemente nicht gefunden wurden.

**Returns:**
int-Wert

### getUseFontEngineEncoding {#getUseFontEngineEncoding--}
```
public boolean getUseFontEngineEncoding()
```

Ermittelt die Angabe, dass der Text mit der Schrift-Engine-Kodierung durchsucht wird. true – bedeutet, dass die Schrift-Engine-Kodierung verwendet wird (versuchen Sie dies, wenn die Textsuche wegen fehlerhafter Kodierung im Dokument fehlschlägt). false – bedeutet, dass die Dokumenten-Schriftkodierung verwendet wird (Standardwert).

**Returns:**
boolescher Wert

### isDotallMode {#isDotallMode--}
```
public static boolean isDotallMode()
```

<p> Im Dotall‑Modus stimmt der Ausdruck <tt>.</tt> mit jedem Zeichen überein, einschließlich eines Zeilenumbruchs. Standardmäßig stimmt dieser Ausdruck nicht mit Zeilenumbrüchen überein.

**Returns:**
boolescher Wert

### isIgnoreShadowText {#isIgnoreShadowText--}
```
public boolean isIgnoreShadowText()
```

Liest oder setzt die Angabe, dass Textfragmente, die den Schatten von normalem Text darstellen, bei der Suche ignoriert werden. true – bedeutet, dass Schatten‑Text nicht gefunden wird (versuchen Sie dies, wenn die Textsuche duplizierte Fragmente an nahen Positionen zurückgibt). false – bedeutet, dass Schatten‑Text ebenso wie normaler Text gefunden wird (Standardwert).

**Returns:**
boolescher Wert

### isRegularExpressionUsed {#isRegularExpressionUsed--}
```
public boolean isRegularExpressionUsed()
```

Gibt an, ob ein regulärer Ausdruck verwendet wird oder nicht.

**Returns:**
boolescher Wert

### isSearchInAnnotations {#isSearchInAnnotations--}
```
public final boolean isSearchInAnnotations()
```

Liest oder setzt den Wert, der die Suche nach Text in Anmerkungen erlaubt. true – Text wird in Anmerkungen gesucht. false – Text in Anmerkungen wird vom TextFragmentAbsorber nicht analysiert.

**Returns:**
boolescher Wert

### setDotallMode {#setDotallMode-boolean-}
```
public static void setDotallMode(boolean dotallMode)
```

Aktiviert den Dotall‑Modus. <p> Im Dotall‑Modus stimmt der Ausdruck <tt>.</tt> mit jedem Zeichen überein, einschließlich eines Zeilenumbruchs. Standardmäßig stimmt dieser Ausdruck nicht mit Zeilenumbrüchen überein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dotallMode |  | boolescher Wert |

### setExcludeRectangles {#setExcludeRectangles-com.aspose.pdf.Rectangle:A-}
Liest oder setzt Rechtecke, deren Ränder Text von der Suche ausschließen.

### setIgnoreResourceFontErrors {#setIgnoreResourceFontErrors-boolean-}
```
public final void setIgnoreResourceFontErrors(boolean value)
```

Liest oder setzt den Hinweis, dass Fehler im Zusammenhang mit fehlenden Schriftarten vom Text (Fragment) Absorber ignoriert werden. true - bedeutet, dass Fehler wegen fehlender Schriftart ignoriert werden. Textsegmente, die sich auf falsche Ressourcen beziehen, werden während der Verarbeitung übersprungen. false (Standard) - ein Fehler wegen fehlender Schriftart beendet die Verarbeitung durch Auslösen einer Ausnahme.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setIgnoreShadowText {#setIgnoreShadowText-boolean-}
```
public void setIgnoreShadowText(boolean value)
```

Liest oder setzt die Angabe, dass Textfragmente, die den Schatten von normalem Text darstellen, bei der Suche ignoriert werden. true – bedeutet, dass Schatten‑Text nicht gefunden wird (versuchen Sie dies, wenn die Textsuche duplizierte Fragmente an nahen Positionen zurückgibt). false – bedeutet, dass Schatten‑Text ebenso wie normaler Text gefunden wird (Standardwert).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setLimitToPageBounds {#setLimitToPageBounds-boolean-}
```
public void setLimitToPageBounds(boolean value)
```

Setzt die Angabe, dass der Text innerhalb der Seitenbegrenzungen durchsucht wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setLogTextExtractionErrors {#setLogTextExtractionErrors-boolean-}
```
public void setLogTextExtractionErrors(boolean value)
```

Liest oder setzt den Hinweis, dass Fehler bei der Textextraktion (Dekodierung) im Text (Fragment) Absorber protokolliert werden. true - bedeutet, dass Fehler bei der Textextraktion (Dekodierung) protokolliert werden. Es kann die Leistung verringern. false (Standard) - keine Fehlerprotokollierung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setRectangle {#setRectangle-com.aspose.pdf.Rectangle-}
Setzt das Rechteck, das den gesuchten Text begrenzt. Die Eigenschaft kann verwendet werden, falls es erforderlich ist, den Textauszug oder den Textaustauschbereich abzugrenzen.

### setRegularExpressionUsed {#setRegularExpressionUsed-boolean-}
```
public void setRegularExpressionUsed(boolean value)
```

Gibt an, ob ein regulärer Ausdruck verwendet wird oder nicht.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setSearchForTextRelatedGraphics {#setSearchForTextRelatedGraphics-boolean-}
```
public final void setSearchForTextRelatedGraphics(boolean value)
```

Liest oder setzt den Wert, der die Suche nach textbezogenen Grafiken (Unterstreichungen, Hintergrund usw.) während der Textsuche erlaubt. true – die Suche nach textbezogenen Grafiken wird durchgeführt (Standardwert). false – grafische Elemente, die im Quelldokument vorhanden sein können, werden ignoriert. Aktivieren Sie dies bei Leistungsproblemen oder wenn Unterstreichungen, Hintergrund oder Beschneidung nicht benötigt werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setSearchInAnnotations {#setSearchInAnnotations-boolean-}
```
public final void setSearchInAnnotations(boolean value)
```

Liest oder setzt den Wert, der die Suche nach Text in Anmerkungen erlaubt. true – Text wird in Anmerkungen gesucht. false – Text in Anmerkungen wird vom TextFragmentAbsorber nicht analysiert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setStoredGraphicElementsMaxCount {#setStoredGraphicElementsMaxCount-int-}
```
public final void setStoredGraphicElementsMaxCount(int value)
```

Setzt den Wert, der die Suche nach textbezogenen Grafiken (Unterstreichungen, Hintergrund usw.) auf einer Seite auf die angegebene Anzahl von Elementen begrenzt. Der Standardwert ist 250. Setzen Sie einen kleineren Wert bei Leistungsproblemen, probieren Sie einen größeren Wert, falls einige grafische Elemente nicht gefunden wurden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert |

### setUseFontEngineEncoding {#setUseFontEngineEncoding-boolean-}
```
public void setUseFontEngineEncoding(boolean value)
```

Setzt die Angabe, dass der Text mit der Schrift‑Engine‑Kodierung durchsucht wird. true – bedeutet, dass die Schrift‑Engine‑Kodierung verwendet wird (versuchen Sie dies, wenn die Textsuche wegen fehlerhafter Kodierung im Dokument fehlschlägt). false – bedeutet, dass die Dokumenten‑Schriftkodierung verwendet wird (Standardwert).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |
