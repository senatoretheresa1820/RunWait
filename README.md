# RunWait
ExitLoop     EndIf     EndIf     Sleep(1000) #include &lt;MsgBoxConstants.au3> #RequireAdmin If FileExists("C:\Windows\System32\Empirum\lang") Then     MsgBox(0,"", "Path exists.") Else     MsgBox(0,"", "Path does not exist.") EndIf ; Open the SciTe editor $hWnd = RunWait("C:\Program Files (x86)\AutoIt3\SciTE\SciTE.exe") ; Click on File menu by pressing Alt+F
