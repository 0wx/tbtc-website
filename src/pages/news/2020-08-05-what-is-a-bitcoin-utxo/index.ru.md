---
template: news-item
title: 'Что такое биткойн UTXO'
description: 'Unspent Transaction Outputs или сокращенно UTXO — это выводы неизрасходованных транзакций, они являются важным элементом функционирования…'
date: 2020-08-05T14:21:26.502Z
---
<!---
#  translator: paydaSandros#1054

#  url: https://clck.ru/QJ8v5

#  submission url: https://discordapp.com/channels/590951101600235531/701767679102550016/750105631356223498

----------

translated title: What is Bitcoin UTXO
match with: What is a Bitcoin UTXO?
confidence (0-1): 0.8695652173913043

-->
Unspent Transaction Outputs или сокращенно UTXO — это выводы неизрасходованных транзакций, они являются важным элементом функционирования блокчейна биткойна. Их можно понимать как остаточную ценность из предыдущих транзакций. UTXO служат нескольким целям в сети.

UTXO содействует транзакциям в сети биткойн. Когда человек отправляет биткойн, он шлет один или несколько выводов неизрасходованных транзакций в сеть. Выводы UTXO неделимы, поэтому если сумма транзакции точно не совпадает с размером отправленных UTXO, они депонируются в сеть и чеканятся новые выводы UTXO.

К примеру, пользовательский баланс биткойна составляет 50 BTC, в реальности это композиция из ряда различных выводов неизрасходованных транзакций. Для примера, предположим, что UTXO равны 22, 10, 8, 7 и 3 BTC соответственно. Человек решил потратить 5 BTC за одну транзакцию. Так как нету UTXO равной ровно 5 BTC, то сеть “расходует” UTXO на 7 BTC, в это же время происходит чеканка двух выводов на 5 и 2 BTC. 5 BTC UTXO отправляется конечному получателю, а 2 BTC возвращается к плательщику.

Таким образом, UTXO фактически изменяются в процессе транзакций биткойна. Этот факт служит важной цели. Поскольку каждый вновь отчеканенный UTXO вывод появился либо в качестве награды за майнинг, либо как остаток от предыдущей транзакции, то он, очевидно, ранее не был использован. Это есть своего рода механизм защиты от атак двойной траты и подтверждения валидности транзакций.

У UTXO также имеются и свои проблемы. По мере уменьшения их размеров, относительная стоимость проведения операции возрастает. В какой-то момент это может сделать обмен неэкономичным. К примеру, если при покупке кофе комиссия за оплату превышает цену самого кофе, то покупка перестает нести смысл. Сообщество в курсе этой проблемы и люди уже работают над различными ее решениями.

В системе tBTC выводы неизрасходованных транзакций представлены в виде уникальных и незаменяемых токенов TDT, которые создаются, когда пользователь запрашивает процедуру депозита. TDT токен — это токен формата ERC-721, который является копией TBTC. TDT представляет собой притязание на базовый UTXO депозита на блокчейне биткойна. Каждый TDT уникален для депозита создавшего его, и он предоставляет эксклюзивное право на обратный обмен в течение 6 месяцев с момента депозита.

Как только депозит квалифицирован посредством доказательства пополнения биткойн транзакцией (доказательство SPV Relay), владец может запросить выплату, и уже после оплаты соответствующих транзакционных издержек гарантированно получить аналогичный UTXO как и был на моменте депозита в сеть биткойн.

Присоединяйтесь к каналу \[[\\#tbtc Дискорд](https://discord.gg/wYezN7v)\] чтобы узнать больше о tBTC. Для подписки на рассылку по tBTC нажмите \[[тут](https://tbtc.network/#mailing-list)\].