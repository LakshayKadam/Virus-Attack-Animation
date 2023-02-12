# Virus-Attack-Animation
This animation is created as an assignment for subject 3D Modelling and Animation . It shows how an virus attack on a cell.
The animaiton is mode on blender 3.4 with help of some addons and imported backgrounds.

## Objects used:-
 1.Ico Sphere as Cell <br />
 2.Cube for particle system <br/>
 3.Force <br/>
 4.Corono Virus Addon <br/>
 
## Steps
 1.First added Ico Sphere and Cube into the scene .<br/>
 2.In Icosphere modifier , **Add Modifier->Subdivion Surface->** Set **Render=5** and then **Apply** Then again , **Add Modifier->Displace->Texture->New->Type->Modifier->Str** Set **Str=-0.200**.<br/>
 3.Then right click on Ico sphere and shade smooth.<br/>
 4.Add Cube and Press G to move few it distance from origin.<br/>
 5.Click on Cube then **Particle Properties->Add Particle System Slot->** Set **Number=522** , **Lifetime =2000**, In Velocity tab -> **Normal=-30m/s**, Mark tick on Rotation checkbox,Set **Phase =-0.328** and **Randomize Phase = 0.463** , In Field Weights Tab -> Set **Gravity =0**.
 6.In Ico sphere , **Physics Properties->Collision**.  In Particle Tab-> Set **Damping=0.903** ,      **Friction=0.903** ,In Softbody & Cloth Tab -> **Damping=0.100** , **Thickness Outer =0.02**       , **Inner=0.200** and Set everything else to 0.<br/>
 7.Shift+A to add Force , Set Location such that centre of Force is in centre of Ico sphere and then in Physics Properties, Set **Strength=-15 and Flow=0.025**.<br/>
 8.Import Virus Model from the zip folder .<br/>
 9.Select Cube , **Particle Properties->Render** Set **Render As = Object** ,**Scale=0.02** and  Instance Object as the Virus Model.<br/>
 10.Then Bake the animation .<br/>
 11.Then choose each object and shade it accordlingly and Add background .<br/>
 12.In Cube,**Output Properties->Output Tab** , Select Path where you want to save video . Set **File Format = FFmpeg Video** , in Enconding Tab  Set **Container = MPEG-4** , **Output Quality = Perceptually Lossless**.<br/>
 13.Then Render animation .<br/>
 14.Your animation will be saved in specified path.<br/>
 
