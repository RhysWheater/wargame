# My Wargame Rules
*A Minimalist Mass Battle Wargame*

---

## CORE CONCEPT  
1. A fast-playing wargame for massed battles, focusing on unit cohesion and positioning rather than individual model hit points.
1. Designed for quick, decisive games that reward clever positioning and cohesion management.
1. Units degrade via cohesion (not hit points) through combat, morale shocks, and positioning.  
1. The system works with any scale or base size, provided both sides use the same base width.
1. All distances are measured in **base widths**.

---

## UNIT STATES  
1. Each unit has four cohesion states:  
   **Fresh → Shaken → Disrupted → Destroyed**
1. **Fresh**: Full combat effectiveness.
1. **Shaken**: May act but suffers minor penalties.
1. **Disrupted**: Severely impaired.
1. **Destroyed**: Removed from battlefield.
1. Units degrade one state when they take a *hit*.  
1. Use tokens, markers, dice, or dials to track unit states.

---

## TURN STRUCTURE  
1. On each player's turn, they may activate each of their units once, in any order.
1. When a unit is activated, it may perform one of the following actions:
    1. **Move**: Move up to its movement distance.
    1. **Attack**: Engage in combat if in front-edge contact with an enemy unit.
    1. **Rally**: Attempt to recover cohesion state (see 9; if Shaken or Disrupted, and not engaged).

---

## MOVEMENT  
1. Units may move freely any distance up to a maximum of their move stat x base width.  
1. Units may pivot freely before or after movement.  
1. Units may not move through or end movement inside enemy units.
1. Units may not end movement inside friendly units.
1. Units may not move through friendly units unless they have the **Skirmisher** trait.

---

## Terrain

1. Players should agree during setup what type each piece of terrain represents.  
    1. **Open:** Normal movement.  
    1. **Road:** Double movement distance when moving entirely along a road.  
    1. **Rough:** Half movement distance.  
    1. **Obstacle:** Costs one full movement to cross, regardless of distance.  
    1. **Impassable:** Cannot be entered or crossed.  

---

## SUPPORT  
1. In melee, a unit gains **+1 Resolve** for each **supporting friendly unit**:  
   - **Side support**: Base to base contact on either side, facing the same direction.
   - **Rear support**: Directly behind and not engaged.  

---

## FACING  
1. **Flank attacks** grant +1 Resolve.  
1. **Rear attacks** grant +2 Resolve.  
1. Defending units gain **no support** if attacked from flank or rear.

---

## COMBAT

1. When two units are in melee, compare their **Resolve** (base + modifiers).
1. **Roll Dice**:  
   1. If Resolve is equal: attacker rolls 1D6 and uses the result.
   1. If attacker has higher Resolve: attacker rolls 2D6, picks their preferred result.
   1. If defender has higher Resolve: defender rolls 2D6, picks their preferred result.
1. **Combat Result Table:**

   | Roll | Result       | Effect                                  |
   | ---- | ------------ | --------------------------------------- |
   | 1    | Repulsed     | Attacker takes 1 hit                    |
   | 2    | Brutal Clash | Both attacker and defender take 1 hit   |
   | 3-4  | Forced Back  | Defender pushed back 1 base width       |
   | 5    | Hit & Hold   | Defender takes 1 hit                    |
   | 6    | Breakthrough | Defender takes 1 hit and is pushed back |

1. Pushbacks must move directly away 1 base width.
1. If a unit is pushed back into another friendly unit, and it is not a skirmisher, the other unit is also pushed back the same distance.
1. If a unit is pushed back into an enemy unit, or into impassable, obstacle or rough terrain, or off the table, it is **destroyed**.

### Resolve Modifiers

1. **Cohesion State:**
   1. Fresh: no modifier
   1. Shaken: −1 Resolve
   1. Disrupted: −2 Resolve
1. **Support:** +1 Resolve per supporting friendly unit (side or rear)
1. **Flank Attack:** +1 Resolve for attacker
1. **Rear Attack:** +2 Resolve for attacker
