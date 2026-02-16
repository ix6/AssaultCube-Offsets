**Assault Cube Version  1.3.0.2**  `With IDA PRO and CE`

````
Base Adress = "ac_client.exe"
LocalPlayer = "ac_client.exe" + 0x017E0A8
EntityList = "ac_client.exe"+0x018AC04  ; EC +  0x4, 0x4, 0x2
FOV = "ac_client.exe"+18A7CC

GiveAdmin = 0x200  ; 2 = Admin
PlayerHealth = 0xEC
PlayerArmour = 0xF0
PlayerName =  0x204
Score = 0x476

AngleX = 0x34
AngleY = 0x38
AngleZ= 0x3C
PositonX = 0x2C
PositionY = 0x28
PositionZ = 0x30

AssaultRifle
Ammo = 0x140
FireRate : 0x164

Pistol
Ammo = 0x12C
FireRate= 0x150 

Sniper 
Ammo = 0x13C
FireRate = 0x160

SMG
Ammo= 0x138
FireRate= 15C

Shotgun 
Ammo = 0x134
FireRate = 0x158

Carbine
Ammo= 0x130
FireRate= 0x154

Knife
FireRate= 0x14C

