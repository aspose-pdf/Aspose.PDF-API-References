---
title: "PdfFileSignature"
linktitle: "PdfFileSignature"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa uma classe para assinar um arquivo PDF com um certificado."
type: docs
weight: 530
url: /pt/java/com.aspose.pdf.facades/pdffilesignature/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileSignature, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileSignature, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfFileSignature

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfFileSignature extends SaveableFacade
```

Representa uma classe para assinar um arquivo PDF com um certificado.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [PdfFileSignature](#PdfFileSignature--) | O construtor da classe PdfFileSignature. |
| [PdfFileSignature](#PdfFileSignature-com.aspose.pdf.IDocument-) | O construtor da classe PdfFileSignature. |
| [PdfFileSignature](#PdfFileSignature-com.aspose.pdf.IDocument-java.lang.String-) | O construtor da classe PdfFileSignature. |
| [PdfFileSignature](#PdfFileSignature-java.lang.String-) | O construtor da classe PdfFileSignature. |
| [PdfFileSignature](#PdfFileSignature-java.lang.String-java.lang.String-) | O construtor da classe PdfFileSignature. |

## Métodos

| Método | Descrição |
| --- | --- |
| [bindPdf](#bindPdf-java.io.InputStream-) | Vincula um fluxo Pdf para edição. |
| [bindPdf](#bindPdf-java.lang.String-) | Vincula um arquivo Pdf para edição. |
| [certify](#certify-int-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-com.aspose.pdf.DocMDPSignature-) | Certifica o documento com a assinatura MDP. |
| [certify](#certify-java.lang.String-com.aspose.pdf.DocMDPSignature-) | Certifica o documento com a assinatura MDP que está colocada em um campo de assinatura já apresentado. Antes de assinar, o campo de assinatura deve estar vazio, ou seja, o campo não deve conter dicionário de assinatura. Assim, o documento PDF já possui um campo de assinatura; você não deve fornecer o local para aplicar a assinatura, a página correspondente e o retângulo são obtidos a partir do campo de assinatura encontrado pelo nome da assinatura (veja o parâmetro sigName). |
| [close](#close--) | Fecha a fachada. |
| [containsSignature](#containsSignature--) | Verifica se o PDF tem uma assinatura digital ou não. |
| [containsUsageRights](#containsUsageRights--) | Verifica se o PDF tem direitos de uso ou não. |
| [coversWholeDocument](#coversWholeDocument-com.aspose.pdf.facades.SignatureName-) | Verifica se a assinatura cobre todo o documento. |
| [coversWholeDocument](#coversWholeDocument-java.lang.String-) | Verifica se a assinatura cobre todo o documento. |
| [dispose](#dispose--) | Fecha a fachada. Este método está obsoleto, use close() em vez disso. |
| [extractCertificate](#extractCertificate-com.aspose.pdf.facades.SignatureName-) | Extrai o único certificado X.509 da assinatura como um fluxo. |
| [extractCertificate](#extractCertificate-java.lang.String-) | Extrai o único certificado X.509 da assinatura como um fluxo. |
| [extractImage](#extractImage-com.aspose.pdf.facades.SignatureName-) | Extrai a imagem da assinatura. |
| [extractImage](#extractImage-java.lang.String-) | Extrai a imagem da assinatura. |
| [getAccessPermissions](#getAccessPermissions--) | Retorna o valor das permissões de acesso do documento certificado pelo tipo de assinatura MDP. |
| [getBlankSignNames](#getBlankSignNames--) | Obtém os nomes de todos os campos de assinatura vazios. |
| [getContactInfo](#getContactInfo-com.aspose.pdf.facades.SignatureName-) | Obtém as informações de contato de uma assinatura. |
| [getContactInfo](#getContactInfo-java.lang.String-) | Obtém as informações de contato de uma assinatura. |
| [getDateTime](#getDateTime-com.aspose.pdf.facades.SignatureName-) | Obtém a data e hora da assinatura. |
| [getDateTime](#getDateTime-java.lang.String-) | Obtém a data e hora da assinatura. |
| [getLocation](#getLocation-com.aspose.pdf.facades.SignatureName-) | Obtém a localização de uma assinatura. |
| [getLocation](#getLocation-java.lang.String-) | Obtém a localização de uma assinatura. |
| [getReason](#getReason-com.aspose.pdf.facades.SignatureName-) | Obtém o motivo de uma assinatura. |
| [getReason](#getReason-java.lang.String-) | Obtém o motivo de uma assinatura. |
| [getRevision](#getRevision-com.aspose.pdf.facades.SignatureName-) | Obtém a revisão de uma assinatura. |
| [getRevision](#getRevision-java.lang.String-) | Obtém a revisão de uma assinatura. |
| [getSignatureAppearance](#getSignatureAppearance--) | Obtém uma aparência gráfica para a assinatura. O valor da propriedade representa o nome do arquivo de imagem. |
| [getSignatureAppearanceStream](#getSignatureAppearanceStream--) | Obtém uma aparência gráfica para a assinatura. O valor da propriedade representa o fluxo de imagem. |
| [getSignatureNames](#getSignatureNames--) | / * <p> / * Obtém os nomes de todas as assinaturas não vazias. / * </p> / * <p> / * <pre> / * string inFile=TestPath + "example1.pdf"; / * PdfFileSignature pdfSign=new PdfFileSignature(); / * pdfSign.bindPdf(inFile); / * java.util.List<String> names=pdfSign.getSignatureNames(); / * for(int i=0;i<names.size();i++) / * { / * System.out.println("signature name:" + names[i]); / * System.out.println("coverswholedocument:" + pdfSign.coversWholeDocument(names[i])); / * System.out.println("revision:" + pdfSign.getRevision(names[i])); / * System.out.println("verifysigned:" + pdfSign.verifySignature(names[i])); / * System.out.println("reason:" + pdfSign.getReason(names[i])); / * System.out.println("location:" + pdfSign.getLocation(names[i])); / * System.out.println("datatime:" + pdfSign.getDateTime(names[i])); / * } / * System.out.println("totalvision:" + pdfSign.GetTotalRevision()); / * / * </pre> / * |
| [getSignatureNames](#getSignatureNames-boolean-) | Obtém os nomes de todas as assinaturas não vazias. string inFile=TestPath + "example1.pdf"; PdfFileSignature pdfSign=new PdfFileSignature(); pdfSign.bindPdf(inFile); java.util.List names=pdfSign.getSignatureNames(); for(int i=0;i<names.size();i++) { System.out.println("signature name:" + names[i]); System.out.println("coverswholedocument:" + pdfSign.coversWholeDocument(names[i])); System.out.println("revision:" + pdfSign.getRevision(names[i])); System.out.println("verifysigned:" + pdfSign.verifySignature(names[i])); System.out.println("reason:" + pdfSign.getReason(names[i])); System.out.println("location:" + pdfSign.getLocation(names[i])); System.out.println("datatime:" + pdfSign.getDateTime(names[i])); } System.out.println("totalvision:" + pdfSign.GetTotalRevision()); |
| [getSignaturesInfo](#getSignaturesInfo--) | Recupera informações sobre todos os algoritmos de assinaturas presentes no documento PDF. |
| [getSignerName](#getSignerName-com.aspose.pdf.facades.SignatureName-) | Obtém o nome da pessoa ou organização que assina o documento PDF. |
| [getSignerName](#getSignerName-java.lang.String-) | Obtém o nome da pessoa ou organização que assina o documento PDF. |
| [getSignNames](#getSignNames--) | <p> Obtém os nomes de todas as assinaturas não vazias. </p> <hr> |
| [getSignNames](#getSignNames-boolean-) | <p> Obtém os nomes de todas as assinaturas não vazias. </p> <hr> <pre> String inFile=TestPath + "example1.pdf"; PdfFileSignature pdfSign=new PdfFileSignature(); pdfSign.bindPdf(inFile); ArrayList names=pdfSign.getSignNames(true); for(int i=0;i<names.Count;i++) { System.out.println("signature name:"+(String)names[i]); System.out.println("coverswholedocument:"+pdfSign.IsCoversWholeDocument((String)names[i])); System.out.println("revision:"+pdfSign.GetRevision((String)names[i])); System.out.println("verifysigned:"+pdfSign.VerifySigned((String)names[i])); System.out.println("reason:"+pdfSign.GetReason((String)names[i])); System.out.println("location:"+pdfSign.GetLocation((String)names[i])); System.out.println("datatime:"+pdfSign.GetDateTime((String)names[i])); } System.out.println("totalvision:"+pdfSign.GetTotalRevision()); </pre> |
| [getTotalRevision](#getTotalRevision--) | Obtém a revisão total. |
| [isCertified](#isCertified--) | Obtém o indicador que determina se um documento está certificado ou não. |
| [isContainSignature](#isContainSignature--) | Verifica se o PDF tem uma assinatura digital ou não. |
| [isCoversWholeDocument](#isCoversWholeDocument-java.lang.String-) | Verifica se a assinatura cobre todo o documento. |
| [isLtvEnabled](#isLtvEnabled--) | Obtém o indicador de LTV habilitado. |
| [removeSignature](#removeSignature-com.aspose.pdf.facades.SignatureName-) | Remove a assinatura de acordo com o nome da assinatura. string inFile = TestPath + "example1.pdf"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); IList<SignatureName> names = pdfSign.getSignatureNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature(names[i]); } pdfSign.save(TestPath + "signed_removed.pdf"); |
| [removeSignature](#removeSignature-com.aspose.pdf.facades.SignatureName-boolean-) | Remove a assinatura de acordo com o nome da assinatura. string inFile = TestPath + "example1.pdf"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); IList<SignatureName> names = pdfSign.getSignatureNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature(names[i], false); } pdfSign.save(TestPath + "signed_removed.pdf"); |
| [removeSignature](#removeSignature-java.lang.String-) | <p> Remova a assinatura de acordo com o nome da assinatura. </p> <hr> <pre> String inFile = TestPath + "example1.pdf"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); List names = pdfSign.getSignNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature((String)names.get(i)); } pdfSign.save(TestPath + "signed_removed.pdf"); </pre> |
| [removeSignature](#removeSignature-java.lang.String-boolean-) | <p> Remove a assinatura de acordo com o nome da assinatura. </p> <hr> <pre> String inFile = TestPath + "example1.pdf"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.BindPdf(inFile); List names = pdfSign.getSignNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature((String)names.get(i), false); } pdfSign.save(TestPath + "signed_removed.pdf"); </pre> |
| [removeSignatures](#removeSignatures--) | Remove todas as assinaturas. string inFile = TestPath + "example1.pdf"; var pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); pdfSign.removeSignatures(); pdfSign.save(TestPath + "signed_removed.pdf"); |
| [removeUsageRights](#removeUsageRights--) | Remove a entrada de direitos de uso. |
| [save](#save--) | Salve o arquivo PDF assinado. O nome do arquivo de saída deve ser fornecido antes com a ajuda do construtor correspondente do PdfFileSignature. |
| [save](#save-java.io.OutputStream-) | Salve o arquivo PDF assinado. O nome do arquivo de saída deve ser fornecido antes com a ajuda do construtor correspondente do PdfFileSignature. |
| [save](#save-java.lang.String-) | Salve o arquivo PDF assinado. O nome do arquivo de saída deve ser fornecido antes com a ajuda do construtor correspondente do PdfFileSignature. |
| [setCertificate](#setCertificate-java.lang.String-java.lang.String-) | Defina o arquivo de certificado e a senha para a rotina de assinatura. |
| [setSignatureAppearance](#setSignatureAppearance-java.lang.String-) | Define uma aparência gráfica para a assinatura. O valor da propriedade representa o nome do arquivo de imagem. |
| [setSignatureAppearanceStream](#setSignatureAppearanceStream-java.io.InputStream-) | Define uma aparência gráfica para a assinatura. O valor da propriedade representa o fluxo de imagem. |
| [sign](#sign-int-boolean-java.awt.Rectangle-com.aspose.pdf.Signature-) | Assine o documento com a assinatura do tipo fornecido. |
| [sign](#sign-int-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-) | Faça uma assinatura no documento PDF. |
| [sign](#sign-int-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-com.aspose.pdf.Signature-) | Assine o documento com a assinatura do tipo fornecido. |
| [sign](#sign-int-java.lang.String-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-com.aspose.pdf.Signature-) | Assine o documento com a assinatura do tipo fornecido que está colocada em um campo de assinatura já apresentado. |
| [sign](#sign-java.lang.String-com.aspose.pdf.Signature-) | <p> Assine o documento com a assinatura do tipo fornecido que está colocada em um campo de assinatura já apresentado. Antes de assinar, o campo de assinatura deve estar vazio, ou seja, o campo não deve conter dicionário de assinatura. Assim, o documento PDF já possui um campo de assinatura; você não deve fornecer o local para aplicar a assinatura, a página e o retângulo correspondentes são obtidos do campo de assinatura encontrado pelo nome da assinatura (veja o parâmetro SigName). Dados como motivo da assinatura, contato e localização devem ser fornecidos pelas propriedades correspondentes do objeto Signature sig. </p> <hr> <pre> String inFile = TestPath + "example1.pdf"; String outFile = TestPath + "signature.pdf"; PKCS1 sig = new PKCS1("certificate.pfx", "password"); sig.setReason ( "Some reason"); sig.setContact ( "Smith"); sig.setLocation ( "New York"); PdfFileSignature pdfSign = new PdfFileSignature(inFile, outFile); pdfSign.setSignatureAppearance ( TestPath + "butterfly.jpg"); pdfSign.sign("Signature1", sig); pdfSign.save(); </pre> |
| [sign](#sign-java.lang.String-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.Signature-) | <p> Assine o documento com a assinatura do tipo fornecido que está colocada em um campo de assinatura já apresentado. Antes de assinar, o campo de assinatura deve estar vazio, ou seja, o campo não deve conter dicionário de assinatura. Assim, o documento PDF já possui um campo de assinatura; você não deve fornecer o local para aplicar a assinatura, a página e o retângulo correspondentes são obtidos do campo de assinatura encontrado pelo nome da assinatura (veja o parâmetro SigName). </p> <hr> <pre> String inFile = TestPath + "example1.pdf"; String outFile = TestPath + "signature.pdf"; PKCS1 sig = new PKCS1("certificate.pfx", "password"); PdfFileSignature pdfSign = new PdfFileSignature(inFile, outFile); pdfSign.setSignatureAppearance ( TestPath + "butterfly.jpg"); pdfSign.sign("Signature1", "Allen", "success", "ChangSha", sig); pdfSign.save(); </pre> |
| [tryExtractCertificate](#tryExtractCertificate-com.aspose.pdf.facades.SignatureName-java.io.OutputStream:A-) | Extrai o único certificado X.509 da assinatura como um fluxo. |
| [tryExtractCertificate](#tryExtractCertificate-com.aspose.pdf.facades.SignatureName-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2:A-) | Extrai o único certificado X.509 da assinatura. |
| [verifySignature](#verifySignature-com.aspose.pdf.facades.SignatureName-) | Verifica a validade de uma assinatura. |
| [verifySignature](#verifySignature-com.aspose.pdf.facades.SignatureName-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-) | Verifica a validade de uma assinatura. |
| [verifySignature](#verifySignature-com.aspose.pdf.facades.SignatureName-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-) | Verifica a validade de uma assinatura. |
| [verifySignature](#verifySignature-com.aspose.pdf.facades.SignatureName-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-) | Verifica a validade de uma assinatura. |
| [verifySignature](#verifySignature-java.lang.String-) | Verifica a validade de uma assinatura. |
| [verifySignature](#verifySignature-java.lang.String-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-) | Verifica a validade de uma assinatura. |
| [verifySigned](#verifySigned-java.lang.String-) | Verifica a validade de uma assinatura. O método está obsoleto e será removido na versão 25.1. Use o método VerifySignature em vez disso. |

### PdfFileSignature {#PdfFileSignature--}
```
public PdfFileSignature()
```

O construtor da classe PdfFileSignature.

### PdfFileSignature {#PdfFileSignature-com.aspose.pdf.IDocument-}
O construtor da classe PdfFileSignature.

### PdfFileSignature {#PdfFileSignature-com.aspose.pdf.IDocument-java.lang.String-}
O construtor da classe PdfFileSignature.

### PdfFileSignature {#PdfFileSignature-java.lang.String-}
O construtor da classe PdfFileSignature.

### PdfFileSignature {#PdfFileSignature-java.lang.String-java.lang.String-}
O construtor da classe PdfFileSignature.

### bindPdf {#bindPdf-java.io.InputStream-}
Vincula um fluxo Pdf para edição.

### bindPdf {#bindPdf-java.lang.String-}
Vincula um arquivo Pdf para edição.

### certify {#certify-int-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-com.aspose.pdf.DocMDPSignature-}
Certifica o documento com a assinatura MDP.

### certify {#certify-java.lang.String-com.aspose.pdf.DocMDPSignature-}
Certifica o documento com a assinatura MDP que está colocada em um campo de assinatura já apresentado. Antes de assinar, o campo de assinatura deve estar vazio, ou seja, o campo não deve conter dicionário de assinatura. Assim, o documento PDF já possui um campo de assinatura; você não deve fornecer o local para aplicar a assinatura, a página correspondente e o retângulo são obtidos a partir do campo de assinatura encontrado pelo nome da assinatura (veja o parâmetro sigName).

### close {#close--}
```
public void close()
```

Fecha a fachada.

### containsSignature {#containsSignature--}
```
public boolean containsSignature()
```

Verifica se o PDF tem uma assinatura digital ou não.

**Returns:**
Retorna um resultado do tipo bool.

### containsUsageRights {#containsUsageRights--}
```
public boolean containsUsageRights()
```

Verifica se o PDF tem direitos de uso ou não.

**Returns:**
Retorna um resultado do tipo bool.

### coversWholeDocument {#coversWholeDocument-com.aspose.pdf.facades.SignatureName-}
Verifica se a assinatura cobre todo o documento.

### coversWholeDocument {#coversWholeDocument-java.lang.String-}
Verifica se a assinatura cobre todo o documento.

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Fecha a fachada. Este método está obsoleto, use close() em vez disso.

### extractCertificate {#extractCertificate-com.aspose.pdf.facades.SignatureName-}
Extrai o único certificado X.509 da assinatura como um fluxo.

### extractCertificate {#extractCertificate-java.lang.String-}
Extrai o único certificado X.509 da assinatura como um fluxo.

### extractImage {#extractImage-com.aspose.pdf.facades.SignatureName-}
Extrai a imagem da assinatura.

### extractImage {#extractImage-java.lang.String-}
Extrai a imagem da assinatura.

### getAccessPermissions {#getAccessPermissions--}
```
public DocMDPAccessPermissions getAccessPermissions()
```

Retorna o valor das permissões de acesso do documento certificado pelo tipo de assinatura MDP.

**Returns:**
PdfException Se o documento estiver sendo certificado, então retorna o valor das permissões de acesso; caso contrário, é lançada. @see com.aspose.pdf.DocMDPAccessPermissions

### getBlankSignNames {#getBlankSignNames--}
```
@Deprecated public List < String > getBlankSignNames()
```

Obtém os nomes de todos os campos de assinatura vazios.

**Returns:**
Retorna um arrayList. @deprecated Use GetBlankSignatureNames() em vez disso.

### getContactInfo {#getContactInfo-com.aspose.pdf.facades.SignatureName-}
Obtém as informações de contato de uma assinatura.

### getContactInfo {#getContactInfo-java.lang.String-}
Obtém as informações de contato de uma assinatura.

### getDateTime {#getDateTime-com.aspose.pdf.facades.SignatureName-}
Obtém a data e hora da assinatura.

### getDateTime {#getDateTime-java.lang.String-}
Obtém a data e hora da assinatura.

### getLocation {#getLocation-com.aspose.pdf.facades.SignatureName-}
Obtém a localização de uma assinatura.

### getLocation {#getLocation-java.lang.String-}
Obtém a localização de uma assinatura.

### getReason {#getReason-com.aspose.pdf.facades.SignatureName-}
Obtém o motivo de uma assinatura.

### getReason {#getReason-java.lang.String-}
Obtém o motivo de uma assinatura.

### getRevision {#getRevision-com.aspose.pdf.facades.SignatureName-}
Obtém a revisão de uma assinatura.

### getRevision {#getRevision-java.lang.String-}
Obtém a revisão de uma assinatura.

### getSignatureAppearance {#getSignatureAppearance--}
```
public String getSignatureAppearance()
```

Obtém uma aparência gráfica para a assinatura. O valor da propriedade representa o nome do arquivo de imagem.

**Returns:**
valor String

### getSignatureAppearanceStream {#getSignatureAppearanceStream--}
```
public InputStream getSignatureAppearanceStream()
```

Obtém uma aparência gráfica para a assinatura. O valor da propriedade representa o fluxo de imagem.

**Returns:**
Elemento InputStream

### getSignatureNames {#getSignatureNames--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericList< SignatureName > getSignatureNames()
```

