# SupernaturalENG - Test Sürümü / Test Build

Supernatural dizisinden esinlenen bir Minecraft (Java, Fabric) modunun **test sürümü**. Bu depo yalnızca derlenmiş sürümü içerir; kaynak kod burada yoktur.
A **test build** of a Supernatural-inspired Minecraft (Java Edition, Fabric) mod. This repository contains only compiled releases, no source code.

## Gereksinimler / Requirements

- Windows, Minecraft Java Edition **26.2**, Minecraft Launcher (en az bir kez açılmış / opened at least once)
- **Java 25** (Minecraft Launcher'ın kendi Java'sı da olur / the launcher's bundled Java works too)

## Kurulum / Install

1. [Releases](../../releases/latest) sayfasından `SupernaturalENG-Test.zip` dosyasını indirin ve bir klasöre çıkarın.
   Download `SupernaturalENG-Test.zip` from Releases and extract it.
2. `Supernatural-Baslat.cmd` dosyasına çift tıklayın. Açılan pencerede **Kur / Güncelle**'ye basın.
   Double-click `Supernatural-Baslat.cmd`, then press **Kur / Güncelle** (Install / Update).
3. Kurucu Fabric Loader, Fabric API ve modu `.minecraft` klasörünüze kurar.
   The installer sets up Fabric Loader, Fabric API and the mod in your `.minecraft` folder.
4. Minecraft Launcher'da **fabric-loader-26.2** profilini seçip oynayın. Yeni dünyada **Supernatural: Hikâye** seçili kalsın.
   Pick the **fabric-loader-26.2** profile in the launcher. Keep **Supernatural: Hikâye** (Story) selected in a new world.

## Güncelleme / Updates

`Supernatural-Baslat.cmd` her açılışta en son sürümü kendisi indirir (SHA-256 doğrulamalı). Elle güncellemek: `java -jar supernaturaleng-0.1.0.jar --guncelle`.
The launcher fetches the newest release on every start (SHA-256 verified). Manual: `java -jar supernaturaleng-0.1.0.jar --guncelle`.

## Notlar / Notes

- Bu bir test sürümüdür; hatalar olabilir. Sorun görürseniz `.minecraft/logs/latest.log` dosyasını paylaşın.
  This is a test build and may contain bugs. If something breaks, share `.minecraft/logs/latest.log`.
- Kurucu yalnızca `maven.fabricmc.net`, `meta.fabricmc.net` ve bu deponun GitHub sürümlerine bağlanır; kimlik bilgisi göndermez.
  The installer connects only to `maven.fabricmc.net`, `meta.fabricmc.net` and this repository's GitHub releases; it sends no credentials.
- Kaldırmak için `.minecraft/mods` içindeki `supernaturaleng-*.jar` dosyasını silin. / To uninstall, delete `supernaturaleng-*.jar` from `.minecraft/mods`.

## Lisans ve atıf / License and attribution

© Tüm hakları saklıdır / All rights reserved. Bu sürüm yalnızca test amacıyla dağıtılır; yeniden dağıtım, değiştirme ve ticari kullanım izne tabidir.
Distributed for testing only; redistribution, modification and commercial use require permission.

Harita verisi / Map data: © OpenStreetMap contributors, ODbL 1.0 - openstreetmap.org/copyright. Yükseklik/Elevation: USGS 3DEP; arazi örtüsü/land cover: USGS NLCD (public domain).

Bu proje bağımsız bir hayran projesidir; Supernatural, Warner Bros. Entertainment'ın ticari markasıdır ve proje onunla ilişkili değildir. / This is an independent fan project, not affiliated with Warner Bros. Supernatural is a trademark of its owner.
