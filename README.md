# 🔌 GreenAutoPilot Plugins Collection

![Community](https://img.shields.io/badge/Community-Driven-orange?style=for-the-badge&logo=github)
![NVIDIA](https://img.shields.io/badge/GPU-RTX%20%7C%20GTX-76b900?style=for-the-badge&logo=nvidia)
![Format](https://img.shields.io/badge/Format-JSON-lightgrey?style=for-the-badge&logo=json)

Добро пожаловать в официальную базу пресетов для **[GreenAutoPilot](https://github.com/Fasdeq/GreenAutoPilot)**.
Здесь собраны оптимизированные `.json` конфигурации для разных моделей видеокарт NVIDIA.

> **Зачем это нужно?**
> Вам не нужно вручную искать стабильные частоты и лимиты питания. Просто найдите свою карту, скачайте файл и закиньте его в папку с программой.

---

## 📂 Как установить плагин

1. **Найдите файл** для вашей видеокарты в списке файлов (например, `rtx_3060_msi_ventus.json` или просто `rtx_3060.json`).
2. **Скачайте его** (Raw -> Save As).
3. **Переименуйте** файл так, чтобы он соответствовал тому, как вашу карту видит драйвер (обычно достаточно упростить до `rtx_3060.json`).
4. **Положите файл** в папку `plugins/` рядом с исполняемым файлом `GreenAutoPilot`.

Структура папок должна выглядеть так:
```text
My_App_Folder/
├── GreenAutoPilot       (Бинарник программы)
└── plugins/             (Папка с конфигами)
    ├── rtx_4090.json
    └── rtx_3060.json
