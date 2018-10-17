# 1pp
One Pixel Productions improves the BGII inventory icons.</br></br>

**Author:** Erephine

**Version:** 4.2.0

**Languages:**  English, French

**Platform:** Windows


## Overview

Without a doubt the most comprehensive mod when it comes to post-release QA and visuals, 1pp has been a growing work of love for close to 8 years with the aim of providing a refined, polished experience with attention to detail that many felt was lacking in some aspects of Baldur's Gate II compared to its predecessor. </br></br>
1ppv4 represents the culmination of this effort, bringing together the various previously disjointed graphical and mechanical tweaks and components that have accumulated over the years and many more besides; updated, streamlined and in the form of one coherent installer.</br>

Visit the <a href="http://www.spellholdstudios.net/ie/1pp">website</a> or <a href="http://www.shsforums.net/index.php?showforum=159">forum</a> for all the latest updates.


## Installation


## Components

&#8258; <strong>Game engine and core related content</strong></br>
><a href="#101">[101] 1ppv4: Core paperdolls</a></br>
><a href="#102">[102,103] 1ppv4: Extended palette entries</a></br>
><a href="#104">[104] 1ppv4: GUI additions for BGII</a></br>
><a href="#105">[105] 1ppv4: Avatar fixes</a></br>
><a href="#106">[106-109] 1ppv4: Female Dwarves</a></br>
><a href="#110">[110-112] 1ppv4: Thieves Galore</a></br>
><a href="#113">[113] 1ppv4: Smart Avatar & Armour Switching</a></br>
><a href="#114">[114] 1ppv4: Softer Spell Effects</a></br></br>

&#8258; <strong>Item patches, additions and implementation</strong></br>

><a href="#200">[200] 1ppv4: Core content patches</a>
><a href="#201">[201] 1ppv4: Consistent spell and scroll icons</a></br>
><a href="#202">[202] 1ppv4: Spell tweaks</a></br>
><a href="#203">[203] 1ppv4: Restored flame sword animations</a></br>
><a href="#204">[204] 1ppv4: Colourable Quarterstaves</a></br>
><a href="#205">[205] 1ppv4: Legacy Shields v2</a></br>
><a href="#206">[206] 1ppv4: Additional Shield Animations (core)</a></br>
><a href="#207">[207] 1ppv4: Wizards' Staves (core)</a></br>
><a href="#208">[208] 1ppv4: Additional Helmet Animations (core)</a></br>
><a href="#209">[209] 1ppv4: Attachable wings (core)</a></br>
><a href="#210">[210] 1ppv4: Increased paperdoll object variety (core)</a></br></br>

><a href="#400">[400] 1ppv4: Core updates and item patches</a> <em>[main 1ppv4 update component]</em></br>
><a href="#401">[401] 1ppv4: Improved projectile effects</a></br></br>

&#8258; <strong>Extras and non-character related fixes</strong></br>

><a href="#300">[300] 1ppv4: Fixed animations for solars and elementals</a></br>
><a href="#301">[301] 1ppv4: Miscellaneous content fixes</a></br></br>


### <a name="101" id="101"></a>[101] 1ppv4: Core paperdolls

Supports: <span style='color:red'>SoA</span>, <span style='color:#700'>ToB</span>, <span style="color:#080;">Tutu</span>, <span style="color:#088;">HoW</span>, <span style="color:#666;">IWDII (placeholder)</span></br>

<img src="1pp/documentation/files/101.jpg"></br>

The component that essentially started it all, this is a port of Baldur's Gate I style paperdolls for the Baldur's Gate II engine (used in SoA/ToB and HoW). Included are reworked 1ppv4 paperdolls for all race/class combinations matching vanilla animations as well as equipped object overlays. New in this version is detection and native support for Infinity Animations, including support for installs of HoW using BG1 animations via the 1pp IWD animation fixpack.

###### Note that this component does not update icon graphics or item colours, so it is not recommended to be installed by itself. It is, however, required for most of the components that follow.</br></br>


### <a name="102" id="102"></a>[102,103] 1ppv4: Extended palette entries

<strong>Non-optional component</strong></br>
Supports: <span style="color:#060">SoA</span>, <span style="color:#700">ToB</span>, <span style="color:#080">Tutu</span>, <span style="color:#088">HoW</span>, <span style="color:#666">IWDII</span></br>

<img src="1pp/documentation/files/102.jpg">

