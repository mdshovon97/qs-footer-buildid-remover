<div align="center">

<img src="preview/banner.jpg"/>

</div>


<p align="center">
<img src="https://readme-typing-svg.demolab.com?font=Orbitron&size=28&duration=2500&pause=1000&color=FF0000&center=true&vCenter=true&width=1000&lines=ROOT+ACCESS+GRANTED;SYSTEMUI+TARGET+DETECTED;QS+FOOTER+BUILD+ID+REMOVER;ANDROID+RUNTIME+SMALI+MODIFICATION;MR+MATRIX+%7C+SHOVON+X+OS"/>
</p>

---

<div align="center">

<img src="https://img.shields.io/badge/ANDROID-12--16-red?style=for-the-badge&logo=android&logoColor=white"/>

<img src="https://img.shields.io/badge/SYSTEMUI-SMALI-black?style=for-the-badge&logo=android"/>

<img src="https://img.shields.io/badge/ROOT-REQUIRED-darkred?style=for-the-badge"/>

<img src="https://img.shields.io/badge/STATUS-ACTIVE-red?style=for-the-badge"/>

<img src="https://img.shields.io/badge/LICENSE-MSSML-red?style=for-the-badge"/>

</div>

---

<div align="center">

# MATRIX SYSTEM BOOT

### QS FOOTER BUILD ID REMOVER

Advanced Android SystemUI runtime smali modification  
for removing QS Footer Build ID text from AOSP ROMs.

</div>

---

<img src="https://user-images.githubusercontent.com/74038190/212284068-7c9c8c6d-8f4b-4d87-b7f2-3fbbf6d3b2d5.gif">

<div align="left">

# SYSTEM PREVIEW

</div>

<table align="left">
<tr>
<th>BEFORE</th>
<th>AFTER</th>
</tr>

<tr>
<td><img src="preview/before.png" width="300"/></td>
<td><img src="preview/after.png" width="300"/></td>
</tr>
</table>

---

<div align="left">

# ROOT TERMINAL STATUS

</div>

```diff
+ ROOT ACCESS GRANTED
+ SYSTEMUI RUNTIME DETECTED
+ TARGET METHOD LOCATED
+ SMALI PATCH READY
- RRO OVERLAY METHOD REJECTED
```

---

<div align="left">

# BOUT THIS MODIFICATION

</div>

This project demonstrates direct Android SystemUI runtime smali modification.

The implementation removes:

```txt
QS Footer Build ID Text
```

from Android SystemUI runtime logic.

Target smali path:

```txt
com/android/systemui/qs/QSFooterView.smali
```

---

<div align="left">

# WHY RRO CANNOT DO THIS

</div>

Normal Runtime Resource Overlays (RRO) can modify:

- strings
- dimens
- drawables
- layouts
- booleans
- integers

But RRO cannot:

- modify smali methods
- inject runtime logic
- override execution flow
- replace Java/Kotlin implementation
- bypass conditional checks

Because of these limitations,  
this modification requires direct smali editing.

---

<div align="left">

# THIS IS THE KEY

</div>

<details>
<summary> VIEW MAIN SMALI IMPLEMENTATION</summary>

```smali
.method public final setBuildText()V
    .locals 0

    return-void
.end method
```

</details>

---

<div align="left">

# TARGET LINES

</div>

```txt
.line 349 → .line 714
```

Replace all instructions between these lines  
with the implementation above.

---

<div align="left">

# FILE LOCATION

</div>

```txt
SystemUI_src/smali/com/android/systemui/qs/QSFooterView.smali
```

---

<div align="left">

# SYSTEM COMPATIBILITY

</div>

 ROM | STATUS 
 AOSP LineageOS ✅ 

---

| ANDROID VERSION | STATUS |
|------|------|
| Android 12 | ✅ |
| Android 13 | ✅ |
| Android 14 | ✅ |
| Android 15 | ✅ |
| Android 16 QPR2 | ✅ |

---

<div align="left">

# VIDEO GUIDE

</div>

```txt
resources/16-min-video-guide.txt
```

---

<div align="left">

# WARNING!

</div>

```diff
- THIS MODIFICATION AFFECTS LIVE SYSTEMUI RUNTIME
- INCORRECT IMPLEMENTATION MAY CAUSE:
```

The author of this build, as well as the
developer MD Shovon, are not responsible for any
possible damage, malfunctions, device bricking,
or data loss that may result from using this
modification.
Use this modificaton at your own risk.
Before perfoming any actions, please back up 
your SystemUI.apk using any method you are
comfortable with.

---

<div align="left">

# GITHUB SYSTEM STATS

</div>

<p align="left">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=mdshovon97&show_icons=true&theme=transparent&title_color=ff0000&icon_color=ff0000&text_color=ffffff&border_color=ff0000"/>

<img height="180em" src="https://github-readme-streak-stats.herokuapp.com/?user=mdshovon97&theme=highcontrast&ring=ff0000&fire=ff0000&currStreakLabel=ff0000"/>

</p>

---

<p align="left">

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=mdshovon97&layout=compact&theme=transparent&title_color=ff0000&text_color=ffffff&border_color=ff0000"/>

</p>

---

<div align="left">

# CONTRIBUTION MATRIX

</div>

<p align="left">

<img src="https://raw.githubusercontent.com/Platane/snk/output/github-contribution-grid-snake-dark.svg"/>

</p>

---

<div align="left">

# CYBERPUNK HUD

</div>

<p align="left">

<img src="https://skillicons.dev/icons?i=android,linux,git,github,kotlin,java,bash"/>

</p>

---

<div align="left">

# LICENSE

</div>

Licensed under:

```txt
MD SHOVON SYSTEMUI MOD LICENSE (MSSML) v1.1
```

See:

```txt
LICENSE.txt
```

---

<div align="left">

# CREDITS

Original SystemUI modification by

# MR MATRIX • SHOVON X OS

</div>

---

<div align="left">

<img src="https://capsule-render.vercel.app/api?type=waving&height=120&section=footer&color=0:000000,50:1a0000,100:ff0000"/>

</div>
