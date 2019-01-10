# ZGame

## Resource game
Là phần input cơ bản của mỗi game

- Story

- Dialogue Writers

- Concept art
	- Character
	- Npc

- Art 3d
	- Static
		- Filler
		- Interior
		- Exterior
	- Dynamic
		- Human
			- Npc
			- Character
		- Pet
		- Filler with animation & effect
	- High level
		- Environment

- Icon game
	- Ui
	- Item
	- Dictionary

## Game Mechanics Model
Là phần mà kết hợp rời rạc giữa Design Writers và Design Mechanics

### 1. Map & Interior
- Terrain, filler, doom, effect cho map city.
- Exterior

### 2. Script

#### 2.1 Conversation

##### 2.1.1 Chat

##### 2.1.1 Choice
- List
- Grid
- Drag /drop

#### 2.1 Character
- Reward items
- Request move to
- Request move by

#### 2.3 NPC
- Appear /disappeared
- Request move to
- Request move by
- Follow Character

### 3. Parameter ofcharacter

### 4. Property (asset) of character:
- Item
```
Gây ảnh hưởng lên các Parameter character. (Ex: tăng tiền, tăng năng lượng)
```
- Business ( sinh ra Property)
- Costumes
- Pet

## Mission/ Level Editor
Kết nối các phần Mechanics Model lại và Art để show cho End user

### 1. Map
- Build map layout cho map city
- Create Quest ( assign NPC - Script)
- Create Business ( assign Exterior - Interior - input /output Item)

### 2. Ui-Dialog
- Conversation chat, choice ( group, grid, drag- drop)
- Shop
- Gacha
- Crafting
- Business

### 3. Minigame
- Drag drop game ( using Dictionary + Choise by Drag- drop Item)
- Food game ( using Conversation Script - Action npc)


## Todo (Short-term)

### Art
Update later

### Design
Update later

### Programmer
```
- Diễn cảnh nói chuyện giữa NPC & Character ( Bao gồm cắt cảnh, cử chỉ tay chân, mắt, miệng)
- Diễn cảnh kể chuyện Story
- Chuyển cảnh move to Map, Interior
```
```
- Action npc - follow nhân vật
- Action npc - move by
```
```
- Choise by Drag- drop Item
- Choise by Grid
```
```
- Thay các từ định danh trong game ( tên Learner, tên NPC, giá tiền)
- Highlight teaching points (giống như từ điển, câu nào có từ nằm trong từ điển đó thì sẽ đc đánh dấu và click vào sẽ pop up nghĩa lên)
- Đổi font chữ
```
```
- Add pet + ani ingame
```
```
- Build Package editor ( 1 Package chứa input /output nhiều Property, sử dụng cho Shop, Gacha, Crafting).
- Build input /output cho Business ( tài nguyên cần, tài nguyên được sinh ra )
- Dictionary ( từ điển: từ, định nghĩa, hình ảnh)
```

## Note

- Flow Art 3d
```
Concept -> dựng xương -> tách khối ( chia patch) -> phủ màu ( texture) -> hiệu ứng ( shader)
```

- Flow Ui
```
Chức năng + icon + hệ màu -> ux -> ui
```
