# Leikjaforritun

### Verkefni 1

#### 1. Game loop er það sem er alltaf að keyra. Allur leikurinn keyrir á einni lykkju sem sér um alla útreikninga eins og position update, collision detection, virkni eða viðbrögð þegar hlutur gerir eitthvað ákveðið og uppfærir allt og renderar content.

#### 2. Útskýrðuð hvernig hægt er að fá hreyfingu (e. movement) á hlut með notkun e. velocity,
position ogsfrv. Notaðu kóða, stærðfræði (vigrar og stefnur) og aðrar leiðir til
útskýringar
þegar spilandi ýtir á einhvern takka hækkar velocity-ið á hlutinum og position breytist svo samkvæmt hraðanum.

acceleration = force / mass
change in position = velocity * dt
change in velocity = acceleration * dt
x_position += x_velocity
y_position += y_velocity

#### 3. Útskýrðu hvernig árekstur (e. collision detection) gæti verið útfærður í leik með
sýnidæmi (kóði, skýringamynd, stærðfræði osfrv.). (

if y_position > 460 or y_position < 0:  # top - bottom check
        y_velocity = 0
    if x_position > 620 or x_position < 0:  # left - right check
        x_velocity = 0

#### 4. Leikur (4%)
