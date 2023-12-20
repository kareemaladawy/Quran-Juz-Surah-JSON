# Quran-Juz-Surah-JSON
JSON files containing structured data about the Quran's parts (juz) and surahs, intended for developers and researchers. 
Includes information about surah names, number of verses, revelation order, and more. 
Use this data for applications, websites, or research projects.

## Contents

- **[quran_juzs.json](./quran_juzs.json):** JSON array with details about the 30 parts of the Quran.
- **[quran_surahs.json](./quran_surahs.json):** JSON array containing information about each surah, including name, number, verses, starts_at_juz, ends_at_juz and more.

## How to Use

Clone the repository or download the individual JSON files to integrate Quranic data into your projects. Feel free to contribute or use the data for research, applications, or educational purposes.

## Examples

### Juz' Information (Example)

```json
{
    "id": 1,
    "name": "Juz' 1",
    "name_ar": "الجزء الأول",
    "number": 1
}
```

### Surah Information (Example)

```json
{
    "id": 1,
    "name_ar": "الفاتحة",
    "name": "Al-Fatihah",
    "type": "meccan",
    "type_ar": "مكية",
    "total_verses": 7,
    "starts_at_juz": 1,
    "ends_at_juz": 1
}
