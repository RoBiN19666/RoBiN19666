<div align="center">

# RoBiN19666

**Локальные панели для умных устройств · инструменты для школы · self-hosted без облака**

[![MidiPult — панель для Станции Миди](https://img.shields.io/badge/MidiPult-%D0%BF%D0%B0%D0%BD%D0%B5%D0%BB%D1%8C_%D0%B4%D0%BB%D1%8F_%D0%A1%D1%82%D0%B0%D0%BD%D1%86%D0%B8%D0%B8_%D0%9C%D0%B8%D0%B4%D0%B8-6C5CE7?style=for-the-badge&logo=linux&logoColor=white)](https://github.com/RoBiN19666/midipult)
[![OlympClock — часы и таймер для олимпиад](https://img.shields.io/badge/OlympClock-%D1%87%D0%B0%D1%81%D1%8B_%D0%B8_%D1%82%D0%B0%D0%B9%D0%BC%D0%B5%D1%80_%D0%B4%D0%BB%D1%8F_%D0%BE%D0%BB%D0%B8%D0%BC%D0%BF%D0%B8%D0%B0%D0%B4-D97706?style=for-the-badge&logo=html5&logoColor=white)](https://github.com/RoBiN19666/olymp-clock)
[![School Journal — электронный журнал](https://img.shields.io/badge/School_Journal-%D1%8D%D0%BB%D0%B5%D0%BA%D1%82%D1%80%D0%BE%D0%BD%D0%BD%D1%8B%D0%B9_%D0%B6%D1%83%D1%80%D0%BD%D0%B0%D0%BB-2563EB?style=for-the-badge&logo=django&logoColor=white)](https://github.com/RoBiN19666/school-journal)

![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=flat-square&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-5-092E20?style=flat-square&logo=django&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-16-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-vanilla-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-compose-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-embedded-FCC624?style=flat-square&logo=linux&logoColor=black)

</div>

---

## О себе

Сисадмин по профессии, вайбкодер по вечерам: делаю то, чем потом пользуюсь сам.

## Избранное

### MidiPult

<p align="center">
  <a href="https://github.com/RoBiN19666/midipult">
    <img src="https://raw.githubusercontent.com/RoBiN19666/midipult/main/docs/img/logo.png?v=5" alt="MidiPult — локальная панель Яндекс Станции Миди" width="520">
  </a>
</p>

Локальная веб-панель для рутованной **Яндекс Станции Миди**: дисплей,
LED-кольцо, плеер, радио, голосовые команды, нейросеть, VPN, сценарии,
свои звуки и IPv6.

- лёгкий интерфейс на чистом HTML/CSS/JS;
- Python CGI + `lighttpd` на самой колонке;
- установщик с проверкой зависимостей и автозапуском;
- безопасное удаление с бэкапом;
- MIT License.

[![Release](https://img.shields.io/github/v/release/RoBiN19666/midipult?style=flat-square&label=release)](https://github.com/RoBiN19666/midipult/releases)
[![License](https://img.shields.io/github/license/RoBiN19666/midipult?style=flat-square&label=license)](https://github.com/RoBiN19666/midipult/blob/main/LICENSE)

[Репозиторий](https://github.com/RoBiN19666/midipult) · [Релизы](https://github.com/RoBiN19666/midipult/releases) · [Документация](https://github.com/RoBiN19666/midipult#readme)

### OlympClock

<p align="center">
  <a href="https://github.com/RoBiN19666/olymp-clock">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/RoBiN19666/olymp-clock/main/assets/logo-dark.png?v=2">
      <img src="https://raw.githubusercontent.com/RoBiN19666/olymp-clock/main/assets/logo-light.png" alt="OlympClock — часы и таймер для олимпиад" width="420">
    </picture>
  </a>
</p>

**OlympClock** — часы, расписание и таймер для олимпиад: один HTML-файл, работает без интернета.
Есть APK для досок, которые вообще не открывают `.html`, встроенный плеер для аудирования,
часовые пояса и проверка обновлений прямо из приложения.

[Репозиторий](https://github.com/RoBiN19666/olymp-clock) ·
[Открыть в браузере](https://robin19666.github.io/olymp-clock/) ·
[Скачать APK](https://github.com/RoBiN19666/olymp-clock/releases/latest)

### School Journal

<p align="center">
  <a href="https://github.com/RoBiN19666/school-journal">
      <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/RoBiN19666/school-journal/main/docs/branding/logo-wordmark-light.png?v=2">
    <img src="https://raw.githubusercontent.com/RoBiN19666/school-journal/main/docs/branding/logo-wordmark-dark.png" alt="School Journal — электронный журнал посещаемости" width="420">
  </picture>
  </a>
</p>

Электронный журнал посещаемости для образовательной организации: ученики и группы,
расписание по адресам и полугодиям, отметки, темы занятий с академическими часами,
отсутствия преподавателей и подмены, конкурсы, выгрузки в Excel и картинкой.

- Django 5 + PostgreSQL 16, интерфейс на Tailwind без сборки Node.js;
- установка одной командой в Docker, мастер первичной настройки;
- полностью двуязычный интерфейс (русский и английский);
- MIT License.

[![Release](https://img.shields.io/github/v/release/RoBiN19666/school-journal?style=flat-square&label=release)](https://github.com/RoBiN19666/school-journal/releases)
[![License](https://img.shields.io/github/license/RoBiN19666/school-journal?style=flat-square&label=license)](https://github.com/RoBiN19666/school-journal/blob/main/LICENSE)

[Репозиторий](https://github.com/RoBiN19666/school-journal) · [Документация](https://github.com/RoBiN19666/school-journal/blob/main/docs/admin-guide.md)
## Стек

`Python` · `JavaScript` · `HTML/CSS` · `lighttpd` · `Linux` · `Entware` · `Git`

## Связаться

Вопросы и баги по проектам — через **Issues** в соответствующем репозитории.

---

<div align="center">
  <sub>Сделано на своём устройстве, для своего устройства.</sub>
</div>
