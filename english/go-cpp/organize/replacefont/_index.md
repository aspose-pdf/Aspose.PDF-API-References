---
title: "ReplaceFont"
second_title: Aspose.PDF for Go via C++
description: "Replace font in a PDF-document."
type: docs
url: /go-cpp/organize/replacefont/
---

_Replace font in a PDF-document._

```go
func (document *Document) ReplaceFont(findFontName, replaceFontName string) error
```

**Parameters**: 
  * **findFontName** - font name to search
  * **replaceFontName** - font name to replace

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
        // ReplaceFont(findFontName, replaceFontName string) replaces font in a PDF-document
        err = pdf.ReplaceFont("Helvetica", "Courier")
        if err != nil {
                log.Fatal(err)
        }
        // SaveAs(filename string) saves previously opened PDF-document with new filename
        err = pdf.SaveAs("sample_ReplaceFont.pdf")
        if err != nil {
                log.Fatal(err)
        }
}
```
