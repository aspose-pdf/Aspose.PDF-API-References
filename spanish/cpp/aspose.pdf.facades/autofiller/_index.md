---
title: "Aspose::Pdf::Facades::AutoFiller class"
linktitle: "AutoFiller"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Facades::AutoFiller class. Representa una clase para recibir datos de una base de datos u otra fuente de datos, los inserta en los campos diseñados de la plantilla PDF y finalmente genera un nuevo archivo PDF o flujo. Tiene dos modos de entrada de archivo de plantilla: entrada como flujo o archivo PDF. Tiene cuatro tipos de modos de salida: un flujo combinado, un archivo combinado, muchos flujos pequeños, muchos archivos pequeños. Puede recibir datos literales contenidos en un System.Data.DataTable en C++."
type: docs
weight: 100
url: /es/cpp/aspose.pdf.facades/autofiller/
---
## AutoFiller class


Representa una clase para recibir datos de una base de datos u otra fuente de datos, los inserta en los campos diseñados de la plantilla PDF y finalmente genera un nuevo archivo PDF o flujo. Tiene dos modos de entrada de archivo de plantilla: entrada como flujo o archivo PDF. Tiene cuatro tipos de modos de salida: un flujo combinado, un archivo combinado, muchos flujos pequeños, muchos archivos pequeños. Puede recibir datos literales contenidos en una [System.Data.DataTable](../../system.data/datatable/).

```cpp
class AutoFiller : public Aspose::Pdf::Facades::ISaveableFacade
```

## Métodos

| Método | Descripción |
| --- | --- |
| [AutoFiller](./autofiller/)() |  |
| [BindPdf](./bindpdf/)(System::String) override | Vincula un archivo [Pdf](../../aspose.pdf/). |
| [BindPdf](./bindpdf/)(System::SharedPtr\<System::IO::Stream\>) override | Vincula un archivo [Pdf](../../aspose.pdf/). |
| [BindPdf](./bindpdf/)(System::SharedPtr\<Document\>) override | Vincula un documento [Pdf](../../aspose.pdf/). |
| [Close](./close/)() override | Cierra el objeto y los flujos de salida. |
| [Dispose](./dispose/)() override | Cierra el objeto y los flujos de salida. |
| [get_BasicFileName](./get_basicfilename/)() const | Obtiene el nombre de archivo básico si se generarán muchos archivos pequeños. El archivo generado será como "BasicFileName0","BasicFileName1",... Funciona con otra propiedad [GeneratingPath](../)GeneratingPath. |
| [get_GeneratingPath](./get_generatingpath/)() const | Obtiene la ruta de generación de los archivos PDF pequeños si se van a generar muchos archivos PDF pequeños. Funciona con otra propiedad [BasicFileName](../)BasicFileName. Uno de los cuatro modos de salida. |
| [get_InputFileName](./get_inputfilename/)() const | Obtiene el archivo de plantilla de entrada. Uno de los dos modos de entrada. |
| [get_InputStream](./get_inputstream/)() const | Obtiene el flujo de plantilla de entrada. Uno de los dos modos de entrada. |
| [get_OutputFileName](./get_outputfilename/)() const | Obtiene el único archivo de salida grande combinado. Uno de los cuatro modos de salida. |
| [get_OutputStream](./get_outputstream/)() const | Obtiene el OutputStream. Uno de los cuatro modos de salida. Su caso de uso clásico es Response.OutputStream. Por favor, consulte la demostración en línea. |
| [get_OutputStreams](./get_outputstreams/)() const | Obtiene los múltiples Output Streams. Uno de los cuatro modos de salida. |
| [Save](./save/)() | Guarda todos los PDFs. |
| [Save](./save/)(System::String) override | Guarda todos los PDFs. |
| [Save](./save/)(System::SharedPtr\<System::IO::Stream\>) override | Guarda todos los PDFs. |
| [set_BasicFileName](./set_basicfilename/)(const System::String\&) | Establece el nombre de archivo básico si se generarán muchos archivos pequeños. El archivo generado será como "BasicFileName0","BasicFileName1",... Funciona con otra propiedad [GeneratingPath](../)GeneratingPath. |
| [set_GeneratingPath](./set_generatingpath/)(const System::String\&) | Establece la ruta de generación de los archivos PDF pequeños si se van a generar muchos archivos PDF pequeños. Funciona con otra propiedad [BasicFileName](../)BasicFileName. Uno de los cuatro modos de salida. |
| [set_InputFileName](./set_inputfilename/)(const System::String\&) | Establece el archivo de plantilla de entrada. Uno de los dos modos de entrada. |
| [set_InputStream](./set_inputstream/)(const System::SharedPtr\<System::IO::Stream\>\&) | Establece el flujo de plantilla de entrada. Uno de los dos modos de entrada. |
| [set_OutputFileName](./set_outputfilename/)(const System::String\&) | Establece el único archivo de salida grande combinado. Uno de los cuatro modos de salida. |
| [set_OutputStream](./set_outputstream/)(const System::SharedPtr\<System::IO::Stream\>\&) | Establece el OutputStream. Uno de los cuatro modos de salida. Su caso de uso clásico es Response.OutputStream. Por favor, consulte la demostración en línea. |
| [set_OutputStreams](./set_outputstreams/)(const System::ArrayPtr\<System::SharedPtr\<System::IO::Stream\>\>\&) | Establece los múltiples Output Streams. Uno de los cuatro modos de salida. |
| [set_UnFlattenFields](./set_unflattenfields/)(const System::ArrayPtr\<System::String\>\&) | Establece los campos que no se aplanarán. Si esta propiedad no se establece, todos los campos se aplanarán. |
## Ver también

* Class [ISaveableFacade](../isaveablefacade/)
* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
