---
title: PdfFileSignature
second_title: Aspose.PDF for Python via .NET API Reference
description: Represents a class to sign a pdf file with a certificate.
type: docs
weight: 310
url: /python-net/aspose.pdf.facades/pdffilesignature/
---

## PdfFileSignature class

Represents a class to sign a pdf file with a certificate.

The PdfFileSignature type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|PdfFileSignature()|The constructor of PdfFileSignature class.|
|PdfFileSignature(input_file)|Initializes a new instance of the PdfFileSignature class|
|PdfFileSignature(input_file, output_file)|Initializes a new instance of the PdfFileSignature class|
|PdfFileSignature(document)|Initializes a new instance of the PdfFileSignature class|
|PdfFileSignature(document, output_file)|Initializes a new instance of the PdfFileSignature class|
## Properties
| Name | Description |
| :- | :- |
|document|Gets the document facade is working on.|
|signature_appearance|Sets or gets a graphic appearance for the signature. Property value represents image file name.|
|is_ltv_enabled|Gets the LTV enabled flag.|
|is_certified|Gets the flag determining whether a document is certified or not.|
|signature_appearance_stream|Sets or gets a graphic appearance for the signature. Property value represents image stream.|
## Methods
| Name | Description |
| :- | :- |
|bind_pdf(input_file)|Binds a Pdf file for editing.|
|bind_pdf(input_stream)|Binds a Pdf stream for editing.|
|bind_pdf(src_doc)|Binds PDF document for editing.|
|save(output_file)|Saves the result PDF to file.|
|save(output_stream)|Saves the result PDF to stream.|
|save()|Saves the result PDF to file.|
|sign(page, sig_reason, sig_contact, sig_location, visible, annot_rect)|Make a signature on the pdf document.|
|sign(page, sig_reason, sig_contact, sig_location, visible, annot_rect, sig)|Sign the document with the given type signature.|
|sign(page, visible, annot_rect, sig)|Sign the document with the given type signature.|
|sign(sig_name, sig_reason, sig_contact, sig_location, sig)|Sign the document with the given type signature.|
|sign(page, sig_name, sig_reason, sig_contact, sig_location, visible, annot_rect, sig)|Sign the document with the given type signature.|
|sign(sig_name, sig)|Sign the document with the given type signature.|
|certify(page, sig_reason, sig_contact, sig_location, visible, annot_rect, doc_mdp_signature)|Certify the document with the MDP signature.<br/>            Such data as signature reason, contact and location must be provided by corresponding properties of the Signature object sig.|
|certify(sig_name, doc_mdp_signature)|Certify the document with the MDP signature.<br/>            Such data as signature reason, contact and location must be provided by corresponding properties of the Signature object sig.|
|remove_signature(sign_name)|Remove the signature according to the name of the signature.|
|remove_signature(sign_name, remove_field)|Removes the signature according to the name of the signature.|
|close()|Closes the facade.|
|get_access_permissions()|Returns the access permissions value of certified document by the MDP signature type.|
|get_sign_names(only_active)|Gets the names of all not empty signatures.|
|get_blank_sign_names()|Gets the names of all empty signature fields.|
|is_contain_signature()|Checks if the pdf  has a digital signature or not.|
|contains_signature()|Checks if the pdf  has a digital signature or not.|
|contains_usage_rights()|Checks if the pdf has a usage rights or not.|
|is_covers_whole_document(sign_name)|Checks if the signature covers the whole document.|
|covers_whole_document(sign_name)|Checks if the signature covers the whole document.|
|get_revision(sign_name)|Gets the revision of a signature.|
|get_total_revision()|Gets the toltal revision.|
|remove_usage_rights()|Removes the usage rights entry.|
|verify_signed(sign_name)|Checks the validity of a signature.|
|get_signer_name(sign_name)|Gets the name of person or organization who signing the pdf document.|
|get_date_time(sign_name)|Gets the signature's datetime.|
|get_reason(sign_name)|Gets the reason of a signature.|
|get_location(sign_name)|Gets the location of a signature.|
|get_contact_info(sign_name)|Gets the contact information of a signature.|
|verify_signature(sign_name)|Checks the validity of a signature.|
|extract_image(sign_name)|Extracts signature's image.|
|extract_certificate(sign_name)|Extracts signature's single X.509 certificate as a stream.|
|set_certificate(pfx, pass)|Set certificate file and password for signing routine.|

### See Also

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

