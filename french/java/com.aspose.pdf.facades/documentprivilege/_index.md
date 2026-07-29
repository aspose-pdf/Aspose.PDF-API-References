---
title: "DocumentPrivilege"
linktitle: "DocumentPrivilege"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente les privilèges d'accès au fichier Pdf. Référez-vous à{@code PdfFileSecurity}. Il existe 4 manières d'utiliser cette classe : 1. Utiliser directement le privilège prédéfini. 2. Basé sur un."
type: docs
weight: 110
url: /fr/java/com.aspose.pdf.facades/documentprivilege/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.DocumentPrivilege

**All Implemented Interfaces:**
Comparable < Object >

```
public final class DocumentPrivilege extends Object implements Comparable < Object >
```

Représente les privilèges d'accès au fichier PDF. Référez-vous à {@code PdfFileSecurity}. Il existe 4 manières d'utiliser cette classe : 1. Utiliser directement un privilège prédéfini. 2. Partir d'un privilège prédéfini et modifier certaines permissions spécifiques. 3. Partir d'un privilège prédéfini et modifier une combinaison spécifique de permissions Adobe Professional. 4. Mélanger les méthodes 2 et 3. //Way1 : Utilisation directe d'un privilège prédéfini. DocumentPrivilege privilege = DocumentPrivilege.getPrint(); //Way2 : À partir d'un privilège prédéfini et modification de certaines permissions spécifiques. DocumentPrivilege privilege = DocumentPrivilege.getAllowAll(); privilege.setAllowPrint(false); privilege.setAllowModifyContents(false); //Way3 : À partir d'un privilège prédéfini et modification d'une combinaison spécifique de permissions Adobe Professional. DocumentPrivilege privilege = DocumentPrivilege.getForbidAll(); privilege.setChangeAllowLevel(1); privilege.setPrintAllowLevel(2); //Way4 : Mélange des méthodes 2 et 3 DocumentPrivilege privilege = DocumentPrivilege.getForbidAll(); privilege.setChangeAllowLevel(1); privilege.setAllowPrint(true);

## Méthodes

