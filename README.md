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
> 
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
  - **attributes** `id` == `id` **attributes** and **that is the road of changes**
  - **attributes** `name` == `name` **attributes**
  - **attributes** `aggroRange` == `<ai type="BALANCED" aggroRange="300"/>` **tag**
  - ai_type == **dont change this**
  - **attributes** `baseCON` == `<stats con="00">` **tag**
  - **attributes** `baseCritRate` == `<attack critical="0" />` **tag**
  - > in **`baseCritRate`** if = 40 it gonna be 4 in  `<attack critical="4" />`
  - > in **`baseCritRate`** if = 90 it gonna be 9 in  `<attack critical="9" />`
  - **attributes** `baseDEX` == `<stats dex="00">` **tag**
  - **attributes** `baseHpMax` == `<vitals hp="00.00" />` **tag**
  - **attributes** `baseHpRate` == **dont change this**
  - **attributes** `baseHpReg` == `<vitals hpRegen="00.00" />` **tag**
  - **attributes** `baseINT` == `<stats int="00">` **tag**
  - **attributes** `baseMAtk` == `<attack magical="6998.04554416799" />` **tag**
  - **attributes** `baseMAtkSpd` == **by default is 333**
  - **attributes** `baseMDef` == `<defence magical="621.45708" />`**tag**
  - **attributes** `baseMEN` == `<stats men="00">` **tag**
  - **attributes** `baseMpMax` == `<vitals mp="00.00" />` **tag**
  - **attributes** `baseMpReg` == `<vitals mpRegen="00.00" />` **tag**
  - **attributes** `basePAtk` == `<attack physical="10247.9853769394" />` **tag**
  - **attributes** `basePAtkSpd` == `<attack attackSpeed="253" />` **tag**
  - **attributes** `basePDef` == `<defence physical="566.178304" />` **tag**
  - **attributes** `baseRunSpd` == `<run ground="200" />` **tag**
  - **attributes** `baseSTR` == `<stats str="00">` **tag**
  - **attributes** `baseShldDef` == check if has `Shield Defence`
  - > not all mobs has `Shield Defence`
  - **attributes** `baseShldRate` == check if has `Shield Defence rate`
  - > not all mobs has `Shield Defence rate`
  - **attributes** `baseWIT` == `<stats wit="00">` **tag**
  - **attributes** `baseWalkSpd` == `<walk ground="100" />` **tag**
  - **attributes** `collision_height` == `<height normal="55" />` **tag**
  - **attributes** `collision_radius` == `<radius normal="50" />` **tag**
  - **attributes** `level` == `<npc level="00">` **tag**
  - **attributes** `rewardExp` == `<acquire expRate="60.6003927743101" />` **tag**
  - **attributes** `rewardRp` == `<acquire raidPoints="0" />` **tag**
  - **attributes** `rewardSp` == `<acquire sp="42928" />` **tag**
  - **attributes** `texture` == if you checked the texture are the same in client etc do the right.
  - **attributes** `type` == **dont change this**
- `<skills>` == `<skillList>` **tag**
  - `<skill id="4408" level="11" />` == `<skill id="4408" level="11" />` **tag and attributes**
  - > **all mobs must have skills if you dont found it in our files you must put it!!!**
- `<attributes>` == `<attribute>` **tag**
  - `<attack attribute="fire" value="200" />` == `<attack type="FIRE" value="200" />` **tag and attributes**
  - `<defence attribute="fire" value="170" />` == `<defence fire="200" water="140" wind="170" earth="170" holy="170" dark="170" default="180" />`
  - > **all mobs must have attribute if you dont found it in our files you must put it!!!**

## after finish edit you have to put your signture after open tag `<npc>` like this
 - > `<npc>`
 - > `<!-- Edited to Retail CT2.6 by <YourName> -->`
