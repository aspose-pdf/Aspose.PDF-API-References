---
title: "set_background"
second_title: "Aspose.PDF для Rust через C++"
description: "Устанавливает цвет фона PDF-документа с использованием значений RGB."
type: docs
url: /ru/rust-cpp/organize/set_background/
---

_Устанавливает цвет фона PDF-документа с использованием значений RGB._

```rust
pub fn set_background(&self, r: i32, g: i32, b: i32) -> Result<(), PdfError>
```

**Arguments**
  * **r** - red component (0-255)
  * **g** - green component (0-255)
  * **b** - blue component (0-255)

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Откройте PDF‑документ с именем файла
    let pdf = Document::open("sample.pdf")?;

    // Установить цвет фона PDF-документа с использованием значений RGB
    pdf.set_background(200, 100, 101)?;

    // Сохранить ранее открытый PDF-документ с новым именем файла
    pdf.save_as("sample_set_background.pdf")?;

    Ok(())
}

```