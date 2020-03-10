# LaTeX template for an Unibe parcel label

This repository is based on the [PSI letter and label template](https://gitlab.psi.ch/abis_m/LaTeX-letter-and-maillabel/), which I whipped up during my Postdoc at PSI.
It's useful if you just want to slap a parcel label onto something you want to send to someone.

If you want to write an official looking [University of Bern](https://unibe.ch) *letter* with LaTeX, there's a quite good `ubletter.cls` LaTeX template.
You can download it (internally from Unibe or via VPN) from the [Corporate Design](https://intern.unibe.ch/dienstleistungen/corporate_design_und_vorlagen/korrespondenz/index_ger.html) page.

The official Unibe logo is copied from [here](http://intern.unibe.ch/dienstleistungen/kommunikation_und_marketing/print/vorlagen_zum_download/logo_schriften_amp_farben/index_ger.html).

## Send a parcel
* Edit your details in `unibelabel.lco`
* Write an address label based on `unibe-label-template.tex`, save to `recipient.tex`
* compile `latexmk -pdf recipient.tex`
* Print the resulting PDF, affix it to the parcel and put everything wherever your physical outbox is.
