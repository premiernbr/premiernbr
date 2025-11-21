# Security Policy / سياسة الأمان / Politique de sécurité

نحن ملتزمون بحماية مستخدمي المشروع والتعامل الجاد مع أي ثغرة أو سلوك غير آمن.  
We are committed to protecting users and treating any vulnerability seriously.  
Nous sommes engagés à protéger les utilisateurs et à traiter toute vulnérabilité avec sérieux.

## Supported Versions / الإصدارات المدعومة / Versions prises en charge

- المرحلة الحالية تجريبية: فرع **main** فقط يستقبل تحديثات أمنية، والفروع الأخرى للاختبار دون ضمانات إنتاجية.  
- Experimental phase: only **main** receives security updates; other branches are experimental with no production guarantees.  
- Phase expérimentale : seul **main** reçoit des mises à jour de sécurité ; les autres branches sont expérimentales sans garantie de production.

| Branch | Status |
|--------|--------|
| main   | ✅ Active |
| others | ⚠️ Experimental / no guarantees |

> سيتم تحديث السياسة عند الانتقال إلى إصدارات موسومة (tags).  
> Policy will be revised once tagged releases are adopted.  
> La politique sera révisée lors du passage à des versions taguées.

## Reporting a Vulnerability / الإبلاغ عن ثغرة / Signaler une vulnérabilité

إذا وجدت ثغرة في الكود أو واجهة الويب `https://premiernbr.github.io/premiernbr/`:  
If you discover a vulnerability in the code or web UI at `https://premiernbr.github.io/premiernbr/`:  
Si vous trouvez une vulnérabilité dans le code ou l’interface web `https://premiernbr.github.io/premiernbr/` :

1. **لا** تنشر التفاصيل علنًا أو في Issue عامة.  
   **Do not** publish exploit details publicly or in a public Issue.  
   **Ne publiez pas** les détails techniques publiquement ni dans une Issue publique.
2. استخدم قناة خاصة للإبلاغ:  
   Use a private channel to report:  
   Utilisez un canal privé pour signaler :
   - افتح Issue بعنوان عام مثل `Security report (details shared privately)` بدون تفاصيل تقنية.  
     Open an Issue with a neutral title like `Security report (details shared privately)` and no technical details.  
     Ouvrez une Issue au titre neutre, ex. `Security report (details shared privately)`, sans détails techniques.
   - أو راسل بريد الأمان: `security@premiernbr.dev`.  
     Or email the security contact: `security@premiernbr.dev`.  
     Ou écrivez au contact sécurité : `security@premiernbr.dev`.

يرجى تضمين / Please include / Merci d’inclure:  
- وصفًا واضحًا للثغرة · Clear description · Description claire.  
- خطوات إعادة الإنتاج (PoC إن أمكن) · Repro steps (PoC if possible) · Étapes de repro (PoC si possible).  
- أي سجلات أو لقطات ذات صلة · Relevant logs/screenshots · Journaux/captures pertinents.  
- نظام التشغيل والمتصفح/البيئة · OS and browser/runtime · OS et navigateur/environnement.

## Commitments / التزاماتنا / Nos engagements

- تأكيد استلام البلاغ خلال **7 أيام عمل**.  
- Acknowledge receipt within **7 business days**.  
- Accuser réception sous **7 jours ouvrés**.

- تحديث أولي خلال **14 يومًا** بشأن تأكيد الثغرة وخطة الإصلاح.  
- Initial update within **14 days** on validation and remediation plan.  
- Mise à jour initiale sous **14 jours** sur la validation et le plan de correction.

- إبلاغك عند إصدار الإصلاح وقبل نشر أي تفاصيل تقنية.  
- Notify you when a fix ships and before publishing technical details.  
- Vous informer lors de la mise à disposition du correctif et avant toute publication technique.

يمكن الإشارة إلى اسمك كمساهم في تحسين الأمان إذا رغبت.  
Credit is available on request.  
Une mention est possible sur demande.

## Scope / نطاق هذه السياسة / Portée de la politique

- تغطي هذه السياسة الكود في هذا المستودع والموقع المنشور على GitHub Pages.  
- This policy covers code in this repository and the associated GitHub Pages site.  
- Cette politique couvre le code de ce dépôt et le site GitHub Pages associé.

- المكتبات الخارجية تخضع لسياسات أصحابها؛ نحدثها عند صدور تنبيهات أمنية معروفة.  
- Third-party dependencies follow their vendors’ policies; we update when advisories arise.  
- Les dépendances tierces suivent les politiques de leurs éditeurs ; nous les mettons à jour dès parution d’avis de sécurité.
