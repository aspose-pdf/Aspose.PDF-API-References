---
title: "SaveOptions.ResourceSavingInfo"
linktitle: "SaveOptions.ResourceSavingInfo"
second_title: "Aspose.PDF för Java API-referens"
description: "Denna klass representerar en uppsättning data som är relaterade till sparande av externa resursfiler som sker under konvertering av PDF till något annat format (t.ex. HTML)."
type: docs
weight: 4440
url: /sv/java/com.aspose.pdf/saveoptions.resourcesavinginfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions.ResourceSavingInfo

```
public static class SaveOptions.ResourceSavingInfo extends Object
```

Denna klass representerar en uppsättning data som är relaterade till sparande av externa resursfiler som sker under konvertering av PDF till något annat format (t.ex. HTML).

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getContentStream](#getContentStream--) | Ställs in av konverteraren. Representerar binärt innehåll i den sparade filen. |
| [getResourceType](#getResourceType--) | Ställs in av konverteraren. Antaget filnamn som går från konverteraren till koden för en anpassad metod. Kan användas i anpassad kod för att avgöra hur man ska bearbeta eller var man sparar den filen. |
| [getSupposedFileName](#getSupposedFileName--) | Ställs in av konverteraren. Antaget filnamn som går från konverteraren till koden för en anpassad metod. Kan användas i anpassad kod för att avgöra hur man ska bearbeta eller var man sparar den filen. |
| [isCustomProcessingCancelled](#isCustomProcessingCancelled--) | Denna flagga måste sättas till \"true\" i anpassad kod om den föreslagna filen av någon anledning ska bearbetas inte med anpassad kod utan med konverterarens kod själv på standard sätt för konverteraren. Så betyder inställningen satt till true att anpassad kod inte bearbetade den refererade filen och konverteraren måste hantera den själv (i båda fallen – för att spara någonstans och för namngivning i den refererande filen). |
| [setCustomProcessingCancelled](#setCustomProcessingCancelled-boolean-) | Denna flagga måste sättas till \"true\" i anpassad kod om den föreslagna filen av någon anledning ska bearbetas inte med anpassad kod utan med konverterarens kod själv på standard sätt för konverteraren. Så betyder inställningen satt till true att anpassad kod inte bearbetade den refererade filen och konverteraren måste hantera den själv (i båda fallen – för att spara någonstans och för namngivning i den refererande filen). |

### getContentStream {#getContentStream--}
```
public byte[] getContentStream()
```

Ställs in av konverteraren. Representerar binärt innehåll i den sparade filen.

**Returns:**
byte‑array

### getResourceType {#getResourceType--}
```
public SaveOptions.NodeLevelResourceType getResourceType()
```

Ställs in av konverteraren. Antaget filnamn som går från konverteraren till koden för en anpassad metod. Kan användas i anpassad kod för att avgöra hur man ska bearbeta eller var man sparar den filen.

**Returns:**
NodeLevelResourceType-element @see NodeLevelResourceType

### getSupposedFileName {#getSupposedFileName--}
```
public String getSupposedFileName()
```

Ställs in av konverteraren. Antaget filnamn som går från konverteraren till koden för en anpassad metod. Kan användas i anpassad kod för att avgöra hur man ska bearbeta eller var man sparar den filen.

**Returns:**
String värde

### isCustomProcessingCancelled {#isCustomProcessingCancelled--}
```
public boolean isCustomProcessingCancelled()
```

Denna flagga måste sättas till \"true\" i anpassad kod om den föreslagna filen av någon anledning ska bearbetas inte med anpassad kod utan med konverterarens kod själv på standard sätt för konverteraren. Så betyder inställningen satt till true att anpassad kod inte bearbetade den refererade filen och konverteraren måste hantera den själv (i båda fallen – för att spara någonstans och för namngivning i den refererande filen).

**Returns:**
booleskt värde

### setCustomProcessingCancelled {#setCustomProcessingCancelled-boolean-}
```
public void setCustomProcessingCancelled(boolean customProcessingCancelled)
```

Denna flagga måste sättas till \"true\" i anpassad kod om den föreslagna filen av någon anledning ska bearbetas inte med anpassad kod utan med konverterarens kod själv på standard sätt för konverteraren. Så betyder inställningen satt till true att anpassad kod inte bearbetade den refererade filen och konverteraren måste hantera den själv (i båda fallen – för att spara någonstans och för namngivning i den refererande filen).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| customProcessingCancelled |  | booleskt värde |
