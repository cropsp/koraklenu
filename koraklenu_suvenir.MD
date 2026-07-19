# Промти для Nano Banana — сувенірна лінійка «Княжа доба» (v2, з референсами)

Оновлення v2: до кожного промта додано перевірені референсні зображення (1–3). Робочий цикл: **завантажте референс(и) в Nano Banana → вставте промт → ітеруйте**. Промти англійською — модель працює з нею найточніше.

---

## ГОЛОВНЕ ПРАВИЛО (чому футболка вийшла «фантазією»)

Без референса модель вигадує — так з'явився неіснуючий «ВЕЛИКИЙ КНЯЗЬ ІШАННЪ · ЧЕРВОНА РУСЬ · 1400». Підвіска-колт вдалася саме тому, що був референс. Тому:

1. **Завжди завантажуйте референс** перед промтом.
2. **Додавайте до КОЖНОГО промта цей блок точності:**

```
ACCURACY: Faithfully reproduce the design, composition and figures from the
uploaded reference image. Do not invent any inscriptions, dates, names or
symbols. If the reference has lettering, copy its letterforms as decorative
shapes exactly as they appear, or render them as worn, barely legible strokes.
Do not add the modern Ukrainian state emblem.
```

3. **Точний текст (легенди монет) все одно вноситиме дизайнер у векторі.** Генерації — для концептів і презентацій, не для друку.

---

## БІБЛІОТЕКА РЕФЕРЕНСІВ (усі перевірені)

### Монети
| Що | Посилання |
|---|---|
| Срібник Володимира, тип IV (НМІУ, фото експоната) | https://assets.museum-digital.org/ua-kyiv/images/18/12777-au-744/_v____/v---12777-685094.jpg |
| Срібник Володимира (реверс, Одеський нумізматичний музей) | https://commons.wikimedia.org/wiki/File:Coin_of_Vladimir_the_Great.JPG |
| Уся категорія срібників (16 файлів: фото + промальовки) | https://commons.wikimedia.org/wiki/Category:Srebrennik |
| Златник Володимира (Ермітаж) — файл «Zlatnik from Hermitage.jpg» у категорії | https://commons.wikimedia.org/wiki/Category:Coins_of_Vladimir_I_of_Kiev |
| Срібник Ярослава Мудрого (св. Георгій + знак Ярослава) | https://commons.wikimedia.org/wiki/File:Coin_of_Yaroslav_the_Wise_with_his_lifetime_image.jpg |
| Категорія монет Ярослава (фото + векторні промальовки) | https://commons.wikimedia.org/wiki/Category:Coins_of_Yaroslav_I_the_Wise |

### Знаки та символи
| Що | Посилання |
|---|---|
| Плінфа з тризубом Володимира (НМІУ) | https://old.nmiu.org/images/content/exponat_week/plinfa.jpg |
| Вірча підвіска з Циблів — тризуб + рослинний орнамент (НМІУ) | https://old.nmiu.org/images/content/exponat_week/pidviska_tryzub.jpg |

### Колти та прикраси — Метрополітен (PUBLIC DOMAIN, можна і в друк)
| Що | Пряме зображення (оригінальна роздільність) |
|---|---|
| Колт: два сирини + дерево життя (інв. 17.190.680) | https://images.metmuseum.org/CRDImages/md/original/DT11967.jpg |
| — його зворот: дві птахи | https://images.metmuseum.org/CRDImages/md/original/DT11968.jpg |
| Колт: два птахи + дерево життя (інв. 17.190.679) | https://images.metmuseum.org/CRDImages/md/original/17.190.679.jpg |
| Колт: птахи (аверс) / людські голови (реверс), з перлами (інв. 17.190.704) | https://images.metmuseum.org/CRDImages/md/original/DT11965.jpg |
| Колт: святі з мученицьким хрестом (інв. 17.190.699) | https://images.metmuseum.org/CRDImages/md/original/DT12038.jpg |
| Ланцюжок-рясна з птахами, емаль (інв. 17.190.681) | https://images.metmuseum.org/CRDImages/md/original/sf17-190-681s1.jpg |

