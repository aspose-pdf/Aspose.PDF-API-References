---
title: "PageRemoveWatermarks"
second_title: "Aspose.PDF pour Go via C++"
description: "Supprimer les filigranes de la page."
type: docs
url: /fr/go-cpp/organize/pageremovewatermarks/
---

_Supprimer les filigranes de la page._

```go
func (document *Document) PageRemoveWatermarks(num int32) error
```

**Parameters**: 
  * **num** - page number of the PDF-document

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
        // PageRemoveWatermarks(num int32) supprime les filigranes de la page
        err = pdf.PageRemoveWatermarks(1)
        if err != nil {
                log.Fatal(err)
        }
        // SaveAs(filename string) enregistre le PDF-document précédemment ouvert avec un nouveau nom de fichier
        err = pdf.SaveAs("sample_page1_RemoveWatermarks.pdf")
        if err != nil {
                log.Fatal(err)
        }
}
```
