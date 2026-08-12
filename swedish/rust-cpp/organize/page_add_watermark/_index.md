---
title: "page_add_watermark"
second_title: "Aspose.PDF för Rust via C++"
description: "Lägger till vattenstämpel på sidan."
type: docs
url: /sv/rust-cpp/organize/page_add_watermark/
---

_Lägger till vattenstämpel på sidan._

```rust
pub fn page_add_watermark(
    &self,
    num: i32,
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
  * **num** - the page number (1-based)
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
    // Öppna ett PDF-dokument med filnamn
    let pdf = Document::open("sample.pdf")?;

    // Lägg till vattenstämpel på sidan
    pdf.page_add_watermark(
        1,
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

    // Spara det tidigare öppnade PDF-document med nytt filnamn
    pdf.save_as("sample_page1_add_watermark.pdf")?;

    Ok(())
}

```