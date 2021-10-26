# fonts

You will need Go 1.16 or newer.

## Usage

```go
import "gioui.org/font/opentype"
import "gioui.org/widget/material"
import "gioui.org/text"
import "github.com/caiguanhao/fonts/NotoSansRegular"
face, err := opentype.Parse(NotoSansRegular.TTF)
material.NewTheme([]text.FontFace{
	text.FontFace{Font: text.Font{Typeface: "Go"}, Face: face},
})
```

## Noto Sans

From <https://fonts.google.com/noto/specimen/Noto+Sans>.
