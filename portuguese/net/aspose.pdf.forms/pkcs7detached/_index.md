---
title: Class PKCS7Detached
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Forms.PKCS7Detached. Representa o objeto PKCS7 que está em conformidade com a especificação PKCS7 no RFC 2315 da Internet PKCS 7 Sintaxe de Mensagem Criptográfica Versão 1.5. O resumo da mensagem assinada original sobre o intervalo de bytes dos documentos é incorporado como o campo normal PKCS7 SignedData. Nenhum dado deve ser encapsulado no campo PKCS7 SignedData.
type: docs
weight: 5190
url: /pt/net/aspose.pdf.forms/pkcs7detached/
---
## Classe PKCS7Detached

Representa o objeto PKCS#7 que está em conformidade com a especificação PKCS#7 no RFC 2315 da Internet, PKCS #7: Sintaxe de Mensagem Criptográfica, Versão 1.5. O resumo da mensagem assinada original sobre o intervalo de bytes do documento é incorporado como o campo normal PKCS#7 SignedData. Nenhum dado deve ser encapsulado no campo PKCS#7 SignedData.

```csharp
public sealed class PKCS7Detached : Signature
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [PKCS7Detached](pkcs7detached/#constructor)() | Inicializa uma nova instância da classe `PKCS7Detached`. |
| [PKCS7Detached](pkcs7detached/#constructor_1)(DigestHashAlgorithm) | Inicializa uma nova instância da classe `PKCS7Detached`. |
| [PKCS7Detached](pkcs7detached/#constructor_2)(Stream) | Inicializa uma nova instância da classe `PKCS7Detached`. |
| [PKCS7Detached](pkcs7detached/#constructor_3)(Stream, DigestHashAlgorithm) | Inicializa uma nova instância da classe `PKCS7Detached`. |
| [PKCS7Detached](pkcs7detached/#constructor_4)(Stream, string) | Inicializa uma nova instância da classe `PKCS7Detached`. |
| [PKCS7Detached](pkcs7detached/#constructor_6)(string, string) | Inicializa uma nova instância da classe `PKCS7Detached`. |
| [PKCS7Detached](pkcs7detached/#constructor_5)(Stream, string, DigestHashAlgorithm) | Inicializa uma nova instância da classe `PKCS7Detached`. |
| [PKCS7Detached](pkcs7detached/#constructor_7)(string, string, DigestHashAlgorithm) | Inicializa uma nova instância da classe `PKCS7Detached`. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [Authority](../../aspose.pdf.forms/signature/authority/) { get; set; } | O nome da pessoa ou autoridade que assina o documento. |
| [AvoidEstimatingSignatureLength](../../aspose.pdf.forms/signature/avoidestimatingsignaturelength/) { get; set; } | Obtém e define uma opção que indica se deve evitar estimar o comprimento de uma assinatura. |
| [ByteRange](../../aspose.pdf.forms/signature/byterange/) { get; } | Um array de pares de inteiros (offset de byte inicial, comprimento em bytes) que deve descrever o intervalo exato de bytes para o cálculo do resumo. |
| [ContactInfo](../../aspose.pdf.forms/signature/contactinfo/) { get; set; } | Informações fornecidas pelo signatário para permitir que um destinatário entre em contato com o signatário para verificar a assinatura, por exemplo, um número de telefone. |
| [CustomAppearance](../../aspose.pdf.forms/signature/customappearance/) { get; set; } | Obtém/define a aparência personalizada. |
| [CustomSignHash](../../aspose.pdf.forms/signature/customsignhash/) { get; set; } | O delegado para assinar o hash do documento de forma personalizada. |
| [Date](../../aspose.pdf.forms/signature/date/) { get; set; } | O momento da assinatura. |
| [DefaultSignatureLength](../../aspose.pdf.forms/signature/defaultsignaturelength/) { get; set; } | Obtém ou define o comprimento padrão para os dados da assinatura em bytes. |
| [Location](../../aspose.pdf.forms/signature/location/) { get; set; } | O nome do host da CPU ou a localização física da assinatura. |
| [OcspSettings](../../aspose.pdf.forms/signature/ocspsettings/) { get; set; } | Obtém/define as configurações do ocsp. |
| [Reason](../../aspose.pdf.forms/signature/reason/) { get; set; } | O motivo da assinatura, como (Eu concordo, Pip B.). |
| [ShowProperties](../../aspose.pdf.forms/signature/showproperties/) { get; set; } | Força a exibição/ocultação das propriedades da assinatura. Caso ShowProperties seja verdadeiro, o campo de assinatura tem um formato de aparência predefinido (strings para representar): ------------------------------------------- Assinado digitalmente por {certificate subject} Data: {signature.Date} Motivo: {signature.Reason} Localização: {signature.Location} ------------------------------------------- onde {X} é um espaço reservado para o valor X. Além disso, a assinatura pode ter uma imagem; neste caso, as strings listadas são colocadas sobre a imagem. ShowProperties é verdadeiro por padrão. |
| [TimestampSettings](../../aspose.pdf.forms/signature/timestampsettings/) { get; set; } | Obtém/define as configurações de timestamp. |
| [UseLtv](../../aspose.pdf.forms/signature/useltv/) { get; set; } | Obtém/define a flag de validação ltv. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [GetSignatureAlgorithmInfo](../../aspose.pdf.forms/signature/getsignaturealgorithminfo/)() | Recupera informações sobre o algoritmo de assinatura usado na assinatura. |
| [Verify](../../aspose.pdf.forms/signature/verify/)() | Verifica o documento em relação a esta assinatura e retorna verdadeiro se o documento for válido ou falso caso contrário. |
| [Verify](../../aspose.pdf.forms/signature/verify/)(ValidationOptions, out ValidationResult) | Verifica o documento em relação a esta assinatura e retorna verdadeiro se o documento for válido ou falso caso contrário. |

### Veja Também

* classe [Signature](../signature/)
* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)