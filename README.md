# rlaszlo.github.io

Szándékosan üres repó. Egyetlen feladata van: a GitHub Pages ebből a repóból
szolgálja ki a `rlaszlo.github.io` → `rlaszlo.dev` szerver szintű, 301-es,
útvonalmegtartó átirányítást. Ezt a `CNAME` fájl váltja ki: ha egy user-site
repó Pages-ének custom domainje be van állítva, a GitHub a `.github.io` címre
érkező kéréseket erre a domainre irányítja.

Az oldal tényleges tartalma és forráskódja a privát `rlaszlo.dev` repóban
van, és a Cloudflare Workersre deployol. Ide ne kerüljön tartalom.

Azért publikus ez a repó, mert privát repóból a GitHub Pages csak fizetős
csomaggal működik — így viszont az átirányítás ingyenes, miközben a tartalmat
hordozó repó privát marad.
