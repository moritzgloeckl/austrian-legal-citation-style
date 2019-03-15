![](https://img.shields.io/badge/Work-In%20Progress-informational.svg?style=for-the-badge)

# Work In Progress - Austrian Legal Citation Style

This is an update to the Austrian Legal Citation Style (Abkürzungs- und Zitierregeln nach Friedl/Loebenstein). The original has been created by Andreas Geyrecker from LexisNexis, but it was missing some important styling features such as subsequent citations ("Folgezitate") or correct EU law citation styles.

# Usage
## Citation type Book ("Selbständige Werke")
### Format
First citation:

*Friedl/Loebenstein*, AZR Abkürzungs- und Zitierregeln der österreichischen Rechtssprache und europarechtlicher Rechtsquellen<sup>7</sup> (2012).

Subsequent citations:

*Friedl/Loebenstein*, Abkürzungs- und Zitierregeln.

### Possible values
The Book uses the following data:
* Author(s)
* Title
* Short title (for subsequent citation, usually first noun of title)
* Volume (use Roman numerals)
* Edition (use Arabic numerals)
* Year
* Optional: Cited Pages

## Citation type Chapter ("Sammelwerk")
### Format
First citation:

*Lehner*, Von der bürgerlich-patriarchalen zur partnerschaftlichen Ehe, in: *Floßmann/Lehner (Hrsg)*, Frau – Recht – Gesellschaft<sup>2</sup> (1986) 11 (13).

Subsequent citations:

*Lehner*, in: *Floßmann/Lehner (Hrsg)*, 13.

### Possible Values
This is the information you should fill in for Chapters:
* Author(s)
* Title of the Chapter
* Publisher ("Herausgeber")
* Title of the Book
* Edition
* Year 
* Page on where the Chapter begins inside the Book
* Cited Page(s)

## Citation Type Legal Case ("Gerichtsentscheidung")
### Format

Austrian Legal Cases:
* OGH 3 Ob 32/04h EvBl 2004/190 or
* VwGH 97/03/0267 ZVR 1999/112 

European Legal Cases:
* EuGH 9.11.2010, C-296/10, *Purrucker/Vallés Perez* EF-Z 2011/100
* EuGH 12.3.2002, C-168/00, *Leitner/Tui*

### Possible Values
This is the information you should fill in for Austrian Legal Cases:
* Title

This is the information you should fill in for European Legal Cases:
* Title - Purrucker/Vallés Perez
* Authority - EuGH
* Issued - 9.11.2010
* Number - C-296/10
* Source - EF-Z 2011/100

## Citation Type Legislation ("Rechtsvorschriften")
### Format

Austrian Legislation:

* Gewerbeordnung (GewO) 1994 BGBl 1994/194
* DSG 2000 BGBl I 1999/165

European Legislation:

RL 2003/9/EG des Rates vom 27.1.2003 zur Festlegung von Mindestnormen für die Aufnahme von Asylwerbern in den Mitgliedstaaten, ABl L 2003/31, 18

Subsequent Citation:

AufnahmeRL 2003/9 ABl L 2003/31, 18

### Possible Values
This is the information you should fill in for Austrian Legislation:
* Title - Gewerbeordnung (GewO) 1994
* Source - BGBl 1994/194
* First Page

This is the information you should fill in for European Legislation:
* Title - L 2003/9/EG des Rates vom 27.1.2003 zur Festlegung von Mindestnormen für die Aufnahme von Asylwerbern in den Mitgliedstaaten
* Short-Title - 
* Source - ABl L 2003/31
* First Page - 18
* Jurisdiction - Any value ("EU"), so that it can be distinguished between Austrian Legislation
