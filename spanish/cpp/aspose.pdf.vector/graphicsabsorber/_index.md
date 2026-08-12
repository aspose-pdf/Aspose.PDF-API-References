---
title: "Aspose::Pdf::Vector::GraphicsAbsorber clase"
linktitle: "GraphicsAbsorber"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Vector::GraphicsAbsorber clase. Representa un objeto absorbente de elementos gráficos. Realiza búsquedas de gráficos y proporciona acceso a los resultados de búsqueda a través de la colección GraphicsAbsorber::Elements en C++."
type: docs
weight: 300
url: /es/cpp/aspose.pdf.vector/graphicsabsorber/
---
## GraphicsAbsorber class


Representa un objeto absorbente de elementos gráficos. Realiza búsquedas gráficas y proporciona acceso a los resultados de búsqueda mediante la colección [GraphicsAbsorber::Elements](../).

```cpp
class GraphicsAbsorber : public System::IDisposable
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Dispose](./dispose/)() override | Libera todos los recursos utilizados por la clase [GraphicsAbsorber](./). |
| [get_Elements](./get_elements/)() const | Obtiene la colección de ocurrencias de búsqueda que se presentan con objetos [GraphicElement](../graphicelement/). |
| [GraphicsAbsorber](./graphicsabsorber/)() |  |
|  | [ResumeUpdate](./resumeupdate/)() | Reanudar actualización para [Page::Contents](../) y todos [XForm::Contents](../). Fue hecho para aumentar el rendimiento, ver también |
[OperatorCollection::ResumeUpdate](../../aspose.pdf/operatorcollection/resumeupdate/)


. |
|  | [SuppressUpdate](./suppressupdate/)() | Suprime la actualización para [Page::Contents](../) y todos [XForm::Contents](../). Fue hecho para aumentar el rendimiento, ver también |
[OperatorCollection::SuppressUpdate](../../aspose.pdf/operatorcollection/suppressupdate/)


. |
| [Visit](./visit/)(const System::SharedPtr\<Page\>\&) | Realiza la búsqueda en la página especificada. |
## Ver también

* Class [IDisposable](../../system/idisposable/)
* Namespace [Aspose::Pdf::Vector](../)
* Library [Aspose.PDF for C++](../../)
