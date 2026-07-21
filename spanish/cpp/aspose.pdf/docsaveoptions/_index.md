---
title: "Aspose::Pdf::DocSaveOptions class"
linktitle: "DocSaveOptions"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::DocSaveOptions class. Opciones de guardado para exportar al formato Doc en C++."
type: docs
weight: 3800
url: /es/cpp/aspose.pdf/docsaveoptions/
---
## DocSaveOptions class


Opciones de guardado para exportar al formato Doc.

```cpp
class DocSaveOptions : public Aspose::Pdf::UnifiedSaveOptions,
                       public Aspose::Pdf::IPipelineOptions
```

## Enums

| Enumeración | Descripción |
| --- | --- |
| [DocFormat](./docformat/) | Permite especificar el formato de archivo .doc o .docx. |
| [RecognitionMode](./recognitionmode/) | Permite controlar cómo se convierte un documento PDF en un documento de procesamiento de texto. |
## Métodos

| Método | Descripción |
| --- | --- |
| [DocSaveOptions](./docsaveoptions/)() | Constructor. |
| [get_AddReturnToLineEnd](./get_addreturntolineend/)() const | Utiliza saltos de párrafo o de línea. |
| [get_BatchSize](./get_batchsize/)() override | Define el tamaño del lote si la conversión por lotes es aplicable al par de formatos de origen y destino. |
| [get_ConvertType3Fonts](./get_converttype3fonts/)() const | Obtiene la conversión para fuentes Type3. En fuentes Type 3, los glifos deben definirse mediante flujos de operadores gráficos. Esto significa que en la salida DOC/DOCX vemos imágenes en lugar de texto. Establezca este indicador en true para convertir fuentes Type3 a TTF y obtener texto en el archivo resultante. |
| [get_Format](./get_format/)() const | Formato de salida. |
| [get_ImageResolutionX](./get_imageresolutionx/)() const | Resolución X de las imágenes convertidas. |
| [get_ImageResolutionY](./get_imageresolutiony/)() const | Resolución Y de las imágenes convertidas. |
| [get_MaxDistanceBetweenTextLines](./get_maxdistancebetweentextlines/)() const | Este parámetro se usa para agrupar líneas de texto en párrafos. Determina cuán separadas pueden estar dos líneas de texto relativas. Se especifica en cientos de por ciento de la altura de las líneas de texto. |
| [get_MemorySaveModePath](./get_memorysavemodepath/)() const | Define la ruta (nombre de archivo o de directorio) para almacenar datos temporales al convertir en modo de guardado en memoria. |
| [get_Mode](./get_mode/)() const | Modo de reconocimiento. |
| [get_RecognizeBullets](./get_recognizebullets/)() const | Activar el reconocimiento de viñetas. |
| [get_RelativeHorizontalProximity](./get_relativehorizontalproximity/)() const | En [Pdf](../) las palabras pueden estar representadas internamente con operadores que imprimen palabras al imprimir independientemente sus letras o sílabas. Por lo tanto, para detectar palabras a veces necesitamos detectar grupos de caracteres independientes que en realidad son palabras. Esta configuración define el ancho del espacio entre los elementos de texto (letras, sílabas) que debe tratarse como distancia entre palabras durante el reconocimiento de palabras en el PDF de origen. (La presencia de un espacio vacío al menos con este ancho entre letras indica que los elementos textuales pertenecen a palabras diferentes). Está normalizado al tamaño de la fuente: 1.0 significa el 100 % del supuesto tamaño de fuente de la palabra. ¡ATENCIÓN! Se usa solo en casos en que el PDF de origen contiene fuentes específicas de uso raro para las que no se puede calcular un valor óptimo a partir de la fuente. Así, en la gran mayoría de los casos este parámetro no cambia nada en el documento resultante. |
| [get_ReSaveFonts](./get_resavefonts/)() const | Obtiene el procedimiento para volver a guardar fuentes. Si se establece en true, recargamos las fuentes en cada página para evitar la influencia de propiedades de fuentes anteriores y cargamos la fuente recién creada desde cero. Establezca esta opción en false si desea mejorar el rendimiento. El valor predeterminado es true;. |
| [set_AddReturnToLineEnd](./set_addreturntolineend/)(bool) | Utiliza saltos de párrafo o de línea. |
| [set_BatchSize](./set_batchsize/)(int32_t) override | Define el tamaño del lote si la conversión por lotes es aplicable al par de formatos de origen y destino. |
| [set_ConvertType3Fonts](./set_converttype3fonts/)(bool) | Establece la conversión para fuentes Type3. En fuentes Type 3, los glifos deben definirse mediante flujos de operadores gráficos. Esto significa que en la salida DOC/DOCX vemos imágenes en lugar de texto. Establezca este indicador en true para convertir fuentes Type3 a TTF y obtener texto en el archivo resultante. |
| [set_Format](./set_format/)(DocSaveOptions::DocFormat) | Formato de salida. |
| [set_ImageResolutionX](./set_imageresolutionx/)(int32_t) | Resolución X de las imágenes convertidas. |
| [set_ImageResolutionY](./set_imageresolutiony/)(int32_t) | Resolución Y de las imágenes convertidas. |
| [set_MaxDistanceBetweenTextLines](./set_maxdistancebetweentextlines/)(float) | Este parámetro se usa para agrupar líneas de texto en párrafos. Determina cuán separadas pueden estar dos líneas de texto relativas. Se especifica en cientos de por ciento de la altura de las líneas de texto. |
| [set_MemorySaveModePath](./set_memorysavemodepath/)(const System::String\&) | Define la ruta (nombre de archivo o de directorio) para almacenar datos temporales al convertir en modo de guardado en memoria. |
| [set_Mode](./set_mode/)(DocSaveOptions::RecognitionMode) | Modo de reconocimiento. |
| [set_RecognizeBullets](./set_recognizebullets/)(bool) | Activar el reconocimiento de viñetas. |
| [set_RelativeHorizontalProximity](./set_relativehorizontalproximity/)(float) | En [Pdf](../) las palabras pueden estar representadas internamente con operadores que imprimen palabras al imprimir independientemente sus letras o sílabas. Por lo tanto, para detectar palabras a veces necesitamos detectar grupos de caracteres independientes que en realidad son palabras. Esta configuración define el ancho del espacio entre los elementos de texto (letras, sílabas) que debe tratarse como distancia entre palabras durante el reconocimiento de palabras en el PDF de origen. (La presencia de un espacio vacío al menos con este ancho entre letras indica que los elementos textuales pertenecen a palabras diferentes). Está normalizado al tamaño de la fuente: 1.0 significa el 100 % del supuesto tamaño de fuente de la palabra. ¡ATENCIÓN! Se usa solo en casos en que el PDF de origen contiene fuentes específicas de uso raro para las que no se puede calcular un valor óptimo a partir de la fuente. Así, en la gran mayoría de los casos este parámetro no cambia nada en el documento resultante. |
| [set_ReSaveFonts](./set_resavefonts/)(bool) | Establece el procedimiento para volver a guardar fuentes. Si se establece en true, recargamos las fuentes en cada página para evitar la influencia de las propiedades de fuentes anteriores y cargamos la fuente recién creada desde cero. Establece esta opción en false si deseas mejorar el rendimiento. El valor predeterminado es true;. |
## Ver también

* Class [UnifiedSaveOptions](../unifiedsaveoptions/)
* Class [IPipelineOptions](../ipipelineoptions/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
