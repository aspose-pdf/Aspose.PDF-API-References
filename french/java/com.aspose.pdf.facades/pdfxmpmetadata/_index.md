---
title: "PdfXmpMetadata"
linktitle: "PdfXmpMetadata"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Classe pour la manipulation des métadonnées XMP."
type: docs
weight: 620
url: /fr/java/com.aspose.pdf.facades/pdfxmpmetadata/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfXmpMetadata, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfXmpMetadata, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfXmpMetadata

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XmpValue >>, com.aspose.ms.System.Collections.Generic.IGenericDictionary< String, XmpValue >, com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XmpValue >>, com.aspose.ms.System.Collections.IEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XmpValue >>, com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable, Iterable <com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XmpValue >>

```
public final class PdfXmpMetadata extends SaveableFacade implements com.aspose.ms.System.Collections.Generic.IGenericDictionary< String , XmpValue >
```

Classe pour la manipulation des métadonnées XMP.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PdfXmpMetadata](#PdfXmpMetadata--) | <p> Constructeur pour PdfXmpMetadata. </p> <hr> <pre> PdfXmlMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); </pre> |
| [PdfXmpMetadata](#PdfXmpMetadata-com.aspose.pdf.IDocument-) | <p> Constructeur pour PdfXmpMetadata. </p> <hr> <pre> PdfXmlMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); </pre> |

## Méthodes

| Méthode | Description |
| --- | --- |
| [add](#add-com.aspose.pdf.XmpPdfAExtensionObject-java.lang.String-java.lang.String-java.lang.String-) | Ajoute un champ d'extension aux métadonnées. |
| [addItem](#addItem-int-com.aspose.pdf.XmpValue-) | <p> Ajoute une valeur aux métadonnées XMP. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.add(DefaultMetadataProperties.Nickname, "name1"); xmp.save(TestSettings.getOutputFile("XMP_AddedValue.pdf")); </pre> |
| [addItem](#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Ajoute une paire avec la clé et la valeur dans le dictionnaire. |
| [addItem](#addItem-java.lang.String-java.lang.Object-) | Ajoute un nouvel élément à l'objet dictionnaire. |
| [addItem](#addItem-java.lang.String-com.aspose.pdf.XmpValue-) | <p> Ajoute un nouvel élément à l'objet dictionnaire. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.add("xmp:Nickname", "Nickname1"); </pre> |
| [clear](#clear--) | <p> Supprime tous les éléments de l'objet. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.clear(); </pre> |
| [contains](#contains-int-) | Vérifie si le dictionnaire contient la propriété spécifiée. |
| [contains](#contains-java.lang.String-) | <p> Vérifie si le dictionnaire contient la clé spécifiée. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.add("xmp:Nickname", "Nickname1"); if (!xmp.contains("xmp:Nickname")) System.out.println("Key does not exists"); </pre> |
| [containsItem](#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Vérifie si la paire clé-valeur spécifiée est contenue dans le dictionnaire. |
| [containsKey](#containsKey-java.lang.String-) | Détermine si ce dictionnaire contient la clé spécifiée. |
| [copyToTArray](#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-) | Copie les métadonnées dans un tableau. |
| [get_Item](#get_Item-java.lang.String-) | <p> Obtient la valeur par clé. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); System.out.println(pxm.get_Item("xmp:Nickname")); </pre> |
| [getByDefaultMetadataProperties](#getByDefaultMetadataProperties-int-) | <p> Obtient la valeur des métadonnées XMP par clé. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); System.out.println(pxm.get_Item(DefaultMetadataProperties.CreatorTool)); </pre> |
| [getExtensionFields](#getExtensionFields--) | <p> Obtient le dictionnaire des champs d'extension. </p> |
| [getKeys](#getKeys--) | Obtient les clés du dictionnaire. |
| [getNamespaceURIByPrefix](#getNamespaceURIByPrefix-java.lang.String-) | <p> Obtient l'URI d'espace de noms par préfixe. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf"); System.out.println(xmp.getNamespaceURIByPrefix("xmp")); </pre> |
| [getPrefixByNamespaceURI](#getPrefixByNamespaceURI-java.lang.String-) | <p> Obtient le préfixe par URI d'espace de noms. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf"); System.out.println(xmp.getPrefixByNamespaceURI("http://ns.adobe.com/xap/1.0/")); </pre> |
| [getSyncRoot](#getSyncRoot--) | Obtient l'objet de synchronisation de la collection. |
| [getValues](#getValues--) | Obtient la collection des valeurs du dictionnaire. |
| [getXmpMetadata](#getXmpMetadata--) | <p> Obtient le XmpMetadata du PDF d'entrée au format XML. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); byte[] data = pxm.getXmpMetadata(); </pre> |
| [getXmpMetadata](#getXmpMetadata-java.lang.String-) | <p> Obtient le XmpMetadata du PDF d'entrée au format XML. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); byte[] data = pxm.getXmpMetadata(); </pre> |
| [isFixedSize](#isFixedSize--) | Renvoie true si la collection a une taille fixe. |
| [isReadOnly](#isReadOnly--) | Renvoie true si la collection est en lecture seule. |
| [isSynchronized](#isSynchronized--) | Renvoie true si la collection est synchronisée. |
| [iterator_Rename_Namesake](#iterator_Rename_Namesake--) |  |
| [iterator](#iterator--) | Obtient l'objet énumérateur du dictionnaire. |
| [iteratorIt](#iteratorIt--) | Obtient l'objet énumérateur de la collection. |
| [registerNamespaceURI](#registerNamespaceURI-java.lang.String-java.lang.String-) | <p> Enregistre l'URI de l'espace de noms. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf"); xmp.registerNamespaceURI("xmp", "http://ns.adobe.com/xap/1.0/"); </pre> |
| [removeItem](#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Supprime la paire clé/valeur de la collection. |
| [removeItemByKey](#removeItemByKey-int-) | <p> Supprime l'élément avec la clé spécifiée. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.remove(DefaultMetadataProperties.Nickname); </pre> |
| [removeItemByKey](#removeItemByKey-java.lang.String-) | <p> Supprime la clé du dictionnaire. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.remove("xmp:Nickname"); </pre> |
| [set_Item](#set_Item-java.lang.String-com.aspose.pdf.XmpValue-) | <p> Définit la valeur par clé. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); System.out.println(pxm.get_Item("xmp:Nickname")); </pre> |
| [setByDefaultMetadataProperties](#setByDefaultMetadataProperties-int-com.aspose.pdf.XmpValue-) | <p> Définit la valeur des métadonnées XMP par clé. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); System.out.println(pxm.get_Item(DefaultMetadataProperties.CreatorTool)); </pre> |
| [size](#size--) | <p> Obtient le nombre d'éléments dans la collection. </p> |
| [tryGetValue](#tryGetValue-java.lang.String-java.lang.Object:A-) | Essaie de trouver la clé dans le dictionnaire et récupère la valeur si elle est trouvée. |

### PdfXmpMetadata {#PdfXmpMetadata--}
```
public PdfXmpMetadata()
```

<p> Constructeur pour PdfXmpMetadata. </p> <hr> <pre> PdfXmlMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); </pre>

### PdfXmpMetadata {#PdfXmpMetadata-com.aspose.pdf.IDocument-}
<p> Constructeur pour PdfXmpMetadata. </p> <hr> <pre> PdfXmlMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); </pre>

### add {#add-com.aspose.pdf.XmpPdfAExtensionObject-java.lang.String-java.lang.String-java.lang.String-}
Ajoute un champ d'extension aux métadonnées.

### addItem {#addItem-int-com.aspose.pdf.XmpValue-}
<p> Ajoute une valeur aux métadonnées XMP. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.add(DefaultMetadataProperties.Nickname, "name1"); xmp.save(TestSettings.getOutputFile("XMP_AddedValue.pdf")); </pre>

### addItem {#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Ajoute une paire avec la clé et la valeur dans le dictionnaire.

### addItem {#addItem-java.lang.String-java.lang.Object-}
Ajoute un nouvel élément à l'objet dictionnaire.

### addItem {#addItem-java.lang.String-com.aspose.pdf.XmpValue-}
<p> Ajoute un nouvel élément à l'objet dictionnaire. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.add("xmp:Nickname", "Nickname1"); </pre>

### clear {#clear--}
```
public void clear()
```

<p> Supprime tous les éléments de l'objet. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.clear(); </pre>

### contains {#contains-int-}
```
public boolean contains(int property)
```

Vérifie si le dictionnaire contient la propriété spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| propriété |  | Propriété qui sera vérifiée. |

**Returns:**
True - si le dictionnaire contient la propriété spécifiée ; sinon, false.

### contains {#contains-java.lang.String-}
<p> Vérifie si le dictionnaire contient la clé spécifiée. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.add("xmp:Nickname", "Nickname1"); if (!xmp.contains("xmp:Nickname")) System.out.println("Key does not exists"); </pre>

### containsItem {#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Vérifie si la paire clé-valeur spécifiée est contenue dans le dictionnaire.

### containsKey {#containsKey-java.lang.String-}
Détermine si ce dictionnaire contient la clé spécifiée.

### copyToTArray {#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-}
Copie les métadonnées dans un tableau.

### get_Item {#get_Item-java.lang.String-}
<p> Obtient la valeur par clé. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); System.out.println(pxm.get_Item("xmp:Nickname")); </pre>

### getByDefaultMetadataProperties {#getByDefaultMetadataProperties-int-}
```
public XmpValue getByDefaultMetadataProperties(int key)
```

<p> Obtient la valeur des métadonnées XMP par clé. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); System.out.println(pxm.get_Item(DefaultMetadataProperties.CreatorTool)); </pre>

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| key |  | Clé de la valeur. |

**Returns:**
Valeur provenant des métadonnées XMP. @see DefaultMetadataProperties

### getExtensionFields {#getExtensionFields--}
```
public Hashtable < String , XmpPdfAExtensionSchema > getExtensionFields()
```

<p> Obtient le dictionnaire des champs d'extension. </p>

**Returns:**
{@code Hashtable<String, XmpPdfAExtensionSchema>} objet

### getKeys {#getKeys--}
```
public com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getKeys()
```

Obtient les clés du dictionnaire.

**Returns:**
Élément ICollection

### getNamespaceURIByPrefix {#getNamespaceURIByPrefix-java.lang.String-}
<p> Obtient l'URI d'espace de noms par préfixe. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf"); System.out.println(xmp.getNamespaceURIByPrefix("xmp")); </pre>

### getPrefixByNamespaceURI {#getPrefixByNamespaceURI-java.lang.String-}
<p> Obtient le préfixe par URI d'espace de noms. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf"); System.out.println(xmp.getPrefixByNamespaceURI("http://ns.adobe.com/xap/1.0/")); </pre>

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Obtient l'objet de synchronisation de la collection.

**Returns:**
Élément d'objet

### getValues {#getValues--}
```
public com.aspose.ms.System.Collections.Generic.IGenericCollection< XmpValue > getValues()
```

Obtient la collection des valeurs du dictionnaire.

**Returns:**
objet ICollection

### getXmpMetadata {#getXmpMetadata--}
```
public byte[] getXmpMetadata()
```

<p> Obtient le XmpMetadata du PDF d'entrée au format XML. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); byte[] data = pxm.getXmpMetadata(); </pre>

**Returns:**
Les octets du XmpMetadata.

### getXmpMetadata {#getXmpMetadata-java.lang.String-}
<p> Obtient le XmpMetadata du PDF d'entrée au format XML. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); byte[] data = pxm.getXmpMetadata(); </pre>

**Returns:**
Les octets du XmpMetadata.

### isFixedSize {#isFixedSize--}
```
public boolean isFixedSize()
```

Renvoie true si la collection a une taille fixe.

**Returns:**
valeur booléenne

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Renvoie true si la collection est en lecture seule.

**Returns:**
valeur booléenne

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Renvoie true si la collection est synchronisée.

**Returns:**
valeur booléenne

### iterator_Rename_Namesake {#iterator_Rename_Namesake--}
```
public com.aspose.ms.System.Collections.IEnumerator iterator_Rename_Namesake()
```



### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair< String , XmpValue >> iterator()
```

Obtient l'objet énumérateur du dictionnaire.

**Returns:**
L'objet énumérateur.

### iteratorIt {#iteratorIt--}
```
public com.aspose.ms.System.Collections.IEnumerator iteratorIt()
```

Obtient l'objet énumérateur de la collection.

**Returns:**
Objet IEnumerator

### registerNamespaceURI {#registerNamespaceURI-java.lang.String-java.lang.String-}
<p> Enregistre l'URI de l'espace de noms. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf"); xmp.registerNamespaceURI("xmp", "http://ns.adobe.com/xap/1.0/"); </pre>

### removeItem {#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Supprime la paire clé/valeur de la collection.

### removeItemByKey {#removeItemByKey-int-}
```
public void removeItemByKey(int key)
```

<p> Supprime l'élément avec la clé spécifiée. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.remove(DefaultMetadataProperties.Nickname); </pre>

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| key |  | Clé de l'élément qui sera supprimé. @see DefaultMetadataProperties |

### removeItemByKey {#removeItemByKey-java.lang.String-}
<p> Supprime la clé du dictionnaire. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.remove("xmp:Nickname"); </pre>

### set_Item {#set_Item-java.lang.String-com.aspose.pdf.XmpValue-}
<p> Définit la valeur par clé. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); System.out.println(pxm.get_Item("xmp:Nickname")); </pre>

### setByDefaultMetadataProperties {#setByDefaultMetadataProperties-int-com.aspose.pdf.XmpValue-}
<p> Définit la valeur des métadonnées XMP par clé. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); System.out.println(pxm.get_Item(DefaultMetadataProperties.CreatorTool)); </pre>

### size {#size--}
```
public int size()
```

<p> Obtient le nombre d'éléments dans la collection. </p>

**Returns:**
valeur int <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); System.out.println("Count = " + pxm.size()); </pre>

### tryGetValue {#tryGetValue-java.lang.String-java.lang.Object:A-}
Essaie de trouver la clé dans le dictionnaire et récupère la valeur si elle est trouvée.
