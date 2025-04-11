---
title: Class XslFoLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.XslFoLoadOptions. Representa opciones para cargar/importar un archivo XSLFO en un documento pdf
type: docs
weight: 11530
url: /es/net/aspose.pdf/xslfoloadoptions/
---
## Clase XslFoLoadOptions

Representa opciones para cargar/importar un archivo XSL-FO en un documento pdf.

```csharp
public sealed class XslFoLoadOptions : XmlLoadOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [XslFoLoadOptions](xslfoloadoptions/#constructor)() | Crea un objeto `XslFoLoadOptions` sin datos xsl. |
| [XslFoLoadOptions](xslfoloadoptions/#constructor_1)(Stream) | Crea un objeto `XslFoLoadOptions` con datos xsl. |
| [XslFoLoadOptions](xslfoloadoptions/#constructor_2)(string) | Crea un objeto `XslFoLoadOptions` con datos xsl. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BasePath](../../aspose.pdf/xslfoloadoptions/basepath/) { get; set; } | La ruta/base url desde la cual se buscan rutas relativas a recursos externos (si los hay) referenciados en el archivo SVG cargado. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Obtiene o establece un indicador para deshabilitar cualquier restricción de licencia para todas las fuentes al cargar el archivo. Cuando `true`, permite ejecutar operaciones con fuentes que están prohibidas por una licencia de esta fuente, por ejemplo, permite incrustar una fuente en un documento PDF incluso si las reglas de licencia deshabilitan la incrustación para esta fuente. Por defecto `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Representa el formato de archivo que describe [`LoadOptions`](../loadoptions/). |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback para manejar cualquier advertencia generada. El WarningHandler devuelve un elemento de enumeración ReturnAction que especifica ya sea Continuar o Abort. Continuar es la acción predeterminada y la operación de carga continúa, sin embargo, el usuario también puede devolver Abort en cuyo caso la operación de carga debe cesar. |
| [XslStream](../../aspose.pdf/xmlloadoptions/xslstream/) { get; } | Obtiene datos xsl para convertir xml en un documento pdf. |
| [XsltArgumentList](../../aspose.pdf/xslfoloadoptions/xsltargumentlist/) { get; set; } | XsltArgumentList para insertar valores en parámetros xls existentes. El archivo XLS tiene el parámetro 'animal' sin valor: XsltArgumentList args = new XsltArgumentList(); args.AddParam("animal", "", "cat"); ahora el convertidor asume que hay un parámetro 'animal' con el valor 'cat' en el archivo XLS. |

## Campos

| Nombre | Descripción |
| --- | --- |
| [ParsingErrorsHandlingType](../../aspose.pdf/xslfoloadoptions/parsingerrorshandlingtype/) | El documento XSLFO de origen puede contener errores de formato. Esta enumeración enumera las posibles estrategias para manejar esos errores. |

## Ejemplos

El siguiente ejemplo muestra cómo convertir un archivo XSL-FO a un archivo PDF.

```csharp
[C#]
// The path to the documents directory.
string dataDir = @"YOUR_DATA_DIRECTORY";

// The path to your XSL-FO File.
string xslFoFile = Path.Combine(dataDir, "XSLFO-to-PDF.xslfo");

// The path to output PDF File.
string pdfFile = Path.Combine(dataDir, "XSLFO-to-PDF.pdf");

// Initialize XslFoLoadOptions	
XslFoLoadOptions xslFoLoadOptions = new XslFoLoadOptions();
    
using (Document pdfDocument = new Document(xslFoFile, xslFoLoadOptions))
{
 
    // Save PDF file
    pdfDocument.Save(pdfFile);
}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your XSL-FO File.
    Dim xslFoFile = Path.Combine(dataDir, "XSLFO-to-PDF.xslfo")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "XSLFO-to-PDF.pdf")
 
    ' Initialize XslFoLoadOptions  
    Dim xslFoLoadOptions As XslFoLoadOptions = New XslFoLoadOptions()
 
    Using pdfDocument As Document = New Document(xslFoFile, xslFoLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### Ver También

* clase [XmlLoadOptions](../xmlloadoptions/)
* espacio de nombres [Aspose.Pdf](../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../)