---
title: "export_fdf"
second_title: "Aspose.PDF for Rust via C++"
description: "将先前打开的带有 AcroForm 的 PDF 文档导出为具有文件名的 FDF 文档。"
type: docs
url: /zh/rust-cpp/convert/export_fdf/
---

_将先前打开的带有 AcroForm 的 PDF 文档导出为具有文件名的 FDF 文档。_

```rust
pub fn export_fdf(&self, filename: &str) -> Result<(), PdfError>
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

    // 将先前打开的带有 AcroForm 的 PDF 文档导出为 FDF 文档
    pdf.export_fdf("sample.fdf")?;

    Ok(())
}

```