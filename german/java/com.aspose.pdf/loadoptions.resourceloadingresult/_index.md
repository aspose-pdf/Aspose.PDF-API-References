---
title: "LoadOptions.ResourceLoadingResult"
linktitle: "LoadOptions.ResourceLoadingResult"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Ergebnis des benutzerdefinierten Ladens einer Ressource"
type: docs
weight: 2820
url: /de/java/com.aspose.pdf/loadoptions.resourceloadingresult/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions.ResourceLoadingResult

```
public static class LoadOptions.ResourceLoadingResult extends Object
```

Ergebnis des benutzerdefinierten Ladens einer Ressource

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ResourceLoadingResult](#ResourceLoadingResult-byte:A-) | Erstellt eine Instanz des Ladeergebnisses |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getData](#getData--) | Binärdaten, die mit einem benutzerdefinierten Loader geladen wurden – sie müssen nach dem Laden gesetzt werden |
| [getEncodingIfKnown](#getEncodingIfKnown--) | Manchmal ist die Kodierung einer Ressource nach oder während des Ladens bekannt. In einem solchen Fall kann benutzerdefinierter Code den Konverter über diesen Parameter mit diesem Wissen versorgen. Sie können in diesem Parameter null lassen, wenn die Kodierung unbekannt ist oder keine Rolle spielt. |
| [getExceptionOfLoadingIfAny](#getExceptionOfLoadingIfAny--) | Manchmal ist es aus irgendeinem Grund nicht möglich, die angeforderte Ressource zu laden. Die Nichtverfügbarkeit einer Ressource führt oft nicht zu einem Absturz der Konvertierungen und das Ergebnisdokument kann trotzdem erstellt werden (eventuell in etwas geringerer Qualität, ohne Bilder usw.). Wenn während des Ladens eine Ausnahme auftritt, fangen Sie sie einfach ab und übergeben sie in diesem Parameter – manchmal ist diese Information für den Konverter beim Rendern des Ergebnisses nützlich. |
| [getMIMETypeIfKnown](#getMIMETypeIfKnown--) | Manchmal ist das Wissen über den MIME‑Typ einer geladenen Ressource für den Konverter nützlich. Sie können den MIME‑Typ (falls er nach dem Laden bekannt ist) in diesem Parameter angeben. Bitte lassen Sie den Parameter gleich null, wenn der MIME‑Typ unbekannt ist oder nicht bereitgestellt werden muss. |
| [isLoadingCancelled](#isLoadingCancelled--) | Manchmal sollte das Laden aus bestimmten Gründen nicht durch benutzerdefinierten Code erfolgen. Setzen Sie in diesem Fall das Flag auf True. Der Konverter wird dann versuchen, den internen Standard‑Ressourcen‑Loader zu verwenden, um dieses Ergebnis zu erhalten (wie er sich verhält, wenn keine benutzerdefinierte Strategie bereitgestellt wird). |
| [setEncodingIfKnown](#setEncodingIfKnown-java.nio.charset.Charset-) | Manchmal ist die Kodierung einer Ressource nach oder während des Ladens bekannt. In einem solchen Fall kann benutzerdefinierter Code den Konverter über diesen Parameter mit diesem Wissen versorgen. Sie können in diesem Parameter null lassen, wenn die Kodierung unbekannt ist oder keine Rolle spielt. |
| [setExceptionOfLoadingIfAny](#setExceptionOfLoadingIfAny-com.aspose.ms.System.Exception-) | Manchmal ist es aus irgendeinem Grund nicht möglich, die angeforderte Ressource zu laden. |
| [setLoadingCancelled](#setLoadingCancelled-boolean-) | Manchmal sollte das Laden aus bestimmten Gründen nicht durch benutzerdefinierten Code erfolgen. Setzen Sie in diesem Fall das Flag auf True. Der Konverter wird dann versuchen, den internen Standard‑Ressourcen‑Loader zu verwenden, um dieses Ergebnis zu erhalten (wie er sich verhält, wenn keine benutzerdefinierte Strategie bereitgestellt wird). |
| [setMIMETypeIfKnown](#setMIMETypeIfKnown-java.lang.String-) | Manchmal ist das Wissen über den MIME‑Typ einer geladenen Ressource für den Konverter nützlich. Sie können den MIME‑Typ (falls er nach dem Laden bekannt ist) in diesem Parameter angeben. Bitte lassen Sie den Parameter gleich null, wenn der MIME‑Typ unbekannt ist oder nicht bereitgestellt werden muss. |

### ResourceLoadingResult {#ResourceLoadingResult-byte:A-}
```
public ResourceLoadingResult(byte[] data)
```

Erstellt eine Instanz des Ladeergebnisses

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Daten |  | Das Ergebnis des benutzerdefinierten Ladens muss immer bereitgestellt werden; es kann ein Array mit Länge 0 sein, wenn es unmöglich ist, ein Ergebnis zu erhalten. |

### getData {#getData--}
```
public byte[] getData()
```

Binärdaten, die mit einem benutzerdefinierten Loader geladen wurden – sie müssen nach dem Laden gesetzt werden

**Returns:**
Array von Byte‑Werten

### getEncodingIfKnown {#getEncodingIfKnown--}
```
public Charset getEncodingIfKnown()
```

Manchmal ist die Kodierung einer Ressource nach oder während des Ladens bekannt. In einem solchen Fall kann benutzerdefinierter Code den Konverter über diesen Parameter mit diesem Wissen versorgen. Sie können in diesem Parameter null lassen, wenn die Kodierung unbekannt ist oder keine Rolle spielt.

**Returns:**
Charset‑Instanz

### getExceptionOfLoadingIfAny {#getExceptionOfLoadingIfAny--}
```
public com.aspose.ms.System.Exception getExceptionOfLoadingIfAny()
```

Manchmal ist es aus irgendeinem Grund nicht möglich, die angeforderte Ressource zu laden. Die Nichtverfügbarkeit einer Ressource führt oft nicht zu einem Absturz der Konvertierungen und das Ergebnisdokument kann trotzdem erstellt werden (eventuell in etwas geringerer Qualität, ohne Bilder usw.). Wenn während des Ladens eine Ausnahme auftritt, fangen Sie sie einfach ab und übergeben sie in diesem Parameter – manchmal ist diese Information für den Konverter beim Rendern des Ergebnisses nützlich.

**Returns:**
Exception

### getMIMETypeIfKnown {#getMIMETypeIfKnown--}
```
public String getMIMETypeIfKnown()
```

Manchmal ist das Wissen über den MIME‑Typ einer geladenen Ressource für den Konverter nützlich. Sie können den MIME‑Typ (falls er nach dem Laden bekannt ist) in diesem Parameter angeben. Bitte lassen Sie den Parameter gleich null, wenn der MIME‑Typ unbekannt ist oder nicht bereitgestellt werden muss.

**Returns:**
String Wert

### isLoadingCancelled {#isLoadingCancelled--}
```
public boolean isLoadingCancelled()
```

Manchmal sollte das Laden aus bestimmten Gründen nicht durch benutzerdefinierten Code erfolgen. Setzen Sie in diesem Fall das Flag auf True. Der Konverter wird dann versuchen, den internen Standard‑Ressourcen‑Loader zu verwenden, um dieses Ergebnis zu erhalten (wie er sich verhält, wenn keine benutzerdefinierte Strategie bereitgestellt wird).

**Returns:**
boolescher Wert

### setEncodingIfKnown {#setEncodingIfKnown-java.nio.charset.Charset-}
Manchmal ist die Kodierung einer Ressource nach oder während des Ladens bekannt. In einem solchen Fall kann benutzerdefinierter Code den Konverter über diesen Parameter mit diesem Wissen versorgen. Sie können in diesem Parameter null lassen, wenn die Kodierung unbekannt ist oder keine Rolle spielt.

### setExceptionOfLoadingIfAny {#setExceptionOfLoadingIfAny-com.aspose.ms.System.Exception-}
Manchmal ist es aus irgendeinem Grund nicht möglich, die angeforderte Ressource zu laden.

### setLoadingCancelled {#setLoadingCancelled-boolean-}
```
public void setLoadingCancelled(boolean loadingCancelled)
```

Manchmal sollte das Laden aus bestimmten Gründen nicht durch benutzerdefinierten Code erfolgen. Setzen Sie in diesem Fall das Flag auf True. Der Konverter wird dann versuchen, den internen Standard‑Ressourcen‑Loader zu verwenden, um dieses Ergebnis zu erhalten (wie er sich verhält, wenn keine benutzerdefinierte Strategie bereitgestellt wird).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| loadingCancelled |  | boolescher Wert |

### setMIMETypeIfKnown {#setMIMETypeIfKnown-java.lang.String-}
Manchmal ist das Wissen über den MIME‑Typ einer geladenen Ressource für den Konverter nützlich. Sie können den MIME‑Typ (falls er nach dem Laden bekannt ist) in diesem Parameter angeben. Bitte lassen Sie den Parameter gleich null, wenn der MIME‑Typ unbekannt ist oder nicht bereitgestellt werden muss.
