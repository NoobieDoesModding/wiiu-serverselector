Lets you swap between different Wii U servers (ex. Pretendo, Protarium) with a menu in the home menu. Make a folder in the root of your SD Card called "wiiu-plugins" and put your .wms and .wps files into a folder inside the "wiiu-plugins" folder, directly into that folder. Still a work in progress, built off of the "evWii" plugin code.
  
note: if anything crashes, try deleting any "inkay-pretendo.wms" and "inkay-pretendo.wps" files, or whatever they may be called for you.
  
HOW TO COMPILE
get docker desktop
  
run these two lines of code
"docker build -t evwii_builder ."
"docker run --rm -v ${PWD}:/project evwii_builder make"

done
