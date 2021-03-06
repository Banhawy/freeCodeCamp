---
id: 5900f3a81000cf542c50feba
challengeType: 5
title: 'Problem 59: XOR decryption'
videoUrl: ''
localeTitle: 'المشكلة 59: فك XOR'
---

## Description
<section id="description"> يتم تعيين رمز فريد لكل حرف على جهاز الكمبيوتر ويكون المعيار المفضل هو ASCII (الرمز القياسي الأمريكي لتبادل المعلومات). على سبيل المثال ، الأحرف الكبيرة A = 65 ، العلامة النجمية (*) = 42 ، والأحرف الصغيرة k = 107. طريقة التشفير الحديثة هي أخذ ملف نصي ، تحويل البايت إلى ASCII ، ثم XOR كل بايت مع قيمة معينة ، مأخوذة من مفتاح سر. الميزة مع الدالة XOR هي أن استخدام نفس مفتاح التشفير على النص المشفر ، يستعيد النص العادي ؛ على سبيل المثال ، 65 XOR 42 = 107 ، ثم 107 XOR 42 = 65. بالنسبة للتشفير غير القابل للكسر ، يكون المفتاح هو نفس طول رسالة النص العادي ، ويتكون المفتاح من وحدات البايت العشوائية. سيحتفظ المستخدم بالرسالة المشفرة ومفتاح التشفير في مواقع مختلفة ، وبدون كلا &quot;نصفين&quot; ، من المستحيل فك تشفير الرسالة. للأسف ، هذه الطريقة غير عملية لمعظم المستخدمين ، لذا فإن الطريقة المعدلة هي استخدام كلمة مرور كمفتاح. إذا كانت كلمة المرور أقصر من الرسالة ، وهو الأمر المحتمل ، فإن المفتاح يتكرر دوريًا في جميع أنحاء الرسالة. يستخدم رصيد هذه الطريقة مفتاح كلمة مرور طويل بما فيه الكفاية للأمان ، ولكنه قصير بما يكفي ليكون قابلاً للتذكر. لقد أصبحت مهمتك سهلة ، حيث أن مفتاح التشفير يتكون من ثلاثة أحرف أقل. باستخدام cipher.txt (النقر بزر الماوس الأيمن و &quot;حفظ الرابط / الهدف باسم ...&quot;) ، والملف الذي يحتوي على رموز ASCII المشفرة ، ومعرفة أن النص العادي يجب أن يحتوي على كلمات إنجليزية شائعة ، قم بفك تشفير الرسالة والعثور على مجموع قيم ASCII في النص الأصلي. </section>

## Instructions
<section id="instructions">
</section>

## Tests
<section id='tests'>

```yml
tests:
  - text: يجب أن يقوم <code>euler59()</code> بإرجاع 107359.
    testString: 'assert.strictEqual(euler59(), 107359, "<code>euler59()</code> should return 107359.");'

```

</section>

## Challenge Seed
<section id='challengeSeed'>

<div id='js-seed'>

```js
function euler59() {
  // Good luck!
  return true;
}

euler59();

```

</div>



</section>

## Solution
<section id='solution'>

```js
// solution required
```
</section>
