---
title: "XFA"
linktitle: "XFA"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente le formulaire XML concernant l'Architecture des formulaires XML (XFA)."
type: docs
weight: 5550
url: /fr/java/com.aspose.pdf/xfa/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XFA

```
public final class XFA extends Object
```

Représente le formulaire XML concernant l'Architecture des formulaires XML (XFA).

## Méthodes

| Méthode | Description |
| --- | --- |
| [appendToTemplate](#appendToTemplate-java.lang.String-java.lang.String-) | Ajouter la valeur XML au nœud du modèle qui correspond à l'expression XPath |
| [beginCachedUpdates](#beginCachedUpdates--) | Démarrer le mode de mises à jour en cache. Toutes les modifications apportées à XFA seront mises en cache et enregistrées dans la structure du document lors de l'appel à EndCachedUpdates. Cela permet d'améliorer les performances en évitant les opérations redondantes lors de l'enregistrement des paquets XML dans le document lorsqu'un grand nombre de modifications sont apportées à XFA. |
| [endCachedUpdates](#endCachedUpdates--) | Met fin aux mises à jour en cache et enregistre toutes les données dans la structure du document. |
| [flattenXfaField](#flattenXfaField-com.aspose.ms.System.Xml.XmlNode-) | Aplatir le champ du formulaire XFA. |
| [get_Item](#get_Item-java.lang.String-) | Obtient la valeur du nœud de données selon {@code path}. |
| [getConfig](#getConfig--) | Composant XFA Config d'un formulaire XFA. |
| [getDatasets](#getDatasets--) | Composant XFA Datasets d'un formulaire XFA. |
| [getFieldNames](#getFieldNames--) | Liste des noms de champs dans le modèle du formulaire. |
| [getFieldsWithTextValuesMap](#getFieldsWithTextValuesMap--) | <p> Retourne une map avec le nom court du champ et sa valeur chaîne pour tous les champs. </p> |
| [getFieldTemplate](#getFieldTemplate-java.lang.String-) | Retourne le nœud XML du modèle de champ XFA. |
| [getFieldTemplates](#getFieldTemplates--) | Retourne la liste de tous les modèles de champ du formulaire XFA. |
| [getForm](#getForm--) | Obtient le composant XFA Form d'un formulaire XFA. |
| [getNamespaceManager_](#getNamespaceManager_--) | Obtient l'espace de noms du formulaire XFA. Les espaces de noms suivants sont définis : "data" pour les données du formulaire et "tpl" pour le modèle du formulaire. |
| [getNamespaceManager](#getNamespaceManager--) | Retourne le gestionnaire d'espaces de noms avec les espaces de noms utilisés pour le modèle et les données. |
| [getTemplate](#getTemplate--) | Composant XFA Template d'un formulaire XFA. |
| [getXDP](#getXDP--) | Package de données XML (tous les composants du formulaire XFA dans un conteneur XML environnant). |
| [getXfaField](#getXfaField-java.lang.String-) |  |
| [set_Item](#set_Item-java.lang.String-java.lang.String-) | Obtient la valeur du nœud de données selon {@code path}. |
| [setFieldImage](#setFieldImage-java.lang.String-java.io.InputStream-) | Définit l'image pour le champ XFA. |
| [setFieldImageInternal](#setFieldImageInternal-java.lang.String-com.aspose.ms.System.IO.Stream-) |  |
| [tryGetTemplateString](#tryGetTemplateString-java.lang.String-) | Essaie d'exporter le script de calcul du formulaire XFA. Sinon, retourne la chaîne vide ; |

### appendToTemplate {#appendToTemplate-java.lang.String-java.lang.String-}
Ajouter la valeur XML au nœud du modèle qui correspond à l'expression XPath

### beginCachedUpdates {#beginCachedUpdates--}
```
public void beginCachedUpdates()
```

Démarrer le mode de mises à jour en cache. Toutes les modifications apportées à XFA seront mises en cache et enregistrées dans la structure du document lors de l'appel à EndCachedUpdates. Cela permet d'améliorer les performances en évitant les opérations redondantes lors de l'enregistrement des paquets XML dans le document lorsqu'un grand nombre de modifications sont apportées à XFA.

### endCachedUpdates {#endCachedUpdates--}
```
public void endCachedUpdates()
```

Met fin aux mises à jour en cache et enregistre toutes les données dans la structure du document.

### flattenXfaField {#flattenXfaField-com.aspose.ms.System.Xml.XmlNode-}
Aplatir le champ du formulaire XFA.

### get_Item {#get_Item-java.lang.String-}
Obtient la valeur du nœud de données selon {@code path}.

### getConfig {#getConfig--}
```
public com.aspose.ms.System.Xml.XmlNode getConfig()
```

Composant XFA Config d'un formulaire XFA.

**Returns:**
Objet XmlNode

### getDatasets {#getDatasets--}
```
public com.aspose.ms.System.Xml.XmlNode getDatasets()
```

Composant XFA Datasets d'un formulaire XFA.

**Returns:**
Objet XmlNode

### getFieldNames {#getFieldNames--}
```
public String [] getFieldNames()
```

Liste des noms de champs dans le modèle du formulaire.

**Returns:**
tableau de valeurs String

### getFieldsWithTextValuesMap {#getFieldsWithTextValuesMap--}
```
public HashMap < String , String > getFieldsWithTextValuesMap()
```

<p> Retourne une map avec le nom court du champ et sa valeur chaîne pour tous les champs. </p>

**Returns:**
{@code HashMap<String, String>} objet

### getFieldTemplate {#getFieldTemplate-java.lang.String-}
Retourne le nœud XML du modèle de champ XFA.

### getFieldTemplates {#getFieldTemplates--}
```
public com.aspose.ms.System.Xml.XmlNodeList getFieldTemplates()
```

Retourne la liste de tous les modèles de champ du formulaire XFA.

**Returns:**
Liste des modèles de champ.

### getForm {#getForm--}
```
public com.aspose.ms.System.Xml.XmlNode getForm()
```

Obtient le composant XFA Form d'un formulaire XFA.

**Returns:**
Objet XmlNode

### getNamespaceManager_ {#getNamespaceManager_--}
```
public com.aspose.ms.System.Xml.XmlNamespaceManager getNamespaceManager_()
```

Obtient l'espace de noms du formulaire XFA. Les espaces de noms suivants sont définis : "data" pour les données du formulaire et "tpl" pour le modèle du formulaire.

**Returns:**
Objet XmlNamespaceManager

### getNamespaceManager {#getNamespaceManager--}
```
public com.aspose.ms.System.Xml.XmlNamespaceManager getNamespaceManager()
```

Retourne le gestionnaire d'espaces de noms avec les espaces de noms utilisés pour le modèle et les données.

**Returns:**
Objet XmlNamespaceManager

### getTemplate {#getTemplate--}
```
public com.aspose.ms.System.Xml.XmlNode getTemplate()
```

Composant XFA Template d'un formulaire XFA.

**Returns:**
Objet XmlNode

### getXDP {#getXDP--}
```
public com.aspose.ms.System.Xml.XmlDocument getXDP()
```

Package de données XML (tous les composants du formulaire XFA dans un conteneur XML environnant).

**Returns:**
Objet XmlDocument

### getXfaField {#getXfaField-java.lang.String-}


### set_Item {#set_Item-java.lang.String-java.lang.String-}
Obtient la valeur du nœud de données selon {@code path}.

### setFieldImage {#setFieldImage-java.lang.String-java.io.InputStream-}
Définit l'image pour le champ XFA.

### setFieldImageInternal {#setFieldImageInternal-java.lang.String-com.aspose.ms.System.IO.Stream-}


### tryGetTemplateString {#tryGetTemplateString-java.lang.String-}
Essaie d'exporter le script de calcul du formulaire XFA. Sinon, retourne la chaîne vide ;
