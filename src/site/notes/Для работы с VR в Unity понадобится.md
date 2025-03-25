---
{"dg-publish":true,"permalink":"/dlya-raboty-s-vr-v-unity-ponadobitsya/","tags":["gardenEntry"]}
---

`Много места на компе.`
`Пару часов на установку - настройку. Если установка пойдет с ошибками.`

1. Установить Unity Hub 
2. Зарегаться в Unity Hub
3. Установить Unity 6 ( последняя версия)
4. Загрузить и установить проект? 
5. `file - build profile - Android` - нужно скачать и установить 
	1. ![Pasted image 20250325132647.png](/img/user/Cache/Pasted%20image%2020250325132647.png) нужно скачать и установить 
-  у меня установка с пробуксовкой - Unity Android SDK Platforms - install filed 
	- дальше жмем - switch platform 
		- ![Pasted image 20250325135053.png](/img/user/Cache/Pasted%20image%2020250325135053.png)
6. `file - build profile - Android` - Build a Run
	- У меня с ошибкой.
		![Pasted image 20250325140022.png](/img/user/Cache/Pasted%20image%2020250325140022.png)
	- Качаю [Android Studio](https://developer.android.com/studio?hl=ru) что бы вручную поставить Android SDK Command Line Tools (то что он сам почему то не смог установить)
	- Юзаю [туториал](https://www.youtube.com/watch?v=oO0oXcWN03g)
	- Дополнительно установил - *Command-Line Tools* 
		![Pasted image 20250325145622.png](/img/user/Cache/Pasted%20image%2020250325145622.png)
		![Pasted image 20250325142744.png](/img/user/Cache/Pasted%20image%2020250325142744.png)
	-  Дополнительно установил - *CMake* ( у меня попросил 3.22.1) есть галочка - `show Package details` и тогда можно выбирать версию. 
	- Соглашаемся на все что будет предлагать установить или обновить.
	- У меня ушел на обновление андрод (больше 20 минут устанавливал)
7. Build a Run - компеляция моэет занять 10 - 20 мин.


