---
title: "OptimizeFileSize"
second_title: "Aspose.PDF per Go via C++"
description: "Ottimizza le dimensioni del PDF-document con la qualità di compressione delle immagini."
type: docs
url: /it/go-cpp/organize/optimizefilesize/
---

_Ottimizza le dimensioni del documento PDF con la qualità di compressione delle immagini._

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
        // Open(filename string) apre un PDF-document con filename
        pdf, err := asposepdf.Open("sample.pdf")
        if err != nil {
                log.Fatal(err)
        }
        // Close() rilascia le risorse allocate per il PDF-document
        defer pdf.Close()
        // OptimizeFileSize(imageQuality int32) ottimizza le dimensioni del documento PDF con la qualità di compressione delle immagini
        err = pdf.OptimizeFileSize(20)
        if err != nil {
                log.Fatal(err)
        }
        // SaveAs(filename string) salva il PDF-document precedentemente aperto con un nuovo nome file
        err = pdf.SaveAs("sample_OptimizeFileSize.pdf")
        if err != nil {
                log.Fatal(err)
        }
}
```
