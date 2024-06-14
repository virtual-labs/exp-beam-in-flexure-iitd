<h4>Background:</h4>
<br>
Reinforced concrete (RC) beams are structural elements that carry transverse external loads. The loads cause bending moments, shear forces, and sometimes torsion across their length. Moreover, concrete is strong in compression and very weak in tension. Thus, steel reinforcement is used to take up tensile stresses in RC beams. 
<br>
<div align="center"><img src="images/fig1.png"></div>
<br>
Beams are divided into two categories based on the presence of tension and compression steel -
<ol>
<li>Singly Reinforced Beam ( see Fig. 1 (A) ) 
<br>
A beam section with steel only on the tension side is a singly reinforced beam.
</li>
<li>
Doubly Reinforced Beam ( see Fig. 1 (B) )
A beam section with steel on the tension and compression side is known as a doubly reinforced beam.
</li>
</ol>
Further, beam sections are divided into three categories based on the area of tension steel -
<ol>
<li>Balanced Section: The area of tension steel is such that the two limiting conditions (yielding of steel and crushing of concrete) are reached simultaneously. </li>
<li>Under Reinforced (UR) Section: The area of tension steel is such that the beam fails by yielding of tension steel followed by crushing of concrete. </li>
<li>Over Reinforced (OR) Section: The area of tension steel is such that the beam fails due to the crushing of concrete.  </li>
</ol>
Fig. 2 shows the moment-curvature curve for an UR and OR beam section. OR beams show a sudden brittle failure due to the crushing of concrete. The behaviour of UR beams is ductile.
<br>
<div align="center"><img src="images/fig2.png"></div>
<br>
As per the limit state design method given in IS-456, the design ultimate moment of resistance of an UR section is given by:
<br>M<sub>ur,design</sub> = 0.36f<sub>ck</sub>bx<sub>u</sub>(d-0.416x<sub>u</sub>)
<br>where
<br>x<sub>u</sub> = (0.87f<sub>y</sub>A<sub>st</sub>) / (0.362f<sub>ck</sub>b)  < x<sub>u,max</sub>
<br>and where
<br>x<sub>u,max</sub> / d = 0.0035 / ( 0.0055 + 0.87f<sub>y</sub>/E<sub>s</sub> ) 

<br>The predicted ultimate moment of resistance of a UR section is given by setting the values of factors of safety for both concrete and steel equal to 1.0 and by considering the observed (mean) strength of concrete and steel instead of the characteristic values. With this, the predicted ultimate moment of resistance of an UR section is given by:
<br>M<sub>ur,predicted</sub> = 0.54f<sub>cm</sub>bx<sub>u</sub>(d-0.416x<sub>u</sub>)
<br>where
<br>x<sub>u</sub> = (f<sub>y,m</sub>A<sub>st</sub>) / (0.54f<sub>cm</sub>b)  < x<sub>u,max,predicted</sub>
<br>and where
<br>x<sub>u,max,predicted</sub> / d = 0.0035 / ( 0.0055 + f<sub>ym</sub>/E<sub>s</sub> ) 

<br>In the above equation:
<br>b	= width of the beam 
<br>D	= depth of the beam 
<br>d	= effective depth of the beam 
<br>A<sub>st</sub> 	= area of steel in tension 
<br>f<sub>ym</sub>	= mean yield strength of steel 
<br>f<sub>y</sub>	= characteristic yield strength of steel 
<br>f<sub>cm</sub>	= mean compressive strength of concrete 
<br>f<sub>ck</sub>	= characteristic compressive strength of concrete 
<br>E<sub>s</sub>	= elastic modulus of steel (= 200 GPa)
<br>x<sub>u</sub>	= depth of neutral axis 
<br>x<sub>u,max</sub>	= limiting depth of neutral axis 
<br>M<sub>ur,design</sub> = design ultimate moment of resistance
<br>M<sub>ur,predicted</sub> = predicted ultimate moment of resistance
<br>M<sub>ur,observed</sub> = observed (experimental) ultimate moment of resistance

