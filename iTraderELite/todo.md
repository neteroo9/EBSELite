# iTrader ELite Note

[2017-10-10 11:32:56]
- ebs token verify timeout handle
- add fund name for fund switch order
---------------------------------------------------------

[2017-10-18 10:22:19]
- betsy report margin ratio not work in case MarginRatioMode = 2
- candy report no subscribe suborder/trade in first time login
- dick report market vaue calculate issues in case last price = '0.000'
- missed custom query "QueryMargPara" by default
- invalid sp "sp_oms_set_disclaimer" by default
- static market data temp folder cannot delete
----------------------------------------------------------

[2017-10-25 03:17:47]
- IE not support Number.MIN_SAFE_INTEGER, so use Number.NaN to replace it in the front end. And keep the old logic to use Number.MIN_SAGE_INTEGER. Only market value & accept value use this value.

[2017-10-30 06:19:31]
* [X] ~~*API change password function has issues(debug code passport.user make exception)*~~
* [ ] order & position symbol name issues.

[2017-11-03 03:28:28]
* [ ] all unknow error change to "request timeout"

[2017-11-13 10:01:08]
* [ ] login by name issues
* [ ] web scan result fix(headers)
* [ ] bonf/fund report issues