# 3.6.2. Permitted inertia moment estimation

Loads must be kept below maximum conditions shown in [Table 3-2] ~ [Table 3-3]

*	Step 1

    Calculate the inertia moment value of the load at each wrist axis center (J<sub>a4</sub>, J<sub>a5</sub>, J<sub>a6</sub>)

    J<sub>a4</sub> - Inertia moment from R2 axis rotation center

    J<sub>a5</sub> - Inertia moment from B axis rotation center

    J<sub>a6</sub> - Inertia moment from R1 axis rotation center

*	Step 2

    Check if the inertia moment is under the thread according to the permissible inertia moment table


![](../../_assets/작은주의표시.png) <b>Allowable moment of inertia</b>

Table 3 3 Allowable moment of inertia
<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-zegx{background-color:#f8f8be;color:#000000; font-weight:bold;text-align:center;vertical-align:middle}
.tg .tg-nrix{text-align:center;vertical-align:middle}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-zegx" rowspan="2">Robot model</th>
    <th class="tg-zegx" colspan="3">Allowable moment of inertia</th>
  </tr>
  <tr>
    <th class="tg-zegx">R2 axis rotation</th>
    <th class="tg-zegx">B axis rotation</th>
    <th class="tg-zegx">R1 axis rotation</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-nrix">HH020</td>
    <td class="tg-nrix" colspan="2">0.88kgm²(0.088kgfms²)</td>
    <td class="tg-nrix">0.25kgm²(0.025kgfms²)</td>
  </tr>
  <tr>
    <td class="tg-nrix">HH020T</td>
    <td class="tg-nrix">-</td>
    <td class="tg-nrix">0.88kgm²(0.088kgfms²)</td>
    <td class="tg-nrix">0.25kgm²(0.025kgfms²)</td>
  </tr>
 <tr>
    <td class="tg-nrix">HH010L</td>
    <td class="tg-nrix" colspan="2">0.63kgm²(0.063kgfms²)</td>
    <td class="tg-nrix">0.15kgm²(0.015kgfms²)</td>
  </tr>
</tbody>
</table>