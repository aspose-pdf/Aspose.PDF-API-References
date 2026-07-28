---
title: "DocumentPrivilege"
linktitle: "DocumentPrivilege"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa los privilegios para acceder al archivo Pdf. Consulte{@code PdfFileSecurity}. Hay 4 formas de usar esta clase: 1.Usando privilegio predefinido directamente. 2.Basado en un."
type: docs
weight: 110
url: /es/java/com.aspose.pdf.facades/documentprivilege/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.DocumentPrivilege

**All Implemented Interfaces:**
Comparable < Object >

```
public final class DocumentPrivilege extends Object implements Comparable < Object >
```

Representa los privilegios para acceder a un archivo Pdf. Consulte {@code PdfFileSecurity}. Hay 4 formas de usar esta clase: 1.Usar un privilegio predefinido directamente. 2.Basado en un privilegio predefinido y cambiar algunos permisos específicos. 3.Basado en un privilegio predefinido y cambiar una combinación específica de permisos de Adobe Professional. 4.Mezcla la forma 2 y la forma 3. //Way1: Usando privilegio predefinido directamente. DocumentPrivilege privilege = DocumentPrivilege.getPrint(); //Way2: Basado en un privilegio predefinido y cambiar algunos permisos específicos. DocumentPrivilege privilege = DocumentPrivilege.getAllowAll(); privilege.setAllowPrint(false); privilege.setAllowModifyContents(false); //Way3: Basado en un privilegio predefinido y cambiar una combinación específica de permisos de Adobe Professional. DocumentPrivilege privilege = DocumentPrivilege.getForbidAll(); privilege.setChangeAllowLevel(1); privilege.setPrintAllowLevel(2); //Way4: Mezcla la forma 2 y la forma 3 DocumentPrivilege privilege = DocumentPrivilege.getForbidAll(); privilege.setChangeAllowLevel(1); privilege.setAllowPrint(true);

## Métodos

