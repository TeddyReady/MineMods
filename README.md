# Сборка модов для Minecraft Fabric 1.18.2

## Оглавление
1. [**API**](#api);
2. [**Моды на оптимизацию**](#моды-на-оптимизацию);
3. [**Моды на визуал**](#моды-на-визуал);
4. [**Моды на обновление боевой системы**](#моды-на-обновление-боевой-системы);
5. [**Моды на мобов**](#моды-на-мобов);
6. [**Моды на новые предметы**](#моды-на-новые-предметы);
7. [**Глобальные моды**](#глобальные-моды);
8. [**Моды на структуры**](#моды-на-структуры);
9. [**Моды на генерацию**](#моды-на-генерацию);
10. [**Прочие моды**](#прочие-моды);

## [API](#оглавление)
1. [**Fabric API**](https://minecraft-inside.ru/mods/94725-fabric-api.html) - API для модлоадера Fabric;
2. [**FabricShieldLib**](https://ru-minecraft.ru/mody-minecraft/72594-fabric-shield-lib.html) - API для модов на щиты;
3. [**Fabric Language Kotlin**](https://minecraft-inside.ru/mods/153218-fabric-language-kotlin.html) - Библиотека, позволяющая разработчикам модификаций использовать для их создания язык программирования Kotlin;
4. [**YUNG's API**](https://minecraft-inside.ru/mods/155323-yungs-api.html) - это библиотека, нужная для работы модов от авторы YUNG;
5. [**Architectury API**](https://minecraft-inside.ru/mods/153263-architectury-api.html) - Библиотека с промежуточным API, позволяющая упростить разработку мультиплатформенных модов;
6. [**Forge Config API Port**](https://www.curseforge.com/minecraft/mc-mods/forge-config-api-port-fabric) - is a modding library for mod developers that provides the whole config system designed by the Forge team to the Fabric ecosystem;
7. [**GeckoLib**](https://minecraft-inside.ru/mods/146483-geckolib.html) - Движок прямой кинематики для Minecraft, он позволяет переносить анимации в игру и использовать их в автоматическом режиме;
8. [**Iceberg**](https://ru-minecraft.ru/mody-minecraft/70873-iceberg-mod-yadro-1171-1165.html) - И ещё один мод-ядро, что нужен для работы немалого количества модов;
9. [**CriticaLib**](https://www.curseforge.com/minecraft/mc-mods/criticalib) - lib for Damage Indicator mod;
10. [**Bookshelf**](https://minecraft-inside.ru/mods/22154-bookshelf.html) - это небольшой мод-ядро, предназначенный для работы других модов. Также он добавит новые виды брони для лошадей и позволит изменять цвет предметов;
11. [**PlayerAnimator**](https://www.curseforge.com/minecraft/mc-mods/playeranimator) - library,
animate the player using keyframes;
12. [**Prism**](https://ru-minecraft.ru/mody-minecraft/74630-prism.html) - это техническая библиотека от разработчика Grend_G, он использует ее для упрощения разработки и поддержки собственных модов, а так же другие разработчики могут использовать её;
13. [**Collective**](https://minecraft-inside.ru/mods/136251-collective.html) - Библиотека необходимая для работы модов от автора Serilum. Она содержит в себе общий код, который используется в модах автора, тем самым позволяя не дублировать его в каждом отдельном моде;
14. [**ConnectedTexturesMod**](https://ru-minecraft.ru/mody-minecraft/49568-connectedtexturesmod.html) - это вспомогательный мод необходимый для крутого и популярного мода Chisel, он позволяет лучше работать с пакетами ресурсов и текстурами, без него игра будет вылетать при запуске игры, либо сообщать о необходимости мода CTM;
15. [**Cloth API**](https://ru-minecraft.ru/mody-minecraft/69396-cloth-api.html) - это еще один технический мод для Fabric, он содержит в себе разные функции которые используют авторы достаточно большого количества модов, они позволяют упростить создание мода и сделать его работу более эффективной, но из-за этого вместе с этим модом придется установить и данный технический мод;
16. [**Cloth Config API**](https://ru-minecraft.ru/mody-minecraft/65857-cloth-config-api.html) - технический мод от shedaniel который требуется для других модов. Сам по себе мод ничего не добавляет и в игре не меняет, его нужно установить только если другой мод этого требует;
17. [**Puzzles Lib**](https://minecraft-inside.ru/mods/161089-puzzles-lib.html) - Библиотека для модификаций автора Fuzs. Она состоит из нескольких фреймворков и служебных классов и предлагает уровень абстракции для разработки модов как для Forge, так для Fabric, делая портирование и поддержку модов на разные загрузчики простым занятием, без переписывания логики проектов;
18. [**Balm**](https://minecraft-inside.ru/mods/151367-balm.html) - Библиотека для модов от автора BlayTheNinth. Сама по себе она ничего не добавляет, но позволяет другим модам автора использовать общий код, необходимый для работы модов с forge и fabric;
19. [**ARRP**](https://ru-minecraft.ru/mody-minecraft/72277-arrp.html) - это технический мод который добавляет API для разработчиков модов которое позволяет упростить работу с крафтами в их модах. С этим техническим модом они смогут программировать рецепты в коде мода, без необходимости создавать Json конфиги крафтов;
20. [**TerraBlender**](https://minecraft-inside.ru/mods/154255-terrablender.html) - Библиотека, предоставляющая другим модам простой и универсальный способ добавления новых видов биомов;

## [Моды на оптимизацию](#оглавление)
1. [**Sodium**](https://minecraft-inside.ru/mods/137408-sodium.html) - это рендер-движок с открытым кодом, позволяющий значительно повысить частоту кадров, уменьшить подвисания и исправить графические ошибки в майнкрафт;
2. [**Sodium Extra**](https://ru-minecraft.ru/mody-minecraft/67253-sodium-extra.html) - дополнение для sodium которое добавляет возможность настроить графику в Minecraft более детально, что поможет на слабых устройствах;
3. [**Indium**](https://minecraft-inside.ru/mods/155383-indium.html) - это аддон для Sodium, добавляющий совместимость для модификаций, использующих Fabric Rendering API;
4. [**Dynamic FPS**](https://minecraft-inside.ru/mods/106352-dynamic-fps.html) - Полезный Fabric-мод, который будет автоматически снижать фпс во время сворачивания и бездействия игры. Это позволит значительно снизить нагрузку на компьютер;
5. [**EntityCulling**](https://ru-minecraft.ru/mody-minecraft/67228-entity-culling.html) - создан для оптимизации расхода ресурсов на просчет и рендеринг игровых сущностей, в том числе мобов, он ограничивает дальность просчета до 64 блоков, а так же старается применяет технологию raytraces для просчета видимых и скрытых сущностей с целью оптимизации;
6. [**Better Fps - Render Distance**](https://minecraft-inside.ru/mods/152686-better-fps-render-distance.html) - способен улучшить производительность игры и повысить фпс за счет изменения системы рендеринга с классической квадратной на трёхмерную круговую, которая позволяет прогружать на 10-35% меньше чанков;
7. [**Better Beds**](https://www.geroncraft.ru/better-beds/) - Мод для Майнкрафт, который изменяет рендерер кровати, чтобы использовать модели json вместо рендерера блочных сущностей;
8. [**Concurrent Chunk Management Engine**](https://www.curseforge.com/minecraft/mc-mods/c2me-fabric) - A Fabric mod designed to improve the chunk performance of Minecraft;
9. [**Smooth Boot**](https://ru-minecraft.ru/mody-minecraft/66097-smooth-boot.html) -  немного ускорит процесс загрузки игры и сделает его более плавным, теперь игра при загрузке не будет потреблять 100% процессора, а значит не будет лагов \ прерываний музыки \ подвисаний курсоров в других приложениях;
10. [**LazyDFU**](https://www.curseforge.com/minecraft/mc-mods/lazydfu) - is an optimization mod for Minecraft that defers unnecessary initialization work so that it is only performed if required;
11. [**Lithium**](https://minecraft-inside.ru/mods/136978-lithium.html) - мод оптимизирует серверную часть игры, что приведет к улучшению частоты кадров и скорости отклика. Совместим с Phosphor;
12. [**Starlight**](https://minecraft-inside.ru/mods/152800-starlight.html) - отличная замена моду Phosphor, мод полностью заменяет ванильный движок работающий с освещением. Модификация показывает огромный прирост производительности в Minecraft, это можно увидеть на графиках сравнение с Phosphor;
13. [**Enhanced Block Entities**](https://minecraft-inside.ru/mods/144195-enhanced-block-entities.html) - EBE нацелен на повышение производительности игры путем оптимизации рендеринга блочных сущностей. На данный момент мод улучшит работу с сундуками, увеличивая производительность при большом количестве установленных сундуков;
14. [**Clumps**](https://minecraft-inside.ru/mods/51947-clumps.html) - Неплохая модификация, с которой сферы опыта будут собираться в одну большую единицу. Это позволит уменьшить лаги и сократить время сбора элементов;

## [Моды на визуал](#оглавление)
1. [**Iris**](https://minecraft-inside.ru/mods/149349-iris-shaders.html) - добавляет поддержку существующих шейдеров в игру с установленным Sodium;
2. [**Damage Indicators**](https://minecraft-inside.ru/mods/35587-damage-indicators-by-torocraft.html) - Довольно простая реализация мода Damage Indicators. При наведении курсора на моба в левом верхнем углу экрана появится интерфейс с уровнем его жизни;
3. [**Eating Animation**](https://minecraft-inside.ru/mods/150338-eating-animation.html) - модификация изменит анимацию поедания;
4. [**Traveler's Titles**](https://minecraft-inside.ru/mods/148766-travelers-titles.html) - С данным модом смена измерения и биома будет сопровождаться текстом, наподобие РПГ-игр;
5. [**AppleSkin**](https://minecraft-inside.ru/mods/55336-appleskin.html) - добавит вырезанные из AppleCore твики, которые покажут насколько насытит вас та или иная еда и визуализируют насыщение в интерфейсе голода;
6. [**Advancement Plaques**](https://minecraft-inside.ru/mods/148572-advancement-plaques.html) - заменит скучные всплывающие сообщения о получении достижения. Теперь они станут ярче, красочней и получат красивую анимацию появления, благодаря чему, каждое новое достижение станет для вас торжественным событием;
7. [**Visuality**](https://minecraft-inside.ru/mods/150240-visuality.html) - простой косметический мод, который добавляет новые разновидности частицы, немного дополняющие и улучшающие вид игры: кристаллические искры, частицы мобов, частицы окружения и многое другое;
8. [**Better Animal Models**](https://minecraft-inside.ru/mods/66770-better-animal-models.html) - изменит стандартные модели животных (коров, куриц, овец и свиней),  новые модели содержат дополнительные элементы, которые сделают мобов немного реалистичнее;
9. [**Better Third Person**](https://www.curseforge.com/minecraft/mc-mods/better-third-person) - Mod adds independent rotation of the camera in a third person view;
10. [**Blur**](https://minecraft-inside.ru/mods/52900-blur.html) - Если вас отвлекает фон во время использования инвентаря или при крафте вещей, то вам пригодится этот мод, он добавит шейдер размывающий зданий фон всех интерфейсов в игре;
11. [**Spawn Animations**](https://minecraft-inside.ru/mods/163324-spawn-animations.html) - добавит некоторым мобам необычные анимации появления. Теперь вместо простого появления, враждебные мобы будут вылазить из-под земли или появляться с характерными частицами;
12. [**Slight Gui Modifications**](https://minecraft-inside.ru/mods/134999-slight-gui-modifications.html) - добавит в майнкрафт плавные анимации интерфейса: чата, инвентаря, достижений, скриншотов, контекстного меню. Все они по умолчанию отключены, чтобы включить их вам необходимо зайти в настройки майнкрафт и найти кнопку "'Slight' Gui Modifications";
13. [**Smooth Scrolling Everywhere**](https://minecraft-inside.ru/mods/101267-smooth-scrolling-everywhere.html) - Очень простой твик, с которым пролистывание списков в игре станет плавным и приятным, а при достижении грницы (верха/низа), контент списка будет отскакивать назад;
14. [**Roughly Enough Items**](https://www.curseforge.com/minecraft/mc-mods/roughly-enough-items) - он позволит в любой момент открыть меню и посмотреть крафт любого предмета, теперь не нужно будет рыскать по всяким сайтам и искать нужный крафт, а найти его прямо в игре;
15. [**Mod Menu**](https://minecraft-inside.ru/mods/96050-mod-menu.html) - По умолчанию загрузчик Fabric не отображается список модов, Mod Menu исправит данное упущение и добавит специальный интерфейс, в котором вы можете посмотреть все загруженные моды и их описание;
16. [**Merchant Markers**](https://minecraft-inside.ru/mods/152300-merchant-markers.html) - над жителями будут отображаться пользовательские маркеры. А чтобы их было ещё легче найти, мод полностью совместим с Xaero's Minimap;
17. [**Legendary Tooltips**](https://minecraft-inside.ru/mods/150777-legendary-tooltips.html) - поменяются всплывающие подсказки в инвентаре, теперь у них появятся красивые рамки которые  изменяются в зависимости от предмета, также в моде присутствует поддержка цветов из модификаций;
18. [**Visual Workbench**](https://minecraft-inside.ru/mods/148353-visual-workbench.html) - состоит из набора твиков улучшающих верстак. С его помощью, предметы размещенные в сетке крафта можно будет увидеть на самом блоке, а при закрытии интерфейса верстака, эти предметы не выпадут, а останутся на месте;
19. [**WI Zoom**](https://minecraft-inside.ru/mods/113724-wi-zoom.html) - добавит функцию регулируемого приближения (зума), вплоть до увеличения в 50 раз. По умолчанию необходимо нажать клавишу "V" и воспользоваться колесом мыши для регулирования;
20. [**Weapon Master**](https://ru-minecraft.ru/mody-minecraft/73208-ydms-weapon-master.html) - позволит отображать оружие и инструменты на самой модельке игроке в игре;
21. [**REESE'S SODIUM OPTIONS**](https://xenolith.ru/mody/fabric/325-reeses-sodium-options-119-1182-1171-1165.html) - данный мод заменяет экран настроек Sodium с целью улучшения пользовательского интерфейса;
22. [**Droplight**](https://minecraft-inside.ru/mods/161391-droplight.html) - редкие предметы будут подсвечиваться красивым лучом, направленным в небо. Звуки и цвета лучей настраиваются в файле конфигурации;
23. [**By Design**](https://minecraft-inside.ru/mods/162591-by-design.html) - перерабатывает некоторое оружие и снаряды, добавляя им трёхмерные модели и придавая майнкрафт больше объема. Так, лук, арбалет, стрелы и фейерверки будут иметь 3d модели, соответствующие ванильному стилю;
24. [**Chunks fade in**](https://minecraft-inside.ru/mods/162519-chunks-fade-in.html) - Этот простой мод добавляет красивую анимацию прорисовки чанков. Вместо обрубленного появления чанки будут медленно проявляться. Больше никаких чанков, появляющихся перед вашим лицом из ниоткуда;
25. [**RPG-Hud**](https://minecraft-inside.ru/mods/10294-rpg-hud.html) - Мод изменит основные показатели игрока под интерфейс в стиле RPG игр;
26. [**RPG-Hud**](https://minecraft-inside.ru/mods/10294-rpg-hud.html) - Мод изменит основные 
27. [**Illuminations**](https://minecraft-inside.ru/mods/70274-illuminations.html) - добавит в игру различные светящиеся частицы, с которыми вы сможете взаимодействовать. На данной момент в игре имеются светлячки, обитающие в влажные и лесных биомах, а также их аналоги фиолетового цвета, появляющиеся в Краю и магических биомах;
28. [**LambdaBetterGrass**](https://www.curseforge.com/minecraft/mc-mods/lambdabettergrass) - which adds better grass and snow to the game;
29. [**Falling Leaves**](https://minecraft-inside.ru/mods/140700-falling-leaves.html) - добавит красивую анимацию падающих листьев для деревьев, что сделает майнкрафт немного реалистичнее и живее;
30. [**Make Bubbles Pop**](https://minecraft-inside.ru/mods/156147-make-bubbles-pop.html) - добавляющая каплю реализма, меняя частицы пузырей в игре. Теперь при всплывании из воды они будут лопаться, прямо как настоящие пузырики;
31. [**Interactic**](https://ru-minecraft.ru/mody-minecraft/69715-interactic-novaya-sistema-vzaimodeystviya-s-veschami.html) - изменит взаимодействие с брошенными предметами в игре. Теперь они имеют полноценную физику - при броске крутятся, вертятся, меняют скорость и падают до тех пор, пока не найдут точку опоры;
32. [**Effective**](https://minecraft-inside.ru/mods/153029-effective.html) -  добавляющий в игру различные эффекты окружающей среды. После его установке в мире появятся как визуальные, так и звуковые эффекты, улучшающие погружение в игру и делающие её реалистичнее;
33. [**Tiny Item Animations**](https://beta.curseforge.com/minecraft/mc-mods/tiny-item-animations) - This mod adds little animations when you pick up or insert items with your mouse;
34. [**LambDynamicLights**](https://minecraft-inside.ru/mods/136972-lambdynamiclights.html) - появится динамическое освещение, с которым предметы будут излучать свет в руках и на земле;
35. [**Shulker Tooltip**](https://minecraft-inside.ru/mods/70233-shulker-tooltip.html) - Благодаря этому твику можно будет быстро посмотреть содержимое ящика шалкера, когда он находится в инвентаре. Для этого достаточно навести на него курсор мыши, зажав Ctrl;
36. [**Enchantment Descriptions**](https://minecraft-inside.ru/mods/40034-enchantment-descriptions.html) - Небольшой, но крайне полезный мод, который добавит описание зачарования к подсказкам зачарованных книг. С помощью этого вы сможете сэкономить время и сделать процесс зачарования более легким;
37. [**Dynamic Surroundings**](https://www.curseforge.com/minecraft/mc-mods/dynamic-surroundings) - Dynamic Surroundings alters the player’s visual and audible experience in Minecraft, and does not alter game mechanics. The player has a high degree of control over their experience, and modpack authors can customize biome and block effects based on their need;
38. [**Trinkets**](https://minecraft-inside.ru/mods/152996-trinkets.html) - Trinkets добавляет в интерфейс игрока дополнительные слоты, которые используются для украшений или функциональных предметов. Мод не содержит предметы для слотов и является по сути библиотекой, которую используют другие моды;
39. [**SnowyLeavesPlus**](https://www.curseforge.com/minecraft/mc-mods/snowyleavesplus) - In Bedrock Edition, leaves slowly turn white when it is snowing. SnowyLeavesPlus brings this feature to Java Edition! When it is snowing, leaves will slowly turn white, and when it is not, they will turn back to normal;
40. [**Xаero’s Minimаp**](https://minecraft-inside.ru/mods/310-x%D0%B0eros-minim%D0%B0p-mod.html) - Мод добавит в игру приятную мини-карту, на которой желтыми точками будут показаны мобы, белыми - игроки, а красными предметы;

## [Моды на обновление боевой системы](#оглавление)
1. [**Falling Attack**](https://minecraft-inside.ru/mods/149473-falling-attack.html) - Модификация добавит в игру новое зачарование, которое позволит применять эффектную воздушную атаку. Нажав ЛКМ в падении с мечом в руках, вы сможете ударить врага сверху и откинуть на далекое расстояние;
2. [**Better Combat - by Daedelus**](https://minecraft-inside.ru/mods/159242-better-combat-by-daedelus.html) - мод обновит скучную боевую систему в игре, заменив её на более увлекательную версию из Minecraft Dungeons;
3. [**LevelZ**](https://minecraft-inside.ru/mods/149643-levelz.html) -  особый механизм прокачки, с которым вам нужно будет улучшать свои навыки при помощи опыта - это позволит вам открывать предметы, блоки и снаряжение. Для открытия меню используйте клавишу K;

## [Моды на мобов](#оглавление)
1. [**Dinocraft: Extinction**](https://minecraft-inside.ru/mods/151249-dinocraft-extinction.html) - добавит в майнкрафт динозавров и сделает мир игры ещё более диким и опасным местом;
2. [**Better Animals Plus**](https://minecraft-inside.ru/mods/79490-better-animals-plus.html) - разнообразит игровой мир новыми существами (реальными и выдуманными). Он добавит как пассивных, так и враждебных мобов, появится даже мини-босс;
3. [**MobZ**](https://minecraft-inside.ru/mods/114905-mobz.html) - ряд мобов в ванильном стиле, а также некоторые предметы, которые помогут вам в путешествиях (ботинки с ускорением, новая броня и оружие);
4. [**Rotten Creatures**](https://minecraft-inside.ru/mods/129351-rotten-creatures.html) - Теперь в вашем мире будут появляться восемь новых видов зомби, которые обладают качественными моделями и отличаются от обычных собратьев интересными умениями и характерными особенностями;
5. [**Naturalist**](https://minecraft-inside.ru/mods/157752-naturalist.html) - Масштабный мод на животных, в котором каждый новый моб будет взаимодействовать с другими;
6. [**Eldritch Mobs**](https://minecraft-inside.ru/mods/136597-eldritch-mobs.html) - моб может случайным образом получить определенный "класс". С ними мобы будут иметь повышенное здоровье, уникальные способности, а также после смерти давать большее количество опыта и уникальные предметы;
7. [**Creatures of The Snow**](https://minecraft-inside.ru/mods/154502-creatures-of-the-snow.html) - Creatures of The Snow добавит в игру таких милых существ, как пингвинов, белух, нарвалов и милых снежных тюленей! Кроме того, вы сможете также создавать интересные постройки в зимнем стиле с новыми блоками, такими как снежные кирпичи или замороженный пух;
8. [**Terrarian Slimes**](https://minecraft-inside.ru/mods/145473-terrarian-slimes.html) - C TS в игре появится целая охапка новых видов слизней, вдохновленных Террарией. Из них вы сможете получать различные материалы и крафтить полезные вещи (например, прыгучую взрывчатку);
9. [**Creeper Overhaul**](https://minecraft-inside.ru/mods/153426-creeper-overhaul.html) - Creeper Overhaul вводит в игровой мир разнообразные варианты криперов с красивыми текстурами и моделями. Теперь кроме стандартного, в игре появятся криперы из разных биомов, пещерные и даже дружелюбные криперы, которые не будут взрывать вас, если конечно вы не нападете сами;
10. [**Critters and Companions**](https://minecraft-inside.ru/mods/162496-critters-and-companions.html) - Critters and Companions наполнит игровой мир новыми милыми мобами! Хотите приручить хорька? Поискать моллюсков вместе с выдрой? А может вздремнуть вместе с соней красной пандой? С этим модом вы сможете с лёгкостью это сделать;

## [Моды на новые предметы](#оглавление)
1. [**Automobility**](https://minecraft-inside.ru/mods/159859-automobility.html) - мод, добавляющий настраиваемые транспортные средства;
2. [**Adorn**](https://minecraft-inside.ru/mods/94948-adorn.html) - Декоративный мод, с которым вы сможете обставить свой дом мебелью и добавить капельку уюта в квадратный мир игры. Мод добавит в игру: столы, стулья, диваны, кухонные шкафы, ящики и дымоходы;
3. [**XP Obelisk**](https://minecraft20.ru/mody/8816-mod-xp-obelisk-1171-hranenie-opyta-v-kletke.html) -  добавит в игру метод хранения очков опыта внутри духовной клетки;
4. [**Vanilla Hammers**](https://minecraft-inside.ru/mods/131707-vanilla-hammers.html) - добавит пятнадцать вариантов молота, способного разрушать площадь 3 на 3 блока. Новый инструмент будет работать как обычная кирка, так что с его помощью можно будет добывать блоки камней и руды;
5. [**Nature's Compass**](https://minecraft-inside.ru/mods/42394-natures-compass.html) - добавит в игру природный компас, который поможет вам найти определенный биом и покажет вам информацию о нем;
6. [**Tool Leveling+**](https://minecraft-inside.ru/mods/140066-tool-leveling.html) - Воспользуйтесь новым блоком, который откроет возможность повышать уровень зачарований выше ванильного лимита. Для этого выберите нужные чары и используйте материал (по умолчанию незеритовые слитки);
7. [**Macaw's Roofs**](https://minecraft-inside.ru/mods/115344-macaws-roofs.html) - добавит в майнкрафт несколько разновидностей блоков для крыши со справедливыми рецептами;
8. [**Modern Elevators and Escalators**](https://minecraft-inside.ru/mods/161711-modern-elevators-and-escalators.html) - С этим модом в вашем распоряжении появятся блоки для строительства лифтов и эскалаторов. Абсолютно всё конструкционные блоки модульны, а поэтому вы сможете строить лифты и эскалаторы любых размеров, устанавливая их даже в самых невероятных постройках;
9. [**Laser Bridges & Doors**](https://minecraft-inside.ru/mods/163031-laser-bridges-doors.html) - вводит лазерный блок, который при включении создаёт лазерные двери и платформы. Данный блок при активации красным камнем будет создавать поток лазерных блоков, длина которого будет зависеть от силы сигнала редстоуна;
10. [**Animal Feeding Trough**](https://minecraft-inside.ru/mods/143685-animal-feeding-trough.html) - добавит кормушку, с которой можно организовать автоматическое разведение животных: наполните кормушку подходящим видом корма, а животные сами будут находить лакомство;
11. [**Test Dummy**](https://minecraft-inside.ru/mods/10922-test-dummy-mod.html) - тестовый манекен, на котором можно оттачивать свои навыки обращения с оружием;
12. [**Disc holders & Dj**](https://minecraft-inside.ru/mods/154198-disc-holders-dj.html) - Кроме семи новых музыкальных пластинок, вас ждет подставка под пластинки, доступная в шестнадцати цветах и вмещающая в себя все семь пластинок. А чтобы вам не пришлось долго искать пластинки, в деревнях будет появляться новый житель, продающий их;
13. [**Dramatic Doors**](https://minecraft-inside.ru/mods/134175-dramatic-doors.html) - вариант дверей, высотой в три блока, через эти высокие двери можно проходить сидя на лошади или же пустить в гости эндермена;
14. [**Enchanting Infuser**](https://minecraft-inside.ru/mods/152574-enchanting-infuser.html) - Enchanting Infuser вводит удобный стол зачарования. Инфьюзер позволяет вам выбирать, какое конкретное зачарование вы хотите получить и не требует лазурит;
15. [**Immersive Aircraft**](https://minecraft-inside.ru/mods/162491-immersive-aircraft.html) - в майнкрафт появится воздушный транспорт! Вы сможете создать себе самолёт, дирижабль или гиродин, каждый по своему полезный и уникальный. С их помощью вы сможете с лёгкостью путешествовать, исследовать мир или транспортировать ресурсы;
16. [**Macaw's Bridges**](https://minecraft-inside.ru/mods/115275-macaws-bridges.html) - С Macaw's Bridges вы получите в свое распоряжение семь разновидностей навесных мостов, позволяющих красиво соединить между собой два берега или края обрыва;
17. [**Decorative Blocks**](https://minecraft-inside.ru/mods/123806-decorative-blocks.html) - добавляющий ряд декоративных блоков: жаровня, деревянные опоры и сиденья, канделябр, каменный столб и блок цепи;
18. [**Carpet Trapdoors**](https://minecraft-inside.ru/mods/162660-carpet-trapdoors.html) - Теперь можно будет маскировать люки под ковры. Просто совместите нужные вам люк и ковёр в верстаке и вы получите замаскированный люк, который будет вести себя также, как и обычный люк, но иметь другой внешний вид;
19. [**Beautify**](https://minecraft-inside.ru/mods/158117-beautify.html) - добавит множество способов оживления ваших построек с помощью декоративных блоков. Большинство из них будут не только красивы, но и функциональны. Так, вы сможете использовать стопки книг для увеличения уровня зачарования, по верёвкам возможно будет карабкаться, а растения в больших горшках можно будет выращивать костной мукой;
20. [**Nyf's Quivers**](https://minecraft-inside.ru/mods/153001-nyfs-quivers.html) - возвращает в игру колчан и добавляет его новые разновидности. Всего появится пять новых видов, вмещающих в себя от девяти до сорока пяти стаков стрел. Колчан можно переименовать, щёлкнув по нему правой кнопкой мыши с зажатой клавишей шифт;
21. [**Xtra Arrows**](https://minecraft-inside.ru/mods/153781-xtra-arrows.html) - Вы прирожденный стрелок и вместо меча, предпочитаете сражаться луком и стрелами? Именно для вас Xtra Arrows пополнит разнообразие стрел новыми видами! С новыми стрелами вы сможете взрывать, призывать молнии, освещать путь факелами и улучшать обычные стрелы до нового уровня;

## [Глобальные моды](#оглавление)
1. [**The Twilight Forest**](https://minecraft-inside.ru/mods/9549-the-twilight-forest-mod.html) - Глобальная модификация добавляющая новое измерение "Сумеречный лес" - темный, заколдованный мир, почти весь покрытый лесом, в котором витает дух приключений и опасности. Здесь вам встретятся множество новых структур, мобов и боссов;

## [Моды на структуры](#оглавление)
1. [**It Takes a Pillage**](https://minecraft-inside.ru/mods/160762-it-takes-a-pillage.html) - Разбойники расширяют свою цивилизацию! Теперь у них в два раза больше лагерей и крепостей! Кроме новых построек, кишащих разбойниками вдоль и поперёк, вам предстоит также сразиться с новыми врагами, чтобы пробраться вглубь их строений и найти там полезный лут;

## [Моды на генерацию](#оглавление)
1. [**CoralReef**](https://minecraft-inside.ru/mods/39381-coralreef.html) - Перед нами ремейк уже существующего мода,  который позволит вам насладиться красивым дном, покрытым разноцветными кораллами. В данном случае код мода полностью переписан, а текстуры взяты с оригинальной версии;

## [Прочие моды](#оглавление)
1. [**Bed Benefits**](https://www.9minecraft.net/bed-benefits-mod/) - introduces a new feature, and the Bed has more benefits;
2. [**Quicksort**](https://minecraft-inside.ru/mods/158982-quicksort.html) - поместите сундук на изумрудный или алмазный блок, положите в него нужные предметы и они будут быстро рассортированы между ближайшими хранилищами, которые уже имеют внутри схожие предметы;
3. [**TrashSlot**](https://minecraft-inside.ru/mods/20388-trashslot.html) - добавит в интерфейс вашего инвентаря новую ячейку - корзину. Она позволит вам уничтожить ненужные предметы и блоки;
4. [**ExtraSounds**](https://minecraft-inside.ru/mods/146548-extrasounds.html) - добавит в игру новые звуки: прокрутки панели быстрого доступа, творческого инвентаря, взятия или размещения предметов в инвентаре;
5. [**Double Doors**](https://minecraft-inside.ru/mods/112740-double-doors.html) - двойные двери будут открываться одновременно при открытии одной из них;
6. [**Friendly Fire**](https://minecraft-inside.ru/mods/44641-friendly-fire.html) - Полезная модификация, которая будет оберегать питомцев от урона со стороны своих хозяев. Помимо этого в файле конфигурации можно настроить защиту мобов-детенышей;
7. [**Blossom**](https://minecraft-inside.ru/mods/154589-blossom.html) - заставит дубовые листья цвести и приносить плоды! Теперь чтобы получить яблоко не обязательно срубать листву, достаточно просто срезать яблоко когда оно созреет;
8. [**BoatOverhaul**](https://www.curseforge.com/minecraft/mc-mods/boatoverhaul-fabric) - The mod ports WOWS's boat sailing mechanism to Minecraft;