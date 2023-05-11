# snap package reference

A list of the snap packages that Wasta-Linux users might find useful.

Depending on your system, you may be able to find most of these in your built-in software manager app. If not, the terminal install commands are given below.

## Audacity

[Audacity](https://www.audacityteam.org/) is an easy-to-use, multi-track audio editor and recorder.
```bash
snap install audacity
```
https://github.com/diddlesnaps/audacity

## laMETA

[Lameta](https://www.lameta.org) is a metadata tool to help with organising collections of files.

It provides the metadata functionality of [SayMore](https://software.sil.org/saymore/).
```bash
snap install lameta-unofficial --beta
```
https://github.com/wasta-linux/lameta-snap

## Logos9

The [Logos](https://www.logos.com/) Bible Study app contains a powerful Bible study and sermon prep platform that allows you to study Scripture and consult commentaries, devotionals, Bible dictionaries, and more—all from your computer, tablet, or phone.

This snap package installs WINE to run Logos9. It will also download the Windows installer when first run. All this will require nearly 1.5 GB of downloads intially. Once running, the Logos *resources* that will be downloaded can easily surpass 15 GB.
```bash
snap install logos9 --devmode --beta
```
https://github.com/wasta-linux/logos9-snap/

## Map Creator

Create language-specific maps, charts, diagrams, and timelines.

This snap package installs WINE to run [Map Creator](http://fmosoft.com/map-creator). It will also download the Windows installer when first run. All this will require significant downloads (nearly 1.5 GB).
```bash
snap install map-creator-unofficial
```
https://github.com/wasta-linux/map-creator-snap

## Paratext Lite

Paratext Lite allows users of Paratext 8 and 9 to read and edit their project data on an Android tablet, phone, or Linux or MacOS computer. This is useful for comprehension checking and for simple editing comparable to what can be done in Paratext's Basic view.

```bash
snap install paratextlite
```
https://snapcraft.io/paratextlite