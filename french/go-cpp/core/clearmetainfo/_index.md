---
title: "ClearMetaInfo"
second_title: "Aspose.PDF pour Go via C++"
description: "Effacer toutes les valeurs des métadonnées du document PDF."
type: docs
url: /fr/go-cpp/core/clearmetainfo/
---

_Effacer toutes les valeurs des métadonnées du document PDF._

```go
func (document *Document) ClearMetaInfo() error
```

**Parameters**: 

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
	// ClearMetaInfo() efface toutes les valeurs des métadonnées du document PDF
	err = pdf.ClearMetaInfo()
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) enregistre le PDF-document précédemment ouvert avec un nouveau nom de fichier
	err = pdf.SaveAs("sample_ClearMetaInfo.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
