# DocumentName
$text = "File=    DocumentName.txt" &amp; @CRLF &amp; _         "Test= blabla.txt" &amp; @CRLF &amp; _         "Author=    autoitscript.com" &amp; @CRLF &amp; _         "blabla.txt"  $text = StringRegExpReplace($text, '(?i)(File=)(\s+).+?(.txt)', '$1$2' &amp; "DocumentNameNew.txt") ConsoleWrite($text &amp; @CRLF)
