---
title: "TimestampSettings"
linktitle: "TimestampSettings"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar ocsp-inställningarna som används under signeringsprocessen."
type: docs
weight: 5360
url: /sv/java/com.aspose.pdf/timestampsettings/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TimestampSettings

```
public class TimestampSettings extends Object
```

Representerar ocsp-inställningarna som används under signeringsprocessen.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [TimestampSettings](#TimestampSettings-java.lang.String-java.lang.String-) | Initierar en ny instans av klassen {@code TimestampSettings}. |
| [TimestampSettings](#TimestampSettings-java.lang.String-java.lang.String-com.aspose.pdf.DigestHashAlgorithm-) | Initierar en ny instans av klassen {@code TimestampSettings}. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBasicAuthCredentials](#getBasicAuthCredentials--) | Hämtar de grundläggande autentiseringsuppgifterna, Användarnamn och lösenord kombineras till en sträng "username:password". |
| [getDigestHashAlgorithm](#getDigestHashAlgorithm--) | Hämtar/anger digest-algoritmen för interna hash-funktioner. |
| [getServerUrl](#getServerUrl--) | Hämtar tidsstämpelserverns URL. |
| [setBasicAuthCredentials](#setBasicAuthCredentials-java.lang.String-) | Anger de grundläggande autentiseringsuppgifterna, Användarnamn och lösenord kombineras till en sträng "username:password". |
| [setDigestHashAlgorithm](#setDigestHashAlgorithm-com.aspose.pdf.DigestHashAlgorithm-) | Hämtar/anger digest-algoritmen för interna hash-funktioner. |
| [setServerUrl](#setServerUrl-java.lang.String-) | Anger tidsstämpelserverns URL. |

### TimestampSettings {#TimestampSettings-java.lang.String-java.lang.String-}
Initierar en ny instans av klassen {@code TimestampSettings}.

### TimestampSettings {#TimestampSettings-java.lang.String-java.lang.String-com.aspose.pdf.DigestHashAlgorithm-}
Initierar en ny instans av klassen {@code TimestampSettings}.

### getBasicAuthCredentials {#getBasicAuthCredentials--}
```
public String getBasicAuthCredentials()
```

Hämtar de grundläggande autentiseringsuppgifterna, Användarnamn och lösenord kombineras till en sträng "username:password".

**Returns:**
String värde

### getDigestHashAlgorithm {#getDigestHashAlgorithm--}
```
public final DigestHashAlgorithm getDigestHashAlgorithm()
```

Hämtar/anger digest-algoritmen för interna hash-funktioner.

**Returns:**
DigestHashAlgorithm-element @see DigestHashAlgorithm

### getServerUrl {#getServerUrl--}
```
public String getServerUrl()
```

Hämtar tidsstämpelserverns URL.

**Returns:**
String värde

### setBasicAuthCredentials {#setBasicAuthCredentials-java.lang.String-}
Anger de grundläggande autentiseringsuppgifterna, Användarnamn och lösenord kombineras till en sträng "username:password".

### setDigestHashAlgorithm {#setDigestHashAlgorithm-com.aspose.pdf.DigestHashAlgorithm-}
Hämtar/anger digest-algoritmen för interna hash-funktioner.

### setServerUrl {#setServerUrl-java.lang.String-}
Anger tidsstämpelserverns URL.
