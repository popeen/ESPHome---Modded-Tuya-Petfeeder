
I don't like cloud services so when I got a Nedis (rebranded Tuya) pet feeder I went and looked for a way to localize it. This lead me to this awsome blogpost where kvvhost reverse engineers the same machine (under a different rebrand) and reflashes the esp chip inside it.
https://kvvhost-ru.translate.goog/2020/06/19/petoneer-nutri-smart-pet-feeder/?_x_tr_sl=auto&_x_tr_tl=en&_x_tr_hl=sv&_x_tr_pto=wapp

I didn't want to reflash it just in case I ever wanted to move over to local tuya or similar so I had a look at his documentation and code and then modified it to fit my needs.

This is the result. Instead of flashing the esp inside the feeder I flashed an esp32-cam and hooked it up in a similar way to kvvhost. I plan on doing a full writeup on the process soon but for now the code and his writeup will have to do if you are interested in replicating it.

I still need to cad a replacement cap so I can use the camera on the esp32-cam board but at least the code is ready for it.