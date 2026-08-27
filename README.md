# VARUS × Bolt — MBR draft (Aug 2026)

Перший драфт MBR-презентації по VARUS: продажі vs ramp, результати лончу, юзери та Bolt+,
спенди й ефективність кампаній, операційні метрики (DT vs інші гравці), store hotspots,
availability / ODR / customer feedback, CVP, перевірка ціноутворення, action tracker
на 6 місяців і playbook на лонч наступних grocery-партнерів.

- Онлайн-версія: https://viktorskalivskyi-bolt.github.io/varus-mbr/
- Дані: `main.ng_delivery.dim_order_delivery`, `dim_basket_item_delivery`,
  `dim_food_getplace_item_price_comparison` (Databricks, bolt-data), станом на 26 Aug 2026.

## Статус

Internal draft. Не відправляти партнеру, поки не підтверджено:

1. Офіційний ramp-план і KPI з контракту (у драфті гіпотеза 3 / 5 / 8 / 10 млн грн).
2. Дані по банерній підтримці в додатку (impressions, incremental GMV) — немає в Databricks.
3. Looker CVP / ODR-цифри.
4. Скріни 20 SKU «полиця vs Bolt» для слайду про маркап ×2.
5. Список CZ-тікетів зі статусами.

## Файли

- `index.html` — самодостатній 15-слайдовий дек у стилі Corezoid-документа:
  Avenir Next, 16:9 layout, inline SVG-графіки, без зовнішніх залежностей.
