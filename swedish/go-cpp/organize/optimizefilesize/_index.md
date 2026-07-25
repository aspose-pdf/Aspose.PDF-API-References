---
title: "OptimizeFileSize"
second_title: "Aspose.PDF för Go via C++"
description: "Optimera storleken på PDF-dokumentet med bildkomprimeringskvalitet."
type: docs
url: /sv/go-cpp/organize/optimizefilesize/
---

_Optimera storleken på PDF-dokument med bildkomprimeringskvalitet._

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
        // Open(filename string) öppnar ett PDF-dokument med filnamn
        pdf, err := asposepdf.Open("sample.pdf")
        if err != nil {
                log.Fatal(err)
        }
        // Close() frigör allokerade resurser för PDF-dokument
        defer pdf.Close()
        // OptimizeFileSize(imageQuality int32) optimerar storleken på PDF-dokument med bildkomprimeringskvalitet
        err = pdf.OptimizeFileSize(20)
        if err != nil {
                log.Fatal(err)
        }
        // SaveAs(filename string) sparar tidigare öppnat PDF-dokument med ett nytt filnamn
        err = pdf.SaveAs("sample_OptimizeFileSize.pdf")
        if err != nil {
                log.Fatal(err)
        }
}
```
