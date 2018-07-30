# LaTeX template for an Unibe parcel label

This repository is based on the [PSI letter and label template](https://gitlab.psi.ch/abis_m/LaTeX-letter-and-maillabel/), which I whipped up during my PostDoc at PSI.

If you want to write an official Unibe letter with LaTeX, there's an offcial `ubletter.cls`, but it seems to be impossible to get ahold of.
Just send me a message and I can provide the file to you.

## Send a parcel
* Edit your details in `unibelabel.lco`
* Write an address label based on `unibe-label-template.tex`, save to `recipient.tex`
* compile `latexmk -pdf recipient.tex`
* print the label, glue it to the parcel and put everything wherever your physical outbox is.
