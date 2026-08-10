# STUDY-HELPER-AI---N8N
# AI Educational Telegram Bot (n8n Workflow)

[English](#-english) | [فارسی](#-فارسی)

---

## 🇬🇧 English

An intelligent n8n workflow that powers a Telegram bot designed to help users study and learn through text, images, and voice messages. Powered by OpenAI's GPT-4o-mini, it acts as a knowledgeable academic tutor.

### 🌟 Features

- **Multi-Modal Input Processing:** Handles text, images, and voice messages seamlessly.
- **AI-Powered Tutoring:** Uses OpenAI's `gpt-4o-mini` to act as a knowledgeable and kind academic tutor.
- **Image Analysis:** Extracts data from images, analyzes them, and explains the concepts visually and textually.
- **Voice Transcription:** Converts voice notes to text and processes them for learning.
- **Bilingual Support:** Explains image concepts and complex topics in both Persian and English (formulas and operations always remain in English).
- **Contextual Memory:** Remembers the context of the conversation using a window buffer memory for continuous and coherent learning.

### ⚙️ Prerequisites

- An active **n8n** instance (self-hosted or cloud).
- **Telegram Bot API** credentials (Bot Token from BotFather).
- **OpenAI API** Key.

### 🚀 Installation & Setup

1. Open your n8n dashboard.
2. Go to the **Workflows** section and click **Add workflow** -> **Import from File**.
3. Upload the `.json` workflow file from this repository.
4. Set up your credentials in n8n:
   - Create a **Telegram API** credential using your Bot Token.
   - Create an **OpenAI API** credential using your OpenAI API Key.
5. Assign the created credentials to the respective nodes in the workflow (Telegram Trigger, Telegram nodes, and OpenAI nodes).
6. Click **Active** to turn on the workflow.

### 📱 How to Use

- **Text Messages:** Send a topic or question, and the bot will summarize and explain it to you.
- **Images:** Send a photo (e.g., a textbook page or a diagram). The bot will analyze it and teach you the concepts in both Persian and English.
- **Voice Messages:** Send a voice note. The bot will transcribe it and explain the contents.

### 🤝 Contributing

Feel free to fork this repository, modify the workflow, and submit a pull request to improve the AI tutor's capabilities!

---

## 🇮🇷 فارسی

# ربات آموزشی تلگرام مبتنی بر هوش مصنوعی (ورک‌فلو n8n)

یک ورک‌فلو هوشمند در n8n که یک ربات تلگرامی را برای کمک به مطالعه و یادگیری کاربران از طریق پیام‌های متنی، تصویری و صوتی مدیریت می‌کند. این ربات با استفاده از مدل GPT-4o-mini شرکت OpenAI، نقش یک دستیار و معلم آموزشی دانا و مهربان را ایفا می‌کند.

### 🌟 ویژگی‌ها

- **پردازش ورودی‌های چندگانه:** پشتیبانی یکپارچه از پیام‌های متنی، عکس و ویس (صوت).
- **آموزش مبتنی بر هوش مصنوعی:** استفاده از مدل `gpt-4o-mini` برای ایفای نقش یک معلم و دستیار آموزشی دانا.
- **تحلیل تصویر:** بررسی تصاویر ارسال شده، استخراج داده‌ها و آموزش مفاهیم موجود در آن‌ها.
- **تبدیل صدا به متن:** تبدیل پیام‌های صوتی به متن و پردازش آن‌ها برای یادگیری بهتر.
- **پشتیبانی از دو زبان:** ارائه توضیحات به هر دو زبان فارسی و انگلیسی (فرمول‌ها و عملیات‌های ریاضی همیشه به انگلیسی خواهند بود).
- **حافظه مکالمه:** به یاد آوردن تاریخچه چت با استفاده از حافظه بافر برای ارائه پاسخ‌های دقیق‌تر و پیوسته.

### ⚙️ پیش‌نیازها

- یک نمونه فعال از **n8n** (هاست شخصی یا فضای ابری).
- اطلاعات API ربات تلگرام (توکن ربات از BotFather).
- کلید API شرکت OpenAI.

### 🚀 نصب و راه‌اندازی

۱. وارد پنل کاربری n8n خود شوید.
۲. به بخش **Workflows** بروید و روی **Add workflow** و سپس **Import from File** کلیک کنید.
۳. فایل `.json` ورک‌فلو را از این مخزن آپلود کنید.
۴. اعتبارنامه‌های (Credentials) خود را در n8n تنظیم کنید:
   - یک Credential برای **Telegram API** با استفاده از توکن ربات خود بسازید.
   - یک Credential برای **OpenAI API** با استفاده از کلید API خود بسازید.
۵. اعتبارنامه‌های ساخته شده را به نودهای مربوطه در ورک‌فلو (نودهای تلگرام و OpenAI) اختصاص دهید.
۶. ورک‌فلو را فعال (**Active**) کنید.

### 📱 نحوه استفاده

- **پیام متنی:** یک موضوع یا سوال بفرستید؛ ربات آن را خلاصه کرده و به شما آموزش می‌دهد.
- **عکس:** یک عکس (مثلاً از یک صفحه کتاب یا نمودار) بفرستید تا ربات آن را تحلیل کرده و مفاهیم آن را به فارسی و انگلیسی آموزش دهد.
- **پیام صوتی:** یک ویس بفرستید تا ربات آن را به متن تبدیل کرده و محتوای آن را توضیح دهد.

### 🤝 مشارکت

برای بهبود قابلیت‌های این ربات آموزشی، می‌توانید این مخزن را Fork کرده، ورک‌فلو را تغییر دهید و Pull Request ثبت کنید!
