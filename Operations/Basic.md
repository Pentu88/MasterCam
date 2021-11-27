# Basic
Vaneri / mänty / Sika Block 700

## Luettelo
- [1. 2D Profiili (Kohdistus)](#1-2d-profiili-kohdistus)
- [2. 2D Profiili (Tupit)](#2-2d-profiili-tupit)
- [3. 2D Tasaus](#3-2d-tasaus)
- [4. Suurnopeus Aluerouhinta](#4-aluerouhinta-rouhinta)
- [5. Suurnopeus Vakiokarheus (Rouhinta)](#5-vakiokarheus-rouhinta)
- [6. 2D Profiili (Rouhinta)](#6-2d-profiili-rouhinta)

## **1.** 2D Profiili (*Kohdistus*)
Kohdistus naarmujen ajo pöytään.

![Kuva: 2D profiili][type_contour]

![Kuva: Työkalu T07][tool_t7]

![Kuva: Cut parammeters][cutparam-contour-1]

![Kuva: Linking parammeters][linkingparam-target]

**Kuva puuttuu**


## **2.** 2D Profiili (*Tupit*)
Puutuipien ajo pöytään ja kappaleen pohjaan. Messinki tupien ajo jakotasolle.

![Kuva: 2D profiili][type_contour]

![Kuva: Työkalu T08][tool_t8-1]

![Kuva: Cut parammeters][cutparam-contour-1]

![Kuva: Linking parammeters][linkingparam-woodenpin]

![Kuva: 11][arcfilparam-woodenpin]

## **3.** 2D Tasaus

![Kuva: 2D profiili][type_face]

![Kuva: Työkalu T01][tool_t1]

![Kuva: Cut parammeters][cutparam-face]

![Kuva: Depht cuts][depthcuts]

![Kuva: Linking parammeters][linkingparam-face]

![Kuva: 11][arcfilparam-face]

## **4.** Aluerouhinta (*Rouhinta*)

![Kuva: 2D profiili][type-arearoughing]

![Kuva: model geometry][geometry-roughing]

![Kuva: toolpath control][control-1]

![Kuva: Työkalu T03][tool_t3]

![Kuva: Cut parammeters][cutparam-area]


![Kuva: Transitions][transitions-1]

**Kuva puuttuu**

![Kuva: Linking parammeters][linkingparam-1]

![Kuva: Arc filter - Tolerance][arcfilparam-roughing]

## **5.** Vakiokarheus (*Rouhinta*)

![Kuva: Toolpath type][type-scallop]

![Kuva: model geometry][geometry-roughing]

![Kuva: toolpath control][control-2]

![Kuva: Työkalu T03][tool_t3]

![Kuva: Cut parammeters][cutparam-scallop-1]

![Kuva: Transitions][transitions-2]

![Kuva: Steep / Shallow][steepshallow-1]

![Kuva: Linking parammeters][linkingparam-2]

![Kuva: Arc filter - Tolerance][arcfilparam-roughing-2]

## **6.** 2D Profiili (*Rouhinta*)

[type_contour]: Images/Toolpath_type-2D_Contour.png 'Työstöradan tyyppi'
[tool_t7]: Images/Tool-T07-Target.png 'Työkalu'
[cutparam-contour-1]: Images/Cut_parammeters-Contour_1.png 'Työstöparametrit'
[linkingparam-target]: Images/Linking_parameters-Target.png 'Siirtymisparametrit'
[arcfilparam-target]: Images/Arc_filter_Tolerance-Target.png 'Kaarisuodatus / Toleranssi'
[tool_t8-1]: Images/Tool-T08-8T-.png 'Työkalu'
[cutparam-contour-2]: Images/Cut_parammeters-Contour_2.png 'Työstöparametrit'
[linkingparam-woodenpin]: Images/Linking_parameters-woodenpin.png 'Siirtymisparametrit'
[arcfilparam-woodenpin]: Images/Arc_filter_Tolerance-woodenpin.png 'Kaarisuodatus / Toleranssi'
[type_face]: Images/Toolpath_type-2D_Face.png 'Työstöradan tyyppi'
[tool_t1]: Images/Tool-T01-80L.png 'Työkalu'
[cutparam-face]: Images/Cut_parammeters-Face.png 'Työstöparametrit'
[depthcuts]: Images/Depht_cuts-Face.png 'Syvyyslastut'
[linkingparam-face]: Images/Linking_parameters-face.png 'Siirtymisparametrit'
[arcfilparam-face]: Images/Arc_filter_Tolerance-face.png 'Kaarisuodatus / Toleranssi'
[type-arearoughing]: Images/Toolpath_type-Area_roughing.png 'Työstöradan tyyppi'
[geometry-roughing]: Images/Model_geometry-Roughing.png 'Mallin geometria'
[control-1]: Images/Toolpath_control-1.png 'Työstöradan ohjaus'
[tool_t3]: Images/Tool-T03-20R.png 'Työkalu'
[cutparam-area]: Images/Cut_parammeters-Area_roughing.png 'Työstöparametrit'

[transitions-1]: Images/Transitions-1.png 'Siirtymiset'
[linkingparam-1]: Images/Linking_parameters-1.png 'Siirtymisparametrit'
[arcfilparam-roughing]: Images/Arc_filter_Tolerance-roughing.png 'Kaarisuodatus / Toleranssi'
[type-scallop]: Images/Toolpath_type-Scallop.png 'Työstöradan tyyppi'
[control-2]: Images/Toolpath_control-2.png 'Työstöradan ohjaus'
[cutparam-scallop-1]: Images/Cut_parameters-Sacallop-1.png 'Työstöparametrit'
[transitions-2]: Images/Transitions-2.png 'Siirtymiset'
[steepshallow-1]: Images/Steep_shallow-1.png 'Jyrkkä / laakea'
[linkingparam-2]: Images/Linking_parameters-2.png 'Siirtymisparametrit'
[arcfilparam-roughing-2]: Images/Arc_filter_Tolerance-roughing-2.png 'Kaarisuodatus / Toleranssi'

## Välilehdet 

- [type] - Työstöradan tyyppi (
- [geometry] - Mallin geometria (model geometry)
- [control] - Työstöradan ohjaus (Toolpath control)
- [tool] - Työkalu (Tool)
- [holder] - pidin (Holder)
- [Stock] - aihio (Stock)
- [cutparam] - Työstöparametrit (Cut parammeters)
- [depthcuts] - Syvyyslastut (Depth Cuts)
- [transitions] - Siirtymiset ?
- [sleepshallow] - Jyrkkä / laakea (Steep / Shallow)?
- [linkingparam] - Siirtymisparametrit (Linking parammeters) ?
- [arcfilparam] - Kaarisuodatus / Toleranssit (Arc filter / Tolerance)

## TODO
- [ ] Kohdistus, kaarisuodatus / toleranssi (kuva puuttuu)
- [x] Tasaus, Syvyyslastut (kuva puuttuu)
- [ ] Aluerouhinta, Jyrkkä / laakea (kuva puuttuu)
