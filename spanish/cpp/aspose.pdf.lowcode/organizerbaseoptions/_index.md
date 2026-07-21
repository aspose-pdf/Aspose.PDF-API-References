---
title: "Aspose::Pdf::LowCode::OrganizerBaseOptions clase"
linktitle: "OrganizerBaseOptions"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::LowCode::OrganizerBaseOptions clase. Representa opciones base para complementos en C++."
type: docs
weight: 5200
url: /es/cpp/aspose.pdf.lowcode/organizerbaseoptions/
---
## OrganizerBaseOptions class


Representa las opciones base para los plugins.

```cpp
class OrganizerBaseOptions : public Aspose::Pdf::LowCode::IPluginOptions,
                             public Aspose::Pdf::LowCode::IDataContainer,
                             public Aspose::Pdf::LowCode::ISaveInstruction
```

## Métodos

| Método | Descripción |
| --- | --- |
| [AddInput](./addinput/)(System::SharedPtr\<IDataSource\>) override | Agrega una nueva fuente de datos al conjunto de datos del complemento PdfOrganizer. |
| [AddOutput](./addoutput/)(System::SharedPtr\<IDataSource\>) override | Agrega una nueva fuente de datos al conjunto de datos del complemento PdfOrganizer. |
| [get_CloseInputStreams](./get_closeinputstreams/)() const | Cierra los flujos de entrada después de que la operación se complete. |
| [get_CloseOutputStreams](./get_closeoutputstreams/)() const | Cierra los flujos de salida después de que la operación se complete. |
| [get_Inputs](./get_inputs/)() override | Devuelve la colección de datos del complemento OrganizerOptions. |
| [get_Outputs](./get_outputs/)() override | Obtiene la colección de objetivos añadidos para guardar los resultados de la operación. |
| [set_CloseInputStreams](./set_closeinputstreams/)(bool) | Cierra los flujos de entrada después de que la operación se complete. |
| [set_CloseOutputStreams](./set_closeoutputstreams/)(bool) | Cierra los flujos de salida después de que la operación se complete. |
## Ver también

* Class [IPluginOptions](../ipluginoptions/)
* Class [IDataContainer](../idatacontainer/)
* Class [ISaveInstruction](../isaveinstruction/)
* Namespace [Aspose::Pdf::LowCode](../)
* Library [Aspose.PDF for C++](../../)