/ * <p> / * Obtém os nomes de todas as assinaturas não vazias. / * </p> / * <p> / * <pre> / * string inFile=TestPath + "example1.pdf"; / * PdfFileSignature pdfSign=new PdfFileSignature(); / * pdfSign.bindPdf(inFile); / * java.util.List<String> names=pdfSign.getSignatureNames(); / * for(int i=0;i<names.size();i++) / * { / * System.out.println("signature name:" + names[i]); / * System.out.println("coverswholedocument:" + pdfSign.coversWholeDocument(names[i])); / * System.out.println("revision:" + pdfSign.getRevision(names[i])); / * System.out.println("verifysigned:" + pdfSign.verifySignature(names[i])); / * System.out.println("reason:" + pdfSign.getReason(names[i])); / * System.out.println("location:" + pdfSign.getLocation(names[i])); / * System.out.println("datatime:" + pdfSign.getDateTime(names[i])); / * } / * System.out.println("totalvision:" + pdfSign.GetTotalRevision()); / * / * </pre> / *

**Returns:**
Retorna um IList<SignatureName>. /

### getSignatureNames {#getSignatureNames-boolean-}
```
public final com.aspose.ms.System.Collections.Generic.IGenericList< SignatureName > getSignatureNames(boolean onlyActive)
```

