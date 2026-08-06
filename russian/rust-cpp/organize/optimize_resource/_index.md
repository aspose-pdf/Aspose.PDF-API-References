---
title: "optimize_resource"
second_title: "Aspose.PDF для Rust через C++"
description: "Оптимизирует ресурсы PDF-document."
type: docs
url: /ru/rust-cpp/organize/optimize_resource/
---

_Оптимизирует ресурсы PDF-document._

```rust
pub fn optimize_resource(&self) -> Result<(), PdfError>
```

**Arguments**


**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Откройте PDF‑документ с именем файла
    let pdf = Document::open("sample.pdf")?;

    // Оптимизировать ресурсы PDF-document
    pdf.optimize_resource()?;

    // Сохранить ранее открытый PDF-документ с новым именем файла
    pdf.save_as("sample_optimize_resource.pdf")?;

    Ok(())
}

```