This component adds new colour gradients to Infinity Engine games, raising the count of available colours from 116 to 256. It also includes a new random colour table making use of them for Baldur's Gate II and new colour set files for Icewind Dale II, giving you more skin/hair colour choices for the various races.</br>
It also fixes a few minor problems with standard gradients. <a href="1pp/documentation//files/extpal_readme.html">Read more »</a></br></br>

<strong>Compatibility install [102]</strong></br>
For installs that do not support the binary patch (OSX), this installs the basic files needed for 1pp to work properly but does not support using the new colours as character colours.</br></br>

<strong>Full install [103]</strong></br>
Complete install patching the game executable, enabling full use of the extended colour entries.</br>
When installing the full version, extra choices for skin and hair colour will automatically become available from the ingame selection.
As for clothing colours, during character creation and from the inventory the standard complement of 34 primary and secondary colours will be offered. To access more clothing colours, choose 'customise' » 'colours' from the character sheet to gain access to yet another set of 34 colours.</br></br>


### <a name="104" id="104"></a>[104] 1ppv4: GUI additions for BGII

Supports: <span style="color:#060">SoA</span>, <span style="color:#700">ToB</span>, <span style="color:#080">Tutu (if using the BG2 GUI)</span></br>

<img src="1pp/documentation/files/104.jpg">

A reworked graphical user interface for Baldur's Gate II SoA/ToB. This aims to get rid of a lot of the rough edges present in the original while maintaining a similar feel. Major changes include a time dial that is not just a box, getting rid of 'infinite parchment' (see additional screenshots) and an optional choice of updated fonts.</br>
<a href="1pp/documentation//gui_readme.html">See more »</a></br></br>


### <a name="105" id="105"></a>[105] 1ppv4: Avatar fixes

<strong>Requires: <a href="#101">[101]</a></strong></br>
Supports: <span style="color:#060">SoA</span>, <span style="color:#700">ToB</span>, <span style="color:#080">Tutu</span>, <span style="color:#088">HoW</span>, <span style="color:#666">IWDII</span></br>

<img src="1pp/documentation/files/105.jpg">

This component contains fixes and improvements for several avatar series of Baldur's Gate II character animations, along with updated paperdolls to better match the new content.</br>
<a href="1pp/documentation/files/avafix_readme.html">See more »</a></br></br>


### <a name="106" id="106"></a>[106-109] 1ppv4: Female Dwarves

<strong>Requires: <a href="#101">[101]</a></strong></br>
Supports: <span style="color:#060">SoA</span>, <span style="color:#700">ToB</span>, <span style="color:#080">Tutu</span>, <span style="color:#088">HoW</span>, <span style="color:#666">IWDII</span></br>

<img src="1pp/documentation/files/106.jpg">

This component patches Baldur's Gate II engine games to use separate avatar animations for female dwarves and mages of small races, and includes game content for all of these.</br>
<a href="1pp/documentation/files/dwarf_readme.html">See more »</a></br></br>


### <a name="110" id="110"></a>[110-112] 1ppv4: Thieves Galore

<strong>Requires: <a href="#101">[101]</a> <a href="#106">[106-109]</a></strong></br>
###### Note: Due to the way patching is currently handled, this component will fail if Infinity Animations is already installed. To resolve this issue, install IA after this component.</br>
Supports: <span style="color:#060">SoA</span>, <span style="color:#700">ToB</span>, <span style="color:#080">Tutu</span>, <span style="color:#088">HoW</span>, <span style="color:#666">IWDII</span><</br>

<img src="1pp/documentation/files/110.jpg">

In standard BGII only one armour level of thieves had unique animations (leather armour). Any other armour level would revert to the default unarmoured animation. On the inventory, the first two armour levels had unique paperdolls, anything else would revert to the unarmoured paperdoll.</br>
This component will patch your executable to support full thief animation sequences and install content for them.</br>
<a href="1pp/documentation/files/thieves_readme.html">Original readme »</a></br></br>


### <a name="113" id="113"></a>[113] 1ppv4: Smart Avatar & Armour Switching

Supports: <span style="color:#060">SoA</span>, <span style="color:#700">ToB</span>, <span style="color:#080">Tutu</span>, <span style="color:#088">HoW</span>, <span style="color:#666">IWDII</span></br>

<img src="1pp/documentation/files/113.jpg">

This component allows armour and robes to properly show up for characters of any class when equipped. While normally robes would not show up for fighter/cleric/thief animations, and armour would not show up for mage animations, this is circumvented by changing the character animation accordingly while such items are equipped.</br>
<a href="1pp/documentation/files/switch_readme.html">See original readme »</a></br></br>


