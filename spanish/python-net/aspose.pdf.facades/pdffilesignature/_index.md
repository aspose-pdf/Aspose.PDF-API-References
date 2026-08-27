---
title: "PdfFileSignature"
second_title: "Referencia de API de Aspose.PDF para Python vía .NET"
description: "Representa una clase para firmar un archivo pdf con un certificado."
type: docs
weight: 310
url: /es/python-net/aspose.pdf.facades/pdffilesignature/
---

## PdfFileSignature class

Representa una clase para firmar un archivo pdf con un certificado.

El tipo PdfFileSignature expone los siguientes miembros:
## Constructores
| Nombre | Descripción |
| :- | :- |
| PdfFileSignature() | El constructor de la clase PdfFileSignature. |
| PdfFileSignature(input_file) | Inicializa una nueva instancia de la clase PdfFileSignature |
| PdfFileSignature(input_file, output_file) | Inicializa una nueva instancia de la clase PdfFileSignature |
| PdfFileSignature(document) | Inicializa una nueva instancia de la clase PdfFileSignature |
| PdfFileSignature(document, output_file) | Inicializa una nueva instancia de la clase PdfFileSignature |
## Propiedades
| Nombre | Descripción |
| :- | :- |
| document | Obtiene la fachada del documento en la que está trabajando. |
| signature_appearance | Establece o obtiene una apariencia gráfica para la firma. El valor de la propiedad representa el nombre del archivo de imagen. |
| is_ltv_enabled | Obtiene la bandera LTV habilitada. |
| is_certified | Obtiene la bandera que determina si un documento está certificado o no. |
| signature_appearance_stream | Establece o obtiene una apariencia gráfica para la firma. El valor de la propiedad representa el flujo de imagen. |
## Métodos
| Nombre | Descripción |
| :- | :- |
| bind_pdf(input_file) | Vincula un archivo Pdf para editar. |
| bind_pdf(input_stream) | Vincula un flujo Pdf para editar. |
| bind_pdf(src_doc) | Vincula el documento PDF para su edición. |
| save(output_file) | Guarda el PDF resultante en un archivo. |
| save(output_stream) | Guarda el PDF resultante en un flujo. |
| save() | Guarda el PDF resultante en un archivo. |
| sign(page, sig_reason, sig_contact, sig_location, visible, annot_rect) | Crear una firma en el documento pdf. |
| sign(page, sig_reason, sig_contact, sig_location, visible, annot_rect, sig) | Firma el documento con la firma de tipo proporcionada. |
| sign(page, visible, annot_rect, sig) | Firma el documento con la firma de tipo proporcionada. |
| sign(sig_name, sig_reason, sig_contact, sig_location, sig) | Firma el documento con la firma de tipo proporcionada. |
| sign(page, sig_name, sig_reason, sig_contact, sig_location, visible, annot_rect, sig) | Firma el documento con la firma de tipo proporcionada. |
| sign(sig_name, sig) | Firma el documento con la firma de tipo proporcionada. |
| certify(page, sig_reason, sig_contact, sig_location, visible, annot_rect, doc_mdp_signature) | Certificar el documento con la firma MDP.<br/>            Datos como el motivo de la firma, contacto y ubicación deben ser proporcionados por las propiedades correspondientes del objeto Signature sig. |
| certify(sig_name, doc_mdp_signature) | Certificar el documento con la firma MDP.<br/>            Datos como el motivo de la firma, contacto y ubicación deben ser proporcionados por las propiedades correspondientes del objeto Signature sig. |
| remove_signature(sign_name) | Eliminar la firma según el nombre de la firma. |
| remove_signature(sign_name, remove_field) | Elimina la firma según el nombre de la firma. |
| close() | Cierra la fachada. |
| get_access_permissions() | Devuelve el valor de permisos de acceso del documento certificado por el tipo de firma MDP. |
| get_sign_names(only_active) | Obtiene los nombres de todas las firmas no vacías. |
| get_blank_sign_names() | Obtiene los nombres de todos los campos de firma vacíos. |
| is_contain_signature() | Comprueba si el pdf tiene una firma digital o no. |
| contains_signature() | Comprueba si el pdf tiene una firma digital o no. |
| contains_usage_rights() | Comprueba si el pdf tiene derechos de uso o no. |
| is_covers_whole_document(sign_name) | Comprueba si la firma cubre todo el documento. |
| covers_whole_document(sign_name) | Comprueba si la firma cubre todo el documento. |
| get_revision(sign_name) | Obtiene la revisión de una firma. |
| get_total_revision() | Obtiene la revisión total. |
| remove_usage_rights() | Elimina la entrada de derechos de uso. |
| verify_signed(sign_name) | Comprueba la validez de una firma. |
| get_signer_name(sign_name) | Obtiene el nombre de la persona u organización que firma el documento pdf. |
| get_date_time(sign_name) | Obtiene la fecha y hora de la firma. |
| get_reason(sign_name) | Obtiene el motivo de una firma. |
| get_location(sign_name) | Obtiene la ubicación de una firma. |
| get_contact_info(sign_name) | Obtiene la información de contacto de una firma. |
| verify_signature(sign_name) | Comprueba la validez de una firma. |
| extract_image(sign_name) | Extrae la imagen de la firma. |
| extract_certificate(sign_name) | Extrae el único certificado X.509 de la firma como un flujo. |
| set_certificate(pfx, pass) | Establece el archivo de certificado y la contraseña para la rutina de firma. |

### Ver también

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

