# bluetooth-tiktok-remote
I bough one of the many bluetooth remotes sold on aliexpress as tiktok remote, thinking it would emulate a keyboard.

Once I received it, I found that it emulates mouse movements instead, so I'd like to reprogram it.

I opened it but I found that the chip identification had been filed down.

[<img src="front.jpg" width="100" />](./front.jpg)

The oscillator is 24MHz and the silkscreen says "SD-F1-V1.1 2021.7.5."


on the back there is no useful identification either

[<img src="rear.jpg" width="100" />](./rear.jpg)

The device identifies itself as "Beauty-R1" and the seller says the chip is from Yizhao.

I couldn't find anything searching for the manufacturer, the bluetooth id  or the markings on the pcb.

# interceptor

Eventually I [identified the chip](https://github.com/olivluca/bluetooth-tiktok-remote/issues/1#issuecomment-1258535251) but I couldn't get hold of a development kit, so [I wrote a program](https://github.com/olivluca/beauty-r1-android-interceptor)
that intercepts the mouse movements and transforms them to keypresses.





