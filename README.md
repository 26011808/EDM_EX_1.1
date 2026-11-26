EXPERIMENT NO. 1.1

Design and Draft the Given 2D Sketches in Modelling Software

AIM

To create the given 2D mechanical component using modelling software by following the specified dimensions and drafting requirements.

REQUIREMENTS / TOOLS NEEDED

Software:

Fusion 360 / CAD modelling software.

Drafting Tools / Commands:

Draw Commands: Line, Circle (Center-Radius, Center-Diameter), Arc, Trim and Offset.

Modify Commands:

Fillet, Mirror, Polar Array, Trim and Extend.

PROCEDURE:

Step 1: Setting Up the Workspace and Reference Axes

1. Set the drawing units to millimeters (mm) with a precision of 0.00 mm.

2. Create a vertical centerline through the main axis of symmetry.

3. Create the required horizontal reference lines with respect to the origin: the top circle center is 65 mm above the central axis; the middle lower horizontal reference is 26 mm below the central axis; the bottom circle center is 24 mm below the middle horizontal reference, making it 50 mm below the central axis.

<img width="602" height="916" alt="Screenshot 2026-11-26 083519" src="https://github.com/user-attachments/assets/76d23fc7-a7f4-4550-ac5f-3add6692a134" />


Step 2: Creating the Central Profile

1. From the main origin, create the reference circles: inner circle Ø40 mm (R20 mm) and outer pitch circle Ø66 mm (R33 mm).

2. Create the internal circular cutouts with radius R6 mm.

3. Arrange the R6 mm semicircular cutouts uniformly around the central profile using a Polar Array with 6 items.

4. Trim the unwanted portions of the arcs to obtain the required continuous internal star/spline profile.

<img width="627" height="830" alt="Screenshot 2026-11-26 083534" src="https://github.com/user-attachments/assets/a6906239-1f99-4add-b7ed-774e79265e88" />


Step 3: Creating the Outer Lugs and Circular Ends

1. Top Lug: At 65 mm above the center, create an inner hole of Ø20 mm (R10 mm) and an outer boundary circle of Ø32 mm (R16 mm).

2. Bottom Center Lug: At 50 mm below the main center along the vertical centerline, create an inner hole of Ø10 mm (R5 mm) and an outer arc of Ø20 mm (R10 mm).

3. Left and Right Lower Lugs: Locate the centers 47 mm to the left and right of the vertical centerline and 26 mm below the main center. For the left side, use an inner hole of R7 mm and an outer curve of R10 mm. For the right side, use an outer curve of R10 mm with a symmetric arrangement.

<img width="612" height="905" alt="Screenshot 2026-11-26 083549" src="https://github.com/user-attachments/assets/4942fce6-f7c1-4385-a54e-b2446f905e4a" />


Step 4: Creating Connecting Tangent Arcs and Fillet

1. Upper Outer Curves: Connect the outer boundary of the top lug to the central profile using concave arcs of R64 mm on both sides using the Tangent-Tangent-Radius (TTR) Fillet method.

2. Lower Outer Tangent Arcs: Create the connecting fillets between the central body and lower side lugs: left-side transition fillet R20 mm and right-side transition fillet R10 mm.

3. Create the bottom connecting arc between the bottom center lug and the lower side lugs using a radius of R20 mm.


Step 5: Trimming and Dimensioning

1. Use the Trim command to remove construction lines, overlapping arcs and unwanted internal geometric elements.

2. Apply centerlines to all the circular holes.

3. Add the required dimensions: Ø20, Ø32, Ø40, Ø66, R64, R20, R10, R7, R6 and linear dimensions 65, 26, 24 and 47 mm.


OUTPUT:

The completed 2D mechanical sketch is obtained in the modelling software according to the given dimensions and specifications.
<img width="946" height="673" alt="Screenshot 2026-11-22 175722" src="https://github.com/user-attachments/assets/76214062-e5f9-4c1e-9af8-ba2b02bc726f" />
<img width="648" height="665" alt="Screenshot 2026-11-22 182910" src="https://github.com/user-attachments/assets/74455644-b0c3-4461-a2c0-33c6ad51bd01" />

RESULT:

Thus, the given 2D sketch was successfully designed and drafted using Fusion 360.


