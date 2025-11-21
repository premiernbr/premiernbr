# Security Policy / سياسة الأمان / Politique de sécurité

نحن نهتم بأمان مستخدمي هذا المشروع، ونتعامل بجدية مع أي ثغرة أو سلوك غير آمن.  
We take the security of this project seriously.  
Nous prenons la sécurité de ce projet très au sérieux.

## Supported Versions / الإصدارات المدعومة / Versions prises en charge

- المرحلة الحالية تجريبية، ولا يتم دعم إلا فرع **main** بالتحديثات الأمنية. أي فروع أخرى غير مدعومة للإنتاج.  
- In this experimental phase, only branch **main** receives security updates; other branches are not production-supported.  
- Durant cette phase expérimentale, seul le branche **main** reçoit des mises à jour de sécurité ; les autres branches ne sont pas prévues pour la production.

| Branch | Status |
|--------|--------|
| main   | ✅ Active |
| others | ❌ Experimental / no guarantees |

> سيتم تحديث هذه السياسة عند الانتقال إلى نظام إصدارات (tags) رسمي.  
> This policy will be updated when we adopt tagged releases.  
> Cette politique sera mise à jour lorsque nous passerons à des versions taguées.

## Reporting a Vulnerability / الإبلاغ عن ثغرة / Signaler une vulnérabilité

إذا اعتقدت أنك اكتشفت ثغرة أمنية في الكود أو في واجهة الويب `https://premiernbr.github.io/premiernbr/`:  
If you think you’ve found a vulnerability in the code or the web UI at `https://premiernbr.github.io/premiernbr/`:  
Si vous pensez avoir trouvé une vulnérabilité dans le code ou sur l’interface web `https://premiernbr.github.io/premiernbr/` :

1. **لا** تفتح Issue عمومي بتفاصيل الثغرة.  
   **Do not** open a public Issue with exploit details.  
   **N’ouvrez pas** d’Issue publique contenant les détails techniques.
2. استخدم قناة خاصة:  
   Use a private channel:  
   Utilisez une voie privée :
   - افتح Issue بعنوان عام مثل: `Security report (private details by email)` بدون تفاصيل فنية.  
     Open an Issue with a general title like `Security report (private details by email)` and no technical details.  
     Ouvrez une Issue au titre général, par ex. `Security report (private details by email)`, sans détails techniques.
   - أو راسل البريد المخصص للأمان: `security@premiernbr.dev`.  
     Or email the dedicated security contact: `security@premiernbr.dev`.  
     Ou envoyez un courriel au contact sécurité dédié : `security@premiernbr.dev`.

يرجى أن يتضمن البلاغ / Please include / Merci d’inclure :  
- وصفًا واضحًا للثغرة · Clear description of the issue · Description claire de la vulnérabilité.  
- خطوات إعادة الإنتاج (PoC إن أمكن) · Reproduction steps (PoC if possible) · Étapes de reproduction (PoC si possible).  
- أي سجلات أو لقطات ذات صلة · Relevant logs or screenshots · Journaux ou captures pertinentes.  
- نظام التشغيل والمتصفح/البيئة · OS, browser/runtime used · OS, navigateur/environnement utilisés.

## Commitments / التزاماتنا / Nos engagements

- تأكيد استلام البلاغ خلال **7 أيام عمل**.  
- Acknowledge receipt within **7 business days**.  
- Accuser réception sous **7 jours ouvrés**.
- تحديث أولي خلال **14 يومًا** حول تأكيد الثغرة وخطة الإصلاح.  
- Initial update within **14 days** on confirmation and remediation plan.  
- Mise à jour initiale sous **14 jours** sur la confirmation et le plan de correction.
- إبلاغك عند إصدار الإصلاح وقبل نشر أي تفاصيل تقنية.  
- Notify you when a fix ships and before publishing technical details.  
- Vous informer lors de la mise à disposition du correctif et avant toute publication technique.

إذا رغبت، يمكن ذكر اسمك كمساهم في تحسين الأمان.  
Credit is offered if you wish to be mentioned.  
Une mention de votre contribution est possible sur demande.

## Scope / نطاق هذه السياسة / Portée de la politique

- تغطي هذه السياسة الكود في هذا المستودع والصفحة المنشورة على GitHub Pages فقط.  
- This policy covers code in this repository and the GitHub Pages site only.  
- Cette politique couvre uniquement le code de ce dépôt et le site GitHub Pages associé.
- المكتبات الخارجية تخضع لسياسات أصحابها، ونسعى لتحديثها عند ظهور ثغرات معروفة.  
- Third-party dependencies follow their own security policies; we aim to update them when advisories appear.  
- Les dépendances tierces relèvent des politiques de leurs éditeurs ; nous les mettrons à jour dès qu’un avis de sécurité est publié.
