# حصن المسلم
يحتوي هذا المشروع على ملف 'جيسون' به كلّ الأذكار المصنّفة في كتاب: حصن المسلم للفقير إلى اللّه تعالى: سعيد بن عليّ بن وهف القحطاني.

# طريقة جمع الأذكار
الأذكار قمت بكاتبتها ونقلها شخصيًّا من الكتاب المطبوع (لدار السّجلّات). ثمّ بعد ذلك قمت بتحميل نسخة من الأذكار من الأنترنت وقمت بمقارنة النسخة المكتوبة من قبلي مع النّسخة المحمّلة من النت من أجل التأكّد من خلوّها من الأخطاء سواءًا في الأذكار أو مصادرها.  
المقارنة بين النسختين المكتوبة والمحمّلة من النت ثمّت باستعمال خوارزميّة:  
Levenshtein distance: https://en.wikipedia.org/wiki/Levenshtein_distance  
في النهاية، بعد المقارنة وتصحيح الأخطاء في النسخة المكتوبة تمّ الاحتفظ بالنّسخة المكتوبة المصحّحة.

# التّبليغ عن الأخطاء
 في حالة وجود أيّة أخطاء في الأذكر يرجى التبليغ عنها في المكان المخصّص لها في هذا المشروع:  
https://github.com/asellam/HisnElMuslim/issues/new

# HisnElMuslim
This repos contains the whole book of HisnElMuslim as a JSON file.
# عناوين الأبواب بالإنجليزيّة
يحتوي الملفّ `titles_en.json` على ترجمة إنجليزيّة لعناوين الأبواب الـ133، مفهرسةً بالعنوان العربيّ كما هو في `hisn.json` وبنفس الترتيب. الأذكار نفسها غير مترجمة، و`hisn.json` لم يتغيّر.

## English chapter titles
`titles_en.json` maps each of the 133 chapter titles in `hisn.json` (the exact Arabic key, in the book's order) to a short English title, so apps can show English chapter names without changing `hisn.json`:

```json
{
  "أَذْكَارُ الِاسْتِيقَاظِ مِنَ النَّوْمِ": "When waking up",
  "دُعَاءُ لُبْسِ الثَّوْبِ": "When putting on clothes"
}
```

Only the chapter titles are translated; the adhkar themselves are not. The titles were translated directly from the Arabic headings and are offered for review.
