---
title: Document.Convert
second_title: Aspose.PDF for .NET API Reference
description: Méthode Document. Convertir le document et enregistrer les erreurs dans le fichier spécifié
type: docs
weight: 580
url: /fr/net/aspose.pdf/document/convert/
---
## Convert(string, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) {#convert_8}

Convertir le document et enregistrer les erreurs dans le fichier spécifié.

```csharp
public bool Convert(string outputLogFileName, PdfFormat format, ConvertErrorAction action, 
    ConvertTransparencyAction transparencyAction)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| outputLogFileName | String | Chemin vers le fichier où les commentaires seront stockés. |
| format | PdfFormat | Le format pdf. |
| action | ConvertErrorAction | Action pour les objets qui ne peuvent pas être convertis |
| transparencyAction | ConvertTransparencyAction | Action pour les objets d'image masqués |

### Valeur de retour

Le résultat de l'opération

### Voir aussi

* enum [PdfFormat](../../pdfformat/)
* enum [ConvertErrorAction](../../converterroraction/)
* enum [ConvertTransparencyAction](../../converttransparencyaction/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Stream, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) {#convert_6}

Convertir le document et enregistrer les erreurs dans le fichier spécifié.

```csharp
public bool Convert(Stream outputLogStream, PdfFormat format, ConvertErrorAction action, 
    ConvertTransparencyAction transparencyAction)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| outputLogStream | Stream | Flux où les commentaires seront stockés. |
| format | PdfFormat | Le format pdf. |
| action | ConvertErrorAction | Action pour les objets qui ne peuvent pas être convertis |
| transparencyAction | ConvertTransparencyAction | Action pour les objets d'image masqués |

### Valeur de retour

Le résultat de l'opération

### Voir aussi

