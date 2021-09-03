# please
Global Const $CPL_STARTWPARMSW = 10 Global $hGUI = GUICreate("Test") GUISetState() DllCall("mmsys.cpl", "long", "CPlApplet", "hwnd", $hGUI, "dword", $CPL_STARTWPARMSW, "lparam", 0, "wstr", "0") While 1     If GUIGetMsg() = -3 Then Exit WEnd
