Ebben a lépésben történik a függőségi elemzés kimenetének kézi ellenőrzése és javítása. Ehhez a [WebAnno](https://webanno.github.io/webanno/) webalapú annotációs segédeszközt használjuk.

A CoNLL-U formátumú fájlok függőségi faként jelennek meg a felületen. Az egér segítségével megfordíthatók, áthelyezhetők vagy törölhetők az egyes függőségi élek, valamint a címkék is módosíthatók. Emellett a szóalakot, a tövet és a morfológiai címkét is lehetőségünk van módosítani. A tokenizálás módosítására nincs lehetőség. A részleteket lásd az [annotálási útmutatóban](../../utmutatok/emdep_checker_guide.pdf)! Az annotátorok által összegyűjtött kérdésekből készült [gyik](../../utmutatok/emdep_checker_fak.pdf) is segítséget nyújthat az kérdéses esetekben.

A lépés bemenete: [6_webanno_preproc/globv_10.conll](../6_webanno_preproc/globv_10.conll)