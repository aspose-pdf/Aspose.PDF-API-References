---
title: "PageReplaceFont"
second_title: "Aspose.PDF pour Go via C++"
description: "Remplacer la police dans la page."
type: docs
url: /fr/go-cpp/organize/pagereplacefont/
---

_Remplacer la police dans la page._

```go
func (document *Document) PageReplaceFont(num int32, findFontName, replaceFontName string) error
```

**Parameters**: 
  * **num** - page number of the PDF-document
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
        // Open(filename string) ouvre un PDF-document avec filename
        pdf, err := asposepdf.Open("sample.pdf")
        if err != nil {
                log.Fatal(err)
        }
        // Close() libère les ressources allouées pour le PDF-document
        defer pdf.Close()
        // PageReplaceFont(num int32, findFontName, replaceFontName string) remplace la police dans la page
        err = pdf.PageReplaceFont(1, "Times-BoldItalic", "Helvetica-Bold")
        if err != nil {
                log.Fatal(err)
        }
        // SaveAs(filename string) enregistre le PDF-document précédemment ouvert avec un nouveau nom de fichier
        err = pdf.SaveAs("sample_page1_ReplaceFont.pdf")
        if err != nil {
                log.Fatal(err)
        }
}
```
