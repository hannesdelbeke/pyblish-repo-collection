
## Maya Plugins  
[![](https://img.shields.io/github/stars/hannesdelbeke/pyblish-plugins-maya-quality-assurance?color=grey&label=%E2%AD%90&style=flat-square) pyblish-plugins-maya-quality-assurance](https://github.com/hannesdelbeke/pyblish-plugins-maya-quality-assurance): 48 maya plugins [thread](https://forums.pyblish.com/t/collection-of-48-reusable-plugins-for-maya-validation/679)  original [repo](https://github.com/robertjoosten/maya-quality-assurance)  
[![](https://img.shields.io/github/stars/hannesdelbeke/pyblish-plugins-modelChecker?color=grey&label=%E2%AD%90&style=flat-square) pyblish-plugins-modelChecker](https://github.com/hannesdelbeke/pyblish-plugins-modelChecker): (now behind source repo) 25 maya plugins [thread](https://forums.pyblish.com/t/collection-of-25-maya-mesh-validation-plugins/692)  
[![](https://img.shields.io/github/stars/fkaijun/maya_scene_check?color=grey&label=%E2%AD%90&style=flat-square) maya_scene_check](https://github.com/fkaijun/maya_scene_check): 15 maya plugins [thread](https://forums.pyblish.com/t/collection-of-15-reusable-plugins-for-maya-validation/680)  
[![](https://img.shields.io/github/stars/sol-ansano-kim/medic?color=grey&label=%E2%AD%90&style=flat-square) medic](https://github.com/sol-ansano-kim/medic): 22 maya plugins with the Pyblish converter [medicToPyblish](https://github.com/sol-ansano-kim/medicToPyblish), [thread](https://forums.pyblish.com/t/medic-in-pyblish-22-reusable-plugins-for-maya-mesh-validation/682/6)  

## Blender Plugins  
[![](https://img.shields.io/github/stars/hannesdelbeke/pyblish-plugins-blender-lint?color=grey&label=%E2%AD%90&style=flat-square) pyblish-plugins-blender-lint](https://github.com/hannesdelbeke/pyblish-plugins-blender-lint): 7 blender plugins [thread](https://forums.pyblish.com/t/collection-of-7-generic-blender-plugins/693)  

---

a collection of repos that use pyblish
so far the ones with reusable plugins are mostly all made by Marcus. (and myself)
I color coded them by how reusable they were, or how usefull to me.

## 🟢 My own pyblish repos (biased)

### modelChecker 25 maya plugins
https://github.com/hannesdelbeke/modelChecker-pyblish-support
fork from modelchecker to add pyblish support
Pyblish forum [discussion](https://forums.pyblish.com/t/collection-of-25-maya-mesh-validation-plugins/692)

### pyblish manager
standalone tool to manage your pyblish environment
https://github.com/hannesdelbeke/pyblish-manager

### pyblish simple
a simpler pyblish UI, still WIP
https://github.com/hannesdelbeke/pyblish-simple

### pyblish plugin manager
enable configs for plugins
control their settings externally, and a editor UI to make the config
https://github.com/hannesdelbeke/pyblish-plugin-manager

### pyblish blender lint
https://github.com/hannesdelbeke/pyblish-blender-lint
7 plugins for blender

### maya quality assurance 
https://github.com/hannesdelbeke/maya-quality-assurance-pyblish-plugins

## Other

not yet investigated, looks good
https://github.com/kredencstudio/pyblish-kredenc/tree/master/pyblish_kredenc/plugins (mkolar)

### 🟢 default pyblish repos (author: Marcus)


see https://github.com/orgs/pyblish/repositories  <br/>
setup available for most dcc packages


## avalon configs (author: Marcus)


### 🟢 AVA (author: Marcus)
https://github.com/getavalon/config <br/>
Ava - the Avalon default configuration <br/>
• maya


### 🟢 Polly (avalon config) (consultant: Marcus)
https://github.com/mindbender-studio/config <br/>
The Mindbender configuration of Avalon. <br/>
last commit 4 years ago. has a lot of plugins for maya that seem reusable.  <br/>
• maya


### OpenPype (build on top of Avalon)
https://github.com/pypeclub/OpenPype  <br/>
• maya • ftrack


## other


### 🟢 colorbleed (author: Marcus?)
https://github.com/Colorbleed/colorbleed-config <br/>
anim studio config for colorbleed studio <br/>
great reference to see how it all hooks up. but not a lot of reusable plugins <br/>
• fusion • global • houdini • maya


### 🟢 artellapipe pyblish plugins
https://github.com/ArtellaPipe/artellapipe-libs-pyblish <br/>
lots of reusable plugins, they do have dependency on [tpDcc](https://github.com/tpDcc/tpDcc-core) <br/>
• maya

### 🟢 jiminy-tailcoat
Config package for Jiminy, looks like some kind of fork.
see https://github.com/getblessing/jiminy-tailcoat/tree/master/tailcoat/plugins/maya/publish <br/>
• maya

### 🟠 tgbvfx-environment
https://github.com/TGBVFX/tgbvfx-environment <br/>
mostly studio specific plugins but some reusable <br/>
see [pluginfolder](https://github.com/TGBVFX/tgbvfx-environment/tree/master/environment/PYBLISHPLUGINPATH) <br/>
• FTRACK • MAYA • NUKEstudio • royalrender


### 🟠 LVFX-pipeline
https://github.com/lvfx-devteam/LVFX-pipeline <br/>
mostly studio specific plugins but some reusable (mayapy) <br/>
see https://github.com/lvfx-devteam/LVFX-pipeline/tree/master/pyblish-plugins <br/>
• FTRACK • HIERO • MAYA • NUKE


### 🔴 bumpybox
https://github.com/bumpybox/bumpybox-environment <br/>
The centralized pipeline used at Bumpybox <br/>
organised repo but no plugins that look reusable <br/>
• BIFROST • FTRACK • HIERO • LUCIDITY • MAYA • NUKE • PYTHON • XBMLANG


### 🔴 blacksmith 
see blacksmithvfx-environment/environment/PYBLISHPLUGINPATH/ <br/>
looks very studio specific, nothing to reuse i think. last submit 4 years ago.<br/>
https://github.com/blacksmithvfx/blacksmithvfx-environment <br/>
• deadline • ftrack • houdini • maya • nuke


### 🔴 wudi
https://github.com/hanbinren/wudi <br/>
seems like some kind of link between ftrack and dcc software. repo has no readme or instructions. <br/>
see [wudi/ftrack-connect-package-1.1.1/resource/connect-standard-plugins/](https://github.com/hanbinren/wudi/tree/359f3774e3de0003c8844e9f13d7fcba7e08a979/ftrack-connect-package-1.1.1/resource/connect-standard-plugins) <br/>
• HIERO • max • maya • nuke • ftrack
