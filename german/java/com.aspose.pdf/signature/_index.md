---
title: "Signature"
linktitle: "Signature"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Eine abstrakte Klasse, die ein Signaturobjekt im PDF-Dokument darstellt. Signaturen sind Felder mit Werten von Signaturobjekten, wobei das letzte Daten enthält, die zur Verifizierung verwendet werden."
type: docs
weight: 4490
url: /de/java/com.aspose.pdf/signature/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Signature

```
public abstract class Signature extends Object
```

Eine abstrakte Klasse, die ein Signaturobjekt im PDF-Dokument repräsentiert. Signaturen sind Felder mit Werten von Signaturobjekten, die letztlich Daten enthalten, die zur Überprüfung der Gültigkeit des Dokuments verwendet werden.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Signature](#Signature--) | Initialisiert eine neue Instanz der {@code Signature}-Klasse. |
| [Signature](#Signature-java.io.InputStream-java.lang.String-) | Initialisiert eine neue Instanz der {@code Signature}-Klasse. |
| [Signature](#Signature-java.lang.String-java.lang.String-) | Initialisiert eine neue Instanz der {@code Signature}-Klasse. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [close](#close--) | Destruktor, der temporäre Streams schließt (falls erforderlich). |
| [getAuthority](#getAuthority--) | Der Name der Person oder Behörde, die das Dokument unterschreibt. |
| [getByteRange](#getByteRange--) | Gibt ein Array von Ganzzahlpaaren (Start-Byte-Offset, Länge in Bytes) zurück, das den genauen Bytebereich für die Digest-Berechnung beschreibt. |
| [getContactInfo](#getContactInfo--) | Gibt Informationen zurück, die vom Unterzeichner bereitgestellt werden, um einem Empfänger zu ermöglichen, den Unterzeichner zur Überprüfung der Signatur zu kontaktieren, z. B. eine Telefonnummer. |
| [getCustomAppearance](#getCustomAppearance--) | Liest/setzt das benutzerdefinierte Erscheinungsbild. |
| [getCustomSign](#getCustomSign--) | Der Delegat für benutzerdefiniertes Hashen und Signieren des Dokuments (Beta). {@code Der Algorithmus, mit dem Sie das Dokument im Delegaten hashieren und signieren, muss zum Typ des privaten Schlüssels des Zertifikats passen.} |
| [getCustomSignHash](#getCustomSignHash--) | Der Delegat für das benutzerdefinierte Signieren des Dokument-Hashes (Beta). {@code The algorithm with which you sign the hash in the delegate must match the type of the certificate's private key.} |
| [getDate](#getDate--) | Liest die Signaturzeit. |
| [getDefaultSignatureLength](#getDefaultSignatureLength--) | Liest oder setzt die Standardlänge für die Signaturdaten in Bytes. Dies ist eine Schätzung der Signaturlänge in Bytes. Wird zum Signieren über {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) verwendet, wenn der Parameter {@code AvoidEstimatingSignatureLength}({@code #getAvoidEstimatingSignatureLength}/{@code #setAvoidEstimatingSignatureLength(boolean)}) gesetzt ist. Der Standardwert ist 3000. |
| [getImageInternal](#getImageInternal--) | Liest den Bild-Stream. Nur für interne Verwendung. |
| [getLocation](#getLocation--) | Liest den CPU-Hostnamen oder den physischen Standort der Signatur. |
| [getOcspSettings](#getOcspSettings--) | Liest/setzt OCSP-Einstellungen. |
| [getReason](#getReason--) | Liest den Grund für die Signatur, z. B. (I agreed!, Pip B.). |
| [getSignatureAlgorithmInfo](#getSignatureAlgorithmInfo--) | Ruft Informationen über den in der Signatur verwendeten Signaturalgorithmus ab. |
| [getSignatureReferences](#getSignatureReferences--) | hole Signaturreferenzen |
| [getTimestampSettings](#getTimestampSettings--) | Liest Zeitstempel-Einstellungen. |
| [getUseLtv](#getUseLtv--) | Liest/setzt LTV-Validierungs-Flag. |
| [isAvoidEstimatingSignatureLength](#isAvoidEstimatingSignatureLength--) | Liest und setzt eine Option, die angibt, ob die Schätzung der Signaturlänge vermieden werden soll. Vermeidet die Schätzung der Signaturlänge vor einem zu signierenden Dokument. Wird zum Signieren über {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) und über {@code ExternalSignature} verwendet. Wenn {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) eine Signatur zurückgibt, die länger ist als {@code DefaultSignatureLength}({@code #getDefaultSignatureLength}/{@code #setDefaultSignatureLength(int)}), wird {@code SignatureLengthMismatchException} ausgelöst. Der Standardwert ist {@code false}. |
| [isShowProperties](#isShowProperties--) | Erzwingt das Anzeigen/Verbergen von Signatur-Eigenschaften. Falls ShowProperties true ist, hat das Signaturfeld ein vordefiniertes Anzeigeformat (Zeichenketten zur Darstellung): ------------------------------------------- Digital signiert von {certificate subject} Datum: {signature.Date} Grund: {signature.Reason} Ort: {signature.Location} ------------------------------------------- wobei {X} ein Platzhalter für den X‑Wert ist. Die Signatur kann auch ein Bild enthalten; in diesem Fall werden die aufgeführten Zeichenketten über das Bild gelegt. ShowProperties ist standardmäßig true. |
| [setAuthority](#setAuthority-java.lang.String-) | Setzt den Namen der Person oder Behörde, die das Dokument signiert. |
| [setAvoidEstimatingSignatureLength](#setAvoidEstimatingSignatureLength-boolean-) | Liest und setzt eine Option, die angibt, ob die Schätzung der Signaturlänge vermieden werden soll. Vermeidet die Schätzung der Signaturlänge vor einem zu signierenden Dokument. Wird zum Signieren über {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) und über {@code ExternalSignature} verwendet. Wenn {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) eine Signatur zurückgibt, die länger ist als {@code DefaultSignatureLength}({@code #getDefaultSignatureLength}/{@code #setDefaultSignatureLength(int)}), wird {@code SignatureLengthMismatchException} ausgelöst. Der Standardwert ist {@code false}. |
| [setContactInfo](#setContactInfo-java.lang.String-) | Setzt vom Unterzeichner bereitgestellte Informationen, um einem Empfänger zu ermöglichen, den Unterzeichner zur Überprüfung der Signatur zu kontaktieren, z. B. eine Telefonnummer. |
| [setCustomAppearance](#setCustomAppearance-com.aspose.pdf.SignatureCustomAppearance-) | Liest/setzt das benutzerdefinierte Erscheinungsbild. |
| [setCustomSign](#setCustomSign-com.aspose.pdf.CustomSign-) | Der Delegat für benutzerdefiniertes Hashen und Signieren des Dokuments (Beta). {@code Der Algorithmus, mit dem Sie das Dokument im Delegaten hashieren und signieren, muss zum Typ des privaten Schlüssels des Zertifikats passen.} |
| [setCustomSignHash](#setCustomSignHash-com.aspose.pdf.SignHash-) | Der Delegat für das benutzerdefinierte Signieren des Dokument-Hashes (Beta). {@code The algorithm with which you sign the hash in the delegate must match the type of the certificate's private key.} |
| [setDate](#setDate-java.util.Date-) | Setzt die Signaturzeit. |
| [setDefaultSignatureLength](#setDefaultSignatureLength-int-) | Liest oder setzt die Standardlänge für die Signaturdaten in Bytes. Dies ist eine Schätzung der Signaturlänge in Bytes. Wird zum Signieren über {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) verwendet, wenn der Parameter {@code AvoidEstimatingSignatureLength}({@code #getAvoidEstimatingSignatureLength}/{@code #setAvoidEstimatingSignatureLength(boolean)}) gesetzt ist. Der Standardwert ist 3000. |
| [setImage](#setImage-java.io.InputStream-) | Setzt den Bild-Stream. |
| [setImageInternal](#setImageInternal-com.aspose.ms.System.IO.Stream-) |  |
| [setLocation](#setLocation-java.lang.String-) | Setzt den CPU-Hostnamen oder den physischen Standort der Signatur. |
| [setOcspSettings](#setOcspSettings-com.aspose.pdf.OcspSettings-) | Liest/setzt OCSP-Einstellungen. |
| [setReason](#setReason-java.lang.String-) | Setzt den Grund für die Signatur, z. B. (I agreed!, Pip B.). |
| [setShowProperties](#setShowProperties-boolean-) | Erzwingt das Anzeigen/Verbergen von Signatur-Eigenschaften. Falls ShowProperties true ist, hat das Signaturfeld ein vordefiniertes Anzeigeformat (Zeichenketten zur Darstellung): ------------------------------------------- Digital signiert von {certificate subject} Datum: {signature.Date} Grund: {signature.Reason} Ort: {signature.Location} ------------------------------------------- wobei {X} ein Platzhalter für den X‑Wert ist. Die Signatur kann auch ein Bild enthalten; in diesem Fall werden die aufgeführten Zeichenketten über das Bild gelegt. ShowProperties ist standardmäßig true. |
| [setTimestampSettings](#setTimestampSettings-com.aspose.pdf.TimestampSettings-) | Setzt Zeitstempel-Einstellungen. |
| [setUseLtv](#setUseLtv-boolean-) | Liest/setzt LTV-Validierungs-Flag. |
| [verify](#verify--) | Überprüft das Dokument hinsichtlich dieser Signatur und gibt true zurück, wenn das Dokument gültig ist, andernfalls false. |
| [verify](#verify-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-) | Überprüft das Dokument hinsichtlich dieser Signatur und gibt true zurück, wenn das Dokument gültig ist, andernfalls false. |
| [verify](#verify-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-) | Überprüft das Dokument hinsichtlich dieser Signatur und gibt true zurück, wenn das Dokument gültig ist, andernfalls false. |

### Signature {#Signature--}
```
public Signature()
```

Initialisiert eine neue Instanz der {@code Signature}-Klasse.

### Signature {#Signature-java.io.InputStream-java.lang.String-}
Initialisiert eine neue Instanz der {@code Signature}-Klasse.

### Signature {#Signature-java.lang.String-java.lang.String-}
Initialisiert eine neue Instanz der {@code Signature}-Klasse.

### close {#close--}
```
public void close()
```

Destruktor, der temporäre Streams schließt (falls erforderlich).

### getAuthority {#getAuthority--}
```
public final String getAuthority()
```

Der Name der Person oder Behörde, die das Dokument unterschreibt.

**Returns:**
String Wert

### getByteRange {#getByteRange--}
```
public int[] getByteRange()
```

Gibt ein Array von Ganzzahlpaaren (Start-Byte-Offset, Länge in Bytes) zurück, das den genauen Bytebereich für die Digest-Berechnung beschreibt.

**Returns:**
Array von int-Werten

### getContactInfo {#getContactInfo--}
```
public String getContactInfo()
```

Gibt Informationen zurück, die vom Unterzeichner bereitgestellt werden, um einem Empfänger zu ermöglichen, den Unterzeichner zur Überprüfung der Signatur zu kontaktieren, z. B. eine Telefonnummer.

**Returns:**
String Wert

### getCustomAppearance {#getCustomAppearance--}
```
public final SignatureCustomAppearance getCustomAppearance()
```

Liest/setzt das benutzerdefinierte Erscheinungsbild.

**Returns:**
SignatureCustomAppearance-Instanz

### getCustomSign {#getCustomSign--}
```
public final CustomSign getCustomSign()
```

Der Delegat für benutzerdefiniertes Hashen und Signieren des Dokuments (Beta). {@code Der Algorithmus, mit dem Sie das Dokument im Delegaten hashieren und signieren, muss zum Typ des privaten Schlüssels des Zertifikats passen.}

**Returns:**
SignHash-Instanz

### getCustomSignHash {#getCustomSignHash--}
```
public final SignHash getCustomSignHash()
```

Der Delegat für das benutzerdefinierte Signieren des Dokument-Hashes (Beta). {@code The algorithm with which you sign the hash in the delegate must match the type of the certificate's private key.}

**Returns:**
SignHash-Instanz

### getDate {#getDate--}
```
public Date getDate()
```

Liest die Signaturzeit.

**Returns:**
Datumswert

### getDefaultSignatureLength {#getDefaultSignatureLength--}
```
public final int getDefaultSignatureLength()
```

Liest oder setzt die Standardlänge für die Signaturdaten in Bytes. Dies ist eine Schätzung der Signaturlänge in Bytes. Wird zum Signieren über {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) verwendet, wenn der Parameter {@code AvoidEstimatingSignatureLength}({@code #getAvoidEstimatingSignatureLength}/{@code #setAvoidEstimatingSignatureLength(boolean)}) gesetzt ist. Der Standardwert ist 3000.

**Returns:**
int-Wert

### getImageInternal {#getImageInternal--}
```
public com.aspose.ms.System.IO.Stream getImageInternal()
```

Liest den Bild-Stream. Nur für interne Verwendung.

**Returns:**
Stream-Objekt

### getLocation {#getLocation--}
```
public String getLocation()
```

Liest den CPU-Hostnamen oder den physischen Standort der Signatur.

**Returns:**
String Wert

### getOcspSettings {#getOcspSettings--}
```
public OcspSettings getOcspSettings()
```

Liest/setzt OCSP-Einstellungen.

**Returns:**
OcspSettings-Instanz

### getReason {#getReason--}
```
public String getReason()
```

Liest den Grund für die Signatur, z. B. (I agreed!, Pip B.).

**Returns:**
String Wert

### getSignatureAlgorithmInfo {#getSignatureAlgorithmInfo--}
```
public final com.aspose.pdf.engine.security.SignatureAlgorithmInfo getSignatureAlgorithmInfo()
```

Ruft Informationen über den in der Signatur verwendeten Signaturalgorithmus ab.

**Returns:**
Eine Instanz von { SignatureAlgorithmInfo}, die Details zum Signaturalgorithmus enthält.

### getSignatureReferences {#getSignatureReferences--}
```
public List <com.aspose.pdf.engine.security.impl.signatures.SignatureReference> getSignatureReferences()
```

hole Signaturreferenzen

**Returns:**
{@code java.util.List<SignatureReference> object}

### getTimestampSettings {#getTimestampSettings--}
```
public TimestampSettings getTimestampSettings()
```

Liest Zeitstempel-Einstellungen.

**Returns:**
TimestampSettings

### getUseLtv {#getUseLtv--}
```
public final boolean getUseLtv()
```

Liest/setzt LTV-Validierungs-Flag.

**Returns:**
boolescher Wert

### isAvoidEstimatingSignatureLength {#isAvoidEstimatingSignatureLength--}
```
public final boolean isAvoidEstimatingSignatureLength()
```

Liest und setzt eine Option, die angibt, ob die Schätzung der Signaturlänge vermieden werden soll. Vermeidet die Schätzung der Signaturlänge vor einem zu signierenden Dokument. Wird zum Signieren über {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) und über {@code ExternalSignature} verwendet. Wenn {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) eine Signatur zurückgibt, die länger ist als {@code DefaultSignatureLength}({@code #getDefaultSignatureLength}/{@code #setDefaultSignatureLength(int)}), wird {@code SignatureLengthMismatchException} ausgelöst. Der Standardwert ist {@code false}.

**Returns:**
boolescher Wert

### isShowProperties {#isShowProperties--}
```
public boolean isShowProperties()
```

Erzwingt das Anzeigen/Verbergen von Signatur-Eigenschaften. Falls ShowProperties true ist, hat das Signaturfeld ein vordefiniertes Anzeigeformat (Zeichenketten zur Darstellung): ------------------------------------------- Digital signiert von {certificate subject} Datum: {signature.Date} Grund: {signature.Reason} Ort: {signature.Location} ------------------------------------------- wobei {X} ein Platzhalter für den X‑Wert ist. Die Signatur kann auch ein Bild enthalten; in diesem Fall werden die aufgeführten Zeichenketten über das Bild gelegt. ShowProperties ist standardmäßig true.

**Returns:**
boolescher Wert

### setAuthority {#setAuthority-java.lang.String-}
Setzt den Namen der Person oder Behörde, die das Dokument signiert.

### setAvoidEstimatingSignatureLength {#setAvoidEstimatingSignatureLength-boolean-}
```
public final void setAvoidEstimatingSignatureLength(boolean value)
```

Liest und setzt eine Option, die angibt, ob die Schätzung der Signaturlänge vermieden werden soll. Vermeidet die Schätzung der Signaturlänge vor einem zu signierenden Dokument. Wird zum Signieren über {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) und über {@code ExternalSignature} verwendet. Wenn {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) eine Signatur zurückgibt, die länger ist als {@code DefaultSignatureLength}({@code #getDefaultSignatureLength}/{@code #setDefaultSignatureLength(int)}), wird {@code SignatureLengthMismatchException} ausgelöst. Der Standardwert ist {@code false}.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setContactInfo {#setContactInfo-java.lang.String-}
Setzt vom Unterzeichner bereitgestellte Informationen, um einem Empfänger zu ermöglichen, den Unterzeichner zur Überprüfung der Signatur zu kontaktieren, z. B. eine Telefonnummer.

### setCustomAppearance {#setCustomAppearance-com.aspose.pdf.SignatureCustomAppearance-}
Liest/setzt das benutzerdefinierte Erscheinungsbild.

### setCustomSign {#setCustomSign-com.aspose.pdf.CustomSign-}
Der Delegat für benutzerdefiniertes Hashen und Signieren des Dokuments (Beta). {@code Der Algorithmus, mit dem Sie das Dokument im Delegaten hashieren und signieren, muss zum Typ des privaten Schlüssels des Zertifikats passen.}

### setCustomSignHash {#setCustomSignHash-com.aspose.pdf.SignHash-}
Der Delegat für das benutzerdefinierte Signieren des Dokument-Hashes (Beta). {@code The algorithm with which you sign the hash in the delegate must match the type of the certificate's private key.}

### setDate {#setDate-java.util.Date-}
Setzt die Signaturzeit.

### setDefaultSignatureLength {#setDefaultSignatureLength-int-}
```
public final void setDefaultSignatureLength(int value)
```

Liest oder setzt die Standardlänge für die Signaturdaten in Bytes. Dies ist eine Schätzung der Signaturlänge in Bytes. Wird zum Signieren über {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) verwendet, wenn der Parameter {@code AvoidEstimatingSignatureLength}({@code #getAvoidEstimatingSignatureLength}/{@code #setAvoidEstimatingSignatureLength(boolean)}) gesetzt ist. Der Standardwert ist 3000.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert |

### setImage {#setImage-java.io.InputStream-}
Setzt den Bild-Stream.

### setImageInternal {#setImageInternal-com.aspose.ms.System.IO.Stream-}


### setLocation {#setLocation-java.lang.String-}
Setzt den CPU-Hostnamen oder den physischen Standort der Signatur.

### setOcspSettings {#setOcspSettings-com.aspose.pdf.OcspSettings-}
Liest/setzt OCSP-Einstellungen.

### setReason {#setReason-java.lang.String-}
Setzt den Grund für die Signatur, z. B. (I agreed!, Pip B.).

### setShowProperties {#setShowProperties-boolean-}
```
public void setShowProperties(boolean value)
```

Erzwingt das Anzeigen/Verbergen von Signatur-Eigenschaften. Falls ShowProperties true ist, hat das Signaturfeld ein vordefiniertes Anzeigeformat (Zeichenketten zur Darstellung): ------------------------------------------- Digital signiert von {certificate subject} Datum: {signature.Date} Grund: {signature.Reason} Ort: {signature.Location} ------------------------------------------- wobei {X} ein Platzhalter für den X‑Wert ist. Die Signatur kann auch ein Bild enthalten; in diesem Fall werden die aufgeführten Zeichenketten über das Bild gelegt. ShowProperties ist standardmäßig true.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setTimestampSettings {#setTimestampSettings-com.aspose.pdf.TimestampSettings-}
Setzt Zeitstempel-Einstellungen.

### setUseLtv {#setUseLtv-boolean-}
```
public final void setUseLtv(boolean value)
```

Liest/setzt LTV-Validierungs-Flag.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### verify {#verify--}
```
public boolean verify()
```

Überprüft das Dokument hinsichtlich dieser Signatur und gibt true zurück, wenn das Dokument gültig ist, andernfalls false.

**Returns:**
true, wenn das Dokument gültig ist.

### verify {#verify-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-}
Überprüft das Dokument hinsichtlich dieser Signatur und gibt true zurück, wenn das Dokument gültig ist, andernfalls false.

**Returns:**
true, wenn das Dokument gültig ist.

### verify {#verify-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-}
Überprüft das Dokument hinsichtlich dieser Signatur und gibt true zurück, wenn das Dokument gültig ist, andernfalls false.

**Returns:**
true, wenn das Dokument gültig ist.
