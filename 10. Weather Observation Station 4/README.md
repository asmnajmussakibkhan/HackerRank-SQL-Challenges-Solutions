Find the difference between the total number of CITY entries in the table and the number of distinct CITY entries in the table.

The STATION table is described as follows:
<table>
  <caption>STATION</caption>
  <tr>
    <th>Field</th>
    <th>Type</th>
  </tr>
  <tr>
    <td>ID</td>
    <td>NUMBER</td>
  </tr>
  <tr>
    <td>CITY</td>
    <td>VARCHAR2(21)</td>
  </tr>
  <tr>
    <td>STATE</td>
    <td>VARCHAR2(2)</td>
  </tr>
  <tr>
    <td>LAT_N</td>
    <td>NUMBER</td>
  </tr>
  <tr>
    <td>LONG_N</td>
    <td>NUMBER</td>
  </tr>
</table>

where LAT_N is the northern latitude and LONG_W is the western longitude.

For example, if there are three records in the table with CITY values 'New York', 'New York', 'Bengalaru', there are 2 different city names: 'New York' and 'Bengalaru'. The query returns 1, because
total number of records — number of unique city names = 3 — 2 = 1.