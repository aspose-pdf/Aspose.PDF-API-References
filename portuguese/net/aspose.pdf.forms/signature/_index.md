---
title: Class Signature
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Forms.Signature. Uma classe abstrata que representa o objeto de assinatura no documento pdf. Assinaturas são campos com valores de objetos de assinatura, os últimos contêm dados que são usados para verificar a validade do documento.
type: docs
weight: 5270
url: /pt/net/aspose.pdf.forms/signature/
---
## Classe Assinatura

Uma classe abstrata que representa o objeto de assinatura no documento pdf. Assinaturas são campos com valores de objetos de assinatura, os últimos contêm dados que são usados para verificar a validade do documento.

```csharp
public abstract class Signature
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [Signature](signature/#constructor)() | Inicializa uma nova instância da classe `Signature`. |
| [Signature](signature/#constructor_1)(Stream, string) | Inicializa uma nova instância da classe `Signature`. |
| [Signature](signature/#constructor_2)(string, string) | Inicializa uma nova instância da classe `Signature`. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [Authority](../../aspose.pdf.forms/signature/authority/) { get; set; } | O nome da pessoa ou autoridade que assina o documento. |
| [AvoidEstimatingSignatureLength](../../aspose.pdf.forms/signature/avoidestimatingsignaturelength/) { get; set; } | Obtém e define uma opção que indica se deve evitar estimar o comprimento de uma assinatura. |
| [ByteRange](../../aspose.pdf.forms/signature/byterange/) { get; } | Um array de pares de inteiros (offset de byte inicial, comprimento em bytes) que descrevem o intervalo exato de bytes para o cálculo do resumo. |
| [ContactInfo](../../aspose.pdf.forms/signature/contactinfo/) { get; set; } | Informações fornecidas pelo signatário para permitir que um destinatário entre em contato com o signatário para verificar a assinatura, por exemplo, um número de telefone. |
| [CustomAppearance](../../aspose.pdf.forms/signature/customappearance/) { get; set; } | Obtém/define a aparência personalizada. |
| [CustomSignHash](../../aspose.pdf.forms/signature/customsignhash/) { get; set; } | O delegado para assinar o hash do documento de forma personalizada. |
| [Date](../../aspose.pdf.forms/signature/date/) { get; set; } | O momento da assinatura. |
| [DefaultSignatureLength](../../aspose.pdf.forms/signature/defaultsignaturelength/) { get; set; } | Obtém ou define o comprimento padrão para os dados da assinatura em bytes. |
| [Location](../../aspose.pdf.forms/signature/location/) { get; set; } | O nome do host da CPU ou a localização física da assinatura. |
| [OcspSettings](../../aspose.pdf.forms/signature/ocspsettings/) { get; set; } | Obtém/define as configurações ocsp. |
| [Reason](../../aspose.pdf.forms/signature/reason/) { get; set; } | O motivo da assinatura, como (Eu concordo, Pip B.). |
| [ShowProperties](../../aspose.pdf.forms/signature/showproperties/) { get; set; } | Força a mostrar/ocultar propriedades da assinatura. Caso ShowProperties seja verdadeiro, o campo de assinatura tem um formato de aparência predefinido (strings para representar): ------------------------------------------- Assinado digitalmente por {certificate subject} Data: {signature.Date} Motivo: {signature.Reason} Localização: {signature.Location} ------------------------------------------- onde {X} é um espaço reservado para o valor X. Além disso, a assinatura pode ter uma imagem; neste caso, as strings listadas são colocadas sobre a imagem. ShowProperties é verdadeiro por padrão. |
| [TimestampSettings](../../aspose.pdf.forms/signature/timestampsettings/) { get; set; } | Obtém/define as configurações de timestamp. |
| [UseLtv](../../aspose.pdf.forms/signature/useltv/) { get; set; } | Obtém/define a flag de validação ltv. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [GetSignatureAlgorithmInfo](../../aspose.pdf.forms/signature/getsignaturealgorithminfo/)() | Recupera informações sobre o algoritmo de assinatura usado na assinatura. |
| [Verify](../../aspose.pdf.forms/signature/verify/#verify)() | Verifica o documento em relação a esta assinatura e retorna verdadeiro se o documento for válido ou falso caso contrário. |
| [Verify](../../aspose.pdf.forms/signature/verify/#verify_1)(ValidationOptions, out ValidationResult) | Verifica o documento em relação a esta assinatura e retorna verdadeiro se o documento for válido ou falso caso contrário. |

### Veja Também

* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)