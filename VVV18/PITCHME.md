# WB-Toolbox 3 &nbsp; @fa[object-ungroup]
###### A Simulink Toolbox for Whole-Body Control

<p style="margin: 59px; padding: 1px 0px 1px 0px"></p>

### Towards Automatic Code Generation

<p style="margin: 59px; padding: 1px 0px 1px 0px"></p>

<table class="invisible">
    <thead>
        <tr>
            <th></th>
            <th></th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td style="text-align: right;">
                <small>Diego Ferigo</small>
            </td>
            <td style="text-align: center;">
                <small>@fa[user]</small>
            </td>
            <td style="text-align: center;">
                <small>@fa[map-marker]</small>
            </td>
            <td>
                <small>VVV18 @ Santa Margherita Ligure</small>
            </td>
        </tr>
        <tr>
            <td style="text-align: right;">
                <small>diego.ferigo@iit.it</small>
            </td>
            <td style="text-align: center;">
                <small>@fa[envelope]</small>
            </td>
            <td style="text-align: center;">
                <small>@fa[calendar]</small>
            </td>
            <td>
                <small>10 February 2018</small>
            </td>
        </tr>
    </tbody>
</table>

---

|                            |                              |
| :------------------------: | :--------------------------- |
| <h2>@fa[binoculars]</h2>   | <h2>Aims</h2>               |
| <h2>@fa[puzzle-piece]</h2> | <h2>`WBT3` New Features</h2> |
| <h2>@fa[map-signs]</h2>    | <h2>Future directions</h2>   |

---

## Aims &nbsp; @fa[binoculars]

<p style="margin: 34px; padding: 1px 0px 1px 0px"></p>

<p class="fragment light">
    Controller designers <small style="vertical-align: middle;">@fa[heart]</small> Simulink
</p>

<p style="margin: 34px; padding: 1px 0px 1px 0px"></p>

<ul>
<li class="fragment">Rapid Prototyping</li>
<li class="fragment">Robot as a Black-Box</li>
<li class="fragment">Seamless switch `simulator` <small style="vertical-align: middle;">@fa[arrows-h]</small> `robot`</li>
<li class="fragment">Debugging ease (scopes!)</li>
</ul>

+++

### Components overview

![Logo](assets/image/WB-Toolbox_components.png)

+++?image=assets/image/WB-Toolbox_StatesActuator_transparent.png&size=contain

### States and Actuators
<p style="margin: 250px; padding: 1px 0px 1px 0px"></p>

+++?image=assets/image/WB-Toolbox_Model_transparent.png&size=contain

### Kinematics and Dynamics
<p style="margin: 250px; padding: 1px 0px 1px 0px"></p>

+++?image=assets/image/WB-Toolbox_Utilities_transparent.png&size=contain

### Utilities
<p style="margin: 250px; padding: 1px 0px 1px 0px"></p>

---

## `WBT3` New Features &nbsp; @fa[puzzle-piece]

<p style="margin: 29px; padding: 1px 0px 1px 0px"></p>

<ul>
<li class="fragment">
    Multiple robots control
</li>
<li class="fragment">
    Self contained (no config files)
</li>
<li class="fragment">
    Under the hood: big code refactoring
</li>
<li class="fragment">
    Deprecated `wholeBodyInterface` [<small style="vertical-align: middle;">@fa[github]</small>](https://github.com/robotology/wholebodyinterface) in favour of:<br>
    <ul>
        <li>`iDynTree` [<small style="vertical-align: middle;">@fa[github]</small>](https://github.com/robotology/idyntree)</li>
        <li>`RemoteControlBoardRemapper` [<small style="vertical-align: middle;">@fa[link]</small>](http://www.yarp.it/classyarp_1_1dev_1_1RemoteControlBoardRemapper.html)</li>
    </ul>
</li>

+++?image=assets/image/two_icubs.gif&size=contain

---

## Future directions &nbsp; @fa[map-signs]

<p style="margin: 69px; padding: 1px 0px 1px 0px"></p>

- Automatic code generation |
- Blocks C++ Unit Tests |

<p style="margin: 39px; padding: 1px 0px 1px 0px"></p>

+++
<!-- .slide: id="slide-noimageborder" data-background="#E9E9F1" -->

![CodeGeneration](assets/image/MatlabCodeGeneration.png)

---?image=assets/image/MineralTone.png&size=cover
<!-- .slide: id="slide-end" -->

<p style="margin: 19px; padding: 1px 0px 1px 0px"></p>

### @fa[link] Resources

|               |                                                                 |
| ------------- | --------------------------------------------------------------- |
| WB-Toolbox    | https://github.com/robotology/WB-Toolbox @fa[code-fork] `WB3.0` |
| Release Notes | https://github.com/robotology/WB-Toolbox/issues/65              |

<p style="margin: 79px; padding: 1px 0px 1px 0px"></p>

## Thank you

<p style="margin: 79px; padding: 1px 0px 1px 0px"></p>

<p class="light" style="font-size: 40%">Happy holidays! @fa[tree] @fa[glass] @fa[bed]</p>
