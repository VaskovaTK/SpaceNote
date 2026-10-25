# Space Note — сайт с политикой конфиденциальности

Два файла для GitHub Pages:

- `index.html` — простая главная страница
- `privacy.html` — политика конфиденциальности на трёх языках (RU / EN / TR)

## Что заменить перед публикацией

Открой оба файла в блокноте (или прямо в редакторе GitHub) и замени:

Всё подставлено: e-mail `vaskovatk@gmail.com`, издатель `Norka Tanya`. Менять ничего не нужно.

Даты уже проставлены: 25 октября 2026. Если публикация позже — поменяй на дату публикации
(в `privacy.html` они в конце каждого языкового блока, строки `class="date"`).

## Как опубликовать на GitHub Pages

1. На github.com → **New repository**. Имя: `spacenote` (или любое). Public. Поставь галочку
   «Add a README file» — репозиторий не должен быть пустым.
2. В репозитории: **Add file → Upload files** → перетащи `index.html` и `privacy.html` →
   **Commit changes**.
3. **Settings → Pages** → Source: *Deploy from a branch* → Branch: `main`, папка `/ (root)` → **Save**.
4. Через 1–3 минуты сайт будет доступен по адресу:
   `https://ИМЯ_АККАУНТА.github.io/spacenote/`
   Политика: `https://ИМЯ_АККАУНТА.github.io/spacenote/privacy.html`

Если репозиторий назван `ИМЯ_АККАУНТА.github.io`, адрес будет без хвоста:
`https://ИМЯ_АККАУНТА.github.io/privacy.html`

## Куда вставить ссылку в Google Play Console

**App content → Privacy policy** → вставить ссылку на `privacy.html` → Save.
Ссылку на ту же страницу обычно добавляют и в описание приложения, и в настройках
магазина (Store listing → Contact details, рядом с e-mail).

## Что ещё важно в Data safety

В разделе **App content → Data safety** в Play Console отвечай «нет» на сбор и передачу данных:
приложение ничего не собирает и не отправляет на сервер. Покупка обрабатывается Google Play —
отдельно её указывать как сбор данных не нужно.