| Método | Descripción |
| --- | --- |
| [compareTo](#compareTo-java.lang.Object-) | Compara dos objetos {@code DocumentPrivilege}. |
| [equals](#equals-java.lang.Object-) | Indica si algún otro objeto es "igual a" este. <p> El método <code>equals</code> implementa una relación de equivalencia sobre referencias de objetos no nulas: <ul> <li>Es <i>reflexivo</i>: para cualquier valor de referencia no nulo <code>x</code>, <code>x.equals(x)</code> debe devolver <code>true</code>. <li>Es <i>simétrico</i>: para cualquier valor de referencia no nulo <code>x</code> y <code>y</code>, <code>x.equals(y)</code> debe devolver <code>true</code> si y solo si <code>y.equals(x)</code> devuelve <code>true</code>. <li>Es <i>transitivo</i>: para cualquier valor de referencia no nulo <code>x</code>, <code>y</code> y <code>z</code>, si <code>x.equals(y)</code> devuelve <code>true</code> y <code>y.equals(z)</code> devuelve <code>true</code>, entonces <code>x.equals(z)</code> debe devolver <code>true</code>. <li>Es <i>consistente</i>: para cualquier valor de referencia no nulo <code>x</code> y <code>y</code>, múltiples invocaciones de <tt>x.equals(y)</tt> devuelven consistentemente <code>true</code> o consistentemente <code>false</code>, siempre que no se modifique la información utilizada en comparaciones <code>equals</code> de los objetos. <li>Para cualquier valor de referencia no nulo <code>x</code>, <code>x.equals(null)</code> debe devolver <code>false</code>. </ul> <p> El método <tt>equals</tt> para la clase <code>Object</code> implementa la relación de equivalencia más discriminatoria posible sobre los objetos; es decir, para cualquier valor de referencia no nulo <code>x</code> y <code>y</code>, este método devuelve <code>true</code> si y solo si <code>x</code> y <code>y</code> hacen referencia al mismo objeto (<code>x == y</code> tiene el valor <code>true</code>). <p> Tenga en cuenta que generalmente es necesario sobrescribir el método <tt>hashCode</tt> siempre que se sobrescriba este método, para mantener el contrato general del método <tt>hashCode</tt>, que establece que los objetos iguales deben tener códigos hash iguales. |
| [getAllowAll](#getAllowAll--) | Todo permitido. |
| [getAssembly](#getAssembly--) | Permite ensamblar el archivo. |
| [getChangeAllowLevel](#getChangeAllowLevel--) | Obtiene y establece el nivel de cambios del privilegio del documento. Igual que la configuración Cambios Permitidos de Adobe Professional. 0: Ninguno. 1: Insertar, eliminar y rotar páginas. 2: Rellenar campos de formulario y firmar campos de firma existentes. 3: Comentar, rellenar campos de formulario y firmar campos de firma existentes. 4: Cualquier acción excepto extraer páginas. Si la propiedad tiene un valor de -1, el nivel está indefinido. |
| [getCopy](#getCopy--) | Permite copiar el archivo. |
| [getCopyAllowLevel](#getCopyAllowLevel--) | Obtiene y establece el nivel de copia del privilegio del documento. Igual que la configuración de permisos de Adobe Professional. 0: Ninguno. 1: Habilitar acceso de texto para dispositivos de lectura de pantalla para personas con discapacidad visual. 2: Habilitar la copia de texto, imágenes y otro contenido. Si la propiedad tiene un valor de -1, el nivel está indefinido. |
| [getDegradedPrinting](#getDegradedPrinting--) | Permite impresión degradada. |
| [getFillIn](#getFillIn--) | Permite rellenar formularios en el archivo. |
| [getForbidAll](#getForbidAll--) | Todo prohibido. |
| [getModifyAnnotations](#getModifyAnnotations--) | Permite modificar anotaciones del archivo. |
| [getModifyContents](#getModifyContents--) | Permite modificar el archivo. |
| [getPrint](#getPrint--) | Permite imprimir el archivo. |
| [getPrintAllowLevel](#getPrintAllowLevel--) | Obtiene y establece el nivel de impresión del privilegio del documento. Igual que la configuración Impresión Permitida de Adobe Professional. 0: Ninguno. 1: Baja resolución (150 dpi). 2: Alta resolución. Si la propiedad tiene un valor de -1, el nivel está indefinido. |
| [getScreenReaders](#getScreenReaders--) | Permite solo lectura en pantalla. |
| [getValue](#getValue--) |  |
| [hashCode](#hashCode--) | Devuelve un valor de código hash para el objeto. Este método es compatible para el beneficio de las tablas hash, como las proporcionadas por <code>java.util.Hashtable</code>. <p> El contrato general de <code>hashCode</code> es: <ul> <li>Siempre que se invoque en el mismo objeto más de una vez durante la ejecución de una aplicación Java, el método <tt>hashCode</tt> debe devolver consistentemente el mismo entero, siempre que no se modifique ninguna información utilizada en comparaciones <tt>equals</tt> del objeto. Este entero no necesita permanecer consistente de una ejecución de una aplicación a otra ejecución de la misma aplicación. <li>Si dos objetos son iguales según el método <tt>equals(Object)</tt>, entonces llamar al método <code>hashCode</code> en cada uno de los dos objetos debe producir el mismo resultado entero. <li>No es <em>requerido</em> que si dos objetos son desiguales según el método {@link java.lang.Object#equals(java.lang.Object)}, entonces llamar al método <tt>hashCode</tt> en cada uno de los dos objetos produzca resultados enteros distintos. Sin embargo, el programador debe ser consciente de que producir resultados enteros distintos para objetos desiguales puede mejorar el rendimiento de las tablas hash. </ul> <p> En la medida de lo razonablemente práctico, el método hashCode definido por la clase <tt>Object</tt> devuelve enteros distintos para objetos distintos. (Esto suele implementarse convirtiendo la dirección interna del objeto en un entero, pero esta técnica de implementación no es requerida por el lenguaje de programación Java<span style="font-size:70%"><sup>TM</sup></span>.) |
| [isAllowAssembly](#isAllowAssembly--) | Establece el permiso que permite el ensamblado o no. true permite y false está prohibido. |
| [isAllowCopy](#isAllowCopy--) | Establece el permiso que permite la copia o no. true permite y false está prohibido. |
| [isAllowDegradedPrinting](#isAllowDegradedPrinting--) | Establece el permiso que permite la impresión degradada o no. true permite y false está prohibido. Cuando se establece, la impresión se limitará a una representación de bajo nivel de la apariencia, posiblemente de calidad degradada. |
| [isAllowFillIn](#isAllowFillIn--) | Establece el permiso que permite rellenar formularios o no. true permite y false está prohibido. |
| [isAllowModifyAnnotations](#isAllowModifyAnnotations--) | Establece el permiso que permite modificar anotaciones o no. true permite y false está prohibido. |
| [isAllowModifyContents](#isAllowModifyContents--) | Establece el permiso que permite modificar contenidos o no. true permite y false está prohibido. |
| [isAllowPrint](#isAllowPrint--) | Establece el permiso que permite imprimir o no. true permite y false está prohibido. |
| [isAllowScreenReaders](#isAllowScreenReaders--) | Establece el permiso que permite lectores de pantalla o no. true permite y false está prohibido. |
| [setAllowAssembly](#setAllowAssembly-boolean-) | Establece el permiso que permite el ensamblado o no. true permite y false está prohibido. |
| [setAllowCopy](#setAllowCopy-boolean-) | Establece el permiso que permite la copia o no. true permite y false está prohibido. |
| [setAllowDegradedPrinting](#setAllowDegradedPrinting-boolean-) | Establece el permiso que permite la impresión degradada o no. true permite y false está prohibido. Cuando se establece, la impresión se limitará a una representación de bajo nivel de la apariencia, posiblemente de calidad degradada. |
| [setAllowFillIn](#setAllowFillIn-boolean-) | Establece el permiso que permite rellenar formularios o no. true permite y false está prohibido. |
| [setAllowModifyAnnotations](#setAllowModifyAnnotations-boolean-) | Establece el permiso que permite modificar anotaciones o no. true permite y false está prohibido. |
| [setAllowModifyContents](#setAllowModifyContents-boolean-) | Establece el permiso que permite modificar contenidos o no. true permite y false está prohibido. |
| [setAllowPrint](#setAllowPrint-boolean-) | Establece el permiso que permite imprimir o no. true permite y false está prohibido. |
| [setAllowScreenReaders](#setAllowScreenReaders-boolean-) | Establece el permiso que permite lectores de pantalla o no. true permite y false está prohibido. |
| [setChangeAllowLevel](#setChangeAllowLevel-int-) | Obtiene y establece el nivel de cambios del privilegio del documento. Igual que la configuración Cambios Permitidos de Adobe Professional. 0: Ninguno. 1: Insertar, eliminar y rotar páginas. 2: Rellenar campos de formulario y firmar campos de firma existentes. 3: Comentar, rellenar campos de formulario y firmar campos de firma existentes. 4: Cualquier acción excepto extraer páginas. Si la propiedad tiene un valor de -1, el nivel está indefinido. |
| [setCopyAllowLevel](#setCopyAllowLevel-int-) | Obtiene y establece el nivel de copia del privilegio del documento. Igual que la configuración de permisos de Adobe Professional. 0: Ninguno. 1: Habilitar acceso de texto para dispositivos de lectura de pantalla para personas con discapacidad visual. 2: Habilitar la copia de texto, imágenes y otro contenido. Si la propiedad tiene un valor de -1, el nivel está indefinido. |
| [setPrintAllowLevel](#setPrintAllowLevel-int-) | Obtiene y establece el nivel de impresión del privilegio del documento. Igual que la configuración Impresión Permitida de Adobe Professional. 0: Ninguno. 1: Baja resolución (150 dpi). 2: Alta resolución. Si la propiedad tiene un valor de -1, el nivel está indefinido. |

### compareTo {#compareTo-java.lang.Object-}
Compara dos objetos {@code DocumentPrivilege}.

### equals {#equals-java.lang.Object-}
Indica si algún otro objeto es "igual a" este. <p> El método <code>equals</code> implementa una relación de equivalencia sobre referencias de objetos no nulas: <ul> <li>Es <i>reflexivo</i>: para cualquier valor de referencia no nulo <code>x</code>, <code>x.equals(x)</code> debe devolver <code>true</code>. <li>Es <i>simétrico</i>: para cualquier valor de referencia no nulo <code>x</code> y <code>y</code>, <code>x.equals(y)</code> debe devolver <code>true</code> si y solo si <code>y.equals(x)</code> devuelve <code>true</code>. <li>Es <i>transitivo</i>: para cualquier valor de referencia no nulo <code>x</code>, <code>y</code> y <code>z</code>, si <code>x.equals(y)</code> devuelve <code>true</code> y <code>y.equals(z)</code> devuelve <code>true</code>, entonces <code>x.equals(z)</code> debe devolver <code>true</code>. <li>Es <i>consistente</i>: para cualquier valor de referencia no nulo <code>x</code> y <code>y</code>, múltiples invocaciones de <tt>x.equals(y)</tt> devuelven consistentemente <code>true</code> o consistentemente <code>false</code>, siempre que no se modifique la información utilizada en comparaciones <code>equals</code> de los objetos. <li>Para cualquier valor de referencia no nulo <code>x</code>, <code>x.equals(null)</code> debe devolver <code>false</code>. </ul> <p> El método <tt>equals</tt> para la clase <code>Object</code> implementa la relación de equivalencia más discriminatoria posible sobre los objetos; es decir, para cualquier valor de referencia no nulo <code>x</code> y <code>y</code>, este método devuelve <code>true</code> si y solo si <code>x</code> y <code>y</code> hacen referencia al mismo objeto (<code>x == y</code> tiene el valor <code>true</code>). <p> Tenga en cuenta que generalmente es necesario sobrescribir el método <tt>hashCode</tt> siempre que se sobrescriba este método, para mantener el contrato general del método <tt>hashCode</tt>, que establece que los objetos iguales deben tener códigos hash iguales.

### getAllowAll {#getAllowAll--}
```
public static DocumentPrivilege getAllowAll()
```

Todo permitido.

**Returns:**
Elemento DocumentPrivilege

### getAssembly {#getAssembly--}
```
public static DocumentPrivilege getAssembly()
```

Permite ensamblar el archivo.

**Returns:**
Elemento DocumentPrivilege

### getChangeAllowLevel {#getChangeAllowLevel--}
```
public final int getChangeAllowLevel()
```

Obtiene y establece el nivel de cambios del privilegio del documento. Igual que la configuración Cambios Permitidos de Adobe Professional. 0: Ninguno. 1: Insertar, eliminar y rotar páginas. 2: Rellenar campos de formulario y firmar campos de firma existentes. 3: Comentar, rellenar campos de formulario y firmar campos de firma existentes. 4: Cualquier acción excepto extraer páginas. Si la propiedad tiene un valor de -1, el nivel está indefinido.

**Returns:**
valor int

### getCopy {#getCopy--}
```
public static DocumentPrivilege getCopy()
```

Permite copiar el archivo.

**Returns:**
Elemento DocumentPrivilege

### getCopyAllowLevel {#getCopyAllowLevel--}
```
public final int getCopyAllowLevel()
```

Obtiene y establece el nivel de copia del privilegio del documento. Igual que la configuración de permisos de Adobe Professional. 0: Ninguno. 1: Habilitar acceso de texto para dispositivos de lectura de pantalla para personas con discapacidad visual. 2: Habilitar la copia de texto, imágenes y otro contenido. Si la propiedad tiene un valor de -1, el nivel está indefinido.

**Returns:**
valor int

### getDegradedPrinting {#getDegradedPrinting--}
```
public static DocumentPrivilege getDegradedPrinting()
```

Permite impresión degradada.

**Returns:**
Elemento DocumentPrivilege

### getFillIn {#getFillIn--}
```
public static DocumentPrivilege getFillIn()
```

Permite rellenar formularios en el archivo.

**Returns:**
Elemento DocumentPrivilege

### getForbidAll {#getForbidAll--}
```
public static DocumentPrivilege getForbidAll()
```

Todo prohibido.

**Returns:**
Elemento DocumentPrivilege

### getModifyAnnotations {#getModifyAnnotations--}
```
public static DocumentPrivilege getModifyAnnotations()
```

Permite modificar anotaciones del archivo.

**Returns:**
Elemento DocumentPrivilege

### getModifyContents {#getModifyContents--}
```
public static DocumentPrivilege getModifyContents()
```

Permite modificar el archivo.

**Returns:**
Elemento DocumentPrivilege

### getPrint {#getPrint--}
```
public static DocumentPrivilege getPrint()
```

Permite imprimir el archivo.

**Returns:**
Elemento DocumentPrivilege

### getPrintAllowLevel {#getPrintAllowLevel--}
```
public final int getPrintAllowLevel()
```

Obtiene y establece el nivel de impresión del privilegio del documento. Igual que la configuración Impresión Permitida de Adobe Professional. 0: Ninguno. 1: Baja resolución (150 dpi). 2: Alta resolución. Si la propiedad tiene un valor de -1, el nivel está indefinido.

**Returns:**
valor int

### getScreenReaders {#getScreenReaders--}
```
public static DocumentPrivilege getScreenReaders()
```

Permite solo lectura en pantalla.

**Returns:**
Elemento DocumentPrivilege

### getValue {#getValue--}
```
public final int getValue()
```



### hashCode {#hashCode--}
```
public int hashCode()
```

Devuelve un valor de código hash para el objeto. Este método es compatible para el beneficio de las tablas hash, como las proporcionadas por <code>java.util.Hashtable</code>. <p> El contrato general de <code>hashCode</code> es: <ul> <li>Siempre que se invoque en el mismo objeto más de una vez durante la ejecución de una aplicación Java, el método <tt>hashCode</tt> debe devolver consistentemente el mismo entero, siempre que no se modifique ninguna información utilizada en comparaciones <tt>equals</tt> del objeto. Este entero no necesita permanecer consistente de una ejecución de una aplicación a otra ejecución de la misma aplicación. <li>Si dos objetos son iguales según el método <tt>equals(Object)</tt>, entonces llamar al método <code>hashCode</code> en cada uno de los dos objetos debe producir el mismo resultado entero. <li>No es <em>requerido</em> que si dos objetos son desiguales según el método {@link java.lang.Object#equals(java.lang.Object)}, entonces llamar al método <tt>hashCode</tt> en cada uno de los dos objetos produzca resultados enteros distintos. Sin embargo, el programador debe ser consciente de que producir resultados enteros distintos para objetos desiguales puede mejorar el rendimiento de las tablas hash. </ul> <p> En la medida de lo razonablemente práctico, el método hashCode definido por la clase <tt>Object</tt> devuelve enteros distintos para objetos distintos. (Esto suele implementarse convirtiendo la dirección interna del objeto en un entero, pero esta técnica de implementación no es requerida por el lenguaje de programación Java<span style="font-size:70%"><sup>TM</sup></span>.)

**Returns:**
un valor de código hash para este objeto. @see java.lang.Object#equals(java.lang.Object) @see java.util.Hashtable

### isAllowAssembly {#isAllowAssembly--}
```
public boolean isAllowAssembly()
```

Establece el permiso que permite el ensamblado o no. true permite y false está prohibido.

**Returns:**
valor booleano

### isAllowCopy {#isAllowCopy--}
```
public boolean isAllowCopy()
```

Establece el permiso que permite la copia o no. true permite y false está prohibido.

**Returns:**
valor booleano

### isAllowDegradedPrinting {#isAllowDegradedPrinting--}
```
public boolean isAllowDegradedPrinting()
```

Establece el permiso que permite la impresión degradada o no. true permite y false está prohibido. Cuando se establece, la impresión se limitará a una representación de bajo nivel de la apariencia, posiblemente de calidad degradada.

**Returns:**
valor booleano

### isAllowFillIn {#isAllowFillIn--}
```
public boolean isAllowFillIn()
```

Establece el permiso que permite rellenar formularios o no. true permite y false está prohibido.

**Returns:**
valor booleano

### isAllowModifyAnnotations {#isAllowModifyAnnotations--}
```
public boolean isAllowModifyAnnotations()
```

Establece el permiso que permite modificar anotaciones o no. true permite y false está prohibido.

**Returns:**
valor booleano

### isAllowModifyContents {#isAllowModifyContents--}
```
public boolean isAllowModifyContents()
```

Establece el permiso que permite modificar contenidos o no. true permite y false está prohibido.

**Returns:**
valor booleano

### isAllowPrint {#isAllowPrint--}
```
public boolean isAllowPrint()
```

Establece el permiso que permite imprimir o no. true permite y false está prohibido.

**Returns:**
valor booleano

### isAllowScreenReaders {#isAllowScreenReaders--}
```
public boolean isAllowScreenReaders()
```

Establece el permiso que permite lectores de pantalla o no. true permite y false está prohibido.

**Returns:**
valor booleano

### setAllowAssembly {#setAllowAssembly-boolean-}
```
public void setAllowAssembly(boolean value)
```

Establece el permiso que permite el ensamblado o no. true permite y false está prohibido.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setAllowCopy {#setAllowCopy-boolean-}
```
public void setAllowCopy(boolean value)
```

Establece el permiso que permite la copia o no. true permite y false está prohibido.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setAllowDegradedPrinting {#setAllowDegradedPrinting-boolean-}
```
public void setAllowDegradedPrinting(boolean value)
```

Establece el permiso que permite la impresión degradada o no. true permite y false está prohibido. Cuando se establece, la impresión se limitará a una representación de bajo nivel de la apariencia, posiblemente de calidad degradada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setAllowFillIn {#setAllowFillIn-boolean-}
```
public void setAllowFillIn(boolean value)
```

Establece el permiso que permite rellenar formularios o no. true permite y false está prohibido.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setAllowModifyAnnotations {#setAllowModifyAnnotations-boolean-}
```
public void setAllowModifyAnnotations(boolean value)
```

Establece el permiso que permite modificar anotaciones o no. true permite y false está prohibido.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setAllowModifyContents {#setAllowModifyContents-boolean-}
```
public void setAllowModifyContents(boolean value)
```

Establece el permiso que permite modificar contenidos o no. true permite y false está prohibido.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setAllowPrint {#setAllowPrint-boolean-}
```
public void setAllowPrint(boolean value)
```

Establece el permiso que permite imprimir o no. true permite y false está prohibido.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setAllowScreenReaders {#setAllowScreenReaders-boolean-}
```
public void setAllowScreenReaders(boolean value)
```

Establece el permiso que permite lectores de pantalla o no. true permite y false está prohibido.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setChangeAllowLevel {#setChangeAllowLevel-int-}
```
public void setChangeAllowLevel(int value)
```

Obtiene y establece el nivel de cambios del privilegio del documento. Igual que la configuración Cambios Permitidos de Adobe Professional. 0: Ninguno. 1: Insertar, eliminar y rotar páginas. 2: Rellenar campos de formulario y firmar campos de firma existentes. 3: Comentar, rellenar campos de formulario y firmar campos de firma existentes. 4: Cualquier acción excepto extraer páginas. Si la propiedad tiene un valor de -1, el nivel está indefinido.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int |

### setCopyAllowLevel {#setCopyAllowLevel-int-}
```
public void setCopyAllowLevel(int value)
```

Obtiene y establece el nivel de copia del privilegio del documento. Igual que la configuración de permisos de Adobe Professional. 0: Ninguno. 1: Habilitar acceso de texto para dispositivos de lectura de pantalla para personas con discapacidad visual. 2: Habilitar la copia de texto, imágenes y otro contenido. Si la propiedad tiene un valor de -1, el nivel está indefinido.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int |

### setPrintAllowLevel {#setPrintAllowLevel-int-}
```
public void setPrintAllowLevel(int value)
```

Obtiene y establece el nivel de impresión del privilegio del documento. Igual que la configuración Impresión Permitida de Adobe Professional. 0: Ninguno. 1: Baja resolución (150 dpi). 2: Alta resolución. Si la propiedad tiene un valor de -1, el nivel está indefinido.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int |
