---
title: "OptimizeFileSize"
second_title: "Aspose.PDF pour Go via C++"
description: "Optimiser la taille d'un document PDF avec la qualité de compression des images."
type: docs
url: /fr/go-cpp/organize/optimizefilesize/
---

_Optimiser la taille du PDF-document avec la qualité de compression d'image._

```go
func (document *Document) OptimizeFileSize(imageQuality int32) error
```

**Parameters**: 
  * **imageQuality** - image compression quality 

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
        // OptimizeFileSize(imageQuality int32) optimise la taille du PDF-document avec la qualité de compression d'image
        err = pdf.OptimizeFileSize(20)
        if err != nil {
                log.Fatal(err)
        }
        // SaveAs(filename string) enregistre le PDF-document précédemment ouvert avec un nouveau nom de fichier
        err = pdf.SaveAs("sample_OptimizeFileSize.pdf")
        if err != nil {
                log.Fatal(err)
        }
}
```
