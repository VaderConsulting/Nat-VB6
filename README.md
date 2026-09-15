# Nat

DAGS / D. Robinson VB6 NAT (`NAT.dll`, Oct 2002) ActiveX XML helper over MSXML 3.0 and Scripting Runtime. Class `NAT.XML` Create/Append/Read/Load/Save DOM documents into Dictionary name/value pairs; harnesses `NAT_Test` and `Reader` exercise paths like `c:\XMLTest.XML`.

**Source last updated:** 2026-08-27 · **Language:** VB6 · **Target:** VB6 Win32 · **Output:** ActiveX DLL, WinForms exe

_Note: original OneDrive LastWriteTime values were wiped to 2026-08-27 by a zip transfer; date above uses best available evidence (headers/copyright where helpful)._

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `NAT` (`Components/Nat/Nat.vbp`) | VB6 | ActiveX DLL | MSXML Create/Append/Read/Load/Save helper (`NAT.dll`) |
| `NAT_Test` (`Components/Nat/Test/Nat_test.vbp`) | VB6 | WinForms exe | NAT.XML Create/Save/Read harness |
| `Reader` (`Reader/Reader.vbp`) | VB6 | WinForms exe | NAT.XML Load/Append/Read harness |

## How to open

Open the `.vbp` in Visual Basic 6.0 IDE:
- `Components/Nat/Nat.vbp`
- `Components/Nat/Test/Nat_test.vbp`
- `Reader/Reader.vbp`

## Requirements

- Visual Basic 6.0 IDE
- MSXML 3.0 (`msxml3.dll`) and Microsoft Scripting Runtime (`scrrun.dll`)

## Attribution and provenance

Working copy from Dave Robinson's OneDrive Historical Dev folder `VB/Old/Nat`.
Company names in project files: DAGS. Author headers: D Robinson (23 October 2002).

## License

MIT (c) 2026 VaderConsulting for Dave Robinson's code. See `LICENSE`.
