# WinKeyBoard
Windows下的键盘控制

# 例子
```
# 单击a
key = WinKeyBoard.type_conversion.fromCHAR('a')
WinKeyBoard.key_controller.PressKey(key)
WinKeyBoard.wait(200)
WinKeyBoard.key_controller.ReleaseKey(key)

# 单击按键码为65的按键
key = WinKeyBoard.type_conversion.fromVK_CODE(65)
WinKeyBoard.key_controller.PressKey(key)
WinKeyBoard.wait(1000)
WinKeyBoard.key_controller.ReleaseKey(key)

# 单击扫描码为30的键
key = WinKeyBoard.type_conversion.fromSCAN_CODE(30)
WinKeyBoard.key_controller.PressKey(key)
WinKeyBoard.wait(1000)
WinKeyBoard.key_controller.ReleaseKey(key)
```