### <a name="114" id="114"></a>[114] 1ppv4: Softer Spell Effects

<strong>Requires enabled 3D support</strong></br>

Supports: <span style="color:#060">SoA (partial)</span>, <span style="color:#700">ToB</span>, <span style="color:#080">Tutu</span>, <span style="color:#088">HoW</span>, <span style="color:#666">IWDII (placeholder)</span></br>

<img src="1pp/documentation/files/114.jpg">

Substantially improved spell effects with smooth alpha blending for Baldur's Gate II engine based IE games. Note that 3D support has to be enabled for this component to work properly - if you run your game with software rendering mode, it is not recommended to install this.</br>
<a href="1pp/documentation/files/effects_readme.html">See more information »</a></br></br>


### <a name="200" id="200"></a>[200] 1ppv4: Core content patches

<strong>Requires: <a href="#101">[101]</a></strong></br>
Supports: <span style="color:#060">SoA</span>, <span style="color:#700">ToB</span>, <span style="color:#080">Tutu</span></br>

<img src="1pp/documentation/files/200.jpg">

This is essentially the inventory icon/item related patches of 1ppv2. In other words, lots of random icon improvements for BGII, especially on the ToB side of things, as well as some mod item patches and updates. It will form the basis on which 1ppv4 is built on SoA/ToB.</br>
<a href="1pp/documentation/files/v2_readme.html">See original readme »</a></br></br>


### <a name="201" id="201"></a>[201] 1ppv4: Consistent spell and scroll icons

Supports: <span style="color:#060">SoA</span>, <span style="color:#700">ToB</span>, <span style="color:#080">Tutu</span></br>

<img src="1pp/documentation/files/201.jpg">

This component harmonises spell icons introduced in Baldur's Gate II with the ones in the original game. It updates icons found in the spellbook as well as the stone styled UI icons along with spell scrolls.</br>
<a href="1pp/documentation/files/spic_readme.html">See more »</a></br></br>


### <a name="202" id="202"></a>[202] 1ppv4: Spell tweaks

Supports: <span style="color:#060">SoA</span>, <span style="color:#700">ToB</span>, <span style="color:#080">Tutu</span></br>

<img src="1pp/documentation/files/202.jpg">

Minor spell tweaks for SoA/ToB, giving armour spells distinct appearances (ghost armour, spirit armour) as well as reworked 'cause wounds' type of spells, bringing them into line with their p&amp;p equivalents and actually making them viable.</br></br>


### <a name="203" id="203"></a>[203] 1ppv4: Restored flame sword animations

<strong>Requires: <a href="#101">[101]</a></strong></br>
Supports: <span style="color:#060">SoA</span>, <span style="color:#700">ToB</span>, <span style="color:#080">Tutu</span>, <span style="color:#088">HoW</span>, <span style="color:#666">IWDII</span></br>

<img src="1pp/documentation/files/203.jpg">

This component restores separate flame sword animations for Baldur's Gate II (similar to the ones in the original). It also includes flame short swords, adding a new item type to the game.</br></br>
<a href="1pp/documentation/files/fs_readme.html">See original readme »</a></br></br>


### <a name="204" id="204"></a>[204] 1ppv4: Colourable Quarterstaves

<strong>Requires: <a href="#101">[101]</a></strong></br>
Supports:<span style="color:#060">SoA</span>, <span style="color:#700">ToB</span>, <span style="color:#080">Tutu</span>, <span style="color:#088">HoW</span>, <span style="color:#666">IWDII</span></br>

<img src="1pp/documentation/files/204.jpg">

This component makes quarterstaves colourable by segment (as opposed to uniform) to allow more variety in-game and match inventory depictions. It also includes item patches to make use of the new content.</br>
<a href="1pp/documentation/files/qs_readme.html">See developer reference »</a></br></br>


### <a name="205" id="205"></a>[205] 1ppv4: Legacy Shields v2

<strong>Requires: <a href="#101">[101]</a></strong></br>
Supports: <span style="color:#060">SoA</span>, <span style="color:#700">ToB</span>, <span style="color:#080">Tutu</span>, <span style="color:#088">HoW</span>, <span style="color:#666">IWDII</span></br>

<img src="1pp/documentation/files/205.jpg">

Proper reconstruction and re-renders of the Baldur's Gate I shield animations, superseding the old legacy ports; thanks to invaluable support from the BG:EE team.</br></br>


### <a name="206" id="206"></a>[206] 1ppv4: Additional Shield Animations (core)

