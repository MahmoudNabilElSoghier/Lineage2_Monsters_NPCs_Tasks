# Lineage2 Monsters NPCs Tasks
## Hello guys, and how are you, i hope everything gonna be well.
---
### i will explane about task and what we gonna work on it
#### everyone gonna have foldar and every folder has 2 folders and every folder has 25 file like this
- Folder **part 1 zyad**
  - Folder **from** has 25 files
  - Folder **to** has 25 files
- Folder **part 1 swelam**
  - Folder **from** has 25 files
  - Folder **to** has 25 files
- Folder **part 1 eldoc**
  - Folder **from** has 25 files
  - Folder **to** has 25 files
- Folder **part 1 omar**
  - Folder **from** has 25 files
  - Folder **to** has 25 files
- Folder **part 1 mahmoud**
  - Folder **from** has 25 files
  - Folder **to** has 25 files
> here you have to open **from** folder and put it in left side in the window and **to** folder in right side in the window and start check keys and change values.

---

first i'm gonna show you what's the **different** between our file **WolfPack (WP)** and **L2JSunrise**
> WE TALK ABOUT **NPCs** only!
- our file **WolfPack**
`
	<npc id="22822" name="Drakos Warrior" title="">
	<!-- Edited to Retail CT2.6 by LordOfBattle -->
		<set name="aggroRange" value="400" />
		<set name="ai_type" value="Fighter" />
		<set name="baseAtkRange" value="40" />
		<set name="baseCON" value="43" />
		<set name="baseCritRate" value="40" />
		<set name="baseDEX" value="30" />
		<set name="baseHpMax" value="18734.280667127" />
		<set name="baseHpRate" value="1" />
		<set name="baseHpReg" value="190.897045965523" />
		<set name="baseINT" value="21" />
		<set name="baseMAtk" value="6998" />
		<set name="baseMAtkSpd" value="333" />
		<set name="baseMDef" value="622" />
		<set name="baseMEN" value="20" />
		<set name="baseMpMax" value="1777.4" />
		<set name="baseMpReg" value="3" />
		<set name="basePAtk" value="10248" />
		<set name="basePAtkSpd" value="253" />
		<set name="basePDef" value="566" />
		<set name="baseRunSpd" value="200" />
		<set name="baseSTR" value="40" />
		<set name="baseShldDef" value="0" />
		<set name="baseShldRate" value="0" />
		<set name="baseWIT" value="20" />
		<set name="baseWalkSpd" value="100" />
		<set name="collision_height" value="55.0" />
		<set name="collision_radius" value="50.0" />
		<set name="level" value="83" />
		<set name="rewardExp" value="61" />
		<set name="rewardRp" value="0" />
		<set name="rewardSp" value="42928" />
		<set name="shots" value="NONE" />
		<set name="texture" value="" />
		<set name="type" value="Monster" />
		<skills>
			<skill id="4408" level="11" /> <!--HP Increase (3x) -->
			<skill id="4409" level="1" /> <!--MP Increase (1x) -->
			<skill id="4410" level="15" /> <!--Strong P. Atk. -->
			<skill id="4411" level="11" /> <!--Average M. Atk. -->
			<skill id="4412" level="17" /> <!--Very Strong P. Def. -->
			<skill id="4413" level="7" /> <!--Weak M. Def. -->
			<skill id="4414" level="2" /> <!--Standard Type -->
			<skill id="4415" level="1" /> <!--Bare Hands -->
			<skill id="4416" level="10" /> <!--Dragons -->
			<skill id="5462" level="1" /> <!--Fire Attacks -->
			<skill id="6857" level="1" /> <!--Power Strike -->
		</skills>
		<attributes>
			<attack attribute="fire" value="200" />
			<defence attribute="fire" value="170" />
			<defence attribute="water" value="140" />
			<defence attribute="wind" value="170" />
			<defence attribute="earth" value="170" />
			<defence attribute="holy" value="170" />
			<defence attribute="unholy" value="170" />
		</attributes>
		<drop_lists>
			<death>
				<group chance="66">
					<item id="57" min="18619" max="43478" chance="100" /> <!-- Adena -->
				</group>
				<group chance="0.010499999858438969">
					<item id="10221" min="1" max="1" chance="17.8323" /> <!-- Icarus Hand -->
					<item id="15697" min="1" max="1" chance="82.1677" /> <!-- Sealed Moirai Breastplate -->
				</group>
				<group chance="49.711299896240234">
					<item id="1879" min="1" max="3" chance="40.4996" /> <!-- Cokes -->
					<item id="1885" min="1" max="1" chance="40.4996" /> <!-- High-Grade Suede -->
					<item id="9628" min="1" max="1" chance="3.8117" /> <!-- Leonard -->
					<item id="9630" min="1" max="1" chance="2.5579" /> <!-- Orichalcum -->
					<item id="9629" min="1" max="1" chance="2.113" /> <!-- Adamantine -->
					<item id="10483" min="1" max="1" chance="3.375" /> <!-- Life Stone - Level 82 -->
					<item id="10484" min="1" max="1" chance="0.8437" /> <!-- Mid-Grade Life Stone - Level 82 -->
					<item id="10485" min="1" max="1" chance="0.0844" /> <!-- High-Grade Life Stone - Level 82 -->
					<item id="9552" min="1" max="1" chance="0.0972" /> <!-- Fire Crystal -->
					<item id="9546" min="1" max="1" chance="3.888" /> <!-- Fire Stone -->
					<item id="17248" min="1" max="1" chance="0.2859" /> <!-- Large Dragon Bone -->
					<item id="6622" min="1" max="1" chance="1.944" /> <!-- Giant's Codex -->
				</group>
			</death>
			<corpse>
				<item id="4042" min="1" max="1" chance="42.0375" /> <!-- Enria -->
				<item id="9628" min="1" max="1" chance="19.7823" /> <!-- Leonard -->
				<item id="10401" min="1" max="1" chance="1.0779" /> <!-- Icarus Trident Piece -->
				<item id="15780" min="1" max="1" chance="0.9987" /> <!-- Recipe - Sealed Moirai Tunic (60%) -->
				<item id="10397" min="1" max="1" chance="1.0813" /> <!-- Icarus Sawsword Piece -->
				<item id="10373" min="1" max="1" chance="0.1626" /> <!-- Recipe - Icarus Sawsword (60%) -->
				<item id="15697" min="1" max="1" chance="0.015" /> <!-- Sealed Moirai Breastplate -->
			</corpse>
		</drop_lists>
	</npc>
`
- **L2JSunrise** file
`
	<npc id="22822" level="83" type="L2Monster" name="Drakos Warrior">
		<!-- Confirmed CT2.5 -->
		<parameters>
			<param name="IsAggressive" value="1" />
			<skill name="Skill01_ID" id="6857" level="1" /> <!-- Power Strike -->
		</parameters>
		<race>DRAGON</race>
		<sex>MALE</sex>
		<acquire expRate="60.6003927743101" sp="42928" />
		<stats str="40" int="21" dex="30" wit="20" con="43" men="20">
			<vitals hp="18734.280667127" hpRegen="190.897045965523" mp="1777.4" mpRegen="3" />
			<attack physical="10247.9853769394" magical="6998.04554416799" random="10" critical="4" accuracy="5" attackSpeed="253" type="FIST" range="40" distance="80" width="120" />
			<defence physical="566.178304" magical="621.45708" />
			<attribute>
				<attack type="FIRE" value="200" />
				<defence fire="200" water="140" wind="170" earth="170" holy="170" dark="170" default="180" />
			</attribute>
			<speed>
				<walk ground="100" />
				<run ground="200" />
			</speed>
			<hitTime>570</hitTime>
		</stats>
		<status undying="false" canBeSown="true" />
		<skillList>
			<skill id="4408" level="11" /> <!--HP Increase (3x) -->
			<skill id="4409" level="1" /> <!--MP Increase (1x) -->
			<skill id="4410" level="15" /> <!--Strong P. Atk. -->
			<skill id="4411" level="11" /> <!--Average M. Atk. -->
			<skill id="4412" level="17" /> <!--Very Strong P. Def. -->
			<skill id="4413" level="7" /> <!--Weak M. Def. -->
			<skill id="4414" level="2" /> <!--Standard Type -->
			<skill id="4415" level="1" /> <!--Bare Hands -->
			<skill id="4416" level="10" /> <!--Dragons -->
			<skill id="5462" level="1" /> <!--Fire Attacks -->
			<skill id="6857" level="1" /> <!--Power Strike -->
		</skillList>
		<exCrtEffect>false</exCrtEffect>
		<sNpcPropHpRate>3</sNpcPropHpRate>
		<ai type="BALANCED" aggroRange="300" clanHelpRange="300" />
		<dropLists>
			<death>
				<group chance="66">
					<item id="57" min="18619" max="43478" chance="100" /> <!-- Adena -->
				</group>
				<group chance="0.010499999858438969">
					<item id="10221" min="1" max="1" chance="17.8323" /> <!-- Icarus Hand -->
					<item id="15697" min="1" max="1" chance="82.1677" /> <!-- Sealed Moirai Breastplate -->
				</group>
				<group chance="49.711299896240234">
					<item id="1879" min="1" max="3" chance="40.4996" /> <!-- Cokes -->
					<item id="1885" min="1" max="1" chance="40.4996" /> <!-- High-Grade Suede -->
					<item id="9628" min="1" max="1" chance="3.8117" /> <!-- Leonard -->
					<item id="9630" min="1" max="1" chance="2.5579" /> <!-- Orichalcum -->
					<item id="9629" min="1" max="1" chance="2.113" /> <!-- Adamantine -->
					<item id="10483" min="1" max="1" chance="3.375" /> <!-- Life Stone - Level 82 -->
					<item id="10484" min="1" max="1" chance="0.8437" /> <!-- Mid-Grade Life Stone - Level 82 -->
					<item id="10485" min="1" max="1" chance="0.0844" /> <!-- High-Grade Life Stone - Level 82 -->
					<item id="9552" min="1" max="1" chance="0.0972" /> <!-- Fire Crystal -->
					<item id="9546" min="1" max="1" chance="3.888" /> <!-- Fire Stone -->
					<item id="17248" min="1" max="1" chance="0.2859" /> <!-- Large Dragon Bone -->
					<item id="6622" min="1" max="1" chance="1.944" /> <!-- Giant's Codex -->
				</group>
			</death>
			<corpse>
				<item id="4042" min="1" max="1" chance="42.0375" /> <!-- Enria -->
				<item id="9628" min="1" max="1" chance="19.7823" /> <!-- Leonard -->
				<item id="10401" min="1" max="1" chance="1.0779" /> <!-- Icarus Trident Piece -->
				<item id="15780" min="1" max="1" chance="0.9987" /> <!-- Recipe - Sealed Moirai Tunic (60%) -->
				<item id="10397" min="1" max="1" chance="1.0813" /> <!-- Icarus Sawsword Piece -->
				<item id="10373" min="1" max="1" chance="0.1626" /> <!-- Recipe - Icarus Sawsword (60%) -->
				<item id="15697" min="1" max="1" chance="0.015" /> <!-- Sealed Moirai Breastplate -->
			</corpse>
		</dropLists>
		<collision>
			<radius normal="50" />
			<height normal="55" />
		</collision>
	</npc>
`


