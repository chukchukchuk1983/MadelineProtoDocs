---
title: "payments.getStarsGiveawayOptions"
description: "Fetch a list of [star giveaway options »](https://core.telegram.org/api/giveaways#star-giveaways)."
grand_parent: "Telegram RPC API"
parent: "Methods"
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
redirect_from: /API_docs/methods/payments_getStarsGiveawayOptions.html
---
# Method: payments.getStarsGiveawayOptions
[Back to methods index](index.html)



Fetch a list of [star giveaway options »](https://core.telegram.org/api/giveaways#star-giveaways).



### Return type: [Vector\_of\_StarsGiveawayOption](/API_docs/types/StarsGiveawayOption.html)

### Can userbots use this method: **YES**

### Can bots use this method: **NO**


### MadelineProto Example ([now async for huge speed and parallelism!](https://docs.madelineproto.xyz/docs/ASYNC.html)):


```php
if (!file_exists('madeline.php')) {
    copy('https://phar.madelineproto.xyz/madeline.php', 'madeline.php');
}
include 'madeline.php';

$MadelineProto = new \danog\MadelineProto\API('session.madeline');
$MadelineProto->start();

$Vector_of_StarsGiveawayOption = $MadelineProto->payments->getStarsGiveawayOptions();
```

