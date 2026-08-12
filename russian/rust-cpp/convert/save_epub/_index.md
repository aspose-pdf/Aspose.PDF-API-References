---
title: "save_epub"
second_title: "Aspose.PDF для Rust через C++"
description: "Преобразует и сохраняет ранее открытый PDF‑документ как EPUB‑документ."
type: docs
url: /ru/rust-cpp/convert/save_epub/
---

_Конвертирует и сохраняет ранее открытый PDF-document как EPUB-document._

```rust
pub fn save_epub(&self, filename: &str) -> Result<(), PdfError>
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

    // Конвертировать и сохранить ранее открытый PDF-document как Epub-document
    pdf.save_epub("sample.epub")?;

    Ok(())
}

```