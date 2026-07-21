---
title: "Aspose::Pdf::Forms::XFA clase"
linktitle: "XFA"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::Forms::XFA. Representa un formulario XML respecto a la arquitectura XML Forms (XFA) en C++."
type: docs
weight: 3000
url: /es/cpp/aspose.pdf.forms/xfa/
---
## XFA class


Representa un formulario XML respecto a la arquitectura XML [Forms](../) ([XFA](./)).

```cpp
class XFA : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_Config](./get_config/)() | Componente de configuración de un formulario [XFA](./). |
| [get_Datasets](./get_datasets/)() | Componente de conjuntos de datos de un formulario [XFA](./). |
| [get_FieldNames](./get_fieldnames/)() | Lista de nombres de campos en la plantilla del formulario. |
| [get_Form](./get_form/)() | Componente [XFA](./)[Form](../form/) de un formulario [XFA](./). |
| [get_NamespaceManager](./get_namespacemanager/)() | Obtiene el espacio de nombres del formulario [XFA](./). Los siguientes espacios de nombres están definidos: "data" para datos del formulario y "tpl" para la plantilla del formulario. |
| [get_Template](./get_template/)() | Componente de plantilla de un formulario [XFA](./). |
| [get_XDP](./get_xdp/)() | Paquete de datos XML (todos los componentes del formulario [XFA](./) dentro de un contenedor XML circundante). |
| [GetFieldTemplate](./getfieldtemplate/)(const System::String\&) | Devuelve el nodo XML del campo [XFA](./) de la plantilla. |
| [GetFieldTemplates](./getfieldtemplates/)() | Devuelve la lista de todas las plantillas de campo en el formulario [XFA](./). |
| [idx_get](./idx_get/)(const System::String\&) | Obtiene o establece el valor del nodo de datos según *path*. |
| [idx_set](./idx_set/)(const System::String\&, const System::String\&) | Obtiene o establece el valor del nodo de datos según *path*. |
| [SetFieldImage](./setfieldimage/)(const System::String\&, const System::SharedPtr\<System::IO::Stream\>\&) | Establece la imagen para el campo [XFA](./). |
## Ver también

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Forms](../)
* Library [Aspose.PDF for C++](../../)
