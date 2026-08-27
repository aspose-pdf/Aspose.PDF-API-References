---
title: "PageMergeLayers"
second_title: "Aspose.PDF pour Go via C++"
description: "Fusionner toutes les couches de la page en une seule couche avec le nom de nouvelle couche spécifié."
type: docs
url: /fr/go-cpp/organize/pagemergelayers/
---

_Fusionne toutes les calques de la page en un seul calque avec le nom du nouveau calque spécifié._

```go
func (document *Document) PageMergeLayers(num int32, newLayerName string) error
```

**Parameters**: 
  * **num** - page number of the PDF-document
  * **newLayerName** - name of the new layer after merging

**Return**: 
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"

func main() {
	// Open(filename string) ouvre un PDF-document avec filename
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() libère les ressources allouées pour le PDF-document
	defer pdf.Close()
	// PageMergeLayers(num int32, newLayerName string) fusionne toutes les calques de la page en un seul calque avec le nom du nouveau calque spécifié
	err = pdf.PageMergeLayers(1, "newLayerName")
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) enregistre le PDF-document précédemment ouvert avec un nouveau nom de fichier
	err = pdf.SaveAs("sample_PageMergeLayers.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
