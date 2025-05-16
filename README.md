# TG
TG浏览器关联注册表修复 新建txt 复制下面代码并根据自己情况修改地址 改reg后缀 点击运行


Windows Registry Editor Version 5.00

[HKEY_CLASSES_ROOT\tdesktop.tg]

[HKEY_CLASSES_ROOT\tdesktop.tg\DefaultIcon]
@="\\"`D:\\soft\\Telegram Desktop\\Telegram.exe`,1\""

[HKEY_CLASSES_ROOT\tdesktop.tg\shell]

[HKEY_CLASSES_ROOT\tdesktop.tg\shell\open]

[HKEY_CLASSES_ROOT\tdesktop.tg\shell\open\command]
@="\\"`D:\\soft\\Telegram Desktop\\Telegram.exe`\" -workdir \"`D:/soft/Telegram Desktop`/\" -- \"%1\""

[HKEY_CURRENT_USER\SOFTWARE\Classes\tdesktop.tg]

[HKEY_CURRENT_USER\SOFTWARE\Classes\tdesktop.tg\DefaultIcon]
@="\\"`D:\\soft\\Telegram Desktop\\Telegram.exe`,1\""

[HKEY_CURRENT_USER\SOFTWARE\Classes\tdesktop.tg\shell]

[HKEY_CURRENT_USER\SOFTWARE\Classes\tdesktop.tg\shell\open]

[HKEY_CURRENT_USER\SOFTWARE\Classes\tdesktop.tg\shell\open\command]
@="\\"`D:\\soft\\Telegram Desktop\\Telegram.exe`\" -workdir \"`D:/soft/Telegram Desktop`/\" -- \"%1\""

[HKEY_CLASSES_ROOT\tg]
"URL Protocol"=""
@="URL:Telegram Link"

[HKEY_CLASSES_ROOT\tg\DefaultIcon]
@="\\"`D:\\soft\\Telegram Desktop\\Telegram.exe`,1\""

[HKEY_CLASSES_ROOT\tg\shell]

[HKEY_CLASSES_ROOT\tg\shell\open]

[HKEY_CLASSES_ROOT\tg\shell\open\command]
@="\\"`D:\\soft\\Telegram Desktop\\Telegram.exe`\" -workdir \"`D:/soft/Telegram Desktop`/\" -- \"%1\""

[HKEY_CURRENT_USER\SOFTWARE\Classes\tg]
"URL Protocol"=""
@="URL:Telegram Link"

[HKEY_CURRENT_USER\SOFTWARE\Classes\tg\DefaultIcon]
@="\\"`D:\\soft\\Telegram Desktop\\Telegram.exe`,1\""

[HKEY_CURRENT_USER\SOFTWARE\Classes\tg\shell]

[HKEY_CURRENT_USER\SOFTWARE\Classes\tg\shell\open]

[HKEY_CURRENT_USER\SOFTWARE\Classes\tg\shell\open\command]
@="\\"`D:\\soft\\Telegram Desktop\\Telegram.exe`\" -workdir \"`D:/soft/Telegram Desktop`/\" -- \"%1\""

[HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Run]
"telegram"="`D:\\soft\\Telegram Desktop\\Telegram.exe` -autostart"
