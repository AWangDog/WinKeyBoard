# WinKeyBoard
Windows下的键盘控制

## 例子
``` Python
# 单击 a
key = WinKeyBoard.VK.A
WinKeyBoard.key_controller.PressKey(key)
WinKeyBoard.wait(200)
WinKeyBoard.key_controller.ReleaseKey(key)

# 单击键名为 a 的键
key = WinKeyBoard.type_conversion.fromCHAR('a')
WinKeyBoard.key_controller.PressKey(key)
WinKeyBoard.wait(200)
WinKeyBoard.key_controller.ReleaseKey(key)

# 单击按键码为 65 的按键
key = WinKeyBoard.type_conversion.fromVK_CODE(65)
WinKeyBoard.key_controller.PressKey(key)
WinKeyBoard.wait(200)
WinKeyBoard.key_controller.ReleaseKey(key)

# 单击扫描码为 30 的键
key = WinKeyBoard.type_conversion.fromSCAN_CODE(30)
WinKeyBoard.key_controller.PressKey(key)
WinKeyBoard.wait(200)
WinKeyBoard.key_controller.ReleaseKey(key)

# 单击VK码为 VK_A 的键
key = WinKeyBoard.type_conversion.fromVK_NAME('VK_A')
WinKeyBoard.key_controller.PressKey(key)
WinKeyBoard.wait(200)
WinKeyBoard.key_controller.ReleaseKey(key)
```
## 安装
``` Batch
pip install WinKeyBoard
```

