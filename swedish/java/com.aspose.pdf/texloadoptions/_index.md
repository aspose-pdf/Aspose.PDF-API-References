---
title: "TeXLoadOptions"
linktitle: "TeXLoadOptions"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar alternativ för att ladda/importera TeX-fil till PDF-dokument."
type: docs
weight: 4870
url: /sv/java/com.aspose.pdf/texloadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions com.aspose.pdf.TeXLoadOptions, com.aspose.pdf.LoadOptions, com.aspose.pdf.TeXLoadOptions

```
public class TeXLoadOptions extends LoadOptions
```

Representerar alternativ för att ladda/importera TeX-fil till PDF-dokument.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [TeXLoadOptions](#TeXLoadOptions--) | Skapar standardladdningsalternativ för att konvertera TeX‑fil till PDF‑dokument. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getDateTime](#getDateTime--) | Hämtar/anger ett visst värde för datum/tids‑primitive som år, månad, dag och tid. |
| [getInputDirectory](#getInputDirectory--) | Hämtar/anger TeX‑indatakatalog. |
| [getJobName](#getJobName--) | Hämtar/anger namnet på jobbet. |
| [getLoadResult](#getLoadResult--) | Hämtar resultat för TeX‑laddning och kompilering – gick allt smidigt eller fanns det några kommentarer/fel. |
| [getNoLigatures](#getNoLigatures--) | Hämtar/anger en flagga som avbryter ligaturer i alla typsnitt. |
| [getOutputDirectory](#getOutputDirectory--) | Hämtar/anger TeX‑utdata‑katalog. |
| [getRasterizeFormulas](#getRasterizeFormulas--) | Hämtar/anger en flagga som möjliggör rasterisering av matematiska formler. |
| [getRepeat](#getRepeat--) | Hämtar/anger flaggan som indikerar om det är nödvändigt att köra TeX‑jobbet två gånger om exempelvis det finns referenser i indata‑TeX‑fil(er). Generellt är detta beteende användbart när motorn samlar in data under typsättningsprocessen och lagrar den i en hjälpfil under första körningen. Och vid den andra körningen använder motorn på något sätt den datan. |
| [getRequiredInputDirectory](#getRequiredInputDirectory--) | Hämtar/anger TeX‑kräver‑indatakatalog. Nödvändig indata är de filer som på något sätt inkluderas i huvud‑.tex‑filen, t.ex. paket som saknar inbyggt stöd. |
| [getShowTerminalOutput](#getShowTerminalOutput--) | Hämtar/anger flaggan som indikerar om terminalutdata ska visas i konsolen. |
| [getSubsetFonts](#getSubsetFonts--) | Hämtar/anger flaggan som indikerar om typsnitt ska delmängdas i utdatafilen eller inte. |
| [setDateTime](#setDateTime-java.util.Date-) | Hämtar/anger ett visst värde för datum/tids‑primitive som år, månad, dag och tid. |
| [setInputDirectory](#setInputDirectory-com.aspose.pdf.tex.ITeXInputDirectory-) | Hämtar/anger TeX‑indatakatalog. |
| [setJobName](#setJobName-java.lang.String-) | Hämtar/anger namnet på jobbet. |
| [setNoLigatures](#setNoLigatures-boolean-) | Hämtar/anger en flagga som avbryter ligaturer i alla typsnitt. |
| [setOutputDirectory](#setOutputDirectory-com.aspose.pdf.tex.ITeXOutputDirectory-) | Hämtar/anger TeX‑utdata‑katalog. |
| [setRasterizeFormulas](#setRasterizeFormulas-boolean-) | Hämtar/anger en flagga som möjliggör rasterisering av matematiska formler. |
| [setRepeat](#setRepeat-boolean-) | Hämtar/anger flaggan som indikerar om det är nödvändigt att köra TeX‑jobbet två gånger om exempelvis det finns referenser i indata‑TeX‑fil(er). Generellt är detta beteende användbart när motorn samlar in data under typsättningsprocessen och lagrar den i en hjälpfil under första körningen. Och vid den andra körningen använder motorn på något sätt den datan. |
| [setRequiredInputDirectory](#setRequiredInputDirectory-com.aspose.pdf.tex.ITeXInputDirectory-) | Hämtar/anger TeX‑kräver‑indatakatalog. Nödvändig indata är de filer som på något sätt inkluderas i huvud‑.tex‑filen, t.ex. paket som saknar inbyggt stöd. |
| [setShowTerminalOutput](#setShowTerminalOutput-boolean-) | Hämtar/anger flaggan som indikerar om terminalutdata ska visas i konsolen. |
| [setSubsetFonts](#setSubsetFonts-boolean-) | Hämtar/anger flaggan som indikerar om typsnitt ska delmängdas i utdatafilen eller inte. |

### TeXLoadOptions {#TeXLoadOptions--}
```
public TeXLoadOptions()
```

Skapar standardladdningsalternativ för att konvertera TeX‑fil till PDF‑dokument.

### getDateTime {#getDateTime--}
```
public final Date getDateTime()
```

Hämtar/anger ett visst värde för datum/tids‑primitive som år, månad, dag och tid.

**Returns:**
Datum‑instans

### getInputDirectory {#getInputDirectory--}
```
public final ITeXInputDirectory getInputDirectory()
```

Hämtar/anger TeX‑indatakatalog.

**Returns:**
ITeXInputDirectory‑instans

### getJobName {#getJobName--}
```
public final String getJobName()
```

Hämtar/anger namnet på jobbet.

**Returns:**
String värde

### getLoadResult {#getLoadResult--}
```
public final int getLoadResult()
```

Hämtar resultat för TeX‑laddning och kompilering – gick allt smidigt eller fanns det några kommentarer/fel.

**Returns:**
TeXLoadResult‑element

### getNoLigatures {#getNoLigatures--}
```
public final boolean getNoLigatures()
```

Hämtar/anger en flagga som avbryter ligaturer i alla typsnitt.

**Returns:**
booleskt värde

### getOutputDirectory {#getOutputDirectory--}
```
public final ITeXOutputDirectory getOutputDirectory()
```

Hämtar/anger TeX‑utdata‑katalog.

**Returns:**
ITeXOutputDirectory‑instans

### getRasterizeFormulas {#getRasterizeFormulas--}
```
public final boolean getRasterizeFormulas()
```

Hämtar/anger en flagga som möjliggör rasterisering av matematiska formler.

**Returns:**
booleskt värde

### getRepeat {#getRepeat--}
```
public final boolean getRepeat()
```

Hämtar/anger flaggan som indikerar om det är nödvändigt att köra TeX‑jobbet två gånger om exempelvis det finns referenser i indata‑TeX‑fil(er). Generellt är detta beteende användbart när motorn samlar in data under typsättningsprocessen och lagrar den i en hjälpfil under första körningen. Och vid den andra körningen använder motorn på något sätt den datan.

**Returns:**
booleskt värde

### getRequiredInputDirectory {#getRequiredInputDirectory--}
```
public final ITeXInputDirectory getRequiredInputDirectory()
```

Hämtar/anger TeX‑kräver‑indatakatalog. Nödvändig indata är de filer som på något sätt inkluderas i huvud‑.tex‑filen, t.ex. paket som saknar inbyggt stöd.

**Returns:**
ITeXInputDirectory‑instans

### getShowTerminalOutput {#getShowTerminalOutput--}
```
public final boolean getShowTerminalOutput()
```

Hämtar/anger flaggan som indikerar om terminalutdata ska visas i konsolen.

**Returns:**
booleskt värde

### getSubsetFonts {#getSubsetFonts--}
```
public final boolean getSubsetFonts()
```

Hämtar/anger flaggan som indikerar om typsnitt ska delmängdas i utdatafilen eller inte.

**Returns:**
booleskt värde

### setDateTime {#setDateTime-java.util.Date-}
Hämtar/anger ett visst värde för datum/tids‑primitive som år, månad, dag och tid.

### setInputDirectory {#setInputDirectory-com.aspose.pdf.tex.ITeXInputDirectory-}
Hämtar/anger TeX‑indatakatalog.

### setJobName {#setJobName-java.lang.String-}
Hämtar/anger namnet på jobbet.

### setNoLigatures {#setNoLigatures-boolean-}
```
public final void setNoLigatures(boolean value)
```

Hämtar/anger en flagga som avbryter ligaturer i alla typsnitt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setOutputDirectory {#setOutputDirectory-com.aspose.pdf.tex.ITeXOutputDirectory-}
Hämtar/anger TeX‑utdata‑katalog.

### setRasterizeFormulas {#setRasterizeFormulas-boolean-}
```
public final void setRasterizeFormulas(boolean value)
```

Hämtar/anger en flagga som möjliggör rasterisering av matematiska formler.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setRepeat {#setRepeat-boolean-}
```
public final void setRepeat(boolean value)
```

Hämtar/anger flaggan som indikerar om det är nödvändigt att köra TeX‑jobbet två gånger om exempelvis det finns referenser i indata‑TeX‑fil(er). Generellt är detta beteende användbart när motorn samlar in data under typsättningsprocessen och lagrar den i en hjälpfil under första körningen. Och vid den andra körningen använder motorn på något sätt den datan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setRequiredInputDirectory {#setRequiredInputDirectory-com.aspose.pdf.tex.ITeXInputDirectory-}
Hämtar/anger TeX‑kräver‑indatakatalog. Nödvändig indata är de filer som på något sätt inkluderas i huvud‑.tex‑filen, t.ex. paket som saknar inbyggt stöd.

### setShowTerminalOutput {#setShowTerminalOutput-boolean-}
```
public final void setShowTerminalOutput(boolean value)
```

Hämtar/anger flaggan som indikerar om terminalutdata ska visas i konsolen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setSubsetFonts {#setSubsetFonts-boolean-}
```
public final void setSubsetFonts(boolean value)
```

Hämtar/anger flaggan som indikerar om typsnitt ska delmängdas i utdatafilen eller inte.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |
