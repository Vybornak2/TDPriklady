# Vypracovane priklady z předmětu Termodynamika na FS CVUT Praha

Datum: 18.6.2024
Vydal: Jan Výborný
email: <jan.vyborny2@gmail.com>

## Obsah

1. příklady ze strojar.com - rankinovy oběhy
2. příklady ze sbírky

K řešení problémů je užita knihovna **pyfluid** která je lightweight wrapperem pro knihovnu CoolProp.

Doporučuji spíše prozkoumat příklady R. Cyklů, které jsem kontroloval a mají dobrou dokumentaci.

Většina příkladů obsahuje zapsané poznámky pro řešení příkladů.

## Entrypoint

Příklady jsou zapsané v jupyter-notebook formatu - *.ipynb
Pro otevření je potřeba spustit v terminálu příkaz `jupyter-notebook`
Tyto soubory je dále možné otevřít v různých IDE jako je Pycharm, VS Code ...

## Instalace - windows (terminál)

### Doporučený způsob (pomocí uv)

Pokud není nainstalován nástroj `uv`, nainstalujte ho pomocí:
`py -m pip install uv` nebo z oficiálních stránek `https://docs.astral.sh/uv/`

1. Naklonování repozitáře: `git clone https://github.com/Vybornak2/TDPriklady.git`
2. Vytvoření virtuálního prostředí: `uv venv`
3. Synchronizace knihoven: `uv sync`
4. Aktivace virtuálního prostředí: `./venv/scripts/activate` (nebo dle instrukcí uv po příkazu `uv venv`)
5. V případě IDE jako VS Code je potřeba při spouštění Jupyter Notebooků vybrat správné prostředí (při otevření v pravém horním rohu `select Kernel`)

### Alternativní způsob (pomocí pip)

1. Naklonování repozitáře: `git clone https://github.com/Vybornak2/TDPriklady.git`
2. Instalace závislostí: `py -m pip install -r requirements.txt`
3. V případě IDE jako VS Code je potřeba při spouštění Jupyter Notebooků vybrat správné prostředí

## Dodatečné poznámky

S obsahem nakládat opatrně. Toto byla moje příprava a tedy se může najít sem tam nějaká chyba.
