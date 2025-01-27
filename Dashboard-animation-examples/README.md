# **Dashboard animation examples**

How to create animated dashboards with RealDash.

- Name the animation XML file as *dashboardname_anim.xml*
- Place the animation XML file into same folder with *.rd* file
- On Windows version of RealDash, use *File* menu *Import* option to import the XML file (in edit mode).
	* This is required since Windows Store apps are not allowed to access files without user interaction.
- When XML has changed, reload the .rd file, or press *F2* on Windows to reload the dash and apply changes.
- Every time .rd file is saved it also contains all animations, there is no need to distribute the XML with .rd file.


&nbsp;
## **Files**
| file | description |
|:--------|:----------:|
| RealDash_animation_example.rd</br>RealDash_animation_example_anim.xml | Example dashboard that demonstrates most common animation techniques. |
| value_anim_example.rd</br>value_anim_example_anim.xml | Example of how to animate gauges based on input values. |
| Multiview.rd</br>Multiview_anim.xml | Multiview dashboard and associated animation XML file. Multiview is available for free in RealDash gallery. |


&nbsp;
## **Animations**

&nbsp;
### **Animation types**
| type | description |
|:--------|:----------:|
| morph | animate the area of the gauge or group |
| fade | fade gauge or group |
| value-morph | animate the area of the gauge or group based on input value |
| value-fade | fade gauge or group based on input value |


&nbsp;
### **Animation easing types**
Animations use easing. Multiple easing types are available for animations.

Each easing type may have postfix In, Out, or InOut. Default for all is InOut.

Default easing for all animations is SineInOut.

Examples of easing in action: [https://matthewlein.com/tools/ceaser]

| type | description |
|:--------|:----------:|
| Back | --- |
| Bounce | --- |
| Circ | --- |
| Cubic | --- |
| Elastic | --- |
| Expo | --- |
| Linear | --- |
| Quad | --- |
| Quart | --- |
| Quint | --- |
| Sine | --- |


[realdash.net](https://www.realdash.net)

