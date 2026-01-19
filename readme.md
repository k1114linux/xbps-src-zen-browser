# Zen Browser XBPS Package
This repository provides a `template` file to help you easily install `zen-browser` on your `Void Linux`.

## Installation
1. Clone the repository to your computer using:
   ```bash
   git clone https://github.com/k1114linux/xbps-src-zen-browser.git zen-browser
   ```
2. Copy the `zen-browser` directory into the `srcpkgs/` directory of your `void-packages` repository:
   ```bash
   cp -rf zen-browser /path/to/void-packages/srcpkgs/
   ```
3. Build the package from within the `void-packages` repository:
   ```bash
   ./xbps-src pkg -f zen-browser
   ```
4. Install the package using `xbps-install`, pointing to the `hostdir/binpkgs` repository:
   ```bash
   sudo xbps-install --repository=hostdir/binpkgs zen-browser
   ```
5. After installation, you can launch the `zen` browser directly from your terminal using:
   ```bash
   zen
   ```
