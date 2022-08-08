<a id="start"></a>

# TIL: Today I Learned<br>Сегодня я узнал вот что... #

Добро пожаловать в идеальное рабочее пространство для осознанного самообразования. Отдыхая от работы читаю книжки, статьи, блоги. Смотрю видео и лекции. Слушаю подкасты. Прохожу курсы, интенсивы.

`TIL: Today I Learned`- это всё, что увидел, услышал, прочитал.<br>`Сегодня я узнал вот что..`

## Система виртуализации ##

  Виртуализация — это процесс создания программной (виртуальной) версии компьютера с выделенными ресурсами ЦП, памяти и хранилища, которые "заимствуются" у физического компьютера (например, персонального компьютера) и (или) удаленного сервера, например сервера в центре обработки данных поставщика облачных услуг. Виртуальная машина — это компьютерный файл (обычно его называют образом), который действует как обычный компьютер. Эти виртуальные машины именуются «гостевыми», а ОС, установленная на физическом сервере – «хостовой». Каждая гостевая операционная система запускается в своем изолированном окружении, и «думает», что работает на отдельном компьютере.

### Virtualbox ###

VirtualBox (Oracle VM VirtualBox) — программный продукт виртуализации для операционных систем Windows, Linux, FreeBSD, macOS, Solaris/OpenSolaris, ReactOS, DOS и других.

### Hyper-V ###

Microsoft Hyper-V – это одна из технологий виртуализации серверов, позволяющая запускать на одном физическом сервере множество виртуальных ОС. 
- [Системные требования]()
- [Включение аппаратной виртуализации]()
- ...
- [Эти и другие знания про Git](/Git/README.md)

## Система контроля версий Git ##

Уверен, что вы неоднократно могли сталкиваться с терминами: система контроля версий, Git, GitHub и GitLab.

Git — самая популярная распределённая система контроля версий. Это система, которая позволяет контролировать версии приложения. Она сохраняет все подтвержденные изменения кода. Поэтому в любой момент можно отменить правки или исключить ненужные части кода. Git-сервисы позволяют переключаться между ветками кода и просматривать коммиты.

Распределенная система контроля версий означает, что локальный клон проекта является полным репозиторием управления версиями. Полнофункциональные локальные репозитории упрощают работу в автономном режиме или в удаленном расположении.

Основное предназначение Git – это сохранение снимков последовательно улучшающихся состояний вашего проекта. С помощью Git можно отслеживать и контролировать все изменения, вносимые в базу кода проекта. Основной структурный элемент в системе Git называется репозиторий. Он представляет собой отдельный каталог на удаленном сервере, в котором хранятся все файлы для конкретного проекта: программный код, изображения, аудио, видео, документация и т.д.
- [Первоначальная настройка Git на Windows]()
- [Устанавливаем SSH-ключи]()
- [Основная шпаргалка по командам Git]()
- ...
- [Эти и другие знания про Microsoft Hyper-V](/Hyper-V/README.md)

## Управление репозиториями ##

Репозиторий — часть системы Git, которая позволяет совместно работать над проектами, хранилище всех версий кода. Он бывает трех видов:
- локальный, расположен на одном компьютере, и работать с ним может только один человек.
- централизованный, расположен на сервере, куда имеют доступ сразу несколько программистов.
- распределенный, самый удобный вариант с облачным хранилищем. Главный репозиторий хранится в облаке, а его локальные копии у разработчиков на компьютерах. Когда программист вносит правки в локальную версию, ее можно синхронизировать с удаленной. Получается, что в облаке всегда актуальный код.

Для работы с распределёнными репозиториями нужен удобный сервис. Самые популярные: GitHub, GitLab и Bitbucket. У них понятный интерфейс, в котором можно управлять проектом, добавлять новые объекты и искать общедоступные репозитории.

- [Что такое GitHub? В чём его функции и чем он отличается от Git?]()
- [GitLab – набирающая популярность альтернатива GitHub]()
- [Bitbucket – еще один популярный инструмент]()

## Vagrant ##

Vagrant — продукт компании HashiCorp, специализирующейся на инструментах для автоматизации разработки и эксплуатации. По сути, это просто надчтройка над Virtualbox. Vagrant позволяет создавать и конфигурировать легковесные, повторяемые и переносимые окружения для разработки.

- [Vagrant](/Vagrant/README.md#vagrant)

# [А вы это знали?](#start) #
