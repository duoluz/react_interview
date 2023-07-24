# React Frontend дастурчиси билимини бахолаш учун топшириқ

Сизга тақдим этилаётган ушбу лойиҳа **duol.uz** жамоси тамонидан ишлаб чиқилган.
Мазкур лойиҳадан кўзланган асосий мақсад бизнинг компаниямизга `React Frontend` дастурчи сифатида ишга кириш истаги бўлган
номзодларнинг билим даражасини, технологиялардан тўғри фойдалана олишини, ҳамда код ёзиш услуби ҳақидаги маълумотларни аниқлаш
ҳисобланади.

![](https://i.ibb.co/FxBtfQ4/duol-logo.png)

### Лойиҳани ҳақида қичқача маълумот
Сиздан Java Spring дастурчичи сифатида талаб қилинадиган лойиҳа бу Spring Boot ёрдами оддий веб иловани ишлаб чиқиш ҳисобланади.
Мазкур лойиҳа java ва Spring ҳақида мақолалар ва уларга ёзиладиган шрахлардан ташкил топган ва унинг номни BLOG деб номалймиз.
Ушбу лойиҳада ассоан ўрганувчилар учун долзарб ва қизиқарли бўлган маълумотлар тўлиқ ёртииб борилади.

Топшириқ ҳақидаги тўлиқ маълумотларни сиз [PROJECT_REQUIREMENTS](/PROJECT_REQUIREMENTS.md) файлидан олшингиз мумкин.

### Лойиҳани амалга ошириш бўйича қичқача маълумот

Мазкур лойиҳа сизниг React ва TypeScript ҳақида билимларингизни аниқлаш ҳамда замонваий технологиялар ечимларни қай
даражада қўллай олишингиз ҳақидаги маълумотларни аниқлаш учун мўлжалланган. Сизларга енгиллик яратиш мақсадида енгил
ва ўртача даражадаги технолигиялардан фойдаланишга қарор қилдик.
Яъни лойиҳани амалга оширишда сиз қуидагилардан фойдаланишингиз мумкин:

* Node.js 17 +
* React
* TypeScript
* Redux
* Redux Toolkit
* RTK Query (Веб сервиларга мурожат қилиш ва маълумотларни кешлаш мақсадида ишлатиш мумкин)
* Tailwind(Бунинг ўрнига Bootstrap ишлатишингиз хам мумкин)
* json-server(Mock api сервер сифатида ишлатиш мумкин)

## Git Commit ҳақида
Ушбу бўлим git commit учун ёзиладан хабарлар ва шарҳлар учун қоидалар тўпламидан ташкил топган.
Лойиҳанинг ҳар бир иштирокчиси қуйидаги қоидаларни яхши билиши талаб этилади.

Бизнинг жамода git commit ҳабарларини ёзиш формати бўйича аниқ ишлаб чиқилган қоидаларимиз бор.
Бу қоидалар бизга лойиҳанинг тарихини кузатишни енгиллаштиради ҳамда мазкур ўзгаришлар ҳақида хабарларни ўқишни осонлаштиради.

## Git Commit ҳақидаги хабарларни форматлаш бўйича наъмуна

Ҳар битта Git Commit хабари сарлавҳа, асоси қисм ва пастки қисмдан ташкил топган
The header has a special format that includes a type, a scope and a subject:
Сарлавҳа ҳам ўзнавбатида махсус форматга эга бўлиб, у топшириқ тури ва унинг мавзусини ўз ичига қамраб олади
Хабарлар қуйида келтирилган намуна асосида яратилади:
```gitexclude
<type>(<scope>): <subject>
<BLANK LINE>
<body>
<BLANK LINE>
<footer>
```

Бу ерда сарлавҳа(subject)ни тўлдириш мажбурий ва топшириқ тури(scope)ни белгилаш ихтиёрий ҳисобланади.
Шунингдек ҳар қандай хабардаги символлар сони 100 та символдан ошмаслиги лозим.
Бу жиҳат бизларга турли ҳилдаги git воситалари ёрдамида хабарни ўқиш жараёнини енгиллаштиради.

Лойиҳа доирасида юзага келадиган ўзрашилар турини ифодалаш учун одатда қуйидаги типлардан фойдаланилади:
* **feature**: Лойиҳага янги имклниятлар ёки функциялар амалга оширилган тақдирда фойдаланилади
* **fix**: Лойиҳага тегишли турли хил хатоликларни тўғриланган тақдирда фойдаланилади
* **docs**: Лойиҳага тегишли ҳужжатдар ўзгарган тақдирда фойдаланилади
* **style**: дастурдаги кодларнинг мазмунига таъсир қилмайдиган ўзгаришлар (ортиқча пробелларни олиб ташлаш, форматлаш ва бошқалар)
* **refactor**: Мавжуд коднинг ишлашиши тўғриламайдиган ёки янги фунциялар қўшилмаган тарздаги мавжуд кодларнинг ўзгаришини ифодаш учун ишлатилади
* **perf**: Коднинг иш самарадорлигини яхшилашга қаратилган ўзгаришлани ифодалаш
* **test**: Янг тестларни қўйиш ёки мавжудларини тўғрилнганлигини ифодалаш учун ишлатилади
* **build**: Лойиҳани ишчи ҳолатга келтириш ва йиғишга таъсир қилувчи ўзгаришларни ифодалаш учун ишлатилади (мисол учун: gulp, npm)
* **ci**: CI конфигурацияларига алоқадор файл ва скриптларга киритилган ўзгаришларни ифодалаш учун ишлатилади (мисол учун: Travis, Circle, BrowserStack, SauceLabs)
* **chore**: Лойиҳа таркибидаги src ва test файллари ташқари ўзгаришларни ифодалаш учун ишлатилади
* **revert**: Лойиҳага киритлган ўзгаришларни бекор қилиш олдини ҳолатига қайтариш учун ишлатилади

## Дастурни тетслаш бўйича талаблар

Лойиҳадаги кодларни тестлаш мақсадида сиздан албатта `unit test` ёзиш талаб этилади.

###  Барча номзодларга омад тилаймиз!