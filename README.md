# LaTeX template for an Unibe parcel label

This repository is based on the [PSI letter and label template](https://gitlab.psi.ch/abis_m/LaTeX-letter-and-maillabel/), which I whipped up during my PostDoc at PSI.

If you want to write an official Unibe letter with LaTeX, there's an offcial `ubletter.cls` LaTeX template.
You can download it (internally from Unibe or via VPN) from the [Kommunikation und Marketing](http://intern.unibe.ch/dienstleistungen/kommunikation_und_marketing/print/corporate_design/brief_set/index_ger.html) page.

The Unibe logo is copied from [here](http://intern.unibe.ch/dienstleistungen/kommunikation_und_marketing/print/corporate_design/logo_schriften_amp_farben/index_ger.html)

## Send a parcel
* Edit your details in `unibelabel.lco`
* Write an address label based on `unibe-label-template.tex`
* Compile the file with `latexmk -pdf unibe-label-template.tex`
* Print the resulting PDF, glue it to the parcel and put everything wherever your physical outbox is.
