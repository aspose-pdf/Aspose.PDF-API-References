---
title: "save_markdown"
second_title: "Aspose.PDF для Rust через C++"
description: "Конвертирует и сохраняет ранее открытый PDF‑документ как Markdown‑документ."
type: docs
url: /ru/rust-cpp/convert/save_markdown/
---

_Конвертирует и сохраняет ранее открытый PDF‑документ как Markdown‑документ._

```rust
pub fn save_markdown(&self, filename: &str) -> Result<(), PdfError>
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
    // Откройте PDF‑документ с именем файла
    let pdf = Document::open("sample.pdf")?;

    // Конвертировать и сохранить ранее открытый PDF‑документ как Markdown‑документ
    pdf.save_markdown("sample.md")?;

    Ok(())
}
```