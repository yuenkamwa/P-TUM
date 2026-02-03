中意就攞去用喇! 

<b>PTUM</b> stands for Point load, Triangular load, Uniform load and Moment<br />
This is an open-source program. VBA project password: 123<br />
It contains a beam analysis function and a RC design function.

Reference:
- Hong Kong Code of Practice for Structural Use of Concrete 2013
- Chapter 11, Reinforced Concrete Designer's Handbook
  (10th, Charles E. Reynolds and James C. Steedman)
- 第二章, 建築結構靜力計算手冊(第二版), 中國建築工業出版社 1998

This application:
- Developed with VBA. It doesn't support Excel 2003 or before. Macro must be enabled before using it.
- Adopts equations derived from reference manuals for analysis of shearing force, bending moment and deflection along the member span at 50 equal segments.

Features:
- Support one-span beam with 4 basic load types: Point, Triangle, Uniform and Moment
- Support 28 no. of loads with 3 Load Cases and 3 custom Load Combinations.
- Support RC design

Assumptions of RC design:<br>
- Design for <b>Hong Kong Code of Practice for Structural Use of Concrete 2013</b>
- The beam is under sagging stress, and without any pattern loads
- Max. 4 layers of mainbar in both upper part and lower part of the beam
- No more than one type of mainbar per beam, eg. T25
- No more than one type of shearbar per beam, eg. T10
- All mainbar layers contain same nos. of rebar 
- Do NOT consider torsional design
- Do NOT consider side bar
- Do NOT consider crack width
- Do NOT consider curtailment
- Do NOT consider lapping of mainbar
- Do NOT consider support width
<br>
<img width="1302" height="1006" alt="P-TUM" src="https://github.com/user-attachments/assets/eceb5800-5929-4423-bfed-ff91186009c1" />
<br>
<br>
RC Beam Design has an SADS-like user interface
<img width="1304" height="1007" alt="RC Beam Design" src="https://github.com/user-attachments/assets/74ac4015-bec3-4b61-9992-23430ea6875a" />
<br>
<br>

![PTUM Video](https://github.com/user-attachments/assets/cdf795f9-0c6e-4d3f-b131-ceca733fd7e7)
