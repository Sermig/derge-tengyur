# Digital Derge Tengyur

Working repository for the digital Derge Tengyur prepared by Esukhia and Barom Theksum Choling.

## Format

The texts contain the following structural markup at beginning of lines:

* **[1b]** is _[Page and folio markers]_
* **[1b.1]** is _[Page and folio markers.line number]_

We follow the page numbers indicated in the original, this means that sometimes the page numbers go back to 1a (ex: vol. 31 after p. 256). Pages numbers that appear twice in a row are indicated with an `x`, example in volume 102: `[355xa]`.

They also contain a few error suggestions noted as example. It is far from an exhausted list of the issues found in the original, the staff was actually discouraged to add these.

* **(X,Y)** is _(potential error, correction suggestion)_ , example: `མཁའ་ལ་(མི་,མེ་)ཏོག་དམར་པོ་`

* **[X]** signals obvious errors or highly suspicious spellings (ex: `མཎྜལ་ཐིག་[ལ་]ལྔ་པ་ལ།`), or un-transcribable characters
* **#** signals an unreadable graphical unit
* **{TX}** signals the beginning of the text with Tohoku catalog number **X**. We use the following conventions:
  * when a text is missing from the Tohoku catalog, we indicate it with the preceding number followed by **a**, ex: **T7**, **T7a**, **T8**, following the [rKTs](https://www.istb.univie.ac.at/kanjur/rktsneu/sub/index.php) convention.

The files are UTF8 with no BOM, using LF end of lines. The Unicode is in [NFD](http://unicode.org/reports/tr15/), and oM is rendered as `\u0F68\u0F7C\u0F7E` (`ཨོཾ`) and not `\u0F00` (`ༀ`).

The end of lines sometimes are preceded by a space character (when they end with a shad) so that the result of appending all the lines content is useabletext is correct.

TODO: format of notes insertion.

# Feedback

The files are on Github hoping they'll improve, don't hesitate to [report issues](https://github.com/Esukhia/derge-tengyur/issues) or even open a pull request!

# How to cite

Use the following statemnent:
    
     ཆོས་ཀྱི་འབྱུང་གནས། [1721–31], བཀའ་འགྱུར་སྡེ་དགེ་པར་མ།, Etexts from ACIP and BDRC OCR, combined and further proofread by Esukhia, 2015-2018, https://github.com/Esukhia/derge-tengyur

# License

This work is a mechanical reproduction of a Public Domain work, and as such is also in the Public Domain.
