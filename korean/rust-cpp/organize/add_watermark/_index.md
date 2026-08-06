---
title: "add_watermark"
second_title: "C++를 통해 Rust용 Aspose.PDF"
description: "PDF-document에 워터마크를 추가합니다."
type: docs
url: /ko/rust-cpp/organize/add_watermark/
---

_PDF-document에 워터마크를 추가합니다._

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
    // 파일 이름으로 PDF 문서를 엽니다
    let pdf = Document::open("sample.pdf")?;

    // PDF-document에 워터마크를 추가합니다
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

    // 이전에 열었던 PDF-document을 새 파일 이름으로 저장합니다
    pdf.save_as("sample_add_watermark.pdf")?;

    Ok(())
}

```