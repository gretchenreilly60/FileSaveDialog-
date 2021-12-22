# FileSaveDialog-
#include &lt;FileConstants.au3> #include &lt;MsgBoxConstants.au3> $hFile = FileSaveDialog ( "title", @ScriptDir, "All (*.*)"  , $FD_MULTISELECT  , "test.txt" ) ConsoleWrite($hFile &amp; @CRLF)
