<p align="center"><img src="./assets/banner.svg" alt="XXD Panel 037 project banner" width="1200"></p>

<div align="center" dir="rtl">

# 🦁 XXD Panel 037

### تحويل كل رحلة إلى شارة مينا مذهّبة قابلة للاقتناء

[![Codex Skill](https://img.shields.io/badge/Codex-Skill-000000?style=flat-square)](./SKILL.md)
[![Modes](https://img.shields.io/badge/Modes-4-E7483E?style=flat-square)](#)
[![Output](https://img.shields.io/badge/Output-PNG-1A7A8C?style=flat-square)](#)

<a href="README.md">简体中文</a> · <a href="README.en.md">English</a> · <a href="README.ja.md">日本語</a> · <a href="README.ko.md">한국어</a> · <strong>العربية</strong>

</div>

<div dir="rtl">

> شارة واحدة · مينا من المصدر · إطار معدني أبيض · تفصيل مذهّب · ظل حقيقي قصير

يُضغط المحيط الحاسم والسمات الموضعية في شارة سفر مادية واحدة: خلايا مينا من المصدر، وفواصل معدنية، وإطار من معدن أبيض، وتفاصيل مذهّبة محدودة، وسماكة مدوّرة، وظل حقيقي قصير.

## لماذا توجد هذه المهارة؟

يعتمد الأسلوب على المصدر وليس قالباً زخرفياً يمكن تبديل محتواه. ويتبع سلسلة التحويل الآتية:

```text
lock identity and silhouette → preserve the decisive contour and local features → simplify into meaningful enamel cells → build real metal dividers and white-metal rim → add restrained gilded accents, thickness, bevel, and short contact shadow → integrate native title into the badge body
```

إذا أمكن استبدال المصدر بصورة لا صلة لها من دون تغيير جوهري في التعرّف والبناء والموضع والمادة واللون والفراغ والنص، فالنتيجة لا تنتمي إلى هذا Panel.

## العقد البصري

- **الارتباط بالمصدر:** تحويل كل رحلة إلى شارة مينا مذهّبة قابلة للاقتناء
- **بصمة الأسلوب:** شارة واحدة · مينا من المصدر · إطار معدني أبيض · تفصيل مذهّب · ظل حقيقي قصير
- **قابلية التعرّف:** تُحفظ ثلاث علامات خاصة بالمصدر على الأقل، ويجب أن تنتج الصورة غير المرتبطة بناءً مختلفاً جوهرياً.
- **التكوين:** يحافظ على موضوع واحد أو علاقة لا تنفصل، وموضع مدعوم بالمصدر، وفراغ فعّال.
- **المادة واللون:** يُشتقان من الصورة وفق توجيه الإنتاج الخاص بالمشروع، لا من قالب ثابت.

توجد القيود الجمالية وقواعد الرفض الكاملة في المهارة وتوجيهات الإنتاج. وهي تحفظ دافع النص الأصلي من دون تحويل لوحة 3:4 التاريخية إلى قيمة افتراضية خفية. [SKILL.md](SKILL.md) · [production prompt](references/xxd-panel-037-prompt.en.md)

## النماذج · قريباً

لن يضاف إلى `assets/examples/` إلا عمل مكتمل بهذا الأسلوب ومؤكد من صاحب المشروع، ولن يُستخدم أسلوب آخر كعنصر مؤقت.

## أربعة مخرجات قابلة للجمع

اختر نمطاً واحداً أو عدة أنماط بـ `1` أو `1+3` أو `1,2,4` أو `الكل`. ينتج «الكل» سبعة ملفات PNG لكل مصدر: ثلاثة مخرجات عادية وأربع خلفيات.

| النمط | المقاس عند غياب التحديد | الناتج |
| --- | --- | --- |
| `top-bottom` | متكيف مع المصدر `W×2H` | الأصل كاملاً في الأعلى والتصميم المتحوّل في الأسفل، بنسبة 50/50 دقيقة |
| `left-right` | متكيف مع المصدر `2W×H` | الأصل كاملاً في اليسار والتصميم المتحوّل في اليمين، بنسبة 50/50 دقيقة |
| `design-only` | متكيف مع المصدر `W×H` | التصميم المتحوّل وحده من دون ظهور الأصل |
| `wallpaper-pack` | مقاسات مسمّاة لكل جهاز | ملفات PNG منفصلة للهاتف وiPad والحاسوب وساعة الأطفال |

قد تكون الخلفيات مترابطة أو مستقلة. تعتمد المجموعة المترابطة عملاً مرجعياً واحداً ثم يرجع كل جهاز إلى الأصل وإلى المرجع نفسه، من دون قص أو سلسلة مشتقات. أما المستقلة فيرجع كل جهاز فيها إلى الأصل فقط.

## النص واللغة

يُحسم قبل التوليد النص التلقائي أو النص الدقيق المخصص أو غياب النص. تتبع اللغة الجمهور المقصود لا لغة الأمر، ويبقى نص المستخدم النهائي حرفياً.

قاعدة النص الخاصة بالمشروع: يُنشأ عنوان قصير واحد مرتبط بقوة بموضوع المصدر أو فعله أو علاقته أو شعوره أو دلالته، مع أقل قدر لازم من الملاحظات الدقيقة. ويُدمج النص ببنية الكتابة الأصلية للغة المستهدفة في المادة والمحيط والمحور والفراغ، مع حفظ النص النهائي حرفياً.

## الهندسة والصورة النقطية والثقة

تتكيف الأنماط العادية مع المصدر ما لم يرد مقاس صريح، وتنقسم التركيبات الثنائية 50/50 بدقة، وكل النتائج ملفات PNG نقطية. ينشئ كل استدعاء مهمة جديدة تحت `~/Desktop/xxd/` ولا يكشف معلومات مسار التوليد الخاصة.

لا يعيد جسر الصور المضبوط إلا حالة منزوعة التفاصيل، ولا يكشف المزوّد أو نقطة الاتصال أو بيانات الاعتماد أو الرؤوس أو التوجيه أو الاستجابة أو معلومات الحساب. ولا تصلح SVG أو HTML أو Canvas أو الرسوم البرمجية بديلاً للعمل النقطي النهائي.

## البدء

```bash
git clone https://github.com/nevertoday/xxd-panel-037.git
mkdir -p ~/.codex/skills
ln -s "$(pwd)/xxd-panel-037" ~/.codex/skills/xxd-panel-037
```

يمكن لمستخدمي Claude Code ربط المجلد نفسه بالمسار: `~/.claude/skills/xxd-panel-037`. أعد تشغيل جلسة الوكيل بعد التثبيت.

```text
$xxd-panel-037
Use this photograph, ask me for the modes and copy setting, then generate fresh raster outputs.
```

المواصفات الكاملة: [مسار عمل المهارة](SKILL.md) · [أرشيف الأسلوب الأصلي](references/037-source.md) · [توجيه الإنتاج الإنجليزي](references/xxd-panel-037-prompt.en.md) · [توجيه الإنتاج الصيني](references/xxd-panel-037-prompt.zh-CN.md)

## عن XXD

XXD هو اختصار اسم علامة Xiaoxiaodong. أنشأ المشروع ويديره: [@xiaoxiaodong01](https://x.com/xiaoxiaodong01).

## الدعم والعضوية

### استشارة متعمقة · 299 يواناً/ساعة

استشارة فردية متعمقة في استخدام Skills ومسار العمل. تواصل مع Xiaoxiaodong عبر WeChat. [WeChat](https://xiaoxiaodong.pages.dev/assets/wechat-qr.png)

### مجموعة مستخدمي Xiaoxiaodong Skills · 99 يواناً

تتيح دفعة واحدة الانضمام إلى مجموعة مستخدمي Skills لتبادل المسارات والنقاش؛ والاستشارة الفردية بالساعة منفصلة.

### Knowledge Planet＋مكتبة توجيهات الأعضاء · 699 يواناً/سنة

Knowledge Planet ومكتبة توجيهات الأعضاء عضوية سنوية واحدة. اشترك عبر أي منهما ثم تواصل عبر WeChat لفتح الخدمة الأخرى.

[Knowledge Planet](https://wx.zsxq.com/group/15554814142882) · [Member Prompt Library](https://vip.xiaoxiaodong.ai/)

<p align="center"><a href="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png"><img src="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png" alt="XXD WeChat" width="280"></a></p>

<div align="center" dir="rtl"><strong>تصبح الرحلة قابلة للاقتناء حين يبقى محيطها المميّز داخل اللمعان.</strong></div>

---

<div align="center" dir="rtl">

## ☕ دعم المشروع المفتوح المصدر

تستخدم النسخ غير الصينية Buy Me a Coffee. الدعم اختياري ولا يغيّر الوصول إلى المشروع المفتوح المصدر.


<p align="center"><a href="https://github.com/nevertoday/zhongguo-traditional-colors/blob/main/docs/images/buy-me-a-coffee-qr.png?raw=true"><img src="https://github.com/nevertoday/zhongguo-traditional-colors/blob/main/docs/images/buy-me-a-coffee-qr.png?raw=true" alt="Buy Me a Coffee" width="180"></a></p>

</div>
</div>
