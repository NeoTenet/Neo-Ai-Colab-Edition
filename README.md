<div align="center">

# ⚡ NeoTenet AI Labs

### ابزارهای هوش مصنوعی برای ساخت و ویرایش تصویر و تولید موسیقی

**پروژه‌های اختصاصی ساخته‌شده توسط NeoTenet**

<p>
  <a href="https://t.me/NeoTenet"><img src="https://img.shields.io/badge/Telegram-NeoTenet-2AABEE?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram NeoTenet"></a>
  <img src="https://img.shields.io/badge/Platform-Google%20Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white" alt="Google Colab">
  <img src="https://img.shields.io/badge/Language-Persian%20%7C%20English-7952B3?style=for-the-badge" alt="Persian and English">
  <img src="https://img.shields.io/badge/License-All%20Rights%20Reserved-red?style=for-the-badge" alt="All Rights Reserved">
</p>

<p>
  <a href="#-شروع-سریع--quick-start">🚀 شروع سریع</a> ·
  <a href="#-qwen-image-21--neotenet-edition">🖼️ Qwen Image 2.1</a> ·
  <a href="#-yue-20--music-studio">🎵 YuE 2.0</a> ·
  <a href="#-مجوز-و-کپی‌رایت--license--copyright">🔒 کپی‌رایت</a>
</p>

---

**فارسی:** دو نوت‌بوک مستقل Google Colab برای ویرایش تصویر با هوش مصنوعی و تولید موسیقی؛ با گردش‌کارها و تنظیمات اختصاصی NeoTenet.

**English:** Two independent Google Colab notebooks for AI image editing and AI music generation, featuring NeoTenet-focused workflows and configuration.

</div>

---

## 🚀 شروع سریع | Quick Start

**فارسی:** روی دکمه‌ی `Open in Colab` پروژه‌ی دلخواه کلیک کن. سپس در Google Colab از مسیر `Runtime → Change runtime type` گزینه‌ی GPU را انتخاب کن و سلول‌ها را به‌ترتیب اجرا کن.

**English:** Click **Open in Colab** for the notebook you want to use. In Colab, select `Runtime → Change runtime type → GPU`, then run the cells from top to bottom.

> **تنظیم لینک‌ها | Link setup:** پس از انتشار این فایل در GitHub، عبارت `YOUR_GITHUB_USERNAME/YOUR_REPOSITORY` را در لینک‌های این README با نام کاربری و نام مخزن واقعی خود جایگزین کن.

## 🖼️ Qwen Image 2.1 — NeoTenet Edition

<div align="center">

### نوت‌بوک ویرایش تصویر با مدل کوانتایز‌شده | Quantized Image Editing Notebook

<a href="https://colab.research.google.com/github/YOUR_GITHUB_USERNAME/YOUR_REPOSITORY/blob/main/Qwen_Image_2_1_NeoTenet_Edition.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open Qwen Image 2.1 in Google Colab"></a>
&nbsp;
<a href="https://github.com/YOUR_GITHUB_USERNAME/YOUR_REPOSITORY/blob/main/Qwen_Image_2_1_NeoTenet_Edition.ipynb"><img src="https://img.shields.io/badge/View_Notebook-GitHub-181717?style=flat&logo=github&logoColor=white" alt="View Qwen notebook on GitHub"></a>

</div>

### 🇮🇷 معرفی فارسی

این نوت‌بوک برای اجرای گردش‌کار ویرایش تصویر Qwen Image 2.1 در Google Colab آماده شده است. نسخه‌ی ارائه‌شده از اجزای کوانتایز‌شده و تنظیمات بهینه‌سازی حافظه استفاده می‌کند تا اجرای مدل در محیط GPU سازگارتر باشد.

**ویژگی‌های اصلی**
- استفاده از اجزای مدل با دقت INT8، طبق تنظیمات نوت‌بوک.
- ویرایش تصویر با دستور متنی و استفاده از تصاویر مرجع.
- پشتیبانی از چند جایگاه تصویر مرجع؛ جایگاه اول تصویر اصلی و جایگاه‌های دیگر برای ارجاع بصری.
- مسیر کاری Alpha/RGBA طبق پیاده‌سازی موجود در نوت‌بوک.
- تنظیمات مرتبط با حافظه و اجرای GPU، از جمله تنظیمات CUDA و اجزای بهینه‌سازی‌شده‌ی تعریف‌شده در کد.
- رابط کاربری اختصاصی NeoTenet و فرایند راه‌اندازی رابط.

