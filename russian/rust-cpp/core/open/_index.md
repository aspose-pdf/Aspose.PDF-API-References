---
title: "open"
second_title: "Aspose.PDF для Rust через C++"
description: "Открывает PDF-документ с именем файла."
type: docs
url: /ru/rust-cpp/core/open/
---

_Открывает PDF-документ с именем файла._

```rust
pub fn open(filename: &str) -> Result<Self, PdfError>
```

**Arguments**
  * **filename** - path to the PDF-document to open

**Returns**
  * **Ok(Self)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Откройте PDF-document с именем "sample.pdf"
    let pdf = Document::open("sample.pdf")?;

    // Сохранить ранее открытый PDF-документ с новым именем файла
    pdf.save_as("sample_open.pdf")?;

    Ok(())
}

```