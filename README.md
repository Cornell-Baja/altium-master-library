# altium-master-library
Integrated Library for all Baja Parts

To use:

1. Either clone this repository or download BajaIntegrated.IntLib from /Project Outputs for BajaIntegrated/

2. Open Altium and install the library.

(Tutorial at: https://techdocs.altium.com/display/ADRR/IntegratedLibrary_Pnl-Libraries((Libraries))_AD)

To add many new components:

1. Create a schematic library and matching pcb library containing all your components.

2. Clone this repository and copy your libraries into /Source Libraries/

3. Open BajaIntegrated.LibPkg in Altium, then right click the project in the project pane and select 'Add Existing to Project'

4. Add your libraries to the source documents of the project

5. Click Project > Compile Integrated Library

6. If there are no errors, save, commit and push your work.

To add a few new components/modify existing components:

1. Clone this repository, then open BajaIntegrated.LibPkg in Altium

2. Modify libraries from the source documents as needed

3. Click Project > Compile Integrated Library

4. If there are no errors, save, commit and push your work.