### 🇬🇧 English Overview

This notebook packages a Google Colab workflow for Qwen Image 2.1 image editing. It uses quantized components and memory-oriented settings intended to make the workflow more practical on compatible GPU runtimes.

**Key features**
- INT8 model components, as configured in the notebook.
- Instruction-guided image editing with optional reference images.
- Multiple image-reference slots: the first slot is the primary image, while additional slots can guide visual attributes.
- An Alpha/RGBA workflow as implemented in the notebook.
- CUDA and other GPU/memory optimization settings included in the code.
- A NeoTenet-branded interface and launch workflow.

**Notebook:** `Qwen_Image_2_1_NeoTenet_Edition.ipynb`

---

## 🎵 YuE 2.0 — Music Studio

<div align="center">

### نوت‌بوک تولید موسیقی با هوش مصنوعی | AI Music Generation Notebook

<a href="https://colab.research.google.com/github/YOUR_GITHUB_USERNAME/YOUR_REPOSITORY/blob/main/Yue2_Music_Genrator_Turbo_3B_Version_Fix.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open YuE 2.0 in Google Colab"></a>
&nbsp;
<a href="https://github.com/YOUR_GITHUB_USERNAME/YOUR_REPOSITORY/blob/main/Yue2_Music_Genrator_Turbo_3B_Version_Fix.ipynb"><img src="https://img.shields.io/badge/View_Notebook-GitHub-181717?style=flat&logo=github&logoColor=white" alt="View YuE notebook on GitHub"></a>

</div>

### 🇮🇷 معرفی فارسی

این نوت‌بوک برای اجرای گردش‌کار تولید موسیقی با YuE 2.0 در Google Colab طراحی شده است. کاربر می‌تواند سبک موسیقی، متن ترانه و تنظیمات ارائه‌شده در رابط نوت‌بوک را مشخص کند و خروجی صوتی تولیدشده را دریافت کند.

**ویژگی‌های اصلی**
- گردش‌کار تولید موسیقی با مدل YuE 2.0 3B در قالب FP16، طبق تنظیمات نوت‌بوک.
- انتخاب سبک‌های پیشنهادی و واردکردن سبک دلخواه.
- امکان ارائه‌ی متن ترانه و توضیحات سبکی.
- نصب و اجرای ComfyUI و وابستگی‌های موردنیاز توسط سلول‌های نوت‌بوک.
- گزینه‌های اجرای کم‌مصرف‌تر از نظر VRAM، مطابق تنظیمات کد.
- جمع‌آوری خروجی‌های صوتی و آماده‌سازی آن‌ها برای دریافت ZIP.

### 🇬🇧 English Overview

This notebook provides a Google Colab workflow for AI music generation with YuE 2.0. Users can configure a musical style, provide lyrics and use the available notebook controls to generate audio.

**Key features**
- YuE 2.0 3B FP16 checkpoint workflow, as configured in the notebook.
- Built-in style presets and a custom-style option.
- User-provided lyrics and style descriptions.
- Notebook-managed ComfyUI setup and required dependencies.
- VRAM-conscious launch options included in the code.
- Collection of generated audio files into a downloadable ZIP archive.

**Notebook:** `Yue2_Music_Genrator_Turbo_3B_Version_Fix.ipynb`

---

## 🧰 نیازمندی‌ها | Requirements

- حساب Google و دسترسی به Google Colab.
- فعال‌بودن یک Runtime دارای GPU سازگار؛ دسترسی GPU در Colab رایگان تضمین‌شده نیست.
- فضای ذخیره‌سازی و اینترنت کافی برای دریافت مدل‌ها و وابستگی‌ها.
- اجرای سلول‌ها به‌ترتیب و بررسی پیام‌ها و خطاهای هر نوت‌بوک.

**نکته | Note:** زمان اجرا، حافظه‌ی مصرفی و در دسترس بودن GPU بسته به Runtime، مدل و تنظیمات انتخابی متغیر است. اجرای موفق در همه‌ی نشست‌ها تضمین نمی‌شود.

## 🛡️ نکات استفاده | Usage Notes

