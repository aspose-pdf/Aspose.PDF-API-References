---
title: "EnregistrerSvgZip"
second_title: "Aspose.PDF pour Go via C++"
description: "Convertir et enregistrer le PDF-document précédemment ouvert au format SVG-archive."
type: docs
url: /fr/go-cpp/convert/savesvgzip/
---

_Convertir et enregistrer le PDF-document précédemment ouvert en tant qu'archive SVG._

```go
func (document *Document) SaveSvgZip(filename string) error
```

**Parameters**: 
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
	// SaveSvgZip(filename string) enregistre le PDF-document précédemment ouvert en tant qu'archive SVG avec le nom de fichier
	err = pdf.SaveSvgZip("sample_svg.zip")
	if err != nil {
		log.Fatal(err)
	}
}
```
