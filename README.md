# POCO M5 Audio Emoji (Google Dialer Fart & Sound Reactions)

**POCO M5 (MediaTek Helio G99 / MT6789) — HyperOS Global / MIUI**  
Модуль Magisk + LSPosed для включения эксклюзивной функции Google Pixel **«Звуковые эмодзи»** (Audio Emoji) в приложении «Google Телефон» (`com.google.android.dialer`).

---

## 🔥 Возможности

* 💩 **Пердёж в звонке (Fart reaction)**
* 👏 **Аплодисменты (Applause)**
* 🥁 **Барабанная дробь и тарелка (Ba-dum-tss)**
* 🎉 **Праздник (Party horn)**
* 😢 **Унылый тромбон (Sad trombone)**
* 😂 **Смех (Laugh)**
* 🔊 **Оба абонента слышат звук:** звук маршрутизируется напрямую в голосовой тракт звонка (`USAGE_VOICE_COMMUNICATION` / `STREAM_VOICE_CALL`), гарантированно обходя ограничения аудиодрайвера MediaTek Helio G99.
* 🎯 **Безопасный точечный спуфинг:** подменяет `Pixel 8 Pro` исключительно внутри процесса Google Телефон. Камера HyperOS, 90 Гц герцовка экрана и системные настройки POCO M5 остаются нетронутыми!
* 🛡️ **Play Integrity / DenyList Safe:** Сервисы Google Play (`com.google.android.gms`) **НЕ затрагиваются** и остаются в Magisk DenyList / Shamiko. Банки, Mir Pay и верификация устройства не слетают!
* 🚀 **Плавающий In-Call интерфейс:** во время разговора поверх экрана звонка появляется кнопка с красивой анимацией взлетающих вверх эмодзи.

---

## 📦 Установка

1. Скачайте **`MirageAudioEmoji-Magisk-v1.0.zip`** из вкладки [Releases](https://github.com/Mor4land/poco-audio-emoji/releases).
2. Прошейте архив в **Magisk** (или KernelSU / APatch).
3. Перезагрузите устройство.
4. Откройте **LSPosed Manager**, найдите модуль **POCO M5 Audio Emoji** и активируйте его. Область применения:
   * **Телефон** (`com.google.android.dialer`) — *и всё! Сервисы Google Play трогать НЕ нужно, они должны оставаться в DenyList.*
5. Сделайте звонок через Google Телефон — на экране появится плавающая кнопка `[💩 Звуки в звонке]`.

---

## 🛠 Автор
Разработано Mirage (@Mor4land) для POCO M5.
