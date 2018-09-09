# Leikjaforritun

### Verkefni 1

#### 1. Allur leikurinn keyrir á einni lykkju sem er kölluð Game loop, Game loop sér um alla útreikninga eins og position, velocity, collision detection, virkni eða viðbrögð þegar hlutur gerir eitthvað ákveðið og uppfærir og renderar allt contentið.

#### 2. þegar spilandi ýtir á einhvern takka hækkar hraðinn á hlutinum og position breytist svo samkvæmt hraðanum.

acceleration = force / mass
change in position = velocity * dt
change in velocity = acceleration * dt
x_position += x_velocity
y_position += y_velocity

#### 3. Ef hluti af playerinum snertir annan hlut á skjánum er hraðinn lækkaður í 0 í þá átt sem hluturinn er svo hann getur ekki fært sig inn í hlutin.
sýnidæmi (kóði, skýringamynd, stærðfræði osfrv.). (

ef hluti af playerinum reynir að komast útaf skjánum er hraðinn lækkaður í 0 svo hann getur ekki fært sig lengra í þá átt þar sem er veggur

if y_position > 460 or y_position < 0:  # top - bottom check
        y_velocity = 0
    if x_position > 620 or x_position < 0:  # left - right check
        x_velocity = 0

#### 4. Leikur (4%)
