<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=300&color=0:000000,50:1a0000,100:ff0000&text=⚡%20MATRIX%20SYSTEM%20BOOT&fontColor=ffffff&fontSize=45&fontAlignY=40&animation=fadeIn&desc=ANDROID%20SYSTEMUI%20RUNTIME%20MODIFICATION%20PROTOCOL&descAlignY=60"/>

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

# ⚡ MATRIX SYSTEM BOOT

### QS FOOTER BUILD ID REMOVER

Advanced Android SystemUI runtime smali modification  
for removing QS Footer Build ID text from AOSP ROMs.

</div>

---

<div align="center">

<img src="preview/banner.png"/>

</div>

---

<img src="https://user-images.githubusercontent.com/74038190/212284068-7c9c8c6d-8f4b-4d87-b7f2-3fbbf6d3b2d5.gif">

<div align="center">

# ⚡ SYSTEM PREVIEW

</div>

<table align="center">
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

<div align="center">

# ⚡ ROOT TERMINAL STATUS

</div>

```diff
+ ROOT ACCESS GRANTED
+ SYSTEMUI RUNTIME DETECTED
+ TARGET METHOD LOCATED
+ SMALI PATCH READY
- RRO OVERLAY METHOD REJECTED
```

---

<div align="center">

# ⚡ ABOUT THIS MODIFICATION

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

<div align="center">

# ⚡ WHY RRO CANNOT DO THIS

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

<div align="center">

# ⚡ MAIN IMPLEMENTATION

</div>

<details>
<summary>⚡ VIEW MAIN SMALI IMPLEMENTATION</summary>

```smali
.method public final setBuildText()V
    .locals 0

    return-void
.end method
```

</details>

---

<div align="center">

# ⚡ TARGET LINES

</div>

```txt
.line 349 → .line 714
```

Replace all instructions between these lines  
with the implementation above.

---

<div align="center">

# ⚡ FILE LOCATION

</div>

```txt
SystemUI_src/smali/com/android/systemui/qs/QSFooterView.smali
```

---

<div align="center">

# ⚡ SYSTEM COMPATIBILITY

</div>

| ROM | STATUS |
|------|------|
| AOSP | ✅ |
| LineageOS | ✅ |
| PixelOS | ✅ |
| Evolution X | ✅ |

---

| ANDROID VERSION | STATUS |
|------|------|
| Android 12 | ✅ |
| Android 13 | ✅ |
| Android 14 | ✅ |
| Android 15 | ✅ |
| Android 16 QPR2 | ✅ |

---

<div align="center">

# ⚡ VIDEO GUIDE

</div>

```txt
resources/16-min-video-guide.txt
```

---

<div align="center">

# ⚡ WARNING

</div>

```diff
- THIS MODIFICATION AFFECTS LIVE SYSTEMUI RUNTIME
- INCORRECT IMPLEMENTATION MAY CAUSE:
```

- SystemUI crash
- bootloop
- instability
- data loss

Backup SystemUI.apk before modification.

---

<div align="center">

# ⚡ GITHUB SYSTEM STATS

</div>

<p align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=mdshovon97&show_icons=true&theme=transparent&title_color=ff0000&icon_color=ff0000&text_color=ffffff&border_color=ff0000"/>

<img height="180em" src="https://github-readme-streak-stats.herokuapp.com/?user=mdshovon97&theme=highcontrast&ring=ff0000&fire=ff0000&currStreakLabel=ff0000"/>

</p>

---

<div align="center">

# ⚡ LANGUAGE MATRIX

</div>

<p align="center">

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=mdshovon97&layout=compact&theme=transparent&title_color=ff0000&text_color=ffffff&border_color=ff0000"/>

</p>

---

<div align="center">

# ⚡ CONTRIBUTION MATRIX

</div>

<p align="center">

<img src="https://raw.githubusercontent.com/Platane/snk/output/github-contribution-grid-snake-dark.svg"/>

</p>

---

<div align="center">

# ⚡ CYBERPUNK HUD

</div>

<p align="center">

<img src="https://skillicons.dev/icons?i=android,linux,git,github,kotlin,java,bash"/>

</p>

---

<div align="center">

# ⚡ LICENSE

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

<div align="center">

# ⚡ CREDITS

Original SystemUI modification by

# MR MATRIX • SHOVON X OS

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=120&section=footer&color=0:000000,50:1a0000,100:ff0000"/>

</div>
