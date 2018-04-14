# Roguelike Development Resources

*A curated list of roguelike development resources*

* [Communities](#communities)
* [Resources](#resources)
	* [Procedural Map Generation](#procedural-map-generation)
	* [Field of View](#field-of-view)
	* [AI](#ai)
	* [Time Management](#time-management)
* [Tutorials](#tutorials)
* [Videos](#videos)
* [Libraries](#libraries)
* [Open Source Roguelikes](#open-source-roguelikes)
* [Miscellaneous](#miscellaneous)

## Communities

* [RoguelikeDev Reddit](https://www.reddit.com/r/roguelikedev) - :+1:
* [Roguelikes Discord](https://discord.gg/9pmFGKx)
* [Temple of the Roguelike](http://forums.roguetemple.com/)

## Resources

* [RogueBasin Articles](http://www.roguebasin.com/index.php?title=Articles) - :+1:
* [Procedural Generation Resources](https://www.firespark.de/?id=article&article=ProceduralGenerationResources) - :+1:
* [Random Dungeon Generators](http://wiki.secretgeek.net/random-dungeon-generators)
* [Procedural Map Generation](http://www.gridsagegames.com/blog/2014/06/procedural-map-generation/)
* [FAQ Friday](https://www.reddit.com/r/roguelikedev/wiki/faq_friday)
* [Roguelike Tilesets](https://www.reddit.com/r/roguelikedev/comments/436sop/roguelike_tilesets/)

### Procedural Map Generation

* **Dungeon**
	* BSP
		* [Basic BSP Dungeon Generation](http://www.roguebasin.com/index.php?title=Basic_BSP_Dungeon_generation)
		* [Dungeon Generation using BSP Trees](https://eskerda.com/bsp-dungeon-generation/)
		* [How to Use BSP Trees to Generate Game Maps](https://gamedevelopment.tutsplus.com/tutorials/how-to-use-bsp-trees-to-generate-game-maps--gamedev-12268)
		* [Procedural Dungeon Generation](http://www.varav.in/posts/2016/05/25/dungeon.html)
		* [Procedural Dungeon Generator](https://www.reddit.com/r/gamedev/comments/z6gl5/procedural_dungeon_generator/)
		* [Random Map Generators](http://www.acornarcade.com/articles/Random_map_generators/index1114.html) - [#2](http://www.acornarcade.com/articles/Building_the_Dream_1_-_Container_data_structures/index1162.html) [#3](http://www.acornarcade.com/articles/Building_the_Dream_2_-_The_RISC_OS_Sound_System/index1209.html) [#4](http://www.acornarcade.com/articles/Building_the_Dream_3_-_Random_map_generators_redux/index1211.html) [#5](http://www.acornarcade.com/articles/Building_the_Dream_4_-_Random_city_basics/index1214.html)
		* [Infra Arcana Map Generation Demo](http://forums.roguetemple.com/index.php?topic=3778.0) - Videos [#2](http://www.youtube.com/watch?v=b6Kz2qMyKww) [#3](http://www.youtube.com/watch?v=_oRKLYqB4GI)

	* Maze
		* [Jamis Buck's Maze Algorithms](http://www.jamisbuck.org/mazes/)
		* [Jamis Buck's Random Dungeon Generator](http://dungeonsndigressions.blogspot.kr/2011/02/bucks-random-dungeon-generator.html) - [#2](https://github.com/jamis/dnd-dungeon)
		* [Think Labyrinth: Maze Algorithms](http://www.astrolog.org/labyrnth/algrithm.htm)
		* [Random Dungeon Generator Launcher by Wizards of the Coast](https://www.wizards.com/dnd/mapper/launcher.htm)
		* [Rooms and Mazes: A Procedural Dungeon Generator](http://journal.stuffwithstuff.com/2014/12/21/rooms-and-mazes/)

	* Cellular Automata
		* [Cellular Automata Method for Generating Random Cave-Like Levels](http://www.jimrandomh.org/misc/caves.html)
		* [Using A Cellular Automata Style Rule to Create A Cave System](http://pixelenvy.ca/wa/ca_cave.html)
		* [C# Algorithm to Build Interesting Cave Systems](http://www.evilscience.co.uk/a-c-algorithm-to-build-roguelike-cave-systems-part-1/)
		* [Procedural Cave Generator](https://github.com/AK-Saigyouji/Procedural-Cave-Generator) - Unity/C#, 3D
		* [How Does Level Generation Work In Brogue?](https://www.rockpapershotgun.com/2015/07/28/how-do-roguelikes-generate-levels/) - :+1:
		* [Python Dungeon Generator](https://whatjaysaid.wordpress.com/2016/01/15/1228/)
		* [Improving Procedural 2D Map Generation](https://www.sbgames.org/sbgames2017/papers/COMPUTACAO/FULL_PAPERS/175350_2_versao_preliminar.pdf) - Hilbert curves
		* [Contour Bombing Cave Generation Algorithm](http://www.darkgnosis.com/2018/03/03/contour-bombing-cave-generation-algorithm) - Alternative for CA

	* Graph
		* [Over-Engineering Dungeon Generation](http://angband.oook.cz/forum/showthread.php?t=927)
		* [Procedural Dungeon Generation Algorithm Explained](https://www.reddit.com/r/gamedev/comments/1dlwc4/procedural_dungeon_generation_algorithm_explained/) - :+1:
			* [TinyKeep](https://forums.tigsource.com/index.php?topic=36176.0) - Devlog
			* [Demo](http://tinykeep.com/dungen/) - Flash
		* [Procedural Dungeon Generation Algorithm](https://github.com/adonaac/blog/issues/7)
		* [Delaunay Triangulation Dungeon Generator](https://github.com/glouw/dunge) - C
		* [Dungeon Generation Algorithm](https://www.reddit.com/r/roguelikedev/comments/1sd730/my_dungeon_generation_algorithm/) - Relative Neighborhood Graph
		* [2D Map Generated with a Node-Based Approach](https://www.reddit.com/r/proceduralgeneration/comments/65xrvc/2d_map_generated_with_a_nodebased_approach/)

	* Template
		* [Spelunky Generator Lessons](http://tinysubversions.com/spelunkyGen/)
		* [Herringbone Wang Tiles](http://nothings.org/gamedev/herringbone/) - :+1:
		* [Rogue-like Level Generator](https://www.reddit.com/r/proceduralgeneration/comments/3pa8a1/my_take_at_a_roguelike_level_generator_ft/)
		* [Procedural Room Generation Explained](http://www.magicaltimebean.com/2014/11/procedural-room-generation-explained/)
		* [How I Learned to Stop Worrying and Love Prefabs](http://www.goldenkronehotel.com/wordpress/2017/02/18/how-i-learned-to-stop-worrying-and-love-prefabs/)
		* [A Template-Based Approach to Procedural Map Generation](https://docs.google.com/document/d/e/2PACX-1vR2cc7r4s_K2T9AYWn06HiccQBv4jlfeFD874yWTa6BZOBDKLVMH7pRW0wZIOZ8cqHombTISFVMlkbV/pub)

	* Miscellaneous
		* [The Original Rogue Algorithm](https://web.archive.org/web/20131025132021/http://kuoi.org/~kamikaze/GameDesign/art07_rogue_dungeon.php)
		* [Dungeon Maker](http://dungeonmaker.sourceforge.net/DM2_Manual/index.html)
        * [Level Generator](https://github.com/mreinstein/level-generator)
		* [Recursive Tile Map Growth](https://github.com/r3eckon/Recursive-Tile-Map-Growth) - Java
		* [Make a Mystery Dungeon](http://www5f.biglobe.ne.jp/~kenmo/program/dangeon2/dangeon2.html) - :jp:
		* [Three Techniques to Procedurally Generate Dungeons](https://www.reddit.com/r/gamedev/comments/2lyqki/three_techniques_to_procedurally_generate/)
		* [A Bunch of Dungeon Algorithms](https://www.reddit.com/r/roguelikedev/comments/6df0aw/my_implementation_of_a_bunch_of_dungeon_algorithms/)
		* [Level Generator Toolkit](https://chilly-durango.itch.io/level-generator-toolkit)
		* [DCSS Layout Types](https://crawl.develz.org/wiki/doku.php?id=dcss:brainstorm:dungeon:layout_types)
		* [Sample Levels from placerooms.pl](http://jonadab.jumpingcrab.com/pastebin/508.html) - [#2](https://github.com/tsadok/level-generator-perlscripts/blob/master/placerooms.pl)
		* [The Zelda Dungeon Generator](http://beckylavender.co.uk/portfolio/the-zelda-dungeon-generator/)
		* [Constructive Generation Methods for Dungeons and Levels](https://graphics.tudelft.nl/Publications-new/2016/SLTLB16/chapter03.Online.pdf) - PDF
        * [Unangband Dungeon Generation](http://roguelikedeveloper.blogspot.ru/2007/11/unangband-dungeon-generation-part-one.html) - Parts 2-9 links in the article.
        * [Random Dungeons: Turbulence Algorithm](http://earok.net/sections/articles/game-dev/theory/random-dungeons)

* **Town**
	* [A Constrained Growth Method for Procedural Floor Plan Generation](http://graphics.tudelft.nl/~rval/papers/lopes.GAMEON10.pdf) - PDF

* **Overworld**
	* [Generating Fantasy Maps](http://mewo2.com/notes/terrain/)
	* [Overworld Overview](http://bytten-studio.com/devlog/2014/09/08/overworld-overview-part-1/)
	* [World Generation Breakdown](http://www.nolithius.com/articles/world-generation/world-generation-breakdown)
	* [Creating a Random 2D Game World Map](https://gillesleblanc.wordpress.com/2012/10/16/creating-a-random-2d-game-world-map/)
	* [Building an Infinite Procedurally-Generated World](https://spin.atomicobject.com/2015/05/03/infinite-procedurally-generated-world/)
	* [Map Generator Based on Voronoi Diagram and Perlin Noise](https://github.com/averrin/mapgen) - C++
	* [World Generator Inspired by Dwarf Fortress](https://github.com/Dozed12/df-style-worldgen) - Python
	* [Procedural Worlds from Simple Tiles](http://ijdykeman.github.io/ml/2017/10/12/wang-tile-procedural-generation.html)
	
* **Landscape**
	* [Landscape Generation using Midpoint Displacement](https://bitesofcode.wordpress.com/2016/12/23/landscape-generation-using-midpoint-displacement/)
	* [Simple 2D Terrain with Midpoint Displacement](http://www.somethinghitme.com/2013/11/11/simple-2d-terrain-with-midpoint-displacement/)
	* [Simple 2D Landscape Generator Inspired by No Man's Sky](http://theadarshsinha.com/pcg.html) - [#2](https://www.reddit.com/r/proceduralgeneration/comments/4v3vce/simple_2d_scenemountainlandscape_generator/)

* **Space**
	* [Procedural Generation for Dummies: Galaxy Generation](http://martindevans.me/game-development/2016/01/14/Procedural-Generation-For-Dummies-Galaxies/)
	* [Procedural Stars Map](http://simonrodriguez.fr/starmap/)
	* [Procedural Generation of 2D Space Scenes in WebGL](https://wwwtyro.net/2016/10/22/2D-space-scene-procgen.html)
	* [A 2D Procedural Galaxy with C++](http://itinerantgames.tumblr.com/post/78592276402/a-2d-procedural-galaxy-with-c)
	* [The Frontier Galaxy](http://www.jongware.com/galaxy1.html)
	* Poisson Disk Sampling
		* [Fast Poisson Disk Sampling in Arbitrary Dimensions](http://www.cs.ubc.ca/~rbridson/docs/bridson-siggraph07-poissondisk.pdf) - PDF
		* [Poisson-Disc Sampling](https://www.jasondavies.com/poisson-disc/) - Demo
		* [Poisson Disk Sampling](http://devmag.org.za/2009/05/03/poisson-disk-sampling/) - Tutorial
		* [Poisson Disk Points Generator](https://github.com/corporateshark/poisson-disk-generator) - C++

* **Spaceship**
	* [How I Generate a Layout for Space Ships; Quick Guide](https://www.reddit.com/r/gamedev/comments/1z676s/how_i_generate_a_layout_for_space_ships_quick/)
	* [Randomly Generating Simple Spaceships In Heat Signature](https://www.pentadact.com/2014-02-07-randomly-generating-simple-spaceships-in-heat-signature/) - [#2](https://www.pentadact.com/2014-07-19-improving-heat-signatures-randomly-generated-ships-inside-and-out/)
	* [Procedurally Generate Spaceship Sprites](https://github.com/stewsters/shipwright)
	* [How My Toolkit Builds Spaceships](https://www.reddit.com/r/proceduralgeneration/comments/6daqjb/really_pleased_with_how_my_toolkit_builds/)

### Field of View

* [Roguelike Vision Algorithms](http://www.adammil.net/blog/v125_Roguelike_Vision_Algorithms.html) - :+1:
* [Comparative Study of Field of View Algorithms for 2D Grid Based Worlds](http://www.roguebasin.com/index.php?title=Comparative_study_of_field_of_view_algorithms_for_2D_grid_based_worlds)
* [What the Hero Sees: Field-of-View for Roguelikes](http://journal.stuffwithstuff.com/2015/09/07/what-the-hero-sees/)
* [Partial Occlusion Field-of-View](http://blog.pixelpracht.net/?p=340)

### AI

* [The Incredible Power of Dijkstra Maps](http://www.roguebasin.com/index.php?title=The_Incredible_Power_of_Dijkstra_Maps) - :+1:
	* Progressive Dijkstra Scan - [#1](http://paleoludic.com/writing/whitespace-reasoning/) [#2](http://paleoludic.com/writing/a-pathfinding-primer/) [#3](http://paleoludic.com/writing/engineering-pds/)
* [Dijkstra Maps Visualized](http://www.roguebasin.com/index.php?title=Dijkstra_Maps_Visualized)
* [Distance Map](http://projects.jake.cx/distance-map/)
* [Applications of Dijkstra Maps in Roguelikes](https://www.youtube.com/watch?v=2ExLEY32RgM) - Video
* [TinyKeep AI Demo](http://tinykeep.com/ai/) - Flash Demo, Videos

### Time Management

* [A Turn-Based Game Loop](http://journal.stuffwithstuff.com/2014/07/15/a-turn-based-game-loop/)

## Tutorials

* [Complete Roguelike Tutorial using Python and libtcod](http://www.roguebasin.com/index.php?title=Complete_Roguelike_Tutorial,_using_python%2Blibtcod) - :+1:
* [Complete Roguelike Tutorial using C++ and libtcod](http://www.roguebasin.com/index.php?title=Complete_roguelike_tutorial_using_C%2B%2B_and_libtcod_-_part_1:_setting_up)
* [Creating a Roguelike Game in C# and RogueSharp](https://roguesharp.wordpress.com/)
* [Roguelike Tutorial in Java and AsciiPanel](http://trystans.blogspot.kr/2016/01/roguelike-tutorial-00-table-of-contents.html)
* [Building a Roguelike in JavaScript and rot.js](http://www.codingcookies.com/2013/04/01/building-a-roguelike-in-javascript-part-1/)
* [Let's Build a Roguelike in FreeBasic](http://users.freebasic-portal.de/rdc/tutorials.html)
* [Unity 2D Roguelike Tutorial](https://unity3d.com/kr/learn/tutorials/s/2d-roguelike-tutorial)
* [Python Roguelike Tutorial](https://www.youtube.com/playlist?list=PLKUel_nHsTQ1yX7tQxR_SQRdcOFyXfNAb) - Videos

## Videos

* [Roguelike Celebration 2016](https://www.youtube.com/channel/UCsCqXksJuAkfZRtnW5Pq1mw/videos)
* [Roguelike Celebration 2017](https://www.youtube.com/channel/UCKv_QzXft4mD6TXmQBZtzIA)
* [IRDC 2016](https://www.youtube.com/channel/UCIxJ3OhqqQkUP6xaD23rZcQ/videos)
* [IRDC 2017](https://www.youtube.com/playlist?list=PLcZ-fMpNVsjUQ_eKlGrOH_OOgjxKzT84w)

## Libraries

* [libtcod](http://roguecentral.org/doryen/libtcod/) - C/C++, Python
* [BearLibTerminal](http://foo.wyrd.name/en:bearlibterminal) - C/C++, C#, Lua, Pascal, Python, Ruby
* [rltk](https://github.com/thebracket/rltk) - C++
* [SadConsole](https://github.com/Thraka/SadConsole) - C#
* [rot.js](https://github.com/ondras/rot.js) - JavaScript

## Open Source Roguelikes

* [Angband](https://github.com/angband/angband) - C
* [Nethack](https://github.com/NetHack/NetHack) - C
* [Retro Rogue Collection](https://github.com/mikeyk730/Rogue-Collection) - C :+1:
* [Martin's Dungeon Bash](http://www.chiark.greenend.org.uk/~mpread/dungeonbash/) - C/C++
* [Cataclysm DDA](https://github.com/CleverRaven/Cataclysm-DDA) - C++
* [Dungeon Crawl Stone Soup](https://github.com/crawl/crawl) - C++
* [Infra Arcana](https://github.com/martin-tornqvist/ia) - C++
* [IVAN](https://github.com/Attnam/ivan) - C++
* [KeeperRL](https://github.com/miki151/keeperrl) - C++
* [Amaranth](https://github.com/munificent/amaranth) - C#
* [Pixel Dungeon](https://github.com/watabou/pixel-dungeon) - Java
* [Hauberk](https://github.com/munificent/hauberk) - Dart :+1:
* [DoomRL](https://github.com/ChaosForge/doomrl) - FreePascal

## Miscellaneous

* [The Roguelike Archive](https://britzl.github.io/roguearchive/)
* [Donnie Russell II's Home Page](https://sites.google.com/site/donnierussellii/home) - Rogue, Hack, Larn, MAG, Moria, etc.
* [Decoded: Rogue](http://www.maizure.org/projects/decoded-rogue/index.html)
* [Roguelike Source Code Review](https://github.com/rsaarelm/roguereview)
* [Fantasy Name Generator](https://github.com/alxgiraud/fantasygen) - JavaScript
* [Dyson's Map Archive](https://rpgcharacters.wordpress.com/maps/)
* [Cool Retro Term](https://github.com/Swordfish90/cool-retro-term)
