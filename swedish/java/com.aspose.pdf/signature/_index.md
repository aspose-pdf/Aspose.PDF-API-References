---
title: "Signature"
linktitle: "Signature"
second_title: "Aspose.PDF för Java API-referens"
description: "En abstrakt klass som representerar signaturobjekt i pdf-dokumentet. Signaturer är fält med värden av signaturobjekt, där de sista innehåller data som används för att verifiera dem."
type: docs
weight: 4490
url: /sv/java/com.aspose.pdf/signature/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Signature

```
public abstract class Signature extends Object
```

En abstrakt klass som representerar signaturobjekt i PDF-dokumentet. Signaturer är fält med värden av signaturobjekt, där de sista innehåller data som används för att verifiera dokumentets giltighet.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [Signature](#Signature--) | Initierar en ny instans av {@code Signature}-klassen. |
| [Signature](#Signature-java.io.InputStream-java.lang.String-) | Initierar en ny instans av {@code Signature}-klassen. |
| [Signature](#Signature-java.lang.String-java.lang.String-) | Initierar en ny instans av {@code Signature}-klassen. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [close](#close--) | Destruktor som stänger temporära strömmar (om nödvändigt). |
| [getAuthority](#getAuthority--) | Namnet på personen eller myndigheten som undertecknar dokumentet. |
| [getByteRange](#getByteRange--) | Hämta en array av heltalpar (startbyteoffset, längd i byte) som ska beskriva det exakta byteintervallet för beräkning av digest. |
| [getContactInfo](#getContactInfo--) | Hämta information som tillhandahålls av undertecknaren för att möjliggöra att en mottagare kan kontakta undertecknaren för att verifiera signaturen, t.ex. ett telefonnummer. |
| [getCustomAppearance](#getCustomAppearance--) | Hämtar/anger det anpassade utseendet. |
| [getCustomSign](#getCustomSign--) | Delegaten för anpassad hashning och signering av dokumentet (Beta). {@code The algorithm with which you hash and sign the document in the delegate must match the type of the certificate's private key.} |
| [getCustomSignHash](#getCustomSignHash--) | Delegaten för anpassad signering av dokumenthashen (Beta). {@code The algorithm with which you sign the hash in the delegate must match the type of the certificate's private key.} |
| [getDate](#getDate--) | Hämtar signeringstidpunkten. |
| [getDefaultSignatureLength](#getDefaultSignatureLength--) | Hämtar eller anger standardlängden för signaturdata i byte. Detta är en uppskattning av signaturens längd i byte. Används för signering via {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) om parametern {@code AvoidEstimatingSignatureLength}({@code #getAvoidEstimatingSignatureLength}/{@code #setAvoidEstimatingSignatureLength(boolean)}) är satt. Standardvärdet är 3000. |
| [getImageInternal](#getImageInternal--) | Hämtar bildström. Endast för internt bruk. |
| [getLocation](#getLocation--) | Hämtar CPU-värdnamnet eller den fysiska platsen för signeringen. |
| [getOcspSettings](#getOcspSettings--) | Hämtar/anger ocsp-inställningar. |
| [getReason](#getReason--) | Hämtar orsaken till signeringen, till exempel (I agreed!, Pip B.). |
| [getSignatureAlgorithmInfo](#getSignatureAlgorithmInfo--) | Hämtar information om signaturalgoritmen som används i signaturen. |
| [getSignatureReferences](#getSignatureReferences--) | get Signaturreferenser |
| [getTimestampSettings](#getTimestampSettings--) | Hämtar tidsstämpelinställningar. |
| [getUseLtv](#getUseLtv--) | Hämtar/inställer ltv‑valideringsflagga. |
| [isAvoidEstimatingSignatureLength](#isAvoidEstimatingSignatureLength--) | Hämtar och inställer ett alternativ som anger om signaturens längd ska undvikas att uppskattas. Undviker att uppskatta signaturlängden innan ett signeringsdokument. Används för signering via {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) och via {@code ExternalSignature}. Om {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) returnerar en signatur som är längre än {@code DefaultSignatureLength}({@code #getDefaultSignatureLength}/{@code #setDefaultSignatureLength(int)}), kastas {@code SignatureLengthMismatchException}. Standardvärdet är {@code false}. |
| [isShowProperties](#isShowProperties--) | Tvinga att visa/dölja signaturegenskaper. Om ShowProperties är true har signaturfältet ett fördefinierat format för utseende (strängar att representera): ------------------------------------------- Digitally signed by {certificate subject} Date: {signature.Date} Reason: {signature.Reason} Location: {signature.Location} ------------------------------------------- där {X} är en platshållare för X‑värdet. Signaturen kan också ha en bild; i så fall placeras de listade strängarna över bilden. ShowProperties är true som standard. |
| [setAuthority](#setAuthority-java.lang.String-) | Ställer in namnet på personen eller myndigheten som signerar dokumentet. |
| [setAvoidEstimatingSignatureLength](#setAvoidEstimatingSignatureLength-boolean-) | Hämtar och inställer ett alternativ som anger om signaturens längd ska undvikas att uppskattas. Undviker att uppskatta signaturlängden innan ett signeringsdokument. Används för signering via {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) och via {@code ExternalSignature}. Om {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) returnerar en signatur som är längre än {@code DefaultSignatureLength}({@code #getDefaultSignatureLength}/{@code #setDefaultSignatureLength(int)}), kastas {@code SignatureLengthMismatchException}. Standardvärdet är {@code false}. |
| [setContactInfo](#setContactInfo-java.lang.String-) | Ställ in information som tillhandahålls av undertecknaren för att möjliggöra att en mottagare kan kontakta undertecknaren för att verifiera signaturen, t.ex. ett telefonnummer. |
| [setCustomAppearance](#setCustomAppearance-com.aspose.pdf.SignatureCustomAppearance-) | Hämtar/anger det anpassade utseendet. |
| [setCustomSign](#setCustomSign-com.aspose.pdf.CustomSign-) | Delegaten för anpassad hashning och signering av dokumentet (Beta). {@code The algorithm with which you hash and sign the document in the delegate must match the type of the certificate's private key.} |
| [setCustomSignHash](#setCustomSignHash-com.aspose.pdf.SignHash-) | Delegaten för anpassad signering av dokumenthashen (Beta). {@code The algorithm with which you sign the hash in the delegate must match the type of the certificate's private key.} |
| [setDate](#setDate-java.util.Date-) | Ställ in signeringstiden. |
| [setDefaultSignatureLength](#setDefaultSignatureLength-int-) | Hämtar eller anger standardlängden för signaturdata i byte. Detta är en uppskattning av signaturens längd i byte. Används för signering via {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) om parametern {@code AvoidEstimatingSignatureLength}({@code #getAvoidEstimatingSignatureLength}/{@code #setAvoidEstimatingSignatureLength(boolean)}) är satt. Standardvärdet är 3000. |
| [setImage](#setImage-java.io.InputStream-) | Ställer in bildström. |
| [setImageInternal](#setImageInternal-com.aspose.ms.System.IO.Stream-) |  |
| [setLocation](#setLocation-java.lang.String-) | Ställer in CPU‑värdnamnet eller den fysiska platsen för signeringen. |
| [setOcspSettings](#setOcspSettings-com.aspose.pdf.OcspSettings-) | Hämtar/anger ocsp-inställningar. |
| [setReason](#setReason-java.lang.String-) | Ställer in orsaken till signeringen, till exempel (I agreed!, Pip B.). |
| [setShowProperties](#setShowProperties-boolean-) | Tvinga att visa/dölja signaturegenskaper. Om ShowProperties är true har signaturfältet ett fördefinierat format för utseende (strängar att representera): ------------------------------------------- Digitally signed by {certificate subject} Date: {signature.Date} Reason: {signature.Reason} Location: {signature.Location} ------------------------------------------- där {X} är en platshållare för X‑värdet. Signaturen kan också ha en bild; i så fall placeras de listade strängarna över bilden. ShowProperties är true som standard. |
| [setTimestampSettings](#setTimestampSettings-com.aspose.pdf.TimestampSettings-) | Ställer in tidsstämpelinställningar. |
| [setUseLtv](#setUseLtv-boolean-) | Hämtar/inställer ltv‑valideringsflagga. |
| [verify](#verify--) | Verifiera dokumentet med avseende på denna signatur och returnera true om dokumentet är giltigt annars false. |
| [verify](#verify-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-) | Verifiera dokumentet med avseende på denna signatur och returnera true om dokumentet är giltigt annars false. |
| [verify](#verify-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-) | Verifiera dokumentet med avseende på denna signatur och returnera true om dokumentet är giltigt annars false. |

### Signature {#Signature--}
```
public Signature()
```

Initierar en ny instans av {@code Signature}-klassen.

### Signature {#Signature-java.io.InputStream-java.lang.String-}
Initierar en ny instans av {@code Signature}-klassen.

### Signature {#Signature-java.lang.String-java.lang.String-}
Initierar en ny instans av {@code Signature}-klassen.

### close {#close--}
```
public void close()
```

Destruktor som stänger temporära strömmar (om nödvändigt).

### getAuthority {#getAuthority--}
```
public final String getAuthority()
```

Namnet på personen eller myndigheten som undertecknar dokumentet.

**Returns:**
String värde

### getByteRange {#getByteRange--}
```
public int[] getByteRange()
```

Hämta en array av heltalpar (startbyteoffset, längd i byte) som ska beskriva det exakta byteintervallet för beräkning av digest.

**Returns:**
array av int‑värde

### getContactInfo {#getContactInfo--}
```
public String getContactInfo()
```

Hämta information som tillhandahålls av undertecknaren för att möjliggöra att en mottagare kan kontakta undertecknaren för att verifiera signaturen, t.ex. ett telefonnummer.

**Returns:**
String värde

### getCustomAppearance {#getCustomAppearance--}
```
public final SignatureCustomAppearance getCustomAppearance()
```

Hämtar/anger det anpassade utseendet.

**Returns:**
SignatureCustomAppearance‑instans

### getCustomSign {#getCustomSign--}
```
public final CustomSign getCustomSign()
```

Delegaten för anpassad hashning och signering av dokumentet (Beta). {@code The algorithm with which you hash and sign the document in the delegate must match the type of the certificate's private key.}

**Returns:**
SignHash‑instans

### getCustomSignHash {#getCustomSignHash--}
```
public final SignHash getCustomSignHash()
```

Delegaten för anpassad signering av dokumenthashen (Beta). {@code The algorithm with which you sign the hash in the delegate must match the type of the certificate's private key.}

**Returns:**
SignHash‑instans

### getDate {#getDate--}
```
public Date getDate()
```

Hämtar signeringstidpunkten.

**Returns:**
Datumvärde

### getDefaultSignatureLength {#getDefaultSignatureLength--}
```
public final int getDefaultSignatureLength()
```

Hämtar eller anger standardlängden för signaturdata i byte. Detta är en uppskattning av signaturens längd i byte. Används för signering via {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) om parametern {@code AvoidEstimatingSignatureLength}({@code #getAvoidEstimatingSignatureLength}/{@code #setAvoidEstimatingSignatureLength(boolean)}) är satt. Standardvärdet är 3000.

**Returns:**
int‑värde

### getImageInternal {#getImageInternal--}
```
public com.aspose.ms.System.IO.Stream getImageInternal()
```

Hämtar bildström. Endast för internt bruk.

**Returns:**
Strömobjekt

### getLocation {#getLocation--}
```
public String getLocation()
```

Hämtar CPU-värdnamnet eller den fysiska platsen för signeringen.

**Returns:**
String värde

### getOcspSettings {#getOcspSettings--}
```
public OcspSettings getOcspSettings()
```

Hämtar/anger ocsp-inställningar.

**Returns:**
OcspSettings‑instans

### getReason {#getReason--}
```
public String getReason()
```

Hämtar orsaken till signeringen, till exempel (I agreed!, Pip B.).

**Returns:**
String värde

### getSignatureAlgorithmInfo {#getSignatureAlgorithmInfo--}
```
public final com.aspose.pdf.engine.security.SignatureAlgorithmInfo getSignatureAlgorithmInfo()
```

Hämtar information om signaturalgoritmen som används i signaturen.

**Returns:**
En instans av { SignatureAlgorithmInfo} som innehåller detaljer om signaturalgoritmen.

### getSignatureReferences {#getSignatureReferences--}
```
public List <com.aspose.pdf.engine.security.impl.signatures.SignatureReference> getSignatureReferences()
```

get Signaturreferenser

**Returns:**
{@code java.util.List<SignatureReference> object}

### getTimestampSettings {#getTimestampSettings--}
```
public TimestampSettings getTimestampSettings()
```

Hämtar tidsstämpelinställningar.

**Returns:**
TimestampSettings

### getUseLtv {#getUseLtv--}
```
public final boolean getUseLtv()
```

Hämtar/inställer ltv‑valideringsflagga.

**Returns:**
booleskt värde

### isAvoidEstimatingSignatureLength {#isAvoidEstimatingSignatureLength--}
```
public final boolean isAvoidEstimatingSignatureLength()
```

Hämtar och inställer ett alternativ som anger om signaturens längd ska undvikas att uppskattas. Undviker att uppskatta signaturlängden innan ett signeringsdokument. Används för signering via {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) och via {@code ExternalSignature}. Om {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) returnerar en signatur som är längre än {@code DefaultSignatureLength}({@code #getDefaultSignatureLength}/{@code #setDefaultSignatureLength(int)}), kastas {@code SignatureLengthMismatchException}. Standardvärdet är {@code false}.

**Returns:**
booleskt värde

### isShowProperties {#isShowProperties--}
```
public boolean isShowProperties()
```

Tvinga att visa/dölja signaturegenskaper. Om ShowProperties är true har signaturfältet ett fördefinierat format för utseende (strängar att representera): ------------------------------------------- Digitally signed by {certificate subject} Date: {signature.Date} Reason: {signature.Reason} Location: {signature.Location} ------------------------------------------- där {X} är en platshållare för X‑värdet. Signaturen kan också ha en bild; i så fall placeras de listade strängarna över bilden. ShowProperties är true som standard.

**Returns:**
booleskt värde

### setAuthority {#setAuthority-java.lang.String-}
Ställer in namnet på personen eller myndigheten som signerar dokumentet.

### setAvoidEstimatingSignatureLength {#setAvoidEstimatingSignatureLength-boolean-}
```
public final void setAvoidEstimatingSignatureLength(boolean value)
```

Hämtar och inställer ett alternativ som anger om signaturens längd ska undvikas att uppskattas. Undviker att uppskatta signaturlängden innan ett signeringsdokument. Används för signering via {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) och via {@code ExternalSignature}. Om {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) returnerar en signatur som är längre än {@code DefaultSignatureLength}({@code #getDefaultSignatureLength}/{@code #setDefaultSignatureLength(int)}), kastas {@code SignatureLengthMismatchException}. Standardvärdet är {@code false}.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setContactInfo {#setContactInfo-java.lang.String-}
Ställ in information som tillhandahålls av undertecknaren för att möjliggöra att en mottagare kan kontakta undertecknaren för att verifiera signaturen, t.ex. ett telefonnummer.

### setCustomAppearance {#setCustomAppearance-com.aspose.pdf.SignatureCustomAppearance-}
Hämtar/anger det anpassade utseendet.

### setCustomSign {#setCustomSign-com.aspose.pdf.CustomSign-}
Delegaten för anpassad hashning och signering av dokumentet (Beta). {@code The algorithm with which you hash and sign the document in the delegate must match the type of the certificate's private key.}

### setCustomSignHash {#setCustomSignHash-com.aspose.pdf.SignHash-}
Delegaten för anpassad signering av dokumenthashen (Beta). {@code The algorithm with which you sign the hash in the delegate must match the type of the certificate's private key.}

### setDate {#setDate-java.util.Date-}
Ställ in signeringstiden.

### setDefaultSignatureLength {#setDefaultSignatureLength-int-}
```
public final void setDefaultSignatureLength(int value)
```

Hämtar eller anger standardlängden för signaturdata i byte. Detta är en uppskattning av signaturens längd i byte. Används för signering via {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) om parametern {@code AvoidEstimatingSignatureLength}({@code #getAvoidEstimatingSignatureLength}/{@code #setAvoidEstimatingSignatureLength(boolean)}) är satt. Standardvärdet är 3000.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde |

### setImage {#setImage-java.io.InputStream-}
Ställer in bildström.

### setImageInternal {#setImageInternal-com.aspose.ms.System.IO.Stream-}


### setLocation {#setLocation-java.lang.String-}
Ställer in CPU‑värdnamnet eller den fysiska platsen för signeringen.

### setOcspSettings {#setOcspSettings-com.aspose.pdf.OcspSettings-}
Hämtar/anger ocsp-inställningar.

### setReason {#setReason-java.lang.String-}
Ställer in orsaken till signeringen, till exempel (I agreed!, Pip B.).

### setShowProperties {#setShowProperties-boolean-}
```
public void setShowProperties(boolean value)
```

Tvinga att visa/dölja signaturegenskaper. Om ShowProperties är true har signaturfältet ett fördefinierat format för utseende (strängar att representera): ------------------------------------------- Digitally signed by {certificate subject} Date: {signature.Date} Reason: {signature.Reason} Location: {signature.Location} ------------------------------------------- där {X} är en platshållare för X‑värdet. Signaturen kan också ha en bild; i så fall placeras de listade strängarna över bilden. ShowProperties är true som standard.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setTimestampSettings {#setTimestampSettings-com.aspose.pdf.TimestampSettings-}
Ställer in tidsstämpelinställningar.

### setUseLtv {#setUseLtv-boolean-}
```
public final void setUseLtv(boolean value)
```

Hämtar/inställer ltv‑valideringsflagga.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### verify {#verify--}
```
public boolean verify()
```

Verifiera dokumentet med avseende på denna signatur och returnera true om dokumentet är giltigt annars false.

**Returns:**
true om dokumentet är giltigt.

### verify {#verify-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-}
Verifiera dokumentet med avseende på denna signatur och returnera true om dokumentet är giltigt annars false.

**Returns:**
true om dokumentet är giltigt.

### verify {#verify-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-}
Verifiera dokumentet med avseende på denna signatur och returnera true om dokumentet är giltigt annars false.

**Returns:**
true om dokumentet är giltigt.