every value are the same and key too but with small different on name but still close on it

like open tag in L2JSunrise
`<npc id="22822" level="83" type="L2Monster" name="Drakos Warrior">`

and open tag in our file WolfPack
`<npc id="22822" name="Drakos Warrior" title="">`
- here open tag `<npc>`
  - with same id and same name
- in L2JSunrise open tag `<npc>`
  - with same id and same name
> the different here in our file **level** **attribute** in `<set>` tag and it's like **key** and **value** but in L2JSunrise **level** in `<npc>` tag and if NPC not have **title** in L2JSunrise not gonna be have this **attribute**

#### here i'm gonna put WOLFPACK Tags and Keys == L2JSunrise Tags and Keys
- `<npc>` == `<npc>` **tag**
  - **attributes** id == id **attributes** and **that is the road of changes**
  - **attributes** name == name **attributes**
  - **attributes** aggroRange == `<ai type="BALANCED" aggroRange="300"/>` **tag**
  - ai_type == **dont change this**
  - **attributes** baseCON == `<stats con="00">` **tag**
  - **attributes** baseCritRate == `<attack critical="0" />` **tag**
  - > in **baseCritRate** if = 40 it gonna be 4 in  `<attack critical="4" />`
  - > in **baseCritRate** if = 90 it gonna be 9 in  `<attack critical="9" />`
  - **attributes** baseDEX == `<stats dex="00">` **tag**
  - **attributes** baseHpMax == `<vitals hp="00.00" />` **tag**
  - **attributes** baseHpRate == **dont change this**
  - **attributes** baseHpReg == `<vitals hpRegen="00.00" />` **tag**
  - **attributes** baseINT == `<stats int="00">` **tag**
  - **attributes** baseMAtk == `<attack magical="6998.04554416799" />` **tag**
  - **attributes** baseMAtkSpd == **by default is 333**
  - **attributes** baseMDef == `<defence magical="621.45708" />`**tag**
  - **attributes** baseMEN == `<stats men="00">` **tag**
  - **attributes** baseMpMax == `<vitals mp="00.00" />` **tag**
  - **attributes** baseMpReg == `<vitals mpRegen="00.00" />` **tag**
  - **attributes** basePAtk == `<attack physical="10247.9853769394" />` **tag**
  - **attributes** basePAtkSpd == `<attack attackSpeed="253" />` **tag**
  - **attributes** basePDef == `<defence physical="566.178304" />` **tag**
  - **attributes** baseRunSpd == `<run ground="200" />` **tag**
  - **attributes** baseSTR == `<stats str="00">` **tag**
  - **attributes** baseShldDef == check if has Shield Defence
  - > not all mobs has Shield Defence
  - **attributes** baseShldRate == check if has Shield Defence rate
  - > not all mobs has Shield Defence rate
  - **attributes** baseWIT == `<stats wit="00">` **tag**
  - **attributes** baseWalkSpd == `<walk ground="100" />` **tag**
  - **attributes** collision_height == `<height normal="55" />` **tag**
  - **attributes** collision_radius == `<radius normal="50" />` **tag**
  - **attributes** level == 
  - **attributes** rewardExp == `<acquire expRate="60.6003927743101" />` **tag**
  - **attributes** rewardRp == `<acquire raidPoints="0" />` **tag**
  - **attributes** rewardSp == `<acquire sp="42928" />` **tag**
  - **attributes** texture == 
  - **attributes** type == **dont change this**
- `<skills>` == `<skillList>` **tag**
  - `<skill id="4408" level="11" />` == `<skill id="4408" level="11" />` **tag and attributes**
  - > **all mobs must have skills if you dont found it in our files you must put it!!!**
- `<attributes>` == `<attribute>` **tag**
  - `<attack attribute="fire" value="200" />` == `<attack type="FIRE" value="200" />` **tag and attributes**
  - `<defence attribute="fire" value="170" />` == `<defence fire="200" water="140" wind="170" earth="170" holy="170" dark="170" default="180" />`
  - > **all mobs must have attribute if you dont found it in our files you must put it!!!**
- 
- 
- 
- 
- 
- 
- 
- 
- 
- 
- 
- 
