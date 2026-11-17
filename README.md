# TDK_2026
Pajzsmirigy szövettani digitális képek elemzése modern mélytanuló technikákkal
A dolgozatommal részt vettem a 2026/27/1 félévben megrendezett Tudományos Diákköri Konferencián, a Debreceni Egyetemen.

Absztrakt: 
A TCGA a rákkutatás történetének egyik meghatározó kutatási projektje. A dolgozatom során a TCGA-THCA adatbázisból származó, digitalizált szövettani felvételeket (Whole Slide Imaging – WSI) használtam fel. A gigapixeles felbontású metszetekből előfeldolgozás során kisebb képrészleteket (patch) képeztem. A kialakított adatbázisom megközelítőleg 360 ezer tanító képet tartalmaz, amelyet 500 beteg felvételeiből mintavételeztem. A modellezést egy háromlépcsős keretrendszerben valósítottam meg: kiinduló referenciaként (baseline) egy egyszerű, kilapított képi vektorokon (flattened features) alapuló osztályozót értékeltem ki, amelyet egy szövettani mintázatokra optimalizált, nulláról tanított egyedi konvolúciós neurális hálózat (CNN), majd egy ImageNet-en előtanított és a feladathoz finomhangolt ResNet-50 architektúra követett. A modellek teljesítményét standard metrikák (pontosság, szenzitivitás, specificitás, F1-pontszám, valamint ROC-AUC görbék) mentén, kiterjedt tévesztési mátrixok elemzésével hasonlítottam össze. A dolgozat eredményei rámutatnak a mély reprezentációk és az átviteli tanulás (transfer learning) hozzáadott értékére a szövettani diagnosztikában a hagyományos megközelítésekkel szemben.

A repository tartalmazza a dolgozatom alapját, magát a notebookot, amelyben dolgoztam. 
