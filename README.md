*******> HyDRA.patch

 Author: Lopez Elias (eliaslopez@qb.fcen.uba.ar)

 Date: Feb. 21, 2018

 Programs: sander, sander Lio

 Description: Description:  Add the HyDRA  module to sander
Please cite: 
        Ramírez, C. L., Zeida, A., Jara, G. E., Roitberg, A. E., & Martí, M. A. (2014). Improving efficiency in SMD simulations through a hybrid differential relaxation algorithm. Journal of chemical theory and computation, 10(10), 4609-4617.

###############################################################################################################
###########################################   I N S T A L L  ##################################################
###############################################################################################################
Here is the instruction to apply the patch:

HyDRA.patch is the patch for Amber16 (AmberTools 16.21, Amber 16.09 tested)

please make sure you have the correct $AMBERHOME set and the required version updated before applying the patch

To apply the patch, just go to $AMBERHOME and run the command

./update_amber --apply-patch=PATH-TO-FILE/HyDRA.patch

you can also easily reverse the patch by

./update_amber --reverse-patch=.patches/ThirdParty16_Applied_Patches/HyDRA.patch

Once you have the patch applied, you need to recompile to make the changes effective

****************************************************************************************************************
