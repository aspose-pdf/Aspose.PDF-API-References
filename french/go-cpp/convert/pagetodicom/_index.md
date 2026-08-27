---
title: "PageToDICOM"
second_title: "Aspose.PDF pour Go via C++"
description: "Convertir et enregistrer la page spécifiée en tant qu'image DICOM-image."
type: docs
url: /fr/go-cpp/convert/pagetodicom/
---

_Convertir et enregistrer la page spécifiée en image DICOM._

```go
func (document *Document) PageToDICOM(num int32, resolution_dpi int32, filename string) error
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
	// PageToDICOM(num int32, resolution_dpi int32, filename string) enregistre la page spécifiée en fichier image DICOM
	err = pdf.PageToDICOM(1, 100, "sample_page1.dcm")
	if err != nil {
		log.Fatal(err)
	}
}
```