Obtém os nomes de todas as assinaturas não vazias. string inFile=TestPath + "example1.pdf"; PdfFileSignature pdfSign=new PdfFileSignature(); pdfSign.bindPdf(inFile); java.util.List names=pdfSign.getSignatureNames(); for(int i=0;i<names.size();i++) { System.out.println("signature name:" + names[i]); System.out.println("coverswholedocument:" + pdfSign.coversWholeDocument(names[i])); System.out.println("revision:" + pdfSign.getRevision(names[i])); System.out.println("verifysigned:" + pdfSign.verifySignature(names[i])); System.out.println("reason:" + pdfSign.getReason(names[i])); System.out.println("location:" + pdfSign.getLocation(names[i])); System.out.println("datatime:" + pdfSign.getDateTime(names[i])); } System.out.println("totalvision:" + pdfSign.GetTotalRevision());

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| onlyActive |  | se true, retorna apenas assinaturas ativas; caso contrário, retorna todas as assinaturas. |

**Returns:**
Retorna um IList<SignatureName>.

### getSignaturesInfo {#getSignaturesInfo--}
```
public final List <com.aspose.pdf.engine.security.SignatureAlgorithmInfo> getSignaturesInfo()
```

Recupera informações sobre todos os algoritmos de assinaturas presentes no documento PDF.

