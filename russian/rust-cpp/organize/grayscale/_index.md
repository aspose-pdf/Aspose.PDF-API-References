---
title: "grayscale"
second_title: "Aspose.PDF для Rust через C++"
description: "Преобразует PDF-документ в черно-белый."
type: docs
url: /ru/rust-cpp/organize/grayscale/
---

_Преобразует PDF-документ в черно-белый._

```rust
pub fn grayscale(&self) -> Result<(), PdfError>
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

    // Преобразовать PDF-документ в черно-белый
    pdf.grayscale()?;

    // Сохранить ранее открытый PDF-документ с новым именем файла
    pdf.save_as("sample_grayscale.pdf")?;

    Ok(())
}

```