| Méthode | Description |
| --- | --- |
| [compareTo](#compareTo-java.lang.Object-) | Compare deux objets {@code DocumentPrivilege}. |
| [equals](#equals-java.lang.Object-) | Indique si un autre objet est « égal à » celui-ci. <p> La méthode <code>equals</code> implémente une relation d'équivalence sur les références d'objets non nulles : <ul> <li>Elle est <i>réflexive</i> : pour toute valeur de référence non nulle <code>x</code>, <code>x.equals(x)</code> doit renvoyer <code>true</code>. <li>Elle est <i>symétrique</i> : pour toute paire de références non nulles <code>x</code> et <code>y</code>, <code>x.equals(y)</code> doit renvoyer <code>true</code> si et seulement si <code>y.equals(x)</code> renvoie <code>true</code>. <li>Elle est <i>transitive</i> : pour toute référence non nulle <code>x</code>, <code>y</code> et <code>z</code>, si <code>x.equals(y)</code> renvoie <code>true</code> et <code>y.equals(z)</code> renvoie <code>true</code>, alors <code>x.equals(z)</code> doit renvoyer <code>true</code>. <li>Elle est <i>cohérente</i> : pour toute référence non nulle <code>x</code> et <code>y</code>, plusieurs appels de <tt>x.equals(y)</tt> renvoient toujours <code>true</code> ou toujours <code>false</code>, à condition qu'aucune information utilisée dans les comparaisons <code>equals</code> sur les objets ne soit modifiée. <li>Pour toute référence non nulle <code>x</code>, <code>x.equals(null)</code> doit renvoyer <code>false</code>. </ul> <p> La méthode <tt>equals</tt> de la classe <code>Object</code> implémente la relation d'équivalence la plus discriminante possible sur les objets ; c'est‑à‑dire que, pour toute paire de références non nulles <code>x</code> et <code>y</code>, cette méthode renvoie <code>true</code> si et seulement si <code>x</code> et <code>y</code> font référence au même objet (<code>x == y</code> a la valeur <code>true</code>). <p> Notez qu'il est généralement nécessaire de remplacer la méthode <tt>hashCode</tt> chaque fois que cette méthode est remplacée, afin de respecter le contrat général de la méthode <tt>hashCode</tt>, qui stipule que les objets égaux doivent avoir des codes de hachage égaux. |
| [getAllowAll](#getAllowAll--) | Tout autorisé. |
| [getAssembly](#getAssembly--) | Autorise l'assemblage du fichier. |
| [getChangeAllowLevel](#getChangeAllowLevel--) | Obtient et définit le niveau de modification du privilège du document. Identique aux paramètres « Changes Allowed » d'Adobe Professional. 0 : Aucun. 1 : Insertion, suppression et rotation des pages. 2 : Remplissage des champs de formulaire et signature des champs de signature existants. 3 : Commentaire, remplissage des champs de formulaire et signature des champs de signature existants. 4 : Tout sauf l'extraction des pages. Si la propriété a la valeur -1, le niveau est indéfini. |
| [getCopy](#getCopy--) | Autorise la copie du fichier. |
| [getCopyAllowLevel](#getCopyAllowLevel--) | Obtient et définit le niveau de copie du privilège du document. Identique aux paramètres d'autorisation d'Adobe Professional. 0 : Aucun. 1 : Autoriser l'accès au texte pour les appareils de lecture d'écran destinés aux malvoyants. 2 : Autoriser la copie du texte, des images et d'autres contenus. Si la propriété a la valeur -1, le niveau est indéfini. |
| [getDegradedPrinting](#getDegradedPrinting--) | Autorise l'impression dégradée. |
| [getFillIn](#getFillIn--) | Autorise le remplissage des formulaires dans le fichier. |
| [getForbidAll](#getForbidAll--) | Tout interdit. |
| [getModifyAnnotations](#getModifyAnnotations--) | Autorise la modification des annotations du fichier. |
| [getModifyContents](#getModifyContents--) | Autorise la modification du fichier. |
| [getPrint](#getPrint--) | Autorise l'impression du fichier. |
| [getPrintAllowLevel](#getPrintAllowLevel--) | Obtient et définit le niveau d'impression du privilège du document. Identique aux paramètres « Printing Allowed » d'Adobe Professional. 0 : Aucun. 1 : Basse résolution (150 dpi). 2 : Haute résolution. Si la propriété a la valeur -1, le niveau est indéfini. |
| [getScreenReaders](#getScreenReaders--) | Autorise la lecture à l'écran uniquement. |
| [getValue](#getValue--) |  |
| [hashCode](#hashCode--) | Renvoie une valeur de code de hachage pour l'objet. Cette méthode est prise en charge pour le bénéfice des tables de hachage telles que celles fournies par <code>java.util.Hashtable</code>. <p> Le contrat général de <code>hashCode</code> est : <ul> <li>Chaque fois qu'il est invoqué sur le même objet plus d'une fois pendant l'exécution d'une application Java, la méthode <tt>hashCode</tt> doit toujours renvoyer le même entier, à condition qu'aucune information utilisée dans les comparaisons <tt>equals</tt> sur l'objet ne soit modifiée. Cet entier n'a pas besoin de rester identique d'une exécution d'une application à une autre exécution de la même application. <li>Si deux objets sont égaux selon la méthode <tt>equals(Object)</tt>, alors appeler la méthode <code>hashCode</code> sur chacun des deux objets doit produire le même résultat entier. <li>Il n'est <em>pas</em> requis que si deux objets sont inégaux selon la méthode {@link java.lang.Object#equals(java.lang.Object)}, alors appeler la méthode <tt>hashCode</tt> sur chacun des deux objets doit produire des résultats entiers distincts. Cependant, le programmeur doit être conscient que produire des résultats entiers distincts pour des objets inégaux peut améliorer les performances des tables de hachage. </ul> <p> Dans la mesure du raisonnable, la méthode hashCode définie par la classe <tt>Object</tt> renvoie des entiers distincts pour des objets distincts. (Ceci est généralement implémenté en convertissant l'adresse interne de l'objet en un entier, mais cette technique d'implémentation n'est pas requise par le langage de programmation Java<span style="font-size:70%"><sup>TM</sup></span>.) |
| [isAllowAssembly](#isAllowAssembly--) | Définit la permission qui autorise l'assemblage ou non. true autorise et false interdit. |
| [isAllowCopy](#isAllowCopy--) | Définit la permission qui autorise la copie ou non. true autorise et false interdit. |
| [isAllowDegradedPrinting](#isAllowDegradedPrinting--) | Définit la permission qui autorise l'impression dégradée ou non. true autorise et false interdit. Lorsqu'elle est définie, l'impression sera limitée à une représentation de bas niveau de l'apparence, éventuellement de qualité dégradée. |
| [isAllowFillIn](#isAllowFillIn--) | Définit la permission qui autorise le remplissage de formulaires ou non. true autorise et false interdit. |
| [isAllowModifyAnnotations](#isAllowModifyAnnotations--) | Définit la permission qui autorise la modification des annotations ou non. true autorise et false interdit. |
| [isAllowModifyContents](#isAllowModifyContents--) | Définit la permission qui autorise la modification du contenu ou non. true autorise et false interdit. |
| [isAllowPrint](#isAllowPrint--) | Définit la permission qui autorise l'impression ou non. true autorise et false interdit. |
| [isAllowScreenReaders](#isAllowScreenReaders--) | Définit la permission qui autorise les lecteurs d'écran ou non. true autorise et false interdit. |
| [setAllowAssembly](#setAllowAssembly-boolean-) | Définit la permission qui autorise l'assemblage ou non. true autorise et false interdit. |
| [setAllowCopy](#setAllowCopy-boolean-) | Définit la permission qui autorise la copie ou non. true autorise et false interdit. |
| [setAllowDegradedPrinting](#setAllowDegradedPrinting-boolean-) | Définit la permission qui autorise l'impression dégradée ou non. true autorise et false interdit. Lorsqu'elle est définie, l'impression sera limitée à une représentation de bas niveau de l'apparence, éventuellement de qualité dégradée. |
| [setAllowFillIn](#setAllowFillIn-boolean-) | Définit la permission qui autorise le remplissage de formulaires ou non. true autorise et false interdit. |
| [setAllowModifyAnnotations](#setAllowModifyAnnotations-boolean-) | Définit la permission qui autorise la modification des annotations ou non. true autorise et false interdit. |
| [setAllowModifyContents](#setAllowModifyContents-boolean-) | Définit la permission qui autorise la modification du contenu ou non. true autorise et false interdit. |
| [setAllowPrint](#setAllowPrint-boolean-) | Définit la permission qui autorise l'impression ou non. true autorise et false interdit. |
| [setAllowScreenReaders](#setAllowScreenReaders-boolean-) | Définit la permission qui autorise les lecteurs d'écran ou non. true autorise et false interdit. |
| [setChangeAllowLevel](#setChangeAllowLevel-int-) | Obtient et définit le niveau de modification du privilège du document. Identique aux paramètres « Changes Allowed » d'Adobe Professional. 0 : Aucun. 1 : Insertion, suppression et rotation des pages. 2 : Remplissage des champs de formulaire et signature des champs de signature existants. 3 : Commentaire, remplissage des champs de formulaire et signature des champs de signature existants. 4 : Tout sauf l'extraction des pages. Si la propriété a la valeur -1, le niveau est indéfini. |
| [setCopyAllowLevel](#setCopyAllowLevel-int-) | Obtient et définit le niveau de copie du privilège du document. Identique aux paramètres d'autorisation d'Adobe Professional. 0 : Aucun. 1 : Autoriser l'accès au texte pour les appareils de lecture d'écran destinés aux malvoyants. 2 : Autoriser la copie du texte, des images et d'autres contenus. Si la propriété a la valeur -1, le niveau est indéfini. |
| [setPrintAllowLevel](#setPrintAllowLevel-int-) | Obtient et définit le niveau d'impression du privilège du document. Identique aux paramètres « Printing Allowed » d'Adobe Professional. 0 : Aucun. 1 : Basse résolution (150 dpi). 2 : Haute résolution. Si la propriété a la valeur -1, le niveau est indéfini. |

### compareTo {#compareTo-java.lang.Object-}
Compare deux objets {@code DocumentPrivilege}.

### equals {#equals-java.lang.Object-}
Indique si un autre objet est « égal à » celui-ci. <p> La méthode <code>equals</code> implémente une relation d'équivalence sur les références d'objets non nulles : <ul> <li>Elle est <i>réflexive</i> : pour toute valeur de référence non nulle <code>x</code>, <code>x.equals(x)</code> doit renvoyer <code>true</code>. <li>Elle est <i>symétrique</i> : pour toute paire de références non nulles <code>x</code> et <code>y</code>, <code>x.equals(y)</code> doit renvoyer <code>true</code> si et seulement si <code>y.equals(x)</code> renvoie <code>true</code>. <li>Elle est <i>transitive</i> : pour toute référence non nulle <code>x</code>, <code>y</code> et <code>z</code>, si <code>x.equals(y)</code> renvoie <code>true</code> et <code>y.equals(z)</code> renvoie <code>true</code>, alors <code>x.equals(z)</code> doit renvoyer <code>true</code>. <li>Elle est <i>cohérente</i> : pour toute référence non nulle <code>x</code> et <code>y</code>, plusieurs appels de <tt>x.equals(y)</tt> renvoient toujours <code>true</code> ou toujours <code>false</code>, à condition qu'aucune information utilisée dans les comparaisons <code>equals</code> sur les objets ne soit modifiée. <li>Pour toute référence non nulle <code>x</code>, <code>x.equals(null)</code> doit renvoyer <code>false</code>. </ul> <p> La méthode <tt>equals</tt> de la classe <code>Object</code> implémente la relation d'équivalence la plus discriminante possible sur les objets ; c'est‑à‑dire que, pour toute paire de références non nulles <code>x</code> et <code>y</code>, cette méthode renvoie <code>true</code> si et seulement si <code>x</code> et <code>y</code> font référence au même objet (<code>x == y</code> a la valeur <code>true</code>). <p> Notez qu'il est généralement nécessaire de remplacer la méthode <tt>hashCode</tt> chaque fois que cette méthode est remplacée, afin de respecter le contrat général de la méthode <tt>hashCode</tt>, qui stipule que les objets égaux doivent avoir des codes de hachage égaux.

### getAllowAll {#getAllowAll--}
```
public static DocumentPrivilege getAllowAll()
```

Tout autorisé.

**Returns:**
Élément DocumentPrivilege

### getAssembly {#getAssembly--}
```
public static DocumentPrivilege getAssembly()
```

Autorise l'assemblage du fichier.

**Returns:**
Élément DocumentPrivilege

### getChangeAllowLevel {#getChangeAllowLevel--}
```
public final int getChangeAllowLevel()
```

Obtient et définit le niveau de modification du privilège du document. Identique aux paramètres « Changes Allowed » d'Adobe Professional. 0 : Aucun. 1 : Insertion, suppression et rotation des pages. 2 : Remplissage des champs de formulaire et signature des champs de signature existants. 3 : Commentaire, remplissage des champs de formulaire et signature des champs de signature existants. 4 : Tout sauf l'extraction des pages. Si la propriété a la valeur -1, le niveau est indéfini.

**Returns:**
valeur int

### getCopy {#getCopy--}
```
public static DocumentPrivilege getCopy()
```

Autorise la copie du fichier.

**Returns:**
Élément DocumentPrivilege

### getCopyAllowLevel {#getCopyAllowLevel--}
```
public final int getCopyAllowLevel()
```

Obtient et définit le niveau de copie du privilège du document. Identique aux paramètres d'autorisation d'Adobe Professional. 0 : Aucun. 1 : Autoriser l'accès au texte pour les appareils de lecture d'écran destinés aux malvoyants. 2 : Autoriser la copie du texte, des images et d'autres contenus. Si la propriété a la valeur -1, le niveau est indéfini.

**Returns:**
valeur int

### getDegradedPrinting {#getDegradedPrinting--}
```
public static DocumentPrivilege getDegradedPrinting()
```

Autorise l'impression dégradée.

**Returns:**
Élément DocumentPrivilege

### getFillIn {#getFillIn--}
```
public static DocumentPrivilege getFillIn()
```

Autorise le remplissage des formulaires dans le fichier.

**Returns:**
Élément DocumentPrivilege

### getForbidAll {#getForbidAll--}
```
public static DocumentPrivilege getForbidAll()
```

Tout interdit.

**Returns:**
Élément DocumentPrivilege

### getModifyAnnotations {#getModifyAnnotations--}
```
public static DocumentPrivilege getModifyAnnotations()
```

Autorise la modification des annotations du fichier.

**Returns:**
Élément DocumentPrivilege

### getModifyContents {#getModifyContents--}
```
public static DocumentPrivilege getModifyContents()
```

Autorise la modification du fichier.

**Returns:**
Élément DocumentPrivilege

### getPrint {#getPrint--}
```
public static DocumentPrivilege getPrint()
```

Autorise l'impression du fichier.

**Returns:**
Élément DocumentPrivilege

### getPrintAllowLevel {#getPrintAllowLevel--}
```
public final int getPrintAllowLevel()
```

Obtient et définit le niveau d'impression du privilège du document. Identique aux paramètres « Printing Allowed » d'Adobe Professional. 0 : Aucun. 1 : Basse résolution (150 dpi). 2 : Haute résolution. Si la propriété a la valeur -1, le niveau est indéfini.

**Returns:**
valeur int

### getScreenReaders {#getScreenReaders--}
```
public static DocumentPrivilege getScreenReaders()
```

Autorise la lecture à l'écran uniquement.

**Returns:**
Élément DocumentPrivilege

### getValue {#getValue--}
```
public final int getValue()
```



### hashCode {#hashCode--}
```
public int hashCode()
```

Renvoie une valeur de code de hachage pour l'objet. Cette méthode est prise en charge pour le bénéfice des tables de hachage telles que celles fournies par <code>java.util.Hashtable</code>. <p> Le contrat général de <code>hashCode</code> est : <ul> <li>Chaque fois qu'il est invoqué sur le même objet plus d'une fois pendant l'exécution d'une application Java, la méthode <tt>hashCode</tt> doit toujours renvoyer le même entier, à condition qu'aucune information utilisée dans les comparaisons <tt>equals</tt> sur l'objet ne soit modifiée. Cet entier n'a pas besoin de rester identique d'une exécution d'une application à une autre exécution de la même application. <li>Si deux objets sont égaux selon la méthode <tt>equals(Object)</tt>, alors appeler la méthode <code>hashCode</code> sur chacun des deux objets doit produire le même résultat entier. <li>Il n'est <em>pas</em> requis que si deux objets sont inégaux selon la méthode {@link java.lang.Object#equals(java.lang.Object)}, alors appeler la méthode <tt>hashCode</tt> sur chacun des deux objets doit produire des résultats entiers distincts. Cependant, le programmeur doit être conscient que produire des résultats entiers distincts pour des objets inégaux peut améliorer les performances des tables de hachage. </ul> <p> Dans la mesure du raisonnable, la méthode hashCode définie par la classe <tt>Object</tt> renvoie des entiers distincts pour des objets distincts. (Ceci est généralement implémenté en convertissant l'adresse interne de l'objet en un entier, mais cette technique d'implémentation n'est pas requise par le langage de programmation Java<span style="font-size:70%"><sup>TM</sup></span>.)

**Returns:**
une valeur de code de hachage pour cet objet. @see java.lang.Object#equals(java.lang.Object) @see java.util.Hashtable

### isAllowAssembly {#isAllowAssembly--}
```
public boolean isAllowAssembly()
```

Définit la permission qui autorise l'assemblage ou non. true autorise et false interdit.

**Returns:**
valeur booléenne

### isAllowCopy {#isAllowCopy--}
```
public boolean isAllowCopy()
```

Définit la permission qui autorise la copie ou non. true autorise et false interdit.

**Returns:**
valeur booléenne

### isAllowDegradedPrinting {#isAllowDegradedPrinting--}
```
public boolean isAllowDegradedPrinting()
```

Définit la permission qui autorise l'impression dégradée ou non. true autorise et false interdit. Lorsqu'elle est définie, l'impression sera limitée à une représentation de bas niveau de l'apparence, éventuellement de qualité dégradée.

**Returns:**
valeur booléenne

### isAllowFillIn {#isAllowFillIn--}
```
public boolean isAllowFillIn()
```

Définit la permission qui autorise le remplissage de formulaires ou non. true autorise et false interdit.

**Returns:**
valeur booléenne

### isAllowModifyAnnotations {#isAllowModifyAnnotations--}
```
public boolean isAllowModifyAnnotations()
```

Définit la permission qui autorise la modification des annotations ou non. true autorise et false interdit.

**Returns:**
valeur booléenne

### isAllowModifyContents {#isAllowModifyContents--}
```
public boolean isAllowModifyContents()
```

Définit la permission qui autorise la modification du contenu ou non. true autorise et false interdit.

**Returns:**
valeur booléenne

### isAllowPrint {#isAllowPrint--}
```
public boolean isAllowPrint()
```

Définit la permission qui autorise l'impression ou non. true autorise et false interdit.

**Returns:**
valeur booléenne

### isAllowScreenReaders {#isAllowScreenReaders--}
```
public boolean isAllowScreenReaders()
```

Définit la permission qui autorise les lecteurs d'écran ou non. true autorise et false interdit.

**Returns:**
valeur booléenne

### setAllowAssembly {#setAllowAssembly-boolean-}
```
public void setAllowAssembly(boolean value)
```

Définit la permission qui autorise l'assemblage ou non. true autorise et false interdit.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setAllowCopy {#setAllowCopy-boolean-}
```
public void setAllowCopy(boolean value)
```

Définit la permission qui autorise la copie ou non. true autorise et false interdit.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setAllowDegradedPrinting {#setAllowDegradedPrinting-boolean-}
```
public void setAllowDegradedPrinting(boolean value)
```

Définit la permission qui autorise l'impression dégradée ou non. true autorise et false interdit. Lorsqu'elle est définie, l'impression sera limitée à une représentation de bas niveau de l'apparence, éventuellement de qualité dégradée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setAllowFillIn {#setAllowFillIn-boolean-}
```
public void setAllowFillIn(boolean value)
```

Définit la permission qui autorise le remplissage de formulaires ou non. true autorise et false interdit.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setAllowModifyAnnotations {#setAllowModifyAnnotations-boolean-}
```
public void setAllowModifyAnnotations(boolean value)
```

Définit la permission qui autorise la modification des annotations ou non. true autorise et false interdit.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setAllowModifyContents {#setAllowModifyContents-boolean-}
```
public void setAllowModifyContents(boolean value)
```

Définit la permission qui autorise la modification du contenu ou non. true autorise et false interdit.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setAllowPrint {#setAllowPrint-boolean-}
```
public void setAllowPrint(boolean value)
```

Définit la permission qui autorise l'impression ou non. true autorise et false interdit.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setAllowScreenReaders {#setAllowScreenReaders-boolean-}
```
public void setAllowScreenReaders(boolean value)
```

Définit la permission qui autorise les lecteurs d'écran ou non. true autorise et false interdit.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setChangeAllowLevel {#setChangeAllowLevel-int-}
```
public void setChangeAllowLevel(int value)
```

Obtient et définit le niveau de modification du privilège du document. Identique aux paramètres « Changes Allowed » d'Adobe Professional. 0 : Aucun. 1 : Insertion, suppression et rotation des pages. 2 : Remplissage des champs de formulaire et signature des champs de signature existants. 3 : Commentaire, remplissage des champs de formulaire et signature des champs de signature existants. 4 : Tout sauf l'extraction des pages. Si la propriété a la valeur -1, le niveau est indéfini.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int |

### setCopyAllowLevel {#setCopyAllowLevel-int-}
```
public void setCopyAllowLevel(int value)
```

Obtient et définit le niveau de copie du privilège du document. Identique aux paramètres d'autorisation d'Adobe Professional. 0 : Aucun. 1 : Autoriser l'accès au texte pour les appareils de lecture d'écran destinés aux malvoyants. 2 : Autoriser la copie du texte, des images et d'autres contenus. Si la propriété a la valeur -1, le niveau est indéfini.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int |

### setPrintAllowLevel {#setPrintAllowLevel-int-}
```
public void setPrintAllowLevel(int value)
```

Obtient et définit le niveau d'impression du privilège du document. Identique aux paramètres « Printing Allowed » d'Adobe Professional. 0 : Aucun. 1 : Basse résolution (150 dpi). 2 : Haute résolution. Si la propriété a la valeur -1, le niveau est indéfini.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int |
