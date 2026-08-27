---
title: "License"
linktitle: "License"
second_title: "Aspose.PDF för Java API-referens"
description: "Tillhandahåller metoder för att licensiera komponenten. I det här exemplet kommer ett försök att hitta en licensfil med namnet MyLicense.lic i mappen som innehåller komponenten, i."
type: docs
weight: 2670
url: /sv/java/com.aspose.pdf/license/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.License

```
public class License extends Object
```

Tillhandahåller metoder för att licensiera komponenten. I det här exemplet kommer ett försök att hitta en licensfil med namnet MyLicense.lic i mappen som innehåller komponenten, i mappen som innehåller den anropande samlingen, i mappen för ingångssamlingen och sedan i de inbäddade resurserna för den anropande samlingen. License license = new License(); license.setLicense("MyLicense.lic");

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [License](#License--) | Initierar en ny instans av den här klassen. I det här exemplet kommer ett försök att hitta en licensfil med namnet MyLicense.lic i mappen som innehåller komponenten, i mappen som innehåller den anropande samlingen, i mappen för startsamlingen och sedan i de inbäddade resurserna för den anropande samlingen. License license = new License(); license.setLicense("MyLicense.lic"); |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [clearLicense](#clearLicense--) | Rensar den aktuella licensen. |
| [getLicenseInfo](#getLicenseInfo--) | Hämtar den aktuella licensinformationen. |
| [isInternalFIPSSecurity](#isInternalFIPSSecurity--) | Som standard använder vi standard jdk-säkerhet. Standardvärde == false. I vissa fall kan en anpassad java-miljö inte stödja erforderliga algoritmer, så vi kan föreslå att använda intern inbyggd FIPS-säkerhet. |
| [setInternalFIPSSecurity](#setInternalFIPSSecurity-boolean-) | Som standard använder vi standard jre-säkerhet. Standardvärde == false. I vissa fall kan en anpassad java-miljö inte stödja erforderliga algoritmer, så vi kan föreslå att använda intern inbyggd FIPS-säkerhet. <p> Observera också: Enligt JVM SecureRandom-algoritmen väntar /dev/random på vissa operativsystem på en viss mängd “brus” som genereras på värddatorn innan ett resultat returneras. Biblioteket som används för slumpmässig talgenerering i Oracles JVM förlitar sig som standard på /dev/random för UNIX-plattformar. Även om /dev/random är säkrare rekommenderas att använda /dev/urandom om standard JVM‑konfigurationen har fördröjningar, eller att lägga till enheter som genererar entropi för /dev/random. <p> Följande java‑alternativ kan hjälpa till att undvika fördröjningar och åsidosätta inställningen securerandom.source. -Djava.security.egd=file:/dev/./urandom |
| [setLicense](#setLicense-java.io.InputStream-) | Licensierar komponenten. En ström som innehåller licensen. Använd den här metoden för att läsa in en licens från en ström. License license = new License(); license.setLicense(myStream); |
| [setLicense](#setLicense-java.lang.String-) | Licensierar komponenten. Försöker hitta licensen på följande platser: 1. Explicit sökväg. 2. Mappen för komponentens jar‑fil. I det här exemplet kommer ett försök göras att hitta en licensfil med namnet MyLicense.lic i mappen som innehåller komponenten, i mappen som innehåller den anropande samlingen, i mappen för startsamlingen och sedan i de inbäddade resurserna för den anropande samlingen. License license = new License(); license.setLicense("MyLicense.lic"); |

### License {#License--}
```
public License()
```

Initierar en ny instans av den här klassen. I det här exemplet kommer ett försök att hitta en licensfil med namnet MyLicense.lic i mappen som innehåller komponenten, i mappen som innehåller den anropande samlingen, i mappen för startsamlingen och sedan i de inbäddade resurserna för den anropande samlingen. License license = new License(); license.setLicense("MyLicense.lic");

### clearLicense {#clearLicense--}
```
public final void clearLicense()
```

Rensar den aktuella licensen.

### getLicenseInfo {#getLicenseInfo--}
```
public final LicenseInfo getLicenseInfo()
```

Hämtar den aktuella licensinformationen.

**Returns:**
LicenseInfo-instans

### isInternalFIPSSecurity {#isInternalFIPSSecurity--}
```
public static boolean isInternalFIPSSecurity()
```

Som standard använder vi standard jdk-säkerhet. Standardvärde == false. I vissa fall kan en anpassad java-miljö inte stödja erforderliga algoritmer, så vi kan föreslå att använda intern inbyggd FIPS-säkerhet.

**Returns:**
booleskt värde

### setInternalFIPSSecurity {#setInternalFIPSSecurity-boolean-}
```
public static void setInternalFIPSSecurity(boolean internalFIPSSecurity)
```

Som standard använder vi standard jre-säkerhet. Standardvärde == false. I vissa fall kan en anpassad java-miljö inte stödja erforderliga algoritmer, så vi kan föreslå att använda intern inbyggd FIPS-säkerhet. <p> Observera också: Enligt JVM SecureRandom-algoritmen väntar /dev/random på vissa operativsystem på en viss mängd “brus” som genereras på värddatorn innan ett resultat returneras. Biblioteket som används för slumpmässig talgenerering i Oracles JVM förlitar sig som standard på /dev/random för UNIX-plattformar. Även om /dev/random är säkrare rekommenderas att använda /dev/urandom om standard JVM‑konfigurationen har fördröjningar, eller att lägga till enheter som genererar entropi för /dev/random. <p> Följande java‑alternativ kan hjälpa till att undvika fördröjningar och åsidosätta inställningen securerandom.source. -Djava.security.egd=file:/dev/./urandom

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| internalFIPSSecurity |  | booleskt värde |

### setLicense {#setLicense-java.io.InputStream-}
Licensierar komponenten. En ström som innehåller licensen. Använd den här metoden för att läsa in en licens från en ström. License license = new License(); license.setLicense(myStream);

### setLicense {#setLicense-java.lang.String-}
Licensierar komponenten. Försöker hitta licensen på följande platser: 1. Explicit sökväg. 2. Mappen för komponentens jar‑fil. I det här exemplet kommer ett försök göras att hitta en licensfil med namnet MyLicense.lic i mappen som innehåller komponenten, i mappen som innehåller den anropande samlingen, i mappen för startsamlingen och sedan i de inbäddade resurserna för den anropande samlingen. License license = new License(); license.setLicense("MyLicense.lic");