**Returns:**
Uma lista de instâncias {@link SignatureAlgorithmInfo} contendo informações sobre cada assinatura.

### getSignerName {#getSignerName-com.aspose.pdf.facades.SignatureName-}
Obtém o nome da pessoa ou organização que assina o documento PDF.

### getSignerName {#getSignerName-java.lang.String-}
Obtém o nome da pessoa ou organização que assina o documento PDF.

### getSignNames {#getSignNames--}
```
public final List < String > getSignNames()
```

<p> Obtém os nomes de todas as assinaturas não vazias. </p> <hr>

**Returns:**
Retorna um arrayList.

### getSignNames {#getSignNames-boolean-}
```
@Deprecated public List < String > getSignNames(boolean onlyActive)
```

<p> Obtém os nomes de todas as assinaturas não vazias. </p> <hr> <pre> String inFile=TestPath + "example1.pdf"; PdfFileSignature pdfSign=new PdfFileSignature(); pdfSign.bindPdf(inFile); ArrayList names=pdfSign.getSignNames(true); for(int i=0;i<names.Count;i++) { System.out.println("signature name:"+(String)names[i]); System.out.println("coverswholedocument:"+pdfSign.IsCoversWholeDocument((String)names[i])); System.out.println("revision:"+pdfSign.GetRevision((String)names[i])); System.out.println("verifysigned:"+pdfSign.VerifySigned((String)names[i])); System.out.println("reason:"+pdfSign.GetReason((String)names[i])); System.out.println("location:"+pdfSign.GetLocation((String)names[i])); System.out.println("datatime:"+pdfSign.GetDateTime((String)names[i])); } System.out.println("totalvision:"+pdfSign.GetTotalRevision()); </pre>

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| onlyActive |  | valor booleano, se true, retorna apenas assinaturas ativas; caso contrário, retorna todas as assinaturas. |

