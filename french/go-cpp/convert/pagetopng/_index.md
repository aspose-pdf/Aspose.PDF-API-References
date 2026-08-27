---
title: "PageToPng"
second_title: "Aspose.PDF pour Go via C++"
description: "Convertir et enregistrer la page spécifiée au format Png-image."
type: docs
url: /fr/go-cpp/convert/pagetopng/
---

_Convertir et enregistrer la page spécifiée en image Png._

```go
func (document *Document) PageToPng(num int32, resolution_dpi int32, filename string) error
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
	// PageToPng(num int32, resolution_dpi int32, filename string) enregistre la page spécifiée en fichier image Png
	err = pdf.PageToPng(1, 100, "sample_page1.png")
	if err != nil {
		log.Fatal(err)
	}
}
```
