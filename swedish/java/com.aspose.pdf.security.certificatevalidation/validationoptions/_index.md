---
title: "ValidationOptions"
linktitle: "ValidationOptions"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar alternativ för att validera en digital signatur i ett PDF‑dokument."
type: docs
weight: 30
url: /sv/java/com.aspose.pdf.security.certificatevalidation/validationoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.security.certificatevalidation.ValidationOptions

```
public final class ValidationOptions extends Object
```

Representerar alternativ för att validera en digital signatur i ett PDF‑dokument.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [ValidationOptions](#ValidationOptions--) | Skapar en instans av {@link ValidationOptions}‑klassen. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getCheckCertificateChain](#getCheckCertificateChain--) | Hämtar eller anger ett värde som indikerar om certifikatkedjan ska kontrolleras under valideringsprocessen. När egenskapen är satt kontrolleras existensen av en kedja av certifikat; om den saknas blir resultatet av verifieringen {@link ValidationStatus#Undefined}, vilket motsvarar Adobe Acrobats beteende. Om du bara vill kontrollera revocationsstatus online, sätt fältet till {@code false}. Standardvärdet är {@code false}. |
| [getRequestTimeout](#getRequestTimeout--) | Hämtar eller anger timeout-tiden, i millisekunder, för nätverksrelaterade operationer under valideringsprocessen. Egenskapen RequestTimeout definierar den maximala tid systemet ska vänta på ett nätverkssvar när det åtkommer till online-resurser, såsom revocationsstatus eller OCSP-servrar. |
| [getValidationMethod](#getValidationMethod--) | Hämtar eller anger metoden som används för att validera ett certifikat. |
| [getValidationMode](#getValidationMode--) | Hämtar eller anger valideringsläget för digitala signaturer i ett PDF-dokument. ValidationMode‑egenskapen bestämmer hur strikt valideringsprocessen är. |
| [setCheckCertificateChain](#setCheckCertificateChain-boolean-) | Hämtar eller anger ett värde som indikerar om certifikatkedjan ska kontrolleras under valideringsprocessen. När egenskapen är satt kontrolleras existensen av en kedja av certifikat; om den saknas blir resultatet av verifieringen {@link ValidationStatus#Undefined}, vilket motsvarar Adobe Acrobats beteende. Om du bara vill kontrollera revocationsstatus online, sätt fältet till {@code false}. Standardvärdet är {@code false}. |
| [setRequestTimeout](#setRequestTimeout-int-) | Hämtar eller anger timeout-tiden, i millisekunder, för nätverksrelaterade operationer under valideringsprocessen. Egenskapen RequestTimeout definierar den maximala tid systemet ska vänta på ett nätverkssvar när det åtkommer till online-resurser, såsom revocationsstatus eller OCSP-servrar. |
| [setValidationMethod](#setValidationMethod-int-) | Hämtar eller anger metoden som används för att validera ett certifikat. |
| [setValidationMode](#setValidationMode-int-) | Hämtar eller anger valideringsläget för digitala signaturer i ett PDF-dokument. ValidationMode‑egenskapen bestämmer hur strikt valideringsprocessen är. |

### ValidationOptions {#ValidationOptions--}
```
public ValidationOptions()
```

Skapar en instans av {@link ValidationOptions}‑klassen.

### getCheckCertificateChain {#getCheckCertificateChain--}
```
public final boolean getCheckCertificateChain()
```

Hämtar eller anger ett värde som indikerar om certifikatkedjan ska kontrolleras under valideringsprocessen. När egenskapen är satt kontrolleras existensen av en kedja av certifikat; om den saknas blir resultatet av verifieringen {@link ValidationStatus#Undefined}, vilket motsvarar Adobe Acrobats beteende. Om du bara vill kontrollera revocationsstatus online, sätt fältet till {@code false}. Standardvärdet är {@code false}.

**Returns:**
booleskt värde

### getRequestTimeout {#getRequestTimeout--}
```
public final int getRequestTimeout()
```

Hämtar eller anger timeout-tiden, i millisekunder, för nätverksrelaterade operationer under valideringsprocessen. Egenskapen RequestTimeout definierar den maximala tid systemet ska vänta på ett nätverkssvar när det åtkommer till online-resurser, såsom revocationsstatus eller OCSP-servrar.

**Returns:**
int‑värde

### getValidationMethod {#getValidationMethod--}
```
public final int getValidationMethod()
```

Hämtar eller anger metoden som används för att validera ett certifikat.

**Returns:**
ValidationMethod‑element

### getValidationMode {#getValidationMode--}
```
public final int getValidationMode()
```

Hämtar eller anger valideringsläget för digitala signaturer i ett PDF-dokument. ValidationMode‑egenskapen bestämmer hur strikt valideringsprocessen är.

**Returns:**
ValidationMode‑element

### setCheckCertificateChain {#setCheckCertificateChain-boolean-}
```
public final void setCheckCertificateChain(boolean value)
```

Hämtar eller anger ett värde som indikerar om certifikatkedjan ska kontrolleras under valideringsprocessen. När egenskapen är satt kontrolleras existensen av en kedja av certifikat; om den saknas blir resultatet av verifieringen {@link ValidationStatus#Undefined}, vilket motsvarar Adobe Acrobats beteende. Om du bara vill kontrollera revocationsstatus online, sätt fältet till {@code false}. Standardvärdet är {@code false}.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setRequestTimeout {#setRequestTimeout-int-}
```
public final void setRequestTimeout(int value)
```

Hämtar eller anger timeout-tiden, i millisekunder, för nätverksrelaterade operationer under valideringsprocessen. Egenskapen RequestTimeout definierar den maximala tid systemet ska vänta på ett nätverkssvar när det åtkommer till online-resurser, såsom revocationsstatus eller OCSP-servrar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde |

### setValidationMethod {#setValidationMethod-int-}
```
public final void setValidationMethod(int value)
```

Hämtar eller anger metoden som används för att validera ett certifikat.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | ValidationMethod‑element |

### setValidationMode {#setValidationMode-int-}
```
public final void setValidationMode(int value)
```

Hämtar eller anger valideringsläget för digitala signaturer i ett PDF-dokument. ValidationMode‑egenskapen bestämmer hur strikt valideringsprocessen är.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | ValidationMode‑element |