**Returns:**
Retorna um arrayList. @deprecated O método pode produzir os mesmos nomes de assinatura, que não podem ser distinguidos durante a verificação. Use getSignatureNames(boolean onlyActive) em vez disso.

### getTotalRevision {#getTotalRevision--}
```
public int getTotalRevision()
```

Obtém a revisão total.

**Returns:**
Retorna o número total de revisões de assinatura.

### isCertified {#isCertified--}
```
public boolean isCertified()
```

Obtém o indicador que determina se um documento está certificado ou não.

**Returns:**
valor booleano

### isContainSignature {#isContainSignature--}
```
@Deprecated public boolean isContainSignature()
```

Verifica se o PDF tem uma assinatura digital ou não.

**Returns:**
Retorna um resultado do tipo bool.

### isCoversWholeDocument {#isCoversWholeDocument-java.lang.String-}
Verifica se a assinatura cobre todo o documento.

### isLtvEnabled {#isLtvEnabled--}
```
public final boolean isLtvEnabled()
```

Obtém o indicador de LTV habilitado.

**Returns:**
valor booleano

### removeSignature {#removeSignature-com.aspose.pdf.facades.SignatureName-}
Remove a assinatura de acordo com o nome da assinatura. string inFile = TestPath + "example1.pdf"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); IList<SignatureName> names = pdfSign.getSignatureNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature(names[i]); } pdfSign.save(TestPath + "signed_removed.pdf");

