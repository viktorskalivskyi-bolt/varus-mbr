# VARUS × Bolt — CEO MBR (Aug 2026)

CEO-level MBR-презентація по VARUS: один управлінський висновок на слайд, короткі
коментарі, графіки для ключових трендів та чіткі рішення/owners. Фокус: перевиконання
рампу, результати лончу, активні користувачі й Bolt+, інвестиції та campaign attribution,
операційні втрати, DT vs peers, CZ/IT backlog, CVP, pricing і шестимісячний action plan.

- Онлайн-версія: https://viktorskalivskyi-bolt.github.io/varus-mbr/
- Дані: `main.ng_delivery.dim_order_delivery`, `dim_basket_item_delivery`,
  `dim_food_getplace_item_price_comparison` (Databricks, bolt-data), станом на 26 Aug 2026.

## Статус

Перед відправкою партнеру підтвердити:

1. Офіційний ramp-план і KPI з контракту (у драфті гіпотеза 3 / 5 / 8 / 10 млн грн).
2. Дані по банерній підтримці в додатку (impressions, incremental GMV) — немає в Databricks.
3. Looker CVP / ODR-цифри.
4. Скріни 20 SKU «полиця vs Bolt» для слайду про маркап ×2.
5. Список CZ-тікетів зі статусами.

## Операційні втрати

Оціночний avoidable GMV loss за 1 Jun–26 Aug — **₴0.91 млн**:

- ≈1,141 excess failed orders проти NDR benchmark інших 3P stores (3.2%);
- середній кошик ≈₴798;
- метод: delivered orders × різниця failed/delivered rate × monthly AOV.

Це benchmark-оцінка втраченої можливості, а не бухгалтерський write-off.

## Файли

- `index.html` — самодостатній 15-слайдовий CEO-дек:
  Avenir Next, 16:9 layout, inline SVG-графіки, без зовнішніх залежностей.
