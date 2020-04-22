# Minecraft Snippets

## Light Grid Orientation

Matches up with the player tracking grid in the construct.

|-Z 🠕||||||||||||||||||
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|11|8|[•](#a8)|[•](#b8)|[•](#c8)|[•](#d8)|[•](#e8)|[•](#f8)|[•](#g8)|[•](#h8)|[•](#i8)|[•](#j8)|[•](#k8)|[•](#l8)|[•](#m8)|[•](#n8)|[•](#o8)|[•](#p8)|
|10|7|[•](#a7)|[•](#b7)|[•](#c7)|[•](#d7)|[•](#e7)|[•](#f7)|[•](#g7)|[•](#h7)|[•](#i7)|[•](#j7)|[•](#k7)|[•](#l7)|[•](#m7)|[•](#n7)|[•](#o7)|[•](#p7)|
|9 |6|[•](#a6)|[•](#b6)|[•](#c6)|[•](#d6)|[•](#e6)|[•](#f6)|[•](#g6)|[•](#h6)|[•](#i6)|[•](#j6)|[•](#k6)|[•](#l6)|[•](#m6)|[•](#n6)|[•](#o6)|[•](#p6)|
|8 |5|[•](#a5)|[•](#b5)|[•](#c5)|[•](#d5)|[•](#e5)|[•](#f5)|[•](#g5)|[•](#h5)|[•](#i5)|[•](#j5)|[•](#k5)|[•](#l5)|[•](#m5)|[•](#n5)|[•](#o5)|[•](#p5)|
|7 |4|[•](#a4)|[•](#b4)|[•](#c4)|[•](#d4)|[•](#e4)|[•](#f4)|[•](#g4)|[•](#h4)|[•](#i4)|[•](#j4)|[•](#k4)|[•](#l4)|[•](#m4)|[•](#n4)|[•](#o4)|[•](#p4)|
|6 |3|[•](#a3)|[•](#b3)|[•](#c3)|[•](#d3)|[•](#e3)|[•](#f3)|[•](#g3)|[•](#h3)|[•](#i3)|[•](#j3)|[•](#k3)|[•](#l3)|[•](#m3)|[•](#n3)|[•](#o3)|[•](#p3)|
|5 |2|[•](#a2)|[•](#b2)|[•](#c2)|[•](#d2)|[•](#e2)|[•](#f2)|[•](#g2)|[•](#h2)|[•](#i2)|[•](#j2)|[•](#k2)|[•](#l2)|[•](#m2)|[•](#n2)|[•](#o2)|[•](#p2)|
|4 |1|[•](#a1)|[•](#b1)|[•](#c1)|[•](#d1)|[•](#e1)|[•](#f1)|[•](#g1)|[•](#h1)|[•](#i1)|[•](#j1)|[•](#k1)|[•](#l1)|[•](#m1)|[•](#n1)|[•](#o1)|[•](#p1)|
|  | |A|B|C|D|E|F|G|H|I|J|K|L|M|N|O|P|
|  |+X 🠖|16|17|18|19|20|21|22|23|24|25|26|27|28|29|30|31|

----

Formatting for the command block pairs.

Block setting: Repeat | Unconditional | Always Active

<h3 name="a1">A1:</h3>

    execute as @p[x=0,y=65,z=0,dx=48,dy=65,dz=-33] run setblock 16 4 -3 minecraft:redstone_block
    execute unless entity @p[x=0,y=65,z=0,dx=48,dy=65,dz=-33] run setblock 16 4 -3 minecraft:air

<h3 name="a2">A2:</h3>

    execute as @p[x=0,y=65,z=-34,dx=48,dy=65,dz=-33] run setblock 16 5 -3 minecraft:redstone_block
    execute unless entity @p[x=0,y=65,z=-34,dx=48,dy=65,dz=-33] run setblock 16 5 -3 minecraft:air

<h3 name="a3">A3:</h3>

    execute as @p[x=0,y=65,z=-67,dx=48,dy=65,dz=-33] run setblock 16 6 -3 minecraft:redstone_block
    execute unless entity @p[x=0,y=65,z=-67,dx=48,dy=65,dz=-33] run setblock 16 6 -3 minecraft:air

<h3 name="a4">A4:</h3>

    execute as @p[x=0,y=65,z=-100,dx=48,dy=65,dz=-33] run setblock 16 7 -3 minecraft:redstone_block
    execute unless entity @p[x=0,y=65,z=-100,dx=48,dy=65,dz=-33] run setblock 16 7 -3 minecraft:air

<h3 name="a5">A5:</h3>

    execute as @p[x=0,y=65,z=-133,dx=48,dy=65,dz=-33] run setblock 16 8 -3 minecraft:redstone_block
    execute unless entity @p[x=0,y=65,z=-133,dx=48,dy=65,dz=-33] run setblock 16 8 -3 minecraft:air

<h3 name="a6">A6:</h3>

    execute as @p[x=0,y=65,z=-166,dx=48,dy=65,dz=-33] run setblock 16 9 -3 minecraft:redstone_block
    execute unless entity @p[x=0,y=65,z=-166,dx=48,dy=65,dz=-33] run setblock 16 9 -3 minecraft:air

<h3 name="a7">A7:</h3>

    execute as @p[x=0,y=65,z=-199,dx=48,dy=65,dz=-33] run setblock 16 10 -3 minecraft:redstone_block
    execute unless entity @p[x=0,y=65,z=-199,dx=48,dy=65,dz=-33] run setblock 16 10 -3 minecraft:air

<h3 name="a8">A8:</h3>

    execute as @p[x=0,y=65,z=-232,dx=48,dy=65,dz=-33] run setblock 16 11 -3 minecraft:redstone_block
    execute unless entity @p[x=0,y=65,z=-232,dx=48,dy=65,dz=-33] run setblock 16 11 -3 minecraft:air

----

<h3 name="b1">B1:</h3>

    execute as @p[x=48,y=65,z=0,dx=48,dy=65,dz=-33] run setblock 17 4 -3 minecraft:redstone_block
    execute unless entity @p[x=48,y=65,z=0,dx=48,dy=65,dz=-33] run setblock 17 4 -3 minecraft:air

<h3 name="b2">B2:</h3>

    execute as @p[x=48,y=65,z=-34,dx=48,dy=65,dz=-33] run setblock 17 5 -3 minecraft:redstone_block
    execute unless entity @p[x=48,y=65,z=-34,dx=48,dy=65,dz=-33] run setblock 17 5 -3 minecraft:air

<h3 name="b3">B3:</h3>

    execute as @p[x=48,y=65,z=-67,dx=48,dy=65,dz=-33] run setblock 17 6 -3 minecraft:redstone_block
    execute unless entity @p[x=48,y=65,z=-67,dx=48,dy=65,dz=-33] run setblock 17 6 -3 minecraft:air

<h3 name="b4">B4:</h3>

    execute as @p[x=48,y=65,z=-100,dx=48,dy=65,dz=-33] run setblock 17 7 -3 minecraft:redstone_block
    execute unless entity @p[x=48,y=65,z=-100,dx=48,dy=65,dz=-33] run setblock 17 7 -3 minecraft:air

<h3 name="b5">B5:</h3>

    execute as @p[x=48,y=65,z=-133,dx=48,dy=65,dz=-33] run setblock 17 8 -3 minecraft:redstone_block
    execute unless entity @p[x=48,y=65,z=-133,dx=48,dy=65,dz=-33] run setblock 17 8 -3 minecraft:air

<h3 name="b6">B6:</h3>

    execute as @p[x=48,y=65,z=-166,dx=48,dy=65,dz=-33] run setblock 17 9 -3 minecraft:redstone_block
    execute unless entity @p[x=48,y=65,z=-166,dx=48,dy=65,dz=-33] run setblock 17 9 -3 minecraft:air

<h3 name="b7">B7:</h3>

    execute as @p[x=48,y=65,z=-199,dx=48,dy=65,dz=-33] run setblock 17 10 -3 minecraft:redstone_block
    execute unless entity @p[x=48,y=65,z=-199,dx=48,dy=65,dz=-33] run setblock 17 10 -3 minecraft:air

<h3 name="b8">B8:</h3>

    execute as @p[x=48,y=65,z=-232,dx=48,dy=65,dz=-33] run setblock 17 11 -3 minecraft:redstone_block
    execute unless entity @p[x=48,y=65,z=-232,dx=48,dy=65,dz=-33] run setblock 17 11 -3 minecraft:air

----

<h3 name="c1">C1:</h3>

    execute as @p[x=96,y=65,z=0,dx=48,dy=65,dz=-33] run setblock 18 4 -3 minecraft:redstone_block
    execute unless entity @p[x=96,y=65,z=0,dx=48,dy=65,dz=-33] run setblock 18 4 -3 minecraft:air

<h3 name="c2">C2:</h3>

    execute as @p[x=96,y=65,z=-34,dx=48,dy=65,dz=-33] run setblock 18 5 -3 minecraft:redstone_block
    execute unless entity @p[x=96,y=65,z=-34,dx=48,dy=65,dz=-33] run setblock 18 5 -3 minecraft:air

<h3 name="c3">C3:</h3>

    execute as @p[x=96,y=65,z=-67,dx=48,dy=65,dz=-33] run setblock 18 6 -3 minecraft:redstone_block
    execute unless entity @p[x=96,y=65,z=-67,dx=48,dy=65,dz=-33] run setblock 18 6 -3 minecraft:air

<h3 name="c4">C4:</h3>

    execute as @p[x=96,y=65,z=-100,dx=48,dy=65,dz=-33] run setblock 18 7 -3 minecraft:redstone_block
    execute unless entity @p[x=96,y=65,z=-100,dx=48,dy=65,dz=-33] run setblock 18 7 -3 minecraft:air

<h3 name="c5">C5:</h3>

    execute as @p[x=96,y=65,z=-133,dx=48,dy=65,dz=-33] run setblock 18 8 -3 minecraft:redstone_block
    execute unless entity @p[x=96,y=65,z=-133,dx=48,dy=65,dz=-33] run setblock 18 8 -3 minecraft:air

<h3 name="c6">C6:</h3>

    execute as @p[x=96,y=65,z=-166,dx=48,dy=65,dz=-33] run setblock 18 9 -3 minecraft:redstone_block
    execute unless entity @p[x=96,y=65,z=-166,dx=48,dy=65,dz=-33] run setblock 18 9 -3 minecraft:air

<h3 name="c7">C7:</h3>

    execute as @p[x=96,y=65,z=-199,dx=48,dy=65,dz=-33] run setblock 18 10 -3 minecraft:redstone_block
    execute unless entity @p[x=96,y=65,z=-199,dx=48,dy=65,dz=-33] run setblock 18 10 -3 minecraft:air

<h3 name="c8">C8:</h3>

    execute as @p[x=96,y=65,z=-232,dx=48,dy=65,dz=-33] run setblock 18 11 -3 minecraft:redstone_block
    execute unless entity @p[x=96,y=65,z=-232,dx=48,dy=65,dz=-33] run setblock 18 11 -3 minecraft:air