### removeSignature {#removeSignature-com.aspose.pdf.facades.SignatureName-boolean-}
Remove a assinatura de acordo com o nome da assinatura. string inFile = TestPath + "example1.pdf"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); IList<SignatureName> names = pdfSign.getSignatureNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature(names[i], false); } pdfSign.save(TestPath + "signed_removed.pdf");

### removeSignature {#removeSignature-java.lang.String-}
<p> Remova a assinatura de acordo com o nome da assinatura. </p> <hr> <pre> String inFile = TestPath + "example1.pdf"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); List names = pdfSign.getSignNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature((String)names.get(i)); } pdfSign.save(TestPath + "signed_removed.pdf"); </pre>

### removeSignature {#removeSignature-java.lang.String-boolean-}
<p> Remove a assinatura de acordo com o nome da assinatura. </p> <hr> <pre> String inFile = TestPath + "example1.pdf"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.BindPdf(inFile); List names = pdfSign.getSignNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature((String)names.get(i), false); } pdfSign.save(TestPath + "signed_removed.pdf"); </pre>

### removeSignatures {#removeSignatures--}
```
public final void removeSignatures()
```

Remove todas as assinaturas. string inFile = TestPath + "example1.pdf"; var pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); pdfSign.removeSignatures(); pdfSign.save(TestPath + "signed_removed.pdf");

