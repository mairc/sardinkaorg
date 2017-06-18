---
title: Основы GCS. Часть 0
date: 2016-09-20 15:36
update: 2016-09-20 15:36
---

# Основы GCS. Часть 0

...в которой герой приручил дракона и обучил принцессу своему языку.

В этой части мы установим Java и GCS[^gcs], а также русифицируем его. 

Или можете скачать готовый перевод:

- [Windows 64bit](https://sardinka.org/files/gcs-windows-64.zip); 
- [Windows 32bit](https://sardinka.org/files/gcs-windows-32.zip); 
- [macOS](https://sardinka.org/files/gcs-mac.zip);
- [Linux 64bit](https://sardinka.org/files/gcs-linux-64.zip);
- [Linux 32bit](https://sardinka.org/files/gcs-linux-32.zip). 

Если вы уже сделали это переходите к [Части один][l-part1], где мы начнем создавать нового персонажа.

## Установка Java

Сначала нам понадобится скачать и установить Java. Переходим на [официальный сайт Java][l-java]:

[![Сайт java.com][i-java]][l-java]

<!-- more -->

Нажимаем на большую красную кнопку «[Free Java Download][l-jdownload]». Далее подтверждаем сохранение файла[^file], ждем пока он загрузится. После чего запускаем его и проходим ряд шагов:

![Java Setup — Welcome][i-jwelcome]

Нажимаем «Install».

![Java Setup — Progress][i-jprogress-s]

Ждем.

![Java Setup — Peogress ¼][i-jprogress]

Всё ещё ждём.

![Java Setup — Complete][i-jprogress-c]

Установка успешно завершена, нажимаем «Close».

## Установка GURPS Character Sheet

Заходим на [сайт программы GCS][l-gcs]: 

[![Imgur][i-gcs]][l-gcs]

И нажимаем соответствующую вашей операционной системе иконку[^os]. Ждем загрузки файла. После чего находим его в проводнике[^path] нажимаем ПКМ → Распаковать всё → Распаковать → Заходим в распакованную папку → Находим «gcs.exe» → Запускаем:

[![Кликабельно][g-unzip]][g-unzip]

Кликабельно[^click].

Все работает, отлично!

## Русификация GCS

После этого можно приступить к русификации. Для этого зайдем в группу [vk.com/gurpsvk][l-gurpsvk] → [Обсуждения][l-gvk-o] → [Перевод Gurps Character Sheet][l-vktop]:

[![GURPSvk – Перевод Gurps Character Sheet][i-vktop]][l-vktop]

P.S. Не забываем благодарить [Станислава Малуша][l-stas] за перевод.

Cкачиваем последнюю версию файла "[Library.rar][l-rar]" → Распаковываем[^7z] → Копируем содержимое в папку GCS с заменой:

[![Распаковка Library.rar][g-rar]][l-grar]
 
[![Окно программы GCS с русскими библиотеками][i-fin]][i-fin]

Поздравляю, вы установили и русифицировали Gurps Character Sheet. В следующих частях мы научимся создавать нового персонажа с помощь готовых библиотек навыков/преимуществ, а также создать свои навыки/преимущества и снаряжение. 

Keep calm and carry on.

P.S На некоторых версиях Firefox есть странный баг: [![ris-gif]][ris-gif] Он как-то криво масштабируются gif'ки; если у вас также то, открывайте или полноразмерную картинку или воспользуйтесь другим браузером.



[^gcs]: Gurps Character Sheet;
[^file]: В моем случаи это “jre-8u51-windows-x64.exe”;
[^os]: Windows 64-bit в моем случае;
[^path]: У меня это “/User/Downloads”;
[^click]: Гифки и картинки кликабельны;
[^7z]: Я использую бесплатный open source архиватор [7-zip](http://www.7-zip.org/download.html).

[l-part0]:https://sardinka.org/gcs/gcs-0/
[l-part0#java]:https://sardinka.org/gcs/gcs-0/#java
[l-part0#gcs]:https://sardinka.org/gcs/gcs-0/#gcs
[l-part0#rus]:https://sardinka.org/gcs/gcs-0/#rus
[l-part1]:https://sardinka.org/gcs/gcs-1/
[l-part2]:https://sardinka.org/gcs/gcs-2/

[ris-gif]:http://i.imgur.com/NpuwWpu.png
[l-java]:https://java.com/en/download
[l-jdownload]:https://java.com/inc/BrowserRedirect1.jsp?locale=ru
[l-gcs]:http://gurpscharactersheet.com
[l-unzip]:http://i.imgur.com/kJlmzR4.gifv
[l-gurpsvk]:https://vk.com/gurpsvk
[l-gvk-o]:https://vk.com/board3656533
[l-vktop]:https://vk.com/topic-3656533_30663617
[l-stas]:https://vk.com/masoku
[l-rar]:https://cloud.mail.ru/public/i2dMPUF9fuL6/Library.rar
[l-grar]:http://i.imgur.com/anqgwf0.gifv
[l-ask]:http://mairc.tk/ask
[l-7z]:http://www.7-zip.org/download.html

[i-java]:http://i.imgur.com/uBS75dt.png "Java.com"
[i-jwelcome]:http://i.imgur.com/VoaF4hD.png "Java Setup - Welcome"
[i-jprogress-s]:http://i.imgur.com/KeKckae.png "Java Setup - Progress"
[i-jprogress]:http://i.imgur.com/Ze6LekA.png "Java Setup - Progress"
[i-jprogress-c]:http://i.imgur.com/SKVGRdG.png  "Java Setup - Complete"
[i-gcs]:http://i.imgur.com/3Jk35vn.png "gurpscharactersheet.com"
[i-vktop]:http://i.imgur.com/sxs5Xhl.png "VK - Перевод Gurps Character Sheet"
[i-fin]:http://i.imgur.com/9GM8b4L.png "GUPRS Workspace"

[g-unzip]:http://i.imgur.com/kJlmzR4.gif
[g-rar]:http://i.imgur.com/anqgwf0.gif


