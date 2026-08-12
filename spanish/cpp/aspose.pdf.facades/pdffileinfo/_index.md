---
title: "Clase Aspose::Pdf::Facades::PdfFileInfo"
linktitle: "PdfFileInfo"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::Facades::PdfFileInfo. Representa una clase para acceder a la información meta de un documento PDF en C++."
type: docs
weight: 2100
url: /es/cpp/aspose.pdf.facades/pdffileinfo/
---
## PdfFileInfo class


Representa una clase para acceder a la información meta de documentos PDF.

```cpp
class PdfFileInfo : public Aspose::Pdf::Facades::SaveableFacade
```

## Métodos

| Método | Descripción |
| --- | --- |
| [BindPdf](./bindpdf/)(System::SharedPtr\<Aspose::Pdf::Document\>) override | Inicializa la fachada. |
| [ClearInfo](./clearinfo/)() | Borra toda la información meta del documento PDF. |
| [Close](./close/)() override | Desinicializa la instancia. |
| [get_Author](./get_author/)() | Obtiene la información del Autor del documento PDF. |
| [get_CreationDate](./get_creationdate/)() | Obtiene la información de CreationDate del documento PDF. |
| [get_Creator](./get_creator/)() | Obtiene la información de Creator del documento PDF. |
| [get_HasCollection](./get_hascollection/)() | Devuelve true si el archivo de entrada actual es un archivo 'Portfolio' que contiene una colección de archivos PDF. |
| [get_HasEditPassword](./get_haseditpassword/)() | Devuelve true si se necesita una contraseña para modificar los permisos o la propiedad de seguridad del documento. Tenga en cuenta que esta propiedad solo puede leerse si se proporcionó una contraseña válida en el constructor de [PdfFileInfo](./). En caso de que [PasswordType](../../aspose.pdf/passwordtype/) sea Inaccessible (significa que se proporcionó una contraseña inválida), la lectura de esta propiedad fallará con [InvalidPasswordException](../../aspose.pdf/invalidpasswordexception/). |
| [get_HasOpenPassword](./get_hasopenpassword/)() | Devuelve true si se necesita una contraseña para abrir un documento PDF protegido con contraseña. |
| [get_Header](./get_header/)() const | Obtiene la información personalizada del documento PDF. |
| [get_InputFile](./get_inputfile/)() const | Obtiene el archivo de entrada. |
| [get_InputStream](./get_inputstream/)() const | Obtiene el flujo de entrada. |
| [get_IsEncrypted](./get_isencrypted/)() | Comprueba si el documento PDF está cifrado. |
| [get_IsPdfFile](./get_ispdffile/)() | Comprueba si la entrada de origen es un archivo PDF válido. |
| [get_Keywords](./get_keywords/)() | Obtiene la información de Keywords del documento PDF. |
| [get_ModDate](./get_moddate/)() | Obtiene la información de fecha ModDate del documento PDF. |
| [get_NumberOfPages](./get_numberofpages/)() | Obtiene el número de páginas del documento. |
| [get_PasswordType](./get_passwordtype/)() | Devuelve el tipo de contraseña que se pasó al crear la instancia de [PdfFileInfo](./). Consulte los valores posibles en [PasswordType](../../aspose.pdf/passwordtype/). Tenga en cuenta que el documento PDF puede abrirse tanto con la contraseña de usuario (o de apertura) como con la contraseña de propietario (o de permisos, edición). |
| [get_Producer](./get_producer/)() | Obtiene la información de Producer del documento PDF. |
| [get_Subject](./get_subject/)() | Obtiene la información de Subject del documento PDF. |
| [get_Title](./get_title/)() | Obtiene la información de Title del documento PDF. |
| [get_UseStrictValidation](./get_usestrictvalidation/)() const | Utiliza reglas de validación estrictas mediante la propiedad [IsPdfFile](../). |
| [GetDocumentPrivilege](./getdocumentprivilege/)() | Obtiene la configuración de privilegios del documento PDF. |
| [GetMetaInfo](./getmetainfo/)(const System::String\&) | Obtiene la información personalizada del documento PDF con el nombre de la propiedad. Si no hay ninguna propiedad que coincida con el nombre, devolverá una cadena vacía. |
| [GetPageHeight](./getpageheight/)(int32_t) | Obtiene la altura de la página especificada. |
| [GetPageRotation](./getpagerotation/)(int32_t) | Obtiene la rotación de la página especificada. |
| [GetPageWidth](./getpagewidth/)(int32_t) | Obtiene el ancho de la página especificada. |
| [GetPageXOffset](./getpagexoffset/)(int32_t) | Obtiene el desplazamiento horizontal del área de visualización de la página especificada. |
| [GetPageYOffset](./getpageyoffset/)(int32_t) | Obtiene el desplazamiento vertical del área de visualización de la página especificada. |
| [GetPdfVersion](./getpdfversion/)() | Obtiene la información de versión del documento PDF. |
| [PdfFileInfo](./pdffileinfo/)() | Inicializa una nueva instancia de la clase [Aspose.Pdf.Facades.PdfFileInfo](./) con valores predeterminados. |
| [PdfFileInfo](./pdffileinfo/)(const System::SharedPtr\<System::IO::Stream\>\&) | Inicializa una nueva instancia de la clase [Aspose.Pdf.Facades.PdfFileInfo](./). |
| [PdfFileInfo](./pdffileinfo/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&) | Inicializa una nueva instancia de la clase [Aspose.Pdf.Facades.PdfFileInfo](./). |
| [PdfFileInfo](./pdffileinfo/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&, const System::SharedPtr\<Security::ICustomSecurityHandler\>\&) | Inicializa una nueva instancia de la clase [Aspose.Pdf.Facades.PdfFileInfo](./). |
| [PdfFileInfo](./pdffileinfo/)(const System::String\&) | Inicializa una nueva instancia de la clase [Aspose.Pdf.Facades.PdfFileInfo](./). |
| [PdfFileInfo](./pdffileinfo/)(const System::String\&, const System::String\&) | Inicializa una nueva instancia de la clase [Aspose.Pdf.Facades.PdfFileInfo](./). |
| [PdfFileInfo](./pdffileinfo/)(const System::String\&, const System::String\&, const System::SharedPtr\<Security::ICustomSecurityHandler\>\&) | Inicializa una nueva instancia de la clase [Aspose.Pdf.Facades.PdfFileInfo](./). |
| [PdfFileInfo](./pdffileinfo/)(const System::SharedPtr\<Aspose::Pdf::Document\>\&) | Inicializa un nuevo objeto [PdfFileInfo](./) basado en el *documento*. |
| [Save](./save/)(System::SharedPtr\<System::IO::Stream\>) override | Guarda el documento PDF en el archivo especificado. |
| [Save](./save/)(System::String) override | Guarda el documento PDF en el archivo especificado. |
| [SaveNewInfo](./savenewinfo/)(const System::SharedPtr\<System::IO::Stream\>\&) | Guarda el documento PDF actualizado en el flujo especificado. |
| [SaveNewInfo](./savenewinfo/)(const System::String\&) | Guarda el documento PDF actualizado en el archivo especificado. |
| [SaveNewInfoWithXmp](./savenewinfowithxmp/)(const System::String\&) | Cambia las propiedades especificadas explícitamente estableciendo la información del archivo, las demás propiedades permanecen. |
| [set_Author](./set_author/)(const System::String\&) | Establece la información del Autor del documento PDF. |
| [set_CreationDate](./set_creationdate/)(const System::String\&) | Establece la información de CreationDate del documento PDF. |
| [set_Creator](./set_creator/)(const System::String\&) | Establece la información del Creator del documento PDF. |
| [set_Header](./set_header/)(const System::SharedPtr\<System::Collections::Generic::Dictionary\<System::String, System::String\>\>\&) | Establece la información personalizada del documento PDF. |
| [set_InputFile](./set_inputfile/)(const System::String\&) | Establece el archivo de entrada. |
| [set_InputStream](./set_inputstream/)(const System::SharedPtr\<System::IO::Stream\>\&) | Establece el flujo de entrada. |
| [set_Keywords](./set_keywords/)(const System::String\&) | Establece la información de Keywords del documento PDF. |
| [set_ModDate](./set_moddate/)(const System::String\&) | Establece la información de ModDate del documento PDF. |
| [set_Subject](./set_subject/)(const System::String\&) | Establece la información del Subject del documento PDF. |
| [set_Title](./set_title/)(const System::String\&) | Establece la información del Title del documento PDF. |
| [set_UseStrictValidation](./set_usestrictvalidation/)(bool) | Utiliza reglas de validación estrictas mediante la propiedad [IsPdfFile](../). |
| [SetMetaInfo](./setmetainfo/)(const System::String\&, const System::String\&) | Establece información personalizada del documento PDF. |
## Ver también

* Class [SaveableFacade](../saveablefacade/)
* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
