---
title: Aspose::Pdf::Document::Encrypt method
linktitle: Encrypt
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Document::Encrypt method. Encrypts the document. Call then Save to get encrypted version of the document in C++.'
type: docs
weight: 9500
url: /cpp/aspose.pdf/document/encrypt/
---
## Document::Encrypt(System::String, System::String, System::SharedPtr\<Facades::DocumentPrivilege\>, Aspose::Pdf::CryptoAlgorithm, bool) method


Encrypts the document. Call then Save to get encrypted version of the document.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::Document::Encrypt(System::String userPassword, System::String ownerPassword, System::SharedPtr<Facades::DocumentPrivilege> privileges, Aspose::Pdf::CryptoAlgorithm cryptoAlgorithm, bool usePdf20)
```


| Parameter | Type | Description |
| --- | --- | --- |
| userPassword | System::String | User password. |
| ownerPassword | System::String | Owner password. |
| privileges | System::SharedPtr\<Facades::DocumentPrivilege\> | [Document](../) permissions, see [Permissions](../../permissions/) for details. |
| cryptoAlgorithm | Aspose::Pdf::CryptoAlgorithm | Cryptographic algorithm, see [CryptoAlgorithm](../../cryptoalgorithm/) for details. |
| usePdf20 | bool | Support for revision 6 (Extension 8). |
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
      <parametername>privileges</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="class_aspose_1_1_pdf_1_1_document" kindref="compound">Document</ref> permissions, see <ref refid="namespace_aspose_1_1_pdf_1acbb404dc8d3b328891faa5fba341ce0c" kindref="member">Permissions</ref> for details.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>cryptoAlgorithm</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Cryptographic algorithm, see <ref refid="namespace_aspose_1_1_pdf_1ae15d4d8afe86aae14972a6e493d19f66" kindref="member">CryptoAlgorithm</ref> for details.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>usePdf20</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Support for revision 6 (Extension 8).</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [DocumentPrivilege](../../../aspose.pdf.facades/documentprivilege/)
* Enum [CryptoAlgorithm](../../cryptoalgorithm/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Encrypt(System::String, System::String, Aspose::Pdf::Permissions, Aspose::Pdf::CryptoAlgorithm) method


Encrypts the document. Call then Save to get encrypted version of the document.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::Document::Encrypt(System::String userPassword, System::String ownerPassword, Aspose::Pdf::Permissions permissions, Aspose::Pdf::CryptoAlgorithm cryptoAlgorithm)
```


| Parameter | Type | Description |
| --- | --- | --- |
| userPassword | System::String | User password. |
| ownerPassword | System::String | Owner password. |
| permissions | Aspose::Pdf::Permissions | [Document](../) permissions, see [Permissions](../../permissions/) for details. |
| cryptoAlgorithm | Aspose::Pdf::CryptoAlgorithm | Cryptographic algorithm, see [CryptoAlgorithm](../../cryptoalgorithm/) for details. |
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
      <parametername>permissions</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="class_aspose_1_1_pdf_1_1_document" kindref="compound">Document</ref> permissions, see <ref refid="namespace_aspose_1_1_pdf_1acbb404dc8d3b328891faa5fba341ce0c" kindref="member">Permissions</ref> for details.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>cryptoAlgorithm</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Cryptographic algorithm, see <ref refid="namespace_aspose_1_1_pdf_1ae15d4d8afe86aae14972a6e493d19f66" kindref="member">CryptoAlgorithm</ref> for details.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Enum [Permissions](../../permissions/)
* Enum [CryptoAlgorithm](../../cryptoalgorithm/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Encrypt(System::String, System::String, Aspose::Pdf::Permissions, Aspose::Pdf::CryptoAlgorithm, bool) method


Encrypts the document. Call then Save to get encrypted version of the document.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::Document::Encrypt(System::String userPassword, System::String ownerPassword, Aspose::Pdf::Permissions permissions, Aspose::Pdf::CryptoAlgorithm cryptoAlgorithm, bool usePdf20)
```


| Parameter | Type | Description |
| --- | --- | --- |
| userPassword | System::String | User password. |
| ownerPassword | System::String | Owner password. |
| permissions | Aspose::Pdf::Permissions | [Document](../) permissions, see [Permissions](../../permissions/) for details. |
| cryptoAlgorithm | Aspose::Pdf::CryptoAlgorithm | Cryptographic algorithm, see [CryptoAlgorithm](../../cryptoalgorithm/) for details. |
| usePdf20 | bool | Support for revision 6 (Extension 8). |
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
      <parametername>permissions</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="class_aspose_1_1_pdf_1_1_document" kindref="compound">Document</ref> permissions, see <ref refid="namespace_aspose_1_1_pdf_1acbb404dc8d3b328891faa5fba341ce0c" kindref="member">Permissions</ref> for details.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>cryptoAlgorithm</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Cryptographic algorithm, see <ref refid="namespace_aspose_1_1_pdf_1ae15d4d8afe86aae14972a6e493d19f66" kindref="member">CryptoAlgorithm</ref> for details.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>usePdf20</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Support for revision 6 (Extension 8).</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Enum [Permissions](../../permissions/)
* Enum [CryptoAlgorithm](../../cryptoalgorithm/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
