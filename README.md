# NX-Setup-Checker
A script to quickly check a CFW setup and parse the latest fatal report

Prints informations about your CFW setup.
Parses the latest report stored in `atmosphere/fatal_errors`.

This script uses [TegraScript v3](https://github.com/suchmememanyskill/TegraScript).

# Features

Currently prints sysMMC's firmware, emuMMC's firmware (if enabled), Atmosphère's version, latest HOS firmware supported (by Atmosphère), and Hekate's version (if used).
Prints useful informations from the latest AMS fatal report (error code, title id, name of module and sysmodule if known).
Titles and errors database from [SwitchBrew](https://switchbrew.org/wiki/Main_Page) and sysmodules database from [ndeadly](https://gist.github.com/ndeadly/a4b8c01bb453028cd0008f282098f696).

# How To Use

You will need the latest release of [TegraExplorer](https://github.com/suchmememanyskill/TegraExplorer/releases).

- Place the `SetupChecker.te` script from the [latest release](https://github.com/JeffVi/NX-Setup-Checker/releases/latest) on your sd.
- Insert your SD in your Switch and launch the TegraExplorer payload.
- Browse your SD and launch the `FatalParse.te` script.

Credits to [suchmememanyskill](https://github.com/suchmememanyskill) for the MMC version check.