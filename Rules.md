# My Wargame Rules
*A Minimalist Mass Battle Wargame*

---

## 1. CORE CONCEPT  
1. A fast-playing wargame for massed battles, focusing on unit cohesion and positioning rather than individual model hit points.
1. Designed for quick, decisive games that reward clever positioning and cohesion management.
1. Units degrade via cohesion (not hit points) through combat, morale shocks, and positioning.  
1. Inspired by the tactical depth of BloodBowl's positioning, blocking and dodging mechanics, but applied to massed battles.
1. The system works with any scale or base size, provided both sides use the same base width.
1. All distances are measured in **base widths**.

---

## 2. UNIT STATES  
1. Each unit has four cohesion states:  
   **<font color="red">Fresh</font> → <font color="goldenrod">Shaken</font> → <font color="orange">Disrupted</font> → <font color="red">Destroyed</font>**
1. **<font color="green">Fresh</font>**: Full combat effectiveness.
1. **<font color="goldenrod">Shaken</font>**: May act but suffers minor penalties.
1. **<font color="orange">Disrupted</font>**: Severely impaired.
1. **<font color="red">Destroyed</font>**: Removed from battlefield.
1. Units degrade one state when they take a *hit*.  
1. Use tokens, markers, dice, or dials to track unit states.

---

## 3. TURN STRUCTURE  
1. Players alternate **activating one unit at a time** until all units have acted.  
1. Each activated unit may perform one of the following:  
   1. **Move**  
   1. **Attack** (if engaged)  
   1. **Fall Back** (see 8)  
   1. **Rally** (see 9; if Shaken or Disrupted, and not engaged)

---

## 4. MOVEMENT  
1. Units move a standard distance of **1 base width** (unless terrain modifies it).  
1. Units may pivot freely before or after movement.  
1. Units may not move through or end movement inside enemy units.
1. Units may not end movement inside friendly units.
1. Units may not move through friendly units unless they have the **Skirmisher** trait.

---

## 5. SUPPORT  
1. In melee, a unit gains **+1 Resolve** for each **supporting friendly unit**:  
   - **Side support**: Base to base contact on either side, facing the same direction.
   - **Rear support**: Directly behind and not engaged.  

---

## 6. FACING  
1. **Flank attacks** grant +1 Resolve.  
1. **Rear attacks** grant +2 Resolve.  
1. Defending units gain **no support** if attacked from flank or rear.

---

## 7. COMBAT

1. When two units are in melee, compare their **Resolve** (base + modifiers).
1. **Roll Dice**:  
   - If Resolve is equal: attacker rolls 1D6 and uses the result.
   - If attacker has higher Resolve: attacker rolls 2D6, picks their preferred result.
   - If defender has higher Resolve: defender rolls 2D6, picks their preferred result.
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
1. If a unit is pushed back into an enemy unit, or into impassable or rough terrain, or off the table, it is **destroyed**.

### 7.1 Resolve Modifiers

1. **Cohesion State:**
   - Fresh: no modifier
   - Shaken: −1 Resolve
   - Disrupted: −2 Resolve
1. **Support:** +1 Resolve per supporting friendly unit (side or rear)
1. **Flank Attack:** +1 Resolve for attacker
1. **Rear Attack:** +2 Resolve for attacker
