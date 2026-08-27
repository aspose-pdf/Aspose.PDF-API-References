---
title: "SignatureField"
linktitle: "SignatureField"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa um campo de formulário de assinatura."
type: docs
weight: 4510
url: /pt/java/com.aspose.pdf/signaturefield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.SignatureField, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.SignatureField, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.SignatureField, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field com.aspose.pdf.SignatureField, com.aspose.pdf.Field, com.aspose.pdf.SignatureField

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public final class SignatureField extends Field
```

Representa um campo de formulário de assinatura.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [SignatureField](#SignatureField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-) | Inicializa uma nova instância da classe {@code SignatureField}. |
| [SignatureField](#SignatureField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Inicializa uma nova instância da classe {@code SignatureField}. |

## Métodos

| Método | Descrição |
| --- | --- |
| [clear](#clear--) | Remove o objeto de assinatura do campo. |
| [extractCertificate](#extractCertificate--) | Extrai o único certificado X.509 no formato DER como um fluxo. |
| [extractCertificateObject](#extractCertificateObject--) | Extrai o objeto do único certificado X.509. |
| [extractImage](#extractImage--) | Extrai a imagem da assinatura como um fluxo codificado em JPEG. |
| [extractImage](#extractImage-com.aspose.pdf.ImageType-) | Extrai a imagem da assinatura como um fluxo codificado em JPEG. |
| [getSignature](#getSignature--) | Obtém o objeto de assinatura. Este objeto contém dados de assinatura referentes a padrões criptográficos de chave pública. As classes {@code PKCS1}, {@code PKCS7} e {@code PKCS7Detached} representam todos os tipos suportados de objetos de assinatura. |
| [sign](#sign-com.aspose.pdf.Signature-) | Assine o documento usando este campo de assinatura. |
| [sign](#sign-com.aspose.pdf.Signature-java.io.InputStream-java.lang.String-) | Assina o documento usando este campo de assinatura. |

### SignatureField {#SignatureField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-}
Inicializa uma nova instância da classe {@code SignatureField}.

### SignatureField {#SignatureField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Inicializa uma nova instância da classe {@code SignatureField}.

### clear {#clear--}
```
public void clear()
```

Remove o objeto de assinatura do campo.

### extractCertificate {#extractCertificate--}
```
public InputStream extractCertificate()
```

Extrai o único certificado X.509 no formato DER como um fluxo.

**Returns:**
Se o certificado for encontrado, retorna o único certificado X.509; caso contrário, null.

### extractCertificateObject {#extractCertificateObject--}
```
public final com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2 extractCertificateObject()
```

Extrai o objeto do único certificado X.509.

**Returns:**
Se o certificado for encontrado, retorna o único certificado X.509; caso contrário, null.

### extractImage {#extractImage--}
```
public InputStream extractImage()
```

Extrai a imagem da assinatura como um fluxo codificado em JPEG.

**Returns:**
Se a imagem for encontrada com sucesso, retorna o objeto de fluxo codificado em JPEG; caso contrário, null.

### extractImage {#extractImage-com.aspose.pdf.ImageType-}
Extrai a imagem da assinatura como um fluxo codificado em JPEG.

**Returns:**
Se a imagem for encontrada com sucesso, retorna o objeto de fluxo codificado em JPEG; caso contrário, null.

### getSignature {#getSignature--}
```
public final Signature getSignature()
```

Obtém o objeto de assinatura. Este objeto contém dados de assinatura referentes a padrões criptográficos de chave pública. As classes {@code PKCS1}, {@code PKCS7} e {@code PKCS7Detached} representam todos os tipos suportados de objetos de assinatura.

**Returns:**
Objeto de assinatura

### sign {#sign-com.aspose.pdf.Signature-}
Assine o documento usando este campo de assinatura.

### sign {#sign-com.aspose.pdf.Signature-java.io.InputStream-java.lang.String-}
Assina o documento usando este campo de assinatura.
