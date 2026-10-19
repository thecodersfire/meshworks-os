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

## Ten more purpose-specific preinstalled applications

The setup installs these ten Flathub apps selected for 3D modeling:

1. **LibreOffice** — create reports and spreadsheets (org.libreoffice.LibreOffice)
2. **Zotero** — manage research sources and citations (org.zotero.Zotero)
3. **GNOME Calendar** — schedule sessions, deadlines, and events (org.gnome.Calendar)
4. **GNOME Clocks** — time work sessions and events (org.gnome.clocks)
5. **GNOME Contacts** — organize partner and team contacts (org.gnome.Contacts)
6. **GNOME Papers** — read project and reference PDFs (org.gnome.Papers)
7. **Document Scanner** — digitize paper notes and forms (org.gnome.SimpleScan)
8. **Foliate** — read EPUB books (com.github.johnfactotum.Foliate)
9. **Calibre** — organize ebooks and convert documents (com.calibre_ebook.calibre)
10. **Anki** — create spaced-repetition study decks (net.ankiweb.Anki)

Flathub distributes the app packages. Check each publisher license and terms. This repository contains app IDs and documentation, not third-party binaries.

## Fifteen more purpose-specific preinstalled applications

These applications add tools suited to this setup focus. They are installed from Flathub by the setup scripts.

1. **QElectroTech** (org.qelectrotech.QElectroTech) — draw electrical schematics and wiring diagrams.
2. **LibreCAD** (org.librecad.librecad) — draft precise 2D technical drawings.
3. **DBeaver Community** (io.dbeaver.DBeaverCommunity) — browse, query, and manage SQL databases.
4. **Gitg** (org.gnome.gitg) — review Git history and branches graphically.
5. **GeoGebra Classic** (org.geogebra.GeoGebra) — explore geometry, algebra, graphing, and 3D math.
6. **Xournal++** (com.github.xournalpp.xournalpp) — annotate PDFs and take handwritten notes.
7. **JabRef** (org.jabref.jabref) — organize BibTeX references and research citations.
8. **Stellarium** (org.stellarium.Stellarium) — explore a planetarium sky for astronomy learning.
9. **Thunderbird** (org.mozilla.Thunderbird) — manage email and communication accounts.
10. **Evolution** (org.gnome.Evolution) — manage email, calendars, and contacts.
11. **RawTherapee** (com.rawtherapee.RawTherapee) — develop RAW photo files with tone and color controls.
12. **digiKam** (org.kde.digikam) — catalog, tag, and batch-process large photo collections.
13. **OpenSCAD** (org.openscad.OpenSCAD) — model parametric 3D parts in code.
14. **KiCad** (org.kicad.KiCad) — design circuits and PCBs.
15. **Arduino IDE** (cc.arduino.IDE2) — write and upload microcontroller sketches.

Emulator frontends do not include game ROMs or copyrighted game files; supply only files you are legally allowed to use.
