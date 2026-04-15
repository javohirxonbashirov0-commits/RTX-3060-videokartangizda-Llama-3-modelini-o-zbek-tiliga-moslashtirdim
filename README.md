# RTX-3060-videokartamda-Llama-3-modelini-o-zbek-tiliga-moslashtirdim
🚀 Mening Birinchi LLM Fine-Tuning Loyiham: Llama-3-Uzbek
Ushbu loyihada men dunyodagi eng kuchli ochiq manbali til modellaridan biri bo'lgan Llama-3 (8B) modelini o'zimning shaxsiy kompyuterimda (NVIDIA RTX 3060) o'zbek tilida so'zlashishga o'rgatdim.

🤖 Loyiha haqida qisqacha
Ushbu loyihaning maqsadi — umumiy bilimlarga ega bo'lgan sun'iy intellektni maxsus o'zbekcha dataset yordamida "Fine-tune" qilish va uni Data Science hamda mahalliy ma'lumotlar bo'yicha mutaxassisga aylantirishdir.

🛠 Texnologik uskunalari (Tech Stack)
Men modelni samarali o'qitish uchun quyidagi zamonaviy texnologiyalardan foydalandim:

Model: Llama-3-8B (Meta)

Framework: Unsloth (O'qitishni 2-5 baravar tezlashtiradi)

Texnika: QLoRA (4-bitli kvantlash orqali modelni kichraytirish)

GPU: NVIDIA RTX 3060 (12GB VRAM)

🧠 Fine-Tuning nima va u qanday ishladi?
Tasavvur qiling, Llama-3 — bu dunyo kutubxonalaridagi barcha kitoblarni o'qigan talaba. Men unga o'zbekcha maxsus "darslik" (Dataset) berdim va faqat kerakli qismlarini o'zgartirdim.

O'qitish jarayoni:
Dataset tayyorlash: O'zbekiston poytaxtlari va Data Science terminlari bo'yicha JSON formatidagi ma'lumotlar bazasi yaratildi.

LoRA Adapters: Modelning barcha 8 milliard parametrini emas, faqat kichik bir qismini (LoRA Rank = 16) o'zgartirdim. Bu videokarta xotirasini tejashga yordam berdi.

Training: Unsloth yordamida model 60 qadamda (steps) yangi bilimlarni o'zlashtirdi.

📊 Natijalar (Inference)
Modelga berilgan savol va uning javobi:

Savol: Turkiya poytaxti qayer? AI Javobi: Turkiya poytaxti Ankara. ✅

Savol: Machine Learning nima? AI Javobi: Machine Learning — bu kompyuterlarga ma'lumotlar asosida mustaqil qaror qabul qilishni o'rgatuvchi AI sohasi. ✅

🌟 Nega bu juda muhim?
Ko'pchilik AI modellarni o'qitish uchun minglab dollarlik serverlar kerak deb o'ylaydi. Lekin ushbu loyiha shuni isbotladiki:

Sizning uyingizdagi RTX 3060 ham kuchli AI yaratishga qodir!

O'zbek tili sun'iy intellekt olamida o'z o'rniga ega bo'lishi mumkin.

ML o'rganish — bu nafaqat matematika, balki ijodkorlik va texnologiyani birlashtirishdir.

👨‍💻 Qanday qilib o'rganishni boshlash kerak?
Agar siz ham ML olamiga kirmoqchi bo'lsangiz, mana mening maslahatlarim:

Pythonni o'rganing: Bu AI tilidir.

Kutubxonalar: Pandas, NumPy va PyTorch bilan tanishing.

Unsloth va HuggingFace: Tayyor modellarni o'zgartirishni (Fine-tuning) sinab ko'ring.
