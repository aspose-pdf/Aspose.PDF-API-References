---
title: "RemoveTextFooters"
second_title: "Aspose.PDF pour Go via C++"
description: "Supprimer les pieds de page de texte d'un document PDF."
type: docs
url: /fr/go-cpp/organize/removetextfooters/
---

_Supprimer les pieds de texte du PDF-document._

```go
func (document *Document) RemoveTextFooters() error
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
        // RemoveTextFooters() supprime les pieds de texte du PDF-document
        err = pdf.RemoveTextFooters()
        if err != nil {
                log.Fatal(err)
        }
        // SaveAs(filename string) enregistre le PDF-document précédemment ouvert avec un nouveau nom de fichier
        err = pdf.SaveAs("sample_RemoveTextFooters.pdf")
        if err != nil {
                log.Fatal(err)
        }
}
```
