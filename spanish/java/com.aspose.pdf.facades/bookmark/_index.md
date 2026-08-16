---
title: "Bookmark"
linktitle: "Bookmark"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa un marcador."
type: docs
weight: 60
url: /es/java/com.aspose.pdf.facades/bookmark/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Bookmark

```
public final class Bookmark extends Object
```

Representa un marcador.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [Bookmark](#Bookmark--) | Inicializa una nueva instancia de la clase {@code Bookmark}. |

## Métodos

| Método | Descripción |
| --- | --- |
| [getAction](#getAction--) | Obtiene la acción vinculada al marcador. Si se presenta PageNumber, la acción no puede especificarse. El tipo de acción incluye: "GoTo", "GoToR", "Launch", "Named". |
| [getBoldFlag](#getBoldFlag--) | Obtiene la bandera de negrita del título del marcador. |
| [getChildItem](#getChildItem--) | Obtiene los hijos del marcador. Obsoleto("Use getChildItems() property instead of this one.") |
| [getChildItems](#getChildItems--) | Obtiene los hijos del marcador. |
| [getCustomAcorbatViewerMenuActionName](#getCustomAcorbatViewerMenuActionName--) | Aún no soportado. El nombre de acción correspondiente para ejecutar un elemento del menú en el visor Acrobat. |
| [getDestination](#getDestination--) | Obtiene la página de destino del marcador. Requerido si la acción se establece como "". |
| [getItalicFlag](#getItalicFlag--) | Obtiene la bandera de cursiva del título del marcador. |
| [getLevel](#getLevel--) | Obtiene el nivel jerárquico del marcador. |
| [getPageDisplay_Bottom](#getPageDisplay_Bottom--) | Obtiene la coordenada inferior de la visualización de la página. |
| [getPageDisplay_Left](#getPageDisplay_Left--) | Obtiene la coordenada izquierda de la visualización de la página. |
| [getPageDisplay_Right](#getPageDisplay_Right--) | Obtiene la coordenada derecha de la visualización de la página. |
| [getPageDisplay_Top](#getPageDisplay_Top--) | Obtiene la coordenada superior de la visualización de la página. |
| [getPageDisplay_Zoom](#getPageDisplay_Zoom--) | Obtiene el factor de zoom de la visualización de la página. |
| [getPageDisplay](#getPageDisplay--) | Obtiene el tipo de página de destino del marcador de visualización. |
| [getPageNumber](#getPageNumber--) | Obtiene el número de página de destino del marcador. |
| [getRemoteFile](#getRemoteFile--) | Obtiene el archivo (ruta) que se requiere para la acción "GoToR" del marcador. |
| [getTitle](#getTitle--) | Obtiene el título del marcador. |
| [getTitleColor](#getTitleColor--) | Obtiene el color del título del marcador. |
| [isOpen](#isOpen--) | Obtiene el estado del marcador (abierto, cerrado). |
| [setAction](#setAction-java.lang.String-) | Establece la acción vinculada al marcador. Si se presenta PageNumber, la acción no puede especificarse. El tipo de acción incluye: "GoTo", "GoToR", "Launch", "Named". |
| [setBoldFlag](#setBoldFlag-boolean-) | Establece la bandera de negrita del título del marcador. |
| [setChildItem](#setChildItem-com.aspose.pdf.facades.Bookmarks-) | Establece los hijos del marcador. Obsolete("Use setChildItems() property instead of this one.") |
| [setChildItems](#setChildItems-com.aspose.pdf.facades.Bookmarks-) | Establece los hijos del marcador. |
| [setCustomAcorbatViewerMenuActionName](#setCustomAcorbatViewerMenuActionName-int:A-) | Aún no soportado. Establece el nombre de la acción correspondiente para ejecutar un elemento de menú en el visor Acrobat. |
| [setDestination](#setDestination-java.lang.String-) | Establece la página de destino del marcador. Requerido si la acción se establece como "". |
| [setItalicFlag](#setItalicFlag-boolean-) | Establece la bandera de cursiva del título del marcador. |
| [setLevel](#setLevel-int-) | Establece el nivel jerárquico del marcador. |
| [setOpen](#setOpen-boolean-) | Establece el estado del marcador (abierto, cerrado). |
| [setPageDisplay_Bottom](#setPageDisplay_Bottom-int-) | Establece la coordenada inferior de la visualización de la página. |
| [setPageDisplay_Left](#setPageDisplay_Left-int-) | Establece la coordenada izquierda de la visualización de la página. |
| [setPageDisplay_Right](#setPageDisplay_Right-int-) | Establece la coordenada derecha de la visualización de la página. |
| [setPageDisplay_Top](#setPageDisplay_Top-int-) | Establece la coordenada superior de la visualización de la página. |
| [setPageDisplay_Zoom](#setPageDisplay_Zoom-int-) | Establece el factor de zoom de la visualización de la página. |
| [setPageDisplay](#setPageDisplay-java.lang.String-) | Establece el tipo de página de destino del marcador de visualización. |
| [setPageNumber](#setPageNumber-int-) | Establece el número de página de destino del marcador. |
| [setRemoteFile](#setRemoteFile-java.lang.String-) | Establece el archivo (ruta) que se requiere para la acción "GoToR" del marcador. |
| [setTitle](#setTitle-java.lang.String-) | Establece el título del marcador. |
| [setTitleColor](#setTitleColor-java.awt.Color-) | Establece el color del título del marcador. |
| [toOutlineItemCollection](#toOutlineItemCollection-com.aspose.pdf.IDocument-) | convertir a OutlineItemCollection |

### Bookmark {#Bookmark--}
```
public Bookmark()
```

Inicializa una nueva instancia de la clase {@code Bookmark}.

### getAction {#getAction--}
```
public String getAction()
```

Obtiene la acción vinculada al marcador. Si se presenta PageNumber, la acción no puede especificarse. El tipo de acción incluye: "GoTo", "GoToR", "Launch", "Named".

**Returns:**
valor String

### getBoldFlag {#getBoldFlag--}
```
public boolean getBoldFlag()
```

Obtiene la bandera de negrita del título del marcador.

**Returns:**
valor booleano

### getChildItem {#getChildItem--}
```
@Deprecated public Bookmarks getChildItem()
```

Obtiene los hijos del marcador. Obsoleto("Use getChildItems() property instead of this one.")

**Returns:**
Elemento Bookmarks

### getChildItems {#getChildItems--}
```
public Bookmarks getChildItems()
```

Obtiene los hijos del marcador.

**Returns:**
elementos hijos del marcador.

### getCustomAcorbatViewerMenuActionName {#getCustomAcorbatViewerMenuActionName--}
```
public int[] getCustomAcorbatViewerMenuActionName()
```

Aún no soportado. El nombre de acción correspondiente para ejecutar un elemento del menú en el visor Acrobat.

**Returns:**
matriz de valores int

### getDestination {#getDestination--}
```
public String getDestination()
```

Obtiene la página de destino del marcador. Requerido si la acción se establece como "".

**Returns:**
valor String

### getItalicFlag {#getItalicFlag--}
```
public boolean getItalicFlag()
```

Obtiene la bandera de cursiva del título del marcador.

**Returns:**
valor booleano

### getLevel {#getLevel--}
```
public int getLevel()
```

Obtiene el nivel jerárquico del marcador.

**Returns:**
valor int

### getPageDisplay_Bottom {#getPageDisplay_Bottom--}
```
public int getPageDisplay_Bottom()
```

Obtiene la coordenada inferior de la visualización de la página.

**Returns:**
valor int

### getPageDisplay_Left {#getPageDisplay_Left--}
```
public int getPageDisplay_Left()
```

Obtiene la coordenada izquierda de la visualización de la página.

**Returns:**
valor int

### getPageDisplay_Right {#getPageDisplay_Right--}
```
public int getPageDisplay_Right()
```

Obtiene la coordenada derecha de la visualización de la página.

**Returns:**
valor int

### getPageDisplay_Top {#getPageDisplay_Top--}
```
public int getPageDisplay_Top()
```

Obtiene la coordenada superior de la visualización de la página.

**Returns:**
valor int

### getPageDisplay_Zoom {#getPageDisplay_Zoom--}
```
public int getPageDisplay_Zoom()
```

Obtiene el factor de zoom de la visualización de la página.

**Returns:**
valor int

### getPageDisplay {#getPageDisplay--}
```
public String getPageDisplay()
```

Obtiene el tipo de página de destino del marcador de visualización.

**Returns:**
valor String

### getPageNumber {#getPageNumber--}
```
public int getPageNumber()
```

Obtiene el número de página de destino del marcador.

**Returns:**
valor int

### getRemoteFile {#getRemoteFile--}
```
public String getRemoteFile()
```

Obtiene el archivo (ruta) que se requiere para la acción "GoToR" del marcador.

**Returns:**
valor String

### getTitle {#getTitle--}
```
public String getTitle()
```

Obtiene el título del marcador.

**Returns:**
valor String

### getTitleColor {#getTitleColor--}
```
public Color getTitleColor()
```

Obtiene el color del título del marcador.

**Returns:**
Elemento de color

### isOpen {#isOpen--}
```
public boolean isOpen()
```

Obtiene el estado del marcador (abierto, cerrado).

**Returns:**
valor booleano

### setAction {#setAction-java.lang.String-}
Establece la acción vinculada al marcador. Si se presenta PageNumber, la acción no puede especificarse. El tipo de acción incluye: "GoTo", "GoToR", "Launch", "Named".

### setBoldFlag {#setBoldFlag-boolean-}
```
public void setBoldFlag(boolean value)
```

Establece la bandera de negrita del título del marcador.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setChildItem {#setChildItem-com.aspose.pdf.facades.Bookmarks-}
Establece los hijos del marcador. Obsolete("Use setChildItems() property instead of this one.")

### setChildItems {#setChildItems-com.aspose.pdf.facades.Bookmarks-}
Establece los hijos del marcador.

### setCustomAcorbatViewerMenuActionName {#setCustomAcorbatViewerMenuActionName-int:A-}
```
public void setCustomAcorbatViewerMenuActionName(int[] value)
```

Aún no soportado. Establece el nombre de la acción correspondiente para ejecutar un elemento de menú en el visor Acrobat.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | matriz de valores int |

### setDestination {#setDestination-java.lang.String-}
Establece la página de destino del marcador. Requerido si la acción se establece como "".

### setItalicFlag {#setItalicFlag-boolean-}
```
public void setItalicFlag(boolean value)
```

Establece la bandera de cursiva del título del marcador.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setLevel {#setLevel-int-}
```
public void setLevel(int value)
```

Establece el nivel jerárquico del marcador.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int |

### setOpen {#setOpen-boolean-}
```
public void setOpen(boolean value)
```

Establece el estado del marcador (abierto, cerrado).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setPageDisplay_Bottom {#setPageDisplay_Bottom-int-}
```
public void setPageDisplay_Bottom(int value)
```

Establece la coordenada inferior de la visualización de la página.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int |

### setPageDisplay_Left {#setPageDisplay_Left-int-}
```
public void setPageDisplay_Left(int value)
```

Establece la coordenada izquierda de la visualización de la página.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int |

### setPageDisplay_Right {#setPageDisplay_Right-int-}
```
public void setPageDisplay_Right(int value)
```

Establece la coordenada derecha de la visualización de la página.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int |

### setPageDisplay_Top {#setPageDisplay_Top-int-}
```
public void setPageDisplay_Top(int value)
```

Establece la coordenada superior de la visualización de la página.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int |

### setPageDisplay_Zoom {#setPageDisplay_Zoom-int-}
```
public void setPageDisplay_Zoom(int value)
```

Establece el factor de zoom de la visualización de la página.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int |

### setPageDisplay {#setPageDisplay-java.lang.String-}
Establece el tipo de página de destino del marcador de visualización.

### setPageNumber {#setPageNumber-int-}
```
public void setPageNumber(int value)
```

Establece el número de página de destino del marcador.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int |

### setRemoteFile {#setRemoteFile-java.lang.String-}
Establece el archivo (ruta) que se requiere para la acción "GoToR" del marcador.

### setTitle {#setTitle-java.lang.String-}
Establece el título del marcador.

### setTitleColor {#setTitleColor-java.awt.Color-}
Establece el color del título del marcador.

### toOutlineItemCollection {#toOutlineItemCollection-com.aspose.pdf.IDocument-}
convertir a OutlineItemCollection
