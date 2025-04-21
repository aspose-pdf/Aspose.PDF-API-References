---
title: SvgSaveOptions.TreatTargetFileNameAsDirectory
second_title: Aspose.PDF for .NET API Reference
description: Campo SvgSaveOptions. Esta opción define si se creará un directorio de destino si aún no existe con el mismo nombre que el archivo de salida solicitado en lugar del archivo de salida solicitado en sí. De esta manera, el directorio contendrá todas las imágenes SVG de salida de las páginas como se describe a continuación. Si no, los archivos de salida de las páginas, aparte del primero, se crearán exactamente en el directorio solicitado como archivo de salida principal, pero contendrán en el nombre del archivo el sufijo _2...n que está definido por el número de página, por ejemplo, si defines el archivo de salida "C\AsposeTests\output.svg" y la salida contendrá varios archivos svg de páginas, entonces los archivos de las páginas también se crearán en el directorio "C\AsposeTests\" y tendrán nombres 'output.svg', 'output_2.svg', 'output_3.svg', etc.
type: docs
weight: 50
url: /es/net/aspose.pdf/svgsaveoptions/treattargetfilenameasdirectory/
---
## Campo SvgSaveOptions.TreatTargetFileNameAsDirectory

Esta opción define si se creará un directorio de destino (si aún no existe) con el mismo nombre que el archivo de salida solicitado en lugar del archivo de salida solicitado en sí. De esta manera, el directorio contendrá todas las imágenes SVG de salida de las páginas (como se describe a continuación). Si no, los archivos de salida de las páginas, aparte del primero, se crearán exactamente en el directorio solicitado como archivo de salida principal, pero contendrán en el nombre del archivo el sufijo _[2...n], que está definido por el número de página, por ejemplo, si defines el archivo de salida "C:\AsposeTests\output.svg" y la salida contendrá varios archivos svg de páginas, entonces los archivos de las páginas también se crearán en el directorio "C:\AsposeTests\" y tendrán nombres 'output.svg', 'output_2.svg', 'output_3.svg', etc.

```csharp
public bool TreatTargetFileNameAsDirectory;
```

### Ver También

* clase [SvgSaveOptions](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblaje [Aspose.PDF](../../../)