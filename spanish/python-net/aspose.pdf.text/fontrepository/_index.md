---
title: "FontRepository"
second_title: "Referencia de API de Aspose.PDF para Python vía .NET"
description: "Realiza la búsqueda de fuentes. Busca en fuentes instaladas en el sistema y fuentes Pdf estándar.<br/>             También proporciona funcionalidad para abrir fuentes personalizadas."
type: docs
weight: 130
url: /es/python-net/aspose.pdf.text/fontrepository/
---

## FontRepository class

Realiza la búsqueda de fuentes. Busca en fuentes instaladas en el sistema y fuentes Pdf estándar.<br/>             También proporciona funcionalidad para abrir fuentes personalizadas.

El tipo FontRepository expone los siguientes miembros:
## Constructores
| Nombre | Descripción |
| :- | :- |
| FontRepository() | Inicializa una nueva instancia de la clase FontRepository |
## Propiedades
| Nombre | Descripción |
| :- | :- |
| substitutions | Obtiene la colección de estrategias de sustitución de fuentes. |
| sources | Obtiene la colección de orígenes de fuentes. |
## Métodos
| Nombre | Descripción |
| :- | :- |
| find_font(font_name) | Busca y devuelve la fuente con el nombre de fuente especificado. |
| find_font(font_name, ignore_case) | Busca y devuelve la fuente con el nombre de fuente especificado ignorando o respetando la sensibilidad a mayúsculas. |
| find_font(font_family_name, stl) | Busca y devuelve la fuente con el nombre y estilo de fuente especificados. |
| find_font(font_family_name, stl, ignore_case) | Busca y devuelve la fuente con el nombre y estilo de fuente especificados <br/>             ignorando o respetando la sensibilidad a mayúsculas. |
| open_font(font_stream, font_type) | Abre la fuente con el flujo de fuente especificado. |
| open_font(font_file_path) | Abre la fuente con la ruta de archivo de fuente especificada. |
| open_font(font_file_path, metrics_file_path) | Abre la fuente con la ruta de archivo de fuente especificada. |
| load_fonts() | Carga fuentes instaladas en el sistema y fuentes PDF estándar. Este método fue diseñado para acelerar el proceso de carga de fuentes.<br/>            Por defecto, las fuentes se cargan en la primera solicitud de cualquier fuente. El uso de este método carga las fuentes del sistema y las fuentes PDF estándar<br/>            inmediatamente antes de que se abra cualquier documento PDF. |
| reload_fonts() | Recarga todas las fuentes especificadas por la propiedad [sources](/pdf/python-net/aspose.pdf.text/fontrepository/) |

### Ver también

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

