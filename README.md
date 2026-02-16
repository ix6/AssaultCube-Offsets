**Assault Cube Version  1.3.0.2**



````
Base Adress = ac_client.exe
LocalPlayer = ac_client.exe + 0x0017E0A8
EntityList = "ac_client.exe"+0018AC04    ; EC + offsets per 4, 4, 2
FOV = ac_client.exe+18A7CC ; (Float) 160 recommended

GiveAdmin = 0x200   ;  4Bytes 2= Admin
PlayerHealth = 0xEC
PlayerArmour = 0xF0
PlayerName =  0x204

Score = 0x476

PositonX = 0x2C
PositionY = 0x28
PositionZ = 0x30

Pistol
Ammo = 0x12C
FireRate= 0x150 

Sniper 
Ammo = 0x13C
FireRate = 0x160

AssaultRifle
Ammo = 0x140
FireRate : 0x164

