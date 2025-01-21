# playwright_visual_blok

Tento repozítář je připravený pro blog o využití Playwright pro vizuální testování:https://tredgate.cz/2025/01/21/jak-na-vizualni-testovani-v-playwright-v-5-krocich/

## Instalace

Nejdříve je potřeba nainstalovat [Node.js](https://nodejs.org/en/).

Poté si repozitář naklonujte.

Následně nainstalujte závislosti pomocí příkazu:

```bash
npm install
```

A následně si stáhněte prohlížeče pro Playwright pomocí příkazu:

```bash
npx playwright install
```

## Spuštění testů

Testy spustíte pomocí příkazu:

```bash
npx playwright test visual_tests.spec.ts
```

Snapshoty pro MacOS jsou již v repozitáři.
Pokud chcete snapshoty pro jiný operační systém, tak při prvním spuštění testů budou automaticky vytvořeny a testy se ukončí s chybou.
Druhý běh testů již proběhne v pořádku.
