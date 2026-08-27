---
title: "Formulär"
linktitle: "Formulär"
second_title: "Aspose.PDF för Java API-referens"
description: "Klass som representerar formulärobjekt."
type: docs
weight: 1740
url: /sv/java/com.aspose.pdf/form/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Form

**All Implemented Interfaces:**
Iterable < WidgetAnnotation >

```
public final class Form extends Object implements Iterable < WidgetAnnotation >
```

Klass som representerar formulärobjekt.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [Form](#Form-com.aspose.pdf.IDocument-) | Konstruktör |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [add](#add-com.aspose.pdf.Field-) | Lägger till fält på formuläret. |
| [add](#add-com.aspose.pdf.Field-int-) | Lägger till fält på formuläret. |
| [add](#add-com.aspose.pdf.Field-java.lang.String-int-) | Lägger till nytt fält i formuläret; om detta fält redan är placerat på ett annat eller detta formulär, skapas en kopia av fältet. |
| [add](#add-com.aspose.pdf.WidgetAnnotation-) | Lägger till fält på formuläret. |
| [addFieldAppearance](#addFieldAppearance-com.aspose.pdf.Field-int-com.aspose.pdf.Rectangle-) | Lägger till ytterligare utseende för fältet på angiven sida i dokumentet på den angivna platsen. |
| [addFieldToAcroForm](#addFieldToAcroForm-com.aspose.pdf.Field-) | Lägger till ytterligare utseende för fältet på angiven sida i dokumentet. |
| [assignXfa](#assignXfa-com.aspose.ms.System.Xml.XmlDocument-) | Ställer in XFA för formuläret till angivet värde. |
| [clear](#clear--) | Raderar alla fält från formuläret. Stöds inte. |
| [contains](#contains-com.aspose.pdf.WidgetAnnotation-) | Bestämmer om fältet är presenterat i formuläret.. |
| [copyTo](#copyTo-com.aspose.pdf.Field:A-int-) | Kopierar fält placerade i formuläret till en array. |
| [copyTo](#copyTo-com.aspose.pdf.WidgetAnnotation:A-int-) | Kopierar formulärets fält till en array. |
| [delete](#delete-com.aspose.pdf.Field-) | Radera fält från formuläret. |
| [delete](#delete-java.lang.String-) | Raderar fält från formuläret efter dess namn. |
| [flatten](#flatten--) | Tar bort alla statiska formulärfält och placerar deras värden direkt på sidan. |
| [get_Item](#get_Item-int-) | Hämtar fält från formuläret efter fältindex. |
| [get_Item](#get_Item-java.lang.String-) | Hämtar fält från formuläret efter fältnamn. Kastar undantag om fältet inte hittades. |
| [get_xfa](#get_xfa--) | Endast för internt bruk |
| [get](#get-int-) |  |
| [get](#get-java.lang.String-) | Söker fält efter fältnamn. Returnerar null om fältet inte hittades. |
| [getAutoRecalculate](#getAutoRecalculate--) | Om inställt kommer alla formulärfält att omberäknas när något fält ändras. Standardvärdet är true. Ställ in på false för att öka prestandan när formuläret fylls i med ett stort antal beräknade fält. |
| [getAutoRestoreForm](#getAutoRestoreForm--) | Om inställt, kommer frånvarande formulärfält att automatiskt skapas om de finns i annotationer. |
| [getDefaultAppearance](#getDefaultAppearance--) | Hämtar standardutseendet för formuläret (objekt som beskriver standardtypsnitt, textstorlek och färg för fält på formuläret). |
| [getDefaultResources](#getDefaultResources--) | Hämtar standardresurser som placerats på detta formulär. |
| [getDocument](#getDocument--) | Endast för internt bruk |
| [getEmulateRequierdGroups](#getEmulateRequierdGroups--) | Om den här egenskapen är sann kommer ytterligare röda avgränsningsrektanglar att ritas för obligatoriska Xfa exclGroup‑elementbehållare. Denna egenskap infördes på grund av avsaknaden av motsvarigheter för exclGroup under konvertering av Xfa‑representationen av formulär till standard. Den är falsk som standard. |
| [getFields](#getFields--) | Hämtar en lista över alla fält på den lägsta nivån i det hierarkiska formuläret. |
| [getFieldsInRect](#getFieldsInRect-com.aspose.pdf.Rectangle-) | Returnerar fält inom den angivna rektangeln. |
| [getIgnoreNeedsRendering](#getIgnoreNeedsRendering--) | Om den här egenskapen är sann kommer värdet för nyckeln NeedsRendering att ignoreras under konvertering av XFA‑formulär till standardformulär. Den är falsk som standard. |
| [getNeedsRendering](#getNeedsRendering--) | Hämtar ett värde som indikerar om dokumentet kräver borttagning av det dynamiska XFA‑formuläret. Denna egenskap infördes för att avgöra om {@code IgnoreNeedsRendering}({@link #getIgnoreNeedsRendering}/{@link #setIgnoreNeedsRendering(boolean)}) ska användas för att ta bort XFA‑formuläret i fall där XFA‑formuläret är närvarande och {@code NeedsRendering}({@link #getNeedsRendering}) är falskt. |
| [getRemovePermission](#getRemovePermission--) | Om den här egenskapen är sann kommer "Perms"‑ordlistan att tas bort från pdf‑dokumentet efter konvertering av dynamiska dokument till standard. "Perms"‑ordlistan kan innehålla regler som stör visning av obligatoriska fält i Adobe Acrobat Reader. Den är falsk som standard. |
| [getSignaturesAppendOnly](#getSignaturesAppendOnly--) | Om inställt, innehåller dokumentet signaturer som kan ogiltigförklaras om filen sparas (skrivs) på ett sätt som ändrar dess tidigare innehåll, till skillnad från en inkrementell uppdatering. |
| [getSignaturesExist](#getSignaturesExist--) | Om inställt, innehåller dokumentet minst ett signaturfält. |
| [getSignDependentElementsRenderingModeWhenConverted](#getSignDependentElementsRenderingModeWhenConverted--) | Formulär kan innehålla signeringsinformation, dvs. kan vara signerade eller osignerade. Och formulärets vy måste ibland bero på om formuläret är signerat eller inte. Denna egenskap talar om för formulärets konverterare (t.ex. under konvertering av XFA‑formulär till standardformulär) om det resulterande formuläret ska renderas som signerat eller osignerat. |
| [getSyncRoot](#getSyncRoot--) | Returnerar synkroniseringsobjekt. |
| [getType](#getType--) | Hämtar formulärets typ. Möjliga värden är: Standard, Static, Dynamic. |
| [getXFA](#getXFA--) | Hämtar XFA‑data för formuläret (om det finns). |
| [hasField](#hasField-com.aspose.pdf.Field-) | Kontrollera om formuläret redan har det angivna fältet. |
| [hasField](#hasField-java.lang.String-) | Avgör om fältet med angivet namn redan har lagts till i formuläret. |
| [hasField](#hasField-java.lang.String-boolean-) | Avgör om fältet med angivet namn redan har lagts till i formuläret, med möjlighet att söka i fältens underordnade hierarki. |
| [hasXfa](#hasXfa--) | Hämtar ett värde som indikerar om dokumentet innehåller XFA‑formulär. Denna egenskap infördes för att avgöra om {@code IgnoreNeedsRendering}({@link #getIgnoreNeedsRendering}/{@link #setIgnoreNeedsRendering(boolean)}) ska användas för att ta bort XFA‑formuläret i fall där XFA‑formuläret är närvarande och {@code NeedsRendering}({@link #getNeedsRendering}) är falskt. |
| [isReadOnly](#isReadOnly--) | Avgör om samlingen är skrivskyddad. Returnerar alltid falskt. |
| [isSynchronized](#isSynchronized--) | Returnerar sant om objektet är trådsäkert. |
| [iterator](#iterator--) | Hämtar uppräkning av formulärfält. |
| [makeFormAnnotationsIndependent](#makeFormAnnotationsIndependent-com.aspose.pdf.Page-) | / * / * Exporterar PDF‑formulärfält till JSON‑format och skriver resultatet till den angivna strömmen. / * / * Document document = new Document(\"PdfDoc.pdf\"); / * FileStream fs = new FileStream(\"export.json\", FileMode.Create, FileAccess.Write); / * document.Form.ExportFormFieldsToJson(fs); / * fs.Close(); / * |
| [remove](#remove-com.aspose.pdf.WidgetAnnotation-) | Tar bort fält från formuläret. |
| [removeFieldAppearance](#removeFieldAppearance-com.aspose.pdf.Field-int-) | Tar bort fältets utseende på angivet index. Om endast ett barnutseende återstår, bäddar metoden in det i fältet. |
| [setAutoRecalculate](#setAutoRecalculate-boolean-) | Om inställt kommer alla formulärfält att omberäknas när något fält ändras. Standardvärdet är true. Ställ in på false för att öka prestandan när formuläret fylls i med ett stort antal beräknade fält. |
| [setAutoRestoreForm](#setAutoRestoreForm-boolean-) | Om inställt, kommer frånvarande formulärfält att automatiskt skapas om de finns i annotationer. |
| [setCalculatedFields](#setCalculatedFields-java.util.List-) | Tillåter att ange ordning för fältberäkning. |
| [setDefaultAppearance](#setDefaultAppearance-com.aspose.pdf.DefaultAppearance-) | Ställer in standardutseende för formuläret (objekt som beskriver standardtypsnitt, textstorlek och färg för fält i formuläret). |
| [setEmulateRequierdGroups](#setEmulateRequierdGroups-boolean-) | Om den här egenskapen är sann kommer ytterligare röda avgränsningsrektanglar att ritas för obligatoriska Xfa exclGroup‑elementbehållare. Denna egenskap infördes på grund av avsaknaden av motsvarigheter för exclGroup under konvertering av Xfa‑representationen av formulär till standard. Den är falsk som standard. |
| [setIgnoreNeedsRendering](#setIgnoreNeedsRendering-boolean-) | Om den här egenskapen är sann kommer värdet för nyckeln NeedsRendering att ignoreras under konvertering av XFA‑formulär till standardformulär. Den är falsk som standard. |
| [setRemovePermission](#setRemovePermission-boolean-) | Om den här egenskapen är sann kommer "Perms"‑ordlistan att tas bort från pdf‑dokumentet efter konvertering av dynamiska dokument till standard. "Perms"‑ordlistan kan innehålla regler som stör visning av obligatoriska fält i Adobe Acrobat Reader. Den är falsk som standard. |
| [setSignaturesAppendOnly](#setSignaturesAppendOnly-boolean-) | Om inställt, innehåller dokumentet signaturer som kan ogiltigförklaras om filen sparas (skrivs) på ett sätt som ändrar dess tidigare innehåll, till skillnad från en inkrementell uppdatering. |
| [setSignaturesExist](#setSignaturesExist-boolean-) | Om inställt, innehåller dokumentet minst ett signaturfält. |
| [setSignDependentElementsRenderingModeWhenConverted](#setSignDependentElementsRenderingModeWhenConverted-int-) | Formulär kan innehålla signeringsinformation, dvs. kan vara signerade eller osignerade. Och formulärets vy måste ibland bero på om formuläret är signerat eller inte. Denna egenskap talar om för formulärets konverterare (t.ex. under konvertering av XFA‑formulär till standardformulär) om det resulterande formuläret ska renderas som signerat eller osignerat. |
| [setType](#setType-com.aspose.pdf.FormType-) | Hämtar formulärets typ. Möjliga värden är: Standard, Static, Dynamic. |
| [size](#size--) | Hämtar antalet fält i detta formulär. |

### Form {#Form-com.aspose.pdf.IDocument-}
Konstruktör

### add {#add-com.aspose.pdf.Field-}
Lägger till fält på formuläret.

### add {#add-com.aspose.pdf.Field-int-}
Lägger till fält på formuläret.

### add {#add-com.aspose.pdf.Field-java.lang.String-int-}
Lägger till nytt fält i formuläret; om detta fält redan är placerat på ett annat eller detta formulär, skapas en kopia av fältet.

### add {#add-com.aspose.pdf.WidgetAnnotation-}
Lägger till fält på formuläret.

### addFieldAppearance {#addFieldAppearance-com.aspose.pdf.Field-int-com.aspose.pdf.Rectangle-}
Lägger till ytterligare utseende för fältet på angiven sida i dokumentet på den angivna platsen.

### addFieldToAcroForm {#addFieldToAcroForm-com.aspose.pdf.Field-}
Lägger till ytterligare utseende för fältet på angiven sida i dokumentet.

### assignXfa {#assignXfa-com.aspose.ms.System.Xml.XmlDocument-}
Ställer in XFA för formuläret till angivet värde.

### clear {#clear--}
```
public void clear()
```

Raderar alla fält från formuläret. Stöds inte.

### contains {#contains-com.aspose.pdf.WidgetAnnotation-}
Bestämmer om fältet är presenterat i formuläret..

### copyTo {#copyTo-com.aspose.pdf.Field:A-int-}
Kopierar fält placerade i formuläret till en array.

### copyTo {#copyTo-com.aspose.pdf.WidgetAnnotation:A-int-}
Kopierar formulärets fält till en array.

### delete {#delete-com.aspose.pdf.Field-}
Radera fält från formuläret.

### delete {#delete-java.lang.String-}
Raderar fält från formuläret efter dess namn.

### flatten {#flatten--}
```
public void flatten()
```

Tar bort alla statiska formulärfält och placerar deras värden direkt på sidan.

### get_Item {#get_Item-int-}
```
public WidgetAnnotation get_Item(int index)
```

Hämtar fält från formuläret efter fältindex.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index |  | Index för fältet. |

**Returns:**
Hämtat fält.

### get_Item {#get_Item-java.lang.String-}
Hämtar fält från formuläret efter fältnamn. Kastar undantag om fältet inte hittades.

### get_xfa {#get_xfa--}
```
public XFA get_xfa()
```

Endast för internt bruk

**Returns:**
XFA-objekt

### get {#get-int-}
```
public WidgetAnnotation get(int index)
```



**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index |  |  |

### get {#get-java.lang.String-}
Söker fält efter fältnamn. Returnerar null om fältet inte hittades.

### getAutoRecalculate {#getAutoRecalculate--}
```
public final boolean getAutoRecalculate()
```

Om inställt kommer alla formulärfält att omberäknas när något fält ändras. Standardvärdet är true. Ställ in på false för att öka prestandan när formuläret fylls i med ett stort antal beräknade fält.

**Returns:**
booleskt värde

### getAutoRestoreForm {#getAutoRestoreForm--}
```
public final boolean getAutoRestoreForm()
```

Om inställt, kommer frånvarande formulärfält att automatiskt skapas om de finns i annotationer.

**Returns:**
booleskt värde

### getDefaultAppearance {#getDefaultAppearance--}
```
public DefaultAppearance getDefaultAppearance()
```

Hämtar standardutseendet för formuläret (objekt som beskriver standardtypsnitt, textstorlek och färg för fält på formuläret).

**Returns:**
DefaultAppearance‑objekt

### getDefaultResources {#getDefaultResources--}
```
public Resources getDefaultResources()
```

Hämtar standardresurser som placerats på detta formulär.

**Returns:**
Resursvärde

### getDocument {#getDocument--}
```
public IDocument getDocument()
```

Endast för internt bruk

**Returns:**
IDocument-objekt

### getEmulateRequierdGroups {#getEmulateRequierdGroups--}
```
public boolean getEmulateRequierdGroups()
```

Om den här egenskapen är sann kommer ytterligare röda avgränsningsrektanglar att ritas för obligatoriska Xfa exclGroup‑elementbehållare. Denna egenskap infördes på grund av avsaknaden av motsvarigheter för exclGroup under konvertering av Xfa‑representationen av formulär till standard. Den är falsk som standard.

**Returns:**
booleskt värde

### getFields {#getFields--}
```
public Field [] getFields()
```

Hämtar en lista över alla fält på den lägsta nivån i det hierarkiska formuläret.

**Returns:**
Array med hittade fält.

### getFieldsInRect {#getFieldsInRect-com.aspose.pdf.Rectangle-}
Returnerar fält inom den angivna rektangeln.

### getIgnoreNeedsRendering {#getIgnoreNeedsRendering--}
```
public boolean getIgnoreNeedsRendering()
```

Om den här egenskapen är sann kommer värdet för nyckeln NeedsRendering att ignoreras under konvertering av XFA‑formulär till standardformulär. Den är falsk som standard.

**Returns:**
booleskt värde

### getNeedsRendering {#getNeedsRendering--}
```
public final boolean getNeedsRendering()
```

Hämtar ett värde som indikerar om dokumentet kräver borttagning av det dynamiska XFA‑formuläret. Denna egenskap infördes för att avgöra om {@code IgnoreNeedsRendering}({@link #getIgnoreNeedsRendering}/{@link #setIgnoreNeedsRendering(boolean)}) ska användas för att ta bort XFA‑formuläret i fall där XFA‑formuläret är närvarande och {@code NeedsRendering}({@link #getNeedsRendering}) är falskt.

**Returns:**
booleskt värde

### getRemovePermission {#getRemovePermission--}
```
public boolean getRemovePermission()
```

Om den här egenskapen är sann kommer "Perms"‑ordlistan att tas bort från pdf‑dokumentet efter konvertering av dynamiska dokument till standard. "Perms"‑ordlistan kan innehålla regler som stör visning av obligatoriska fält i Adobe Acrobat Reader. Den är falsk som standard.

**Returns:**
booleskt värde

### getSignaturesAppendOnly {#getSignaturesAppendOnly--}
```
public final boolean getSignaturesAppendOnly()
```

Om inställt, innehåller dokumentet signaturer som kan ogiltigförklaras om filen sparas (skrivs) på ett sätt som ändrar dess tidigare innehåll, till skillnad från en inkrementell uppdatering.

**Returns:**
booleskt värde

### getSignaturesExist {#getSignaturesExist--}
```
public final boolean getSignaturesExist()
```

Om inställt, innehåller dokumentet minst ett signaturfält.

**Returns:**
booleskt värde

### getSignDependentElementsRenderingModeWhenConverted {#getSignDependentElementsRenderingModeWhenConverted--}
```
public int getSignDependentElementsRenderingModeWhenConverted()
```

Formulär kan innehålla signeringsinformation, dvs. kan vara signerade eller osignerade. Och formulärets vy måste ibland bero på om formuläret är signerat eller inte. Denna egenskap talar om för formulärets konverterare (t.ex. under konvertering av XFA‑formulär till standardformulär) om det resulterande formuläret ska renderas som signerat eller osignerat.

**Returns:**
SignDependentElementsRenderingModes-element @see SignDependentElementsRenderingModes

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Returnerar synkroniseringsobjekt.

**Returns:**
Objekt för synkronisering

### getType {#getType--}
```
public FormType getType()
```

Hämtar formulärets typ. Möjliga värden är: Standard, Static, Dynamic.

**Returns:**
FormType-värde @see FormType

### getXFA {#getXFA--}
```
public XFA getXFA()
```

Hämtar XFA‑data för formuläret (om det finns).

**Returns:**
XFA-värde

### hasField {#hasField-com.aspose.pdf.Field-}
Kontrollera om formuläret redan har det angivna fältet.

### hasField {#hasField-java.lang.String-}
Avgör om fältet med angivet namn redan har lagts till i formuläret.

### hasField {#hasField-java.lang.String-boolean-}
Avgör om fältet med angivet namn redan har lagts till i formuläret, med möjlighet att söka i fältens underordnade hierarki.

### hasXfa {#hasXfa--}
```
public final boolean hasXfa()
```

Hämtar ett värde som indikerar om dokumentet innehåller XFA‑formulär. Denna egenskap infördes för att avgöra om {@code IgnoreNeedsRendering}({@link #getIgnoreNeedsRendering}/{@link #setIgnoreNeedsRendering(boolean)}) ska användas för att ta bort XFA‑formuläret i fall där XFA‑formuläret är närvarande och {@code NeedsRendering}({@link #getNeedsRendering}) är falskt.

**Returns:**
booleskt värde

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Avgör om samlingen är skrivskyddad. Returnerar alltid falskt.

**Returns:**
booleskt värde

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Returnerar sant om objektet är trådsäkert.

**Returns:**
booleskt värde

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.Generic.List.Enumerator< WidgetAnnotation > iterator()
```

Hämtar uppräkning av formulärfält.

**Returns:**
Fältenumerator.

### makeFormAnnotationsIndependent {#makeFormAnnotationsIndependent-com.aspose.pdf.Page-}
/ * / * Exporterar PDF‑formulärfält till JSON‑format och skriver resultatet till den angivna strömmen. / * / * Document document = new Document(\"PdfDoc.pdf\"); / * FileStream fs = new FileStream(\"export.json\", FileMode.Create, FileAccess.Write); / * document.Form.ExportFormFieldsToJson(fs); / * fs.Close(); / *

### remove {#remove-com.aspose.pdf.WidgetAnnotation-}
Tar bort fält från formuläret.

### removeFieldAppearance {#removeFieldAppearance-com.aspose.pdf.Field-int-}
Tar bort fältets utseende på angivet index. Om endast ett barnutseende återstår, bäddar metoden in det i fältet.

### setAutoRecalculate {#setAutoRecalculate-boolean-}
```
public final void setAutoRecalculate(boolean value)
```

Om inställt kommer alla formulärfält att omberäknas när något fält ändras. Standardvärdet är true. Ställ in på false för att öka prestandan när formuläret fylls i med ett stort antal beräknade fält.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setAutoRestoreForm {#setAutoRestoreForm-boolean-}
```
public final void setAutoRestoreForm(boolean value)
```

Om inställt, kommer frånvarande formulärfält att automatiskt skapas om de finns i annotationer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setCalculatedFields {#setCalculatedFields-java.util.List-}
Tillåter att ange ordning för fältberäkning.

### setDefaultAppearance {#setDefaultAppearance-com.aspose.pdf.DefaultAppearance-}
Ställer in standardutseende för formuläret (objekt som beskriver standardtypsnitt, textstorlek och färg för fält i formuläret).

### setEmulateRequierdGroups {#setEmulateRequierdGroups-boolean-}
```
public void setEmulateRequierdGroups(boolean value)
```

Om den här egenskapen är sann kommer ytterligare röda avgränsningsrektanglar att ritas för obligatoriska Xfa exclGroup‑elementbehållare. Denna egenskap infördes på grund av avsaknaden av motsvarigheter för exclGroup under konvertering av Xfa‑representationen av formulär till standard. Den är falsk som standard.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setIgnoreNeedsRendering {#setIgnoreNeedsRendering-boolean-}
```
public void setIgnoreNeedsRendering(boolean value)
```

Om den här egenskapen är sann kommer värdet för nyckeln NeedsRendering att ignoreras under konvertering av XFA‑formulär till standardformulär. Den är falsk som standard.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setRemovePermission {#setRemovePermission-boolean-}
```
public void setRemovePermission(boolean value)
```

Om den här egenskapen är sann kommer "Perms"‑ordlistan att tas bort från pdf‑dokumentet efter konvertering av dynamiska dokument till standard. "Perms"‑ordlistan kan innehålla regler som stör visning av obligatoriska fält i Adobe Acrobat Reader. Den är falsk som standard.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setSignaturesAppendOnly {#setSignaturesAppendOnly-boolean-}
```
public final void setSignaturesAppendOnly(boolean value)
```

Om inställt, innehåller dokumentet signaturer som kan ogiltigförklaras om filen sparas (skrivs) på ett sätt som ändrar dess tidigare innehåll, till skillnad från en inkrementell uppdatering.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setSignaturesExist {#setSignaturesExist-boolean-}
```
public final void setSignaturesExist(boolean value)
```

Om inställt, innehåller dokumentet minst ett signaturfält.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setSignDependentElementsRenderingModeWhenConverted {#setSignDependentElementsRenderingModeWhenConverted-int-}
```
public void setSignDependentElementsRenderingModeWhenConverted(int signDependentElementsRenderingModeWhenConverted)
```

Formulär kan innehålla signeringsinformation, dvs. kan vara signerade eller osignerade. Och formulärets vy måste ibland bero på om formuläret är signerat eller inte. Denna egenskap talar om för formulärets konverterare (t.ex. under konvertering av XFA‑formulär till standardformulär) om det resulterande formuläret ska renderas som signerat eller osignerat.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| signDependentElementsRenderingModeWhenConverted |  | SignDependentElementsRenderingModes-element @see SignDependentElementsRenderingModes |

### setType {#setType-com.aspose.pdf.FormType-}
Hämtar formulärets typ. Möjliga värden är: Standard, Static, Dynamic.

### size {#size--}
```
public final int size()
```

Hämtar antalet fält i detta formulär.

**Returns:**
int‑värde
