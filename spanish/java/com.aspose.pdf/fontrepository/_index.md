---
title: "FontRepository"
linktitle: "FontRepository"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "<p> Realiza una búsqueda de fuentes. Busca en fuentes instaladas en el sistema y fuentes estándar de Pdf. También proporciona funcionalidad para abrir fuentes personalizadas. </p> <hr> <pre> El ejemplo demuestra.</pre>"
type: docs
weight: 1690
url: /es/java/com.aspose.pdf/fontrepository/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FontRepository

```
public final class FontRepository extends Object
```

<p> Realiza una búsqueda de fuentes. Busca en fuentes instaladas en el sistema y fuentes estándar de Pdf. También proporciona funcionalidad para abrir fuentes personalizadas. </p> <hr> <pre> El ejemplo demuestra cómo encontrar una fuente y reemplazar la fuente del texto de la primera página. // Find font Font font = FontRepository.findFont("Arial"); // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> @see TextFragmentAbsorber @see IDocument

## Constructores

| Constructor | Descripción |
| --- | --- |
| [FontRepository](#FontRepository--) |  |

## Métodos

| Método | Descripción |
| --- | --- |
| [addLocalFontPath](#addLocalFontPath-java.lang.String-) | Agregue una ruta más a las fuentes. |
| [addSystemFont](#addSystemFont-com.aspose.pdf.Font-) | <p> Agrega una fuente del sistema con la fuente especificada. </p> <hr> <pre> El ejemplo demuestra cómo agregar una fuente del sistema. InputStream fontStream = new FileInputStream("C:\\\\WINDOWS\\\\Fonts\\\\arial.ttf")) Font font = FontRepository.openFont(fontStream, FontTypes.TTF); FontRepository.addSystemFont(font); </pre> |
| [clear](#clear--) |  |
| [findFont](#findFont-java.lang.String-) | <p> Busca y devuelve la fuente con el nombre de fuente especificado. </p> <hr> <pre> El ejemplo muestra cómo encontrar la fuente y reemplazar la fuente del texto de la primera página. // Buscar fuente Font font = FontRepository.findFont(\"Arial\"); // Abrir documento Document doc = new Document(\"D:\\\\Tests\\\\input.pdf\"); // Crear objeto TextFragmentAbsorber para encontrar todas las ocurrencias del texto \"hello world\" TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // Aceptar el absorber para la primera página doc.getPages().get_Item(1).accept(absorber); // Cambiar la fuente de la primera ocurrencia de texto absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Guardar documento doc.save(\"D:\\\\Tests\\\\output.pdf\"); </pre> |
| [findFont](#findFont-java.lang.String-boolean-) | <p> Busca y devuelve la fuente con el nombre de fuente especificado, ignorando o respetando la sensibilidad a mayúsculas. </p> <hr> <pre> El ejemplo muestra cómo encontrar la fuente y reemplazar la fuente del texto de la primera página. // Buscar fuente Font font = FontRepository.findFont(\"Arial\", FontStyles.Italic); // Abrir documento Document doc = new Document(\"D:\\\\Tests\\\\input.pdf\"); // Crear objeto TextFragmentAbsorber para encontrar todas las ocurrencias del texto \"hello world\" TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // Aceptar el absorber para la primera página doc.getPages().get_Item(1).accept(absorber); // Cambiar la fuente de la primera ocurrencia de texto absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Guardar documento doc.save(\"D:\\\\Tests\\\\output.pdf\"); </pre> |
| [findFont](#findFont-java.lang.String-int-) | <p> Busca y devuelve la fuente con el nombre de fuente y estilo de fuente especificados. </p> <hr> <pre> El ejemplo muestra cómo encontrar la fuente y reemplazar la fuente del texto de la primera página. // Buscar fuente Font font = FontRepository.findFont(\"Arial\", FontStyles.Italic); // Abrir documento Document doc = new Document(\"D:\\\\Tests\\\\input.pdf\"); // Crear objeto TextFragmentAbsorber para encontrar todas las ocurrencias del texto \"hello world\" TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // Aceptar el absorber para la primera página doc.getPages().get_Item(1).accept(absorber); // Cambiar la fuente de la primera ocurrencia de texto absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Guardar documento doc.save(\"D:\\\\Tests\\\\output.pdf\"); </pre> |
| [findFont](#findFont-java.lang.String-int-boolean-) | <p> Busca y devuelve la fuente con el nombre de fuente y estilo de fuente especificados, ignorando o respetando la sensibilidad a mayúsculas. </p> <hr> <pre> El ejemplo muestra cómo encontrar la fuente y reemplazar la fuente del texto de la primera página. // Buscar fuente Font font = FontRepository.findFont(\"Arial\", FontStyles.Italic, true); // Abrir documento Document doc = new Document(\"D:\\\\Tests\\\\input.pdf\"); // Crear objeto TextFragmentAbsorber para encontrar todas las ocurrencias del texto \"hello world\" TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // Aceptar el absorber para la primera página doc.getPages().get_Item(1).accept(absorber); // Cambiar la fuente de la primera ocurrencia de texto absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Guardar documento doc.save(\"D:\\\\Tests\\\\output.pdf\"); </pre> |
| [getLocalFontPaths](#getLocalFontPaths--) | Copia de la lista con los directorios de fuentes reales. |
| [getSources](#getSources--) | Obtiene la colección de fuentes. |
| [getSubstitutions](#getSubstitutions--) | Obtiene la colección de estrategias de sustitución de fuentes. |
| [isReplaceNotFoundFonts](#isReplaceNotFoundFonts--) | Las fuentes no encontradas serán reemplazadas por la fuente estándar. |
| [isThreadStaticConfigEnabled](#isThreadStaticConfigEnabled--) | <p> Devuelve el estado de la configuración del almacenamiento de fuentes. <br> Si es verdadero, se utiliza ThreadStatic y cada hilo tiene sus propias fuentes. <br> Si es falso, se utiliza una configuración estática global para todos los hilos. </p> <hr> El valor predeterminado es Verdadero. |
| [loadFonts](#loadFonts--) | Carga las fuentes instaladas en el sistema y las fuentes PDF estándar. Este método fue diseñado para acelerar el proceso de carga de fuentes. Por defecto, las fuentes se cargan en la primera solicitud de cualquier fuente. El uso de este método carga las fuentes del sistema y las fuentes PDF estándar inmediatamente antes de que se abra cualquier documento PDF. |
| [openFont](#openFont-java.io.InputStream-int-) | <p> Abre la fuente con el flujo de fuente especificado. </p> <hr> <pre> El ejemplo muestra cómo abrir la fuente y reemplazar la fuente del texto de la primera página. // Abrir fuente InputStream fontStream = new FileInputStream("C:\\\\WINDOWS\\\\Fonts\\\\arial.ttf")) { Font font = FontRepository.openFont(fontStream, , FontTypes.TTF); // Abrir documento Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Crear objeto TextFragmentAbsorber para encontrar todas las ocurrencias del texto "hello world" TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Aceptar el absorber para la primera página doc.getPages().get_Item(1).accept(absorber); // Cambiar la fuente de la primera ocurrencia de texto absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Guardar documento doc.save("D:\\\\Tests\\\\output.pdf"); } </pre> |
| [openFont](#openFont-java.lang.String-) | <p> Abre la fuente con la ruta de archivo de fuente especificada. </p> <hr> <pre> El ejemplo muestra cómo abrir la fuente y reemplazar la fuente del texto de la primera página. // Abrir fuente Font font = FontRepository.openFont("C:\\\\WINDOWS\\\\Fonts\\\\arial.ttf"); // Abrir documento Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Crear objeto TextFragmentAbsorber para encontrar todas las ocurrencias del texto "hello world" TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Aceptar el absorber para la primera página doc.getPages().get_Item(1).accept(absorber); // Cambiar la fuente de la primera ocurrencia de texto absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Guardar documento doc.save("D:\\\\Tests\\\\output.pdf"); </pre> |
| [openFont](#openFont-java.lang.String-java.lang.String-) | <p> Abre la fuente con la ruta de archivo de fuente y la ruta del archivo de métricas especificadas. </p> <hr> <pre> El ejemplo muestra cómo abrir una fuente Type1 con métricas y reemplazar la fuente del texto de la primera página. // Abrir fuente Font font = FontRepository.openFont("courier.pfb", "courier.afm"); // Abrir documento Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Crear objeto TextFragmentAbsorber para encontrar todas las ocurrencias del texto "hello world" TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Aceptar el absorber para la primera página doc.getPages().get_Item(1).accept(absorber); // Cambiar la fuente de la primera ocurrencia de texto absorber.getTextFragments().get_Item(1).sgetTextState().setFont(font); // Guardar documento doc.save("D:\\\\Tests\\\\output.pdf"); </pre> |
| [reloadFonts](#reloadFonts--) | Recarga todas las fuentes especificadas por la propiedad {@code Sources}({@link #getSources}) |
| [restoreLocalFontPath](#restoreLocalFontPath--) | Restablece la lista de directorios de fuentes estándar por defecto. |
| [setLocalFontPaths](#setLocalFontPaths-java.util.List-) | Establece la lista de usuario con rutas de fuentes |
| [setReplaceNotFoundFonts](#setReplaceNotFoundFonts-boolean-) | Establezca TRUE si necesita reemplazar fuentes no encontradas con la fuente predeterminada. El valor predeterminado es false. |
| [setThreadStaticConfigEnabled](#setThreadStaticConfigEnabled-boolean-) | Opción para configurar el almacenamiento de Font Sources. Si es true, se usa ThreadStatic y cada hilo tiene sus propios Font Sources. Si es false, se usa una configuración estática global para todos los hilos. |

### FontRepository {#FontRepository--}
```
public FontRepository()
```



### addLocalFontPath {#addLocalFontPath-java.lang.String-}
Agregue una ruta más a las fuentes.

### addSystemFont {#addSystemFont-com.aspose.pdf.Font-}
<p> Añadir fuente del sistema con la fuente especificada. </p> <hr> <pre> El ejemplo muestra cómo añadir una fuente del sistema. InputStream fontStream = new FileInputStream("C:\\WINDOWS\\Fonts\\arial.ttf")) Font font = FontRepository.openFont(fontStream, FontTypes.TTF); FontRepository.addSystemFont(font); </pre>

### clear {#clear--}
```
public static void clear()
```



### findFont {#findFont-java.lang.String-}
<p> Busca y devuelve la fuente con el nombre de fuente especificado. </p> <hr> <pre> El ejemplo muestra cómo encontrar la fuente y reemplazar la fuente del texto de la primera página. // Encontrar fuente Font font = FontRepository.findFont("Arial"); // Abrir documento Document doc = new Document("D:\\Tests\\input.pdf"); // Crear objeto TextFragmentAbsorber para encontrar todas las ocurrencias del texto "hello world" TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Aceptar el absorber para la primera página doc.getPages().get_Item(1).accept(absorber); // Cambiar la fuente de la primera ocurrencia de texto absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Guardar documento doc.save("D:\\Tests\\output.pdf"); </pre>

### findFont {#findFont-java.lang.String-boolean-}
<p> Busca y devuelve la fuente con el nombre de fuente especificado, ignorando o respetando la distinción entre mayúsculas y minúsculas. </p> <hr> <pre> El ejemplo muestra cómo encontrar la fuente y reemplazar la fuente del texto de la primera página. // Find font Font font = FontRepository.findFont("Arial", FontStyles.Italic); // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurence absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Save document doc.save("D:\\Tests\\output.pdf"); </pre>

### findFont {#findFont-java.lang.String-int-}
<p> Busca y devuelve la fuente con el nombre de fuente y estilo de fuente especificados. </p> <hr> <pre> El ejemplo muestra cómo encontrar la fuente y reemplazar la fuente del texto de la primera página. // Find font Font font = FontRepository.findFont("Arial", FontStyles.Italic); // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurence absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Save document doc.save("D:\\Tests\\output.pdf"); </pre>

### findFont {#findFont-java.lang.String-int-boolean-}
<p> Busca y devuelve la fuente con el nombre de fuente y estilo de fuente especificados, ignorando o respetando la distinción entre mayúsculas y minúsculas. </p> <hr> <pre> El ejemplo muestra cómo encontrar la fuente y reemplazar la fuente del texto de la primera página. // Find font Font font = FontRepository.findFont("Arial", FontStyles.Italic, true); // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurence absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Save document doc.save("D:\\Tests\\output.pdf"); </pre>

### getLocalFontPaths {#getLocalFontPaths--}
```
public static List < String > getLocalFontPaths()
```

Copia de la lista con los directorios de fuentes reales.

**Returns:**
lista de String

### getSources {#getSources--}
```
public static FontSourceCollection getSources()
```

Obtiene la colección de fuentes.

**Returns:**
objeto FontSourceCollection

### getSubstitutions {#getSubstitutions--}
```
public static FontSubstitutionCollection getSubstitutions()
```

Obtiene la colección de estrategias de sustitución de fuentes.

**Returns:**
objeto FontSubstitutionCollection

### isReplaceNotFoundFonts {#isReplaceNotFoundFonts--}
```
public static boolean isReplaceNotFoundFonts()
```

Las fuentes no encontradas serán reemplazadas por la fuente estándar.

**Returns:**
valor booleano

### isThreadStaticConfigEnabled {#isThreadStaticConfigEnabled--}
```
public static boolean isThreadStaticConfigEnabled()
```

<p> Devuelve el estado de la configuración del almacenamiento de fuentes. <br> Si es verdadero, se utiliza ThreadStatic y cada hilo tiene sus propias fuentes. <br> Si es falso, se utiliza una configuración estática global para todos los hilos. </p> <hr> El valor predeterminado es Verdadero.

**Returns:**
valor booleano

### loadFonts {#loadFonts--}
```
public static void loadFonts()
```

Carga las fuentes instaladas en el sistema y las fuentes PDF estándar. Este método fue diseñado para acelerar el proceso de carga de fuentes. Por defecto, las fuentes se cargan en la primera solicitud de cualquier fuente. El uso de este método carga las fuentes del sistema y las fuentes PDF estándar inmediatamente antes de que se abra cualquier documento PDF.

### openFont {#openFont-java.io.InputStream-int-}
<p> Abre la fuente con el flujo de fuente especificado. </p> <hr> <pre> El ejemplo muestra cómo abrir la fuente y reemplazar la fuente del texto de la primera página. // Open font InputStream fontStream = new FileInputStream("C:\\WINDOWS\\Fonts\\arial.ttf")) { Font font = FontRepository.openFont(fontStream, , FontTypes.TTF); // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Save document doc.save("D:\\Tests\\output.pdf"); } </pre>

### openFont {#openFont-java.lang.String-}
<p> Abre la fuente con la ruta de archivo de fuente especificada. </p> <hr> <pre> El ejemplo muestra cómo abrir la fuente y reemplazar la fuente del texto de la primera página. // Open font Font font = FontRepository.openFont("C:\\WINDOWS\\Fonts\\arial.ttf"); // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Save document doc.save("D:\\Tests\\output.pdf"); </pre>

### openFont {#openFont-java.lang.String-java.lang.String-}
<p> Abre la fuente con la ruta de archivo de fuente especificada y la ruta del archivo de métricas. </p> <hr> <pre> El ejemplo muestra cómo abrir una fuente Type1 con métricas y reemplazar la fuente del texto de la primera página. // Abrir fuente Font font = FontRepository.openFont(\"courier.pfb\", \"courier.afm\"); // Abrir documento Document doc = new Document(\"D:\\\\Tests\\\\input.pdf\"); // Crear objeto TextFragmentAbsorber para encontrar todas las ocurrencias del texto \"hello world\" TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // Aceptar el absorber para la primera página doc.getPages().get_Item(1).accept(absorber); // Cambiar la fuente de la primera ocurrencia de texto absorber.getTextFragments().get_Item(1).sgetTextState().setFont(font); // Guardar documento doc.save(\"D:\\\\Tests\\\\output.pdf\"); </pre>

### reloadFonts {#reloadFonts--}
```
public static void reloadFonts()
```

Recarga todas las fuentes especificadas por la propiedad {@code Sources}({@link #getSources})

### restoreLocalFontPath {#restoreLocalFontPath--}
```
public static void restoreLocalFontPath()
```

Restablece la lista de directorios de fuentes estándar por defecto.

### setLocalFontPaths {#setLocalFontPaths-java.util.List-}
Establece la lista de usuario con rutas de fuentes

### setReplaceNotFoundFonts {#setReplaceNotFoundFonts-boolean-}
```
public static void setReplaceNotFoundFonts(boolean value)
```

Establezca TRUE si necesita reemplazar fuentes no encontradas con la fuente predeterminada. El valor predeterminado es false.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | boolean |

### setThreadStaticConfigEnabled {#setThreadStaticConfigEnabled-boolean-}
```
public static void setThreadStaticConfigEnabled(boolean isTheadLocal)
```

Opción para configurar el almacenamiento de Font Sources. Si es true, se usa ThreadStatic y cada hilo tiene sus propios Font Sources. Si es false, se usa una configuración estática global para todos los hilos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| isTheadLocal |  | valor booleano |
