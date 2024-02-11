
An RPG-II Star Trek game "Ported to the System/34" from presumably the System/32

Source from https://web.archive.org/web/20190421201356/https://freeas400software.com/downloads/strek.txt

TREKLOAD is a s/36 procedure that unwraps itself into STREK RPG-II source, STREKFM
display format member, and STREK procedure to launch the app. It's not needed, the
source files are separated here for convenience, but the loader proc is left here
for reference. This sort of procedure was a common way to transport multiple program
files in a single program.

Files can be loaded on a S/34 or S/36 as:
STREK   S
STREKFM S
STREK   P

Files can be uploaded to an AS/400 with S/36 Environment as:
QS36SRC.FILE/STREK.MBR
QS36SRC.FILE/STREKFM.MBR
QS36PROC.FILE/STREK.MBR

See the general build instructions in the top-level directory 
for information on building this application.


