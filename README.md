Blender3D Import psk psa addon
========================
<ul>
<li>This is an heavily edited version of original blender plugin by Darknet / Optimus_P-Fat / Active_Trash / Sinsoft / flufy3d: https://en.blender.org/index.php/Extensions:2.6/Py/Scripts/Import-Export/Unreal_psk_psa (<a href="https://wiki.blender.org/index.php/Extensions:2.6/Py/Scripts/Import-Export/Unreal_psk_psa">old link</a>)
<li>Import mesh and skeleton from <b>.psk/.pskx</b></li>
<li>Import animation from <b>.psa</b></li>
<li>Game files can be exported to psk/psa by UModel: 
https://github.com/gildor2/UModel</li>
</ul>

<h5>Changes from original release</h5>
<ul>
<li>Blender 2.80+ support</li>
<li>Fixed animation/skeleton import</li>
<li>Psa: using .config generated by UModel</li>
<li>Panel UI updated: All actions to NLA track, Mesh / skeleton or both import, Scale down, Vertex color</li>
</ul>

<h3>Download</h3>  

* <a href ="https://github.com/Befzz/blender3d_import_psk_psa/releases">**Releases**</a> -> **_280.py** file.

  Blender 2.7x ?  
* <a href ="https://github.com/Befzz/blender3d_import_psk_psa/releases">**Releases**</a> -> *Source code (zip)* -> (use _270.py version)


<h3>Install</h3> 

* Edit -> Preferences... -> Add-ons -> Install...  
  
  Blender 2.7x ?  
* File -> User preferences -> Add-ons -> Install Add-on from File...  

<h3>Install manually</h3> 

  Blender will look for .py add-ons there:  
  (*you may need to create folders manually for your blender version!*)

    %APPDATA%\Blender Foundation\Blender\2.79\scripts\addons\  
    %APPDATA%\Blender Foundation\Blender\ _version_ \scripts\addons\
    

Blender 2.7x ?  

  Disable original add-on:  
`Import Unreal Skeleton Mesh (.psk)/Animation Set (.psa)`  

  Enable this one:  
`Import Unreal Skeleton Mesh (.psk)/Animation Set (.psa) (280)`
<h3>Usage</h3>  
<table><tbody>
<tr><th> Panel in 3DView (270) </th><th> Panel in 3DView (280) </th></tr>
<tr><td valign="top" align="center"><img src="https://github.com/Befzz/blender3d_import_psk_psa/blob/latest/imgs/270_psk.jpg"/></td>
<td valign="top" align="center"><img src="https://github.com/Befzz/blender3d_import_psk_psa/blob/latest/imgs/280_psk.jpg"/></td>
</tr></tbody></table>
