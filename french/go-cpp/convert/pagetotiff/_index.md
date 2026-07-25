---
title: "PageToTiff"
second_title: "Aspose.PDF pour Go via C++"
description: "Convertir et enregistrer la page spécifiée au format Tiff-image."
type: docs
url: /fr/go-cpp/convert/pagetotiff/
---

_Convertir et enregistrer la page spécifiée en image Tiff._

```go
func (document *Document) PageToTiff(num int32, resolution_dpi int32, filename string) error
```

**Parameters**: 
  * **num** - page number of the PDF-document
  * **resolution_dpi** - resolution in DPI of the resulting file
  * **filename** - new filename

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
	// PageToTiff(num int32, resolution_dpi int32, filename string) enregistre la page spécifiée en fichier image Tiff
	err = pdf.PageToTiff(1, 100, "sample_page1.tiff")
	if err != nil {
		log.Fatal(err)
	}
}
```
