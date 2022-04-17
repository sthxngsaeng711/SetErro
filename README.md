# SetErro
 _IsDir($sTmp)     $sTmp = FileGetAttrib($sTmp)     Return SetError(@error, 0, StringInStr($sTmp, 'D', 2) > 0) EndFunc
