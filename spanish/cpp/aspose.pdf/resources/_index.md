---
title: "Clase Aspose::Pdf::Resources"
linktitle: "Recursos"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::Resources. Clase que representa los recursos de página en C++."
type: docs
weight: 16500
url: /es/cpp/aspose.pdf/resources/
---
## Resources class


Clase que representa los recursos de página.

```cpp
class Resources : public Aspose::Pdf::ISupportsMemoryCleanup
```

## Nested classes

* Class [ExtGStateValue](./extgstatevalue/)
## Métodos

| Método | Descripción |
| --- | --- |
| [cpp_set_xfrom_weak](./cpp_set_xfrom_weak/)(const System::SharedPtr\<XForm\>\&) |  |
| [FreeMemory](./freememory/)() override | Borra datos en caché, libera memoria, etc. |
| [get_Fonts](./get_fonts/)() | Obtiene la colección de recursos de [Fonts](../). |
| [get_Forms](./get_forms/)() | Obtiene la colección de [Forms](../../aspose.pdf.forms/) formularios. |
| [get_Images](./get_images/)() | Obtiene la colección de [Images](../) imágenes. |
| [GetExtGStates](./getextgstates/)() | Obtiene todos los ExGStates de los recursos. |
| [GetFonts](./getfonts/)(bool) | Devuelve la colección de fuentes. Si los recursos no contienen una entrada de fuentes, se creará según el indicador CreateIfAbsent. |
## Ver también

* Class [ISupportsMemoryCleanup](../isupportsmemorycleanup/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
