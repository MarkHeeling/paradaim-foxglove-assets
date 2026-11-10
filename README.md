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

**Extensie:** download `panel/paradaim.paradaim-panel-2.2.0.foxe` en open het met de Foxglove-app (dubbelklik). Laad daarna de layout `configs/foxglove/paradaim_layout.json` uit planner (Layout → Import from file): die werkt voor een opname (`.mcap`), de datasetserver (`ws://10.8.0.1:8770`) en URSim of de robot (`ws://10.8.0.1:8765`). Het panel "Paradaim Bediening" is voor Isaac.
