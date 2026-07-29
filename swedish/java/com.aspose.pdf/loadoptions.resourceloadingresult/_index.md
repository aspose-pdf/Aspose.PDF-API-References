---
title: "LoadOptions.ResourceLoadingResult"
linktitle: "LoadOptions.ResourceLoadingResult"
second_title: "Aspose.PDF för Java API-referens"
description: "Resultat av anpassad inläsning av resurs"
type: docs
weight: 2820
url: /sv/java/com.aspose.pdf/loadoptions.resourceloadingresult/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions.ResourceLoadingResult

```
public static class LoadOptions.ResourceLoadingResult extends Object
```

Resultat av anpassad inläsning av resurs

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [ResourceLoadingResult](#ResourceLoadingResult-byte:A-) | Skapar en instans av laddningsresultatet |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getData](#getData--) | Binär data som laddats med anpassad laddare – den måste sättas efter laddning |
| [getEncodingIfKnown](#getEncodingIfKnown--) | Ibland är kodningen av resursen känd efter eller under laddning. I sådant fall kan anpassad kod förse konverteraren med den kunskapen via denna parameter. Du kan lämna null i denna parameter om kodningen är okänd eller inte spelar någon roll. |
| [getExceptionOfLoadingIfAny](#getExceptionOfLoadingIfAny--) | Ibland är det omöjligt att ladda den begärda resursen av någon anledning. Otillgänglighet av resursen leder ofta inte till att konverteringar kraschar och resultatsdokumentet kan ändå skapas (men kanske i något sämre kvalitet, utan bilder etc.). Om ett undantag inträffade under laddning, fånga det bara och placera det i denna parameter – ibland är den informationen användbar för konverteraren vid rendering av resultatet. |
| [getMIMETypeIfKnown](#getMIMETypeIfKnown--) | Ibland är kunskap om MIME‑typen för den laddade resursen användbar för konverteraren. Du kan ange MIME‑typen (om den är känd efter laddning) i denna parameter. Lämna parametern som null när MIME‑typen är okänd eller det inte är nödvändigt att ange den. |
| [isLoadingCancelled](#isLoadingCancelled--) | Ibland bör laddning inte ske av anpassad kod av någon anledning. I sådant fall sätt denna flagga till True. Då kommer konverteraren att försöka använda den interna standardresursladdaren för att få resultatet (som den beter sig i situationen när ingen anpassad strategi har angetts). |
| [setEncodingIfKnown](#setEncodingIfKnown-java.nio.charset.Charset-) | Ibland är kodningen av resursen känd efter eller under laddning. I sådant fall kan anpassad kod förse konverteraren med den kunskapen via denna parameter. Du kan lämna null i denna parameter om kodningen är okänd eller inte spelar någon roll. |
| [setExceptionOfLoadingIfAny](#setExceptionOfLoadingIfAny-com.aspose.ms.System.Exception-) | Ibland är det omöjligt att ladda den begärda resursen av någon anledning. |
| [setLoadingCancelled](#setLoadingCancelled-boolean-) | Ibland bör laddning inte ske av anpassad kod av någon anledning. I sådant fall sätt denna flagga till True. Då kommer konverteraren att försöka använda den interna standardresursladdaren för att få resultatet (som den beter sig i situationen när ingen anpassad strategi har angetts). |
| [setMIMETypeIfKnown](#setMIMETypeIfKnown-java.lang.String-) | Ibland är kunskap om MIME‑typen för den laddade resursen användbar för konverteraren. Du kan ange MIME‑typen (om den är känd efter laddning) i denna parameter. Lämna parametern som null när MIME‑typen är okänd eller det inte är nödvändigt att ange den. |

### ResourceLoadingResult {#ResourceLoadingResult-byte:A-}
```
public ResourceLoadingResult(byte[] data)
```

Skapar en instans av laddningsresultatet

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data |  | Resultatet av anpassad laddning måste alltid tillhandahållas, det kan vara en noll‑längd array om det är omöjligt att få något resultat. |

### getData {#getData--}
```
public byte[] getData()
```

Binär data som laddats med anpassad laddare – den måste sättas efter laddning

**Returns:**
array av byte‑värden

### getEncodingIfKnown {#getEncodingIfKnown--}
```
public Charset getEncodingIfKnown()
```

Ibland är kodningen av resursen känd efter eller under laddning. I sådant fall kan anpassad kod förse konverteraren med den kunskapen via denna parameter. Du kan lämna null i denna parameter om kodningen är okänd eller inte spelar någon roll.

**Returns:**
Charset‑instans

### getExceptionOfLoadingIfAny {#getExceptionOfLoadingIfAny--}
```
public com.aspose.ms.System.Exception getExceptionOfLoadingIfAny()
```

Ibland är det omöjligt att ladda den begärda resursen av någon anledning. Otillgänglighet av resursen leder ofta inte till att konverteringar kraschar och resultatsdokumentet kan ändå skapas (men kanske i något sämre kvalitet, utan bilder etc.). Om ett undantag inträffade under laddning, fånga det bara och placera det i denna parameter – ibland är den informationen användbar för konverteraren vid rendering av resultatet.

**Returns:**
Undantag

### getMIMETypeIfKnown {#getMIMETypeIfKnown--}
```
public String getMIMETypeIfKnown()
```

Ibland är kunskap om MIME‑typen för den laddade resursen användbar för konverteraren. Du kan ange MIME‑typen (om den är känd efter laddning) i denna parameter. Lämna parametern som null när MIME‑typen är okänd eller det inte är nödvändigt att ange den.

**Returns:**
String värde

### isLoadingCancelled {#isLoadingCancelled--}
```
public boolean isLoadingCancelled()
```

Ibland bör laddning inte ske av anpassad kod av någon anledning. I sådant fall sätt denna flagga till True. Då kommer konverteraren att försöka använda den interna standardresursladdaren för att få resultatet (som den beter sig i situationen när ingen anpassad strategi har angetts).

**Returns:**
booleskt värde

### setEncodingIfKnown {#setEncodingIfKnown-java.nio.charset.Charset-}
Ibland är kodningen av resursen känd efter eller under laddning. I sådant fall kan anpassad kod förse konverteraren med den kunskapen via denna parameter. Du kan lämna null i denna parameter om kodningen är okänd eller inte spelar någon roll.

### setExceptionOfLoadingIfAny {#setExceptionOfLoadingIfAny-com.aspose.ms.System.Exception-}
Ibland är det omöjligt att ladda den begärda resursen av någon anledning.

### setLoadingCancelled {#setLoadingCancelled-boolean-}
```
public void setLoadingCancelled(boolean loadingCancelled)
```

Ibland bör laddning inte ske av anpassad kod av någon anledning. I sådant fall sätt denna flagga till True. Då kommer konverteraren att försöka använda den interna standardresursladdaren för att få resultatet (som den beter sig i situationen när ingen anpassad strategi har angetts).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| loadingCancelled |  | booleskt värde |

### setMIMETypeIfKnown {#setMIMETypeIfKnown-java.lang.String-}
Ibland är kunskap om MIME‑typen för den laddade resursen användbar för konverteraren. Du kan ange MIME‑typen (om den är känd efter laddning) i denna parameter. Lämna parametern som null när MIME‑typen är okänd eller det inte är nödvändigt att ange den.