* enum [PdfFormat](../../pdfformat/)
* enum [ConvertErrorAction](../../converterroraction/)
* enum [ConvertTransparencyAction](../../converttransparencyaction/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(string, PdfFormat, ConvertErrorAction) {#convert_7}

Convertir le document et enregistrer les erreurs dans le fichier spécifié.

```csharp
public bool Convert(string outputLogFileName, PdfFormat format, ConvertErrorAction action)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| outputLogFileName | String | Chemin vers le fichier où les commentaires seront stockés. |
| format | PdfFormat | Le format pdf. |
| action | ConvertErrorAction | Action pour les objets qui ne peuvent pas être convertis |

### Valeur de retour

Le résultat de l'opération

### Voir aussi

* enum [PdfFormat](../../pdfformat/)
* enum [ConvertErrorAction](../../converterroraction/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(PdfFormatConversionOptions) {#convert_2}

Convertir le document en utilisant les options de conversion spécifiées

```csharp
public bool Convert(PdfFormatConversionOptions options)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| options | PdfFormatConversionOptions | ensemble d'options pour convertir le document PDF |

### Valeur de retour

Le résultat de l'opération

### Voir aussi

* class [PdfFormatConversionOptions](../../pdfformatconversionoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(CallBackGetHocrWithPage, bool) {#convert_4}

Reconnaître les images à l'intérieur du document et ajouter des chaînes hocr par-dessus.

```csharp
public bool Convert(CallBackGetHocrWithPage callback, bool flattenImages = false)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| callback | CallBackGetHocrWithPage | Action pour les images qui seront traitées par la reconnaissance hocr. |
| flattenImages | Boolean | Le texte dans les images pdf peut être peint en utilisant les mécanismes de masques, auquel cas les images doivent être aplaties. |

### Valeur de retour

Le résultat de l'opération. S'il n'y a pas d'images dans le document, retourne !:false.

### Voir aussi

* delegate [CallBackGetHocrWithPage](../../document.callbackgethocrwithpage/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(CallBackGetHocr, bool) {#convert_3}

Reconnaître les images à l'intérieur du document et ajouter des chaînes hocr par-dessus.

```csharp
public bool Convert(CallBackGetHocr callback, bool flattenImages = false)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| callback | CallBackGetHocr | Action pour les images qui seront traitées par la reconnaissance hocr. |
| flattenImages | Boolean | Le texte dans les images pdf peut être peint en utilisant les mécanismes de masques, auquel cas les images doivent être aplaties. |

### Valeur de retour

Le résultat de l'opération. S'il n'y a pas d'images dans le document, retourne !:false.

### Voir aussi

* delegate [CallBackGetHocr](../../document.callbackgethocr/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Stream, PdfFormat, ConvertErrorAction) {#convert_5}

Convertir le document et enregistrer les erreurs dans le flux spécifié.

```csharp
public bool Convert(Stream outputLogStream, PdfFormat format, ConvertErrorAction action)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| outputLogStream | Stream | Flux où les commentaires seront stockés. |
| format | PdfFormat | Format pdf. |
| action | ConvertErrorAction | Action pour les objets qui ne peuvent pas être convertis |

### Valeur de retour

Le résultat de l'opération

### Voir aussi

* enum [PdfFormat](../../pdfformat/)
* enum [ConvertErrorAction](../../converterroraction/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Fixup, Stream, bool, object[]) {#convert}

Convertir le document en appliquant le Fixup.

```csharp
public bool Convert(Fixup fixup, Stream outputLog, bool onlyValidation = false, 
    object[] parameters = null)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fixup | Fixup | Le type de Fixup. |
| outputLog | Stream | Le journal du processus. |
| onlyValidation | Boolean | Validation uniquement du document. |
| parameters | Object[] | Propriétés pour Fixup qui ne peuvent pas être définies. |

### Valeur de retour

Le résultat de l'opération.

### Voir aussi

* enum [Fixup](../../fixup/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Fixup, string, bool, object[]) {#convert_1}

Convertir le document en appliquant le Fixup.

```csharp
public bool Convert(Fixup fixup, string outputLog, bool onlyValidation = false, 
    object[] parameters = null)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fixup | Fixup | Le type de Fixup. |
| outputLog | String | Le journal du processus. |
| onlyValidation | Boolean | Validation uniquement du document. |
| parameters | Object[] | Propriétés pour Fixup qui ne peuvent pas être définies. |

### Valeur de retour

Le résultat de l'opération.

### Voir aussi

* enum [Fixup](../../fixup/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(string, LoadOptions, string, SaveOptions) {#convert_3}

Convertit le fichier source dans le format source en fichier de destination dans le format de destination.

```csharp
public static void Convert(string srcFileName, LoadOptions loadOptions, string dstFileName, 
    SaveOptions saveOptions)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| srcFileName | String | Le nom du fichier source. |
| loadOptions | LoadOptions | Le format du fichier source. |
| dstFileName | String | Le nom du fichier de destination. |
| saveOptions | SaveOptions | Le format du fichier de destination. |

### Voir aussi

* class [LoadOptions](../../loadoptions/)
* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Stream, LoadOptions, string, SaveOptions) {#convert_1}

Convertit le flux dans le format source en fichier de destination dans le format de destination.

```csharp
public static void Convert(Stream srcStream, LoadOptions loadOptions, string dstFileName, 
    SaveOptions saveOptions)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| srcStream | Stream | Le flux source. |
| loadOptions | LoadOptions | Le format du flux source. |
| dstFileName | String | Le nom du fichier de destination. |
| saveOptions | SaveOptions | Le format du fichier de destination. |

### Voir aussi

* class [LoadOptions](../../loadoptions/)
* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(string, LoadOptions, Stream, SaveOptions) {#convert_2}

Convertit le fichier source dans le format source en flux dans le format de destination.

```csharp
public static void Convert(string srcFileName, LoadOptions loadOptions, Stream dstStream, 
    SaveOptions saveOptions)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| srcFileName | String | Le nom du fichier source. |
| loadOptions | LoadOptions | Le format du fichier source. |
| dstStream | Stream | Le flux de destination. |
| saveOptions | SaveOptions | Le format du flux de destination. |

### Voir aussi

* class [LoadOptions](../../loadoptions/)
* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Stream, LoadOptions, Stream, SaveOptions) {#convert}

Convertit le flux dans le format source en flux dans le format de destination.

```csharp
public static void Convert(Stream srcStream, LoadOptions loadOptions, Stream dstStream, 
    SaveOptions saveOptions)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| srcStream | Stream | Le flux source. |
| loadOptions | LoadOptions | Le format du flux source. |
| dstStream | Stream | Le flux de destination. |
| saveOptions | SaveOptions | Le format du fichier de destination. |

### Voir aussi

* class [LoadOptions](../../loadoptions/)
* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)