Poznámky k přednášce boolovské funkce a jejich aplikace (MFF UK, 2010/11)
=========================================================================

Download
--------

Stažení [bf.pdf](/tom-kuca/bool-fce/raw/master/all/bf.pdf)

Opravy
------

Opravy můžete hlásit následujícími způsoby:

* patche
* založit téma v Issues
* mailem [tomas.kuca@matfyz.cz](mailto:tomas.kuca@matfyz.cz)

Budu je obratem zařazovat. Pokud nemáte verzi staženou z github, doporučuju
aktualizovat. Chyb se vyskytlo více než jsme čekali, zde je jich hodně
opravených.

Kompilace
---------

Zápisky se zkompilují příkazem

    cd all && make

případně lze vytvořit konkrétní formát:

    cd all && make [pdf|ps|dvi]

Spuštěním `make` v adresáři přednášky se zkompiluje pouze daná přednáška. `make
clean` v kořenovém adresáři odstraní cokoliv kromě zdrojových souborů.
