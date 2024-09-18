---
title: Aspose::Pdf::Facades::PdfFileSecurity::SetPrivilege method
linktitle: SetPrivilege
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfFileSecurity::SetPrivilege method. Sets Pdf file security with empty user/owner passwords. The owner password will be added by a random string. Throws an exception if process failed in C++.'
type: docs
weight: 1300
url: /cpp/aspose.pdf.facades/pdffilesecurity/setprivilege/
---
## PdfFileSecurity::SetPrivilege(System::SharedPtr\<DocumentPrivilege\>) method


Sets [Pdf](../../../aspose.pdf/) file security with empty user/owner passwords. The owner password will be added by a random string. Throws an exception if process failed.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Facades::PdfFileSecurity::SetPrivilege(System::SharedPtr<DocumentPrivilege> privilege)
```


| Parameter | Type | Description |
| --- | --- | --- |
| privilege | System::SharedPtr\<DocumentPrivilege\> | Set privilege. |

### ReturnValue

True for success.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>privilege</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Set privilege.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [DocumentPrivilege](../../documentprivilege/)
* Class [PdfFileSecurity](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileSecurity::SetPrivilege(System::String, System::String, System::SharedPtr\<DocumentPrivilege\>) method


Sets [Pdf](../../../aspose.pdf/) file security with original password. Throws an exception if process failed.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Facades::PdfFileSecurity::SetPrivilege(System::String userPassword, System::String ownerPassword, System::SharedPtr<DocumentPrivilege> privilege)
```


| Parameter | Type | Description |
| --- | --- | --- |
| userPassword | System::String | Original user password. |
| ownerPassword | System::String | Original owner password. |
| privilege | System::SharedPtr\<DocumentPrivilege\> | Set privilege. |

### ReturnValue

True for success.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>userPassword</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Original user password.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>ownerPassword</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Original owner password.</para>
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
</parameterlist>
## See Also

* Class [DocumentPrivilege](../../documentprivilege/)
* Class [PdfFileSecurity](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
