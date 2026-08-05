---
title: "ExternalSignature"
second_title: "Aspose.PDF para Python via .NET Referência da API"
description: "Cria uma assinatura PKCS#7Detached destacada usando um X509Certificate2. Suporta cartões inteligentes usb, tokens sem chaves privadas exportáveis."
type: docs
weight: 80
url: /pt/python-net/aspose.pdf.forms/externalsignature/
---

## ExternalSignature class

Cria uma assinatura PKCS#7Detached destacada usando um X509Certificate2. Suporta cartões inteligentes usb, tokens sem chaves privadas exportáveis.

O tipo ExternalSignature expõe os seguintes membros:
## Propriedades
| Nome | Descrição |
| :- | :- |
| custom_appearance | Obtém/define a aparência personalizada. |
| authority | O nome da pessoa ou autoridade que assina o documento. |
| date | O horário da assinatura. |
| location | O nome do host da CPU ou a localização física da assinatura. |
| reason | O motivo da assinatura, como (Concordo…). |
| contact_info | Informações fornecidas pelo assinante para permitir que o destinatário entre em contato com o assinante <br/>            para verificar a assinatura, por exemplo, um número de telefone. |
| byte_range | Um array de pares de inteiros (deslocamento inicial em bytes, comprimento em bytes) <br/>             que descreve o intervalo exato de bytes para o cálculo do digest. |
| timestamp_settings | Obtém/define as configurações de timestamp. |
| ocsp_settings | Obtém/define as configurações de OCSP. |
| use_ltv | Obtém/define a bandeira de validação LTV. |
| show_properties | Força a exibir/ocultar as propriedades da assinatura.<br/>            Caso ShowProperties seja true, o campo de assinatura tem um formato de aparência predefinido (strings para representar):<br/>            -------------------------------------------<br/>            Assinado digitalmente por {certificate subject}<br/>            Data: {signature.Date}<br/>            Motivo: {signature.Reason}<br/>            Local: {signature.Location}<br/>            -------------------------------------------<br/>            onde {X} é um placeholder para o valor X. A assinatura também pode ter imagem; nesse caso as strings listadas são colocadas sobre a imagem.<br/>            ShowProperties é true por padrão. |
## Métodos
| Nome | Descrição |
| :- | :- |
| verify() | Verifica o documento em relação a esta assinatura e retorna true se o documento for válido <br/>            ou false caso contrário. |

### Veja Também

* namespace [aspose.pdf.forms](/pdf/python-net/aspose.pdf.forms/)
* assembly [Aspose.PDF](/pdf/python-net/)

