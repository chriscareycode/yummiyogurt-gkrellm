# yummiyogurt-gkrellm

<img src="https://chriscarey.com/graphics/skins/gkrellm/yummiyogurt-gkrellm-100.png" />

Installation
==============
- Install GKrellM. `sudo apt-get install gkrellm` or `sudo yum install gkrellm`
- `git clone https://github.com/chriscareycode/yummiyogurt-gkrellm.git`
- Launching gkrellm will create the .gkrellm2/themes folder, or you need to create it yourself. `mkdir -p .gkrellm2/themes`
- `mv yummiyogurt-gkrellm .gkrellm2/themes/yummiyogurt`
- Relaunch gkrellm and select the YummiYogurt theme

Tweaks
==============
I suggest right-clicking on each chart and setting "Number of Grids" to 1. This will get rid of those horizontal grid lines. I'm not sure of another way to get rid of those in the theme config.

TO-DO
==============
I'm in the process of updating the theme to work properly at the default 100px wide. The original version of this skin was set to 65 pixels wide, but that will not suit the majority of users who will want to stick with the default width.

Upgrading
==============
- cd .gkrellm2/themes/yummiyogurt
- git pull --rebase
