


<div align="center">

# PopIcon

<img src="https://github.com/user-attachments/assets/4ea0a7bb-7b7e-4715-80f6-691358eb7d6b"
     width="180" height="180" alt="PopIcon" />
<br/><br/>
<a href="../../releases/latest">
  <img src="https://img.shields.io/badge/Download-5%20MB-blue?style=for-the-badge" />
</a>
<a href="https://boosty.to/eukerka">
  <img src="https://img.shields.io/badge/Boosty-donate🙏-orange?style=for-the-badge" />
</a>
<a href="https://example.com">
  <img src="https://img.shields.io/badge/Site-PopIcon-black?style=for-the-badge" />
</a>
</div>


PopIcon is a lightweight and convenient Windows application that allows you to quickly customize the Recycle Bin icon. Apply the desired Recycle Bin icon quickly, without the need for manual configuration or changing [system settings](https://github.com/elmoiv/PopCat.exe).

# Download ⬇️


**Requirements**
- Windows 10 / 11
- .NET Framework 4.8

**Download**
- 👉 [Download latest release](../../releases/latest)     / [![Download](https://img.shields.io/badge/Download-5%20MB-blue?style=for-the-badge)](https://example.com/install-160mb) 



# **Key features** ✨
- Library: Choose from a built-in collection of funny icons for empty and full Recycle Bins.
- Your own icons: Upload your own .ico files and install them.
- Simplicity: Intuitive interface and one-click icon application.
- Return to default: You won't break the basic trash can icon. (Not that it's anything to brag about, but why not?) 

# **How to use it?** 🎨
1. Launch the app.
2. Select an icon from the library or click Choose custom icon to specify your own files for the empty and full trash cans.
3. Click Apply. Done!
![Desktop 20-01-2026 0-20-30](https://github.com/user-attachments/assets/c3882900-fd25-484b-a29a-38a494c63bba)

# How to create your own icon? 🛠️

For an example, you can check out [this video](https://youtu.be/wox4ytUFHrU?si=kqaeMKpSAPT1QjwX)

However, I will explain it. The author of the video ended up with a crooked, jumping icon — I want that if you make your own icons, you do it correctly.

The existing Recycle Bin icon changes, roughly speaking, only in that there is either no trash in it or there is trash — the positioning of the bin inside the icon is always the same, and the body of the bin is also always the same. A real feeling appears that the bin does not change the icon but gets filled or emptied — because there is zero difference in the bin’s body.

In our case, we will most often use cats, creatures, french fries, and nuggets.

I take this image as an example — it contains two instances of the cat, and even though there are small differences (Photoshop helps here: you overlay the open-mouth version onto the closed-mouth one and carefully remove unnecessary parts and adjust), they are identical.

1. In Photoshop, we create an empty layer with the specified resolution of 256x256 (transparent, in any way) <img width="313" height="568" alt="2026-01-20_02-01-52" src="https://github.com/user-attachments/assets/dbada679-c41d-406b-b4fb-def634b5f7ea" />

2. From our example image, we first cut out the closed-mouth version — remove the background from the cropped part, scale the closed-mouth cat (problems may occur when you try to fit the second cat), and get the finished first instance. Save it.

<details>
  <summary>2</summary>
  
https://github.com/user-attachments/assets/d30e5f32-3c20-4ac3-a799-0d4e7d13b19e

</details>

3. Working with the second icon, you create a new file with the same resolution and the same transparent layer. You perform the same manipulations, but now overlay the second cat on top of the first one to roughly estimate how smoothly and seamlessly “without jumps” the icon will change. Tried it? Remove the background (the previous cat) from the canvas and then save the second cat with the open mouth.
<details>
  <summary>3</summary>
  
https://github.com/user-attachments/assets/35bf9faf-8c3b-4059-987b-e214322e2567

</details>

4. And then — you need to convert your created .png images into .ico files using any online converter; if there is a choice of resolutions, be sure to select all of them. (16x16, 32x32, 48x48, 256x256)
This is required so that the Recycle Bin displays correctly in different cases. (How? This is explained in [this video](https://youtu.be/wox4ytUFHrU?si=kqaeMKpSAPT1QjwX))

!Note! — the icon that I made may not be completely seamless; you must definitely do better. If you do not have a second instance of the icon, you can safely ask any AI (I recommend ChatGPT) to generate a second instance with a very widely open mouth, and in about 70% of cases the AI will manage.

# Thanks 🙏
This project was inspired by the Pop Cat Bin utility by [dudetechitout](https://popcatbin.com/). Thanks to him for the great idea! 

# Русское описание - спойлер снизу

<details>
  <summary>открой спойлер</summary>



  PopIcon — это лёгкое и удобное приложение для Windows, которое позволяет быстро кастомизировать иконку корзины. Без необходимости [ручной настройки](https://github.com/elmoiv/PopCat.exe) и изменения системных параметров вручную вы можете быстро применить желаемую иконку.

# Установка ⬇️

**Требования/Рекомендации**
- Windows 10 / 11
- .NET Framework 4.8

**Установка**
- 👉 [Нажми чтобы установить](../../releases/latest)     / [![Download](https://img.shields.io/badge/Download-5%20MB-blue?style=for-the-badge)](https://example.com/install-160mb) 

# **Ключевые возможности** ✨
- Библиотека: Выбирайте из встроенной коллекции забавных иконок для пустой и полной Корзины.
- Свои иконки: Загружайте собственные файлы в формате .ico и устанавливайте их.
- Простота: Интуитивно понятный интерфейс и применение иконок в один клик.
- Возврат к стандарту: Вы не сломаете базовую иконку корзины. (Хотя тут нечем хвастаться, но почему нет?) 
# **Как пользоваться?** 🛠️
1. Запустите приложение.
2. Выберите иконку из библиотеки или нажмите Choose custom icon, чтобы указать свои файлы для пустой и полной корзины.
3. Нажмите Apply. Готово!
![Desktop 20-01-2026 0-20-30](https://github.com/user-attachments/assets/c3882900-fd25-484b-a29a-38a494c63bba)

# Как создать свою иконку? 🎨

Для примера вы можете ознакомиться с [этим видео](https://youtu.be/wox4ytUFHrU?si=kqaeMKpSAPT1QjwX) 

Однако я обьясню. У автора с видео получилась кривая иконка, прыгающая - я хочу чтобы если вы и делали собственные, то делали правильно. 

Существующая корзина иконки меняется грубо говоря лишь тем , что в ней либо мусора нет, либо он есть - а позиционирование корзины внутри иконки всегда одинаковое, и тело корзины тоже одинаково. Появляется реальное ощущение того, что корзина не меняет иконку а наполняется либо очищается - из за нулевого различия в теле корзины. 

В нашем случае мы чаще всего будем использовать котов, существ, картошек фри и наггетсов. 

Беру в пример эту картинку - в ней 2 экземляра кота, и хоть есть небольшие отличия(фотошоп в помощь, накладываете на закрытый рот открытый и аккуратно убираете ненужные части и корректируете), они одинаковы. 

1. В фотошопе мы создаем пустой слой c заданным разрешением 256х256 (прозрачный, любым способом) <img width="313" height="568" alt="2026-01-20_02-01-52" src="https://github.com/user-attachments/assets/dbada679-c41d-406b-b4fb-def634b5f7ea" />
2. С нашей картинки-примера вырезаем сначала закрытый рот - убираем фон с обрезанной части, растягиваем кота-закрытый рот(возможны проблемы, когда вы будете примерять второго кота) и получаем готовый экземляр номер один. Cохраняем.

<details>
  <summary>2</summary>
  
https://github.com/user-attachments/assets/d30e5f32-3c20-4ac3-a799-0d4e7d13b19e

</details>

3. Работая с второй иконкой, вы создаете новый файл и в нем всё так же то же разрешение и тот же прозрачный слой. Проводите те же манипуляции, но уже накладывая второго кота на первого, чтобы +/- прикинуть насколько гладко и бесшовно "без прыжков" будет меняться иконка. Примерили? Удаляем задний фон (прошлого кота) с холста и уже сохраняем второго кота с открытым ртом.

<details>
  <summary>3</summary>
  
https://github.com/user-attachments/assets/35bf9faf-8c3b-4059-987b-e214322e2567

</details>

4. А дальше - вам нужно сконвентировать ваши созданные .png картинки в .ico файлы любым онлайн-конвентатором , в случае если будет выбор разрешений обязательно выбираем все. (16×16, 32×32, 48×48, 256×256)
Это нужно, чтобы корзина правильно отображалась в разных случаях. (Как? Об этом есть в [этом видео](https://youtu.be/wox4ytUFHrU?si=kqaeMKpSAPT1QjwX))

!Примечание! - иконка , что сделал я, возможно не совсем бесшовная, вы обязательно должны сделать лучше. В случае если у вас нету второго экземляра иконки, то вы можете спокойно попросить любое ИИ (Я рекомендую ChatGPT) сгенерировать 2 экземляр с очень сильно открытым ртом и в 70% случаев ИИ справится.
# Благодарности 🙏
Этот проект был вдохновлён утилитой Pop Cat Bin от автора [dudetechitout](https://popcatbin.com/). Спасибо ему за отличную идею! 


</details>
