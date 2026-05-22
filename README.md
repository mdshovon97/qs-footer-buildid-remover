<div align="center">

<img src="preview/banner.jpg"/>

</div>

<p align="center">
<img src="https://readme-typing-svg.demolab.com?font=Orbitron&size=28&duration=2500&pause=1000&color=FF0000&center=true&vCenter=true&width=1000&lines=ROOT+ACCESS+GRANTED;SYSTEMUI+QS+FOOTER+BUILD+ID+REMOVED;ANDROID+RUNTIME+SMALI+MODIFICATION;MR+MATRIX+%7C+SHOVON+X+OS"/>
</p>

---

<div align="center">

<img src="https://img.shields.io/badge/ANDROID-12--16-red?style=for-the-baddiv&logo=android&logoColor=white"/>

<img src="https://img.shields.io/badge/SYSTEMUI-SMALI-red?style=for-the-baddiv&logo=android"/>

<img src="https://img.shields.io/badge/ROOT-REQUIRED-darkred?style=for-the-baddiv"/>

<img src="https://img.shields.io/badge/STATUS-ACTIVE-red?style=for-the-baddiv"/>

<img src="https://img.shields.io/badge/LICENSE-MSSML-red?style=for-the-baddiv"/>

---

<div align="center">

### QS FOOTER BUILD ID REMOVER

Advanced Android SystemUI runtime smali modification  
for removing QS Footer Build ID text from AOSP ROMs.

</div>

---

<p align="center">
<img src="https://user-images.githubusercontent.com/74038190/212284068-7c9c8c6d-8f4b-4d87-b7f2-3fbbf6d3b2d5.gif"/>
</p>

---

<div align="left">

# SYSTEM PREVIEW

</div>

<table>
<tr>
<td align="left">

#### BEFORE

<img src="preview/before.png" width="300"/>

</td>

<td align="left">

#### AFTER

<img src="preview/after.png" width="300"/>

</td>
</tr>
</table>

---

<div align="left">

# ABOUT THIS MODIFICATION

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

```smali
.method public final setBuildText()V
    .locals 0

    return-void
.end method
```

---

<div align="left">

# TARGET LINES

</div>

```txt
.line 349 → .line 714
```

Remove / Replace all instructions
within this section with THE KEY logic.
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

| ROM | STATUS |
| :--- | :---: |
| AOSP | ✅ |
| LineageOS | ✅ |

---

| ANDROID VERSION | STATUS |
| :--- | :---: |
| Android 12 | ✅ |
| Android 13 | ✅ |
| Android 14 | ✅ |
| Android 15 | ✅ |
| Android 16 QPR2 | ✅ |

---

<div align="left">

# 🎥 VIDEO GUIDE

</div>

> 🎬 16 MIN VIDEO GUIDE

[▶ WATCH NOW](https://drive.google.com/file/d/1RmnqVLj7OcPUXbx0bZnTiQ_T_-4UruUX/view?usp=drivesdk)

---

<div align="left">

# WARNING!

</div>

```diff
 THIS MODIFICATION AFFECTS LIVE SYSTEMUI RUNTIME
 INCORRECT IMPLEMENTATION MAY CAUSE:
```

The author of this build, as well as the developer  
MD Shovon, are not responsible for any possible damage,  
malfunctions, device bricking, or data loss that may  
result from using this modification.

Use this modification at your own risk.

Before performing any actions, please back up  
your `SystemUI.apk` using any method you are  
comfortable with.

---

<div align="left">

# GITHUB SYSTEM STATS

</div>

<p align="center">

<img width="95%" src="https://github-readme-stats.vercel.app/api?username=mdshovon97&show_icons=true&theme=tokyonight&hide_border=false&border_color=ff0000&title_color=ff0000&icon_color=ff0000&text_color=ffffff&bg_color=000000"/>

</p>

<p align="center">

<img width="95%" src="https://github-readme-streak-stats.herokuapp.com/?user=mdshovon97&theme=highcontrast&hide_border=false&ring=ff0000&fire=ff0000&currStreakLabel=ff0000&background=000000"/>

</p>

<p align="center">

<img width="70%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=mdshovon97&layout=compact&theme=tokyonight&hide_border=false&border_color=ff0000&title_color=ff0000&text_color=ffffff&bg_color=000000"/>

</p>

---

<div align="left">

# CONTRIBUTION MATRIX

</div>

<p align="ce">

<img src="https://raw.githubusercontent.com/Platane/snk/output/github-contribution-grid-snake-dark.svg"/>

</p>

---

<div align="left">

# CYBERPUNK HUD

</div>

<p align="center">

<img src="https://skillicons.dev/icons?i=android,linux,git,github,kotlin,java,bash"/>

</p>

---

<div align="left">

# LICENSE

</div>

Licensed under:

```txt
`MD SHOVON SYSTEMUI MOD LICENSE (MSSML) v1.1`
```

---

<div align="left">

# MR MATRIX • SHOVON X OS

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=120&section=footer&color=0:000000,50:1a0000,100:ff0000"/>

</div>