- پیش از اجرا، کد سلول‌ها و منابعی را که دریافت می‌شوند بررسی کن.
- توکن‌ها، اطلاعات ورود، فایل‌های خصوصی یا داده‌های حساس را از طریق تونل عمومی منتشر نکن.
- وزن‌های مدل و وابستگی‌های ثالث ممکن است شرایط مجوز جداگانه‌ای داشته باشند؛ شرایط رسمی آن‌ها را بررسی کن.
- نام‌ها و علائم تجاری پروژه‌های ثالث متعلق به صاحبان آن‌ها هستند.

---

## 🔒 مجوز و کپی‌رایت | License & Copyright

**© NeoTenet — All Rights Reserved.**

**فارسی:** حقوق بخش‌هایی از کد، رابط کاربری، سازمان‌دهی نوت‌بوک و محتوای اصلی که توسط NeoTenet ایجاد شده‌اند، برای NeoTenet محفوظ است. بدون اجازه‌ی کتبی قبلی، کپی‌برداری، بازنشر، توزیع، فروش، ارائه‌ی نسخه‌ی آینه‌ای یا انتشار نسخه‌ی تغییر‌یافته از بخش‌های متعلق به NeoTenet مجاز نیست.

**English:** The NeoTenet-authored code, custom interface, notebook organization, and original project content are reserved by NeoTenet. Prior written permission is required to copy, republish, redistribute, sell, mirror, sublicense, or publish modified versions of NeoTenet-authored portions.

- این مخزن برای بخش‌های متعلق به NeoTenet مجوز متن‌باز یا مجوز استفاده‌ی مجدد اعطا نمی‌کند.
- عمومی‌بودن مخزن در GitHub به‌معنای اجازه‌ی کپی یا بازتوزیع نیست.
- این اعلامیه شامل مالکیت آثار اشخاص ثالث نمی‌شود؛ کدها، مدل‌ها و وزن‌های ثالث تابع مجوز و شرایط صاحبان خود هستند.
- در صورت مشاهده‌ی استفاده یا بازنشر غیرمجاز، شواهد را نگه دارید و گزارش مربوطه را از مسیر رسمی GitHub یا پلتفرم میزبان ارسال کنید. پذیرش گزارش یا مسدودشدن حساب به بررسی پلتفرم و قوانین مربوط بستگی دارد.
- بدون اجازه‌ی صریح صاحب حقوق، مجوزهایی مانند MIT، Apache-2.0 یا GPL را به بخش‌های متعلق به NeoTenet نسبت ندهید.

> **یادآوری حقوقی | Legal note:** این متن یک اعلامیه‌ی کپی‌رایت برای پروژه است و مشاوره‌ی حقوقی محسوب نمی‌شود. حفاظت قانونی و امکان پیگیری به حوزه‌ی قضایی و مالکیت واقعی هر بخش بستگی دارد. مجوزهای مدل‌ها و اجزای ثالث باید جداگانه بررسی شوند.

---

## 🙌 اعتبارها | Credits

این پروژه‌ها از ابزارها، کتابخانه‌ها و مدل‌های ثالث استفاده می‌کنند یا ممکن است در زمان اجرا آن‌ها را دریافت کنند؛ از جمله:

- [ComfyUI](https://github.com/comfyanonymous/ComfyUI)
- [Qwen models](https://huggingface.co/Qwen)
- [YuE](https://github.com/multimodal-art-projection/YuE)
- [Hugging Face](https://huggingface.co/)
- PyTorch و سایر وابستگی‌هایی که در نوت‌بوک نصب می‌شوند.

این پیوندها برای ارجاع و شناسایی منابع هستند و به‌معنای تأیید یا حمایت رسمی از سوی پروژه‌های یادشده نیستند. پیش از استفاده یا بازتوزیع، مجوزهای بالادستی را مطالعه کنید.

---

## 📡 ارتباط با NeoTenet | Connect

<div align="center">

**برای خبرها، به‌روزرسانی‌ها و پروژه‌های بیشتر به کانال تلگرام NeoTenet بپیوندید.**

**Follow NeoTenet on Telegram for updates and future projects.**

<a href="https://t.me/NeoTenet"><img src="https://img.shields.io/badge/Telegram-Join%20NeoTenet-2AABEE?style=for-the-badge&logo=telegram&logoColor=white" alt="Join NeoTenet on Telegram"></a>

<br><br>

**ساخته‌شده با ⚡ توسط NeoTenet | Built with ⚡ by NeoTenet**

</div>
