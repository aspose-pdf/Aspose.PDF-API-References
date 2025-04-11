---
title: Class PdfFileSignature
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Facades.PdfFileSignature. Representa uma classe para assinar um arquivo pdf com um certificado
type: docs
weight: 4560
url: /pt/net/aspose.pdf.facades/pdffilesignature/
---
## Classe PdfFileSignature

Representa uma classe para assinar um arquivo pdf com um certificado.

```csharp
public sealed class PdfFileSignature : SaveableFacade
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [PdfFileSignature](pdffilesignature/#constructor)() | O construtor da classe PdfFileSignature. |
| [PdfFileSignature](pdffilesignature/#constructor_1)(Document) | Inicializa um novo objeto `PdfFileSignature` com base no *documento*. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Obtém a fachada do documento em que está trabalhando. |
| [IsCertified](../../aspose.pdf.facades/pdffilesignature/iscertified/) { get; } | Obtém o indicador que determina se um documento está certificado ou não. |
| [IsLtvEnabled](../../aspose.pdf.facades/pdffilesignature/isltvenabled/) { get; } | Obtém o indicador de LTV habilitado. |
| [SignatureAppearance](../../aspose.pdf.facades/pdffilesignature/signatureappearance/) { get; set; } | Define ou obtém uma aparência gráfica para a assinatura. O valor da propriedade representa o nome do arquivo de imagem. |
| [SignatureAppearanceStream](../../aspose.pdf.facades/pdffilesignature/signatureappearancestream/) { get; set; } | Define ou obtém uma aparência gráfica para a assinatura. O valor da propriedade representa o fluxo de imagem. |

## Métodos

| Nome | Descrição |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Inicializa a fachada. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesignature/bindpdf/#bindpdf_1)(Stream) | Vincula um fluxo Pdf para edição. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesignature/bindpdf/#bindpdf_2)(string) | Vincula um arquivo Pdf para edição. |
| [Certify](../../aspose.pdf.facades/pdffilesignature/certify/#certify_1)(string, DocMDPSignature) | Certifica o documento com a assinatura MDP que está colocada no campo de assinatura já apresentado. Antes de assinar, o campo de assinatura deve estar vazio, ou seja, o campo não deve conter um dicionário de assinatura. Assim, o documento pdf já possui um campo de assinatura, você não deve fornecer o local para carimbar a assinatura, a página correspondente e o retângulo são retirados do campo de assinatura que é encontrado pelo nome da assinatura (veja o parâmetro sigName). |
| [Certify](../../aspose.pdf.facades/pdffilesignature/certify/#certify)(int, string, string, string, bool, Rectangle, DocMDPSignature) | Certifica o documento com a assinatura MDP. Dados como motivo da assinatura, contato e localização devem ser fornecidos pelas propriedades correspondentes do objeto Signature sig. |
| override [Close](../../aspose.pdf.facades/pdffilesignature/close/)() | Fecha a fachada. |
| [ContainsSignature](../../aspose.pdf.facades/pdffilesignature/containssignature/)() | Verifica se o pdf possui uma assinatura digital ou não. |
| [ContainsUsageRights](../../aspose.pdf.facades/pdffilesignature/containsusagerights/)() | Verifica se o pdf possui direitos de uso ou não. |
| [CoversWholeDocument](../../aspose.pdf.facades/pdffilesignature/coverswholedocument/#coverswholedocument)(SignatureName) | Verifica se a assinatura cobre todo o documento. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Desfaz a fachada. |
| [ExtractCertificate](../../aspose.pdf.facades/pdffilesignature/extractcertificate/#extractcertificate)(SignatureName) | Extrai o único certificado X.509 da assinatura como um fluxo. |
| [ExtractImage](../../aspose.pdf.facades/pdffilesignature/extractimage/#extractimage)(SignatureName) | Extrai a imagem da assinatura. |
| [GetAccessPermissions](../../aspose.pdf.facades/pdffilesignature/getaccesspermissions/)() | Retorna o valor das permissões de acesso do documento certificado pelo tipo de assinatura MDP. |
| [GetBlankSignatureNames](../../aspose.pdf.facades/pdffilesignature/getblanksignaturenames/)() | Obtém os nomes de todos os campos de assinatura vazios. |
| [GetContactInfo](../../aspose.pdf.facades/pdffilesignature/getcontactinfo/#getcontactinfo)(SignatureName) | Obtém as informações de contato de uma assinatura. |
| [GetDateTime](../../aspose.pdf.facades/pdffilesignature/getdatetime/#getdatetime)(SignatureName) | Obtém a data e hora da assinatura. |
| [GetLocation](../../aspose.pdf.facades/pdffilesignature/getlocation/#getlocation)(SignatureName) | Obtém a localização de uma assinatura. |
| [GetReason](../../aspose.pdf.facades/pdffilesignature/getreason/#getreason)(SignatureName) | Obtém o motivo de uma assinatura. |
| [GetRevision](../../aspose.pdf.facades/pdffilesignature/getrevision/#getrevision)(SignatureName) | Obtém a revisão de uma assinatura. |
| [GetSignatureNames](../../aspose.pdf.facades/pdffilesignature/getsignaturenames/)(bool) | Obtém os nomes de todas as assinaturas não vazias. |
| [GetSignaturesInfo](../../aspose.pdf.facades/pdffilesignature/getsignaturesinfo/)() | Recupera informações sobre todos os algoritmos de assinatura presentes no documento PDF. |
| [GetSignerName](../../aspose.pdf.facades/pdffilesignature/getsignername/#getsignername)(SignatureName) | Obtém o nome da pessoa ou organização que assina o documento pdf. |
| [GetTotalRevision](../../aspose.pdf.facades/pdffilesignature/gettotalrevision/)() | Obtém a revisão total. |
| [RemoveSignature](../../aspose.pdf.facades/pdffilesignature/removesignature/#removesignature)(SignatureName) | Remove a assinatura de acordo com o nome da assinatura. |
| [RemoveSignature](../../aspose.pdf.facades/pdffilesignature/removesignature/#removesignature_1)(SignatureName, bool) | Remove a assinatura de acordo com o nome da assinatura. |
| [RemoveSignatures](../../aspose.pdf.facades/pdffilesignature/removesignatures/)() | Remove todas as assinaturas. |
| [RemoveUsageRights](../../aspose.pdf.facades/pdffilesignature/removeusagerights/)() | Remove a entrada de direitos de uso. |
| override [Save](../../aspose.pdf.facades/pdffilesignature/save/#save_1)(Stream) | Salva o PDF resultante no fluxo. |
| override [Save](../../aspose.pdf.facades/pdffilesignature/save/#save_2)(string) | Salva o PDF resultante no arquivo. |
| [SetCertificate](../../aspose.pdf.facades/pdffilesignature/setcertificate/)(string, string) | Define o arquivo de certificado e a senha para o procedimento de assinatura. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_4)(string, Signature) | Assina o documento com o tipo de assinatura fornecido que está colocado no campo de assinatura já apresentado. Antes de assinar, o campo de assinatura deve estar vazio, ou seja, o campo não deve conter um dicionário de assinatura. Assim, o documento pdf já possui um campo de assinatura, você não deve fornecer o local para carimbar a assinatura, a página correspondente e o retângulo são retirados do campo de assinatura que é encontrado pelo nome da assinatura (veja o parâmetro SigName). Dados como motivo da assinatura, contato e localização devem ser fornecidos pelas propriedades correspondentes do objeto Signature sig. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign)(int, bool, Rectangle, Signature) | Assina o documento com o tipo de assinatura fornecido. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_5)(string, string, string, string, Signature) | Assina o documento com o tipo de assinatura fornecido que está colocado no campo de assinatura já apresentado. Antes de assinar, o campo de assinatura deve estar vazio, ou seja, o campo não deve conter um dicionário de assinatura. Assim, o documento pdf já possui um campo de assinatura, você não deve fornecer o local para carimbar a assinatura, a página correspondente e o retângulo são retirados do campo de assinatura que é encontrado pelo nome da assinatura (veja o parâmetro SigName). |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_1)(int, string, string, string, bool, Rectangle) | Faz uma assinatura no documento pdf. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_2)(int, string, string, string, bool, Rectangle, Signature) | Assina o documento com o tipo de assinatura fornecido. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_3)(int, string, string, string, string, bool, Rectangle, Signature) | Assina o documento com o tipo de assinatura fornecido que está colocado no campo de assinatura já apresentado. Antes de assinar, o documento pdf já deve ter um campo de assinatura, a página correspondente e o retângulo são retirados do campo de assinatura que é encontrado pelo nome da assinatura (veja o parâmetro SigName). |
| [VerifySignature](../../aspose.pdf.facades/pdffilesignature/verifysignature/#verifysignature)(SignatureName) | Verifica a validade de uma assinatura. |
| [VerifySignature](../../aspose.pdf.facades/pdffilesignature/verifysignature/#verifysignature_1)(SignatureName, ValidationOptions, out ValidationResult) | Verifica a validade de uma assinatura. |

### Veja Também

* classe [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)