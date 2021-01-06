# Map Data for MrDestructo
Credit goes to DiaZ/AOD for creating MrDestructo and to whoever put together Rialto and Hollywood.
I decided to create map data for each map. I've included the entire subroutine.  
I know for sure this will work with Hax Framework.  

Not included as there is nothing really breakable:  
- King's Row
- Ecopoint: Antartica
- Petra

## INSTALLATION:
1. Copy the contents of the applicable map .txt file from the [Maps](/Maps/) folder or from the list below.
- [Ayutthaya](/Maps/Ayutthaya.txt)
- [Black Forest](/Maps/BlackForest.txt)
- [Blizzard World](/Maps/BlizzardWorld.txt)
- [Busan](/Maps/Busan.txt)
- [Castillo](/Maps/Castillo.txt)
- [Chateau Guillard](/Maps/ChateauGuillard.txt)
- [Dorado](/Maps/Dorado.txt)
- [Eichenwald](/Maps/Eichenwald.txt)
- [Hanamura](/Maps/Hanamura.txt)
- [Havana](/Maps/Havana.txt)
- [Hollywood](/Maps/Hollywood.txt)
- [Horizon Lunar Colony](/Maps/HorizonLunarColony.txt)
- [Ilios](/Maps/Ilios.txt)
- [Junkertown](/Maps/Junkertown.txt)
- [Lijiang Tower](/Maps/LijiangTower.txt)
- [Necropolis](/Maps/Necropolis.txt)
- [Nepal](/Maps/Nepal.txt)
- [Numbani](/Maps/Numbani.txt)
- [Oasis](/Maps/Oasis.txt)
- [Paris](/Maps/Paris.txt)
- [Rialto](/Maps/Rialto.txt)
- [Route 66](/Maps/Route66.txt)
- [Temple of Anubis](/Maps/TempleOfAnubis.txt)
- [Volskaya Industries](/Maps/VolskayaIndustries.txt)
- [Watchpoint: Gibralter](/Maps/WatchpointGibralter.txt)
- [Empty Map (For future maps)](/Maps/EmptyMap.txt)

2. In Workshop, a yellow button will appear at the top. Click that button to paste the contents that you copied in step one.  

3. Paste the entire condition statement to the Hax Framework rule named *Player Joins, Current CP Color* using the yellow button that appears in the *conditions* section of the rule.  
Be sure to copy from the word *conditions* to the closing curly brace *}*.
```
conditions
{
    Is Dummy Bot(Event Player) == False;
}
```
