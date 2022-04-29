Ray-MMD
========
###### [English](https://github.com/vellynproduction/ray-mmd-2.0/blob/master/README.md) &nbsp; [中文文档](https://github.com/vellynproduction/ray-mmd-2.0/blob/master/README_chs.md)  &nbsp; [Русский](https://github.com/vellynproduction/ray-mmd-2.0/blob/master/README_ru.md)
### Физически-Основанный Рендер ###
　　<img style="vertical-align: top;" src="./Shader/screenshots/logo.png" alt="logo" height="48px">

　　Ray-MMD - это бесплатная, мощная библиотека и пакет расширений [mikumikudance](http://www.geocities.jp/higuchuu4/index_e.htm), предлагающий простой способ добавления Физически-Основанного Рендера с высокой свободой действий. она написана на языке HLSL с использованием DirectX 9 и базируется на [mikumikueffect](https://bowlroll.net/file/35012). 

Screenshots:
------------
[![link text](./Shader/screenshots/screen1_small.jpg)](https://raw.githubusercontent.com/ray-cast/ray-mmd/master/Shader/screenshots/screen1.jpg)
[![link text](./Shader/screenshots/screen2_small.png)](https://raw.githubusercontent.com/ray-cast/ray-mmd/master/Shader/screenshots/screen2.png)
[![link text](./Shader/screenshots/screen3_small.jpg)](https://raw.githubusercontent.com/ray-cast/ray-mmd/master/Shader/screenshots/screen3.png)
[![link text](./Shader/screenshots/screen4_small.jpg)](https://raw.githubusercontent.com/ray-cast/ray-mmd/master/Shader/screenshots/screen4.png)

Загрузить
------------
　[![img](https://img.shields.io/badge/version-1.3.1v2-brightgreen.svg)](https://github.com/ray-cast/ray-mmd/archive/1.3.1v2.zip)
　[![img](https://img.shields.io/badge/version-1.5.0-brightgreen.svg)](https://github.com/ray-cast/ray-mmd/archive/1.5.0.zip)

* [Ray-MMD - 1.3.1v2 (zip)](https://github.com/ray-cast/ray-mmd/archive/1.3.1v2.zip)  (Обновлён: 27 апреля 2017)
* [Ray-MMD - 1.3.1v2 (tar.gz)](https://github.com/ray-cast/ray-mmd/archive/1.3.1v2.tar.gz)  (Обновлён: 27 апреля 2017)
* [Ray-MMD - 1.5.0 (zip)](https://github.com/ray-cast/ray-mmd/archive/1.5.0.zip) (Обновлён: 15 Января 2018)
* [Ray-MMD - 1.5.0 (tar.gz)](https://github.com/ray-cast/ray-mmd/archive/1.5.0.tar.gz) (Обновлен: 15 Января 2018)

* Ray-MMD - 2.0 - в будущем

- Extension
	- [ColorGrading - v1.0.0 (zip)](https://github.com/MikuMikuShaders/ColorGrading/archive/v1.0.0.zip) (Обновлён: 2 Декабря 2017, \[[Github](https://github.com/MikuMikuShaders/ColorGrading)\])
	- [FilmGrain - v1.0.0 (zip)](https://github.com/MikuMikuShaders/FilmGrain/archive/v1.0.0.zip) (Обновлён: 2 Декабря 2017, \[[Github](https://github.com/MikuMikuShaders/FilmGrain)\])
	- [FXAA - v1.0.0 (zip)](https://github.com/MikuMikuShaders/FXAA/archive/v1.0.0.zip) (Обновлён: 2 Декабря 2017, \[[Github](https://github.com/MikuMikuShaders/FXAA)\])
	- [LightBloom - v1.1.1 (zip)](https://github.com/MikuMikuShaders/LightBloom/archive/v1.1.1.zip) (Обновлён: 2 Декабря 2017, \[[Github](https://github.com/MikuMikuShaders/LightBloom)\])
	- [SMAA - v1.0.0 (zip)](https://github.com/MikuMikuShaders/SMAA/archive/v1.0.0.zip) (Обновлён: 2 Декабря 2017, \[[Github](https://github.com/MikuMikuShaders/SMAA)\])

Требования :
------------
* [MikuMikuDance](http://www.geocities.jp/higuchuu4/index_e.htm) - 9.26(x64) и выше (Без сглаживания)
* [MikuMikuEffect](https://bowlroll.net/file/35012) - 0.37(x64)
* Видеоадаптер с поддержкой Direct3D 9 с Shader Model 3.0 (ps_3_0)

Особенности :
------------
* Физически основанные материалы: Альбедо, Металлические, Гладкие/Прозрачные, Зеркальный/Отражаемый, Светящийся и т.д.
* Материал прозрачного покрытия с поглощением для имитации второго слоя
* Тканевый материал с тканевым ДФГ для имитации зеркального отражения
* Анизотропный материал для имитации зеркального отражения
* Специальные влажные материалы
* Аппроксимационные материалы подповерхностного рассеяния
* Микрофасетный спекулярный BRDF Кука-Торренса (GGX) и диффузный BRDF Берли.
* Физические единицы света
* Множественные источники света (точечный, пятно, солнце, прямоугольного, диск, сфера, труба, ies)
* Профили света IES (поддержка точечного и рассеяного света)
* Мягкая тень (PCF, VSM, PSSM)
* Поддержка нескольких светотеней на основе проекта двойного параболоида
* Линейное HDR-освещение
* Объемный свет (поддержка точечных, спотовых и IES источников света)
* Объемный туман (поддержка тумана в виде куба и сферы)
* Эффект светового вала
* Аппроксимация атмосферного тумана и рассеивания неба
* Эффект наземного тумана
* Небо на основе RGBT-кодирования
* Освещение на основе изображений на основе RGBT-кодирования
* Отражение в пространстве экрана
* Окружающее освещение экранного пространства
* Рассеивание подповерхностного пространства
* Пост-эффект - Боке с глубиной резкости
* Пост-эффект - Блум
* Пост-эффект - HDR Адаптация глаз
* Пост-эффект - Тон-маппинг (поддержка ACES-like, Reinhard, Hable, Hejl2015, NaughtyDog)
* Пост-эффект Цветовой баланс
* Пост-эффект - FXAA сглаживание
* Пост-эффект - SMAA сглаживание

Ресурсы :
------------
- HDRi
	- sIBL Archive - Hdrlabs.com \[[link](http://www.hdrlabs.com/sibl/archive.html)\].
	- ++skies; - **[aokcub](https://twitter.com/aokcub_cg)** \[[link](https://aokcub.net/cg/incskies/)\].
	- USC Institute \[[link](http://gl.ict.usc.edu/Data/HighResProbes)\].
- Редактор кода
	- Notepad++ \[[link](https://notepad-plus-plus.org)\].
	- Visual studio code \[[link](http://code.visualstudio.com/Download)\].

Контакты:
------------
　　Если вы разработчик, использующий это как часть вашей любви, и думаете связаться со мной, вы можете отправить код через `Pull requests` или не стесняйтесь связаться со мной через `twitter` и `issues`, я добавлю ваш профиль в члены команды, Спасибо.

* Свяжитесь со мной через Twitter: [@Rui](https://twitter.com/Rui_cg).(Оригинальный автор

   Если хотите связаться с данным супроводителем
* [DeviantArt](https://www.deviantart.com/vellyn-production)

[License (MIT)](https://raw.githubusercontent.com/vellynproduction/ray-mmd/master/LICENSE.txt)
-------------------------------------------------------------------------------
	Copyright (C) 2016-2022 Ray-MMD Developers. All rights reserved.

	https://github.com/ray-cast/ray-mmd
	
	or
	
	https://github.com/vellynproduction/ray-mmd-2.0

	Permission is hereby granted, free of charge, to any person obtaining a
	copy of this software and associated documentation files (the "Software"),
	to deal in the Software without restriction, including without limitation
	the rights to use, copy, modify, merge, publish, distribute, sublicense,
	and/or sell copies of the Software, and to permit persons to whom the
	Software is furnished to do so, subject to the following conditions:

	The above copyright notice and this permission notice shall be included
	in all copies or substantial portions of the Software.

	THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS
	OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
	FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.  IN NO EVENT SHALL
	BRIAN PAUL BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN
	AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN
	CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

Референсы :
--------
* Moving to the Next Generation - The Rendering Technology of Ryse \[[link](http://www.crytek.com/download/2014_03_25_CRYENGINE_GDC_Schultz.pdf)\].
* ACES Filmic Tone Mapping Curve \[[link](https://knarkowicz.wordpress.com/2016/08/31/hdr-display-first-steps/)\].
* Compact Normal Storage for small G-Buffers \[[link](http://aras-p.info/texts/CompactNormalStorage.html)\].
* Convert Blinn-Phong to Beckmann distribution \[[link](http://simonstechblog.blogspot.de/2011/12/microfacet-brdf.html)\].
* Spherical Gaussian approximation for Blinn-Phong, Phong and Fresnel \[[link](https://seblagarde.wordpress.com/2012/06/03/spherical-gaussien-approximation-for-blinn-phong-phong-and-fresnel/)\].
* Physically Based Area Lights \[[link](http://www.frostbite.com/wp-content/uploads/2014/11/course_notes_moving_frostbite_to_pbr.pdf)\].
* Physics and Math of Shading \[[link](http://blog.selfshadow.com/publications/s2015-shading-course/hoffman/s2015_pbs_physics_math_slides.pdf)\].
* Compact YCoCg Frame Buffer for small IBL-Buffer \[[link](http://jcgt.org/published/0001/01/02/)\].
* RGBM color encoding \[[link](http://graphicrants.blogspot.com/2009/04/rgbm-color-encoding.html)\].
* Horizon Occlusion for IBL \[[link](http://marmosetco.tumblr.com/post/81245981087)\].
* Screen space glossy reflections \[[link](http://roar11.com/2015/07/screen-space-glossy-reflections/)\].
* Parallax Occlusion Map \[[link](http://sunandblackcat.com/tipFullView.php?topicid=28)\].
* Convert Temperature to RGB \[[link](https://github.com/davidf2281/ColorTempToRGB)\].
* Texture repetition \[[link](http://www.iquilezles.org/www/articles/texturerepetition/texturerepetition.htm)\].
* Pre-Integrated Skin Shading \[[link](http://simonstechblog.blogspot.com/2015/02/pre-integrated-skin-shading.html)\]
* Normal Blending in Detail \[[link](http://blog.selfshadow.com/publications/blending-in-detail/)\]
* An Approximation to the Chapman Grazing-Incidence Function for Atmospheric Scattering \[[link](http://www.gameenginegems.net/gemsdb/article.php?id=1133)\]
* Bump map to normal \[[link](https://docs.unrealengine.com/latest/attachments/Engine/Rendering/LightingAndShadows/BumpMappingWithoutTangentSpace/mm_sfgrad_bump.pdf)\]
* Special-Case Materials Wetness \[[link](http://advances.realtimerendering.com/other/2016/naughty_dog/NaughtyDog_TechArt_Final.pdf)\]
* Mip Fog \[[link](http://advances.realtimerendering.com/other/2016/naughty_dog/NaughtyDog_TechArt_Final.pdf)\]
* Gaussian-kernel-calculator \[[link](http://dev.theomader.com/gaussian-kernel-calculator/)\]
* Ray Box Intersection on the GPU \[[link](https://github.com/hpicgs/cgsee/wiki/Ray-Box-Intersection-on-the-GPU)\]
* Hexagonal Bokeh Blur Revisited \[[link](https://colinbarrebrisebois.com/2017/04/18/hexagonal-bokeh-blur-revisited/)\]
* Practical Post-Process Depth of Field \[[link](https://developer.nvidia.com/gpugems/GPUGems3/gpugems3_ch28.html)\]
* Approximation of the IBL’s DFG term for a cloth BRDF \[[link](https://gist.github.com/romainguy/52d0e7f070d9ed7b44a0327d735fe33e)\]
* Real-Time Polygonal-Light Shading with Linearly Transformed Cosines\[[link](https://eheitzresearch.wordpress.com/415-2/)\]
* Limb Darkening model \[[link](http://www.physics.hmc.edu/faculty/esin/a101/limbdarkening.pdf)\]
