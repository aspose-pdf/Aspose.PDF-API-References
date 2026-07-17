---
title: Aspose::Pdf::Forms::Signature::Signature constructor
linktitle: Signature
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Forms::Signature::Signature constructor. Inititalizes new instance of the Signature class in C++.'
type: docs
weight: 100
url: /cpp/aspose.pdf.forms/signature/signature/
---
## Signature::Signature() constructor


Inititalizes new instance of the [Signature](../) class.

```cpp
Aspose::Pdf::Forms::Signature::Signature()
```

## See Also

* Class [Signature](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## Signature::Signature(const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&) constructor


Inititalizes new instance of the [Signature](../) class.

```cpp
Aspose::Pdf::Forms::Signature::Signature(const System::SharedPtr<System::IO::Stream> &pfx, const System::String &password)
```


| Parameter | Type | Description |
| --- | --- | --- |
| pfx | const System::SharedPtr\<System::IO::Stream\>\& | Stream with certificate data organized as pfx. |
| password | const System::String\& | Password to get access to the private key in the certificate. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Class [Signature](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## Signature::Signature(const System::String\&, const System::String\&) constructor


Inititalizes new instance of the [Signature](../) class.

```cpp
Aspose::Pdf::Forms::Signature::Signature(const System::String &pfx, const System::String &password)
```


| Parameter | Type | Description |
| --- | --- | --- |
| pfx | const System::String\& | Pfx file which contains certificate for signing. |
| password | const System::String\& | Password to get access to the private key in the certificate. |

## See Also

* Class [String](../../../system/string/)
* Class [Signature](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
