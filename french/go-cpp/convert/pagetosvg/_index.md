---
title: "PageToSvg"
second_title: "Aspose.PDF pour Go via C++"
description: "Convertir et enregistrer la page spécifiée en tant qu'image Svg-image."
type: docs
url: /fr/go-cpp/convert/pagetosvg/
---

_Convertir et enregistrer la page spécifiée en image Svg._

```go
func (document *Document) PageToSvg(num int32, filename string) error
```

**Parameters**: 
  * **num** - page number of the PDF-document
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
	// PageToSvg(num int32, filename string) enregistre la page spécifiée en tant que fichier image Svg
	err = pdf.PageToSvg(1, "sample_page1.svg")
	if err != nil {
		log.Fatal(err)
	}
}
```
