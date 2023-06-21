# snap package reference

A list of the snap packages that Wasta-Linux users might find useful.

Depending on your system, you may be able to find most of these in your built-in software manager app. If not, the terminal install commands are given below.

## Audacity

[Audacity](https://www.audacityteam.org/) is an easy-to-use, multi-track audio editor and recorder.
```bash
snap install audacity
```
https://github.com/diddlesnaps/audacity

## SayMore (via WINE)

Recording speakers of the world’s languages is fun and rewarding, but keeping all the resulting
files and meta data organized? Converting files to archive formats? Transcription? Painful.

That’s why we built SayMore – to make common Language Documentation tasks fun and keep you productive.
```bash
snap install saymore-unofficial --devmode
```
https://github.com/wasta-linux/saymore-snap

## laMETA

[Lameta](https://www.lameta.org) is a metadata tool to help with organising collections of files.

It provides the metadata functionality of [SayMore](https://software.sil.org/saymore/).
```bash
snap install lameta-unofficial --beta
```
https://github.com/wasta-linux/lameta-snap

## Logos 10 (via WINE)

The [Logos](https://www.logos.com/) Bible Study app contains a powerful Bible study and sermon prep platform that allows you to study Scripture and consult commentaries, devotionals, Bible dictionaries, and more—all from your computer, tablet, or phone.

This snap package installs WINE to run Logos10. It will also download the Windows installer when first run. All this will require nearly 1.5 GB of downloads intially. Once running, the Logos *resources* that will be downloaded can easily surpass 15 GB.
```bash
snap install logos10-unofficial --beta --devmode
```
https://github.com/wasta-linux/logos10-unofficial-snap/

## Logos9 (via WINE)

The [Logos](https://www.logos.com/) Bible Study app contains a powerful Bible study and sermon prep platform that allows you to study Scripture and consult commentaries, devotionals, Bible dictionaries, and more—all from your computer, tablet, or phone.

This snap package installs WINE to run Logos9. It will also download the Windows installer when first run. All this will require nearly 1.5 GB of downloads intially. Once running, the Logos *resources* that will be downloaded can easily surpass 15 GB.
```bash
snap install logos9 --devmode --beta
```
https://github.com/wasta-linux/logos9-snap/

## Paratext Lite

Paratext Lite allows users of Paratext 8 and 9 to read and edit their project data on an Android tablet, phone, or Linux or MacOS computer. This is useful for comprehension checking and for simple editing comparable to what can be done in Paratext's Basic view.

```bash
snap install paratextlite
```
https://snapcraft.io/paratextlite

## Map Creator

Create language-specific maps, charts, diagrams, and timelines.

This snap package installs WINE to run [Map Creator](http://fmosoft.com/map-creator). It will also download the Windows installer when first run. All this will require significant downloads (nearly 1.5 GB).
```bash
snap install map-creator-unofficial
```
https://github.com/wasta-linux/map-creator-snap

## Apps under consideration

### Cog (via WINE; .NET 4.8)

Cog is a tool for comparing languages using lexicostatistics and comparative linguistics techniques. It can be used to automate much of the process of comparing word lists from different language varieties.
https://software.sil.org/cog/

### HearThis (via WINE; .NET 4.8)

Bible recording made easy! HearThis provides a do-it-yourself alternative for communities wanting to get translated scripture text into their own language.
https://github.com/sillsdev/hearthis/

### Keyman Developer

[Keyman Developer 16](https://keyman.com/developer/features.php) is the most powerful tool for creating keyboard layouts for any popular platform for any language around the world. Build keyboards layouts for desktop, web, tablet and phone. Optimise your keyboards for each platform, including touch-and-hold keys and alternative layers.
https://github.com/keymanapp/keyman

### OneStory Editor (via WINE; .NET 4.8)

OneStory Editor is documentation software for Oral Bible storying.
https://github.com/bobeaton/OneStoryEditor

### PrimerPro (via WINE; .NET 3.5sp1?)

Assists literacy workers by making it simpler to develop primers. It does tedious work which native authors and literacy specialists traditionally had to do themselves.
https://github.com/sillsdev/PrimerPro
