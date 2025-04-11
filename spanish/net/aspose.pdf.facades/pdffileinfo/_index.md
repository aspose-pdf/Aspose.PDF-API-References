---
title: Class PdfFileInfo
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Facades.PdfFileInfo. Representa una clase para acceder a la información meta del documento PDF
type: docs
weight: 4520
url: /es/net/aspose.pdf.facades/pdffileinfo/
---
## Clase PdfFileInfo

Representa una clase para acceder a la información meta del documento PDF.

```csharp
public sealed class PdfFileInfo : SaveableFacade
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PdfFileInfo](pdffileinfo/#constructor)() | Inicializa una nueva instancia de la clase Aspose.Pdf.Facades.PdfFileInfo con valores predeterminados. |
| [PdfFileInfo](pdffileinfo/#constructor_1)(Document) | Inicializa un nuevo objeto `PdfFileInfo` basado en el *documento*. |
| [PdfFileInfo](pdffileinfo/#constructor_2)(Stream) | Inicializa una nueva instancia de la clase Aspose.Pdf.Facades.PdfFileInfo. |
| [PdfFileInfo](pdffileinfo/#constructor_4)(string) | Inicializa una nueva instancia de la clase Aspose.Pdf.Facades.PdfFileInfo. |
| [PdfFileInfo](pdffileinfo/#constructor_3)(Stream, string) | Inicializa una nueva instancia de la clase Aspose.Pdf.Facades.PdfFileInfo. |
| [PdfFileInfo](pdffileinfo/#constructor_5)(string, string) | Inicializa una nueva instancia de la clase Aspose.Pdf.Facades.PdfFileInfo. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Author](../../aspose.pdf.facades/pdffileinfo/author/) { get; set; } | Obtiene o establece la información del Autor del documento PDF. |
| [CreationDate](../../aspose.pdf.facades/pdffileinfo/creationdate/) { get; set; } | Obtiene o establece la información de la Fecha de Creación del documento PDF. |
| [Creator](../../aspose.pdf.facades/pdffileinfo/creator/) { get; set; } | Obtiene o establece la información del Creador del documento PDF. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Obtiene la fachada del documento en la que está trabajando. |
| [HasCollection](../../aspose.pdf.facades/pdffileinfo/hascollection/) { get; } | Devuelve verdadero si el archivo de entrada actual es un archivo 'Portfolio' que contiene una colección de archivos PDF. |
| [HasEditPassword](../../aspose.pdf.facades/pdffileinfo/haseditpassword/) { get; } | Devuelve verdadero si se necesita una contraseña para modificar los permisos o la propiedad de seguridad del documento. Preste atención a que esta propiedad solo se puede leer si se proporcionó una contraseña válida en el constructor de `PdfFileInfo`. En caso de que PasswordType sea Inaccessible (significa que se proporcionó una contraseña inválida), la lectura de esta propiedad fallará con [`InvalidPasswordException`](../../aspose.pdf/invalidpasswordexception/). |
| [HasOpenPassword](../../aspose.pdf.facades/pdffileinfo/hasopenpassword/) { get; } | Devuelve verdadero si se necesita una contraseña para abrir un documento PDF protegido por contraseña. |
| [Header](../../aspose.pdf.facades/pdffileinfo/header/) { get; set; } | Obtiene o establece la información personalizada del documento PDF. |
| [IsEncrypted](../../aspose.pdf.facades/pdffileinfo/isencrypted/) { get; } | Verifica si el documento PDF está encriptado. |
| [IsPdfFile](../../aspose.pdf.facades/pdffileinfo/ispdffile/) { get; } | Verifica si la entrada de origen es un archivo PDF válido. |
| [Keywords](../../aspose.pdf.facades/pdffileinfo/keywords/) { get; set; } | Obtiene o establece la información de las Palabras Clave del documento PDF. |
| [ModDate](../../aspose.pdf.facades/pdffileinfo/moddate/) { get; set; } | Obtiene o establece la información de la fecha ModDate del documento PDF. |
| [NumberOfPages](../../aspose.pdf.facades/pdffileinfo/numberofpages/) { get; } | Obtiene el número de páginas del documento. |
| [PasswordType](../../aspose.pdf.facades/pdffileinfo/passwordtype/) { get; } | Devuelve el tipo de contraseña que se pasó para crear la instancia de PdfFileInfo. Vea los valores posibles en [`PasswordType`](./passwordtype/). Preste atención a que el documento PDF se puede abrir utilizando tanto la contraseña de usuario (o de apertura) como la contraseña de propietario (o de permisos, edición). |
| [Producer](../../aspose.pdf.facades/pdffileinfo/producer/) { get; } | Obtiene la información del Productor del documento PDF. |
| [Subject](../../aspose.pdf.facades/pdffileinfo/subject/) { get; set; } | Obtiene o establece la información del Asunto del documento PDF. |
| [Title](../../aspose.pdf.facades/pdffileinfo/title/) { get; set; } | Obtiene o establece la información del Título del documento PDF. |
| [UseStrictValidation](../../aspose.pdf.facades/pdffileinfo/usestrictvalidation/) { get; set; } | Utiliza reglas de validación estrictas mediante el uso de la propiedad [`IsPdfFile`](./ispdffile/). |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [BindPdf](../../aspose.pdf.facades/pdffileinfo/bindpdf/#bindpdf)(Document) | Inicializa la fachada. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Inicializa la fachada. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Inicializa la fachada. |
| [ClearInfo](../../aspose.pdf.facades/pdffileinfo/clearinfo/)() | Limpia toda la información meta del documento PDF. |
| override [Close](../../aspose.pdf.facades/pdffileinfo/close/)() | Desinicializa la instancia. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Libera la fachada. |
| [GetDocumentPrivilege](../../aspose.pdf.facades/pdffileinfo/getdocumentprivilege/)() | Obtiene la configuración de privilegios del documento PDF. |
| [GetMetaInfo](../../aspose.pdf.facades/pdffileinfo/getmetainfo/)(string) | Obtiene información personalizada del documento PDF con el nombre de la propiedad. Si no hay ninguna propiedad que coincida con el nombre, devolverá una cadena vacía. |
| [GetPageHeight](../../aspose.pdf.facades/pdffileinfo/getpageheight/)(int) | Obtiene la altura de la página especificada. |
| [GetPageRotation](../../aspose.pdf.facades/pdffileinfo/getpagerotation/)(int) | Obtiene la rotación de la página especificada. |
| [GetPageWidth](../../aspose.pdf.facades/pdffileinfo/getpagewidth/)(int) | Obtiene el ancho de la página especificada. |
| [GetPageXOffset](../../aspose.pdf.facades/pdffileinfo/getpagexoffset/)(int) | Obtiene el desplazamiento horizontal del área de visualización de la página especificada. |
| [GetPageYOffset](../../aspose.pdf.facades/pdffileinfo/getpageyoffset/)(int) | Obtiene el desplazamiento vertical del área de visualización de la página especificada. |
| [GetPdfVersion](../../aspose.pdf.facades/pdffileinfo/getpdfversion/)() | Obtiene la información de la versión del documento PDF. |
| override [Save](../../aspose.pdf.facades/pdffileinfo/save/#save)(Stream) | Guarda el documento PDF en el archivo especificado. |
| override [Save](../../aspose.pdf.facades/pdffileinfo/save/#save_1)(string) | Guarda el documento PDF en el archivo especificado. |
| [SaveNewInfo](../../aspose.pdf.facades/pdffileinfo/savenewinfo/#savenewinfo_1)(string) | Guarda el documento PDF actualizado en el archivo especificado. |
| [SaveNewInfoWithXmp](../../aspose.pdf.facades/pdffileinfo/savenewinfowithxmp/)(string) | Cambia las propiedades especificadas explícitamente configurando la información del archivo, las demás propiedades permanecen. |
| [SetMetaInfo](../../aspose.pdf.facades/pdffileinfo/setmetainfo/)(string, string) | Establece información personalizada del documento PDF. |

### Ver También

* clase [SaveableFacade](../saveablefacade/)
* espacio de nombres [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../)