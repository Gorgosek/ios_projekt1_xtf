# IOS Projekt 1
- **Assignment specification**: pdf file at `zadani/ios_xtf_zadani.pdf`
- **Final Grade**: 15.5/15 (.5 extra)

```
15:celkem bodu za projekt
#-- automaticke hodnoceni -----------------------------
0:ok: docasne soubory:
0.5:ok: vypis zaznamu
0.5:ok: implicitni vypis zaznamu
0.5:ok: vypis (crypto)men
0.5:ok: stav uctu
0.5:ok: profit uctu uzivatele
0.5:ok: profit uctu navyseny o 35% (export XTF_PROFIT=35)
0.5:ok: filtr -c nad seznamem transakci
0.5:ok: filtr -c bez existujicich zaznamu
0.5:ok: filtr -a nad stavem uctu
0.5:ok: filtr -b nad stavem uctu
0.5:ok: filtr -a a -b nad profitem uctu
0.5:ok: filtr -a, -b a -c nad profitem uctu navysenym o 42% (export XTF_PROFIT=42)
0:test14_no_params: xtf bez parametru (chybi zprava na stderr)
0:test15_some_params: xtf s neuplnymi parametry (neni stderr a chybovy kod)
0.5:ok: chybejici hodnota u filtru -a
0.5:ok: vicenasobna specifikace filtru -a
0.5:ok: nevalidni cas u filtru -b
0.5:ok: vypis napovedy
0.5:ok: vypis napovedy s nadbytecnym parametrem
0.5:ok: neexistujici log soubor
0.5:ok: vice textovych log souboru
0.5:ok: textovy, komprimovany a prazdny log soubor
0.5:ok: identicke log soubory
0.5:ok: log soubor s chybejicimi sloupci
0.5:ok: chybny format dat v log soubru
0.5:ok: prestupny rok
0.5:ok: symlink log souboru
0.5:ok: nepristupny log soubor
0.5:ok: prace s neobvyklymi nazvy souboru
0.5:ok: filtr -a a -b s prazdnym prunikem zaznamu
0.25:ok: dvojity filtr -c nad seznamem transakci
0.25:ok: trojity filtr -c nad stavem uctu
0.25:ok: obracene poradi parametru
0.25:ok: libovolne poradi parametru
0.5:ok: omezena pamet pro zpracovani 90MB souboru, prikaz spousten s ulimit -v 185750 a ulimit -H -v &>/dev/null
#------------------------------------------------------
15.5:celkove score (max pro hodnoceni 15)
15:celkem bodu za projekt
```
