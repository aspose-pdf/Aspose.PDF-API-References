---
title: Aspose::Pdf::Forms::SignatureField::Sign method
linktitle: Sign
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Forms::SignatureField::Sign method. Signs the document using this signature field in C++.'
type: docs
weight: 200
url: /cpp/aspose.pdf.forms/signaturefield/sign/
---
## SignatureField::Sign(System::SharedPtr\<Aspose::Pdf::Forms::Signature\>, System::SharedPtr\<System::IO::Stream\>, System::String) method


Signs the document using this signature field.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::Forms::SignatureField::Sign(System::SharedPtr<Aspose::Pdf::Forms::Signature> signature, System::SharedPtr<System::IO::Stream> pfx, System::String pass)
```


| Parameter | Type | Description |
| --- | --- | --- |
| signature | System::SharedPtr\<Aspose::Pdf::Forms::Signature\> | [Signature](../../signature/) object, see [PKCS1](../../pkcs1/), [PKCS7](../../pkcs7/), [PKCS7Detached](../../pkcs7detached/). |
| pfx | System::SharedPtr\<System::IO::Stream\> | Stream with certificate. |
| pass | System::String | Password to access private in the *pfx* . |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>signature</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="class_aspose_1_1_pdf_1_1_forms_1_1_signature" kindref="compound">Signature</ref> object, see <ref refid="class_aspose_1_1_pdf_1_1_forms_1_1_p_k_c_s1" kindref="compound">PKCS1</ref>, <ref refid="class_aspose_1_1_pdf_1_1_forms_1_1_p_k_c_s7" kindref="compound">PKCS7</ref>, <ref refid="class_aspose_1_1_pdf_1_1_forms_1_1_p_k_c_s7_detached" kindref="compound">PKCS7Detached</ref>. </para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>pfx</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Stream with certificate. </para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>pass</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Password to access private in the <emphasis>pfx</emphasis> . </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Signature](../../signature/)
* Class [SignatureField](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## SignatureField::Sign(System::SharedPtr\<Aspose::Pdf::Forms::Signature\>) method


Sign the document using this signature field.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::Forms::SignatureField::Sign(System::SharedPtr<Aspose::Pdf::Forms::Signature> signature)
```


| Parameter | Type | Description |
| --- | --- | --- |
| signature | System::SharedPtr\<Aspose::Pdf::Forms::Signature\> | [Signature](../../signature/) object, see [PKCS1](../../pkcs1/), [PKCS7](../../pkcs7/) and [PKCS7Detached](../../pkcs7detached/). |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>signature</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="class_aspose_1_1_pdf_1_1_forms_1_1_signature" kindref="compound">Signature</ref> object, see <ref refid="class_aspose_1_1_pdf_1_1_forms_1_1_p_k_c_s1" kindref="compound">PKCS1</ref>, <ref refid="class_aspose_1_1_pdf_1_1_forms_1_1_p_k_c_s7" kindref="compound">PKCS7</ref> and <ref refid="class_aspose_1_1_pdf_1_1_forms_1_1_p_k_c_s7_detached" kindref="compound">PKCS7Detached</ref>.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Signature](../../signature/)
* Class [SignatureField](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
