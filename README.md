 # ملف وثائق المستخدمين (User Documentation)
user_documentation = """
# Apm# Language User Documentation

## Components

### Button
A button component used for user interaction.

Attributes:
- `type`: The type of button.
- `text`: The text displayed on the button.
- `background_color`: The background color of the button.
- `text_color`: The color of the text on the button.
- `width`: The width of the button.
- `height`: The height of the button.
- `state`: The state of the button (e.g., active, disabled).
- `font_style`: The style of the text font.
- `shape`: The shape of the button.

Example:
```apm#
.Component[
    "button" → type
    "Click me" → text
    "#FFFFFF" → background_color
    "#000000" → text_color
    "100px" → width
    "50px" → height
    "active" → state
    "bold" → font_style
    "rounded" → shape
]
