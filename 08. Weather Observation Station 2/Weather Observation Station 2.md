Query the following two values from the STATION table:

1. The sum of all values in LAT_N rounded to a scale of 2 decimal places.
2. The sum of all values in LONG_W rounded to a scale of 2 decimal places.

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

Output Format:
Your results must be in the form:
lat lon

where lat is the sum of all values in LAT_N and lon is the sum of all values in LONG_W. Both results must be rounded to a scale of 2 decimal places.