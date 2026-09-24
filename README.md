# TCPServer

VB6 Logon Server (`Logon Server.exe`) that listens on Winsock (port 1001) for `TCPClient` connections, accepts multiple clients, and returns drive-mapping payload (plus `Logon.mdb`). Pair with sibling `TCPClient`. Open `Logon Server.Vbp` in the VB6 IDE.

**Source last updated:** 2026-08-27 · **Language:** VB6 · **Target:** VB6 Win32 · **Output:** WinForms exe

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `Server` (`Logon Server.Vbp`) | VB6 | WinForms exe | Logon server: accept clients and send map data |

## How to open

Open the `.vbp` in Visual Basic 6.0 IDE:
- `Logon Server.Vbp`

## Requirements

- Visual Basic 6.0 IDE
- Registered OCX/DLL dependencies referenced by the `.vbp` (may need to be installed separately):
  - `Mswinsck.ocx`

## Attribution and provenance

Working copy from my Historical Dev folder `VB/TCPServer`.
Company names in `.vbp` files: Unknown Organization.

## License

MIT © 2026 VaderConsulting for Dave Robinson's code. See `LICENSE`.
