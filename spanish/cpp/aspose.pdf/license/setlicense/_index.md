---
title: "Aspose::Pdf::License::SetLicense método"
linktitle: "SetLicense"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::License::SetLicense método. Licencia el componente en C++."
type: docs
weight: 600
url: /es/cpp/aspose.pdf/license/setlicense/
---
## License::SetLicense(const System::SharedPtr\<System::IO::Stream\>\&) method


Licencia el componente.

```cpp
void Aspose::Pdf::License::SetLicense(const System::SharedPtr<System::IO::Stream> &stream)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | const System::SharedPtr\<System::IO::Stream\>\& | Un flujo que contiene la licencia. |
## Observaciones



Utilice este método para cargar una licencia desde un flujo.

[Java] void setLicense(java.io.InputStream stream) 
## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [License](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## License::SetLicense(const System::String\&) method


Licencia el componente.

```cpp
void Aspose::Pdf::License::SetLicense(const System::String &licenseName)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| licenseName | const System::String\& | Puede ser un nombre de archivo completo o corto o el nombre de un recurso incrustado. Use una cadena vacía para cambiar al modo de evaluación. |
## Observaciones


Intenta encontrar la licencia en las siguientes ubicaciones:

1. Ruta explícita.

2. La carpeta que contiene el ensamblado del componente **Aspose**.

3. La carpeta que contiene el ensamblado de llamada del cliente.

4. La carpeta que contiene el ensamblado de entrada (inicio).

5. Un recurso incrustado en el ensamblado de llamada del cliente.

**[Note](../../note/):**On the .NET Compact Framework, tries to find the license only in these locations:

1. Ruta explícita.

2. Un recurso incrustado en el ensamblado de llamada del cliente.

[Java] 

2. La carpeta que contiene el archivo JAR del componente **Aspose**.

3. La carpeta que contiene el archivo JAR de llamada del cliente.

## Ver también

* Class [String](../../../system/string/)
* Class [License](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
