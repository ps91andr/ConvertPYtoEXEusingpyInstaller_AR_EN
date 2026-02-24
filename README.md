
# ⚙️ Python-to-EXE-Professional-Converter-PyInstaller_AR_EN

<div align="center">
  
  <h1>⚙️ Python to EXE PyInstaller Professional</h1>
  <h3>محول بايثون الاحترافي إلى EXE PyInstaller| Professional Python Converter PyInstaller</h3>
  <p><em>أداة سطح مكتب متطورة لتحويل سكربتات Python إلى تطبيقات Windows تنفيذية مع دعم الضغط والحماية</em></p>
  
  <p>
    <img src="https://img.shields.io/badge/version-1.0.0-blue.svg" alt="Version 1.0.0">
    <img src="https://img.shields.io/badge/python-3.10+-green.svg" alt="Python 3.10+">
    <img src="https://img.shields.io/badge/PyQt-6.0-orange.svg" alt="PyQt6">
    <img src="https://img.shields.io/badge/PyInstaller-6.0+-red.svg" alt="PyInstaller">
    <img src="https://img.shields.io/badge/license-MIT-yellow.svg" alt="MIT License">
    <img src="https://img.shields.io/badge/platform-windows-lightgrey" alt="Platforms">
  </p>
  
  <h3>
    <a href="#المميزات">المميزات</a> •
    <a href="#-التثبيت">التثبيت</a> •
    <a href="#-الاستخدام">الاستخدام</a> •
    <a href="#-الملفات-المدعومة">الملفات</a> •
    <a href="#-المساهمة">المساهمة</a> •
    <a href="#-الترخيص">الترخيص</a>
  </h3>
  
  <h3>
    <a href="#english">English</a> |
    <a href="#-العربية">العربية</a>
  </h3>
  
</div>

---

## 🎧 العربية

<div dir="rtl">

### نظرة عامة

**Python to EXE Professional** هي أداة رسومية قوية ومفتوحة المصدر مصممة للمطورين لتحويل ملفات البايثون (`.py`) إلى ملفات تنفيذية (`.exe`) بكل سهولة. تجمع الأداة بين قوة **PyInstaller** وتقنيات الضغط **UPX** مع محرر متكامل لبيانات الإصدار (Version Info) وطبقات حماية متقدمة.

---

### ✨ المميزات {#المميزات}

| الميزة | الوصف |
|--------|-------|
| 🔒 **ملف واحد (One-File)** | دمج جميع المكتبات والملفات في ملف EXE واحد فقط |
| 🕶️ **إخفاء الكونسول** | إمكانية تشغيل البرنامج بدون ظهور نافذة الأوامر السوداء |
| 📦 **ضغط UPX** | تقليل حجم ملف الـ EXE الناتج لأقصى درجة (أكثر من 50%) |
| 📝 **محرر الإصدار** | إنشاء وتعديل بيانات حقوق الملكية، اسم الشركة، وإصدار البرنامج |
| 📁 **إضافة بيانات** | دعم إضافة الصور، قواعد البيانات، والملفات الخارجية (--add-data) |
| 🛡️ **حماية Anti-Debug** | مدمج به حماية ضد أدوات التصحيح والبيئات الافتراضية وVMs |
| 🖼️ **معاينة الأيقونات** | اختيار ومعاينة أيقونة التطبيق مباشرة من الواجهة |
| ⚡ **سحب وإفلات** | واجهة ذكية تدعم سحب الملفات، الأيقونات، وحتى مجلدات UPX |
| 🌐 **ثنائي اللغة** | واجهة عربية وإنجليزية كاملة مع دعم اتجاهات النص |

---

