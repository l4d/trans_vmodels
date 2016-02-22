**Translucent ViewModels** by jeffrey 

**If you don't have any installed mods that modify the pak01_dir.vpk, follow these steps:**

1. Download the [zip](https://github.com/l4d/trans_vmodels/archive/master.zip)

2. Extract **trans_vmodels_50.vpk** to your addons folder:

	 **x64** C:\Program Files (x86)\Steam\steamapps\common\left 4 dead\left 4 dead\addons
	 
	 **x32** C:\Program Files\Steam\steamapps\common\left 4 dead\left 4 dead\addons
	 
3.  Extract **pak01_dir.vpk** to your left 4 dead folder and click yes to overwrite:

	 **x64** C:\Program Files (x86)\Steam\steamapps\common\left 4 dead\left 4 dead
	 
	 **x32** C:\Program Files\Steam\steamapps\common\left 4 dead\left 4 dead

**If you have a mod(s) installed that modifies the pak01_dir.vpk, follow these steps:**

1. Download the [zip](https://github.com/l4d/trans_vmodels/archive/master.zip)

2. Extract **trans_vmodels_50.vpk** to your addons folder:

	 **x64** C:\Program Files (x86)\Steam\steamapps\common\left 4 dead\left 4 dead\addons
	 
	 **x32** C:\Program Files\Steam\steamapps\common\left 4 dead\left 4 dead\addons

3. You will now need to modify your existing pak01_dir.vpk with Notepad++. Use ctrl+g to jump to the line number I list below and modify the line with these values (save the file after you complete the edit):

 > Line **26836**, replace **m4super** with **m4supe5**

 > Line **26862**, replace **v_eq_medkit** with **v_eq_medki5**

 > Line **26874**, replace **v_eq_molotov**_bottle with **v_eq_molotov_bottl5**

 > Line **26897**, replace **v_eq_molotov_rag** with **v_eq_molotov_ra5**

 > Line **26937**, replace **v_pistol_reference** with **v_pistol_referenc5**

 > Line **26964**, replace **m16a2** with **m16a5**

 > Line **26991**, replace **v_pump_shotgun_reference** with **v_pump_shotgun_referenc5**

 > Line **27017**, replace **uzi** with **uz5**

 > Line **27045**, replace **v_sniper_reference** with **v_sniper_referenc5**

 > Line **27058**, replace **v_sniper_reference_lens** **with v_sniper_referenc5_lens**

 > Line **26786**, replace **v_boomer_hands** with **v_boomer_hand5**

 > Line **26795**, replace **v_hulk** with **v_hul5**

 > Line **26810**, replace **v_hunter_hands** with **v_hunter_hand5**

<sub>Survivor and Smoker arms are missing. These two v_models share the same texture with the world models and don't provide a v_model vmt to bypass. This makes any changes made to the v_models carry over to the w_models and I won't provide it. </sub>

<sub> 75% translucent a64: Later</sub>

<sub> 50% translucent a128: Completed</sub>

<sub> 25% translucent a191: Later</sub>
