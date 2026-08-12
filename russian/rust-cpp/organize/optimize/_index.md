---
title: "optimize"
second_title: "Aspose.PDF для Rust через C++"
description: "Оптимизирует содержимое PDF-document."
type: docs
url: /ru/rust-cpp/organize/optimize/
---

_Оптимизирует содержимое PDF-document._

```rust
pub fn optimize(&self) -> Result<(), PdfError>
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

    // Оптимизировать содержимое PDF-document
    pdf.optimize()?;

    // Сохранить ранее открытый PDF-документ с новым именем файла
    pdf.save_as("sample_optimize.pdf")?;

    Ok(())
}

```