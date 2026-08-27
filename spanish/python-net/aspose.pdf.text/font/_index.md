---
title: "Font"
second_title: "Referencia de API de Aspose.PDF para Python vía .NET"
description: "Representa un objeto de fuente."
type: docs
weight: 100
url: /es/python-net/aspose.pdf.text/font/
---

## Font class

Representa un objeto de fuente.

El tipo Font expone los siguientes miembros:
## Propiedades
| Nombre | Descripción |
| :- | :- |
| font_name | Obtiene el nombre de la fuente del objeto [Font](/pdf/python-net/aspose.pdf.text/font/). |
| decoded_font_name | A veces las fuentes PDF (generalmente fuentes chinas/japonesas/coreanas) pueden tener un nombre de fuente específico.<br/>            Este nombre es el valor de la propiedad de fuente PDF "BaseFont" y a veces esta propiedad<br/>            puede representarse en forma hexadecimal. Si se lee este nombre directamente, podría aparecer<br/>            en forma no legible. Para obtener una forma legible es necesario decodificar el nombre de la fuente<br/>            según reglas específicas para esa fuente. <br/>            Esta propiedad devuelve el nombre de fuente decodificado, así que úsela en los casos en que se encuentre <br/>            con un [font_name](/pdf/python-net/aspose.pdf.text/font/) no legible.<br/>            Si la propiedad [font_name](/pdf/python-net/aspose.pdf.text/font/) tiene una forma legible, esta propiedad será la misma que <br/>            [font_name](/pdf/python-net/aspose.pdf.text/font/), por lo que puede usar esta propiedad en cualquier caso en que necesite<br/>            obtener el nombre de la fuente en una forma legible. |
| base_font | Obtiene el valor BaseFont del objeto de fuente PDF. También conocido como el nombre PostScript de la fuente. |
| is_embedded | Obtiene o establece un valor que indica si la fuente está incrustada.<br/>            La fuente basada en IFont se subestablecerá y se incrustará automáticamente |
| is_subset | Obtiene o establece un valor que indica si la fuente es un subconjunto.<br/>             La fuente basada en IFont se subestablecerá y se incrustará automáticamente |
| is_accessible | Obtiene un indicador de si la fuente está presente (instalada) en el sistema. |
| font_options | Propiedades útiles para ajustar el comportamiento de Font |
## Métodos
| Nombre | Descripción |
| :- | :- |
| get_last_font_embedding_error() | El objetivo de este método es devolver la descripción del error si un intento<br/>            de incrustar la fuente falló. Si no hay casos de error, devuelve una cadena vacía. |
| save(stream) | Guarda la fuente en el flujo.<br/>            Tenga en cuenta que la fuente se guarda en formato TTF intermedio destinado a usarse solo en una copia convertida del documento original.<br/>            El archivo de fuente no está destinado a usarse fuera del contexto del documento original. |
| measure_string(str, font_size) | Mide la cadena. |

### Ver también

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

