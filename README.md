# plotly_adaptation
This is a plotly adaptation regarding the language of the date format of x axis.
Only <b>two languages</b> are available, english and portuguese.
<br><b>Requeriments:</b> Gregorian date format needs to be set.</br>

- After the plotly layout configuration, 4 variables are set regarding the abbreviations and the full names of the day of the month   and the month it self. Those variables receives a array with string objects.
  
- To generate those arrays, 4 methods are invoked:
  - <i>getAcroMonth, getFullMonth, getAcroWeek and getFullWeek </i>, that received a cookie value to confirm what language the user   is using.

- Those 4 arrays are placed into <i>uo.locale</i> as parameters -  days, shortDays, months and shortMonths.
