---
title: "Aspose::Pdf::Flow::IStructureRecognitionVisitor clase"
linktitle: "IStructureRecognitionVisitor"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Flow::IStructureRecognitionVisitor clase. Interfaz base para un visitante de reconocimiento de estructura de documento personalizado en C++."
type: docs
weight: 100
url: /es/cpp/aspose.pdf.flow/istructurerecognitionvisitor/
---
## IStructureRecognitionVisitor class


Interfaz base para un visitante de reconocimiento de estructura de documento personalizado.

```cpp
class IStructureRecognitionVisitor : public virtual System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [EndDocument](./enddocument/)() | Señala el final del procesamiento del documento. |
| virtual [StartDocument](./startdocument/)() | Se llama cuando comienza el recorrido del documento. |
| virtual [VisitParagraph](./visitparagraph/)(System::SharedPtr\<BaseParagraph\>) | Se llama cuando se visita un nodo de párrafo. |
| virtual [VisitSectionEnd](./visitsectionend/)(System::SharedPtr\<MarginInfo\>) | Visita el final de una sección reconocida en el documento. |
| virtual [VisitTable](./visittable/)(System::SharedPtr\<Table\>) | Visita una tabla reconocida en la estructura del documento. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Flow](../)
* Library [Aspose.PDF for C++](../../)
