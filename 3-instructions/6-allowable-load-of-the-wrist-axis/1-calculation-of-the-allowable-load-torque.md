# 3.6.1. Permitted load torque estimation

The load, which will be applied to the mechanical interface of robot's wrist axis, is restricted by allowable weight, allowable load torque and allowable moment of inertia. The direction of coordinate system used to calculate the load torque and inertia moment is the same with the direction of robot base coordinate system.


*	Step 1

    Calculate the location of the weight center from the B axis rotation center (L<sub>X</sub>, L<sub>Y</sub>, L<sub>Z</sub>.)

    L<sub>x</sub>: Location of weight center in X axis

    L<sub>y</sub>: Location of weight center in Y axis

    L<sub>z</sub>: Location of weight center in Z axis



*	Step 2

    Distance calculation from the axis B and R1 to the center of gravity.

    ![](../../_assets/3.6.1_수식1.png)

    L<sub>B</sub> : Length from B axis rotation center to weight center

    L<sub>R1</sub> : Length from R1 axis rotation center to weight center



*	Step 3

    Calculate the load torque from the calculated distance.

    ![](../../_assets/3.6.1_수식2.png)


*	Step 4

    Check if the load torque calculated in the step 3 is the same with or smaller than the limit value, on the basis of allowed load torque table.

 
* Note : If the load mass is similar to the mass on the torque curve below, the torque can be alternatively validated by checking if the distance calculated in the step 2 is distributed in the torque curve, instead of the step 3 and 4. If it is in the torque curve, the calculated load torque is smaller than the allowed load torque but if it is out of the torque curve, the calculated load torque is bigger than the allowed load torque.


<br></br>

![](../../_assets/작은주의표시.png) <b>Allowable load torque</b>

Table 3-2 Allowable load torque
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
    <th class="tg-zegx" colspan="3">Allowable load torque</th>
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
    <td class="tg-nrix" colspan="2">39.2 N·m (4 kgf·m) or less</td>
    <td class="tg-nrix">19.6 N·m (2 kgf·m) or less</td>
  </tr>
  <tr>
    <td class="tg-nrix">HH020T</td>
    <td class="tg-nrix">-</td>
    <td class="tg-nrix">39.2 N·m (4 kgf·m) or less</td>
    <td class="tg-nrix">19.6 N·m (2 kgf·m) or less</td>
  </tr>
 <tr>
    <td class="tg-nrix">HH010L</td>
    <td class="tg-nrix" colspan="2">24.5 N·m (2.5 kgf·m) or less</td>
    <td class="tg-nrix">10.5 N·m (1.1kgf·m) or less</td>
  </tr>
</tbody>
</table>
