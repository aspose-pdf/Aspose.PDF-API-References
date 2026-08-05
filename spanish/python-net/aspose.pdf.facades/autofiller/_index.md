---
title: "AutoFiller"
second_title: "Referencia de API de Aspose.PDF para Python vía .NET"
description: "Representa una clase para recibir datos de una base de datos u otra fuente de datos, los rellena en los campos diseñados de la plantilla pdf y al final genera un nuevo archivo pdf o flujo.<br/>             Tiene dos modos de entrada de archivo de plantilla: entrada como flujo o como archivo pdf.<br/>             Tiene cuatro tipos de modos de salida: un flujo fusionado, un archivo fusionado, muchos flujos pequeños, muchos archivos pequeños.<br/>             Puede recibir datos literales contenidos en un System.Data.DataTable."
type: docs
weight: 20
url: /es/python-net/aspose.pdf.facades/autofiller/
---

## AutoFiller class

Representa una clase para recibir datos de una base de datos u otra fuente de datos, los rellena en los campos diseñados de la plantilla pdf y al final genera un nuevo archivo pdf o flujo.<br/>             Tiene dos modos de entrada de archivo de plantilla: entrada como flujo o como archivo pdf.<br/>             Tiene cuatro tipos de modos de salida: un flujo fusionado, un archivo fusionado, muchos flujos pequeños, muchos archivos pequeños.<br/>             Puede recibir datos literales contenidos en un System.Data.DataTable.

El tipo AutoFiller expone los siguientes miembros:
## Constructores
| Nombre | Descripción |
| :- | :- |
| AutoFiller() | Inicializa una nueva instancia de la clase AutoFiller |
## Propiedades
| Nombre | Descripción |
| :- | :- |
| output_stream | Obtiene o establece el OutputStream. Uno de cuatro modos de salida. Su caso de uso clásico es Response.OutputStream.<br/>            Consulte la demostración en línea. |
| output_streams | Obtiene o establece los múltiples Output Streams. Uno de cuatro modos de salida. |
| input_stream | Obtiene o establece el flujo de plantilla de entrada. Uno de dos modos de entrada. |
| input_file_name | Obtiene o establece el archivo de plantilla de entrada. Uno de dos modos de entrada. |
| output_file_name | Obtiene o establece el único archivo de salida grande fusionado. Uno de los cuatro modos de salida. |
| generating_path | Obtiene o establece el Generating Path de los archivos pdf pequeños si se van a generar muchos archivos pdf pequeños. Funciona con otra propiedad [basic_file_name](/pdf/python-net/aspose.pdf.facades/autofiller/)BasicFileName.<br/>            Uno de los cuatro modos de salida. |
| basic_file_name | Obtiene o establece el nombre de archivo básico si se van a generar muchos archivos pequeños. El archivo generado será como "BasicFileName0","BasicFileName1",...<br/>            Funciona con otra propiedad [generating_path](/pdf/python-net/aspose.pdf.facades/autofiller/)GeneratingPath. |
## Métodos
| Nombre | Descripción |
| :- | :- |
| save() | Guarda todos los pdf. |
| save(dest_file) | Guarda todos los pdf. |
| save(dest_stream) | Guarda todos los pdf. |
| bind_pdf(src_file) | Vincula un archivo Pdf. |
| bind_pdf(src_stream) | Vincula un archivo Pdf. |
| bind_pdf(src_doc) | Vincula un documento Pdf. |
| close() | Cierra el objeto y los flujos de salida. |

### Ver también

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