### removeUsageRights {#removeUsageRights--}
```
public void removeUsageRights()
```

Remove a entrada de direitos de uso.

### save {#save--}
```
@Deprecated public void save()
```

Salve o arquivo PDF assinado. O nome do arquivo de saída deve ser fornecido antes com a ajuda do construtor correspondente do PdfFileSignature.

### save {#save-java.io.OutputStream-}
Salve o arquivo PDF assinado. O nome do arquivo de saída deve ser fornecido antes com a ajuda do construtor correspondente do PdfFileSignature.

### save {#save-java.lang.String-}
Salve o arquivo PDF assinado. O nome do arquivo de saída deve ser fornecido antes com a ajuda do construtor correspondente do PdfFileSignature.

### setCertificate {#setCertificate-java.lang.String-java.lang.String-}
Defina o arquivo de certificado e a senha para a rotina de assinatura.

### setSignatureAppearance {#setSignatureAppearance-java.lang.String-}
Define uma aparência gráfica para a assinatura. O valor da propriedade representa o nome do arquivo de imagem.

### setSignatureAppearanceStream {#setSignatureAppearanceStream-java.io.InputStream-}
Define uma aparência gráfica para a assinatura. O valor da propriedade representa o fluxo de imagem.

### sign {#sign-int-boolean-java.awt.Rectangle-com.aspose.pdf.Signature-}
Assine o documento com a assinatura do tipo fornecido.

