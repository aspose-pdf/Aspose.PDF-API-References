---
title: "com.aspose.pdf.devices"
linktitle: "com.aspose.pdf.devices"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Le package com.aspose.pdf.devices fournit des classes utilisées pour représenter le document sous forme d'image(s) ou de texte brut."
type: docs
weight: 140
url: /fr/java/com.aspose.pdf.devices/
---
Le package com.aspose.pdf.devices fournit des classes utilisées pour représenter le document sous forme d'image(s) ou de texte brut.

## Classes

| Classe | Description |
| --- | --- |
| [BmpDevice](./bmpdevice/) | Représente un dispositif d'image qui aide à enregistrer les pages de documents pdf au format bmp. |
| [Device](./device/) | Classe abstraite pour tous les types de dispositifs. Le dispositif est utilisé pour représenter un document pdf dans un certain format. Par exemple, la page d'un document peut être représentée comme une image ou du texte. |
| [DicomDevice](./dicomdevice/) | Représente un dispositif d'image qui aide à enregistrer les pages de documents PDF au format Dicom. |
| [DocumentDevice](./documentdevice/) | Classe abstraite pour tous les dispositifs utilisés pour traiter l'intégralité du document PDF. |
| [EmfDevice](./emfdevice/) | Représente un dispositif d'image qui aide à enregistrer les pages de documents PDF au format emf. |
| [FormPresentationMode](./formpresentationmode/) | Utilisé pour spécifier le mode de présentation du formulaire lors de l'impression ou de la conversion en documents PDF image. |
| [GifDevice](./gifdevice/) | Représente un dispositif d'image qui aide à enregistrer les pages de documents PDF au format gif. |
| [GraphicsDevice](./graphicsdevice/) | Représente un dispositif d'image qui aide à rendre les pages de documents PDF sous forme de graphiques. |
| [ImageDevice](./imagedevice/) | Une classe abstraite pour les dispositifs d'image. |
| [InternalHelper](./internalhelper/) |  |
| [JpegDevice](./jpegdevice/) | Représente un dispositif d'image qui aide à enregistrer les pages de documents PDF au format jpeg. |
| [Margins](./margins/) | Cette classe représente les marges d'une image. |
| [PageDevice](./pagedevice/) | Classe abstraite pour tous les dispositifs utilisés pour traiter une certaine page du document PDF. |
| [PngDevice](./pngdevice/) | Représente un dispositif d'image qui aide à enregistrer les pages de documents PDF au format png. |
| [Resolution](./resolution/) | Représente une classe permettant de stocker la résolution d'image. |
| [TextDevice](./textdevice/) | <p> Représente une classe permettant de convertir les pages de documents PDF en texte. </p> <hr> <pre> L'exemple montre comment extraire le texte de la première page du document PDF. Document doc = new Document(inFile); String extractedText; ByteArrayOutputStream ms = new ByteArrayOutputStream(); try { // create text device TextDevice device = new TextDevice(); // convert the page and save text to the stream device.process(doc.getPages().get_Item(1), ms); // use the extracted text extractedText = Encoding.getUnicode().getString(ms.toByteArray()); ms.close(); } catch (IOException e) { e.printStackTrace(); } </pre> <hr> <p> L'objet {@code TextDevice} est essentiellement utilisé pour extraire le texte d'une page PDF. </p> |
| [ThumbnailDevice](./thumbnaildevice/) | Représente un dispositif d'image qui enregistre les pages de documents PDF sous forme d'image miniature. |
| [TiffDevice](./tiffdevice/) | Cette classe aide à enregistrer les pages d'un document PDF une par une dans une seule image TIFF. |
| [TiffSettings](./tiffsettings/) | Cette classe représente les paramètres d'importation de PDF vers TIFF. |
| [TiffSettings.IndexedConversionType](./tiffsettings.indexedconversiontype/) | Classe représentant les types de conversion indexés |
## Enums

| Enum | Description |
| --- | --- |
| [ColorDepth](./colordepth/) | Utilisé pour spécifier la valeur du paramètre transmis à un dispositif d'image TIFF. |
| [CompressionType](./compressiontype/) | Utilisé pour spécifier la valeur du paramètre transmis à un dispositif d'image TIFF. |
| [ShapeType](./shapetype/) | Cette énumération représente le type de forme pour les images extraites. |
