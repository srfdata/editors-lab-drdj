# editors-lab-drdj (codename "ddrj": drive-driven journalism) 


Making Google Spreadsheets Journalism-compatible, i.e.

  Unify spreadsheet structures, i.e.
  Merge source sheets into one master sheet
  Enforce column types & semantic consistency
  Maintain consistency (IDs, additions, updates timestamps)
  Automagic offsite backup routine

For further explanation: see the [project pitch](https://docs.google.com/presentation/d/19EwH3JsTlw_bI91qs7AwSwCKOGAKykbNEpXrxitAwcQ/pub?start=false&loop=false&delayms=3000)

(test) master sheet: https://docs.google.com/spreadsheets/d/1rCezxcknkgLo6-19elDzhVRHMNvoR_iE4SlkgV6BVPI/edit#gid=0

script bound to this test master sheet: https://script.google.com/macros/d/1rpshAYiJWon3oORCEmrUtqioFBWCnD7EmGkc-_zymDKdedwlWvBt5Y24/edit?uiv=2&mid=ACjPJvECg5oHjiYpSpWq1mEEYTyAnXsjsmYke2PwZBN2EZh3gvR6Mej-ae6NwFmYl20YlaRfApIe8czbPebAxZHQ3284stIeQXml0wqYM-xK-sak4Ip9aGsUBNURrcKkShgiMUqeoAUEETk&splash=yes


## dev workflow

1. *develop* locally 
2. copy-paste to Google Drive Bound Script (see below, further info at https://developers.google.com/apps-script/guides/bound)
3. test with sheet to which the script is attached to
4. **deploy** script as Sheets web add-on


## license

[MIT](https://opensource.org/licenses/MIT)
