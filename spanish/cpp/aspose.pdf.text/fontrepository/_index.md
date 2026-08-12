---
title: "Aspose::Pdf::Text::FontRepository class"
linktitle: "FontRepository"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Text::FontRepository class. Realiza la búsqueda de fuentes. Busca en fuentes instaladas en el sistema y fuentes Pdf estándar. También proporciona funcionalidad para abrir fuentes personalizadas en C++."
type: docs
weight: 1200
url: /es/cpp/aspose.pdf.text/fontrepository/
---
## FontRepository class


Realiza la búsqueda de fuentes. Busca en fuentes instaladas en el sistema y fuentes [Pdf](../../aspose.pdf/) estándar. También proporciona funcionalidad para abrir fuentes personalizadas.

```cpp
class FontRepository : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| static [FindFont](./findfont/)(const System::String\&) | Busca y devuelve la fuente con el nombre de fuente especificado. |
| static [FindFont](./findfont/)(const System::String\&, bool) | Busca y devuelve la fuente con el nombre de fuente especificado, ignorando o respetando la sensibilidad a mayúsculas. |
| static [FindFont](./findfont/)(const System::String\&, FontStyles) | Busca y devuelve la fuente con el nombre de fuente y estilo de fuente especificados. |
| static [FindFont](./findfont/)(const System::String\&, FontStyles, bool) | Busca y devuelve la fuente con el nombre de fuente y estilo de fuente especificados, ignorando o respetando la sensibilidad a mayúsculas. |
| static [get_Sources](./get_sources/)() | Obtiene la colección de fuentes de origen. |
| static [get_Substitutions](./get_substitutions/)() | Obtiene la colección de estrategias de sustitución de fuentes. |
| static [LoadFonts](./loadfonts/)() | Carga fuentes instaladas en el sistema y fuentes estándar de [Pdf](../../aspose.pdf/). Este método fue diseñado para acelerar el proceso de carga de fuentes. Por defecto, las fuentes se cargan en la primera solicitud de cualquier fuente. El uso de este método carga las fuentes del sistema y las fuentes estándar de [Pdf](../../aspose.pdf/) inmediatamente antes de que se abra cualquier documento de [Pdf](../../aspose.pdf/). |
| static [OpenFont](./openfont/)(const System::SharedPtr\<System::IO::Stream\>\&, const FontTypes\&) | Abre la fuente con el flujo de fuente especificado. |
| static [OpenFont](./openfont/)(const System::String\&) | Abre la fuente con la ruta de archivo de fuente especificada. |
| static [OpenFont](./openfont/)(const System::String\&, const System::String\&) | Abre la fuente con la ruta de archivo de fuente y la ruta de archivo de métricas especificadas. |
| static [ReloadFonts](./reloadfonts/)() | Recarga todas las fuentes especificadas por la propiedad [Sources](../) |


## Ver también

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