### Скарби, браслети, діадема
| Що | Посилання |
|---|---|
| Сахнівська діадема (грифони + Александр) | https://spadok.org.ua/images/bolokhiv/2456.jpg |
| Браслет-наруч 1893 (грифони, чернь) | https://spadok.org.ua/images/braslety-naruchni/3_6480.jpg |
| Браслет-наруч, Кудрявський скарб (воїн і хижак) | https://spadok.org.ua/images/braslety-naruchni/braslet-naruch-kudryavskyi-skarb.jpg |
| Колти Сахнівського скарбу (сирини, емаль — НМІУ) | https://nmiu.org/strapi/uploads/34_DM_1780_26b81a1dee.jpg |
| Галерея прикрас Русі (Commons, багато файлів) | https://commons.wikimedia.org/wiki/Category:Jewellery_of_Kievan_Rus |

### Мозаїки, рукописи
| Що | Посилання |
|---|---|
| Оранта, Софія Київська (3131×4324 px) | https://commons.wikimedia.org/wiki/File:Oranta-Kyiv.jpg |
| Усі мозаїки Софії (категорія) | https://commons.wikimedia.org/wiki/Category:Mosaics_of_Saint_Sophia_Cathedral_in_Kyiv |
| Ізборник 1073: мініатюра родини Святослава | https://commons.wikimedia.org/wiki/File:Izbornik.jpg |
| Ізборник 1073: категорія (заставки, сторінки) | https://commons.wikimedia.org/wiki/Category:Svyatoslav%27s_Miscellanies |
| Остромирове Євангеліє: сторінка із заставкою | https://commons.wikimedia.org/wiki/File:Ostromir_Gospel_1.jpg |
| Остромирове Євангеліє: категорія (буквиці, мініатюри) | https://commons.wikimedia.org/wiki/Category:Ostromir_Gospels |

З Commons-сторінки завантажуйте оригінал кнопкою «Download original file». Прямі URL Met та музеїв можна зберігати одразу.

---

## Стильовий блок (у кінець кожного промта)

```
STYLE: professional product photography, soft studio lighting, neutral
light-gray background, shallow depth of field, photorealistic, high detail,
no text overlays, no watermarks, museum gift shop aesthetic.
```

Для флет-лей: `STYLE: flat lay product photography, top-down view, linen fabric background, natural window light, photorealistic.`

---

## НОВИЙ БЛОК: Колекція монет (на ваш запит)

### М1. Набір «Монети князів» — три дерев'яні «монети»
РЕФЕРЕНСИ (завантажте всі три):
- Срібник Володимира: https://assets.museum-digital.org/ua-kyiv/images/18/12777-au-744/_v____/v---12777-685094.jpg
- Срібник Ярослава: https://commons.wikimedia.org/wiki/File:Coin_of_Yaroslav_the_Wise_with_his_lifetime_image.jpg
- Златник (з категорії): https://commons.wikimedia.org/wiki/Category:Coins_of_Vladimir_I_of_Kiev
```
Using the three uploaded photos of medieval Kyivan Rus coins as exact
references, create a collectible set of three laser-engraved wooden coin
replicas, 60 mm each, displayed in a row inside a kraft cardboard collector
box with a linen lining. Each wooden coin faithfully reproduces one
reference: (1) the prince on a throne with the trident, (2) Saint George
with a spear, (3) Christ Pantokrator bust. Deep engraving on birch plywood.
ACCURACY: [блок точності] STYLE: [стильовий блок]
```
Українською: колекційний набір із трьох монет у коробці — розширення вашого вдалого магніта.

