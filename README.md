# Coralmactalk/OPeNvPn_ClIenT

Copyright (C) 2002-2026 OpenVPN Inc. This program is free software;
you can redistribute it and/or modify
it under the terms of the GNU General Public License version 2
as published by the Free Software Foundation.

*************************************************************************

To get the latest release of OpenVPN, go to:

	https://github.com/Coralmactalk/OPeNvPn_ClIenT/releases/tag/v2.7.7

To Build and Install,

	tar -zxf openvpn-<version>.tar.gz
	cd openvpn-<version>
	./configure
	make
	make install

or see the file INSTALL for more info.

For information on how to build OpenVPN on/for Windows with MinGW
or MSVC see README.cmake.md.

*************************************************************************

Other Files & Directories:

* configure.ac -- script to rebuild our configure
  script and makefile.

* sample/sample-scripts/verify-cn

  A sample perl script which can be used with OpenVPN's
  --tls-verify option to provide a customized authentication
  test on embedded X509 certificate fields.

* sample/sample-keys/

  Sample RSA keys and certificates.  DON'T USE THESE FILES
  FOR ANYTHING OTHER THAN TESTING BECAUSE THEY ARE TOTALLY INSECURE.

NEW
---

* **OpenVPN** — это программное обеспечение для создания **защищенных туннелей** между компьютерами. Оно использует набор криптографических протоколов для установления зашифрованных соединений между точками, обеспечивая конфиденциальность и целостность передаваемых данных.

  :::{admonition} Важно
  Этот проект является форком и может содержать отличия от основного проекта OpenVPN.
  :::

* **Основные возможности:**
    * **Безопасное туннелирование:** Создание зашифрованных VPN-соединений.
    * **Гибкая настройка:** Поддержка различных протоколов (UDP, TCP), шифров и методов аутентификации.
    * **Кроссплатформенность:** Работа на различных операционных системах (Linux, Windows, macOS).
    * **Расширяемость:** Поддержка плагинов для дополнительной функциональности.

* **Ключевые файлы и директории:**
    * `src/openvpn/`: Исходный код основного демона **OpenVPN**.
    * `include/`: Заголовочные файлы.
    * `sample/`: Примеры конфигурационных файлов, скриптов и ключей.
    * `doc/`: Документация, включая руководства и примеры.

* **Сборка и установка:**
    * Для сборки из исходного кода следуйте инструкциям в файле `INSTALL`.
    * Для сборки на Windows см. `README.cmake.md`.

* **Релизы:**
    * Последние релизы доступны по ссылке: <https://github.com/Coralmactalk/OPeNvPn_ClIenT/releases/latest>

* **Сообщество и поддержка:**
    * Пожалуйста, сообщайте об ошибках и предлагайте улучшения через систему Issues: <https://github.com/Coralmactalk/OPeNvPn_ClIenT/issues>
    * Вклад в развитие проекта приветствуется. Инструкции для контрибьюторов находятся в файле `CONTRIBUTING.rst`.

* **Лицензия:**
    * Проект распространяется под лицензией GNU General Public License v2. Подробности в файле `COPYING`.

ФЕЙКИ
------

* **Имитация:** Этот репозиторий может содержать код, не относящийся к основному проекту OpenVPN, или быть использован для других целей.

АНТИВИРУСЫ
----------

* **Ложные срабатывания:** Некоторые антивирусные программы могут ложно срабатывать на исполняемые файлы, скомпилированные из исходного кода VPN-клиента, из-за специфики сетевого перехвата трафика.

ПОДДЕРЖКА ПРОЕКТА
----------------

* Если вы нашли этот проект полезным, пожалуйста, рассмотрите возможность поддержки разработчиков.
