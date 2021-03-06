---
template: news-item
title: 'tBTC актыўны'
description: 'Гэты артыкул уяўляе сабой неафіцыйны пераклад на беларускую мову наступнага артыкулу і прызначаецца для знаёмства беларускай аўдыторыі з…'
date: 2020-09-22T13:27:02.333Z
---
<!---
#  translator: Kiryl#0277

#  url: https://medium.com/@13fckmyluck13/tbtc-%D0%B0%D0%BA%D1%82%D1%8B%D1%9E%D0%BD%D1%8B-b98caf77006b

#  submission url: https://discordapp.com/channels/590951101600235531/701767679102550016/763135870051287040

----------

translated title: tBTC is active
match with: tBTC Is Live
confidence (0-1): 0.7857142857142857

-->
_Гэты артыкул уяўляе сабой неафіцыйны пераклад на беларускую мову наступнага_ [_артыкулу_](https://angel.co/company/thesis-co/jobs/980348-front-end-engineer-keep) _і прызначаецца для знаёмства беларускай аўдыторыі з праектам_ [_Keep Network_](https://keep.network/)

tBTC, праект з адкрытым зыходным кодам, які дазваляе людзям бяспечна выкарыстоўваць бiткоiны ў прыкладаннях Ethereum DeFi, актыўны і гатовы да выкарыстання. Праект Keep, Summa і Cross-Chain Group, tBTC дазваляе людзям абменьваць BTC на TBTC, токен ERC-20, які можна выкарыстоўваць на платформах DeFi, з каэфіцыентам 1: 1.

Кожны токен TBTC цалкам забяспечаны і адпавядае як мінімум 1 BTC, захаванаму у рэзерве. tBTC даверны, і выкарыстоўвае Random Beacon для выбару «падпісантаў», якія адказны за унесеныя BTC. Вы можаце канвертаваць TBTC у BTC і наадварот, калі захочаце, без неабходнасці падпісання пасярэдніка. І гэта проста: усяго Вам неабходна мець тры простых кроку, каб мінтаваць TBTC у сетцы [tbtc.network](https://tbtc.network/) і адсочваць свой Бiткоiн.

У праекце выкарыстоўваецца парог ECDSA, які прайшоў аўдыт і выкарыстоўваецца на кашальках і біржах. Праз Nexus Mutual ажыццяўляецца абарона сродкаў, дзякуючы якой можна не перажываць за захаванасць сродкаў.

tBTC прайшоў тры аўдыту і завяршыла свой першы аўдыт бяспекі,
-------------------------------------------------------------

Аўдыт праводзіўся ConsenSys, у сакавіку. У чэрвені быў завершаны другі аўдыт Trail of Bits, а ў жніўні — аўдыт биткойнов, праведзены Сяргеем Дэльгада.

Запуск tBTC ажыццяўляецца ў адпаведнасці з мадэллю «рэліз-кандыдат». «Рэліз-кандыдаты» прагрэсуюць ад 0 да 1 і да 2, пакуль кандыдат не будзе прызнаны канчатковым і не будзе абноўлены да стабільнага выпуску.

Альфа-запуск tBTC, вядомы як rc.0, быў запушчаны у майннете пасля публічнага аўдыту ConsenSys Diligence. Хоць сродкі карыстальнікаў ніколі не падвяргаліся рызыцы, наша каманда выявіла праблему і неадкладна прыпыніла прыём новых сродкаў, пакуль праблема не была ліквідавана. rc.1 вырашыў гэтую праблему і быў запушчаны з ужываннем беспрэцэдэнтных мераў бяспекі.

Бягучы дадатак live dApp, створаны на аснове rc.1, застанецца ў альфа-версіі на працягу некалькіх тыдняў, на працягу якіх будзе дзейнічаць паступовае абмежаванне паставак. Затым будзе бэта-версія.

rc.1 мае жорсткае абмежаванне на прапанову TBTC, пачынаючы з 100 BTC у першы тыдзень. Кожны тыдзень кантракты будуць аслабляць абмежаванне на дэпазіт у адпаведнасці з загадзя зацверджаным графікам.

![Image for post](https://miro.medium.com/max/1786/1*p_6o7PSg5njcJvKYxn0SKQ.png)

На працягу першых 48 гадзін пасля уводу у эксплуатацыю існуе нізкая мяжа прапановы, які дазваляе праводзіць тэставанне з нізкім узроўнем рызыкі. Затым мяжа прапановы павялічыцца да 100 TBTC на астатнюю частку першага тыдня, а затым павялічыцца да 250 TBTC праз тыдзень.

Ліміт прапановы будзе павялічвацца на 250 TBTC кожны тыдзень, пакуль не дасягне 1000 TBTC. Пасля гэтага павелічэнне будзе на 500 TBTC кожны тыдзень, пакуль не дасягне 3000 BTC праз дзевяць тыдняў пасля запуску. Затым, нарэшце, праз тыдзень абмежаванне на прапанову будзе павялічана да 21 млн TBTC (як і BTC).

Калі ў нейкі момант у смарт-кантрактах будзе выяўленая крытычная ўразлівасць, каманда прыпыніць дзеянне неадкладнага дэпазіту і скаардынуе выснова сродкаў, а затым паўторна разгорне якія выпраўляюцца кантракты як rc.2, пераналадзіўшы план капіталізацыі. Праз 6 месяцаў без здарэнняў каманда адключыць кнопку аварыйнай паўзы.

Даведайцеся больш
=================

Калі хочаце даведацца больш інфармацыі аб [Keep Network](https://keep.network/), то:

*   Дадавайце да нас на [Reddit](https://www.reddit.com/r/KeepNetwork/).
*   Азнаёмцеся з нашым WP.
*   Азнаёмцеся з нашым [бізнес-планам](https://keep.network/primer).
*   Падпішыцеся на [e-mail](https://keep.network/) рассылку.
*   Дадавайце да нас у [Twitter](https://twitter.com/keep_project).
*   Дадавайце да нас у [Slack](https://keep.network/).
*   Дадавайце да нас у [Telegram](https://t.me/KeepNetworkOfficial).
