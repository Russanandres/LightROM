# LightROM
# Only for Nexus 5 *hammerhead* and Nexus 4 *mako*!!
I haven't developed or ported any Lightrom before. This is my own project. All matches (including in the rom name) are random. Don't confuse with Adobe Lightroom! **You are on the page with Android AOSP/CM firmware/rom for phones!**
 
Completely stripped down ROM based on CyanogenMod 11. Almost all applications are cut out. Only the settings, music player, terminal and Titanium Backup remained. In the case of the ULTRA version - only the settings. You can install applications via ADB.
# Table of contents:
- [Описание на русском языке](https://github.com/Russanandres/LightROM#lightrom-2)
- [Weight](https://github.com/Russanandres/LightROM#zip-weight-on-last-readme-update)
- [Who needs it?](https://github.com/Russanandres/LightROM#who-needs-this-rom-is-it-for-me)
- [Then is the release?](https://github.com/Russanandres/LightROM#when-is-the-release)
- [Supported devices right now.](https://github.com/Russanandres/LightROM#supported-devices-right-now)
- [Apps](https://github.com/Russanandres/LightROM#apps-built-in)
- [Bugs](https://github.com/Russanandres/LightROM#bugs)
- [Q&A](https://github.com/Russanandres/LightROM#qa)
- [Other phones table](https://github.com/Russanandres/LightROM#all-devices-that-have-a-chance-to-get-lightrom)
## Zip weight (*on last readme update*)
- Cyanogenmod 11 - 260mb
- Lightrom - 163mb
- Lightrom ULTRA - 161mb
### Weight /system folder in zip
- Cyanogenmod 11 - 380mb
- Lightrom - 288mb
- Lightrom ULTRA - 285mb

about 100mb savings!
## Who needs this rom? Is it for me?
Most likely no. For people who use youtube, twitter and so on, that is, ordinary people do not need it. If you want an iPod-like music player or just a video player. You don't like a lot of programs installed on your device or you just want multirom rom to test programs. Then it is most likely for you, but be aware that there are a lot of bugs here.
## When is the release?
The release for Nexus 5 hammerhead version 1.0 is already out. For the Nexus 4, nothing really has been done. For S2, development has just started based on cm9 (cm7 on my phone just gives a bootloop)
### How well does the release work for the Nexus 4?
Yes, development for the Nexus 4 has begun. Since the CM firmware is different, some settings from the nexus 4 are missing in the nexus 5. There are fewer bugs, except for the fatal one. The back button doesn't work.
## Supported devices right now.
This rom at this time **support for Nexus 5 *Hammerhead* and Nexus 4 *Mako* only (n4 in development)!!!!! THE AUTHOR IS NOT RESPONSIBLE FOR A DAMAGED DEVICE!!!!** (although during installation you can hardly brick it, but believe me, it’s better not to try)
### Porting?
Maybe.
If it does, then first on nexus devices (nexus 10 and 9) and on Samsung devices (S2, S3, S7390, S5363). I'm not sure about others, I do it myself on my own devices.
## Apps built-in
### LightROM
| Apps       |                    |
| ---------- | ------------------ |
| Launcher        | Text launcher |
| Settings        | Standart      |
| Music player    | HiKi player   |
| Titanium backup | Lite 8.4.0.2  |
| Terminal        | 1.0.62        |
### ULTRA
| Apps     |               |
| -------- | ------------- |
| Launcher | Text launcher |
| Settings | Standart      |
## Bugs
Oh yeah. Bugs here are just a huge amount. Imagine all the people on earth (about 8 billion, right?) and multiply by 2. That will be the total number of bugs. Jokes aside, here are the known issues:
1. NFC - Partial work
2. Lockscreen - Can't set screen lock
3. Notification curtain - some shortcuts lead to system inoperability and reinstallation is required
4. Settings - Some items are throwing an error. (I know the fix, but let the rom be 1MB smaller)
5. Wallpapers - they are, but they write an error during installation. To fix it yourself, install the APK from cm11
6. Battery percentage - Something strange. Different from the real values.
#### LightromULTRA bugs:
1. All 😅
## Q&A
- Q - batus built in?
- A - No, lol.
- 
- Q - How do I know which release to download?
- A -

| Parts      | Designation                               |
| ---------- | ------------------------------------------|
| N5-1.0 NC1 | Example                                   |
| N5         | Model designation. (N5, N4, S2, A369 etc) |
| 1.0        | ROM version. (1.0, 1.1, 2.154 etc)        |
| NC1        | ROM codename (NC, Operatify etc)          |

- 
- Q - CM7/8/9/10/12/13/14? LinageOS?
- A - [Click there](https://github.com/Russanandres/LightROM#all-devices-that-have-a-chance-to-get-lightrom)
- 
- Q - X86 arch?
- A - 90% NO. Only if there is a desire. And who needs a neutered cyanogenmod on a PC?
- 
- Q - Anything other than Lightrom based and Ultra?
- A - Yes. There will be an extended release (LightromEXtented?) where there will be a calculator, a camera and similar necessary things.
- A - As well as the Debug version (LightROM Debug) filled with various debugging features. It will be released of course.

## All devices that have a chance to get LightROM:
| CM version     | Device                                                             | In development?    |
| -------------- | ------------------------------------------------------------------ | ------------------ |
| cm6 and below  | no information yet                                                 | No                 |
| cyanogenmod 7  | Galaxy S2, S5363                                                   | As soon as i can   |
| cyanogenmod 8  | I would like to, but there is no information yet                   | No                 |
| cyanogenmod 9  | Galaxy S2/S3.                                                      | Galaxy S2 (Freezed)|
| cyanogenmod 10 | Galaxy S2/S3, Nexus4/10, Lenovo A369i                              | No                 |
| cyanogenmod 11 | Galaxy S2/S3, Nexus4/5/10?, Galaxy S7390, Lenovo A369i             | Nexus 4, Nexus 5   |
| cyanogenmod 12 | Galaxy S2/S3, Nexus4/5/10, Lenovo A369i                      | No                 |
| cyanogenmod 13 | Galaxy S2/S3, mi4c, Nexus4/5/9/10, Lenovo A369i                    | No                 |
| cyanogenmod 14 | Galaxy S2/S3, mi4c, Nexus4/5/9/10                                  | No                 |
| LinageOS 14+   | Galaxy S2/S3, mi4c, Nexus4/5/5X/9/10?, redmi note 9 pro, Lenovo A369i | No                 |

The list will probably be replenished as I own devices. Devices for which I have already released a port and sold them, the firmware will not be updated. I want to myself and most likely I will buy a line of nexus smartphones and will mainly do this mod on them.


- ***Russian***

- ***description***

- ***below***


# LightROM
# Только для Nexus 5 *hammerhead* и Nexus 4 *mako*!!
**Я не разрабатывал и не портировал любой Lightrom раньше. Это мой собственный проект. Все совпадения (в том числе в названии) случайны. Не путайте с Adobe Lightroom! Вы находитесь на странице с Android AOSP/CM прошивкой для телефонов!** 

Полностью урезанный ROM на базе CyanogenMod 11. Вырезаны почти все приложения. Остались только настройки, музыкальный плеер, терминал и Titanium Backup. В случае версии ULTRA - только настройки. Можно устанавливать приложения через ADB. 
# Оглавление:
- [English readme](https://github.com/Russanandres/LightROM#lightrom)
- [Вес](https://github.com/Russanandres/LightROM#%D0%B2%D0%B5%D1%81-%D0%B0%D1%80%D1%85%D0%B8%D0%B2%D0%B0-%D0%BD%D0%B0-%D0%BF%D0%BE%D1%81%D0%BB%D0%B5%D0%B4%D0%BD%D0%B5%D0%B5-%D0%BE%D0%B1%D0%BD%D0%BE%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5-readme)
- [Кому это надо?](https://github.com/Russanandres/LightROM#%D0%BA%D0%BE%D0%BC%D1%83-%D0%BD%D1%83%D0%B6%D0%BD%D0%B0-%D1%8D%D1%82%D0%B0-%D0%BF%D1%80%D0%BE%D1%88%D0%B8%D0%B2%D0%BA%D0%B0-%D0%BE%D0%BD%D0%B0-%D0%B4%D0%BB%D1%8F-%D0%BC%D0%B5%D0%BD%D1%8F)
- [Когда релиз?](https://github.com/Russanandres/LightROM#%D0%BA%D0%BE%D0%B3%D0%B4%D0%B0-%D1%80%D0%B5%D0%BB%D0%B8%D0%B7)
- [Поддерживаемые сейчас устроиства](https://github.com/Russanandres/LightROM#%D0%BF%D0%BE%D0%B4%D0%B4%D0%B5%D1%80%D0%B6%D0%B8%D0%B2%D0%B0%D0%B5%D0%BC%D1%8B%D0%B5-%D1%81%D0%B5%D0%B9%D1%87%D0%B0%D1%81-%D1%83%D1%81%D1%82%D1%80%D0%BE%D0%B8%D1%81%D1%82%D0%B2%D0%B0)
- [Программы](https://github.com/Russanandres/LightROM#%D0%B2%D1%81%D1%82%D1%80%D0%BE%D0%B5%D0%BD%D0%BD%D1%8B%D0%B5-%D0%BF%D1%80%D0%BE%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D1%8B)
- [Баги, дюпы, глитчи](https://github.com/Russanandres/LightROM#%D0%B1%D0%B0%D0%B3%D0%B8-%D0%BF%D1%80%D0%BE%D0%B1%D0%BB%D0%B5%D0%BC%D1%8B-%D0%BD%D0%B5%D0%B4%D0%BE%D1%87%D1%91%D1%82%D1%8B)
- [Вопрос-Ответ](https://github.com/Russanandres/LightROM#%D0%B2%D0%BE%D0%BF%D1%80%D0%BE%D1%81-%D0%BE%D1%82%D0%B2%D0%B5%D1%82)
- [Таблица будущих поддерживаемых устроиств.](https://github.com/Russanandres/LightROM#%D0%B2%D1%81%D0%B5-%D1%83%D1%81%D1%82%D1%80%D0%BE%D0%B8%D1%81%D1%82%D0%B2%D0%B0-%D0%BA%D0%BE%D1%82%D0%BE%D1%80%D1%8B%D0%B5-%D0%B8%D0%BC%D0%B5%D1%8E%D1%82-%D1%88%D0%B0%D0%BD%D1%81-%D0%BF%D0%BE%D0%BB%D1%83%D1%87%D0%B8%D1%82%D1%8C-lightrom)
## Вес архива (*на последнее обновление readme*)
- Cyanogenmod 11 - 260мб
- Lightrom - 163мб
- Lightrom ULTRA - 161мб
### Вес папки /system в архиве
- Cyanogenmod 11 - 380мб
- Lightrom - 288мб
- Lightrom ULTRA - 285мб

Экономия около 90мб в сравнении с cm!
## Кому нужна эта прошивка? Она для меня?
Скорее всего нет. Для людей кто пользуется youtube, twitter и тд, тоесть обычных людей она не нужна. Если вы хотите музыкальный плеер на подобии iPod или только видеопроигрыватель. Вы не любите много программ установленных на ваше устроиство или просто хотите прошивку в multirom для теста программ. Тогда оно скорее всего для вас, но учтите, здесь очень много багов.
## Когда релиз?
Релиз для Nexus 5 hammerhead версии 1.0 уже есть. Для Nexus 4 толком ничего не сделанно. Для S2 разработка только начата на основе cm9 (cm7 на моём телефоне просто выдаёт бутлуп)
## Как хорошо релиз работает для Nexus 4?
Да, разработка для Nexus 4 начата. Так как CM прошивки разные, то некоторые настройки из nexus 4 отсутствуют в nexus 5. Багов меньше, за исключением фатального. Кнопка назад не работает.
## Поддерживаемые сейчас устроиства.
В настоящее время **поддерживается только Nexus 5 *Hammerhead* и Nexus 4 *Mako* (n4 в разработке)!!!!! АВТОР НЕ НЕСЕТ ОТВЕТСТВЕННОСТИ ЗА ПОВРЕЖДЕННОЕ УСТРОЙСТВО!!!!** (хотя при установке его вряд ли можно окирпичить, но поверьте, лучше и не пробовать)
### Портирование?
Возможно.
Если это и будет, то первые устроиства будут из линейки Nexus (nexus 10 и 9) и устроиства Samsung (S2, S3, S7390, S5363). Я не уверен насчёт остальных устроиств, так как я всё делаю на своих личных и вашего телефона у меня может просто не быть.
## Встроенные программы
### LightROM
| Программы  |                      |
| ---------- | -------------------- |
| Лаунчер           | Text launcher |
| Настройки         | Стандартные   |
| Музыкальный плеер | HiKi player   |
| Titanium backup   | Lite 8.4.0.2  |
| Терминал          | 1.0.62        |
### ULTRA
| Программы |               |
| --------- | ------------- |
| Лаунчер   | Text launcher |
| Настройки | Стандартные   |
## Баги, проблемы, недочёты.
О, да. Багов тут просто огромное количество. Представьте всех людей на земле (около 8 миллиардов, верно?) и умножьте на 2. Это будет общее количество проблем. Отбросив шутки, вот известные проблемы:
1. NFC - Время от времени
2. Экран блокировки - Нельзя поставить экран разблокировки. Сразу отключайте его.
3. Панель быстрых настроек - Некоторые пункты ведут к необратимому брику системы и потребуется переустановка прошивки.
4. Настройки - Некоторые пунты выдают ошибку. (Я знаю исправление, но прошивка будет чуть больше весить)
5. Обои - Живые обои выдают ошибку. Нужно самостоятельно ставить APK фаил с обоями.
6. Проценты батареи - Отличаются от реальных значений. Зачастую сильно.
#### Баги LightromULTRA:
1. Всё 😅
## Вопрос-Ответ
- Q - Batus встроен?
- A - Нет конечно)
- 
- Q - Как мне понять какую версию качать?
- A - 

| Части      | Обозначение                                       |
| ---------- | ------------------------------------------------- |
| N5-1.0 NC1 | Пример                                            |
| N5         | Обозначение модели. (N5, N4, S2, A369 и тд)       |
| 1.0        | Версия прошивки. (1.0, 1.1, 2.154 и тд)           |
| NC1        | Кодовое обозначение прошивки (NC, Operatify и тд) |

- 
- Q - CM7/8/9/10/12/13/14? LinageOS?
- A - [Нажми сюда](https://github.com/Russanandres/LightROM#%D0%B2%D1%81%D0%B5-%D1%83%D1%81%D1%82%D1%80%D0%BE%D0%B8%D1%81%D1%82%D0%B2%D0%B0-%D0%BA%D0%BE%D1%82%D0%BE%D1%80%D1%8B%D0%B5-%D0%B8%D0%BC%D0%B5%D1%8E%D1%82-%D1%88%D0%B0%D0%BD%D1%81-%D0%BF%D0%BE%D0%BB%D1%83%D1%87%D0%B8%D1%82%D1%8C-lightrom)
- 
- Q - X86 архитектура??
- A - 90% НЕТ. Только если будет желание, да и кому нужен кастрированный cm на пк?
- 
- Q - Какие нибудь ещё релизы кроме Lightrom base и Ultra?
- A - Да. Я хочу ещё несколько релизов. Один из них LEX (LightromEXtented?). Там будет камера, календарь, калькулятор и другие нужные вещи.
- A - А также версия Debug (LightROM Debug) наполненная разными функциями отладки. Она будет выложенна в открытый доступ конечно же.

## Все устроиства которые имеют шанс получить LightROM:
| Версия CM      | Устроиство                                                        | В разработке?       |
| -------------- | ----------------------------------------------------------------- | ------------------- |
| cm6 и ниже     | пока нет информации                                               | Нет                 |
| cyanogenmod 7  | Galaxy S2, S5363                                                  | Скоро               | 
| cyanogenmod 8  | Хотелось бы, но пока нет информации.                              | Нет                 |
| cyanogenmod 9  | Galaxy S2/S3.                                                     | Galaxy S2 (пока нет)|
| cyanogenmod 10 | Galaxy S2/S3, Nexus4/10, Lenovo A369i                             | Нет                 |
| cyanogenmod 11 | Galaxy S2/S3, Nexus4/5/10?, Galaxy S7390, Lenovo A369i            | Nexus 4, Nexus 5    |
| cyanogenmod 12 | Galaxy S2/S3, Nexus4/5/10, Lenovo A369i                     | Нет                 |
| cyanogenmod 13 | Galaxy S2/S3, mi4c, Nexus4/5/9/10, Lenovo A369i                   | Нет                 |
| cyanogenmod 14 | Galaxy S2/S3, mi4c, Nexus4/5/9/10                                 | Нет                 |
| LinageOS 14+   | Galaxy S2/S3, mi4c, Nexus4/5/5X/9/10, redmi note 9 pro, Lenovo A369i | Нет                 |

Список возможно будет пополнятся по мере владения мной устроиств. Устроиства для которых я уже выпустил порт и продал их, прошивка обновлятся не будет.
Я хочу сам и скорее всего буду покупать линейку сматрфонов nexus и премущественно на них буду делать этот мод, и там соответвественно будет и LinageOS и cm12/13/14+
