---
title: "repair"
second_title: "Aspose.PDF для Rust через C++"
description: "Восстанавливает PDF-document."
type: docs
url: /ru/rust-cpp/organize/repair/
---

_Восстанавливает PDF-документ._

```rust
pub fn repair(&self) -> Result<(), PdfError>
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

    // Восстановить PDF-документ
    pdf.repair()?;

    // Сохранить ранее открытый PDF-документ с новым именем файла
    pdf.save_as("sample_repair.pdf")?;

    Ok(())
}

```