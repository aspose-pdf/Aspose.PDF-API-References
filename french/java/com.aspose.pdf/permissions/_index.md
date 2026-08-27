---
title: "Permissions"
linktitle: "Permissions"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Indicateur binaire Cette énumération représente les autorisations de l'utilisateur pour un pdf."
type: docs
weight: 3830
url: /fr/java/com.aspose.pdf/permissions/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.Permissions, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.Permissions, com.aspose.ms.System.Enum, com.aspose.pdf.Permissions

```
public final class Permissions extends com.aspose.ms.System.Enum
```

Indicateur binaire Cette énumération représente les autorisations de l'utilisateur pour un pdf.

## Champs

| Champ | Description |
| --- | --- |
| [AssembleDocument](#AssembleDocument) | (Gestionnaires de sécurité de la révision 3 ou supérieure) Assembler le document (insérer, faire pivoter ou supprimer des pages et créer des signets ou des images miniatures), même si {@code ModifyContent} est désactivé. |
| [ExtractContent](#ExtractContent) | (Gestionnaires de sécurité de la révision 2) Copier ou extraire autrement le texte et les graphiques du document, y compris l'extraction du texte et des graphiques (dans le cadre de l'accessibilité aux utilisateurs handicapés ou à d'autres fins). (Gestionnaires de sécurité de la révision 3 ou supérieure) Copier ou extraire autrement le texte et les graphiques du document par des opérations autres que celles contrôlées par {@code ExtractContentWithDisabilities}. |
| [ExtractContentWithDisabilities](#ExtractContentWithDisabilities) | (Gestionnaires de sécurité de la révision 3 ou supérieure) Extraire le texte et les graphiques (dans le cadre de l'accessibilité aux utilisateurs handicapés ou à d'autres fins). |
| [FillForm](#FillForm) | (Gestionnaires de sécurité de la révision 3 ou supérieure) Remplir les champs de formulaire interactifs existants (y compris les champs de signature), même si {@code ModifyTextAnnotations} est désactivé. |
| [ModifyContent](#ModifyContent) | Modifier le contenu du document par des opérations autres que celles contrôlées par {@code ModifyTextAnnotations}, {@code FillForm}, et 11. |
| [ModifyTextAnnotations](#ModifyTextAnnotations) | Ajouter ou modifier des annotations de texte, remplir des champs de formulaire interactifs et, si {@code ModifyContent} est également activé, créer ou modifier des champs de formulaire interactifs (y compris les champs de signature). |
| [PrintDocument](#PrintDocument) | (Gestionnaires de sécurité de la révision 2) Imprimer le document. (Gestionnaires de sécurité de la révision 3 ou supérieure) Imprimer le document (possiblement pas au niveau de qualité le plus élevé, selon que {@code PrintingQuality} soit également activé). |
| [PrintingQuality](#PrintingQuality) | (Gestionnaires de sécurité de révision 3 ou supérieure) Imprimez le document vers une représentation à partir de laquelle une copie numérique fidèle du contenu PDF pourrait être générée. Lorsque ce bit est désactivé (et que le bit 3 est activé), l'impression est limitée à une représentation de bas niveau de l'apparence, éventuellement de qualité dégradée. |

### AssembleDocument {#AssembleDocument}
```
public static final int AssembleDocument
```

(Gestionnaires de sécurité de la révision 3 ou supérieure) Assembler le document (insérer, faire pivoter ou supprimer des pages et créer des signets ou des images miniatures), même si {@code ModifyContent} est désactivé.

### ExtractContent {#ExtractContent}
```
public static final int ExtractContent
```

(Gestionnaires de sécurité de la révision 2) Copier ou extraire autrement le texte et les graphiques du document, y compris l'extraction du texte et des graphiques (dans le cadre de l'accessibilité aux utilisateurs handicapés ou à d'autres fins). (Gestionnaires de sécurité de la révision 3 ou supérieure) Copier ou extraire autrement le texte et les graphiques du document par des opérations autres que celles contrôlées par {@code ExtractContentWithDisabilities}.

### ExtractContentWithDisabilities {#ExtractContentWithDisabilities}
```
public static final int ExtractContentWithDisabilities
```

(Gestionnaires de sécurité de la révision 3 ou supérieure) Extraire le texte et les graphiques (dans le cadre de l'accessibilité aux utilisateurs handicapés ou à d'autres fins).

### FillForm {#FillForm}
```
public static final int FillForm
```

(Gestionnaires de sécurité de la révision 3 ou supérieure) Remplir les champs de formulaire interactifs existants (y compris les champs de signature), même si {@code ModifyTextAnnotations} est désactivé.

### ModifyContent {#ModifyContent}
```
public static final int ModifyContent
```

Modifier le contenu du document par des opérations autres que celles contrôlées par {@code ModifyTextAnnotations}, {@code FillForm}, et 11.

### ModifyTextAnnotations {#ModifyTextAnnotations}
```
public static final int ModifyTextAnnotations
```

Ajouter ou modifier des annotations de texte, remplir des champs de formulaire interactifs et, si {@code ModifyContent} est également activé, créer ou modifier des champs de formulaire interactifs (y compris les champs de signature).

### PrintDocument {#PrintDocument}
```
public static final int PrintDocument
```

(Gestionnaires de sécurité de la révision 2) Imprimer le document. (Gestionnaires de sécurité de la révision 3 ou supérieure) Imprimer le document (possiblement pas au niveau de qualité le plus élevé, selon que {@code PrintingQuality} soit également activé).

### PrintingQuality {#PrintingQuality}
```
public static final int PrintingQuality
```

(Gestionnaires de sécurité de révision 3 ou supérieure) Imprimez le document vers une représentation à partir de laquelle une copie numérique fidèle du contenu PDF pourrait être générée. Lorsque ce bit est désactivé (et que le bit 3 est activé), l'impression est limitée à une représentation de bas niveau de l'apparence, éventuellement de qualité dégradée.
