• shell
  
  Windows Registry Editor Version 5.00

  [HKEY_CLASSES_ROOT\Directory\Background\shell\zTerminal Way]
  "MUIVerb"="Open in..."
  "ExtendedSubCommandsKey"="Directory\\Background\\shellex\\CustomContextMenus\\Terminal Way"
  "SeparatorAfter"=""

• shellex
  
  Windows Registry Editor Version 5.00

  [HKEY_CLASSES_ROOT\Directory\Background\shellex\CustomContextMenus\Terminal Way]

  [HKEY_CLASSES_ROOT\Directory\Background\shellex\CustomContextMenus\Terminal Way\shell]

  [HKEY_CLASSES_ROOT\Directory\Background\shellex\CustomContextMenus\Terminal Way\shell\CMD]
  "Icon"="cmd.exe"

  [HKEY_CLASSES_ROOT\Directory\Background\shellex\CustomContextMenus\Terminal Way\shell\CMD\command]
  @="powershell -WindowStyle hidden -Command \"Start-Process CMD -ArgumentList '/s,/k,pushd,%V && start CMD && exit' \""

  [HKEY_CLASSES_ROOT\Directory\Background\shellex\CustomContextMenus\Terminal Way\shell\CMD Admin]
  "Icon"="cmd.exe"
  "HasLUAShield"=""

  [HKEY_CLASSES_ROOT\Directory\Background\shellex\CustomContextMenus\Terminal Way\shell\CMD Admin\command]
  @="powershell -WindowStyle hidden -Command \"Start-Process CMD -ArgumentList '/s,/k,pushd,%V && start CMD && exit' -Verb runas\""

  [HKEY_CLASSES_ROOT\Directory\Background\shellex\CustomContextMenus\Terminal Way\shell\Explorer]
  "Icon"="imageres.dll,203"

  [HKEY_CLASSES_ROOT\Directory\Background\shellex\CustomContextMenus\Terminal Way\shell\Explorer\command]
  @="explorer.exe ."

  [HKEY_CLASSES_ROOT\Directory\Background\shellex\CustomContextMenus\Terminal Way\shell\PS]
  "Icon"="powershell.exe"

  [HKEY_CLASSES_ROOT\Directory\Background\shellex\CustomContextMenus\Terminal Way\shell\PS\command]
  @="powershell -WindowStyle hidden -Command \"Start-Process CMD -ArgumentList '/s,/k,pushd,%V && start PowerShell && exit' \""

  [HKEY_CLASSES_ROOT\Directory\Background\shellex\CustomContextMenus\Terminal Way\shell\PS Admin]
  "Icon"="powershell.exe"
  "HasLUAShield"=""

  [HKEY_CLASSES_ROOT\Directory\Background\shellex\CustomContextMenus\Terminal Way\shell\PS Admin\command]
  @="powershell -WindowStyle hidden -Command \"Start-Process CMD -ArgumentList '/s,/k,pushd,%V && start PowerShell && exit' -Verb runas\""

  [HKEY_CLASSES_ROOT\Directory\Background\shellex\CustomContextMenus\Terminal Way\shell\PS ISE]
  "Icon"="powershell_ise.exe"

  [HKEY_CLASSES_ROOT\Directory\Background\shellex\CustomContextMenus\Terminal Way\shell\PS ISE\command]
  @="powershell -WindowStyle hidden -Command \"Start-Process CMD -ArgumentList '/s,/k,pushd,%V && start PowerShell_ISE && exit' \""

  [HKEY_CLASSES_ROOT\Directory\Background\shellex\CustomContextMenus\Terminal Way\shell\PS ISE Admin]
  "Icon"="powershell_ise.exe"
  "HasLUAShield"=""

  [HKEY_CLASSES_ROOT\Directory\Background\shellex\CustomContextMenus\Terminal Way\shell\PS ISE Admin\command]
  @="powershell -WindowStyle hidden -Command \"Start-Process CMD -ArgumentList '/s,/k,pushd,%V && start PowerShell_ISE && exit' -Verb runas\""