<strong>Requires: <a href="#101">[101]</a></strong></br>
Supports: <span style="color:#060">SoA</span>, <span style="color:#700">ToB</span>, <span style="color:#080">Tutu</span>, <span style="color:#088">HoW</span>, <span style="color:#666">IWDII</span></br>

<img src="1pp/documentation/files/206a.jpg">

<img src="1pp/documentation/files/206b.jpg">

This component includes updated versions of Baldur's Gate II's shield animations, as well as several completely new animation types. Also included is one variant that shares common animations but has distinct paperdolls.</br>

###### <em>Note that this is a core component; by itself it does not contain any item patches. If installed, the content will instead be used by following 1ppv4 components to give you more options when updating.</em></br></br>


### <a name="207" id="207"></a>[207] 1ppv4: Wizards' Staves (core)

<strong>Requires: <a href="#101">[101]</a></strong></br>
Supports: <span style="color:#060">SoA</span>, <span style="color:#700">ToB</span>, <span style="color:#080">Tutu</span>, <span style="color:#088">HoW</span>, <span style="color:#666">IWDII</span></br>

<img src="1pp/documentation/files/207.jpg">

This component includes one new animation (wizard's staff) as well as several new paperdoll appearances for regular colourable quarterstaves.</br>

###### <em>Note that this is a core component; by itself it does not contain any item patches. If installed, the content will instead be used by following 1ppv4 components to give you more options when updating.</em></br></br>


### <a name="208" id="208"></a>[208] 1ppv4: Additional Helmet Animations (core)

<strong>Requires: <a href="#101">[101]</a></strong></br>
Supports: <span style="color:#060">SoA</span>, <span style="color:#700">ToB</span>, <span style="color:#080">Tutu</span>, <span style="color:#088">HoW</span>, <span style="color:#666">IWDII</span></br>

<img src="1pp/documentation/files/208a.jpg">
<img src="1pp/documentation/files/208b.jpg">

This component includes improved content for Baldur's Gate II's vanilla helmet animations, and introduces five new helmet animations (one not pictured). It also introduces circlets which actually render on model!</br>

###### <em>Note that this is a core component; by itself it does not contain any item patches. If installed, the content will instead be used by following 1ppv4 components to give you more options when updating.</em></br></br>


### <a name="209" id="209"></a>[209] 1ppv4: Attachable wings (core)

<strong>Requires: <a href="#101">[101]</a></strong></br>
Supports: <span style="color:#060">SoA</span>, <span style="color:#700">ToB</span>, <span style="color:#080">Tutu</span>, <span style="color:#088">HoW</span>, <span style="color:#666">IWDII</span></br>

<img src="1pp/documentation/files/209.jpg">

This adds equippable wings for elven characters (with some restrictions).</br></br>
<a href="files/wings_readme.html">See readme &amp; developer notes »</a></br>

###### <em>Note that this is a core component; by itself it does not contain any item patches. If installed, the content will instead be used by following 1ppv4 components to give you more options when updating.</em></br></br>


### <a name="210" id="210"></a>[210] 1ppv4: Increased paperdoll object variety (core)

<strong>Requires: <a href="#101">[101]</a></strong></br>
Supports: <span style="color:#060">SoA</span>, <span style="color:#700">ToB</span>, <span style="color:#080">Tutu</span>, <span style="color:#088">HoW</span>, <span style="color:#666">IWDII</span></br>

<img src="1pp/documentation/files/210.jpg">

This component increases paperdoll variety by adding various alternates sharing existing object animations. Included are separate paperdoll appearances for bastard swords, various types of flails, maces, short bows, and more (not all of them pictured).</br>

###### <em>Note that this is a core component; by itself it does not contain any item patches. If installed, the content will instead be used by following 1ppv4 components to give you more options when updating.</em></br></br>


### <a name="400" id="400"></a>[400] 1ppv4: Core updates and item patches

<strong>Requires: <a href="#101">[101]</a> <a href="#200">[200]</a> (on SoA/ToB/Tutu)</strong></br>
<strong>Suggested: <a href="#203">[203]</a> <a href="#204">[204]</a> <a href="#205">[205]</a> <a href="#206">[206]</a> <a href="#207">[207]</a> <a href="#208">[208]</a> <a href="#209">[209]</a> <a href="#210">[210]</a></strong></br>
Supports: <span style="color:#060">SoA</span>, <span style="color:#700">ToB</span>, <span style="color:#080">Tutu</span>, <span style="color:#088">HoW</span></br>

This is the main 1ppv4 update component. Make sure you have all components you would like to see used installed before proceeding (suggested components will provide additional content and install choices). The following screenshots depict standard installation choices, except where noted otherwise.</br>

<img src="1pp/documentation/files/400h4.jpg">
<img src="1pp/documentation/files/400s4.jpg">
<img src="1pp/documentation/files/400ss.jpg">

Various content choices will be presented to you during installation (depending on which IE game you are installing for and installed components). For a full, visual guide to choices see the link below. Consider choosing 'yes' to setting item colours for non-magical items (setting 2/3).</br>
<a href="1pp/documentation/files/v4u_readme.html">Alternative install choices »</a></br></br>


### <a name="401" id="401"></a>[401] 1ppv4: Improved projectile effects

<strong>Requires: <a href="#200">[200]</a> <a href="#400">[400]</a></strong></br>
Supports: <span style="color:#060">SoA</span>, <span style="color:#700">ToB</span>, <span style="color:#080">Tutu</span></br>

<img src="1pp/documentation/files/401.jpg">
<img src="1pp/documentation/files/401b.jpg">

This component improves projectile effects around Baldur's Gate II. Be able to see what kind of bullets/arrows/bolts are shot at you (or if you're really absent-minded, which <em>you</em> are shooting). Includes coloured bolt and bullet projectiles, axes and darts, and what is even neater, you can actually see the ammunition change on your paperdoll!</br></br>


