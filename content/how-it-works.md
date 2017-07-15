---
title: "How It Works"
date: 2017-07-16T00:32:14+05:30
draft: false
type: page
---

##### Program

The signaller program is called **Polu**. It is written in PHP and runs using  **PHP 7.1** on **Ubuntu 16.04**.

##### Frequency

The signaller is started when I use my computer. I'm in the `GMT+05:30` timezone. So you must be seeing most of the signals during the working hours of this timezone.

The signals won't be send automatically. I analyse the market manually before sending it. What Polu does is pick needles from a haystack and I make a cloth for you after careful consideration.

##### Signal Selection

1. Using the exchange's API, information about all the markets are updated every 5 seconds
2. Going through each market, the rise in volume and prices are noted
3. Of them, the ones with the best price and volume are selected
4. These markets are again looked over manually and finally sent

{{< img src="/img/signaller.png" title="Polu dashboard from where the decision to send signals are made" >}}

