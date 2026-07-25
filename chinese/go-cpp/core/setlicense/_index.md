---
title: "SetLicense"
second_title: "Aspose.PDF for Go via C++"
description: "使用文件名设置许可证。"
type: docs
url: /zh/go-cpp/core/setlicense/
---

_使用文件名设置许可证._

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
	// Open(filename string) 使用文件名打开 PDF-document
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() 释放为 PDF-document 分配的资源
	defer pdf.Close()
	// SetLicense(filename string) 使用文件名进行授权
	err = pdf.SetLicense("Aspose.PDF.GoViaCPP.lic")
	if err != nil {
		log.Fatal(err)
	}
	// 使用 PDF-document
	// ...
}
```
