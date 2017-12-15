# Cranleigh Slacker

## Installation
Install this using composer:
```
composer require fredbradley/cranleigh-slacker
```

## Usage

``` 
require_once 'vendor/autoload.php';
$slacker = new FredBradley\CranleighSlacker\Slacker();
$slacker->setWebhook("<SLACK WEBHOOK>")
        ->setRoom("<SLACK ROOM>")
        ->setUsername("Choose a Username");

$slacker->post("Write your post here");

```
