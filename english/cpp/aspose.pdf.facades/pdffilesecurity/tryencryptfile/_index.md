---
title: Aspose::Pdf::Facades::PdfFileSecurity::TryEncryptFile method
linktitle: TryEncryptFile
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfFileSecurity::TryEncryptFile method. Encrypts Pdf file with userpassword and ownerpassword and sets the document''s privileges to access. The user password and the owner password can be null or empty. The owner password will be replaced with a random string if the input owner password is null or empty. Does not throw an exception if process failed in C++.'
type: docs
weight: 1000
url: /cpp/aspose.pdf.facades/pdffilesecurity/tryencryptfile/
---
## PdfFileSecurity::TryEncryptFile method


Encrypts [Pdf](../../../aspose.pdf/) file with userpassword and ownerpassword and sets the document's privileges to access. The user password and the owner password can be null or empty. The owner password will be replaced with a random string if the input owner password is null or empty. Does not throw an exception if process failed.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Facades::PdfFileSecurity::TryEncryptFile(System::String userPassword, System::String ownerPassword, System::SharedPtr<DocumentPrivilege> privilege, KeySize keySize)
```


| Parameter | Type | Description |
| --- | --- | --- |
| userPassword | System::String | User password. |
| ownerPassword | System::String | Owner password. |
| privilege | System::SharedPtr\<DocumentPrivilege\> | Set privilege. |
| keySize | KeySize | [KeySize.x40](../../keysize/) for 40 bits encryption, [KeySize.x128](../../keysize/) for 128 bits encryption and [KeySize.x256](../../keysize/) for 256 bits encryption. |

### ReturnValue

True for success, or false.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>userPassword</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>User password.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>ownerPassword</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Owner password.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>privilege</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Set privilege.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>keySize</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="namespace_aspose_1_1_pdf_1_1_facades_1ab61025f7d780f3d09ad4dfa4e72a8616afaa8d77797bccc851ba9150df4da8eef" kindref="member">KeySize.x40</ref> for 40 bits encryption, <ref refid="namespace_aspose_1_1_pdf_1_1_facades_1ab61025f7d780f3d09ad4dfa4e72a8616a8c00ad18d377660cdc22d0c40a9c63f9" kindref="member">KeySize.x128</ref> for 128 bits encryption and <ref refid="namespace_aspose_1_1_pdf_1_1_facades_1ab61025f7d780f3d09ad4dfa4e72a8616a4074f9625c94fbcf7a68ecc1745274ce" kindref="member">KeySize.x256</ref> for 256 bits encryption.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [DocumentPrivilege](../../documentprivilege/)
* Enum [KeySize](../../keysize/)
* Class [PdfFileSecurity](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
