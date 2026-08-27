---
title: "SaveDocXEnhanced"
second_title: "Aspose.PDF pour Go via C++"
description: "Convertir et enregistrer le PDF-document précédemment ouvert au format DocX-document avec le Mode de Reconnaissance Améliorée (tables et paragraphes entièrement modifiables)."
type: docs
url: /fr/go-cpp/convert/savedocxenhanced/
---

_Convertir et enregistrer le PDF-document précédemment ouvert en document DocX avec le Mode de Reconnaissance Amélioré (tables et paragraphes entièrement éditables)._

```go
func (document *Document) SaveDocXEnhanced(filename string) error
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
	// SaveDocX(filename string) enregistre le PDF-document précédemment ouvert en document DocX en Mode de Reconnaissance Amélioré avec filename
	err = pdf.SaveDocXEnhanced("sampleEnhanced.docx")
	if err != nil {
		log.Fatal(err)
	}
}
```
