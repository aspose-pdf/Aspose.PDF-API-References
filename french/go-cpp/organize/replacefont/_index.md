---
title: "ReplaceFont"
second_title: "Aspose.PDF pour Go via C++"
description: "Remplacer la police dans un document PDF."
type: docs
url: /fr/go-cpp/organize/replacefont/
---

_Remplace la police dans un PDF-document._

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
        // Open(filename string) ouvre un PDF-document avec filename
        pdf, err := asposepdf.Open("sample.pdf")
        if err != nil {
                log.Fatal(err)
        }
        // Close() libère les ressources allouées pour le PDF-document
        defer pdf.Close()
        // ReplaceFont(findFontName, replaceFontName string) remplace la police dans un PDF-document
        err = pdf.ReplaceFont("Helvetica", "Courier")
        if err != nil {
                log.Fatal(err)
        }
        // SaveAs(filename string) enregistre le PDF-document précédemment ouvert avec un nouveau nom de fichier
        err = pdf.SaveAs("sample_ReplaceFont.pdf")
        if err != nil {
                log.Fatal(err)
        }
}
```
