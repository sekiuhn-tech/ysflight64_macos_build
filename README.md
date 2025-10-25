# ysflight64_macos_build
YSFLIGHT 2025 macOS (Apple Silicon) build with CMake fixes
This is a prebuilt binary of YSFLIGHT for macOS Sequoia (Apple Silicon / M3),
built from the latest source using CMake fixes.

✅ Platform: macOS Sequoia (M3)

✅ Compiler: AppleClang 17.0

✅ Python: Homebrew /opt/homebrew/bin/python3

## 🛠️ How to Install (macOS, Apple Silicon Only)

> ⚠️ **Apple Silicon (M1/M2/M3) Macs only.**  
> Intel Macs are **not supported**, as this build targets the `arm64` architecture only.

1. **Download**
   - Go to the [Releases](https://github.com/sekiuhn-tech/ysflight64_macos_build/releases) page.
   - Download the latest `.zip` file.

2. **Extract**
   - Create any folder you like, for example:
     ```
     ~/Ysflight_CE
     ```
   - Unzip the downloaded file inside that folder.

3. **Launch**
   - Double-click the app to run it.  
   - If macOS shows a security warning saying  
     *“The developer cannot be verified”*, do the following:
     1. Right-click the app → choose **“Open”**
     2. Click **“Open”** again when prompted (only once).

   - Or remove the quarantine flag manually:
     ```bash
     xattr -dr com.apple.quarantine YSFlight64.app
     ```

4. **Done!**
   - The app should now launch normally.  
   - Tested on macOS Sequoia (M3 MacBook Air); it should also run on Ventura and Sonoma.

---

### ⚙️ Notes
- **Apple Silicon only (arm64 build).**  
- No external libraries (SDL2/Homebrew) required.  
- Uses built-in macOS frameworks: OpenGL, Cocoa, CoreFoundation, IOKit.  
- macOS may show a warning because the app is unsigned — this is normal.
