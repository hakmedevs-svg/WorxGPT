# Security Policy - سياسة الأمان

**Last Updated: October 3, 2026**

---

## Overview

WorxGPT is committed to protecting user data, system integrity, and secure access to the Service. This Security Policy explains the security measures, responsibilities, and practices used to protect information and infrastructure.

This document is intended for administrators, developers, contributors, and users who interact with the WorxGPT ecosystem.

---

## Security Principles

We follow these principles:

- Least privilege access
- Defense in depth
- Encryption in transit and at rest
- Secure authentication and authorization
- Continuous monitoring and audit logging
- Prompt incident response and recovery
- Responsible handling of user data

---

## Asset Protection

### Data We Protect

- User account data
- Authentication tokens and secrets
- Uploaded files and project content
- Conversation history
- Workspace metadata
- API keys and external integration credentials
- System logs and monitoring data

### Protection Methods

- Encryption using TLS 1.2+ in transit
- Encrypted storage for sensitive data
- Access controls based on user role and least privilege
- Regular backup and retention procedures
- Secure coding practices and peer review
- Vulnerability scanning and dependency updates

---

## Authentication and Access Control

- Strong password requirements and secure account recovery
- OAuth 2.0 for external integrations
- JWT or equivalent secure token approaches
- Multi-factor authentication support where applicable
- Session timeout and invalidation controls
- Restrictive API permission scopes

---

## Secret Management

- Secrets are never stored in code repositories
- Environment variables are used for local and deployment configuration
- Production secrets should be stored in a secure secret manager
- API keys and tokens should be rotated periodically
- Access to secrets should be logged and restricted

---

## Data Handling

- Sensitive data should be minimized and purpose-limited
- User content is processed only as necessary to provide the service
- Access to user content is restricted to authorized personnel or systems
- Logs should avoid storing plaintext secrets
- Data retention should follow documented retention policy

---

## Input and File Safety

- File uploads should be scanned for malicious content where possible
- Unsupported or dangerous file types should be rejected
- File size limits and sandboxing should be enforced
- Security validation should run on upload, parse, and processing steps

---

## Vulnerability Management

We encourage responsible reporting of vulnerabilities and security issues. Security researchers and users may report issues privately to our team.

### Reporting a Security Issue

Please contact:

