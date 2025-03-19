# PRK_2025

## Vlastnosti jazyka

### 1. Proměnné
- Názvy mohou obsahovat latinská písmena (`a-Z`), číslice (`0-9`) a řecká písmena.
- Musí začínat písmenem.
- Příklady: `altitude`, `velocity_α`, `μ`.

### 2. Čísla
- **Celá čísla**: Celá čísla (např. `42`, `-7`, `0`).
- **Desetinná čísla**: Desetinná čísla (např. `3.14`, `-0.5`).

### 3. Operátory
#### Binární operátory
- Aritmetické: `+`, `-`, `*`, `/`,`^`
- Porovnání: `==`, `!=`, `<`, `>`, `<=`, `>=`
- Přiřazení: `=`

#### Unární operátory
- Logická negace: `!`
- Aritmetická negace: `-`

### 4. Bloky
- `()`: Závorky pro určení priority.
- `LAUNCH` - `END_LAUNCH`: Blok pro provedení mise.
- `IF` - `END_IF`: Podmíněný blok.
- `SEQUENCE` - `END_SEQUENCE`: Blok pro definici sekvence kroků.
-- `STEP` - `END_STEP`: Definuje konkrétní krok v sekvenci.

### 5. Příkazy
- `IGNITE`: Spustit proces (např. motory).
- `DEPLOY`: Provedení akce (např. nasazení padáků).
- `LOG`: Výpis hodnoty do konzole.
- `BAIL`: Předčasné ukončení aktuálního cyklu (`LOOP`).
- `ABORT`: Okamžité ukončení celého programu.

### 6. Řízení mise
- `MISSION_SUCCESS`: Indikuje úspěšné dokončení.
- `MISSION_FAIL`: Indikuje selhání.

### 7. Komentáře
- `#`: Hashtag začíná inline komentář
