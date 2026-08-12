---
title: "Clase Aspose::Pdf::XForm"
linktitle: "XForm"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::XForm. La clase representa XForm en C++."
type: docs
weight: 19500
url: /es/cpp/aspose.pdf/xform/
---
## XForm class


La clase representa [XForm](./).

```cpp
class XForm : public System::IDisposable,
              public Aspose::Pdf::ISupportsMemoryCleanup,
              public Aspose::Pdf::IOperatorContainer
```

## Métodos

| Método | Descripción |
| --- | --- |
| static [CreateNewForm](./createnewform/)(const System::SharedPtr\<Page\>\&, const System::SharedPtr\<Document\>\&) | Crea [XForm](./) que duplica el contenido de la página. |
| [Dispose](./dispose/)() override | Libera memoria. |
| [FreeMemory](./freememory/)() override | Borra los datos en caché. |
| [get_BBox](./get_bbox/)() | Obtiene el cuadro delimitador del formulario. |
| [get_Contents](./get_contents/)() override | Obtiene los operadores del formulario. |
| [get_IT](./get_it/)() | Obtiene el formulario IT. Form IT es un nombre que describe la intención del XObject. |
| [get_Matrix](./get_matrix/)() | Obtiene la matriz del formulario. |
| [get_Name](./get_name/)() | Obtiene el nombre del formulario. El nombre del formulario es el nombre que se usa para referenciar el formulario en el diccionario XObejct de los recursos de la página. |
| [get_Opi](./get_opi/)() | Obtiene la Interfaz de Preimpresión Abierta (OPI). |
| [get_Rectangle](./get_rectangle/)() | Obtiene el rectángulo del formulario. |
| [get_Resources](./get_resources/)() override | Obtiene los recursos del Form XObject. |
| [get_Subtype](./get_subtype/)() | Obtiene el subtipo del formulario. |
| [GetResources](./getresources/)(bool) | Devuelve los recursos del Form X-Object. |
| [GetResources](./getresources/)() override | Devuelve los recursos del Form X-Object. Si el Form no tiene recursos y allowCreate es verdadero, [Resources](../resources/) se creará automáticamente para el formulario. |
| [set_BBox](./set_bbox/)(const System::SharedPtr\<Aspose::Pdf::Rectangle\>\&) | Establece el cuadro delimitador del formulario. |
| [set_Matrix](./set_matrix/)(const System::SharedPtr\<Aspose::Pdf::Matrix\>\&) | Establece la matriz del formulario. |
| [set_Name](./set_name/)(const System::String\&) | Establece el nombre del formulario. El nombre del formulario es el nombre que se usa para referenciar el formulario en el diccionario XObejct de los recursos de la página. |
## Ver también

* Class [IDisposable](../../system/idisposable/)
* Class [ISupportsMemoryCleanup](../isupportsmemorycleanup/)
* Class [IOperatorContainer](../ioperatorcontainer/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
