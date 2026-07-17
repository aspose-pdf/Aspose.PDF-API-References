---
title: Aspose::Pdf::LowCode::TimestampOptions class
linktitle: TimestampOptions
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::LowCode::TimestampOptions class. Options for the Timestamp Low‑Code plugin in C++.'
type: docs
weight: 9100
url: /cpp/aspose.pdf.lowcode/timestampoptions/
---
## TimestampOptions class


Options for the [Timestamp](../timestamp/) Low‑Code plugin.

```cpp
class TimestampOptions : public Aspose::Pdf::LowCode::PdfConverterOptions
```

## Methods

| Method | Description |
| --- | --- |
| [get_BasicAuthCredentials](./get_basicauthcredentials/)() const | Gets the basic authentication credentials, Username and password are combined into a string "username:password". |
| [get_DigestHashAlgorithm](./get_digesthashalgorithm/)() const | Digest hash algorithm to use for the timestamp. Defaults to Sha256. |
| [get_OperationName](./get_operationname/)() override | Returns operation name. |
| [get_PageNumber](./get_pagenumber/)() const | [Page](../../aspose.pdf/page/) number on which the timestamped signature will be applied. |
| [get_Rectangle](./get_rectangle/)() const | [Rectangle](../../aspose.pdf/rectangle/) defining the annotation area (ignored when Visible is false). |
| [get_ServerUrl](./get_serverurl/)() const | URL of the timestamp server. |
| [get_SigContact](./get_sigcontact/)() const | Contact information for the signature. |
| [get_SigLocation](./get_siglocation/)() const | Location for the signature. |
| [get_SigReason](./get_sigreason/)() const | Reason for the signature. |
| [get_Visible](./get_visible/)() const | Visibility flag – false for a pure timestamp (no visible annotation). |
| [set_BasicAuthCredentials](./set_basicauthcredentials/)(const System::String\&) | Sets the basic authentication credentials, Username and password are combined into a string "username:password". |
| [set_DigestHashAlgorithm](./set_digesthashalgorithm/)(Aspose::Pdf::DigestHashAlgorithm) | Digest hash algorithm to use for the timestamp. Defaults to Sha256. |
| [set_PageNumber](./set_pagenumber/)(int32_t) | [Page](../../aspose.pdf/page/) number on which the timestamped signature will be applied. |
| [set_Rectangle](./set_rectangle/)(System::Drawing::Rectangle) | [Rectangle](../../aspose.pdf/rectangle/) defining the annotation area (ignored when Visible is false). |
| [set_ServerUrl](./set_serverurl/)(const System::String\&) | URL of the timestamp server. |
| [set_SigContact](./set_sigcontact/)(const System::String\&) | Contact information for the signature. |
| [set_SigLocation](./set_siglocation/)(const System::String\&) | Location for the signature. |
| [set_SigReason](./set_sigreason/)(const System::String\&) | Reason for the signature. |
| [set_Visible](./set_visible/)(bool) | Visibility flag – false for a pure timestamp (no visible annotation). |
| [TimestampOptions](./timestampoptions/)(const System::String\&, const System::String\&) | Creates a new instance with a PFX file path and password. |
| [TimestampOptions](./timestampoptions/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&) | Creates a new instance with a PFX stream and password. |
| [TimestampOptions](./timestampoptions/)() | Creates a new instance with default values. Used to sing TSA with a PFX file. |
## See Also

* Class [PdfConverterOptions](../pdfconverteroptions/)
* Namespace [Aspose::Pdf::LowCode](../)
* Library [Aspose.PDF for C++](../../)
