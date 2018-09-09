# Leikjaforritun

### Verkefni 1

#### 1. Allur leikurinn keyrir á einni lykkju sem er kölluð Game loop, Game loop sér um alla útreikninga eins og position, velocity, collision detection, virkni eða viðbrögð þegar hlutur gerir eitthvað ákveðið og uppfærir og renderar allt contentið.

#### 2. Þegar spilandi ýtir á einhvern takka hækkar hraðinn á hlutinum og position breytist svo samkvæmt hraðanum.
```javascript
    if (cursors.left.isDown){
        player.setVelocityX(-160);
    }
    else if (cursors.right.isDown){
        player.setVelocityX(160);
    }
    else{
        player.setVelocityX(0);
    }
    if (cursors.up.isDown && player.body.touching.down){
        player.setVelocityY(-330);
    }
```

#### 3. Ef hluti af playerinum snertir annan hlut á skjánum er hraðinn lækkaður í 0 í þá átt sem hluturinn er svo hann getur ekki fært sig inn í hlutin.
```javascript
    if (player_bottom_y_position > object_bottom_y_position || player_top_y_position < object_top_y_position){
        y_velocity = 0
    }
    if (player_bottom_x_position > object_bottom_x_position || player_top_x_position < object_top_x_position){
        x_velocity = 0
    }
```
#### 4. Leikur (kóði er á github)
http://youtu.be/cIiKWiwpYQc?hd=1
