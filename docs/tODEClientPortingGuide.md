
login sequence:
  - [GciLibrary>>apiGciSetNet: a: a: a:](https://github.com/dalehenrich/tode/blob/master/repository/GemTools-ClientGCI.package/GciLibrary.class/instance/apiGciSetNet.a.a.a..st)
  - [GciLIbrary>>apiGciLogin: a:](https://github.com/dalehenrich/tode/blob/master/repository/GemTools-ClientGCI.package/GciLibrary.class/instance/apiGciLogin.a..st)
  - [GciLIbrary>>apiGciGetSessionId](https://github.com/dalehenrich/tode/blob/master/repository/GemTools-ClientGCI.package/GciLibrary.class/instance/apiGciGetSessionId.st)

set session before making in-session calls:

  - [GciLibrary>>apiGciSetSessionId:](https://github.com/dalehenrich/tode/blob/master/repository/GemTools-ClientGCI.package/GciLibrary.class/instance/apiGciSetSessionId..st)

in-session calls:
  - [GciSession>>executeStringExpectingStringNB:envId:](https://github.com/dalehenrich/tode/blob/master/repository/GemTools-ClientSession.package/GciSession.class/instance/executeStringExpectingStringNB.envId..st)
  - [Gci64bit3x>>apiGciNbExecuteStr: a: a: ](https://github.com/dalehenrich/tode/blob/master/repository/GemTools-ClientGCI.package/Gci64bit3x.class/instance/apiGciNbExecuteStr.a.a..st)
  - [GciLibrary>>apiGciNbEnd:](https://github.com/dalehenrich/tode/blob/master/repository/GemTools-ClientGCI.package/GciLibrary.class/instance/apiGciNbEnd..st)
  - [Gci64bit>>apiGciNbContinueWith: a: a: err:](https://github.com/dalehenrich/tode/blob/master/repository/GemTools-ClientGCI.package/Gci64bit.class/instance/apiGciContinueWith.a.a.err..st)
  - [Gci64bit>>apiGciFetchSize:](https://github.com/dalehenrich/tode/blob/master/repository/GemTools-ClientGCI.package/Gci64bit.class/instance/apiGciFetchSize..st)
  - [Gci64bit>>apiGciFetchChars: a: a: a:](https://github.com/dalehenrich/tode/blob/master/repository/GemTools-ClientGCI.package/Gci64bit.class/instance/apiGciFetchChars.a.a.a..st)
  - [Gci64bit>>apiGciNbContinueWith: a: a: err:](https://github.com/dalehenrich/tode/blob/master/repository/GemTools-ClientGCI.package/Gci64bit.class/instance/apiGciContinueWith.a.a.err..st)
  - [Gci64bit>>apiGciNbStep: a:](https://github.com/dalehenrich/tode/blob/master/repository/GemTools-ClientGCI.package/Gci64bit.class/instance/apiGciNbStep.a..st)
  - [Gci64bit3x>>apiGciNbPerform: a: a: a: a:
](https://github.com/dalehenrich/tode/blob/master/repository/GemTools-ClientGCI.package/Gci64bit3x.class/instance/apiGciNbPerform.a.a.a.a..st)
