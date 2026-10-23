# scoop-tuhi

A [Scoop](https://scoop.sh) bucket for [**tuhi**](https://github.com/vernonkay/tuhi) — a fast, cross-platform text & Markdown editor that opens multi-gigabyte files without flinching.

## Install

    scoop bucket add tuhi https://github.com/vernonkay/scoop-tuhi
    scoop install tuhi

Then run `tuhi` from any terminal, or launch it from the Start menu.

## Notes

tuhi uses the Microsoft Edge **WebView2** runtime, which is preinstalled on Windows 11 and current Windows 10. If the window comes up blank, install the "Evergreen WebView2 Runtime" from Microsoft.

## Updating

    scoop update tuhi

The manifest tracks tuhi's GitHub releases, so `scoop update` picks up new versions automatically.
