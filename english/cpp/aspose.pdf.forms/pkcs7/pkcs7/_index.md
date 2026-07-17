---
title: Aspose::Pdf::Forms::PKCS7::PKCS7 constructor
linktitle: PKCS7
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Forms::PKCS7::PKCS7 constructor. Initializes new instance of the PKCS7 class in C++.'
type: docs
weight: 100
url: /cpp/aspose.pdf.forms/pkcs7/pkcs7/
---
## PKCS7::PKCS7() constructor


Initializes new instance of the [PKCS7](../) class.

```cpp
Aspose::Pdf::Forms::PKCS7::PKCS7()
```

## See Also

* Class [PKCS7](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## PKCS7::PKCS7(const System::SharedPtr\<Aspose::Pdf::TimestampSettings\>\&) constructor


Inititalizes new instance of the [PKCS7](../) class.

```cpp
Aspose::Pdf::Forms::PKCS7::PKCS7(const System::SharedPtr<Aspose::Pdf::TimestampSettings> &timestampSettings)
```


| Parameter | Type | Description |
| --- | --- | --- |
| timestampSettings | const System::SharedPtr\<Aspose::Pdf::TimestampSettings\>\& | The timestamp settings for the signature. |
## Remarks



The timestamp settings are used to create the timestamp signature without the need to provide a certificate. You can set the timestamp for a document as a separate signature. 
## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [TimestampSettings](../../../aspose.pdf/timestampsettings/)
* Class [PKCS7](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## PKCS7::PKCS7(const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&) constructor


Initializes new instance of the [PKCS7](../) class.

```cpp
Aspose::Pdf::Forms::PKCS7::PKCS7(const System::SharedPtr<System::IO::Stream> &pfx, const System::String &password)
```


| Parameter | Type | Description |
| --- | --- | --- |
| pfx | const System::SharedPtr\<System::IO::Stream\>\& | Stream with certificate data organized as pfx. |
| password | const System::String\& | Password to get access to the private key in the certificate. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Class [PKCS7](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## PKCS7::PKCS7(const System::String\&, const System::String\&) constructor


Initializes new instance of the [PKCS7](../) class.

```cpp
Aspose::Pdf::Forms::PKCS7::PKCS7(const System::String &pfx, const System::String &password)
```


| Parameter | Type | Description |
| --- | --- | --- |
| pfx | const System::String\& | Pfx file which contains certificate for signing. |
| password | const System::String\& | Password for certificate. |
## Remarks



Password to get access to the private key in the certificate. 
## See Also

* Class [String](../../../system/string/)
* Class [PKCS7](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
