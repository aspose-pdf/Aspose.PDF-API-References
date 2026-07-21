---
title: "Aspose::Pdf::Flow::StructureRecognitionVisitor clase"
linktitle: "StructureRecognitionVisitor"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Flow::StructureRecognitionVisitor clase. Clase base para un visitante personalizado de reconocimiento de estructura de documento en C++."
type: docs
weight: 200
url: /es/cpp/aspose.pdf.flow/structurerecognitionvisitor/
---
## StructureRecognitionVisitor class


Clase base para un visitante de reconocimiento de estructura de documento personalizado.

```cpp
class StructureRecognitionVisitor : public Aspose::Pdf::Flow::IStructureRecognitionVisitor
```

## Métodos

| Método | Descripción |
| --- | --- |
| [EndDocument](./enddocument/)() override | Señala el final del procesamiento del documento. |
| virtual [Recognize](./recognize/)(System::SharedPtr\<Document\>) | Iniciar reconocimiento del documento. |
| virtual [Recognize](./recognize/)(System::SharedPtr\<Page\>) | Iniciar reconocimiento de la página. |
| [StartDocument](./startdocument/)() override | Se llama cuando comienza el recorrido del documento. |
| [VisitParagraph](./visitparagraph/)(System::SharedPtr\<BaseParagraph\>) override | Se llama cuando se visita un nodo de párrafo. |
| [VisitSectionEnd](./visitsectionend/)(System::SharedPtr\<MarginInfo\>) override | Visita el final de una sección reconocida en el documento. |
| [VisitTable](./visittable/)(System::SharedPtr\<Table\>) override | Visita una tabla reconocida en la estructura del documento. |
## Ver también

* Class [IStructureRecognitionVisitor](../istructurerecognitionvisitor/)
* Namespace [Aspose::Pdf::Flow](../)
* Library [Aspose.PDF for C++](../../)
