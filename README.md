# Finding STM imaging of a compound along a plane.
Self consistent calculations.
Step 1 : Optimize a structre pw.x relax.in > relax.out
<br>
Step 2: Use the optimized coordinates to visualize the structure using VESTA, BURAI, or XCrySDen.
<br>
Step 3: In BURAI, Select the option Modeler, and enter miller index (hkl) values along which you want the STM imaging and enter build. 
<br>
Step 4: Adding amount of vaccum (since it's important to have vaccum present for post production of .cube file using Critic2 package)
<br>
*Not specifing vaccum will lead to a error during the image generation that : "Vaccum not detected" by critic2.*




