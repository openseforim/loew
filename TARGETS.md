# Other possible targets: German scholarship on rabbinic realia

Brainstorm, 31-Oct-2026. Works that could go through the same pipeline (scan → OCR → gold check →
English with script-preserving transliteration). "Checked" means I ran a web search on
31-Oct-2026; "not checked" means it is from my own knowledge and must be verified before work starts.

Public-domain status (rough rule): **EU** = author died 70+ years ago (died before 1956);
**US** = published before 1931. Most works below are in both. Where they differ, it says so.

## Priority: Lewysohn, *Die Zoologie des Talmuds* (now in progress: [lewysohn-zoologie](https://github.com/openseforim/lewysohn))

Ludwig Lewysohn, *Die Zoologie des Talmuds: eine umfassende Darstellung der rabbinischen
Zoologie*, Frankfurt a. M.: Baer, 1858 (426 pp.). The animal counterpart of Löw's Flora, and the
first systematic collection of the Talmudic and Midrashic material on animals.

- **Scan:** [archive.org: diezoologiedesta00lewyuoft](http://www.archive.org/details/diezoologiedesta00lewyuoft)
  (University of Toronto, Robarts Library; PDF, B/W PDF, and archive.org's own full-text file).
  The archive.org text is automatic OCR and must be checked before use, as with Löw.
- **Existing work:** Natan Slifkin wrote in a 2012 post,
  ["A Few Announcements"](https://www.rationalistjudaism.com/p/a-few-announcements), that he was
  studying the book for his doctoral dissertation and running the PDF through OCR, and he asked
  for help to set up a collaborative translation "with facing translation" (for example on
  Wikibooks). I found no sign that this translation was published. Worth contacting him before
  starting, both to avoid duplicate work and because his reading of the zoology would be the
  natural check on the translation.
- **Fit with this pipeline:** a single volume, German with Hebrew and Aramaic (and some Greek,
  Latin and Arabic), the same kind of abbreviated references. The same steps apply: IIIF or PDF
  page images → OCR with script runs → a few hand-checked pages → English with the v3 rules.
- **Status:** checked 31-Oct-2026 (scan, Slifkin post). Not started.

## Suggested: Bochart, *Hierozoicon* (much harder)

Suggested by a reader on 01-Nov-2026 as "very useful (but immensely more complex)". Samuel
Bochart, *Hierozoicon, sive bipertitum opus de animalibus Sacrae Scripturae*, London 1663: the
standard early-modern study of every animal in the Bible, and a main source for Lewysohn and Löw.
Public domain everywhere. Checked by a web search on 01-Nov-2026 (details below are from that check).

- **Editions:** London 1663 (folio, 2 parts, two numbered columns: Pars I 1094 cols, Pars II 888);
  Frankfurt 1675 (ed. Clodius, same column numbers); Leiden 1692 and 1712 (*Opera omnia*);
  **Leipzig 1793–96, ed. E. F. C. Rosenmüller**, 3 vols quarto, about 2,780 pp, with notes, indices
  and the old column numbers in the margin. Rosenmüller is the usual citation base and the best
  base text.
- **Scans:** Munich (MDZ/BSB) has all the later editions, with IIIF and a page-level hOCR layer
  that is already good for Latin and Greek: Rosenmüller
  [bsb10353453](https://www.digitale-sammlungen.de/en/view/bsb10353453),
  [bsb10353454](https://www.digitale-sammlungen.de/en/view/bsb10353454),
  [bsb10353455](https://www.digitale-sammlungen.de/en/view/bsb10353455)
  (manifest `https://api.digitale-sammlungen.de/iiif/presentation/v2/{id}/manifest`); Leiden 1692
  bsb11203288–89; Leiden 1712 bsb10409819–20; Frankfurt 1675 bsb11935761–62. Also HathiTrust and
  archive.org (Google, Wellcome copies). London 1663 only as an EEBO microfilm on archive.org (poor).
- **Existing work:** no modern translation found, full or partial, in any language, and no AI
  translation project. Studies: Zur Shalev, *Sacred Words and Worlds* (Brill 2012), ch. 4 (mostly
  on the *Geographia sacra*). The NOSCEMUS wiki (Innsbruck) may list a Transkribus text of the 1675
  edition (not verified: the page gave an error).
- **Why it is harder:** about 1 million words (a few times Lewysohn, the size of all four volumes
  of Löw); 17th-century Latin, not German; Greek, Hebrew/Aramaic, Syriac and much **Arabic in
  Arabic type** (al-Damīrī, al-Qazwīnī) on most pages; Bochart's own transliterations; a second
  layer of notes by Rosenmüller.
- **What helps:** the MDZ OCR can be a first draft, so the vision model corrects instead of reading
  from zero.
- **Pilot:** Book III ch. 33 on the shafan (it is a large mouse, "non esse cuniculum"), Rosenmüller
  vol. 2 pp. 409–428 (bsb10353454, canvases about 425–444; 20 pages, about 8,000 words). It has
  every hard feature (Hebrew word study, the LXX χοιρογρύλλιος, heavy Arabic) and ties in with the
  hyrax claim in the [Talmud zoology fact-check](https://ezrabrand.github.io/talmud-zoology-factcheck/).
  A second pilot could be Behemoth (vol. 3) for a narrative chapter.
- **Status:** state of the art checked 01-Nov-2026; not started. Not checked: Gallica, e-rara,
  Google Books, the Ethiopic type in some editions.

## Short list

| Work | Why | Scans | Existing OCR / translation | Status of check |
|---|---|---|---|---|
| Samuel Krauss, *Griechische und lateinische Lehnwörter im Talmud, Midrasch und Targum*, 2 vols., Berlin 1898–99, **with notes by Immanuel Löw** | Direct continuation of my Krauss transcription-rules translations; Löw's notes link it to this project | archive.org ([syri.ac bibliography entry](https://syri.ac/bibliography/594847923)), HathiTrust ([Online Books Page](https://onlinebooks.library.upenn.edu/webbin/who/Krauss%2c%20Samuel%2c%201866%2d1948)) | No translation found; reprints 1964 and 1987 (Olms) | Checked |
| Immanuel Löw, *Aramäische Pflanzennamen*, Leipzig 1881 | The predecessor of the Flora (cited as "Pf." in it); same author, same notation | Halle ULB, Public Domain Mark ([opendata.uni-halle.de](https://opendata.uni-halle.de/handle/1981185920/102678?mode=full), [MENADOC](https://menadoc.bibliothek.uni-halle.de/publicdomain/content/structure/591390)); Princeton Theological Seminary ([commons.ptsem.edu](https://commons.ptsem.edu/id/aramischepflanze00lowi), machine text with an estimated 67% error rate) | No translation found; the existing OCR is unusable | Checked |
| Samuel Krauss, *Talmudische Archäologie*, 3 vols., Leipzig 1910–12 | The standard handbook of rabbinic material culture (house, clothing, food, crafts, trade) | to check (HathiTrust / archive.org likely) | No English translation found. **Hebrew:** Krauss's own Hebrew version, *Ḳadmoniyot ha-Talmud* (קדמוניות התלמוד), Berlin/Vienna: Binyamin Harz, from 1923; it was never finished (2 vols.), and sources differ on the dates ([Swiss library record](https://swisscollections.k8s-001.unibas.ch/Record/991171977923505501), [ANU Museum](https://dbs.anumuseum.org.il/skn/en/c6/e206792/Personalities/Samuel_Krauss), [Wikipedia](https://en.wikipedia.org/wiki/Samuel_Krauss)) | Checked (translations); scans not checked |
## Further candidates

| Work | Why | Existing translation / notes | Status of check |
|---|---|---|---|
| Hermann Vogelstein, *Die Landwirtschaft in Palästina zur Zeit der Mišnah. 1: Der Getreidebau*, Berlin 1894 | Agriculture in the Mishnah; short | Scan at Halle ULB, Public Domain Mark ([opendata.uni-halle.de](https://opendata.uni-halle.de/handle/1981185920/100457?mode=full)); no translation found | Checked |
| Paul Rieger, *Versuch einer Technologie und Terminologie der Handwerke in der Mišnâh. 1: Spinnen, Färben, Weben, Walken*, 1894 | Crafts terminology; short | Scan at Halle ULB ([opendata.uni-halle.de](https://opendata.uni-halle.de/handle/1981185920/100011?mode=full)); no translation found | Checked |
| Gustaf Dalman, *Arbeit und Sitte in Palästina*, 7 vols., 1928–42 | Ethnography of Palestinian agriculture and crafts, used all through rabbinic realia | **English translation in progress** (Nadia Abdulhadi-Sukhtian et al., Dar al-Nasher; vols. 1–3, 2013–2024) ([bibleplaces.com](https://bibleplaces.com/?p=19275), [Wikipedia](https://en.wikipedia.org/wiki/Gustaf_Dalman)). Vols. after 1930 are still under US copyright. Low priority because of the translation | Checked |
| Julius Preuss, *Biblisch-talmudische Medizin*, Berlin 1911 | Medicine | **Translated** by Fred Rosner, New York 1978 ([Wellcome Collection](https://wellcomecollection.org/works/f3wn9emu)). Not a target | Checked |
| Felix Goldmann, *Der Ölbau in Palästina zur Zeit der Mišnah*, Preßburg 1907 | Cited on Flora II p. 289; olive culture | not checked | Not checked |
| Adolf Brüll, *Trachten der Juden im nachbiblischen Alterthume*, Frankfurt 1873 | Clothing | not checked | Not checked |
| Samuel Krauss, *Synagogale Altertümer*, Berlin/Vienna 1922 | Synagogue archaeology | not checked | Not checked |
| Levi Herzfeld, *Handelsgeschichte der Juden des Alterthums*, Braunschweig 1879 | Trade and commodities | not checked | Not checked |
| Joseph Bergel, *Die Naturwissenschaftlichen Kenntnisse der Talmudisten*, Leipzig 1880 | Natural science in the Talmud | not checked | Not checked |
| Jacob Levy, *Neuhebräisches und chaldäisches Wörterbuch über die Talmudim und Midraschim*, 1876–89 | Lexicon; complements the Jastrow/BDB work in Bekiut | not checked; very large | Not checked |
| Immanuel Löw, *Fauna und Mineralien der Juden*, ed. A. Scheiber, 1969 | Completes the Flora | Löw's text is public domain in the EU (he died 1944), but Scheiber's edition (1969) is not, in the US or the EU | Not checked |

## Hebrew works (added 21-Nov-2026)

Suggested in the review of the [Emden *Megillat Sefer* reader](https://openseforim.org/emden/);
same pipeline as that project (Hebrew scan → Kraken OCR → page check → English draft). All "not checked": from my own
knowledge, to verify before work starts.

| Work | Why | Editions and existing translation | Status of check |
|---|---|---|---|
| Ḥida (Ḥayyim Yosef David Azulai, 1724–1806), *Ma'agal Tov* | His travel diary as an emissary of Hebron (journeys of the 1750s and 1770s): Italy, Germany, Holland, France, England, North Africa. A first-person 18th-c. Hebrew text like *Megillat Sefer*, and some of the same communities | Livorno 1879 (partial); full edition by A. Freimann, Jerusalem (Mekize Nirdamim), 1921–34, which may still be in copyright in the EU. An English translation by B. Cymerman (1997) probably exists: check how complete and how good it is before starting | Not checked |
| Ḥida, *Shem ha-Gedolim* | His bio-bibliographical dictionary of rabbis (Ma'arekhet Gedolim) and of books (Ma'arekhet Sefarim). Kahana cites it in his notes to *Megillat Sefer*; a structured English version could link to the Emden and Hyman projects | Livorno 1774–96 (two parts); later editions with added notes (e.g. Vilna 1853). No English translation known to me | Not checked |
| Judah al-Ḥarizi, *Taḥkemoni* (תחכמוני), early 13th c. | The classic Hebrew maqamat: 50 chapters of rhymed prose and poems. The model for Immanuel of Rome's *Maḥberot* (see the [immanuel-mahberot](https://github.com/openseforim/immanuel) project), so the two would make a pair | **Scans (checked 21-Nov-2026 in the hebrew-print-inventory):** first edition Constantinople 1578 (HathiTrust uc1.b4616630 only); Amsterdam 1729 (HathiTrust mdp.39015014644572); P. de Lagarde's edition, Göttingen 1883 ([archive.org tahkemoni00hari](https://archive.org/details/tahkemoni00hari), 400 ppi, open IIIF; also HathiTrust uc1.b4612172); A. Kaminka's edition with commentary, Warsaw 1899 (HathiTrust hvd.hwmiag, mdp.39015093249079; [archive.org TachkemoniYehudaAlchariziWarsaw1899](https://archive.org/details/TachkemoniYehudaAlchariziWarsaw1899), 333 ppi); German translation of the first maqamat by S. I. Kaempf, Berlin 1845 ([archive.org dieerstenmakamen00juda](https://archive.org/details/dieerstenmakamen00juda), 400 ppi; also UB Frankfurt). Lagarde or Kaminka would be the base text. The critical edition by J. Yahalom and N. Katsumata (Ben-Zvi, 2010) is in copyright; an archive.org upload of it should not be used. **Translations (not checked):** English by V. E. Reichert (2 vols., Jerusalem 1965–73) and by D. S. Segal (*The Book of Taḥkemoni*, Littman, 2001), both in copyright; so the value is an open Hebrew text and an open translation, not a first translation. Check Ben-Yehuda and Sefaria for an existing Hebrew text before OCR | Scans checked; translations and existing Hebrew text not checked |
| Isaac Hirsch Weiss, *Dor Dor ve-Dorshav*, 5 vols., Vienna 1871–91 | The classic 19th-c. history of the Oral Law from the Bible to the early modern period. A companion to the Hyman *Toldot Tannaim ve-Amoraim* work | Public domain (Weiss d. 1905). No English translation known to me; check for a Sefaria or Wikisource text before running OCR | Not checked |

## Notes

- **Existing projects to check before starting any of these:** Sefaria (texts and dictionaries),
  the Frankfurt and Halle digital collections (scans only, no usable OCR so far), HathiTrust full
  text, Wikisource (de), and the Dicta/Bar-Ilan corpora.
- Frankfurt's scans of the Flora have **no OCR text layer** (checked 31-Oct-2026: no IIIF
  annotations, no METS full-text group, full-text URLs 404, the PDF has images only). Halle's
  Löw *Pflanzennamen* scan should be checked the same way.
- The cost estimate for one full work: about 500 pages per volume × about $0.10 per page for OCR
  and about $0.08 per page for translation with Claude Opus 5.5 through OpenRouter.
