---
title: "Clase Aspose::Pdf::ComHelper"
linktitle: "ComHelper"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::ComHelper. Proporciona métodos para clientes COM para cargar un documento en Aspose.Pdf en C++."
type: docs
weight: 3100
url: /es/cpp/aspose.pdf/comhelper/
---
## ComHelper class


Proporciona métodos para clientes COM para cargar un documento en [Aspose.Pdf](../).

```cpp
class ComHelper : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [OpenFile](./openfile/)(const System::String\&) | Simplemente cree y devuelva [Document](../document/) usando *filename*. Lo mismo que [Document(Stream)](../). |
| [OpenFile](./openfile/)(const System::String\&, const System::String\&) | Inicialice y devuelva una nueva instancia de la clase [Document](../document/) para trabajar con un documento cifrado. |
| [OpenFile](./openfile/)(const System::String\&, const System::String\&, bool) | Inicialice una nueva instancia de la clase [Document](../document/) para trabajar con un documento cifrado. |
| [OpenFile](./openfile/)(const System::String\&, const System::SharedPtr\<LoadOptions\>\&) | Abra un documento existente desde un archivo proporcionando las opciones de conversión necesarias para obtener un documento PDF. |
| [OpenStream](./openstream/)(const System::SharedPtr\<System::IO::Stream\>\&) | Inicialice y devuelva una nueva instancia de [Document](../document/) a partir del flujo *input*. |
| [OpenStream](./openstream/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&) | Inicialice y devuelva una nueva instancia de [Document](../document/) a partir del flujo *input*. |
| [OpenStream](./openstream/)(const System::SharedPtr\<System::IO::Stream\>\&, bool) | Inicialice y devuelva una nueva instancia de [Document](../document/) a partir del flujo *input*. |
| [OpenStream](./openstream/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&, bool) | Inicialice y devuelva una nueva instancia de [Document](../document/) a partir del flujo *input*. |
| [OpenStream](./openstream/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<LoadOptions\>\&) | Abra y devuelva un documento existente desde un flujo proporcionando la conversión necesaria para obtener un documento PDF. |
## Observaciones


Utilice la clase [ComHelper](./) para cargar un documento desde un archivo o flujo en un objeto [Document](../document/) en una aplicación COM. La clase [Document](../document/) proporciona un constructor predeterminado para crear un nuevo documento y también ofrece constructores sobrecargados para cargar un documento desde un archivo o flujo. Si está utilizando Aspose.Words desde una aplicación .NET, puede usar directamente todos los constructores de [Document](../document/), pero si está utilizando [Aspose.Pdf](../) desde una aplicación COM, solo está disponible el constructor predeterminado de [Document](../document/).
## Ver también

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
