**English** | [简体中文](./zh/README.md) | [日本語](./ja/README.md) | [한국어](./ko/README.md) | [Türkçe](./tr/README.md) | [Русский](./ru/README.md)
# Realme GT neo5 Пользовательское ядро

## ПРЕДУПРЕЖДЕНИЕ: Ваша гарантия больше недействительна!

Я **не несу ответственности** заbrickнутые устройства, поврежденное оборудование или любые проблемы, возникающие из-за использования этого ядра.

**Пожалуйста**, проведите тщательное исследование и полностью понимайте функции, включенные в это ядро, прежде чем прошивать его!

Прошивая это ядро, **вы** выбираете сделать эти изменения. Если что-то пойдет не так, **не вините меня**!

### Продолжайте на свой страх и риск!

---

# Общие функции для всех вариантов
  - **KernelSU**: KernelSU — это решение для root для устройств Android GKI, оно работает в режиме ядра и предоставляет права root непосредственно в пространстве ядра.
  - **SUSFS**: аддон для скрытия root патчей ядра и модуля пользовательского пространства для KernelSU.
  - Последние исходные коды Realme GT neo5
  - Последние варианты SUSFS ඞ для всех решений root
  - Встроенный патч LZ4KD ZRAM
  - Встроенный патч Ptrace
  - Встроенный патч Sultan Memory
  - Поддержка IPSet для расширенной сетевой фильтрации
  - Поддержка Wireguard
  - Поддержка BBR v1
  - BBG (Baseband-guard)️

### Уникальные функции для всех версий
| --- \ --- | Stock | KernelSU | KernelSU SUSFS | KernelSU-Next | KernelSU-Next SUSFS | Wild KSU | Wild KSU SUSFS | Suki-SU Ultra SUSFS |
|----|----------------|----------------|----------------|----------------|----------------|----------------|----------------|----------------|
| Root | ❌ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ |
| SUSFS | ❌ | ❌ | ✅ | ❌ | ✅ | ❌ | ✅ | ✅ |
| Hooks | ❌ | [Kprobe](https://kernelsu.org/guide/how-to-integrate-for-non-gki.html#integrate-with-kprobe) | [Kprobe](https://kernelsu.org/guide/how-to-integrate-for-non-gki.html#integrate-with-kprobe) | Manual hooks v1.4 | Manual hooks v1.4 | Manual hooks v1.4 | Manual hooks v1.4 | [Kprobe](https://sukisu.org/guide/installation#method-3-manual-kernel-integration-advanced) |

---

# Инструкции по установке:

Следуйте шагам для GKI:
[Установка](https://kernelsu.org/guide/installation.html)

Чтобы получить формат boot.img:
[Получить формат моего ядра](https://github.com/TheWildJames/Get_My_Kernel_Format)

---

#  credits

- **KernelSU**: Разработано [tiann](https://github.com/tiann/KernelSU).
- **KernelSU-Next**: Разработано [rifsxd](https://github.com/KernelSU-Next/KernelSU-Next).
- **Magic-KSU**: Разработано [5ec1cff](https://github.com/5ec1cff/KernelSU).
- **SUSFS**: Разработано [simonpunk](https://gitlab.com/simonpunk/susfs4ksu.git).
- **Модуль SUSFS**: Разработано [sidex15](https://github.com/sidex15).
- **Sultan Ядра**: Разработано [kerneltoast](https://github.com/kerneltoast).
- **Wild Ядра**: Разработано [TheWildJames](https://github.com/TheWildJames).

Особая благодарность сообществу открытого исходного кода за их вклад!

---

# Поддержка

Если у вас возникли проблемы или нужна помощь, не стесняйтесь открывать issue в этом репозитории или свяжитесь со мной.

---

# Отказ от ответственности

Прошивка этого ядра аннулирует вашу гарантию, и всегда существует риск brickнутия вашего устройства. Пожалуйста, сделайте резервную копию ваших данных и убедитесь, что вы понимаете риски, прежде чем продолжать.

**Продолжайте на свой страх и риск!**

---

# Особая благодарность следующим людям за их вклад!
Это очень мне помогает! <3

[simonpunk](https://gitlab.com/simonpunk/susfs4ksu.git) - Создал SUSFS!
[sidex15](https://github.com/sidex15) - Создал модуль!

Если вы внесли вклад и вас здесь нет, пожалуйста, напомните мне!