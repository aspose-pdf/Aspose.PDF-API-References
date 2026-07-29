---
title: "HtmlLoadOptions"
linktitle: "HtmlLoadOptions"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt Optionen zum Laden/Importieren einer HTML‑Datei in ein PDF‑Dokument dar."
type: docs
weight: 1960
url: /de/java/com.aspose.pdf/htmlloadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions com.aspose.pdf.HtmlLoadOptions, com.aspose.pdf.LoadOptions, com.aspose.pdf.HtmlLoadOptions

```
public final class HtmlLoadOptions extends LoadOptions
```

Stellt Optionen zum Laden/Importieren einer HTML‑Datei in ein PDF‑Dokument dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [HtmlLoadOptions](#HtmlLoadOptions--) | Erstellt Ladeoptionen zum Konvertieren von HTML in ein PDF-Dokument mit leerem Basispfad. |
| [HtmlLoadOptions](#HtmlLoadOptions-java.lang.String-) | Erstellt Ladeoptionen zum Konvertieren von HTML in ein PDF-Dokument mit leerem Basispfad. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBasePath](#getBasePath--) | Der Basis-Pfad/URL für die HTML-Datei. |
| [getCustomLoaderOfExternalResources](#getCustomLoaderOfExternalResources--) | Manchmal ist es notwendig, die Verwendung des internen Loaders externer Ressourcen (wie Bilder oder CSS) zu vermeiden und eine benutzerdefinierte Methode bereitzustellen, die die angeforderten Ressourcen von irgendwo abruft. Zum Beispiel ist bei der Verwendung von Aspose.PDF in der Cloud der direkte Zugriff auf referenzierte Dateien unmöglich: In einem solchen Fall sollte ein vom Kunden bereitgestellter Code in eine spezielle Methode eingefügt werden, und das Delegat, das auf diese Methode verweist, muss diesem Attribut zugewiesen werden. |
| [getHtmlMediaType](#getHtmlMediaType--) | Liest oder setzt mögliche Medientypen, die beim Rendern verwendet werden. |
| [getInputEncoding](#getInputEncoding--) | Liest das Attribut, das die für dieses Dokument beim Parsen verwendete Kodierung angibt. Ist dieses Attribut null, wird die Kodierung aus dem Zeichensatz des Dokuments ermittelt. |
| [getPageInfo](#getPageInfo--) | Liest Seiteninformationen des Dokuments. |
| [getPageLayoutOption](#getPageLayoutOption--) | Liest oder setzt Layout-Option. |
| [isEmbedFonts](#isEmbedFonts--) | Liest oder setzt das Einbetten von Schriftarten in das Ergebnisdokument. |
| [isPriorityCssPageRule](#isPriorityCssPageRule--) | Liest oder setzt das Flag, das festlegt, dass @page‑Regeln, die in CSS definiert sind, Werte aus PageInfo überschreiben. |
| [isRenderToSinglePage](#isRenderToSinglePage--) | Liest oder setzt das Rendern des gesamten Dokuments auf einer einzelnen Seite. |
| [setCustomLoaderOfExternalResources](#setCustomLoaderOfExternalResources-com.aspose.pdf.LoadOptions.ResourceLoadingStrategy-) | Manchmal ist es notwendig, die Verwendung des internen Loaders externer Ressourcen (wie Bilder oder CSS) zu vermeiden und eine benutzerdefinierte Methode bereitzustellen, die die angeforderten Ressourcen von irgendwo abruft. |
| [setEmbedFonts](#setEmbedFonts-boolean-) | Liest oder setzt das Einbetten von Schriftarten in das Ergebnisdokument. |
| [setHtmlMediaType](#setHtmlMediaType-com.aspose.pdf.HtmlMediaType-) | Liest oder setzt mögliche Medientypen, die beim Rendern verwendet werden. |
| [setInputEncoding](#setInputEncoding-java.lang.String-) | Setzt das Attribut, das die für dieses Dokument beim Parsen verwendete Kodierung angibt. Ist dieses Attribut null, wird die Kodierung aus dem Zeichensatz des Dokuments ermittelt. |
| [setPageInfo](#setPageInfo-com.aspose.pdf.PageInfo-) | Setzt Seiteninformationen des Dokuments. |
| [setPageLayoutOption](#setPageLayoutOption-int-) | Liest oder setzt Layout-Option. |
| [setPriorityCssPageRule](#setPriorityCssPageRule-boolean-) | Liest oder setzt das Flag, das festlegt, dass @page‑Regeln, die in CSS definiert sind, Werte aus PageInfo überschreiben. |
| [setRenderToSinglePage](#setRenderToSinglePage-boolean-) | Liest oder setzt das Rendern des gesamten Dokuments auf einer einzelnen Seite. |

### HtmlLoadOptions {#HtmlLoadOptions--}
```
public HtmlLoadOptions()
```

Erstellt Ladeoptionen zum Konvertieren von HTML in ein PDF-Dokument mit leerem Basispfad.

### HtmlLoadOptions {#HtmlLoadOptions-java.lang.String-}
Erstellt Ladeoptionen zum Konvertieren von HTML in ein PDF-Dokument mit leerem Basispfad.

### getBasePath {#getBasePath--}
```
public String getBasePath()
```

Der Basis-Pfad/URL für die HTML-Datei.

**Returns:**
String Wert

### getCustomLoaderOfExternalResources {#getCustomLoaderOfExternalResources--}
```
public LoadOptions.ResourceLoadingStrategy getCustomLoaderOfExternalResources()
```

Manchmal ist es notwendig, die Verwendung des internen Loaders externer Ressourcen (wie Bilder oder CSS) zu vermeiden und eine benutzerdefinierte Methode bereitzustellen, die die angeforderten Ressourcen von irgendwo abruft. Zum Beispiel ist bei der Verwendung von Aspose.PDF in der Cloud der direkte Zugriff auf referenzierte Dateien unmöglich: In einem solchen Fall sollte ein vom Kunden bereitgestellter Code in eine spezielle Methode eingefügt werden, und das Delegat, das auf diese Methode verweist, muss diesem Attribut zugewiesen werden.

**Returns:**
ResourceLoadingStrategy-Instanz

### getHtmlMediaType {#getHtmlMediaType--}
```
public HtmlMediaType getHtmlMediaType()
```

Liest oder setzt mögliche Medientypen, die beim Rendern verwendet werden.

**Returns:**
HtmlMediaType-Element

### getInputEncoding {#getInputEncoding--}
```
public String getInputEncoding()
```

Liest das Attribut, das die für dieses Dokument beim Parsen verwendete Kodierung angibt. Ist dieses Attribut null, wird die Kodierung aus dem Zeichensatz des Dokuments ermittelt.

**Returns:**
String Wert

### getPageInfo {#getPageInfo--}
```
public PageInfo getPageInfo()
```

Liest Seiteninformationen des Dokuments.

**Returns:**
Seiteninformationen

### getPageLayoutOption {#getPageLayoutOption--}
```
public final int getPageLayoutOption()
```

Liest oder setzt Layout-Option.

**Returns:**
HtmlPageLayoutOption-Element @see HtmlPageLayoutOption

### isEmbedFonts {#isEmbedFonts--}
```
public final boolean isEmbedFonts()
```

Liest oder setzt das Einbetten von Schriftarten in das Ergebnisdokument.

**Returns:**
boolescher Wert

### isPriorityCssPageRule {#isPriorityCssPageRule--}
```
public final boolean isPriorityCssPageRule()
```

Liest oder setzt das Flag, das festlegt, dass @page‑Regeln, die in CSS definiert sind, Werte aus PageInfo überschreiben.

**Returns:**
boolescher Wert

### isRenderToSinglePage {#isRenderToSinglePage--}
```
public final boolean isRenderToSinglePage()
```

Liest oder setzt das Rendern des gesamten Dokuments auf einer einzelnen Seite.

**Returns:**
boolescher Wert

### setCustomLoaderOfExternalResources {#setCustomLoaderOfExternalResources-com.aspose.pdf.LoadOptions.ResourceLoadingStrategy-}
Manchmal ist es notwendig, die Verwendung des internen Loaders externer Ressourcen (wie Bilder oder CSS) zu vermeiden und eine benutzerdefinierte Methode bereitzustellen, die die angeforderten Ressourcen von irgendwo abruft.

### setEmbedFonts {#setEmbedFonts-boolean-}
```
public final void setEmbedFonts(boolean value)
```

Liest oder setzt das Einbetten von Schriftarten in das Ergebnisdokument.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setHtmlMediaType {#setHtmlMediaType-com.aspose.pdf.HtmlMediaType-}
Liest oder setzt mögliche Medientypen, die beim Rendern verwendet werden.

### setInputEncoding {#setInputEncoding-java.lang.String-}
Setzt das Attribut, das die für dieses Dokument beim Parsen verwendete Kodierung angibt. Ist dieses Attribut null, wird die Kodierung aus dem Zeichensatz des Dokuments ermittelt.

### setPageInfo {#setPageInfo-com.aspose.pdf.PageInfo-}
Setzt Seiteninformationen des Dokuments.

### setPageLayoutOption {#setPageLayoutOption-int-}
```
public final void setPageLayoutOption(int value)
```

Liest oder setzt Layout-Option.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | HtmlPageLayoutOption-Element @see HtmlPageLayoutOption |

### setPriorityCssPageRule {#setPriorityCssPageRule-boolean-}
```
public final void setPriorityCssPageRule(boolean value)
```

Liest oder setzt das Flag, das festlegt, dass @page‑Regeln, die in CSS definiert sind, Werte aus PageInfo überschreiben.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setRenderToSinglePage {#setRenderToSinglePage-boolean-}
```
public final void setRenderToSinglePage(boolean value)
```

Liest oder setzt das Rendern des gesamten Dokuments auf einer einzelnen Seite.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |
