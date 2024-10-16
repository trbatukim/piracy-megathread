## İçindekiler

1. [İşe Yarar Yazılımlar/Eklentiler](#ise-yarar-yazilimlar)
2. [Oyun Siteleri](#oyun-siteleri)
   1. [Torrent Siteleri](#torrent-siteleri)
   2. [DDL (Direkt indirme) Siteleri](#ddl-siteleri)
   3. [Oyun Arama Motorları](#oyun-arama-motorlari)
   4. [Repack Siteleri](#repack-siteleri)
3. [Çizgi Roman Siteleri](#cizgi-roman-siteleri)
4. [Emülatörler](#emulatorler)
5. [ROM Siteleri](#rom-siteleri)
6. [Denuvo Problemi](#denuvo)
7. [Windows/Office Aktifleştirme](#mas)
8. [Dikkat Edilmesi Gerekenler](#dikkat-edilmesi-gerekenler)
   1. [Güvenilmez Siteler](#guvenilmez-siteler)
   2. [Güvenilmez Korsanlar](#guvenilmez-korsanlar)
   3. [Güvenilmez Yazılımlar](#guvenilmez-yazilimlar)

## İşe yarar yazılımlar/eklentiler <a name="ise-yarar-yazilimlar"></a>

1. Firefox + uBlock Origin + Wavefox

İnternette reklamsız ve anonim gezmenin en kolay ve iyi yollarından biri (Benim kişisel tercihim). Wavefox, Firefox için önceden hazırlanmış bir CSS dosyası. Firefox'un UI hoşunuza gitmezse veya bazı küçük değişikler yapmak istiyorsanız fakat CSS yazmayı bilmiyorsanız kullanabilirsiniz. 

- [Firefox](https://www.mozilla.org/tr/firefox/new/)
- uBlock Origin
  - [Chrome/Brave/Edge/Chromium için](https://chromewebstore.google.com/detail/ublock-origin/cjpalhdlnbpafiamejdnhcphjbkeiagm)
  - [Firefox için](https://addons.mozilla.org/tr/firefox/addon/ublock-origin/)
- [Wavefox](https://github.com/QNetITQ/WaveFox)

2. [AdGuard DNS](https://adguard-dns.io/tr/public-dns.html#:~:text=A%C4%9F%20alt%C4%B1nda%20Ayarlar%20%C3%B6%C4%9Fesini%20se%C3%A7in,ard%C4%B1ndan%20DNS%20Ayarlar%C4%B1%20%C3%B6%C4%9Fesini%20se%C3%A7in.&text=AdGuard%20DNS%2C%20reklamlar%C4%B1%20ve%20izleyicileri%20engeller.,-Non%2Dfiltering%20sunucular)

Bilinen reklam sevrerlarını engelleyerek o modeme bağlı olan cihazlarda reklamları engeller.<br/>Aynı zamanda cihazın kendisine de kurulabilir.

3. FastForward

Kısaltılmış linklerin direkt göndermeye çalıştığı siteye yönlendirerek gizliliği korumaya yardımcı olur.

- [Firefox için](https://addons.mozilla.org/en-US/firefox/addon/fastforwardteam/)
- [Chrome/Brave/Edge/Chromium için](https://chromewebstore.google.com/detail/fastforward/icallnadddjmdinamnolclfjanhfoafe)

4. [ProtonVPN](https://protonvpn.com/download)

**Türkiye'de sitesi zaman zaman yasaklanıyor o yüzden indirmekte ve çalıştırmakta sıkıntı çekebilirsin. Böyle bir sorun yaşarsanız bir sonraki hizmeti kullanın.** Kullanması bedava, hızı fena değil, Türkiye'de yasak olan sitelere girebiliyor fakat bedava versiyonu P2P bağlantıları desteklemiyor. Yani torrent indirirken/yüklerken IP'ni saklamaz ama zaten Türkiye'de saklamana gerek yok. Windows dışında iOS, Android, macOS, Linux için de uygulaması bulunuyor.

5. [CroxyProxy](https://www.croxyproxy.com/)

VPN kurmaya/açmaya üşeniyorsanız yasaklı websitelere girmek için kullanılabilecek bir proxy servisi. ProtonVPN kurmaya karar verdiyseniz sitesine erişmek için kullanılabilir.

6. [qBitTorrent](https://www.qbittorrent.org/download)

Benim kullandığım torrent clientı. μTorrent'ten daha güvenli olması dışında aman aman bir ekstrası yok. Yine de geçmeni tavsiye ederim ama sana kalmış.

7. HEVC Video Uzantıları

Windows bazı fotoğraf ve video türlerini açabilmek için sizden HEVC Video Uzantılarını satın almanızı isteyebilir. HEVC Video Uzantılarını bedavaya elde etmek için tek yapmanız gereken [Microsoft Store - Generator Project](https://store.rg-adguard.net/) sitesine aşağıdaki linki yapıştırmak ve en altta çıkan (yani boyutu en büyük olan) dosyayı indirerek kurmak.

```
https://www.microsoft.com/store/productId/9N4WGH0Z6VHQ
```

8. [GoodbyeDPI](https://github.com/ValdikSS/GoodbyeDPI)

Türkiye'de veya yaşadığınız herhangi bir yerde yasaklı sitelere girmek için kullanılan bir gizlilik programı. Bir kere kurduktan sonra her bilgisayarı açışınızda çalıştırmanız gerekmez. VPN'lerin aksine hız kaybınız olmaz. Kurulum için ya başlıktaki linkten en yeni sürümü indirin ya da techolay forumlarında alp15eren tarafından 0.2.3rc3-2 sürümü üzerine hazırlanmış [Türkiye için özel ayarlanmış versiyonunu](https://drive.google.com/drive/folders/1xmWMRroUWR-oAUsKkFFylnTIfApxbSuV?usp=sharing) indirin (Benim tercihim ikincisi). Sistemi kurduktan sonra dosyanın yerini değiştiremeyeceksiniz o yüzden sonradan yerini değiştirmek istemeyeceğiniz bir yere koyun (Örn: C:\Users\PC\Documents\GoodbyeDPI). Dosyayı çıkarttıktan sonra içindeki "service_install_turktelekom.cmd" (Normal versiyonunu kullanıyorsanız ismi direk "service_install.cmd") adlı dosyaya sağ tıklayarak yönetici olarak çalıştırın. Sistemin çalışması için DNS ayarlarınızı değiştirmeniz gerekmektedir (Önerim yukarıdaki ADGuard DNS fakat Cloudflare DNS de kullanabilirsiniz).

## Oyun Siteleri <a name="oyun-siteleri"></a>

### Torrent Siteleri <a name="torrent-siteleri"></a>

- [1337x](https://1337x.to/) - Mümkünse oyunlarınızı sadece bu kullanıcılar yüklediyse indirin: (cs.rin.ru'dan herhangi biri, 0xEMPRESS, anadius, DODI, FitGirl, JohnCena141 (Linux), KaOsKrew, s7on3r, TinyRepacks).
- [EMPRESS Releases](https://telegra.ph/empress-biography-07-15)
- [RuTor](http://www.rutor.info/) - Sadece Chovka ve FitGirl'den indirin
- [RuTracker](https://rutracker.org/)
- [MacTorrents](https://www.torrentmac.net/) - macOS
- [Rustorka](http://rustorka.com/)
- [Tapochek](https://tapochek.net/index.php)

### DDL Siteleri <a name="ddl-siteleri"></a>

**Old/Retro PC Oyunları**

**Çoğu eski oyun kaynağı güvenilir olsa da bu sitelerden oyun indirirken dikkat edin!**

- [Archive.org - ClassicPCGames](https://archive.org/details/classicpcgames)
- [MyAbandonware](https://www.myabandonware.com/)
- [OldGamesDownload](https://oldgamesdownload.com/)

**Modern PC Oyunları**

- [CS.RIN.RU - Steam Underground Community](https://cs.rin.ru/forum/) - Başka sitelerde aradığını bulamazsan buraya bakabilirsin, hesap açman gerekiyor, çoğunlukla Rusça o yüzden Google Translate kullansan işine gelir. [Tor linki](http://csrinrutkb3tshptdctl5lyei4et35itl22qvk5ktdcat6aeavy6nhid.onion/forum)
- [CS.RIN.RU - GOG Games Complete Collection](https://cs.rin.ru/forum/viewtopic.php?f=38&t=136823)
- [DownloadHa](https://www.downloadha.com/category/%d8%a8%d8%a7%d8%b2%db%8c-%da%a9%d8%a7%d9%85%d9%be%db%8c%d9%88%d8%aa%d8%b1-pc-computer-game/) - Google Translate kullan.
- [G4U](https://g4u.to/)
- [GLOAD](https://gload.cc/)
- [Gamesdrive](https://gamesdrive.net/)
- [GOG Games](https://www.gog-games.to/) | [Tor linki](http://goggamespyi7b6ybpnpnlwhb4md6owgbijfsuj6z5hesqt3yfyz42rad.onion/)
- [Online-Fix](https://online-fix.me/) - online fix/bypass'ler içindir, bazı oyunlarda multiplayer oynamanı sağlar.
- [Ovagames](http://www.ovagames.com/)
- [RLSBB](https://rlsbb.ru/)
- [SCNLOG.ME](https://scnlog.me/)
- [SteamRIP.com](https://steamrip.com/)
- [Torrminatorr Forums](https://torrminatorr.com/) - GOG/Linux oyunları için. Hesap açman gerekiyor.

**Diğer platformlar**

- [iPhoneCake](https://www.iphonecake.com/) - macOS ve iOS
- [AppKed](https://www.macbed.com/) - macOS
- [NXMAC](https://nxmac.com/) - macOS, aynı zamanda torrent de sunar. [Alternatif link](https://nmac.to/)
- [CMacked](https://cmacked.com/) - macOS
- [Mobilism](https://forum.mobilism.org/index.php) - Modlu android oyunları için, hesap açman gerek.
- [APKMirror](https://www.apkmirror.com/) - Direk Play Store'dan alınan Android APK'lar 
- [Zamunda](https://zamunda.net/) - Linux için. Hesap açman gerek. Oyun indirmek için "Банани" (Bananas) menüsüne gir ve "Linux Games" filtresine tıkla.

#### Diğer

- [UltimMC](https://github.com/UltimMC/Launcher) | [PollyMC](https://github.com/fn2006/PollyMC) (Prism Launcher Fork) | Legacy Launcher [(1)](https://llaun.ch/en) [(2)](https://ll4n.ru/) | [SKlauncher](https://skmedix.pl/) (İndirmek için adblockunuzu kapatınız) - Minecraft için.
- [Moriya Shrine](https://moriyashrine.org/) - Touhou oyunları için.
- [f95zone](https://f95zone.to/) - Visual Novel tarzı oyunlar / +18 *yetişkinlere yönelik* oyunlar.

### Oyun Arama Motorları <a name="oyun-arama-motorlari"></a>

- [Rezi](https://rezi.one/) - DDL Arama Motoru.
- [Özel Google Temelli Korsan Oyun Arama Motoru](https://cse.google.com/cse?cx=20c2a3e5f702049aa)
- [Hatt](https://github.com/FrenchGithubUser/Hatt) - DDL Arama Uygulaması.

### Repack Siteleri <a name="repack-siteleri"></a>

Repackçiler oyunları başka kaynaklardan alır, virüs olup olmadığını kontrol eder ve sıkıştırarak kendileri sunmaya başlarlar. Repackler sıkıştırıldıkları için internetten indirmeleri daha kolaydır fakat indikten sonra cihazın dosyayı çıkarması uzun sürebilir.

Linki olmayan kullanıcıların kendi siteleri yoktur ve forumlara yükleme yapmaktadırlar.

- [ARMGDDN](https://t.me/ARMGDDNGames) - Telegram grubu, VR oyunları da sunarlar.
- Chovka - [RuTor Profili](http://rutor.info/browse/0/0/1642915/0) | [Telegram](https://repack.info/)
- [CPG Repacks](https://cpgrepacks.site/) - Visual Novellar için / Anime / +18 *yetişkinlere yönelik* oyunlar.
- [DODI Repacks](https://dodi-repacks.site/) [(Alternatif link)](https://dodi-repacks.download/)
- [ElAmigos](https://elamigos.site/)
- [FitGirl Repacks](https://fitgirl-repacks.site/)
- [Gnarly Repacks](https://rentry.org/gnarly_repacks) - Retro oyunlar
- [KaOs Krew](https://kaoskrew.org/)
- [Kapital Sin](https://www.kapitalsin.com/forum/)
- [M4ckD0ge Repacks](https://m4ckd0ge-repacks.site/)
- Mr DJ
- R.G. Catalyst
- R.G. Mechanics
- R.G. Revenants
- [Tiny Repacks](https://www.tiny-repacks.win/)
- [Xatab](https://byxatab.com/)
- ZAZIX

## Çizgi Roman Siteleri <a name="cizgi-roman-siteleri"></a>

### DDL Siteleri

- [Get Comics](https://getcomics.org/)

### Online Okuma Siteleri

- [Read Comics Online](https://readcomicsonline.ru/)

## Emülatörler <a name="emulatorler"></a>

Emülatörler eski/başka bir cihaza ait olan oyunları çalıştırmak için kullanılan programlardır.

**NOT: Bu emülatörlerin bazıları BIOS dosyaları gerektirir ve * ile işaretlenmişlerdir.**

- [GameTechWiki](https://emulation.gametechwiki.com/) - The Emulation Wiki - Bazı emülatörler için lazım olan BIOS dosyalarını burada bulabilirsiniz.
- [ares](https://ares-emu.net/) * | [MAME](https://www.mamedev.org/index.php) * | [Mednafen](https://mednafen.github.io/) * | [RetroArch](https://www.retroarch.com/) * | [Delta (iOS için)](https://apps.apple.com/us/app/delta-game-emulator/id1048524688) * | [OpenEmu (macOS için)](https://openemu.org/) - Çoklu-sistem Emülatörleri
- [bsnes](https://github.com/bsnes-emu/bsnes) | [Snes9x](https://www.snes9x.com/) - SNES oyunları için.
- [Project64](https://www.pj64-emu.com/) | [RMG](https://github.com/Rosalie241/RMG) | [simple64](https://simple64.github.io/) - Nintendo 64 oyunları için.
- [Dolphin Emulator](https://dolphin-emu.org/) - GameCube / Wii oyunları için.
- [mGBA](https://mgba.io/) | [VBA-M](https://vba-m.com/) - GBA oyunları için.
- [DeSmuME](https://desmume.org/) | [melonDS](https://melonds.kuribo64.net/) - DS oyunları için.
- [Cemu](http://cemu.info/) - Wii U oyunları için.
- [Ryujinx](https://ryujinx.org/) * - Nintendo Switch oyunları için.
- [DuckStation](https://www.duckstation.org/) * | [ePSXe](https://www.epsxe.com/) * - PlayStation 1 oyunları için.
- [PCSX2](https://pcsx2.net/) * - PS2 oyunları için.
- [PPSSPP](https://www.ppsspp.org/index.html) - PSP oyunları için.
- [Vita3K](https://vita3k.org/) - PSVita oyunları için.
- [RCPS3](https://rpcs3.net/) - PS3 oyunları için.
- [Xemu](https://xemu.app/) * - original XBOX oyunları için.
- [Xenia](https://xenia.jp/) - XBOX 360 oyunları için.
- [KEGA Fusion](https://www.carpeludum.com/kega-fusion/) * - SEGA Genesis / Mega Drive oyunları için.
- [Mesen2](https://github.com/SourMesen/Mesen2) | [puNes](https://github.com/punesemu/puNES) - NES oyunları için.
- [Flycast](https://github.com/flyinghead/flycast) | [redream](https://redream.io/) - Dreamcast oyunları için.
- [Vice](https://vice-emu.sourceforge.io/) - Commadore 64 oyunları için

## ROM Siteleri <a name="rom-siteleri"></a>

ROMlar emülatörler aracılığıyla oynadığın oyunların dosya türünün genel ismidir.

- [r/Roms Megathread](https://r-roms.github.io/)
- [CDRomance](https://cdromance.com/)
- [Edge Emulation](https://edgeemu.net/)
- [Game-2U](https://game-2u.com/) - PS4 oyunları için (Reklamlı link kısaltıcılar için FastForward eklentisini kullanın)
- [Gnarly Repacks](https://rentry.org/gnarly_repacks)
- [Myrient](https://myrient.erista.me/)
- [NXBrew](https://nxbrew.com/) - Nintendo Switch
- [TheRomDepot](https://theromdepot.com/)
- [Vimm's Lair](https://vimm.net/?p=vault)
- [Ziperto](https://www.ziperto.com/)

## Denuvo Problemi <a name="denuvo"></a>

Denuvo kırılması inanılmaz zor bir korsanlık karşıtı program. Bu oyunların korsan versiyonlarını bulmak çok zordur ve bazen imkansızdır. Denuvo kırmayı bilen iki korsan vardır.

- 0xEMPRESS - Yeni Denuvo oyunlarını kırabilen tek lişi, pisliğin teki, arada bir trip atmak için oyun kırmayı kesiyor ama Denuvo'nun yeni versiyonlarını kırmayı bilen tek kişi o. O yüzden bükemediğin eli öpeceksin.
- Delusional - Denuvo'nun eski sürümlerini kırar. Daha yenidir, kırdığı çok bir oyun yoktur.

Kırılmış ve kırılmamış denuvo oyunlarının bir listesi aşağıdaki linkte bulunmaktadır:

- [r/CrackWatch](https://www.reddit.com/r/CrackWatch/comments/p9ak4n/crack_watch_games/)

## Windows/Office Aktifleştirme

### Microsoft Activation Scripts <a name="mas"></a>

Aşağıdaki kodu bir Powershell terminaline yapıştırarak Windows'unuzu veya Office uygulamalarını aktifleştirebilirsiniz.

```
irm https://get.activated.win | iex
```

## Dikkat Edilmesi Gerekenler <a name="dikkat-edilmesi-gerekenler"></a>

### Güvenilmez Siteler <a name="guvenilmez-siteler"></a>

Güvenilmez sitelerin bir listesi:

- IGG Games / PCGamesTorrents / LoadGames / GamesTorrents 
- SteamUnlocked / GOG Unlocked / ROMs Unlocked
- TLauncher
- Artık orijinal sahipleri tarafından yönetilmeyen siteler. Buna dahil olan siteler:
    - The Pirate Bay
    - RARBG olduğunu iddia eden her site
    - Kickass Torrents
- URL'sinde bir korsan grubu ismi bulunduran her site - KORSAN GRUPLARININ SİTELERİ OLMAZ! (Örnekler: CODEX, CPY, SKIDROW, HOODLUM, RELOADED, SiMPLEX, DARKSiDERS, PLAZA, etc. Bu grupların siteleri başkaları tarafından yönetilmektedir.)
- Google'a "bedava oyun indir", "cracked oyunlar", vb. yazarak bulduğunuz siteler. Google gerçek korsan oyun dağıtan siteleri filtreler. Bu YouTube için de geçerlidir.
- AGFY
- AimHaven
- Apunkagames
- BBRepacks
- Corepack
- Cracked-Games
- Crohasit
- Downloadly
- Game3rb 
- GameFabrique 
- kLauncher (minecraft)
- Nexus Games / WorldOfPCGames / steamrepacks / unlocked-games
- nosTEAM
- OceanOfGames / OceanOfAPKs
- PiviGames 
- PolyMC (minecraft launcher)
- RepackGame
- Seyter/Qoob 
- Wifi4games 

### Güvenilmez Korsanlar <a name="guvenilmez-korsanlar"></a>

Güvenilmez korsanların bir listesi:

- IGG Games / PCGamesTorrents / LoadGames / GamesTorrents
- The Pirate Bay sitesindeki herhangi bir üye
- anr285
- BBRepacks
- Cracked-games
- CrackingPatching
- CracksHash
- haxnode
- IGI30
- nosTEAM
- OceanOfGames / OceanOfAPKs 
- RepackGames
- SadeemAPK
- SadeemPC
- Seyter/Qoob
- VitaminX
- xGIROx

### Güvenilmez Yazılımlar <a name="guvenilmez-yazilimlar"></a>

- BitTorrent/μTorrent - Yapımcıları uygulamalarını reklamlar, trackerlar, ve BTC minerlarıyla dolduruyor. µTorrent'in son "güvenli" sürümü, v2.2.1, de eski olduğundan birçok güvenlik özelliğinden mahrum durumda.
- Herhangi "kırılmış" VPN.
- Avast
- Bitlord
- CCleaner
