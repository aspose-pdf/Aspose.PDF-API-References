---
title: "Clase Aspose::Pdf::FileSpecificationComparer"
linktitle: "FileSpecificationComparer"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::FileSpecificationComparer. Representa una clase comparadora para una especificación de archivo. El comparador compara según la especificación, utilizando la lista de campos para ordenar en la definición de la colección. Según la especificación, la ordenación se realiza por los valores de los elementos de la colección. Si no existe un diccionario de elementos de la colección, entonces la ordenación se realiza por los valores de Params en C++."
type: docs
weight: 5600
url: /es/cpp/aspose.pdf/filespecificationcomparer/
---
## FileSpecificationComparer class


Representa una clase comparadora para una especificación de archivo. El comparador compara según la especificación, utilizando la lista de campos para ordenar en la definición de la colección. Según la especificación, la ordenación se realiza por los valores de los elementos de la colección. Si no existe un diccionario de elementos de la colección, entonces la ordenación se realiza por los valores de Params.

```cpp
class FileSpecificationComparer : public System::Collections::Generic::IComparer<System::SharedPtr<FileSpecification>>
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Compare](./compare/)(const System::SharedPtr\<FileSpecification\>\&, const System::SharedPtr\<FileSpecification\>\&) const override | Compara dos especificaciones de archivo según la definición de la colección, usando la ordenación especificada. |
| [FileSpecificationComparer](./filespecificationcomparer/)(const System::SharedPtr\<CollectionSort\>\&) | Crea un comparador de especificaciones de archivo. |
## Ver también

* Class [IComparer](../../system.collections.generic/icomparer/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
