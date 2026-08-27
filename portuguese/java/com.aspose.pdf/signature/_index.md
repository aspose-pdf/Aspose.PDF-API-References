---
title: "Signature"
linktitle: "Signature"
second_title: "Referência da API Aspose.PDF para Java"
description: "Uma classe abstrata que representa o objeto de assinatura no documento pdf. Assinaturas são campos com valores de objetos de assinatura, os últimos contêm dados que são usados para verificar o."
type: docs
weight: 4490
url: /pt/java/com.aspose.pdf/signature/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Signature

```
public abstract class Signature extends Object
```

Uma classe abstrata que representa um objeto de assinatura no documento PDF. Assinaturas são campos com valores de objetos de assinatura, que contêm dados usados para verificar a validade do documento.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [Signature](#Signature--) | Inicializa nova instância da classe {@code Signature}. |
| [Signature](#Signature-java.io.InputStream-java.lang.String-) | Inicializa nova instância da classe {@code Signature}. |
| [Signature](#Signature-java.lang.String-java.lang.String-) | Inicializa nova instância da classe {@code Signature}. |

## Métodos

| Método | Descrição |
| --- | --- |
| [close](#close--) | Destrutor que fecha fluxos temporários (se necessário). |
| [getAuthority](#getAuthority--) | O nome da pessoa ou autoridade que assina o documento. |
| [getByteRange](#getByteRange--) | Obtém um array de pares de inteiros (deslocamento inicial em bytes, comprimento em bytes) que descrevem o intervalo exato de bytes para o cálculo do digest. |
| [getContactInfo](#getContactInfo--) | Obtém informações fornecidas pelo assinante para permitir que o destinatário entre em contato com o assinante para verificar a assinatura, por exemplo, um número de telefone. |
| [getCustomAppearance](#getCustomAppearance--) | Obtém/define a aparência personalizada. |
| [getCustomSign](#getCustomSign--) | O delegado para hash personalizado e assinatura do documento (Beta). {@code O algoritmo com o qual você faz hash e assina o documento no delegado deve corresponder ao tipo da chave privada do certificado.} |
| [getCustomSignHash](#getCustomSignHash--) | O delegado para assinatura personalizada do hash do documento (Beta). {@code O algoritmo com o qual você assina o hash no delegado deve corresponder ao tipo da chave privada do certificado.} |
| [getDate](#getDate--) | Obtém o horário da assinatura. |
| [getDefaultSignatureLength](#getDefaultSignatureLength--) | Obtém ou define o comprimento padrão para os dados da assinatura em bytes. Esta é uma estimativa do comprimento da assinatura em bytes. Usado para assinatura via {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) se o parâmetro {@code AvoidEstimatingSignatureLength}({@code #getAvoidEstimatingSignatureLength}/{@code #setAvoidEstimatingSignatureLength(boolean)}) estiver definido. O valor padrão é 3000. |
| [getImageInternal](#getImageInternal--) | Obtém o fluxo de imagem. Apenas para uso interno |
| [getLocation](#getLocation--) | Obtém o nome do host da CPU ou a localização física da assinatura. |
| [getOcspSettings](#getOcspSettings--) | Obtém/define as configurações OCSP. |
| [getReason](#getReason--) | Obtém o motivo da assinatura, como (Concordo!, Pip B.). |
| [getSignatureAlgorithmInfo](#getSignatureAlgorithmInfo--) | Recupera informações sobre o algoritmo de assinatura usado na assinatura. |
| [getSignatureReferences](#getSignatureReferences--) | Obter Referências de Assinatura |
| [getTimestampSettings](#getTimestampSettings--) | Obtém as configurações de timestamp. |
| [getUseLtv](#getUseLtv--) | Obtém/define a bandeira de validação LTV. |
| [isAvoidEstimatingSignatureLength](#isAvoidEstimatingSignatureLength--) | Obtém e define uma opção que indica se deve evitar estimar o comprimento de uma assinatura. Evita estimar o comprimento da assinatura antes de assinar um documento. Usado para assinatura via {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) e via {@code ExternalSignature}. Se {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) retornar uma assinatura mais longa que {@code DefaultSignatureLength}({@code #getDefaultSignatureLength}/{@code #setDefaultSignatureLength(int)}), então {@code SignatureLengthMismatchException} será lançada. O valor padrão é {@code false}. |
| [isShowProperties](#isShowProperties--) | Força a exibição/ocultação das propriedades da assinatura. Caso ShowProperties seja true, o campo de assinatura tem formato predefinido de aparência (strings para representar): ------------------------------------------- Assinado digitalmente por {certificate subject} Data: {signature.Date} Motivo: {signature.Reason} Localização: {signature.Location} ------------------------------------------- onde {X} é um placeholder para o valor X. A assinatura também pode ter imagem; nesse caso as strings listadas são colocadas sobre a imagem. ShowProperties é true por padrão. |
| [setAuthority](#setAuthority-java.lang.String-) | Define o nome da pessoa ou autoridade que assina o documento. |
| [setAvoidEstimatingSignatureLength](#setAvoidEstimatingSignatureLength-boolean-) | Obtém e define uma opção que indica se deve evitar estimar o comprimento de uma assinatura. Evita estimar o comprimento da assinatura antes de assinar um documento. Usado para assinatura via {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) e via {@code ExternalSignature}. Se {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) retornar uma assinatura mais longa que {@code DefaultSignatureLength}({@code #getDefaultSignatureLength}/{@code #setDefaultSignatureLength(int)}), então {@code SignatureLengthMismatchException} será lançada. O valor padrão é {@code false}. |
| [setContactInfo](#setContactInfo-java.lang.String-) | Define as informações fornecidas pelo assinante para permitir que o destinatário entre em contato com o assinante para verificar a assinatura, por exemplo, um número de telefone. |
| [setCustomAppearance](#setCustomAppearance-com.aspose.pdf.SignatureCustomAppearance-) | Obtém/define a aparência personalizada. |
| [setCustomSign](#setCustomSign-com.aspose.pdf.CustomSign-) | O delegado para hash personalizado e assinatura do documento (Beta). {@code O algoritmo com o qual você faz hash e assina o documento no delegado deve corresponder ao tipo da chave privada do certificado.} |
| [setCustomSignHash](#setCustomSignHash-com.aspose.pdf.SignHash-) | O delegado para assinatura personalizada do hash do documento (Beta). {@code O algoritmo com o qual você assina o hash no delegado deve corresponder ao tipo da chave privada do certificado.} |
| [setDate](#setDate-java.util.Date-) | Define o horário da assinatura. |
| [setDefaultSignatureLength](#setDefaultSignatureLength-int-) | Obtém ou define o comprimento padrão para os dados da assinatura em bytes. Esta é uma estimativa do comprimento da assinatura em bytes. Usado para assinatura via {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) se o parâmetro {@code AvoidEstimatingSignatureLength}({@code #getAvoidEstimatingSignatureLength}/{@code #setAvoidEstimatingSignatureLength(boolean)}) estiver definido. O valor padrão é 3000. |
| [setImage](#setImage-java.io.InputStream-) | Define o fluxo de imagem. |
| [setImageInternal](#setImageInternal-com.aspose.ms.System.IO.Stream-) |  |
| [setLocation](#setLocation-java.lang.String-) | Define o nome do host da CPU ou a localização física da assinatura. |
| [setOcspSettings](#setOcspSettings-com.aspose.pdf.OcspSettings-) | Obtém/define as configurações OCSP. |
| [setReason](#setReason-java.lang.String-) | Define o motivo da assinatura, como (I agreed!, Pip B.). |
| [setShowProperties](#setShowProperties-boolean-) | Força a exibição/ocultação das propriedades da assinatura. Caso ShowProperties seja true, o campo de assinatura tem formato predefinido de aparência (strings para representar): ------------------------------------------- Assinado digitalmente por {certificate subject} Data: {signature.Date} Motivo: {signature.Reason} Localização: {signature.Location} ------------------------------------------- onde {X} é um placeholder para o valor X. A assinatura também pode ter imagem; nesse caso as strings listadas são colocadas sobre a imagem. ShowProperties é true por padrão. |
| [setTimestampSettings](#setTimestampSettings-com.aspose.pdf.TimestampSettings-) | Define as configurações de timestamp. |
| [setUseLtv](#setUseLtv-boolean-) | Obtém/define a bandeira de validação LTV. |
| [verify](#verify--) | Verifique o documento em relação a esta assinatura e retorne true se o documento for válido ou false caso contrário. |
| [verify](#verify-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-) | Verifique o documento em relação a esta assinatura e retorne true se o documento for válido ou false caso contrário. |
| [verify](#verify-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-) | Verifique o documento em relação a esta assinatura e retorne true se o documento for válido ou false caso contrário. |

### Signature {#Signature--}
```
public Signature()
```

Inicializa nova instância da classe {@code Signature}.

### Signature {#Signature-java.io.InputStream-java.lang.String-}
Inicializa nova instância da classe {@code Signature}.

### Signature {#Signature-java.lang.String-java.lang.String-}
Inicializa nova instância da classe {@code Signature}.

### close {#close--}
```
public void close()
```

Destrutor que fecha fluxos temporários (se necessário).

### getAuthority {#getAuthority--}
```
public final String getAuthority()
```

O nome da pessoa ou autoridade que assina o documento.

**Returns:**
valor String

### getByteRange {#getByteRange--}
```
public int[] getByteRange()
```

Obtém um array de pares de inteiros (deslocamento inicial em bytes, comprimento em bytes) que descrevem o intervalo exato de bytes para o cálculo do digest.

**Returns:**
array de valores int

### getContactInfo {#getContactInfo--}
```
public String getContactInfo()
```

Obtém informações fornecidas pelo assinante para permitir que o destinatário entre em contato com o assinante para verificar a assinatura, por exemplo, um número de telefone.

**Returns:**
valor String

### getCustomAppearance {#getCustomAppearance--}
```
public final SignatureCustomAppearance getCustomAppearance()
```

Obtém/define a aparência personalizada.

**Returns:**
Instância de SignatureCustomAppearance

### getCustomSign {#getCustomSign--}
```
public final CustomSign getCustomSign()
```

O delegado para hash personalizado e assinatura do documento (Beta). {@code O algoritmo com o qual você faz hash e assina o documento no delegado deve corresponder ao tipo da chave privada do certificado.}

**Returns:**
Instância de SignHash

### getCustomSignHash {#getCustomSignHash--}
```
public final SignHash getCustomSignHash()
```

O delegado para assinatura personalizada do hash do documento (Beta). {@code O algoritmo com o qual você assina o hash no delegado deve corresponder ao tipo da chave privada do certificado.}

**Returns:**
Instância de SignHash

### getDate {#getDate--}
```
public Date getDate()
```

Obtém o horário da assinatura.

**Returns:**
Valor de Date

### getDefaultSignatureLength {#getDefaultSignatureLength--}
```
public final int getDefaultSignatureLength()
```

Obtém ou define o comprimento padrão para os dados da assinatura em bytes. Esta é uma estimativa do comprimento da assinatura em bytes. Usado para assinatura via {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) se o parâmetro {@code AvoidEstimatingSignatureLength}({@code #getAvoidEstimatingSignatureLength}/{@code #setAvoidEstimatingSignatureLength(boolean)}) estiver definido. O valor padrão é 3000.

**Returns:**
valor int

### getImageInternal {#getImageInternal--}
```
public com.aspose.ms.System.IO.Stream getImageInternal()
```

Obtém o fluxo de imagem. Apenas para uso interno

**Returns:**
Objeto Stream

### getLocation {#getLocation--}
```
public String getLocation()
```

Obtém o nome do host da CPU ou a localização física da assinatura.

**Returns:**
valor String

### getOcspSettings {#getOcspSettings--}
```
public OcspSettings getOcspSettings()
```

Obtém/define as configurações OCSP.

**Returns:**
Instância de OcspSettings

### getReason {#getReason--}
```
public String getReason()
```

Obtém o motivo da assinatura, como (Concordo!, Pip B.).

**Returns:**
valor String

### getSignatureAlgorithmInfo {#getSignatureAlgorithmInfo--}
```
public final com.aspose.pdf.engine.security.SignatureAlgorithmInfo getSignatureAlgorithmInfo()
```

Recupera informações sobre o algoritmo de assinatura usado na assinatura.

**Returns:**
Uma instância de { SignatureAlgorithmInfo} que contém detalhes sobre o algoritmo de assinatura.

### getSignatureReferences {#getSignatureReferences--}
```
public List <com.aspose.pdf.engine.security.impl.signatures.SignatureReference> getSignatureReferences()
```

Obter Referências de Assinatura

**Returns:**
{@code java.util.List<SignatureReference> object}

### getTimestampSettings {#getTimestampSettings--}
```
public TimestampSettings getTimestampSettings()
```

Obtém as configurações de timestamp.

**Returns:**
TimestampSettings

### getUseLtv {#getUseLtv--}
```
public final boolean getUseLtv()
```

Obtém/define a bandeira de validação LTV.

**Returns:**
valor booleano

### isAvoidEstimatingSignatureLength {#isAvoidEstimatingSignatureLength--}
```
public final boolean isAvoidEstimatingSignatureLength()
```

Obtém e define uma opção que indica se deve evitar estimar o comprimento de uma assinatura. Evita estimar o comprimento da assinatura antes de assinar um documento. Usado para assinatura via {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) e via {@code ExternalSignature}. Se {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) retornar uma assinatura mais longa que {@code DefaultSignatureLength}({@code #getDefaultSignatureLength}/{@code #setDefaultSignatureLength(int)}), então {@code SignatureLengthMismatchException} será lançada. O valor padrão é {@code false}.

**Returns:**
valor booleano

### isShowProperties {#isShowProperties--}
```
public boolean isShowProperties()
```

Força a exibição/ocultação das propriedades da assinatura. Caso ShowProperties seja true, o campo de assinatura tem formato predefinido de aparência (strings para representar): ------------------------------------------- Assinado digitalmente por {certificate subject} Data: {signature.Date} Motivo: {signature.Reason} Localização: {signature.Location} ------------------------------------------- onde {X} é um placeholder para o valor X. A assinatura também pode ter imagem; nesse caso as strings listadas são colocadas sobre a imagem. ShowProperties é true por padrão.

**Returns:**
valor booleano

### setAuthority {#setAuthority-java.lang.String-}
Define o nome da pessoa ou autoridade que assina o documento.

### setAvoidEstimatingSignatureLength {#setAvoidEstimatingSignatureLength-boolean-}
```
public final void setAvoidEstimatingSignatureLength(boolean value)
```

Obtém e define uma opção que indica se deve evitar estimar o comprimento de uma assinatura. Evita estimar o comprimento da assinatura antes de assinar um documento. Usado para assinatura via {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) e via {@code ExternalSignature}. Se {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) retornar uma assinatura mais longa que {@code DefaultSignatureLength}({@code #getDefaultSignatureLength}/{@code #setDefaultSignatureLength(int)}), então {@code SignatureLengthMismatchException} será lançada. O valor padrão é {@code false}.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setContactInfo {#setContactInfo-java.lang.String-}
Define as informações fornecidas pelo assinante para permitir que o destinatário entre em contato com o assinante para verificar a assinatura, por exemplo, um número de telefone.

### setCustomAppearance {#setCustomAppearance-com.aspose.pdf.SignatureCustomAppearance-}
Obtém/define a aparência personalizada.

### setCustomSign {#setCustomSign-com.aspose.pdf.CustomSign-}
O delegado para hash personalizado e assinatura do documento (Beta). {@code O algoritmo com o qual você faz hash e assina o documento no delegado deve corresponder ao tipo da chave privada do certificado.}

### setCustomSignHash {#setCustomSignHash-com.aspose.pdf.SignHash-}
O delegado para assinatura personalizada do hash do documento (Beta). {@code O algoritmo com o qual você assina o hash no delegado deve corresponder ao tipo da chave privada do certificado.}

### setDate {#setDate-java.util.Date-}
Define o horário da assinatura.

### setDefaultSignatureLength {#setDefaultSignatureLength-int-}
```
public final void setDefaultSignatureLength(int value)
```

Obtém ou define o comprimento padrão para os dados da assinatura em bytes. Esta é uma estimativa do comprimento da assinatura em bytes. Usado para assinatura via {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) se o parâmetro {@code AvoidEstimatingSignatureLength}({@code #getAvoidEstimatingSignatureLength}/{@code #setAvoidEstimatingSignatureLength(boolean)}) estiver definido. O valor padrão é 3000.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int |

### setImage {#setImage-java.io.InputStream-}
Define o fluxo de imagem.

### setImageInternal {#setImageInternal-com.aspose.ms.System.IO.Stream-}


### setLocation {#setLocation-java.lang.String-}
Define o nome do host da CPU ou a localização física da assinatura.

### setOcspSettings {#setOcspSettings-com.aspose.pdf.OcspSettings-}
Obtém/define as configurações OCSP.

### setReason {#setReason-java.lang.String-}
Define o motivo da assinatura, como (I agreed!, Pip B.).

### setShowProperties {#setShowProperties-boolean-}
```
public void setShowProperties(boolean value)
```

Força a exibição/ocultação das propriedades da assinatura. Caso ShowProperties seja true, o campo de assinatura tem formato predefinido de aparência (strings para representar): ------------------------------------------- Assinado digitalmente por {certificate subject} Data: {signature.Date} Motivo: {signature.Reason} Localização: {signature.Location} ------------------------------------------- onde {X} é um placeholder para o valor X. A assinatura também pode ter imagem; nesse caso as strings listadas são colocadas sobre a imagem. ShowProperties é true por padrão.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setTimestampSettings {#setTimestampSettings-com.aspose.pdf.TimestampSettings-}
Define as configurações de timestamp.

### setUseLtv {#setUseLtv-boolean-}
```
public final void setUseLtv(boolean value)
```

Obtém/define a bandeira de validação LTV.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### verify {#verify--}
```
public boolean verify()
```

Verifique o documento em relação a esta assinatura e retorne true se o documento for válido ou false caso contrário.

**Returns:**
true se o documento for válido.

### verify {#verify-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-}
Verifique o documento em relação a esta assinatura e retorne true se o documento for válido ou false caso contrário.

**Returns:**
true se o documento for válido.

### verify {#verify-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-}
Verifique o documento em relação a esta assinatura e retorne true se o documento for válido ou false caso contrário.

**Returns:**
true se o documento for válido.
