---
title: "PdfFileSignature"
second_title: "Aspose.PDF para Python via .NET Referência da API"
description: "Representa uma classe para assinar um arquivo pdf com um certificado."
type: docs
weight: 310
url: /pt/python-net/aspose.pdf.facades/pdffilesignature/
---

## PdfFileSignature class

Representa uma classe para assinar um arquivo pdf com um certificado.

O tipo PdfFileSignature expõe os seguintes membros:
## Construtores
| Nome | Descrição |
| :- | :- |
| PdfFileSignature() | O construtor da classe PdfFileSignature. |
| PdfFileSignature(input_file) | Inicializa uma nova instância da classe PdfFileSignature |
| PdfFileSignature(input_file, output_file) | Inicializa uma nova instância da classe PdfFileSignature |
| PdfFileSignature(document) | Inicializa uma nova instância da classe PdfFileSignature |
| PdfFileSignature(document, output_file) | Inicializa uma nova instância da classe PdfFileSignature |
## Propriedades
| Nome | Descrição |
| :- | :- |
| document | Obtém a fachada do documento em que está trabalhando. |
| signature_appearance | Define ou obtém a aparência gráfica da assinatura. O valor da propriedade representa o nome do arquivo de imagem. |
| is_ltv_enabled | Obtém o sinalizador LTV habilitado. |
| is_certified | Obtém o sinalizador que determina se um documento está certificado ou não. |
| signature_appearance_stream | Define ou obtém a aparência gráfica da assinatura. O valor da propriedade representa o fluxo de imagem. |
## Métodos
| Nome | Descrição |
| :- | :- |
| bind_pdf(input_file) | Vincula um arquivo Pdf para edição. |
| bind_pdf(input_stream) | Vincula um fluxo Pdf para edição. |
| bind_pdf(src_doc) | Vincula o documento PDF para edição. |
| save(output_file) | Salva o PDF resultante em um arquivo. |
| save(output_stream) | Salva o PDF resultante em um fluxo. |
| save() | Salva o PDF resultante em um arquivo. |
| sign(page, sig_reason, sig_contact, sig_location, visible, annot_rect) | Faça uma assinatura no documento pdf. |
| sign(page, sig_reason, sig_contact, sig_location, visible, annot_rect, sig) | Assine o documento com a assinatura do tipo fornecido. |
| sign(page, visible, annot_rect, sig) | Assine o documento com a assinatura do tipo fornecido. |
| sign(sig_name, sig_reason, sig_contact, sig_location, sig) | Assine o documento com a assinatura do tipo fornecido. |
| sign(page, sig_name, sig_reason, sig_contact, sig_location, visible, annot_rect, sig) | Assine o documento com a assinatura do tipo fornecido. |
| sign(sig_name, sig) | Assine o documento com a assinatura do tipo fornecido. |
| certify(page, sig_reason, sig_contact, sig_location, visible, annot_rect, doc_mdp_signature) | Certifique o documento com a assinatura MDP.<br/>            Dados como motivo da assinatura, contato e localização devem ser fornecidos pelas propriedades correspondentes do objeto Signature sig. |
| certify(sig_name, doc_mdp_signature) | Certifique o documento com a assinatura MDP.<br/>            Dados como motivo da assinatura, contato e localização devem ser fornecidos pelas propriedades correspondentes do objeto Signature sig. |
| remove_signature(sign_name) | Remova a assinatura de acordo com o nome da assinatura. |
| remove_signature(sign_name, remove_field) | Remove a assinatura de acordo com o nome da assinatura. |
| close() | Fecha a fachada. |
| get_access_permissions() | Retorna o valor das permissões de acesso do documento certificado pelo tipo de assinatura MDP. |
| get_sign_names(only_active) | Obtém os nomes de todas as assinaturas não vazias. |
| get_blank_sign_names() | Obtém os nomes de todos os campos de assinatura vazios. |
| is_contain_signature() | Verifica se o pdf tem uma assinatura digital ou não. |
| contains_signature() | Verifica se o pdf tem uma assinatura digital ou não. |
| contains_usage_rights() | Verifica se o PDF tem direitos de uso ou não. |
| is_covers_whole_document(sign_name) | Verifica se a assinatura cobre todo o documento. |
| covers_whole_document(sign_name) | Verifica se a assinatura cobre todo o documento. |
| get_revision(sign_name) | Obtém a revisão de uma assinatura. |
| get_total_revision() | Obtém a revisão total. |
| remove_usage_rights() | Remove a entrada de direitos de uso. |
| verify_signed(sign_name) | Verifica a validade de uma assinatura. |
| get_signer_name(sign_name) | Obtém o nome da pessoa ou organização que assina o documento PDF. |
| get_date_time(sign_name) | Obtém a data e hora da assinatura. |
| get_reason(sign_name) | Obtém o motivo de uma assinatura. |
| get_location(sign_name) | Obtém a localização de uma assinatura. |
| get_contact_info(sign_name) | Obtém as informações de contato de uma assinatura. |
| verify_signature(sign_name) | Verifica a validade de uma assinatura. |
| extract_image(sign_name) | Extrai a imagem da assinatura. |
| extract_certificate(sign_name) | Extrai o único certificado X.509 da assinatura como um fluxo. |
| set_certificate(pfx, pass) | Define o arquivo de certificado e a senha para a rotina de assinatura. |

### Veja Também

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

