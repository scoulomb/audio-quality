# audio-quality

## 24 or 32 bits

- http://www.cochlea.eu/son#:~:text=La%20fr%C3%A9quence%20est%20le%20nombre,p%C3%A9riode%20en%20seconde%20(s). 
- https://www.laboiteconcept.com/fichier-audio-numerique-choisir-utilisation/
- https://blog.cobrason.com/2021/02/peut-on-entendre-une-vraie-difference-entre-un-fichier-en-qualite-cd-et-un-fichier-en-hi-res/

- https://www.qobuz.com/fr-fr/info/magazine-actualites/hi-fi-pratique/les-fichiers-studio-masters-c-est89767
- https://www.son-video.com/guide/tout-savoir-sur-la-norme-hi-res-audio
- https://blog.sonos.com/fr-fr/hi-res-audio-guide
- Denon throttle: https://www.homecinema-fr.com/forum/son-audio-amplificateurs-integres-homecinema/2020-denon-avc-x6700h-4700h-3700h-et-2700h-voir-post-1-t30105818-2295.html
- https://www.whathifi.com/advice/mqa-audio-what-it-how-can-you-get-it


MP3 quality
- https://lasonotheque.org/dossier-2-qualite-audio.html
- https://www.audiomountain.com/tech/audio-file-size.html

Screenshot phone


also vlc 32 bit in upnp + local?

power dvd -> dolby digital 
Use VLC as powerdvd hue issue due to protection 
but https://www.pcastuces.com/pratique/astuces/4818.htm
    and select good track in vlc

https://www.dolby.com/fr/musique/
whta is dolby atmos

https://www.maplatine.com/fr/content/322-comment-brancher-et-utiliser-son-dac-usb
ame exclusive mode in Amazon music
Do not select 32 bits: Unrecoverable playback error: Endpoint creation failed

IN COURSE + JM video in whatsapp

Actually quobuz is https://www.qobuz.com/fr-fr/album/if-you-wait-london-grammar/5060281616258 
 24-Bit 44.1 kHz - Stereo 
 
 Some are in 48khz https://www.qobuz.com/fr-fr/album/aventine-agnes-obel/5414939568176
 and 96
 and 176https://www.qobuz.com/fr-fr/album/redcar-les-adorables-etoiles-prologue-christine-and-the-queens/bmli1c01hksgb
 (swee filter)
 
 pay a 88 to try , compare mp3
 resync nas
 
 can see https://192.168.1.44:10443/general/general.html#
 if exclusive mode sampling rate == quality of sounf
 
 otherwise 88.z as configure wondows in windows property
 
 
and heos has samplerate 0f 96khz!!!
mediatheque @@55

nas sync new zik

http://www.traitement-signal.com/theoreme_d_echantillonnage_de_nyquist-shannon.php
https://www.headphonesty.com/2019/07/sample-rate-bit-depth-bit-rate/

https://sourdoreille.net/test-decoute-faites-vous-la-difference-entre-plusieurs-formats-audio/


****************
Amaazon MUSIC Unlimited 
> settings > Audio qulaity hd/uhd
example Petite Marie wich is avaialble in UHD 96khz/24 bits
si dans windows device quality is 88.2 il sortira le morcecau en 48khz/24 bits
See amazon-music-uhd-device-88.2

Denon UI will show

````
Sound Mode	Matrix
Input Signal	PCM
Sample Rate	88.2 kHz
Format	2/0/.0
````


il faut donc change en 96khz les audio settnifgs dans windows
amazon-music-uhd-device-96

we are playing at besy possible quality


Denon UI will show

````
Sound Mode	Matrix
Input Signal	PCM
Sample Rate	96 kHz
Format	2/0/.0
````

Addtional test with exclusive mode
Sadly exclusive mode keep windows preference of sahred mode for audio quality

Also if we select 176400 in windwos and try to play a song in 96 (here) in will not  work 
(tested same beahvir in exclusive mode or not)

select 192  works (exlcusive or not)

Denon UI will show (exclusive or not)

````
Sound Mode	Matrix
Input Signal	PCM
Sample Rate	192 kHz
Format	2/0/.0
````

This behavior is different from foobar which plays at optimal quality and ignore shaed mode preference


****************


quobuz wav file 
24*96000*2* => 4608 kbps seconds 
can find same rate asin foobar
and aproz size example of tack 1 which 4'04
4608*263*0.125 = 151488
4608*264*0.125 = 152064

and actaull size 144 MB (151,865,388 bytes)
