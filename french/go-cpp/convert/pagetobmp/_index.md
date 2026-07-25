---
title: "PageToBmp"
second_title: "Aspose.PDF pour Go via C++"
description: "Convertir et enregistrer la page spécifiée au format Bmp-image."
type: docs
url: /fr/go-cpp/convert/pagetobmp/
---

_Convertir et enregistrer la page spécifiée en image Bmp._

```go
func (document *Document) PageToBmp(num int32, resolution_dpi int32, filename string) error
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
	// PageToBmp(num int32, resolution_dpi int32, filename string) enregistre la page spécifiée en fichier image Bmp
	err = pdf.PageToBmp(1, 100, "sample_page1.bmp")
	if err != nil {
		log.Fatal(err)
	}
}
```
