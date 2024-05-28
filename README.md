Configuration and Profiles Set for D4LF (Diablo 4 Loot Filter)
Настройки и Профили для D4LF (Diablo 4 Loot Filter)

D4LF (Diablo 4 Loot Filter) project website:
D4LF (Diablo 4 Loot Filter) сайт проекта:

https://github.com/aeon0/d4lf

-------------------------
D4LF will search for `params.ini` and for `profiles/*.yaml` in `C:/Users/WINDOWS_USER/.d4lf`.
All values in `C:/Users/WINDOWS_USER/.d4lf/params.ini` will overwrite the values from the `params.ini` file in the D4LF folder.
In the profiles folder, additional custom profiles can be added and used.

Copy `params.ini` as mentioned before to `C:/Users/WINDOWS_USER/.d4lf`
and needed profiles `*.yaml` to `C:/Users/WINDOWS_USER/.d4lf/profiles`

This setup is helpful to facilitate updating to a new version as you don't need to copy around your config and profiles.

To load/remove profiles to/from D4LF you need just once add/remove profile name to `C:/Users/WINDOWS_USER/.d4lf/params.ini` with Notepad or any text editor.

Example:
`profiles=s4_sigils,s4_necro_minions_pit,s4_necro_golem_minion,s4_sorc_forb`
separated with `,` no spaces allowed (just exclude `.yaml` from profile's file name).

-------------------------
D4LF будет искать файлы `params.ini` и  `profiles/*.yaml` в папке `C:/Users/WINDOWS_USER/.d4lf`.
Все значения `C:/Users/WINDOWS_USER/.d4lf/params.ini` будут перезаписывать значения из файла `params.ini` в папке самого D4LF.
В папке профилей (profiles), могут размещаться и использоваться дополнительные профили.

Скопируйте `params.ini` на основании написанного выше в папку `C:/Users/WINDOWS_USER/.d4lf`
и нужные профили `*.yaml` в папку `C:/Users/WINDOWS_USER/.d4lf/profiles`

Эта настройка помогает и облегчает обновление на обновленные версии D4LF так как вам больше не требуется сохранять/копировать/прописывать конфигурацию и профили.

Чтобы загружать/удалять профили в/из D4LF вам необходимо один раз добавить/удалить имя профиля в файле `C:/Users/WINDOWS_USER/.d4lf/params.ini` с помощью программы Блокнот или любого текстового редактора.

Пример:
`profiles=s4_sigils,s4_necro_minions_pit,s4_necro_golem_minion,s4_sorc_forb`
разделение профилей через `,` пробелы не допускаются (просто исключите `.yaml` из имени файла профиля).
