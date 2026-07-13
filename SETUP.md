# 🚀 Як задеплоїти профіль

## Крок 1 — Створи спеціальний репозиторій
На GitHub створи **новий репозиторій з назвою рівно `evlinges`** (така сама, як твій нікнейм).
> ⚠️ Важливо: `Public`, і НЕ додавай README при створенні (він у нас уже є).

## Крок 2 — Онови gh-токен (він протермінувався)
```bash
gh auth login -h github.com
```
Або пушни напряму (див. нижче).

## Крок 3 — Запуш файли
```bash
cd /home/evelina/evlinges
git remote add origin git@github.com:evlinges/evlinges.git   # SSH
# або HTTPS:  git remote add origin https://github.com/evlinges/evlinges.git
git push -u origin main
```

## Крок 4 — Увімкни змійку 🐍
1. Відкрий репо → вкладка **Actions** → дозволь workflows.
2. Запусти workflow **"🐍 Generate Snake Animation"** вручну (кнопка *Run workflow*).
3. Він створить гілку `output` зі змійкою. Далі оновлюється щодня автоматично.
> Поки workflow не відпрацював — блок зі змійкою в README буде порожнім, це нормально.

---

## Що всередині профілю
- 🌊 Анімований waving-банер (capsule-render)
- ⌨️ Друкована анімація зі слоганами (readme-typing-svg)
- 👁️ Лічильник переглядів + фоловери + Pull Shark badge
- 🧪 Стек технологій badge-ами (у твоєму фіолетовому дарк-стилі)
- 📊 GitHub Stats + Top Languages + Streak (dark theme #1a1a2e / #8338ec)
- 🏆 Trophy shelf
- 🎨 Pinned проєкти карточками
- 🐍 Анімація змійки з контрибуцій
- 💭 Випадкова цитата
- ☕ Контакти + footer

## Хочеш підкрутити?
- Колірна палітра: скрізь `1a1a2e` (фон), `8338ec` (акцент), `c8b6ff`/`e0aaff` (текст). Заміни на свої.
- Слогани друкарки — у параметрі `lines=` в блоці Typing SVG.
- Прибрати блок — просто видали відповідну секцію.