### 🖼️ لقطات شاشة
![Screenshot](https://github.com/ps91andr/ConvertPYtoEXEusingpyInstaller_AR_EN/blob/main/AR.png)

---

### 📦 التحميل المباشر

#### نسخ جاهزة للتشغيل (Windows EXE)

| الملف | الوصف |
|-------|-------|
| [ConvertPYtoEXE_AR.exe](https://github.com/ps91andr/ConvertPYtoEXEusingpyInstaller_AR_EN/releases/tag/ConvertPYtoEXEusingpyInstaller_AR_EN) | النسخة العربية الاحترافية - لا يحتاج تثبيت |
| [ConvertPYtoEXE_EN.exe](https://github.com/ps91andr/ConvertPYtoEXEusingpyInstaller_AR_EN/releases/tag/ConvertPYtoEXEusingpyInstaller_AR_EN) | النسخة الإنجليزية الاحترافية - لا يحتاج تثبيت |

---

### 🚀 طريقة الاستخدام

1. **اختيار الملف**: اسحب ملف الـ `.py` وأفلته في البرنامج أو استخدم زر "استعراض".
2. **تخصيص الأيقونة**: اختر ملف `.ico` ليكون الواجهة الرسمية لبرنامجك.
3. **بيانات الإصدار**: 
   - اضغط "إنشاء ملف إصدار" لإضافة اسمك واسم برنامجك.
   - يمكنك تعديل ملفات الإصدار القديمة مباشرة عبر البرنامج.
4. **الملفات الإضافية**: إذا كان برنامجك يستخدم صوراً أو ملفات خارجية، استخدم خيار "إضافة ملفات إضافية".
5. **إعدادات الضغط**: قم بتفعيل **UPX** وحدد مسار المجلد لتقليص الحجم.
6. **بدء التحويل**: اضغط "تحويل إلى EXE" وتابع سجل المخرجات لحظة بلحظة.

---

### 🎛️ الملفات المدعومة

| نوع الملف | الامتداد | الوظيفة |
|--------|----------|-----------------|
| Python Script | `.py` | الملف البرمجي الأساسي المراد تحويله |
| Icon File | `.ico` | أيقونة التطبيق الرسمية |
| Version Info | `.txt` | ملف يحتوي على بيانات المنتج وحقوق النشر |
| UPX Tool | `upx.exe` | أداة اختيارية تستخدم لضغط حجم الملف |

---

### ⚖️ إخلاء المسؤولية

<div dir="rtl" style="background-color:#1e1e1e;padding:20px;border-radius:8px;border-right:6px solid #ff4b4b;line-height:1.9;font-size:15px;color:#ffffff;font-family:Tahoma,Arial,sans-serif;">

<h3 style="margin-top:0;">🔴 تنبيه هام جداً – يرجى القراءة بعناية قبل الاستخدام</h3>

هذه الأداة هي أداة مساعدة موجهة للمطورين والمحترفين، ومخصصة <strong>للاستخدام القانوني والمهني المشروع فقط</strong>.  
باستخدامك لهذه الأداة فإنك تقر وتوافق بشكل صريح على جميع البنود التالية دون استثناء، وتتحمل المسؤولية الكاملة والتامة عن أي استخدام للملفات أو البرمجيات الناتجة عنها:

<ul>
<li>أنك تتحمل المسؤولية الكاملة عن جميع البرامج أو الملفات التي تقوم بتحويلها أو معالجتها أو توزيعها باستخدام هذه الأداة.</li>
<li>أنك لن تستخدم الأداة أو أي من ميزاتها — بما في ذلك ميزات الحماية أو التعتيم أو Anti-Debug — في إخفاء أو حماية أو توزيع برمجيات خبيثة أو ضارة أو غير قانونية أو منتهكة لحقوق الآخرين.</li>
<li>أن المطور غير مسؤول نهائياً عن أي استخدام غير مشروع أو مخالف للقوانين المحلية أو الدولية أو لشروط منصات التوزيع، أو أي استخدام غير مرخّص للبرمجيات الناتجة.</li>
<li>أن عملية التحويل قد تؤدي — في بعض الحالات — إلى فقدان أجزاء من الكود أو حدوث أخطاء أو نتائج غير متوقعة، ولذلك تتحمل مسؤولية <strong>الاحتفاظ بنسخة احتياطية كاملة من الكود المصدري الأصلي</strong> قبل البدء بأي عملية تحويل أو تعديل.</li>
<li>أن المطور غير مسؤول عن أي فقدان بيانات، أو تلف ملفات، أو خسائر مباشرة أو غير مباشرة، أو أضرار تشغيلية أو مالية أو تقنية ناتجة عن الاستخدام أو سوء الاستخدام أو الإهمال.</li>
<li>أن توافق البرامج الناتجة مع أنظمة التشغيل أو الإصدارات المختلفة (بما في ذلك إصدارات ويندوز) يعتمد على بيئة التطوير والمكتبات وإعدادات البناء المستخدمة، وليس على الأداة وحدها.</li>
</ul>

<hr style="border-color:#333;">

<h4>🔐 بخصوص ميزة الحماية (Anti-Debug)</h4>

ميزة الحماية المدمجة تهدف إلى:
<ul>
<li>تقليل محاولات الهندسة العكسية البسيطة.</li>
<li>إضافة طبقة حماية أولية للكود أو البرنامج الناتج.</li>
</ul>

<p><strong>⚠️ ملاحظة:</strong> ميزة الحماية (Anti-Debug) المدمجة تهدف لحماية كودك من الهندسة العكسية البسيطة، وليست حماية مطلقة ضد الخبراء.</p>

ومع ذلك:
<ul>
<li>لا تُعتبر هذه الميزة حماية مطلقة.</li>
<li>لا تضمن منع التحليل أو الاختراق أو التفكيك المتقدم من قبل الخبراء.</li>
<li>لا يجب الاعتماد عليها كوسيلة أمنية وحيدة لحماية المشاريع أو المنتجات الحساسة.</li>
</ul>

<hr style="border-color:#333;">

<h4>🛠️ طريقة تفعيل ميزة الحماية (Anti-Debug)</h4>

لتطبيق ميزة الحماية على سكربت بايثون الخاص بك:

<ul>
<li>قم بلصق كود الحماية التالي في أعلى الملف المراد تحويله.</li>
<li>يجب أن يكون اللصق بعد سطور الاستيراد (imports) مباشرة.</li>
<li>يجب استدعاء الدالة مرة واحدة فقط عند بداية التشغيل.</li>
</ul>

<details style="margin-top:10px;">
<summary style="cursor:pointer;font-weight:bold;color:#ffb3b3;">
📄 اضغط هنا لعرض / إخفاء كود الحماية Anti‑Debug
</summary>

<pre style="background:#111;padding:12px;border-radius:6px;overflow:auto;direction:ltr;color:#e6e6e6;">
import sys
import os
import ctypes
import socket
import subprocess

def anti_debug_protection():
    """طبقات حماية متعددة"""
    
    debug_indicators = [
        'PYCHARM_HOSTED','PYDEV_CONSOLE_ENCODING',
        'PYTHONDEVMODE','PYTHONINSPECT'
    ]
    
    for indicator in debug_indicators:
        if indicator in os.environ:
            sys.exit(1)
    
    if os.name == 'nt':
        try:
            if ctypes.windll.kernel32.IsDebuggerPresent():
                sys.exit(1)
            
            debug_ports = [5858,5859,5678,21000,21001]
            for port in debug_ports:
                sock = socket.socket(socket.AF_INET,socket.SOCK_STREAM)
                if sock.connect_ex(('127.0.0.1',port)) == 0:
                    sys.exit(1)
                sock.close()
        except:
            pass
    
    try:
        vm_indicators = ["vbox","vmware","qemu","virtual","hyper-v"]
        output = subprocess.check_output("systeminfo",shell=True).decode().lower()
        for indicator in vm_indicators:
            if indicator in output:
                sys.exit(1)
    except:
        pass
    
    class SecureString:
        def __init__(self,encrypted,key):
            self.encrypted = encrypted
            self.key = key
        def decrypt(self):
            return ''.join(chr(ord(c)^self.key) for c in self.encrypted)
    
    def verify_integrity():
        with open(__file__,'rb') as f:
            f.read()
        return True

anti_debug_protection()
</pre>

</details>

<hr style="border-color:#333;">

<h4>⚖️ إقرار قانوني وأخلاقي</h4>

باستخدامك لهذه الأداة فإنك:
<ul>
<li>تقر بأنك المالك الشرعي للبرامج التي تقوم بتحويلها أو لديك إذن قانوني صريح بذلك.</li>
<li>تتعهد بعدم استخدامها في أي نشاط غير قانوني أو ضار أو منتهك للحقوق أو يسبب ضرراً تقنياً أو مادياً أو قانونياً للآخرين.</li>
<li>تعفي المطور إبراءً كاملاً ونهائياً من أي تبعات أو مطالبات قانونية أو مالية أو تقنية تنتج عن الاستخدام أو سوء الاستخدام.</li>
<li>تقر بأنك قرأت هذا الإخلاء بالكامل وفهمته وتوافق عليه قبل استخدام الأداة.</li>
</ul>

<div style="margin-top:15px;padding:12px;background:#2a0000;border-radius:6px;">
<strong>⚠️ تنبيه أخير:</strong> أي استخدام غير مشروع أو ضار لهذه الأداة يقع تحت المسؤولية الشخصية الكاملة للمستخدم أمام الجهات القانونية المختصة، ونتبرأ من ذلك في الدنيا والآخرة.
</div>

</div>

---
---




---

### 📬 التواصل

- **المطور**: فهد علي (FAHED ALI)(#)
- **البريد الإلكتروني**: [ps91andr@gmail.com](mailto:ps91andr@gmail.com)(#)
- **غيت هاب**: [@ps91andr](https://github.com/ps91andr)(#)
- **الموقع**: [https://github.com/ps91andr](https://github.com/ps91andr))(#)


---

### ⭐ الدعم
إذا أعجبك المشروع، لا تنسى وضع نجمة ⭐ على غيت هاب!

---

</div>

---

## 🎧 English

<div dir="ltr">

### Overview

**Python to EXE Professional** is a powerful open-source GUI tool designed for developers to convert Python files (`.py`) into executable files (`.exe`) effortlessly. The tool combines the power of **PyInstaller** with **UPX compression**, an integrated Version Info editor, and advanced protection layers.

---

### ✨ Features

| Feature | Description |
|--------|-------------|
| 🔒 **One-File** | Merge all libraries and files into a single EXE file |
| 🕶️ **Hide Console** | Run the program without showing the black command window |
| 📦 **UPX Compression** | Reduce the final EXE size to the maximum (over 50%) |
| 📝 **Version Editor** | Create and edit product info, company name, and program version |
| 📁 **Add Data** | Support adding images, databases, and external files (--add-data) |
| 🛡️ **Anti-Debug Protection** | Built-in protection against debugging tools, virtual environments, and VMs |
| 🖼️ **Icon Preview** | Choose and preview the app icon directly from the interface |
| ⚡ **Drag & Drop** | Smart interface supports dragging files, icons, and even UPX folders |
| 🌐 **Bilingual UI** | Full Arabic & English interface with text direction support |

---

### 🖼️ Screenshots
![Screenshot](https://github.com/ps91andr/ConvertPYtoEXEusingpyInstaller_AR_EN/blob/main/EN.png)

---

### 📦 Direct Download

#### Ready-to-Run Versions (Windows EXE)

| File | Description |
|------|-------------|
| [ConvertPYtoEXE_AR.exe](https://github.com/ps91andr/ConvertPYtoEXEusingpyInstaller_AR_EN/releases/tag/ConvertPYtoEXEusingpyInstaller_AR_EN) | Professional Arabic version – No installation needed |
| [ConvertPYtoEXE_EN.exe](https://github.com/ps91andr/ConvertPYtoEXEusingpyInstaller_AR_EN/releases/tag/ConvertPYtoEXEusingpyInstaller_AR_EN) | Professional English version – No installation needed |

---

### 🚀 How to Use

1. **Select File**: Drag and drop your `.py` file into the program or use the "Browse" button.
2. **Customize Icon**: Choose a `.ico` file as your program’s official icon.
3. **Version Info**: 
   - Click "Create Version File" to add your name and program name.
   - Edit existing version files directly within the program.
4. **Additional Files**: If your program uses images or external files, use the "Add Additional Files" option.
5. **Compression Settings**: Enable **UPX** and select the folder path to reduce size.
6. **Start Conversion**: Click "Convert to EXE" and monitor the output log step by step.

---

### 🎛️ Supported Files

| File Type | Extension | Purpose |
|-----------|----------|---------|
| Python Script | `.py` | Main source file to convert |
| Icon File | `.ico` | Official application icon |
| Version Info | `.txt` | File containing product and copyright info |
| UPX Tool | `upx.exe` | Optional tool for compressing the EXE |

---

### ⚖️ Disclaimer

<div dir="ltr" style="background-color:#1e1e1e;padding:20px;border-radius:8px;border-left:6px solid #ff4b4b;line-height:1.9;font-size:15px;color:#ffffff;font-family:Tahoma,Arial,sans-serif;">

<h3 style="margin-top:0;">🔴 Important – Please Read Carefully Before Use</h3>

This tool is a utility for developers and professionals, intended for <strong>legal and professional use only</strong>.  
By using this tool, you explicitly agree to the following terms and accept full responsibility for any use of the resulting files or software:

<ul>
<li>You are fully responsible for all programs or files you convert, process, or distribute using this tool.</li>
<li>You will not use the tool or any of its features — including protection, obfuscation, or Anti-Debug — to hide, protect, or distribute malicious, harmful, illegal, or infringing software.</li>
<li>The developer is not responsible for any illegal use, violations of local or international laws, platform terms, or unlicensed use of the resulting software.</li>
<li>Conversion may, in some cases, result in loss of code or errors, so you are responsible for <strong>backing up your original source code</strong> before any conversion or modification.</li>
<li>The developer is not liable for data loss, file corruption, direct or indirect damages, or operational, financial, or technical losses from use, misuse, or negligence.</li>
<li>Compatibility of the resulting software with operating systems or versions depends on your development environment, libraries, and build settings, not solely on the tool.</li>
</ul>

<hr style="border-color:#333;">

<h4>🔐 About Anti-Debug Protection</h4>

The built-in protection feature aims to:
<ul>
<li>Reduce simple reverse engineering attempts.</li>
<li>Add an initial protection layer to your code or resulting program.</li>
</ul>

<p><strong>⚠️ Note:</strong> Anti-Debug provides basic protection against simple reverse engineering but is not absolute protection against experts.</p>

<ul>
<li>This feature is not absolute security.</li>
<li>It does not guarantee prevention of analysis, hacking, or advanced disassembly by experts.</li>
<li>It should not be relied on as the sole security measure for sensitive projects.</li>
</ul>

<hr style="border-color:#333;">

<h4>🛠️ How to Enable Anti-Debug</h4>

To apply Anti-Debug to your Python script:

<ul>
<li>Paste the protection code at the top of the file to convert.</li>
<li>Paste it directly after import statements.</li>
<li>Call the function once at program start.</li>
</ul>

<details style="margin-top:10px;">
<summary style="cursor:pointer;font-weight:bold;color:#ffb3b3;">
📄 Click to show/hide Anti-Debug code
</summary>

<pre style="background:#111;padding:12px;border-radius:6px;overflow:auto;direction:ltr;color:#e6e6e6;">
import sys
import os
import ctypes
import socket
import subprocess

def anti_debug_protection():
    """Multiple protection layers"""
    
    debug_indicators = [
        'PYCHARM_HOSTED','PYDEV_CONSOLE_ENCODING',
        'PYTHONDEVMODE','PYTHONINSPECT'
    ]
    
    for indicator in debug_indicators:
        if indicator in os.environ:
            sys.exit(1)
    
    if os.name == 'nt':
        try:
            if ctypes.windll.kernel32.IsDebuggerPresent():
                sys.exit(1)
            
            debug_ports = [5858,5859,5678,21000,21001]
            for port in debug_ports:
                sock = socket.socket(socket.AF_INET,socket.SOCK_STREAM)
                if sock.connect_ex(('127.0.0.1',port)) == 0:
                    sys.exit(1)
                sock.close()
        except:
            pass
    
    try:
        vm_indicators = ["vbox","vmware","qemu","virtual","hyper-v"]
        output = subprocess.check_output("systeminfo",shell=True).decode().lower()
        for indicator in vm_indicators:
            if indicator in output:
                sys.exit(1)
    except:
        pass
    
    class SecureString:
        def __init__(self,encrypted,key):
            self.encrypted = encrypted
            self.key = key
        def decrypt(self):
            return ''.join(chr(ord(c)^self.key) for c in self.encrypted)
    
    def verify_integrity():
        with open(__file__,'rb') as f:
            f.read()
        return True

anti_debug_protection()
</pre>

</details>

<hr style="border-color:#333;">

<h4>⚖️ Legal & Ethical Acknowledgment</h4>

By using this tool you:

<ul>
<li>Confirm you are the legitimate owner of the software you convert or have explicit legal permission.</li>
<li>Agree not to use it for illegal, harmful, infringing, or damaging activities.</li>
<li>Release the developer from any legal, financial, or technical liability arising from usage or misuse.</li>
<li>Acknowledge you have read and understood this disclaimer fully and agree before using the tool.</li>
</ul>

<div style="margin-top:15px;padding:12px;background:#2a0000;border-radius:6px;">
<strong>⚠️ Final Warning:</strong> Any illegal or harmful use is the user’s sole responsibility before relevant authorities. The developer disclaims all liability.
</div>

</div>

---

### 📬 Contact

- **Developer**: Fahed Ali (FAHED ALI)(#)  
- **Email**: [ps91andr@gmail.com](mailto:ps91andr@gmail.com)(#)  
- **GitHub**: [@ps91andr](https://github.com/ps91andr)(#)  
- **Website**: [https://github.com/ps91andr](https://github.com/ps91andr)(#)  

---

### ⭐ Support
If you like the project, don’t forget to give a ⭐ on GitHub!

---

</div>

<div align="center">
  
  ---
  
  **صنع بحب للمجتمع البرمجي العربي والعالمي** ❤️  
  **Made with love for the Dev Community**
  
  <sub>© 2026 FAHED ALI. Professional Python Tools.</sub>
  
</div>
