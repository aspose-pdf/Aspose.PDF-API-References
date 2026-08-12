---
title: "Aspose::Pdf::LowCode::TimestampOptions clase"
linktitle: "TimestampOptions"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::LowCode::TimestampOptions. Opciones para el complemento Low‑Code Timestamp en C++."
type: docs
weight: 9100
url: /es/cpp/aspose.pdf.lowcode/timestampoptions/
---
## TimestampOptions class


Opciones para el complemento Low‑Code [Timestamp](../timestamp/).

```cpp
class TimestampOptions : public Aspose::Pdf::LowCode::PdfConverterOptions
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_BasicAuthCredentials](./get_basicauthcredentials/)() const | Obtiene las credenciales de autenticación básica, el nombre de usuario y la contraseña se combinan en una cadena "username:password". |
| [get_DigestHashAlgorithm](./get_digesthashalgorithm/)() const | Algoritmo de hash digest a usar para la marca de tiempo. Predeterminado a Sha256. |
| [get_OperationName](./get_operationname/)() override | Devuelve el nombre de la operación. |
| [get_PageNumber](./get_pagenumber/)() const | Número de [Page](../../aspose.pdf/page/) en el que se aplicará la firma con marca de tiempo. |
| [get_Rectangle](./get_rectangle/)() const | [Rectangle](../../aspose.pdf/rectangle/) que define el área de anotación (ignorada cuando Visible es false). |
| [get_ServerUrl](./get_serverurl/)() const | URL del servidor de marca de tiempo. |
| [get_SigContact](./get_sigcontact/)() const | Información de contacto para la firma. |
| [get_SigLocation](./get_siglocation/)() const | Ubicación para la firma. |
| [get_SigReason](./get_sigreason/)() const | Razón de la firma. |
| [get_Visible](./get_visible/)() const | Indicador de visibilidad – false para una marca de tiempo pura (sin anotación visible). |
| [set_BasicAuthCredentials](./set_basicauthcredentials/)(const System::String\&) | Establece las credenciales de autenticación básica, el nombre de usuario y la contraseña se combinan en una cadena "username:password". |
| [set_DigestHashAlgorithm](./set_digesthashalgorithm/)(Aspose::Pdf::DigestHashAlgorithm) | Algoritmo de hash digest a usar para la marca de tiempo. Predeterminado a Sha256. |
| [set_PageNumber](./set_pagenumber/)(int32_t) | Número de [Page](../../aspose.pdf/page/) en el que se aplicará la firma con marca de tiempo. |
| [set_Rectangle](./set_rectangle/)(System::Drawing::Rectangle) | [Rectangle](../../aspose.pdf/rectangle/) que define el área de anotación (ignorada cuando Visible es false). |
| [set_ServerUrl](./set_serverurl/)(const System::String\&) | URL del servidor de marca de tiempo. |
| [set_SigContact](./set_sigcontact/)(const System::String\&) | Información de contacto para la firma. |
| [set_SigLocation](./set_siglocation/)(const System::String\&) | Ubicación para la firma. |
| [set_SigReason](./set_sigreason/)(const System::String\&) | Razón de la firma. |
| [set_Visible](./set_visible/)(bool) | Indicador de visibilidad – false para una marca de tiempo pura (sin anotación visible). |
| [TimestampOptions](./timestampoptions/)(const System::String\&, const System::String\&) | Crea una nueva instancia con una ruta de archivo PFX y contraseña. |
| [TimestampOptions](./timestampoptions/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&) | Crea una nueva instancia con un flujo PFX y contraseña. |
| [TimestampOptions](./timestampoptions/)() | Crea una nueva instancia con valores predeterminados. Se utiliza para firmar TSA con un archivo PFX. |
## Ver también

* Class [PdfConverterOptions](../pdfconverteroptions/)
* Namespace [Aspose::Pdf::LowCode](../)
* Library [Aspose.PDF for C++](../../)
