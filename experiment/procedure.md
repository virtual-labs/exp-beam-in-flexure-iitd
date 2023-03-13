<h4>Basic Guildelines For Conducting The Experiment</h4>
The beam section shown below is prepared for casting and conducting the experiment-
Dimensions of the beam  = L’*b*D  = ( 2000x150x200 )mm<sup>3</sup>
<br>
<div align="center"><img src="images/fig18.png"></div>
<br>

<div align="center"><img src="images/fig19.png"></div>
<br>
  The reinforcement cage is  a system of reinforcement bars used in strengthening the concrete structures. The reinforcement cage used in our experiment is shown below-                                                  

<br>
<div align="center"><img src="images/fig20.png"></div>
<br>
Cover is the distance between the directly exposed concrete surface to the nearest reinforcement bar.. The cover provided in our experiment is about 25mm.
Before casting the beam, the reinforcement cage is prepared.  The cage and cover blocks are then placed in the casting mold. The mold is then filled with concrete and finished using a vibration needle and other necessary equipment. The casted beam is then allowed to set and demoulded once it sets. The beam is then cured for around 28 days. Three cube and three flexure beam specimens are also casted along with the UR beam. 
Before starting the experiment, some additional information is required from various other experiments. The properties and their requirements are listed below -

<ul>
<li>Compressive Strength of Concrete(f<sub>cm</sub>)
This property of concrete is obtained from the “Compressive Test of Concrete(Cube)” experiment.<br>
Material to be casted: 3 Concrete Cube specimen
                                    ( 150x150x150 ) mm<sup>3</sup>
  *You can read the test details from our virtual lab Experiment 1
</li>
  <li>Flexural Strength of Concrete(f<sub>cr</sub>)

This property of concrete is obtained from the “Flexural Strength Test of Concrete(Beam)” experiment.
<br>
Specimen to be casted: Small Beams made of concrete only
                                       ( 500x100x100 )mm<sup>3</sup>
</li>
  <li>
  Tensile Yield Strength of Steel (f<sub>ym</sub>)
This property of steel is obtained from the “Reinforcement Bars under Uniaxial Tension” experiment.<br>
    Material Required: 2 steel bars

  </li>
  
</ul>


After 28 days, the beam and other concrete specimens are tested for their respective properties. The detailed procedure for UR beam testing is given in the Procedure section. 


Instrumentation in UR beam before testing
<ul>
  <li>A LVDT is provided at the bottom of the UR beam during testing. This measures the displacements at the bottom of the beam</li>
  <li>Load cells are connected to the hydraulic jack, which in turn apply load on the beam.</li>
  <li>The beam is tested using a four point loading setup.</li>
</ul>
<br>
<div align="center"><img src="images/fig21.png"></div>
<br>

<h4>Procedure</h4>
<ul>

  <li>Place the beam on the loading frame.</li> 

  <li>Measure and note the depth(D), width(w) and effective length(L) of the beam before starting the experiment.</li> 

  <li>Measure and note the distance between the loading points, supports.</li>

  <li>Apply the load with uniform increment in the load using a hydraulic jet.</li>

  <li>As the cracks appear on the beam, stop increasing the load and mark the cracks.</li>

  <li>Repeat step 5 at least for 3 different loads.</li>

  <li>Increase the load till the failure occurs and then note the failure load.</li>

</ul>

<h4>Observations and Calculations</h4>
Grade of concrete(f<sub>ck</sub>)                         =
Mean compressive strength of concrete(f<sub>cm</sub>)     =
Flexural strength of concrete(f<sub>cr</sub>)             =
Grade of steel(f<sub>y</sub>)                             =
Mean Yield strength of steel(f<sub>ym</sub>)              =
Area of tension steel(A<sub>st</sub>)                     =
Length of Beam Between Supports(L)             =
Depth of Beam(D)                               =
Width of Beam(b)                               =
Young’s Modulus of concrete(E<sub>c</sub>)    (5000√<sub>fcm</sub> ) =
Young’s Modulus of steel(E<sub>s</sub>)                   =
<ul>
  <li><b>Cracking Moment</b>
    <ol>
      <li>Gross Section <br>
        Cracking Moment = M<sub>cr,gs</sub> = f<sub>cr</sub>*I<sub>g</sub>/y
      </li>
      <li>Transformed Section<br>
      Depth of neutral axis = y
        Second Moment of area for transformed section = I <sub>ts</sub>
        Cracking Moment = M<sub>cr,ts</sub> = f<sub>cr</sub>*I<sub>ts</sub>/( D - y )
      </li>
    </ol>
  </li>
  <li><b>Yielding Moment</b>
  Depth of neutral axis (h) = M<sub>yield</sub> = f<sub>ym</sub>A<sub>st</sub>( d - h/3 ) </li>
  <li><b>Ultimate Moment</b>
  <br>
    <table>
