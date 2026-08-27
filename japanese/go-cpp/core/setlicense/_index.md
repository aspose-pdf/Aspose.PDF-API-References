---
title: "SetLicense"
second_title: "C++ 経由の Go 用 Aspose.PDF"
description: "ファイル名でライセンスを設定します。"
type: docs
url: /ja/go-cpp/core/setlicense/
---

_ファイル名でライセンスを設定します。_

```go
func (document *Document) SetLicense(filename string) error
```

**Parameters**: 
  * **filename** - full name of the license file

**Return**: 
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"

func main() {
	// Open(filename string) は、指定したファイル名の PDF-document を開きます
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() は、PDF-document に割り当てられたリソースを解放します
	defer pdf.Close()
	// SetLicense(filename string) はファイル名でライセンスを設定します
	err = pdf.SetLicense("Aspose.PDF.GoViaCPP.lic")
	if err != nil {
		log.Fatal(err)
	}
	// PDFドキュメントの操作
	// ...
}
```
