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

## Instalace - windows

1. git clone <https://github.com/Vybornak2/TDPriklady.git>
2. otevřít terminál v naklonované složce a spustit příkazy

   ```
   uv venv
   uv sync
   ```

   pozn: (v případě, že není nainstalován nástroj `uv` je možné ho nainstalovat pomocí:
   `py -m pip install uv` nebo z oficiálních stránek `https://docs.astral.sh/uv/`)

3. aktivace virtualního prostředí pomocí (dle instrukcí uv po příkazu `uv venv`)
4. v případě IDE jako VS Code je potřeba při spouštění Jupyter Notebooků vybrat správné prostředí (při otevření v pravém horním rohu `select Kernel`

## Dodatečné poznámky

S obsahem nakládat opatrně. Toto byla moje příprava a tedy se může najít sem tam nějaká chyba.
