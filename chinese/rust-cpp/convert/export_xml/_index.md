---
title: "export_xml"
second_title: "Aspose.PDF for Rust via C++"
description: "将先前打开的带有 AcroForm 的 PDF-document 导出为带文件名的 XML-document。"
type: docs
url: /zh/rust-cpp/convert/export_xml/
---

_将先前打开的带有 AcroForm 的 PDF-document 导出为带文件名的 XML-document。_

```rust
pub fn export_xml(&self, filename: &str) -> Result<(), PdfError>
```

**Arguments**
  * **filename** - the path to the output file

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // 打开具有文件名的 PDF 文档
    let pdf = Document::open("sample.pdf")?;

    // 从先前打开的带有 AcroForm 的 PDF-document 导出为 XML-document
    pdf.export_xml("sample.xml")?;

    Ok(())
}

```