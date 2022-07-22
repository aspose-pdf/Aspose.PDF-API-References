---
title: Convert
second_title: Référence de l'API Aspose.PDF pour .NET
description: Convertit le fichier source au format source en fichier de destination au format de destination.
type: docs
weight: 790
url: /fr/net/aspose.pdf/document/convert/
---
## Convert(string, LoadOptions, string, SaveOptions) {#convert_3}

Convertit le fichier source au format source en fichier de destination au format de destination.

```csharp
public static void Convert(string srcFileName, LoadOptions loadOptions, string dstFileName, 
    SaveOptions saveOptions)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| srcFileName | String | Le nom du fichier source. |
| loadOptions | LoadOptions | Le format du fichier source. |
| dstFileName | String | Le nom du fichier de destination. |
| saveOptions | SaveOptions | Le format du fichier de destination. |

### Voir également

* class [LoadOptions](../../loadoptions)
* class [SaveOptions](../../saveoptions)
* class [Document](../../document)
* espace de noms [Aspose.Pdf](../../document)
* Assemblée [Aspose.PDF](../../../)

---

## Convert(Stream, LoadOptions, string, SaveOptions) {#convert_1}

Convertit le flux au format source en fichier de destination au format de destination.

```csharp
public static void Convert(Stream srcStream, LoadOptions loadOptions, string dstFileName, 
    SaveOptions saveOptions)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| srcStream | Stream | Le flux source. |
| loadOptions | LoadOptions | Format du flux source. |
| dstFileName | String | Le nom du fichier de destination. |
| saveOptions | SaveOptions | Le format du fichier de destination. |

### Voir également

* class [LoadOptions](../../loadoptions)
* class [SaveOptions](../../saveoptions)
* class [Document](../../document)
* espace de noms [Aspose.Pdf](../../document)
* Assemblée [Aspose.PDF](../../../)

---

## Convert(string, LoadOptions, Stream, SaveOptions) {#convert_2}

Convertit le fichier source au format source en flux au format de destination.

```csharp
public static void Convert(string srcFileName, LoadOptions loadOptions, Stream dstStream, 
    SaveOptions saveOptions)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| srcFileName | String | Le nom du fichier source. |
| loadOptions | LoadOptions | Le format du fichier source. |
| dstStream | Stream | Le flux de destination. |
| saveOptions | SaveOptions | Format du flux de destination. |

### Voir également

* class [LoadOptions](../../loadoptions)
* class [SaveOptions](../../saveoptions)
* class [Document](../../document)
* espace de noms [Aspose.Pdf](../../document)
* Assemblée [Aspose.PDF](../../../)

---

## Convert(Stream, LoadOptions, Stream, SaveOptions) {#convert}

Convertit le flux au format source en flux au format de destination.

```csharp
public static void Convert(Stream srcStream, LoadOptions loadOptions, Stream dstStream, 
    SaveOptions saveOptions)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| srcStream | Stream | Le flux source. |
| loadOptions | LoadOptions | Format du flux source. |
| dstStream | Stream | Le flux de destination. |
| saveOptions | SaveOptions | Le format du fichier de destination. |

### Voir également

* class [LoadOptions](../../loadoptions)
* class [SaveOptions](../../saveoptions)
* class [Document](../../document)
* espace de noms [Aspose.Pdf](../../document)
* Assemblée [Aspose.PDF](../../../)

---

## Convert(string, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) {#convert_7}

Convertir le document et enregistrer les erreurs dans le fichier spécifié.

```csharp
public bool Convert(string outputLogFileName, PdfFormat format, ConvertErrorAction action, 
    ConvertTransparencyAction transparencyAction)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| outputLogFileName | String | Chemin d'accès au fichier dans lequel les commentaires seront stockés. |
| format | PdfFormat | Le format pdf. |
| action | ConvertErrorAction | Action pour les objets qui ne peuvent pas être convertis |
| transparencyAction | ConvertTransparencyAction | Action pour les objets masqués par l'image |

### Return_Value

Le résultat de l'opération

### Voir également

* enum [PdfFormat](../../pdfformat)
* enum [ConvertErrorAction](../../converterroraction)
* enum [ConvertTransparencyAction](../../converttransparencyaction)
* class [Document](../../document)
* espace de noms [Aspose.Pdf](../../document)
* Assemblée [Aspose.PDF](../../../)

---

## Convert(Stream, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) {#convert_5}

Convertir le document et enregistrer les erreurs dans le fichier spécifié.

```csharp
public bool Convert(Stream outputLogStream, PdfFormat format, ConvertErrorAction action, 
    ConvertTransparencyAction transparencyAction)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| outputLogStream | Stream | Stream où les commentaires seront stockés. |
