# Keyboard Layout Translator

A lightweight desktop tool for converting text between different keyboard layouts.

This project is useful when text is typed using the wrong keyboard layout
and needs to be converted without retyping.

---

## Features

- Simple GUI built with Tkinter
- Customizable keyboard mapping
- Fast character-based translation
- Easily extendable to any language or layout

---

## Usage

1. Paste or type text into the input field
2. Click **Translate**
3. The converted text will appear in the output field

---

## Custom Keyboard Layout

You can define your own keyboard layout by editing the `KEYBOARD_MAP`
dictionary in the source code.

Example:

```python
KEYBOARD_MAP = {
    'a': 'α',
    'b': 'β',
    'c': 'γ',
}
