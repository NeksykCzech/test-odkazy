# Testovací stránka: únik z vestavěného prohlížeče

Pomocná stránka projektu GeekBoy „chytré affiliate odkazy“. Ukáže, jestli se odkaz otevřel
uvnitř aplikace (Instagram, Threads, TikTok, YouTube), nebo v běžném prohlížeči, a nabídne
tlačítka na všechny známé cesty ven. Nic nesbírá ani neposílá; výsledek se kopíruje ručně.

- Stránka: https://neksykczech.github.io/test-odkazy/
- Automatický pokus při načtení: https://neksykczech.github.io/test-odkazy/auto.html

Zdroj je ve složce `docs/test-stranka` soukromého repozitáře `NeksykCzech/instagram-odkazy`.
Nová verze se vydá z hlavního repozitáře jedním příkazem:

    git subtree push --prefix=docs/test-stranka https://github.com/NeksykCzech/test-odkazy.git main
