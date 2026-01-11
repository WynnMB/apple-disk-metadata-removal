## This batch script removes garbage metadata files that are created when a **FAT32** or **exFAT** external drive is connected to an **iOS / iPadOS** or **macOS** device.

```batchfile
D:
del /s /q /f /a ._*
del /s /q /f /a .Spotlight-V100
rmdir /s /q "D:\.Spotlight-V100"
del /s /q /f /a .Trashes
rmdir /s /q "D:\.Trashes"
E:
del /s /q /f /a ._*
del /s /q /f /a .Spotlight-V100
rmdir /s /q "E:\.Spotlight-V100"
del /s /q /f /a .Trashes
rmdir /s /q "E:\.Trashes"
F:
del /s /q /f /a ._*
del /s /q /f /a .Spotlight-V100
rmdir /s /q "F:\.Spotlight-V100"
del /s /q /f /a .Trashes
rmdir /s /q "F:\.Trashes"
Q:
del /s /q /f /a ._*
del /s /q /f /a .Spotlight-V100
rmdir /s /q "Q:\.Spotlight-V100"
del /s /q /f /a .Trashes
rmdir /s /q "Q:\.Trashes"
pause