### М2. Монета-магніт «Срібник» (те, що вже вийшло, — фінальні правки)
РЕФЕРЕНС: https://assets.museum-digital.org/ua-kyiv/images/18/12777-au-744/_v____/v---12777-685094.jpg
```
Using the uploaded photo of the medieval srebrenik coin as exact reference,
refine the wooden engraved coin-magnet: keep the seated prince composition
and the dotted border exactly as in the reference, make the trident symbol
match the reference precisely, render the circular legend as the same worn
letterforms seen in the reference (do not invent new letters). 55 mm birch
plywood, deep burn engraving.
ACCURACY: [блок точності] STYLE: [стильовий блок]
```
Українською: доведення вашого магніта — композиція і легенда суворо за референсом.

### М3. Подвійний сувенір «аверс/реверс»
РЕФЕРЕНСИ: обидва боки з https://commons.wikimedia.org/wiki/Category:Srebrennik
```
Two laser-engraved wooden coins side by side showing the obverse and reverse
of the same medieval coin from the uploaded references: one with the seated
prince, one with the large trident symbol filling the whole field. Presented
on a small wooden stand with a printed caption card (blank). Museum shop
collectible look.
ACCURACY: [блок точності] STYLE: [стильовий блок]
```
Українською: пара «аверс + реверс» на підставці — тип II–III срібника, де тризуб на все поле.

---

## БЛОК А. Лазер по дереву

### A1. Магніт-«монета» → див. М2 (об'єднано, з референсом)

### A2. Брелоки «Знаки князів» (серія)
РЕФЕРЕНСИ:
- Плінфа з тризубом: https://old.nmiu.org/images/content/exponat_week/plinfa.jpg
- Підвіска з Циблів: https://old.nmiu.org/images/content/exponat_week/pidviska_tryzub.jpg
- Промальовки знаків: https://commons.wikimedia.org/wiki/Category:Srebrennik (файли «drawing.svg»)
```
Using the uploaded reference images of authentic 10th–11th century princely
trident symbols (from a brick stamp and a coin), create a set of three wooden
keychains laser-cut from birch plywood, displayed on dark slate. Each keychain
is a cut-through silhouette of one authentic symbol variant from the
references. Clean charred edges, small leather cords.
ACCURACY: [блок точності] STYLE: [стильовий блок]
```

### A3. Закладка з плетінкою та буквицею
РЕФЕРЕНСИ:
- Сторінка Остромирового Євангелія: https://commons.wikimedia.org/wiki/File:Ostromir_Gospel_1.jpg
- Буквиці з категорії: https://commons.wikimedia.org/wiki/Category:Ostromir_Gospels
```
Using the uploaded manuscript page as reference for the ornament style,
create a slim wooden bookmark, laser-cut from thin plywood, with an openwork
interlace pattern along one edge copied from the manuscript headpiece, and
one large engraved initial letter reproduced from the reference. The bookmark
sticks out of an open old book, warm library light.
ACCURACY: [блок точності] STYLE: [стильовий блок]
```

### A4. Підвіска-«колт» (ваш вдалий кейс — тепер варіанти)
РЕФЕРЕНСИ (по одному на генерацію — вийде серія з 4 різних підвісок):
- Сирини + дерево життя: https://images.metmuseum.org/CRDImages/md/original/DT11967.jpg
- Птахи + дерево життя: https://images.metmuseum.org/CRDImages/md/original/17.190.679.jpg
- Птахи + перли по краю: https://images.metmuseum.org/CRDImages/md/original/DT11965.jpg
- Святі з хрестом: https://images.metmuseum.org/CRDImages/md/original/DT12038.jpg
```
Using the uploaded photo of a medieval gold kolt pendant as reference, create
a laser-cut wooden pendant necklace that reproduces its exact shape and
engraved design. Light wood, dark engraved lines, thin leather cord. Product
photo on a ceramic dish with dried flowers.
ACCURACY: [блок точності] STYLE: [стильовий блок]
```
Українською: той самий промт, що спрацював, — тепер із чотирма різними верифікованими колтами Метрополітену (усі public domain).

