---
title: "add_watermark"
second_title: "Aspose.PDF для Rust через C++"
description: "Добавляет водяной знак в PDF-документ."
type: docs
url: /ru/rust-cpp/organize/add_watermark/
---

_Добавляет водяной знак в PDF-документ._

```rust
pub fn add_watermark(
    &self,
    text: &str,
    font_name: &str,
    font_size: f64,
    foreground_color: &str,
    x_position: i32,
    y_position: i32,
    rotation: i32,
    is_background: bool,
    opacity: f64,
) -> Result<(), PdfError>
```

**Arguments**
  * **text** - the watermark text
  * **font_name** - the font name
  * **font_size** - the font size
  * **foreground_color** - the text color (hexadecimal format "#RRGGBB", where RR-red, GG-green and BB-blue hexadecimal integers)
  * **x_position** - the 'x' watermark position
  * **y_position** - the 'y' watermark position
  * **rotation** - the watermark rotation (0-360)
  * **is_background** - the background
  * **opacity** - the opacity (decimal)

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Откройте PDF‑документ с именем файла
    let pdf = Document::open("sample.pdf")?;

    // Добавить водяной знак в PDF-документ
    pdf.add_watermark(
        "WATERMARK",
        "Arial",
        16.0,
        "#010101",
        100,
        100,
        45,
        true,
        0.5,
    )?;

    // Сохранить ранее открытый PDF-документ с новым именем файла
    pdf.save_as("sample_add_watermark.pdf")?;

    Ok(())
}

```