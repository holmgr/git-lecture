## I grova drag
- Introduktion, vem är du?
- Vad är versionshantering?
    - En sorts databas som sparar "snapshots" av ditt projekt när du vill.
    - Kan visa hur din senaste version skiljer sig från den föregående
- Varför bör man använda ett _VCS_ (version control system)
    - Sammarbete (flera utvecklare, ett projekt)
    - Lagra olika versioner av samma system
    - Återställa äldre versioner
    - Förstå vad som hände
    - Backup
- Centraliserat eller distribuerat? Git kontra SVN
    - Git följer innehåll tillskillnad från filer. SVN tappar historik vid flytt.
    - Branch:er är lättviktiga och merging är trivialt i jämförelse med SVN och CVS.
    - Framförallt: Det är distributerat, enkelt sagt så är alla repon en egen branch.
        - Gör det mycket enklare att arbetra paralellt och sammarbeta.
        - Gör det även möjligt att arbeta offline.
    - Git är mycket snabbare i alla viktiga kategorierer eftersom du slipper gå över nätet.
    - Korruptionssäkerhet.
    - Git använder en s.k staging area, möjliggör dig att göra delvisa commits osv.

- Historian om Git, vem använder det?
    - Av skaparen av Linux kerneln, Linus Torvalds som skrev det på två veckor,
    tyckte att alla andra versionshanteringssystem var värdelösa. År 2005.
    - Programmeringsspråket Go
    - Linux kernel
    - Git :)
    - Chromium (Open source biten av Chrome)

Nu blir det demostration:

- Basic workflow
    - Repositiory
    - Commit
    - Local & remote repositories
    - Push & pull
- Att ångra?
    - Checkout
    - Reset
- Mer avancerat
    - Branches och merge
- Mer om git?
    - Linus Torvalds Google talk (varför andra VCS är värdelösa)
    - [Lathund för git](http://rogerdudler.github.io/git-guide/)
    - [Interaktiv guide, Github](https://try.github.io/levels/1/challenges/1)
    - Finns grafiska editors som kan hjälpa, även om jag skulle rekommendera terminalen


called file tracking. try renaming the file, or moving it somewhere else manually [same content, new file (because of the new path/name)]: will SVN know that that's the same file and retain the previous countless revisions you've made to it? no, I guess not. –  Filip Dupanović May 18 '10 at 21:07