### A5. Костери зі сланцю
РЕФЕРЕНСИ:
- Оранта: https://commons.wikimedia.org/wiki/File:Oranta-Kyiv.jpg
- Плетінка/заставка: https://commons.wikimedia.org/wiki/File:Ostromir_Gospel_1.jpg
```
Using the uploaded mosaic and manuscript references, create a set of four
round slate coasters with laser-engraved line-art designs: one reproduces the
standing figure with raised hands from the mosaic reference as fine line art,
the others use the interlace patterns from the manuscript reference.
Silver-gray engraving on black slate, stacked and fanned on a wooden table.
ACCURACY: [блок точності] STYLE: [стильовий блок]
```

### A6. Ялинкова прикраса «Колт»
РЕФЕРЕНС: https://images.metmuseum.org/CRDImages/md/original/DT11965.jpg (колт з перлами — край дає красивий ажур)
```
Using the uploaded kolt pendant photo as reference, create a delicate
laser-cut wooden Christmas ornament reproducing its shape with an openwork
beaded border, hanging on a red ribbon against a blurred Christmas tree.
ACCURACY: [блок точності] STYLE: [стильовий блок]
```

---

## БЛОК Б. Лазер по шкірі

### Б1. Шкіряний браслет «Русалії»
РЕФЕРЕНСИ:
- Браслет 1893 (грифони): https://spadok.org.ua/images/braslety-naruchni/3_6480.jpg
- Кудрявський браслет: https://spadok.org.ua/images/braslety-naruchni/braslet-naruch-kudryavskyi-skarb.jpg
```
Using the uploaded photos of medieval silver bracelets with engraved arched
panels as reference, create a wide veg-tan leather cuff bracelet with the
same scenes laser-engraved along its length, reproducing the figures from
the references: griffins with turned-back heads and the fantastic beasts in
arched frames. Dark engraving on cognac leather, brass snap closures.
ACCURACY: [блок точності] STYLE: [стильовий блок]
```

### Б2. Картхолдер із тризубом
РЕФЕРЕНС: https://old.nmiu.org/images/content/exponat_week/pidviska_tryzub.jpg
```
Using the uploaded photo of the ancient trident pendant as reference,
create a slim cognac leather cardholder with that exact trident symbol
laser-engraved small and centered. A matching keychain beside it, craft
workshop table, warm light.
ACCURACY: [блок точності] STYLE: [стильовий блок]
```

### Б3. Шкіряний патч із грифоном (заготовка для кепок)
РЕФЕРЕНСИ:
- Діадема з грифонами: https://spadok.org.ua/images/bolokhiv/2456.jpg
- Браслет 1893: https://spadok.org.ua/images/braslety-naruchni/3_6480.jpg
```
Using the uploaded references, create a round laser-engraved leather patch,
60 mm, reproducing one griffin from the reference — wings raised, head turned
back — framed by a thin interlace border. Dark burn on natural tan leather,
flat on white background, product catalog style.
ACCURACY: [блок точності] STYLE: [стильовий блок]
```

---

## БЛОК В. Текстиль (принти)

