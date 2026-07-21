---
title: "Aspose::Pdf::Facades::PdfFileSecurity class"
linktitle: "PdfFileSecurity"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Facades::PdfFileSecurity class. Representa el cifrado o descifrado de un archivo Pdf con contraseña de propietario o de usuario, cambiando la configuración de seguridad y la contraseña en C++."
type: docs
weight: 2400
url: /es/cpp/aspose.pdf.facades/pdffilesecurity/
---
## PdfFileSecurity class


Representa el cifrado o descifrado de un archivo [Pdf](../../aspose.pdf/) con contraseña de propietario o de usuario, cambiando la configuración de seguridad y la contraseña.

```cpp
class PdfFileSecurity : public Aspose::Pdf::Facades::SaveableFacade
```

## Métodos

| Método | Descripción |
| --- | --- |
| [BindPdf](./bindpdf/)(System::String) override | Inicializa la fachada. |
| [BindPdf](./bindpdf/)(System::SharedPtr\<System::IO::Stream\>) override | Inicializa la fachada. |
| [ChangePassword](./changepassword/)(const System::String\&, const System::String\&, const System::String\&) | Cambia la contraseña de usuario y la contraseña de propietario mediante la contraseña de propietario, manteniendo la configuración de seguridad original. La nueva contraseña de usuario y la nueva contraseña de propietario pueden ser nulas o estar vacías. La contraseña de propietario será reemplazada por una cadena aleatoria si la nueva contraseña de propietario es nula o está vacía. Lanza una excepción si el proceso falla. |
| [ChangePassword](./changepassword/)(const System::String\&, const System::String\&, const System::String\&, const System::SharedPtr\<DocumentPrivilege\>\&, KeySize) | Cambia la contraseña de usuario y la contraseña mediante la contraseña de propietario, permite restablecer la seguridad del [Pdf](../../aspose.pdf/) documento. La nueva contraseña de usuario y la nueva contraseña de propietario pueden ser nulas o estar vacías. La contraseña de propietario será reemplazada por una cadena aleatoria si la nueva contraseña de propietario es nula o está vacía. Lanza una excepción si el proceso falla. |
| [ChangePassword](./changepassword/)(const System::String\&, const System::String\&, const System::String\&, const System::SharedPtr\<DocumentPrivilege\>\&, KeySize, Algorithm) | Cambia la contraseña de usuario y la contraseña mediante la contraseña de propietario, permite restablecer la seguridad del [Pdf](../../aspose.pdf/) documento. La nueva contraseña de usuario y la nueva contraseña de propietario pueden ser nulas o estar vacías. La contraseña de propietario será reemplazada por una cadena aleatoria si la nueva contraseña de propietario es nula o está vacía. Existen 6 combinaciones posibles de valores de [KeySize](../keysize/) y [Algorithm](../algorithm/). Sin embargo, ([KeySize.x40](../keysize/), [Algorithm.AES](../algorithm/)) y ([KeySize.x256](../keysize/), [Algorithm.RC4](../algorithm/)) son inválidas y se lanzará una excepción correspondiente si el kit encuentra esta combinación. Lanza una excepción si el proceso falla. |
| [Close](./close/)() override | Cierra la fachada. |
| [get_AllowExceptions](./get_allowexceptions/)() | Si este valor se establece en true, se lanzará una excepción al fallar la operación. De lo contrario, el método devuelve false en caso de error y la última excepción puede verificarse con la propiedad LastException. |
| [get_LastException](./get_lastexception/)() const | Devuelve la excepción que fue lanzada por la última operación. |
| [MfDecryptFile](./mfdecryptfile/)(const System::String\&) | Descifra un documento [Pdf](../../aspose.pdf/) cifrado mediante la contraseña de propietario. Si el documento no tiene contraseña de propietario, se permite usar la contraseña de usuario. Lanza una excepción si el proceso falla. |
| [MfEncryptFile](./mfencryptfile/)(const System::String\&, const System::String\&, const System::SharedPtr\<DocumentPrivilege\>\&, KeySize) | Cifra el archivo [Pdf](../../aspose.pdf/) con contraseña de usuario y contraseña de propietario y establece los privilegios de acceso del documento. La contraseña de usuario y la contraseña de propietario pueden ser nulas o estar vacías. La contraseña de propietario será reemplazada por una cadena aleatoria si la contraseña de propietario de entrada es nula o está vacía. Lanza una excepción si el proceso falla. |
| [MfEncryptFile](./mfencryptfile/)(const System::String\&, const System::String\&, const System::SharedPtr\<DocumentPrivilege\>\&, KeySize, Algorithm) | Cifra el archivo [Pdf](../../aspose.pdf/) con contraseña de usuario y contraseña de propietario y establece los privilegios de acceso del documento. La contraseña de usuario y la contraseña de propietario pueden ser nulas o estar vacías. La contraseña de propietario será reemplazada por una cadena aleatoria si la contraseña de propietario de entrada es nula o está vacía. Existen 6 combinaciones posibles de valores de [KeySize](../keysize/) y [Algorithm](../algorithm/). Sin embargo, ([KeySize.x40](../keysize/), [Algorithm.AES](../algorithm/)) y ([KeySize.x256](../keysize/), [Algorithm.RC4](../algorithm/)) son inválidas y se lanzará una excepción correspondiente si el kit encuentra esta combinación. Lanza una excepción si el proceso falla. |
| [PdfFileSecurity](./pdffilesecurity/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&) | Inicializa el objeto de [PdfFileSecurity](./) con flujo de entrada y salida. |
| [PdfFileSecurity](./pdffilesecurity/)(const System::String\&, const System::String\&) | Inicializa el objeto de [PdfFileSecurity](./) con archivo de entrada y salida. |
| [PdfFileSecurity](./pdffilesecurity/)() | Inicializa el objeto de [PdfFileSecurity](./). |
| [PdfFileSecurity](./pdffilesecurity/)(const System::SharedPtr\<Aspose::Pdf::Document\>\&) | Inicializa un nuevo objeto [PdfFileSecurity](./) basado en el *documento*. |
| [PdfFileSecurity](./pdffilesecurity/)(const System::SharedPtr\<Aspose::Pdf::Document\>\&, const System::String\&) | Inicializa un nuevo objeto [PdfFileSecurity](./) basado en el *documento*. |
| [PdfFileSecurity](./pdffilesecurity/)(const System::SharedPtr\<Aspose::Pdf::Document\>\&, const System::SharedPtr\<System::IO::Stream\>\&) | Inicializa un nuevo objeto [PdfFileSecurity](./) basado en el *documento*. |
| [set_AllowExceptions](./set_allowexceptions/)(bool) | Si este valor se establece en true, se lanzará una excepción al fallar la operación. De lo contrario, el método devuelve false en caso de error y la última excepción puede verificarse con la propiedad LastException. |
| [set_InputFile](./set_inputfile/)(const System::String\&) | Establece el archivo de entrada. |
| [set_InputStream](./set_inputstream/)(const System::SharedPtr\<System::IO::Stream\>\&) | Establece el flujo de entrada. |
| [set_OutputFile](./set_outputfile/)(const System::String\&) | Establece el archivo de salida. |
| [set_OutputStream](./set_outputstream/)(const System::SharedPtr\<System::IO::Stream\>\&) | Establece el flujo de salida. |
| [SetPrivilege](./setprivilege/)(const System::SharedPtr\<DocumentPrivilege\>\&) | Establece la seguridad del archivo [Pdf](../../aspose.pdf/) con contraseñas de usuario/propietario vacías. La contraseña de propietario será añadida mediante una cadena aleatoria. Lanza una excepción si el proceso falla. |
| [SetPrivilege](./setprivilege/)(const System::String\&, const System::String\&, const System::SharedPtr\<DocumentPrivilege\>\&) | Establece la seguridad del archivo [Pdf](../../aspose.pdf/) con la contraseña original. Lanza una excepción si el proceso falla. |
| [TryChangePassword](./trychangepassword/)(const System::String\&, const System::String\&, const System::String\&) | Cambia la contraseña de usuario y la contraseña de propietario mediante la contraseña de propietario, mantiene la configuración de seguridad original. La nueva contraseña de usuario y la nueva contraseña de propietario pueden ser nulas o vacías. La contraseña de propietario será reemplazada con una cadena aleatoria si la nueva contraseña de propietario es nula o vacía. No lanza una excepción si el proceso falla. |
| [TryChangePassword](./trychangepassword/)(const System::String\&, const System::String\&, const System::String\&, const System::SharedPtr\<DocumentPrivilege\>\&, KeySize) | Cambia la contraseña de usuario y la contraseña mediante la contraseña de propietario, permite restablecer la seguridad del documento [Pdf](../../aspose.pdf/). La nueva contraseña de usuario y la nueva contraseña de propietario pueden ser nulas o vacías. La contraseña de propietario será reemplazada con una cadena aleatoria si la nueva contraseña de propietario es nula o vacía. No lanza una excepción si el proceso falla. |
| [TryChangePassword](./trychangepassword/)(const System::String\&, const System::String\&, const System::String\&, const System::SharedPtr\<DocumentPrivilege\>\&, KeySize, Algorithm) | Cambia la contraseña de usuario y la contraseña mediante la contraseña de propietario, permite restablecer la seguridad del documento [Pdf](../../aspose.pdf/). La nueva contraseña de usuario y la nueva contraseña de propietario pueden ser nulas o vacías. La contraseña de propietario será reemplazada con una cadena aleatoria si la nueva contraseña de propietario es nula o vacía. Existen 6 combinaciones posibles de los valores de [KeySize](../keysize/) y [Algorithm](../algorithm/). Sin embargo, ([KeySize.x40](../keysize/), [Algorithm.AES](../algorithm/)) y ([KeySize.x256](../keysize/), [Algorithm.RC4](../algorithm/)) son inválidas y se lanzará la excepción correspondiente si el kit encuentra esta combinación. No lanza una excepción si el proceso falla. |
| [TryDecryptFile](./trydecryptfile/)(const System::String\&) | Descifra un documento [Pdf](../../aspose.pdf/) cifrado mediante la contraseña de propietario. Si el documento no tiene contraseña de propietario, se permite usar la contraseña de usuario. No lanza una excepción si el proceso falla. |
| [TryEncryptFile](./tryencryptfile/)(const System::String\&, const System::String\&, const System::SharedPtr\<DocumentPrivilege\>\&, KeySize) | Encripta el archivo [Pdf](../../aspose.pdf/) con la contraseña de usuario y la contraseña de propietario y establece los privilegios de acceso del documento. La contraseña de usuario y la contraseña de propietario pueden ser nulas o vacías. La contraseña de propietario será reemplazada con una cadena aleatoria si la contraseña de propietario de entrada es nula o vacía. No lanza una excepción si el proceso falla. |
| [TrySetPrivilege](./trysetprivilege/)(const System::String\&, const System::String\&, const System::SharedPtr\<DocumentPrivilege\>\&) | Establece la seguridad del archivo [Pdf](../../aspose.pdf/) con la contraseña original. No lanza una excepción si el proceso falla. |
## Ver también

* Class [SaveableFacade](../saveablefacade/)
* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
