---
title: "Signature"
linktitle: "Signature"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Una classe astratta che rappresenta l'oggetto firma nel documento pdf. Le firme sono campi con valori di oggetti firma, quest'ultimo contiene i dati che vengono usati per verificare il."
type: docs
weight: 4490
url: /it/java/com.aspose.pdf/signature/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Signature

```
public abstract class Signature extends Object
```

Una classe astratta che rappresenta l'oggetto firma nel documento PDF. Le firme sono campi con valori di oggetti firma, quest'ultimi contengono dati utilizzati per verificare la validità del documento.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Signature](#Signature--) | Inizializza una nuova istanza della classe {@code Signature}. |
| [Signature](#Signature-java.io.InputStream-java.lang.String-) | Inizializza una nuova istanza della classe {@code Signature}. |
| [Signature](#Signature-java.lang.String-java.lang.String-) | Inizializza una nuova istanza della classe {@code Signature}. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [close](#close--) | Distruttore che chiude i flussi temporanei (se necessario). |
| [getAuthority](#getAuthority--) | Il nome della persona o dell'autorità che firma il documento. |
| [getByteRange](#getByteRange--) | Ottieni un array di coppie di interi (offset iniziale in byte, lunghezza in byte) che descrivono l'intervallo di byte esatto per il calcolo del digest. |
| [getContactInfo](#getContactInfo--) | Ottieni le informazioni fornite dal firmatario per consentire a un destinatario di contattare il firmatario per verificare la firma, ad es. un numero di telefono. |
| [getCustomAppearance](#getCustomAppearance--) | Ottiene/imposta l'aspetto personalizzato. |
| [getCustomSign](#getCustomSign--) | Il delegato per l'hash personalizzato e la firma del documento (Beta). {@code The algorithm with which you hash and sign the document in the delegate must match the type of the certificate's private key.} |
| [getCustomSignHash](#getCustomSignHash--) | Il delegato per la firma personalizzata dell'hash del documento (Beta). {@code The algorithm with which you sign the hash in the delegate must match the type of the certificate's private key.} |
| [getDate](#getDate--) | Ottiene l'ora della firma. |
| [getDefaultSignatureLength](#getDefaultSignatureLength--) | Ottiene o imposta la lunghezza predefinita per i dati della firma in byte. Questa è una stima della lunghezza della firma in byte. Utilizzata per la firma tramite {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) se il parametro {@code AvoidEstimatingSignatureLength}({@code #getAvoidEstimatingSignatureLength}/{@code #setAvoidEstimatingSignatureLength(boolean)}) è impostato. Il valore predefinito è 3000. |
| [getImageInternal](#getImageInternal--) | Ottiene lo stream dell'immagine. Solo per uso interno |
| [getLocation](#getLocation--) | Ottiene il nome host della CPU o la posizione fisica della firma. |
| [getOcspSettings](#getOcspSettings--) | Ottiene/imposta le impostazioni OCSP. |
| [getReason](#getReason--) | Ottiene il motivo della firma, ad esempio (Ho accettato!, Pip B.). |
| [getSignatureAlgorithmInfo](#getSignatureAlgorithmInfo--) | Recupera informazioni sull'algoritmo di firma utilizzato nella firma. |
| [getSignatureReferences](#getSignatureReferences--) | Ottieni riferimenti della firma |
| [getTimestampSettings](#getTimestampSettings--) | Ottiene le impostazioni del timestamp. |
| [getUseLtv](#getUseLtv--) | Ottiene/imposta il flag di convalida LTV. |
| [isAvoidEstimatingSignatureLength](#isAvoidEstimatingSignatureLength--) | Ottiene e imposta un'opzione che indica se evitare di stimare la lunghezza di una firma. Evita di stimare la lunghezza della firma prima di firmare un documento. Utilizzata per la firma tramite {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) e tramite {@code ExternalSignature}. Se {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) restituisce una firma più lunga di {@code DefaultSignatureLength}({@code #getDefaultSignatureLength}/{@code #setDefaultSignatureLength(int)}), verrà sollevata {@code SignatureLengthMismatchException}. Il valore predefinito è {@code false}. |
| [isShowProperties](#isShowProperties--) | Forza la visualizzazione/nascondi le proprietà della firma. Nel caso in cui ShowProperties sia true, il campo firma ha un formato di aspetto predefinito (stringhe da rappresentare): ------------------------------------------- Firmato digitalmente da {certificate subject} Data: {signature.Date} Motivo: {signature.Reason} Posizione: {signature.Location} ------------------------------------------- dove {X} è un segnaposto per il valore X. Inoltre la firma può avere un'immagine; in questo caso le stringhe elencate sono posizionate sull'immagine. ShowProperties è true per impostazione predefinita. |
| [setAuthority](#setAuthority-java.lang.String-) | Imposta il nome della persona o dell'autorità che firma il documento. |
| [setAvoidEstimatingSignatureLength](#setAvoidEstimatingSignatureLength-boolean-) | Ottiene e imposta un'opzione che indica se evitare di stimare la lunghezza di una firma. Evita di stimare la lunghezza della firma prima di firmare un documento. Utilizzata per la firma tramite {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) e tramite {@code ExternalSignature}. Se {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) restituisce una firma più lunga di {@code DefaultSignatureLength}({@code #getDefaultSignatureLength}/{@code #setDefaultSignatureLength(int)}), verrà sollevata {@code SignatureLengthMismatchException}. Il valore predefinito è {@code false}. |
| [setContactInfo](#setContactInfo-java.lang.String-) | Imposta le informazioni fornite dal firmatario per consentire a un destinatario di contattare il firmatario per verificare la firma, ad es. un numero di telefono. |
| [setCustomAppearance](#setCustomAppearance-com.aspose.pdf.SignatureCustomAppearance-) | Ottiene/imposta l'aspetto personalizzato. |
| [setCustomSign](#setCustomSign-com.aspose.pdf.CustomSign-) | Il delegato per l'hash personalizzato e la firma del documento (Beta). {@code The algorithm with which you hash and sign the document in the delegate must match the type of the certificate's private key.} |
| [setCustomSignHash](#setCustomSignHash-com.aspose.pdf.SignHash-) | Il delegato per la firma personalizzata dell'hash del documento (Beta). {@code The algorithm with which you sign the hash in the delegate must match the type of the certificate's private key.} |
| [setDate](#setDate-java.util.Date-) | Imposta l'ora della firma. |
| [setDefaultSignatureLength](#setDefaultSignatureLength-int-) | Ottiene o imposta la lunghezza predefinita per i dati della firma in byte. Questa è una stima della lunghezza della firma in byte. Utilizzata per la firma tramite {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) se il parametro {@code AvoidEstimatingSignatureLength}({@code #getAvoidEstimatingSignatureLength}/{@code #setAvoidEstimatingSignatureLength(boolean)}) è impostato. Il valore predefinito è 3000. |
| [setImage](#setImage-java.io.InputStream-) | Imposta lo stream dell'immagine. |
| [setImageInternal](#setImageInternal-com.aspose.ms.System.IO.Stream-) |  |
| [setLocation](#setLocation-java.lang.String-) | Imposta il nome host della CPU o la posizione fisica della firma. |
| [setOcspSettings](#setOcspSettings-com.aspose.pdf.OcspSettings-) | Ottiene/imposta le impostazioni OCSP. |
| [setReason](#setReason-java.lang.String-) | Imposta il motivo della firma, ad esempio (I agreed!, Pip B.). |
| [setShowProperties](#setShowProperties-boolean-) | Forza la visualizzazione/nascondi le proprietà della firma. Nel caso in cui ShowProperties sia true, il campo firma ha un formato di aspetto predefinito (stringhe da rappresentare): ------------------------------------------- Firmato digitalmente da {certificate subject} Data: {signature.Date} Motivo: {signature.Reason} Posizione: {signature.Location} ------------------------------------------- dove {X} è un segnaposto per il valore X. Inoltre la firma può avere un'immagine; in questo caso le stringhe elencate sono posizionate sull'immagine. ShowProperties è true per impostazione predefinita. |
| [setTimestampSettings](#setTimestampSettings-com.aspose.pdf.TimestampSettings-) | Imposta le impostazioni del timestamp. |
| [setUseLtv](#setUseLtv-boolean-) | Ottiene/imposta il flag di convalida LTV. |
| [verify](#verify--) | Verifica il documento rispetto a questa firma e restituisce true se il documento è valido, altrimenti false. |
| [verify](#verify-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-) | Verifica il documento rispetto a questa firma e restituisce true se il documento è valido, altrimenti false. |
| [verify](#verify-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-) | Verifica il documento rispetto a questa firma e restituisce true se il documento è valido, altrimenti false. |

### Signature {#Signature--}
```
public Signature()
```

Inizializza una nuova istanza della classe {@code Signature}.

### Signature {#Signature-java.io.InputStream-java.lang.String-}
Inizializza una nuova istanza della classe {@code Signature}.

### Signature {#Signature-java.lang.String-java.lang.String-}
Inizializza una nuova istanza della classe {@code Signature}.

### close {#close--}
```
public void close()
```

Distruttore che chiude i flussi temporanei (se necessario).

### getAuthority {#getAuthority--}
```
public final String getAuthority()
```

Il nome della persona o dell'autorità che firma il documento.

**Returns:**
valore String

### getByteRange {#getByteRange--}
```
public int[] getByteRange()
```

Ottieni un array di coppie di interi (offset iniziale in byte, lunghezza in byte) che descrivono l'intervallo di byte esatto per il calcolo del digest.

**Returns:**
array di valore int

### getContactInfo {#getContactInfo--}
```
public String getContactInfo()
```

Ottieni le informazioni fornite dal firmatario per consentire a un destinatario di contattare il firmatario per verificare la firma, ad es. un numero di telefono.

**Returns:**
valore String

### getCustomAppearance {#getCustomAppearance--}
```
public final SignatureCustomAppearance getCustomAppearance()
```

Ottiene/imposta l'aspetto personalizzato.

**Returns:**
istanza di SignatureCustomAppearance

### getCustomSign {#getCustomSign--}
```
public final CustomSign getCustomSign()
```

Il delegato per l'hash personalizzato e la firma del documento (Beta). {@code The algorithm with which you hash and sign the document in the delegate must match the type of the certificate's private key.}

**Returns:**
istanza di SignHash

### getCustomSignHash {#getCustomSignHash--}
```
public final SignHash getCustomSignHash()
```

Il delegato per la firma personalizzata dell'hash del documento (Beta). {@code The algorithm with which you sign the hash in the delegate must match the type of the certificate's private key.}

**Returns:**
istanza di SignHash

### getDate {#getDate--}
```
public Date getDate()
```

Ottiene l'ora della firma.

**Returns:**
valore Date

### getDefaultSignatureLength {#getDefaultSignatureLength--}
```
public final int getDefaultSignatureLength()
```

Ottiene o imposta la lunghezza predefinita per i dati della firma in byte. Questa è una stima della lunghezza della firma in byte. Utilizzata per la firma tramite {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) se il parametro {@code AvoidEstimatingSignatureLength}({@code #getAvoidEstimatingSignatureLength}/{@code #setAvoidEstimatingSignatureLength(boolean)}) è impostato. Il valore predefinito è 3000.

**Returns:**
valore int

### getImageInternal {#getImageInternal--}
```
public com.aspose.ms.System.IO.Stream getImageInternal()
```

Ottiene lo stream dell'immagine. Solo per uso interno

**Returns:**
oggetto Stream

### getLocation {#getLocation--}
```
public String getLocation()
```

Ottiene il nome host della CPU o la posizione fisica della firma.

**Returns:**
valore String

### getOcspSettings {#getOcspSettings--}
```
public OcspSettings getOcspSettings()
```

Ottiene/imposta le impostazioni OCSP.

**Returns:**
istanza di OcspSettings

### getReason {#getReason--}
```
public String getReason()
```

Ottiene il motivo della firma, ad esempio (Ho accettato!, Pip B.).

**Returns:**
valore String

### getSignatureAlgorithmInfo {#getSignatureAlgorithmInfo--}
```
public final com.aspose.pdf.engine.security.SignatureAlgorithmInfo getSignatureAlgorithmInfo()
```

Recupera informazioni sull'algoritmo di firma utilizzato nella firma.

**Returns:**
Un'istanza di { SignatureAlgorithmInfo} che contiene i dettagli sull'algoritmo di firma.

### getSignatureReferences {#getSignatureReferences--}
```
public List <com.aspose.pdf.engine.security.impl.signatures.SignatureReference> getSignatureReferences()
```

Ottieni riferimenti della firma

**Returns:**
{@code java.util.List<SignatureReference> object}

### getTimestampSettings {#getTimestampSettings--}
```
public TimestampSettings getTimestampSettings()
```

Ottiene le impostazioni del timestamp.

**Returns:**
TimestampSettings

### getUseLtv {#getUseLtv--}
```
public final boolean getUseLtv()
```

Ottiene/imposta il flag di convalida LTV.

**Returns:**
valore booleano

### isAvoidEstimatingSignatureLength {#isAvoidEstimatingSignatureLength--}
```
public final boolean isAvoidEstimatingSignatureLength()
```

Ottiene e imposta un'opzione che indica se evitare di stimare la lunghezza di una firma. Evita di stimare la lunghezza della firma prima di firmare un documento. Utilizzata per la firma tramite {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) e tramite {@code ExternalSignature}. Se {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) restituisce una firma più lunga di {@code DefaultSignatureLength}({@code #getDefaultSignatureLength}/{@code #setDefaultSignatureLength(int)}), verrà sollevata {@code SignatureLengthMismatchException}. Il valore predefinito è {@code false}.

**Returns:**
valore booleano

### isShowProperties {#isShowProperties--}
```
public boolean isShowProperties()
```

Forza la visualizzazione/nascondi le proprietà della firma. Nel caso in cui ShowProperties sia true, il campo firma ha un formato di aspetto predefinito (stringhe da rappresentare): ------------------------------------------- Firmato digitalmente da {certificate subject} Data: {signature.Date} Motivo: {signature.Reason} Posizione: {signature.Location} ------------------------------------------- dove {X} è un segnaposto per il valore X. Inoltre la firma può avere un'immagine; in questo caso le stringhe elencate sono posizionate sull'immagine. ShowProperties è true per impostazione predefinita.

**Returns:**
valore booleano

### setAuthority {#setAuthority-java.lang.String-}
Imposta il nome della persona o dell'autorità che firma il documento.

### setAvoidEstimatingSignatureLength {#setAvoidEstimatingSignatureLength-boolean-}
```
public final void setAvoidEstimatingSignatureLength(boolean value)
```

Ottiene e imposta un'opzione che indica se evitare di stimare la lunghezza di una firma. Evita di stimare la lunghezza della firma prima di firmare un documento. Utilizzata per la firma tramite {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) e tramite {@code ExternalSignature}. Se {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) restituisce una firma più lunga di {@code DefaultSignatureLength}({@code #getDefaultSignatureLength}/{@code #setDefaultSignatureLength(int)}), verrà sollevata {@code SignatureLengthMismatchException}. Il valore predefinito è {@code false}.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setContactInfo {#setContactInfo-java.lang.String-}
Imposta le informazioni fornite dal firmatario per consentire a un destinatario di contattare il firmatario per verificare la firma, ad es. un numero di telefono.

### setCustomAppearance {#setCustomAppearance-com.aspose.pdf.SignatureCustomAppearance-}
Ottiene/imposta l'aspetto personalizzato.

### setCustomSign {#setCustomSign-com.aspose.pdf.CustomSign-}
Il delegato per l'hash personalizzato e la firma del documento (Beta). {@code The algorithm with which you hash and sign the document in the delegate must match the type of the certificate's private key.}

### setCustomSignHash {#setCustomSignHash-com.aspose.pdf.SignHash-}
Il delegato per la firma personalizzata dell'hash del documento (Beta). {@code The algorithm with which you sign the hash in the delegate must match the type of the certificate's private key.}

### setDate {#setDate-java.util.Date-}
Imposta l'ora della firma.

### setDefaultSignatureLength {#setDefaultSignatureLength-int-}
```
public final void setDefaultSignatureLength(int value)
```

Ottiene o imposta la lunghezza predefinita per i dati della firma in byte. Questa è una stima della lunghezza della firma in byte. Utilizzata per la firma tramite {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) se il parametro {@code AvoidEstimatingSignatureLength}({@code #getAvoidEstimatingSignatureLength}/{@code #setAvoidEstimatingSignatureLength(boolean)}) è impostato. Il valore predefinito è 3000.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int |

### setImage {#setImage-java.io.InputStream-}
Imposta lo stream dell'immagine.

### setImageInternal {#setImageInternal-com.aspose.ms.System.IO.Stream-}


### setLocation {#setLocation-java.lang.String-}
Imposta il nome host della CPU o la posizione fisica della firma.

### setOcspSettings {#setOcspSettings-com.aspose.pdf.OcspSettings-}
Ottiene/imposta le impostazioni OCSP.

### setReason {#setReason-java.lang.String-}
Imposta il motivo della firma, ad esempio (I agreed!, Pip B.).

### setShowProperties {#setShowProperties-boolean-}
```
public void setShowProperties(boolean value)
```

Forza la visualizzazione/nascondi le proprietà della firma. Nel caso in cui ShowProperties sia true, il campo firma ha un formato di aspetto predefinito (stringhe da rappresentare): ------------------------------------------- Firmato digitalmente da {certificate subject} Data: {signature.Date} Motivo: {signature.Reason} Posizione: {signature.Location} ------------------------------------------- dove {X} è un segnaposto per il valore X. Inoltre la firma può avere un'immagine; in questo caso le stringhe elencate sono posizionate sull'immagine. ShowProperties è true per impostazione predefinita.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setTimestampSettings {#setTimestampSettings-com.aspose.pdf.TimestampSettings-}
Imposta le impostazioni del timestamp.

### setUseLtv {#setUseLtv-boolean-}
```
public final void setUseLtv(boolean value)
```

Ottiene/imposta il flag di convalida LTV.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### verify {#verify--}
```
public boolean verify()
```

Verifica il documento rispetto a questa firma e restituisce true se il documento è valido, altrimenti false.

**Returns:**
true se il documento è valido.

### verify {#verify-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-}
Verifica il documento rispetto a questa firma e restituisce true se il documento è valido, altrimenti false.

**Returns:**
true se il documento è valido.

### verify {#verify-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-}
Verifica il documento rispetto a questa firma e restituisce true se il documento è valido, altrimenti false.

**Returns:**
true se il documento è valido.
