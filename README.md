# -MsgBox
If Not (@error Or $sTmp) Then     MsgBox(0, ';)', 'File') ElseIf $sTmp Then     MsgBox(0, ';)', 'Folder') Else     MsgBox(0, ';)', 'Error') EndIf  Func 
