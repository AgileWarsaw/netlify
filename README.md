# ABELight
Strona www konferencji ABE Light

# Jak wprowadzić zmiany?

## Mechanika:

   1. Sklonuj to repo.
   2. Strona abelight jest automatycznie generowana z kodu na branchu `abelight`
   3. Decyzja potrzebna: czy chcesz zmiany od razu wrzucić "na produkcję" czy raczej pull-request
   4. Ściągnij odpowiednią wersję Hugo (generator statycznych stron) stąd: https://github.com/gohugoio/hugo/releases
   5. Lokalny podgląd: `hugo server --watch`
   6. Popchnij zmiany na github.

## Treść:

Większość treści znajduje się w pliku konfiguracyjnym `config.yml`

Inne miejsca:

  * Treść sekcji "About the conference" jest w pliku `ABELight/layouts/partials/about.html`

Na podstawie:
https://github.com/jweslley/hugo-conference
