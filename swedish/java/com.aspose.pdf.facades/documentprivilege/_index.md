---
title: "DocumentPrivilege"
linktitle: "DocumentPrivilege"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar behörigheterna för åtkomst till Pdf‑filen. Se {@code PdfFileSecurity}. Det finns 4 sätt att använda denna klass: 1. Använda fördefinierad behörighet direkt. 2. Baserat på en."
type: docs
weight: 110
url: /sv/java/com.aspose.pdf.facades/documentprivilege/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.DocumentPrivilege

**All Implemented Interfaces:**
Comparable < Object >

```
public final class DocumentPrivilege extends Object implements Comparable < Object >
```

Representerar behörigheterna för åtkomst till Pdf fil. Referera till{@code PdfFileSecurity}. Det finns 4 sätt att använda denna klass: 1. Använda fördefinierad behörighet direkt. 2. Baserat på en fördefinierad behörighet och ändra vissa specifika rättigheter. 3. Baserat på en fördefinierad behörighet och ändra en specifik kombination av Adobe Professional‑rättigheter. 4. Kombinerar sätt 2 och sätt 3. //Way1: Använda fördefinierad behörighet direkt. DocumentPrivilege privilege = DocumentPrivilege.getPrint(); //Way2: Baserat på en fördefinierad behörighet och ändra vissa specifika rättigheter. DocumentPrivilege privilege = DocumentPrivilege.getAllowAll(); privilege.setAllowPrint(false); privilege.setAllowModifyContents(false); //Way3: Baserat på en fördefinierad behörighet och ändra en specifik kombination av Adobe Professional‑rättigheter. DocumentPrivilege privilege = DocumentPrivilege.getForbidAll(); privilege.setChangeAllowLevel(1); privilege.setPrintAllowLevel(2); //Way4: Kombinerar sätt 2 och sätt 3 DocumentPrivilege privilege = DocumentPrivilege.getForbidAll(); privilege.setChangeAllowLevel(1); privilege.setAllowPrint(true);

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [compareTo](#compareTo-java.lang.Object-) | Jämför två {@code DocumentPrivilege}-objekt. |
| [equals](#equals-java.lang.Object-) | Indikerar om ett annat objekt är "lika med" detta. <p> Metoden <code>equals</code> implementerar en ekvivalensrelation på icke‑null objektreferenser: <ul> <li>Den är <i>reflexiv</i>: för varje icke‑null referensvärde <code>x</code>, bör <code>x.equals(x)</code> returnera <code>true</code>. <li>Den är <i>symmetrisk</i>: för varje icke‑null referensvärden <code>x</code> och <code>y</code>, bör <code>x.equals(y)</code> returnera <code>true</code> om och endast om <code>y.equals(x)</code> returnerar <code>true</code>. <li>Den är <i>transitiv</i>: för varje icke‑null referensvärden <code>x</code>, <code>y</code> och <code>z</code>, om <code>x.equals(y)</code> returnerar <code>true</code> och <code>y.equals(z)</code> returnerar <code>true</code>, bör <code>x.equals(z)</code> returnera <code>true</code>. <li>Den är <i>konsekvent</i>: för varje icke‑null referensvärden <code>x</code> och <code>y</code>, ger flera anrop av <tt>x.equals(y)</tt> konsekvent <code>true</code> eller konsekvent <code>false</code>, förutsatt att ingen information som används i <code>equals</code>-jämförelser på objekten har ändrats. <li>För varje icke‑null referensvärde <code>x</code>, bör <code>x.equals(null)</code> returnera <code>false</code>. </ul> <p> Metoden <tt>equals</tt> för klassen <code>Object</code> implementerar den mest diskriminerande möjliga ekvivalensrelationen på objekt; det vill säga, för varje icke‑null referensvärden <code>x</code> och <code>y</code>, returnerar denna metod <code>true</code> om och endast om <code>x</code> och <code>y</code> refererar till samma objekt (<code>x == y</code> har värdet <code>true</code>). <p> Observera att det i allmänhet är nödvändigt att åsidosätta metoden <tt>hashCode</tt> när denna metod åsidosätts, för att upprätthålla det allmänna kontraktet för <tt>hashCode</tt>-metoden, vilket anger att lika objekt måste ha lika hash‑koder. |
| [getAllowAll](#getAllowAll--) | Allt tillåtet. |
| [getAssembly](#getAssembly--) | Tillåter montering av fil. |
| [getChangeAllowLevel](#getChangeAllowLevel--) | Hämtar och anger ändringsnivån för dokumentets behörighet. Samma som Adobe Professionals inställningar för Tillåtna ändringar. 0: Ingen. 1: Infoga, ta bort och rotera sidor. 2: Fyll i formulärfält och signera befintliga signaturfält. 3: Kommentera, fylla i formulärfält och signera befintliga signaturfält. 4: Allt förutom att extrahera sidor. Om egenskapen har värdet -1 är nivån odefinierad. |
| [getCopy](#getCopy--) | Tillåter kopiering av fil. |
| [getCopyAllowLevel](#getCopyAllowLevel--) | Hämtar och anger kopieringsnivån för dokumentets behörighet. Samma som Adobe Professionals behörighetsinställningar. 0: Ingen. 1: Aktivera textåtkomst för skärmläsarenheter för synskadade. 2: Aktivera kopiering av text, bilder och annat innehåll. Om egenskapen har värdet -1 är nivån odefinierad. |
| [getDegradedPrinting](#getDegradedPrinting--) | Tillåter nedsatt utskrift. |
| [getFillIn](#getFillIn--) | Tillåter ifyllning av formulär i fil. |
| [getForbidAll](#getForbidAll--) | Allt förbjudet. |
| [getModifyAnnotations](#getModifyAnnotations--) | Tillåter ändring av filens annotationer. |
| [getModifyContents](#getModifyContents--) | Tillåter ändring av fil. |
| [getPrint](#getPrint--) | Tillåter utskrift av fil. |
| [getPrintAllowLevel](#getPrintAllowLevel--) | Hämtar och anger utskriftsnivån för dokumentets behörighet. Samma som Adobe Professionals inställningar för Tillåten utskrift. 0: Ingen. 1: Låg upplösning (150 dpi). 2: Hög upplösning. Om egenskapen har värdet -1 är nivån odefinierad. |
| [getScreenReaders](#getScreenReaders--) | Tillåter endast läsning på skärmen. |
| [getValue](#getValue--) |  |
| [hashCode](#hashCode--) | Returnerar ett hashkodvärde för objektet. Denna metod stöds för fördelarna med hashtabeller såsom de som tillhandahålls av <code>java.util.Hashtable</code>. <p> Det allmänna kontraktet för <code>hashCode</code> är: <ul> <li>När den anropas på samma objekt mer än en gång under en körning av en Java-applikation, måste <tt>hashCode</tt>-metoden konsekvent returnera samma heltal, förutsatt att ingen information som används i <tt>equals</tt>-jämförelser på objektet har ändrats. Detta heltal behöver inte förbli konsekvent från en körning av en applikation till en annan körning av samma applikation. <li>Om två objekt är lika enligt <tt>equals(Object)</tt>-metoden, måste anrop av <code>hashCode</code>-metoden på var och en av de två objekten producera samma heltalsresultat. <li>Det är <em>inte</em> ett krav att om två objekt är ojämna enligt {@link java.lang.Object#equals(java.lang.Object)}-metoden, så måste anrop av <tt>hashCode</tt>-metoden på var och en av de två objekten producera olika heltalsresultat. Däremot bör programmeraren vara medveten om att producera olika heltalsresultat för ojämna objekt kan förbättra prestandan för hashtabeller. </ul> <p> Så långt som rimligt praktiskt är, returnerar hashCode-metoden som definieras av klassen <tt>Object</tt> olika heltal för olika objekt. (Detta implementeras vanligtvis genom att konvertera objektets interna adress till ett heltal, men denna implementeringsteknik krävs inte av Java<span style=\"font-size:70%\"><sup>TM</sup></span>-programspråket.) |
| [isAllowAssembly](#isAllowAssembly--) | Ställer in behörigheten som tillåter montering eller inte. true betyder tillåten och false betyder förbjuden. |
| [isAllowCopy](#isAllowCopy--) | Ställer in behörigheten som tillåter kopiering eller inte. true betyder tillåten och false betyder förbjuden. |
| [isAllowDegradedPrinting](#isAllowDegradedPrinting--) | Ställer in behörigheten som tillåter degraderad utskrift eller inte. true betyder tillåten och false betyder förbjuden. När den är inställd kommer utskrift att begränsas till en lågupplöst representation av utseendet, eventuellt med försämrad kvalitet. |
| [isAllowFillIn](#isAllowFillIn--) | Ställer in behörigheten som tillåter ifyllning av formulär eller inte. true betyder tillåten och false betyder förbjuden. |
| [isAllowModifyAnnotations](#isAllowModifyAnnotations--) | Ställer in behörigheten som tillåter ändring av annotationer eller inte. true betyder tillåten och false betyder förbjuden. |
| [isAllowModifyContents](#isAllowModifyContents--) | Ställer in behörigheten som tillåter ändring av innehåll eller inte. true betyder tillåten och false betyder förbjuden. |
| [isAllowPrint](#isAllowPrint--) | Ställer in behörigheten som tillåter utskrift eller inte. true betyder tillåten och false betyder förbjuden. |
| [isAllowScreenReaders](#isAllowScreenReaders--) | Ställer in behörigheten som tillåter skärmläsare eller inte. true betyder tillåten och false betyder förbjuden. |
| [setAllowAssembly](#setAllowAssembly-boolean-) | Ställer in behörigheten som tillåter montering eller inte. true betyder tillåten och false betyder förbjuden. |
| [setAllowCopy](#setAllowCopy-boolean-) | Ställer in behörigheten som tillåter kopiering eller inte. true betyder tillåten och false betyder förbjuden. |
| [setAllowDegradedPrinting](#setAllowDegradedPrinting-boolean-) | Ställer in behörigheten som tillåter degraderad utskrift eller inte. true betyder tillåten och false betyder förbjuden. När den är inställd kommer utskrift att begränsas till en lågupplöst representation av utseendet, eventuellt med försämrad kvalitet. |
| [setAllowFillIn](#setAllowFillIn-boolean-) | Ställer in behörigheten som tillåter ifyllning av formulär eller inte. true betyder tillåten och false betyder förbjuden. |
| [setAllowModifyAnnotations](#setAllowModifyAnnotations-boolean-) | Ställer in behörigheten som tillåter ändring av annotationer eller inte. true betyder tillåten och false betyder förbjuden. |
| [setAllowModifyContents](#setAllowModifyContents-boolean-) | Ställer in behörigheten som tillåter ändring av innehåll eller inte. true betyder tillåten och false betyder förbjuden. |
| [setAllowPrint](#setAllowPrint-boolean-) | Ställer in behörigheten som tillåter utskrift eller inte. true betyder tillåten och false betyder förbjuden. |
| [setAllowScreenReaders](#setAllowScreenReaders-boolean-) | Ställer in behörigheten som tillåter skärmläsare eller inte. true betyder tillåten och false betyder förbjuden. |
| [setChangeAllowLevel](#setChangeAllowLevel-int-) | Hämtar och anger ändringsnivån för dokumentets behörighet. Samma som Adobe Professionals inställningar för Tillåtna ändringar. 0: Ingen. 1: Infoga, ta bort och rotera sidor. 2: Fyll i formulärfält och signera befintliga signaturfält. 3: Kommentera, fylla i formulärfält och signera befintliga signaturfält. 4: Allt förutom att extrahera sidor. Om egenskapen har värdet -1 är nivån odefinierad. |
| [setCopyAllowLevel](#setCopyAllowLevel-int-) | Hämtar och anger kopieringsnivån för dokumentets behörighet. Samma som Adobe Professionals behörighetsinställningar. 0: Ingen. 1: Aktivera textåtkomst för skärmläsarenheter för synskadade. 2: Aktivera kopiering av text, bilder och annat innehåll. Om egenskapen har värdet -1 är nivån odefinierad. |
| [setPrintAllowLevel](#setPrintAllowLevel-int-) | Hämtar och anger utskriftsnivån för dokumentets behörighet. Samma som Adobe Professionals inställningar för Tillåten utskrift. 0: Ingen. 1: Låg upplösning (150 dpi). 2: Hög upplösning. Om egenskapen har värdet -1 är nivån odefinierad. |

### compareTo {#compareTo-java.lang.Object-}
Jämför två {@code DocumentPrivilege}-objekt.

### equals {#equals-java.lang.Object-}
Indikerar om ett annat objekt är "lika med" detta. <p> Metoden <code>equals</code> implementerar en ekvivalensrelation på icke‑null objektreferenser: <ul> <li>Den är <i>reflexiv</i>: för varje icke‑null referensvärde <code>x</code>, bör <code>x.equals(x)</code> returnera <code>true</code>. <li>Den är <i>symmetrisk</i>: för varje icke‑null referensvärden <code>x</code> och <code>y</code>, bör <code>x.equals(y)</code> returnera <code>true</code> om och endast om <code>y.equals(x)</code> returnerar <code>true</code>. <li>Den är <i>transitiv</i>: för varje icke‑null referensvärden <code>x</code>, <code>y</code> och <code>z</code>, om <code>x.equals(y)</code> returnerar <code>true</code> och <code>y.equals(z)</code> returnerar <code>true</code>, bör <code>x.equals(z)</code> returnera <code>true</code>. <li>Den är <i>konsekvent</i>: för varje icke‑null referensvärden <code>x</code> och <code>y</code>, ger flera anrop av <tt>x.equals(y)</tt> konsekvent <code>true</code> eller konsekvent <code>false</code>, förutsatt att ingen information som används i <code>equals</code>-jämförelser på objekten har ändrats. <li>För varje icke‑null referensvärde <code>x</code>, bör <code>x.equals(null)</code> returnera <code>false</code>. </ul> <p> Metoden <tt>equals</tt> för klassen <code>Object</code> implementerar den mest diskriminerande möjliga ekvivalensrelationen på objekt; det vill säga, för varje icke‑null referensvärden <code>x</code> och <code>y</code>, returnerar denna metod <code>true</code> om och endast om <code>x</code> och <code>y</code> refererar till samma objekt (<code>x == y</code> har värdet <code>true</code>). <p> Observera att det i allmänhet är nödvändigt att åsidosätta metoden <tt>hashCode</tt> när denna metod åsidosätts, för att upprätthålla det allmänna kontraktet för <tt>hashCode</tt>-metoden, vilket anger att lika objekt måste ha lika hash‑koder.

### getAllowAll {#getAllowAll--}
```
public static DocumentPrivilege getAllowAll()
```

Allt tillåtet.

**Returns:**
DocumentPrivilege-element

### getAssembly {#getAssembly--}
```
public static DocumentPrivilege getAssembly()
```

Tillåter montering av fil.

**Returns:**
DocumentPrivilege-element

### getChangeAllowLevel {#getChangeAllowLevel--}
```
public final int getChangeAllowLevel()
```

Hämtar och anger ändringsnivån för dokumentets behörighet. Samma som Adobe Professionals inställningar för Tillåtna ändringar. 0: Ingen. 1: Infoga, ta bort och rotera sidor. 2: Fyll i formulärfält och signera befintliga signaturfält. 3: Kommentera, fylla i formulärfält och signera befintliga signaturfält. 4: Allt förutom att extrahera sidor. Om egenskapen har värdet -1 är nivån odefinierad.

**Returns:**
int‑värde

### getCopy {#getCopy--}
```
public static DocumentPrivilege getCopy()
```

Tillåter kopiering av fil.

**Returns:**
DocumentPrivilege-element

### getCopyAllowLevel {#getCopyAllowLevel--}
```
public final int getCopyAllowLevel()
```

Hämtar och anger kopieringsnivån för dokumentets behörighet. Samma som Adobe Professionals behörighetsinställningar. 0: Ingen. 1: Aktivera textåtkomst för skärmläsarenheter för synskadade. 2: Aktivera kopiering av text, bilder och annat innehåll. Om egenskapen har värdet -1 är nivån odefinierad.

**Returns:**
int‑värde

### getDegradedPrinting {#getDegradedPrinting--}
```
public static DocumentPrivilege getDegradedPrinting()
```

Tillåter nedsatt utskrift.

**Returns:**
DocumentPrivilege-element

### getFillIn {#getFillIn--}
```
public static DocumentPrivilege getFillIn()
```

Tillåter ifyllning av formulär i fil.

**Returns:**
DocumentPrivilege-element

### getForbidAll {#getForbidAll--}
```
public static DocumentPrivilege getForbidAll()
```

Allt förbjudet.

**Returns:**
DocumentPrivilege-element

### getModifyAnnotations {#getModifyAnnotations--}
```
public static DocumentPrivilege getModifyAnnotations()
```

Tillåter ändring av filens annotationer.

**Returns:**
DocumentPrivilege-element

### getModifyContents {#getModifyContents--}
```
public static DocumentPrivilege getModifyContents()
```

Tillåter ändring av fil.

**Returns:**
DocumentPrivilege-element

### getPrint {#getPrint--}
```
public static DocumentPrivilege getPrint()
```

Tillåter utskrift av fil.

**Returns:**
DocumentPrivilege-element

### getPrintAllowLevel {#getPrintAllowLevel--}
```
public final int getPrintAllowLevel()
```

Hämtar och anger utskriftsnivån för dokumentets behörighet. Samma som Adobe Professionals inställningar för Tillåten utskrift. 0: Ingen. 1: Låg upplösning (150 dpi). 2: Hög upplösning. Om egenskapen har värdet -1 är nivån odefinierad.

**Returns:**
int‑värde

### getScreenReaders {#getScreenReaders--}
```
public static DocumentPrivilege getScreenReaders()
```

Tillåter endast läsning på skärmen.

**Returns:**
DocumentPrivilege-element

### getValue {#getValue--}
```
public final int getValue()
```



### hashCode {#hashCode--}
```
public int hashCode()
```

Returnerar ett hashkodvärde för objektet. Denna metod stöds för fördelarna med hashtabeller såsom de som tillhandahålls av <code>java.util.Hashtable</code>. <p> Det allmänna kontraktet för <code>hashCode</code> är: <ul> <li>När den anropas på samma objekt mer än en gång under en körning av en Java-applikation, måste <tt>hashCode</tt>-metoden konsekvent returnera samma heltal, förutsatt att ingen information som används i <tt>equals</tt>-jämförelser på objektet har ändrats. Detta heltal behöver inte förbli konsekvent från en körning av en applikation till en annan körning av samma applikation. <li>Om två objekt är lika enligt <tt>equals(Object)</tt>-metoden, måste anrop av <code>hashCode</code>-metoden på var och en av de två objekten producera samma heltalsresultat. <li>Det är <em>inte</em> ett krav att om två objekt är ojämna enligt {@link java.lang.Object#equals(java.lang.Object)}-metoden, så måste anrop av <tt>hashCode</tt>-metoden på var och en av de två objekten producera olika heltalsresultat. Däremot bör programmeraren vara medveten om att producera olika heltalsresultat för ojämna objekt kan förbättra prestandan för hashtabeller. </ul> <p> Så långt som rimligt praktiskt är, returnerar hashCode-metoden som definieras av klassen <tt>Object</tt> olika heltal för olika objekt. (Detta implementeras vanligtvis genom att konvertera objektets interna adress till ett heltal, men denna implementeringsteknik krävs inte av Java<span style=\"font-size:70%\"><sup>TM</sup></span>-programspråket.)

**Returns:**
ett hashkodvärde för detta objekt. @see java.lang.Object#equals(java.lang.Object) @see java.util.Hashtable

### isAllowAssembly {#isAllowAssembly--}
```
public boolean isAllowAssembly()
```

Ställer in behörigheten som tillåter montering eller inte. true betyder tillåten och false betyder förbjuden.

**Returns:**
booleskt värde

### isAllowCopy {#isAllowCopy--}
```
public boolean isAllowCopy()
```

Ställer in behörigheten som tillåter kopiering eller inte. true betyder tillåten och false betyder förbjuden.

**Returns:**
booleskt värde

### isAllowDegradedPrinting {#isAllowDegradedPrinting--}
```
public boolean isAllowDegradedPrinting()
```

Ställer in behörigheten som tillåter degraderad utskrift eller inte. true betyder tillåten och false betyder förbjuden. När den är inställd kommer utskrift att begränsas till en lågupplöst representation av utseendet, eventuellt med försämrad kvalitet.

**Returns:**
booleskt värde

### isAllowFillIn {#isAllowFillIn--}
```
public boolean isAllowFillIn()
```

Ställer in behörigheten som tillåter ifyllning av formulär eller inte. true betyder tillåten och false betyder förbjuden.

**Returns:**
booleskt värde

### isAllowModifyAnnotations {#isAllowModifyAnnotations--}
```
public boolean isAllowModifyAnnotations()
```

Ställer in behörigheten som tillåter ändring av annotationer eller inte. true betyder tillåten och false betyder förbjuden.

**Returns:**
booleskt värde

### isAllowModifyContents {#isAllowModifyContents--}
```
public boolean isAllowModifyContents()
```

Ställer in behörigheten som tillåter ändring av innehåll eller inte. true betyder tillåten och false betyder förbjuden.

**Returns:**
booleskt värde

### isAllowPrint {#isAllowPrint--}
```
public boolean isAllowPrint()
```

Ställer in behörigheten som tillåter utskrift eller inte. true betyder tillåten och false betyder förbjuden.

**Returns:**
booleskt värde

### isAllowScreenReaders {#isAllowScreenReaders--}
```
public boolean isAllowScreenReaders()
```

Ställer in behörigheten som tillåter skärmläsare eller inte. true betyder tillåten och false betyder förbjuden.

**Returns:**
booleskt värde

### setAllowAssembly {#setAllowAssembly-boolean-}
```
public void setAllowAssembly(boolean value)
```

Ställer in behörigheten som tillåter montering eller inte. true betyder tillåten och false betyder förbjuden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setAllowCopy {#setAllowCopy-boolean-}
```
public void setAllowCopy(boolean value)
```

Ställer in behörigheten som tillåter kopiering eller inte. true betyder tillåten och false betyder förbjuden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setAllowDegradedPrinting {#setAllowDegradedPrinting-boolean-}
```
public void setAllowDegradedPrinting(boolean value)
```

Ställer in behörigheten som tillåter degraderad utskrift eller inte. true betyder tillåten och false betyder förbjuden. När den är inställd kommer utskrift att begränsas till en lågupplöst representation av utseendet, eventuellt med försämrad kvalitet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setAllowFillIn {#setAllowFillIn-boolean-}
```
public void setAllowFillIn(boolean value)
```

Ställer in behörigheten som tillåter ifyllning av formulär eller inte. true betyder tillåten och false betyder förbjuden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setAllowModifyAnnotations {#setAllowModifyAnnotations-boolean-}
```
public void setAllowModifyAnnotations(boolean value)
```

Ställer in behörigheten som tillåter ändring av annotationer eller inte. true betyder tillåten och false betyder förbjuden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setAllowModifyContents {#setAllowModifyContents-boolean-}
```
public void setAllowModifyContents(boolean value)
```

Ställer in behörigheten som tillåter ändring av innehåll eller inte. true betyder tillåten och false betyder förbjuden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setAllowPrint {#setAllowPrint-boolean-}
```
public void setAllowPrint(boolean value)
```

Ställer in behörigheten som tillåter utskrift eller inte. true betyder tillåten och false betyder förbjuden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setAllowScreenReaders {#setAllowScreenReaders-boolean-}
```
public void setAllowScreenReaders(boolean value)
```

Ställer in behörigheten som tillåter skärmläsare eller inte. true betyder tillåten och false betyder förbjuden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setChangeAllowLevel {#setChangeAllowLevel-int-}
```
public void setChangeAllowLevel(int value)
```

Hämtar och anger ändringsnivån för dokumentets behörighet. Samma som Adobe Professionals inställningar för Tillåtna ändringar. 0: Ingen. 1: Infoga, ta bort och rotera sidor. 2: Fyll i formulärfält och signera befintliga signaturfält. 3: Kommentera, fylla i formulärfält och signera befintliga signaturfält. 4: Allt förutom att extrahera sidor. Om egenskapen har värdet -1 är nivån odefinierad.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde |

### setCopyAllowLevel {#setCopyAllowLevel-int-}
```
public void setCopyAllowLevel(int value)
```

Hämtar och anger kopieringsnivån för dokumentets behörighet. Samma som Adobe Professionals behörighetsinställningar. 0: Ingen. 1: Aktivera textåtkomst för skärmläsarenheter för synskadade. 2: Aktivera kopiering av text, bilder och annat innehåll. Om egenskapen har värdet -1 är nivån odefinierad.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde |

### setPrintAllowLevel {#setPrintAllowLevel-int-}
```
public void setPrintAllowLevel(int value)
```

Hämtar och anger utskriftsnivån för dokumentets behörighet. Samma som Adobe Professionals inställningar för Tillåten utskrift. 0: Ingen. 1: Låg upplösning (150 dpi). 2: Hög upplösning. Om egenskapen har värdet -1 är nivån odefinierad.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde |
