# Gear-Team-1
Gear design code for windmill project.

Some of the inputs that are include:
  1. Input speed
  2. Input torque
  3. Gear Ratio 
  4. Bending Safety Factor
  5. Contact Safety Factor
  6. Operation Time
  7. Quality Number
  8. Max Gearbox Height w/ Clearance and Case Thickness
  9. Addendum Height
  
There is also many of constant values which are dependent on the number of teeth for both gears which are taken from certain tables from the textbook. 

Gears 2 and 3 will have the same geometrical properties as with gears 4 and 5. Ideally, the face width for gears 2 and 3 would be smaller since their loadings are less than that of gears 2 and 3 but in this case, we kept them the same for simplicity and it won't affect the results for our project requirements.

The minimum material strength properties are output (sigma_c_insertGEARNUMBER and sigma_b_insertGEARNUMBER) depending on the contact and bending factor of safeties. This would be used to determine the actual factor of safeties for each of the materials used. 

With this code, you should be able to plug in the requirements and be given a geometry of the gear. However, these results are not optimized which will be added later on. 