- Email: security@worxgpt.io
- Telegram: [@hhyr10](https://t.me/hhyr10)

Please include:

- Description of the issue
- Affected component or service
- Steps to reproduce
- Severity assessment
- Screenshots or logs if available

---

## Incident Response

If a security issue is identified, the team will:

- Validate and assess the impact
- Contain the issue and restrict affected access
- Notify affected stakeholders when required
- Remediate and document the root cause
- Review and improve prevention controls

---

## Secure Development Standards

Developers and contributors should follow these practices:

- Use secure frameworks and updated dependencies
- Validate and sanitize user-controlled input
- Avoid storing sensitive secrets in source files
- Use role-based access controls and audit logs
- Follow secure coding best practices for API and frontend work
- Review changes for security implications

---

## Third-Party Dependencies

Third-party services, APIs, and libraries are used only when necessary. All integrations should be reviewed for security posture and permission scope before use.

---

## Compliance and Legal Notice

WorxGPT aims to comply with applicable privacy, security, and legal obligations. Local laws may require additional safeguards or restrictions depending on deployment and geography.

---

## Contact

For security questions or reporting concerns:

- Email: security@worxgpt.io
- Telegram: [@hhyr10](https://t.me/hhyr10)

---

## Arabic

# سياسة الأمان

**آخر تحديث: 3 أكتوبر 2026**

---

## نظرة عامة

يلتزم WorxGPT بحماية بيانات المستخدمين وسلامة النظام والوصول الآمن إلى الخدمة. تشرح هذه السياسة الأمان التدابير والسياسات والمسؤوليات المستخدمة لحماية المعلومات والبنية التحتية.

هذا المستند موجه للمسؤولين والمطورين والمساهمين والمستخدمين الذين يتفاعلون مع نظام WorxGPT.

---

## مبادئ الأمان

نتبع هذه المبادئ:

- الوصول بأقل امتيازات
- الدفاع المتعدد الطبقات
- تشفير البيانات أثناء النقل وفي حالة السكون
- المصادقة والتفويض الآمن
- المراقبة المستمرة وسجلات التدقيق
- الاستجابة السريعة للحوادث والتعافي
- التعامل المسؤول مع بيانات المستخدمين

---

## حماية الأصول

### البيانات التي نحميها

- بيانات حساب المستخدم
- رموز المصادقة والأسرار
- ملفات المستخدمين ومحتوى المشاريع
- سجل المحادثات
- بيانات مساحة العمل
- مفاتيح API وبيانات تكاملات الجهات الخارجية
- سجلات النظام وبيانات المراقبة

### طرق الحماية

- تشفير باستخدام TLS 1.2+ أثناء النقل
- تخزين مشفر للبيانات الحساسة
- ضوابط الوصول حسب الدور وبأقل صلاحيات
- نسخ احتياطية منتظمة وسياسات الاحتفاظ
- ممارسات البرمجة الآمنة ومراجعة الأقران
- فحص الثغرات وتحديث التبعيات

---

## المصادقة والتحكم في الوصول

- متطلبات كلمات مرور قوية واسترداد حساب آمن
- OAuth 2.0 للتكاملات الخارجية
- JWT أو أدوات مماثلة للتوكنات الآمنة
- دعم المصادقة متعددة العوامل عند توفرها
- انتهاء الجلسات وإبطالها
- صلاحيات API محدودة ومقيّدة

---

## إدارة الأسرار

- لا يتم تخزين الأسرار داخل مستودعات الكود
- تُستخدم متغيرات البيئة للتكوين المحلي ونشر الخدمة
- يجب تخزين الأسرار في مدير أسرار آمن في الإنتاج
- ينبغي تدوير مفاتيح API ورموز الوصول بشكل دوري
- يجب تسجيل الوصول إلى الأسرار وتقييده

---

## التعامل مع البيانات

- يجب تقليل البيانات الحساسة وتحديد غرضها بوضوح
- يتم معالجة محتوى المستخدم فقط حسب الضرورة لتقديم الخدمة
- يقتصر الوصول إلى محتوى المستخدم على الموظفين أو الأنظمة المصرح لها
- يجب تجنب تسجيل الأسرار في النصوص العادية
- يجب الالتزام بسياسات الاحتفاظ الموثقة

---

## أمان الملفات والمدخلات

- ينبغي فحص ملفات التحميل بحثاً عن محتوى ضار عند الإمكان
- يجب رفض أنواع الملفات غير المدعومة أو الخطرة
- تطبيق حدود لحجم الملف والسandbox عند الضرورة
- تنفيذ التحقق الأمني أثناء التحميل والمعالجة والتحليل

---

## إدارة الثغرات

نشجع على الإبلاغ المسؤول عن الثغرات ومشكلات الأمان. يمكن للباحثين الأمنيين والمستخدمين الإبلاغ عن المشكلات بشكل خاص إلى فريقنا.

### الإبلاغ عن مشكلة أمنية

يرجى التواصل عبر:

- البريد الإلكتروني: security@worxgpt.io
- تيليجرام: [@hhyr10](https://t.me/hhyr10)

يرجى تضمين:

- وصف المشكلة
- المكون أو الخدمة المتأثرة
- خطوات الاستنساخ
- تقييم الخطورة
- لقطات أو سجلات إن وجدت

---

## استجابة الحوادث

إذا تم اكتشاف مشكلة أمنية، سيعمل الفري�� على:

- التحقق من المشكلة وتقييم تأثيرها
- احتواء المشكلة وتقييد الوصول المتأثر
- إخطار الأطراف المعنية عند الضرورة
- معالجة المشكلة وتوثيق سبب الجذر
- مراجعة وتحسين ضوابط الوقاية

---

## معايير التطوير الآمن

يجب على المطورين والمساهمين اتباع هذه الممارسات:

- استخدام أطر عمل آمنة وتحديثات التبعيات
- التحقق من المدخلات والتحكم فيها
- تجنب تخزين الأسرار الحساسة داخل ملفات المصدر
- استخدام ضوابط الوصول القائمة على الدور وسجلات التدقيق
- اتباع أفضل الممارسات الأمنية في API وواجهة المستخدم
- مراجعة التغييرات من حيث الأمان

---

## التبعيات الخارجية

يتم استخدام الخدمات والواجهات البرمجية الخارجية فقط عند الضرورة. يجب مراجعة جميع التكاملات من حيث الممارسات الأمنية ونطاق الأذونات قبل الاستخدام.

---

## الالتزام القانوني والإشعار

تهدف WorxGPT إلى الامتثال للتزامات الخصوصية والأمان والقانونية المعمول بها. قد تتطلب القوانين المحلية تدابير حماية إضافية حسب النشر والجغرافيا.

---

## التواصل

للاستفسارات الأمنية أو الإبلاغ عن المخاوف:

- البريد الإلكتروني: security@worxgpt.io
- تيليجرام: [@hhyr10](https://t.me/hhyr10)

---

**Last Updated: October 3, 2026**
