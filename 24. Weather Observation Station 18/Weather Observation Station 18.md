Consider P_l (a, b) and P_2 (c, d) to be two points on a 2D plane.
• a happens to equal the minimum value in Northern Latitude (LAT_N in STATION).
• b happens to equal the minimum value in Western Longitude (LONG_W in STATION).
• c happens to equal tie maximum value in Northern Latitude (LAT_N in STATION).
• d happens to equal the maximum value in Western Longitude (LONG_W in STATION).
Query the Manhattan Distance [https://xlinux.nist.gov/dads/HTML/manhattanDistance.html] between points P_l and P_2 and round it to a scale of 4 decimal places.

Input Format

The STATION table is described as follm•vs:
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