# Symbols & Footprint Library for KiCAD

This is a collection of KiCAD symbols and footprints I either created
or modified for use in my projects.

You're free to use the files in the `symbols/` and `footprints/` directories
under the terms of the WTFPL as published by Sam Hocevar, or alternatively if
that license scares you or is otherwise incompatible with your use-case, under
the terms of the BSD 2-Clause license.

The files in the `logos/` directory contain footprint versions of my logos,
which I reserve all rights for. You may use them when crediting me by name,
ideally including a reference to the relevant web properties.

## Importing symbols

To use these symbols on your system, open the KiCAD symbol library editor.

Create a new library (if you do not have a personal one to use already) and select a location for it on your system.
You may choose to create a library local to your project, or a global one for use with all projects.

Find your library in the list, right-click it and select `Import symbol`.
Navigate to the symbol file you want to import and click `Open`.

The symbol can now be used via this library.

## Importing footprints

To import the provided footprints as a footprint library, select `Preferences` -> `Manage Footprint Libraries`.

Add the `footprints/` directory as either a global or project-specific entry.

The footprints will then be available for use.