### sign {#sign-int-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-}
Faça uma assinatura no documento PDF.

### sign {#sign-int-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-com.aspose.pdf.Signature-}
Assine o documento com a assinatura do tipo fornecido.

### sign {#sign-int-java.lang.String-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-com.aspose.pdf.Signature-}
Assine o documento com a assinatura do tipo fornecido que está colocada em um campo de assinatura já apresentado.

### sign {#sign-java.lang.String-com.aspose.pdf.Signature-}
<p> Assine o documento com a assinatura do tipo fornecido que está colocada em um campo de assinatura já apresentado. Antes de assinar, o campo de assinatura deve estar vazio, ou seja, o campo não deve conter dicionário de assinatura. Assim, o documento PDF já possui um campo de assinatura; você não deve fornecer o local para aplicar a assinatura, a página e o retângulo correspondentes são obtidos do campo de assinatura encontrado pelo nome da assinatura (veja o parâmetro SigName). Dados como motivo da assinatura, contato e localização devem ser fornecidos pelas propriedades correspondentes do objeto Signature sig. </p> <hr> <pre> String inFile = TestPath + "example1.pdf"; String outFile = TestPath + "signature.pdf"; PKCS1 sig = new PKCS1("certificate.pfx", "password"); sig.setReason ( "Some reason"); sig.setContact ( "Smith"); sig.setLocation ( "New York"); PdfFileSignature pdfSign = new PdfFileSignature(inFile, outFile); pdfSign.setSignatureAppearance ( TestPath + "butterfly.jpg"); pdfSign.sign("Signature1", sig); pdfSign.save(); </pre>

### sign {#sign-java.lang.String-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.Signature-}
<p> Assine o documento com a assinatura do tipo fornecido que está colocada em um campo de assinatura já apresentado. Antes de assinar, o campo de assinatura deve estar vazio, ou seja, o campo não deve conter dicionário de assinatura. Assim, o documento PDF já possui um campo de assinatura; você não deve fornecer o local para aplicar a assinatura, a página e o retângulo correspondentes são obtidos do campo de assinatura encontrado pelo nome da assinatura (veja o parâmetro SigName). </p> <hr> <pre> String inFile = TestPath + "example1.pdf"; String outFile = TestPath + "signature.pdf"; PKCS1 sig = new PKCS1("certificate.pfx", "password"); PdfFileSignature pdfSign = new PdfFileSignature(inFile, outFile); pdfSign.setSignatureAppearance ( TestPath + "butterfly.jpg"); pdfSign.sign("Signature1", "Allen", "success", "ChangSha", sig); pdfSign.save(); </pre>

### tryExtractCertificate {#tryExtractCertificate-com.aspose.pdf.facades.SignatureName-java.io.OutputStream:A-}
Extrai o único certificado X.509 da assinatura como um fluxo.

### tryExtractCertificate {#tryExtractCertificate-com.aspose.pdf.facades.SignatureName-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2:A-}
Extrai o único certificado X.509 da assinatura.

### verifySignature {#verifySignature-com.aspose.pdf.facades.SignatureName-}
Verifica a validade de uma assinatura.

### verifySignature {#verifySignature-com.aspose.pdf.facades.SignatureName-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-}
Verifica a validade de uma assinatura.

### verifySignature {#verifySignature-com.aspose.pdf.facades.SignatureName-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-}
Verifica a validade de uma assinatura.

### verifySignature {#verifySignature-com.aspose.pdf.facades.SignatureName-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-}
Verifica a validade de uma assinatura.

### verifySignature {#verifySignature-java.lang.String-}
Verifica a validade de uma assinatura.

### verifySignature {#verifySignature-java.lang.String-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-}
Verifica a validade de uma assinatura.

### verifySigned {#verifySigned-java.lang.String-}
Verifica a validade de uma assinatura. O método está obsoleto e será removido na versão 25.1. Use o método VerifySignature em vez disso.
