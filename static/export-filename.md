# Different export filename

This asset is called `export-filename.md` in the .tar.gz but `different-filename.md` when seen in Studio. This will **not** survive a round-trip; upon export, it will have the name `different-filename.md` everywhere. The static asset system can "remember" when the export's file is in a subfolder, and restore the subfolder on export, but does not treat the actual filename the same way.
