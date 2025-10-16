### Установка и настройка  VSCode + EIDE + pyocd + openocd

Все эти программы можно установить по отдельности, но PUYA сделала пакет PY32_GCC_SDE который устанавливет всё это и ещё дополнительные утилиты.

[Ссылка для скачивания](https://www.puyasemi.com/download_path/%E5%B7%A5%E5%85%B7/MCU%20%E5%BE%AE%E5%A4%84%E7%90%86%E5%99%A8/PY32_GCC_SDE_V1.0.0.zip)<br>

после установки архивы проектов в папке - C:\Program Files (x86)\PuyaSDE\sdk\example

но лучше скачать свежие архивы Firmware на сайте PUYA --> [Firmware F0xx](https://www.puyasemi.com/download_path/%E5%BA%93%E5%87%BD%E6%95%B0%E4%B8%8E%E4%BE%8B%E7%A8%8B/MCU%20%E5%BE%AE%E5%A4%84%E7%90%86%E5%99%A8/PY32F0xx_Firmware_V1.4.9.zip)<br>

в версии 1.4.9 - основным отладчиком в проектах EIDE - сделан pyocd

основные примеры для библиотеки HAL, но есть и для библиотеки LL

шаблоны в папке  ./Templates<br>
примеры в папке  ./Projects  - для демоплат<br>

В данном случае я распаковал архивы Firmware для F0xx и F002B в одну папку  C:\PY32<br>
<img src="../images/folders.png" alt="drawing" width="400"/>

Далее - если всё встало нормально<br>
запускаем VSCode с нужной папкой примера или шаблона<br>
сборка, прошивка и отладка должны быть без проблем

! pyocd - желательно один программатор чтобы был подключен<br>
(работает с ST-Link V2; J-Link OB V2; CMSIS-DAP(любой ?) )

