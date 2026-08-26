# paradaim-foxglove-assets

UR5e-robotmodel voor Foxglove's URDF-layer (paradaim digital twin).
Automatisch gesynct vanuit de (private) planner-repo — hier niets
rechtstreeks wijzigen.

**Gebruik in Foxglove:** 3D-panel → Custom layers → Add URDF → Source
"URL":

    https://raw.githubusercontent.com/MarkHeeling/paradaim-foxglove-assets/main/ur5e_hand_e/ur5e_hand_e_foxglove.urdf

De mesh-paden in die URDF zijn relatief en laden automatisch mee.

De UR5e-meshes komen uit `ur_description` van Universal Robots
(ros-industrial/universal_robot, BSD-3-Clause); de Hand-E-gripper zit
niet in de URDF.

**Bedieningspaneel:** download `panel/paradaim.paradaim-panel-1.0.0.foxe`, open het met de Foxglove-app (dubbelklik) en voeg het panel "Paradaim Bediening" toe aan je layout.
