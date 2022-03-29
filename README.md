---
aliases: 
- Overview
---

# Kizomba Notation
The Kizomba Notation is based on 4 main information sources:
- [[Kizomba Notation/README#Count|Count]]
- Leader/ Follower [[Kizomba Notation/README#Movement|Movement]]
- [[Kizomba Notation/README#Orientation|Orientation]]

## Structure
All displayed information assumes the orientation to the north. 
Thus the leader would face by default toward the north.

This means that the displayed signs are not necessary using the Leader's/ Follower's own perspective.
### Long Notation
In the long or table notation these information are displayed in this order:
1. Count (C)
2. Follower movement (F)
3. Orientation (O)
4. Leader movement (L)

Using the [[Saida Woman]] as an example this would result such an output:

| C   |     | 1   | 2   | 3   | &   | 4   | 5   | 6   |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| F   | ▿▾  | ↘   | →   | ↙   | ▾   | ↓   | ←   | ▿   |
| O   | ⬒   | ◩   | ◧   | ⬕   | ⬓   | ⬓   | ⬓   | ⬓   |
| L   | ▿▾  | ↘   | →   | ↙   | ▾   | ↓   | ←   | ▿   |

### Short Notation
For a non-table display the short notation can be used.
The short notation is defined in this order: 
1. Count
2. Leader movement
3. Orientation
4. Follower movement

Thus the above mentioned [[Saida Woman]] would be written like this:
```
▿▾⬒▿▾
1↘◩↘
2→◧→
3↙⬕↙
&▾⬓▾
4↓⬓↓
5←⬓←
6▿⬓▿
```

## Count
The count represents the dance's timing information.
Full counts are represented using the corresponding number, while half counts are either ommited when there is no information needed or displayed using the **&** sign.


## Movement
### Basics
#### Steps with weight change
- Apart from minor changes, the frames stays; facing the same direction as previously
- After the step is completed, the weight is on the just moved foot. 

| Sign | Unicode | Description                  |
| ---- | ------- | ---------------------------- |
| ↑    | U+2191  | north step                 |
| ←    | U+2190  | west step                    |
| →    | U+2192  | east step                   |
| ↓    | U+2193  | south step                |
| ↖    | U+2196  | north-west step   |
| ↗    | U+2197  | north-east step  |
| ↙    | U+2199  | south-west step  |
| ↘    | U+2198  | south-east step |

#### Steps without weight change
- the bar/ hook at the start of each arrow should symbolize that the weight stays in place

| Sign | Unicode | Description |
| ---- | ------- | ----------- |
| ↥    | U+21A5  |    non-weighted north step         |
| ↤    | U+21A4  |    non-weighted west step         |
| ↦    | U+21A6  |   non-weighted east step          |
| ↧    | U+21A7  |    non-weighted south step         |
| ⤣    | U+2923  |     non-weighted north-west step        |
| ⤤    | U+2924  |     non-weighted north-east step        |
| ⤦    | U+2926  |     non-weighted south-west step        |
| ⤥    | U+2925  |     non-weighted south-east step        |

#### Long Steps with weight change

| Sign | Unicode | Description        |
| ---- | ------- | ------------------ |
| ↟    | U+219F  | long north step  |
| ↞    | U+219E  | long west step     |
| ↠    | U+21A0  | long east step    |
| ↡    | U+21A1  | long south step |

#### Weight change, Lifting, Shifting
- The filled triangles always represent the weighted version of the non-filled triangles

| Sign | Unicode | Description                                   |
| ---- | ------- | --------------------------------------------- |
| ◈    | U+25C8  | Weight change in place                        |
| ▿    | U+25BF  | Tap or closing motion without a weight change |
| ▾    | U+25BE  | Closing motion with weight change             |
| ▵    | U+25B5  | Lifting                                       |
| ▴    | U+25B4  | Lifting signal (foot stays on the ground)     |
| ◃    | U+25C3  | Shift to the left                             |
| ◂    | U+25C2  | Shift to the left with weight change          |
| ▹    | U+25B9  | Shift to the right                            |
| ▸    | U+25B8  | Shift to the right with weight change         |

#### Turns, Pivots

| Sign | Unicode | Description     |
| ---- | ------- | --------------- |
| ◷    | U+25F7  | 90° right turn  |
| ◴    | U+25F4  | 90° left turn   |
| ◑    | U+25D1  | 180° right turn |
| ◐    | U+25D0  | 180° left turn  |
| ◶    | U+25F6  | 270° right turn |
| ◵    | U+25F5  | 270° left turn  |
| ⥁    | U+2941  | 360° right turn |
| ⥀    | U+2940  | 360° left turn  |

#### Tabs, Touches
- The Tap move consists of a step without a weight shift and the movement **back to the start position**

| Sign | Unicode | Description  |
| ---- | ------- | ------------ |
| ⤒    | U+2912  | north tap  |
| ⇤    | U+21E4  | west tap     |
| ⇥    | U+21E5  | east tap    |
| ⤓    | U+2913  | south tap |

### Advanced
#### Signals

| Sign | Unicode | Description |
| ---- | ------- | ----------- |
| ◇    | U+25C7  | Signal      |
| ◆    | U+25C6  | Block       |

#### Body Part Additions

| Sign | Unicode | Body Part   |
| ---- | ------- | ----------- |
| ₐ    | U+2090  | Arm         |
| ₕ    | U+2095  | Hand        |
| ₖ    | U+2096  | Knee        |
| ₗ    | U+2097  | Leg         |
| ₚ    | U+209A  | Pelvis/ Hip |
| ₛ    | U+209B  | Shoulder    |
| ₜ    | U+209C  | Thigh       |
| ₑ    | U+2091  | Elbow       |
| ᵦ    | U+1D66  | Base/ Foot  |

#### Additions

| Sign | Unicode | Description  |
| ---- | ------- | ------------ |
| ₓ    | U+2093  | cross behind |
|  ᪲    | U+1AB2  | hip rotation |

#### Hooks
- similar to [Tango Number 4](https://en.m.wikipedia.org/wiki/File:Homer2_tango_quatro.JPG )

| Sign | Unicode | Description |
| ---- | ------- | ----------- |
| ⥾    | U+297E  |             |
| ⥼    | U+297C  |             |
| ⥽    | U+297D  |             |
| ⥿    | U+297F  |             |

## Orientation
### Writing Order
1. Leader's [[Kizomba Notation/README#Weight Distribution|weight distribution]] (optional, only used in [[Positions]])
2. Leader's [[Kizomba Notation/README#Frame Foot|Frame + Foot]]
3. [[Kizomba Notation/README#Followers Positioning|Followers Positioning]]
4. Follower's [[Kizomba Notation/README#Frame Foot|Frame + Foot]]
5. Follower's [[Kizomba Notation/README#Weight Distribution|weight distribution]] (optional, only used in [[Positions]])

### Weight Distribution
- shown from the leader's perspective
- the weight distribution is only used in the beginning of a notation or while notating [[Positions]]

| Sign Combi | Description                  |
| ---------- | ---------------------------- |
| ▾▿         | Weight is on the left foot   |
| ▿▾         | Weight is on the right foot  |
| ▾▾         | Weight is equaly distributed |

### Followers Positioning
- describes the position of the follower in relation to the leader
- default orientation is toward the center like this means: ⬒=╿⬒╽, ◧=╾◧╼, ◨=╼◨╾, etc. 

| Sign | Unicode | Description        |
| ---- | ------- | ------------------ |
| ⬒    | U+2B12  | in front           |
| ◧    | U+25E7  | to the right       |
| ◨    | U+25E8  | to the left        |
| ⬓    | U+2B13  | behind             |
| ◩    | U+25E9  | to the front left  |
| ⬔    | U+2B14  | to the front right |
| ⬕    | U+2B15  | behind left        |
| ◪    | U+25EA  | behind right       |
### Frame + Foot
- in most use cases the following signs function as addition to other steps (eg. ↓┍, to move backward, foot facing backwards, frame to the previous right.) 
- For non straight line signs (eg. ┚), the bold part represents the frame, while the small part represents the foot

| Sign | Unicode | Frame    | Foot     | Previous Sign |
| ---- | ------- | -------- | -------- | ------------- |
| │    | U+2502  | same     | same     | necessary     |
| ╎    | U+254E  | opposite | opposite | necessary     |
| ╿    | U+257F  | ↑        | ↑        |               |
| ╽    | U+257D  | ↓        | ↓        |               |
| ╾    | U+257E  | ←        | ←        |               |
| ╼    | U+257C  | →        | →        |               |
| ┚    | U+251A  | ↑        | ←        |               |
| ┙    | U+2519  | ←        | ↑        |               |
| ┖    | U+2516  | ↑        | →        |               |
| ┕    | U+2515  | →        | ↑        |               |
| ┒    | U+2512  | ↓        | ←        |               |
| ┑    | U+2511  | ←        | ↓        |               |
| ┎    | U+250E  | ↓        | →        |               |
| ┍    | U+250D  | →        | ↓        |               |