<thead>
  <tr>
    <th>&nbsp;&nbsp;&nbsp;<br>PROPERTY&nbsp;&nbsp;&nbsp;</th>
    <th>&nbsp;&nbsp;&nbsp;<br>ACTUAL(EXPERIMENTAL) ULTIMATE MOMENT&nbsp;&nbsp;&nbsp;</th>
    <th>&nbsp;&nbsp;&nbsp;<br>DESIGN(THEORETICAL) ULTIMATE MOMENT&nbsp;&nbsp;&nbsp;</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>   <br>Material Strength   </td>
    <td>   <br>Concrete                0.67f<sub>cm</sub> = <br>   <br>Steel                       f<sub>ym</sub>   = </td>
    <td>   <br>Concrete                0.67f<sub>ck</sub> = <br>   <br>Steel                     f<sub>y</sub> = <br>   <br>    </td>
  </tr>
  <tr>
    <td>   <br>Factor of Safety(FOS)<br>   <br>    </td>
    <td>   <br>Concrete                0.67f<sub>cm</sub> = <br>   <br>Steel                       f<sub>ym</sub>   = </td>
    <td>   <br>Concrete                0.446f<sub>ck</sub> = <br>   <br>Steel                     0.87f<sub>y</sub> = <br>   <br>    </td>
  </tr>
  <tr>
    <td>   <br>Design/Actual Stress   </td>
    <td>   <br>Concrete                  0.67f<sub>cm</sub><br>   <br>Steel                         f<sub>ym</sub>   </td>
    <td>   <br>Concrete                 0.446f<sub>ck</sub><br>   <br>Steel                       0.87f<sub>y</sub>   </td>
  </tr>
  <tr>
    <td>Limiting Depth of Neutral Axis </td>
    <td> x<sub>u,max</sub> / d = 0.0035 / ( 0.0055 + f<sub>ym</sub>/E<sub>s</sub> ) = </td>
    <td> x<sub>u,max</sub> / d = 0.0035 / ( 0.0055 + 0.87f<sub>ym</sub>/E<sub>s</sub> ) = </td>
  </tr>
  <tr>
    <td>Depth of Neutral axis</td>
    <td>x<sub>u</sub> = f<sub>ym</sub>A<sub>st</sub> / 0.54f<sub>cm</sub>b = <br><br>(x<sub>u</sub> <= x <sub>u,max</sub>)</td>
    <td>x<sub>u</sub> = 0.87f<sub>y</sub>A<sub>st</sub> / 0.362f<sub>ck</sub>b = <br><br>(x<sub>u</sub> <= x <sub>u,max</sub>)</td>
  </tr>
  <tr>
    <td>&nbsp;&nbsp;&nbsp;<br> <br>&nbsp;&nbsp;&nbsp;<br>Ultimate Moment&nbsp;&nbsp;&nbsp;</td>
    <td>   <br>M<sub>u</sub> =   0.54 f<sub>cm</sub>bx<sub>u</sub>(d   – 0.416x<sub>u</sub> )<br>   <br>                              OR<br>   <br>M<sub>u</sub> = f<sub>ym</sub>A<sub>st</sub>(d –   0.416x<sub>u</sub>   )<br>   <br>M<sub>u</sub> =     </td>
    <td>   <br> M<sub>u</sub> = 0.362f<sub>ck</sub>bx<sub>u</sub>(d − 0.416x<sub>u</sub> )<br>   <br>                       OR     <br>   <br>M<sub>u</sub> = 0.87f<sub>y</sub>A<sub>st</sub>(d −   0.416x<sub>u</sub>   ) <br>   <br>M<sub>u</sub> =     </td>
  </tr>
</tbody>
</table>

  </li>
  <li><b>Model Error</b>
    Model error = M<sub>u,experimental</sub> / M<sub>u,design</sub></li>
</ul>








<h4>Results</h4>
<ol>
<li>The model error in the experiment is :</li>
<li>The Load vs displacement curve obtained from the experiment is :</li>
</ol>


<h4>Precautions</h4>
<ol>
<li>Before casting, ensure the beam section is under-reinforced.</li>

<li>Mix design calculations before preparing concrete for casting should be accurate.</li>

<li>Ensure compaction of the beam is done properly, to obtain accurate test results.</li>

<li>Testing must be done after a minimum of 28 days.</li>

<li>Before testing the beam, check if the load cell, hydraulic jet and LVDTs are connected properly.</li>

<li>Wear safety helmets while marking the cracks on the beam.</li>
</ol>
  