| format | PdfFormat | Le format pdf. |
| action | ConvertErrorAction | Action pour les objets qui ne peuvent pas être convertis |
| transparencyAction | ConvertTransparencyAction | Action pour les objets masqués par l'image |

### Return_Value

Le résultat de l'opération

### Voir également

* enum [PdfFormat](../../pdfformat)
* enum [ConvertErrorAction](../../converterroraction)
* enum [ConvertTransparencyAction](../../converttransparencyaction)
* class [Document](../../document)
* espace de noms [Aspose.Pdf](../../document)
* Assemblée [Aspose.PDF](../../../)

---

## Convert(string, PdfFormat, ConvertErrorAction) {#convert_6}

Convertir le document et enregistrer les erreurs dans le fichier spécifié.

```csharp
public bool Convert(string outputLogFileName, PdfFormat format, ConvertErrorAction action)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| outputLogFileName | String | Chemin d'accès au fichier dans lequel les commentaires seront stockés. |
| format | PdfFormat | Le format pdf. |
| action | ConvertErrorAction | Action pour les objets qui ne peuvent pas être convertis |

### Return_Value

Le résultat de l'opération

### Voir également

* enum [PdfFormat](../../pdfformat)
* enum [ConvertErrorAction](../../converterroraction)
* class [Document](../../document)
* espace de noms [Aspose.Pdf](../../document)
* Assemblée [Aspose.PDF](../../../)

---

## Convert(PdfFormatConversionOptions) {#convert_2}

Convertir le document en utilisant les options de conversion spécifiées

```csharp
public bool Convert(PdfFormatConversionOptions options)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| options | PdfFormatConversionOptions | ensemble d'options pour convertir un document PDF |

### Return_Value

Le résultat de l'opération

### Voir également

* class [PdfFormatConversionOptions](../../pdfformatconversionoptions)
* class [Document](../../document)
* espace de noms [Aspose.Pdf](../../document)
* Assemblée [Aspose.PDF](../../../)

---

## Convert(CallBackGetHocr) {#convert_3}

Convertir le document et enregistrer les erreurs dans le fichier spécifié.

```csharp
public bool Convert(CallBackGetHocr callback)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| callback | CallBackGetHocr | Action pour les objets qui ne peuvent pas être convertis |

### Return_Value

Le résultat de l'opération

### Voir également

* delegate [CallBackGetHocr](../../document.callbackgethocr)
* class [Document](../../document)
* espace de noms [Aspose.Pdf](../../document)
* Assemblée [Aspose.PDF](../../../)

---

## Convert(Stream, PdfFormat, ConvertErrorAction) {#convert_4}

Convertir le document et enregistrer les erreurs dans le flux spécifié.

```csharp
public bool Convert(Stream outputLogStream, PdfFormat format, ConvertErrorAction action)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| outputLogStream | Stream | Stream où les commentaires seront stockés. |
| format | PdfFormat | Format PDF. |
| action | ConvertErrorAction | Action pour les objets qui ne peuvent pas être convertis |

### Return_Value

Le résultat de l'opération

### Voir également

* enum [PdfFormat](../../pdfformat)
* enum [ConvertErrorAction](../../converterroraction)
* class [Document](../../document)
* espace de noms [Aspose.Pdf](../../document)
* Assemblée [Aspose.PDF](../../../)

---

## Convert(Fixup, Stream, bool, object[]) {#convert}

Convertir le document en appliquant le Fixup.

```csharp
public bool Convert(Fixup fixup, Stream outputLog, bool onlyValidation = false, 
    object[] parameters = null)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| fixup | Fixup | Le type de correction. |
| outputLog | Stream | Le journal du processus. |
| onlyValidation | Boolean | Uniquement la validation des documents. |
| parameters | Object[] | Propriétés de Fixup qui ne peuvent pas être définies. |

### Return_Value

Le résultat de l'opération.

### Voir également

* enum [Fixup](../../fixup)
* class [Document](../../document)
* espace de noms [Aspose.Pdf](../../document)
* Assemblée [Aspose.PDF](../../../)

---

## Convert(Fixup, string, bool, object[]) {#convert_1}

Convertir le document en appliquant le Fixup.

```csharp
public bool Convert(Fixup fixup, string outputLog, bool onlyValidation = false, 
    object[] parameters = null)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| fixup | Fixup | Le type de correction. |
| outputLog | String | Le journal du processus. |
| onlyValidation | Boolean | Uniquement la validation des documents. |
| parameters | Object[] | Propriétés de Fixup qui ne peuvent pas être définies. |

### Return_Value

Le résultat de l'opération.

### Voir également

* enum [Fixup](../../fixup)
* class [Document](../../document)
* espace de noms [Aspose.Pdf](../../document)
* Assemblée [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
