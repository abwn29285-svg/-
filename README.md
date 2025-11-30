# تعليمات تشغيل تطبيق AI Chat مجاني - النسخة المباشرة

1. ضع جميع الملفات في مجلد واحد.
   الملفات: app.py, database.py, README.txt

2. حمّل نموذج GPT4All من الرابط التالي وضعه في نفس المجلد:
   https://gpt4all.io/index.html
   الملف: ggml-gpt4all-j-v1.3-groovy.bin

3. افتح Command Prompt (CMD) في المجلد.

4. أنشئ البيئة الافتراضية وفعلها:
       python -m venv venv
       venv\Scripts\activate

5. ثبّت المكتبات اللازمة:
       pip install streamlit gpt4all

6. شغّل التطبيق:
       streamlit run app.py

7. ستظهر لك الواجهة مع:
   - اختيار شخصية AI
   - ألوان واجهة مخصصة
   - حفظ آخر 10 محادثات
   - زر لمسح المحادثة
