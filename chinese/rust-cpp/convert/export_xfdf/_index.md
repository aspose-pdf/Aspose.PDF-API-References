---
title: "export_xfdf"
second_title: "Aspose.PDF for Rust via C++"
description: "将先前打开的带有 AcroForm 的 PDF-document 导出为带文件名的 XFDF-document。"
type: docs
url: /zh/rust-cpp/convert/export_xfdf/
---

_将先前打开的带有 AcroForm 的 PDF-document 导出为带文件名的 XFDF-document。_

```rust
pub fn export_xfdf(&self, filename: &str) -> Result<(), PdfError>
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

    // 从先前打开的带有 AcroForm 的 PDF-document 导出为 XFDF-document
    pdf.export_xfdf("sample.xfdf")?;

    Ok(())
}

```