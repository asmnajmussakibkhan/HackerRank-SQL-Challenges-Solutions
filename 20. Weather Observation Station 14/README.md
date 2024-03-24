Query the greatest value of the Northern Latitudes (LAT_N) from STATION that is less than 1372345. Truncate your answer to 4 decimal places.

Input Format

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