# Odyssey of the Rings Desktop Build (Windows .exe)

## 1) Install dependencies
```bash
npm install
```

## 2) Run desktop app locally
```bash
npm start
```

## 3) Build Windows portable executable
```bash
npm run dist:win
```

Output goes to:
- `release/` (file name similar to `Odyssey of the Rings Playtest <version>.exe`)

## Notes
- Build must run on a machine with required build toolchain.
- If you build on Windows, you'll get a Windows `.exe` directly.
