---
title: "OptimizeFileSize"
second_title: Aspose.PDF for Go via C++
description: "Optimize size of PDF-document with image compression quality."
type: docs
url: /go-cpp/organize/optimizefilesize/
---

_Optimize size of PDF-document with image compression quality._

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
        // Open(filename string) opens a PDF-document with filename
        pdf, err := asposepdf.Open("sample.pdf")
        if err != nil {
                log.Fatal(err)
        }
        // Close() releases allocated resources for PDF-document
        defer pdf.Close()
        // OptimizeFileSize(imageQuality int32) optimizes size of PDF-document with image compression quality
        err = pdf.OptimizeFileSize(20)
        if err != nil {
                log.Fatal(err)
        }
        // SaveAs(filename string) saves previously opened PDF-document with new filename
        err = pdf.SaveAs("sample_OptimizeFileSize.pdf")
        if err != nil {
                log.Fatal(err)
        }
}
```
