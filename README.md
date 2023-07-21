# The-Chronicles-Of-Myrtana-Archolos.-Ukrainian-translation
The Chronicles Of Myrtana: Archolos. Ukrainian translation

В цій гілці проєкт для OmegaT, орієнтований на переклад діалогів з польської мови, що знаходяться тут 
Scripts\Content\Story\Dialoge\

Тут перекладаються діалоги. Тобто усі файли, що знаходяться у теці Dialoge, яка, в свою чергу, знаходиться тут "Scripts\Content\Story\". Всього файлів з діалогами 731, та більшість з них не містять в собі і десятка сегментів, ще менше - під сотню сегментів. І окремі випадки - від 300 і більше. З них найбільші DIA_MIL_4000_Roderich.d.json(877) і DIA_SLD_5000_Lorenzo.d.json(766). Діалоги перекладаються тільки з польської. 
Сегментація діалогів відбувається по абзацах. Цей проєкт не може використовувати файли пам'яті перекладів з гілки ArcholosOmegaT.

Теки target, dictionary, omegat, tm  не синхронізуються.
Синхронізації підлягають лише:
./omegat/project_save.tmx
./glossary/glossary.txt
./source/