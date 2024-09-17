---
title: Aspose::Pdf::Facades::PdfFileSecurity::MfEncryptFile method
linktitle: MfEncryptFile
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfFileSecurity::MfEncryptFile method. Encrypts Pdf file with userpassword and ownerpassword and sets the document''s privileges to access. The user password and the owner password can be null or empty. The owner password will be replaced with a random string if the input owner password is null or empty. Throws exception if process failed in C++.'
type: docs
weight: 900
url: /cpp/aspose.pdf.facades/pdffilesecurity/mfencryptfile/
---
## PdfFileSecurity::MfEncryptFile(System::String, System::String, System::SharedPtr\<DocumentPrivilege\>, KeySize) method


Encrypts [Pdf](../../../aspose.pdf/) file with userpassword and ownerpassword and sets the document's privileges to access. The user password and the owner password can be null or empty. The owner password will be replaced with a random string if the input owner password is null or empty. Throws exception if process failed.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Facades::PdfFileSecurity::MfEncryptFile(System::String userPassword, System::String ownerPassword, System::SharedPtr<DocumentPrivilege> privilege, KeySize keySize)
```


| Parameter | Type | Description |
| --- | --- | --- |
| userPassword | System::String | User password. |
| ownerPassword | System::String | Owner password. |
| privilege | System::SharedPtr\<DocumentPrivilege\> | Set privilege. |
| keySize | KeySize | [KeySize.x40](../../keysize/) for 40 bits encryption, [KeySize.x128](../../keysize/) for 128 bits encryption and [KeySize.x256](../../keysize/) for 256 bits encryption. |

### ReturnValue

True for success.
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
## PdfFileSecurity::MfEncryptFile(System::String, System::String, System::SharedPtr\<DocumentPrivilege\>, KeySize, Algorithm) method


Encrypts [Pdf](../../../aspose.pdf/) file with userpassword and ownerpassword and sets the document's privileges to access. The user password and the owner password can be null or empty. The owner password will be replaced with a random string if the input owner password is null or empty. There are 6 possible combinations of KeySize and Algorithm values. However ([KeySize.x40](../../keysize/), [Algorithm.AES](../../algorithm/)) and ([KeySize.x256](../../keysize/), [Algorithm.RC4](../../algorithm/)) are invalid and corresponding exception will be raised if kit encounters this combination. Throws an exception if process failed.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Facades::PdfFileSecurity::MfEncryptFile(System::String userPassword, System::String ownerPassword, System::SharedPtr<DocumentPrivilege> privilege, KeySize keySize, Algorithm cipher)
```


| Parameter | Type | Description |
| --- | --- | --- |
| userPassword | System::String | User password. |
| ownerPassword | System::String | Owner password. |
| privilege | System::SharedPtr\<DocumentPrivilege\> | Set privilege. |
| keySize | KeySize | [KeySize.x40](../../keysize/) for 40 bits encryption, [KeySize.x128](../../keysize/) for 128 bits encryption and [KeySize.x256](../../keysize/) for 256 bits encryption. |
| cipher | Algorithm | [Algorithm.AES](../../algorithm/) to encrypt using AES algorithm or [Algorithm.RC4](../../algorithm/) for RC4 encryption. |

### ReturnValue

True for success.
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
  <parameteritem>
    <parameternamelist>
      <parametername>cipher</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="namespace_aspose_1_1_pdf_1_1_facades_1ab57782da8f2b93e1c26c19139ee84010a76b7593457e2ab50befe2dcd63cf388f" kindref="member">Algorithm.AES</ref> to encrypt using AES algorithm or <ref refid="namespace_aspose_1_1_pdf_1_1_facades_1ab57782da8f2b93e1c26c19139ee84010a995371a4f7f429535f3d9d61fc64f6b6" kindref="member">Algorithm.RC4</ref> for RC4 encryption.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [DocumentPrivilege](../../documentprivilege/)
* Enum [KeySize](../../keysize/)
* Enum [Algorithm](../../algorithm/)
* Class [PdfFileSecurity](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
