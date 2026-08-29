# PrivacyHub

PrivacyHub — Desktop application for creating, editing, versioning and exporting privacy / confidentiality rules. Inspired by GitHub (repository structure) and Telegram (clean minimal design).

## Features

- Create, edit, delete rules with versioning
- Attach screenshots/images to rules
- Export to .txt, .md and .pdf (with Cyrillic font support)
- Preview window before publishing
- Publish rules with a shareable base64 code
- Browse public PrivacyHub templates (EN/RU/KK)
- Settings: Dark/Light theme + Language (English, Русский, Қазақша)
- Auto-translate rule content via MyMemory API when switching languages
- Downloads history with Windows Explorer integration

## Requirements

- Windows 10/11
- Python 3.10+
- `ttkbootstrap`, `Pillow`, `fpdf2`

## Install dependencies

```bash
pip install ttkbootstrap Pillow fpdf2
```

## Run

```bash
python main.py
```

## Build EXE

```bash
pip install pyinstaller
python -m PyInstaller --onefile --windowed --name PrivacyHub --collect-all ttkbootstrap main.py
```

## License

MIT
