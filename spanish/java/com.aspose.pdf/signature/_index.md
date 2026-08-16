---
title: "Signature"
linktitle: "Signature"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Una clase abstracta que representa un objeto de firma en el documento pdf. Las firmas son campos con valores de objetos de firma, los últimos contienen datos que se utilizan para verificar la."
type: docs
weight: 4490
url: /es/java/com.aspose.pdf/signature/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Signature

```
public abstract class Signature extends Object
```

Una clase abstracta que representa un objeto de firma en el documento PDF. Las firmas son campos con valores de objetos de firma, los cuales contienen datos que se utilizan para verificar la validez del documento.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [Signature](#Signature--) | Inicializa una nueva instancia de la clase {@code Signature}. |
| [Signature](#Signature-java.io.InputStream-java.lang.String-) | Inicializa una nueva instancia de la clase {@code Signature}. |
| [Signature](#Signature-java.lang.String-java.lang.String-) | Inicializa una nueva instancia de la clase {@code Signature}. |

## Métodos

| Método | Descripción |
| --- | --- |
| [close](#close--) | Destructor que cierra los flujos temporales (si es necesario). |
| [getAuthority](#getAuthority--) | El nombre de la persona o autoridad que firma el documento. |
| [getByteRange](#getByteRange--) | Obtiene una matriz de pares de enteros (desplazamiento inicial en bytes, longitud en bytes) que describen el rango exacto de bytes para el cálculo del resumen. |
| [getContactInfo](#getContactInfo--) | Obtiene la información proporcionada por el firmante para permitir que un destinatario contacte al firmante y verifique la firma, p. ej., un número de teléfono. |
| [getCustomAppearance](#getCustomAppearance--) | Obtiene/establece la apariencia personalizada. |
| [getCustomSign](#getCustomSign--) | El delegado para hash personalizado y firma del documento (Beta). {@code The algorithm with which you hash and sign the document in the delegate must match the type of the certificate's private key.} |
| [getCustomSignHash](#getCustomSignHash--) | El delegado para firmar de forma personalizada el hash del documento (Beta). {@code The algorithm with which you sign the hash in the delegate must match the type of the certificate's private key.} |
| [getDate](#getDate--) | Obtiene la hora de la firma. |
| [getDefaultSignatureLength](#getDefaultSignatureLength--) | Obtiene o establece la longitud predeterminada para los datos de la firma en bytes. Esta es una estimación de la longitud de la firma en bytes. Se utiliza para firmar a través de {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) si el parámetro {@code AvoidEstimatingSignatureLength}({@code #getAvoidEstimatingSignatureLength}/{@code #setAvoidEstimatingSignatureLength(boolean)}) está configurado. El valor predeterminado es 3000. |
| [getImageInternal](#getImageInternal--) | Obtiene el flujo de imagen. Solo para uso interno. |
| [getLocation](#getLocation--) | Obtiene el nombre de host de la CPU o la ubicación física de la firma. |
| [getOcspSettings](#getOcspSettings--) | Obtiene/establece la configuración de OCSP. |
| [getReason](#getReason--) | Obtiene la razón de la firma, como (¡Estoy de acuerdo!, Pip B.). |
| [getSignatureAlgorithmInfo](#getSignatureAlgorithmInfo--) | Recupera información sobre el algoritmo de firma utilizado en la firma. |
| [getSignatureReferences](#getSignatureReferences--) | obtener Referencias de Firma |
| [getTimestampSettings](#getTimestampSettings--) | Obtiene la configuración de marca de tiempo. |
| [getUseLtv](#getUseLtv--) | Obtiene/establece la bandera de validación LTV. |
| [isAvoidEstimatingSignatureLength](#isAvoidEstimatingSignatureLength--) | Obtiene y establece una opción que indica si se debe evitar estimar la longitud de una firma. Evita estimar la longitud de la firma antes de firmar un documento. Se utiliza para firmar a través de {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) y mediante {@code ExternalSignature}. Si {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) devuelve una firma más larga que {@code DefaultSignatureLength}({@code #getDefaultSignatureLength}/{@code #setDefaultSignatureLength(int)}), se lanzará {@code SignatureLengthMismatchException}. El valor predeterminado es {@code false}. |
| [isShowProperties](#isShowProperties--) | Forzar a mostrar/ocultar las propiedades de la firma. En caso de que ShowProperties sea verdadero, el campo de firma tiene un formato de apariencia predefinido (cadenas para representar): ------------------------------------------- Firmado digitalmente por {certificate subject} Fecha: {signature.Date} Razón: {signature.Reason} Ubicación: {signature.Location} ------------------------------------------- donde {X} es un marcador de posición para el valor X. Además, la firma puede tener una imagen; en este caso, las cadenas listadas se colocan sobre la imagen. ShowProperties es verdadero por defecto. |
| [setAuthority](#setAuthority-java.lang.String-) | Establece el nombre de la persona o autoridad que firma el documento. |
| [setAvoidEstimatingSignatureLength](#setAvoidEstimatingSignatureLength-boolean-) | Obtiene y establece una opción que indica si se debe evitar estimar la longitud de una firma. Evita estimar la longitud de la firma antes de firmar un documento. Se utiliza para firmar a través de {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) y mediante {@code ExternalSignature}. Si {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) devuelve una firma más larga que {@code DefaultSignatureLength}({@code #getDefaultSignatureLength}/{@code #setDefaultSignatureLength(int)}), se lanzará {@code SignatureLengthMismatchException}. El valor predeterminado es {@code false}. |
| [setContactInfo](#setContactInfo-java.lang.String-) | Establece la información proporcionada por el firmante para permitir que un destinatario contacte al firmante y verifique la firma, p. ej., un número de teléfono. |
| [setCustomAppearance](#setCustomAppearance-com.aspose.pdf.SignatureCustomAppearance-) | Obtiene/establece la apariencia personalizada. |
| [setCustomSign](#setCustomSign-com.aspose.pdf.CustomSign-) | El delegado para hash personalizado y firma del documento (Beta). {@code The algorithm with which you hash and sign the document in the delegate must match the type of the certificate's private key.} |
| [setCustomSignHash](#setCustomSignHash-com.aspose.pdf.SignHash-) | El delegado para firmar de forma personalizada el hash del documento (Beta). {@code The algorithm with which you sign the hash in the delegate must match the type of the certificate's private key.} |
| [setDate](#setDate-java.util.Date-) | Establece la hora de la firma. |
| [setDefaultSignatureLength](#setDefaultSignatureLength-int-) | Obtiene o establece la longitud predeterminada para los datos de la firma en bytes. Esta es una estimación de la longitud de la firma en bytes. Se utiliza para firmar a través de {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) si el parámetro {@code AvoidEstimatingSignatureLength}({@code #getAvoidEstimatingSignatureLength}/{@code #setAvoidEstimatingSignatureLength(boolean)}) está configurado. El valor predeterminado es 3000. |
| [setImage](#setImage-java.io.InputStream-) | Establece el flujo de imagen. |
| [setImageInternal](#setImageInternal-com.aspose.ms.System.IO.Stream-) |  |
| [setLocation](#setLocation-java.lang.String-) | Establece el nombre de host de la CPU o la ubicación física de la firma. |
| [setOcspSettings](#setOcspSettings-com.aspose.pdf.OcspSettings-) | Obtiene/establece la configuración de OCSP. |
| [setReason](#setReason-java.lang.String-) | Establece la razón de la firma, como (¡Estoy de acuerdo!, Pip B.). |
| [setShowProperties](#setShowProperties-boolean-) | Forzar a mostrar/ocultar las propiedades de la firma. En caso de que ShowProperties sea verdadero, el campo de firma tiene un formato de apariencia predefinido (cadenas para representar): ------------------------------------------- Firmado digitalmente por {certificate subject} Fecha: {signature.Date} Razón: {signature.Reason} Ubicación: {signature.Location} ------------------------------------------- donde {X} es un marcador de posición para el valor X. Además, la firma puede tener una imagen; en este caso, las cadenas listadas se colocan sobre la imagen. ShowProperties es verdadero por defecto. |
| [setTimestampSettings](#setTimestampSettings-com.aspose.pdf.TimestampSettings-) | Establece la configuración de marca de tiempo. |
| [setUseLtv](#setUseLtv-boolean-) | Obtiene/establece la bandera de validación LTV. |
| [verify](#verify--) | Verifica el documento respecto a esta firma y devuelve true si el documento es válido o false en caso contrario. |
| [verify](#verify-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-) | Verifica el documento respecto a esta firma y devuelve true si el documento es válido o false en caso contrario. |
| [verify](#verify-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-) | Verifica el documento respecto a esta firma y devuelve true si el documento es válido o false en caso contrario. |

### Signature {#Signature--}
```
public Signature()
```

Inicializa una nueva instancia de la clase {@code Signature}.

### Signature {#Signature-java.io.InputStream-java.lang.String-}
Inicializa una nueva instancia de la clase {@code Signature}.

### Signature {#Signature-java.lang.String-java.lang.String-}
Inicializa una nueva instancia de la clase {@code Signature}.

### close {#close--}
```
public void close()
```

Destructor que cierra los flujos temporales (si es necesario).

### getAuthority {#getAuthority--}
```
public final String getAuthority()
```

El nombre de la persona o autoridad que firma el documento.

**Returns:**
valor String

### getByteRange {#getByteRange--}
```
public int[] getByteRange()
```

Obtiene una matriz de pares de enteros (desplazamiento inicial en bytes, longitud en bytes) que describen el rango exacto de bytes para el cálculo del resumen.

**Returns:**
matriz de valores int

### getContactInfo {#getContactInfo--}
```
public String getContactInfo()
```

Obtiene la información proporcionada por el firmante para permitir que un destinatario contacte al firmante y verifique la firma, p. ej., un número de teléfono.

**Returns:**
valor String

### getCustomAppearance {#getCustomAppearance--}
```
public final SignatureCustomAppearance getCustomAppearance()
```

Obtiene/establece la apariencia personalizada.

**Returns:**
instancia de SignatureCustomAppearance

### getCustomSign {#getCustomSign--}
```
public final CustomSign getCustomSign()
```

El delegado para hash personalizado y firma del documento (Beta). {@code The algorithm with which you hash and sign the document in the delegate must match the type of the certificate's private key.}

**Returns:**
instancia de SignHash

### getCustomSignHash {#getCustomSignHash--}
```
public final SignHash getCustomSignHash()
```

El delegado para firmar de forma personalizada el hash del documento (Beta). {@code The algorithm with which you sign the hash in the delegate must match the type of the certificate's private key.}

**Returns:**
instancia de SignHash

### getDate {#getDate--}
```
public Date getDate()
```

Obtiene la hora de la firma.

**Returns:**
valor de Date

### getDefaultSignatureLength {#getDefaultSignatureLength--}
```
public final int getDefaultSignatureLength()
```

Obtiene o establece la longitud predeterminada para los datos de la firma en bytes. Esta es una estimación de la longitud de la firma en bytes. Se utiliza para firmar a través de {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) si el parámetro {@code AvoidEstimatingSignatureLength}({@code #getAvoidEstimatingSignatureLength}/{@code #setAvoidEstimatingSignatureLength(boolean)}) está configurado. El valor predeterminado es 3000.

**Returns:**
valor int

### getImageInternal {#getImageInternal--}
```
public com.aspose.ms.System.IO.Stream getImageInternal()
```

Obtiene el flujo de imagen. Solo para uso interno.

**Returns:**
objeto Stream

### getLocation {#getLocation--}
```
public String getLocation()
```

Obtiene el nombre de host de la CPU o la ubicación física de la firma.

**Returns:**
valor String

### getOcspSettings {#getOcspSettings--}
```
public OcspSettings getOcspSettings()
```

Obtiene/establece la configuración de OCSP.

**Returns:**
instancia de OcspSettings

### getReason {#getReason--}
```
public String getReason()
```

Obtiene la razón de la firma, como (¡Estoy de acuerdo!, Pip B.).

**Returns:**
valor String

### getSignatureAlgorithmInfo {#getSignatureAlgorithmInfo--}
```
public final com.aspose.pdf.engine.security.SignatureAlgorithmInfo getSignatureAlgorithmInfo()
```

Recupera información sobre el algoritmo de firma utilizado en la firma.

**Returns:**
Una instancia de { SignatureAlgorithmInfo} que contiene detalles sobre el algoritmo de firma.

### getSignatureReferences {#getSignatureReferences--}
```
public List <com.aspose.pdf.engine.security.impl.signatures.SignatureReference> getSignatureReferences()
```

obtener Referencias de Firma

**Returns:**
{@code java.util.List<SignatureReference> object}

### getTimestampSettings {#getTimestampSettings--}
```
public TimestampSettings getTimestampSettings()
```

Obtiene la configuración de marca de tiempo.

**Returns:**
TimestampSettings

### getUseLtv {#getUseLtv--}
```
public final boolean getUseLtv()
```

Obtiene/establece la bandera de validación LTV.

**Returns:**
valor booleano

### isAvoidEstimatingSignatureLength {#isAvoidEstimatingSignatureLength--}
```
public final boolean isAvoidEstimatingSignatureLength()
```

Obtiene y establece una opción que indica si se debe evitar estimar la longitud de una firma. Evita estimar la longitud de la firma antes de firmar un documento. Se utiliza para firmar a través de {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) y mediante {@code ExternalSignature}. Si {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) devuelve una firma más larga que {@code DefaultSignatureLength}({@code #getDefaultSignatureLength}/{@code #setDefaultSignatureLength(int)}), se lanzará {@code SignatureLengthMismatchException}. El valor predeterminado es {@code false}.

**Returns:**
valor booleano

### isShowProperties {#isShowProperties--}
```
public boolean isShowProperties()
```

Forzar a mostrar/ocultar las propiedades de la firma. En caso de que ShowProperties sea verdadero, el campo de firma tiene un formato de apariencia predefinido (cadenas para representar): ------------------------------------------- Firmado digitalmente por {certificate subject} Fecha: {signature.Date} Razón: {signature.Reason} Ubicación: {signature.Location} ------------------------------------------- donde {X} es un marcador de posición para el valor X. Además, la firma puede tener una imagen; en este caso, las cadenas listadas se colocan sobre la imagen. ShowProperties es verdadero por defecto.

**Returns:**
valor booleano

### setAuthority {#setAuthority-java.lang.String-}
Establece el nombre de la persona o autoridad que firma el documento.

### setAvoidEstimatingSignatureLength {#setAvoidEstimatingSignatureLength-boolean-}
```
public final void setAvoidEstimatingSignatureLength(boolean value)
```

Obtiene y establece una opción que indica si se debe evitar estimar la longitud de una firma. Evita estimar la longitud de la firma antes de firmar un documento. Se utiliza para firmar a través de {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) y mediante {@code ExternalSignature}. Si {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) devuelve una firma más larga que {@code DefaultSignatureLength}({@code #getDefaultSignatureLength}/{@code #setDefaultSignatureLength(int)}), se lanzará {@code SignatureLengthMismatchException}. El valor predeterminado es {@code false}.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setContactInfo {#setContactInfo-java.lang.String-}
Establece la información proporcionada por el firmante para permitir que un destinatario contacte al firmante y verifique la firma, p. ej., un número de teléfono.

### setCustomAppearance {#setCustomAppearance-com.aspose.pdf.SignatureCustomAppearance-}
Obtiene/establece la apariencia personalizada.

### setCustomSign {#setCustomSign-com.aspose.pdf.CustomSign-}
El delegado para hash personalizado y firma del documento (Beta). {@code The algorithm with which you hash and sign the document in the delegate must match the type of the certificate's private key.}

### setCustomSignHash {#setCustomSignHash-com.aspose.pdf.SignHash-}
El delegado para firmar de forma personalizada el hash del documento (Beta). {@code The algorithm with which you sign the hash in the delegate must match the type of the certificate's private key.}

### setDate {#setDate-java.util.Date-}
Establece la hora de la firma.

### setDefaultSignatureLength {#setDefaultSignatureLength-int-}
```
public final void setDefaultSignatureLength(int value)
```

Obtiene o establece la longitud predeterminada para los datos de la firma en bytes. Esta es una estimación de la longitud de la firma en bytes. Se utiliza para firmar a través de {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) si el parámetro {@code AvoidEstimatingSignatureLength}({@code #getAvoidEstimatingSignatureLength}/{@code #setAvoidEstimatingSignatureLength(boolean)}) está configurado. El valor predeterminado es 3000.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int |

### setImage {#setImage-java.io.InputStream-}
Establece el flujo de imagen.

### setImageInternal {#setImageInternal-com.aspose.ms.System.IO.Stream-}


### setLocation {#setLocation-java.lang.String-}
Establece el nombre de host de la CPU o la ubicación física de la firma.

### setOcspSettings {#setOcspSettings-com.aspose.pdf.OcspSettings-}
Obtiene/establece la configuración de OCSP.

### setReason {#setReason-java.lang.String-}
Establece la razón de la firma, como (¡Estoy de acuerdo!, Pip B.).

### setShowProperties {#setShowProperties-boolean-}
```
public void setShowProperties(boolean value)
```

Forzar a mostrar/ocultar las propiedades de la firma. En caso de que ShowProperties sea verdadero, el campo de firma tiene un formato de apariencia predefinido (cadenas para representar): ------------------------------------------- Firmado digitalmente por {certificate subject} Fecha: {signature.Date} Razón: {signature.Reason} Ubicación: {signature.Location} ------------------------------------------- donde {X} es un marcador de posición para el valor X. Además, la firma puede tener una imagen; en este caso, las cadenas listadas se colocan sobre la imagen. ShowProperties es verdadero por defecto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setTimestampSettings {#setTimestampSettings-com.aspose.pdf.TimestampSettings-}
Establece la configuración de marca de tiempo.

### setUseLtv {#setUseLtv-boolean-}
```
public final void setUseLtv(boolean value)
```

Obtiene/establece la bandera de validación LTV.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### verify {#verify--}
```
public boolean verify()
```

Verifica el documento respecto a esta firma y devuelve true si el documento es válido o false en caso contrario.

**Returns:**
true si el documento es válido.

### verify {#verify-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-}
Verifica el documento respecto a esta firma y devuelve true si el documento es válido o false en caso contrario.

**Returns:**
true si el documento es válido.

### verify {#verify-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-}
Verifica el documento respecto a esta firma y devuelve true si el documento es válido o false en caso contrario.

**Returns:**
true si el documento es válido.
