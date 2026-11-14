# AD.Animara-mods

Мод **AD.Animara** для The Sims 4 и русские строки к модам 18+ (WickedWhims, Extreme Violence, Basemental Drugs). Бесплатно.

Мод работает вместе с лаунчером AD.Animara: лаунчер сам скачивает отсюда `AD.Animara-mods.zip` и `mods.json`, проверяет подпись автора и кладёт файлы в папку Mods игры. Без лаунчера мод ничего не делает.

## Что в архиве

| Путь | Что это |
|---|---|
| `mod/animara.ts4script`, `mod/mod.json` | мод AD.Animara |
| `loc/zz_*_Russian_AD.Animara.package` | русские строки модов 18+ (таблицы строк, язык «русский»). Самих модов 18+ здесь нет: лаунчер скачивает их у их авторов |

## Проверка

Файлы подписаны (ECDSA P-256). `mods.json` — описание: номер слоя, `sha256` и размер архива, подпись. Лаунчер проверяет подпись вшитым открытым ключом до скачивания архива и не принимает пачку без подписи, с чужой подписью или старее уже принятой.

Имена файлов постоянные: `AD.Animara-mods.zip` и `mods.json` в релизе `mods-latest`. Запасной адрес — Hugging Face (`Archidexter/adanimara-assets`, папка `mods/`).

## Лицензия

См. [LICENSE](LICENSE).

---

**AD.Animara** mod for The Sims 4 and Russian strings for the 18+ mods (WickedWhims, Extreme Violence, Basemental Drugs). Free of charge.

The mod works together with the AD.Animara launcher: the launcher downloads `AD.Animara-mods.zip` and `mods.json` from here, checks the author's signature and puts the files into the game's Mods folder. Without the launcher the mod does nothing. The 18+ mods themselves are not included: the launcher downloads them from their authors.
