---
$title: تضمين صورة
---

يمكن استخدام معظم علامات HTML مباشرةً في <span dir="ltr" class="nowrap">AMP HTML</span>، لكن بعض العلامات، مثل علامة `<img>`، يتم استبدالها بعلامات <span dir="ltr" class="nowrap">AMP HTML</span> مكافئة أو مخصصة محسّنة بعض الشيء (وتم حظر بضع العلامات المسببة للأخطاء حظرًا تامًا، انظر [علامات HTML في المواصفة]({{g.doc('/content/amp-dev/documentation/guides-and-tutorials/learn/spec/index.md', locale=doc.locale).url.path}})).

لتوضيح المظهر الذي يمكن أن يبدو عليه الترميز الإضافي، إليك الشفرة المطلوبة لتضمين صورة في الصفحة:

[sourcecode:html]
<amp-img src="welcome.jpg" alt="Welcome" height="400" width="800"></amp-img>
[/sourcecode]

للتعرّف على أسباب إقدامنا على استبدال العلامات، مثل استبدال `<img>` بـ `<amp-img>`، وكم عدد المتاح منها، يُرجى الانتقال إلى [تضمين إطارات Iframe والوسائط]({{g.doc('/content/amp-dev/documentation/guides-and-tutorials/develop/amp_replacements.md', locale=doc.locale).url.path}}).

<div class="prev-next-buttons">
  <a class="button prev-button" href="{{g.doc('/content/amp-dev/documentation/guides-and-tutorials/start/create/basic_markup.md', locale=doc.locale).url.path}}"><span class="arrow-prev">سابق</span></a>
  <a class="button next-button" href="{{g.doc('/content/amp-dev/documentation/guides-and-tutorials/start/create/presentation_layout.md', locale=doc.locale).url.path}}"><span class="arrow-next">سابق</span></a>
</div>
