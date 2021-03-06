# Deutsch-Bulgarisches Wörterbuch

For English please read below.

През 1991 когато бях на 14 години бях приет в Немска Езикова Гимназия в родния ми Бургас. По онова време вече бях започнал да се занимавам с компютри от няколко години. През 1986 баща ми донесе вкъщи Правец 82 - клонинг на Apple ][ Plus, но няколко години по-късно го смени с Правец 8А, който е клонинг на Apple //e. Знаех, че в това училище ще се учи много и че ще трябва да уча много нови думи всеки ден. Така че си помислих защо да не напиша програма речник, която да ме изпитва колко добре съм си научил думите.

И така през август 1991 след като стана ясно, че съм приет седнах пред моя Правец 8А и започнах да пиша първата си програма с конкретно приложение. До тогава си мислех, че една дискета ще е достатъчна да съхраня няколко стотин думи и техните значения но бързо осъзнах, че трябва да използвам всеки възможен байт и че една дискета изобщо не е достатъчна. В края на първата година се очакваше да знаем между 5000 и 6000 думи. И така, след около седмица писане моята програма речник беше готова. Частта за изпитване я взех от списание Млад Конструктор. Резултатите от това компютърно асистирано учене бяха много добри. За съжаление баща ми трябваше да върне компютъра само месец след началото на учебната година защото той беше собственост на работата му.

Програмата е написана на Бейсик и е единствено съвместима с Првец 8A, Правец 8C и Правец 8S. Използва се командата SETMOD x която позволява употребата на малки букви. Тази команда заменя SHLOAD и ако стартирате програмата на друг компютър ще има опит за четене от касетофон.

Речникът използва отделни файлове за всяка буква от немската азбука. Умлаутите (Ä, Ö и Ü) нямат свои собствени файлове защото знаковия генератор на Правец ги съдържа и те принадлежат на своите стандартни букви. Реших да добавям многоточие за да отбелязвам умлаут.

Интерфейсът е на български, защото го правих само за себе си. Програмата никога не е била използвана от друг за което съжалявам но тогава Правец 8C беше много скъп и аз бях единствен в класа си с компютър у дома. Сдобих се със следващия си компютър (486SX) в късната есен на 1995 и към този момент не се нуждаех от програмата и не си направих труда да я портна.

Реших да отворя кода за да отбележа 30-тата годишнина от влизането ми Немска Езикова Гимназия. А и като любител на ретрокомпютрите искам да споделя с общността какво съм правил тогава.

-------

English:

In 1991 at the age of 14 I was accepted in the German Language School in my home town of Burgas, Bulgaria. Back then I already had started dealing with computers some years ago. In 1986 my father brought home a Pravetz 82 machine - a clone of Apple ][ Plus, but a couple of years later he substituted it with Pravetz 8A which is a clone of Apple //e. I new that the learning curve in this school is steep and that I will have to learn many new words every day. So I thought why not creating a computer dictionary which is able to examine me how good I learn the words.

So in August, 1991, after it got clear that I qualified for the school I sat down in front of my Pravetz 8A and started implementing my first program with a concrete application. Until then I though that a single diskette should be enough to store several hundred words and their translations but I quickly realized that I must use every available byte and just one diskette is not enough at all. At the end of the first year we were expected to know between 5000 and 6000 words. So after probably a week of coding my dictionary application was ready. The exam part I borrowed from a magazine called Млад Конструктор (Young Constructor). Тhe results from this computer assisted words learning was very good. Unfortunately my father had to give back the computer just a month after the school year beginning because it belonged to his job.

The program is written in Basic and is only compatible with Pravetz 8A, Pravetz 8C and Pravetz 8S. It uses the SETMOD x command which can allow the usage of small characters. This command substitutes the SHLOAD command so running it on other machine will result in an attempt read from a cassette player.

The dictionary uses a separate text file for every letter of the German alphabet. The umlaut letters (Ä, Ö and Ü) don’t have their own files because the character set of Pravetz doesn’t contain them so they belong to their corresponding standard letters. I decided to add a colon to denote an umlaut.

The interface is in Bulgarian as I made it only for me. The program was never used by anyone else for which I regret but back then a Pravtez 8C was extremely expensive and I was the only one in my class having a personal computer home. I got my next machine (486SX) in the late autumn of 1995 and at that moment I didn’t need this program so I didn’t bother to port it.

I decided to open source the code to mark the 30-th anniversary since I joined the German Language School. And as a retro computers fan I want to share what I did back then to the community.
