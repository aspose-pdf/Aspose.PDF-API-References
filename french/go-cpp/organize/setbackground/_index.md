---
title: "SetBackground"
second_title: "Aspose.PDF pour Go via C++"
description: "Définir la couleur d'arrière-plan du PDF-document."
type: docs
url: /fr/go-cpp/organize/setbackground/
---

_Définir la couleur d'arrière-plan du document PDF._

```go
func (document *Document) SetBackground(r, g, b int32) error
```

**Parameters**: 
  * **r** - Red color of RGB color model (0-255)
  * **g** - Green color of RGB color model (0-255)
  * **b** - Blue color of RGB color model (0-255)

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
	// SetBackground(r, g, b int32) définit la couleur d'arrière-plan du document PDF
	err = pdf.SetBackground(200, 100, 101)
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) enregistre le PDF-document précédemment ouvert avec un nouveau nom de fichier
	err = pdf.SaveAs("sample_SetBackground.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
