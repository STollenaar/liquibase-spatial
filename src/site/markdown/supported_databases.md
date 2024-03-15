Supported Databases
-------------------

The table below lists the supported databases and their specific requirements:

<table>
   <tr>
      <th>Database</th>
      <th>Version</th>
      <th>Remarks</th>
   </tr>
   <tr>
      <td>Apache Derby<sup>1</sup></td>
      <td>10.8.2.2+</td>
      <td>Requires <a href="https://github.com/jdeolive/geodb">GeoDB</a>, 
      <a href="http://hatbox.sourceforge.net">Hatbox</a> and 
      <a href="http://tsusiatsoftware.net/jts/main.html">JTS</a> in the classpath</td>
   </tr>
   <tr>
      <td>H2</td>
      <td>1.2.135+</td>
      <td>Requires <a href="https://github.com/jdeolive/geodb">GeoDB</a>, 
      <a href="http://hatbox.sourceforge.net">Hatbox</a> and 
      <a href="http://tsusiatsoftware.net/jts/main.html">JTS</a> in the classpath</td>
   </tr>
   <tr>
      <td>MySQL</td>
      <td>5.0+</td>
      <td>None</td>
   </tr>
   <tr>
      <td>Oracle</td>
      <td>all</td>
      <td>Requires the <a href="http://www.oracle.com/technetwork/database/options/spatialandgraph/overview">Oracle Spatial</a> extension</td>
   </tr>
   <tr>
      <td>PostgreSQL</td>
      <td>8.4+</td>
      <td>Requires <a href="http://postgis.net">PostGIS</a> 2.0+</td>
   </tr>
</table>
<hr/>
1. I am in the process of contributing Derby support to GeoDB.  Please refer to my <a href="https://github.com/stollenaar/geodb">fork</a> until it has been accepted.