### В1. Футболка «Срібник» (виправлення вашої «фантазійної»)
РЕФЕРЕНС (обов'язково!): https://assets.museum-digital.org/ua-kyiv/images/18/12777-au-744/_v____/v---12777-685094.jpg
```
Using the uploaded photo of the medieval srebrenik coin as exact reference,
create a sand-colored cotton t-shirt on a wooden hanger against a white brick
wall. Large centered screen print in dark brown reproducing the coin design
faithfully: the same seated prince, the same trident, the same dotted border,
and the circular legend rendered as the same worn letterforms visible in the
reference — do not invent any new text, names or dates. Distressed vintage
stamp texture.
ACCURACY: [блок точності]
```
Українською: та сама футболка, але композиція і напис — суворо з монети НМІУ. Точну легенду «ВЛАДИМИРЪ НА СТОЛѢ А СЕ ЕГО СРЕБРО» дизайнер набере у векторі шрифтом-уставом.

### В2. Футболка «Оранта»
РЕФЕРЕНС: https://commons.wikimedia.org/wiki/File:Oranta-Kyiv.jpg
```
Using the uploaded mosaic photo as reference, create a black premium t-shirt
flat lay with a small chest print: the standing figure with raised hands
reproduced from the reference, built from visible mosaic tesserae squares in
gold and deep blue. Minimalist, lots of empty space.
ACCURACY: [блок точності]
```

### В3. Тоут-бег із патерном
РЕФЕРЕНСИ:
- Заставка Остромирового Євангелія: https://commons.wikimedia.org/wiki/File:Ostromir_Gospel_1.jpg
- Браслет із плетінкою: https://spadok.org.ua/images/braslety-naruchni/3_6480.jpg
```
Using the uploaded references for ornament style, create a natural cotton
canvas tote bag whose entire front is covered with a seamless repeating
interlace pattern derived from the manuscript headpiece ornament in the
reference, printed in a single deep terracotta color.
ACCURACY: [блок точності] STYLE: [стильовий блок]
```

### В4. Бандана «Русалії»
РЕФЕРЕНСИ: обидва браслети зі спадок (див. Б1)
```
Using the uploaded bracelet photos as reference, create a square cotton
bandana printed with a border composition: around the perimeter run the same
arched panels with figures reproduced from the references — dancers,
musicians, griffins — in dark indigo on off-white. A single interlace
medallion in the center.
ACCURACY: [блок точності] STYLE: flat lay, top-down view.
```

### В5. Дитяча футболка «Сирин»
РЕФЕРЕНС: https://images.metmuseum.org/CRDImages/md/original/DT11967.jpg
```
Using the uploaded kolt photo as reference, create a small child-size
mustard-yellow t-shirt with a friendly storybook-style illustration of the
sirin bird from the reference — a smiling bird with a human face and little
halo, simplified shapes, warm colors, keeping the recognizable silhouette
from the reference. Flat lay with wooden toys.
ACCURACY: [блок точності]
```

---

## БЛОК Г. Гібриди (лазер + текстиль)

### Г1. Кепка зі шкіряним патчем
РЕФЕРЕНСИ: як у Б3 (діадема + браслет)
```
Using the uploaded references, create a washed olive-green dad cap with a
round laser-engraved leather patch sewn on the front, the patch reproducing
the griffin from the reference framed by an interlace border. Concrete
surface, three-quarter view.
ACCURACY: [блок точності] STYLE: [стильовий блок]
```

### Г2. Подарунковий набір (один мотив наскрізь)
РЕФЕРЕНСИ: срібник НМІУ + браслет 1893 (два файли)
```
Using the uploaded coin and bracelet references, create a flat lay gift set
in an open kraft box with wood shavings: a sand t-shirt with the coin design
print folded neatly, a leather cuff with the engraved griffins from the
bracelet reference, a wooden coin-magnet reproducing the coin, and a small
blank caption card. All designs faithfully follow the references.
ACCURACY: [блок точності] STYLE: flat lay, warm daylight, premium unboxing.
```

### Г3. Сумка з аплікацією
РЕФЕРЕНС: https://spadok.org.ua/images/bolokhiv/2456.jpg
```
Using the uploaded diadem photo as reference, create a dark canvas tote bag
with a sewn-on appliqué: a laser-cut tan leather silhouette of one griffin
from the reference, stitched with visible contrast thread. Close-up showing
stitching and laser-cut edge.
ACCURACY: [блок точності] STYLE: [стильовий блок]
```

---

## БЛОК Д. Інші техніки

### Д1. Значок із м'якою емаллю «Колт»
РЕФЕРЕНС: https://images.metmuseum.org/CRDImages/md/original/DT11967.jpg
```
Using the uploaded cloisonné kolt photo as reference, create a small enamel
pin reproducing its exact shape and design: two sirins flanking a tree of
life in enamel cells of deep blue, red and white with gold metal outlines —
the modern soft-enamel technique deliberately echoing the original medieval
cloisonné. Macro shot on a linen jacket lapel.
ACCURACY: [блок точності] STYLE: [стильовий блок]
```

### Д2. Керамічне горня
РЕФЕРЕНС (стиль орнаменту): будь-яке фото давньоруської кераміки з https://commons.wikimedia.org/wiki/Category:Kievan_Rus (або без референса — орнамент простий і типовий)
```
A handmade ceramic mug in warm cream glaze with a band of simple medieval
Slavic pottery ornament around the middle: parallel wavy and straight
incised lines, exactly like on 10th–13th century Kyivan Rus pots. A small
potter's wheel mark stamped on the bottom, shown beside. Rustic kitchen,
morning light.
ACCURACY: no invented symbols or text. STYLE: [стильовий блок]
```

### Д3. Блокнот «Ізборник»
РЕФЕРЕНСИ:
- Мініатюра родини Святослава: https://commons.wikimedia.org/wiki/File:Izbornik.jpg
- Категорія (заставки): https://commons.wikimedia.org/wiki/Category:Svyatoslav%27s_Miscellanies
```
Using the uploaded manuscript page as reference, create a hardcover notebook
whose cover reproduces the ornate rectangular headpiece frame from the
reference — old-Byzantine floral ornament with peacocks — with gold accents
on deep teal, plus a leather spine. On a desk with a fountain pen.
ACCURACY: [блок точності] STYLE: [стильовий блок]
```

### Д4. Сургучна печатка «Молівдовул»
РЕФЕРЕНС (стиль): срібник Ярослава зі св. Георгієм — https://commons.wikimedia.org/wiki/File:Coin_of_Yaroslav_the_Wise_with_his_lifetime_image.jpg
```
Using the uploaded coin photo as style reference, create a brass wax seal
stamp carved with the Saint George bust design from the reference, shown
next to red wax impressions on kraft envelopes. Byzantine seal aesthetic.
ACCURACY: [блок точності] STYLE: [стильовий блок]
```

---

## Вітрина (генеральний кадр колекції)
РЕФЕРЕНСИ: 3–4 найкращі вже згенеровані вами продукти (Nano Banana вміє збирати сцену з кількох завантажених зображень)
```
Combine the uploaded product photos into one museum gift shop display shelf:
arrange the wooden coin-magnets, the kolt pendant, the leather bracelet and
the t-shirt as a cohesive collection with warm spotlighting, clean modern
museum retail design. Keep each product's design exactly as in its photo.
```
Українською: замість генерувати вітрину «з нуля» — зберіть її з ваших вдалих генерацій, так усі продукти лишаться консистентними.

---

## Технічні поради (оновлено)

1. **Один референс = один продукт.** Не завантажуйте 5 артефактів для однієї підвіски — модель змішає. Виняток: набори (М1, Г2), де змішання і потрібне.
2. **Commons-посилання** ведуть на сторінку файлу — завантажте звідти оригінал («Download original file») і його вже кладіть у Nano Banana.
3. **Met-зображення (images.metmuseum.org) — public domain**: їх можна використовувати навіть у фінальному друці без дозволу. Для решти (НМІУ, spadok) генерації ок, а друк — після узгодження прав або через власну промальовку.
4. **Правки серією:** "same design, but deeper engraving" / "same coin, now as a slate coaster" — в одному чаті стиль зберігається.
5. **Формат:** "square 1:1" для карток товару, "4:5" для Instagram, "16:9" для банерів.
6. **Чесне маркування на виробах:** «За срібником Володимира X–XI ст., НМІУ» тощо.
