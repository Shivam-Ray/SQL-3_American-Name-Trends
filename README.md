# SQL-3__American-Name-Trends

We'll be working with data provided by the United States Social Security Administration, which lists first names along with the number and sex of babies they were given to in each year. Our data spans 101 years, from 1920 through 2020


<h3 id="baby_names"><code>baby_names</code></h3>
<table>
<thead>
<tr>
<th style="text-align:left;">column</th>
<th>type</th>
<th>meaning</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:left;"><code>year</code></td>
<td>int</td>
<td>year</td>
</tr>
<tr>
<td style="text-align:left;"><code>first_name</code></td>
<td>varchar</td>
<td>first name</td>
</tr>
<tr>
<td style="text-align:left;"><code>sex</code></td>
<td>varchar</td>
<td><code>sex</code> of babies given <code>first_name</code></td>
</tr>
<tr>
<td style="text-align:left;"><code>num</code></td>
<td>int</td>
<td>number of babies of <code>sex</code> given <code>first_name</code> in that <code>year</code></td>
</tr>
</tbody>
</table>
