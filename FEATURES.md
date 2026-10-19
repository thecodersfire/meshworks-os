# Built-in features for meshworks-os

Purpose: 3D modeling

1. **prepare a creative project** — run meshworks-os-workspace. It creates ~/Documents/meshworks-os-workspace/ with Briefs, Working Files, Exports folders.
2. **plan a production session** — run meshworks-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/meshworks-os-session-plans/.
3. **check project and export readiness** — run meshworks-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/meshworks-os-workspace features/meshworks-os-plan features/meshworks-os-check "$HOME/.local/bin/"

## Preinstalled purpose software

The installer adds these three Flathub applications for 3D modeling:

1. **GIMP** — org.gimp.GIMP
2. **Inkscape** — org.inkscape.Inkscape
3. **Krita** — org.kde.krita

They are installed from Flathub during setup. The repository contains application IDs and documentation, not third-party binaries; each publisher’s terms and licenses apply.
