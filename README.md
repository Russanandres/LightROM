# Lightrom-hammerhead
# Only for Nexus 5 *hammerhead* and Nexus 4 *mako*!!
I haven't developed or ported any Lightrom before. This is my own project. All matches (including in the rom name) are random. Don't confuse with Adobe Lightroom! **You are on the page with Android AOSP/CM firmware/rom for phones!**
 
Completely stripped down ROM based on CyanogenMod 11. Almost all applications are cut out. Only the settings, music player, terminal and Titanium Backup remained. In the case of the ULTRA version - only the settings. You can install applications via ADB or terminal (not tested).
# Table of contents:
[Описание на русском языке](https://github.com/Russanandres/Lightrom-hammerhead/edit/main/README.md#lightrom-hammerhead-1)
Weight
Who needs it?
When is the release?
Supported devices right now.
Bugs
Q&A
Other phones table
## Zip weight (*on last readme update*)
- Lightrom - 168mb
- Lightrom ULTRA - 162mb
### Weight system folder in zip
- Cyanogenmod 11 - 380mb
- Lightrom - 293mb
- Lightrom ULTRA - 287mb

about 90mb savings!
## Who needs this firmware? Is it for me?
Most likely no. For people who use youtube, twitter and so on, that is, ordinary people do not need it. If you want an iPod-like music player or just a video player. You don't like a lot of programs installed on your device or you just want multirom rom to test programs. Then it is most likely for you, but be aware that there are a lot of bugs here.
## When is the release?
Honestly, I do not know. Maybe I will delete this repository. Prerelease for Nexus 5 and alpha for Nexus 4 are now ready. As soon as I understand how to properly edit the system resources of APK files on linux, I will release the first release.
### What? Nexus 4 is being developed? How well does it work?
What? Nexus 4 is still there (contrary to the text below)? How well does it work?
Yes, development for the Nexus 4 has begun (although I haven't even released it for the nexus 5). Since the CM firmware is different, some settings from the nexus 4 are missing in the nexus 5. There are fewer bugs, except for the fatal one. The back button doesn't work.
## Supported devices right now.
This rom at this time **support for Nexus 5 *Hammerhead* and Nexus 4 *Mako* only (n4 in development)!!!!! THE AUTHOR IS NOT RESPONSIBLE FOR A DAMAGED DEVICE!!!!** (although during installation you can hardly brick it, but believe me, it’s better not to try)
### Porting?
Maybe.
If it does, then first on nexus devices (nexus 10 and 5X (maybe)) and on Samsung devices (S2, S3, S7390). I'm not sure about others, I do it myself on my own devices.
## Bugs
Oh yeah. Bugs here are just a huge amount. Imagine all the people on earth (about 8 billion, right?) and multiply by 2. That will be the total number of bugs. Jokes aside, here are the known issues:
1. NFC - Partial work
2. Lockscreen - Can't set screen lock
3. Notification curtain - some shortcuts lead to system inoperability and reinstallation is required
4. Settings - Some items are throwing an error. (I know the fix, but let the rom be 1MB smaller)
5. Wallpapers - they are, but they write an error during installation. To fix it yourself, install the APK from cm11
#### LightromULTRA bugs:
1. All 😅
## Q&A
- Q - batus built in?
- A - No, lol.
- 
- Q - CM7/8/9/10/12/13/14? LinageOS?
- A - 
- 
- Q - X86 arch?
- A - 90% NO. Only if there is a desire. And who needs a neutered cyanogenmod on a PC?
- 
- Q - Anything other than Lightrom based and Ultra?
- A - Yes. There will be an extended release (LightromEXtented?) where there will be a calculator, a camera and similar necessary things.

## All devices that have a chance to get LightROM:
- cm6 and below - no information yet
- cm7 - so far only Galaxy S2, but I have a little problem with it
- cm8 - I would like to, but there is no information yet
- cm9 - Galaxy S2/S3.
- cm10 - Galaxy S2/S3, mi4c?, Nexus4?, Galaxy S7390, Lenovo A369i
- cm11 - Galaxy S2/S3, mi4c?, Nexus4/5/10?, Galaxy S7390, Lenovo A369i
- cm12 - Galaxy S2/S3, mi4c, Nexus4/5/10, Lenovo A369i
- cm13 - Galaxy S2/S3, mi4c, Nexus4/5/10, Lenovo A369i
- cm14 - Galaxy S2/S3, mi4c, Nexus4/5/10, Lenovo A369i (will not be on cm)
- LinageOS+ - Galaxy S2/S3, mi4c, Nexus4/5/10?, redmi note 9 pro
The list will probably be replenished as I own devices. Devices for which I have already released a port and sold them, the firmware will not be updated.

I want to myself and most likely I will buy a line of nexus smartphones and will mainly do this mod on them.


# Lightrom-hammerhead
# Только для Nexus 5 *hammerhead* и Nexus 4 *mako*!!
**Я не разрабатывал и не портировал любой Lightrom раньше. Это мой собственный проект. Все совпадения (в том числе в названии) случайны. Не путайте с Adobe Lightroom! Вы находитесь на странице с Android AOSP/CM прошивкой для телефонов!** 

Полностью урезанный ROM на базе CyanogenMod 11. Вырезаны почти все приложения. Остались только настройки, музыкальный плеер, терминал и Titanium Backup. В случае версии ULTRA - только настройки. Можно устанавливать приложения через ADB или терминал (не проверял). 
# Оглавление:
[English readme](https://github.com/Russanandres/Lightrom-hammerhead/edit/main/README.md#lightrom-hammerhead-1)
Вес
Кому это надо?
Когда релиз?
Поддерживаемые сейчас устроиства
Баги, дюпы, глитчи
Вопрос-Ответ
Таблица будущих поддерживаемых устроиств.
## Вес архива (*на последнее обновление readme*)
- Lightrom - 168mb
- Lightrom ULTRA - 162mb
### Вес папки /system в врхиве
- Cyanogenmod 11 - 380mb
- Lightrom - 293mb
- Lightrom ULTRA - 287mb

Экономия около 90мб в сравнении с cm!
## Кому нужна эта прошивка? Она для меня?
Скорее всего нет. Для людей кто пользуется youtube, twitter и тд, тоесть обычных людей она не нужна. Если вы хотите музыкальный плеер на подобии iPod или только видеопроигрыватель. Вы не любите много программ установленных на ваше устроиство или просто хотите прошивку в multirom для теста программ. Тогда оно скорее всего для вас, но учтите, здесь очень много багов.
## Когда релиз?
Честно, я не знаю. Возможно я удалю этот репозиторий. Сейчас готов пререлиз для Nexus 5 и альфа для Nexus 4. Как только я пойму как правильно редактировать системные ресурсы APK файлов на linux, я выпущу первый релиз.
## Что? Nexus 4 всё же разрабатывается? Как хорошо оно работает?
Да, разработка для Nexus 4 начата (хоть я и не выпустил даже для nexus 5). Так как CM прошивки разные, то некоторые настройки из nexus 4 отсутствуют в nexus 5. Багов меньше, за исключением фатального. Кнопка назад не работает.
## Поддерживаемые сейчас устроиства.
В настоящее время **поддерживается только Nexus 5 *Hammerhead* и Nexus 4 *Mako* (n4 в разработке)!!!!! АВТОР НЕ НЕСЕТ ОТВЕТСТВЕННОСТИ ЗА ПОВРЕЖДЕННОЕ УСТРОЙСТВО!!!!** (хотя при установке его вряд ли можно окирпичить, но поверьте, лучше и не пробовать)
### Портирование?
Возможно.
Если это и будет, то первые устроиства будут из линейки Nexus (nexus 10 и 5X (возможно)) и устроиства Samsung (S2, S3, S7390). Я не уверен насчёт остальных устроиств, так как я всё делаю на своих личных и вашего телефона у меня может просто не быть.
## Баги, проблемы, недочёты.
О, да. Багов тут просто огромное количество. Представьте всех людей на земле (около 8 миллиардов, верно?) и умножьте на 2. Это будет общее количество проблем. Отбросив шутки, вот известные проблемы:
1. NFC - Время от времени
2. Экран блокировки - Нельзя поставить экран разблокировки. Сразу отключайте его.
3. Панель быстрых настроек - Некоторые пункты ведут к необратимому брику системы и потребуется переустановка прошивки.
4. Настройки - Некоторые пунты выдают ошибку. (Я знаю исправление, но прошивка будет чуть больше весить)
5. Обои - Живые обои выдают ошибку. Нужно самостоятельно ставить APK фаил с обоями.
#### Баги LightromULTRA:
1. Всё 😅
## Вопрос-Ответ
- Q - Batus встроен?
- A - Нет конечно)
- 
- Q - CM7/8/9/10/12/13/14? LinageOS?
- A - 
- 
- Q - X86 архитектура??
- A - 90% НЕТ. Только если будет желание, да и кому нужен кастрированный cm на пк?
- 
- Q - Какие нибудь ещё релизы кроме Lightrom base и Ultra?
- A - Да. Я хочу ещё несколько релизов. Один из них LEX (LightromEXtented?). Там будет камера, календарь, калькулятор и другие нужные вещи.

## Все устроиства которые имеют шанс получить LightROM:
- cm6 и ниже - пока нет информации
- cm7 - пока что только Galaxy S2, но у меня с ним небольшие проблемы
- cm8 - Хотелось бы, но пока нет информации.
- cm9 - Galaxy S2/S3.
- cm10 - Galaxy S2/S3, mi4c?, Nexus4?, Galaxy S7390, Lenovo A369i
- cm11 - Galaxy S2/S3, mi4c?, Nexus4/5/10?, Galaxy S7390, Lenovo A369i
- cm12 - Galaxy S2/S3, mi4c, Nexus4/5/10, Lenovo A369i
- cm13 - Galaxy S2/S3, mi4c, Nexus4/5/10, Lenovo A369i
- cm14 - Galaxy S2/S3, mi4c, Nexus4/5/10, Lenovo A369i (будет не на cm)
- LinageOS+ - Galaxy S2/S3, mi4c, Nexus4/5/10?, redmi note 9 pro
- Список возможно будет пополнятся по мере владения мной устроиств. Устроиства для которых я уже выпустил порт и продал их, прошивка обновлятся не будет.
Я хочу сам и скорее всего буду покупать линейку сматрфонов nexus и премущественно на них буду делать этот мод, и там соответвественно будет и LinageOS и cm12/13/14+