### <a name="300" id="300"></a>[300] 1ppv4: Fixed animations for solars and elementals

Supports: <span style="color:#700">ToB</span>, <span style="color:#080">Tutu</span></br>

<img src="1pp/documentation/files/300.jpg">

Fixed rendering for solar animations on ToB based games, as well as blended fire elementals.</br></br>


### <a name="301" id="301"></a>[301] 1ppv4: Miscellaneous content fixes

Supports: <span style="color:#060">SoA</span>, <span style="color:#700">ToB</span>, <span style="color:#080">Tutu</span>, <span style="color:#088">HoW</span>, <span style="color:#666">IWDII</span></br>

<img src="1pp/documentation/files/301.jpg">

Contains the following fixes: dog animations (corrupted palette), sitting static peasant woman (bad BAM conversion), alternate fire giant animation slot (was useless as the animation had no unified palette, thus impossible to fill). It also fixes an engine related bug on SoA/ToB and IWD:TotLM that will have helmets randomly render wrong sequences when changing equipment, making them 'float' off your character.  Finally, it contains a fix for bugged shield z-buffering on SoA, ToB, IWD:TotLM and IWDII on BGII character animations.</br></br>


## Credits

For support or questions, please visit the <a href="http://www.shsforums.net/index.php?showforum=159">mod forum</a>.

#### Installer & content: Erephine<br />

#### Tools used in creation (among others):

- <a href="http://www.weidu.org/%7Ethebigg/"><acronym title="Weimer Dialogue Utility">WeiDU</acronym></a>, by Wes Weimer, the bigg and Wisp.
- <a href="http://notepad-plus-plus.org/">Notepad++</a>, by the Notepad++ team, Don Ho, and the spellcheck plug-in.
- <a href="http://www.shsforums.net/files/file/1048-weidu-highlighter-for-notepad/">WeiDU Notepad++ Highlighters </a>, by Argent77.
- <a href="http://www.teambg.eu/?page=tools&amp;cat=32">BAM Workshop</a>, by Glenn Flansburg.
- <a href="http://www.shsforums.net/topic/57564-bamworkshop/">BAMWorkshop 2</a>, by Andrew Bridges.
- <a href="https://www.adobe.com/products/photoshop.html">Adobe Photoshop</a>
- <a href="http://www.gimp.org/"><acronym title="GNU Image Manipulation Program">GIMP</acronym></a>, by the GIMP team.
- <a href="http://www.gamani.com/">GIF Movie Gear</a>
- <a href="https://www.autodesk.com/products/3ds-max/overview">3ds Max</a>
- <a href="http://" target="_blank">1pp dev tools</a>
- <a href="http://" target="_blank">Hex Editor Neo</a>
- <a href="http://" target="_blank">ACDSee Pro</a>
</br></br>


## Version History

##### Version 4.2.0 - October 1x, 2018


##### Version 4.1.0
- Scale shields now have their own animations
- Improved carried/description images
- Fixed low resolution GUI overlap


##### Version 4.0.0
- Initial release


