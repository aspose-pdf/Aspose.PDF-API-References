---
title: "set_license"
second_title: "Aspose.PDF for Rust via C++"
description: "使用文件名设置许可证。"
type: docs
url: /zh/rust-cpp/core/set_license/
---

_使用文件名设置许可证。_

```rust
pub fn set_license(&self, filename: &str) -> Result<(), PdfError>
```

**Arguments**
  * **filename** - the path to the license-file

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // 打开具有文件名的 PDF 文档
    let pdf = Document::open("sample.pdf")?;

    // 使用文件名设置许可证
    pdf.set_license("Aspose.PDF.RustViaCPP.lic")?;

    // 现在您可以使用已授权的 PDF 文档
    // ...

    Ok(())
}

```