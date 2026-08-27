---
title: "RemoveTextFooters"
second_title: "Aspose.PDF för Go via C++"
description: "Ta bort textsidfötter från PDF-dokumentet."
type: docs
url: /sv/go-cpp/organize/removetextfooters/
---

_Ta bort textfotter från PDF-dokumentet._

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
        // Open(filename string) öppnar ett PDF-dokument med filnamn
        pdf, err := asposepdf.Open("sample.pdf")
        if err != nil {
                log.Fatal(err)
        }
        // Close() frigör allokerade resurser för PDF-dokument
        defer pdf.Close()
        // RemoveTextFooters() tar bort textfotter från PDF-dokumentet
        err = pdf.RemoveTextFooters()
        if err != nil {
                log.Fatal(err)
        }
        // SaveAs(filename string) sparar tidigare öppnat PDF-dokument med ett nytt filnamn
        err = pdf.SaveAs("sample_RemoveTextFooters.pdf")
        if err != nil {
                log.Fatal(err)
        }
}
```
