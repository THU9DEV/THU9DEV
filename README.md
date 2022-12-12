Lua version: 5.3
EnBi = "L4448" (endianness and bitness of this bytecode)
  Endianness          = L (little-endian)
  Size of C int       = 4
  Size of C pointer   = 4
  Size of Lua integer = 4
  Size of Lua float   = 8
Debug info: included

************ Main Function
Source: Lua script in the left pane
Parameters: 0
Is vararg: yes
VM registers needed: 6
Constants: 49
  +01F3:Size=4: 67 61 6D 65                     Const#1   string    "game"
  +01F9:Size=7: 50 6C 61 63 65 49 64            Const#2   string    "PlaceId"
  +0201:Size=8: 00 00 A0 53 AD 84 E4 41         Const#3   float     2753915549.0
  +020B:Size=1: 57                              Const#4   string    "W"
  +020D:Size=1: 01                              Const#5   boolean   true
  +020F:Size=8: 00 00 70 1B 7B 8C F0 41         Const#6   float     4442272183.0
  +0219:Size=2: 57 32                           Const#7   string    "W2"
  +021C:Size=8: 00 00 30 F1 52 C0 FB 41         Const#8   float     7449423635.0
  +0226:Size=2: 57 33                           Const#9   string    "W3"
  +022A:Size=A: 43 68 65 63 6B 51 75 65 73 74   Const#10  string    "CheckQuest"
  +0236:Size=3: 48 6F 70                        Const#11  string    "Hop"
  +023B:Size=5: 69 73 6E 69 6C                  Const#12  string    "isnil"
  +0242:Size=6: 4E 75 6D 62 65 72               Const#13  string    "Number"
  +024A:Size=4: 6D 61 74 68                     Const#14  string    "math"
  +0250:Size=6: 72 61 6E 64 6F 6D               Const#15  string    "random"
  +0257:Size=4: 01 00 00 00                     Const#16  integer   1
  +025C:Size=4: 40 42 0F 00                     Const#17  integer   1000000
  +0262:Size=F: 55 70 64 61 74 65 45 73 70...   Const#18  string    "UpdateEspPlayer"
  +0273:Size=F: 55 70 64 61 74 65 49 73 6C...   Const#19  string    "UpdateIslandESP"
  +0284:Size=E: 55 70 64 61 74 65 43 68 65...   Const#20  string    "UpdateChestEsp"
  +0294:Size=B: 55 70 64 61 74 65 42 66 45...   Const#21  string    "UpdateBfEsp"
  +02A1:Size=F: 55 70 64 61 74 65 46 6C 6F...   Const#22  string    "UpdateFlowerEsp"
  +02B2:Size=5: 49 6E 66 41 62                  Const#23  string    "InfAb"
  +02B9:Size=4: 67 61 6D 65                     Const#24  string    "game"
  +02BF:Size=A: 47 65 74 53 65 72 76 69 63 65   Const#25  string    "GetService"
  +02CB:Size=7: 50 6C 61 79 65 72 73            Const#26  string    "Players"
  +02D4:Size=B: 4C 6F 63 61 6C 50 6C 61 79...   Const#27  string    "LocalPlayer"
  +02E1:Size=9: 43 68 61 72 61 63 74 65 72      Const#28  string    "Character"
  +02EC:Size=6: 45 6E 65 72 67 79               Const#29  string    "Energy"
  +02F4:Size=5: 56 61 6C 75 65                  Const#30  string    "Value"
  +02FB:Size=C: 69 6E 66 69 6E 69 74 65 73...   Const#31  string    "infinitestam"
  +0309:Size=5: 73 70 61 77 6E                  Const#32  string    "spawn"
  +0310:Size=B: 4E 6F 44 6F 64 67 65 43 6F...   Const#33  string    "NoDodgeCool"
  +031D:Size=3: 66 6C 79                        Const#34  string    "fly"
  +0322:Size=5: 43 6C 69 63 6B                  Const#35  string    "Click"
  +0329:Size=8: 41 75 74 6F 48 61 6B 69         Const#36  string    "AutoHaki"
  +0333:Size=D: 55 6E 45 71 75 69 70 57 65...   Const#37  string    "UnEquipWeapon"
  +0342:Size=B: 45 71 75 69 70 57 65 61 70...   Const#38  string    "EquipWeapon"
  +034F:Size=5: 74 6F 70 6F 73                  Const#39  string    "topos"
  +0356:Size=B: 47 65 74 44 69 73 74 61 6E...   Const#40  string    "GetDistance"
  +0363:Size=3: 54 50 31                        Const#41  string    "TP1"
  +0368:Size=2: 54 50                           Const#42  string    "TP"
  +036C:Size=9: 53 74 6F 70 54 77 65 65 6E      Const#43  string    "StopTween"
  +0377:Size=4: 67 61 6D 65                     Const#44  string    "game"
  +037D:Size=A: 47 65 74 53 65 72 76 69 63 65   Const#45  string    "GetService"
  +0389:Size=7: 50 6C 61 79 65 72 73            Const#46  string    "Players"
  +0392:Size=B: 4C 6F 63 61 6C 50 6C 61 79...   Const#47  string    "LocalPlayer"
  +039F:Size=5: 49 64 6C 65 64                  Const#48  string    "Idled"
  +03A6:Size=7: 63 6F 6E 6E 65 63 74            Const#49  string    "connect"
Upvalues: 1
  Upv#1 is parent function's R0                 name: _ENV
Locals: 3
  Local#1   R0   def:<24>   scope:<25..105>     name: round
  Local#2   R1   def:<47>   scope:<48..105>     name: LocalPlayer
  Local#3   R2   def:<50>   scope:<51..105>     name: originalstam
Instructions: 105
  +0049: 06 00 40 00   line#1    GETTABUP 0 0 -1         <1>   R0 = Upv#1@_ENV["game"]                         -- It's Const#1
  +004D: 07 40 40 00   line#1    GETTABLE 0 0 -2         <2>   R0 = R0["PlaceId"]                              -- It's Const#2
  +0051: 1F 80 40 00   line#1    EQ 0 0 -3               <3>   if R0 == 2753915549.0 then GOTO <5>             -- It's Const#3
  +0055: 1E 40 00 80   line#1    JMP 0 2                 <4>   GOTO <7>
  +0059: 08 00 C1 81   line#2    SETTABUP 0 -4 -5        <5>   Upv#1@_ENV["W"] = true                          -- It's Const#4, Const#5
  +005D: 1E 80 02 80   line#2    JMP 0 11                <6>   GOTO <18>
  +0061: 06 00 40 00   line#3    GETTABUP 0 0 -1         <7>   R0 = Upv#1@_ENV["game"]                         -- It's Const#1
  +0065: 07 40 40 00   line#3    GETTABLE 0 0 -2         <8>   R0 = R0["PlaceId"]                              -- It's Const#2
  +0069: 1F 40 41 00   line#3    EQ 0 0 -6               <9>   if R0 == 4442272183.0 then GOTO <11>            -- It's Const#6
  +006D: 1E 40 00 80   line#3    JMP 0 2                <10>   GOTO <13>
  +0071: 08 00 41 83   line#4    SETTABUP 0 -7 -5       <11>   Upv#1@_ENV["W2"] = true                         -- It's Const#7, Const#5
  +0075: 1E 00 01 80   line#4    JMP 0 5                <12>   GOTO <18>
  +0079: 06 00 40 00   line#5    GETTABUP 0 0 -1        <13>   R0 = Upv#1@_ENV["game"]                         -- It's Const#1
  +007D: 07 40 40 00   line#5    GETTABLE 0 0 -2        <14>   R0 = R0["PlaceId"]                              -- It's Const#2
  +0081: 1F C0 41 00   line#5    EQ 0 0 -8              <15>   if R0 == 7449423635.0 then GOTO <17>            -- It's Const#8
  +0085: 1E 00 00 80   line#5    JMP 0 1                <16>   GOTO <18>
  +0089: 08 00 41 84   line#6    SETTABUP 0 -9 -5       <17>   Upv#1@_ENV["W3"] = true                         -- It's Const#9, Const#5
  +008D: 2C 00 00 00   line#547  CLOSURE 0 0            <18>   R0 = Function#1
  +0091: 08 00 80 84   line#9    SETTABUP 0 -10 0       <19>   Upv#1@_ENV["CheckQuest"] = R0                   -- It's Const#10
  +0095: 2C 40 00 00   line#609  CLOSURE 0 1            <20>   R0 = Function#2
  +0099: 08 00 00 85   line#549  SETTABUP 0 -11 0       <21>   Upv#1@_ENV["Hop"] = R0                          -- It's Const#11
  +009D: 2C 80 00 00   line#613  CLOSURE 0 2            <22>   R0 = Function#3
  +00A1: 08 00 80 85   line#611  SETTABUP 0 -12 0       <23>   Upv#1@_ENV["isnil"] = R0                        -- It's Const#12
  +00A5: 2C C0 00 00   line#616  CLOSURE 0 3            <24>   R0@round = Function#4
  +00A9: 46 40 43 00   line#617  GETTABUP 1 0 -14       <25>   R1 = Upv#1@_ENV["math"]                         -- It's Const#14
  +00AD: 47 80 C3 00   line#617  GETTABLE 1 1 -15       <26>   R1 = R1["random"]                               -- It's Const#15
  +00B1: 81 C0 03 00   line#617  LOADK 2 -16            <27>   R2 = 1                                          -- It's Const#16
  +00B5: C1 00 04 00   line#617  LOADK 3 -17            <28>   R3 = 1000000                                    -- It's Const#17
  +00B9: 64 80 80 01   line#617  CALL 1 3 2             <29>   R1 = R1(R2, R3)
  +00BD: 08 40 00 86   line#617  SETTABUP 0 -13 1       <30>   Upv#1@_ENV["Number"] = R1                       -- It's Const#13
  +00C1: 6C 00 01 00   line#655  CLOSURE 1 4            <31>   R1 = Function#5
  +00C5: 08 40 80 88   line#618  SETTABUP 0 -18 1       <32>   Upv#1@_ENV["UpdateEspPlayer"] = R1              -- It's Const#18
  +00C9: 6C 40 01 00   line#689  CLOSURE 1 5            <33>   R1 = Function#6
  +00CD: 08 40 00 89   line#657  SETTABUP 0 -19 1       <34>   Upv#1@_ENV["UpdateIslandESP"] = R1              -- It's Const#19
  +00D1: 6C 80 01 00   line#734  CLOSURE 1 6            <35>   R1 = Function#7
  +00D5: 08 40 80 89   line#691  SETTABUP 0 -20 1       <36>   Upv#1@_ENV["UpdateChestEsp"] = R1               -- It's Const#20
  +00D9: 6C C0 01 00   line#769  CLOSURE 1 7            <37>   R1 = Function#8
  +00DD: 08 40 00 8A   line#736  SETTABUP 0 -21 1       <38>   Upv#1@_ENV["UpdateBfEsp"] = R1                  -- It's Const#21
  +00E1: 6C 00 02 00   line#811  CLOSURE 1 8            <39>   R1 = Function#9
  +00E5: 08 40 80 8A   line#771  SETTABUP 0 -22 1       <40>   Upv#1@_ENV["UpdateFlowerEsp"] = R1              -- It's Const#22
  +00E9: 6C 40 02 00   line#848  CLOSURE 1 9            <41>   R1 = Function#10
  +00ED: 08 40 00 8B   line#813  SETTABUP 0 -23 1       <42>   Upv#1@_ENV["InfAb"] = R1                        -- It's Const#23
  +00F1: 46 C0 45 00   line#850  GETTABUP 1 0 -24       <43>   R1 = Upv#1@_ENV["game"]                         -- It's Const#24
  +00F5: 4C 00 C6 00   line#850  SELF 1 1 -25           <44>   R2 = R1;  R1 = R1["GetService"]                 -- It's Const#25   -- prepare for R1:GetService()
  +00F9: C1 40 06 00   line#850  LOADK 3 -26            <45>   R3 = "Players"                                  -- It's Const#26
  +00FD: 64 80 80 01   line#850  CALL 1 3 2             <46>   R1 = R1(R2, R3)
  +0101: 47 80 C6 00   line#850  GETTABLE 1 1 -27       <47>   R1@LocalPlayer = R1["LocalPlayer"]              -- It's Const#27
  +0105: 87 C0 C6 00   line#851  GETTABLE 2 1 -28       <48>   R2 = R1@LocalPlayer["Character"]                -- It's Const#28
  +0109: 87 00 47 01   line#851  GETTABLE 2 2 -29       <49>   R2 = R2["Energy"]                               -- It's Const#29
  +010D: 87 40 47 01   line#851  GETTABLE 2 2 -30       <50>   R2@originalstam = R2["Value"]                   -- It's Const#30
  +0111: EC 80 02 00   line#858  CLOSURE 3 10           <51>   R3 = Function#11
  +0115: 08 C0 00 8F   line#852  SETTABUP 0 -31 3       <52>   Upv#1@_ENV["infinitestam"] = R3                 -- It's Const#31
  +0119: C6 C0 47 00   line#860  GETTABUP 3 0 -32       <53>   R3 = Upv#1@_ENV["spawn"]                        -- It's Const#32
  +011D: 2C C1 02 00   line#870  CLOSURE 4 11           <54>   R4 = Function#12
  +0121: E4 40 00 01   line#860  CALL 3 2 1             <55>   R3(R4)
  +0125: EC 00 03 00   line#888  CLOSURE 3 12           <56>   R3 = Function#13
  +0129: 08 C0 00 90   line#872  SETTABUP 0 -33 3       <57>   Upv#1@_ENV["NoDodgeCool"] = R3                  -- It's Const#33
  +012D: EC 40 03 00   line#978  CLOSURE 3 13           <58>   R3 = Function#14
  +0131: 08 C0 80 90   line#890  SETTABUP 0 -34 3       <59>   Upv#1@_ENV["fly"] = R3                          -- It's Const#34
  +0135: EC 80 03 00   line#983  CLOSURE 3 14           <60>   R3 = Function#15
  +0139: 08 C0 00 91   line#980  SETTABUP 0 -35 3       <61>   Upv#1@_ENV["Click"] = R3                        -- It's Const#35
  +013D: EC C0 03 00   line#989  CLOSURE 3 15           <62>   R3 = Function#16
  +0141: 08 C0 80 91   line#985  SETTABUP 0 -36 3       <63>   Upv#1@_ENV["AutoHaki"] = R3                     -- It's Const#36
  +0145: EC 00 04 00   line#999  CLOSURE 3 16           <64>   R3 = Function#17
  +0149: 08 C0 00 92   line#991  SETTABUP 0 -37 3       <65>   Upv#1@_ENV["UnEquipWeapon"] = R3                -- It's Const#37
  +014D: EC 40 04 00   line#1009 CLOSURE 3 17           <66>   R3 = Function#18
  +0151: 08 C0 80 92   line#1001 SETTABUP 0 -38 3       <67>   Upv#1@_ENV["EquipWeapon"] = R3                  -- It's Const#38
  +0155: EC 80 04 00   line#1024 CLOSURE 3 18           <68>   R3 = Function#19
  +0159: 08 C0 00 93   line#1011 SETTABUP 0 -39 3       <69>   Upv#1@_ENV["topos"] = R3                        -- It's Const#39
  +015D: EC C0 04 00   line#1028 CLOSURE 3 19           <70>   R3 = Function#20
  +0161: 08 C0 80 93   line#1026 SETTABUP 0 -40 3       <71>   Upv#1@_ENV["GetDistance"] = R3                  -- It's Const#40
  +0165: EC 00 05 00   line#1046 CLOSURE 3 20           <72>   R3 = Function#21
  +0169: 08 C0 00 94   line#1030 SETTABUP 0 -41 3       <73>   Upv#1@_ENV["TP1"] = R3                          -- It's Const#41
  +016D: EC 40 05 00   line#1063 CLOSURE 3 21           <74>   R3 = Function#22
  +0171: 08 C0 80 94   line#1048 SETTABUP 0 -42 3       <75>   Upv#1@_ENV["TP"] = R3                           -- It's Const#42
  +0175: C6 C0 47 00   line#1065 GETTABUP 3 0 -32       <76>   R3 = Upv#1@_ENV["spawn"]                        -- It's Const#32
  +0179: 2C 81 05 00   line#1079 CLOSURE 4 22           <77>   R4 = Function#23
  +017D: E4 40 00 01   line#1065 CALL 3 2 1             <78>   R3(R4)
  +0181: C6 C0 47 00   line#1081 GETTABUP 3 0 -32       <79>   R3 = Upv#1@_ENV["spawn"]                        -- It's Const#32
  +0185: 2C C1 05 00   line#1093 CLOSURE 4 23           <80>   R4 = Function#24
  +0189: E4 40 00 01   line#1081 CALL 3 2 1             <81>   R3(R4)
  +018D: C6 C0 47 00   line#1095 GETTABUP 3 0 -32       <82>   R3 = Upv#1@_ENV["spawn"]                        -- It's Const#32
  +0191: 2C 01 06 00   line#1103 CLOSURE 4 24           <83>   R4 = Function#25
  +0195: E4 40 00 01   line#1095 CALL 3 2 1             <84>   R3(R4)
  +0199: EC 40 06 00   line#1117 CLOSURE 3 25           <85>   R3 = Function#26
  +019D: 08 C0 00 95   line#1105 SETTABUP 0 -43 3       <86>   Upv#1@_ENV["StopTween"] = R3                    -- It's Const#43
  +01A1: C6 C0 47 00   line#1119 GETTABUP 3 0 -32       <87>   R3 = Upv#1@_ENV["spawn"]                        -- It's Const#32
  +01A5: 2C 81 06 00   line#1131 CLOSURE 4 26           <88>   R4 = Function#27
  +01A9: E4 40 00 01   line#1119 CALL 3 2 1             <89>   R3(R4)
  +01AD: C6 C0 4A 00   line#1133 GETTABUP 3 0 -44       <90>   R3 = Upv#1@_ENV["game"]                         -- It's Const#44
  +01B1: CC 00 CB 01   line#1133 SELF 3 3 -45           <91>   R4 = R3;  R3 = R3["GetService"]                 -- It's Const#45   -- prepare for R3:GetService()
  +01B5: 41 41 0B 00   line#1133 LOADK 5 -46            <92>   R5 = "Players"                                  -- It's Const#46
  +01B9: E4 80 80 01   line#1133 CALL 3 3 2             <93>   R3 = R3(R4, R5)
  +01BD: C7 80 CB 01   line#1133 GETTABLE 3 3 -47       <94>   R3 = R3["LocalPlayer"]                          -- It's Const#47
  +01C1: C7 C0 CB 01   line#1133 GETTABLE 3 3 -48       <95>   R3 = R3["Idled"]                                -- It's Const#48
  +01C5: CC 00 CC 01   line#1133 SELF 3 3 -49           <96>   R4 = R3;  R3 = R3["connect"]                    -- It's Const#49   -- prepare for R3:connect()
  +01C9: 6C C1 06 00   line#1137 CLOSURE 5 27           <97>   R5 = Function#28
  +01CD: E4 40 80 01   line#1133 CALL 3 3 1             <98>   R3(R4, R5)
  +01D1: C6 C0 47 00   line#1138 GETTABUP 3 0 -32       <99>   R3 = Upv#1@_ENV["spawn"]                        -- It's Const#32
  +01D5: 2C 01 07 00   line#1203 CLOSURE 4 28          <100>   R4 = Function#29
  +01D9: E4 40 00 01   line#1138 CALL 3 2 1            <101>   R3(R4)
  +01DD: C6 C0 47 00   line#1204 GETTABUP 3 0 -32      <102>   R3 = Upv#1@_ENV["spawn"]                        -- It's Const#32
  +01E1: 2C 41 07 00   line#1235 CLOSURE 4 29          <103>   R4 = Function#30
  +01E5: E4 40 00 01   line#1204 CALL 3 2 1            <104>   R3(R4)
  +01E9: 26 00 80 00   line#1235 RETURN 0 1            <105>   RETURN
Functions: 30

	************ Function#1   (full path: main.1)
	Source line#: 9..547
	Parameters: 0
	Is vararg: no
	VM registers needed: 13
	Constants: 616
	  +29DD:Size=5: 4C 65 76 65 6C                  Const#1   string    "Level"
	  +29E4:Size=4: 67 61 6D 65                     Const#2   string    "game"
	  +29EA:Size=A: 47 65 74 53 65 72 76 69 63 65   Const#3   string    "GetService"
	  +29F6:Size=7: 50 6C 61 79 65 72 73            Const#4   string    "Players"
	  +29FF:Size=B: 4C 6F 63 61 6C 50 6C 61 79...   Const#5   string    "LocalPlayer"
	  +2A0C:Size=4: 44 61 74 61                     Const#6   string    "Data"
	  +2A12:Size=5: 56 61 6C 75 65                  Const#7   string    "Value"
	  +2A19:Size=1: 57                              Const#8   string    "W"
	  +2A1B:Size=4: 01 00 00 00                     Const#9   integer   1
	  +2A20:Size=4: 09 00 00 00                     Const#10  integer   9
	  +2A26:Size=3: 4D 6F 6E                        Const#11  string    "Mon"
	  +2A2B:Size=E: 42 61 6E 64 69 74 20 5B 4C...   Const#12  string    "Bandit [Lv. 5]"
	  +2A3B:Size=6: 4C 51 75 65 73 74               Const#13  string    "LQuest"
	  +2A43:Size=6: 4E 51 75 65 73 74               Const#14  string    "NQuest"
	  +2A4B:Size=C: 42 61 6E 64 69 74 51 75 65...   Const#15  string    "BanditQuest1"
	  +2A59:Size=7: 4E 61 6D 65 4D 6F 6E            Const#16  string    "NameMon"
	  +2A62:Size=6: 42 61 6E 64 69 74               Const#17  string    "Bandit"
	  +2A6A:Size=B: 43 46 72 61 6D 65 51 75 65...   Const#18  string    "CFrameQuest"
	  +2A77:Size=6: 43 46 72 61 6D 65               Const#19  string    "CFrame"
	  +2A7F:Size=3: 6E 65 77                        Const#20  string    "new"
	  +2A83:Size=8: FD F6 75 E0 7C 8D 90 40         Const#21  float     1059.37195
	  +2A8C:Size=8: C3 A8 5A C1 25 E6 2E 40         Const#22  float     15.4495068
	  +2A95:Size=8: C0 5B 20 41 B1 39 98 40         Const#23  float     1550.4231
	  +2A9E:Size=8: D9 6D 10 E0 06 12 EE 3F         Const#24  float     0.939700544
	  +2AA7:Size=4: 00 00 00 00                     Const#25  integer   0
	  +2AAC:Size=8: 56 FB 88 20 4D E3 D5 BF         Const#26  float     -0.341998369
	  +2AB5:Size=8: 56 FB 88 20 4D E3 D5 3F         Const#27  float     0.341998369
	  +2ABE:Size=4: 0A 00 00 00                     Const#28  integer   10
	  +2AC3:Size=4: 0E 00 00 00                     Const#29  integer   14
	  +2AC9:Size=F: 4D 6F 6E 6B 65 79 20 5B 4C...   Const#30  string    "Monkey [Lv. 14]"
	  +2ADA:Size=B: 4A 75 6E 67 6C 65 51 75 65...   Const#31  string    "JungleQuest"
	  +2AE7:Size=6: 4D 6F 6E 6B 65 79               Const#32  string    "Monkey"
	  +2AEE:Size=8: FC DE A6 3F 5B F8 98 C0         Const#33  float     -1598.08911
	  +2AF7:Size=8: 88 BA 0F 40 6A C6 41 40         Const#34  float     35.5501175
	  +2B00:Size=8: F4 A5 B7 3F 17 2C 63 40         Const#35  float     153.377838
	  +2B09:Size=4: FF FF FF FF                     Const#36  integer   -1
	  +2B0E:Size=4: 0F 00 00 00                     Const#37  integer   15
	  +2B13:Size=4: 18 00 00 00                     Const#38  integer   24
	  +2B19:Size=10: 47 6F 72 69 6C 6C 61 20 5...   Const#39  string    "Gorilla [Lv. 20]"
	  +2B2A:Size=4: 02 00 00 00                     Const#40  integer   2
	  +2B30:Size=7: 47 6F 72 69 6C 6C 61            Const#41  string    "Gorilla"
	  +2B38:Size=4: 19 00 00 00                     Const#42  integer   25
	  +2B3D:Size=4: 3B 00 00 00                     Const#43  integer   59
	  +2B43:Size=2: 5F 47                           Const#44  string    "_G"
	  +2B47:Size=4: 48 4F 4F 4B                     Const#45  string    "HOOK"
	  +2B4D:Size=5: 70 63 61 6C 6C                  Const#46  string    "pcall"
	  +2B53:Size=4: 3C 00 00 00                     Const#47  integer   60
	  +2B58:Size=4: 63 00 00 00                     Const#48  integer   99
	  +2B5E:Size=2: 5F 47                           Const#49  string    "_G"
	  +2B62:Size=4: 4B 4F 4F 4B                     Const#50  string    "KOOK"
	  +2B67:Size=4: 64 00 00 00                     Const#51  integer   100
	  +2B6C:Size=4: 77 00 00 00                     Const#52  integer   119
	  +2B72:Size=11: 53 6E 6F 77 6D 61 6E 20 5...   Const#53  string    "Snowman [Lv. 100]"
	  +2B84:Size=4: 02 00 00 00                     Const#54  integer   2
	  +2B8A:Size=9: 53 6E 6F 77 51 75 65 73 74      Const#55  string    "SnowQuest"
	  +2B95:Size=7: 53 6E 6F 77 6D 61 6E            Const#56  string    "Snowman"
	  +2B9E:Size=6: 43 46 72 61 6D 65               Const#57  string    "CFrame"
	  +2BA6:Size=3: 6E 65 77                        Const#58  string    "new"
	  +2BAA:Size=8: 2E 56 D4 60 FA B6 95 40         Const#59  float     1389.74451
	  +2BB3:Size=8: 3C 0E 28 40 B9 09 56 40         Const#60  float     88.1519318
	  +2BBC:Size=8: 4E 28 44 C0 A1 4B 94 C0         Const#61  float     -1298.90796
	  +2BC5:Size=8: 50 4E 7A 00 07 E4 D5 BF         Const#62  float     -0.342042685
	  +2BCE:Size=4: 00 00 00 00                     Const#63  integer   0
	  +2BD3:Size=8: 7F 03 FD FF E4 11 EE 3F         Const#64  float     0.939684391
	  +2BDC:Size=8: 7F 03 FD FF E4 11 EE BF         Const#65  float     -0.939684391
	  +2BE5:Size=4: 78 00 00 00                     Const#66  integer   120
	  +2BEA:Size=4: 95 00 00 00                     Const#67  integer   149
	  +2BF0:Size=1D: 43 68 69 65 66 20 50 65 7...   Const#68  string    "Chief Petty Officer [Lv. 120]"
	  +2C0F:Size=C: 4D 61 72 69 6E 65 51 75 65...   Const#69  string    "MarineQuest2"
	  +2C1D:Size=13: 43 68 69 65 66 20 50 65 7...   Const#70  string    "Chief Petty Officer"
	  +2C31:Size=8: 65 C7 46 20 96 AF B3 C0         Const#71  float     -5039.58643
	  +2C3A:Size=8: 45 D7 85 1F 9C 59 3B 40         Const#72  float     27.3500385
	  +2C43:Size=8: 65 C7 46 20 AE E4 B0 40         Const#73  float     4324.68018
	  +2C4C:Size=4: 96 00 00 00                     Const#74  integer   150
	  +2C51:Size=4: AE 00 00 00                     Const#75  integer   174
	  +2C57:Size=14: 53 6B 79 20 42 61 6E 64 6...   Const#76  string    "Sky Bandit [Lv. 150]"
	  +2C6D:Size=8: 53 6B 79 51 75 65 73 74         Const#77  string    "SkyQuest"
	  +2C77:Size=A: 53 6B 79 20 42 61 6E 64 69 74   Const#78  string    "Sky Bandit"
	  +2C82:Size=8: 0D 54 C6 BF 87 E7 B2 C0         Const#79  float     -4839.53027
	  +2C8B:Size=8: CD 94 D6 DF F2 62 86 40         Const#80  float     716.368591
	  +2C94:Size=8: 8F E4 F2 1F E2 76 A4 C0         Const#81  float     -2619.44165
	  +2C9D:Size=8: DB 10 C5 DF 54 B6 EB 3F         Const#82  float     0.866007268
	  +2CA6:Size=8: 0E 68 30 E0 41 00 E0 3F         Const#83  float     0.500031412
	  +2CAF:Size=8: 0E 68 30 E0 41 00 E0 BF         Const#84  float     -0.500031412
	  +2CB8:Size=4: AF 00 00 00                     Const#85  integer   175
	  +2CBD:Size=4: BD 00 00 00                     Const#86  integer   189
	  +2CC3:Size=15: 44 61 72 6B 20 4D 61 73 7...   Const#87  string    "Dark Master [Lv. 175]"
	  +2CDA:Size=B: 44 61 72 6B 20 4D 61 73 74...   Const#88  string    "Dark Master"
	  +2CE6:Size=4: BE 00 00 00                     Const#89  integer   190
	  +2CEB:Size=4: D1 00 00 00                     Const#90  integer   209
	  +2CF1:Size=12: 50 72 69 73 6F 6E 65 72 2...   Const#91  string    "Prisoner [Lv. 190]"
	  +2D05:Size=D: 50 72 69 73 6F 6E 65 72 51...   Const#92  string    "PrisonerQuest"
	  +2D14:Size=8: 50 72 69 73 6F 6E 65 72         Const#93  string    "Prisoner"
	  +2D1D:Size=8: AC AD D8 5F EE BC B4 40         Const#94  float     5308.93115
	  +2D26:Size=8: 52 99 41 00 99 7B FA 3F         Const#95  float     1.65517521
	  +2D2F:Size=8: 5D 8B 16 A0 ED B1 7D 40         Const#96  float     475.120514
	  +2D38:Size=8: DC 00 2B 00 B8 E4 B6 BF         Const#97  float     -0.0894274712
	  +2D41:Size=8: 85 5A DA 5F C7 7C 35 BE         Const#98  float     -5.00292918e-009
	  +2D4A:Size=8: A1 25 E8 5F 2D DF EF BF         Const#99  float     -0.995993316
	  +2D53:Size=8: 43 32 EA 1F D8 A0 1B 3E         Const#100 float     1.60817859e-009
	  +2D5C:Size=8: A8 74 EA 7F AB 31 36 BE         Const#101 float     -5.16744869e-009
	  +2D65:Size=8: A1 25 E8 5F 2D DF EF 3F         Const#102 float     0.995993316
	  +2D6E:Size=8: 1B 00 89 9F 72 BA 21 BE         Const#103 float     -2.06384709e-009
	  +2D77:Size=4: D2 00 00 00                     Const#104 integer   210
	  +2D7C:Size=4: F9 00 00 00                     Const#105 integer   249
	  +2D82:Size=1C: 44 61 6E 67 65 72 6F 75 7...   Const#106 string    "Dangerous Prisoner [Lv. 210]"
	  +2DA0:Size=12: 44 61 6E 67 65 72 6F 75 7...   Const#107 string    "Dangerous Prisoner"
	  +2DB3:Size=4: FA 00 00 00                     Const#108 integer   250
	  +2DB8:Size=4: 12 01 00 00                     Const#109 integer   274
	  +2DBE:Size=16: 54 6F 67 61 20 57 61 72 7...   Const#110 string    "Toga Warrior [Lv. 250]"
	  +2DD6:Size=E: 43 6F 6C 6F 73 73 65 75 6D...   Const#111 string    "ColosseumQuest"
	  +2DE6:Size=C: 54 6F 67 61 20 57 61 72 72...   Const#112 string    "Toga Warrior"
	  +2DF3:Size=8: 0D 54 C6 BF 2F B0 98 C0         Const#113 float     -1580.04663
	  +2DFC:Size=8: 3C A3 4A 20 67 66 19 40         Const#114 float     6.35000277
	  +2E05:Size=8: F6 B4 C3 5F F3 54 A7 C0         Const#115 float     -2986.47534
	  +2E0E:Size=8: A6 2A E4 7F 2F 7B E0 BF         Const#116 float     -0.515037298
	  +2E17:Size=8: 23 38 1C 00 EB 6D EB BF         Const#117 float     -0.857167721
	  +2E20:Size=8: 23 38 1C 00 EB 6D EB 3F         Const#118 float     0.857167721
	  +2E29:Size=4: 13 01 00 00                     Const#119 integer   275
	  +2E2E:Size=4: 2B 01 00 00                     Const#120 integer   299
	  +2E34:Size=13: 47 6C 61 64 69 61 74 6F 7...   Const#121 string    "Gladiator [Lv. 275]"
	  +2E49:Size=9: 47 6C 61 64 69 61 74 6F 72      Const#122 string    "Gladiator"
	  +2E53:Size=4: 2C 01 00 00                     Const#123 integer   300
	  +2E58:Size=4: 44 01 00 00                     Const#124 integer   324
	  +2E5E:Size=1A: 4D 69 6C 69 74 61 72 79 2...   Const#125 string    "Military Soldier [Lv. 300]"
	  +2E7A:Size=A: 4D 61 67 6D 61 51 75 65 73 74   Const#126 string    "MagmaQuest"
	  +2E86:Size=10: 4D 69 6C 69 74 61 72 79 2...   Const#127 string    "Military Soldier"
	  +2E97:Size=8: 98 2F 2F C0 5E C1 B4 C0         Const#128 float     -5313.37012
	  +2EA0:Size=8: BF D9 41 80 67 E6 25 40         Const#129 float     10.9500084
	  +2EA9:Size=8: 54 52 27 A0 A5 A1 C0 40         Const#130 float     8515.29395
	  +2EB2:Size=8: BC 8D 2B 00 56 FF DF BF         Const#131 float     -0.499959469
	  +2EBB:Size=8: 49 63 12 00 AC B6 EB 3F         Const#132 float     0.866048813
	  +2EC4:Size=8: 49 63 12 00 AC B6 EB BF         Const#133 float     -0.866048813
	  +2ECD:Size=4: 45 01 00 00                     Const#134 integer   325
	  +2ED2:Size=4: 76 01 00 00                     Const#135 integer   374
	  +2ED8:Size=16: 4D 69 6C 69 74 61 72 79 2...   Const#136 string    "Military Spy [Lv. 325]"
	  +2EF0:Size=C: 4D 69 6C 69 74 61 72 79 20...   Const#137 string    "Military Spy"
	  +2EFD:Size=4: 77 01 00 00                     Const#138 integer   375
	  +2F02:Size=4: 8F 01 00 00                     Const#139 integer   399
	  +2F08:Size=19: 46 69 73 68 6D 61 6E 20 5...   Const#140 string    "Fishman Warrior [Lv. 375]"
	  +2F23:Size=C: 46 69 73 68 6D 61 6E 51 75...   Const#141 string    "FishmanQuest"
	  +2F31:Size=F: 46 69 73 68 6D 61 6E 20 57...   Const#142 string    "Fishman Warrior"
	  +2F41:Size=8: 00 00 00 E0 54 D8 ED 40         Const#143 float     61122.65234375
	  +2F4A:Size=8: 90 FF FF 5F 58 7F 32 40         Const#144 float     18.497442245483
	  +2F53:Size=8: 5B FF FF 5F 99 85 98 40         Const#145 float     1569.3997802734
	  +2F5D:Size=2: 5F 47                           Const#146 string    "_G"
	  +2F61:Size=8: 41 75 74 6F 46 61 72 6D         Const#147 string    "AutoFarm"
	  +2F6B:Size=8: 50 6F 73 69 74 69 6F 6E         Const#148 string    "Position"
	  +2F75:Size=4: 67 61 6D 65                     Const#149 string    "game"
	  +2F7B:Size=9: 43 68 61 72 61 63 74 65 72      Const#150 string    "Character"
	  +2F86:Size=10: 48 75 6D 61 6E 6F 69 64 5...   Const#151 string    "HumanoidRootPart"
	  +2F98:Size=9: 4D 61 67 6E 69 74 75 64 65      Const#152 string    "Magnitude"
	  +2FA2:Size=4: 10 27 00 00                     Const#153 integer   10000
	  +2FA8:Size=A: 47 65 74 53 65 72 76 69 63 65   Const#154 string    "GetService"
	  +2FB4:Size=11: 52 65 70 6C 69 63 61 74 6...   Const#155 string    "ReplicatedStorage"
	  +2FC7:Size=7: 52 65 6D 6F 74 65 73            Const#156 string    "Remotes"
	  +2FD0:Size=6: 43 6F 6D 6D 46 5F               Const#157 string    "CommF_"
	  +2FD8:Size=C: 49 6E 76 6F 6B 65 53 65 72...   Const#158 string    "InvokeServer"
	  +2FE6:Size=F: 72 65 71 75 65 73 74 45 6E...   Const#159 string    "requestEntrance"
	  +2FF7:Size=7: 56 65 63 74 6F 72 33            Const#160 string    "Vector3"
	  +2FFF:Size=8: 00 00 00 40 7B DD ED 40         Const#161 float     61163.8515625
	  +3008:Size=8: 00 00 00 00 00 5C 27 40         Const#162 float     11.6796875
	  +3011:Size=8: 00 00 00 00 23 6F 9C 40         Const#163 float     1819.7841796875
	  +301A:Size=4: 90 01 00 00                     Const#164 integer   400
	  +301F:Size=4: C1 01 00 00                     Const#165 integer   449
	  +3025:Size=1A: 46 69 73 68 6D 61 6E 20 4...   Const#166 string    "Fishman Commando [Lv. 400]"
	  +3041:Size=10: 46 69 73 68 6D 61 6E 20 4...   Const#167 string    "Fishman Commando"
	  +3052:Size=4: C2 01 00 00                     Const#168 integer   450
	  +3057:Size=4: DA 01 00 00                     Const#169 integer   474
	  +305D:Size=15: 47 6F 64 27 73 20 47 75 6...   Const#170 string    "God's Guard [Lv. 450]"
	  +3074:Size=C: 53 6B 79 45 78 70 31 51 75...   Const#171 string    "SkyExp1Quest"
	  +3082:Size=B: 47 6F 64 27 73 20 47 75 61...   Const#172 string    "God's Guard"
	  +308E:Size=8: F0 8A E0 7F E3 71 B2 C0         Const#173 float     -4721.88867
	  +3097:Size=8: CC 97 17 60 FF 5E 8A 40         Const#174 float     843.874695
	  +30A0:Size=8: 7E 6F D3 9F DD 77 9E C0         Const#175 float     -1949.96643
	  +30A9:Size=8: 43 49 DE BF CD E0 EF 3F         Const#176 float     0.996191859
	  +30B2:Size=8: 29 7C DE 1F FB 51 B6 BF         Const#177 float     -0.0871884301
	  +30BB:Size=8: 29 7C DE 1F FB 51 B6 3F         Const#178 float     0.0871884301
	  +30C4:Size=8: C9 76 BE 9F D2 FF B1 C0         Const#179 float     -4607.82275
	  +30CD:Size=8: DF 15 C1 FF 56 44 8B 40         Const#180 float     872.54248
	  +30D6:Size=8: 30 2F C0 3E 3A 0E 9A C0         Const#181 float     -1667.55688
	  +30DF:Size=4: DB 01 00 00                     Const#182 integer   475
	  +30E4:Size=4: 0C 02 00 00                     Const#183 integer   524
	  +30EA:Size=10: 53 68 61 6E 64 61 20 5B 4...   Const#184 string    "Shanda [Lv. 475]"
	  +30FC:Size=6: 53 68 61 6E 64 61               Const#185 string    "Shanda"
	  +3103:Size=8: 6E FA B3 1F 19 B3 BE C0         Const#186 float     -7859.09814
	  +310C:Size=8: 2D 3E 05 C0 30 A8 B5 40         Const#187 float     5544.19043
	  +3115:Size=8: C7 67 B2 7F 9E D7 77 C0         Const#188 float     -381.476196
	  +311E:Size=8: 13 6E 7B 80 C3 0B DB BF         Const#189 float     -0.422592998
	  +3127:Size=8: 15 10 E1 FF 91 00 ED 3F         Const#190 float     0.906319618
	  +3130:Size=8: 15 10 E1 FF 91 00 ED BF         Const#191 float     -0.906319618
	  +3139:Size=8: 37 00 00 20 9E D6 BE C0         Const#192 float     -7894.6176757813
	  +3142:Size=8: 00 00 00 40 24 AB B5 40         Const#193 float     5547.1416015625
	  +314B:Size=8: 16 00 00 C0 A8 C4 77 C0         Const#194 float     -380.29119873047
	  +3154:Size=4: 0D 02 00 00                     Const#195 integer   525
	  +3159:Size=4: 25 02 00 00                     Const#196 integer   549
	  +315F:Size=15: 52 6F 79 61 6C 20 53 71 7...   Const#197 string    "Royal Squad [Lv. 525]"
	  +3176:Size=C: 53 6B 79 45 78 70 32 51 75...   Const#198 string    "SkyExp2Quest"
	  +3184:Size=B: 52 6F 79 61 6C 20 53 71 75...   Const#199 string    "Royal Squad"
	  +3190:Size=8: 27 14 22 E0 D0 E2 BE C0         Const#200 float     -7906.81592
	  +3199:Size=8: 54 52 27 A0 A9 02 B6 40         Const#201 float     5634.6626
	  +31A2:Size=8: 61 8E 1E BF F7 0F 96 C0         Const#202 float     -1411.99194
	  +31AB:Size=4: 26 02 00 00                     Const#203 integer   550
	  +31B0:Size=4: 70 02 00 00                     Const#204 integer   624
	  +31B6:Size=17: 52 6F 79 61 6C 20 53 6F 6...   Const#205 string    "Royal Soldier [Lv. 550]"
	  +31CF:Size=D: 52 6F 79 61 6C 20 53 6F 6C...   Const#206 string    "Royal Soldier"
	  +31DD:Size=4: 71 02 00 00                     Const#207 integer   625
	  +31E2:Size=4: 89 02 00 00                     Const#208 integer   649
	  +31E8:Size=17: 47 61 6C 6C 65 79 20 50 6...   Const#209 string    "Galley Pirate [Lv. 625]"
	  +3201:Size=D: 46 6F 75 6E 74 61 69 6E 51...   Const#210 string    "FountainQuest"
	  +3210:Size=D: 47 61 6C 6C 65 79 20 50 69...   Const#211 string    "Galley Pirate"
	  +321E:Size=8: 9B 38 B9 DF D1 8B B4 40         Const#212 float     5259.81982
	  +3227:Size=8: 8B C3 99 5F CD AC 42 40         Const#213 float     37.3500175
	  +3230:Size=8: 8C DB 68 00 0F A4 AF 40         Const#214 float     4050.0293
	  +3239:Size=8: 4B AE D9 FF 3D 4E B6 3F         Const#215 float     0.087131381
	  +3242:Size=8: 50 20 FB 3F D8 E0 EF 3F         Const#216 float     0.996196866
	  +324B:Size=8: 50 20 FB 3F D8 E0 EF BF         Const#217 float     -0.996196866
	  +3254:Size=4: 8A 02 00 00                     Const#218 integer   650
	  +325A:Size=18: 47 61 6C 6C 65 79 20 43 6...   Const#219 string    "Galley Captain [Lv. 650]"
	  +3274:Size=E: 47 61 6C 6C 65 79 20 43 61...   Const#220 string    "Galley Captain"
	  +3284:Size=2: 57 32                           Const#221 string    "W2"
	  +3287:Size=4: BC 02 00 00                     Const#222 integer   700
	  +328C:Size=4: D4 02 00 00                     Const#223 integer   724
	  +3292:Size=10: 52 61 69 64 65 72 20 5B 4...   Const#224 string    "Raider [Lv. 700]"
	  +32A4:Size=A: 41 72 65 61 31 51 75 65 73 74   Const#225 string    "Area1Quest"
	  +32B0:Size=6: 52 61 69 64 65 72               Const#226 string    "Raider"
	  +32B7:Size=8: 99 2C EE 3F B2 D8 7A C0         Const#227 float     -429.543518
	  +32C0:Size=8: FF C1 D1 9F 47 F1 51 40         Const#228 float     71.7699966
	  +32C9:Size=8: 30 2F C0 3E BA B0 9C 40         Const#229 float     1836.18188
	  +32D2:Size=8: 55 DF 54 FF 7B CB CC BF         Const#230 float     -0.22495985
	  +32DB:Size=8: 68 4E C9 FF 05 2E EF BF         Const#231 float     -0.974368095
	  +32E4:Size=8: 68 4E C9 FF 05 2E EF 3F         Const#232 float     0.974368095
	  +32ED:Size=4: D5 02 00 00                     Const#233 integer   725
	  +32F2:Size=4: 06 03 00 00                     Const#234 integer   774
	  +32F8:Size=13: 4D 65 72 63 65 6E 61 72 7...   Const#235 string    "Mercenary [Lv. 725]"
	  +330D:Size=9: 4D 65 72 63 65 6E 61 72 79      Const#236 string    "Mercenary"
	  +3317:Size=4: 07 03 00 00                     Const#237 integer   775
	  +331C:Size=4: 1F 03 00 00                     Const#238 integer   799
	  +3322:Size=15: 53 77 61 6E 20 50 69 72 6...   Const#239 string    "Swan Pirate [Lv. 775]"
	  +3339:Size=A: 41 72 65 61 32 51 75 65 73 74   Const#240 string    "Area2Quest"
	  +3345:Size=B: 53 77 61 6E 20 50 69 72 61...   Const#241 string    "Swan Pirate"
	  +3351:Size=8: 68 D0 D0 3F 81 F3 83 40         Const#242 float     638.43811
	  +335A:Size=8: E7 51 F1 7F 47 F1 51 40         Const#243 float     71.769989
	  +3363:Size=8: D5 D0 06 60 43 B2 8C 40         Const#244 float     918.282898
	  +336C:Size=8: 2C 6B DF FF 6E D1 C1 3F         Const#245 float     0.139203906
	  +3375:Size=8: D5 A5 F3 9F 3D B0 EF 3F         Const#246 float     0.99026376
	  +337E:Size=8: D5 A5 F3 9F 3D B0 EF BF         Const#247 float     -0.99026376
	  +3387:Size=4: 20 03 00 00                     Const#248 integer   800
	  +338C:Size=4: 6A 03 00 00                     Const#249 integer   874
	  +3392:Size=17: 46 61 63 74 6F 72 79 20 5...   Const#250 string    "Factory Staff [Lv. 800]"
	  +33AB:Size=D: 46 61 63 74 6F 72 79 20 53...   Const#251 string    "Factory Staff"
	  +33B9:Size=8: CB 85 CA BF 96 C5 83 40         Const#252 float     632.698608
	  +33C2:Size=8: 8B 30 EA FF C1 46 52 40         Const#253 float     73.1055908
	  +33CB:Size=8: 1B BD 1A A0 54 B5 8C 40         Const#254 float     918.666321
	  +33D4:Size=8: 27 1E BB 3F AA 5E A0 BF         Const#255 float     -0.0319722369
	  +33DD:Size=8: 72 7E 05 40 F5 C9 0E 3E         Const#256 float     8.96074881e-010
	  +33E6:Size=8: 66 41 05 E0 CF FB EF BF         Const#257 float     -0.999488771
	  +33EF:Size=8: B9 A0 16 3F 90 BC E2 3D         Const#258 float     1.36326533e-010
	  +33F8:Size=8: 53 AF FE 7F A1 A7 0E 3E         Const#259 float     8.92172336e-010
	  +3401:Size=8: 66 41 05 E0 CF FB EF 3F         Const#260 float     0.999488771
	  +340A:Size=8: 62 99 5A BF F8 9C DD BD         Const#261 float     -1.07732087e-010
	  +3413:Size=4: 6B 03 00 00                     Const#262 integer   875
	  +3418:Size=4: 83 03 00 00                     Const#263 integer   899
	  +341E:Size=1B: 4D 61 72 69 6E 65 20 4C 6...   Const#264 string    "Marine Lieutenant [Lv. 875]"
	  +343B:Size=C: 4D 61 72 69 6E 65 51 75 65...   Const#265 string    "MarineQuest3"
	  +3449:Size=11: 4D 61 72 69 6E 65 20 4C 6...   Const#266 string    "Marine Lieutenant"
	  +345B:Size=8: B9 19 6E C0 97 11 A3 C0         Const#267 float     -2440.79639
	  +3464:Size=8: CE 3C 14 60 B3 ED 51 40         Const#268 float     71.7140732
	  +346D:Size=8: 68 E8 9F E0 22 20 A9 C0         Const#269 float     -3216.06812
	  +3476:Size=4: 84 03 00 00                     Const#270 integer   900
	  +347B:Size=4: B5 03 00 00                     Const#271 integer   949
	  +3481:Size=18: 4D 61 72 69 6E 65 20 43 6...   Const#272 string    "Marine Captain [Lv. 900]"
	  +349B:Size=E: 4D 61 72 69 6E 65 20 43 61...   Const#273 string    "Marine Captain"
	  +34AA:Size=4: B6 03 00 00                     Const#274 integer   950
	  +34AF:Size=4: CE 03 00 00                     Const#275 integer   974
	  +34B5:Size=10: 5A 6F 6D 62 69 65 20 5B 4...   Const#276 string    "Zombie [Lv. 950]"
	  +34C7:Size=B: 5A 6F 6D 62 69 65 51 75 65...   Const#277 string    "ZombieQuest"
	  +34D4:Size=6: 5A 6F 6D 62 69 65               Const#278 string    "Zombie"
	  +34DB:Size=8: 0D 54 C6 BF 0F 79 B5 C0         Const#279 float     -5497.06152
	  +34E4:Size=8: 30 B4 DF 7F D0 CB 47 40         Const#280 float     47.5923004
	  +34ED:Size=8: 42 D1 3C 80 E5 D9 88 C0         Const#281 float     -795.237061
	  +34F6:Size=8: 02 4F D6 7F 08 B7 D2 BF         Const#282 float     -0.29242146
	  +34FF:Size=8: 46 6E 1B 80 EC 99 EE BF         Const#283 float     -0.95628953
	  +3508:Size=8: 46 6E 1B 80 EC 99 EE 3F         Const#284 float     0.95628953
	  +3511:Size=4: CF 03 00 00                     Const#285 integer   975
	  +3516:Size=4: E7 03 00 00                     Const#286 integer   999
	  +351C:Size=11: 56 61 6D 70 69 72 65 20 5...   Const#287 string    "Vampire [Lv. 975]"
	  +352F:Size=7: 56 61 6D 70 69 72 65            Const#288 string    "Vampire"
	  +3537:Size=4: E8 03 00 00                     Const#289 integer   1000
	  +353C:Size=4: 19 04 00 00                     Const#290 integer   1049
	  +3542:Size=17: 53 6E 6F 77 20 54 72 6F 6...   Const#291 string    "Snow Trooper [Lv. 1000]"
	  +355B:Size=11: 53 6E 6F 77 4D 6F 75 6E 7...   Const#292 string    "SnowMountainQuest"
	  +356E:Size=C: 53 6E 6F 77 20 54 72 6F 6F...   Const#293 string    "Snow Trooper"
	  +357B:Size=8: A3 77 2A E0 DE 0E 83 40         Const#294 float     609.858826
	  +3584:Size=8: 8E EA 74 20 EB 01 79 40         Const#295 float     400.119904
	  +358D:Size=8: 82 90 2C 60 42 FC B4 C0         Const#296 float     -5372.25928
	  +3596:Size=8: 87 E8 0D 80 83 F9 D7 BF         Const#297 float     -0.374604106
	  +359F:Size=8: 0C 43 1E A0 7F AB ED 3F         Const#298 float     0.92718488
	  +35A8:Size=8: 0C 43 1E A0 7F AB ED BF         Const#299 float     -0.92718488
	  +35B1:Size=4: 1A 04 00 00                     Const#300 integer   1050
	  +35B6:Size=4: 4B 04 00 00                     Const#301 integer   1099
	  +35BC:Size=19: 57 69 6E 74 65 72 20 57 6...   Const#302 string    "Winter Warrior [Lv. 1050]"
	  +35D7:Size=E: 57 69 6E 74 65 72 20 57 61...   Const#303 string    "Winter Warrior"
	  +35E6:Size=4: 4C 04 00 00                     Const#304 integer   1100
	  +35EB:Size=4: 64 04 00 00                     Const#305 integer   1124
	  +35F1:Size=1A: 4C 61 62 20 53 75 62 6F 7...   Const#306 string    "Lab Subordinate [Lv. 1100]"
	  +360D:Size=C: 49 63 65 53 69 64 65 51 75...   Const#307 string    "IceSideQuest"
	  +361B:Size=F: 4C 61 62 20 53 75 62 6F 72...   Const#308 string    "Lab Subordinate"
	  +362B:Size=8: 54 52 27 A0 11 B0 B7 C0         Const#309 float     -6064.06885
	  +3634:Size=8: B2 93 0B DF 0C 7C 2E 40         Const#310 float     15.2422857
	  +363D:Size=8: 7B 66 49 80 FA 26 B3 C0         Const#311 float     -4902.97852
	  +3646:Size=8: 9E 9C F2 FF E2 0D DD 3F         Const#312 float     0.453972578
	  +364F:Size=8: 21 BC 15 40 33 83 EC BF         Const#313 float     -0.891015649
	  +3658:Size=8: 21 BC 15 40 33 83 EC 3F         Const#314 float     0.891015649
	  +3661:Size=4: 65 04 00 00                     Const#315 integer   1125
	  +3666:Size=4: 96 04 00 00                     Const#316 integer   1174
	  +366C:Size=19: 48 6F 72 6E 65 64 20 57 6...   Const#317 string    "Horned Warrior [Lv. 1125]"
	  +3687:Size=E: 48 6F 72 6E 65 64 20 57 61...   Const#318 string    "Horned Warrior"
	  +3696:Size=4: 97 04 00 00                     Const#319 integer   1175
	  +369B:Size=4: AF 04 00 00                     Const#320 integer   1199
	  +36A1:Size=16: 4D 61 67 6D 61 20 4E 69 6...   Const#321 string    "Magma Ninja [Lv. 1175]"
	  +36B9:Size=D: 46 69 72 65 53 69 64 65 51...   Const#322 string    "FireSideQuest"
	  +36C8:Size=B: 4D 61 67 6D 61 20 4E 69 6E...   Const#323 string    "Magma Ninja"
	  +36D4:Size=8: FA D5 1C 20 08 34 B5 C0         Const#324 float     -5428.03174
	  +36DD:Size=8: 2C 99 08 C0 E4 1F 2E 40         Const#325 float     15.0622921
	  +36E6:Size=8: D3 C1 FA 3F 6F B3 B4 C0         Const#326 float     -5299.43457
	  +36EF:Size=8: A6 81 D8 FF 24 41 EC BF         Const#327 float     -0.882952213
	  +36F8:Size=8: 2E A5 FE DF B0 0B DE 3F         Const#328 float     0.469463557
	  +3701:Size=8: 2E A5 FE DF B0 0B DE BF         Const#329 float     -0.469463557
	  +370A:Size=4: B0 04 00 00                     Const#330 integer   1200
	  +370F:Size=4: E1 04 00 00                     Const#331 integer   1249
	  +3715:Size=16: 4C 61 76 61 20 50 69 72 6...   Const#332 string    "Lava Pirate [Lv. 1200]"
	  +372D:Size=B: 4C 61 76 61 20 50 69 72 61...   Const#333 string    "Lava Pirate"
	  +3739:Size=4: E2 04 00 00                     Const#334 integer   1250
	  +373E:Size=4: FA 04 00 00                     Const#335 integer   1274
	  +3744:Size=18: 53 68 69 70 20 44 65 63 6...   Const#336 string    "Ship Deckhand [Lv. 1250]"
	  +375E:Size=A: 53 68 69 70 51 75 65 73 74 31   Const#337 string    "ShipQuest1"
	  +376A:Size=D: 53 68 69 70 20 44 65 63 6B...   Const#338 string    "Ship Deckhand"
	  +3778:Size=8: 10 75 1F 80 34 37 90 40         Const#339 float     1037.80127
	  +3781:Size=8: EF A8 31 21 E6 45 5F 40         Const#340 float     125.092171
	  +378A:Size=8: A9 A4 4E 40 F3 11 E0 40         Const#341 float     32911.6016
	  +3793:Size=8: EA FF FF 3F B3 D9 8C 40         Const#342 float     923.21252441406
	  +379C:Size=8: 37 00 00 E0 76 BE 5F 40         Const#343 float     126.9760055542
	  +37A5:Size=8: 00 00 00 A0 9A 0A E0 40         Const#344 float     32852.83203125
	  +37AE:Size=4: FB 04 00 00                     Const#345 integer   1275
	  +37B3:Size=4: 13 05 00 00                     Const#346 integer   1299
	  +37B9:Size=18: 53 68 69 70 20 45 6E 67 6...   Const#347 string    "Ship Engineer [Lv. 1275]"
	  +37D3:Size=D: 53 68 69 70 20 45 6E 67 69...   Const#348 string    "Ship Engineer"
	  +37E1:Size=4: 14 05 00 00                     Const#349 integer   1300
	  +37E6:Size=4: 2C 05 00 00                     Const#350 integer   1324
	  +37EC:Size=17: 53 68 69 70 20 53 74 65 7...   Const#351 string    "Ship Steward [Lv. 1300]"
	  +3805:Size=A: 53 68 69 70 51 75 65 73 74 32   Const#352 string    "ShipQuest2"
	  +3811:Size=C: 53 68 69 70 20 53 74 65 77...   Const#353 string    "Ship Steward"
	  +381E:Size=8: 95 0E D6 FF 79 46 8E 40         Const#354 float     968.80957
	  +3827:Size=8: 00 00 00 00 84 3B E0 40         Const#355 float     33244.125
	  +3830:Size=4: 2D 05 00 00                     Const#356 integer   1325
	  +3835:Size=4: 45 05 00 00                     Const#357 integer   1349
	  +383B:Size=17: 53 68 69 70 20 4F 66 66 6...   Const#358 string    "Ship Officer [Lv. 1325]"
	  +3854:Size=C: 53 68 69 70 20 4F 66 66 69...   Const#359 string    "Ship Officer"
	  +3861:Size=4: 46 05 00 00                     Const#360 integer   1350
	  +3866:Size=4: 5E 05 00 00                     Const#361 integer   1374
	  +386C:Size=19: 41 72 63 74 69 63 20 57 6...   Const#362 string    "Arctic Warrior [Lv. 1350]"
	  +3887:Size=A: 46 72 6F 73 74 51 75 65 73 74   Const#363 string    "FrostQuest"
	  +3893:Size=E: 41 72 63 74 69 63 20 57 61...   Const#364 string    "Arctic Warrior"
	  +38A2:Size=8: 3A 92 CB 7F A8 23 B6 40         Const#365 float     5667.6582
	  +38AB:Size=8: 9F EF 02 80 BE CC 3A 40         Const#366 float     26.7997818
	  +38B4:Size=8: DF 15 C1 FF 16 56 B9 C0         Const#367 float     -6486.08984
	  +38BD:Size=8: A1 12 23 C0 F3 DF ED BF         Const#368 float     -0.933587909
	  +38C6:Size=8: 4B 2F E8 BF 32 EF D6 BF         Const#369 float     -0.358349502
	  +38CF:Size=8: 4B 2F E8 BF 32 EF D6 3F         Const#370 float     0.358349502
	  +38D8:Size=8: 37 00 00 E0 8E 6C B9 C0         Const#371 float     -6508.5581054688
	  +38E1:Size=8: 00 00 80 F5 08 88 B3 40         Const#372 float     5000.034996032715
	  +38EA:Size=8: 2C 00 00 80 DD 9A 60 C0         Const#373 float     -132.83953857422
	  +38F3:Size=4: 5F 05 00 00                     Const#374 integer   1375
	  +38F8:Size=4: 90 05 00 00                     Const#375 integer   1424
	  +38FE:Size=16: 53 6E 6F 77 20 4C 75 72 6...   Const#376 string    "Snow Lurker [Lv. 1375]"
	  +3916:Size=B: 53 6E 6F 77 20 4C 75 72 6B...   Const#377 string    "Snow Lurker"
	  +3922:Size=4: 91 05 00 00                     Const#378 integer   1425
	  +3927:Size=4: A9 05 00 00                     Const#379 integer   1449
	  +392D:Size=16: 53 65 61 20 53 6F 6C 64 6...   Const#380 string    "Sea Soldier [Lv. 1425]"
	  +3945:Size=E: 46 6F 72 67 6F 74 74 65 6E...   Const#381 string    "ForgottenQuest"
	  +3955:Size=B: 53 65 61 20 53 6F 6C 64 69...   Const#382 string    "Sea Soldier"
	  +3961:Size=8: E9 60 FD 9F E3 DC A7 C0         Const#383 float     -3054.44458
	  +396A:Size=8: B2 DA FC BF 6A 71 6D 40         Const#384 float     235.544281
	  +3973:Size=8: CE 88 D2 DE 68 CF C3 C0         Const#385 float     -10142.8193
	  +397C:Size=8: 92 C3 E3 7F 4B B0 EF 3F         Const#386 float     0.990270376
	  +3985:Size=8: 92 1E E9 80 E2 CF C1 BF         Const#387 float     -0.13915664
	  +398E:Size=8: 92 1E E9 80 E2 CF C1 3F         Const#388 float     0.13915664
	  +3997:Size=4: AA 05 00 00                     Const#389 integer   1450
	  +399D:Size=18: 57 61 74 65 72 20 46 69 6...   Const#390 string    "Water Fighter [Lv. 1450]"
	  +39B7:Size=D: 57 61 74 65 72 20 46 69 67...   Const#391 string    "Water Fighter"
	  +39C6:Size=2: 57 33                           Const#392 string    "W3"
	  +39C9:Size=4: DC 05 00 00                     Const#393 integer   1500
	  +39CE:Size=4: F4 05 00 00                     Const#394 integer   1524
	  +39D4:Size=1D: 50 69 72 61 74 65 20 4D 6...   Const#395 string    "Pirate Millionaire [Lv. 1500]"
	  +39F3:Size=F: 50 69 72 61 74 65 50 6F 72...   Const#396 string    "PiratePortQuest"
	  +3A04:Size=12: 50 69 72 61 74 65 20 4D 6...   Const#397 string    "Pirate Millionaire"
	  +3A17:Size=8: 37 8C 82 E0 31 21 72 C0         Const#398 float     -290.074677
	  +3A20:Size=8: 11 49 3E C0 A4 73 45 40         Const#399 float     42.9034653
	  +3A29:Size=8: DF 15 C1 FF 96 CD B5 40         Const#400 float     5581.58984
	  +3A32:Size=8: B4 7A C6 3F E5 E8 EE 3F         Const#401 float     0.965929627
	  +3A3B:Size=8: 02 4E DD FF 41 90 D0 BF         Const#402 float     -0.258804798
	  +3A44:Size=8: 02 4E DD FF 41 90 D0 3F         Const#403 float     0.258804798
	  +3A4D:Size=4: F5 05 00 00                     Const#404 integer   1525
	  +3A52:Size=4: 26 06 00 00                     Const#405 integer   1574
	  +3A58:Size=1D: 50 69 73 74 6F 6C 20 42 6...   Const#406 string    "Pistol Billionaire [Lv. 1525]"
	  +3A77:Size=12: 50 69 73 74 6F 6C 20 42 6...   Const#407 string    "Pistol Billionaire"
	  +3A8A:Size=4: 27 06 00 00                     Const#408 integer   1575
	  +3A8F:Size=4: 3F 06 00 00                     Const#409 integer   1599
	  +3A95:Size=1E: 44 72 61 67 6F 6E 20 43 7...   Const#410 string    "Dragon Crew Warrior [Lv. 1575]"
	  +3AB5:Size=B: 41 6D 61 7A 6F 6E 51 75 65...   Const#411 string    "AmazonQuest"
	  +3AC2:Size=13: 44 72 61 67 6F 6E 20 43 7...   Const#412 string    "Dragon Crew Warrior"
	  +3AD6:Size=8: 6B F1 29 00 D6 C8 B6 40         Const#413 float     5832.83594
	  +3ADF:Size=8: 62 E7 5C 40 1E D7 49 40         Const#414 float     51.6806107
	  +3AE8:Size=8: 59 8B 4F 01 10 36 91 C0         Const#415 float     -1101.51563
	  +3AF1:Size=8: E5 AE BB FF E3 C2 EC 3F         Const#416 float     0.898790359
	  +3AFA:Size=8: DE 9A B3 BF 65 0E DC BF         Const#417 float     -0.438378751
	  +3B03:Size=8: DE 9A B3 BF 65 0E DC 3F         Const#418 float     0.438378751
	  +3B0C:Size=4: 40 06 00 00                     Const#419 integer   1600
	  +3B11:Size=4: 58 06 00 00                     Const#420 integer   1624
	  +3B17:Size=1D: 44 72 61 67 6F 6E 20 43 7...   Const#421 string    "Dragon Crew Archer [Lv. 1600]"
	  +3B36:Size=12: 44 72 61 67 6F 6E 20 43 7...   Const#422 string    "Dragon Crew Archer"
	  +3B49:Size=8: 37 00 00 60 1D C9 B6 40         Const#423 float     5833.1147460938
	  +3B52:Size=8: 00 00 00 00 70 CD 49 40         Const#424 float     105687/2048
	  +3B5B:Size=8: 00 00 00 00 47 3C 91 C0         Const#425 float     -1103.0693359375
	  +3B64:Size=4: 59 06 00 00                     Const#426 integer   1625
	  +3B69:Size=4: 71 06 00 00                     Const#427 integer   1649
	  +3B6F:Size=1A: 46 65 6D 61 6C 65 20 49 7...   Const#428 string    "Female Islander [Lv. 1625]"
	  +3B8B:Size=C: 41 6D 61 7A 6F 6E 51 75 65...   Const#429 string    "AmazonQuest2"
	  +3B99:Size=F: 46 65 6D 61 6C 65 20 49 73...   Const#430 string    "Female Islander"
	  +3BA9:Size=8: 37 00 00 20 E1 46 B5 40         Const#431 float     5446.8793945313
	  +3BB2:Size=8: 21 00 00 20 09 CD 82 40         Const#432 float     601.62945556641
	  +3BBB:Size=8: 0B 00 00 60 A7 6B 87 40         Const#433 float     749.45672607422
	  +3BC4:Size=4: 72 06 00 00                     Const#434 integer   1650
	  +3BC9:Size=4: A3 06 00 00                     Const#435 integer   1699
	  +3BCF:Size=19: 47 69 61 6E 74 20 49 73 6...   Const#436 string    "Giant Islander [Lv. 1650]"
	  +3BEA:Size=E: 47 69 61 6E 74 20 49 73 6C...   Const#437 string    "Giant Islander"
	  +3BF9:Size=4: A4 06 00 00                     Const#438 integer   1700
	  +3BFE:Size=4: BC 06 00 00                     Const#439 integer   1724
	  +3C04:Size=1B: 4D 61 72 69 6E 65 20 43 6...   Const#440 string    "Marine Commodore [Lv. 1700]"
	  +3C21:Size=10: 4D 61 72 69 6E 65 54 72 6...   Const#441 string    "MarineTreeIsland"
	  +3C33:Size=10: 4D 61 72 69 6E 65 20 43 6...   Const#442 string    "Marine Commodore"
	  +3C44:Size=8: 44 DD 07 20 15 09 A1 40         Const#443 float     2180.54126
	  +3C4D:Size=8: C5 73 B6 80 D0 D0 3B 40         Const#444 float     27.8156815
	  +3C56:Size=8: 57 5B B1 BF 8C 55 BA C0         Const#445 float     -6741.5498
	  +3C5F:Size=8: 5B 27 33 80 E5 E8 EE BF         Const#446 float     -0.965929747
	  +3C68:Size=4: BD 06 00 00                     Const#447 integer   1725
	  +3C6D:Size=4: EE 06 00 00                     Const#448 integer   1774
	  +3C73:Size=1E: 4D 61 72 69 6E 65 20 52 6...   Const#449 string    "Marine Rear Admiral [Lv. 1725]"
	  +3C93:Size=13: 4D 61 72 69 6E 65 20 52 6...   Const#450 string    "Marine Rear Admiral"
	  +3CA7:Size=8: 00 00 00 00 FA 07 A1 40         Const#451 float     558077/256
	  +3CB0:Size=8: 61 00 00 80 32 BB 3C 40         Const#452 float     28.731239318848
	  +3CB9:Size=8: 37 00 00 20 0E 54 BA C0         Const#453 float     -6740.0551757813
	  +3CC2:Size=4: EF 06 00 00                     Const#454 integer   1775
	  +3CC7:Size=4: 07 07 00 00                     Const#455 integer   1799
	  +3CCD:Size=19: 46 69 73 68 6D 61 6E 20 5...   Const#456 string    "Fishman Raider [Lv. 1775]"
	  +3CE8:Size=11: 44 65 65 70 46 6F 72 65 7...   Const#457 string    "DeepForestIsland3"
	  +3CFB:Size=E: 46 69 73 68 6D 61 6E 20 52...   Const#458 string    "Fishman Raider"
	  +3D0A:Size=8: 2F 6E A3 01 D4 AA C4 C0         Const#459 float     -10581.6563
	  +3D13:Size=8: 13 7E A9 9F F7 AD 74 40         Const#460 float     330.872955
	  +3D1C:Size=8: 06 2A E3 DF 97 1C C1 C0         Const#461 float     -8761.18652
	  +3D25:Size=4: 08 07 00 00                     Const#462 integer   1800
	  +3D2A:Size=4: 20 07 00 00                     Const#463 integer   1824
	  +3D30:Size=1A: 46 69 73 68 6D 61 6E 20 4...   Const#464 string    "Fishman Captain [Lv. 1800]"
	  +3D4C:Size=F: 46 69 73 68 6D 61 6E 20 43...   Const#465 string    "Fishman Captain"
	  +3D5C:Size=4: 21 07 00 00                     Const#466 integer   1825
	  +3D61:Size=4: 39 07 00 00                     Const#467 integer   1849
	  +3D67:Size=18: 46 6F 72 65 73 74 20 50 6...   Const#468 string    "Forest Pirate [Lv. 1825]"
	  +3D81:Size=10: 44 65 65 70 46 6F 72 65 7...   Const#469 string    "DeepForestIsland"
	  +3D93:Size=D: 46 6F 72 65 73 74 20 50 69...   Const#470 string    "Forest Pirate"
	  +3DA1:Size=8: EC 51 B8 1E 05 D9 C9 C0         Const#471 float     -13234.04
	  +3DAA:Size=8: 27 14 22 E0 D0 B7 74 40         Const#472 float     331.488495
	  +3DB3:Size=8: 98 2F 2F C0 66 C9 BD C0         Const#473 float     -7625.40137
	  +3DBC:Size=8: 09 E4 17 00 D8 A0 E6 3F         Const#474 float     0.707134247
	  +3DC5:Size=8: 85 C3 D0 BF 64 A0 E6 BF         Const#475 float     -0.707079291
	  +3DCE:Size=8: 85 C3 D0 BF 64 A0 E6 3F         Const#476 float     0.707079291
	  +3DD7:Size=4: 3A 07 00 00                     Const#477 integer   1850
	  +3DDC:Size=4: 6B 07 00 00                     Const#478 integer   1899
	  +3DE2:Size=1E: 4D 79 74 68 6F 6C 6F 67 6...   Const#479 string    "Mythological Pirate [Lv. 1850]"
	  +3E02:Size=13: 4D 79 74 68 6F 6C 6F 67 6...   Const#480 string    "Mythological Pirate"
	  +3E16:Size=4: 6C 07 00 00                     Const#481 integer   1900
	  +3E1B:Size=4: 84 07 00 00                     Const#482 integer   1924
	  +3E21:Size=18: 4A 75 6E 67 6C 65 20 50 6...   Const#483 string    "Jungle Pirate [Lv. 1900]"
	  +3E3B:Size=11: 44 65 65 70 46 6F 72 65 7...   Const#484 string    "DeepForestIsland2"
	  +3E4E:Size=D: 4A 75 6E 67 6C 65 20 50 69...   Const#485 string    "Jungle Pirate"
	  +3E5C:Size=8: CE 88 D2 DE 30 C4 C8 C0         Const#486 float     -12680.3818
	  +3E65:Size=8: 40 C2 30 60 89 5F 78 40         Const#487 float     389.971039
	  +3E6E:Size=8: A5 83 F5 7F 02 57 C3 C0         Const#488 float     -9902.01953
	  +3E77:Size=8: 85 77 CF FF 3F 4E B6 BF         Const#489 float     -0.0871315002
	  +3E80:Size=4: 85 07 00 00                     Const#490 integer   1925
	  +3E85:Size=4: B6 07 00 00                     Const#491 integer   1974
	  +3E8B:Size=1B: 4D 75 73 6B 65 74 65 65 7...   Const#492 string    "Musketeer Pirate [Lv. 1925]"
	  +3EA8:Size=10: 4D 75 73 6B 65 74 65 65 7...   Const#493 string    "Musketeer Pirate"
	  +3EB9:Size=4: B7 07 00 00                     Const#494 integer   1975
	  +3EBE:Size=4: CF 07 00 00                     Const#495 integer   1999
	  +3EC4:Size=1A: 52 65 62 6F 72 6E 20 53 6...   Const#496 string    "Reborn Skeleton [Lv. 1975]"
	  +3EE0:Size=D: 48 61 75 6E 74 65 64 51 75...   Const#497 string    "HauntedQuest1"
	  +3EEF:Size=F: 52 65 62 6F 72 6E 20 53 6B...   Const#498 string    "Reborn Skeleton"
	  +3EFF:Size=8: E3 36 1A C0 9B 83 C2 C0         Const#499 float     -9479.2168
	  +3F08:Size=8: 63 B8 3A 00 E2 A6 61 40         Const#500 float     141.215088
	  +3F11:Size=8: 0D 54 C6 BF 17 BE B5 40         Const#501 float     5566.09277
	  +3F1A:Size=4: D0 07 00 00                     Const#502 integer   2000
	  +3F1F:Size=4: E8 07 00 00                     Const#503 integer   2024
	  +3F25:Size=18: 4C 69 76 69 6E 67 20 5A 6...   Const#504 string    "Living Zombie [Lv. 2000]"
	  +3F3F:Size=D: 4C 69 76 69 6E 67 20 5A 6F...   Const#505 string    "Living Zombie"
	  +3F4D:Size=4: E9 07 00 00                     Const#506 integer   2025
	  +3F52:Size=4: 01 08 00 00                     Const#507 integer   2049
	  +3F58:Size=17: 44 65 6D 6F 6E 69 63 20 5...   Const#508 string    "Demonic Soul [Lv. 2025]"
	  +3F71:Size=D: 48 61 75 6E 74 65 64 51 75...   Const#509 string    "HauntedQuest2"
	  +3F80:Size=C: 44 65 6D 6F 6E 69 63 20 53...   Const#510 string    "Demonic Soul"
	  +3F8D:Size=8: D9 EB DD 1F 7F 96 C2 C0         Const#511 float     -9516.99316
	  +3F96:Size=8: 9A 23 2B BF 8C 80 65 40         Const#512 float     172.017181
	  +3F9F:Size=8: D9 EB DD 1F 77 BE B7 40         Const#513 float     6078.46533
	  +3FA8:Size=4: 02 08 00 00                     Const#514 integer   2050
	  +3FAD:Size=4: 1A 08 00 00                     Const#515 integer   2074
	  +3FB3:Size=19: 50 6F 73 65 73 73 65 64 2...   Const#516 string    "Posessed Mummy [Lv. 2050]"
	  +3FCE:Size=E: 50 6F 73 65 73 73 65 64 20...   Const#517 string    "Posessed Mummy"
	  +3FDD:Size=4: 1B 08 00 00                     Const#518 integer   2075
	  +3FE2:Size=4: 33 08 00 00                     Const#519 integer   2099
	  +3FE8:Size=17: 50 65 61 6E 75 74 20 53 6...   Const#520 string    "Peanut Scout [Lv. 2075]"
	  +4001:Size=F: 4E 75 74 73 49 73 6C 61 6E...   Const#521 string    "NutsIslandQuest"
	  +4012:Size=C: 50 65 61 6E 75 74 20 53 63...   Const#522 string    "Peanut Scout"
	  +401F:Size=8: C9 FF FF 1F C8 70 A0 C0         Const#523 float     -2104.3908691406
	  +4028:Size=8: C5 FF FF 5F 55 0D 43 40         Const#524 float     38.104167938232
	  +4031:Size=8: 00 00 00 00 1C E9 C3 C0         Const#525 float     -326215/32
	  +403A:Size=4: 34 08 00 00                     Const#526 integer   2100
	  +403F:Size=4: 4C 08 00 00                     Const#527 integer   2124
	  +4045:Size=1B: 50 65 61 6E 75 74 20 50 7...   Const#528 string    "Peanut President [Lv. 2100]"
	  +4062:Size=10: 50 65 61 6E 75 74 20 50 7...   Const#529 string    "Peanut President"
	  +4073:Size=4: 4D 08 00 00                     Const#530 integer   2125
	  +4078:Size=4: 65 08 00 00                     Const#531 integer   2149
	  +407E:Size=19: 49 63 65 20 43 72 65 61 6...   Const#532 string    "Ice Cream Chef [Lv. 2125]"
	  +4099:Size=13: 49 63 65 43 72 65 61 6D 4...   Const#533 string    "IceCreamIslandQuest"
	  +40AE:Size=E: 49 63 65 20 43 72 65 61 6D...   Const#534 string    "Ice Cream Chef"
	  +40BD:Size=8: F5 FF FF 9F 2F A5 89 C0         Const#535 float     -820.64825439453
	  +40C6:Size=8: EC FF FF 1F 73 74 50 40         Const#536 float     65.819526672363
	  +40CF:Size=8: 13 01 00 E0 E5 6A C5 C0         Const#537 float     -10965.795898438
	  +40D8:Size=4: 66 08 00 00                     Const#538 integer   2150
	  +40DD:Size=4: 97 08 00 00                     Const#539 integer   2199
	  +40E3:Size=1E: 49 63 65 20 43 72 65 61 6...   Const#540 string    "Ice Cream Commander [Lv. 2150]"
	  +4103:Size=13: 49 63 65 20 43 72 65 61 6...   Const#541 string    "Ice Cream Commander"
	  +4117:Size=4: 98 08 00 00                     Const#542 integer   2200
	  +411C:Size=4: B0 08 00 00                     Const#543 integer   2224
	  +4122:Size=19: 43 6F 6F 6B 69 65 20 43 7...   Const#544 string    "Cookie Crafter [Lv. 2200]"
	  +413D:Size=A: 43 61 6B 65 51 75 65 73 74 31   Const#545 string    "CakeQuest1"
	  +4149:Size=E: 43 6F 6F 6B 69 65 20 43 72...   Const#546 string    "Cookie Crafter"
	  +4158:Size=8: B9 19 6E C0 47 95 9F C0         Const#547 float     -2021.32007
	  +4161:Size=8: 13 EB F9 3F 2C E6 42 40         Const#548 float     37.7982254
	  +416A:Size=8: 37 89 41 60 5D 7E C7 C0         Const#549 float     -12028.7295
	  +4173:Size=8: CE 91 41 60 78 A4 EE 3F         Const#550 float     0.957576931
	  +417C:Size=8: 5D 53 C9 BF 63 A1 77 BE         Const#551 float     -8.80302053e-008
	  +4185:Size=8: 6A 87 EF 5F 81 71 D2 3F         Const#552 float     0.288177818
	  +418E:Size=8: 99 14 F3 5F 57 9A 72 3E         Const#553 float     6.9301187e-008
	  +4197:Size=8: 65 B2 2A 60 3B 2F 74 3E         Const#554 float     7.51931211e-008
	  +41A0:Size=8: 6A 87 EF 5F 81 71 D2 BF         Const#555 float     -0.288177818
	  +41A9:Size=8: 92 36 98 FF 3D EF 6B BE         Const#556 float     -5.2032135e-008
	  +41B2:Size=4: B1 08 00 00                     Const#557 integer   2225
	  +41B7:Size=4: C9 08 00 00                     Const#558 integer   2249
	  +41BD:Size=15: 43 61 6B 65 20 47 75 61 7...   Const#559 string    "Cake Guard [Lv. 2225]"
	  +41D4:Size=A: 43 61 6B 65 20 47 75 61 72 64   Const#560 string    "Cake Guard"
	  +41DF:Size=4: CA 08 00 00                     Const#561 integer   2250
	  +41E4:Size=4: E2 08 00 00                     Const#562 integer   2274
	  +41EA:Size=17: 42 61 6B 69 6E 67 20 53 7...   Const#563 string    "Baking Staff [Lv. 2250]"
	  +4203:Size=A: 43 61 6B 65 51 75 65 73 74 32   Const#564 string    "CakeQuest2"
	  +420F:Size=C: 42 61 6B 69 6E 67 20 53 74...   Const#565 string    "Baking Staff"
	  +421C:Size=8: ED 99 25 01 AA 1F 9E C0         Const#566 float     -1927.91602
	  +4225:Size=8: 1B 2A 6B 40 29 E6 42 40         Const#567 float     37.7981339
	  +422E:Size=8: A3 92 3A 01 45 15 C9 C0         Const#568 float     -12842.5391
	  +4237:Size=8: 72 C4 18 60 38 FA EE BF         Const#569 float     -0.96804446
	  +4240:Size=8: 8F 1A 95 9F E0 A9 66 3E         Const#570 float     4.22142143e-008
	  +4249:Size=8: 50 0E 5A A0 C1 0C D0 3F         Const#571 float     0.250778586
	  +4252:Size=8: 5A 18 5F C0 20 7F 69 3E         Const#572 float     4.74911062e-008
	  +425B:Size=8: 84 82 3D A0 8C 18 50 3E         Const#573 float     1.49904711e-008
	  +4264:Size=8: 50 0E 5A A0 C1 0C D0 BF         Const#574 float     -0.250778586
	  +426D:Size=8: 4E 20 9D 3F 9A 5E 5C 3E         Const#575 float     2.64211941e-008
	  +4276:Size=4: E3 08 00 00                     Const#576 integer   2275
	  +427B:Size=4: FB 08 00 00                     Const#577 integer   2299
	  +4281:Size=15: 48 65 61 64 20 42 61 6B 6...   Const#578 string    "Head Baker [Lv. 2275]"
	  +4298:Size=A: 48 65 61 64 20 42 61 6B 65 72   Const#579 string    "Head Baker"
	  +42A3:Size=4: FC 08 00 00                     Const#580 integer   2300
	  +42A8:Size=4: 14 09 00 00                     Const#581 integer   2324
	  +42AE:Size=18: 43 6F 63 6F 61 20 57 61 7...   Const#582 string    "Cocoa Warrior [Lv. 2300]"
	  +42C8:Size=A: 43 68 6F 63 51 75 65 73 74 31   Const#583 string    "ChocQuest1"
	  +42D4:Size=D: 43 6F 63 6F 61 20 57 61 72...   Const#584 string    "Cocoa Warrior"
	  +42E2:Size=8: 94 11 17 80 C6 F7 6C 40         Const#585 float     231.742981
	  +42EB:Size=8: 24 37 79 80 DD 55 39 40         Const#586 float     25.3354111
	  +42F4:Size=8: E6 3F A4 DF 86 D3 C7 C0         Const#587 float     -12199.0537
	  +42FD:Size=8: EF 4A C0 1F E6 F1 EF 3F         Const#588 float     0.998278677
	  +4306:Size=8: 45 8C B5 5F F1 B3 6B BE         Const#589 float     -5.16006757e-008
	  +430F:Size=8: 20 97 59 00 2A 07 AE 3F         Const#590 float     0.0586484075
	  +4318:Size=8: 07 39 51 E0 BD C0 69 3E         Const#591 float     4.79685092e-008
	  +4321:Size=8: 70 6C DB 3F A0 00 71 3E         Const#592 float     6.33390442e-008
	  +432A:Size=8: 20 97 59 00 2A 07 AE BF         Const#593 float     -0.0586484075
	  +4333:Size=8: 2D 46 18 80 CE 37 70 BE         Const#594 float     -6.04167383e-008
	  +433C:Size=4: 15 09 00 00                     Const#595 integer   2325
	  +4341:Size=4: 2D 09 00 00                     Const#596 integer   2349
	  +4347:Size=20: 43 68 6F 63 6F 6C 61 74 6...   Const#597 string    "Chocolate Bar Battler [Lv. 2325]"
	  +4369:Size=15: 43 68 6F 63 6F 6C 61 74 6...   Const#598 string    "Chocolate Bar Battler"
	  +437F:Size=4: 2E 09 00 00                     Const#599 integer   2350
	  +4384:Size=4: 46 09 00 00                     Const#600 integer   2374
	  +438A:Size=16: 53 77 65 65 74 20 54 68 6...   Const#601 string    "Sweet Thief [Lv. 2350]"
	  +43A2:Size=A: 43 68 6F 63 51 75 65 73 74 32   Const#602 string    "ChocQuest2"
	  +43AE:Size=B: 53 77 65 65 74 20 54 68 69...   Const#603 string    "Sweet Thief"
	  +43BA:Size=8: 15 90 F6 3F C0 BB 62 40         Const#604 float     149.867218
	  +43C3:Size=8: EE A4 74 9F D2 D1 38 40         Const#605 float     24.8196201
	  +43CC:Size=8: 3D 9B 55 9F C3 F3 C8 C0         Const#606 float     -12775.5283
	  +43D5:Size=8: E9 25 05 E0 5F 00 A3 BF         Const#607 float     -0.0371122323
	  +43DE:Size=8: 13 F6 29 60 25 2C 73 BE         Const#608 float     -7.14229245e-008
	  +43E7:Size=8: 48 90 42 40 5B FA EF BF         Const#609 float     -0.99931109
	  +43F0:Size=8: A2 C9 31 A0 0F 9E 72 BE         Const#610 float     -6.93553162e-008
	  +43F9:Size=8: F8 17 2A 40 87 7E 72 BE         Const#611 float     -6.88964548e-008
	  +4402:Size=8: 48 90 42 40 5B FA EF 3F         Const#612 float     0.99931109
	  +440B:Size=8: 66 81 EB 9F 11 EB 71 3E         Const#613 float     6.6750637e-008
	  +4414:Size=4: 47 09 00 00                     Const#614 integer   2375
	  +441A:Size=16: 43 61 6E 64 79 20 52 65 6...   Const#615 string    "Candy Rebel [Lv. 2375]"
	  +4432:Size=B: 43 61 6E 64 79 20 52 65 62...   Const#616 string    "Candy Rebel"
	Upvalues: 1
	  Upv#1 is parent function's Upv#1              name: _ENV
	Instructions: 2436
	  +03C7: 06 40 40 00   line#10   GETTABUP 0 0 -2         <1>   R0 = Upv#1@_ENV["game"]                         -- It's Const#2
	  +03CB: 0C 80 40 00   line#10   SELF 0 0 -3             <2>   R1 = R0;  R0 = R0["GetService"]                 -- It's Const#3   -- prepare for R0:GetService()
	  +03CF: 81 C0 00 00   line#10   LOADK 2 -4              <3>   R2 = "Players"                                  -- It's Const#4
	  +03D3: 24 80 80 01   line#10   CALL 0 3 2              <4>   R0 = R0(R1, R2)
	  +03D7: 07 00 41 00   line#10   GETTABLE 0 0 -5         <5>   R0 = R0["LocalPlayer"]                          -- It's Const#5
	  +03DB: 07 40 41 00   line#10   GETTABLE 0 0 -6         <6>   R0 = R0["Data"]                                 -- It's Const#6
	  +03DF: 07 00 40 00   line#10   GETTABLE 0 0 -1         <7>   R0 = R0["Level"]                                -- It's Const#1
	  +03E3: 07 80 41 00   line#10   GETTABLE 0 0 -7         <8>   R0 = R0["Value"]                                -- It's Const#7
	  +03E7: 08 00 00 80   line#10   SETTABUP 0 -1 0         <9>   Upv#1@_ENV["Level"] = R0                        -- It's Const#1
	  +03EB: 06 C0 41 00   line#11   GETTABUP 0 0 -8        <10>   R0 = Upv#1@_ENV["W"]                            -- It's Const#8
	  +03EF: 22 00 00 00   line#11   TEST 0 0               <11>   if R0 then GOTO <13>
	  +03F3: 1E 40 AE 80   line#11   JMP 0 698              <12>   GOTO <711>
	  +03F7: 06 00 40 00   line#12   GETTABUP 0 0 -1        <13>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +03FB: 5F 00 42 00   line#12   EQ 1 0 -9              <14>   if R0 ~= 1 then GOTO <16>                       -- It's Const#9
	  +03FF: 1E 80 00 80   line#12   JMP 0 3                <15>   GOTO <19>
	  +0403: 06 00 40 00   line#12   GETTABUP 0 0 -1        <16>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +0407: 21 40 42 00   line#12   LE 0 0 -10             <17>   if R0 <= 9 then GOTO <19>                       -- It's Const#10
	  +040B: 1E 00 05 80   line#12   JMP 0 21               <18>   GOTO <40>
	  +040F: 08 C0 42 85   line#13   SETTABUP 0 -11 -12     <19>   Upv#1@_ENV["Mon"] = "Bandit [Lv. 5]"            -- It's Const#11, Const#12
	  +0413: 08 00 42 86   line#14   SETTABUP 0 -13 -9      <20>   Upv#1@_ENV["LQuest"] = 1                        -- It's Const#13, Const#9
	  +0417: 08 80 C3 86   line#15   SETTABUP 0 -14 -15     <21>   Upv#1@_ENV["NQuest"] = "BanditQuest1"           -- It's Const#14, Const#15
	  +041B: 08 00 C4 87   line#16   SETTABUP 0 -16 -17     <22>   Upv#1@_ENV["NameMon"] = "Bandit"                -- It's Const#16, Const#17
	  +041F: 06 80 44 00   line#17   GETTABUP 0 0 -19       <23>   R0 = Upv#1@_ENV["CFrame"]                       -- It's Const#19
	  +0423: 07 C0 44 00   line#17   GETTABLE 0 0 -20       <24>   R0 = R0["new"]                                  -- It's Const#20
	  +0427: 41 00 05 00   line#17   LOADK 1 -21            <25>   R1 = 1059.37195                                 -- It's Const#21
	  +042B: 81 40 05 00   line#17   LOADK 2 -22            <26>   R2 = 15.4495068                                 -- It's Const#22
	  +042F: C1 80 05 00   line#17   LOADK 3 -23            <27>   R3 = 1550.4231                                  -- It's Const#23
	  +0433: 01 C1 05 00   line#17   LOADK 4 -24            <28>   R4 = 0.939700544                                -- It's Const#24
	  +0437: 41 01 06 00   line#17   LOADK 5 -25            <29>   R5 = 0                                          -- It's Const#25
	  +043B: 81 41 06 00   line#17   LOADK 6 -26            <30>   R6 = (-0.341998369)                             -- It's Const#26
	  +043F: C1 01 06 00   line#17   LOADK 7 -25            <31>   R7 = 0                                          -- It's Const#25
	  +0443: 01 02 02 00   line#17   LOADK 8 -9             <32>   R8 = 1                                          -- It's Const#9
	  +0447: 41 02 06 00   line#17   LOADK 9 -25            <33>   R9 = 0                                          -- It's Const#25
	  +044B: 81 82 06 00   line#17   LOADK 10 -27           <34>   R10 = 0.341998369                               -- It's Const#27
	  +044F: C1 02 06 00   line#17   LOADK 11 -25           <35>   R11 = 0                                         -- It's Const#25
	  +0453: 01 C3 05 00   line#17   LOADK 12 -24           <36>   R12 = 0.939700544                               -- It's Const#24
	  +0457: 24 80 80 06   line#17   CALL 0 13 2            <37>   R0 = R0(R1,..,R12)
	  +045B: 08 00 80 88   line#17   SETTABUP 0 -18 0       <38>   Upv#1@_ENV["CFrameQuest"] = R0                  -- It's Const#18
	  +045F: 1E C0 56 82   line#17   JMP 0 2396             <39>   GOTO <2436>
	  +0463: 06 00 40 00   line#18   GETTABUP 0 0 -1        <40>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +0467: 5F C0 46 00   line#18   EQ 1 0 -28             <41>   if R0 ~= 10 then GOTO <43>                      -- It's Const#28
	  +046B: 1E 80 00 80   line#18   JMP 0 3                <42>   GOTO <46>
	  +046F: 06 00 40 00   line#18   GETTABUP 0 0 -1        <43>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +0473: 21 00 47 00   line#18   LE 0 0 -29             <44>   if R0 <= 14 then GOTO <46>                      -- It's Const#29
	  +0477: 1E 00 05 80   line#18   JMP 0 21               <45>   GOTO <67>
	  +047B: 08 40 47 85   line#19   SETTABUP 0 -11 -30     <46>   Upv#1@_ENV["Mon"] = "Monkey [Lv. 14]"           -- It's Const#11, Const#30
	  +047F: 08 00 42 86   line#20   SETTABUP 0 -13 -9      <47>   Upv#1@_ENV["LQuest"] = 1                        -- It's Const#13, Const#9
	  +0483: 08 80 C7 86   line#21   SETTABUP 0 -14 -31     <48>   Upv#1@_ENV["NQuest"] = "JungleQuest"            -- It's Const#14, Const#31
	  +0487: 08 C0 C7 87   line#22   SETTABUP 0 -16 -32     <49>   Upv#1@_ENV["NameMon"] = "Monkey"                -- It's Const#16, Const#32
	  +048B: 06 80 44 00   line#23   GETTABUP 0 0 -19       <50>   R0 = Upv#1@_ENV["CFrame"]                       -- It's Const#19
	  +048F: 07 C0 44 00   line#23   GETTABLE 0 0 -20       <51>   R0 = R0["new"]                                  -- It's Const#20
	  +0493: 41 00 08 00   line#23   LOADK 1 -33            <52>   R1 = (-1598.08911)                              -- It's Const#33
	  +0497: 81 40 08 00   line#23   LOADK 2 -34            <53>   R2 = 35.5501175                                 -- It's Const#34
	  +049B: C1 80 08 00   line#23   LOADK 3 -35            <54>   R3 = 153.377838                                 -- It's Const#35
	  +049F: 01 01 06 00   line#23   LOADK 4 -25            <55>   R4 = 0                                          -- It's Const#25
	  +04A3: 41 01 06 00   line#23   LOADK 5 -25            <56>   R5 = 0                                          -- It's Const#25
	  +04A7: 81 01 02 00   line#23   LOADK 6 -9             <57>   R6 = 1                                          -- It's Const#9
	  +04AB: C1 01 06 00   line#23   LOADK 7 -25            <58>   R7 = 0                                          -- It's Const#25
	  +04AF: 01 02 02 00   line#23   LOADK 8 -9             <59>   R8 = 1                                          -- It's Const#9
	  +04B3: 41 02 06 00   line#23   LOADK 9 -25            <60>   R9 = 0                                          -- It's Const#25
	  +04B7: 81 C2 08 00   line#23   LOADK 10 -36           <61>   R10 = (-1)                                      -- It's Const#36
	  +04BB: C1 02 06 00   line#23   LOADK 11 -25           <62>   R11 = 0                                         -- It's Const#25
	  +04BF: 01 03 06 00   line#23   LOADK 12 -25           <63>   R12 = 0                                         -- It's Const#25
	  +04C3: 24 80 80 06   line#23   CALL 0 13 2            <64>   R0 = R0(R1,..,R12)
	  +04C7: 08 00 80 88   line#23   SETTABUP 0 -18 0       <65>   Upv#1@_ENV["CFrameQuest"] = R0                  -- It's Const#18
	  +04CB: 1E 00 50 82   line#23   JMP 0 2369             <66>   GOTO <2436>
	  +04CF: 06 00 40 00   line#24   GETTABUP 0 0 -1        <67>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +04D3: 5F 00 49 00   line#24   EQ 1 0 -37             <68>   if R0 ~= 15 then GOTO <70>                      -- It's Const#37
	  +04D7: 1E 80 00 80   line#24   JMP 0 3                <69>   GOTO <73>
	  +04DB: 06 00 40 00   line#24   GETTABUP 0 0 -1        <70>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +04DF: 21 40 49 00   line#24   LE 0 0 -38             <71>   if R0 <= 24 then GOTO <73>                      -- It's Const#38
	  +04E3: 1E 00 05 80   line#24   JMP 0 21               <72>   GOTO <94>
	  +04E7: 08 80 49 85   line#25   SETTABUP 0 -11 -39     <73>   Upv#1@_ENV["Mon"] = "Gorilla [Lv. 20]"          -- It's Const#11, Const#39
	  +04EB: 08 C0 49 86   line#26   SETTABUP 0 -13 -40     <74>   Upv#1@_ENV["LQuest"] = 2                        -- It's Const#13, Const#40
	  +04EF: 08 80 C7 86   line#27   SETTABUP 0 -14 -31     <75>   Upv#1@_ENV["NQuest"] = "JungleQuest"            -- It's Const#14, Const#31
	  +04F3: 08 00 CA 87   line#28   SETTABUP 0 -16 -41     <76>   Upv#1@_ENV["NameMon"] = "Gorilla"               -- It's Const#16, Const#41
	  +04F7: 06 80 44 00   line#29   GETTABUP 0 0 -19       <77>   R0 = Upv#1@_ENV["CFrame"]                       -- It's Const#19
	  +04FB: 07 C0 44 00   line#29   GETTABLE 0 0 -20       <78>   R0 = R0["new"]                                  -- It's Const#20
	  +04FF: 41 00 08 00   line#29   LOADK 1 -33            <79>   R1 = (-1598.08911)                              -- It's Const#33
	  +0503: 81 40 08 00   line#29   LOADK 2 -34            <80>   R2 = 35.5501175                                 -- It's Const#34
	  +0507: C1 80 08 00   line#29   LOADK 3 -35            <81>   R3 = 153.377838                                 -- It's Const#35
	  +050B: 01 01 06 00   line#29   LOADK 4 -25            <82>   R4 = 0                                          -- It's Const#25
	  +050F: 41 01 06 00   line#29   LOADK 5 -25            <83>   R5 = 0                                          -- It's Const#25
	  +0513: 81 01 02 00   line#29   LOADK 6 -9             <84>   R6 = 1                                          -- It's Const#9
	  +0517: C1 01 06 00   line#29   LOADK 7 -25            <85>   R7 = 0                                          -- It's Const#25
	  +051B: 01 02 02 00   line#29   LOADK 8 -9             <86>   R8 = 1                                          -- It's Const#9
	  +051F: 41 02 06 00   line#29   LOADK 9 -25            <87>   R9 = 0                                          -- It's Const#25
	  +0523: 81 C2 08 00   line#29   LOADK 10 -36           <88>   R10 = (-1)                                      -- It's Const#36
	  +0527: C1 02 06 00   line#29   LOADK 11 -25           <89>   R11 = 0                                         -- It's Const#25
	  +052B: 01 03 06 00   line#29   LOADK 12 -25           <90>   R12 = 0                                         -- It's Const#25
	  +052F: 24 80 80 06   line#29   CALL 0 13 2            <91>   R0 = R0(R1,..,R12)
	  +0533: 08 00 80 88   line#29   SETTABUP 0 -18 0       <92>   Upv#1@_ENV["CFrameQuest"] = R0                  -- It's Const#18
	  +0537: 1E 40 49 82   line#29   JMP 0 2342             <93>   GOTO <2436>
	  +053B: 06 00 40 00   line#30   GETTABUP 0 0 -1        <94>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +053F: 5F 40 4A 00   line#30   EQ 1 0 -42             <95>   if R0 ~= 25 then GOTO <97>                      -- It's Const#42
	  +0543: 1E 80 00 80   line#30   JMP 0 3                <96>   GOTO <100>
	  +0547: 06 00 40 00   line#30   GETTABUP 0 0 -1        <97>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +054B: 21 80 4A 00   line#30   LE 0 0 -43             <98>   if R0 <= 59 then GOTO <100>                     -- It's Const#43
	  +054F: 1E C0 01 80   line#30   JMP 0 8                <99>   GOTO <108>
	  +0553: 06 C0 4A 00   line#31   GETTABUP 0 0 -44      <100>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#44
	  +0557: 07 00 4B 00   line#31   GETTABLE 0 0 -45      <101>   R0 = R0["HOOK"]                                 -- It's Const#45
	  +055B: 22 00 00 00   line#31   TEST 0 0              <102>   if R0 then GOTO <104>
	  +055F: 1E C0 46 82   line#31   JMP 0 2332            <103>   GOTO <2436>
	  +0563: 06 40 4B 00   line#32   GETTABUP 0 0 -46      <104>   R0 = Upv#1@_ENV["pcall"]                        -- It's Const#46
	  +0567: 6C 00 00 00   line#59   CLOSURE 1 0           <105>   R1 = Function#1
	  +056B: 24 40 00 01   line#32   CALL 0 2 1            <106>   R0(R1)
	  +056F: 1E C0 45 82   line#60   JMP 0 2328            <107>   GOTO <2436>
	  +0573: 06 00 40 00   line#62   GETTABUP 0 0 -1       <108>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +0577: 5F 80 4B 00   line#62   EQ 1 0 -47            <109>   if R0 ~= 60 then GOTO <111>                     -- It's Const#47
	  +057B: 1E 80 00 80   line#62   JMP 0 3               <110>   GOTO <114>
	  +057F: 06 00 40 00   line#62   GETTABUP 0 0 -1       <111>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +0583: 21 C0 4B 00   line#62   LE 0 0 -48            <112>   if R0 <= 99 then GOTO <114>                     -- It's Const#48
	  +0587: 1E C0 01 80   line#62   JMP 0 8               <113>   GOTO <122>
	  +058B: 06 00 4C 00   line#63   GETTABUP 0 0 -49      <114>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#49
	  +058F: 07 40 4C 00   line#63   GETTABLE 0 0 -50      <115>   R0 = R0["KOOK"]                                 -- It's Const#50
	  +0593: 22 00 00 00   line#63   TEST 0 0              <116>   if R0 then GOTO <118>
	  +0597: 1E 40 43 82   line#63   JMP 0 2318            <117>   GOTO <2436>
	  +059B: 06 40 4B 00   line#64   GETTABUP 0 0 -46      <118>   R0 = Upv#1@_ENV["pcall"]                        -- It's Const#46
	  +059F: 6C 40 00 00   line#92   CLOSURE 1 1           <119>   R1 = Function#2
	  +05A3: 24 40 00 01   line#64   CALL 0 2 1            <120>   R0(R1)
	  +05A7: 1E 40 42 82   line#93   JMP 0 2314            <121>   GOTO <2436>
	  +05AB: 06 00 40 00   line#94   GETTABUP 0 0 -1       <122>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +05AF: 5F 80 4C 00   line#94   EQ 1 0 -51            <123>   if R0 ~= 100 then GOTO <125>                    -- It's Const#51
	  +05B3: 1E 80 00 80   line#94   JMP 0 3               <124>   GOTO <128>
	  +05B7: 06 00 40 00   line#94   GETTABUP 0 0 -1       <125>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +05BB: 21 C0 4C 00   line#94   LE 0 0 -52            <126>   if R0 <= 119 then GOTO <128>                    -- It's Const#52
	  +05BF: 1E 00 05 80   line#94   JMP 0 21              <127>   GOTO <149>
	  +05C3: 08 00 4D 85   line#95   SETTABUP 0 -11 -53    <128>   Upv#1@_ENV["Mon"] = "Snowman [Lv. 100]"         -- It's Const#11, Const#53
	  +05C7: 08 40 4D 86   line#96   SETTABUP 0 -13 -54    <129>   Upv#1@_ENV["LQuest"] = 2                        -- It's Const#13, Const#54
	  +05CB: 08 80 CD 86   line#97   SETTABUP 0 -14 -55    <130>   Upv#1@_ENV["NQuest"] = "SnowQuest"              -- It's Const#14, Const#55
	  +05CF: 08 C0 CD 87   line#98   SETTABUP 0 -16 -56    <131>   Upv#1@_ENV["NameMon"] = "Snowman"               -- It's Const#16, Const#56
	  +05D3: 06 00 4E 00   line#99   GETTABUP 0 0 -57      <132>   R0 = Upv#1@_ENV["CFrame"]                       -- It's Const#57
	  +05D7: 07 40 4E 00   line#99   GETTABLE 0 0 -58      <133>   R0 = R0["new"]                                  -- It's Const#58
	  +05DB: 41 80 0E 00   line#99   LOADK 1 -59           <134>   R1 = 1389.74451                                 -- It's Const#59
	  +05DF: 81 C0 0E 00   line#99   LOADK 2 -60           <135>   R2 = 88.1519318                                 -- It's Const#60
	  +05E3: C1 00 0F 00   line#99   LOADK 3 -61           <136>   R3 = (-1298.90796)                              -- It's Const#61
	  +05E7: 01 41 0F 00   line#99   LOADK 4 -62           <137>   R4 = (-0.342042685)                             -- It's Const#62
	  +05EB: 41 81 0F 00   line#99   LOADK 5 -63           <138>   R5 = 0                                          -- It's Const#63
	  +05EF: 81 C1 0F 00   line#99   LOADK 6 -64           <139>   R6 = 0.939684391                                -- It's Const#64
	  +05F3: C1 81 0F 00   line#99   LOADK 7 -63           <140>   R7 = 0                                          -- It's Const#63
	  +05F7: 01 02 02 00   line#99   LOADK 8 -9            <141>   R8 = 1                                          -- It's Const#9
	  +05FB: 41 82 0F 00   line#99   LOADK 9 -63           <142>   R9 = 0                                          -- It's Const#63
	  +05FF: 81 02 10 00   line#99   LOADK 10 -65          <143>   R10 = (-0.939684391)                            -- It's Const#65
	  +0603: C1 82 0F 00   line#99   LOADK 11 -63          <144>   R11 = 0                                         -- It's Const#63
	  +0607: 01 43 0F 00   line#99   LOADK 12 -62          <145>   R12 = (-0.342042685)                            -- It's Const#62
	  +060B: 24 80 80 06   line#99   CALL 0 13 2           <146>   R0 = R0(R1,..,R12)
	  +060F: 08 00 80 88   line#99   SETTABUP 0 -18 0      <147>   Upv#1@_ENV["CFrameQuest"] = R0                  -- It's Const#18
	  +0613: 1E 80 3B 82   line#99   JMP 0 2287            <148>   GOTO <2436>
	  +0617: 06 00 40 00   line#100  GETTABUP 0 0 -1       <149>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +061B: 5F 40 50 00   line#100  EQ 1 0 -66            <150>   if R0 ~= 120 then GOTO <152>                    -- It's Const#66
	  +061F: 1E 80 00 80   line#100  JMP 0 3               <151>   GOTO <155>
	  +0623: 06 00 40 00   line#100  GETTABUP 0 0 -1       <152>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +0627: 21 80 50 00   line#100  LE 0 0 -67            <153>   if R0 <= 149 then GOTO <155>                    -- It's Const#67
	  +062B: 1E 00 05 80   line#100  JMP 0 21              <154>   GOTO <176>
	  +062F: 08 C0 50 85   line#101  SETTABUP 0 -11 -68    <155>   Upv#1@_ENV["Mon"] = "Chief Petty Officer [Lv. 120]"   -- It's Const#11, Const#68
	  +0633: 08 00 42 86   line#102  SETTABUP 0 -13 -9     <156>   Upv#1@_ENV["LQuest"] = 1                        -- It's Const#13, Const#9
	  +0637: 08 00 D1 86   line#103  SETTABUP 0 -14 -69    <157>   Upv#1@_ENV["NQuest"] = "MarineQuest2"           -- It's Const#14, Const#69
	  +063B: 08 40 D1 87   line#104  SETTABUP 0 -16 -70    <158>   Upv#1@_ENV["NameMon"] = "Chief Petty Officer"   -- It's Const#16, Const#70
	  +063F: 06 00 4E 00   line#105  GETTABUP 0 0 -57      <159>   R0 = Upv#1@_ENV["CFrame"]                       -- It's Const#57
	  +0643: 07 40 4E 00   line#105  GETTABLE 0 0 -58      <160>   R0 = R0["new"]                                  -- It's Const#58
	  +0647: 41 80 11 00   line#105  LOADK 1 -71           <161>   R1 = (-5039.58643)                              -- It's Const#71
	  +064B: 81 C0 11 00   line#105  LOADK 2 -72           <162>   R2 = 27.3500385                                 -- It's Const#72
	  +064F: C1 00 12 00   line#105  LOADK 3 -73           <163>   R3 = 4324.68018                                 -- It's Const#73
	  +0653: 01 81 0F 00   line#105  LOADK 4 -63           <164>   R4 = 0                                          -- It's Const#63
	  +0657: 41 81 0F 00   line#105  LOADK 5 -63           <165>   R5 = 0                                          -- It's Const#63
	  +065B: 81 C1 08 00   line#105  LOADK 6 -36           <166>   R6 = (-1)                                       -- It's Const#36
	  +065F: C1 81 0F 00   line#105  LOADK 7 -63           <167>   R7 = 0                                          -- It's Const#63
	  +0663: 01 02 02 00   line#105  LOADK 8 -9            <168>   R8 = 1                                          -- It's Const#9
	  +0667: 41 82 0F 00   line#105  LOADK 9 -63           <169>   R9 = 0                                          -- It's Const#63
	  +066B: 81 02 02 00   line#105  LOADK 10 -9           <170>   R10 = 1                                         -- It's Const#9
	  +066F: C1 82 0F 00   line#105  LOADK 11 -63          <171>   R11 = 0                                         -- It's Const#63
	  +0673: 01 83 0F 00   line#105  LOADK 12 -63          <172>   R12 = 0                                         -- It's Const#63
	  +0677: 24 80 80 06   line#105  CALL 0 13 2           <173>   R0 = R0(R1,..,R12)
	  +067B: 08 00 80 88   line#105  SETTABUP 0 -18 0      <174>   Upv#1@_ENV["CFrameQuest"] = R0                  -- It's Const#18
	  +067F: 1E C0 34 82   line#105  JMP 0 2260            <175>   GOTO <2436>
	  +0683: 06 00 40 00   line#106  GETTABUP 0 0 -1       <176>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +0687: 5F 40 52 00   line#106  EQ 1 0 -74            <177>   if R0 ~= 150 then GOTO <179>                    -- It's Const#74
	  +068B: 1E 80 00 80   line#106  JMP 0 3               <178>   GOTO <182>
	  +068F: 06 00 40 00   line#106  GETTABUP 0 0 -1       <179>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +0693: 21 80 52 00   line#106  LE 0 0 -75            <180>   if R0 <= 174 then GOTO <182>                    -- It's Const#75
	  +0697: 1E 00 05 80   line#106  JMP 0 21              <181>   GOTO <203>
	  +069B: 08 C0 52 85   line#107  SETTABUP 0 -11 -76    <182>   Upv#1@_ENV["Mon"] = "Sky Bandit [Lv. 150]"      -- It's Const#11, Const#76
	  +069F: 08 00 42 86   line#108  SETTABUP 0 -13 -9     <183>   Upv#1@_ENV["LQuest"] = 1                        -- It's Const#13, Const#9
	  +06A3: 08 00 D3 86   line#109  SETTABUP 0 -14 -77    <184>   Upv#1@_ENV["NQuest"] = "SkyQuest"               -- It's Const#14, Const#77
	  +06A7: 08 40 D3 87   line#110  SETTABUP 0 -16 -78    <185>   Upv#1@_ENV["NameMon"] = "Sky Bandit"            -- It's Const#16, Const#78
	  +06AB: 06 00 4E 00   line#111  GETTABUP 0 0 -57      <186>   R0 = Upv#1@_ENV["CFrame"]                       -- It's Const#57
	  +06AF: 07 40 4E 00   line#111  GETTABLE 0 0 -58      <187>   R0 = R0["new"]                                  -- It's Const#58
	  +06B3: 41 80 13 00   line#111  LOADK 1 -79           <188>   R1 = (-4839.53027)                              -- It's Const#79
	  +06B7: 81 C0 13 00   line#111  LOADK 2 -80           <189>   R2 = 716.368591                                 -- It's Const#80
	  +06BB: C1 00 14 00   line#111  LOADK 3 -81           <190>   R3 = (-2619.44165)                              -- It's Const#81
	  +06BF: 01 41 14 00   line#111  LOADK 4 -82           <191>   R4 = 0.866007268                                -- It's Const#82
	  +06C3: 41 81 0F 00   line#111  LOADK 5 -63           <192>   R5 = 0                                          -- It's Const#63
	  +06C7: 81 81 14 00   line#111  LOADK 6 -83           <193>   R6 = 0.500031412                                -- It's Const#83
	  +06CB: C1 81 0F 00   line#111  LOADK 7 -63           <194>   R7 = 0                                          -- It's Const#63
	  +06CF: 01 02 02 00   line#111  LOADK 8 -9            <195>   R8 = 1                                          -- It's Const#9
	  +06D3: 41 82 0F 00   line#111  LOADK 9 -63           <196>   R9 = 0                                          -- It's Const#63
	  +06D7: 81 C2 14 00   line#111  LOADK 10 -84          <197>   R10 = (-0.500031412)                            -- It's Const#84
	  +06DB: C1 82 0F 00   line#111  LOADK 11 -63          <198>   R11 = 0                                         -- It's Const#63
	  +06DF: 01 43 14 00   line#111  LOADK 12 -82          <199>   R12 = 0.866007268                               -- It's Const#82
	  +06E3: 24 80 80 06   line#111  CALL 0 13 2           <200>   R0 = R0(R1,..,R12)
	  +06E7: 08 00 80 88   line#111  SETTABUP 0 -18 0      <201>   Upv#1@_ENV["CFrameQuest"] = R0                  -- It's Const#18
	  +06EB: 1E 00 2E 82   line#111  JMP 0 2233            <202>   GOTO <2436>
	  +06EF: 06 00 40 00   line#112  GETTABUP 0 0 -1       <203>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +06F3: 5F 00 55 00   line#112  EQ 1 0 -85            <204>   if R0 ~= 175 then GOTO <206>                    -- It's Const#85
	  +06F7: 1E 80 00 80   line#112  JMP 0 3               <205>   GOTO <209>
	  +06FB: 06 00 40 00   line#112  GETTABUP 0 0 -1       <206>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +06FF: 21 40 55 00   line#112  LE 0 0 -86            <207>   if R0 <= 189 then GOTO <209>                    -- It's Const#86
	  +0703: 1E 00 05 80   line#112  JMP 0 21              <208>   GOTO <230>
	  +0707: 08 80 55 85   line#113  SETTABUP 0 -11 -87    <209>   Upv#1@_ENV["Mon"] = "Dark Master [Lv. 175]"     -- It's Const#11, Const#87
	  +070B: 08 40 4D 86   line#114  SETTABUP 0 -13 -54    <210>   Upv#1@_ENV["LQuest"] = 2                        -- It's Const#13, Const#54
	  +070F: 08 00 D3 86   line#115  SETTABUP 0 -14 -77    <211>   Upv#1@_ENV["NQuest"] = "SkyQuest"               -- It's Const#14, Const#77
	  +0713: 08 C0 D5 87   line#116  SETTABUP 0 -16 -88    <212>   Upv#1@_ENV["NameMon"] = "Dark Master"           -- It's Const#16, Const#88
	  +0717: 06 00 4E 00   line#117  GETTABUP 0 0 -57      <213>   R0 = Upv#1@_ENV["CFrame"]                       -- It's Const#57
	  +071B: 07 40 4E 00   line#117  GETTABLE 0 0 -58      <214>   R0 = R0["new"]                                  -- It's Const#58
	  +071F: 41 80 13 00   line#117  LOADK 1 -79           <215>   R1 = (-4839.53027)                              -- It's Const#79
	  +0723: 81 C0 13 00   line#117  LOADK 2 -80           <216>   R2 = 716.368591                                 -- It's Const#80
	  +0727: C1 00 14 00   line#117  LOADK 3 -81           <217>   R3 = (-2619.44165)                              -- It's Const#81
	  +072B: 01 41 14 00   line#117  LOADK 4 -82           <218>   R4 = 0.866007268                                -- It's Const#82
	  +072F: 41 81 0F 00   line#117  LOADK 5 -63           <219>   R5 = 0                                          -- It's Const#63
	  +0733: 81 81 14 00   line#117  LOADK 6 -83           <220>   R6 = 0.500031412                                -- It's Const#83
	  +0737: C1 81 0F 00   line#117  LOADK 7 -63           <221>   R7 = 0                                          -- It's Const#63
	  +073B: 01 02 02 00   line#117  LOADK 8 -9            <222>   R8 = 1                                          -- It's Const#9
	  +073F: 41 82 0F 00   line#117  LOADK 9 -63           <223>   R9 = 0                                          -- It's Const#63
	  +0743: 81 C2 14 00   line#117  LOADK 10 -84          <224>   R10 = (-0.500031412)                            -- It's Const#84
	  +0747: C1 82 0F 00   line#117  LOADK 11 -63          <225>   R11 = 0                                         -- It's Const#63
	  +074B: 01 43 14 00   line#117  LOADK 12 -82          <226>   R12 = 0.866007268                               -- It's Const#82
	  +074F: 24 80 80 06   line#117  CALL 0 13 2           <227>   R0 = R0(R1,..,R12)
	  +0753: 08 00 80 88   line#117  SETTABUP 0 -18 0      <228>   Upv#1@_ENV["CFrameQuest"] = R0                  -- It's Const#18
	  +0757: 1E 40 27 82   line#117  JMP 0 2206            <229>   GOTO <2436>
	  +075B: 06 00 40 00   line#118  GETTABUP 0 0 -1       <230>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +075F: 5F 00 56 00   line#118  EQ 1 0 -89            <231>   if R0 ~= 190 then GOTO <233>                    -- It's Const#89
	  +0763: 1E 80 00 80   line#118  JMP 0 3               <232>   GOTO <236>
	  +0767: 06 00 40 00   line#118  GETTABUP 0 0 -1       <233>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +076B: 21 40 56 00   line#118  LE 0 0 -90            <234>   if R0 <= 209 then GOTO <236>                    -- It's Const#90
	  +076F: 1E 00 05 80   line#118  JMP 0 21              <235>   GOTO <257>
	  +0773: 08 80 56 85   line#119  SETTABUP 0 -11 -91    <236>   Upv#1@_ENV["Mon"] = "Prisoner [Lv. 190]"        -- It's Const#11, Const#91
	  +0777: 08 00 42 86   line#120  SETTABUP 0 -13 -9     <237>   Upv#1@_ENV["LQuest"] = 1                        -- It's Const#13, Const#9
	  +077B: 08 C0 D6 86   line#121  SETTABUP 0 -14 -92    <238>   Upv#1@_ENV["NQuest"] = "PrisonerQuest"          -- It's Const#14, Const#92
	  +077F: 08 00 D7 87   line#122  SETTABUP 0 -16 -93    <239>   Upv#1@_ENV["NameMon"] = "Prisoner"              -- It's Const#16, Const#93
	  +0783: 06 00 4E 00   line#123  GETTABUP 0 0 -57      <240>   R0 = Upv#1@_ENV["CFrame"]                       -- It's Const#57
	  +0787: 07 40 4E 00   line#123  GETTABLE 0 0 -58      <241>   R0 = R0["new"]                                  -- It's Const#58
	  +078B: 41 40 17 00   line#123  LOADK 1 -94           <242>   R1 = 5308.93115                                 -- It's Const#94
	  +078F: 81 80 17 00   line#123  LOADK 2 -95           <243>   R2 = 1.65517521                                 -- It's Const#95
	  +0793: C1 C0 17 00   line#123  LOADK 3 -96           <244>   R3 = 475.120514                                 -- It's Const#96
	  +0797: 01 01 18 00   line#123  LOADK 4 -97           <245>   R4 = (-0.0894274712)                            -- It's Const#97
	  +079B: 41 41 18 00   line#123  LOADK 5 -98           <246>   R5 = (-5.00292918e-009)                         -- It's Const#98
	  +079F: 81 81 18 00   line#123  LOADK 6 -99           <247>   R6 = (-0.995993316)                             -- It's Const#99
	  +07A3: C1 C1 18 00   line#123  LOADK 7 -100          <248>   R7 = 1.60817859e-009                            -- It's Const#100
	  +07A7: 01 02 02 00   line#123  LOADK 8 -9            <249>   R8 = 1                                          -- It's Const#9
	  +07AB: 41 02 19 00   line#123  LOADK 9 -101          <250>   R9 = (-5.16744869e-009)                         -- It's Const#101
	  +07AF: 81 42 19 00   line#123  LOADK 10 -102         <251>   R10 = 0.995993316                               -- It's Const#102
	  +07B3: C1 82 19 00   line#123  LOADK 11 -103         <252>   R11 = (-2.06384709e-009)                        -- It's Const#103
	  +07B7: 01 03 18 00   line#123  LOADK 12 -97          <253>   R12 = (-0.0894274712)                           -- It's Const#97
	  +07BB: 24 80 80 06   line#123  CALL 0 13 2           <254>   R0 = R0(R1,..,R12)
	  +07BF: 08 00 80 88   line#123  SETTABUP 0 -18 0      <255>   Upv#1@_ENV["CFrameQuest"] = R0                  -- It's Const#18
	  +07C3: 1E 80 20 82   line#123  JMP 0 2179            <256>   GOTO <2436>
	  +07C7: 06 00 40 00   line#124  GETTABUP 0 0 -1       <257>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +07CB: 5F C0 59 00   line#124  EQ 1 0 -104           <258>   if R0 ~= 210 then GOTO <260>                    -- It's Const#104
	  +07CF: 1E 80 00 80   line#124  JMP 0 3               <259>   GOTO <263>
	  +07D3: 06 00 40 00   line#124  GETTABUP 0 0 -1       <260>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +07D7: 21 00 5A 00   line#124  LE 0 0 -105           <261>   if R0 <= 249 then GOTO <263>                    -- It's Const#105
	  +07DB: 1E 00 05 80   line#124  JMP 0 21              <262>   GOTO <284>
	  +07DF: 08 40 5A 85   line#125  SETTABUP 0 -11 -106   <263>   Upv#1@_ENV["Mon"] = "Dangerous Prisoner [Lv. 210]"   -- It's Const#11, Const#106
	  +07E3: 08 40 4D 86   line#126  SETTABUP 0 -13 -54    <264>   Upv#1@_ENV["LQuest"] = 2                        -- It's Const#13, Const#54
	  +07E7: 08 C0 D6 86   line#127  SETTABUP 0 -14 -92    <265>   Upv#1@_ENV["NQuest"] = "PrisonerQuest"          -- It's Const#14, Const#92
	  +07EB: 08 80 DA 87   line#128  SETTABUP 0 -16 -107   <266>   Upv#1@_ENV["NameMon"] = "Dangerous Prisoner"    -- It's Const#16, Const#107
	  +07EF: 06 00 4E 00   line#129  GETTABUP 0 0 -57      <267>   R0 = Upv#1@_ENV["CFrame"]                       -- It's Const#57
	  +07F3: 07 40 4E 00   line#129  GETTABLE 0 0 -58      <268>   R0 = R0["new"]                                  -- It's Const#58
	  +07F7: 41 40 17 00   line#129  LOADK 1 -94           <269>   R1 = 5308.93115                                 -- It's Const#94
	  +07FB: 81 80 17 00   line#129  LOADK 2 -95           <270>   R2 = 1.65517521                                 -- It's Const#95
	  +07FF: C1 C0 17 00   line#129  LOADK 3 -96           <271>   R3 = 475.120514                                 -- It's Const#96
	  +0803: 01 01 18 00   line#129  LOADK 4 -97           <272>   R4 = (-0.0894274712)                            -- It's Const#97
	  +0807: 41 41 18 00   line#129  LOADK 5 -98           <273>   R5 = (-5.00292918e-009)                         -- It's Const#98
	  +080B: 81 81 18 00   line#129  LOADK 6 -99           <274>   R6 = (-0.995993316)                             -- It's Const#99
	  +080F: C1 C1 18 00   line#129  LOADK 7 -100          <275>   R7 = 1.60817859e-009                            -- It's Const#100
	  +0813: 01 02 02 00   line#129  LOADK 8 -9            <276>   R8 = 1                                          -- It's Const#9
	  +0817: 41 02 19 00   line#129  LOADK 9 -101          <277>   R9 = (-5.16744869e-009)                         -- It's Const#101
	  +081B: 81 42 19 00   line#129  LOADK 10 -102         <278>   R10 = 0.995993316                               -- It's Const#102
	  +081F: C1 82 19 00   line#129  LOADK 11 -103         <279>   R11 = (-2.06384709e-009)                        -- It's Const#103
	  +0823: 01 03 18 00   line#129  LOADK 12 -97          <280>   R12 = (-0.0894274712)                           -- It's Const#97
	  +0827: 24 80 80 06   line#129  CALL 0 13 2           <281>   R0 = R0(R1,..,R12)
	  +082B: 08 00 80 88   line#129  SETTABUP 0 -18 0      <282>   Upv#1@_ENV["CFrameQuest"] = R0                  -- It's Const#18
	  +082F: 1E C0 19 82   line#129  JMP 0 2152            <283>   GOTO <2436>
	  +0833: 06 00 40 00   line#130  GETTABUP 0 0 -1       <284>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +0837: 5F C0 5A 00   line#130  EQ 1 0 -108           <285>   if R0 ~= 250 then GOTO <287>                    -- It's Const#108
	  +083B: 1E 80 00 80   line#130  JMP 0 3               <286>   GOTO <290>
	  +083F: 06 00 40 00   line#130  GETTABUP 0 0 -1       <287>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +0843: 21 00 5B 00   line#130  LE 0 0 -109           <288>   if R0 <= 274 then GOTO <290>                    -- It's Const#109
	  +0847: 1E 00 05 80   line#130  JMP 0 21              <289>   GOTO <311>
	  +084B: 08 40 5B 85   line#131  SETTABUP 0 -11 -110   <290>   Upv#1@_ENV["Mon"] = "Toga Warrior [Lv. 250]"    -- It's Const#11, Const#110
	  +084F: 08 00 42 86   line#132  SETTABUP 0 -13 -9     <291>   Upv#1@_ENV["LQuest"] = 1                        -- It's Const#13, Const#9
	  +0853: 08 80 DB 86   line#133  SETTABUP 0 -14 -111   <292>   Upv#1@_ENV["NQuest"] = "ColosseumQuest"         -- It's Const#14, Const#111
	  +0857: 08 C0 DB 87   line#134  SETTABUP 0 -16 -112   <293>   Upv#1@_ENV["NameMon"] = "Toga Warrior"          -- It's Const#16, Const#112
	  +085B: 06 00 4E 00   line#135  GETTABUP 0 0 -57      <294>   R0 = Upv#1@_ENV["CFrame"]                       -- It's Const#57
	  +085F: 07 40 4E 00   line#135  GETTABLE 0 0 -58      <295>   R0 = R0["new"]                                  -- It's Const#58
	  +0863: 41 00 1C 00   line#135  LOADK 1 -113          <296>   R1 = (-1580.04663)                              -- It's Const#113
	  +0867: 81 40 1C 00   line#135  LOADK 2 -114          <297>   R2 = 6.35000277                                 -- It's Const#114
	  +086B: C1 80 1C 00   line#135  LOADK 3 -115          <298>   R3 = (-2986.47534)                              -- It's Const#115
	  +086F: 01 C1 1C 00   line#135  LOADK 4 -116          <299>   R4 = (-0.515037298)                             -- It's Const#116
	  +0873: 41 81 0F 00   line#135  LOADK 5 -63           <300>   R5 = 0                                          -- It's Const#63
	  +0877: 81 01 1D 00   line#135  LOADK 6 -117          <301>   R6 = (-0.857167721)                             -- It's Const#117
	  +087B: C1 81 0F 00   line#135  LOADK 7 -63           <302>   R7 = 0                                          -- It's Const#63
	  +087F: 01 02 02 00   line#135  LOADK 8 -9            <303>   R8 = 1                                          -- It's Const#9
	  +0883: 41 82 0F 00   line#135  LOADK 9 -63           <304>   R9 = 0                                          -- It's Const#63
	  +0887: 81 42 1D 00   line#135  LOADK 10 -118         <305>   R10 = 0.857167721                               -- It's Const#118
	  +088B: C1 82 0F 00   line#135  LOADK 11 -63          <306>   R11 = 0                                         -- It's Const#63
	  +088F: 01 C3 1C 00   line#135  LOADK 12 -116         <307>   R12 = (-0.515037298)                            -- It's Const#116
	  +0893: 24 80 80 06   line#135  CALL 0 13 2           <308>   R0 = R0(R1,..,R12)
	  +0897: 08 00 80 88   line#135  SETTABUP 0 -18 0      <309>   Upv#1@_ENV["CFrameQuest"] = R0                  -- It's Const#18
	  +089B: 1E 00 13 82   line#135  JMP 0 2125            <310>   GOTO <2436>
	  +089F: 06 00 40 00   line#136  GETTABUP 0 0 -1       <311>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +08A3: 5F 80 5D 00   line#136  EQ 1 0 -119           <312>   if R0 ~= 275 then GOTO <314>                    -- It's Const#119
	  +08A7: 1E 80 00 80   line#136  JMP 0 3               <313>   GOTO <317>
	  +08AB: 06 00 40 00   line#136  GETTABUP 0 0 -1       <314>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +08AF: 21 C0 5D 00   line#136  LE 0 0 -120           <315>   if R0 <= 299 then GOTO <317>                    -- It's Const#120
	  +08B3: 1E 00 05 80   line#136  JMP 0 21              <316>   GOTO <338>
	  +08B7: 08 00 5E 85   line#137  SETTABUP 0 -11 -121   <317>   Upv#1@_ENV["Mon"] = "Gladiator [Lv. 275]"       -- It's Const#11, Const#121
	  +08BB: 08 40 4D 86   line#138  SETTABUP 0 -13 -54    <318>   Upv#1@_ENV["LQuest"] = 2                        -- It's Const#13, Const#54
	  +08BF: 08 80 DB 86   line#139  SETTABUP 0 -14 -111   <319>   Upv#1@_ENV["NQuest"] = "ColosseumQuest"         -- It's Const#14, Const#111
	  +08C3: 08 40 DE 87   line#140  SETTABUP 0 -16 -122   <320>   Upv#1@_ENV["NameMon"] = "Gladiator"             -- It's Const#16, Const#122
	  +08C7: 06 00 4E 00   line#141  GETTABUP 0 0 -57      <321>   R0 = Upv#1@_ENV["CFrame"]                       -- It's Const#57
	  +08CB: 07 40 4E 00   line#141  GETTABLE 0 0 -58      <322>   R0 = R0["new"]                                  -- It's Const#58
	  +08CF: 41 00 1C 00   line#141  LOADK 1 -113          <323>   R1 = (-1580.04663)                              -- It's Const#113
	  +08D3: 81 40 1C 00   line#141  LOADK 2 -114          <324>   R2 = 6.35000277                                 -- It's Const#114
	  +08D7: C1 80 1C 00   line#141  LOADK 3 -115          <325>   R3 = (-2986.47534)                              -- It's Const#115
	  +08DB: 01 C1 1C 00   line#141  LOADK 4 -116          <326>   R4 = (-0.515037298)                             -- It's Const#116
	  +08DF: 41 81 0F 00   line#141  LOADK 5 -63           <327>   R5 = 0                                          -- It's Const#63
	  +08E3: 81 01 1D 00   line#141  LOADK 6 -117          <328>   R6 = (-0.857167721)                             -- It's Const#117
	  +08E7: C1 81 0F 00   line#141  LOADK 7 -63           <329>   R7 = 0                                          -- It's Const#63
	  +08EB: 01 02 02 00   line#141  LOADK 8 -9            <330>   R8 = 1                                          -- It's Const#9
	  +08EF: 41 82 0F 00   line#141  LOADK 9 -63           <331>   R9 = 0                                          -- It's Const#63
	  +08F3: 81 42 1D 00   line#141  LOADK 10 -118         <332>   R10 = 0.857167721                               -- It's Const#118
	  +08F7: C1 82 0F 00   line#141  LOADK 11 -63          <333>   R11 = 0                                         -- It's Const#63
	  +08FB: 01 C3 1C 00   line#141  LOADK 12 -116         <334>   R12 = (-0.515037298)                            -- It's Const#116
	  +08FF: 24 80 80 06   line#141  CALL 0 13 2           <335>   R0 = R0(R1,..,R12)
	  +0903: 08 00 80 88   line#141  SETTABUP 0 -18 0      <336>   Upv#1@_ENV["CFrameQuest"] = R0                  -- It's Const#18
	  +0907: 1E 40 0C 82   line#141  JMP 0 2098            <337>   GOTO <2436>
	  +090B: 06 00 40 00   line#142  GETTABUP 0 0 -1       <338>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +090F: 5F 80 5E 00   line#142  EQ 1 0 -123           <339>   if R0 ~= 300 then GOTO <341>                    -- It's Const#123
	  +0913: 1E 80 00 80   line#142  JMP 0 3               <340>   GOTO <344>
	  +0917: 06 00 40 00   line#142  GETTABUP 0 0 -1       <341>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +091B: 21 C0 5E 00   line#142  LE 0 0 -124           <342>   if R0 <= 324 then GOTO <344>                    -- It's Const#124
	  +091F: 1E 00 05 80   line#142  JMP 0 21              <343>   GOTO <365>
	  +0923: 08 00 5F 85   line#143  SETTABUP 0 -11 -125   <344>   Upv#1@_ENV["Mon"] = "Military Soldier [Lv. 300]"   -- It's Const#11, Const#125
	  +0927: 08 00 42 86   line#144  SETTABUP 0 -13 -9     <345>   Upv#1@_ENV["LQuest"] = 1                        -- It's Const#13, Const#9
	  +092B: 08 40 DF 86   line#145  SETTABUP 0 -14 -126   <346>   Upv#1@_ENV["NQuest"] = "MagmaQuest"             -- It's Const#14, Const#126
	  +092F: 08 80 DF 87   line#146  SETTABUP 0 -16 -127   <347>   Upv#1@_ENV["NameMon"] = "Military Soldier"      -- It's Const#16, Const#127
	  +0933: 06 00 4E 00   line#147  GETTABUP 0 0 -57      <348>   R0 = Upv#1@_ENV["CFrame"]                       -- It's Const#57
	  +0937: 07 40 4E 00   line#147  GETTABLE 0 0 -58      <349>   R0 = R0["new"]                                  -- It's Const#58
	  +093B: 41 C0 1F 00   line#147  LOADK 1 -128          <350>   R1 = (-5313.37012)                              -- It's Const#128
	  +093F: 81 00 20 00   line#147  LOADK 2 -129          <351>   R2 = 10.9500084                                 -- It's Const#129
	  +0943: C1 40 20 00   line#147  LOADK 3 -130          <352>   R3 = 8515.29395                                 -- It's Const#130
	  +0947: 01 81 20 00   line#147  LOADK 4 -131          <353>   R4 = (-0.499959469)                             -- It's Const#131
	  +094B: 41 81 0F 00   line#147  LOADK 5 -63           <354>   R5 = 0                                          -- It's Const#63
	  +094F: 81 C1 20 00   line#147  LOADK 6 -132          <355>   R6 = 0.866048813                                -- It's Const#132
	  +0953: C1 81 0F 00   line#147  LOADK 7 -63           <356>   R7 = 0                                          -- It's Const#63
	  +0957: 01 02 02 00   line#147  LOADK 8 -9            <357>   R8 = 1                                          -- It's Const#9
	  +095B: 41 82 0F 00   line#147  LOADK 9 -63           <358>   R9 = 0                                          -- It's Const#63
	  +095F: 81 02 21 00   line#147  LOADK 10 -133         <359>   R10 = (-0.866048813)                            -- It's Const#133
	  +0963: C1 82 0F 00   line#147  LOADK 11 -63          <360>   R11 = 0                                         -- It's Const#63
	  +0967: 01 83 20 00   line#147  LOADK 12 -131         <361>   R12 = (-0.499959469)                            -- It's Const#131
	  +096B: 24 80 80 06   line#147  CALL 0 13 2           <362>   R0 = R0(R1,..,R12)
	  +096F: 08 00 80 88   line#147  SETTABUP 0 -18 0      <363>   Upv#1@_ENV["CFrameQuest"] = R0                  -- It's Const#18
	  +0973: 1E 80 05 82   line#147  JMP 0 2071            <364>   GOTO <2436>
	  +0977: 06 00 40 00   line#148  GETTABUP 0 0 -1       <365>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +097B: 5F 40 61 00   line#148  EQ 1 0 -134           <366>   if R0 ~= 325 then GOTO <368>                    -- It's Const#134
	  +097F: 1E 80 00 80   line#148  JMP 0 3               <367>   GOTO <371>
	  +0983: 06 00 40 00   line#148  GETTABUP 0 0 -1       <368>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +0987: 21 80 61 00   line#148  LE 0 0 -135           <369>   if R0 <= 374 then GOTO <371>                    -- It's Const#135
	  +098B: 1E 00 05 80   line#148  JMP 0 21              <370>   GOTO <392>
	  +098F: 08 C0 61 85   line#149  SETTABUP 0 -11 -136   <371>   Upv#1@_ENV["Mon"] = "Military Spy [Lv. 325]"    -- It's Const#11, Const#136
	  +0993: 08 40 4D 86   line#150  SETTABUP 0 -13 -54    <372>   Upv#1@_ENV["LQuest"] = 2                        -- It's Const#13, Const#54
	  +0997: 08 40 DF 86   line#151  SETTABUP 0 -14 -126   <373>   Upv#1@_ENV["NQuest"] = "MagmaQuest"             -- It's Const#14, Const#126
	  +099B: 08 00 E2 87   line#152  SETTABUP 0 -16 -137   <374>   Upv#1@_ENV["NameMon"] = "Military Spy"          -- It's Const#16, Const#137
	  +099F: 06 00 4E 00   line#153  GETTABUP 0 0 -57      <375>   R0 = Upv#1@_ENV["CFrame"]                       -- It's Const#57
	  +09A3: 07 40 4E 00   line#153  GETTABLE 0 0 -58      <376>   R0 = R0["new"]                                  -- It's Const#58
	  +09A7: 41 C0 1F 00   line#153  LOADK 1 -128          <377>   R1 = (-5313.37012)                              -- It's Const#128
	  +09AB: 81 00 20 00   line#153  LOADK 2 -129          <378>   R2 = 10.9500084                                 -- It's Const#129
	  +09AF: C1 40 20 00   line#153  LOADK 3 -130          <379>   R3 = 8515.29395                                 -- It's Const#130
	  +09B3: 01 81 20 00   line#153  LOADK 4 -131          <380>   R4 = (-0.499959469)                             -- It's Const#131
	  +09B7: 41 81 0F 00   line#153  LOADK 5 -63           <381>   R5 = 0                                          -- It's Const#63
	  +09BB: 81 C1 20 00   line#153  LOADK 6 -132          <382>   R6 = 0.866048813                                -- It's Const#132
	  +09BF: C1 81 0F 00   line#153  LOADK 7 -63           <383>   R7 = 0                                          -- It's Const#63
	  +09C3: 01 02 02 00   line#153  LOADK 8 -9            <384>   R8 = 1                                          -- It's Const#9
	  +09C7: 41 82 0F 00   line#153  LOADK 9 -63           <385>   R9 = 0                                          -- It's Const#63
	  +09CB: 81 02 21 00   line#153  LOADK 10 -133         <386>   R10 = (-0.866048813)                            -- It's Const#133
	  +09CF: C1 82 0F 00   line#153  LOADK 11 -63          <387>   R11 = 0                                         -- It's Const#63
	  +09D3: 01 83 20 00   line#153  LOADK 12 -131         <388>   R12 = (-0.499959469)                            -- It's Const#131
	  +09D7: 24 80 80 06   line#153  CALL 0 13 2           <389>   R0 = R0(R1,..,R12)
	  +09DB: 08 00 80 88   line#153  SETTABUP 0 -18 0      <390>   Upv#1@_ENV["CFrameQuest"] = R0                  -- It's Const#18
	  +09DF: 1E C0 FE 81   line#153  JMP 0 2044            <391>   GOTO <2436>
	  +09E3: 06 00 40 00   line#154  GETTABUP 0 0 -1       <392>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +09E7: 5F 40 62 00   line#154  EQ 1 0 -138           <393>   if R0 ~= 375 then GOTO <395>                    -- It's Const#138
	  +09EB: 1E 80 00 80   line#154  JMP 0 3               <394>   GOTO <398>
	  +09EF: 06 00 40 00   line#154  GETTABUP 0 0 -1       <395>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +09F3: 21 80 62 00   line#154  LE 0 0 -139           <396>   if R0 <= 399 then GOTO <398>                    -- It's Const#139
	  +09F7: 1E 80 0A 80   line#154  JMP 0 43              <397>   GOTO <441>
	  +09FB: 08 C0 62 85   line#155  SETTABUP 0 -11 -140   <398>   Upv#1@_ENV["Mon"] = "Fishman Warrior [Lv. 375]"   -- It's Const#11, Const#140
	  +09FF: 08 00 42 86   line#156  SETTABUP 0 -13 -9     <399>   Upv#1@_ENV["LQuest"] = 1                        -- It's Const#13, Const#9
	  +0A03: 08 00 E3 86   line#157  SETTABUP 0 -14 -141   <400>   Upv#1@_ENV["NQuest"] = "FishmanQuest"           -- It's Const#14, Const#141
	  +0A07: 08 40 E3 87   line#158  SETTABUP 0 -16 -142   <401>   Upv#1@_ENV["NameMon"] = "Fishman Warrior"       -- It's Const#16, Const#142
	  +0A0B: 06 00 4E 00   line#159  GETTABUP 0 0 -57      <402>   R0 = Upv#1@_ENV["CFrame"]                       -- It's Const#57
	  +0A0F: 07 40 4E 00   line#159  GETTABLE 0 0 -58      <403>   R0 = R0["new"]                                  -- It's Const#58
	  +0A13: 41 80 23 00   line#159  LOADK 1 -143          <404>   R1 = 61122.65234375                             -- It's Const#143
	  +0A17: 81 C0 23 00   line#159  LOADK 2 -144          <405>   R2 = 18.497442245483                            -- It's Const#144
	  +0A1B: C1 00 24 00   line#159  LOADK 3 -145          <406>   R3 = 1569.3997802734                            -- It's Const#145
	  +0A1F: 24 80 00 02   line#159  CALL 0 4 2            <407>   R0 = R0(R1, R2, R3)
	  +0A23: 08 00 80 88   line#159  SETTABUP 0 -18 0      <408>   Upv#1@_ENV["CFrameQuest"] = R0                  -- It's Const#18
	  +0A27: 06 40 64 00   line#160  GETTABUP 0 0 -146     <409>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#146
	  +0A2B: 07 80 64 00   line#160  GETTABLE 0 0 -147     <410>   R0 = R0["AutoFarm"]                             -- It's Const#147
	  +0A2F: 22 00 00 00   line#160  TEST 0 0              <411>   if R0 then GOTO <413>
	  +0A33: 1E 80 F9 81   line#160  JMP 0 2023            <412>   GOTO <2436>
	  +0A37: 06 40 44 00   line#160  GETTABUP 0 0 -18      <413>   R0 = Upv#1@_ENV["CFrameQuest"]                  -- It's Const#18
	  +0A3B: 07 C0 64 00   line#160  GETTABLE 0 0 -148     <414>   R0 = R0["Position"]                             -- It's Const#148
	  +0A3F: 46 00 65 00   line#160  GETTABUP 1 0 -149     <415>   R1 = Upv#1@_ENV["game"]                         -- It's Const#149
	  +0A43: 47 C0 C0 00   line#160  GETTABLE 1 1 -4       <416>   R1 = R1["Players"]                              -- It's Const#4
	  +0A47: 47 00 C1 00   line#160  GETTABLE 1 1 -5       <417>   R1 = R1["LocalPlayer"]                          -- It's Const#5
	  +0A4B: 47 40 E5 00   line#160  GETTABLE 1 1 -150     <418>   R1 = R1["Character"]                            -- It's Const#150
	  +0A4F: 47 80 E5 00   line#160  GETTABLE 1 1 -151     <419>   R1 = R1["HumanoidRootPart"]                     -- It's Const#151
	  +0A53: 47 C0 E4 00   line#160  GETTABLE 1 1 -148     <420>   R1 = R1["Position"]                             -- It's Const#148
	  +0A57: 0E 40 00 00   line#160  SUB 0 0 1             <421>   R0 = R0 - R1
	  +0A5B: 07 C0 65 00   line#160  GETTABLE 0 0 -152     <422>   R0 = R0["Magnitude"]                            -- It's Const#152
	  +0A5F: 20 00 00 CC   line#160  LT 0 -153 0           <423>   if R0 > 10000 then GOTO <425>                   -- It's Const#153
	  +0A63: 1E 80 F6 81   line#160  JMP 0 2011            <424>   GOTO <2436>
	  +0A67: 06 00 65 00   line#161  GETTABUP 0 0 -149     <425>   R0 = Upv#1@_ENV["game"]                         -- It's Const#149
	  +0A6B: 0C 40 66 00   line#161  SELF 0 0 -154         <426>   R1 = R0;  R0 = R0["GetService"]                 -- It's Const#154   -- prepare for R0:GetService()
	  +0A6F: 81 80 26 00   line#161  LOADK 2 -155          <427>   R2 = "ReplicatedStorage"                        -- It's Const#155
	  +0A73: 24 80 80 01   line#161  CALL 0 3 2            <428>   R0 = R0(R1, R2)
	  +0A77: 07 C0 66 00   line#161  GETTABLE 0 0 -156     <429>   R0 = R0["Remotes"]                              -- It's Const#156
	  +0A7B: 07 00 67 00   line#161  GETTABLE 0 0 -157     <430>   R0 = R0["CommF_"]                               -- It's Const#157
	  +0A7F: 0C 40 67 00   line#161  SELF 0 0 -158         <431>   R1 = R0;  R0 = R0["InvokeServer"]               -- It's Const#158   -- prepare for R0:InvokeServer()
	  +0A83: 81 80 27 00   line#161  LOADK 2 -159          <432>   R2 = "requestEntrance"                          -- It's Const#159
	  +0A87: C6 C0 67 00   line#161  GETTABUP 3 0 -160     <433>   R3 = Upv#1@_ENV["Vector3"]                      -- It's Const#160
	  +0A8B: C7 40 CE 01   line#161  GETTABLE 3 3 -58      <434>   R3 = R3["new"]                                  -- It's Const#58
	  +0A8F: 01 01 28 00   line#161  LOADK 4 -161          <435>   R4 = 61163.8515625                              -- It's Const#161
	  +0A93: 41 41 28 00   line#161  LOADK 5 -162          <436>   R5 = 11.6796875                                 -- It's Const#162
	  +0A97: 81 81 28 00   line#161  LOADK 6 -163          <437>   R6 = 1819.7841796875                            -- It's Const#163
	  +0A9B: E4 00 00 02   line#161  CALL 3 4 0            <438>   R3,.. = R3(R4, R5, R6)
	  +0A9F: 24 40 00 00   line#161  CALL 0 0 1            <439>   R0(R1,..)
	  +0AA3: 1E 80 F2 81   line#162  JMP 0 1995            <440>   GOTO <2436>
	  +0AA7: 06 00 40 00   line#163  GETTABUP 0 0 -1       <441>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +0AAB: 5F C0 68 00   line#163  EQ 1 0 -164           <442>   if R0 ~= 400 then GOTO <444>                    -- It's Const#164
	  +0AAF: 1E 80 00 80   line#163  JMP 0 3               <443>   GOTO <447>
	  +0AB3: 06 00 40 00   line#163  GETTABUP 0 0 -1       <444>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +0AB7: 21 00 69 00   line#163  LE 0 0 -165           <445>   if R0 <= 449 then GOTO <447>                    -- It's Const#165
	  +0ABB: 1E 80 0A 80   line#163  JMP 0 43              <446>   GOTO <490>
	  +0ABF: 08 40 69 85   line#164  SETTABUP 0 -11 -166   <447>   Upv#1@_ENV["Mon"] = "Fishman Commando [Lv. 400]"   -- It's Const#11, Const#166
	  +0AC3: 08 40 4D 86   line#165  SETTABUP 0 -13 -54    <448>   Upv#1@_ENV["LQuest"] = 2                        -- It's Const#13, Const#54
	  +0AC7: 08 00 E3 86   line#166  SETTABUP 0 -14 -141   <449>   Upv#1@_ENV["NQuest"] = "FishmanQuest"           -- It's Const#14, Const#141
	  +0ACB: 08 80 E9 87   line#167  SETTABUP 0 -16 -167   <450>   Upv#1@_ENV["NameMon"] = "Fishman Commando"      -- It's Const#16, Const#167
	  +0ACF: 06 00 4E 00   line#168  GETTABUP 0 0 -57      <451>   R0 = Upv#1@_ENV["CFrame"]                       -- It's Const#57
	  +0AD3: 07 40 4E 00   line#168  GETTABLE 0 0 -58      <452>   R0 = R0["new"]                                  -- It's Const#58
	  +0AD7: 41 80 23 00   line#168  LOADK 1 -143          <453>   R1 = 61122.65234375                             -- It's Const#143
	  +0ADB: 81 C0 23 00   line#168  LOADK 2 -144          <454>   R2 = 18.497442245483                            -- It's Const#144
	  +0ADF: C1 00 24 00   line#168  LOADK 3 -145          <455>   R3 = 1569.3997802734                            -- It's Const#145
	  +0AE3: 24 80 00 02   line#168  CALL 0 4 2            <456>   R0 = R0(R1, R2, R3)
	  +0AE7: 08 00 80 88   line#168  SETTABUP 0 -18 0      <457>   Upv#1@_ENV["CFrameQuest"] = R0                  -- It's Const#18
	  +0AEB: 06 40 64 00   line#169  GETTABUP 0 0 -146     <458>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#146
	  +0AEF: 07 80 64 00   line#169  GETTABLE 0 0 -147     <459>   R0 = R0["AutoFarm"]                             -- It's Const#147
	  +0AF3: 22 00 00 00   line#169  TEST 0 0              <460>   if R0 then GOTO <462>
	  +0AF7: 1E 40 ED 81   line#169  JMP 0 1974            <461>   GOTO <2436>
	  +0AFB: 06 40 44 00   line#169  GETTABUP 0 0 -18      <462>   R0 = Upv#1@_ENV["CFrameQuest"]                  -- It's Const#18
	  +0AFF: 07 C0 64 00   line#169  GETTABLE 0 0 -148     <463>   R0 = R0["Position"]                             -- It's Const#148
	  +0B03: 46 00 65 00   line#169  GETTABUP 1 0 -149     <464>   R1 = Upv#1@_ENV["game"]                         -- It's Const#149
	  +0B07: 47 C0 C0 00   line#169  GETTABLE 1 1 -4       <465>   R1 = R1["Players"]                              -- It's Const#4
	  +0B0B: 47 00 C1 00   line#169  GETTABLE 1 1 -5       <466>   R1 = R1["LocalPlayer"]                          -- It's Const#5
	  +0B0F: 47 40 E5 00   line#169  GETTABLE 1 1 -150     <467>   R1 = R1["Character"]                            -- It's Const#150
	  +0B13: 47 80 E5 00   line#169  GETTABLE 1 1 -151     <468>   R1 = R1["HumanoidRootPart"]                     -- It's Const#151
	  +0B17: 47 C0 E4 00   line#169  GETTABLE 1 1 -148     <469>   R1 = R1["Position"]                             -- It's Const#148
	  +0B1B: 0E 40 00 00   line#169  SUB 0 0 1             <470>   R0 = R0 - R1
	  +0B1F: 07 C0 65 00   line#169  GETTABLE 0 0 -152     <471>   R0 = R0["Magnitude"]                            -- It's Const#152
	  +0B23: 20 00 00 CC   line#169  LT 0 -153 0           <472>   if R0 > 10000 then GOTO <474>                   -- It's Const#153
	  +0B27: 1E 40 EA 81   line#169  JMP 0 1962            <473>   GOTO <2436>
	  +0B2B: 06 00 65 00   line#170  GETTABUP 0 0 -149     <474>   R0 = Upv#1@_ENV["game"]                         -- It's Const#149
	  +0B2F: 0C 40 66 00   line#170  SELF 0 0 -154         <475>   R1 = R0;  R0 = R0["GetService"]                 -- It's Const#154   -- prepare for R0:GetService()
	  +0B33: 81 80 26 00   line#170  LOADK 2 -155          <476>   R2 = "ReplicatedStorage"                        -- It's Const#155
	  +0B37: 24 80 80 01   line#170  CALL 0 3 2            <477>   R0 = R0(R1, R2)
	  +0B3B: 07 C0 66 00   line#170  GETTABLE 0 0 -156     <478>   R0 = R0["Remotes"]                              -- It's Const#156
	  +0B3F: 07 00 67 00   line#170  GETTABLE 0 0 -157     <479>   R0 = R0["CommF_"]                               -- It's Const#157
	  +0B43: 0C 40 67 00   line#170  SELF 0 0 -158         <480>   R1 = R0;  R0 = R0["InvokeServer"]               -- It's Const#158   -- prepare for R0:InvokeServer()
	  +0B47: 81 80 27 00   line#170  LOADK 2 -159          <481>   R2 = "requestEntrance"                          -- It's Const#159
	  +0B4B: C6 C0 67 00   line#170  GETTABUP 3 0 -160     <482>   R3 = Upv#1@_ENV["Vector3"]                      -- It's Const#160
	  +0B4F: C7 40 CE 01   line#170  GETTABLE 3 3 -58      <483>   R3 = R3["new"]                                  -- It's Const#58
	  +0B53: 01 01 28 00   line#170  LOADK 4 -161          <484>   R4 = 61163.8515625                              -- It's Const#161
	  +0B57: 41 41 28 00   line#170  LOADK 5 -162          <485>   R5 = 11.6796875                                 -- It's Const#162
	  +0B5B: 81 81 28 00   line#170  LOADK 6 -163          <486>   R6 = 1819.7841796875                            -- It's Const#163
	  +0B5F: E4 00 00 02   line#170  CALL 3 4 0            <487>   R3,.. = R3(R4, R5, R6)
	  +0B63: 24 40 00 00   line#170  CALL 0 0 1            <488>   R0(R1,..)
	  +0B67: 1E 40 E6 81   line#171  JMP 0 1946            <489>   GOTO <2436>
	  +0B6B: 06 00 40 00   line#172  GETTABUP 0 0 -1       <490>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +0B6F: 5F C0 69 00   line#172  EQ 1 0 -168           <491>   if R0 ~= 450 then GOTO <493>                    -- It's Const#168
	  +0B73: 1E 80 00 80   line#172  JMP 0 3               <492>   GOTO <496>
	  +0B77: 06 00 40 00   line#172  GETTABUP 0 0 -1       <493>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +0B7B: 21 00 6A 00   line#172  LE 0 0 -169           <494>   if R0 <= 474 then GOTO <496>                    -- It's Const#169
	  +0B7F: 1E C0 0C 80   line#172  JMP 0 52              <495>   GOTO <548>
	  +0B83: 08 40 6A 85   line#173  SETTABUP 0 -11 -170   <496>   Upv#1@_ENV["Mon"] = "God's Guard [Lv. 450]"     -- It's Const#11, Const#170
	  +0B87: 08 00 42 86   line#174  SETTABUP 0 -13 -9     <497>   Upv#1@_ENV["LQuest"] = 1                        -- It's Const#13, Const#9
	  +0B8B: 08 80 EA 86   line#175  SETTABUP 0 -14 -171   <498>   Upv#1@_ENV["NQuest"] = "SkyExp1Quest"           -- It's Const#14, Const#171
	  +0B8F: 08 C0 EA 87   line#176  SETTABUP 0 -16 -172   <499>   Upv#1@_ENV["NameMon"] = "God's Guard"           -- It's Const#16, Const#172
	  +0B93: 06 00 4E 00   line#177  GETTABUP 0 0 -57      <500>   R0 = Upv#1@_ENV["CFrame"]                       -- It's Const#57
	  +0B97: 07 40 4E 00   line#177  GETTABLE 0 0 -58      <501>   R0 = R0["new"]                                  -- It's Const#58
	  +0B9B: 41 00 2B 00   line#177  LOADK 1 -173          <502>   R1 = (-4721.88867)                              -- It's Const#173
	  +0B9F: 81 40 2B 00   line#177  LOADK 2 -174          <503>   R2 = 843.874695                                 -- It's Const#174
	  +0BA3: C1 80 2B 00   line#177  LOADK 3 -175          <504>   R3 = (-1949.96643)                              -- It's Const#175
	  +0BA7: 01 C1 2B 00   line#177  LOADK 4 -176          <505>   R4 = 0.996191859                                -- It's Const#176
	  +0BAB: 41 81 0F 00   line#177  LOADK 5 -63           <506>   R5 = 0                                          -- It's Const#63
	  +0BAF: 81 01 2C 00   line#177  LOADK 6 -177          <507>   R6 = (-0.0871884301)                            -- It's Const#177
	  +0BB3: C1 81 0F 00   line#177  LOADK 7 -63           <508>   R7 = 0                                          -- It's Const#63
	  +0BB7: 01 02 02 00   line#177  LOADK 8 -9            <509>   R8 = 1                                          -- It's Const#9
	  +0BBB: 41 82 0F 00   line#177  LOADK 9 -63           <510>   R9 = 0                                          -- It's Const#63
	  +0BBF: 81 42 2C 00   line#177  LOADK 10 -178         <511>   R10 = 0.0871884301                              -- It's Const#178
	  +0BC3: C1 82 0F 00   line#177  LOADK 11 -63          <512>   R11 = 0                                         -- It's Const#63
	  +0BC7: 01 C3 2B 00   line#177  LOADK 12 -176         <513>   R12 = 0.996191859                               -- It's Const#176
	  +0BCB: 24 80 80 06   line#177  CALL 0 13 2           <514>   R0 = R0(R1,..,R12)
	  +0BCF: 08 00 80 88   line#177  SETTABUP 0 -18 0      <515>   Upv#1@_ENV["CFrameQuest"] = R0                  -- It's Const#18
	  +0BD3: 06 40 64 00   line#178  GETTABUP 0 0 -146     <516>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#146
	  +0BD7: 07 80 64 00   line#178  GETTABLE 0 0 -147     <517>   R0 = R0["AutoFarm"]                             -- It's Const#147
	  +0BDB: 22 00 00 00   line#178  TEST 0 0              <518>   if R0 then GOTO <520>
	  +0BDF: 1E C0 DE 81   line#178  JMP 0 1916            <519>   GOTO <2436>
	  +0BE3: 06 40 44 00   line#178  GETTABUP 0 0 -18      <520>   R0 = Upv#1@_ENV["CFrameQuest"]                  -- It's Const#18
	  +0BE7: 07 C0 64 00   line#178  GETTABLE 0 0 -148     <521>   R0 = R0["Position"]                             -- It's Const#148
	  +0BEB: 46 00 65 00   line#178  GETTABUP 1 0 -149     <522>   R1 = Upv#1@_ENV["game"]                         -- It's Const#149
	  +0BEF: 47 C0 C0 00   line#178  GETTABLE 1 1 -4       <523>   R1 = R1["Players"]                              -- It's Const#4
	  +0BF3: 47 00 C1 00   line#178  GETTABLE 1 1 -5       <524>   R1 = R1["LocalPlayer"]                          -- It's Const#5
	  +0BF7: 47 40 E5 00   line#178  GETTABLE 1 1 -150     <525>   R1 = R1["Character"]                            -- It's Const#150
	  +0BFB: 47 80 E5 00   line#178  GETTABLE 1 1 -151     <526>   R1 = R1["HumanoidRootPart"]                     -- It's Const#151
	  +0BFF: 47 C0 E4 00   line#178  GETTABLE 1 1 -148     <527>   R1 = R1["Position"]                             -- It's Const#148
	  +0C03: 0E 40 00 00   line#178  SUB 0 0 1             <528>   R0 = R0 - R1
	  +0C07: 07 C0 65 00   line#178  GETTABLE 0 0 -152     <529>   R0 = R0["Magnitude"]                            -- It's Const#152
	  +0C0B: 20 00 00 CC   line#178  LT 0 -153 0           <530>   if R0 > 10000 then GOTO <532>                   -- It's Const#153
	  +0C0F: 1E C0 DB 81   line#178  JMP 0 1904            <531>   GOTO <2436>
	  +0C13: 06 00 65 00   line#179  GETTABUP 0 0 -149     <532>   R0 = Upv#1@_ENV["game"]                         -- It's Const#149
	  +0C17: 0C 40 66 00   line#179  SELF 0 0 -154         <533>   R1 = R0;  R0 = R0["GetService"]                 -- It's Const#154   -- prepare for R0:GetService()
	  +0C1B: 81 80 26 00   line#179  LOADK 2 -155          <534>   R2 = "ReplicatedStorage"                        -- It's Const#155
	  +0C1F: 24 80 80 01   line#179  CALL 0 3 2            <535>   R0 = R0(R1, R2)
	  +0C23: 07 C0 66 00   line#179  GETTABLE 0 0 -156     <536>   R0 = R0["Remotes"]                              -- It's Const#156
	  +0C27: 07 00 67 00   line#179  GETTABLE 0 0 -157     <537>   R0 = R0["CommF_"]                               -- It's Const#157
	  +0C2B: 0C 40 67 00   line#179  SELF 0 0 -158         <538>   R1 = R0;  R0 = R0["InvokeServer"]               -- It's Const#158   -- prepare for R0:InvokeServer()
	  +0C2F: 81 80 27 00   line#179  LOADK 2 -159          <539>   R2 = "requestEntrance"                          -- It's Const#159
	  +0C33: C6 C0 67 00   line#179  GETTABUP 3 0 -160     <540>   R3 = Upv#1@_ENV["Vector3"]                      -- It's Const#160
	  +0C37: C7 40 CE 01   line#179  GETTABLE 3 3 -58      <541>   R3 = R3["new"]                                  -- It's Const#58
	  +0C3B: 01 81 2C 00   line#179  LOADK 4 -179          <542>   R4 = (-4607.82275)                              -- It's Const#179
	  +0C3F: 41 C1 2C 00   line#179  LOADK 5 -180          <543>   R5 = 872.54248                                  -- It's Const#180
	  +0C43: 81 01 2D 00   line#179  LOADK 6 -181          <544>   R6 = (-1667.55688)                              -- It's Const#181
	  +0C47: E4 00 00 02   line#179  CALL 3 4 0            <545>   R3,.. = R3(R4, R5, R6)
	  +0C4B: 24 40 00 00   line#179  CALL 0 0 1            <546>   R0(R1,..)
	  +0C4F: 1E C0 D7 81   line#180  JMP 0 1888            <547>   GOTO <2436>
	  +0C53: 06 00 40 00   line#181  GETTABUP 0 0 -1       <548>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +0C57: 5F 40 6D 00   line#181  EQ 1 0 -182           <549>   if R0 ~= 475 then GOTO <551>                    -- It's Const#182
	  +0C5B: 1E 80 00 80   line#181  JMP 0 3               <550>   GOTO <554>
	  +0C5F: 06 00 40 00   line#181  GETTABUP 0 0 -1       <551>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +0C63: 21 80 6D 00   line#181  LE 0 0 -183           <552>   if R0 <= 524 then GOTO <554>                    -- It's Const#183
	  +0C67: 1E C0 0C 80   line#181  JMP 0 52              <553>   GOTO <606>
	  +0C6B: 08 C0 6D 85   line#182  SETTABUP 0 -11 -184   <554>   Upv#1@_ENV["Mon"] = "Shanda [Lv. 475]"          -- It's Const#11, Const#184
	  +0C6F: 08 40 4D 86   line#183  SETTABUP 0 -13 -54    <555>   Upv#1@_ENV["LQuest"] = 2                        -- It's Const#13, Const#54
	  +0C73: 08 80 EA 86   line#184  SETTABUP 0 -14 -171   <556>   Upv#1@_ENV["NQuest"] = "SkyExp1Quest"           -- It's Const#14, Const#171
	  +0C77: 08 00 EE 87   line#185  SETTABUP 0 -16 -185   <557>   Upv#1@_ENV["NameMon"] = "Shanda"                -- It's Const#16, Const#185
	  +0C7B: 06 00 4E 00   line#186  GETTABUP 0 0 -57      <558>   R0 = Upv#1@_ENV["CFrame"]                       -- It's Const#57
	  +0C7F: 07 40 4E 00   line#186  GETTABLE 0 0 -58      <559>   R0 = R0["new"]                                  -- It's Const#58
	  +0C83: 41 40 2E 00   line#186  LOADK 1 -186          <560>   R1 = (-7859.09814)                              -- It's Const#186
	  +0C87: 81 80 2E 00   line#186  LOADK 2 -187          <561>   R2 = 5544.19043                                 -- It's Const#187
	  +0C8B: C1 C0 2E 00   line#186  LOADK 3 -188          <562>   R3 = (-381.476196)                              -- It's Const#188
	  +0C8F: 01 01 2F 00   line#186  LOADK 4 -189          <563>   R4 = (-0.422592998)                             -- It's Const#189
	  +0C93: 41 81 0F 00   line#186  LOADK 5 -63           <564>   R5 = 0                                          -- It's Const#63
	  +0C97: 81 41 2F 00   line#186  LOADK 6 -190          <565>   R6 = 0.906319618                                -- It's Const#190
	  +0C9B: C1 81 0F 00   line#186  LOADK 7 -63           <566>   R7 = 0                                          -- It's Const#63
	  +0C9F: 01 02 02 00   line#186  LOADK 8 -9            <567>   R8 = 1                                          -- It's Const#9
	  +0CA3: 41 82 0F 00   line#186  LOADK 9 -63           <568>   R9 = 0                                          -- It's Const#63
	  +0CA7: 81 82 2F 00   line#186  LOADK 10 -191         <569>   R10 = (-0.906319618)                            -- It's Const#191
	  +0CAB: C1 82 0F 00   line#186  LOADK 11 -63          <570>   R11 = 0                                         -- It's Const#63
	  +0CAF: 01 03 2F 00   line#186  LOADK 12 -189         <571>   R12 = (-0.422592998)                            -- It's Const#189
	  +0CB3: 24 80 80 06   line#186  CALL 0 13 2           <572>   R0 = R0(R1,..,R12)
	  +0CB7: 08 00 80 88   line#186  SETTABUP 0 -18 0      <573>   Upv#1@_ENV["CFrameQuest"] = R0                  -- It's Const#18
	  +0CBB: 06 40 64 00   line#187  GETTABUP 0 0 -146     <574>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#146
	  +0CBF: 07 80 64 00   line#187  GETTABLE 0 0 -147     <575>   R0 = R0["AutoFarm"]                             -- It's Const#147
	  +0CC3: 22 00 00 00   line#187  TEST 0 0              <576>   if R0 then GOTO <578>
	  +0CC7: 1E 40 D0 81   line#187  JMP 0 1858            <577>   GOTO <2436>
	  +0CCB: 06 40 44 00   line#187  GETTABUP 0 0 -18      <578>   R0 = Upv#1@_ENV["CFrameQuest"]                  -- It's Const#18
	  +0CCF: 07 C0 64 00   line#187  GETTABLE 0 0 -148     <579>   R0 = R0["Position"]                             -- It's Const#148
	  +0CD3: 46 00 65 00   line#187  GETTABUP 1 0 -149     <580>   R1 = Upv#1@_ENV["game"]                         -- It's Const#149
	  +0CD7: 47 C0 C0 00   line#187  GETTABLE 1 1 -4       <581>   R1 = R1["Players"]                              -- It's Const#4
	  +0CDB: 47 00 C1 00   line#187  GETTABLE 1 1 -5       <582>   R1 = R1["LocalPlayer"]                          -- It's Const#5
	  +0CDF: 47 40 E5 00   line#187  GETTABLE 1 1 -150     <583>   R1 = R1["Character"]                            -- It's Const#150
	  +0CE3: 47 80 E5 00   line#187  GETTABLE 1 1 -151     <584>   R1 = R1["HumanoidRootPart"]                     -- It's Const#151
	  +0CE7: 47 C0 E4 00   line#187  GETTABLE 1 1 -148     <585>   R1 = R1["Position"]                             -- It's Const#148
	  +0CEB: 0E 40 00 00   line#187  SUB 0 0 1             <586>   R0 = R0 - R1
	  +0CEF: 07 C0 65 00   line#187  GETTABLE 0 0 -152     <587>   R0 = R0["Magnitude"]                            -- It's Const#152
	  +0CF3: 20 00 00 CC   line#187  LT 0 -153 0           <588>   if R0 > 10000 then GOTO <590>                   -- It's Const#153
	  +0CF7: 1E 40 CD 81   line#187  JMP 0 1846            <589>   GOTO <2436>
	  +0CFB: 06 00 65 00   line#188  GETTABUP 0 0 -149     <590>   R0 = Upv#1@_ENV["game"]                         -- It's Const#149
	  +0CFF: 0C 40 66 00   line#188  SELF 0 0 -154         <591>   R1 = R0;  R0 = R0["GetService"]                 -- It's Const#154   -- prepare for R0:GetService()
	  +0D03: 81 80 26 00   line#188  LOADK 2 -155          <592>   R2 = "ReplicatedStorage"                        -- It's Const#155
	  +0D07: 24 80 80 01   line#188  CALL 0 3 2            <593>   R0 = R0(R1, R2)
	  +0D0B: 07 C0 66 00   line#188  GETTABLE 0 0 -156     <594>   R0 = R0["Remotes"]                              -- It's Const#156
	  +0D0F: 07 00 67 00   line#188  GETTABLE 0 0 -157     <595>   R0 = R0["CommF_"]                               -- It's Const#157
	  +0D13: 0C 40 67 00   line#188  SELF 0 0 -158         <596>   R1 = R0;  R0 = R0["InvokeServer"]               -- It's Const#158   -- prepare for R0:InvokeServer()
	  +0D17: 81 80 27 00   line#188  LOADK 2 -159          <597>   R2 = "requestEntrance"                          -- It's Const#159
	  +0D1B: C6 C0 67 00   line#188  GETTABUP 3 0 -160     <598>   R3 = Upv#1@_ENV["Vector3"]                      -- It's Const#160
	  +0D1F: C7 40 CE 01   line#188  GETTABLE 3 3 -58      <599>   R3 = R3["new"]                                  -- It's Const#58
	  +0D23: 01 C1 2F 00   line#188  LOADK 4 -192          <600>   R4 = (-7894.6176757813)                         -- It's Const#192
	  +0D27: 41 01 30 00   line#188  LOADK 5 -193          <601>   R5 = 5547.1416015625                            -- It's Const#193
	  +0D2B: 81 41 30 00   line#188  LOADK 6 -194          <602>   R6 = (-380.29119873047)                         -- It's Const#194
	  +0D2F: E4 00 00 02   line#188  CALL 3 4 0            <603>   R3,.. = R3(R4, R5, R6)
	  +0D33: 24 40 00 00   line#188  CALL 0 0 1            <604>   R0(R1,..)
	  +0D37: 1E 40 C9 81   line#189  JMP 0 1830            <605>   GOTO <2436>
	  +0D3B: 06 00 40 00   line#190  GETTABUP 0 0 -1       <606>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +0D3F: 5F 80 70 00   line#190  EQ 1 0 -195           <607>   if R0 ~= 525 then GOTO <609>                    -- It's Const#195
	  +0D43: 1E 80 00 80   line#190  JMP 0 3               <608>   GOTO <612>
	  +0D47: 06 00 40 00   line#190  GETTABUP 0 0 -1       <609>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +0D4B: 21 C0 70 00   line#190  LE 0 0 -196           <610>   if R0 <= 549 then GOTO <612>                    -- It's Const#196
	  +0D4F: 1E 00 05 80   line#190  JMP 0 21              <611>   GOTO <633>
	  +0D53: 08 00 71 85   line#191  SETTABUP 0 -11 -197   <612>   Upv#1@_ENV["Mon"] = "Royal Squad [Lv. 525]"     -- It's Const#11, Const#197
	  +0D57: 08 00 42 86   line#192  SETTABUP 0 -13 -9     <613>   Upv#1@_ENV["LQuest"] = 1                        -- It's Const#13, Const#9
	  +0D5B: 08 40 F1 86   line#193  SETTABUP 0 -14 -198   <614>   Upv#1@_ENV["NQuest"] = "SkyExp2Quest"           -- It's Const#14, Const#198
	  +0D5F: 08 80 F1 87   line#194  SETTABUP 0 -16 -199   <615>   Upv#1@_ENV["NameMon"] = "Royal Squad"           -- It's Const#16, Const#199
	  +0D63: 06 00 4E 00   line#195  GETTABUP 0 0 -57      <616>   R0 = Upv#1@_ENV["CFrame"]                       -- It's Const#57
	  +0D67: 07 40 4E 00   line#195  GETTABLE 0 0 -58      <617>   R0 = R0["new"]                                  -- It's Const#58
	  +0D6B: 41 C0 31 00   line#195  LOADK 1 -200          <618>   R1 = (-7906.81592)                              -- It's Const#200
	  +0D6F: 81 00 32 00   line#195  LOADK 2 -201          <619>   R2 = 5634.6626                                  -- It's Const#201
	  +0D73: C1 40 32 00   line#195  LOADK 3 -202          <620>   R3 = (-1411.99194)                              -- It's Const#202
	  +0D77: 01 81 0F 00   line#195  LOADK 4 -63           <621>   R4 = 0                                          -- It's Const#63
	  +0D7B: 41 81 0F 00   line#195  LOADK 5 -63           <622>   R5 = 0                                          -- It's Const#63
	  +0D7F: 81 C1 08 00   line#195  LOADK 6 -36           <623>   R6 = (-1)                                       -- It's Const#36
	  +0D83: C1 81 0F 00   line#195  LOADK 7 -63           <624>   R7 = 0                                          -- It's Const#63
	  +0D87: 01 02 02 00   line#195  LOADK 8 -9            <625>   R8 = 1                                          -- It's Const#9
	  +0D8B: 41 82 0F 00   line#195  LOADK 9 -63           <626>   R9 = 0                                          -- It's Const#63
	  +0D8F: 81 02 02 00   line#195  LOADK 10 -9           <627>   R10 = 1                                         -- It's Const#9
	  +0D93: C1 82 0F 00   line#195  LOADK 11 -63          <628>   R11 = 0                                         -- It's Const#63
	  +0D97: 01 83 0F 00   line#195  LOADK 12 -63          <629>   R12 = 0                                         -- It's Const#63
	  +0D9B: 24 80 80 06   line#195  CALL 0 13 2           <630>   R0 = R0(R1,..,R12)
	  +0D9F: 08 00 80 88   line#195  SETTABUP 0 -18 0      <631>   Upv#1@_ENV["CFrameQuest"] = R0                  -- It's Const#18
	  +0DA3: 1E 80 C2 81   line#195  JMP 0 1803            <632>   GOTO <2436>
	  +0DA7: 06 00 40 00   line#196  GETTABUP 0 0 -1       <633>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +0DAB: 5F 80 72 00   line#196  EQ 1 0 -203           <634>   if R0 ~= 550 then GOTO <636>                    -- It's Const#203
	  +0DAF: 1E 80 00 80   line#196  JMP 0 3               <635>   GOTO <639>
	  +0DB3: 06 00 40 00   line#196  GETTABUP 0 0 -1       <636>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +0DB7: 21 C0 72 00   line#196  LE 0 0 -204           <637>   if R0 <= 624 then GOTO <639>                    -- It's Const#204
	  +0DBB: 1E 00 05 80   line#196  JMP 0 21              <638>   GOTO <660>
	  +0DBF: 08 00 73 85   line#197  SETTABUP 0 -11 -205   <639>   Upv#1@_ENV["Mon"] = "Royal Soldier [Lv. 550]"   -- It's Const#11, Const#205
	  +0DC3: 08 40 4D 86   line#198  SETTABUP 0 -13 -54    <640>   Upv#1@_ENV["LQuest"] = 2                        -- It's Const#13, Const#54
	  +0DC7: 08 40 F1 86   line#199  SETTABUP 0 -14 -198   <641>   Upv#1@_ENV["NQuest"] = "SkyExp2Quest"           -- It's Const#14, Const#198
	  +0DCB: 08 40 F3 87   line#200  SETTABUP 0 -16 -206   <642>   Upv#1@_ENV["NameMon"] = "Royal Soldier"         -- It's Const#16, Const#206
	  +0DCF: 06 00 4E 00   line#201  GETTABUP 0 0 -57      <643>   R0 = Upv#1@_ENV["CFrame"]                       -- It's Const#57
	  +0DD3: 07 40 4E 00   line#201  GETTABLE 0 0 -58      <644>   R0 = R0["new"]                                  -- It's Const#58
	  +0DD7: 41 C0 31 00   line#201  LOADK 1 -200          <645>   R1 = (-7906.81592)                              -- It's Const#200
	  +0DDB: 81 00 32 00   line#201  LOADK 2 -201          <646>   R2 = 5634.6626                                  -- It's Const#201
	  +0DDF: C1 40 32 00   line#201  LOADK 3 -202          <647>   R3 = (-1411.99194)                              -- It's Const#202
	  +0DE3: 01 81 0F 00   line#201  LOADK 4 -63           <648>   R4 = 0                                          -- It's Const#63
	  +0DE7: 41 81 0F 00   line#201  LOADK 5 -63           <649>   R5 = 0                                          -- It's Const#63
	  +0DEB: 81 C1 08 00   line#201  LOADK 6 -36           <650>   R6 = (-1)                                       -- It's Const#36
	  +0DEF: C1 81 0F 00   line#201  LOADK 7 -63           <651>   R7 = 0                                          -- It's Const#63
	  +0DF3: 01 02 02 00   line#201  LOADK 8 -9            <652>   R8 = 1                                          -- It's Const#9
	  +0DF7: 41 82 0F 00   line#201  LOADK 9 -63           <653>   R9 = 0                                          -- It's Const#63
	  +0DFB: 81 02 02 00   line#201  LOADK 10 -9           <654>   R10 = 1                                         -- It's Const#9
	  +0DFF: C1 82 0F 00   line#201  LOADK 11 -63          <655>   R11 = 0                                         -- It's Const#63
	  +0E03: 01 83 0F 00   line#201  LOADK 12 -63          <656>   R12 = 0                                         -- It's Const#63
	  +0E07: 24 80 80 06   line#201  CALL 0 13 2           <657>   R0 = R0(R1,..,R12)
	  +0E0B: 08 00 80 88   line#201  SETTABUP 0 -18 0      <658>   Upv#1@_ENV["CFrameQuest"] = R0                  -- It's Const#18
	  +0E0F: 1E C0 BB 81   line#201  JMP 0 1776            <659>   GOTO <2436>
	  +0E13: 06 00 40 00   line#202  GETTABUP 0 0 -1       <660>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +0E17: 5F 80 73 00   line#202  EQ 1 0 -207           <661>   if R0 ~= 625 then GOTO <663>                    -- It's Const#207
	  +0E1B: 1E 80 00 80   line#202  JMP 0 3               <662>   GOTO <666>
	  +0E1F: 06 00 40 00   line#202  GETTABUP 0 0 -1       <663>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +0E23: 21 C0 73 00   line#202  LE 0 0 -208           <664>   if R0 <= 649 then GOTO <666>                    -- It's Const#208
	  +0E27: 1E 00 05 80   line#202  JMP 0 21              <665>   GOTO <687>
	  +0E2B: 08 00 74 85   line#203  SETTABUP 0 -11 -209   <666>   Upv#1@_ENV["Mon"] = "Galley Pirate [Lv. 625]"   -- It's Const#11, Const#209
	  +0E2F: 08 00 42 86   line#204  SETTABUP 0 -13 -9     <667>   Upv#1@_ENV["LQuest"] = 1                        -- It's Const#13, Const#9
	  +0E33: 08 40 F4 86   line#205  SETTABUP 0 -14 -210   <668>   Upv#1@_ENV["NQuest"] = "FountainQuest"          -- It's Const#14, Const#210
	  +0E37: 08 80 F4 87   line#206  SETTABUP 0 -16 -211   <669>   Upv#1@_ENV["NameMon"] = "Galley Pirate"         -- It's Const#16, Const#211
	  +0E3B: 06 00 4E 00   line#207  GETTABUP 0 0 -57      <670>   R0 = Upv#1@_ENV["CFrame"]                       -- It's Const#57
	  +0E3F: 07 40 4E 00   line#207  GETTABLE 0 0 -58      <671>   R0 = R0["new"]                                  -- It's Const#58
	  +0E43: 41 C0 34 00   line#207  LOADK 1 -212          <672>   R1 = 5259.81982                                 -- It's Const#212
	  +0E47: 81 00 35 00   line#207  LOADK 2 -213          <673>   R2 = 37.3500175                                 -- It's Const#213
	  +0E4B: C1 40 35 00   line#207  LOADK 3 -214          <674>   R3 = 4050.0293                                  -- It's Const#214
	  +0E4F: 01 81 35 00   line#207  LOADK 4 -215          <675>   R4 = 0.087131381                                -- It's Const#215
	  +0E53: 41 81 0F 00   line#207  LOADK 5 -63           <676>   R5 = 0                                          -- It's Const#63
	  +0E57: 81 C1 35 00   line#207  LOADK 6 -216          <677>   R6 = 0.996196866                                -- It's Const#216
	  +0E5B: C1 81 0F 00   line#207  LOADK 7 -63           <678>   R7 = 0                                          -- It's Const#63
	  +0E5F: 01 02 02 00   line#207  LOADK 8 -9            <679>   R8 = 1                                          -- It's Const#9
	  +0E63: 41 82 0F 00   line#207  LOADK 9 -63           <680>   R9 = 0                                          -- It's Const#63
	  +0E67: 81 02 36 00   line#207  LOADK 10 -217         <681>   R10 = (-0.996196866)                            -- It's Const#217
	  +0E6B: C1 82 0F 00   line#207  LOADK 11 -63          <682>   R11 = 0                                         -- It's Const#63
	  +0E6F: 01 83 35 00   line#207  LOADK 12 -215         <683>   R12 = 0.087131381                               -- It's Const#215
	  +0E73: 24 80 80 06   line#207  CALL 0 13 2           <684>   R0 = R0(R1,..,R12)
	  +0E77: 08 00 80 88   line#207  SETTABUP 0 -18 0      <685>   Upv#1@_ENV["CFrameQuest"] = R0                  -- It's Const#18
	  +0E7B: 1E 00 B5 81   line#207  JMP 0 1749            <686>   GOTO <2436>
	  +0E7F: 06 00 40 00   line#208  GETTABUP 0 0 -1       <687>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +0E83: 21 00 80 EC   line#208  LE 0 -218 0           <688>   if R0 >= 650 then GOTO <690>                    -- It's Const#218
	  +0E87: 1E 40 B4 81   line#208  JMP 0 1746            <689>   GOTO <2436>
	  +0E8B: 08 80 76 85   line#209  SETTABUP 0 -11 -219   <690>   Upv#1@_ENV["Mon"] = "Galley Captain [Lv. 650]"   -- It's Const#11, Const#219
	  +0E8F: 08 40 4D 86   line#210  SETTABUP 0 -13 -54    <691>   Upv#1@_ENV["LQuest"] = 2                        -- It's Const#13, Const#54
	  +0E93: 08 40 F4 86   line#211  SETTABUP 0 -14 -210   <692>   Upv#1@_ENV["NQuest"] = "FountainQuest"          -- It's Const#14, Const#210
	  +0E97: 08 C0 F6 87   line#212  SETTABUP 0 -16 -220   <693>   Upv#1@_ENV["NameMon"] = "Galley Captain"        -- It's Const#16, Const#220
	  +0E9B: 06 00 4E 00   line#213  GETTABUP 0 0 -57      <694>   R0 = Upv#1@_ENV["CFrame"]                       -- It's Const#57
	  +0E9F: 07 40 4E 00   line#213  GETTABLE 0 0 -58      <695>   R0 = R0["new"]                                  -- It's Const#58
	  +0EA3: 41 C0 34 00   line#213  LOADK 1 -212          <696>   R1 = 5259.81982                                 -- It's Const#212
	  +0EA7: 81 00 35 00   line#213  LOADK 2 -213          <697>   R2 = 37.3500175                                 -- It's Const#213
	  +0EAB: C1 40 35 00   line#213  LOADK 3 -214          <698>   R3 = 4050.0293                                  -- It's Const#214
	  +0EAF: 01 81 35 00   line#213  LOADK 4 -215          <699>   R4 = 0.087131381                                -- It's Const#215
	  +0EB3: 41 81 0F 00   line#213  LOADK 5 -63           <700>   R5 = 0                                          -- It's Const#63
	  +0EB7: 81 C1 35 00   line#213  LOADK 6 -216          <701>   R6 = 0.996196866                                -- It's Const#216
	  +0EBB: C1 81 0F 00   line#213  LOADK 7 -63           <702>   R7 = 0                                          -- It's Const#63
	  +0EBF: 01 02 02 00   line#213  LOADK 8 -9            <703>   R8 = 1                                          -- It's Const#9
	  +0EC3: 41 82 0F 00   line#213  LOADK 9 -63           <704>   R9 = 0                                          -- It's Const#63
	  +0EC7: 81 02 36 00   line#213  LOADK 10 -217         <705>   R10 = (-0.996196866)                            -- It's Const#217
	  +0ECB: C1 82 0F 00   line#213  LOADK 11 -63          <706>   R11 = 0                                         -- It's Const#63
	  +0ECF: 01 83 35 00   line#213  LOADK 12 -215         <707>   R12 = 0.087131381                               -- It's Const#215
	  +0ED3: 24 80 80 06   line#213  CALL 0 13 2           <708>   R0 = R0(R1,..,R12)
	  +0ED7: 08 00 80 88   line#213  SETTABUP 0 -18 0      <709>   Upv#1@_ENV["CFrameQuest"] = R0                  -- It's Const#18
	  +0EDB: 1E 00 AF 81   line#214  JMP 0 1725            <710>   GOTO <2436>
	  +0EDF: 06 00 77 00   line#215  GETTABUP 0 0 -221     <711>   R0 = Upv#1@_ENV["W2"]                           -- It's Const#221
	  +0EE3: 22 00 00 00   line#215  TEST 0 0              <712>   if R0 then GOTO <714>
	  +0EE7: 1E 80 C7 80   line#215  JMP 0 799             <713>   GOTO <1513>
	  +0EEB: 06 00 40 00   line#216  GETTABUP 0 0 -1       <714>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +0EEF: 5F 40 77 00   line#216  EQ 1 0 -222           <715>   if R0 ~= 700 then GOTO <717>                    -- It's Const#222
	  +0EF3: 1E 80 00 80   line#216  JMP 0 3               <716>   GOTO <720>
	  +0EF7: 06 00 40 00   line#216  GETTABUP 0 0 -1       <717>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +0EFB: 21 80 77 00   line#216  LE 0 0 -223           <718>   if R0 <= 724 then GOTO <720>                    -- It's Const#223
	  +0EFF: 1E 00 05 80   line#216  JMP 0 21              <719>   GOTO <741>
	  +0F03: 08 C0 77 85   line#217  SETTABUP 0 -11 -224   <720>   Upv#1@_ENV["Mon"] = "Raider [Lv. 700]"          -- It's Const#11, Const#224
	  +0F07: 08 00 42 86   line#218  SETTABUP 0 -13 -9     <721>   Upv#1@_ENV["LQuest"] = 1                        -- It's Const#13, Const#9
	  +0F0B: 08 00 F8 86   line#219  SETTABUP 0 -14 -225   <722>   Upv#1@_ENV["NQuest"] = "Area1Quest"             -- It's Const#14, Const#225
	  +0F0F: 08 40 F8 87   line#220  SETTABUP 0 -16 -226   <723>   Upv#1@_ENV["NameMon"] = "Raider"                -- It's Const#16, Const#226
	  +0F13: 06 00 4E 00   line#221  GETTABUP 0 0 -57      <724>   R0 = Upv#1@_ENV["CFrame"]                       -- It's Const#57
	  +0F17: 07 40 4E 00   line#221  GETTABLE 0 0 -58      <725>   R0 = R0["new"]                                  -- It's Const#58
	  +0F1B: 41 80 38 00   line#221  LOADK 1 -227          <726>   R1 = (-429.543518)                              -- It's Const#227
	  +0F1F: 81 C0 38 00   line#221  LOADK 2 -228          <727>   R2 = 71.7699966                                 -- It's Const#228
	  +0F23: C1 00 39 00   line#221  LOADK 3 -229          <728>   R3 = 1836.18188                                 -- It's Const#229
	  +0F27: 01 41 39 00   line#221  LOADK 4 -230          <729>   R4 = (-0.22495985)                              -- It's Const#230
	  +0F2B: 41 81 0F 00   line#221  LOADK 5 -63           <730>   R5 = 0                                          -- It's Const#63
	  +0F2F: 81 81 39 00   line#221  LOADK 6 -231          <731>   R6 = (-0.974368095)                             -- It's Const#231
	  +0F33: C1 81 0F 00   line#221  LOADK 7 -63           <732>   R7 = 0                                          -- It's Const#63
	  +0F37: 01 02 02 00   line#221  LOADK 8 -9            <733>   R8 = 1                                          -- It's Const#9
	  +0F3B: 41 82 0F 00   line#221  LOADK 9 -63           <734>   R9 = 0                                          -- It's Const#63
	  +0F3F: 81 C2 39 00   line#221  LOADK 10 -232         <735>   R10 = 0.974368095                               -- It's Const#232
	  +0F43: C1 82 0F 00   line#221  LOADK 11 -63          <736>   R11 = 0                                         -- It's Const#63
	  +0F47: 01 43 39 00   line#221  LOADK 12 -230         <737>   R12 = (-0.22495985)                             -- It's Const#230
	  +0F4B: 24 80 80 06   line#221  CALL 0 13 2           <738>   R0 = R0(R1,..,R12)
	  +0F4F: 08 00 80 88   line#221  SETTABUP 0 -18 0      <739>   Upv#1@_ENV["CFrameQuest"] = R0                  -- It's Const#18
	  +0F53: 1E 80 A7 81   line#221  JMP 0 1695            <740>   GOTO <2436>
	  +0F57: 06 00 40 00   line#222  GETTABUP 0 0 -1       <741>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +0F5B: 5F 00 7A 00   line#222  EQ 1 0 -233           <742>   if R0 ~= 725 then GOTO <744>                    -- It's Const#233
	  +0F5F: 1E 80 00 80   line#222  JMP 0 3               <743>   GOTO <747>
	  +0F63: 06 00 40 00   line#222  GETTABUP 0 0 -1       <744>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +0F67: 21 40 7A 00   line#222  LE 0 0 -234           <745>   if R0 <= 774 then GOTO <747>                    -- It's Const#234
	  +0F6B: 1E 00 05 80   line#222  JMP 0 21              <746>   GOTO <768>
	  +0F6F: 08 80 7A 85   line#223  SETTABUP 0 -11 -235   <747>   Upv#1@_ENV["Mon"] = "Mercenary [Lv. 725]"       -- It's Const#11, Const#235
	  +0F73: 08 40 4D 86   line#224  SETTABUP 0 -13 -54    <748>   Upv#1@_ENV["LQuest"] = 2                        -- It's Const#13, Const#54
	  +0F77: 08 00 F8 86   line#225  SETTABUP 0 -14 -225   <749>   Upv#1@_ENV["NQuest"] = "Area1Quest"             -- It's Const#14, Const#225
	  +0F7B: 08 C0 FA 87   line#226  SETTABUP 0 -16 -236   <750>   Upv#1@_ENV["NameMon"] = "Mercenary"             -- It's Const#16, Const#236
	  +0F7F: 06 00 4E 00   line#227  GETTABUP 0 0 -57      <751>   R0 = Upv#1@_ENV["CFrame"]                       -- It's Const#57
	  +0F83: 07 40 4E 00   line#227  GETTABLE 0 0 -58      <752>   R0 = R0["new"]                                  -- It's Const#58
	  +0F87: 41 80 38 00   line#227  LOADK 1 -227          <753>   R1 = (-429.543518)                              -- It's Const#227
	  +0F8B: 81 C0 38 00   line#227  LOADK 2 -228          <754>   R2 = 71.7699966                                 -- It's Const#228
	  +0F8F: C1 00 39 00   line#227  LOADK 3 -229          <755>   R3 = 1836.18188                                 -- It's Const#229
	  +0F93: 01 41 39 00   line#227  LOADK 4 -230          <756>   R4 = (-0.22495985)                              -- It's Const#230
	  +0F97: 41 81 0F 00   line#227  LOADK 5 -63           <757>   R5 = 0                                          -- It's Const#63
	  +0F9B: 81 81 39 00   line#227  LOADK 6 -231          <758>   R6 = (-0.974368095)                             -- It's Const#231
	  +0F9F: C1 81 0F 00   line#227  LOADK 7 -63           <759>   R7 = 0                                          -- It's Const#63
	  +0FA3: 01 02 02 00   line#227  LOADK 8 -9            <760>   R8 = 1                                          -- It's Const#9
	  +0FA7: 41 82 0F 00   line#227  LOADK 9 -63           <761>   R9 = 0                                          -- It's Const#63
	  +0FAB: 81 C2 39 00   line#227  LOADK 10 -232         <762>   R10 = 0.974368095                               -- It's Const#232
	  +0FAF: C1 82 0F 00   line#227  LOADK 11 -63          <763>   R11 = 0                                         -- It's Const#63
	  +0FB3: 01 43 39 00   line#227  LOADK 12 -230         <764>   R12 = (-0.22495985)                             -- It's Const#230
	  +0FB7: 24 80 80 06   line#227  CALL 0 13 2           <765>   R0 = R0(R1,..,R12)
	  +0FBB: 08 00 80 88   line#227  SETTABUP 0 -18 0      <766>   Upv#1@_ENV["CFrameQuest"] = R0                  -- It's Const#18
	  +0FBF: 1E C0 A0 81   line#227  JMP 0 1668            <767>   GOTO <2436>
	  +0FC3: 06 00 40 00   line#228  GETTABUP 0 0 -1       <768>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +0FC7: 5F 00 7B 00   line#228  EQ 1 0 -237           <769>   if R0 ~= 775 then GOTO <771>                    -- It's Const#237
	  +0FCB: 1E 80 00 80   line#228  JMP 0 3               <770>   GOTO <774>
	  +0FCF: 06 00 40 00   line#228  GETTABUP 0 0 -1       <771>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +0FD3: 21 40 7B 00   line#228  LE 0 0 -238           <772>   if R0 <= 799 then GOTO <774>                    -- It's Const#238
	  +0FD7: 1E 00 05 80   line#228  JMP 0 21              <773>   GOTO <795>
	  +0FDB: 08 80 7B 85   line#229  SETTABUP 0 -11 -239   <774>   Upv#1@_ENV["Mon"] = "Swan Pirate [Lv. 775]"     -- It's Const#11, Const#239
	  +0FDF: 08 00 42 86   line#230  SETTABUP 0 -13 -9     <775>   Upv#1@_ENV["LQuest"] = 1                        -- It's Const#13, Const#9
	  +0FE3: 08 C0 FB 86   line#231  SETTABUP 0 -14 -240   <776>   Upv#1@_ENV["NQuest"] = "Area2Quest"             -- It's Const#14, Const#240
	  +0FE7: 08 00 FC 87   line#232  SETTABUP 0 -16 -241   <777>   Upv#1@_ENV["NameMon"] = "Swan Pirate"           -- It's Const#16, Const#241
	  +0FEB: 06 00 4E 00   line#233  GETTABUP 0 0 -57      <778>   R0 = Upv#1@_ENV["CFrame"]                       -- It's Const#57
	  +0FEF: 07 40 4E 00   line#233  GETTABLE 0 0 -58      <779>   R0 = R0["new"]                                  -- It's Const#58
	  +0FF3: 41 40 3C 00   line#233  LOADK 1 -242          <780>   R1 = 638.43811                                  -- It's Const#242
	  +0FF7: 81 80 3C 00   line#233  LOADK 2 -243          <781>   R2 = 71.769989                                  -- It's Const#243
	  +0FFB: C1 C0 3C 00   line#233  LOADK 3 -244          <782>   R3 = 918.282898                                 -- It's Const#244
	  +0FFF: 01 01 3D 00   line#233  LOADK 4 -245          <783>   R4 = 0.139203906                                -- It's Const#245
	  +1003: 41 81 0F 00   line#233  LOADK 5 -63           <784>   R5 = 0                                          -- It's Const#63
	  +1007: 81 41 3D 00   line#233  LOADK 6 -246          <785>   R6 = 0.99026376                                 -- It's Const#246
	  +100B: C1 81 0F 00   line#233  LOADK 7 -63           <786>   R7 = 0                                          -- It's Const#63
	  +100F: 01 02 02 00   line#233  LOADK 8 -9            <787>   R8 = 1                                          -- It's Const#9
	  +1013: 41 82 0F 00   line#233  LOADK 9 -63           <788>   R9 = 0                                          -- It's Const#63
	  +1017: 81 82 3D 00   line#233  LOADK 10 -247         <789>   R10 = (-0.99026376)                             -- It's Const#247
	  +101B: C1 82 0F 00   line#233  LOADK 11 -63          <790>   R11 = 0                                         -- It's Const#63
	  +101F: 01 03 3D 00   line#233  LOADK 12 -245         <791>   R12 = 0.139203906                               -- It's Const#245
	  +1023: 24 80 80 06   line#233  CALL 0 13 2           <792>   R0 = R0(R1,..,R12)
	  +1027: 08 00 80 88   line#233  SETTABUP 0 -18 0      <793>   Upv#1@_ENV["CFrameQuest"] = R0                  -- It's Const#18
	  +102B: 1E 00 9A 81   line#233  JMP 0 1641            <794>   GOTO <2436>
	  +102F: 06 00 40 00   line#234  GETTABUP 0 0 -1       <795>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +1033: 5F C0 7D 00   line#234  EQ 1 0 -248           <796>   if R0 ~= 800 then GOTO <798>                    -- It's Const#248
	  +1037: 1E 80 00 80   line#234  JMP 0 3               <797>   GOTO <801>
	  +103B: 06 00 40 00   line#234  GETTABUP 0 0 -1       <798>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +103F: 21 00 7E 00   line#234  LE 0 0 -249           <799>   if R0 <= 874 then GOTO <801>                    -- It's Const#249
	  +1043: 1E 00 05 80   line#234  JMP 0 21              <800>   GOTO <822>
	  +1047: 08 40 7E 85   line#235  SETTABUP 0 -11 -250   <801>   Upv#1@_ENV["Mon"] = "Factory Staff [Lv. 800]"   -- It's Const#11, Const#250
	  +104B: 08 C0 FB 86   line#236  SETTABUP 0 -14 -240   <802>   Upv#1@_ENV["NQuest"] = "Area2Quest"             -- It's Const#14, Const#240
	  +104F: 08 40 4D 86   line#237  SETTABUP 0 -13 -54    <803>   Upv#1@_ENV["LQuest"] = 2                        -- It's Const#13, Const#54
	  +1053: 08 80 FE 87   line#238  SETTABUP 0 -16 -251   <804>   Upv#1@_ENV["NameMon"] = "Factory Staff"         -- It's Const#16, Const#251
	  +1057: 06 00 4E 00   line#239  GETTABUP 0 0 -57      <805>   R0 = Upv#1@_ENV["CFrame"]                       -- It's Const#57
	  +105B: 07 40 4E 00   line#239  GETTABLE 0 0 -58      <806>   R0 = R0["new"]                                  -- It's Const#58
	  +105F: 41 C0 3E 00   line#239  LOADK 1 -252          <807>   R1 = 632.698608                                 -- It's Const#252
	  +1063: 81 00 3F 00   line#239  LOADK 2 -253          <808>   R2 = 73.1055908                                 -- It's Const#253
	  +1067: C1 40 3F 00   line#239  LOADK 3 -254          <809>   R3 = 918.666321                                 -- It's Const#254
	  +106B: 01 81 3F 00   line#239  LOADK 4 -255          <810>   R4 = (-0.0319722369)                            -- It's Const#255
	  +106F: 41 C1 3F 00   line#239  LOADK 5 -256          <811>   R5 = 8.96074881e-010                            -- It's Const#256
	  +1073: 81 01 40 00   line#239  LOADK 6 -257          <812>   R6 = (-0.999488771)                             -- It's Const#257
	  +1077: C1 41 40 00   line#239  LOADK 7 -258          <813>   R7 = 1.36326533e-010                            -- It's Const#258
	  +107B: 01 02 02 00   line#239  LOADK 8 -9            <814>   R8 = 1                                          -- It's Const#9
	  +107F: 41 82 40 00   line#239  LOADK 9 -259          <815>   R9 = 8.92172336e-010                            -- It's Const#259
	  +1083: 81 C2 40 00   line#239  LOADK 10 -260         <816>   R10 = 0.999488771                               -- It's Const#260
	  +1087: C1 02 41 00   line#239  LOADK 11 -261         <817>   R11 = (-1.07732087e-010)                        -- It's Const#261
	  +108B: 01 83 3F 00   line#239  LOADK 12 -255         <818>   R12 = (-0.0319722369)                           -- It's Const#255
	  +108F: 24 80 80 06   line#239  CALL 0 13 2           <819>   R0 = R0(R1,..,R12)
	  +1093: 08 00 80 88   line#239  SETTABUP 0 -18 0      <820>   Upv#1@_ENV["CFrameQuest"] = R0                  -- It's Const#18
	  +1097: 1E 40 93 81   line#239  JMP 0 1614            <821>   GOTO <2436>
	  +109B: 06 00 40 00   line#240  GETTABUP 0 0 -1       <822>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +109F: 41 40 41 00   line#240  LOADK 1 -262          <823>   R1 = 875                                        -- It's Const#262
	  +10A3: 5F 40 00 00   line#240  EQ 1 0 1              <824>   if R0 ~= R1 then GOTO <826>
	  +10A7: 1E C0 00 80   line#240  JMP 0 4               <825>   GOTO <830>
	  +10AB: 06 00 40 00   line#240  GETTABUP 0 0 -1       <826>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +10AF: 41 80 41 00   line#240  LOADK 1 -263          <827>   R1 = 899                                        -- It's Const#263
	  +10B3: 21 40 00 00   line#240  LE 0 0 1              <828>   if R0 <= R1 then GOTO <830>
	  +10B7: 1E C0 05 80   line#240  JMP 0 24              <829>   GOTO <854>
	  +10BB: 01 C0 41 00   line#241  LOADK 0 -264          <830>   R0 = "Marine Lieutenant [Lv. 875]"              -- It's Const#264
	  +10BF: 08 00 00 85   line#241  SETTABUP 0 -11 0      <831>   Upv#1@_ENV["Mon"] = R0                          -- It's Const#11
	  +10C3: 08 00 42 86   line#242  SETTABUP 0 -13 -9     <832>   Upv#1@_ENV["LQuest"] = 1                        -- It's Const#13, Const#9
	  +10C7: 01 00 42 00   line#243  LOADK 0 -265          <833>   R0 = "MarineQuest3"                             -- It's Const#265
	  +10CB: 08 00 80 86   line#243  SETTABUP 0 -14 0      <834>   Upv#1@_ENV["NQuest"] = R0                       -- It's Const#14
	  +10CF: 01 40 42 00   line#244  LOADK 0 -266          <835>   R0 = "Marine Lieutenant"                        -- It's Const#266
	  +10D3: 08 00 80 87   line#244  SETTABUP 0 -16 0      <836>   Upv#1@_ENV["NameMon"] = R0                      -- It's Const#16
	  +10D7: 06 00 4E 00   line#245  GETTABUP 0 0 -57      <837>   R0 = Upv#1@_ENV["CFrame"]                       -- It's Const#57
	  +10DB: 07 40 4E 00   line#245  GETTABLE 0 0 -58      <838>   R0 = R0["new"]                                  -- It's Const#58
	  +10DF: 41 80 42 00   line#245  LOADK 1 -267          <839>   R1 = (-2440.79639)                              -- It's Const#267
	  +10E3: 81 C0 42 00   line#245  LOADK 2 -268          <840>   R2 = 71.7140732                                 -- It's Const#268
	  +10E7: C1 00 43 00   line#245  LOADK 3 -269          <841>   R3 = (-3216.06812)                              -- It's Const#269
	  +10EB: 01 41 14 00   line#245  LOADK 4 -82           <842>   R4 = 0.866007268                                -- It's Const#82
	  +10EF: 41 81 0F 00   line#245  LOADK 5 -63           <843>   R5 = 0                                          -- It's Const#63
	  +10F3: 81 81 14 00   line#245  LOADK 6 -83           <844>   R6 = 0.500031412                                -- It's Const#83
	  +10F7: C1 81 0F 00   line#245  LOADK 7 -63           <845>   R7 = 0                                          -- It's Const#63
	  +10FB: 01 02 02 00   line#245  LOADK 8 -9            <846>   R8 = 1                                          -- It's Const#9
	  +10FF: 41 82 0F 00   line#245  LOADK 9 -63           <847>   R9 = 0                                          -- It's Const#63
	  +1103: 81 C2 14 00   line#245  LOADK 10 -84          <848>   R10 = (-0.500031412)                            -- It's Const#84
	  +1107: C1 82 0F 00   line#245  LOADK 11 -63          <849>   R11 = 0                                         -- It's Const#63
	  +110B: 01 43 14 00   line#245  LOADK 12 -82          <850>   R12 = 0.866007268                               -- It's Const#82
	  +110F: 24 80 80 06   line#245  CALL 0 13 2           <851>   R0 = R0(R1,..,R12)
	  +1113: 08 00 80 88   line#245  SETTABUP 0 -18 0      <852>   Upv#1@_ENV["CFrameQuest"] = R0                  -- It's Const#18
	  +1117: 1E 40 8B 81   line#245  JMP 0 1582            <853>   GOTO <2436>
	  +111B: 06 00 40 00   line#246  GETTABUP 0 0 -1       <854>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +111F: 41 40 43 00   line#246  LOADK 1 -270          <855>   R1 = 900                                        -- It's Const#270
	  +1123: 5F 40 00 00   line#246  EQ 1 0 1              <856>   if R0 ~= R1 then GOTO <858>
	  +1127: 1E C0 00 80   line#246  JMP 0 4               <857>   GOTO <862>
	  +112B: 06 00 40 00   line#246  GETTABUP 0 0 -1       <858>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +112F: 41 80 43 00   line#246  LOADK 1 -271          <859>   R1 = 949                                        -- It's Const#271
	  +1133: 21 40 00 00   line#246  LE 0 0 1              <860>   if R0 <= R1 then GOTO <862>
	  +1137: 1E C0 05 80   line#246  JMP 0 24              <861>   GOTO <886>
	  +113B: 01 C0 43 00   line#247  LOADK 0 -272          <862>   R0 = "Marine Captain [Lv. 900]"                 -- It's Const#272
	  +113F: 08 00 00 85   line#247  SETTABUP 0 -11 0      <863>   Upv#1@_ENV["Mon"] = R0                          -- It's Const#11
	  +1143: 08 40 4D 86   line#248  SETTABUP 0 -13 -54    <864>   Upv#1@_ENV["LQuest"] = 2                        -- It's Const#13, Const#54
	  +1147: 01 00 42 00   line#249  LOADK 0 -265          <865>   R0 = "MarineQuest3"                             -- It's Const#265
	  +114B: 08 00 80 86   line#249  SETTABUP 0 -14 0      <866>   Upv#1@_ENV["NQuest"] = R0                       -- It's Const#14
	  +114F: 01 00 44 00   line#250  LOADK 0 -273          <867>   R0 = "Marine Captain"                           -- It's Const#273
	  +1153: 08 00 80 87   line#250  SETTABUP 0 -16 0      <868>   Upv#1@_ENV["NameMon"] = R0                      -- It's Const#16
	  +1157: 06 00 4E 00   line#251  GETTABUP 0 0 -57      <869>   R0 = Upv#1@_ENV["CFrame"]                       -- It's Const#57
	  +115B: 07 40 4E 00   line#251  GETTABLE 0 0 -58      <870>   R0 = R0["new"]                                  -- It's Const#58
	  +115F: 41 80 42 00   line#251  LOADK 1 -267          <871>   R1 = (-2440.79639)                              -- It's Const#267
	  +1163: 81 C0 42 00   line#251  LOADK 2 -268          <872>   R2 = 71.7140732                                 -- It's Const#268
	  +1167: C1 00 43 00   line#251  LOADK 3 -269          <873>   R3 = (-3216.06812)                              -- It's Const#269
	  +116B: 01 41 14 00   line#251  LOADK 4 -82           <874>   R4 = 0.866007268                                -- It's Const#82
	  +116F: 41 81 0F 00   line#251  LOADK 5 -63           <875>   R5 = 0                                          -- It's Const#63
	  +1173: 81 81 14 00   line#251  LOADK 6 -83           <876>   R6 = 0.500031412                                -- It's Const#83
	  +1177: C1 81 0F 00   line#251  LOADK 7 -63           <877>   R7 = 0                                          -- It's Const#63
	  +117B: 01 02 02 00   line#251  LOADK 8 -9            <878>   R8 = 1                                          -- It's Const#9
	  +117F: 41 82 0F 00   line#251  LOADK 9 -63           <879>   R9 = 0                                          -- It's Const#63
	  +1183: 81 C2 14 00   line#251  LOADK 10 -84          <880>   R10 = (-0.500031412)                            -- It's Const#84
	  +1187: C1 82 0F 00   line#251  LOADK 11 -63          <881>   R11 = 0                                         -- It's Const#63
	  +118B: 01 43 14 00   line#251  LOADK 12 -82          <882>   R12 = 0.866007268                               -- It's Const#82
	  +118F: 24 80 80 06   line#251  CALL 0 13 2           <883>   R0 = R0(R1,..,R12)
	  +1193: 08 00 80 88   line#251  SETTABUP 0 -18 0      <884>   Upv#1@_ENV["CFrameQuest"] = R0                  -- It's Const#18
	  +1197: 1E 40 83 81   line#251  JMP 0 1550            <885>   GOTO <2436>
	  +119B: 06 00 40 00   line#252  GETTABUP 0 0 -1       <886>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +119F: 41 40 44 00   line#252  LOADK 1 -274          <887>   R1 = 950                                        -- It's Const#274
	  +11A3: 5F 40 00 00   line#252  EQ 1 0 1              <888>   if R0 ~= R1 then GOTO <890>
	  +11A7: 1E C0 00 80   line#252  JMP 0 4               <889>   GOTO <894>
	  +11AB: 06 00 40 00   line#252  GETTABUP 0 0 -1       <890>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +11AF: 41 80 44 00   line#252  LOADK 1 -275          <891>   R1 = 974                                        -- It's Const#275
	  +11B3: 21 40 00 00   line#252  LE 0 0 1              <892>   if R0 <= R1 then GOTO <894>
	  +11B7: 1E C0 05 80   line#252  JMP 0 24              <893>   GOTO <918>
	  +11BB: 01 C0 44 00   line#253  LOADK 0 -276          <894>   R0 = "Zombie [Lv. 950]"                         -- It's Const#276
	  +11BF: 08 00 00 85   line#253  SETTABUP 0 -11 0      <895>   Upv#1@_ENV["Mon"] = R0                          -- It's Const#11
	  +11C3: 08 00 42 86   line#254  SETTABUP 0 -13 -9     <896>   Upv#1@_ENV["LQuest"] = 1                        -- It's Const#13, Const#9
	  +11C7: 01 00 45 00   line#255  LOADK 0 -277          <897>   R0 = "ZombieQuest"                              -- It's Const#277
	  +11CB: 08 00 80 86   line#255  SETTABUP 0 -14 0      <898>   Upv#1@_ENV["NQuest"] = R0                       -- It's Const#14
	  +11CF: 01 40 45 00   line#256  LOADK 0 -278          <899>   R0 = "Zombie"                                   -- It's Const#278
	  +11D3: 08 00 80 87   line#256  SETTABUP 0 -16 0      <900>   Upv#1@_ENV["NameMon"] = R0                      -- It's Const#16
	  +11D7: 06 00 4E 00   line#257  GETTABUP 0 0 -57      <901>   R0 = Upv#1@_ENV["CFrame"]                       -- It's Const#57
	  +11DB: 07 40 4E 00   line#257  GETTABLE 0 0 -58      <902>   R0 = R0["new"]                                  -- It's Const#58
	  +11DF: 41 80 45 00   line#257  LOADK 1 -279          <903>   R1 = (-5497.06152)                              -- It's Const#279
	  +11E3: 81 C0 45 00   line#257  LOADK 2 -280          <904>   R2 = 47.5923004                                 -- It's Const#280
	  +11E7: C1 00 46 00   line#257  LOADK 3 -281          <905>   R3 = (-795.237061)                              -- It's Const#281
	  +11EB: 01 41 46 00   line#257  LOADK 4 -282          <906>   R4 = (-0.29242146)                              -- It's Const#282
	  +11EF: 41 81 0F 00   line#257  LOADK 5 -63           <907>   R5 = 0                                          -- It's Const#63
	  +11F3: 81 81 46 00   line#257  LOADK 6 -283          <908>   R6 = (-0.95628953)                              -- It's Const#283
	  +11F7: C1 81 0F 00   line#257  LOADK 7 -63           <909>   R7 = 0                                          -- It's Const#63
	  +11FB: 01 02 02 00   line#257  LOADK 8 -9            <910>   R8 = 1                                          -- It's Const#9
	  +11FF: 41 82 0F 00   line#257  LOADK 9 -63           <911>   R9 = 0                                          -- It's Const#63
	  +1203: 81 C2 46 00   line#257  LOADK 10 -284         <912>   R10 = 0.95628953                                -- It's Const#284
	  +1207: C1 82 0F 00   line#257  LOADK 11 -63          <913>   R11 = 0                                         -- It's Const#63
	  +120B: 01 43 46 00   line#257  LOADK 12 -282         <914>   R12 = (-0.29242146)                             -- It's Const#282
	  +120F: 24 80 80 06   line#257  CALL 0 13 2           <915>   R0 = R0(R1,..,R12)
	  +1213: 08 00 80 88   line#257  SETTABUP 0 -18 0      <916>   Upv#1@_ENV["CFrameQuest"] = R0                  -- It's Const#18
	  +1217: 1E 40 7B 81   line#257  JMP 0 1518            <917>   GOTO <2436>
	  +121B: 06 00 40 00   line#258  GETTABUP 0 0 -1       <918>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +121F: 41 00 47 00   line#258  LOADK 1 -285          <919>   R1 = 975                                        -- It's Const#285
	  +1223: 5F 40 00 00   line#258  EQ 1 0 1              <920>   if R0 ~= R1 then GOTO <922>
	  +1227: 1E C0 00 80   line#258  JMP 0 4               <921>   GOTO <926>
	  +122B: 06 00 40 00   line#258  GETTABUP 0 0 -1       <922>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +122F: 41 40 47 00   line#258  LOADK 1 -286          <923>   R1 = 999                                        -- It's Const#286
	  +1233: 21 40 00 00   line#258  LE 0 0 1              <924>   if R0 <= R1 then GOTO <926>
	  +1237: 1E C0 05 80   line#258  JMP 0 24              <925>   GOTO <950>
	  +123B: 01 80 47 00   line#259  LOADK 0 -287          <926>   R0 = "Vampire [Lv. 975]"                        -- It's Const#287
	  +123F: 08 00 00 85   line#259  SETTABUP 0 -11 0      <927>   Upv#1@_ENV["Mon"] = R0                          -- It's Const#11
	  +1243: 08 40 4D 86   line#260  SETTABUP 0 -13 -54    <928>   Upv#1@_ENV["LQuest"] = 2                        -- It's Const#13, Const#54
	  +1247: 01 00 45 00   line#261  LOADK 0 -277          <929>   R0 = "ZombieQuest"                              -- It's Const#277
	  +124B: 08 00 80 86   line#261  SETTABUP 0 -14 0      <930>   Upv#1@_ENV["NQuest"] = R0                       -- It's Const#14
	  +124F: 01 C0 47 00   line#262  LOADK 0 -288          <931>   R0 = "Vampire"                                  -- It's Const#288
	  +1253: 08 00 80 87   line#262  SETTABUP 0 -16 0      <932>   Upv#1@_ENV["NameMon"] = R0                      -- It's Const#16
	  +1257: 06 00 4E 00   line#263  GETTABUP 0 0 -57      <933>   R0 = Upv#1@_ENV["CFrame"]                       -- It's Const#57
	  +125B: 07 40 4E 00   line#263  GETTABLE 0 0 -58      <934>   R0 = R0["new"]                                  -- It's Const#58
	  +125F: 41 80 45 00   line#263  LOADK 1 -279          <935>   R1 = (-5497.06152)                              -- It's Const#279
	  +1263: 81 C0 45 00   line#263  LOADK 2 -280          <936>   R2 = 47.5923004                                 -- It's Const#280
	  +1267: C1 00 46 00   line#263  LOADK 3 -281          <937>   R3 = (-795.237061)                              -- It's Const#281
	  +126B: 01 41 46 00   line#263  LOADK 4 -282          <938>   R4 = (-0.29242146)                              -- It's Const#282
	  +126F: 41 81 0F 00   line#263  LOADK 5 -63           <939>   R5 = 0                                          -- It's Const#63
	  +1273: 81 81 46 00   line#263  LOADK 6 -283          <940>   R6 = (-0.95628953)                              -- It's Const#283
	  +1277: C1 81 0F 00   line#263  LOADK 7 -63           <941>   R7 = 0                                          -- It's Const#63
	  +127B: 01 02 02 00   line#263  LOADK 8 -9            <942>   R8 = 1                                          -- It's Const#9
	  +127F: 41 82 0F 00   line#263  LOADK 9 -63           <943>   R9 = 0                                          -- It's Const#63
	  +1283: 81 C2 46 00   line#263  LOADK 10 -284         <944>   R10 = 0.95628953                                -- It's Const#284
	  +1287: C1 82 0F 00   line#263  LOADK 11 -63          <945>   R11 = 0                                         -- It's Const#63
	  +128B: 01 43 46 00   line#263  LOADK 12 -282         <946>   R12 = (-0.29242146)                             -- It's Const#282
	  +128F: 24 80 80 06   line#263  CALL 0 13 2           <947>   R0 = R0(R1,..,R12)
	  +1293: 08 00 80 88   line#263  SETTABUP 0 -18 0      <948>   Upv#1@_ENV["CFrameQuest"] = R0                  -- It's Const#18
	  +1297: 1E 40 73 81   line#263  JMP 0 1486            <949>   GOTO <2436>
	  +129B: 06 00 40 00   line#264  GETTABUP 0 0 -1       <950>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +129F: 41 00 48 00   line#264  LOADK 1 -289          <951>   R1 = 1000                                       -- It's Const#289
	  +12A3: 5F 40 00 00   line#264  EQ 1 0 1              <952>   if R0 ~= R1 then GOTO <954>
	  +12A7: 1E C0 00 80   line#264  JMP 0 4               <953>   GOTO <958>
	  +12AB: 06 00 40 00   line#264  GETTABUP 0 0 -1       <954>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +12AF: 41 40 48 00   line#264  LOADK 1 -290          <955>   R1 = 1049                                       -- It's Const#290
	  +12B3: 21 40 00 00   line#264  LE 0 0 1              <956>   if R0 <= R1 then GOTO <958>
	  +12B7: 1E C0 05 80   line#264  JMP 0 24              <957>   GOTO <982>
	  +12BB: 01 80 48 00   line#265  LOADK 0 -291          <958>   R0 = "Snow Trooper [Lv. 1000]"                  -- It's Const#291
	  +12BF: 08 00 00 85   line#265  SETTABUP 0 -11 0      <959>   Upv#1@_ENV["Mon"] = R0                          -- It's Const#11
	  +12C3: 08 00 42 86   line#266  SETTABUP 0 -13 -9     <960>   Upv#1@_ENV["LQuest"] = 1                        -- It's Const#13, Const#9
	  +12C7: 01 C0 48 00   line#267  LOADK 0 -292          <961>   R0 = "SnowMountainQuest"                        -- It's Const#292
	  +12CB: 08 00 80 86   line#267  SETTABUP 0 -14 0      <962>   Upv#1@_ENV["NQuest"] = R0                       -- It's Const#14
	  +12CF: 01 00 49 00   line#268  LOADK 0 -293          <963>   R0 = "Snow Trooper"                             -- It's Const#293
	  +12D3: 08 00 80 87   line#268  SETTABUP 0 -16 0      <964>   Upv#1@_ENV["NameMon"] = R0                      -- It's Const#16
	  +12D7: 06 00 4E 00   line#269  GETTABUP 0 0 -57      <965>   R0 = Upv#1@_ENV["CFrame"]                       -- It's Const#57
	  +12DB: 07 40 4E 00   line#269  GETTABLE 0 0 -58      <966>   R0 = R0["new"]                                  -- It's Const#58
	  +12DF: 41 40 49 00   line#269  LOADK 1 -294          <967>   R1 = 609.858826                                 -- It's Const#294
	  +12E3: 81 80 49 00   line#269  LOADK 2 -295          <968>   R2 = 400.119904                                 -- It's Const#295
	  +12E7: C1 C0 49 00   line#269  LOADK 3 -296          <969>   R3 = (-5372.25928)                              -- It's Const#296
	  +12EB: 01 01 4A 00   line#269  LOADK 4 -297          <970>   R4 = (-0.374604106)                             -- It's Const#297
	  +12EF: 41 81 0F 00   line#269  LOADK 5 -63           <971>   R5 = 0                                          -- It's Const#63
	  +12F3: 81 41 4A 00   line#269  LOADK 6 -298          <972>   R6 = 0.92718488                                 -- It's Const#298
	  +12F7: C1 81 0F 00   line#269  LOADK 7 -63           <973>   R7 = 0                                          -- It's Const#63
	  +12FB: 01 02 02 00   line#269  LOADK 8 -9            <974>   R8 = 1                                          -- It's Const#9
	  +12FF: 41 82 0F 00   line#269  LOADK 9 -63           <975>   R9 = 0                                          -- It's Const#63
	  +1303: 81 82 4A 00   line#269  LOADK 10 -299         <976>   R10 = (-0.92718488)                             -- It's Const#299
	  +1307: C1 82 0F 00   line#269  LOADK 11 -63          <977>   R11 = 0                                         -- It's Const#63
	  +130B: 01 03 4A 00   line#269  LOADK 12 -297         <978>   R12 = (-0.374604106)                            -- It's Const#297
	  +130F: 24 80 80 06   line#269  CALL 0 13 2           <979>   R0 = R0(R1,..,R12)
	  +1313: 08 00 80 88   line#269  SETTABUP 0 -18 0      <980>   Upv#1@_ENV["CFrameQuest"] = R0                  -- It's Const#18
	  +1317: 1E 40 6B 81   line#269  JMP 0 1454            <981>   GOTO <2436>
	  +131B: 06 00 40 00   line#270  GETTABUP 0 0 -1       <982>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +131F: 41 C0 4A 00   line#270  LOADK 1 -300          <983>   R1 = 1050                                       -- It's Const#300
	  +1323: 5F 40 00 00   line#270  EQ 1 0 1              <984>   if R0 ~= R1 then GOTO <986>
	  +1327: 1E C0 00 80   line#270  JMP 0 4               <985>   GOTO <990>
	  +132B: 06 00 40 00   line#270  GETTABUP 0 0 -1       <986>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +132F: 41 00 4B 00   line#270  LOADK 1 -301          <987>   R1 = 1099                                       -- It's Const#301
	  +1333: 21 40 00 00   line#270  LE 0 0 1              <988>   if R0 <= R1 then GOTO <990>
	  +1337: 1E C0 05 80   line#270  JMP 0 24              <989>   GOTO <1014>
	  +133B: 01 40 4B 00   line#271  LOADK 0 -302          <990>   R0 = "Winter Warrior [Lv. 1050]"                -- It's Const#302
	  +133F: 08 00 00 85   line#271  SETTABUP 0 -11 0      <991>   Upv#1@_ENV["Mon"] = R0                          -- It's Const#11
	  +1343: 08 40 4D 86   line#272  SETTABUP 0 -13 -54    <992>   Upv#1@_ENV["LQuest"] = 2                        -- It's Const#13, Const#54
	  +1347: 01 C0 48 00   line#273  LOADK 0 -292          <993>   R0 = "SnowMountainQuest"                        -- It's Const#292
	  +134B: 08 00 80 86   line#273  SETTABUP 0 -14 0      <994>   Upv#1@_ENV["NQuest"] = R0                       -- It's Const#14
	  +134F: 01 80 4B 00   line#274  LOADK 0 -303          <995>   R0 = "Winter Warrior"                           -- It's Const#303
	  +1353: 08 00 80 87   line#274  SETTABUP 0 -16 0      <996>   Upv#1@_ENV["NameMon"] = R0                      -- It's Const#16
	  +1357: 06 00 4E 00   line#275  GETTABUP 0 0 -57      <997>   R0 = Upv#1@_ENV["CFrame"]                       -- It's Const#57
	  +135B: 07 40 4E 00   line#275  GETTABLE 0 0 -58      <998>   R0 = R0["new"]                                  -- It's Const#58
	  +135F: 41 40 49 00   line#275  LOADK 1 -294          <999>   R1 = 609.858826                                 -- It's Const#294
	  +1363: 81 80 49 00   line#275  LOADK 2 -295         <1000>   R2 = 400.119904                                 -- It's Const#295
	  +1367: C1 C0 49 00   line#275  LOADK 3 -296         <1001>   R3 = (-5372.25928)                              -- It's Const#296
	  +136B: 01 01 4A 00   line#275  LOADK 4 -297         <1002>   R4 = (-0.374604106)                             -- It's Const#297
	  +136F: 41 81 0F 00   line#275  LOADK 5 -63          <1003>   R5 = 0                                          -- It's Const#63
	  +1373: 81 41 4A 00   line#275  LOADK 6 -298         <1004>   R6 = 0.92718488                                 -- It's Const#298
	  +1377: C1 81 0F 00   line#275  LOADK 7 -63          <1005>   R7 = 0                                          -- It's Const#63
	  +137B: 01 02 02 00   line#275  LOADK 8 -9           <1006>   R8 = 1                                          -- It's Const#9
	  +137F: 41 82 0F 00   line#275  LOADK 9 -63          <1007>   R9 = 0                                          -- It's Const#63
	  +1383: 81 82 4A 00   line#275  LOADK 10 -299        <1008>   R10 = (-0.92718488)                             -- It's Const#299
	  +1387: C1 82 0F 00   line#275  LOADK 11 -63         <1009>   R11 = 0                                         -- It's Const#63
	  +138B: 01 03 4A 00   line#275  LOADK 12 -297        <1010>   R12 = (-0.374604106)                            -- It's Const#297
	  +138F: 24 80 80 06   line#275  CALL 0 13 2          <1011>   R0 = R0(R1,..,R12)
	  +1393: 08 00 80 88   line#275  SETTABUP 0 -18 0     <1012>   Upv#1@_ENV["CFrameQuest"] = R0                  -- It's Const#18
	  +1397: 1E 40 63 81   line#275  JMP 0 1422           <1013>   GOTO <2436>
	  +139B: 06 00 40 00   line#276  GETTABUP 0 0 -1      <1014>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +139F: 41 C0 4B 00   line#276  LOADK 1 -304         <1015>   R1 = 1100                                       -- It's Const#304
	  +13A3: 5F 40 00 00   line#276  EQ 1 0 1             <1016>   if R0 ~= R1 then GOTO <1018>
	  +13A7: 1E C0 00 80   line#276  JMP 0 4              <1017>   GOTO <1022>
	  +13AB: 06 00 40 00   line#276  GETTABUP 0 0 -1      <1018>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +13AF: 41 00 4C 00   line#276  LOADK 1 -305         <1019>   R1 = 1124                                       -- It's Const#305
	  +13B3: 21 40 00 00   line#276  LE 0 0 1             <1020>   if R0 <= R1 then GOTO <1022>
	  +13B7: 1E C0 05 80   line#276  JMP 0 24             <1021>   GOTO <1046>
	  +13BB: 01 40 4C 00   line#277  LOADK 0 -306         <1022>   R0 = "Lab Subordinate [Lv. 1100]"               -- It's Const#306
	  +13BF: 08 00 00 85   line#277  SETTABUP 0 -11 0     <1023>   Upv#1@_ENV["Mon"] = R0                          -- It's Const#11
	  +13C3: 08 00 42 86   line#278  SETTABUP 0 -13 -9    <1024>   Upv#1@_ENV["LQuest"] = 1                        -- It's Const#13, Const#9
	  +13C7: 01 80 4C 00   line#279  LOADK 0 -307         <1025>   R0 = "IceSideQuest"                             -- It's Const#307
	  +13CB: 08 00 80 86   line#279  SETTABUP 0 -14 0     <1026>   Upv#1@_ENV["NQuest"] = R0                       -- It's Const#14
	  +13CF: 01 C0 4C 00   line#280  LOADK 0 -308         <1027>   R0 = "Lab Subordinate"                          -- It's Const#308
	  +13D3: 08 00 80 87   line#280  SETTABUP 0 -16 0     <1028>   Upv#1@_ENV["NameMon"] = R0                      -- It's Const#16
	  +13D7: 06 00 4E 00   line#281  GETTABUP 0 0 -57     <1029>   R0 = Upv#1@_ENV["CFrame"]                       -- It's Const#57
	  +13DB: 07 40 4E 00   line#281  GETTABLE 0 0 -58     <1030>   R0 = R0["new"]                                  -- It's Const#58
	  +13DF: 41 00 4D 00   line#281  LOADK 1 -309         <1031>   R1 = (-6064.06885)                              -- It's Const#309
	  +13E3: 81 40 4D 00   line#281  LOADK 2 -310         <1032>   R2 = 15.2422857                                 -- It's Const#310
	  +13E7: C1 80 4D 00   line#281  LOADK 3 -311         <1033>   R3 = (-4902.97852)                              -- It's Const#311
	  +13EB: 01 C1 4D 00   line#281  LOADK 4 -312         <1034>   R4 = 0.453972578                                -- It's Const#312
	  +13EF: 41 81 0F 00   line#281  LOADK 5 -63          <1035>   R5 = 0                                          -- It's Const#63
	  +13F3: 81 01 4E 00   line#281  LOADK 6 -313         <1036>   R6 = (-0.891015649)                             -- It's Const#313
	  +13F7: C1 81 0F 00   line#281  LOADK 7 -63          <1037>   R7 = 0                                          -- It's Const#63
	  +13FB: 01 02 02 00   line#281  LOADK 8 -9           <1038>   R8 = 1                                          -- It's Const#9
	  +13FF: 41 82 0F 00   line#281  LOADK 9 -63          <1039>   R9 = 0                                          -- It's Const#63
	  +1403: 81 42 4E 00   line#281  LOADK 10 -314        <1040>   R10 = 0.891015649                               -- It's Const#314
	  +1407: C1 82 0F 00   line#281  LOADK 11 -63         <1041>   R11 = 0                                         -- It's Const#63
	  +140B: 01 C3 4D 00   line#281  LOADK 12 -312        <1042>   R12 = 0.453972578                               -- It's Const#312
	  +140F: 24 80 80 06   line#281  CALL 0 13 2          <1043>   R0 = R0(R1,..,R12)
	  +1413: 08 00 80 88   line#281  SETTABUP 0 -18 0     <1044>   Upv#1@_ENV["CFrameQuest"] = R0                  -- It's Const#18
	  +1417: 1E 40 5B 81   line#281  JMP 0 1390           <1045>   GOTO <2436>
	  +141B: 06 00 40 00   line#282  GETTABUP 0 0 -1      <1046>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +141F: 41 80 4E 00   line#282  LOADK 1 -315         <1047>   R1 = 1125                                       -- It's Const#315
	  +1423: 5F 40 00 00   line#282  EQ 1 0 1             <1048>   if R0 ~= R1 then GOTO <1050>
	  +1427: 1E C0 00 80   line#282  JMP 0 4              <1049>   GOTO <1054>
	  +142B: 06 00 40 00   line#282  GETTABUP 0 0 -1      <1050>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +142F: 41 C0 4E 00   line#282  LOADK 1 -316         <1051>   R1 = 1174                                       -- It's Const#316
	  +1433: 21 40 00 00   line#282  LE 0 0 1             <1052>   if R0 <= R1 then GOTO <1054>
	  +1437: 1E C0 05 80   line#282  JMP 0 24             <1053>   GOTO <1078>
	  +143B: 01 00 4F 00   line#283  LOADK 0 -317         <1054>   R0 = "Horned Warrior [Lv. 1125]"                -- It's Const#317
	  +143F: 08 00 00 85   line#283  SETTABUP 0 -11 0     <1055>   Upv#1@_ENV["Mon"] = R0                          -- It's Const#11
	  +1443: 08 40 4D 86   line#284  SETTABUP 0 -13 -54   <1056>   Upv#1@_ENV["LQuest"] = 2                        -- It's Const#13, Const#54
	  +1447: 01 80 4C 00   line#285  LOADK 0 -307         <1057>   R0 = "IceSideQuest"                             -- It's Const#307
	  +144B: 08 00 80 86   line#285  SETTABUP 0 -14 0     <1058>   Upv#1@_ENV["NQuest"] = R0                       -- It's Const#14
	  +144F: 01 40 4F 00   line#286  LOADK 0 -318         <1059>   R0 = "Horned Warrior"                           -- It's Const#318
	  +1453: 08 00 80 87   line#286  SETTABUP 0 -16 0     <1060>   Upv#1@_ENV["NameMon"] = R0                      -- It's Const#16
	  +1457: 06 00 4E 00   line#287  GETTABUP 0 0 -57     <1061>   R0 = Upv#1@_ENV["CFrame"]                       -- It's Const#57
	  +145B: 07 40 4E 00   line#287  GETTABLE 0 0 -58     <1062>   R0 = R0["new"]                                  -- It's Const#58
	  +145F: 41 00 4D 00   line#287  LOADK 1 -309         <1063>   R1 = (-6064.06885)                              -- It's Const#309
	  +1463: 81 40 4D 00   line#287  LOADK 2 -310         <1064>   R2 = 15.2422857                                 -- It's Const#310
	  +1467: C1 80 4D 00   line#287  LOADK 3 -311         <1065>   R3 = (-4902.97852)                              -- It's Const#311
	  +146B: 01 C1 4D 00   line#287  LOADK 4 -312         <1066>   R4 = 0.453972578                                -- It's Const#312
	  +146F: 41 81 0F 00   line#287  LOADK 5 -63          <1067>   R5 = 0                                          -- It's Const#63
	  +1473: 81 01 4E 00   line#287  LOADK 6 -313         <1068>   R6 = (-0.891015649)                             -- It's Const#313
	  +1477: C1 81 0F 00   line#287  LOADK 7 -63          <1069>   R7 = 0                                          -- It's Const#63
	  +147B: 01 02 02 00   line#287  LOADK 8 -9           <1070>   R8 = 1                                          -- It's Const#9
	  +147F: 41 82 0F 00   line#287  LOADK 9 -63          <1071>   R9 = 0                                          -- It's Const#63
	  +1483: 81 42 4E 00   line#287  LOADK 10 -314        <1072>   R10 = 0.891015649                               -- It's Const#314
	  +1487: C1 82 0F 00   line#287  LOADK 11 -63         <1073>   R11 = 0                                         -- It's Const#63
	  +148B: 01 C3 4D 00   line#287  LOADK 12 -312        <1074>   R12 = 0.453972578                               -- It's Const#312
	  +148F: 24 80 80 06   line#287  CALL 0 13 2          <1075>   R0 = R0(R1,..,R12)
	  +1493: 08 00 80 88   line#287  SETTABUP 0 -18 0     <1076>   Upv#1@_ENV["CFrameQuest"] = R0                  -- It's Const#18
	  +1497: 1E 40 53 81   line#287  JMP 0 1358           <1077>   GOTO <2436>
	  +149B: 06 00 40 00   line#288  GETTABUP 0 0 -1      <1078>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +149F: 41 80 4F 00   line#288  LOADK 1 -319         <1079>   R1 = 1175                                       -- It's Const#319
	  +14A3: 5F 40 00 00   line#288  EQ 1 0 1             <1080>   if R0 ~= R1 then GOTO <1082>
	  +14A7: 1E C0 00 80   line#288  JMP 0 4              <1081>   GOTO <1086>
	  +14AB: 06 00 40 00   line#288  GETTABUP 0 0 -1      <1082>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +14AF: 41 C0 4F 00   line#288  LOADK 1 -320         <1083>   R1 = 1199                                       -- It's Const#320
	  +14B3: 21 40 00 00   line#288  LE 0 0 1             <1084>   if R0 <= R1 then GOTO <1086>
	  +14B7: 1E C0 05 80   line#288  JMP 0 24             <1085>   GOTO <1110>
	  +14BB: 01 00 50 00   line#289  LOADK 0 -321         <1086>   R0 = "Magma Ninja [Lv. 1175]"                   -- It's Const#321
	  +14BF: 08 00 00 85   line#289  SETTABUP 0 -11 0     <1087>   Upv#1@_ENV["Mon"] = R0                          -- It's Const#11
	  +14C3: 08 00 42 86   line#290  SETTABUP 0 -13 -9    <1088>   Upv#1@_ENV["LQuest"] = 1                        -- It's Const#13, Const#9
	  +14C7: 01 40 50 00   line#291  LOADK 0 -322         <1089>   R0 = "FireSideQuest"                            -- It's Const#322
	  +14CB: 08 00 80 86   line#291  SETTABUP 0 -14 0     <1090>   Upv#1@_ENV["NQuest"] = R0                       -- It's Const#14
	  +14CF: 01 80 50 00   line#292  LOADK 0 -323         <1091>   R0 = "Magma Ninja"                              -- It's Const#323
	  +14D3: 08 00 80 87   line#292  SETTABUP 0 -16 0     <1092>   Upv#1@_ENV["NameMon"] = R0                      -- It's Const#16
	  +14D7: 06 00 4E 00   line#293  GETTABUP 0 0 -57     <1093>   R0 = Upv#1@_ENV["CFrame"]                       -- It's Const#57
	  +14DB: 07 40 4E 00   line#293  GETTABLE 0 0 -58     <1094>   R0 = R0["new"]                                  -- It's Const#58
	  +14DF: 41 C0 50 00   line#293  LOADK 1 -324         <1095>   R1 = (-5428.03174)                              -- It's Const#324
	  +14E3: 81 00 51 00   line#293  LOADK 2 -325         <1096>   R2 = 15.0622921                                 -- It's Const#325
	  +14E7: C1 40 51 00   line#293  LOADK 3 -326         <1097>   R3 = (-5299.43457)                              -- It's Const#326
	  +14EB: 01 81 51 00   line#293  LOADK 4 -327         <1098>   R4 = (-0.882952213)                             -- It's Const#327
	  +14EF: 41 81 0F 00   line#293  LOADK 5 -63          <1099>   R5 = 0                                          -- It's Const#63
	  +14F3: 81 C1 51 00   line#293  LOADK 6 -328         <1100>   R6 = 0.469463557                                -- It's Const#328
	  +14F7: C1 81 0F 00   line#293  LOADK 7 -63          <1101>   R7 = 0                                          -- It's Const#63
	  +14FB: 01 02 02 00   line#293  LOADK 8 -9           <1102>   R8 = 1                                          -- It's Const#9
	  +14FF: 41 82 0F 00   line#293  LOADK 9 -63          <1103>   R9 = 0                                          -- It's Const#63
	  +1503: 81 02 52 00   line#293  LOADK 10 -329        <1104>   R10 = (-0.469463557)                            -- It's Const#329
	  +1507: C1 82 0F 00   line#293  LOADK 11 -63         <1105>   R11 = 0                                         -- It's Const#63
	  +150B: 01 83 51 00   line#293  LOADK 12 -327        <1106>   R12 = (-0.882952213)                            -- It's Const#327
	  +150F: 24 80 80 06   line#293  CALL 0 13 2          <1107>   R0 = R0(R1,..,R12)
	  +1513: 08 00 80 88   line#293  SETTABUP 0 -18 0     <1108>   Upv#1@_ENV["CFrameQuest"] = R0                  -- It's Const#18
	  +1517: 1E 40 4B 81   line#293  JMP 0 1326           <1109>   GOTO <2436>
	  +151B: 06 00 40 00   line#294  GETTABUP 0 0 -1      <1110>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +151F: 41 40 52 00   line#294  LOADK 1 -330         <1111>   R1 = 1200                                       -- It's Const#330
	  +1523: 5F 40 00 00   line#294  EQ 1 0 1             <1112>   if R0 ~= R1 then GOTO <1114>
	  +1527: 1E C0 00 80   line#294  JMP 0 4              <1113>   GOTO <1118>
	  +152B: 06 00 40 00   line#294  GETTABUP 0 0 -1      <1114>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +152F: 41 80 52 00   line#294  LOADK 1 -331         <1115>   R1 = 1249                                       -- It's Const#331
	  +1533: 21 40 00 00   line#294  LE 0 0 1             <1116>   if R0 <= R1 then GOTO <1118>
	  +1537: 1E C0 05 80   line#294  JMP 0 24             <1117>   GOTO <1142>
	  +153B: 01 C0 52 00   line#295  LOADK 0 -332         <1118>   R0 = "Lava Pirate [Lv. 1200]"                   -- It's Const#332
	  +153F: 08 00 00 85   line#295  SETTABUP 0 -11 0     <1119>   Upv#1@_ENV["Mon"] = R0                          -- It's Const#11
	  +1543: 08 40 4D 86   line#296  SETTABUP 0 -13 -54   <1120>   Upv#1@_ENV["LQuest"] = 2                        -- It's Const#13, Const#54
	  +1547: 01 40 50 00   line#297  LOADK 0 -322         <1121>   R0 = "FireSideQuest"                            -- It's Const#322
	  +154B: 08 00 80 86   line#297  SETTABUP 0 -14 0     <1122>   Upv#1@_ENV["NQuest"] = R0                       -- It's Const#14
	  +154F: 01 00 53 00   line#298  LOADK 0 -333         <1123>   R0 = "Lava Pirate"                              -- It's Const#333
	  +1553: 08 00 80 87   line#298  SETTABUP 0 -16 0     <1124>   Upv#1@_ENV["NameMon"] = R0                      -- It's Const#16
	  +1557: 06 00 4E 00   line#299  GETTABUP 0 0 -57     <1125>   R0 = Upv#1@_ENV["CFrame"]                       -- It's Const#57
	  +155B: 07 40 4E 00   line#299  GETTABLE 0 0 -58     <1126>   R0 = R0["new"]                                  -- It's Const#58
	  +155F: 41 C0 50 00   line#299  LOADK 1 -324         <1127>   R1 = (-5428.03174)                              -- It's Const#324
	  +1563: 81 00 51 00   line#299  LOADK 2 -325         <1128>   R2 = 15.0622921                                 -- It's Const#325
	  +1567: C1 40 51 00   line#299  LOADK 3 -326         <1129>   R3 = (-5299.43457)                              -- It's Const#326
	  +156B: 01 81 51 00   line#299  LOADK 4 -327         <1130>   R4 = (-0.882952213)                             -- It's Const#327
	  +156F: 41 81 0F 00   line#299  LOADK 5 -63          <1131>   R5 = 0                                          -- It's Const#63
	  +1573: 81 C1 51 00   line#299  LOADK 6 -328         <1132>   R6 = 0.469463557                                -- It's Const#328
	  +1577: C1 81 0F 00   line#299  LOADK 7 -63          <1133>   R7 = 0                                          -- It's Const#63
	  +157B: 01 02 02 00   line#299  LOADK 8 -9           <1134>   R8 = 1                                          -- It's Const#9
	  +157F: 41 82 0F 00   line#299  LOADK 9 -63          <1135>   R9 = 0                                          -- It's Const#63
	  +1583: 81 02 52 00   line#299  LOADK 10 -329        <1136>   R10 = (-0.469463557)                            -- It's Const#329
	  +1587: C1 82 0F 00   line#299  LOADK 11 -63         <1137>   R11 = 0                                         -- It's Const#63
	  +158B: 01 83 51 00   line#299  LOADK 12 -327        <1138>   R12 = (-0.882952213)                            -- It's Const#327
	  +158F: 24 80 80 06   line#299  CALL 0 13 2          <1139>   R0 = R0(R1,..,R12)
	  +1593: 08 00 80 88   line#299  SETTABUP 0 -18 0     <1140>   Upv#1@_ENV["CFrameQuest"] = R0                  -- It's Const#18
	  +1597: 1E 40 43 81   line#299  JMP 0 1294           <1141>   GOTO <2436>
	  +159B: 06 00 40 00   line#300  GETTABUP 0 0 -1      <1142>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +159F: 41 40 53 00   line#300  LOADK 1 -334         <1143>   R1 = 1250                                       -- It's Const#334
	  +15A3: 5F 40 00 00   line#300  EQ 1 0 1             <1144>   if R0 ~= R1 then GOTO <1146>
	  +15A7: 1E C0 00 80   line#300  JMP 0 4              <1145>   GOTO <1150>
	  +15AB: 06 00 40 00   line#300  GETTABUP 0 0 -1      <1146>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +15AF: 41 80 53 00   line#300  LOADK 1 -335         <1147>   R1 = 1274                                       -- It's Const#335
	  +15B3: 21 40 00 00   line#300  LE 0 0 1             <1148>   if R0 <= R1 then GOTO <1150>
	  +15B7: 1E 40 0B 80   line#300  JMP 0 46             <1149>   GOTO <1196>
	  +15BB: 01 C0 53 00   line#301  LOADK 0 -336         <1150>   R0 = "Ship Deckhand [Lv. 1250]"                 -- It's Const#336
	  +15BF: 08 00 00 85   line#301  SETTABUP 0 -11 0     <1151>   Upv#1@_ENV["Mon"] = R0                          -- It's Const#11
	  +15C3: 08 00 42 86   line#302  SETTABUP 0 -13 -9    <1152>   Upv#1@_ENV["LQuest"] = 1                        -- It's Const#13, Const#9
	  +15C7: 01 00 54 00   line#303  LOADK 0 -337         <1153>   R0 = "ShipQuest1"                               -- It's Const#337
	  +15CB: 08 00 80 86   line#303  SETTABUP 0 -14 0     <1154>   Upv#1@_ENV["NQuest"] = R0                       -- It's Const#14
	  +15CF: 01 40 54 00   line#304  LOADK 0 -338         <1155>   R0 = "Ship Deckhand"                            -- It's Const#338
	  +15D3: 08 00 80 87   line#304  SETTABUP 0 -16 0     <1156>   Upv#1@_ENV["NameMon"] = R0                      -- It's Const#16
	  +15D7: 06 00 4E 00   line#305  GETTABUP 0 0 -57     <1157>   R0 = Upv#1@_ENV["CFrame"]                       -- It's Const#57
	  +15DB: 07 40 4E 00   line#305  GETTABLE 0 0 -58     <1158>   R0 = R0["new"]                                  -- It's Const#58
	  +15DF: 41 80 54 00   line#305  LOADK 1 -339         <1159>   R1 = 1037.80127                                 -- It's Const#339
	  +15E3: 81 C0 54 00   line#305  LOADK 2 -340         <1160>   R2 = 125.092171                                 -- It's Const#340
	  +15E7: C1 00 55 00   line#305  LOADK 3 -341         <1161>   R3 = 32911.6016                                 -- It's Const#341
	  +15EB: 24 80 00 02   line#305  CALL 0 4 2           <1162>   R0 = R0(R1, R2, R3)
	  +15EF: 08 00 80 88   line#305  SETTABUP 0 -18 0     <1163>   Upv#1@_ENV["CFrameQuest"] = R0                  -- It's Const#18
	  +15F3: 06 40 64 00   line#306  GETTABUP 0 0 -146    <1164>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#146
	  +15F7: 07 80 64 00   line#306  GETTABLE 0 0 -147    <1165>   R0 = R0["AutoFarm"]                             -- It's Const#147
	  +15FB: 22 00 00 00   line#306  TEST 0 0             <1166>   if R0 then GOTO <1168>
	  +15FF: 1E C0 3C 81   line#306  JMP 0 1268           <1167>   GOTO <2436>
	  +1603: 06 40 44 00   line#306  GETTABUP 0 0 -18     <1168>   R0 = Upv#1@_ENV["CFrameQuest"]                  -- It's Const#18
	  +1607: 07 C0 64 00   line#306  GETTABLE 0 0 -148    <1169>   R0 = R0["Position"]                             -- It's Const#148
	  +160B: 46 00 65 00   line#306  GETTABUP 1 0 -149    <1170>   R1 = Upv#1@_ENV["game"]                         -- It's Const#149
	  +160F: 47 C0 C0 00   line#306  GETTABLE 1 1 -4      <1171>   R1 = R1["Players"]                              -- It's Const#4
	  +1613: 47 00 C1 00   line#306  GETTABLE 1 1 -5      <1172>   R1 = R1["LocalPlayer"]                          -- It's Const#5
	  +1617: 47 40 E5 00   line#306  GETTABLE 1 1 -150    <1173>   R1 = R1["Character"]                            -- It's Const#150
	  +161B: 47 80 E5 00   line#306  GETTABLE 1 1 -151    <1174>   R1 = R1["HumanoidRootPart"]                     -- It's Const#151
	  +161F: 47 C0 E4 00   line#306  GETTABLE 1 1 -148    <1175>   R1 = R1["Position"]                             -- It's Const#148
	  +1623: 0E 40 00 00   line#306  SUB 0 0 1            <1176>   R0 = R0 - R1
	  +1627: 07 C0 65 00   line#306  GETTABLE 0 0 -152    <1177>   R0 = R0["Magnitude"]                            -- It's Const#152
	  +162B: 20 00 00 CC   line#306  LT 0 -153 0          <1178>   if R0 > 10000 then GOTO <1180>                  -- It's Const#153
	  +162F: 1E C0 39 81   line#306  JMP 0 1256           <1179>   GOTO <2436>
	  +1633: 06 00 65 00   line#307  GETTABUP 0 0 -149    <1180>   R0 = Upv#1@_ENV["game"]                         -- It's Const#149
	  +1637: 0C 40 66 00   line#307  SELF 0 0 -154        <1181>   R1 = R0;  R0 = R0["GetService"]                 -- It's Const#154   -- prepare for R0:GetService()
	  +163B: 81 80 26 00   line#307  LOADK 2 -155         <1182>   R2 = "ReplicatedStorage"                        -- It's Const#155
	  +163F: 24 80 80 01   line#307  CALL 0 3 2           <1183>   R0 = R0(R1, R2)
	  +1643: 07 C0 66 00   line#307  GETTABLE 0 0 -156    <1184>   R0 = R0["Remotes"]                              -- It's Const#156
	  +1647: 07 00 67 00   line#307  GETTABLE 0 0 -157    <1185>   R0 = R0["CommF_"]                               -- It's Const#157
	  +164B: 0C 40 67 00   line#307  SELF 0 0 -158        <1186>   R1 = R0;  R0 = R0["InvokeServer"]               -- It's Const#158   -- prepare for R0:InvokeServer()
	  +164F: 81 80 27 00   line#307  LOADK 2 -159         <1187>   R2 = "requestEntrance"                          -- It's Const#159
	  +1653: C6 C0 67 00   line#307  GETTABUP 3 0 -160    <1188>   R3 = Upv#1@_ENV["Vector3"]                      -- It's Const#160
	  +1657: C7 40 CE 01   line#307  GETTABLE 3 3 -58     <1189>   R3 = R3["new"]                                  -- It's Const#58
	  +165B: 01 41 55 00   line#307  LOADK 4 -342         <1190>   R4 = 923.21252441406                            -- It's Const#342
	  +165F: 41 81 55 00   line#307  LOADK 5 -343         <1191>   R5 = 126.9760055542                             -- It's Const#343
	  +1663: 81 C1 55 00   line#307  LOADK 6 -344         <1192>   R6 = 32852.83203125                             -- It's Const#344
	  +1667: E4 00 00 02   line#307  CALL 3 4 0           <1193>   R3,.. = R3(R4, R5, R6)
	  +166B: 24 40 00 00   line#307  CALL 0 0 1           <1194>   R0(R1,..)
	  +166F: 1E C0 35 81   line#308  JMP 0 1240           <1195>   GOTO <2436>
	  +1673: 06 00 40 00   line#309  GETTABUP 0 0 -1      <1196>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +1677: 41 00 56 00   line#309  LOADK 1 -345         <1197>   R1 = 1275                                       -- It's Const#345
	  +167B: 5F 40 00 00   line#309  EQ 1 0 1             <1198>   if R0 ~= R1 then GOTO <1200>
	  +167F: 1E C0 00 80   line#309  JMP 0 4              <1199>   GOTO <1204>
	  +1683: 06 00 40 00   line#309  GETTABUP 0 0 -1      <1200>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +1687: 41 40 56 00   line#309  LOADK 1 -346         <1201>   R1 = 1299                                       -- It's Const#346
	  +168B: 21 40 00 00   line#309  LE 0 0 1             <1202>   if R0 <= R1 then GOTO <1204>
	  +168F: 1E 40 0B 80   line#309  JMP 0 46             <1203>   GOTO <1250>
	  +1693: 01 80 56 00   line#310  LOADK 0 -347         <1204>   R0 = "Ship Engineer [Lv. 1275]"                 -- It's Const#347
	  +1697: 08 00 00 85   line#310  SETTABUP 0 -11 0     <1205>   Upv#1@_ENV["Mon"] = R0                          -- It's Const#11
	  +169B: 08 40 4D 86   line#311  SETTABUP 0 -13 -54   <1206>   Upv#1@_ENV["LQuest"] = 2                        -- It's Const#13, Const#54
	  +169F: 01 00 54 00   line#312  LOADK 0 -337         <1207>   R0 = "ShipQuest1"                               -- It's Const#337
	  +16A3: 08 00 80 86   line#312  SETTABUP 0 -14 0     <1208>   Upv#1@_ENV["NQuest"] = R0                       -- It's Const#14
	  +16A7: 01 C0 56 00   line#313  LOADK 0 -348         <1209>   R0 = "Ship Engineer"                            -- It's Const#348
	  +16AB: 08 00 80 87   line#313  SETTABUP 0 -16 0     <1210>   Upv#1@_ENV["NameMon"] = R0                      -- It's Const#16
	  +16AF: 06 00 4E 00   line#314  GETTABUP 0 0 -57     <1211>   R0 = Upv#1@_ENV["CFrame"]                       -- It's Const#57
	  +16B3: 07 40 4E 00   line#314  GETTABLE 0 0 -58     <1212>   R0 = R0["new"]                                  -- It's Const#58
	  +16B7: 41 80 54 00   line#314  LOADK 1 -339         <1213>   R1 = 1037.80127                                 -- It's Const#339
	  +16BB: 81 C0 54 00   line#314  LOADK 2 -340         <1214>   R2 = 125.092171                                 -- It's Const#340
	  +16BF: C1 00 55 00   line#314  LOADK 3 -341         <1215>   R3 = 32911.6016                                 -- It's Const#341
	  +16C3: 24 80 00 02   line#314  CALL 0 4 2           <1216>   R0 = R0(R1, R2, R3)
	  +16C7: 08 00 80 88   line#314  SETTABUP 0 -18 0     <1217>   Upv#1@_ENV["CFrameQuest"] = R0                  -- It's Const#18
	  +16CB: 06 40 64 00   line#315  GETTABUP 0 0 -146    <1218>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#146
	  +16CF: 07 80 64 00   line#315  GETTABLE 0 0 -147    <1219>   R0 = R0["AutoFarm"]                             -- It's Const#147
	  +16D3: 22 00 00 00   line#315  TEST 0 0             <1220>   if R0 then GOTO <1222>
	  +16D7: 1E 40 2F 81   line#315  JMP 0 1214           <1221>   GOTO <2436>
	  +16DB: 06 40 44 00   line#315  GETTABUP 0 0 -18     <1222>   R0 = Upv#1@_ENV["CFrameQuest"]                  -- It's Const#18
	  +16DF: 07 C0 64 00   line#315  GETTABLE 0 0 -148    <1223>   R0 = R0["Position"]                             -- It's Const#148
	  +16E3: 46 00 65 00   line#315  GETTABUP 1 0 -149    <1224>   R1 = Upv#1@_ENV["game"]                         -- It's Const#149
	  +16E7: 47 C0 C0 00   line#315  GETTABLE 1 1 -4      <1225>   R1 = R1["Players"]                              -- It's Const#4
	  +16EB: 47 00 C1 00   line#315  GETTABLE 1 1 -5      <1226>   R1 = R1["LocalPlayer"]                          -- It's Const#5
	  +16EF: 47 40 E5 00   line#315  GETTABLE 1 1 -150    <1227>   R1 = R1["Character"]                            -- It's Const#150
	  +16F3: 47 80 E5 00   line#315  GETTABLE 1 1 -151    <1228>   R1 = R1["HumanoidRootPart"]                     -- It's Const#151
	  +16F7: 47 C0 E4 00   line#315  GETTABLE 1 1 -148    <1229>   R1 = R1["Position"]                             -- It's Const#148
	  +16FB: 0E 40 00 00   line#315  SUB 0 0 1            <1230>   R0 = R0 - R1
	  +16FF: 07 C0 65 00   line#315  GETTABLE 0 0 -152    <1231>   R0 = R0["Magnitude"]                            -- It's Const#152
	  +1703: 20 00 00 CC   line#315  LT 0 -153 0          <1232>   if R0 > 10000 then GOTO <1234>                  -- It's Const#153
	  +1707: 1E 40 2C 81   line#315  JMP 0 1202           <1233>   GOTO <2436>
	  +170B: 06 00 65 00   line#316  GETTABUP 0 0 -149    <1234>   R0 = Upv#1@_ENV["game"]                         -- It's Const#149
	  +170F: 0C 40 66 00   line#316  SELF 0 0 -154        <1235>   R1 = R0;  R0 = R0["GetService"]                 -- It's Const#154   -- prepare for R0:GetService()
	  +1713: 81 80 26 00   line#316  LOADK 2 -155         <1236>   R2 = "ReplicatedStorage"                        -- It's Const#155
	  +1717: 24 80 80 01   line#316  CALL 0 3 2           <1237>   R0 = R0(R1, R2)
	  +171B: 07 C0 66 00   line#316  GETTABLE 0 0 -156    <1238>   R0 = R0["Remotes"]                              -- It's Const#156
	  +171F: 07 00 67 00   line#316  GETTABLE 0 0 -157    <1239>   R0 = R0["CommF_"]                               -- It's Const#157
	  +1723: 0C 40 67 00   line#316  SELF 0 0 -158        <1240>   R1 = R0;  R0 = R0["InvokeServer"]               -- It's Const#158   -- prepare for R0:InvokeServer()
	  +1727: 81 80 27 00   line#316  LOADK 2 -159         <1241>   R2 = "requestEntrance"                          -- It's Const#159
	  +172B: C6 C0 67 00   line#316  GETTABUP 3 0 -160    <1242>   R3 = Upv#1@_ENV["Vector3"]                      -- It's Const#160
	  +172F: C7 40 CE 01   line#316  GETTABLE 3 3 -58     <1243>   R3 = R3["new"]                                  -- It's Const#58
	  +1733: 01 41 55 00   line#316  LOADK 4 -342         <1244>   R4 = 923.21252441406                            -- It's Const#342
	  +1737: 41 81 55 00   line#316  LOADK 5 -343         <1245>   R5 = 126.9760055542                             -- It's Const#343
	  +173B: 81 C1 55 00   line#316  LOADK 6 -344         <1246>   R6 = 32852.83203125                             -- It's Const#344
	  +173F: E4 00 00 02   line#316  CALL 3 4 0           <1247>   R3,.. = R3(R4, R5, R6)
	  +1743: 24 40 00 00   line#316  CALL 0 0 1           <1248>   R0(R1,..)
	  +1747: 1E 40 28 81   line#317  JMP 0 1186           <1249>   GOTO <2436>
	  +174B: 06 00 40 00   line#318  GETTABUP 0 0 -1      <1250>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +174F: 41 00 57 00   line#318  LOADK 1 -349         <1251>   R1 = 1300                                       -- It's Const#349
	  +1753: 5F 40 00 00   line#318  EQ 1 0 1             <1252>   if R0 ~= R1 then GOTO <1254>
	  +1757: 1E C0 00 80   line#318  JMP 0 4              <1253>   GOTO <1258>
	  +175B: 06 00 40 00   line#318  GETTABUP 0 0 -1      <1254>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +175F: 41 40 57 00   line#318  LOADK 1 -350         <1255>   R1 = 1324                                       -- It's Const#350
	  +1763: 21 40 00 00   line#318  LE 0 0 1             <1256>   if R0 <= R1 then GOTO <1258>
	  +1767: 1E 40 0B 80   line#318  JMP 0 46             <1257>   GOTO <1304>
	  +176B: 01 80 57 00   line#319  LOADK 0 -351         <1258>   R0 = "Ship Steward [Lv. 1300]"                  -- It's Const#351
	  +176F: 08 00 00 85   line#319  SETTABUP 0 -11 0     <1259>   Upv#1@_ENV["Mon"] = R0                          -- It's Const#11
	  +1773: 08 00 42 86   line#320  SETTABUP 0 -13 -9    <1260>   Upv#1@_ENV["LQuest"] = 1                        -- It's Const#13, Const#9
	  +1777: 01 C0 57 00   line#321  LOADK 0 -352         <1261>   R0 = "ShipQuest2"                               -- It's Const#352
	  +177B: 08 00 80 86   line#321  SETTABUP 0 -14 0     <1262>   Upv#1@_ENV["NQuest"] = R0                       -- It's Const#14
	  +177F: 01 00 58 00   line#322  LOADK 0 -353         <1263>   R0 = "Ship Steward"                             -- It's Const#353
	  +1783: 08 00 80 87   line#322  SETTABUP 0 -16 0     <1264>   Upv#1@_ENV["NameMon"] = R0                      -- It's Const#16
	  +1787: 06 00 4E 00   line#323  GETTABUP 0 0 -57     <1265>   R0 = Upv#1@_ENV["CFrame"]                       -- It's Const#57
	  +178B: 07 40 4E 00   line#323  GETTABLE 0 0 -58     <1266>   R0 = R0["new"]                                  -- It's Const#58
	  +178F: 41 40 58 00   line#323  LOADK 1 -354         <1267>   R1 = 968.80957                                  -- It's Const#354
	  +1793: 81 C0 54 00   line#323  LOADK 2 -340         <1268>   R2 = 125.092171                                 -- It's Const#340
	  +1797: C1 80 58 00   line#323  LOADK 3 -355         <1269>   R3 = 33244.125                                  -- It's Const#355
	  +179B: 24 80 00 02   line#323  CALL 0 4 2           <1270>   R0 = R0(R1, R2, R3)
	  +179F: 08 00 80 88   line#323  SETTABUP 0 -18 0     <1271>   Upv#1@_ENV["CFrameQuest"] = R0                  -- It's Const#18
	  +17A3: 06 40 64 00   line#324  GETTABUP 0 0 -146    <1272>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#146
	  +17A7: 07 80 64 00   line#324  GETTABLE 0 0 -147    <1273>   R0 = R0["AutoFarm"]                             -- It's Const#147
	  +17AB: 22 00 00 00   line#324  TEST 0 0             <1274>   if R0 then GOTO <1276>
	  +17AF: 1E C0 21 81   line#324  JMP 0 1160           <1275>   GOTO <2436>
	  +17B3: 06 40 44 00   line#324  GETTABUP 0 0 -18     <1276>   R0 = Upv#1@_ENV["CFrameQuest"]                  -- It's Const#18
	  +17B7: 07 C0 64 00   line#324  GETTABLE 0 0 -148    <1277>   R0 = R0["Position"]                             -- It's Const#148
	  +17BB: 46 00 65 00   line#324  GETTABUP 1 0 -149    <1278>   R1 = Upv#1@_ENV["game"]                         -- It's Const#149
	  +17BF: 47 C0 C0 00   line#324  GETTABLE 1 1 -4      <1279>   R1 = R1["Players"]                              -- It's Const#4
	  +17C3: 47 00 C1 00   line#324  GETTABLE 1 1 -5      <1280>   R1 = R1["LocalPlayer"]                          -- It's Const#5
	  +17C7: 47 40 E5 00   line#324  GETTABLE 1 1 -150    <1281>   R1 = R1["Character"]                            -- It's Const#150
	  +17CB: 47 80 E5 00   line#324  GETTABLE 1 1 -151    <1282>   R1 = R1["HumanoidRootPart"]                     -- It's Const#151
	  +17CF: 47 C0 E4 00   line#324  GETTABLE 1 1 -148    <1283>   R1 = R1["Position"]                             -- It's Const#148
	  +17D3: 0E 40 00 00   line#324  SUB 0 0 1            <1284>   R0 = R0 - R1
	  +17D7: 07 C0 65 00   line#324  GETTABLE 0 0 -152    <1285>   R0 = R0["Magnitude"]                            -- It's Const#152
	  +17DB: 20 00 00 CC   line#324  LT 0 -153 0          <1286>   if R0 > 10000 then GOTO <1288>                  -- It's Const#153
	  +17DF: 1E C0 1E 81   line#324  JMP 0 1148           <1287>   GOTO <2436>
	  +17E3: 06 00 65 00   line#325  GETTABUP 0 0 -149    <1288>   R0 = Upv#1@_ENV["game"]                         -- It's Const#149
	  +17E7: 0C 40 66 00   line#325  SELF 0 0 -154        <1289>   R1 = R0;  R0 = R0["GetService"]                 -- It's Const#154   -- prepare for R0:GetService()
	  +17EB: 81 80 26 00   line#325  LOADK 2 -155         <1290>   R2 = "ReplicatedStorage"                        -- It's Const#155
	  +17EF: 24 80 80 01   line#325  CALL 0 3 2           <1291>   R0 = R0(R1, R2)
	  +17F3: 07 C0 66 00   line#325  GETTABLE 0 0 -156    <1292>   R0 = R0["Remotes"]                              -- It's Const#156
	  +17F7: 07 00 67 00   line#325  GETTABLE 0 0 -157    <1293>   R0 = R0["CommF_"]                               -- It's Const#157
	  +17FB: 0C 40 67 00   line#325  SELF 0 0 -158        <1294>   R1 = R0;  R0 = R0["InvokeServer"]               -- It's Const#158   -- prepare for R0:InvokeServer()
	  +17FF: 81 80 27 00   line#325  LOADK 2 -159         <1295>   R2 = "requestEntrance"                          -- It's Const#159
	  +1803: C6 C0 67 00   line#325  GETTABUP 3 0 -160    <1296>   R3 = Upv#1@_ENV["Vector3"]                      -- It's Const#160
	  +1807: C7 40 CE 01   line#325  GETTABLE 3 3 -58     <1297>   R3 = R3["new"]                                  -- It's Const#58
	  +180B: 01 41 55 00   line#325  LOADK 4 -342         <1298>   R4 = 923.21252441406                            -- It's Const#342
	  +180F: 41 81 55 00   line#325  LOADK 5 -343         <1299>   R5 = 126.9760055542                             -- It's Const#343
	  +1813: 81 C1 55 00   line#325  LOADK 6 -344         <1300>   R6 = 32852.83203125                             -- It's Const#344
	  +1817: E4 00 00 02   line#325  CALL 3 4 0           <1301>   R3,.. = R3(R4, R5, R6)
	  +181B: 24 40 00 00   line#325  CALL 0 0 1           <1302>   R0(R1,..)
	  +181F: 1E C0 1A 81   line#326  JMP 0 1132           <1303>   GOTO <2436>
	  +1823: 06 00 40 00   line#327  GETTABUP 0 0 -1      <1304>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +1827: 41 C0 58 00   line#327  LOADK 1 -356         <1305>   R1 = 1325                                       -- It's Const#356
	  +182B: 5F 40 00 00   line#327  EQ 1 0 1             <1306>   if R0 ~= R1 then GOTO <1308>
	  +182F: 1E C0 00 80   line#327  JMP 0 4              <1307>   GOTO <1312>
	  +1833: 06 00 40 00   line#327  GETTABUP 0 0 -1      <1308>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +1837: 41 00 59 00   line#327  LOADK 1 -357         <1309>   R1 = 1349                                       -- It's Const#357
	  +183B: 21 40 00 00   line#327  LE 0 0 1             <1310>   if R0 <= R1 then GOTO <1312>
	  +183F: 1E 40 0B 80   line#327  JMP 0 46             <1311>   GOTO <1358>
	  +1843: 01 40 59 00   line#328  LOADK 0 -358         <1312>   R0 = "Ship Officer [Lv. 1325]"                  -- It's Const#358
	  +1847: 08 00 00 85   line#328  SETTABUP 0 -11 0     <1313>   Upv#1@_ENV["Mon"] = R0                          -- It's Const#11
	  +184B: 08 40 4D 86   line#329  SETTABUP 0 -13 -54   <1314>   Upv#1@_ENV["LQuest"] = 2                        -- It's Const#13, Const#54
	  +184F: 01 C0 57 00   line#330  LOADK 0 -352         <1315>   R0 = "ShipQuest2"                               -- It's Const#352
	  +1853: 08 00 80 86   line#330  SETTABUP 0 -14 0     <1316>   Upv#1@_ENV["NQuest"] = R0                       -- It's Const#14
	  +1857: 01 80 59 00   line#331  LOADK 0 -359         <1317>   R0 = "Ship Officer"                             -- It's Const#359
	  +185B: 08 00 80 87   line#331  SETTABUP 0 -16 0     <1318>   Upv#1@_ENV["NameMon"] = R0                      -- It's Const#16
	  +185F: 06 00 4E 00   line#332  GETTABUP 0 0 -57     <1319>   R0 = Upv#1@_ENV["CFrame"]                       -- It's Const#57
	  +1863: 07 40 4E 00   line#332  GETTABLE 0 0 -58     <1320>   R0 = R0["new"]                                  -- It's Const#58
	  +1867: 41 40 58 00   line#332  LOADK 1 -354         <1321>   R1 = 968.80957                                  -- It's Const#354
	  +186B: 81 C0 54 00   line#332  LOADK 2 -340         <1322>   R2 = 125.092171                                 -- It's Const#340
	  +186F: C1 80 58 00   line#332  LOADK 3 -355         <1323>   R3 = 33244.125                                  -- It's Const#355
	  +1873: 24 80 00 02   line#332  CALL 0 4 2           <1324>   R0 = R0(R1, R2, R3)
	  +1877: 08 00 80 88   line#332  SETTABUP 0 -18 0     <1325>   Upv#1@_ENV["CFrameQuest"] = R0                  -- It's Const#18
	  +187B: 06 40 64 00   line#333  GETTABUP 0 0 -146    <1326>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#146
	  +187F: 07 80 64 00   line#333  GETTABLE 0 0 -147    <1327>   R0 = R0["AutoFarm"]                             -- It's Const#147
	  +1883: 22 00 00 00   line#333  TEST 0 0             <1328>   if R0 then GOTO <1330>
	  +1887: 1E 40 14 81   line#333  JMP 0 1106           <1329>   GOTO <2436>
	  +188B: 06 40 44 00   line#333  GETTABUP 0 0 -18     <1330>   R0 = Upv#1@_ENV["CFrameQuest"]                  -- It's Const#18
	  +188F: 07 C0 64 00   line#333  GETTABLE 0 0 -148    <1331>   R0 = R0["Position"]                             -- It's Const#148
	  +1893: 46 00 65 00   line#333  GETTABUP 1 0 -149    <1332>   R1 = Upv#1@_ENV["game"]                         -- It's Const#149
	  +1897: 47 C0 C0 00   line#333  GETTABLE 1 1 -4      <1333>   R1 = R1["Players"]                              -- It's Const#4
	  +189B: 47 00 C1 00   line#333  GETTABLE 1 1 -5      <1334>   R1 = R1["LocalPlayer"]                          -- It's Const#5
	  +189F: 47 40 E5 00   line#333  GETTABLE 1 1 -150    <1335>   R1 = R1["Character"]                            -- It's Const#150
	  +18A3: 47 80 E5 00   line#333  GETTABLE 1 1 -151    <1336>   R1 = R1["HumanoidRootPart"]                     -- It's Const#151
	  +18A7: 47 C0 E4 00   line#333  GETTABLE 1 1 -148    <1337>   R1 = R1["Position"]                             -- It's Const#148
	  +18AB: 0E 40 00 00   line#333  SUB 0 0 1            <1338>   R0 = R0 - R1
	  +18AF: 07 C0 65 00   line#333  GETTABLE 0 0 -152    <1339>   R0 = R0["Magnitude"]                            -- It's Const#152
	  +18B3: 20 00 00 CC   line#333  LT 0 -153 0          <1340>   if R0 > 10000 then GOTO <1342>                  -- It's Const#153
	  +18B7: 1E 40 11 81   line#333  JMP 0 1094           <1341>   GOTO <2436>
	  +18BB: 06 00 65 00   line#334  GETTABUP 0 0 -149    <1342>   R0 = Upv#1@_ENV["game"]                         -- It's Const#149
	  +18BF: 0C 40 66 00   line#334  SELF 0 0 -154        <1343>   R1 = R0;  R0 = R0["GetService"]                 -- It's Const#154   -- prepare for R0:GetService()
	  +18C3: 81 80 26 00   line#334  LOADK 2 -155         <1344>   R2 = "ReplicatedStorage"                        -- It's Const#155
	  +18C7: 24 80 80 01   line#334  CALL 0 3 2           <1345>   R0 = R0(R1, R2)
	  +18CB: 07 C0 66 00   line#334  GETTABLE 0 0 -156    <1346>   R0 = R0["Remotes"]                              -- It's Const#156
	  +18CF: 07 00 67 00   line#334  GETTABLE 0 0 -157    <1347>   R0 = R0["CommF_"]                               -- It's Const#157
	  +18D3: 0C 40 67 00   line#334  SELF 0 0 -158        <1348>   R1 = R0;  R0 = R0["InvokeServer"]               -- It's Const#158   -- prepare for R0:InvokeServer()
	  +18D7: 81 80 27 00   line#334  LOADK 2 -159         <1349>   R2 = "requestEntrance"                          -- It's Const#159
	  +18DB: C6 C0 67 00   line#334  GETTABUP 3 0 -160    <1350>   R3 = Upv#1@_ENV["Vector3"]                      -- It's Const#160
	  +18DF: C7 40 CE 01   line#334  GETTABLE 3 3 -58     <1351>   R3 = R3["new"]                                  -- It's Const#58
	  +18E3: 01 41 55 00   line#334  LOADK 4 -342         <1352>   R4 = 923.21252441406                            -- It's Const#342
	  +18E7: 41 81 55 00   line#334  LOADK 5 -343         <1353>   R5 = 126.9760055542                             -- It's Const#343
	  +18EB: 81 C1 55 00   line#334  LOADK 6 -344         <1354>   R6 = 32852.83203125                             -- It's Const#344
	  +18EF: E4 00 00 02   line#334  CALL 3 4 0           <1355>   R3,.. = R3(R4, R5, R6)
	  +18F3: 24 40 00 00   line#334  CALL 0 0 1           <1356>   R0(R1,..)
	  +18F7: 1E 40 0D 81   line#335  JMP 0 1078           <1357>   GOTO <2436>
	  +18FB: 06 00 40 00   line#336  GETTABUP 0 0 -1      <1358>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +18FF: 41 C0 59 00   line#336  LOADK 1 -360         <1359>   R1 = 1350                                       -- It's Const#360
	  +1903: 5F 40 00 00   line#336  EQ 1 0 1             <1360>   if R0 ~= R1 then GOTO <1362>
	  +1907: 1E C0 00 80   line#336  JMP 0 4              <1361>   GOTO <1366>
	  +190B: 06 00 40 00   line#336  GETTABUP 0 0 -1      <1362>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +190F: 41 00 5A 00   line#336  LOADK 1 -361         <1363>   R1 = 1374                                       -- It's Const#361
	  +1913: 21 40 00 00   line#336  LE 0 0 1             <1364>   if R0 <= R1 then GOTO <1366>
	  +1917: 1E 80 0D 80   line#336  JMP 0 55             <1365>   GOTO <1421>
	  +191B: 01 40 5A 00   line#337  LOADK 0 -362         <1366>   R0 = "Arctic Warrior [Lv. 1350]"                -- It's Const#362
	  +191F: 08 00 00 85   line#337  SETTABUP 0 -11 0     <1367>   Upv#1@_ENV["Mon"] = R0                          -- It's Const#11
	  +1923: 08 00 42 86   line#338  SETTABUP 0 -13 -9    <1368>   Upv#1@_ENV["LQuest"] = 1                        -- It's Const#13, Const#9
	  +1927: 01 80 5A 00   line#339  LOADK 0 -363         <1369>   R0 = "FrostQuest"                               -- It's Const#363
	  +192B: 08 00 80 86   line#339  SETTABUP 0 -14 0     <1370>   Upv#1@_ENV["NQuest"] = R0                       -- It's Const#14
	  +192F: 01 C0 5A 00   line#340  LOADK 0 -364         <1371>   R0 = "Arctic Warrior"                           -- It's Const#364
	  +1933: 08 00 80 87   line#340  SETTABUP 0 -16 0     <1372>   Upv#1@_ENV["NameMon"] = R0                      -- It's Const#16
	  +1937: 06 00 4E 00   line#341  GETTABUP 0 0 -57     <1373>   R0 = Upv#1@_ENV["CFrame"]                       -- It's Const#57
	  +193B: 07 40 4E 00   line#341  GETTABLE 0 0 -58     <1374>   R0 = R0["new"]                                  -- It's Const#58
	  +193F: 41 00 5B 00   line#341  LOADK 1 -365         <1375>   R1 = 5667.6582                                  -- It's Const#365
	  +1943: 81 40 5B 00   line#341  LOADK 2 -366         <1376>   R2 = 26.7997818                                 -- It's Const#366
	  +1947: C1 80 5B 00   line#341  LOADK 3 -367         <1377>   R3 = (-6486.08984)                              -- It's Const#367
	  +194B: 01 C1 5B 00   line#341  LOADK 4 -368         <1378>   R4 = (-0.933587909)                             -- It's Const#368
	  +194F: 41 81 0F 00   line#341  LOADK 5 -63          <1379>   R5 = 0                                          -- It's Const#63
	  +1953: 81 01 5C 00   line#341  LOADK 6 -369         <1380>   R6 = (-0.358349502)                             -- It's Const#369
	  +1957: C1 81 0F 00   line#341  LOADK 7 -63          <1381>   R7 = 0                                          -- It's Const#63
	  +195B: 01 02 02 00   line#341  LOADK 8 -9           <1382>   R8 = 1                                          -- It's Const#9
	  +195F: 41 82 0F 00   line#341  LOADK 9 -63          <1383>   R9 = 0                                          -- It's Const#63
	  +1963: 81 42 5C 00   line#341  LOADK 10 -370        <1384>   R10 = 0.358349502                               -- It's Const#370
	  +1967: C1 82 0F 00   line#341  LOADK 11 -63         <1385>   R11 = 0                                         -- It's Const#63
	  +196B: 01 C3 5B 00   line#341  LOADK 12 -368        <1386>   R12 = (-0.933587909)                            -- It's Const#368
	  +196F: 24 80 80 06   line#341  CALL 0 13 2          <1387>   R0 = R0(R1,..,R12)
	  +1973: 08 00 80 88   line#341  SETTABUP 0 -18 0     <1388>   Upv#1@_ENV["CFrameQuest"] = R0                  -- It's Const#18
	  +1977: 06 40 64 00   line#342  GETTABUP 0 0 -146    <1389>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#146
	  +197B: 07 80 64 00   line#342  GETTABLE 0 0 -147    <1390>   R0 = R0["AutoFarm"]                             -- It's Const#147
	  +197F: 22 00 00 00   line#342  TEST 0 0             <1391>   if R0 then GOTO <1393>
	  +1983: 1E 80 04 81   line#342  JMP 0 1043           <1392>   GOTO <2436>
	  +1987: 06 40 44 00   line#342  GETTABUP 0 0 -18     <1393>   R0 = Upv#1@_ENV["CFrameQuest"]                  -- It's Const#18
	  +198B: 07 C0 64 00   line#342  GETTABLE 0 0 -148    <1394>   R0 = R0["Position"]                             -- It's Const#148
	  +198F: 46 00 65 00   line#342  GETTABUP 1 0 -149    <1395>   R1 = Upv#1@_ENV["game"]                         -- It's Const#149
	  +1993: 47 C0 C0 00   line#342  GETTABLE 1 1 -4      <1396>   R1 = R1["Players"]                              -- It's Const#4
	  +1997: 47 00 C1 00   line#342  GETTABLE 1 1 -5      <1397>   R1 = R1["LocalPlayer"]                          -- It's Const#5
	  +199B: 47 40 E5 00   line#342  GETTABLE 1 1 -150    <1398>   R1 = R1["Character"]                            -- It's Const#150
	  +199F: 47 80 E5 00   line#342  GETTABLE 1 1 -151    <1399>   R1 = R1["HumanoidRootPart"]                     -- It's Const#151
	  +19A3: 47 C0 E4 00   line#342  GETTABLE 1 1 -148    <1400>   R1 = R1["Position"]                             -- It's Const#148
	  +19A7: 0E 40 00 00   line#342  SUB 0 0 1            <1401>   R0 = R0 - R1
	  +19AB: 07 C0 65 00   line#342  GETTABLE 0 0 -152    <1402>   R0 = R0["Magnitude"]                            -- It's Const#152
	  +19AF: 20 00 00 CC   line#342  LT 0 -153 0          <1403>   if R0 > 10000 then GOTO <1405>                  -- It's Const#153
	  +19B3: 1E 80 01 81   line#342  JMP 0 1031           <1404>   GOTO <2436>
	  +19B7: 06 00 65 00   line#343  GETTABUP 0 0 -149    <1405>   R0 = Upv#1@_ENV["game"]                         -- It's Const#149
	  +19BB: 0C 40 66 00   line#343  SELF 0 0 -154        <1406>   R1 = R0;  R0 = R0["GetService"]                 -- It's Const#154   -- prepare for R0:GetService()
	  +19BF: 81 80 26 00   line#343  LOADK 2 -155         <1407>   R2 = "ReplicatedStorage"                        -- It's Const#155
	  +19C3: 24 80 80 01   line#343  CALL 0 3 2           <1408>   R0 = R0(R1, R2)
	  +19C7: 07 C0 66 00   line#343  GETTABLE 0 0 -156    <1409>   R0 = R0["Remotes"]                              -- It's Const#156
	  +19CB: 07 00 67 00   line#343  GETTABLE 0 0 -157    <1410>   R0 = R0["CommF_"]                               -- It's Const#157
	  +19CF: 0C 40 67 00   line#343  SELF 0 0 -158        <1411>   R1 = R0;  R0 = R0["InvokeServer"]               -- It's Const#158   -- prepare for R0:InvokeServer()
	  +19D3: 81 80 27 00   line#343  LOADK 2 -159         <1412>   R2 = "requestEntrance"                          -- It's Const#159
	  +19D7: C6 C0 67 00   line#343  GETTABUP 3 0 -160    <1413>   R3 = Upv#1@_ENV["Vector3"]                      -- It's Const#160
	  +19DB: C7 40 CE 01   line#343  GETTABLE 3 3 -58     <1414>   R3 = R3["new"]                                  -- It's Const#58
	  +19DF: 01 81 5C 00   line#343  LOADK 4 -371         <1415>   R4 = (-6508.5581054688)                         -- It's Const#371
	  +19E3: 41 C1 5C 00   line#343  LOADK 5 -372         <1416>   R5 = 5000.034996032715                          -- It's Const#372
	  +19E7: 81 01 5D 00   line#343  LOADK 6 -373         <1417>   R6 = (-132.83953857422)                         -- It's Const#373
	  +19EB: E4 00 00 02   line#343  CALL 3 4 0           <1418>   R3,.. = R3(R4, R5, R6)
	  +19EF: 24 40 00 00   line#343  CALL 0 0 1           <1419>   R0(R1,..)
	  +19F3: 1E 80 FD 80   line#344  JMP 0 1015           <1420>   GOTO <2436>
	  +19F7: 06 00 40 00   line#345  GETTABUP 0 0 -1      <1421>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +19FB: 41 40 5D 00   line#345  LOADK 1 -374         <1422>   R1 = 1375                                       -- It's Const#374
	  +19FF: 5F 40 00 00   line#345  EQ 1 0 1             <1423>   if R0 ~= R1 then GOTO <1425>
	  +1A03: 1E C0 00 80   line#345  JMP 0 4              <1424>   GOTO <1429>
	  +1A07: 06 00 40 00   line#345  GETTABUP 0 0 -1      <1425>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +1A0B: 41 80 5D 00   line#345  LOADK 1 -375         <1426>   R1 = 1424                                       -- It's Const#375
	  +1A0F: 21 40 00 00   line#345  LE 0 0 1             <1427>   if R0 <= R1 then GOTO <1429>
	  +1A13: 1E C0 05 80   line#345  JMP 0 24             <1428>   GOTO <1453>
	  +1A17: 01 C0 5D 00   line#346  LOADK 0 -376         <1429>   R0 = "Snow Lurker [Lv. 1375]"                   -- It's Const#376
	  +1A1B: 08 00 00 85   line#346  SETTABUP 0 -11 0     <1430>   Upv#1@_ENV["Mon"] = R0                          -- It's Const#11
	  +1A1F: 08 40 4D 86   line#347  SETTABUP 0 -13 -54   <1431>   Upv#1@_ENV["LQuest"] = 2                        -- It's Const#13, Const#54
	  +1A23: 01 80 5A 00   line#348  LOADK 0 -363         <1432>   R0 = "FrostQuest"                               -- It's Const#363
	  +1A27: 08 00 80 86   line#348  SETTABUP 0 -14 0     <1433>   Upv#1@_ENV["NQuest"] = R0                       -- It's Const#14
	  +1A2B: 01 00 5E 00   line#349  LOADK 0 -377         <1434>   R0 = "Snow Lurker"                              -- It's Const#377
	  +1A2F: 08 00 80 87   line#349  SETTABUP 0 -16 0     <1435>   Upv#1@_ENV["NameMon"] = R0                      -- It's Const#16
	  +1A33: 06 00 4E 00   line#350  GETTABUP 0 0 -57     <1436>   R0 = Upv#1@_ENV["CFrame"]                       -- It's Const#57
	  +1A37: 07 40 4E 00   line#350  GETTABLE 0 0 -58     <1437>   R0 = R0["new"]                                  -- It's Const#58
	  +1A3B: 41 00 5B 00   line#350  LOADK 1 -365         <1438>   R1 = 5667.6582                                  -- It's Const#365
	  +1A3F: 81 40 5B 00   line#350  LOADK 2 -366         <1439>   R2 = 26.7997818                                 -- It's Const#366
	  +1A43: C1 80 5B 00   line#350  LOADK 3 -367         <1440>   R3 = (-6486.08984)                              -- It's Const#367
	  +1A47: 01 C1 5B 00   line#350  LOADK 4 -368         <1441>   R4 = (-0.933587909)                             -- It's Const#368
	  +1A4B: 41 81 0F 00   line#350  LOADK 5 -63          <1442>   R5 = 0                                          -- It's Const#63
	  +1A4F: 81 01 5C 00   line#350  LOADK 6 -369         <1443>   R6 = (-0.358349502)                             -- It's Const#369
	  +1A53: C1 81 0F 00   line#350  LOADK 7 -63          <1444>   R7 = 0                                          -- It's Const#63
	  +1A57: 01 02 02 00   line#350  LOADK 8 -9           <1445>   R8 = 1                                          -- It's Const#9
	  +1A5B: 41 82 0F 00   line#350  LOADK 9 -63          <1446>   R9 = 0                                          -- It's Const#63
	  +1A5F: 81 42 5C 00   line#350  LOADK 10 -370        <1447>   R10 = 0.358349502                               -- It's Const#370
	  +1A63: C1 82 0F 00   line#350  LOADK 11 -63         <1448>   R11 = 0                                         -- It's Const#63
	  +1A67: 01 C3 5B 00   line#350  LOADK 12 -368        <1449>   R12 = (-0.933587909)                            -- It's Const#368
	  +1A6B: 24 80 80 06   line#350  CALL 0 13 2          <1450>   R0 = R0(R1,..,R12)
	  +1A6F: 08 00 80 88   line#350  SETTABUP 0 -18 0     <1451>   Upv#1@_ENV["CFrameQuest"] = R0                  -- It's Const#18
	  +1A73: 1E 80 F5 80   line#350  JMP 0 983            <1452>   GOTO <2436>
	  +1A77: 06 00 40 00   line#351  GETTABUP 0 0 -1      <1453>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +1A7B: 41 40 5E 00   line#351  LOADK 1 -378         <1454>   R1 = 1425                                       -- It's Const#378
	  +1A7F: 5F 40 00 00   line#351  EQ 1 0 1             <1455>   if R0 ~= R1 then GOTO <1457>
	  +1A83: 1E C0 00 80   line#351  JMP 0 4              <1456>   GOTO <1461>
	  +1A87: 06 00 40 00   line#351  GETTABUP 0 0 -1      <1457>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +1A8B: 41 80 5E 00   line#351  LOADK 1 -379         <1458>   R1 = 1449                                       -- It's Const#379
	  +1A8F: 21 40 00 00   line#351  LE 0 0 1             <1459>   if R0 <= R1 then GOTO <1461>
	  +1A93: 1E C0 05 80   line#351  JMP 0 24             <1460>   GOTO <1485>
	  +1A97: 01 C0 5E 00   line#352  LOADK 0 -380         <1461>   R0 = "Sea Soldier [Lv. 1425]"                   -- It's Const#380
	  +1A9B: 08 00 00 85   line#352  SETTABUP 0 -11 0     <1462>   Upv#1@_ENV["Mon"] = R0                          -- It's Const#11
	  +1A9F: 08 00 42 86   line#353  SETTABUP 0 -13 -9    <1463>   Upv#1@_ENV["LQuest"] = 1                        -- It's Const#13, Const#9
	  +1AA3: 01 00 5F 00   line#354  LOADK 0 -381         <1464>   R0 = "ForgottenQuest"                           -- It's Const#381
	  +1AA7: 08 00 80 86   line#354  SETTABUP 0 -14 0     <1465>   Upv#1@_ENV["NQuest"] = R0                       -- It's Const#14
	  +1AAB: 01 40 5F 00   line#355  LOADK 0 -382         <1466>   R0 = "Sea Soldier"                              -- It's Const#382
	  +1AAF: 08 00 80 87   line#355  SETTABUP 0 -16 0     <1467>   Upv#1@_ENV["NameMon"] = R0                      -- It's Const#16
	  +1AB3: 06 00 4E 00   line#356  GETTABUP 0 0 -57     <1468>   R0 = Upv#1@_ENV["CFrame"]                       -- It's Const#57
	  +1AB7: 07 40 4E 00   line#356  GETTABLE 0 0 -58     <1469>   R0 = R0["new"]                                  -- It's Const#58
	  +1ABB: 41 80 5F 00   line#356  LOADK 1 -383         <1470>   R1 = (-3054.44458)                              -- It's Const#383
	  +1ABF: 81 C0 5F 00   line#356  LOADK 2 -384         <1471>   R2 = 235.544281                                 -- It's Const#384
	  +1AC3: C1 00 60 00   line#356  LOADK 3 -385         <1472>   R3 = (-10142.8193)                              -- It's Const#385
	  +1AC7: 01 41 60 00   line#356  LOADK 4 -386         <1473>   R4 = 0.990270376                                -- It's Const#386
	  +1ACB: 41 81 0F 00   line#356  LOADK 5 -63          <1474>   R5 = 0                                          -- It's Const#63
	  +1ACF: 81 81 60 00   line#356  LOADK 6 -387         <1475>   R6 = (-0.13915664)                              -- It's Const#387
	  +1AD3: C1 81 0F 00   line#356  LOADK 7 -63          <1476>   R7 = 0                                          -- It's Const#63
	  +1AD7: 01 02 02 00   line#356  LOADK 8 -9           <1477>   R8 = 1                                          -- It's Const#9
	  +1ADB: 41 82 0F 00   line#356  LOADK 9 -63          <1478>   R9 = 0                                          -- It's Const#63
	  +1ADF: 81 C2 60 00   line#356  LOADK 10 -388        <1479>   R10 = 0.13915664                                -- It's Const#388
	  +1AE3: C1 82 0F 00   line#356  LOADK 11 -63         <1480>   R11 = 0                                         -- It's Const#63
	  +1AE7: 01 43 60 00   line#356  LOADK 12 -386        <1481>   R12 = 0.990270376                               -- It's Const#386
	  +1AEB: 24 80 80 06   line#356  CALL 0 13 2          <1482>   R0 = R0(R1,..,R12)
	  +1AEF: 08 00 80 88   line#356  SETTABUP 0 -18 0     <1483>   Upv#1@_ENV["CFrameQuest"] = R0                  -- It's Const#18
	  +1AF3: 1E 80 ED 80   line#356  JMP 0 951            <1484>   GOTO <2436>
	  +1AF7: 06 00 40 00   line#357  GETTABUP 0 0 -1      <1485>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +1AFB: 41 00 61 00   line#357  LOADK 1 -389         <1486>   R1 = 1450                                       -- It's Const#389
	  +1AFF: 21 00 80 00   line#357  LE 0 1 0             <1487>   if R1 <= R0 then GOTO <1489>
	  +1B03: 1E 80 EC 80   line#357  JMP 0 947            <1488>   GOTO <2436>
	  +1B07: 01 40 61 00   line#358  LOADK 0 -390         <1489>   R0 = "Water Fighter [Lv. 1450]"                 -- It's Const#390
	  +1B0B: 08 00 00 85   line#358  SETTABUP 0 -11 0     <1490>   Upv#1@_ENV["Mon"] = R0                          -- It's Const#11
	  +1B0F: 08 40 4D 86   line#359  SETTABUP 0 -13 -54   <1491>   Upv#1@_ENV["LQuest"] = 2                        -- It's Const#13, Const#54
	  +1B13: 01 00 5F 00   line#360  LOADK 0 -381         <1492>   R0 = "ForgottenQuest"                           -- It's Const#381
	  +1B17: 08 00 80 86   line#360  SETTABUP 0 -14 0     <1493>   Upv#1@_ENV["NQuest"] = R0                       -- It's Const#14
	  +1B1B: 01 80 61 00   line#361  LOADK 0 -391         <1494>   R0 = "Water Fighter"                            -- It's Const#391
	  +1B1F: 08 00 80 87   line#361  SETTABUP 0 -16 0     <1495>   Upv#1@_ENV["NameMon"] = R0                      -- It's Const#16
	  +1B23: 06 00 4E 00   line#362  GETTABUP 0 0 -57     <1496>   R0 = Upv#1@_ENV["CFrame"]                       -- It's Const#57
	  +1B27: 07 40 4E 00   line#362  GETTABLE 0 0 -58     <1497>   R0 = R0["new"]                                  -- It's Const#58
	  +1B2B: 41 80 5F 00   line#362  LOADK 1 -383         <1498>   R1 = (-3054.44458)                              -- It's Const#383
	  +1B2F: 81 C0 5F 00   line#362  LOADK 2 -384         <1499>   R2 = 235.544281                                 -- It's Const#384
	  +1B33: C1 00 60 00   line#362  LOADK 3 -385         <1500>   R3 = (-10142.8193)                              -- It's Const#385
	  +1B37: 01 41 60 00   line#362  LOADK 4 -386         <1501>   R4 = 0.990270376                                -- It's Const#386
	  +1B3B: 41 81 0F 00   line#362  LOADK 5 -63          <1502>   R5 = 0                                          -- It's Const#63
	  +1B3F: 81 81 60 00   line#362  LOADK 6 -387         <1503>   R6 = (-0.13915664)                              -- It's Const#387
	  +1B43: C1 81 0F 00   line#362  LOADK 7 -63          <1504>   R7 = 0                                          -- It's Const#63
	  +1B47: 01 02 02 00   line#362  LOADK 8 -9           <1505>   R8 = 1                                          -- It's Const#9
	  +1B4B: 41 82 0F 00   line#362  LOADK 9 -63          <1506>   R9 = 0                                          -- It's Const#63
	  +1B4F: 81 C2 60 00   line#362  LOADK 10 -388        <1507>   R10 = 0.13915664                                -- It's Const#388
	  +1B53: C1 82 0F 00   line#362  LOADK 11 -63         <1508>   R11 = 0                                         -- It's Const#63
	  +1B57: 01 43 60 00   line#362  LOADK 12 -386        <1509>   R12 = 0.990270376                               -- It's Const#386
	  +1B5B: 24 80 80 06   line#362  CALL 0 13 2          <1510>   R0 = R0(R1,..,R12)
	  +1B5F: 08 00 80 88   line#362  SETTABUP 0 -18 0     <1511>   Upv#1@_ENV["CFrameQuest"] = R0                  -- It's Const#18
	  +1B63: 1E 80 E6 80   line#363  JMP 0 923            <1512>   GOTO <2436>
	  +1B67: 01 C0 61 00   line#364  LOADK 0 -392         <1513>   R0 = "W3"                                       -- It's Const#392
	  +1B6B: 06 00 00 00   line#364  GETTABUP 0 0 0       <1514>   R0 = Upv#1@_ENV[R0]
	  +1B6F: 22 00 00 00   line#364  TEST 0 0             <1515>   if R0 then GOTO <1517>
	  +1B73: 1E 80 E5 80   line#364  JMP 0 919            <1516>   GOTO <2436>
	  +1B77: 06 00 40 00   line#365  GETTABUP 0 0 -1      <1517>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +1B7B: 41 00 62 00   line#365  LOADK 1 -393         <1518>   R1 = 1500                                       -- It's Const#393
	  +1B7F: 5F 40 00 00   line#365  EQ 1 0 1             <1519>   if R0 ~= R1 then GOTO <1521>
	  +1B83: 1E C0 00 80   line#365  JMP 0 4              <1520>   GOTO <1525>
	  +1B87: 06 00 40 00   line#365  GETTABUP 0 0 -1      <1521>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +1B8B: 41 40 62 00   line#365  LOADK 1 -394         <1522>   R1 = 1524                                       -- It's Const#394
	  +1B8F: 21 40 00 00   line#365  LE 0 0 1             <1523>   if R0 <= R1 then GOTO <1525>
	  +1B93: 1E C0 05 80   line#365  JMP 0 24             <1524>   GOTO <1549>
	  +1B97: 01 80 62 00   line#366  LOADK 0 -395         <1525>   R0 = "Pirate Millionaire [Lv. 1500]"            -- It's Const#395
	  +1B9B: 08 00 00 85   line#366  SETTABUP 0 -11 0     <1526>   Upv#1@_ENV["Mon"] = R0                          -- It's Const#11
	  +1B9F: 08 00 42 86   line#367  SETTABUP 0 -13 -9    <1527>   Upv#1@_ENV["LQuest"] = 1                        -- It's Const#13, Const#9
	  +1BA3: 01 C0 62 00   line#368  LOADK 0 -396         <1528>   R0 = "PiratePortQuest"                          -- It's Const#396
	  +1BA7: 08 00 80 86   line#368  SETTABUP 0 -14 0     <1529>   Upv#1@_ENV["NQuest"] = R0                       -- It's Const#14
	  +1BAB: 01 00 63 00   line#369  LOADK 0 -397         <1530>   R0 = "Pirate Millionaire"                       -- It's Const#397
	  +1BAF: 08 00 80 87   line#369  SETTABUP 0 -16 0     <1531>   Upv#1@_ENV["NameMon"] = R0                      -- It's Const#16
	  +1BB3: 06 00 4E 00   line#370  GETTABUP 0 0 -57     <1532>   R0 = Upv#1@_ENV["CFrame"]                       -- It's Const#57
	  +1BB7: 07 40 4E 00   line#370  GETTABLE 0 0 -58     <1533>   R0 = R0["new"]                                  -- It's Const#58
	  +1BBB: 41 40 63 00   line#370  LOADK 1 -398         <1534>   R1 = (-290.074677)                              -- It's Const#398
	  +1BBF: 81 80 63 00   line#370  LOADK 2 -399         <1535>   R2 = 42.9034653                                 -- It's Const#399
	  +1BC3: C1 C0 63 00   line#370  LOADK 3 -400         <1536>   R3 = 5581.58984                                 -- It's Const#400
	  +1BC7: 01 01 64 00   line#370  LOADK 4 -401         <1537>   R4 = 0.965929627                                -- It's Const#401
	  +1BCB: 41 81 0F 00   line#370  LOADK 5 -63          <1538>   R5 = 0                                          -- It's Const#63
	  +1BCF: 81 41 64 00   line#370  LOADK 6 -402         <1539>   R6 = (-0.258804798)                             -- It's Const#402
	  +1BD3: C1 81 0F 00   line#370  LOADK 7 -63          <1540>   R7 = 0                                          -- It's Const#63
	  +1BD7: 01 02 02 00   line#370  LOADK 8 -9           <1541>   R8 = 1                                          -- It's Const#9
	  +1BDB: 41 82 0F 00   line#370  LOADK 9 -63          <1542>   R9 = 0                                          -- It's Const#63
	  +1BDF: 81 82 64 00   line#370  LOADK 10 -403        <1543>   R10 = 0.258804798                               -- It's Const#403
	  +1BE3: C1 82 0F 00   line#370  LOADK 11 -63         <1544>   R11 = 0                                         -- It's Const#63
	  +1BE7: 01 03 64 00   line#370  LOADK 12 -401        <1545>   R12 = 0.965929627                               -- It's Const#401
	  +1BEB: 24 80 80 06   line#370  CALL 0 13 2          <1546>   R0 = R0(R1,..,R12)
	  +1BEF: 08 00 80 88   line#370  SETTABUP 0 -18 0     <1547>   Upv#1@_ENV["CFrameQuest"] = R0                  -- It's Const#18
	  +1BF3: 1E 80 DD 80   line#370  JMP 0 887            <1548>   GOTO <2436>
	  +1BF7: 06 00 40 00   line#371  GETTABUP 0 0 -1      <1549>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +1BFB: 41 C0 64 00   line#371  LOADK 1 -404         <1550>   R1 = 1525                                       -- It's Const#404
	  +1BFF: 5F 40 00 00   line#371  EQ 1 0 1             <1551>   if R0 ~= R1 then GOTO <1553>
	  +1C03: 1E C0 00 80   line#371  JMP 0 4              <1552>   GOTO <1557>
	  +1C07: 06 00 40 00   line#371  GETTABUP 0 0 -1      <1553>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +1C0B: 41 00 65 00   line#371  LOADK 1 -405         <1554>   R1 = 1574                                       -- It's Const#405
	  +1C0F: 21 40 00 00   line#371  LE 0 0 1             <1555>   if R0 <= R1 then GOTO <1557>
	  +1C13: 1E C0 05 80   line#371  JMP 0 24             <1556>   GOTO <1581>
	  +1C17: 01 40 65 00   line#372  LOADK 0 -406         <1557>   R0 = "Pistol Billionaire [Lv. 1525]"            -- It's Const#406
	  +1C1B: 08 00 00 85   line#372  SETTABUP 0 -11 0     <1558>   Upv#1@_ENV["Mon"] = R0                          -- It's Const#11
	  +1C1F: 08 40 4D 86   line#373  SETTABUP 0 -13 -54   <1559>   Upv#1@_ENV["LQuest"] = 2                        -- It's Const#13, Const#54
	  +1C23: 01 C0 62 00   line#374  LOADK 0 -396         <1560>   R0 = "PiratePortQuest"                          -- It's Const#396
	  +1C27: 08 00 80 86   line#374  SETTABUP 0 -14 0     <1561>   Upv#1@_ENV["NQuest"] = R0                       -- It's Const#14
	  +1C2B: 01 80 65 00   line#375  LOADK 0 -407         <1562>   R0 = "Pistol Billionaire"                       -- It's Const#407
	  +1C2F: 08 00 80 87   line#375  SETTABUP 0 -16 0     <1563>   Upv#1@_ENV["NameMon"] = R0                      -- It's Const#16
	  +1C33: 06 00 4E 00   line#376  GETTABUP 0 0 -57     <1564>   R0 = Upv#1@_ENV["CFrame"]                       -- It's Const#57
	  +1C37: 07 40 4E 00   line#376  GETTABLE 0 0 -58     <1565>   R0 = R0["new"]                                  -- It's Const#58
	  +1C3B: 41 40 63 00   line#376  LOADK 1 -398         <1566>   R1 = (-290.074677)                              -- It's Const#398
	  +1C3F: 81 80 63 00   line#376  LOADK 2 -399         <1567>   R2 = 42.9034653                                 -- It's Const#399
	  +1C43: C1 C0 63 00   line#376  LOADK 3 -400         <1568>   R3 = 5581.58984                                 -- It's Const#400
	  +1C47: 01 01 64 00   line#376  LOADK 4 -401         <1569>   R4 = 0.965929627                                -- It's Const#401
	  +1C4B: 41 81 0F 00   line#376  LOADK 5 -63          <1570>   R5 = 0                                          -- It's Const#63
	  +1C4F: 81 41 64 00   line#376  LOADK 6 -402         <1571>   R6 = (-0.258804798)                             -- It's Const#402
	  +1C53: C1 81 0F 00   line#376  LOADK 7 -63          <1572>   R7 = 0                                          -- It's Const#63
	  +1C57: 01 02 02 00   line#376  LOADK 8 -9           <1573>   R8 = 1                                          -- It's Const#9
	  +1C5B: 41 82 0F 00   line#376  LOADK 9 -63          <1574>   R9 = 0                                          -- It's Const#63
	  +1C5F: 81 82 64 00   line#376  LOADK 10 -403        <1575>   R10 = 0.258804798                               -- It's Const#403
	  +1C63: C1 82 0F 00   line#376  LOADK 11 -63         <1576>   R11 = 0                                         -- It's Const#63
	  +1C67: 01 03 64 00   line#376  LOADK 12 -401        <1577>   R12 = 0.965929627                               -- It's Const#401
	  +1C6B: 24 80 80 06   line#376  CALL 0 13 2          <1578>   R0 = R0(R1,..,R12)
	  +1C6F: 08 00 80 88   line#376  SETTABUP 0 -18 0     <1579>   Upv#1@_ENV["CFrameQuest"] = R0                  -- It's Const#18
	  +1C73: 1E 80 D5 80   line#376  JMP 0 855            <1580>   GOTO <2436>
	  +1C77: 06 00 40 00   line#377  GETTABUP 0 0 -1      <1581>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +1C7B: 41 C0 65 00   line#377  LOADK 1 -408         <1582>   R1 = 1575                                       -- It's Const#408
	  +1C7F: 5F 40 00 00   line#377  EQ 1 0 1             <1583>   if R0 ~= R1 then GOTO <1585>
	  +1C83: 1E C0 00 80   line#377  JMP 0 4              <1584>   GOTO <1589>
	  +1C87: 06 00 40 00   line#377  GETTABUP 0 0 -1      <1585>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +1C8B: 41 00 66 00   line#377  LOADK 1 -409         <1586>   R1 = 1599                                       -- It's Const#409
	  +1C8F: 21 40 00 00   line#377  LE 0 0 1             <1587>   if R0 <= R1 then GOTO <1589>
	  +1C93: 1E C0 05 80   line#377  JMP 0 24             <1588>   GOTO <1613>
	  +1C97: 01 40 66 00   line#378  LOADK 0 -410         <1589>   R0 = "Dragon Crew Warrior [Lv. 1575]"           -- It's Const#410
	  +1C9B: 08 00 00 85   line#378  SETTABUP 0 -11 0     <1590>   Upv#1@_ENV["Mon"] = R0                          -- It's Const#11
	  +1C9F: 08 00 42 86   line#379  SETTABUP 0 -13 -9    <1591>   Upv#1@_ENV["LQuest"] = 1                        -- It's Const#13, Const#9
	  +1CA3: 01 80 66 00   line#380  LOADK 0 -411         <1592>   R0 = "AmazonQuest"                              -- It's Const#411
	  +1CA7: 08 00 80 86   line#380  SETTABUP 0 -14 0     <1593>   Upv#1@_ENV["NQuest"] = R0                       -- It's Const#14
	  +1CAB: 01 C0 66 00   line#381  LOADK 0 -412         <1594>   R0 = "Dragon Crew Warrior"                      -- It's Const#412
	  +1CAF: 08 00 80 87   line#381  SETTABUP 0 -16 0     <1595>   Upv#1@_ENV["NameMon"] = R0                      -- It's Const#16
	  +1CB3: 06 00 4E 00   line#382  GETTABUP 0 0 -57     <1596>   R0 = Upv#1@_ENV["CFrame"]                       -- It's Const#57
	  +1CB7: 07 40 4E 00   line#382  GETTABLE 0 0 -58     <1597>   R0 = R0["new"]                                  -- It's Const#58
	  +1CBB: 41 00 67 00   line#382  LOADK 1 -413         <1598>   R1 = 5832.83594                                 -- It's Const#413
	  +1CBF: 81 40 67 00   line#382  LOADK 2 -414         <1599>   R2 = 51.6806107                                 -- It's Const#414
	  +1CC3: C1 80 67 00   line#382  LOADK 3 -415         <1600>   R3 = (-1101.51563)                              -- It's Const#415
	  +1CC7: 01 C1 67 00   line#382  LOADK 4 -416         <1601>   R4 = 0.898790359                                -- It's Const#416
	  +1CCB: 41 81 0F 00   line#382  LOADK 5 -63          <1602>   R5 = 0                                          -- It's Const#63
	  +1CCF: 81 01 68 00   line#382  LOADK 6 -417         <1603>   R6 = (-0.438378751)                             -- It's Const#417
	  +1CD3: C1 81 0F 00   line#382  LOADK 7 -63          <1604>   R7 = 0                                          -- It's Const#63
	  +1CD7: 01 02 02 00   line#382  LOADK 8 -9           <1605>   R8 = 1                                          -- It's Const#9
	  +1CDB: 41 82 0F 00   line#382  LOADK 9 -63          <1606>   R9 = 0                                          -- It's Const#63
	  +1CDF: 81 42 68 00   line#382  LOADK 10 -418        <1607>   R10 = 0.438378751                               -- It's Const#418
	  +1CE3: C1 82 0F 00   line#382  LOADK 11 -63         <1608>   R11 = 0                                         -- It's Const#63
	  +1CE7: 01 C3 67 00   line#382  LOADK 12 -416        <1609>   R12 = 0.898790359                               -- It's Const#416
	  +1CEB: 24 80 80 06   line#382  CALL 0 13 2          <1610>   R0 = R0(R1,..,R12)
	  +1CEF: 08 00 80 88   line#382  SETTABUP 0 -18 0     <1611>   Upv#1@_ENV["CFrameQuest"] = R0                  -- It's Const#18
	  +1CF3: 1E 80 CD 80   line#382  JMP 0 823            <1612>   GOTO <2436>
	  +1CF7: 06 00 40 00   line#383  GETTABUP 0 0 -1      <1613>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +1CFB: 41 80 68 00   line#383  LOADK 1 -419         <1614>   R1 = 1600                                       -- It's Const#419
	  +1CFF: 5F 40 00 00   line#383  EQ 1 0 1             <1615>   if R0 ~= R1 then GOTO <1617>
	  +1D03: 1E C0 00 80   line#383  JMP 0 4              <1616>   GOTO <1621>
	  +1D07: 06 00 40 00   line#383  GETTABUP 0 0 -1      <1617>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +1D0B: 41 C0 68 00   line#383  LOADK 1 -420         <1618>   R1 = 1624                                       -- It's Const#420
	  +1D0F: 21 40 00 00   line#383  LE 0 0 1             <1619>   if R0 <= R1 then GOTO <1621>
	  +1D13: 1E 80 03 80   line#383  JMP 0 15             <1620>   GOTO <1636>
	  +1D17: 01 00 69 00   line#384  LOADK 0 -421         <1621>   R0 = "Dragon Crew Archer [Lv. 1600]"            -- It's Const#421
	  +1D1B: 08 00 00 85   line#384  SETTABUP 0 -11 0     <1622>   Upv#1@_ENV["Mon"] = R0                          -- It's Const#11
	  +1D1F: 01 80 66 00   line#385  LOADK 0 -411         <1623>   R0 = "AmazonQuest"                              -- It's Const#411
	  +1D23: 08 00 80 86   line#385  SETTABUP 0 -14 0     <1624>   Upv#1@_ENV["NQuest"] = R0                       -- It's Const#14
	  +1D27: 08 40 4D 86   line#386  SETTABUP 0 -13 -54   <1625>   Upv#1@_ENV["LQuest"] = 2                        -- It's Const#13, Const#54
	  +1D2B: 01 40 69 00   line#387  LOADK 0 -422         <1626>   R0 = "Dragon Crew Archer"                       -- It's Const#422
	  +1D2F: 08 00 80 87   line#387  SETTABUP 0 -16 0     <1627>   Upv#1@_ENV["NameMon"] = R0                      -- It's Const#16
	  +1D33: 06 00 4E 00   line#388  GETTABUP 0 0 -57     <1628>   R0 = Upv#1@_ENV["CFrame"]                       -- It's Const#57
	  +1D37: 07 40 4E 00   line#388  GETTABLE 0 0 -58     <1629>   R0 = R0["new"]                                  -- It's Const#58
	  +1D3B: 41 80 69 00   line#388  LOADK 1 -423         <1630>   R1 = 5833.1147460938                            -- It's Const#423
	  +1D3F: 81 C0 69 00   line#388  LOADK 2 -424         <1631>   R2 = 105687/2048                                -- It's Const#424
	  +1D43: C1 00 6A 00   line#388  LOADK 3 -425         <1632>   R3 = (-1103.0693359375)                         -- It's Const#425
	  +1D47: 24 80 00 02   line#388  CALL 0 4 2           <1633>   R0 = R0(R1, R2, R3)
	  +1D4B: 08 00 80 88   line#388  SETTABUP 0 -18 0     <1634>   Upv#1@_ENV["CFrameQuest"] = R0                  -- It's Const#18
	  +1D4F: 1E C0 C7 80   line#388  JMP 0 800            <1635>   GOTO <2436>
	  +1D53: 06 00 40 00   line#389  GETTABUP 0 0 -1      <1636>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +1D57: 41 40 6A 00   line#389  LOADK 1 -426         <1637>   R1 = 1625                                       -- It's Const#426
	  +1D5B: 5F 40 00 00   line#389  EQ 1 0 1             <1638>   if R0 ~= R1 then GOTO <1640>
	  +1D5F: 1E C0 00 80   line#389  JMP 0 4              <1639>   GOTO <1644>
	  +1D63: 06 00 40 00   line#389  GETTABUP 0 0 -1      <1640>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +1D67: 41 80 6A 00   line#389  LOADK 1 -427         <1641>   R1 = 1649                                       -- It's Const#427
	  +1D6B: 21 40 00 00   line#389  LE 0 0 1             <1642>   if R0 <= R1 then GOTO <1644>
	  +1D6F: 1E 80 03 80   line#389  JMP 0 15             <1643>   GOTO <1659>
	  +1D73: 01 C0 6A 00   line#390  LOADK 0 -428         <1644>   R0 = "Female Islander [Lv. 1625]"               -- It's Const#428
	  +1D77: 08 00 00 85   line#390  SETTABUP 0 -11 0     <1645>   Upv#1@_ENV["Mon"] = R0                          -- It's Const#11
	  +1D7B: 01 00 6B 00   line#391  LOADK 0 -429         <1646>   R0 = "AmazonQuest2"                             -- It's Const#429
	  +1D7F: 08 00 80 86   line#391  SETTABUP 0 -14 0     <1647>   Upv#1@_ENV["NQuest"] = R0                       -- It's Const#14
	  +1D83: 08 00 42 86   line#392  SETTABUP 0 -13 -9    <1648>   Upv#1@_ENV["LQuest"] = 1                        -- It's Const#13, Const#9
	  +1D87: 01 40 6B 00   line#393  LOADK 0 -430         <1649>   R0 = "Female Islander"                          -- It's Const#430
	  +1D8B: 08 00 80 87   line#393  SETTABUP 0 -16 0     <1650>   Upv#1@_ENV["NameMon"] = R0                      -- It's Const#16
	  +1D8F: 06 00 4E 00   line#394  GETTABUP 0 0 -57     <1651>   R0 = Upv#1@_ENV["CFrame"]                       -- It's Const#57
	  +1D93: 07 40 4E 00   line#394  GETTABLE 0 0 -58     <1652>   R0 = R0["new"]                                  -- It's Const#58
	  +1D97: 41 80 6B 00   line#394  LOADK 1 -431         <1653>   R1 = 5446.8793945313                            -- It's Const#431
	  +1D9B: 81 C0 6B 00   line#394  LOADK 2 -432         <1654>   R2 = 601.62945556641                            -- It's Const#432
	  +1D9F: C1 00 6C 00   line#394  LOADK 3 -433         <1655>   R3 = 749.45672607422                            -- It's Const#433
	  +1DA3: 24 80 00 02   line#394  CALL 0 4 2           <1656>   R0 = R0(R1, R2, R3)
	  +1DA7: 08 00 80 88   line#394  SETTABUP 0 -18 0     <1657>   Upv#1@_ENV["CFrameQuest"] = R0                  -- It's Const#18
	  +1DAB: 1E 00 C2 80   line#394  JMP 0 777            <1658>   GOTO <2436>
	  +1DAF: 06 00 40 00   line#395  GETTABUP 0 0 -1      <1659>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +1DB3: 41 40 6C 00   line#395  LOADK 1 -434         <1660>   R1 = 1650                                       -- It's Const#434
	  +1DB7: 5F 40 00 00   line#395  EQ 1 0 1             <1661>   if R0 ~= R1 then GOTO <1663>
	  +1DBB: 1E C0 00 80   line#395  JMP 0 4              <1662>   GOTO <1667>
	  +1DBF: 06 00 40 00   line#395  GETTABUP 0 0 -1      <1663>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +1DC3: 41 80 6C 00   line#395  LOADK 1 -435         <1664>   R1 = 1699                                       -- It's Const#435
	  +1DC7: 21 40 00 00   line#395  LE 0 0 1             <1665>   if R0 <= R1 then GOTO <1667>
	  +1DCB: 1E 80 03 80   line#395  JMP 0 15             <1666>   GOTO <1682>
	  +1DCF: 01 C0 6C 00   line#396  LOADK 0 -436         <1667>   R0 = "Giant Islander [Lv. 1650]"                -- It's Const#436
	  +1DD3: 08 00 00 85   line#396  SETTABUP 0 -11 0     <1668>   Upv#1@_ENV["Mon"] = R0                          -- It's Const#11
	  +1DD7: 01 00 6B 00   line#397  LOADK 0 -429         <1669>   R0 = "AmazonQuest2"                             -- It's Const#429
	  +1DDB: 08 00 80 86   line#397  SETTABUP 0 -14 0     <1670>   Upv#1@_ENV["NQuest"] = R0                       -- It's Const#14
	  +1DDF: 08 40 4D 86   line#398  SETTABUP 0 -13 -54   <1671>   Upv#1@_ENV["LQuest"] = 2                        -- It's Const#13, Const#54
	  +1DE3: 01 00 6D 00   line#399  LOADK 0 -437         <1672>   R0 = "Giant Islander"                           -- It's Const#437
	  +1DE7: 08 00 80 87   line#399  SETTABUP 0 -16 0     <1673>   Upv#1@_ENV["NameMon"] = R0                      -- It's Const#16
	  +1DEB: 06 00 4E 00   line#400  GETTABUP 0 0 -57     <1674>   R0 = Upv#1@_ENV["CFrame"]                       -- It's Const#57
	  +1DEF: 07 40 4E 00   line#400  GETTABLE 0 0 -58     <1675>   R0 = R0["new"]                                  -- It's Const#58
	  +1DF3: 41 80 6B 00   line#400  LOADK 1 -431         <1676>   R1 = 5446.8793945313                            -- It's Const#431
	  +1DF7: 81 C0 6B 00   line#400  LOADK 2 -432         <1677>   R2 = 601.62945556641                            -- It's Const#432
	  +1DFB: C1 00 6C 00   line#400  LOADK 3 -433         <1678>   R3 = 749.45672607422                            -- It's Const#433
	  +1DFF: 24 80 00 02   line#400  CALL 0 4 2           <1679>   R0 = R0(R1, R2, R3)
	  +1E03: 08 00 80 88   line#400  SETTABUP 0 -18 0     <1680>   Upv#1@_ENV["CFrameQuest"] = R0                  -- It's Const#18
	  +1E07: 1E 40 BC 80   line#400  JMP 0 754            <1681>   GOTO <2436>
	  +1E0B: 06 00 40 00   line#401  GETTABUP 0 0 -1      <1682>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +1E0F: 41 40 6D 00   line#401  LOADK 1 -438         <1683>   R1 = 1700                                       -- It's Const#438
	  +1E13: 5F 40 00 00   line#401  EQ 1 0 1             <1684>   if R0 ~= R1 then GOTO <1686>
	  +1E17: 1E C0 00 80   line#401  JMP 0 4              <1685>   GOTO <1690>
	  +1E1B: 06 00 40 00   line#401  GETTABUP 0 0 -1      <1686>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +1E1F: 41 80 6D 00   line#401  LOADK 1 -439         <1687>   R1 = 1724                                       -- It's Const#439
	  +1E23: 21 40 00 00   line#401  LE 0 0 1             <1688>   if R0 <= R1 then GOTO <1690>
	  +1E27: 1E C0 05 80   line#401  JMP 0 24             <1689>   GOTO <1714>
	  +1E2B: 01 C0 6D 00   line#402  LOADK 0 -440         <1690>   R0 = "Marine Commodore [Lv. 1700]"              -- It's Const#440
	  +1E2F: 08 00 00 85   line#402  SETTABUP 0 -11 0     <1691>   Upv#1@_ENV["Mon"] = R0                          -- It's Const#11
	  +1E33: 08 00 42 86   line#403  SETTABUP 0 -13 -9    <1692>   Upv#1@_ENV["LQuest"] = 1                        -- It's Const#13, Const#9
	  +1E37: 01 00 6E 00   line#404  LOADK 0 -441         <1693>   R0 = "MarineTreeIsland"                         -- It's Const#441
	  +1E3B: 08 00 80 86   line#404  SETTABUP 0 -14 0     <1694>   Upv#1@_ENV["NQuest"] = R0                       -- It's Const#14
	  +1E3F: 01 40 6E 00   line#405  LOADK 0 -442         <1695>   R0 = "Marine Commodore"                         -- It's Const#442
	  +1E43: 08 00 80 87   line#405  SETTABUP 0 -16 0     <1696>   Upv#1@_ENV["NameMon"] = R0                      -- It's Const#16
	  +1E47: 06 00 4E 00   line#406  GETTABUP 0 0 -57     <1697>   R0 = Upv#1@_ENV["CFrame"]                       -- It's Const#57
	  +1E4B: 07 40 4E 00   line#406  GETTABLE 0 0 -58     <1698>   R0 = R0["new"]                                  -- It's Const#58
	  +1E4F: 41 80 6E 00   line#406  LOADK 1 -443         <1699>   R1 = 2180.54126                                 -- It's Const#443
	  +1E53: 81 C0 6E 00   line#406  LOADK 2 -444         <1700>   R2 = 27.8156815                                 -- It's Const#444
	  +1E57: C1 00 6F 00   line#406  LOADK 3 -445         <1701>   R3 = (-6741.5498)                               -- It's Const#445
	  +1E5B: 01 41 6F 00   line#406  LOADK 4 -446         <1702>   R4 = (-0.965929747)                             -- It's Const#446
	  +1E5F: 41 81 0F 00   line#406  LOADK 5 -63          <1703>   R5 = 0                                          -- It's Const#63
	  +1E63: 81 81 64 00   line#406  LOADK 6 -403         <1704>   R6 = 0.258804798                                -- It's Const#403
	  +1E67: C1 81 0F 00   line#406  LOADK 7 -63          <1705>   R7 = 0                                          -- It's Const#63
	  +1E6B: 01 02 02 00   line#406  LOADK 8 -9           <1706>   R8 = 1                                          -- It's Const#9
	  +1E6F: 41 82 0F 00   line#406  LOADK 9 -63          <1707>   R9 = 0                                          -- It's Const#63
	  +1E73: 81 42 64 00   line#406  LOADK 10 -402        <1708>   R10 = (-0.258804798)                            -- It's Const#402
	  +1E77: C1 82 0F 00   line#406  LOADK 11 -63         <1709>   R11 = 0                                         -- It's Const#63
	  +1E7B: 01 43 6F 00   line#406  LOADK 12 -446        <1710>   R12 = (-0.965929747)                            -- It's Const#446
	  +1E7F: 24 80 80 06   line#406  CALL 0 13 2          <1711>   R0 = R0(R1,..,R12)
	  +1E83: 08 00 80 88   line#406  SETTABUP 0 -18 0     <1712>   Upv#1@_ENV["CFrameQuest"] = R0                  -- It's Const#18
	  +1E87: 1E 40 B4 80   line#406  JMP 0 722            <1713>   GOTO <2436>
	  +1E8B: 06 00 40 00   line#407  GETTABUP 0 0 -1      <1714>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +1E8F: 41 80 6F 00   line#407  LOADK 1 -447         <1715>   R1 = 1725                                       -- It's Const#447
	  +1E93: 5F 40 00 00   line#407  EQ 1 0 1             <1716>   if R0 ~= R1 then GOTO <1718>
	  +1E97: 1E C0 00 80   line#407  JMP 0 4              <1717>   GOTO <1722>
	  +1E9B: 06 00 40 00   line#407  GETTABUP 0 0 -1      <1718>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +1E9F: 41 C0 6F 00   line#407  LOADK 1 -448         <1719>   R1 = 1774                                       -- It's Const#448
	  +1EA3: 21 40 00 00   line#407  LE 0 0 1             <1720>   if R0 <= R1 then GOTO <1722>
	  +1EA7: 1E 80 03 80   line#407  JMP 0 15             <1721>   GOTO <1737>
	  +1EAB: 01 00 70 00   line#408  LOADK 0 -449         <1722>   R0 = "Marine Rear Admiral [Lv. 1725]"           -- It's Const#449
	  +1EAF: 08 00 00 85   line#408  SETTABUP 0 -11 0     <1723>   Upv#1@_ENV["Mon"] = R0                          -- It's Const#11
	  +1EB3: 01 40 70 00   line#409  LOADK 0 -450         <1724>   R0 = "Marine Rear Admiral"                      -- It's Const#450
	  +1EB7: 08 00 80 87   line#409  SETTABUP 0 -16 0     <1725>   Upv#1@_ENV["NameMon"] = R0                      -- It's Const#16
	  +1EBB: 01 00 6E 00   line#410  LOADK 0 -441         <1726>   R0 = "MarineTreeIsland"                         -- It's Const#441
	  +1EBF: 08 00 80 86   line#410  SETTABUP 0 -14 0     <1727>   Upv#1@_ENV["NQuest"] = R0                       -- It's Const#14
	  +1EC3: 08 40 4D 86   line#411  SETTABUP 0 -13 -54   <1728>   Upv#1@_ENV["LQuest"] = 2                        -- It's Const#13, Const#54
	  +1EC7: 06 00 4E 00   line#412  GETTABUP 0 0 -57     <1729>   R0 = Upv#1@_ENV["CFrame"]                       -- It's Const#57
	  +1ECB: 07 40 4E 00   line#412  GETTABLE 0 0 -58     <1730>   R0 = R0["new"]                                  -- It's Const#58
	  +1ECF: 41 80 70 00   line#412  LOADK 1 -451         <1731>   R1 = 558077/256                                 -- It's Const#451
	  +1ED3: 81 C0 70 00   line#412  LOADK 2 -452         <1732>   R2 = 28.731239318848                            -- It's Const#452
	  +1ED7: C1 00 71 00   line#412  LOADK 3 -453         <1733>   R3 = (-6740.0551757813)                         -- It's Const#453
	  +1EDB: 24 80 00 02   line#412  CALL 0 4 2           <1734>   R0 = R0(R1, R2, R3)
	  +1EDF: 08 00 80 88   line#412  SETTABUP 0 -18 0     <1735>   Upv#1@_ENV["CFrameQuest"] = R0                  -- It's Const#18
	  +1EE3: 1E 80 AE 80   line#412  JMP 0 699            <1736>   GOTO <2436>
	  +1EE7: 06 00 40 00   line#413  GETTABUP 0 0 -1      <1737>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +1EEB: 41 40 71 00   line#413  LOADK 1 -454         <1738>   R1 = 1775                                       -- It's Const#454
	  +1EEF: 5F 40 00 00   line#413  EQ 1 0 1             <1739>   if R0 ~= R1 then GOTO <1741>
	  +1EF3: 1E C0 00 80   line#413  JMP 0 4              <1740>   GOTO <1745>
	  +1EF7: 06 00 40 00   line#413  GETTABUP 0 0 -1      <1741>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +1EFB: 41 80 71 00   line#413  LOADK 1 -455         <1742>   R1 = 1799                                       -- It's Const#455
	  +1EFF: 21 40 00 00   line#413  LE 0 0 1             <1743>   if R0 <= R1 then GOTO <1745>
	  +1F03: 1E C0 05 80   line#413  JMP 0 24             <1744>   GOTO <1769>
	  +1F07: 01 C0 71 00   line#414  LOADK 0 -456         <1745>   R0 = "Fishman Raider [Lv. 1775]"                -- It's Const#456
	  +1F0B: 08 00 00 85   line#414  SETTABUP 0 -11 0     <1746>   Upv#1@_ENV["Mon"] = R0                          -- It's Const#11
	  +1F0F: 08 00 42 86   line#415  SETTABUP 0 -13 -9    <1747>   Upv#1@_ENV["LQuest"] = 1                        -- It's Const#13, Const#9
	  +1F13: 01 00 72 00   line#416  LOADK 0 -457         <1748>   R0 = "DeepForestIsland3"                        -- It's Const#457
	  +1F17: 08 00 80 86   line#416  SETTABUP 0 -14 0     <1749>   Upv#1@_ENV["NQuest"] = R0                       -- It's Const#14
	  +1F1B: 01 40 72 00   line#417  LOADK 0 -458         <1750>   R0 = "Fishman Raider"                           -- It's Const#458
	  +1F1F: 08 00 80 87   line#417  SETTABUP 0 -16 0     <1751>   Upv#1@_ENV["NameMon"] = R0                      -- It's Const#16
	  +1F23: 06 00 4E 00   line#418  GETTABUP 0 0 -57     <1752>   R0 = Upv#1@_ENV["CFrame"]                       -- It's Const#57
	  +1F27: 07 40 4E 00   line#418  GETTABLE 0 0 -58     <1753>   R0 = R0["new"]                                  -- It's Const#58
	  +1F2B: 41 80 72 00   line#418  LOADK 1 -459         <1754>   R1 = (-10581.6563)                              -- It's Const#459
	  +1F2F: 81 C0 72 00   line#418  LOADK 2 -460         <1755>   R2 = 330.872955                                 -- It's Const#460
	  +1F33: C1 00 73 00   line#418  LOADK 3 -461         <1756>   R3 = (-8761.18652)                              -- It's Const#461
	  +1F37: 01 81 51 00   line#418  LOADK 4 -327         <1757>   R4 = (-0.882952213)                             -- It's Const#327
	  +1F3B: 41 81 0F 00   line#418  LOADK 5 -63          <1758>   R5 = 0                                          -- It's Const#63
	  +1F3F: 81 C1 51 00   line#418  LOADK 6 -328         <1759>   R6 = 0.469463557                                -- It's Const#328
	  +1F43: C1 81 0F 00   line#418  LOADK 7 -63          <1760>   R7 = 0                                          -- It's Const#63
	  +1F47: 01 02 02 00   line#418  LOADK 8 -9           <1761>   R8 = 1                                          -- It's Const#9
	  +1F4B: 41 82 0F 00   line#418  LOADK 9 -63          <1762>   R9 = 0                                          -- It's Const#63
	  +1F4F: 81 02 52 00   line#418  LOADK 10 -329        <1763>   R10 = (-0.469463557)                            -- It's Const#329
	  +1F53: C1 82 0F 00   line#418  LOADK 11 -63         <1764>   R11 = 0                                         -- It's Const#63
	  +1F57: 01 83 51 00   line#418  LOADK 12 -327        <1765>   R12 = (-0.882952213)                            -- It's Const#327
	  +1F5B: 24 80 80 06   line#418  CALL 0 13 2          <1766>   R0 = R0(R1,..,R12)
	  +1F5F: 08 00 80 88   line#418  SETTABUP 0 -18 0     <1767>   Upv#1@_ENV["CFrameQuest"] = R0                  -- It's Const#18
	  +1F63: 1E 80 A6 80   line#418  JMP 0 667            <1768>   GOTO <2436>
	  +1F67: 06 00 40 00   line#419  GETTABUP 0 0 -1      <1769>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +1F6B: 41 40 73 00   line#419  LOADK 1 -462         <1770>   R1 = 1800                                       -- It's Const#462
	  +1F6F: 5F 40 00 00   line#419  EQ 1 0 1             <1771>   if R0 ~= R1 then GOTO <1773>
	  +1F73: 1E C0 00 80   line#419  JMP 0 4              <1772>   GOTO <1777>
	  +1F77: 06 00 40 00   line#419  GETTABUP 0 0 -1      <1773>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +1F7B: 41 80 73 00   line#419  LOADK 1 -463         <1774>   R1 = 1824                                       -- It's Const#463
	  +1F7F: 21 40 00 00   line#419  LE 0 0 1             <1775>   if R0 <= R1 then GOTO <1777>
	  +1F83: 1E C0 05 80   line#419  JMP 0 24             <1776>   GOTO <1801>
	  +1F87: 01 C0 73 00   line#420  LOADK 0 -464         <1777>   R0 = "Fishman Captain [Lv. 1800]"               -- It's Const#464
	  +1F8B: 08 00 00 85   line#420  SETTABUP 0 -11 0     <1778>   Upv#1@_ENV["Mon"] = R0                          -- It's Const#11
	  +1F8F: 08 40 4D 86   line#421  SETTABUP 0 -13 -54   <1779>   Upv#1@_ENV["LQuest"] = 2                        -- It's Const#13, Const#54
	  +1F93: 01 00 72 00   line#422  LOADK 0 -457         <1780>   R0 = "DeepForestIsland3"                        -- It's Const#457
	  +1F97: 08 00 80 86   line#422  SETTABUP 0 -14 0     <1781>   Upv#1@_ENV["NQuest"] = R0                       -- It's Const#14
	  +1F9B: 01 00 74 00   line#423  LOADK 0 -465         <1782>   R0 = "Fishman Captain"                          -- It's Const#465
	  +1F9F: 08 00 80 87   line#423  SETTABUP 0 -16 0     <1783>   Upv#1@_ENV["NameMon"] = R0                      -- It's Const#16
	  +1FA3: 06 00 4E 00   line#424  GETTABUP 0 0 -57     <1784>   R0 = Upv#1@_ENV["CFrame"]                       -- It's Const#57
	  +1FA7: 07 40 4E 00   line#424  GETTABLE 0 0 -58     <1785>   R0 = R0["new"]                                  -- It's Const#58
	  +1FAB: 41 80 72 00   line#424  LOADK 1 -459         <1786>   R1 = (-10581.6563)                              -- It's Const#459
	  +1FAF: 81 C0 72 00   line#424  LOADK 2 -460         <1787>   R2 = 330.872955                                 -- It's Const#460
	  +1FB3: C1 00 73 00   line#424  LOADK 3 -461         <1788>   R3 = (-8761.18652)                              -- It's Const#461
	  +1FB7: 01 81 51 00   line#424  LOADK 4 -327         <1789>   R4 = (-0.882952213)                             -- It's Const#327
	  +1FBB: 41 81 0F 00   line#424  LOADK 5 -63          <1790>   R5 = 0                                          -- It's Const#63
	  +1FBF: 81 C1 51 00   line#424  LOADK 6 -328         <1791>   R6 = 0.469463557                                -- It's Const#328
	  +1FC3: C1 81 0F 00   line#424  LOADK 7 -63          <1792>   R7 = 0                                          -- It's Const#63
	  +1FC7: 01 02 02 00   line#424  LOADK 8 -9           <1793>   R8 = 1                                          -- It's Const#9
	  +1FCB: 41 82 0F 00   line#424  LOADK 9 -63          <1794>   R9 = 0                                          -- It's Const#63
	  +1FCF: 81 02 52 00   line#424  LOADK 10 -329        <1795>   R10 = (-0.469463557)                            -- It's Const#329
	  +1FD3: C1 82 0F 00   line#424  LOADK 11 -63         <1796>   R11 = 0                                         -- It's Const#63
	  +1FD7: 01 83 51 00   line#424  LOADK 12 -327        <1797>   R12 = (-0.882952213)                            -- It's Const#327
	  +1FDB: 24 80 80 06   line#424  CALL 0 13 2          <1798>   R0 = R0(R1,..,R12)
	  +1FDF: 08 00 80 88   line#424  SETTABUP 0 -18 0     <1799>   Upv#1@_ENV["CFrameQuest"] = R0                  -- It's Const#18
	  +1FE3: 1E 80 9E 80   line#424  JMP 0 635            <1800>   GOTO <2436>
	  +1FE7: 06 00 40 00   line#425  GETTABUP 0 0 -1      <1801>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +1FEB: 41 40 74 00   line#425  LOADK 1 -466         <1802>   R1 = 1825                                       -- It's Const#466
	  +1FEF: 5F 40 00 00   line#425  EQ 1 0 1             <1803>   if R0 ~= R1 then GOTO <1805>
	  +1FF3: 1E C0 00 80   line#425  JMP 0 4              <1804>   GOTO <1809>
	  +1FF7: 06 00 40 00   line#425  GETTABUP 0 0 -1      <1805>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +1FFB: 41 80 74 00   line#425  LOADK 1 -467         <1806>   R1 = 1849                                       -- It's Const#467
	  +1FFF: 21 40 00 00   line#425  LE 0 0 1             <1807>   if R0 <= R1 then GOTO <1809>
	  +2003: 1E C0 05 80   line#425  JMP 0 24             <1808>   GOTO <1833>
	  +2007: 01 C0 74 00   line#426  LOADK 0 -468         <1809>   R0 = "Forest Pirate [Lv. 1825]"                 -- It's Const#468
	  +200B: 08 00 00 85   line#426  SETTABUP 0 -11 0     <1810>   Upv#1@_ENV["Mon"] = R0                          -- It's Const#11
	  +200F: 08 00 42 86   line#427  SETTABUP 0 -13 -9    <1811>   Upv#1@_ENV["LQuest"] = 1                        -- It's Const#13, Const#9
	  +2013: 01 00 75 00   line#428  LOADK 0 -469         <1812>   R0 = "DeepForestIsland"                         -- It's Const#469
	  +2017: 08 00 80 86   line#428  SETTABUP 0 -14 0     <1813>   Upv#1@_ENV["NQuest"] = R0                       -- It's Const#14
	  +201B: 01 40 75 00   line#429  LOADK 0 -470         <1814>   R0 = "Forest Pirate"                            -- It's Const#470
	  +201F: 08 00 80 87   line#429  SETTABUP 0 -16 0     <1815>   Upv#1@_ENV["NameMon"] = R0                      -- It's Const#16
	  +2023: 06 00 4E 00   line#430  GETTABUP 0 0 -57     <1816>   R0 = Upv#1@_ENV["CFrame"]                       -- It's Const#57
	  +2027: 07 40 4E 00   line#430  GETTABLE 0 0 -58     <1817>   R0 = R0["new"]                                  -- It's Const#58
	  +202B: 41 80 75 00   line#430  LOADK 1 -471         <1818>   R1 = (-13234.04)                                -- It's Const#471
	  +202F: 81 C0 75 00   line#430  LOADK 2 -472         <1819>   R2 = 331.488495                                 -- It's Const#472
	  +2033: C1 00 76 00   line#430  LOADK 3 -473         <1820>   R3 = (-7625.40137)                              -- It's Const#473
	  +2037: 01 41 76 00   line#430  LOADK 4 -474         <1821>   R4 = 0.707134247                                -- It's Const#474
	  +203B: 41 81 0F 00   line#430  LOADK 5 -63          <1822>   R5 = 0                                          -- It's Const#63
	  +203F: 81 81 76 00   line#430  LOADK 6 -475         <1823>   R6 = (-0.707079291)                             -- It's Const#475
	  +2043: C1 81 0F 00   line#430  LOADK 7 -63          <1824>   R7 = 0                                          -- It's Const#63
	  +2047: 01 02 02 00   line#430  LOADK 8 -9           <1825>   R8 = 1                                          -- It's Const#9
	  +204B: 41 82 0F 00   line#430  LOADK 9 -63          <1826>   R9 = 0                                          -- It's Const#63
	  +204F: 81 C2 76 00   line#430  LOADK 10 -476        <1827>   R10 = 0.707079291                               -- It's Const#476
	  +2053: C1 82 0F 00   line#430  LOADK 11 -63         <1828>   R11 = 0                                         -- It's Const#63
	  +2057: 01 43 76 00   line#430  LOADK 12 -474        <1829>   R12 = 0.707134247                               -- It's Const#474
	  +205B: 24 80 80 06   line#430  CALL 0 13 2          <1830>   R0 = R0(R1,..,R12)
	  +205F: 08 00 80 88   line#430  SETTABUP 0 -18 0     <1831>   Upv#1@_ENV["CFrameQuest"] = R0                  -- It's Const#18
	  +2063: 1E 80 96 80   line#430  JMP 0 603            <1832>   GOTO <2436>
	  +2067: 06 00 40 00   line#431  GETTABUP 0 0 -1      <1833>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +206B: 41 00 77 00   line#431  LOADK 1 -477         <1834>   R1 = 1850                                       -- It's Const#477
	  +206F: 5F 40 00 00   line#431  EQ 1 0 1             <1835>   if R0 ~= R1 then GOTO <1837>
	  +2073: 1E C0 00 80   line#431  JMP 0 4              <1836>   GOTO <1841>
	  +2077: 06 00 40 00   line#431  GETTABUP 0 0 -1      <1837>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +207B: 41 40 77 00   line#431  LOADK 1 -478         <1838>   R1 = 1899                                       -- It's Const#478
	  +207F: 21 40 00 00   line#431  LE 0 0 1             <1839>   if R0 <= R1 then GOTO <1841>
	  +2083: 1E C0 05 80   line#431  JMP 0 24             <1840>   GOTO <1865>
	  +2087: 01 80 77 00   line#432  LOADK 0 -479         <1841>   R0 = "Mythological Pirate [Lv. 1850]"           -- It's Const#479
	  +208B: 08 00 00 85   line#432  SETTABUP 0 -11 0     <1842>   Upv#1@_ENV["Mon"] = R0                          -- It's Const#11
	  +208F: 08 40 4D 86   line#433  SETTABUP 0 -13 -54   <1843>   Upv#1@_ENV["LQuest"] = 2                        -- It's Const#13, Const#54
	  +2093: 01 00 75 00   line#434  LOADK 0 -469         <1844>   R0 = "DeepForestIsland"                         -- It's Const#469
	  +2097: 08 00 80 86   line#434  SETTABUP 0 -14 0     <1845>   Upv#1@_ENV["NQuest"] = R0                       -- It's Const#14
	  +209B: 01 C0 77 00   line#435  LOADK 0 -480         <1846>   R0 = "Mythological Pirate"                      -- It's Const#480
	  +209F: 08 00 80 87   line#435  SETTABUP 0 -16 0     <1847>   Upv#1@_ENV["NameMon"] = R0                      -- It's Const#16
	  +20A3: 06 00 4E 00   line#436  GETTABUP 0 0 -57     <1848>   R0 = Upv#1@_ENV["CFrame"]                       -- It's Const#57
	  +20A7: 07 40 4E 00   line#436  GETTABLE 0 0 -58     <1849>   R0 = R0["new"]                                  -- It's Const#58
	  +20AB: 41 80 75 00   line#436  LOADK 1 -471         <1850>   R1 = (-13234.04)                                -- It's Const#471
	  +20AF: 81 C0 75 00   line#436  LOADK 2 -472         <1851>   R2 = 331.488495                                 -- It's Const#472
	  +20B3: C1 00 76 00   line#436  LOADK 3 -473         <1852>   R3 = (-7625.40137)                              -- It's Const#473
	  +20B7: 01 41 76 00   line#436  LOADK 4 -474         <1853>   R4 = 0.707134247                                -- It's Const#474
	  +20BB: 41 81 0F 00   line#436  LOADK 5 -63          <1854>   R5 = 0                                          -- It's Const#63
	  +20BF: 81 81 76 00   line#436  LOADK 6 -475         <1855>   R6 = (-0.707079291)                             -- It's Const#475
	  +20C3: C1 81 0F 00   line#436  LOADK 7 -63          <1856>   R7 = 0                                          -- It's Const#63
	  +20C7: 01 02 02 00   line#436  LOADK 8 -9           <1857>   R8 = 1                                          -- It's Const#9
	  +20CB: 41 82 0F 00   line#436  LOADK 9 -63          <1858>   R9 = 0                                          -- It's Const#63
	  +20CF: 81 C2 76 00   line#436  LOADK 10 -476        <1859>   R10 = 0.707079291                               -- It's Const#476
	  +20D3: C1 82 0F 00   line#436  LOADK 11 -63         <1860>   R11 = 0                                         -- It's Const#63
	  +20D7: 01 43 76 00   line#436  LOADK 12 -474        <1861>   R12 = 0.707134247                               -- It's Const#474
	  +20DB: 24 80 80 06   line#436  CALL 0 13 2          <1862>   R0 = R0(R1,..,R12)
	  +20DF: 08 00 80 88   line#436  SETTABUP 0 -18 0     <1863>   Upv#1@_ENV["CFrameQuest"] = R0                  -- It's Const#18
	  +20E3: 1E 80 8E 80   line#436  JMP 0 571            <1864>   GOTO <2436>
	  +20E7: 06 00 40 00   line#437  GETTABUP 0 0 -1      <1865>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +20EB: 41 00 78 00   line#437  LOADK 1 -481         <1866>   R1 = 1900                                       -- It's Const#481
	  +20EF: 5F 40 00 00   line#437  EQ 1 0 1             <1867>   if R0 ~= R1 then GOTO <1869>
	  +20F3: 1E C0 00 80   line#437  JMP 0 4              <1868>   GOTO <1873>
	  +20F7: 06 00 40 00   line#437  GETTABUP 0 0 -1      <1869>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +20FB: 41 40 78 00   line#437  LOADK 1 -482         <1870>   R1 = 1924                                       -- It's Const#482
	  +20FF: 21 40 00 00   line#437  LE 0 0 1             <1871>   if R0 <= R1 then GOTO <1873>
	  +2103: 1E C0 05 80   line#437  JMP 0 24             <1872>   GOTO <1897>
	  +2107: 01 80 78 00   line#438  LOADK 0 -483         <1873>   R0 = "Jungle Pirate [Lv. 1900]"                 -- It's Const#483
	  +210B: 08 00 00 85   line#438  SETTABUP 0 -11 0     <1874>   Upv#1@_ENV["Mon"] = R0                          -- It's Const#11
	  +210F: 08 00 42 86   line#439  SETTABUP 0 -13 -9    <1875>   Upv#1@_ENV["LQuest"] = 1                        -- It's Const#13, Const#9
	  +2113: 01 C0 78 00   line#440  LOADK 0 -484         <1876>   R0 = "DeepForestIsland2"                        -- It's Const#484
	  +2117: 08 00 80 86   line#440  SETTABUP 0 -14 0     <1877>   Upv#1@_ENV["NQuest"] = R0                       -- It's Const#14
	  +211B: 01 00 79 00   line#441  LOADK 0 -485         <1878>   R0 = "Jungle Pirate"                            -- It's Const#485
	  +211F: 08 00 80 87   line#441  SETTABUP 0 -16 0     <1879>   Upv#1@_ENV["NameMon"] = R0                      -- It's Const#16
	  +2123: 06 00 4E 00   line#442  GETTABUP 0 0 -57     <1880>   R0 = Upv#1@_ENV["CFrame"]                       -- It's Const#57
	  +2127: 07 40 4E 00   line#442  GETTABLE 0 0 -58     <1881>   R0 = R0["new"]                                  -- It's Const#58
	  +212B: 41 40 79 00   line#442  LOADK 1 -486         <1882>   R1 = (-12680.3818)                              -- It's Const#486
	  +212F: 81 80 79 00   line#442  LOADK 2 -487         <1883>   R2 = 389.971039                                 -- It's Const#487
	  +2133: C1 C0 79 00   line#442  LOADK 3 -488         <1884>   R3 = (-9902.01953)                              -- It's Const#488
	  +2137: 01 01 7A 00   line#442  LOADK 4 -489         <1885>   R4 = (-0.0871315002)                            -- It's Const#489
	  +213B: 41 81 0F 00   line#442  LOADK 5 -63          <1886>   R5 = 0                                          -- It's Const#63
	  +213F: 81 C1 35 00   line#442  LOADK 6 -216         <1887>   R6 = 0.996196866                                -- It's Const#216
	  +2143: C1 81 0F 00   line#442  LOADK 7 -63          <1888>   R7 = 0                                          -- It's Const#63
	  +2147: 01 02 02 00   line#442  LOADK 8 -9           <1889>   R8 = 1                                          -- It's Const#9
	  +214B: 41 82 0F 00   line#442  LOADK 9 -63          <1890>   R9 = 0                                          -- It's Const#63
	  +214F: 81 02 36 00   line#442  LOADK 10 -217        <1891>   R10 = (-0.996196866)                            -- It's Const#217
	  +2153: C1 82 0F 00   line#442  LOADK 11 -63         <1892>   R11 = 0                                         -- It's Const#63
	  +2157: 01 03 7A 00   line#442  LOADK 12 -489        <1893>   R12 = (-0.0871315002)                           -- It's Const#489
	  +215B: 24 80 80 06   line#442  CALL 0 13 2          <1894>   R0 = R0(R1,..,R12)
	  +215F: 08 00 80 88   line#442  SETTABUP 0 -18 0     <1895>   Upv#1@_ENV["CFrameQuest"] = R0                  -- It's Const#18
	  +2163: 1E 80 86 80   line#442  JMP 0 539            <1896>   GOTO <2436>
	  +2167: 06 00 40 00   line#443  GETTABUP 0 0 -1      <1897>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +216B: 41 40 7A 00   line#443  LOADK 1 -490         <1898>   R1 = 1925                                       -- It's Const#490
	  +216F: 5F 40 00 00   line#443  EQ 1 0 1             <1899>   if R0 ~= R1 then GOTO <1901>
	  +2173: 1E C0 00 80   line#443  JMP 0 4              <1900>   GOTO <1905>
	  +2177: 06 00 40 00   line#443  GETTABUP 0 0 -1      <1901>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +217B: 41 80 7A 00   line#443  LOADK 1 -491         <1902>   R1 = 1974                                       -- It's Const#491
	  +217F: 21 40 00 00   line#443  LE 0 0 1             <1903>   if R0 <= R1 then GOTO <1905>
	  +2183: 1E C0 05 80   line#443  JMP 0 24             <1904>   GOTO <1929>
	  +2187: 01 C0 7A 00   line#444  LOADK 0 -492         <1905>   R0 = "Musketeer Pirate [Lv. 1925]"              -- It's Const#492
	  +218B: 08 00 00 85   line#444  SETTABUP 0 -11 0     <1906>   Upv#1@_ENV["Mon"] = R0                          -- It's Const#11
	  +218F: 08 40 4D 86   line#445  SETTABUP 0 -13 -54   <1907>   Upv#1@_ENV["LQuest"] = 2                        -- It's Const#13, Const#54
	  +2193: 01 C0 78 00   line#446  LOADK 0 -484         <1908>   R0 = "DeepForestIsland2"                        -- It's Const#484
	  +2197: 08 00 80 86   line#446  SETTABUP 0 -14 0     <1909>   Upv#1@_ENV["NQuest"] = R0                       -- It's Const#14
	  +219B: 01 00 7B 00   line#447  LOADK 0 -493         <1910>   R0 = "Musketeer Pirate"                         -- It's Const#493
	  +219F: 08 00 80 87   line#447  SETTABUP 0 -16 0     <1911>   Upv#1@_ENV["NameMon"] = R0                      -- It's Const#16
	  +21A3: 06 00 4E 00   line#448  GETTABUP 0 0 -57     <1912>   R0 = Upv#1@_ENV["CFrame"]                       -- It's Const#57
	  +21A7: 07 40 4E 00   line#448  GETTABLE 0 0 -58     <1913>   R0 = R0["new"]                                  -- It's Const#58
	  +21AB: 41 40 79 00   line#448  LOADK 1 -486         <1914>   R1 = (-12680.3818)                              -- It's Const#486
	  +21AF: 81 80 79 00   line#448  LOADK 2 -487         <1915>   R2 = 389.971039                                 -- It's Const#487
	  +21B3: C1 C0 79 00   line#448  LOADK 3 -488         <1916>   R3 = (-9902.01953)                              -- It's Const#488
	  +21B7: 01 01 7A 00   line#448  LOADK 4 -489         <1917>   R4 = (-0.0871315002)                            -- It's Const#489
	  +21BB: 41 81 0F 00   line#448  LOADK 5 -63          <1918>   R5 = 0                                          -- It's Const#63
	  +21BF: 81 C1 35 00   line#448  LOADK 6 -216         <1919>   R6 = 0.996196866                                -- It's Const#216
	  +21C3: C1 81 0F 00   line#448  LOADK 7 -63          <1920>   R7 = 0                                          -- It's Const#63
	  +21C7: 01 02 02 00   line#448  LOADK 8 -9           <1921>   R8 = 1                                          -- It's Const#9
	  +21CB: 41 82 0F 00   line#448  LOADK 9 -63          <1922>   R9 = 0                                          -- It's Const#63
	  +21CF: 81 02 36 00   line#448  LOADK 10 -217        <1923>   R10 = (-0.996196866)                            -- It's Const#217
	  +21D3: C1 82 0F 00   line#448  LOADK 11 -63         <1924>   R11 = 0                                         -- It's Const#63
	  +21D7: 01 03 7A 00   line#448  LOADK 12 -489        <1925>   R12 = (-0.0871315002)                           -- It's Const#489
	  +21DB: 24 80 80 06   line#448  CALL 0 13 2          <1926>   R0 = R0(R1,..,R12)
	  +21DF: 08 00 80 88   line#448  SETTABUP 0 -18 0     <1927>   Upv#1@_ENV["CFrameQuest"] = R0                  -- It's Const#18
	  +21E3: 1E 80 7E 80   line#448  JMP 0 507            <1928>   GOTO <2436>
	  +21E7: 06 00 40 00   line#449  GETTABUP 0 0 -1      <1929>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +21EB: 41 40 7B 00   line#449  LOADK 1 -494         <1930>   R1 = 1975                                       -- It's Const#494
	  +21EF: 5F 40 00 00   line#449  EQ 1 0 1             <1931>   if R0 ~= R1 then GOTO <1933>
	  +21F3: 1E C0 00 80   line#449  JMP 0 4              <1932>   GOTO <1937>
	  +21F7: 06 00 40 00   line#449  GETTABUP 0 0 -1      <1933>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +21FB: 41 80 7B 00   line#449  LOADK 1 -495         <1934>   R1 = 1999                                       -- It's Const#495
	  +21FF: 21 40 00 00   line#449  LE 0 0 1             <1935>   if R0 <= R1 then GOTO <1937>
	  +2203: 1E C0 05 80   line#449  JMP 0 24             <1936>   GOTO <1961>
	  +2207: 01 C0 7B 00   line#450  LOADK 0 -496         <1937>   R0 = "Reborn Skeleton [Lv. 1975]"               -- It's Const#496
	  +220B: 08 00 00 85   line#450  SETTABUP 0 -11 0     <1938>   Upv#1@_ENV["Mon"] = R0                          -- It's Const#11
	  +220F: 08 00 42 86   line#451  SETTABUP 0 -13 -9    <1939>   Upv#1@_ENV["LQuest"] = 1                        -- It's Const#13, Const#9
	  +2213: 01 00 7C 00   line#452  LOADK 0 -497         <1940>   R0 = "HauntedQuest1"                            -- It's Const#497
	  +2217: 08 00 80 86   line#452  SETTABUP 0 -14 0     <1941>   Upv#1@_ENV["NQuest"] = R0                       -- It's Const#14
	  +221B: 01 40 7C 00   line#453  LOADK 0 -498         <1942>   R0 = "Reborn Skeleton"                          -- It's Const#498
	  +221F: 08 00 80 87   line#453  SETTABUP 0 -16 0     <1943>   Upv#1@_ENV["NameMon"] = R0                      -- It's Const#16
	  +2223: 06 00 4E 00   line#454  GETTABUP 0 0 -57     <1944>   R0 = Upv#1@_ENV["CFrame"]                       -- It's Const#57
	  +2227: 07 40 4E 00   line#454  GETTABLE 0 0 -58     <1945>   R0 = R0["new"]                                  -- It's Const#58
	  +222B: 41 80 7C 00   line#454  LOADK 1 -499         <1946>   R1 = (-9479.2168)                               -- It's Const#499
	  +222F: 81 C0 7C 00   line#454  LOADK 2 -500         <1947>   R2 = 141.215088                                 -- It's Const#500
	  +2233: C1 00 7D 00   line#454  LOADK 3 -501         <1948>   R3 = 5566.09277                                 -- It's Const#501
	  +2237: 01 81 0F 00   line#454  LOADK 4 -63          <1949>   R4 = 0                                          -- It's Const#63
	  +223B: 41 81 0F 00   line#454  LOADK 5 -63          <1950>   R5 = 0                                          -- It's Const#63
	  +223F: 81 01 02 00   line#454  LOADK 6 -9           <1951>   R6 = 1                                          -- It's Const#9
	  +2243: C1 81 0F 00   line#454  LOADK 7 -63          <1952>   R7 = 0                                          -- It's Const#63
	  +2247: 01 02 02 00   line#454  LOADK 8 -9           <1953>   R8 = 1                                          -- It's Const#9
	  +224B: 41 82 0F 00   line#454  LOADK 9 -63          <1954>   R9 = 0                                          -- It's Const#63
	  +224F: 81 C2 08 00   line#454  LOADK 10 -36         <1955>   R10 = (-1)                                      -- It's Const#36
	  +2253: C1 82 0F 00   line#454  LOADK 11 -63         <1956>   R11 = 0                                         -- It's Const#63
	  +2257: 01 83 0F 00   line#454  LOADK 12 -63         <1957>   R12 = 0                                         -- It's Const#63
	  +225B: 24 80 80 06   line#454  CALL 0 13 2          <1958>   R0 = R0(R1,..,R12)
	  +225F: 08 00 80 88   line#454  SETTABUP 0 -18 0     <1959>   Upv#1@_ENV["CFrameQuest"] = R0                  -- It's Const#18
	  +2263: 1E 80 76 80   line#454  JMP 0 475            <1960>   GOTO <2436>
	  +2267: 06 00 40 00   line#455  GETTABUP 0 0 -1      <1961>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +226B: 41 40 7D 00   line#455  LOADK 1 -502         <1962>   R1 = 2000                                       -- It's Const#502
	  +226F: 5F 40 00 00   line#455  EQ 1 0 1             <1963>   if R0 ~= R1 then GOTO <1965>
	  +2273: 1E C0 00 80   line#455  JMP 0 4              <1964>   GOTO <1969>
	  +2277: 06 00 40 00   line#455  GETTABUP 0 0 -1      <1965>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +227B: 41 80 7D 00   line#455  LOADK 1 -503         <1966>   R1 = 2024                                       -- It's Const#503
	  +227F: 21 40 00 00   line#455  LE 0 0 1             <1967>   if R0 <= R1 then GOTO <1969>
	  +2283: 1E C0 05 80   line#455  JMP 0 24             <1968>   GOTO <1993>
	  +2287: 01 C0 7D 00   line#456  LOADK 0 -504         <1969>   R0 = "Living Zombie [Lv. 2000]"                 -- It's Const#504
	  +228B: 08 00 00 85   line#456  SETTABUP 0 -11 0     <1970>   Upv#1@_ENV["Mon"] = R0                          -- It's Const#11
	  +228F: 08 40 4D 86   line#457  SETTABUP 0 -13 -54   <1971>   Upv#1@_ENV["LQuest"] = 2                        -- It's Const#13, Const#54
	  +2293: 01 00 7C 00   line#458  LOADK 0 -497         <1972>   R0 = "HauntedQuest1"                            -- It's Const#497
	  +2297: 08 00 80 86   line#458  SETTABUP 0 -14 0     <1973>   Upv#1@_ENV["NQuest"] = R0                       -- It's Const#14
	  +229B: 01 00 7E 00   line#459  LOADK 0 -505         <1974>   R0 = "Living Zombie"                            -- It's Const#505
	  +229F: 08 00 80 87   line#459  SETTABUP 0 -16 0     <1975>   Upv#1@_ENV["NameMon"] = R0                      -- It's Const#16
	  +22A3: 06 00 4E 00   line#460  GETTABUP 0 0 -57     <1976>   R0 = Upv#1@_ENV["CFrame"]                       -- It's Const#57
	  +22A7: 07 40 4E 00   line#460  GETTABLE 0 0 -58     <1977>   R0 = R0["new"]                                  -- It's Const#58
	  +22AB: 41 80 7C 00   line#460  LOADK 1 -499         <1978>   R1 = (-9479.2168)                               -- It's Const#499
	  +22AF: 81 C0 7C 00   line#460  LOADK 2 -500         <1979>   R2 = 141.215088                                 -- It's Const#500
	  +22B3: C1 00 7D 00   line#460  LOADK 3 -501         <1980>   R3 = 5566.09277                                 -- It's Const#501
	  +22B7: 01 81 0F 00   line#460  LOADK 4 -63          <1981>   R4 = 0                                          -- It's Const#63
	  +22BB: 41 81 0F 00   line#460  LOADK 5 -63          <1982>   R5 = 0                                          -- It's Const#63
	  +22BF: 81 01 02 00   line#460  LOADK 6 -9           <1983>   R6 = 1                                          -- It's Const#9
	  +22C3: C1 81 0F 00   line#460  LOADK 7 -63          <1984>   R7 = 0                                          -- It's Const#63
	  +22C7: 01 02 02 00   line#460  LOADK 8 -9           <1985>   R8 = 1                                          -- It's Const#9
	  +22CB: 41 82 0F 00   line#460  LOADK 9 -63          <1986>   R9 = 0                                          -- It's Const#63
	  +22CF: 81 C2 08 00   line#460  LOADK 10 -36         <1987>   R10 = (-1)                                      -- It's Const#36
	  +22D3: C1 82 0F 00   line#460  LOADK 11 -63         <1988>   R11 = 0                                         -- It's Const#63
	  +22D7: 01 83 0F 00   line#460  LOADK 12 -63         <1989>   R12 = 0                                         -- It's Const#63
	  +22DB: 24 80 80 06   line#460  CALL 0 13 2          <1990>   R0 = R0(R1,..,R12)
	  +22DF: 08 00 80 88   line#460  SETTABUP 0 -18 0     <1991>   Upv#1@_ENV["CFrameQuest"] = R0                  -- It's Const#18
	  +22E3: 1E 80 6E 80   line#460  JMP 0 443            <1992>   GOTO <2436>
	  +22E7: 06 00 40 00   line#461  GETTABUP 0 0 -1      <1993>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +22EB: 41 40 7E 00   line#461  LOADK 1 -506         <1994>   R1 = 2025                                       -- It's Const#506
	  +22EF: 5F 40 00 00   line#461  EQ 1 0 1             <1995>   if R0 ~= R1 then GOTO <1997>
	  +22F3: 1E C0 00 80   line#461  JMP 0 4              <1996>   GOTO <2001>
	  +22F7: 06 00 40 00   line#461  GETTABUP 0 0 -1      <1997>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +22FB: 41 80 7E 00   line#461  LOADK 1 -507         <1998>   R1 = 2049                                       -- It's Const#507
	  +22FF: 21 40 00 00   line#461  LE 0 0 1             <1999>   if R0 <= R1 then GOTO <2001>
	  +2303: 1E C0 05 80   line#461  JMP 0 24             <2000>   GOTO <2025>
	  +2307: 01 C0 7E 00   line#462  LOADK 0 -508         <2001>   R0 = "Demonic Soul [Lv. 2025]"                  -- It's Const#508
	  +230B: 08 00 00 85   line#462  SETTABUP 0 -11 0     <2002>   Upv#1@_ENV["Mon"] = R0                          -- It's Const#11
	  +230F: 08 00 42 86   line#463  SETTABUP 0 -13 -9    <2003>   Upv#1@_ENV["LQuest"] = 1                        -- It's Const#13, Const#9
	  +2313: 01 00 7F 00   line#464  LOADK 0 -509         <2004>   R0 = "HauntedQuest2"                            -- It's Const#509
	  +2317: 08 00 80 86   line#464  SETTABUP 0 -14 0     <2005>   Upv#1@_ENV["NQuest"] = R0                       -- It's Const#14
	  +231B: 01 40 7F 00   line#465  LOADK 0 -510         <2006>   R0 = "Demonic Soul"                             -- It's Const#510
	  +231F: 08 00 80 87   line#465  SETTABUP 0 -16 0     <2007>   Upv#1@_ENV["NameMon"] = R0                      -- It's Const#16
	  +2323: 06 00 4E 00   line#466  GETTABUP 0 0 -57     <2008>   R0 = Upv#1@_ENV["CFrame"]                       -- It's Const#57
	  +2327: 07 40 4E 00   line#466  GETTABLE 0 0 -58     <2009>   R0 = R0["new"]                                  -- It's Const#58
	  +232B: 41 80 7F 00   line#466  LOADK 1 -511         <2010>   R1 = (-9516.99316)                              -- It's Const#511
	  +232F: 81 C0 7F 00   line#466  LOADK 2 -512         <2011>   R2 = 172.017181                                 -- It's Const#512
	  +2333: C1 00 80 00   line#466  LOADK 3 -513         <2012>   R3 = 6078.46533                                 -- It's Const#513
	  +2337: 01 81 0F 00   line#466  LOADK 4 -63          <2013>   R4 = 0                                          -- It's Const#63
	  +233B: 41 81 0F 00   line#466  LOADK 5 -63          <2014>   R5 = 0                                          -- It's Const#63
	  +233F: 81 C1 08 00   line#466  LOADK 6 -36          <2015>   R6 = (-1)                                       -- It's Const#36
	  +2343: C1 81 0F 00   line#466  LOADK 7 -63          <2016>   R7 = 0                                          -- It's Const#63
	  +2347: 01 02 02 00   line#466  LOADK 8 -9           <2017>   R8 = 1                                          -- It's Const#9
	  +234B: 41 82 0F 00   line#466  LOADK 9 -63          <2018>   R9 = 0                                          -- It's Const#63
	  +234F: 81 02 02 00   line#466  LOADK 10 -9          <2019>   R10 = 1                                         -- It's Const#9
	  +2353: C1 82 0F 00   line#466  LOADK 11 -63         <2020>   R11 = 0                                         -- It's Const#63
	  +2357: 01 83 0F 00   line#466  LOADK 12 -63         <2021>   R12 = 0                                         -- It's Const#63
	  +235B: 24 80 80 06   line#466  CALL 0 13 2          <2022>   R0 = R0(R1,..,R12)
	  +235F: 08 00 80 88   line#466  SETTABUP 0 -18 0     <2023>   Upv#1@_ENV["CFrameQuest"] = R0                  -- It's Const#18
	  +2363: 1E 80 66 80   line#466  JMP 0 411            <2024>   GOTO <2436>
	  +2367: 06 00 40 00   line#467  GETTABUP 0 0 -1      <2025>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +236B: 41 40 80 00   line#467  LOADK 1 -514         <2026>   R1 = 2050                                       -- It's Const#514
	  +236F: 5F 40 00 00   line#467  EQ 1 0 1             <2027>   if R0 ~= R1 then GOTO <2029>
	  +2373: 1E C0 00 80   line#467  JMP 0 4              <2028>   GOTO <2033>
	  +2377: 06 00 40 00   line#467  GETTABUP 0 0 -1      <2029>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +237B: 41 80 80 00   line#467  LOADK 1 -515         <2030>   R1 = 2074                                       -- It's Const#515
	  +237F: 21 40 00 00   line#467  LE 0 0 1             <2031>   if R0 <= R1 then GOTO <2033>
	  +2383: 1E C0 05 80   line#467  JMP 0 24             <2032>   GOTO <2057>
	  +2387: 01 C0 80 00   line#468  LOADK 0 -516         <2033>   R0 = "Posessed Mummy [Lv. 2050]"                -- It's Const#516
	  +238B: 08 00 00 85   line#468  SETTABUP 0 -11 0     <2034>   Upv#1@_ENV["Mon"] = R0                          -- It's Const#11
	  +238F: 08 40 4D 86   line#469  SETTABUP 0 -13 -54   <2035>   Upv#1@_ENV["LQuest"] = 2                        -- It's Const#13, Const#54
	  +2393: 01 00 7F 00   line#470  LOADK 0 -509         <2036>   R0 = "HauntedQuest2"                            -- It's Const#509
	  +2397: 08 00 80 86   line#470  SETTABUP 0 -14 0     <2037>   Upv#1@_ENV["NQuest"] = R0                       -- It's Const#14
	  +239B: 01 00 81 00   line#471  LOADK 0 -517         <2038>   R0 = "Posessed Mummy"                           -- It's Const#517
	  +239F: 08 00 80 87   line#471  SETTABUP 0 -16 0     <2039>   Upv#1@_ENV["NameMon"] = R0                      -- It's Const#16
	  +23A3: 06 00 4E 00   line#472  GETTABUP 0 0 -57     <2040>   R0 = Upv#1@_ENV["CFrame"]                       -- It's Const#57
	  +23A7: 07 40 4E 00   line#472  GETTABLE 0 0 -58     <2041>   R0 = R0["new"]                                  -- It's Const#58
	  +23AB: 41 80 7F 00   line#472  LOADK 1 -511         <2042>   R1 = (-9516.99316)                              -- It's Const#511
	  +23AF: 81 C0 7F 00   line#472  LOADK 2 -512         <2043>   R2 = 172.017181                                 -- It's Const#512
	  +23B3: C1 00 80 00   line#472  LOADK 3 -513         <2044>   R3 = 6078.46533                                 -- It's Const#513
	  +23B7: 01 81 0F 00   line#472  LOADK 4 -63          <2045>   R4 = 0                                          -- It's Const#63
	  +23BB: 41 81 0F 00   line#472  LOADK 5 -63          <2046>   R5 = 0                                          -- It's Const#63
	  +23BF: 81 C1 08 00   line#472  LOADK 6 -36          <2047>   R6 = (-1)                                       -- It's Const#36
	  +23C3: C1 81 0F 00   line#472  LOADK 7 -63          <2048>   R7 = 0                                          -- It's Const#63
	  +23C7: 01 02 02 00   line#472  LOADK 8 -9           <2049>   R8 = 1                                          -- It's Const#9
	  +23CB: 41 82 0F 00   line#472  LOADK 9 -63          <2050>   R9 = 0                                          -- It's Const#63
	  +23CF: 81 02 02 00   line#472  LOADK 10 -9          <2051>   R10 = 1                                         -- It's Const#9
	  +23D3: C1 82 0F 00   line#472  LOADK 11 -63         <2052>   R11 = 0                                         -- It's Const#63
	  +23D7: 01 83 0F 00   line#472  LOADK 12 -63         <2053>   R12 = 0                                         -- It's Const#63
	  +23DB: 24 80 80 06   line#472  CALL 0 13 2          <2054>   R0 = R0(R1,..,R12)
	  +23DF: 08 00 80 88   line#472  SETTABUP 0 -18 0     <2055>   Upv#1@_ENV["CFrameQuest"] = R0                  -- It's Const#18
	  +23E3: 1E 80 5E 80   line#472  JMP 0 379            <2056>   GOTO <2436>
	  +23E7: 06 00 40 00   line#473  GETTABUP 0 0 -1      <2057>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +23EB: 41 40 81 00   line#473  LOADK 1 -518         <2058>   R1 = 2075                                       -- It's Const#518
	  +23EF: 5F 40 00 00   line#473  EQ 1 0 1             <2059>   if R0 ~= R1 then GOTO <2061>
	  +23F3: 1E C0 00 80   line#473  JMP 0 4              <2060>   GOTO <2065>
	  +23F7: 06 00 40 00   line#473  GETTABUP 0 0 -1      <2061>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +23FB: 41 80 81 00   line#473  LOADK 1 -519         <2062>   R1 = 2099                                       -- It's Const#519
	  +23FF: 21 40 00 00   line#473  LE 0 0 1             <2063>   if R0 <= R1 then GOTO <2065>
	  +2403: 1E C0 05 80   line#473  JMP 0 24             <2064>   GOTO <2089>
	  +2407: 01 C0 81 00   line#474  LOADK 0 -520         <2065>   R0 = "Peanut Scout [Lv. 2075]"                  -- It's Const#520
	  +240B: 08 00 00 85   line#474  SETTABUP 0 -11 0     <2066>   Upv#1@_ENV["Mon"] = R0                          -- It's Const#11
	  +240F: 08 00 42 86   line#475  SETTABUP 0 -13 -9    <2067>   Upv#1@_ENV["LQuest"] = 1                        -- It's Const#13, Const#9
	  +2413: 01 00 82 00   line#476  LOADK 0 -521         <2068>   R0 = "NutsIslandQuest"                          -- It's Const#521
	  +2417: 08 00 80 86   line#476  SETTABUP 0 -14 0     <2069>   Upv#1@_ENV["NQuest"] = R0                       -- It's Const#14
	  +241B: 01 40 82 00   line#477  LOADK 0 -522         <2070>   R0 = "Peanut Scout"                             -- It's Const#522
	  +241F: 08 00 80 87   line#477  SETTABUP 0 -16 0     <2071>   Upv#1@_ENV["NameMon"] = R0                      -- It's Const#16
	  +2423: 06 00 4E 00   line#478  GETTABUP 0 0 -57     <2072>   R0 = Upv#1@_ENV["CFrame"]                       -- It's Const#57
	  +2427: 07 40 4E 00   line#478  GETTABLE 0 0 -58     <2073>   R0 = R0["new"]                                  -- It's Const#58
	  +242B: 41 80 82 00   line#478  LOADK 1 -523         <2074>   R1 = (-2104.3908691406)                         -- It's Const#523
	  +242F: 81 C0 82 00   line#478  LOADK 2 -524         <2075>   R2 = 38.104167938232                            -- It's Const#524
	  +2433: C1 00 83 00   line#478  LOADK 3 -525         <2076>   R3 = (-326215/32)                               -- It's Const#525
	  +2437: 01 81 0F 00   line#478  LOADK 4 -63          <2077>   R4 = 0                                          -- It's Const#63
	  +243B: 41 81 0F 00   line#478  LOADK 5 -63          <2078>   R5 = 0                                          -- It's Const#63
	  +243F: 81 C1 08 00   line#478  LOADK 6 -36          <2079>   R6 = (-1)                                       -- It's Const#36
	  +2443: C1 81 0F 00   line#478  LOADK 7 -63          <2080>   R7 = 0                                          -- It's Const#63
	  +2447: 01 02 02 00   line#478  LOADK 8 -9           <2081>   R8 = 1                                          -- It's Const#9
	  +244B: 41 82 0F 00   line#478  LOADK 9 -63          <2082>   R9 = 0                                          -- It's Const#63
	  +244F: 81 02 02 00   line#478  LOADK 10 -9          <2083>   R10 = 1                                         -- It's Const#9
	  +2453: C1 82 0F 00   line#478  LOADK 11 -63         <2084>   R11 = 0                                         -- It's Const#63
	  +2457: 01 83 0F 00   line#478  LOADK 12 -63         <2085>   R12 = 0                                         -- It's Const#63
	  +245B: 24 80 80 06   line#478  CALL 0 13 2          <2086>   R0 = R0(R1,..,R12)
	  +245F: 08 00 80 88   line#478  SETTABUP 0 -18 0     <2087>   Upv#1@_ENV["CFrameQuest"] = R0                  -- It's Const#18
	  +2463: 1E 80 56 80   line#478  JMP 0 347            <2088>   GOTO <2436>
	  +2467: 06 00 40 00   line#479  GETTABUP 0 0 -1      <2089>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +246B: 41 40 83 00   line#479  LOADK 1 -526         <2090>   R1 = 2100                                       -- It's Const#526
	  +246F: 5F 40 00 00   line#479  EQ 1 0 1             <2091>   if R0 ~= R1 then GOTO <2093>
	  +2473: 1E C0 00 80   line#479  JMP 0 4              <2092>   GOTO <2097>
	  +2477: 06 00 40 00   line#479  GETTABUP 0 0 -1      <2093>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +247B: 41 80 83 00   line#479  LOADK 1 -527         <2094>   R1 = 2124                                       -- It's Const#527
	  +247F: 21 40 00 00   line#479  LE 0 0 1             <2095>   if R0 <= R1 then GOTO <2097>
	  +2483: 1E C0 05 80   line#479  JMP 0 24             <2096>   GOTO <2121>
	  +2487: 01 C0 83 00   line#480  LOADK 0 -528         <2097>   R0 = "Peanut President [Lv. 2100]"              -- It's Const#528
	  +248B: 08 00 00 85   line#480  SETTABUP 0 -11 0     <2098>   Upv#1@_ENV["Mon"] = R0                          -- It's Const#11
	  +248F: 08 40 4D 86   line#481  SETTABUP 0 -13 -54   <2099>   Upv#1@_ENV["LQuest"] = 2                        -- It's Const#13, Const#54
	  +2493: 01 00 82 00   line#482  LOADK 0 -521         <2100>   R0 = "NutsIslandQuest"                          -- It's Const#521
	  +2497: 08 00 80 86   line#482  SETTABUP 0 -14 0     <2101>   Upv#1@_ENV["NQuest"] = R0                       -- It's Const#14
	  +249B: 01 00 84 00   line#483  LOADK 0 -529         <2102>   R0 = "Peanut President"                         -- It's Const#529
	  +249F: 08 00 80 87   line#483  SETTABUP 0 -16 0     <2103>   Upv#1@_ENV["NameMon"] = R0                      -- It's Const#16
	  +24A3: 06 00 4E 00   line#484  GETTABUP 0 0 -57     <2104>   R0 = Upv#1@_ENV["CFrame"]                       -- It's Const#57
	  +24A7: 07 40 4E 00   line#484  GETTABLE 0 0 -58     <2105>   R0 = R0["new"]                                  -- It's Const#58
	  +24AB: 41 80 82 00   line#484  LOADK 1 -523         <2106>   R1 = (-2104.3908691406)                         -- It's Const#523
	  +24AF: 81 C0 82 00   line#484  LOADK 2 -524         <2107>   R2 = 38.104167938232                            -- It's Const#524
	  +24B3: C1 00 83 00   line#484  LOADK 3 -525         <2108>   R3 = (-326215/32)                               -- It's Const#525
	  +24B7: 01 81 0F 00   line#484  LOADK 4 -63          <2109>   R4 = 0                                          -- It's Const#63
	  +24BB: 41 81 0F 00   line#484  LOADK 5 -63          <2110>   R5 = 0                                          -- It's Const#63
	  +24BF: 81 C1 08 00   line#484  LOADK 6 -36          <2111>   R6 = (-1)                                       -- It's Const#36
	  +24C3: C1 81 0F 00   line#484  LOADK 7 -63          <2112>   R7 = 0                                          -- It's Const#63
	  +24C7: 01 02 02 00   line#484  LOADK 8 -9           <2113>   R8 = 1                                          -- It's Const#9
	  +24CB: 41 82 0F 00   line#484  LOADK 9 -63          <2114>   R9 = 0                                          -- It's Const#63
	  +24CF: 81 02 02 00   line#484  LOADK 10 -9          <2115>   R10 = 1                                         -- It's Const#9
	  +24D3: C1 82 0F 00   line#484  LOADK 11 -63         <2116>   R11 = 0                                         -- It's Const#63
	  +24D7: 01 83 0F 00   line#484  LOADK 12 -63         <2117>   R12 = 0                                         -- It's Const#63
	  +24DB: 24 80 80 06   line#484  CALL 0 13 2          <2118>   R0 = R0(R1,..,R12)
	  +24DF: 08 00 80 88   line#484  SETTABUP 0 -18 0     <2119>   Upv#1@_ENV["CFrameQuest"] = R0                  -- It's Const#18
	  +24E3: 1E 80 4E 80   line#484  JMP 0 315            <2120>   GOTO <2436>
	  +24E7: 06 00 40 00   line#485  GETTABUP 0 0 -1      <2121>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +24EB: 41 40 84 00   line#485  LOADK 1 -530         <2122>   R1 = 2125                                       -- It's Const#530
	  +24EF: 5F 40 00 00   line#485  EQ 1 0 1             <2123>   if R0 ~= R1 then GOTO <2125>
	  +24F3: 1E C0 00 80   line#485  JMP 0 4              <2124>   GOTO <2129>
	  +24F7: 06 00 40 00   line#485  GETTABUP 0 0 -1      <2125>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +24FB: 41 80 84 00   line#485  LOADK 1 -531         <2126>   R1 = 2149                                       -- It's Const#531
	  +24FF: 21 40 00 00   line#485  LE 0 0 1             <2127>   if R0 <= R1 then GOTO <2129>
	  +2503: 1E C0 05 80   line#485  JMP 0 24             <2128>   GOTO <2153>
	  +2507: 01 C0 84 00   line#486  LOADK 0 -532         <2129>   R0 = "Ice Cream Chef [Lv. 2125]"                -- It's Const#532
	  +250B: 08 00 00 85   line#486  SETTABUP 0 -11 0     <2130>   Upv#1@_ENV["Mon"] = R0                          -- It's Const#11
	  +250F: 08 00 42 86   line#487  SETTABUP 0 -13 -9    <2131>   Upv#1@_ENV["LQuest"] = 1                        -- It's Const#13, Const#9
	  +2513: 01 00 85 00   line#488  LOADK 0 -533         <2132>   R0 = "IceCreamIslandQuest"                      -- It's Const#533
	  +2517: 08 00 80 86   line#488  SETTABUP 0 -14 0     <2133>   Upv#1@_ENV["NQuest"] = R0                       -- It's Const#14
	  +251B: 01 40 85 00   line#489  LOADK 0 -534         <2134>   R0 = "Ice Cream Chef"                           -- It's Const#534
	  +251F: 08 00 80 87   line#489  SETTABUP 0 -16 0     <2135>   Upv#1@_ENV["NameMon"] = R0                      -- It's Const#16
	  +2523: 06 00 4E 00   line#490  GETTABUP 0 0 -57     <2136>   R0 = Upv#1@_ENV["CFrame"]                       -- It's Const#57
	  +2527: 07 40 4E 00   line#490  GETTABLE 0 0 -58     <2137>   R0 = R0["new"]                                  -- It's Const#58
	  +252B: 41 80 85 00   line#490  LOADK 1 -535         <2138>   R1 = (-820.64825439453)                         -- It's Const#535
	  +252F: 81 C0 85 00   line#490  LOADK 2 -536         <2139>   R2 = 65.819526672363                            -- It's Const#536
	  +2533: C1 00 86 00   line#490  LOADK 3 -537         <2140>   R3 = (-10965.795898438)                         -- It's Const#537
	  +2537: 01 81 0F 00   line#490  LOADK 4 -63          <2141>   R4 = 0                                          -- It's Const#63
	  +253B: 41 81 0F 00   line#490  LOADK 5 -63          <2142>   R5 = 0                                          -- It's Const#63
	  +253F: 81 C1 08 00   line#490  LOADK 6 -36          <2143>   R6 = (-1)                                       -- It's Const#36
	  +2543: C1 81 0F 00   line#490  LOADK 7 -63          <2144>   R7 = 0                                          -- It's Const#63
	  +2547: 01 02 02 00   line#490  LOADK 8 -9           <2145>   R8 = 1                                          -- It's Const#9
	  +254B: 41 82 0F 00   line#490  LOADK 9 -63          <2146>   R9 = 0                                          -- It's Const#63
	  +254F: 81 02 02 00   line#490  LOADK 10 -9          <2147>   R10 = 1                                         -- It's Const#9
	  +2553: C1 82 0F 00   line#490  LOADK 11 -63         <2148>   R11 = 0                                         -- It's Const#63
	  +2557: 01 83 0F 00   line#490  LOADK 12 -63         <2149>   R12 = 0                                         -- It's Const#63
	  +255B: 24 80 80 06   line#490  CALL 0 13 2          <2150>   R0 = R0(R1,..,R12)
	  +255F: 08 00 80 88   line#490  SETTABUP 0 -18 0     <2151>   Upv#1@_ENV["CFrameQuest"] = R0                  -- It's Const#18
	  +2563: 1E 80 46 80   line#490  JMP 0 283            <2152>   GOTO <2436>
	  +2567: 06 00 40 00   line#491  GETTABUP 0 0 -1      <2153>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +256B: 41 40 86 00   line#491  LOADK 1 -538         <2154>   R1 = 2150                                       -- It's Const#538
	  +256F: 5F 40 00 00   line#491  EQ 1 0 1             <2155>   if R0 ~= R1 then GOTO <2157>
	  +2573: 1E C0 00 80   line#491  JMP 0 4              <2156>   GOTO <2161>
	  +2577: 06 00 40 00   line#491  GETTABUP 0 0 -1      <2157>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +257B: 41 80 86 00   line#491  LOADK 1 -539         <2158>   R1 = 2199                                       -- It's Const#539
	  +257F: 21 40 00 00   line#491  LE 0 0 1             <2159>   if R0 <= R1 then GOTO <2161>
	  +2583: 1E C0 05 80   line#491  JMP 0 24             <2160>   GOTO <2185>
	  +2587: 01 C0 86 00   line#492  LOADK 0 -540         <2161>   R0 = "Ice Cream Commander [Lv. 2150]"           -- It's Const#540
	  +258B: 08 00 00 85   line#492  SETTABUP 0 -11 0     <2162>   Upv#1@_ENV["Mon"] = R0                          -- It's Const#11
	  +258F: 08 40 4D 86   line#493  SETTABUP 0 -13 -54   <2163>   Upv#1@_ENV["LQuest"] = 2                        -- It's Const#13, Const#54
	  +2593: 01 00 85 00   line#494  LOADK 0 -533         <2164>   R0 = "IceCreamIslandQuest"                      -- It's Const#533
	  +2597: 08 00 80 86   line#494  SETTABUP 0 -14 0     <2165>   Upv#1@_ENV["NQuest"] = R0                       -- It's Const#14
	  +259B: 01 00 87 00   line#495  LOADK 0 -541         <2166>   R0 = "Ice Cream Commander"                      -- It's Const#541
	  +259F: 08 00 80 87   line#495  SETTABUP 0 -16 0     <2167>   Upv#1@_ENV["NameMon"] = R0                      -- It's Const#16
	  +25A3: 06 00 4E 00   line#496  GETTABUP 0 0 -57     <2168>   R0 = Upv#1@_ENV["CFrame"]                       -- It's Const#57
	  +25A7: 07 40 4E 00   line#496  GETTABLE 0 0 -58     <2169>   R0 = R0["new"]                                  -- It's Const#58
	  +25AB: 41 80 85 00   line#496  LOADK 1 -535         <2170>   R1 = (-820.64825439453)                         -- It's Const#535
	  +25AF: 81 C0 85 00   line#496  LOADK 2 -536         <2171>   R2 = 65.819526672363                            -- It's Const#536
	  +25B3: C1 00 86 00   line#496  LOADK 3 -537         <2172>   R3 = (-10965.795898438)                         -- It's Const#537
	  +25B7: 01 81 0F 00   line#496  LOADK 4 -63          <2173>   R4 = 0                                          -- It's Const#63
	  +25BB: 41 81 0F 00   line#496  LOADK 5 -63          <2174>   R5 = 0                                          -- It's Const#63
	  +25BF: 81 C1 08 00   line#496  LOADK 6 -36          <2175>   R6 = (-1)                                       -- It's Const#36
	  +25C3: C1 81 0F 00   line#496  LOADK 7 -63          <2176>   R7 = 0                                          -- It's Const#63
	  +25C7: 01 02 02 00   line#496  LOADK 8 -9           <2177>   R8 = 1                                          -- It's Const#9
	  +25CB: 41 82 0F 00   line#496  LOADK 9 -63          <2178>   R9 = 0                                          -- It's Const#63
	  +25CF: 81 02 02 00   line#496  LOADK 10 -9          <2179>   R10 = 1                                         -- It's Const#9
	  +25D3: C1 82 0F 00   line#496  LOADK 11 -63         <2180>   R11 = 0                                         -- It's Const#63
	  +25D7: 01 83 0F 00   line#496  LOADK 12 -63         <2181>   R12 = 0                                         -- It's Const#63
	  +25DB: 24 80 80 06   line#496  CALL 0 13 2          <2182>   R0 = R0(R1,..,R12)
	  +25DF: 08 00 80 88   line#496  SETTABUP 0 -18 0     <2183>   Upv#1@_ENV["CFrameQuest"] = R0                  -- It's Const#18
	  +25E3: 1E 80 3E 80   line#496  JMP 0 251            <2184>   GOTO <2436>
	  +25E7: 06 00 40 00   line#497  GETTABUP 0 0 -1      <2185>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +25EB: 41 40 87 00   line#497  LOADK 1 -542         <2186>   R1 = 2200                                       -- It's Const#542
	  +25EF: 5F 40 00 00   line#497  EQ 1 0 1             <2187>   if R0 ~= R1 then GOTO <2189>
	  +25F3: 1E C0 00 80   line#497  JMP 0 4              <2188>   GOTO <2193>
	  +25F7: 06 00 40 00   line#497  GETTABUP 0 0 -1      <2189>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +25FB: 41 80 87 00   line#497  LOADK 1 -543         <2190>   R1 = 2224                                       -- It's Const#543
	  +25FF: 21 40 00 00   line#497  LE 0 0 1             <2191>   if R0 <= R1 then GOTO <2193>
	  +2603: 1E C0 05 80   line#497  JMP 0 24             <2192>   GOTO <2217>
	  +2607: 01 C0 87 00   line#498  LOADK 0 -544         <2193>   R0 = "Cookie Crafter [Lv. 2200]"                -- It's Const#544
	  +260B: 08 00 00 85   line#498  SETTABUP 0 -11 0     <2194>   Upv#1@_ENV["Mon"] = R0                          -- It's Const#11
	  +260F: 08 00 42 86   line#499  SETTABUP 0 -13 -9    <2195>   Upv#1@_ENV["LQuest"] = 1                        -- It's Const#13, Const#9
	  +2613: 01 00 88 00   line#500  LOADK 0 -545         <2196>   R0 = "CakeQuest1"                               -- It's Const#545
	  +2617: 08 00 80 86   line#500  SETTABUP 0 -14 0     <2197>   Upv#1@_ENV["NQuest"] = R0                       -- It's Const#14
	  +261B: 01 40 88 00   line#501  LOADK 0 -546         <2198>   R0 = "Cookie Crafter"                           -- It's Const#546
	  +261F: 08 00 80 87   line#501  SETTABUP 0 -16 0     <2199>   Upv#1@_ENV["NameMon"] = R0                      -- It's Const#16
	  +2623: 06 00 4E 00   line#502  GETTABUP 0 0 -57     <2200>   R0 = Upv#1@_ENV["CFrame"]                       -- It's Const#57
	  +2627: 07 40 4E 00   line#502  GETTABLE 0 0 -58     <2201>   R0 = R0["new"]                                  -- It's Const#58
	  +262B: 41 80 88 00   line#502  LOADK 1 -547         <2202>   R1 = (-2021.32007)                              -- It's Const#547
	  +262F: 81 C0 88 00   line#502  LOADK 2 -548         <2203>   R2 = 37.7982254                                 -- It's Const#548
	  +2633: C1 00 89 00   line#502  LOADK 3 -549         <2204>   R3 = (-12028.7295)                              -- It's Const#549
	  +2637: 01 41 89 00   line#502  LOADK 4 -550         <2205>   R4 = 0.957576931                                -- It's Const#550
	  +263B: 41 81 89 00   line#502  LOADK 5 -551         <2206>   R5 = (-8.80302053e-008)                         -- It's Const#551
	  +263F: 81 C1 89 00   line#502  LOADK 6 -552         <2207>   R6 = 0.288177818                                -- It's Const#552
	  +2643: C1 01 8A 00   line#502  LOADK 7 -553         <2208>   R7 = 6.9301187e-008                             -- It's Const#553
	  +2647: 01 02 02 00   line#502  LOADK 8 -9           <2209>   R8 = 1                                          -- It's Const#9
	  +264B: 41 42 8A 00   line#502  LOADK 9 -554         <2210>   R9 = 7.51931211e-008                            -- It's Const#554
	  +264F: 81 82 8A 00   line#502  LOADK 10 -555        <2211>   R10 = (-0.288177818)                            -- It's Const#555
	  +2653: C1 C2 8A 00   line#502  LOADK 11 -556        <2212>   R11 = (-5.2032135e-008)                         -- It's Const#556
	  +2657: 01 43 89 00   line#502  LOADK 12 -550        <2213>   R12 = 0.957576931                               -- It's Const#550
	  +265B: 24 80 80 06   line#502  CALL 0 13 2          <2214>   R0 = R0(R1,..,R12)
	  +265F: 08 00 80 88   line#502  SETTABUP 0 -18 0     <2215>   Upv#1@_ENV["CFrameQuest"] = R0                  -- It's Const#18
	  +2663: 1E 80 36 80   line#502  JMP 0 219            <2216>   GOTO <2436>
	  +2667: 06 00 40 00   line#503  GETTABUP 0 0 -1      <2217>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +266B: 41 00 8B 00   line#503  LOADK 1 -557         <2218>   R1 = 2225                                       -- It's Const#557
	  +266F: 5F 40 00 00   line#503  EQ 1 0 1             <2219>   if R0 ~= R1 then GOTO <2221>
	  +2673: 1E C0 00 80   line#503  JMP 0 4              <2220>   GOTO <2225>
	  +2677: 06 00 40 00   line#503  GETTABUP 0 0 -1      <2221>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +267B: 41 40 8B 00   line#503  LOADK 1 -558         <2222>   R1 = 2249                                       -- It's Const#558
	  +267F: 21 40 00 00   line#503  LE 0 0 1             <2223>   if R0 <= R1 then GOTO <2225>
	  +2683: 1E C0 05 80   line#503  JMP 0 24             <2224>   GOTO <2249>
	  +2687: 01 80 8B 00   line#504  LOADK 0 -559         <2225>   R0 = "Cake Guard [Lv. 2225]"                    -- It's Const#559
	  +268B: 08 00 00 85   line#504  SETTABUP 0 -11 0     <2226>   Upv#1@_ENV["Mon"] = R0                          -- It's Const#11
	  +268F: 08 40 4D 86   line#505  SETTABUP 0 -13 -54   <2227>   Upv#1@_ENV["LQuest"] = 2                        -- It's Const#13, Const#54
	  +2693: 01 00 88 00   line#506  LOADK 0 -545         <2228>   R0 = "CakeQuest1"                               -- It's Const#545
	  +2697: 08 00 80 86   line#506  SETTABUP 0 -14 0     <2229>   Upv#1@_ENV["NQuest"] = R0                       -- It's Const#14
	  +269B: 01 C0 8B 00   line#507  LOADK 0 -560         <2230>   R0 = "Cake Guard"                               -- It's Const#560
	  +269F: 08 00 80 87   line#507  SETTABUP 0 -16 0     <2231>   Upv#1@_ENV["NameMon"] = R0                      -- It's Const#16
	  +26A3: 06 00 4E 00   line#508  GETTABUP 0 0 -57     <2232>   R0 = Upv#1@_ENV["CFrame"]                       -- It's Const#57
	  +26A7: 07 40 4E 00   line#508  GETTABLE 0 0 -58     <2233>   R0 = R0["new"]                                  -- It's Const#58
	  +26AB: 41 80 88 00   line#508  LOADK 1 -547         <2234>   R1 = (-2021.32007)                              -- It's Const#547
	  +26AF: 81 C0 88 00   line#508  LOADK 2 -548         <2235>   R2 = 37.7982254                                 -- It's Const#548
	  +26B3: C1 00 89 00   line#508  LOADK 3 -549         <2236>   R3 = (-12028.7295)                              -- It's Const#549
	  +26B7: 01 41 89 00   line#508  LOADK 4 -550         <2237>   R4 = 0.957576931                                -- It's Const#550
	  +26BB: 41 81 89 00   line#508  LOADK 5 -551         <2238>   R5 = (-8.80302053e-008)                         -- It's Const#551
	  +26BF: 81 C1 89 00   line#508  LOADK 6 -552         <2239>   R6 = 0.288177818                                -- It's Const#552
	  +26C3: C1 01 8A 00   line#508  LOADK 7 -553         <2240>   R7 = 6.9301187e-008                             -- It's Const#553
	  +26C7: 01 02 02 00   line#508  LOADK 8 -9           <2241>   R8 = 1                                          -- It's Const#9
	  +26CB: 41 42 8A 00   line#508  LOADK 9 -554         <2242>   R9 = 7.51931211e-008                            -- It's Const#554
	  +26CF: 81 82 8A 00   line#508  LOADK 10 -555        <2243>   R10 = (-0.288177818)                            -- It's Const#555
	  +26D3: C1 C2 8A 00   line#508  LOADK 11 -556        <2244>   R11 = (-5.2032135e-008)                         -- It's Const#556
	  +26D7: 01 43 89 00   line#508  LOADK 12 -550        <2245>   R12 = 0.957576931                               -- It's Const#550
	  +26DB: 24 80 80 06   line#508  CALL 0 13 2          <2246>   R0 = R0(R1,..,R12)
	  +26DF: 08 00 80 88   line#508  SETTABUP 0 -18 0     <2247>   Upv#1@_ENV["CFrameQuest"] = R0                  -- It's Const#18
	  +26E3: 1E 80 2E 80   line#508  JMP 0 187            <2248>   GOTO <2436>
	  +26E7: 06 00 40 00   line#509  GETTABUP 0 0 -1      <2249>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +26EB: 41 00 8C 00   line#509  LOADK 1 -561         <2250>   R1 = 2250                                       -- It's Const#561
	  +26EF: 5F 40 00 00   line#509  EQ 1 0 1             <2251>   if R0 ~= R1 then GOTO <2253>
	  +26F3: 1E C0 00 80   line#509  JMP 0 4              <2252>   GOTO <2257>
	  +26F7: 06 00 40 00   line#509  GETTABUP 0 0 -1      <2253>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +26FB: 41 40 8C 00   line#509  LOADK 1 -562         <2254>   R1 = 2274                                       -- It's Const#562
	  +26FF: 21 40 00 00   line#509  LE 0 0 1             <2255>   if R0 <= R1 then GOTO <2257>
	  +2703: 1E C0 05 80   line#509  JMP 0 24             <2256>   GOTO <2281>
	  +2707: 01 80 8C 00   line#510  LOADK 0 -563         <2257>   R0 = "Baking Staff [Lv. 2250]"                  -- It's Const#563
	  +270B: 08 00 00 85   line#510  SETTABUP 0 -11 0     <2258>   Upv#1@_ENV["Mon"] = R0                          -- It's Const#11
	  +270F: 08 00 42 86   line#511  SETTABUP 0 -13 -9    <2259>   Upv#1@_ENV["LQuest"] = 1                        -- It's Const#13, Const#9
	  +2713: 01 C0 8C 00   line#512  LOADK 0 -564         <2260>   R0 = "CakeQuest2"                               -- It's Const#564
	  +2717: 08 00 80 86   line#512  SETTABUP 0 -14 0     <2261>   Upv#1@_ENV["NQuest"] = R0                       -- It's Const#14
	  +271B: 01 00 8D 00   line#513  LOADK 0 -565         <2262>   R0 = "Baking Staff"                             -- It's Const#565
	  +271F: 08 00 80 87   line#513  SETTABUP 0 -16 0     <2263>   Upv#1@_ENV["NameMon"] = R0                      -- It's Const#16
	  +2723: 06 00 4E 00   line#514  GETTABUP 0 0 -57     <2264>   R0 = Upv#1@_ENV["CFrame"]                       -- It's Const#57
	  +2727: 07 40 4E 00   line#514  GETTABLE 0 0 -58     <2265>   R0 = R0["new"]                                  -- It's Const#58
	  +272B: 41 40 8D 00   line#514  LOADK 1 -566         <2266>   R1 = (-1927.91602)                              -- It's Const#566
	  +272F: 81 80 8D 00   line#514  LOADK 2 -567         <2267>   R2 = 37.7981339                                 -- It's Const#567
	  +2733: C1 C0 8D 00   line#514  LOADK 3 -568         <2268>   R3 = (-12842.5391)                              -- It's Const#568
	  +2737: 01 01 8E 00   line#514  LOADK 4 -569         <2269>   R4 = (-0.96804446)                              -- It's Const#569
	  +273B: 41 41 8E 00   line#514  LOADK 5 -570         <2270>   R5 = 4.22142143e-008                            -- It's Const#570
	  +273F: 81 81 8E 00   line#514  LOADK 6 -571         <2271>   R6 = 0.250778586                                -- It's Const#571
	  +2743: C1 C1 8E 00   line#514  LOADK 7 -572         <2272>   R7 = 4.74911062e-008                            -- It's Const#572
	  +2747: 01 02 02 00   line#514  LOADK 8 -9           <2273>   R8 = 1                                          -- It's Const#9
	  +274B: 41 02 8F 00   line#514  LOADK 9 -573         <2274>   R9 = 1.49904711e-008                            -- It's Const#573
	  +274F: 81 42 8F 00   line#514  LOADK 10 -574        <2275>   R10 = (-0.250778586)                            -- It's Const#574
	  +2753: C1 82 8F 00   line#514  LOADK 11 -575        <2276>   R11 = 2.64211941e-008                           -- It's Const#575
	  +2757: 01 03 8E 00   line#514  LOADK 12 -569        <2277>   R12 = (-0.96804446)                             -- It's Const#569
	  +275B: 24 80 80 06   line#514  CALL 0 13 2          <2278>   R0 = R0(R1,..,R12)
	  +275F: 08 00 80 88   line#514  SETTABUP 0 -18 0     <2279>   Upv#1@_ENV["CFrameQuest"] = R0                  -- It's Const#18
	  +2763: 1E 80 26 80   line#514  JMP 0 155            <2280>   GOTO <2436>
	  +2767: 06 00 40 00   line#515  GETTABUP 0 0 -1      <2281>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +276B: 41 C0 8F 00   line#515  LOADK 1 -576         <2282>   R1 = 2275                                       -- It's Const#576
	  +276F: 5F 40 00 00   line#515  EQ 1 0 1             <2283>   if R0 ~= R1 then GOTO <2285>
	  +2773: 1E C0 00 80   line#515  JMP 0 4              <2284>   GOTO <2289>
	  +2777: 06 00 40 00   line#515  GETTABUP 0 0 -1      <2285>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +277B: 41 00 90 00   line#515  LOADK 1 -577         <2286>   R1 = 2299                                       -- It's Const#577
	  +277F: 21 40 00 00   line#515  LE 0 0 1             <2287>   if R0 <= R1 then GOTO <2289>
	  +2783: 1E C0 05 80   line#515  JMP 0 24             <2288>   GOTO <2313>
	  +2787: 01 40 90 00   line#516  LOADK 0 -578         <2289>   R0 = "Head Baker [Lv. 2275]"                    -- It's Const#578
	  +278B: 08 00 00 85   line#516  SETTABUP 0 -11 0     <2290>   Upv#1@_ENV["Mon"] = R0                          -- It's Const#11
	  +278F: 08 40 4D 86   line#517  SETTABUP 0 -13 -54   <2291>   Upv#1@_ENV["LQuest"] = 2                        -- It's Const#13, Const#54
	  +2793: 01 C0 8C 00   line#518  LOADK 0 -564         <2292>   R0 = "CakeQuest2"                               -- It's Const#564
	  +2797: 08 00 80 86   line#518  SETTABUP 0 -14 0     <2293>   Upv#1@_ENV["NQuest"] = R0                       -- It's Const#14
	  +279B: 01 80 90 00   line#519  LOADK 0 -579         <2294>   R0 = "Head Baker"                               -- It's Const#579
	  +279F: 08 00 80 87   line#519  SETTABUP 0 -16 0     <2295>   Upv#1@_ENV["NameMon"] = R0                      -- It's Const#16
	  +27A3: 06 00 4E 00   line#520  GETTABUP 0 0 -57     <2296>   R0 = Upv#1@_ENV["CFrame"]                       -- It's Const#57
	  +27A7: 07 40 4E 00   line#520  GETTABLE 0 0 -58     <2297>   R0 = R0["new"]                                  -- It's Const#58
	  +27AB: 41 40 8D 00   line#520  LOADK 1 -566         <2298>   R1 = (-1927.91602)                              -- It's Const#566
	  +27AF: 81 80 8D 00   line#520  LOADK 2 -567         <2299>   R2 = 37.7981339                                 -- It's Const#567
	  +27B3: C1 C0 8D 00   line#520  LOADK 3 -568         <2300>   R3 = (-12842.5391)                              -- It's Const#568
	  +27B7: 01 01 8E 00   line#520  LOADK 4 -569         <2301>   R4 = (-0.96804446)                              -- It's Const#569
	  +27BB: 41 41 8E 00   line#520  LOADK 5 -570         <2302>   R5 = 4.22142143e-008                            -- It's Const#570
	  +27BF: 81 81 8E 00   line#520  LOADK 6 -571         <2303>   R6 = 0.250778586                                -- It's Const#571
	  +27C3: C1 C1 8E 00   line#520  LOADK 7 -572         <2304>   R7 = 4.74911062e-008                            -- It's Const#572
	  +27C7: 01 02 02 00   line#520  LOADK 8 -9           <2305>   R8 = 1                                          -- It's Const#9
	  +27CB: 41 02 8F 00   line#520  LOADK 9 -573         <2306>   R9 = 1.49904711e-008                            -- It's Const#573
	  +27CF: 81 42 8F 00   line#520  LOADK 10 -574        <2307>   R10 = (-0.250778586)                            -- It's Const#574
	  +27D3: C1 82 8F 00   line#520  LOADK 11 -575        <2308>   R11 = 2.64211941e-008                           -- It's Const#575
	  +27D7: 01 03 8E 00   line#520  LOADK 12 -569        <2309>   R12 = (-0.96804446)                             -- It's Const#569
	  +27DB: 24 80 80 06   line#520  CALL 0 13 2          <2310>   R0 = R0(R1,..,R12)
	  +27DF: 08 00 80 88   line#520  SETTABUP 0 -18 0     <2311>   Upv#1@_ENV["CFrameQuest"] = R0                  -- It's Const#18
	  +27E3: 1E 80 1E 80   line#520  JMP 0 123            <2312>   GOTO <2436>
	  +27E7: 06 00 40 00   line#521  GETTABUP 0 0 -1      <2313>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +27EB: 41 C0 90 00   line#521  LOADK 1 -580         <2314>   R1 = 2300                                       -- It's Const#580
	  +27EF: 5F 40 00 00   line#521  EQ 1 0 1             <2315>   if R0 ~= R1 then GOTO <2317>
	  +27F3: 1E C0 00 80   line#521  JMP 0 4              <2316>   GOTO <2321>
	  +27F7: 06 00 40 00   line#521  GETTABUP 0 0 -1      <2317>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +27FB: 41 00 91 00   line#521  LOADK 1 -581         <2318>   R1 = 2324                                       -- It's Const#581
	  +27FF: 21 40 00 00   line#521  LE 0 0 1             <2319>   if R0 <= R1 then GOTO <2321>
	  +2803: 1E C0 05 80   line#521  JMP 0 24             <2320>   GOTO <2345>
	  +2807: 01 40 91 00   line#522  LOADK 0 -582         <2321>   R0 = "Cocoa Warrior [Lv. 2300]"                 -- It's Const#582
	  +280B: 08 00 00 85   line#522  SETTABUP 0 -11 0     <2322>   Upv#1@_ENV["Mon"] = R0                          -- It's Const#11
	  +280F: 08 00 42 86   line#523  SETTABUP 0 -13 -9    <2323>   Upv#1@_ENV["LQuest"] = 1                        -- It's Const#13, Const#9
	  +2813: 01 80 91 00   line#524  LOADK 0 -583         <2324>   R0 = "ChocQuest1"                               -- It's Const#583
	  +2817: 08 00 80 86   line#524  SETTABUP 0 -14 0     <2325>   Upv#1@_ENV["NQuest"] = R0                       -- It's Const#14
	  +281B: 01 C0 91 00   line#525  LOADK 0 -584         <2326>   R0 = "Cocoa Warrior"                            -- It's Const#584
	  +281F: 08 00 80 87   line#525  SETTABUP 0 -16 0     <2327>   Upv#1@_ENV["NameMon"] = R0                      -- It's Const#16
	  +2823: 06 00 4E 00   line#526  GETTABUP 0 0 -57     <2328>   R0 = Upv#1@_ENV["CFrame"]                       -- It's Const#57
	  +2827: 07 40 4E 00   line#526  GETTABLE 0 0 -58     <2329>   R0 = R0["new"]                                  -- It's Const#58
	  +282B: 41 00 92 00   line#526  LOADK 1 -585         <2330>   R1 = 231.742981                                 -- It's Const#585
	  +282F: 81 40 92 00   line#526  LOADK 2 -586         <2331>   R2 = 25.3354111                                 -- It's Const#586
	  +2833: C1 80 92 00   line#526  LOADK 3 -587         <2332>   R3 = (-12199.0537)                              -- It's Const#587
	  +2837: 01 C1 92 00   line#526  LOADK 4 -588         <2333>   R4 = 0.998278677                                -- It's Const#588
	  +283B: 41 01 93 00   line#526  LOADK 5 -589         <2334>   R5 = (-5.16006757e-008)                         -- It's Const#589
	  +283F: 81 41 93 00   line#526  LOADK 6 -590         <2335>   R6 = 0.0586484075                               -- It's Const#590
	  +2843: C1 81 93 00   line#526  LOADK 7 -591         <2336>   R7 = 4.79685092e-008                            -- It's Const#591
	  +2847: 01 02 02 00   line#526  LOADK 8 -9           <2337>   R8 = 1                                          -- It's Const#9
	  +284B: 41 C2 93 00   line#526  LOADK 9 -592         <2338>   R9 = 6.33390442e-008                            -- It's Const#592
	  +284F: 81 02 94 00   line#526  LOADK 10 -593        <2339>   R10 = (-0.0586484075)                           -- It's Const#593
	  +2853: C1 42 94 00   line#526  LOADK 11 -594        <2340>   R11 = (-6.04167383e-008)                        -- It's Const#594
	  +2857: 01 C3 92 00   line#526  LOADK 12 -588        <2341>   R12 = 0.998278677                               -- It's Const#588
	  +285B: 24 80 80 06   line#526  CALL 0 13 2          <2342>   R0 = R0(R1,..,R12)
	  +285F: 08 00 80 88   line#526  SETTABUP 0 -18 0     <2343>   Upv#1@_ENV["CFrameQuest"] = R0                  -- It's Const#18
	  +2863: 1E 80 16 80   line#526  JMP 0 91             <2344>   GOTO <2436>
	  +2867: 06 00 40 00   line#527  GETTABUP 0 0 -1      <2345>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +286B: 41 80 94 00   line#527  LOADK 1 -595         <2346>   R1 = 2325                                       -- It's Const#595
	  +286F: 5F 40 00 00   line#527  EQ 1 0 1             <2347>   if R0 ~= R1 then GOTO <2349>
	  +2873: 1E C0 00 80   line#527  JMP 0 4              <2348>   GOTO <2353>
	  +2877: 06 00 40 00   line#527  GETTABUP 0 0 -1      <2349>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +287B: 41 C0 94 00   line#527  LOADK 1 -596         <2350>   R1 = 2349                                       -- It's Const#596
	  +287F: 21 40 00 00   line#527  LE 0 0 1             <2351>   if R0 <= R1 then GOTO <2353>
	  +2883: 1E C0 05 80   line#527  JMP 0 24             <2352>   GOTO <2377>
	  +2887: 01 00 95 00   line#528  LOADK 0 -597         <2353>   R0 = "Chocolate Bar Battler [Lv. 2325]"         -- It's Const#597
	  +288B: 08 00 00 85   line#528  SETTABUP 0 -11 0     <2354>   Upv#1@_ENV["Mon"] = R0                          -- It's Const#11
	  +288F: 08 40 4D 86   line#529  SETTABUP 0 -13 -54   <2355>   Upv#1@_ENV["LQuest"] = 2                        -- It's Const#13, Const#54
	  +2893: 01 80 91 00   line#530  LOADK 0 -583         <2356>   R0 = "ChocQuest1"                               -- It's Const#583
	  +2897: 08 00 80 86   line#530  SETTABUP 0 -14 0     <2357>   Upv#1@_ENV["NQuest"] = R0                       -- It's Const#14
	  +289B: 01 40 95 00   line#531  LOADK 0 -598         <2358>   R0 = "Chocolate Bar Battler"                    -- It's Const#598
	  +289F: 08 00 80 87   line#531  SETTABUP 0 -16 0     <2359>   Upv#1@_ENV["NameMon"] = R0                      -- It's Const#16
	  +28A3: 06 00 4E 00   line#532  GETTABUP 0 0 -57     <2360>   R0 = Upv#1@_ENV["CFrame"]                       -- It's Const#57
	  +28A7: 07 40 4E 00   line#532  GETTABLE 0 0 -58     <2361>   R0 = R0["new"]                                  -- It's Const#58
	  +28AB: 41 00 92 00   line#532  LOADK 1 -585         <2362>   R1 = 231.742981                                 -- It's Const#585
	  +28AF: 81 40 92 00   line#532  LOADK 2 -586         <2363>   R2 = 25.3354111                                 -- It's Const#586
	  +28B3: C1 80 92 00   line#532  LOADK 3 -587         <2364>   R3 = (-12199.0537)                              -- It's Const#587
	  +28B7: 01 C1 92 00   line#532  LOADK 4 -588         <2365>   R4 = 0.998278677                                -- It's Const#588
	  +28BB: 41 01 93 00   line#532  LOADK 5 -589         <2366>   R5 = (-5.16006757e-008)                         -- It's Const#589
	  +28BF: 81 41 93 00   line#532  LOADK 6 -590         <2367>   R6 = 0.0586484075                               -- It's Const#590
	  +28C3: C1 81 93 00   line#532  LOADK 7 -591         <2368>   R7 = 4.79685092e-008                            -- It's Const#591
	  +28C7: 01 02 02 00   line#532  LOADK 8 -9           <2369>   R8 = 1                                          -- It's Const#9
	  +28CB: 41 C2 93 00   line#532  LOADK 9 -592         <2370>   R9 = 6.33390442e-008                            -- It's Const#592
	  +28CF: 81 02 94 00   line#532  LOADK 10 -593        <2371>   R10 = (-0.0586484075)                           -- It's Const#593
	  +28D3: C1 42 94 00   line#532  LOADK 11 -594        <2372>   R11 = (-6.04167383e-008)                        -- It's Const#594
	  +28D7: 01 C3 92 00   line#532  LOADK 12 -588        <2373>   R12 = 0.998278677                               -- It's Const#588
	  +28DB: 24 80 80 06   line#532  CALL 0 13 2          <2374>   R0 = R0(R1,..,R12)
	  +28DF: 08 00 80 88   line#532  SETTABUP 0 -18 0     <2375>   Upv#1@_ENV["CFrameQuest"] = R0                  -- It's Const#18
	  +28E3: 1E 80 0E 80   line#532  JMP 0 59             <2376>   GOTO <2436>
	  +28E7: 06 00 40 00   line#533  GETTABUP 0 0 -1      <2377>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +28EB: 41 80 95 00   line#533  LOADK 1 -599         <2378>   R1 = 2350                                       -- It's Const#599
	  +28EF: 5F 40 00 00   line#533  EQ 1 0 1             <2379>   if R0 ~= R1 then GOTO <2381>
	  +28F3: 1E C0 00 80   line#533  JMP 0 4              <2380>   GOTO <2385>
	  +28F7: 06 00 40 00   line#533  GETTABUP 0 0 -1      <2381>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +28FB: 41 C0 95 00   line#533  LOADK 1 -600         <2382>   R1 = 2374                                       -- It's Const#600
	  +28FF: 21 40 00 00   line#533  LE 0 0 1             <2383>   if R0 <= R1 then GOTO <2385>
	  +2903: 1E C0 05 80   line#533  JMP 0 24             <2384>   GOTO <2409>
	  +2907: 01 00 96 00   line#534  LOADK 0 -601         <2385>   R0 = "Sweet Thief [Lv. 2350]"                   -- It's Const#601
	  +290B: 08 00 00 85   line#534  SETTABUP 0 -11 0     <2386>   Upv#1@_ENV["Mon"] = R0                          -- It's Const#11
	  +290F: 08 00 42 86   line#535  SETTABUP 0 -13 -9    <2387>   Upv#1@_ENV["LQuest"] = 1                        -- It's Const#13, Const#9
	  +2913: 01 40 96 00   line#536  LOADK 0 -602         <2388>   R0 = "ChocQuest2"                               -- It's Const#602
	  +2917: 08 00 80 86   line#536  SETTABUP 0 -14 0     <2389>   Upv#1@_ENV["NQuest"] = R0                       -- It's Const#14
	  +291B: 01 80 96 00   line#537  LOADK 0 -603         <2390>   R0 = "Sweet Thief"                              -- It's Const#603
	  +291F: 08 00 80 87   line#537  SETTABUP 0 -16 0     <2391>   Upv#1@_ENV["NameMon"] = R0                      -- It's Const#16
	  +2923: 06 00 4E 00   line#538  GETTABUP 0 0 -57     <2392>   R0 = Upv#1@_ENV["CFrame"]                       -- It's Const#57
	  +2927: 07 40 4E 00   line#538  GETTABLE 0 0 -58     <2393>   R0 = R0["new"]                                  -- It's Const#58
	  +292B: 41 C0 96 00   line#538  LOADK 1 -604         <2394>   R1 = 149.867218                                 -- It's Const#604
	  +292F: 81 00 97 00   line#538  LOADK 2 -605         <2395>   R2 = 24.8196201                                 -- It's Const#605
	  +2933: C1 40 97 00   line#538  LOADK 3 -606         <2396>   R3 = (-12775.5283)                              -- It's Const#606
	  +2937: 01 81 97 00   line#538  LOADK 4 -607         <2397>   R4 = (-0.0371122323)                            -- It's Const#607
	  +293B: 41 C1 97 00   line#538  LOADK 5 -608         <2398>   R5 = (-7.14229245e-008)                         -- It's Const#608
	  +293F: 81 01 98 00   line#538  LOADK 6 -609         <2399>   R6 = (-0.99931109)                              -- It's Const#609
	  +2943: C1 41 98 00   line#538  LOADK 7 -610         <2400>   R7 = (-6.93553162e-008)                         -- It's Const#610
	  +2947: 01 02 02 00   line#538  LOADK 8 -9           <2401>   R8 = 1                                          -- It's Const#9
	  +294B: 41 82 98 00   line#538  LOADK 9 -611         <2402>   R9 = (-6.88964548e-008)                         -- It's Const#611
	  +294F: 81 C2 98 00   line#538  LOADK 10 -612        <2403>   R10 = 0.99931109                                -- It's Const#612
	  +2953: C1 02 99 00   line#538  LOADK 11 -613        <2404>   R11 = 6.6750637e-008                            -- It's Const#613
	  +2957: 01 83 97 00   line#538  LOADK 12 -607        <2405>   R12 = (-0.0371122323)                           -- It's Const#607
	  +295B: 24 80 80 06   line#538  CALL 0 13 2          <2406>   R0 = R0(R1,..,R12)
	  +295F: 08 00 80 88   line#538  SETTABUP 0 -18 0     <2407>   Upv#1@_ENV["CFrameQuest"] = R0                  -- It's Const#18
	  +2963: 1E 80 06 80   line#538  JMP 0 27             <2408>   GOTO <2436>
	  +2967: 06 00 40 00   line#539  GETTABUP 0 0 -1      <2409>   R0 = Upv#1@_ENV["Level"]                        -- It's Const#1
	  +296B: 41 40 99 00   line#539  LOADK 1 -614         <2410>   R1 = 2375                                       -- It's Const#614
	  +296F: 21 00 80 00   line#539  LE 0 1 0             <2411>   if R1 <= R0 then GOTO <2413>
	  +2973: 1E 80 05 80   line#539  JMP 0 23             <2412>   GOTO <2436>
	  +2977: 01 80 99 00   line#540  LOADK 0 -615         <2413>   R0 = "Candy Rebel [Lv. 2375]"                   -- It's Const#615
	  +297B: 08 00 00 85   line#540  SETTABUP 0 -11 0     <2414>   Upv#1@_ENV["Mon"] = R0                          -- It's Const#11
	  +297F: 08 40 4D 86   line#541  SETTABUP 0 -13 -54   <2415>   Upv#1@_ENV["LQuest"] = 2                        -- It's Const#13, Const#54
	  +2983: 01 40 96 00   line#542  LOADK 0 -602         <2416>   R0 = "ChocQuest2"                               -- It's Const#602
	  +2987: 08 00 80 86   line#542  SETTABUP 0 -14 0     <2417>   Upv#1@_ENV["NQuest"] = R0                       -- It's Const#14
	  +298B: 01 C0 99 00   line#543  LOADK 0 -616         <2418>   R0 = "Candy Rebel"                              -- It's Const#616
	  +298F: 08 00 80 87   line#543  SETTABUP 0 -16 0     <2419>   Upv#1@_ENV["NameMon"] = R0                      -- It's Const#16
	  +2993: 06 00 4E 00   line#544  GETTABUP 0 0 -57     <2420>   R0 = Upv#1@_ENV["CFrame"]                       -- It's Const#57
	  +2997: 07 40 4E 00   line#544  GETTABLE 0 0 -58     <2421>   R0 = R0["new"]                                  -- It's Const#58
	  +299B: 41 C0 96 00   line#544  LOADK 1 -604         <2422>   R1 = 149.867218                                 -- It's Const#604
	  +299F: 81 00 97 00   line#544  LOADK 2 -605         <2423>   R2 = 24.8196201                                 -- It's Const#605
	  +29A3: C1 40 97 00   line#544  LOADK 3 -606         <2424>   R3 = (-12775.5283)                              -- It's Const#606
	  +29A7: 01 81 97 00   line#544  LOADK 4 -607         <2425>   R4 = (-0.0371122323)                            -- It's Const#607
	  +29AB: 41 C1 97 00   line#544  LOADK 5 -608         <2426>   R5 = (-7.14229245e-008)                         -- It's Const#608
	  +29AF: 81 01 98 00   line#544  LOADK 6 -609         <2427>   R6 = (-0.99931109)                              -- It's Const#609
	  +29B3: C1 41 98 00   line#544  LOADK 7 -610         <2428>   R7 = (-6.93553162e-008)                         -- It's Const#610
	  +29B7: 01 02 02 00   line#544  LOADK 8 -9           <2429>   R8 = 1                                          -- It's Const#9
	  +29BB: 41 82 98 00   line#544  LOADK 9 -611         <2430>   R9 = (-6.88964548e-008)                         -- It's Const#611
	  +29BF: 81 C2 98 00   line#544  LOADK 10 -612        <2431>   R10 = 0.99931109                                -- It's Const#612
	  +29C3: C1 02 99 00   line#544  LOADK 11 -613        <2432>   R11 = 6.6750637e-008                            -- It's Const#613
	  +29C7: 01 83 97 00   line#544  LOADK 12 -607        <2433>   R12 = (-0.0371122323)                           -- It's Const#607
	  +29CB: 24 80 80 06   line#544  CALL 0 13 2          <2434>   R0 = R0(R1,..,R12)
	  +29CF: 08 00 80 88   line#544  SETTABUP 0 -18 0     <2435>   Upv#1@_ENV["CFrameQuest"] = R0                  -- It's Const#18
	  +29D3: 26 00 80 00   line#547  RETURN 0 1           <2436>   RETURN
	Functions: 2

		************ Function#1   (full path: main.1.1)
		Source line#: 32..59
		Parameters: 0
		Is vararg: no
		VM registers needed: 11
		Constants: 39
		  +4649:Size=4: 67 61 6D 65                     Const#1   string    "game"
		  +464F:Size=A: 47 65 74 53 65 72 76 69 63 65   Const#2   string    "GetService"
		  +465B:Size=9: 57 6F 72 6B 73 70 61 63 65      Const#3   string    "Workspace"
		  +4666:Size=7: 45 6E 65 6D 69 65 73            Const#4   string    "Enemies"
		  +466F:Size=E: 46 69 6E 64 46 69 72 73 74...   Const#5   string    "FindFirstChild"
		  +467F:Size=10: 53 68 61 6E 64 61 20 5B 4...   Const#6   string    "Shanda [Lv. 475]"
		  +4691:Size=5: 70 61 69 72 73                  Const#7   string    "pairs"
		  +4698:Size=B: 47 65 74 43 68 69 6C 64 72...   Const#8   string    "GetChildren"
		  +46A5:Size=4: 4E 61 6D 65                     Const#9   string    "Name"
		  +46AB:Size=8: 48 75 6D 61 6E 6F 69 64         Const#10  string    "Humanoid"
		  +46B5:Size=10: 48 75 6D 61 6E 6F 69 64 5...   Const#11  string    "HumanoidRootPart"
		  +46C7:Size=6: 48 65 61 6C 74 68               Const#12  string    "Health"
		  +46CE:Size=4: 00 00 00 00                     Const#13  integer   0
		  +46D4:Size=4: 74 61 73 6B                     Const#14  string    "task"
		  +46DA:Size=4: 77 61 69 74                     Const#15  string    "wait"
		  +46E0:Size=B: 45 71 75 69 70 57 65 61 70...   Const#16  string    "EquipWeapon"
		  +46ED:Size=2: 5F 47                           Const#17  string    "_G"
		  +46F1:Size=C: 53 65 6C 65 63 74 57 65 61...   Const#18  string    "SelectWeapon"
		  +46FF:Size=A: 43 61 6E 43 6F 6C 6C 69 64 65   Const#19  string    "CanCollide"
		  +470A:Size=1: 00                              Const#20  boolean   false
		  +470D:Size=9: 57 61 6C 6B 53 70 65 65 64      Const#21  string    "WalkSpeed"
		  +4718:Size=4: 48 65 61 64                     Const#22  string    "Head"
		  +471E:Size=F: 53 74 61 72 74 4D 61 67 6E...   Const#23  string    "StartMagnetKill"
		  +472E:Size=1: 01                              Const#24  boolean   true
		  +4731:Size=A: 50 6F 73 4D 6F 6E 4B 69 6C 6C   Const#25  string    "PosMonKill"
		  +473D:Size=6: 43 46 72 61 6D 65               Const#26  string    "CFrame"
		  +4745:Size=5: 74 6F 70 6F 73                  Const#27  string    "topos"
		  +474C:Size=3: 6E 65 77                        Const#28  string    "new"
		  +4750:Size=4: 02 00 00 00                     Const#29  integer   2
		  +4755:Size=4: 14 00 00 00                     Const#30  integer   20
		  +475B:Size=B: 56 69 72 74 75 61 6C 55 73...   Const#31  string    "VirtualUser"
		  +4768:Size=11: 43 61 70 74 75 72 65 43 6...   Const#32  string    "CaptureController"
		  +477B:Size=B: 42 75 74 74 6F 6E 31 44 6F...   Const#33  string    "Button1Down"
		  +4788:Size=7: 56 65 63 74 6F 72 32            Const#34  string    "Vector2"
		  +4790:Size=4: 00 05 00 00                     Const#35  integer   1280
		  +4795:Size=4: A0 02 00 00                     Const#36  integer   672
		  +479B:Size=E: 41 75 74 6F 5F 46 61 72 6D...   Const#37  string    "Auto_Farm_Kill"
		  +47AB:Size=6: 50 61 72 65 6E 74               Const#38  string    "Parent"
		  +47B3:Size=11: 52 65 70 6C 69 63 61 74 6...   Const#39  string    "ReplicatedStorage"
		Upvalues: 1
		  Upv#1 is parent function's Upv#1              name: _ENV
		Locals: 10
		  Local#1   R0   def:<19>   scope:<20..95>      name: (for generator)
		  Local#2   R1   def:<19>   scope:<20..95>      name: (for state)
		  Local#3   R2   def:<19>   scope:<20..95>      name: (for control)
		  Local#4   R3   def:<20>   scope:<21..93>      name: i
		  Local#5   R4   def:<20>   scope:<21..93>      name: v
		  Local#6   R0   def:<105>  scope:<106..122>    name: (for generator)
		  Local#7   R1   def:<105>  scope:<106..122>    name: (for state)
		  Local#8   R2   def:<105>  scope:<106..122>    name: (for control)
		  Local#9   R3   def:<106>  scope:<107..120>    name: i
		  Local#10  R4   def:<106>  scope:<107..120>    name: v
		Instructions: 123
		  +4457: 06 00 40 00   line#33   GETTABUP 0 0 -1         <1>   R0 = Upv#1@_ENV["game"]                         -- It's Const#1
		  +445B: 0C 40 40 00   line#33   SELF 0 0 -2             <2>   R1 = R0;  R0 = R0["GetService"]                 -- It's Const#2   -- prepare for R0:GetService()
		  +445F: 81 80 00 00   line#33   LOADK 2 -3              <3>   R2 = "Workspace"                                -- It's Const#3
		  +4463: 24 80 80 01   line#33   CALL 0 3 2              <4>   R0 = R0(R1, R2)
		  +4467: 07 C0 40 00   line#33   GETTABLE 0 0 -4         <5>   R0 = R0["Enemies"]                              -- It's Const#4
		  +446B: 0C 00 41 00   line#33   SELF 0 0 -5             <6>   R1 = R0;  R0 = R0["FindFirstChild"]             -- It's Const#5   -- prepare for R0:FindFirstChild()
		  +446F: 81 40 01 00   line#33   LOADK 2 -6              <7>   R2 = "Shanda [Lv. 475]"                         -- It's Const#6
		  +4473: 24 80 80 01   line#33   CALL 0 3 2              <8>   R0 = R0(R1, R2)
		  +4477: 22 00 00 00   line#33   TEST 0 0                <9>   if R0 then GOTO <11>
		  +447B: 1E 40 15 80   line#33   JMP 0 86               <10>   GOTO <97>
		  +447F: 06 80 41 00   line#34   GETTABUP 0 0 -7        <11>   R0 = Upv#1@_ENV["pairs"]                        -- It's Const#7
		  +4483: 46 00 40 00   line#34   GETTABUP 1 0 -1        <12>   R1 = Upv#1@_ENV["game"]                         -- It's Const#1
		  +4487: 4C 40 C0 00   line#34   SELF 1 1 -2            <13>   R2 = R1;  R1 = R1["GetService"]                 -- It's Const#2   -- prepare for R1:GetService()
		  +448B: C1 80 00 00   line#34   LOADK 3 -3             <14>   R3 = "Workspace"                                -- It's Const#3
		  +448F: 64 80 80 01   line#34   CALL 1 3 2             <15>   R1 = R1(R2, R3)
		  +4493: 47 C0 C0 00   line#34   GETTABLE 1 1 -4        <16>   R1 = R1["Enemies"]                              -- It's Const#4
		  +4497: 4C C0 C1 00   line#34   SELF 1 1 -8            <17>   R2 = R1;  R1 = R1["GetChildren"]                -- It's Const#8   -- prepare for R1:GetChildren()
		  +449B: 64 00 00 01   line#34   CALL 1 2 0             <18>   R1,.. = R1(R2)
		  +449F: 24 00 01 00   line#34   CALL 0 0 4             <19>   R0, R1, R2 = R0(R1,..)
		  +44A3: 1E 00 12 80   line#34   JMP 0 73               <20>   GOTO <94>                                       -- for R3@i, R4@v in R0, R1, R2 do
		  +44A7: 47 01 42 02   line#35   GETTABLE 5 4 -9        <21>   R5 = R4@v["Name"]                               -- It's Const#9
		  +44AB: 1F 40 C1 02   line#35   EQ 0 5 -6              <22>   if R5 == "Shanda [Lv. 475]" then GOTO <24>      -- It's Const#6
		  +44AF: 1E 40 11 80   line#35   JMP 0 70               <23>   GOTO <94>
		  +44B3: 4C 01 41 02   line#36   SELF 5 4 -5            <24>   R6 = R4@v;  R5 = R4@v["FindFirstChild"]         -- It's Const#5   -- prepare for R4@v:FindFirstChild()
		  +44B7: C1 41 02 00   line#36   LOADK 7 -10            <25>   R7 = "Humanoid"                                 -- It's Const#10
		  +44BB: 64 81 80 01   line#36   CALL 5 3 2             <26>   R5 = R5(R6, R7)
		  +44BF: 62 01 00 00   line#36   TEST 5 0               <27>   if R5 then GOTO <29>
		  +44C3: 1E 00 10 80   line#36   JMP 0 65               <28>   GOTO <94>
		  +44C7: 4C 01 41 02   line#36   SELF 5 4 -5            <29>   R6 = R4@v;  R5 = R4@v["FindFirstChild"]         -- It's Const#5   -- prepare for R4@v:FindFirstChild()
		  +44CB: C1 81 02 00   line#36   LOADK 7 -11            <30>   R7 = "HumanoidRootPart"                         -- It's Const#11
		  +44CF: 64 81 80 01   line#36   CALL 5 3 2             <31>   R5 = R5(R6, R7)
		  +44D3: 62 01 00 00   line#36   TEST 5 0               <32>   if R5 then GOTO <34>
		  +44D7: 1E C0 0E 80   line#36   JMP 0 60               <33>   GOTO <94>
		  +44DB: 47 41 42 02   line#36   GETTABLE 5 4 -10       <34>   R5 = R4@v["Humanoid"]                           -- It's Const#10
		  +44DF: 47 C1 C2 02   line#36   GETTABLE 5 5 -12       <35>   R5 = R5["Health"]                               -- It's Const#12
		  +44E3: 20 40 01 86   line#36   LT 0 -13 5             <36>   if R5 > 0 then GOTO <38>                        -- It's Const#13
		  +44E7: 1E C0 0D 80   line#36   JMP 0 56               <37>   GOTO <94>
		  +44EB: 46 41 43 00   line#37   GETTABUP 5 0 -14       <38>   R5 = Upv#1@_ENV["task"]                         -- It's Const#14
		  +44EF: 47 81 C3 02   line#37   GETTABLE 5 5 -15       <39>   R5 = R5["wait"]                                 -- It's Const#15
		  +44F3: 64 41 80 00   line#37   CALL 5 1 1             <40>   R5()
		  +44F7: 46 C1 43 00   line#38   GETTABUP 5 0 -16       <41>   R5 = Upv#1@_ENV["EquipWeapon"]                  -- It's Const#16
		  +44FB: 86 01 44 00   line#38   GETTABUP 6 0 -17       <42>   R6 = Upv#1@_ENV["_G"]                           -- It's Const#17
		  +44FF: 87 41 44 03   line#38   GETTABLE 6 6 -18       <43>   R6 = R6["SelectWeapon"]                         -- It's Const#18
		  +4503: 64 41 00 01   line#38   CALL 5 2 1             <44>   R5(R6)
		  +4507: 47 81 42 02   line#39   GETTABLE 5 4 -11       <45>   R5 = R4@v["HumanoidRootPart"]                   -- It's Const#11
		  +450B: 4A C1 44 89   line#39   SETTABLE 5 -19 -20     <46>   R5["CanCollide"] = false                        -- It's Const#19, Const#20
		  +450F: 47 41 42 02   line#40   GETTABLE 5 4 -10       <47>   R5 = R4@v["Humanoid"]                           -- It's Const#10
		  +4513: 4A 01 43 8A   line#40   SETTABLE 5 -21 -13     <48>   R5["WalkSpeed"] = 0                             -- It's Const#21, Const#13
		  +4517: 47 41 45 02   line#41   GETTABLE 5 4 -22       <49>   R5 = R4@v["Head"]                               -- It's Const#22
		  +451B: 4A C1 44 89   line#41   SETTABLE 5 -19 -20     <50>   R5["CanCollide"] = false                        -- It's Const#19, Const#20
		  +451F: 08 C0 45 8B   line#42   SETTABUP 0 -23 -24     <51>   Upv#1@_ENV["StartMagnetKill"] = true            -- It's Const#23, Const#24
		  +4523: 47 81 42 02   line#43   GETTABLE 5 4 -11       <52>   R5 = R4@v["HumanoidRootPart"]                   -- It's Const#11
		  +4527: 47 41 C6 02   line#43   GETTABLE 5 5 -26       <53>   R5 = R5["CFrame"]                               -- It's Const#26
		  +452B: 08 40 01 8C   line#43   SETTABUP 0 -25 5       <54>   Upv#1@_ENV["PosMonKill"] = R5                   -- It's Const#25
		  +452F: 46 81 46 00   line#44   GETTABUP 5 0 -27       <55>   R5 = Upv#1@_ENV["topos"]                        -- It's Const#27
		  +4533: 87 81 42 02   line#44   GETTABLE 6 4 -11       <56>   R6 = R4@v["HumanoidRootPart"]                   -- It's Const#11
		  +4537: 87 41 46 03   line#44   GETTABLE 6 6 -26       <57>   R6 = R6["CFrame"]                               -- It's Const#26
		  +453B: C6 41 46 00   line#44   GETTABUP 7 0 -26       <58>   R7 = Upv#1@_ENV["CFrame"]                       -- It's Const#26
		  +453F: C7 C1 C6 03   line#44   GETTABLE 7 7 -28       <59>   R7 = R7["new"]                                  -- It's Const#28
		  +4543: 01 02 07 00   line#44   LOADK 8 -29            <60>   R8 = 2                                          -- It's Const#29
		  +4547: 41 42 07 00   line#44   LOADK 9 -30            <61>   R9 = 20                                         -- It's Const#30
		  +454B: 81 02 07 00   line#44   LOADK 10 -29           <62>   R10 = 2                                         -- It's Const#29
		  +454F: E4 81 00 02   line#44   CALL 7 4 2             <63>   R7 = R7(R8, R9, R10)
		  +4553: 8F C1 01 03   line#44   MUL 6 6 7              <64>   R6 = R6 * R7
		  +4557: 64 41 00 01   line#44   CALL 5 2 1             <65>   R5(R6)
		  +455B: 46 01 40 00   line#45   GETTABUP 5 0 -1        <66>   R5 = Upv#1@_ENV["game"]                         -- It's Const#1
		  +455F: 4C 41 C0 02   line#45   SELF 5 5 -2            <67>   R6 = R5;  R5 = R5["GetService"]                 -- It's Const#2   -- prepare for R5:GetService()
		  +4563: C1 81 07 00   line#45   LOADK 7 -31            <68>   R7 = "VirtualUser"                              -- It's Const#31
		  +4567: 64 81 80 01   line#45   CALL 5 3 2             <69>   R5 = R5(R6, R7)
		  +456B: 4C C1 C7 02   line#45   SELF 5 5 -32           <70>   R6 = R5;  R5 = R5["CaptureController"]          -- It's Const#32   -- prepare for R5:CaptureController()
		  +456F: 64 41 00 01   line#45   CALL 5 2 1             <71>   R5(R6)
		  +4573: 46 01 40 00   line#46   GETTABUP 5 0 -1        <72>   R5 = Upv#1@_ENV["game"]                         -- It's Const#1
		  +4577: 4C 41 C0 02   line#46   SELF 5 5 -2            <73>   R6 = R5;  R5 = R5["GetService"]                 -- It's Const#2   -- prepare for R5:GetService()
		  +457B: C1 81 07 00   line#46   LOADK 7 -31            <74>   R7 = "VirtualUser"                              -- It's Const#31
		  +457F: 64 81 80 01   line#46   CALL 5 3 2             <75>   R5 = R5(R6, R7)
		  +4583: 4C 01 C8 02   line#46   SELF 5 5 -33           <76>   R6 = R5;  R5 = R5["Button1Down"]                -- It's Const#33   -- prepare for R5:Button1Down()
		  +4587: C6 41 48 00   line#46   GETTABUP 7 0 -34       <77>   R7 = Upv#1@_ENV["Vector2"]                      -- It's Const#34
		  +458B: C7 C1 C6 03   line#46   GETTABLE 7 7 -28       <78>   R7 = R7["new"]                                  -- It's Const#28
		  +458F: 01 82 08 00   line#46   LOADK 8 -35            <79>   R8 = 1280                                       -- It's Const#35
		  +4593: 41 C2 08 00   line#46   LOADK 9 -36            <80>   R9 = 672                                        -- It's Const#36
		  +4597: E4 01 80 01   line#46   CALL 7 3 0             <81>   R7,.. = R7(R8, R9)
		  +459B: 64 41 00 00   line#46   CALL 5 0 1             <82>   R5(R6,..)
		  +459F: 46 01 44 00   line#47   GETTABUP 5 0 -17       <83>   R5 = Upv#1@_ENV["_G"]                           -- It's Const#17
		  +45A3: 47 01 C9 02   line#47   GETTABLE 5 5 -37       <84>   R5 = R5["Auto_Farm_Kill"]                       -- It's Const#37
		  +45A7: 62 01 00 00   line#47   TEST 5 0               <85>   if R5 then GOTO <87>
		  +45AB: 1E 80 01 80   line#47   JMP 0 7                <86>   GOTO <94>
		  +45AF: 47 41 49 02   line#47   GETTABLE 5 4 -38       <87>   R5 = R4@v["Parent"]                             -- It's Const#38
		  +45B3: 62 01 00 00   line#47   TEST 5 0               <88>   if R5 then GOTO <90>
		  +45B7: 1E C0 00 80   line#47   JMP 0 4                <89>   GOTO <94>
		  +45BB: 47 41 42 02   line#47   GETTABLE 5 4 -10       <90>   R5 = R4@v["Humanoid"]                           -- It's Const#10
		  +45BF: 47 C1 C2 02   line#47   GETTABLE 5 5 -12       <91>   R5 = R5["Health"]                               -- It's Const#12
		  +45C3: 21 00 C3 02   line#47   LE 0 5 -13             <92>   if R5 <= 0 then GOTO <94>                       -- It's Const#13
		  +45C7: 1E C0 F1 7F   line#47   JMP 0 -56              <93>   GOTO <38>
		  +45CB: 29 80 00 00   line#34   TFORCALL 0 2           <94>   R3, R4 = R0(R1, R2)
		  +45CF: AA 00 ED 7F   line#34   TFORLOOP 2 -75         <95>   if R3 ~= nil then { R2 = R3;  GOTO <21> }       -- end of loop
		  +45D3: 1E 40 06 80   line#50   JMP 0 26               <96>   GOTO <123>
		  +45D7: 08 C0 44 8B   line#52   SETTABUP 0 -23 -20     <97>   Upv#1@_ENV["StartMagnetKill"] = false           -- It's Const#23, Const#20
		  +45DB: 06 80 41 00   line#53   GETTABUP 0 0 -7        <98>   R0 = Upv#1@_ENV["pairs"]                        -- It's Const#7
		  +45DF: 46 00 40 00   line#53   GETTABUP 1 0 -1        <99>   R1 = Upv#1@_ENV["game"]                         -- It's Const#1
		  +45E3: 4C 40 C0 00   line#53   SELF 1 1 -2           <100>   R2 = R1;  R1 = R1["GetService"]                 -- It's Const#2   -- prepare for R1:GetService()
		  +45E7: C1 80 09 00   line#53   LOADK 3 -39           <101>   R3 = "ReplicatedStorage"                        -- It's Const#39
		  +45EB: 64 80 80 01   line#53   CALL 1 3 2            <102>   R1 = R1(R2, R3)
		  +45EF: 4C C0 C1 00   line#53   SELF 1 1 -8           <103>   R2 = R1;  R1 = R1["GetChildren"]                -- It's Const#8   -- prepare for R1:GetChildren()
		  +45F3: 64 00 00 01   line#53   CALL 1 2 0            <104>   R1,.. = R1(R2)
		  +45F7: 24 00 01 00   line#53   CALL 0 0 4            <105>   R0, R1, R2 = R0(R1,..)
		  +45FB: 1E 40 03 80   line#53   JMP 0 14              <106>   GOTO <121>                                      -- for R3@i, R4@v in R0, R1, R2 do
		  +45FF: 47 01 42 02   line#54   GETTABLE 5 4 -9       <107>   R5 = R4@v["Name"]                               -- It's Const#9
		  +4603: 1F 40 C1 02   line#54   EQ 0 5 -6             <108>   if R5 == "Shanda [Lv. 475]" then GOTO <110>     -- It's Const#6
		  +4607: 1E 80 02 80   line#54   JMP 0 11              <109>   GOTO <121>
		  +460B: 46 81 46 00   line#55   GETTABUP 5 0 -27      <110>   R5 = Upv#1@_ENV["topos"]                        -- It's Const#27
		  +460F: 87 81 42 02   line#55   GETTABLE 6 4 -11      <111>   R6 = R4@v["HumanoidRootPart"]                   -- It's Const#11
		  +4613: 87 41 46 03   line#55   GETTABLE 6 6 -26      <112>   R6 = R6["CFrame"]                               -- It's Const#26
		  +4617: C6 41 46 00   line#55   GETTABUP 7 0 -26      <113>   R7 = Upv#1@_ENV["CFrame"]                       -- It's Const#26
		  +461B: C7 C1 C6 03   line#55   GETTABLE 7 7 -28      <114>   R7 = R7["new"]                                  -- It's Const#28
		  +461F: 01 02 07 00   line#55   LOADK 8 -29           <115>   R8 = 2                                          -- It's Const#29
		  +4623: 41 42 07 00   line#55   LOADK 9 -30           <116>   R9 = 20                                         -- It's Const#30
		  +4627: 81 02 07 00   line#55   LOADK 10 -29          <117>   R10 = 2                                         -- It's Const#29
		  +462B: E4 81 00 02   line#55   CALL 7 4 2            <118>   R7 = R7(R8, R9, R10)
		  +462F: 8F C1 01 03   line#55   MUL 6 6 7             <119>   R6 = R6 * R7
		  +4633: 64 41 00 01   line#55   CALL 5 2 1            <120>   R5(R6)
		  +4637: 29 80 00 00   line#53   TFORCALL 0 2          <121>   R3, R4 = R0(R1, R2)
		  +463B: AA C0 FB 7F   line#53   TFORLOOP 2 -16        <122>   if R3 ~= nil then { R2 = R3;  GOTO <107> }      -- end of loop
		  +463F: 26 00 80 00   line#59   RETURN 0 1            <123>   RETURN
		Functions: 0

		************ Function#2   (full path: main.1.2)
		Source line#: 64..92
		Parameters: 0
		Is vararg: no
		VM registers needed: 11
		Constants: 40
		  +4C81:Size=4: 67 61 6D 65                     Const#1   string    "game"
		  +4C87:Size=A: 47 65 74 53 65 72 76 69 63 65   Const#2   string    "GetService"
		  +4C93:Size=9: 57 6F 72 6B 73 70 61 63 65      Const#3   string    "Workspace"
		  +4C9E:Size=7: 45 6E 65 6D 69 65 73            Const#4   string    "Enemies"
		  +4CA7:Size=E: 46 69 6E 64 46 69 72 73 74...   Const#5   string    "FindFirstChild"
		  +4CB7:Size=15: 52 6F 79 61 6C 20 53 71 7...   Const#6   string    "Royal Squad [Lv. 525]"
		  +4CCE:Size=5: 70 61 69 72 73                  Const#7   string    "pairs"
		  +4CD5:Size=B: 47 65 74 43 68 69 6C 64 72...   Const#8   string    "GetChildren"
		  +4CE2:Size=4: 4E 61 6D 65                     Const#9   string    "Name"
		  +4CE8:Size=8: 48 75 6D 61 6E 6F 69 64         Const#10  string    "Humanoid"
		  +4CF2:Size=10: 48 75 6D 61 6E 6F 69 64 5...   Const#11  string    "HumanoidRootPart"
		  +4D04:Size=6: 48 65 61 6C 74 68               Const#12  string    "Health"
		  +4D0B:Size=4: 00 00 00 00                     Const#13  integer   0
		  +4D11:Size=4: 74 61 73 6B                     Const#14  string    "task"
		  +4D17:Size=4: 77 61 69 74                     Const#15  string    "wait"
		  +4D1D:Size=8: 41 75 74 6F 48 61 6B 69         Const#16  string    "AutoHaki"
		  +4D27:Size=B: 45 71 75 69 70 57 65 61 70...   Const#17  string    "EquipWeapon"
		  +4D34:Size=2: 5F 47                           Const#18  string    "_G"
		  +4D38:Size=C: 53 65 6C 65 63 74 57 65 61...   Const#19  string    "SelectWeapon"
		  +4D46:Size=A: 43 61 6E 43 6F 6C 6C 69 64 65   Const#20  string    "CanCollide"
		  +4D51:Size=1: 00                              Const#21  boolean   false
		  +4D54:Size=9: 57 61 6C 6B 53 70 65 65 64      Const#22  string    "WalkSpeed"
		  +4D5F:Size=4: 48 65 61 64                     Const#23  string    "Head"
		  +4D65:Size=F: 53 74 61 72 74 4D 61 67 6E...   Const#24  string    "StartMagnetKOOK"
		  +4D75:Size=1: 01                              Const#25  boolean   true
		  +4D78:Size=A: 50 6F 73 4D 6F 6E 4B 4F 4F 4B   Const#26  string    "PosMonKOOK"
		  +4D84:Size=6: 43 46 72 61 6D 65               Const#27  string    "CFrame"
		  +4D8C:Size=5: 74 6F 70 6F 73                  Const#28  string    "topos"
		  +4D93:Size=3: 6E 65 77                        Const#29  string    "new"
		  +4D97:Size=4: 02 00 00 00                     Const#30  integer   2
		  +4D9C:Size=4: 14 00 00 00                     Const#31  integer   20
		  +4DA2:Size=B: 56 69 72 74 75 61 6C 55 73...   Const#32  string    "VirtualUser"
		  +4DAF:Size=11: 43 61 70 74 75 72 65 43 6...   Const#33  string    "CaptureController"
		  +4DC2:Size=B: 42 75 74 74 6F 6E 31 44 6F...   Const#34  string    "Button1Down"
		  +4DCF:Size=7: 56 65 63 74 6F 72 32            Const#35  string    "Vector2"
		  +4DD7:Size=4: 00 05 00 00                     Const#36  integer   1280
		  +4DDC:Size=4: A0 02 00 00                     Const#37  integer   672
		  +4DE2:Size=E: 41 75 74 6F 5F 46 61 72 6D...   Const#38  string    "Auto_Farm_Kill"
		  +4DF2:Size=6: 50 61 72 65 6E 74               Const#39  string    "Parent"
		  +4DFA:Size=11: 52 65 70 6C 69 63 61 74 6...   Const#40  string    "ReplicatedStorage"
		Upvalues: 1
		  Upv#1 is parent function's Upv#1              name: _ENV
		Locals: 10
		  Local#1   R0   def:<19>   scope:<20..97>      name: (for generator)
		  Local#2   R1   def:<19>   scope:<20..97>      name: (for state)
		  Local#3   R2   def:<19>   scope:<20..97>      name: (for control)
		  Local#4   R3   def:<20>   scope:<21..95>      name: i
		  Local#5   R4   def:<20>   scope:<21..95>      name: v
		  Local#6   R0   def:<107>  scope:<108..124>    name: (for generator)
		  Local#7   R1   def:<107>  scope:<108..124>    name: (for state)
		  Local#8   R2   def:<107>  scope:<108..124>    name: (for control)
		  Local#9   R3   def:<108>  scope:<109..122>    name: i
		  Local#10  R4   def:<108>  scope:<109..122>    name: v
		Instructions: 125
		  +4A87: 06 00 40 00   line#65   GETTABUP 0 0 -1         <1>   R0 = Upv#1@_ENV["game"]                         -- It's Const#1
		  +4A8B: 0C 40 40 00   line#65   SELF 0 0 -2             <2>   R1 = R0;  R0 = R0["GetService"]                 -- It's Const#2   -- prepare for R0:GetService()
		  +4A8F: 81 80 00 00   line#65   LOADK 2 -3              <3>   R2 = "Workspace"                                -- It's Const#3
		  +4A93: 24 80 80 01   line#65   CALL 0 3 2              <4>   R0 = R0(R1, R2)
		  +4A97: 07 C0 40 00   line#65   GETTABLE 0 0 -4         <5>   R0 = R0["Enemies"]                              -- It's Const#4
		  +4A9B: 0C 00 41 00   line#65   SELF 0 0 -5             <6>   R1 = R0;  R0 = R0["FindFirstChild"]             -- It's Const#5   -- prepare for R0:FindFirstChild()
		  +4A9F: 81 40 01 00   line#65   LOADK 2 -6              <7>   R2 = "Royal Squad [Lv. 525]"                    -- It's Const#6
		  +4AA3: 24 80 80 01   line#65   CALL 0 3 2              <8>   R0 = R0(R1, R2)
		  +4AA7: 22 00 00 00   line#65   TEST 0 0                <9>   if R0 then GOTO <11>
		  +4AAB: 1E C0 15 80   line#65   JMP 0 88               <10>   GOTO <99>
		  +4AAF: 06 80 41 00   line#66   GETTABUP 0 0 -7        <11>   R0 = Upv#1@_ENV["pairs"]                        -- It's Const#7
		  +4AB3: 46 00 40 00   line#66   GETTABUP 1 0 -1        <12>   R1 = Upv#1@_ENV["game"]                         -- It's Const#1
		  +4AB7: 4C 40 C0 00   line#66   SELF 1 1 -2            <13>   R2 = R1;  R1 = R1["GetService"]                 -- It's Const#2   -- prepare for R1:GetService()
		  +4ABB: C1 80 00 00   line#66   LOADK 3 -3             <14>   R3 = "Workspace"                                -- It's Const#3
		  +4ABF: 64 80 80 01   line#66   CALL 1 3 2             <15>   R1 = R1(R2, R3)
		  +4AC3: 47 C0 C0 00   line#66   GETTABLE 1 1 -4        <16>   R1 = R1["Enemies"]                              -- It's Const#4
		  +4AC7: 4C C0 C1 00   line#66   SELF 1 1 -8            <17>   R2 = R1;  R1 = R1["GetChildren"]                -- It's Const#8   -- prepare for R1:GetChildren()
		  +4ACB: 64 00 00 01   line#66   CALL 1 2 0             <18>   R1,.. = R1(R2)
		  +4ACF: 24 00 01 00   line#66   CALL 0 0 4             <19>   R0, R1, R2 = R0(R1,..)
		  +4AD3: 1E 80 12 80   line#66   JMP 0 75               <20>   GOTO <96>                                       -- for R3@i, R4@v in R0, R1, R2 do
		  +4AD7: 47 01 42 02   line#67   GETTABLE 5 4 -9        <21>   R5 = R4@v["Name"]                               -- It's Const#9
		  +4ADB: 1F 40 C1 02   line#67   EQ 0 5 -6              <22>   if R5 == "Royal Squad [Lv. 525]" then GOTO <24>   -- It's Const#6
		  +4ADF: 1E C0 11 80   line#67   JMP 0 72               <23>   GOTO <96>
		  +4AE3: 4C 01 41 02   line#68   SELF 5 4 -5            <24>   R6 = R4@v;  R5 = R4@v["FindFirstChild"]         -- It's Const#5   -- prepare for R4@v:FindFirstChild()
		  +4AE7: C1 41 02 00   line#68   LOADK 7 -10            <25>   R7 = "Humanoid"                                 -- It's Const#10
		  +4AEB: 64 81 80 01   line#68   CALL 5 3 2             <26>   R5 = R5(R6, R7)
		  +4AEF: 62 01 00 00   line#68   TEST 5 0               <27>   if R5 then GOTO <29>
		  +4AF3: 1E 80 10 80   line#68   JMP 0 67               <28>   GOTO <96>
		  +4AF7: 4C 01 41 02   line#68   SELF 5 4 -5            <29>   R6 = R4@v;  R5 = R4@v["FindFirstChild"]         -- It's Const#5   -- prepare for R4@v:FindFirstChild()
		  +4AFB: C1 81 02 00   line#68   LOADK 7 -11            <30>   R7 = "HumanoidRootPart"                         -- It's Const#11
		  +4AFF: 64 81 80 01   line#68   CALL 5 3 2             <31>   R5 = R5(R6, R7)
		  +4B03: 62 01 00 00   line#68   TEST 5 0               <32>   if R5 then GOTO <34>
		  +4B07: 1E 40 0F 80   line#68   JMP 0 62               <33>   GOTO <96>
		  +4B0B: 47 41 42 02   line#68   GETTABLE 5 4 -10       <34>   R5 = R4@v["Humanoid"]                           -- It's Const#10
		  +4B0F: 47 C1 C2 02   line#68   GETTABLE 5 5 -12       <35>   R5 = R5["Health"]                               -- It's Const#12
		  +4B13: 20 40 01 86   line#68   LT 0 -13 5             <36>   if R5 > 0 then GOTO <38>                        -- It's Const#13
		  +4B17: 1E 40 0E 80   line#68   JMP 0 58               <37>   GOTO <96>
		  +4B1B: 46 41 43 00   line#69   GETTABUP 5 0 -14       <38>   R5 = Upv#1@_ENV["task"]                         -- It's Const#14
		  +4B1F: 47 81 C3 02   line#69   GETTABLE 5 5 -15       <39>   R5 = R5["wait"]                                 -- It's Const#15
		  +4B23: 64 41 80 00   line#69   CALL 5 1 1             <40>   R5()
		  +4B27: 46 C1 43 00   line#70   GETTABUP 5 0 -16       <41>   R5 = Upv#1@_ENV["AutoHaki"]                     -- It's Const#16
		  +4B2B: 64 41 80 00   line#70   CALL 5 1 1             <42>   R5()
		  +4B2F: 46 01 44 00   line#71   GETTABUP 5 0 -17       <43>   R5 = Upv#1@_ENV["EquipWeapon"]                  -- It's Const#17
		  +4B33: 86 41 44 00   line#71   GETTABUP 6 0 -18       <44>   R6 = Upv#1@_ENV["_G"]                           -- It's Const#18
		  +4B37: 87 81 44 03   line#71   GETTABLE 6 6 -19       <45>   R6 = R6["SelectWeapon"]                         -- It's Const#19
		  +4B3B: 64 41 00 01   line#71   CALL 5 2 1             <46>   R5(R6)
		  +4B3F: 47 81 42 02   line#72   GETTABLE 5 4 -11       <47>   R5 = R4@v["HumanoidRootPart"]                   -- It's Const#11
		  +4B43: 4A 01 C5 89   line#72   SETTABLE 5 -20 -21     <48>   R5["CanCollide"] = false                        -- It's Const#20, Const#21
		  +4B47: 47 41 42 02   line#73   GETTABLE 5 4 -10       <49>   R5 = R4@v["Humanoid"]                           -- It's Const#10
		  +4B4B: 4A 01 C3 8A   line#73   SETTABLE 5 -22 -13     <50>   R5["WalkSpeed"] = 0                             -- It's Const#22, Const#13
		  +4B4F: 47 81 45 02   line#74   GETTABLE 5 4 -23       <51>   R5 = R4@v["Head"]                               -- It's Const#23
		  +4B53: 4A 01 C5 89   line#74   SETTABLE 5 -20 -21     <52>   R5["CanCollide"] = false                        -- It's Const#20, Const#21
		  +4B57: 08 00 C6 8B   line#75   SETTABUP 0 -24 -25     <53>   Upv#1@_ENV["StartMagnetKOOK"] = true            -- It's Const#24, Const#25
		  +4B5B: 47 81 42 02   line#76   GETTABLE 5 4 -11       <54>   R5 = R4@v["HumanoidRootPart"]                   -- It's Const#11
		  +4B5F: 47 81 C6 02   line#76   GETTABLE 5 5 -27       <55>   R5 = R5["CFrame"]                               -- It's Const#27
		  +4B63: 08 40 81 8C   line#76   SETTABUP 0 -26 5       <56>   Upv#1@_ENV["PosMonKOOK"] = R5                   -- It's Const#26
		  +4B67: 46 C1 46 00   line#77   GETTABUP 5 0 -28       <57>   R5 = Upv#1@_ENV["topos"]                        -- It's Const#28
		  +4B6B: 87 81 42 02   line#77   GETTABLE 6 4 -11       <58>   R6 = R4@v["HumanoidRootPart"]                   -- It's Const#11
		  +4B6F: 87 81 46 03   line#77   GETTABLE 6 6 -27       <59>   R6 = R6["CFrame"]                               -- It's Const#27
		  +4B73: C6 81 46 00   line#77   GETTABUP 7 0 -27       <60>   R7 = Upv#1@_ENV["CFrame"]                       -- It's Const#27
		  +4B77: C7 01 C7 03   line#77   GETTABLE 7 7 -29       <61>   R7 = R7["new"]                                  -- It's Const#29
		  +4B7B: 01 42 07 00   line#77   LOADK 8 -30            <62>   R8 = 2                                          -- It's Const#30
		  +4B7F: 41 82 07 00   line#77   LOADK 9 -31            <63>   R9 = 20                                         -- It's Const#31
		  +4B83: 81 42 07 00   line#77   LOADK 10 -30           <64>   R10 = 2                                         -- It's Const#30
		  +4B87: E4 81 00 02   line#77   CALL 7 4 2             <65>   R7 = R7(R8, R9, R10)
		  +4B8B: 8F C1 01 03   line#77   MUL 6 6 7              <66>   R6 = R6 * R7
		  +4B8F: 64 41 00 01   line#77   CALL 5 2 1             <67>   R5(R6)
		  +4B93: 46 01 40 00   line#78   GETTABUP 5 0 -1        <68>   R5 = Upv#1@_ENV["game"]                         -- It's Const#1
		  +4B97: 4C 41 C0 02   line#78   SELF 5 5 -2            <69>   R6 = R5;  R5 = R5["GetService"]                 -- It's Const#2   -- prepare for R5:GetService()
		  +4B9B: C1 C1 07 00   line#78   LOADK 7 -32            <70>   R7 = "VirtualUser"                              -- It's Const#32
		  +4B9F: 64 81 80 01   line#78   CALL 5 3 2             <71>   R5 = R5(R6, R7)
		  +4BA3: 4C 01 C8 02   line#78   SELF 5 5 -33           <72>   R6 = R5;  R5 = R5["CaptureController"]          -- It's Const#33   -- prepare for R5:CaptureController()
		  +4BA7: 64 41 00 01   line#78   CALL 5 2 1             <73>   R5(R6)
		  +4BAB: 46 01 40 00   line#79   GETTABUP 5 0 -1        <74>   R5 = Upv#1@_ENV["game"]                         -- It's Const#1
		  +4BAF: 4C 41 C0 02   line#79   SELF 5 5 -2            <75>   R6 = R5;  R5 = R5["GetService"]                 -- It's Const#2   -- prepare for R5:GetService()
		  +4BB3: C1 C1 07 00   line#79   LOADK 7 -32            <76>   R7 = "VirtualUser"                              -- It's Const#32
		  +4BB7: 64 81 80 01   line#79   CALL 5 3 2             <77>   R5 = R5(R6, R7)
		  +4BBB: 4C 41 C8 02   line#79   SELF 5 5 -34           <78>   R6 = R5;  R5 = R5["Button1Down"]                -- It's Const#34   -- prepare for R5:Button1Down()
		  +4BBF: C6 81 48 00   line#79   GETTABUP 7 0 -35       <79>   R7 = Upv#1@_ENV["Vector2"]                      -- It's Const#35
		  +4BC3: C7 01 C7 03   line#79   GETTABLE 7 7 -29       <80>   R7 = R7["new"]                                  -- It's Const#29
		  +4BC7: 01 C2 08 00   line#79   LOADK 8 -36            <81>   R8 = 1280                                       -- It's Const#36
		  +4BCB: 41 02 09 00   line#79   LOADK 9 -37            <82>   R9 = 672                                        -- It's Const#37
		  +4BCF: E4 01 80 01   line#79   CALL 7 3 0             <83>   R7,.. = R7(R8, R9)
		  +4BD3: 64 41 00 00   line#79   CALL 5 0 1             <84>   R5(R6,..)
		  +4BD7: 46 41 44 00   line#80   GETTABUP 5 0 -18       <85>   R5 = Upv#1@_ENV["_G"]                           -- It's Const#18
		  +4BDB: 47 41 C9 02   line#80   GETTABLE 5 5 -38       <86>   R5 = R5["Auto_Farm_Kill"]                       -- It's Const#38
		  +4BDF: 62 01 00 00   line#80   TEST 5 0               <87>   if R5 then GOTO <89>
		  +4BE3: 1E 80 01 80   line#80   JMP 0 7                <88>   GOTO <96>
		  +4BE7: 47 81 49 02   line#80   GETTABLE 5 4 -39       <89>   R5 = R4@v["Parent"]                             -- It's Const#39
		  +4BEB: 62 01 00 00   line#80   TEST 5 0               <90>   if R5 then GOTO <92>
		  +4BEF: 1E C0 00 80   line#80   JMP 0 4                <91>   GOTO <96>
		  +4BF3: 47 41 42 02   line#80   GETTABLE 5 4 -10       <92>   R5 = R4@v["Humanoid"]                           -- It's Const#10
		  +4BF7: 47 C1 C2 02   line#80   GETTABLE 5 5 -12       <93>   R5 = R5["Health"]                               -- It's Const#12
		  +4BFB: 21 00 C3 02   line#80   LE 0 5 -13             <94>   if R5 <= 0 then GOTO <96>                       -- It's Const#13
		  +4BFF: 1E 40 F1 7F   line#80   JMP 0 -58              <95>   GOTO <38>
		  +4C03: 29 80 00 00   line#66   TFORCALL 0 2           <96>   R3, R4 = R0(R1, R2)
		  +4C07: AA 80 EC 7F   line#66   TFORLOOP 2 -77         <97>   if R3 ~= nil then { R2 = R3;  GOTO <21> }       -- end of loop
		  +4C0B: 1E 40 06 80   line#83   JMP 0 26               <98>   GOTO <125>
		  +4C0F: 08 00 C5 8B   line#85   SETTABUP 0 -24 -21     <99>   Upv#1@_ENV["StartMagnetKOOK"] = false           -- It's Const#24, Const#21
		  +4C13: 06 80 41 00   line#86   GETTABUP 0 0 -7       <100>   R0 = Upv#1@_ENV["pairs"]                        -- It's Const#7
		  +4C17: 46 00 40 00   line#86   GETTABUP 1 0 -1       <101>   R1 = Upv#1@_ENV["game"]                         -- It's Const#1
		  +4C1B: 4C 40 C0 00   line#86   SELF 1 1 -2           <102>   R2 = R1;  R1 = R1["GetService"]                 -- It's Const#2   -- prepare for R1:GetService()
		  +4C1F: C1 C0 09 00   line#86   LOADK 3 -40           <103>   R3 = "ReplicatedStorage"                        -- It's Const#40
		  +4C23: 64 80 80 01   line#86   CALL 1 3 2            <104>   R1 = R1(R2, R3)
		  +4C27: 4C C0 C1 00   line#86   SELF 1 1 -8           <105>   R2 = R1;  R1 = R1["GetChildren"]                -- It's Const#8   -- prepare for R1:GetChildren()
		  +4C2B: 64 00 00 01   line#86   CALL 1 2 0            <106>   R1,.. = R1(R2)
		  +4C2F: 24 00 01 00   line#86   CALL 0 0 4            <107>   R0, R1, R2 = R0(R1,..)
		  +4C33: 1E 40 03 80   line#86   JMP 0 14              <108>   GOTO <123>                                      -- for R3@i, R4@v in R0, R1, R2 do
		  +4C37: 47 01 42 02   line#87   GETTABLE 5 4 -9       <109>   R5 = R4@v["Name"]                               -- It's Const#9
		  +4C3B: 1F 40 C1 02   line#87   EQ 0 5 -6             <110>   if R5 == "Royal Squad [Lv. 525]" then GOTO <112>   -- It's Const#6
		  +4C3F: 1E 80 02 80   line#87   JMP 0 11              <111>   GOTO <123>
		  +4C43: 46 C1 46 00   line#88   GETTABUP 5 0 -28      <112>   R5 = Upv#1@_ENV["topos"]                        -- It's Const#28
		  +4C47: 87 81 42 02   line#88   GETTABLE 6 4 -11      <113>   R6 = R4@v["HumanoidRootPart"]                   -- It's Const#11
		  +4C4B: 87 81 46 03   line#88   GETTABLE 6 6 -27      <114>   R6 = R6["CFrame"]                               -- It's Const#27
		  +4C4F: C6 81 46 00   line#88   GETTABUP 7 0 -27      <115>   R7 = Upv#1@_ENV["CFrame"]                       -- It's Const#27
		  +4C53: C7 01 C7 03   line#88   GETTABLE 7 7 -29      <116>   R7 = R7["new"]                                  -- It's Const#29
		  +4C57: 01 42 07 00   line#88   LOADK 8 -30           <117>   R8 = 2                                          -- It's Const#30
		  +4C5B: 41 82 07 00   line#88   LOADK 9 -31           <118>   R9 = 20                                         -- It's Const#31
		  +4C5F: 81 42 07 00   line#88   LOADK 10 -30          <119>   R10 = 2                                         -- It's Const#30
		  +4C63: E4 81 00 02   line#88   CALL 7 4 2            <120>   R7 = R7(R8, R9, R10)
		  +4C67: 8F C1 01 03   line#88   MUL 6 6 7             <121>   R6 = R6 * R7
		  +4C6B: 64 41 00 01   line#88   CALL 5 2 1            <122>   R5(R6)
		  +4C6F: 29 80 00 00   line#86   TFORCALL 0 2          <123>   R3, R4 = R0(R1, R2)
		  +4C73: AA C0 FB 7F   line#86   TFORLOOP 2 -16        <124>   if R3 ~= nil then { R2 = R3;  GOTO <109> }      -- end of loop
		  +4C77: 26 00 80 00   line#92   RETURN 0 1            <125>   RETURN
		Functions: 0

	************ Function#2   (full path: main.2)
	Source line#: 549..609
	Parameters: 0
	Is vararg: no
	VM registers needed: 6
	Constants: 9
	  +7741:Size=4: 67 61 6D 65                     Const#1   string    "game"
	  +7747:Size=7: 50 6C 61 63 65 49 64            Const#2   string    "PlaceId"
	  +7750:Size=0:                                 Const#3   string    ""
	  +7752:Size=2: 6F 73                           Const#4   string    "os"
	  +7756:Size=4: 64 61 74 65                     Const#5   string    "date"
	  +775C:Size=3: 21 2A 74                        Const#6   string    "!*t"
	  +7761:Size=4: 68 6F 75 72                     Const#7   string    "hour"
	  +7767:Size=A: 54 50 52 65 74 75 72 6E 65 72   Const#8   string    "TPReturner"
	  +7773:Size=8: 54 65 6C 65 70 6F 72 74         Const#9   string    "Teleport"
	Upvalues: 1
	  Upv#1 is parent function's Upv#1              name: _ENV
	Locals: 5
	  Local#1   R0   def:<2>    scope:<3..17>       name: PlaceID
	  Local#2   R1   def:<3>    scope:<4..17>       name: AllIDs
	  Local#3   R2   def:<4>    scope:<5..17>       name: foundAnything
	  Local#4   R3   def:<9>    scope:<10..17>      name: actualHour
	  Local#5   R4   def:<10>   scope:<11..17>      name: Deleted
	Instructions: 17
	  +76F7: 06 00 40 00   line#550  GETTABUP 0 0 -1         <1>   R0 = Upv#1@_ENV["game"]                         -- It's Const#1
	  +76FB: 07 40 40 00   line#550  GETTABLE 0 0 -2         <2>   R0@PlaceID = R0["PlaceId"]                      -- It's Const#2
	  +76FF: 4B 00 00 00   line#551  NEWTABLE 1 0 0          <3>   R1@AllIDs = {}  arr:0, hash:0
	  +7703: 81 80 00 00   line#552  LOADK 2 -3              <4>   R2@foundAnything = ""                           -- It's Const#3
	  +7707: C6 C0 40 00   line#553  GETTABUP 3 0 -4         <5>   R3 = Upv#1@_ENV["os"]                           -- It's Const#4
	  +770B: C7 00 C1 01   line#553  GETTABLE 3 3 -5         <6>   R3 = R3["date"]                                 -- It's Const#5
	  +770F: 01 41 01 00   line#553  LOADK 4 -6              <7>   R4 = "!*t"                                      -- It's Const#6
	  +7713: E4 80 00 01   line#553  CALL 3 2 2              <8>   R3 = R3(R4)
	  +7717: C7 80 C1 01   line#553  GETTABLE 3 3 -7         <9>   R3@actualHour = R3["hour"]                      -- It's Const#7
	  +771B: 03 01 00 00   line#554  LOADBOOL 4 0 0         <10>   R4@Deleted = false
	  +771F: 6C 01 00 00   line#597  CLOSURE 5 0            <11>   R5 = Function#1
	  +7723: 08 40 81 83   line#555  SETTABUP 0 -8 5        <12>   Upv#1@_ENV["TPReturner"] = R5                   -- It's Const#8
	  +7727: 6C 41 00 00   line#607  CLOSURE 5 1            <13>   R5 = Function#2
	  +772B: 08 40 01 84   line#598  SETTABUP 0 -9 5        <14>   Upv#1@_ENV["Teleport"] = R5                     -- It's Const#9
	  +772F: 46 01 42 00   line#608  GETTABUP 5 0 -9        <15>   R5 = Upv#1@_ENV["Teleport"]                     -- It's Const#9
	  +7733: 64 41 80 00   line#608  CALL 5 1 1             <16>   R5()
	  +7737: 26 00 80 00   line#609  RETURN 0 1             <17>   RETURN
	Functions: 2

		************ Function#1   (full path: main.2.1)
		Source line#: 555..597
		Parameters: 0
		Is vararg: no
		VM registers needed: 17
		Constants: 27
		  +793F:Size=0:                                 Const#1   string    ""
		  +7941:Size=4: 67 61 6D 65                     Const#2   string    "game"
		  +7947:Size=B: 48 74 74 70 53 65 72 76 69...   Const#3   string    "HttpService"
		  +7954:Size=A: 4A 53 4F 4E 44 65 63 6F 64 65   Const#4   string    "JSONDecode"
		  +7960:Size=7: 48 74 74 70 47 65 74            Const#5   string    "HttpGet"
		  +7969:Size=22: 68 74 74 70 73 3A 2F 2F 6...   Const#6   string    "https://games.roblox.com/v1/games/"
		  +798D:Size=27: 2F 73 65 72 76 65 72 73 2...   Const#7   string    "/servers/Public?sortOrder=Asc&limit=100"
		  +79B6:Size=2F: 2F 73 65 72 76 65 72 73 2...   Const#8   string    "/servers/Public?sortOrder=Asc&limit=100&cursor="
		  +79E7:Size=E: 6E 65 78 74 50 61 67 65 43...   Const#9   string    "nextPageCursor"
		  +79F7:Size=4: 6E 75 6C 6C                     Const#10  string    "null"
		  +79FC:Size=0:                                 Const#11  nil       nil
		  +79FD:Size=4: 00 00 00 00                     Const#12  integer   0
		  +7A03:Size=5: 70 61 69 72 73                  Const#13  string    "pairs"
		  +7A0A:Size=4: 64 61 74 61                     Const#14  string    "data"
		  +7A10:Size=8: 74 6F 73 74 72 69 6E 67         Const#15  string    "tostring"
		  +7A1A:Size=2: 69 64                           Const#16  string    "id"
		  +7A1E:Size=8: 74 6F 6E 75 6D 62 65 72         Const#17  string    "tonumber"
		  +7A28:Size=A: 6D 61 78 50 6C 61 79 65 72 73   Const#18  string    "maxPlayers"
		  +7A34:Size=7: 70 6C 61 79 69 6E 67            Const#19  string    "playing"
		  +7A3D:Size=5: 70 63 61 6C 6C                  Const#20  string    "pcall"
		  +7A43:Size=4: 01 00 00 00                     Const#21  integer   1
		  +7A48:Size=1: 01                              Const#22  boolean   true
		  +7A4B:Size=5: 74 61 62 6C 65                  Const#23  string    "table"
		  +7A52:Size=6: 69 6E 73 65 72 74               Const#24  string    "insert"
		  +7A5A:Size=4: 77 61 69 74                     Const#25  string    "wait"
		  +7A60:Size=4: 77 61 69 74                     Const#26  string    "wait"
		  +7A65:Size=4: 04 00 00 00                     Const#27  integer   4
		Upvalues: 5
		  Upv#1 is parent function's R2                 name: foundAnything
		  Upv#2 is parent function's Upv#1              name: _ENV
		  Upv#3 is parent function's R0                 name: PlaceID
		  Upv#4 is parent function's R1                 name: AllIDs
		  Upv#5 is parent function's R3                 name: actualHour
		Locals: 15
		  Local#1   R0   def:<1>    scope:<2..105>      name: Site
		  Local#2   R1   def:<31>   scope:<32..105>     name: ID
		  Local#3   R2   def:<43>   scope:<44..105>     name: num
		  Local#4   R3   def:<46>   scope:<47..104>     name: (for generator)
		  Local#5   R4   def:<46>   scope:<47..104>     name: (for state)
		  Local#6   R5   def:<46>   scope:<47..104>     name: (for control)
		  Local#7   R6   def:<47>   scope:<48..102>     name: i
		  Local#8   R7   def:<47>   scope:<48..102>     name: v
		  Local#9   R8   def:<48>   scope:<49..102>     name: Possible
		  Local#10  R9   def:<63>   scope:<64..87>      name: (for generator)
		  Local#11  R10  def:<63>   scope:<64..87>      name: (for state)
		  Local#12  R11  def:<63>   scope:<64..87>      name: (for control)
		  Local#13  R12  def:<64>   scope:<65..85>      name: _
		  Local#14  R13  def:<64>   scope:<65..85>      name: Existing
		  Local#15  R14  def:<84>   scope:<>            name: delFile
		Instructions: 105
		  +7795: 04 00 00 00   line#556  LOADNIL 0 0             <1>   R0@Site = nil
		  +7799: 45 00 00 00   line#557  GETUPVAL 1 0            <2>   R1 = Upv#1@foundAnything
		  +779D: 1F 00 C0 00   line#557  EQ 0 1 -1               <3>   if R1 == "" then GOTO <5>                       -- It's Const#1
		  +77A1: 1E 00 03 80   line#557  JMP 0 13                <4>   GOTO <18>
		  +77A5: 46 40 C0 00   line#558  GETTABUP 1 1 -2         <5>   R1 = Upv#2@_ENV["game"]                         -- It's Const#2
		  +77A9: 47 80 C0 00   line#558  GETTABLE 1 1 -3         <6>   R1 = R1["HttpService"]                          -- It's Const#3
		  +77AD: 4C C0 C0 00   line#558  SELF 1 1 -4             <7>   R2 = R1;  R1 = R1["JSONDecode"]                 -- It's Const#4   -- prepare for R1:JSONDecode()
		  +77B1: C6 40 C0 00   line#558  GETTABUP 3 1 -2         <8>   R3 = Upv#2@_ENV["game"]                         -- It's Const#2
		  +77B5: CC 00 C1 01   line#558  SELF 3 3 -5             <9>   R4 = R3;  R3 = R3["HttpGet"]                    -- It's Const#5   -- prepare for R3:HttpGet()
		  +77B9: 41 41 01 00   line#558  LOADK 5 -6             <10>   R5 = "https://games.roblox.com/v1/games/"       -- It's Const#6
		  +77BD: 85 01 00 01   line#558  GETUPVAL 6 2           <11>   R6 = Upv#3@PlaceID
		  +77C1: C1 81 01 00   line#558  LOADK 7 -7             <12>   R7 = "/servers/Public?sortOrder=Asc&limit=100"   -- It's Const#7
		  +77C5: 5D C1 81 02   line#558  CONCAT 5 5 7           <13>   R5 = R5..R6..R7
		  +77C9: E4 00 80 01   line#558  CALL 3 3 0             <14>   R3,.. = R3(R4, R5)
		  +77CD: 64 80 00 00   line#558  CALL 1 0 2             <15>   R1 = R1(R2,..)
		  +77D1: 00 00 80 00   line#558  MOVE 0 1               <16>   R0@Site = R1
		  +77D5: 1E 00 03 80   line#558  JMP 0 13               <17>   GOTO <31>
		  +77D9: 46 40 C0 00   line#560  GETTABUP 1 1 -2        <18>   R1 = Upv#2@_ENV["game"]                         -- It's Const#2
		  +77DD: 47 80 C0 00   line#560  GETTABLE 1 1 -3        <19>   R1 = R1["HttpService"]                          -- It's Const#3
		  +77E1: 4C C0 C0 00   line#560  SELF 1 1 -4            <20>   R2 = R1;  R1 = R1["JSONDecode"]                 -- It's Const#4   -- prepare for R1:JSONDecode()
		  +77E5: C6 40 C0 00   line#560  GETTABUP 3 1 -2        <21>   R3 = Upv#2@_ENV["game"]                         -- It's Const#2
		  +77E9: CC 00 C1 01   line#560  SELF 3 3 -5            <22>   R4 = R3;  R3 = R3["HttpGet"]                    -- It's Const#5   -- prepare for R3:HttpGet()
		  +77ED: 41 41 01 00   line#560  LOADK 5 -6             <23>   R5 = "https://games.roblox.com/v1/games/"       -- It's Const#6
		  +77F1: 85 01 00 01   line#560  GETUPVAL 6 2           <24>   R6 = Upv#3@PlaceID
		  +77F5: C1 C1 01 00   line#560  LOADK 7 -8             <25>   R7 = "/servers/Public?sortOrder=Asc&limit=100&cursor="   -- It's Const#8
		  +77F9: 05 02 00 00   line#560  GETUPVAL 8 0           <26>   R8 = Upv#1@foundAnything
		  +77FD: 5D 01 82 02   line#560  CONCAT 5 5 8           <27>   R5 = R5..R6..R7..R8
		  +7801: E4 00 80 01   line#560  CALL 3 3 0             <28>   R3,.. = R3(R4, R5)
		  +7805: 64 80 00 00   line#560  CALL 1 0 2             <29>   R1 = R1(R2,..)
		  +7809: 00 00 80 00   line#560  MOVE 0 1               <30>   R0@Site = R1
		  +780D: 41 00 00 00   line#562  LOADK 1 -1             <31>   R1@ID = ""                                      -- It's Const#1
		  +7811: 87 00 42 00   line#563  GETTABLE 2 0 -9        <32>   R2 = R0@Site["nextPageCursor"]                  -- It's Const#9
		  +7815: A2 00 00 00   line#563  TEST 2 0               <33>   if R2 then GOTO <35>
		  +7819: 1E C0 01 80   line#563  JMP 0 8                <34>   GOTO <43>
		  +781D: 87 00 42 00   line#563  GETTABLE 2 0 -9        <35>   R2 = R0@Site["nextPageCursor"]                  -- It's Const#9
		  +7821: 5F 40 42 01   line#563  EQ 1 2 -10             <36>   if R2 ~= "null" then GOTO <38>                  -- It's Const#10
		  +7825: 1E 00 01 80   line#563  JMP 0 5                <37>   GOTO <43>
		  +7829: 87 00 42 00   line#563  GETTABLE 2 0 -9        <38>   R2 = R0@Site["nextPageCursor"]                  -- It's Const#9
		  +782D: 5F 80 42 01   line#563  EQ 1 2 -11             <39>   if R2 ~= nil then GOTO <41>                     -- It's Const#11
		  +7831: 1E 40 00 80   line#563  JMP 0 2                <40>   GOTO <43>
		  +7835: 87 00 42 00   line#564  GETTABLE 2 0 -9        <41>   R2 = R0@Site["nextPageCursor"]                  -- It's Const#9
		  +7839: 89 00 00 00   line#564  SETUPVAL 2 0           <42>   Upv#1@foundAnything = R2
		  +783D: 81 C0 02 00   line#566  LOADK 2 -12            <43>   R2@num = 0                                      -- It's Const#12
		  +7841: C6 00 C3 00   line#567  GETTABUP 3 1 -13       <44>   R3 = Upv#2@_ENV["pairs"]                        -- It's Const#13
		  +7845: 07 41 43 00   line#567  GETTABLE 4 0 -14       <45>   R4 = R0@Site["data"]                            -- It's Const#14
		  +7849: E4 00 01 01   line#567  CALL 3 2 4             <46>   R3, R4, R5 = R3(R4)
		  +784D: 1E 80 0D 80   line#567  JMP 0 55               <47>   GOTO <103>                                      -- for R6@i, R7@v in R3, R4, R5 do
		  +7851: 03 02 80 00   line#568  LOADBOOL 8 1 0         <48>   R8@Possible = true
		  +7855: 46 82 C3 00   line#569  GETTABUP 9 1 -15       <49>   R9 = Upv#2@_ENV["tostring"]                     -- It's Const#15
		  +7859: 87 C2 C3 03   line#569  GETTABLE 10 7 -16      <50>   R10 = R7@v["id"]                                -- It's Const#16
		  +785D: 64 82 00 01   line#569  CALL 9 2 2             <51>   R9 = R9(R10)
		  +7861: 40 00 80 04   line#569  MOVE 1 9               <52>   R1@ID = R9
		  +7865: 46 02 C4 00   line#570  GETTABUP 9 1 -17       <53>   R9 = Upv#2@_ENV["tonumber"]                     -- It's Const#17
		  +7869: 87 42 C4 03   line#570  GETTABLE 10 7 -18      <54>   R10 = R7@v["maxPlayers"]                        -- It's Const#18
		  +786D: 64 82 00 01   line#570  CALL 9 2 2             <55>   R9 = R9(R10)
		  +7871: 86 02 C4 00   line#570  GETTABUP 10 1 -17      <56>   R10 = Upv#2@_ENV["tonumber"]                    -- It's Const#17
		  +7875: C7 82 C4 03   line#570  GETTABLE 11 7 -19      <57>   R11 = R7@v["playing"]                           -- It's Const#19
		  +7879: A4 82 00 01   line#570  CALL 10 2 2            <58>   R10 = R10(R11)
		  +787D: 20 40 02 05   line#570  LT 0 10 9              <59>   if R10 < R9 then GOTO <61>
		  +7881: 1E 40 0A 80   line#570  JMP 0 42               <60>   GOTO <103>
		  +7885: 46 02 C3 00   line#571  GETTABUP 9 1 -13       <61>   R9 = Upv#2@_ENV["pairs"]                        -- It's Const#13
		  +7889: 85 02 80 01   line#571  GETUPVAL 10 3          <62>   R10 = Upv#4@AllIDs
		  +788D: 64 02 01 01   line#571  CALL 9 2 4             <63>   R9, R10, R11 = R9(R10)
		  +7891: 1E 00 05 80   line#571  JMP 0 21               <64>   GOTO <86>                                       -- for R12@_, R13@Existing in R9, R10, R11 do
		  +7895: 5F C0 42 01   line#572  EQ 1 2 -12             <65>   if R2@num ~= 0 then GOTO <67>                   -- It's Const#12
		  +7899: 1E 80 01 80   line#572  JMP 0 7                <66>   GOTO <74>
		  +789D: 86 83 C3 00   line#573  GETTABUP 14 1 -15      <67>   R14 = Upv#2@_ENV["tostring"]                    -- It's Const#15
		  +78A1: C0 03 80 06   line#573  MOVE 15 13             <68>   R15 = R13@Existing
		  +78A5: A4 83 00 01   line#573  CALL 14 2 2            <69>   R14 = R14(R15)
		  +78A9: 1F 80 83 00   line#573  EQ 0 1 14              <70>   if R1@ID == R14 then GOTO <72>
		  +78AD: 1E 00 03 80   line#573  JMP 0 13               <71>   GOTO <85>
		  +78B1: 03 02 00 00   line#574  LOADBOOL 8 0 0         <72>   R8@Possible = false
		  +78B5: 1E 80 02 80   line#575  JMP 0 11               <73>   GOTO <85>
		  +78B9: 86 03 C4 00   line#577  GETTABUP 14 1 -17      <74>   R14 = Upv#2@_ENV["tonumber"]                    -- It's Const#17
		  +78BD: C5 03 00 02   line#577  GETUPVAL 15 4          <75>   R15 = Upv#5@actualHour
		  +78C1: A4 83 00 01   line#577  CALL 14 2 2            <76>   R14 = R14(R15)
		  +78C5: C6 03 C4 00   line#577  GETTABUP 15 1 -17      <77>   R15 = Upv#2@_ENV["tonumber"]                    -- It's Const#17
		  +78C9: 00 04 80 06   line#577  MOVE 16 13             <78>   R16 = R13@Existing
		  +78CD: E4 83 00 01   line#577  CALL 15 2 2            <79>   R15 = R15(R16)
		  +78D1: 5F C0 03 07   line#577  EQ 1 14 15             <80>   if R14 ~= R15 then GOTO <82>
		  +78D5: 1E 80 00 80   line#577  JMP 0 3                <81>   GOTO <85>
		  +78D9: 86 C3 C4 00   line#578  GETTABUP 14 1 -20      <82>   R14 = Upv#2@_ENV["pcall"]                       -- It's Const#20
		  +78DD: EC 03 00 00   line#581  CLOSURE 15 0           <83>   R15 = Function#1
		  +78E1: A4 83 00 01   line#578  CALL 14 2 2            <84>   R14@delFile = R14(R15)
		  +78E5: 8D 00 45 01   line#584  ADD 2 2 -21            <85>   R2@num = R2@num + 1                             -- It's Const#21
		  +78E9: 69 82 00 00   line#571  TFORCALL 9 2           <86>   R12, R13 = R9(R10, R11)
		  +78ED: EA 02 FA 7F   line#571  TFORLOOP 11 -23        <87>   if R12 ~= nil then { R11 = R12;  GOTO <65> }    -- end of loop
		  +78F1: 1F 40 45 04   line#586  EQ 0 8 -22             <88>   if R8@Possible == true then GOTO <90>           -- It's Const#22
		  +78F5: 1E 00 03 80   line#586  JMP 0 13               <89>   GOTO <103>
		  +78F9: 46 82 C5 00   line#587  GETTABUP 9 1 -23       <90>   R9 = Upv#2@_ENV["table"]                        -- It's Const#23
		  +78FD: 47 C2 C5 04   line#587  GETTABLE 9 9 -24       <91>   R9 = R9["insert"]                               -- It's Const#24
		  +7901: 85 02 80 01   line#587  GETUPVAL 10 3          <92>   R10 = Upv#4@AllIDs
		  +7905: C0 02 80 00   line#587  MOVE 11 1              <93>   R11 = R1@ID
		  +7909: 64 42 80 01   line#587  CALL 9 3 1             <94>   R9(R10, R11)
		  +790D: 46 02 C6 00   line#588  GETTABUP 9 1 -25       <95>   R9 = Upv#2@_ENV["wait"]                         -- It's Const#25
		  +7911: 64 42 80 00   line#588  CALL 9 1 1             <96>   R9()
		  +7915: 46 C2 C4 00   line#589  GETTABUP 9 1 -20       <97>   R9 = Upv#2@_ENV["pcall"]                        -- It's Const#20
		  +7919: AC 42 00 00   line#592  CLOSURE 10 1           <98>   R10 = Function#2
		  +791D: 64 42 00 01   line#589  CALL 9 2 1             <99>   R9(R10)
		  +7921: 46 42 C6 00   line#593  GETTABUP 9 1 -26      <100>   R9 = Upv#2@_ENV["wait"]                         -- It's Const#26
		  +7925: 81 82 06 00   line#593  LOADK 10 -27          <101>   R10 = 4                                         -- It's Const#27
		  +7929: 64 42 00 01   line#593  CALL 9 2 1            <102>   R9(R10)
		  +792D: E9 80 00 00   line#567  TFORCALL 3 2          <103>   R6, R7 = R3(R4, R5)
		  +7931: 6A 81 F1 7F   line#567  TFORLOOP 5 -57        <104>   if R6 ~= nil then { R5 = R6;  GOTO <48> }       -- end of loop
		  +7935: 26 00 80 00   line#597  RETURN 0 1            <105>   RETURN
		Functions: 2

			************ Function#1   (full path: main.2.1.1)
			Source line#: 578..581
			Parameters: 0
			Is vararg: no
			VM registers needed: 3
			Constants: 2
			  +7AB1:Size=5: 74 61 62 6C 65                  Const#1   string    "table"
			  +7AB8:Size=6: 69 6E 73 65 72 74               Const#2   string    "insert"
			Upvalues: 3
			  Upv#1 is parent function's Upv#4              name: AllIDs
			  Upv#2 is parent function's Upv#2              name: _ENV
			  Upv#3 is parent function's Upv#5              name: actualHour
			Instructions: 8
			  +7A8B: 0B 00 00 00   line#579  NEWTABLE 0 0 0          <1>   R0 = {}  arr:0, hash:0
			  +7A8F: 09 00 00 00   line#579  SETUPVAL 0 0            <2>   Upv#1@AllIDs = R0
			  +7A93: 06 00 C0 00   line#580  GETTABUP 0 1 -1         <3>   R0 = Upv#2@_ENV["table"]                        -- It's Const#1
			  +7A97: 07 40 40 00   line#580  GETTABLE 0 0 -2         <4>   R0 = R0["insert"]                               -- It's Const#2
			  +7A9B: 45 00 00 00   line#580  GETUPVAL 1 0            <5>   R1 = Upv#1@AllIDs
			  +7A9F: 85 00 00 01   line#580  GETUPVAL 2 2            <6>   R2 = Upv#3@actualHour
			  +7AA3: 24 40 80 01   line#580  CALL 0 3 1              <7>   R0(R1, R2)
			  +7AA7: 26 00 80 00   line#581  RETURN 0 1              <8>   RETURN
			Functions: 0

			************ Function#2   (full path: main.2.1.2)
			Source line#: 589..592
			Parameters: 0
			Is vararg: no
			VM registers needed: 5
			Constants: 7
			  +7B5D:Size=4: 77 61 69 74                     Const#1   string    "wait"
			  +7B63:Size=4: 67 61 6D 65                     Const#2   string    "game"
			  +7B69:Size=A: 47 65 74 53 65 72 76 69 63 65   Const#3   string    "GetService"
			  +7B75:Size=F: 54 65 6C 65 70 6F 72 74 53...   Const#4   string    "TeleportService"
			  +7B86:Size=17: 54 65 6C 65 70 6F 72 74 5...   Const#5   string    "TeleportToPlaceInstance"
			  +7B9F:Size=7: 50 6C 61 79 65 72 73            Const#6   string    "Players"
			  +7BA8:Size=B: 4C 6F 63 61 6C 50 6C 61 79...   Const#7   string    "LocalPlayer"
			Upvalues: 3
			  Upv#1 is parent function's Upv#2              name: _ENV
			  Upv#2 is parent function's Upv#3              name: PlaceID
			  Upv#3 is parent function's R1                 name: ID
			Instructions: 14
			  +7B1F: 06 00 40 00   line#590  GETTABUP 0 0 -1         <1>   R0 = Upv#1@_ENV["wait"]                         -- It's Const#1
			  +7B23: 24 40 80 00   line#590  CALL 0 1 1              <2>   R0()
			  +7B27: 06 40 40 00   line#591  GETTABUP 0 0 -2         <3>   R0 = Upv#1@_ENV["game"]                         -- It's Const#2
			  +7B2B: 0C 80 40 00   line#591  SELF 0 0 -3             <4>   R1 = R0;  R0 = R0["GetService"]                 -- It's Const#3   -- prepare for R0:GetService()
			  +7B2F: 81 C0 00 00   line#591  LOADK 2 -4              <5>   R2 = "TeleportService"                          -- It's Const#4
			  +7B33: 24 80 80 01   line#591  CALL 0 3 2              <6>   R0 = R0(R1, R2)
			  +7B37: 0C 00 41 00   line#591  SELF 0 0 -5             <7>   R1 = R0;  R0 = R0["TeleportToPlaceInstance"]    -- It's Const#5   -- prepare for R0:TeleportToPlaceInstance()
			  +7B3B: 85 00 80 00   line#591  GETUPVAL 2 1            <8>   R2 = Upv#2@PlaceID
			  +7B3F: C5 00 00 01   line#591  GETUPVAL 3 2            <9>   R3 = Upv#3@ID
			  +7B43: 06 41 40 00   line#591  GETTABUP 4 0 -2        <10>   R4 = Upv#1@_ENV["game"]                         -- It's Const#2
			  +7B47: 07 41 41 02   line#591  GETTABLE 4 4 -6        <11>   R4 = R4["Players"]                              -- It's Const#6
			  +7B4B: 07 81 41 02   line#591  GETTABLE 4 4 -7        <12>   R4 = R4["LocalPlayer"]                          -- It's Const#7
			  +7B4F: 24 40 80 02   line#591  CALL 0 5 1             <13>   R0(R1,..,R4)
			  +7B53: 26 00 80 00   line#592  RETURN 0 1             <14>   RETURN
			Functions: 0

		************ Function#2   (full path: main.2.2)
		Source line#: 598..607
		Parameters: 0
		Is vararg: no
		VM registers needed: 2
		Constants: 2
		  +7F24:Size=4: 77 61 69 74                     Const#1   string    "wait"
		  +7F2A:Size=5: 70 63 61 6C 6C                  Const#2   string    "pcall"
		Upvalues: 2
		  Upv#1 is parent function's Upv#1              name: _ENV
		  Upv#2 is parent function's R2                 name: foundAnything
		Instructions: 9
		  +7EFA: 06 00 40 00   line#599  GETTABUP 0 0 -1         <1>   R0 = Upv#1@_ENV["wait"]                         -- It's Const#1
		  +7EFE: 24 80 80 00   line#599  CALL 0 1 2              <2>   R0 = R0()
		  +7F02: 22 00 00 00   line#599  TEST 0 0                <3>   if R0 then GOTO <5>
		  +7F06: 1E C0 00 80   line#599  JMP 0 4                 <4>   GOTO <9>
		  +7F0A: 06 40 40 00   line#600  GETTABUP 0 0 -2         <5>   R0 = Upv#1@_ENV["pcall"]                        -- It's Const#2
		  +7F0E: 6C 00 00 00   line#605  CLOSURE 1 0             <6>   R1 = Function#1
		  +7F12: 24 40 00 01   line#600  CALL 0 2 1              <7>   R0(R1)
		  +7F16: 1E C0 FD 7F   line#605  JMP 0 -8                <8>   GOTO <1>
		  +7F1A: 26 00 80 00   line#607  RETURN 0 1              <9>   RETURN
		Functions: 1

			************ Function#1   (full path: main.2.2.1)
			Source line#: 600..605
			Parameters: 0
			Is vararg: no
			VM registers needed: 2
			Constants: 2
			  +7F71:Size=A: 54 50 52 65 74 75 72 6E 65 72   Const#1   string    "TPReturner"
			  +7F7D:Size=0:                                 Const#2   string    ""
			Upvalues: 2
			  Upv#1 is parent function's Upv#1              name: _ENV
			  Upv#2 is parent function's Upv#2              name: foundAnything
			Instructions: 8
			  +7F4B: 06 00 40 00   line#601  GETTABUP 0 0 -1         <1>   R0 = Upv#1@_ENV["TPReturner"]                   -- It's Const#1
			  +7F4F: 24 40 80 00   line#601  CALL 0 1 1              <2>   R0()
			  +7F53: 05 00 80 00   line#602  GETUPVAL 0 1            <3>   R0 = Upv#2@foundAnything
			  +7F57: 5F 40 40 00   line#602  EQ 1 0 -2               <4>   if R0 ~= "" then GOTO <6>                       -- It's Const#2
			  +7F5B: 1E 40 00 80   line#602  JMP 0 2                 <5>   GOTO <8>
			  +7F5F: 06 00 40 00   line#603  GETTABUP 0 0 -1         <6>   R0 = Upv#1@_ENV["TPReturner"]                   -- It's Const#1
			  +7F63: 24 40 80 00   line#603  CALL 0 1 1              <7>   R0()
			  +7F67: 26 00 80 00   line#605  RETURN 0 1              <8>   RETURN
			Functions: 0

	************ Function#3   (full path: main.3)
	Source line#: 611..613
	Parameters: 1
	Is vararg: no
	VM registers needed: 2
	Constants: 1
	  +80E5:Size=0:                                 Const#1   nil       nil
	Upvalues: 0
	Locals: 1
	  Local#1   R0   parameter  scope:<1..6>        name: thing
	Instructions: 6
	  +80C8: 5F 00 40 00   line#612  EQ 1 0 -1               <1>   if R0@thing ~= nil then GOTO <3>                -- It's Const#1
	  +80CC: 1E 00 00 80   line#612  JMP 0 1                 <2>   GOTO <4>
	  +80D0: 43 40 00 00   line#612  LOADBOOL 1 0 1          <3>   R1 = false;  GOTO <5>
	  +80D4: 43 00 80 00   line#612  LOADBOOL 1 1 0          <4>   R1 = true
	  +80D8: 66 00 00 01   line#612  RETURN 1 2              <5>   RETURN R1
	  +80DC: 26 00 80 00   line#613  RETURN 0 1              <6>   (unreachable instruction)
	Functions: 0

	************ Function#4   (full path: main.4)
	Source line#: 614..616
	Parameters: 1
	Is vararg: no
	VM registers needed: 4
	Constants: 4
	  +8159:Size=4: 6D 61 74 68                     Const#1   string    "math"
	  +815F:Size=5: 66 6C 6F 6F 72                  Const#2   string    "floor"
	  +8166:Size=8: 74 6F 6E 75 6D 62 65 72         Const#3   string    "tonumber"
	  +816F:Size=8: 00 00 00 00 00 00 E0 3F         Const#4   float     0.5
	Upvalues: 1
	  Upv#1 is parent function's Upv#1              name: _ENV
	Locals: 1
	  Local#1   R0   parameter  scope:<1..9>        name: n
	Instructions: 9
	  +812F: 46 00 40 00   line#615  GETTABUP 1 0 -1         <1>   R1 = Upv#1@_ENV["math"]                         -- It's Const#1
	  +8133: 47 40 C0 00   line#615  GETTABLE 1 1 -2         <2>   R1 = R1["floor"]                                -- It's Const#2
	  +8137: 86 80 40 00   line#615  GETTABUP 2 0 -3         <3>   R2 = Upv#1@_ENV["tonumber"]                     -- It's Const#3
	  +813B: C0 00 00 00   line#615  MOVE 3 0                <4>   R3 = R0@n
	  +813F: A4 80 00 01   line#615  CALL 2 2 2              <5>   R2 = R2(R3)
	  +8143: 8D C0 40 01   line#615  ADD 2 2 -4              <6>   R2 = R2 + 0.5                                   -- It's Const#4
	  +8147: 65 00 00 01   line#615  TAILCALL 1 2            <7>   RETURN R1(R2)
	  +814B: 66 00 00 00   line#615  RETURN 1 0              <8>   (unreachable instruction)
	  +814F: 26 00 80 00   line#616  RETURN 0 1              <9>   (unreachable instruction)
	Functions: 0

	************ Function#5   (full path: main.5)
	Source line#: 618..655
	Parameters: 0
	Is vararg: no
	VM registers needed: 7
	Constants: 6
	  +8216:Size=5: 70 61 69 72 73                  Const#1   string    "pairs"
	  +821D:Size=4: 67 61 6D 65                     Const#2   string    "game"
	  +8223:Size=A: 47 65 74 53 65 72 76 69 63 65   Const#3   string    "GetService"
	  +822F:Size=7: 50 6C 61 79 65 72 73            Const#4   string    "Players"
	  +8238:Size=B: 47 65 74 43 68 69 6C 64 72...   Const#5   string    "GetChildren"
	  +8245:Size=5: 70 63 61 6C 6C                  Const#6   string    "pcall"
	Upvalues: 2
	  Upv#1 is parent function's Upv#1              name: _ENV
	  Upv#2 is parent function's R0                 name: round
	Locals: 5
	  Local#1   R0   def:<8>    scope:<9..15>       name: (for generator)
	  Local#2   R1   def:<8>    scope:<9..15>       name: (for state)
	  Local#3   R2   def:<8>    scope:<9..15>       name: (for control)
	  Local#4   R3   def:<9>    scope:<10..13>      name: i
	  Local#5   R4   def:<9>    scope:<10..13>      name: v
	Instructions: 16
	  +81D0: 06 00 40 00   line#619  GETTABUP 0 0 -1         <1>   R0 = Upv#1@_ENV["pairs"]                        -- It's Const#1
	  +81D4: 46 40 40 00   line#619  GETTABUP 1 0 -2         <2>   R1 = Upv#1@_ENV["game"]                         -- It's Const#2
	  +81D8: 4C 80 C0 00   line#619  SELF 1 1 -3             <3>   R2 = R1;  R1 = R1["GetService"]                 -- It's Const#3   -- prepare for R1:GetService()
	  +81DC: C1 C0 00 00   line#619  LOADK 3 -4              <4>   R3 = "Players"                                  -- It's Const#4
	  +81E0: 64 80 80 01   line#619  CALL 1 3 2              <5>   R1 = R1(R2, R3)
	  +81E4: 4C 00 C1 00   line#619  SELF 1 1 -5             <6>   R2 = R1;  R1 = R1["GetChildren"]                -- It's Const#5   -- prepare for R1:GetChildren()
	  +81E8: 64 00 00 01   line#619  CALL 1 2 0              <7>   R1,.. = R1(R2)
	  +81EC: 24 00 01 00   line#619  CALL 0 0 4              <8>   R0, R1, R2 = R0(R1,..)
	  +81F0: 1E C0 00 80   line#619  JMP 0 4                 <9>   GOTO <14>                                       -- for R3@i, R4@v in R0, R1, R2 do
	  +81F4: 46 41 41 00   line#620  GETTABUP 5 0 -6        <10>   R5 = Upv#1@_ENV["pcall"]                        -- It's Const#6
	  +81F8: AC 01 00 00   line#653  CLOSURE 6 0            <11>   R6 = Function#1
	  +81FC: 64 41 00 01   line#620  CALL 5 2 1             <12>   R5(R6)
	  +8200: 1E C1 FF 7F   line#653  JMP 4 0                <13>   CLOSE R3@i,..
	  +8204: 29 80 00 00   line#619  TFORCALL 0 2           <14>   R3, R4 = R0(R1, R2)
	  +8208: AA 40 FE 7F   line#619  TFORLOOP 2 -6          <15>   if R3 ~= nil then { R2 = R3;  GOTO <10> }       -- end of loop
	  +820C: 26 00 80 00   line#655  RETURN 0 1             <16>   RETURN
	Functions: 1

		************ Function#1   (full path: main.5.1)
		Source line#: 620..653
		Parameters: 0
		Is vararg: no
		VM registers needed: 8
		Constants: 55
		  +8524:Size=5: 69 73 6E 69 6C                  Const#1   string    "isnil"
		  +852B:Size=9: 43 68 61 72 61 63 74 65 72      Const#2   string    "Character"
		  +8536:Size=9: 45 53 50 50 6C 61 79 65 72      Const#3   string    "ESPPlayer"
		  +8541:Size=4: 48 65 61 64                     Const#4   string    "Head"
		  +8547:Size=E: 46 69 6E 64 46 69 72 73 74...   Const#5   string    "FindFirstChild"
		  +8557:Size=7: 4E 61 6D 65 45 73 70            Const#6   string    "NameEsp"
		  +8560:Size=6: 4E 75 6D 62 65 72               Const#7   string    "Number"
		  +8568:Size=8: 49 6E 73 74 61 6E 63 65         Const#8   string    "Instance"
		  +8572:Size=3: 6E 65 77                        Const#9   string    "new"
		  +8577:Size=C: 42 69 6C 6C 62 6F 61 72 64...   Const#10  string    "BillboardGui"
		  +8585:Size=4: 4E 61 6D 65                     Const#11  string    "Name"
		  +858B:Size=D: 45 78 74 65 6E 74 73 4F 66...   Const#12  string    "ExtentsOffset"
		  +859A:Size=7: 56 65 63 74 6F 72 33            Const#13  string    "Vector3"
		  +85A2:Size=4: 00 00 00 00                     Const#14  integer   0
		  +85A7:Size=4: 01 00 00 00                     Const#15  integer   1
		  +85AD:Size=4: 53 69 7A 65                     Const#16  string    "Size"
		  +85B3:Size=5: 55 44 69 6D 32                  Const#17  string    "UDim2"
		  +85B9:Size=4: C8 00 00 00                     Const#18  integer   200
		  +85BE:Size=4: 1E 00 00 00                     Const#19  integer   30
		  +85C4:Size=7: 41 64 6F 72 6E 65 65            Const#20  string    "Adornee"
		  +85CD:Size=B: 41 6C 77 61 79 73 4F 6E 54...   Const#21  string    "AlwaysOnTop"
		  +85D9:Size=1: 01                              Const#22  boolean   true
		  +85DC:Size=9: 54 65 78 74 4C 61 62 65 6C      Const#23  string    "TextLabel"
		  +85E7:Size=4: 46 6F 6E 74                     Const#24  string    "Font"
		  +85ED:Size=A: 47 6F 74 68 61 6D 42 6F 6C 64   Const#25  string    "GothamBold"
		  +85F9:Size=8: 46 6F 6E 74 53 69 7A 65         Const#26  string    "FontSize"
		  +8603:Size=6: 53 69 7A 65 31 34               Const#27  string    "Size14"
		  +860B:Size=B: 54 65 78 74 57 72 61 70 70...   Const#28  string    "TextWrapped"
		  +8618:Size=4: 54 65 78 74                     Const#29  string    "Text"
		  +861E:Size=2: 20 0A                           Const#30  string    " \n"
		  +8622:Size=4: 67 61 6D 65                     Const#31  string    "game"
		  +8628:Size=A: 47 65 74 53 65 72 76 69 63 65   Const#32  string    "GetService"
		  +8634:Size=7: 50 6C 61 79 65 72 73            Const#33  string    "Players"
		  +863D:Size=B: 4C 6F 63 61 6C 50 6C 61 79...   Const#34  string    "LocalPlayer"
		  +864A:Size=8: 50 6F 73 69 74 69 6F 6E         Const#35  string    "Position"
		  +8654:Size=9: 4D 61 67 6E 69 74 75 64 65      Const#36  string    "Magnitude"
		  +865E:Size=4: 03 00 00 00                     Const#37  integer   3
		  +8664:Size=2: 20 4D                           Const#38  string    " M"
		  +8668:Size=E: 54 65 78 74 59 41 6C 69 67...   Const#39  string    "TextYAlignment"
		  +8678:Size=3: 54 6F 70                        Const#40  string    "Top"
		  +867D:Size=16: 42 61 63 6B 67 72 6F 75 6...   Const#41  string    "BackgroundTransparency"
		  +8695:Size=16: 54 65 78 74 53 74 72 6F 6...   Const#42  string    "TextStrokeTransparency"
		  +86AC:Size=8: 00 00 00 00 00 00 E0 3F         Const#43  float     0.5
		  +86B6:Size=4: 54 65 61 6D                     Const#44  string    "Team"
		  +86BC:Size=A: 54 65 78 74 43 6F 6C 6F 72 33   Const#45  string    "TextColor3"
		  +86C8:Size=6: 43 6F 6C 6F 72 33               Const#46  string    "Color3"
		  +86CF:Size=4: FF 00 00 00                     Const#47  integer   255
		  +86D5:Size=3: 20 7C 20                        Const#48  string    " | "
		  +86DA:Size=C: 20 4D 0A 48 65 61 6C 74 68...   Const#49  string    " M\nHealth : "
		  +86E8:Size=8: 48 75 6D 61 6E 6F 69 64         Const#50  string    "Humanoid"
		  +86F2:Size=6: 48 65 61 6C 74 68               Const#51  string    "Health"
		  +86F9:Size=4: 64 00 00 00                     Const#52  integer   100
		  +86FF:Size=9: 4D 61 78 48 65 61 6C 74 68      Const#53  string    "MaxHealth"
		  +870A:Size=1: 25                              Const#54  string    "%"
		  +870D:Size=7: 44 65 73 74 72 6F 79            Const#55  string    "Destroy"
		Upvalues: 3
		  Upv#1 is parent function's Upv#1              name: _ENV
		  Upv#2 is parent function's R4                 name: v
		  Upv#3 is parent function's Upv#2              name: round
		Locals: 2
		  Local#1   R0   def:<29>   scope:<30..114>     name: bill
		  Local#2   R1   def:<57>   scope:<58..114>     name: name
		Instructions: 174
		  +8266: 06 00 40 00   line#621  GETTABUP 0 0 -1         <1>   R0 = Upv#1@_ENV["isnil"]                        -- It's Const#1
		  +826A: 46 40 C0 00   line#621  GETTABUP 1 1 -2         <2>   R1 = Upv#2@v["Character"]                       -- It's Const#2
		  +826E: 24 80 00 01   line#621  CALL 0 2 2              <3>   R0 = R0(R1)
		  +8272: 22 40 00 00   line#621  TEST 0 1                <4>   if not R0 then GOTO <6>
		  +8276: 1E C0 29 80   line#621  JMP 0 168               <5>   GOTO <174>
		  +827A: 06 80 40 00   line#622  GETTABUP 0 0 -3         <6>   R0 = Upv#1@_ENV["ESPPlayer"]                    -- It's Const#3
		  +827E: 22 00 00 00   line#622  TEST 0 0                <7>   if R0 then GOTO <9>
		  +8282: 1E 80 24 80   line#622  JMP 0 147               <8>   GOTO <156>
		  +8286: 06 00 40 00   line#623  GETTABUP 0 0 -1         <9>   R0 = Upv#1@_ENV["isnil"]                        -- It's Const#1
		  +828A: 46 40 C0 00   line#623  GETTABUP 1 1 -2        <10>   R1 = Upv#2@v["Character"]                       -- It's Const#2
		  +828E: 47 C0 C0 00   line#623  GETTABLE 1 1 -4        <11>   R1 = R1["Head"]                                 -- It's Const#4
		  +8292: 24 80 00 01   line#623  CALL 0 2 2             <12>   R0 = R0(R1)
		  +8296: 22 40 00 00   line#623  TEST 0 1               <13>   if not R0 then GOTO <15>
		  +829A: 1E 00 19 80   line#623  JMP 0 101              <14>   GOTO <116>
		  +829E: 06 40 C0 00   line#623  GETTABUP 0 1 -2        <15>   R0 = Upv#2@v["Character"]                       -- It's Const#2
		  +82A2: 07 C0 40 00   line#623  GETTABLE 0 0 -4        <16>   R0 = R0["Head"]                                 -- It's Const#4
		  +82A6: 0C 00 41 00   line#623  SELF 0 0 -5            <17>   R1 = R0;  R0 = R0["FindFirstChild"]             -- It's Const#5   -- prepare for R0:FindFirstChild()
		  +82AA: 81 40 01 00   line#623  LOADK 2 -6             <18>   R2 = "NameEsp"                                  -- It's Const#6
		  +82AE: C6 80 41 00   line#623  GETTABUP 3 0 -7        <19>   R3 = Upv#1@_ENV["Number"]                       -- It's Const#7
		  +82B2: 9D C0 00 01   line#623  CONCAT 2 2 3           <20>   R2 = R2..R3
		  +82B6: 24 80 80 01   line#623  CALL 0 3 2             <21>   R0 = R0(R1, R2)
		  +82BA: 22 40 00 00   line#623  TEST 0 1               <22>   if not R0 then GOTO <24>
		  +82BE: 1E C0 16 80   line#623  JMP 0 92               <23>   GOTO <116>
		  +82C2: 06 C0 41 00   line#624  GETTABUP 0 0 -8        <24>   R0 = Upv#1@_ENV["Instance"]                     -- It's Const#8
		  +82C6: 07 00 42 00   line#624  GETTABLE 0 0 -9        <25>   R0 = R0["new"]                                  -- It's Const#9
		  +82CA: 41 40 02 00   line#624  LOADK 1 -10            <26>   R1 = "BillboardGui"                             -- It's Const#10
		  +82CE: 86 40 C0 00   line#624  GETTABUP 2 1 -2        <27>   R2 = Upv#2@v["Character"]                       -- It's Const#2
		  +82D2: 87 C0 40 01   line#624  GETTABLE 2 2 -4        <28>   R2 = R2["Head"]                                 -- It's Const#4
		  +82D6: 24 80 80 01   line#624  CALL 0 3 2             <29>   R0@bill = R0(R1, R2)
		  +82DA: 41 40 01 00   line#625  LOADK 1 -6             <30>   R1 = "NameEsp"                                  -- It's Const#6
		  +82DE: 86 80 41 00   line#625  GETTABUP 2 0 -7        <31>   R2 = Upv#1@_ENV["Number"]                       -- It's Const#7
		  +82E2: 5D 80 80 00   line#625  CONCAT 1 1 2           <32>   R1 = R1..R2
		  +82E6: 0A 40 00 85   line#625  SETTABLE 0 -11 1       <33>   R0@bill["Name"] = R1                            -- It's Const#11
		  +82EA: 46 00 43 00   line#626  GETTABUP 1 0 -13       <34>   R1 = Upv#1@_ENV["Vector3"]                      -- It's Const#13
		  +82EE: 47 00 C2 00   line#626  GETTABLE 1 1 -9        <35>   R1 = R1["new"]                                  -- It's Const#9
		  +82F2: 81 40 03 00   line#626  LOADK 2 -14            <36>   R2 = 0                                          -- It's Const#14
		  +82F6: C1 80 03 00   line#626  LOADK 3 -15            <37>   R3 = 1                                          -- It's Const#15
		  +82FA: 01 41 03 00   line#626  LOADK 4 -14            <38>   R4 = 0                                          -- It's Const#14
		  +82FE: 64 80 00 02   line#626  CALL 1 4 2             <39>   R1 = R1(R2, R3, R4)
		  +8302: 0A 40 80 85   line#626  SETTABLE 0 -12 1       <40>   R0@bill["ExtentsOffset"] = R1                   -- It's Const#12
		  +8306: 46 00 44 00   line#627  GETTABUP 1 0 -17       <41>   R1 = Upv#1@_ENV["UDim2"]                        -- It's Const#17
		  +830A: 47 00 C2 00   line#627  GETTABLE 1 1 -9        <42>   R1 = R1["new"]                                  -- It's Const#9
		  +830E: 81 80 03 00   line#627  LOADK 2 -15            <43>   R2 = 1                                          -- It's Const#15
		  +8312: C1 40 04 00   line#627  LOADK 3 -18            <44>   R3 = 200                                        -- It's Const#18
		  +8316: 01 81 03 00   line#627  LOADK 4 -15            <45>   R4 = 1                                          -- It's Const#15
		  +831A: 41 81 04 00   line#627  LOADK 5 -19            <46>   R5 = 30                                         -- It's Const#19
		  +831E: 64 80 80 02   line#627  CALL 1 5 2             <47>   R1 = R1(R2,..,R5)
		  +8322: 0A 40 80 87   line#627  SETTABLE 0 -16 1       <48>   R0@bill["Size"] = R1                            -- It's Const#16
		  +8326: 46 40 C0 00   line#628  GETTABUP 1 1 -2        <49>   R1 = Upv#2@v["Character"]                       -- It's Const#2
		  +832A: 47 C0 C0 00   line#628  GETTABLE 1 1 -4        <50>   R1 = R1["Head"]                                 -- It's Const#4
		  +832E: 0A 40 80 89   line#628  SETTABLE 0 -20 1       <51>   R0@bill["Adornee"] = R1                         -- It's Const#20
		  +8332: 0A 40 45 8A   line#629  SETTABLE 0 -21 -22     <52>   R0@bill["AlwaysOnTop"] = true                   -- It's Const#21, Const#22
		  +8336: 46 C0 41 00   line#630  GETTABUP 1 0 -8        <53>   R1 = Upv#1@_ENV["Instance"]                     -- It's Const#8
		  +833A: 47 00 C2 00   line#630  GETTABLE 1 1 -9        <54>   R1 = R1["new"]                                  -- It's Const#9
		  +833E: 81 80 05 00   line#630  LOADK 2 -23            <55>   R2 = "TextLabel"                                -- It's Const#23
		  +8342: C0 00 00 00   line#630  MOVE 3 0               <56>   R3 = R0@bill
		  +8346: 64 80 80 01   line#630  CALL 1 3 2             <57>   R1@name = R1(R2, R3)
		  +834A: 4A 00 C6 8B   line#631  SETTABLE 1 -24 -25     <58>   R1@name["Font"] = "GothamBold"                  -- It's Const#24, Const#25
		  +834E: 4A 80 C6 8C   line#632  SETTABLE 1 -26 -27     <59>   R1@name["FontSize"] = "Size14"                  -- It's Const#26, Const#27
		  +8352: 4A 40 C5 8D   line#633  SETTABLE 1 -28 -22     <60>   R1@name["TextWrapped"] = true                   -- It's Const#28, Const#22
		  +8356: 86 80 C2 00   line#634  GETTABUP 2 1 -11       <61>   R2 = Upv#2@v["Name"]                            -- It's Const#11
		  +835A: C1 40 07 00   line#634  LOADK 3 -30            <62>   R3 = " \n"                                      -- It's Const#30
		  +835E: 05 01 00 01   line#634  GETUPVAL 4 2           <63>   R4 = Upv#3@round
		  +8362: 46 81 47 00   line#634  GETTABUP 5 0 -31       <64>   R5 = Upv#1@_ENV["game"]                         -- It's Const#31
		  +8366: 4C C1 C7 02   line#634  SELF 5 5 -32           <65>   R6 = R5;  R5 = R5["GetService"]                 -- It's Const#32   -- prepare for R5:GetService()
		  +836A: C1 01 08 00   line#634  LOADK 7 -33            <66>   R7 = "Players"                                  -- It's Const#33
		  +836E: 64 81 80 01   line#634  CALL 5 3 2             <67>   R5 = R5(R6, R7)
		  +8372: 47 41 C8 02   line#634  GETTABLE 5 5 -34       <68>   R5 = R5["LocalPlayer"]                          -- It's Const#34
		  +8376: 47 41 C0 02   line#634  GETTABLE 5 5 -2        <69>   R5 = R5["Character"]                            -- It's Const#2
		  +837A: 47 C1 C0 02   line#634  GETTABLE 5 5 -4        <70>   R5 = R5["Head"]                                 -- It's Const#4
		  +837E: 47 81 C8 02   line#634  GETTABLE 5 5 -35       <71>   R5 = R5["Position"]                             -- It's Const#35
		  +8382: 86 41 C0 00   line#634  GETTABUP 6 1 -2        <72>   R6 = Upv#2@v["Character"]                       -- It's Const#2
		  +8386: 87 C1 40 03   line#634  GETTABLE 6 6 -4        <73>   R6 = R6["Head"]                                 -- It's Const#4
		  +838A: 87 81 48 03   line#634  GETTABLE 6 6 -35       <74>   R6 = R6["Position"]                             -- It's Const#35
		  +838E: 4E 81 81 02   line#634  SUB 5 5 6              <75>   R5 = R5 - R6
		  +8392: 47 C1 C8 02   line#634  GETTABLE 5 5 -36       <76>   R5 = R5["Magnitude"]                            -- It's Const#36
		  +8396: 52 01 C9 02   line#634  DIV 5 5 -37            <77>   R5 = R5 / 3                                     -- It's Const#37
		  +839A: 24 81 00 01   line#634  CALL 4 2 2             <78>   R4 = R4(R5)
		  +839E: 41 41 09 00   line#634  LOADK 5 -38            <79>   R5 = " M"                                       -- It's Const#38
		  +83A2: 9D 40 01 01   line#634  CONCAT 2 2 5           <80>   R2 = R2..R3..R4..R5
		  +83A6: 4A 80 00 8E   line#634  SETTABLE 1 -29 2       <81>   R1@name["Text"] = R2                            -- It's Const#29
		  +83AA: 86 00 44 00   line#635  GETTABUP 2 0 -17       <82>   R2 = Upv#1@_ENV["UDim2"]                        -- It's Const#17
		  +83AE: 87 00 42 01   line#635  GETTABLE 2 2 -9        <83>   R2 = R2["new"]                                  -- It's Const#9
		  +83B2: C1 80 03 00   line#635  LOADK 3 -15            <84>   R3 = 1                                          -- It's Const#15
		  +83B6: 01 41 03 00   line#635  LOADK 4 -14            <85>   R4 = 0                                          -- It's Const#14
		  +83BA: 41 81 03 00   line#635  LOADK 5 -15            <86>   R5 = 1                                          -- It's Const#15
		  +83BE: 81 41 03 00   line#635  LOADK 6 -14            <87>   R6 = 0                                          -- It's Const#14
		  +83C2: A4 80 80 02   line#635  CALL 2 5 2             <88>   R2 = R2(R3,..,R6)
		  +83C6: 4A 80 80 87   line#635  SETTABLE 1 -16 2       <89>   R1@name["Size"] = R2                            -- It's Const#16
		  +83CA: 4A C0 49 93   line#636  SETTABLE 1 -39 -40     <90>   R1@name["TextYAlignment"] = "Top"               -- It's Const#39, Const#40
		  +83CE: 4A 80 43 94   line#637  SETTABLE 1 -41 -15     <91>   R1@name["BackgroundTransparency"] = 1           -- It's Const#41, Const#15
		  +83D2: 4A 80 CA 94   line#638  SETTABLE 1 -42 -43     <92>   R1@name["TextStrokeTransparency"] = 0.5         -- It's Const#42, Const#43
		  +83D6: 86 C0 CA 00   line#639  GETTABUP 2 1 -44       <93>   R2 = Upv#2@v["Team"]                            -- It's Const#44
		  +83DA: C6 80 47 00   line#639  GETTABUP 3 0 -31       <94>   R3 = Upv#1@_ENV["game"]                         -- It's Const#31
		  +83DE: C7 00 C8 01   line#639  GETTABLE 3 3 -33       <95>   R3 = R3["Players"]                              -- It's Const#33
		  +83E2: C7 40 C8 01   line#639  GETTABLE 3 3 -34       <96>   R3 = R3["LocalPlayer"]                          -- It's Const#34
		  +83E6: C7 C0 CA 01   line#639  GETTABLE 3 3 -44       <97>   R3 = R3["Team"]                                 -- It's Const#44
		  +83EA: 1F C0 00 01   line#639  EQ 0 2 3               <98>   if R2 == R3 then GOTO <100>
		  +83EE: 1E C0 01 80   line#639  JMP 0 8                <99>   GOTO <108>
		  +83F2: 86 40 4B 00   line#640  GETTABUP 2 0 -46      <100>   R2 = Upv#1@_ENV["Color3"]                       -- It's Const#46
		  +83F6: 87 00 42 01   line#640  GETTABLE 2 2 -9       <101>   R2 = R2["new"]                                  -- It's Const#9
		  +83FA: C1 40 03 00   line#640  LOADK 3 -14           <102>   R3 = 0                                          -- It's Const#14
		  +83FE: 01 81 0B 00   line#640  LOADK 4 -47           <103>   R4 = 255                                        -- It's Const#47
		  +8402: 41 41 03 00   line#640  LOADK 5 -14           <104>   R5 = 0                                          -- It's Const#14
		  +8406: A4 80 00 02   line#640  CALL 2 4 2            <105>   R2 = R2(R3, R4, R5)
		  +840A: 4A 80 00 96   line#640  SETTABLE 1 -45 2      <106>   R1@name["TextColor3"] = R2                      -- It's Const#45
		  +840E: 1E 40 10 80   line#640  JMP 0 66              <107>   GOTO <174>
		  +8412: 86 40 4B 00   line#642  GETTABUP 2 0 -46      <108>   R2 = Upv#1@_ENV["Color3"]                       -- It's Const#46
		  +8416: 87 00 42 01   line#642  GETTABLE 2 2 -9       <109>   R2 = R2["new"]                                  -- It's Const#9
		  +841A: C1 80 0B 00   line#642  LOADK 3 -47           <110>   R3 = 255                                        -- It's Const#47
		  +841E: 01 41 03 00   line#642  LOADK 4 -14           <111>   R4 = 0                                          -- It's Const#14
		  +8422: 41 41 03 00   line#642  LOADK 5 -14           <112>   R5 = 0                                          -- It's Const#14
		  +8426: A4 80 00 02   line#642  CALL 2 4 2            <113>   R2 = R2(R3, R4, R5)
		  +842A: 4A 80 00 96   line#642  SETTABLE 1 -45 2      <114>   R1@name["TextColor3"] = R2                      -- It's Const#45
		  +842E: 1E 40 0E 80   line#643  JMP 0 58              <115>   GOTO <174>
		  +8432: 06 40 C0 00   line#645  GETTABUP 0 1 -2       <116>   R0 = Upv#2@v["Character"]                       -- It's Const#2
		  +8436: 07 C0 40 00   line#645  GETTABLE 0 0 -4       <117>   R0 = R0["Head"]                                 -- It's Const#4
		  +843A: 41 40 01 00   line#645  LOADK 1 -6            <118>   R1 = "NameEsp"                                  -- It's Const#6
		  +843E: 86 80 41 00   line#645  GETTABUP 2 0 -7       <119>   R2 = Upv#1@_ENV["Number"]                       -- It's Const#7
		  +8442: 5D 80 80 00   line#645  CONCAT 1 1 2          <120>   R1 = R1..R2
		  +8446: 07 40 00 00   line#645  GETTABLE 0 0 1        <121>   R0 = R0[R1]
		  +844A: 07 80 45 00   line#645  GETTABLE 0 0 -23      <122>   R0 = R0["TextLabel"]                            -- It's Const#23
		  +844E: 46 80 C2 00   line#645  GETTABUP 1 1 -11      <123>   R1 = Upv#2@v["Name"]                            -- It's Const#11
		  +8452: 81 C0 0B 00   line#645  LOADK 2 -48           <124>   R2 = " | "                                      -- It's Const#48
		  +8456: C5 00 00 01   line#645  GETUPVAL 3 2          <125>   R3 = Upv#3@round
		  +845A: 06 81 47 00   line#645  GETTABUP 4 0 -31      <126>   R4 = Upv#1@_ENV["game"]                         -- It's Const#31
		  +845E: 0C C1 47 02   line#645  SELF 4 4 -32          <127>   R5 = R4;  R4 = R4["GetService"]                 -- It's Const#32   -- prepare for R4:GetService()
		  +8462: 81 01 08 00   line#645  LOADK 6 -33           <128>   R6 = "Players"                                  -- It's Const#33
		  +8466: 24 81 80 01   line#645  CALL 4 3 2            <129>   R4 = R4(R5, R6)
		  +846A: 07 41 48 02   line#645  GETTABLE 4 4 -34      <130>   R4 = R4["LocalPlayer"]                          -- It's Const#34
		  +846E: 07 41 40 02   line#645  GETTABLE 4 4 -2       <131>   R4 = R4["Character"]                            -- It's Const#2
		  +8472: 07 C1 40 02   line#645  GETTABLE 4 4 -4       <132>   R4 = R4["Head"]                                 -- It's Const#4
		  +8476: 07 81 48 02   line#645  GETTABLE 4 4 -35      <133>   R4 = R4["Position"]                             -- It's Const#35
		  +847A: 46 41 C0 00   line#645  GETTABUP 5 1 -2       <134>   R5 = Upv#2@v["Character"]                       -- It's Const#2
		  +847E: 47 C1 C0 02   line#645  GETTABLE 5 5 -4       <135>   R5 = R5["Head"]                                 -- It's Const#4
		  +8482: 47 81 C8 02   line#645  GETTABLE 5 5 -35      <136>   R5 = R5["Position"]                             -- It's Const#35
		  +8486: 0E 41 01 02   line#645  SUB 4 4 5             <137>   R4 = R4 - R5
		  +848A: 07 C1 48 02   line#645  GETTABLE 4 4 -36      <138>   R4 = R4["Magnitude"]                            -- It's Const#36
		  +848E: 12 01 49 02   line#645  DIV 4 4 -37           <139>   R4 = R4 / 3                                     -- It's Const#37
		  +8492: E4 80 00 01   line#645  CALL 3 2 2            <140>   R3 = R3(R4)
		  +8496: 01 01 0C 00   line#645  LOADK 4 -49           <141>   R4 = " M\nHealth : "                            -- It's Const#49
		  +849A: 45 01 00 01   line#645  GETUPVAL 5 2          <142>   R5 = Upv#3@round
		  +849E: 86 41 C0 00   line#645  GETTABUP 6 1 -2       <143>   R6 = Upv#2@v["Character"]                       -- It's Const#2
		  +84A2: 87 41 4C 03   line#645  GETTABLE 6 6 -50      <144>   R6 = R6["Humanoid"]                             -- It's Const#50
		  +84A6: 87 81 4C 03   line#645  GETTABLE 6 6 -51      <145>   R6 = R6["Health"]                               -- It's Const#51
		  +84AA: 8F C1 4C 03   line#645  MUL 6 6 -52           <146>   R6 = R6 * 100                                   -- It's Const#52
		  +84AE: C6 41 C0 00   line#645  GETTABUP 7 1 -2       <147>   R7 = Upv#2@v["Character"]                       -- It's Const#2
		  +84B2: C7 41 CC 03   line#645  GETTABLE 7 7 -50      <148>   R7 = R7["Humanoid"]                             -- It's Const#50
		  +84B6: C7 01 CD 03   line#645  GETTABLE 7 7 -53      <149>   R7 = R7["MaxHealth"]                            -- It's Const#53
		  +84BA: 92 C1 01 03   line#645  DIV 6 6 7             <150>   R6 = R6 / R7
		  +84BE: 64 81 00 01   line#645  CALL 5 2 2            <151>   R5 = R5(R6)
		  +84C2: 81 41 0D 00   line#645  LOADK 6 -54           <152>   R6 = "%"                                        -- It's Const#54
		  +84C6: 5D 80 81 00   line#645  CONCAT 1 1 6          <153>   R1 = R1..R2..R3..R4..R5..R6
		  +84CA: 0A 40 00 8E   line#645  SETTABLE 0 -29 1      <154>   R0["Text"] = R1                                 -- It's Const#29
		  +84CE: 1E 40 04 80   line#646  JMP 0 18              <155>   GOTO <174>
		  +84D2: 06 40 C0 00   line#648  GETTABUP 0 1 -2       <156>   R0 = Upv#2@v["Character"]                       -- It's Const#2
		  +84D6: 07 C0 40 00   line#648  GETTABLE 0 0 -4       <157>   R0 = R0["Head"]                                 -- It's Const#4
		  +84DA: 0C 00 41 00   line#648  SELF 0 0 -5           <158>   R1 = R0;  R0 = R0["FindFirstChild"]             -- It's Const#5   -- prepare for R0:FindFirstChild()
		  +84DE: 81 40 01 00   line#648  LOADK 2 -6            <159>   R2 = "NameEsp"                                  -- It's Const#6
		  +84E2: C6 80 41 00   line#648  GETTABUP 3 0 -7       <160>   R3 = Upv#1@_ENV["Number"]                       -- It's Const#7
		  +84E6: 9D C0 00 01   line#648  CONCAT 2 2 3          <161>   R2 = R2..R3
		  +84EA: 24 80 80 01   line#648  CALL 0 3 2            <162>   R0 = R0(R1, R2)
		  +84EE: 22 00 00 00   line#648  TEST 0 0              <163>   if R0 then GOTO <165>
		  +84F2: 1E 00 02 80   line#648  JMP 0 9               <164>   GOTO <174>
		  +84F6: 06 40 C0 00   line#649  GETTABUP 0 1 -2       <165>   R0 = Upv#2@v["Character"]                       -- It's Const#2
		  +84FA: 07 C0 40 00   line#649  GETTABLE 0 0 -4       <166>   R0 = R0["Head"]                                 -- It's Const#4
		  +84FE: 0C 00 41 00   line#649  SELF 0 0 -5           <167>   R1 = R0;  R0 = R0["FindFirstChild"]             -- It's Const#5   -- prepare for R0:FindFirstChild()
		  +8502: 81 40 01 00   line#649  LOADK 2 -6            <168>   R2 = "NameEsp"                                  -- It's Const#6
		  +8506: C6 80 41 00   line#649  GETTABUP 3 0 -7       <169>   R3 = Upv#1@_ENV["Number"]                       -- It's Const#7
		  +850A: 9D C0 00 01   line#649  CONCAT 2 2 3          <170>   R2 = R2..R3
		  +850E: 24 80 80 01   line#649  CALL 0 3 2            <171>   R0 = R0(R1, R2)
		  +8512: 0C 80 4D 00   line#649  SELF 0 0 -55          <172>   R1 = R0;  R0 = R0["Destroy"]                    -- It's Const#55   -- prepare for R0:Destroy()
		  +8516: 24 40 00 01   line#649  CALL 0 2 1            <173>   R0(R1)
		  +851A: 26 00 80 00   line#653  RETURN 0 1            <174>   RETURN
		Functions: 0

	************ Function#6   (full path: main.6)
	Source line#: 657..689
	Parameters: 0
	Is vararg: no
	VM registers needed: 7
	Constants: 8
	  +8B18:Size=5: 70 61 69 72 73                  Const#1   string    "pairs"
	  +8B1F:Size=4: 67 61 6D 65                     Const#2   string    "game"
	  +8B25:Size=A: 47 65 74 53 65 72 76 69 63 65   Const#3   string    "GetService"
	  +8B31:Size=9: 57 6F 72 6B 73 70 61 63 65      Const#4   string    "Workspace"
	  +8B3C:Size=C: 5F 57 6F 72 6C 64 4F 72 69...   Const#5   string    "_WorldOrigin"
	  +8B4A:Size=9: 4C 6F 63 61 74 69 6F 6E 73      Const#6   string    "Locations"
	  +8B55:Size=B: 47 65 74 43 68 69 6C 64 72...   Const#7   string    "GetChildren"
	  +8B62:Size=5: 70 63 61 6C 6C                  Const#8   string    "pcall"
	Upvalues: 2
	  Upv#1 is parent function's Upv#1              name: _ENV
	  Upv#2 is parent function's R0                 name: round
	Locals: 5
	  Local#1   R0   def:<10>   scope:<11..17>      name: (for generator)
	  Local#2   R1   def:<10>   scope:<11..17>      name: (for state)
	  Local#3   R2   def:<10>   scope:<11..17>      name: (for control)
	  Local#4   R3   def:<11>   scope:<12..15>      name: i
	  Local#5   R4   def:<11>   scope:<12..15>      name: v
	Instructions: 18
	  +8ACA: 06 00 40 00   line#658  GETTABUP 0 0 -1         <1>   R0 = Upv#1@_ENV["pairs"]                        -- It's Const#1
	  +8ACE: 46 40 40 00   line#658  GETTABUP 1 0 -2         <2>   R1 = Upv#1@_ENV["game"]                         -- It's Const#2
	  +8AD2: 4C 80 C0 00   line#658  SELF 1 1 -3             <3>   R2 = R1;  R1 = R1["GetService"]                 -- It's Const#3   -- prepare for R1:GetService()
	  +8AD6: C1 C0 00 00   line#658  LOADK 3 -4              <4>   R3 = "Workspace"                                -- It's Const#4
	  +8ADA: 64 80 80 01   line#658  CALL 1 3 2              <5>   R1 = R1(R2, R3)
	  +8ADE: 47 00 C1 00   line#658  GETTABLE 1 1 -5         <6>   R1 = R1["_WorldOrigin"]                         -- It's Const#5
	  +8AE2: 47 40 C1 00   line#658  GETTABLE 1 1 -6         <7>   R1 = R1["Locations"]                            -- It's Const#6
	  +8AE6: 4C 80 C1 00   line#658  SELF 1 1 -7             <8>   R2 = R1;  R1 = R1["GetChildren"]                -- It's Const#7   -- prepare for R1:GetChildren()
	  +8AEA: 64 00 00 01   line#658  CALL 1 2 0              <9>   R1,.. = R1(R2)
	  +8AEE: 24 00 01 00   line#658  CALL 0 0 4             <10>   R0, R1, R2 = R0(R1,..)
	  +8AF2: 1E C0 00 80   line#658  JMP 0 4                <11>   GOTO <16>                                       -- for R3@i, R4@v in R0, R1, R2 do
	  +8AF6: 46 C1 41 00   line#659  GETTABUP 5 0 -8        <12>   R5 = Upv#1@_ENV["pcall"]                        -- It's Const#8
	  +8AFA: AC 01 00 00   line#687  CLOSURE 6 0            <13>   R6 = Function#1
	  +8AFE: 64 41 00 01   line#659  CALL 5 2 1             <14>   R5(R6)
	  +8B02: 1E C1 FF 7F   line#687  JMP 4 0                <15>   CLOSE R3@i,..
	  +8B06: 29 80 00 00   line#658  TFORCALL 0 2           <16>   R3, R4 = R0(R1, R2)
	  +8B0A: AA 40 FE 7F   line#658  TFORLOOP 2 -6          <17>   if R3 ~= nil then { R2 = R3;  GOTO <12> }       -- end of loop
	  +8B0E: 26 00 80 00   line#689  RETURN 0 1             <18>   RETURN
	Functions: 1

		************ Function#1   (full path: main.6.1)
		Source line#: 659..687
		Parameters: 0
		Is vararg: no
		VM registers needed: 7
		Constants: 48
		  +8D11:Size=9: 49 73 6C 61 6E 64 45 53 50      Const#1   string    "IslandESP"
		  +8D1C:Size=4: 4E 61 6D 65                     Const#2   string    "Name"
		  +8D22:Size=3: 53 65 61                        Const#3   string    "Sea"
		  +8D27:Size=E: 46 69 6E 64 46 69 72 73 74...   Const#4   string    "FindFirstChild"
		  +8D37:Size=7: 4E 61 6D 65 45 73 70            Const#5   string    "NameEsp"
		  +8D40:Size=8: 49 6E 73 74 61 6E 63 65         Const#6   string    "Instance"
		  +8D4A:Size=3: 6E 65 77                        Const#7   string    "new"
		  +8D4F:Size=C: 42 69 6C 6C 62 6F 61 72 64...   Const#8   string    "BillboardGui"
		  +8D5D:Size=D: 45 78 74 65 6E 74 73 4F 66...   Const#9   string    "ExtentsOffset"
		  +8D6C:Size=7: 56 65 63 74 6F 72 33            Const#10  string    "Vector3"
		  +8D74:Size=4: 00 00 00 00                     Const#11  integer   0
		  +8D79:Size=4: 01 00 00 00                     Const#12  integer   1
		  +8D7F:Size=4: 53 69 7A 65                     Const#13  string    "Size"
		  +8D85:Size=5: 55 44 69 6D 32                  Const#14  string    "UDim2"
		  +8D8B:Size=4: C8 00 00 00                     Const#15  integer   200
		  +8D90:Size=4: 1E 00 00 00                     Const#16  integer   30
		  +8D96:Size=7: 41 64 6F 72 6E 65 65            Const#17  string    "Adornee"
		  +8D9F:Size=B: 41 6C 77 61 79 73 4F 6E 54...   Const#18  string    "AlwaysOnTop"
		  +8DAB:Size=1: 01                              Const#19  boolean   true
		  +8DAE:Size=9: 54 65 78 74 4C 61 62 65 6C      Const#20  string    "TextLabel"
		  +8DB9:Size=4: 46 6F 6E 74                     Const#21  string    "Font"
		  +8DBF:Size=A: 47 6F 74 68 61 6D 42 6F 6C 64   Const#22  string    "GothamBold"
		  +8DCB:Size=8: 46 6F 6E 74 53 69 7A 65         Const#23  string    "FontSize"
		  +8DD5:Size=6: 53 69 7A 65 31 34               Const#24  string    "Size14"
		  +8DDD:Size=B: 54 65 78 74 57 72 61 70 70...   Const#25  string    "TextWrapped"
		  +8DEA:Size=E: 54 65 78 74 59 41 6C 69 67...   Const#26  string    "TextYAlignment"
		  +8DFA:Size=3: 54 6F 70                        Const#27  string    "Top"
		  +8DFF:Size=16: 42 61 63 6B 67 72 6F 75 6...   Const#28  string    "BackgroundTransparency"
		  +8E17:Size=16: 54 65 78 74 53 74 72 6F 6...   Const#29  string    "TextStrokeTransparency"
		  +8E2E:Size=8: 00 00 00 00 00 00 E0 3F         Const#30  float     0.5
		  +8E38:Size=A: 54 65 78 74 43 6F 6C 6F 72 33   Const#31  string    "TextColor3"
		  +8E44:Size=6: 43 6F 6C 6F 72 33               Const#32  string    "Color3"
		  +8E4C:Size=7: 66 72 6F 6D 52 47 42            Const#33  string    "fromRGB"
		  +8E54:Size=4: 50 00 00 00                     Const#34  integer   80
		  +8E59:Size=4: F5 00 00 00                     Const#35  integer   245
		  +8E5F:Size=4: 54 65 78 74                     Const#36  string    "Text"
		  +8E65:Size=4: 20 20 20 0A                     Const#37  string    "   \n"
		  +8E6B:Size=4: 67 61 6D 65                     Const#38  string    "game"
		  +8E71:Size=A: 47 65 74 53 65 72 76 69 63 65   Const#39  string    "GetService"
		  +8E7D:Size=7: 50 6C 61 79 65 72 73            Const#40  string    "Players"
		  +8E86:Size=B: 4C 6F 63 61 6C 50 6C 61 79...   Const#41  string    "LocalPlayer"
		  +8E93:Size=9: 43 68 61 72 61 63 74 65 72      Const#42  string    "Character"
		  +8E9E:Size=4: 48 65 61 64                     Const#43  string    "Head"
		  +8EA4:Size=8: 50 6F 73 69 74 69 6F 6E         Const#44  string    "Position"
		  +8EAE:Size=9: 4D 61 67 6E 69 74 75 64 65      Const#45  string    "Magnitude"
		  +8EB8:Size=4: 03 00 00 00                     Const#46  integer   3
		  +8EBE:Size=2: 20 4D                           Const#47  string    " M"
		  +8EC2:Size=7: 44 65 73 74 72 6F 79            Const#48  string    "Destroy"
		Upvalues: 3
		  Upv#1 is parent function's Upv#1              name: _ENV
		  Upv#2 is parent function's R4                 name: v
		  Upv#3 is parent function's Upv#2              name: round
		Locals: 2
		  Local#1   R0   def:<17>   scope:<18..62>      name: bill
		  Local#2   R1   def:<41>   scope:<42..62>      name: name
		Instructions: 98
		  +8B83: 06 00 40 00   line#660  GETTABUP 0 0 -1         <1>   R0 = Upv#1@_ENV["IslandESP"]                    -- It's Const#1
		  +8B87: 22 00 00 00   line#660  TEST 0 0                <2>   if R0 then GOTO <4>
		  +8B8B: 1E 40 14 80   line#660  JMP 0 82                <3>   GOTO <86>
		  +8B8F: 06 40 C0 00   line#661  GETTABUP 0 1 -2         <4>   R0 = Upv#2@v["Name"]                            -- It's Const#2
		  +8B93: 5F 80 40 00   line#661  EQ 1 0 -3               <5>   if R0 ~= "Sea" then GOTO <7>                    -- It's Const#3
		  +8B97: 1E 80 16 80   line#661  JMP 0 91                <6>   GOTO <98>
		  +8B9B: 05 00 80 00   line#662  GETUPVAL 0 1            <7>   R0 = Upv#2@v
		  +8B9F: 0C C0 40 00   line#662  SELF 0 0 -4             <8>   R1 = R0;  R0 = R0["FindFirstChild"]             -- It's Const#4   -- prepare for R0:FindFirstChild()
		  +8BA3: 81 00 01 00   line#662  LOADK 2 -5              <9>   R2 = "NameEsp"                                  -- It's Const#5
		  +8BA7: 24 80 80 01   line#662  CALL 0 3 2             <10>   R0 = R0(R1, R2)
		  +8BAB: 22 40 00 00   line#662  TEST 0 1               <11>   if not R0 then GOTO <13>
		  +8BAF: 1E 80 0C 80   line#662  JMP 0 51               <12>   GOTO <64>
		  +8BB3: 06 40 41 00   line#663  GETTABUP 0 0 -6        <13>   R0 = Upv#1@_ENV["Instance"]                     -- It's Const#6
		  +8BB7: 07 80 41 00   line#663  GETTABLE 0 0 -7        <14>   R0 = R0["new"]                                  -- It's Const#7
		  +8BBB: 41 C0 01 00   line#663  LOADK 1 -8             <15>   R1 = "BillboardGui"                             -- It's Const#8
		  +8BBF: 85 00 80 00   line#663  GETUPVAL 2 1           <16>   R2 = Upv#2@v
		  +8BC3: 24 80 80 01   line#663  CALL 0 3 2             <17>   R0@bill = R0(R1, R2)
		  +8BC7: 0A 00 C1 80   line#664  SETTABLE 0 -2 -5       <18>   R0@bill["Name"] = "NameEsp"                     -- It's Const#2, Const#5
		  +8BCB: 46 40 42 00   line#665  GETTABUP 1 0 -10       <19>   R1 = Upv#1@_ENV["Vector3"]                      -- It's Const#10
		  +8BCF: 47 80 C1 00   line#665  GETTABLE 1 1 -7        <20>   R1 = R1["new"]                                  -- It's Const#7
		  +8BD3: 81 80 02 00   line#665  LOADK 2 -11            <21>   R2 = 0                                          -- It's Const#11
		  +8BD7: C1 C0 02 00   line#665  LOADK 3 -12            <22>   R3 = 1                                          -- It's Const#12
		  +8BDB: 01 81 02 00   line#665  LOADK 4 -11            <23>   R4 = 0                                          -- It's Const#11
		  +8BDF: 64 80 00 02   line#665  CALL 1 4 2             <24>   R1 = R1(R2, R3, R4)
		  +8BE3: 0A 40 00 84   line#665  SETTABLE 0 -9 1        <25>   R0@bill["ExtentsOffset"] = R1                   -- It's Const#9
		  +8BE7: 46 40 43 00   line#666  GETTABUP 1 0 -14       <26>   R1 = Upv#1@_ENV["UDim2"]                        -- It's Const#14
		  +8BEB: 47 80 C1 00   line#666  GETTABLE 1 1 -7        <27>   R1 = R1["new"]                                  -- It's Const#7
		  +8BEF: 81 C0 02 00   line#666  LOADK 2 -12            <28>   R2 = 1                                          -- It's Const#12
		  +8BF3: C1 80 03 00   line#666  LOADK 3 -15            <29>   R3 = 200                                        -- It's Const#15
		  +8BF7: 01 C1 02 00   line#666  LOADK 4 -12            <30>   R4 = 1                                          -- It's Const#12
		  +8BFB: 41 C1 03 00   line#666  LOADK 5 -16            <31>   R5 = 30                                         -- It's Const#16
		  +8BFF: 64 80 80 02   line#666  CALL 1 5 2             <32>   R1 = R1(R2,..,R5)
		  +8C03: 0A 40 00 86   line#666  SETTABLE 0 -13 1       <33>   R0@bill["Size"] = R1                            -- It's Const#13
		  +8C07: 45 00 80 00   line#667  GETUPVAL 1 1           <34>   R1 = Upv#2@v
		  +8C0B: 0A 40 00 88   line#667  SETTABLE 0 -17 1       <35>   R0@bill["Adornee"] = R1                         -- It's Const#17
		  +8C0F: 0A 80 C4 88   line#668  SETTABLE 0 -18 -19     <36>   R0@bill["AlwaysOnTop"] = true                   -- It's Const#18, Const#19
		  +8C13: 46 40 41 00   line#669  GETTABUP 1 0 -6        <37>   R1 = Upv#1@_ENV["Instance"]                     -- It's Const#6
		  +8C17: 47 80 C1 00   line#669  GETTABLE 1 1 -7        <38>   R1 = R1["new"]                                  -- It's Const#7
		  +8C1B: 81 C0 04 00   line#669  LOADK 2 -20            <39>   R2 = "TextLabel"                                -- It's Const#20
		  +8C1F: C0 00 00 00   line#669  MOVE 3 0               <40>   R3 = R0@bill
		  +8C23: 64 80 80 01   line#669  CALL 1 3 2             <41>   R1@name = R1(R2, R3)
		  +8C27: 4A 40 45 8A   line#670  SETTABLE 1 -21 -22     <42>   R1@name["Font"] = "GothamBold"                  -- It's Const#21, Const#22
		  +8C2B: 4A C0 45 8B   line#671  SETTABLE 1 -23 -24     <43>   R1@name["FontSize"] = "Size14"                  -- It's Const#23, Const#24
		  +8C2F: 4A 80 44 8C   line#672  SETTABLE 1 -25 -19     <44>   R1@name["TextWrapped"] = true                   -- It's Const#25, Const#19
		  +8C33: 86 40 43 00   line#673  GETTABUP 2 0 -14       <45>   R2 = Upv#1@_ENV["UDim2"]                        -- It's Const#14
		  +8C37: 87 80 41 01   line#673  GETTABLE 2 2 -7        <46>   R2 = R2["new"]                                  -- It's Const#7
		  +8C3B: C1 C0 02 00   line#673  LOADK 3 -12            <47>   R3 = 1                                          -- It's Const#12
		  +8C3F: 01 81 02 00   line#673  LOADK 4 -11            <48>   R4 = 0                                          -- It's Const#11
		  +8C43: 41 C1 02 00   line#673  LOADK 5 -12            <49>   R5 = 1                                          -- It's Const#12
		  +8C47: 81 81 02 00   line#673  LOADK 6 -11            <50>   R6 = 0                                          -- It's Const#11
		  +8C4B: A4 80 80 02   line#673  CALL 2 5 2             <51>   R2 = R2(R3,..,R6)
		  +8C4F: 4A 80 00 86   line#673  SETTABLE 1 -13 2       <52>   R1@name["Size"] = R2                            -- It's Const#13
		  +8C53: 4A 80 C6 8C   line#674  SETTABLE 1 -26 -27     <53>   R1@name["TextYAlignment"] = "Top"               -- It's Const#26, Const#27
		  +8C57: 4A C0 C2 8D   line#675  SETTABLE 1 -28 -12     <54>   R1@name["BackgroundTransparency"] = 1           -- It's Const#28, Const#12
		  +8C5B: 4A 40 47 8E   line#676  SETTABLE 1 -29 -30     <55>   R1@name["TextStrokeTransparency"] = 0.5         -- It's Const#29, Const#30
		  +8C5F: 86 C0 47 00   line#677  GETTABUP 2 0 -32       <56>   R2 = Upv#1@_ENV["Color3"]                       -- It's Const#32
		  +8C63: 87 00 48 01   line#677  GETTABLE 2 2 -33       <57>   R2 = R2["fromRGB"]                              -- It's Const#33
		  +8C67: C1 40 08 00   line#677  LOADK 3 -34            <58>   R3 = 80                                         -- It's Const#34
		  +8C6B: 01 81 08 00   line#677  LOADK 4 -35            <59>   R4 = 245                                        -- It's Const#35
		  +8C6F: 41 81 08 00   line#677  LOADK 5 -35            <60>   R5 = 245                                        -- It's Const#35
		  +8C73: A4 80 00 02   line#677  CALL 2 4 2             <61>   R2 = R2(R3, R4, R5)
		  +8C77: 4A 80 00 8F   line#677  SETTABLE 1 -31 2       <62>   R1@name["TextColor3"] = R2                      -- It's Const#31
		  +8C7B: 1E 40 08 80   line#677  JMP 0 34               <63>   GOTO <98>
		  +8C7F: 06 00 C1 00   line#679  GETTABUP 0 1 -5        <64>   R0 = Upv#2@v["NameEsp"]                         -- It's Const#5
		  +8C83: 07 C0 44 00   line#679  GETTABLE 0 0 -20       <65>   R0 = R0["TextLabel"]                            -- It's Const#20
		  +8C87: 46 40 C0 00   line#679  GETTABUP 1 1 -2        <66>   R1 = Upv#2@v["Name"]                            -- It's Const#2
		  +8C8B: 81 00 09 00   line#679  LOADK 2 -37            <67>   R2 = "   \n"                                    -- It's Const#37
		  +8C8F: C5 00 00 01   line#679  GETUPVAL 3 2           <68>   R3 = Upv#3@round
		  +8C93: 06 41 49 00   line#679  GETTABUP 4 0 -38       <69>   R4 = Upv#1@_ENV["game"]                         -- It's Const#38
		  +8C97: 0C 81 49 02   line#679  SELF 4 4 -39           <70>   R5 = R4;  R4 = R4["GetService"]                 -- It's Const#39   -- prepare for R4:GetService()
		  +8C9B: 81 C1 09 00   line#679  LOADK 6 -40            <71>   R6 = "Players"                                  -- It's Const#40
		  +8C9F: 24 81 80 01   line#679  CALL 4 3 2             <72>   R4 = R4(R5, R6)
		  +8CA3: 07 01 4A 02   line#679  GETTABLE 4 4 -41       <73>   R4 = R4["LocalPlayer"]                          -- It's Const#41
		  +8CA7: 07 41 4A 02   line#679  GETTABLE 4 4 -42       <74>   R4 = R4["Character"]                            -- It's Const#42
		  +8CAB: 07 81 4A 02   line#679  GETTABLE 4 4 -43       <75>   R4 = R4["Head"]                                 -- It's Const#43
		  +8CAF: 07 C1 4A 02   line#679  GETTABLE 4 4 -44       <76>   R4 = R4["Position"]                             -- It's Const#44
		  +8CB3: 46 C1 CA 00   line#679  GETTABUP 5 1 -44       <77>   R5 = Upv#2@v["Position"]                        -- It's Const#44
		  +8CB7: 0E 41 01 02   line#679  SUB 4 4 5              <78>   R4 = R4 - R5
		  +8CBB: 07 01 4B 02   line#679  GETTABLE 4 4 -45       <79>   R4 = R4["Magnitude"]                            -- It's Const#45
		  +8CBF: 12 41 4B 02   line#679  DIV 4 4 -46            <80>   R4 = R4 / 3                                     -- It's Const#46
		  +8CC3: E4 80 00 01   line#679  CALL 3 2 2             <81>   R3 = R3(R4)
		  +8CC7: 01 81 0B 00   line#679  LOADK 4 -47            <82>   R4 = " M"                                       -- It's Const#47
		  +8CCB: 5D 00 81 00   line#679  CONCAT 1 1 4           <83>   R1 = R1..R2..R3..R4
		  +8CCF: 0A 40 80 91   line#679  SETTABLE 0 -36 1       <84>   R0["Text"] = R1                                 -- It's Const#36
		  +8CD3: 1E C0 02 80   line#681  JMP 0 12               <85>   GOTO <98>
		  +8CD7: 05 00 80 00   line#683  GETUPVAL 0 1           <86>   R0 = Upv#2@v
		  +8CDB: 0C C0 40 00   line#683  SELF 0 0 -4            <87>   R1 = R0;  R0 = R0["FindFirstChild"]             -- It's Const#4   -- prepare for R0:FindFirstChild()
		  +8CDF: 81 00 01 00   line#683  LOADK 2 -5             <88>   R2 = "NameEsp"                                  -- It's Const#5
		  +8CE3: 24 80 80 01   line#683  CALL 0 3 2             <89>   R0 = R0(R1, R2)
		  +8CE7: 22 00 00 00   line#683  TEST 0 0               <90>   if R0 then GOTO <92>
		  +8CEB: 1E 40 01 80   line#683  JMP 0 6                <91>   GOTO <98>
		  +8CEF: 05 00 80 00   line#684  GETUPVAL 0 1           <92>   R0 = Upv#2@v
		  +8CF3: 0C C0 40 00   line#684  SELF 0 0 -4            <93>   R1 = R0;  R0 = R0["FindFirstChild"]             -- It's Const#4   -- prepare for R0:FindFirstChild()
		  +8CF7: 81 00 01 00   line#684  LOADK 2 -5             <94>   R2 = "NameEsp"                                  -- It's Const#5
		  +8CFB: 24 80 80 01   line#684  CALL 0 3 2             <95>   R0 = R0(R1, R2)
		  +8CFF: 0C C0 4B 00   line#684  SELF 0 0 -48           <96>   R1 = R0;  R0 = R0["Destroy"]                    -- It's Const#48   -- prepare for R0:Destroy()
		  +8D03: 24 40 00 01   line#684  CALL 0 2 1             <97>   R0(R1)
		  +8D07: 26 00 80 00   line#687  RETURN 0 1             <98>   RETURN
		Functions: 0

	************ Function#7   (full path: main.7)
	Source line#: 691..734
	Parameters: 0
	Is vararg: no
	VM registers needed: 7
	Constants: 6
	  +919D:Size=5: 70 61 69 72 73                  Const#1   string    "pairs"
	  +91A4:Size=4: 67 61 6D 65                     Const#2   string    "game"
	  +91AA:Size=A: 47 65 74 53 65 72 76 69 63 65   Const#3   string    "GetService"
	  +91B6:Size=9: 57 6F 72 6B 73 70 61 63 65      Const#4   string    "Workspace"
	  +91C1:Size=B: 47 65 74 43 68 69 6C 64 72...   Const#5   string    "GetChildren"
	  +91CE:Size=5: 70 63 61 6C 6C                  Const#6   string    "pcall"
	Upvalues: 2
	  Upv#1 is parent function's Upv#1              name: _ENV
	  Upv#2 is parent function's R0                 name: round
	Locals: 5
	  Local#1   R0   def:<8>    scope:<9..15>       name: (for generator)
	  Local#2   R1   def:<8>    scope:<9..15>       name: (for state)
	  Local#3   R2   def:<8>    scope:<9..15>       name: (for control)
	  Local#4   R3   def:<9>    scope:<10..13>      name: i
	  Local#5   R4   def:<9>    scope:<10..13>      name: v
	Instructions: 16
	  +9157: 06 00 40 00   line#692  GETTABUP 0 0 -1         <1>   R0 = Upv#1@_ENV["pairs"]                        -- It's Const#1
	  +915B: 46 40 40 00   line#692  GETTABUP 1 0 -2         <2>   R1 = Upv#1@_ENV["game"]                         -- It's Const#2
	  +915F: 4C 80 C0 00   line#692  SELF 1 1 -3             <3>   R2 = R1;  R1 = R1["GetService"]                 -- It's Const#3   -- prepare for R1:GetService()
	  +9163: C1 C0 00 00   line#692  LOADK 3 -4              <4>   R3 = "Workspace"                                -- It's Const#4
	  +9167: 64 80 80 01   line#692  CALL 1 3 2              <5>   R1 = R1(R2, R3)
	  +916B: 4C 00 C1 00   line#692  SELF 1 1 -5             <6>   R2 = R1;  R1 = R1["GetChildren"]                -- It's Const#5   -- prepare for R1:GetChildren()
	  +916F: 64 00 00 01   line#692  CALL 1 2 0              <7>   R1,.. = R1(R2)
	  +9173: 24 00 01 00   line#692  CALL 0 0 4              <8>   R0, R1, R2 = R0(R1,..)
	  +9177: 1E C0 00 80   line#692  JMP 0 4                 <9>   GOTO <14>                                       -- for R3@i, R4@v in R0, R1, R2 do
	  +917B: 46 41 41 00   line#693  GETTABUP 5 0 -6        <10>   R5 = Upv#1@_ENV["pcall"]                        -- It's Const#6
	  +917F: AC 01 00 00   line#732  CLOSURE 6 0            <11>   R6 = Function#1
	  +9183: 64 41 00 01   line#693  CALL 5 2 1             <12>   R5(R6)
	  +9187: 1E C1 FF 7F   line#732  JMP 4 0                <13>   CLOSE R3@i,..
	  +918B: 29 80 00 00   line#692  TFORCALL 0 2           <14>   R3, R4 = R0(R1, R2)
	  +918F: AA 40 FE 7F   line#692  TFORLOOP 2 -6          <15>   if R3 ~= nil then { R2 = R3;  GOTO <10> }       -- end of loop
	  +9193: 26 00 80 00   line#734  RETURN 0 1             <16>   RETURN
	Functions: 1

		************ Function#1   (full path: main.7.1)
		Source line#: 693..732
		Parameters: 0
		Is vararg: no
		VM registers needed: 8
		Constants: 58
		  +94E1:Size=6: 73 74 72 69 6E 67               Const#1   string    "string"
		  +94E9:Size=4: 66 69 6E 64                     Const#2   string    "find"
		  +94EF:Size=4: 4E 61 6D 65                     Const#3   string    "Name"
		  +94F5:Size=5: 43 68 65 73 74                  Const#4   string    "Chest"
		  +94FC:Size=8: 43 68 65 73 74 45 53 50         Const#5   string    "ChestESP"
		  +9506:Size=E: 46 69 6E 64 46 69 72 73 74...   Const#6   string    "FindFirstChild"
		  +9516:Size=7: 4E 61 6D 65 45 73 70            Const#7   string    "NameEsp"
		  +951F:Size=6: 4E 75 6D 62 65 72               Const#8   string    "Number"
		  +9527:Size=8: 49 6E 73 74 61 6E 63 65         Const#9   string    "Instance"
		  +9531:Size=3: 6E 65 77                        Const#10  string    "new"
		  +9536:Size=C: 42 69 6C 6C 62 6F 61 72 64...   Const#11  string    "BillboardGui"
		  +9544:Size=D: 45 78 74 65 6E 74 73 4F 66...   Const#12  string    "ExtentsOffset"
		  +9553:Size=7: 56 65 63 74 6F 72 33            Const#13  string    "Vector3"
		  +955B:Size=4: 00 00 00 00                     Const#14  integer   0
		  +9560:Size=4: 01 00 00 00                     Const#15  integer   1
		  +9566:Size=4: 53 69 7A 65                     Const#16  string    "Size"
		  +956C:Size=5: 55 44 69 6D 32                  Const#17  string    "UDim2"
		  +9572:Size=4: C8 00 00 00                     Const#18  integer   200
		  +9577:Size=4: 1E 00 00 00                     Const#19  integer   30
		  +957D:Size=7: 41 64 6F 72 6E 65 65            Const#20  string    "Adornee"
		  +9586:Size=B: 41 6C 77 61 79 73 4F 6E 54...   Const#21  string    "AlwaysOnTop"
		  +9592:Size=1: 01                              Const#22  boolean   true
		  +9595:Size=9: 54 65 78 74 4C 61 62 65 6C      Const#23  string    "TextLabel"
		  +95A0:Size=4: 46 6F 6E 74                     Const#24  string    "Font"
		  +95A6:Size=A: 47 6F 74 68 61 6D 42 6F 6C 64   Const#25  string    "GothamBold"
		  +95B2:Size=8: 46 6F 6E 74 53 69 7A 65         Const#26  string    "FontSize"
		  +95BC:Size=6: 53 69 7A 65 31 34               Const#27  string    "Size14"
		  +95C4:Size=B: 54 65 78 74 57 72 61 70 70...   Const#28  string    "TextWrapped"
		  +95D1:Size=E: 54 65 78 74 59 41 6C 69 67...   Const#29  string    "TextYAlignment"
		  +95E1:Size=3: 54 6F 70                        Const#30  string    "Top"
		  +95E6:Size=16: 42 61 63 6B 67 72 6F 75 6...   Const#31  string    "BackgroundTransparency"
		  +95FE:Size=16: 54 65 78 74 53 74 72 6F 6...   Const#32  string    "TextStrokeTransparency"
		  +9615:Size=8: 00 00 00 00 00 00 E0 3F         Const#33  float     0.5
		  +961F:Size=A: 54 65 78 74 43 6F 6C 6F 72 33   Const#34  string    "TextColor3"
		  +962B:Size=6: 43 6F 6C 6F 72 33               Const#35  string    "Color3"
		  +9633:Size=7: 66 72 6F 6D 52 47 42            Const#36  string    "fromRGB"
		  +963B:Size=4: FF 00 00 00                     Const#37  integer   255
		  +9640:Size=4: FA 00 00 00                     Const#38  integer   250
		  +9646:Size=6: 43 68 65 73 74 31               Const#39  string    "Chest1"
		  +964E:Size=4: 54 65 78 74                     Const#40  string    "Text"
		  +9654:Size=7: 43 68 65 73 74 20 31            Const#41  string    "Chest 1"
		  +965D:Size=2: 20 0A                           Const#42  string    " \n"
		  +9661:Size=4: 67 61 6D 65                     Const#43  string    "game"
		  +9667:Size=A: 47 65 74 53 65 72 76 69 63 65   Const#44  string    "GetService"
		  +9673:Size=7: 50 6C 61 79 65 72 73            Const#45  string    "Players"
		  +967C:Size=B: 4C 6F 63 61 6C 50 6C 61 79...   Const#46  string    "LocalPlayer"
		  +9689:Size=9: 43 68 61 72 61 63 74 65 72      Const#47  string    "Character"
		  +9694:Size=4: 48 65 61 64                     Const#48  string    "Head"
		  +969A:Size=8: 50 6F 73 69 74 69 6F 6E         Const#49  string    "Position"
		  +96A4:Size=9: 4D 61 67 6E 69 74 75 64 65      Const#50  string    "Magnitude"
		  +96AE:Size=4: 03 00 00 00                     Const#51  integer   3
		  +96B4:Size=2: 20 4D                           Const#52  string    " M"
		  +96B8:Size=6: 43 68 65 73 74 32               Const#53  string    "Chest2"
		  +96C0:Size=7: 43 68 65 73 74 20 32            Const#54  string    "Chest 2"
		  +96C9:Size=6: 43 68 65 73 74 33               Const#55  string    "Chest3"
		  +96D1:Size=7: 43 68 65 73 74 20 33            Const#56  string    "Chest 3"
		  +96DA:Size=4: 20 20 20 0A                     Const#57  string    "   \n"
		  +96E0:Size=7: 44 65 73 74 72 6F 79            Const#58  string    "Destroy"
		Upvalues: 3
		  Upv#1 is parent function's Upv#1              name: _ENV
		  Upv#2 is parent function's R4                 name: v
		  Upv#3 is parent function's Upv#2              name: round
		Locals: 2
		  Local#1   R0   def:<30>   scope:<31..144>     name: bill
		  Local#2   R1   def:<57>   scope:<58..144>     name: name
		Instructions: 187
		  +91EF: 06 00 40 00   line#694  GETTABUP 0 0 -1         <1>   R0 = Upv#1@_ENV["string"]                       -- It's Const#1
		  +91F3: 07 40 40 00   line#694  GETTABLE 0 0 -2         <2>   R0 = R0["find"]                                 -- It's Const#2
		  +91F7: 46 80 C0 00   line#694  GETTABUP 1 1 -3         <3>   R1 = Upv#2@v["Name"]                            -- It's Const#3
		  +91FB: 81 C0 00 00   line#694  LOADK 2 -4              <4>   R2 = "Chest"                                    -- It's Const#4
		  +91FF: 24 80 80 01   line#694  CALL 0 3 2              <5>   R0 = R0(R1, R2)
		  +9203: 22 00 00 00   line#694  TEST 0 0                <6>   if R0 then GOTO <8>
		  +9207: 1E 80 2C 80   line#694  JMP 0 179               <7>   GOTO <187>
		  +920B: 06 00 41 00   line#695  GETTABUP 0 0 -5         <8>   R0 = Upv#1@_ENV["ChestESP"]                     -- It's Const#5
		  +920F: 22 00 00 00   line#695  TEST 0 0                <9>   if R0 then GOTO <11>
		  +9213: 1E C0 27 80   line#695  JMP 0 160              <10>   GOTO <171>
		  +9217: 06 00 40 00   line#696  GETTABUP 0 0 -1        <11>   R0 = Upv#1@_ENV["string"]                       -- It's Const#1
		  +921B: 07 40 40 00   line#696  GETTABLE 0 0 -2        <12>   R0 = R0["find"]                                 -- It's Const#2
		  +921F: 46 80 C0 00   line#696  GETTABUP 1 1 -3        <13>   R1 = Upv#2@v["Name"]                            -- It's Const#3
		  +9223: 81 C0 00 00   line#696  LOADK 2 -4             <14>   R2 = "Chest"                                    -- It's Const#4
		  +9227: 24 80 80 01   line#696  CALL 0 3 2             <15>   R0 = R0(R1, R2)
		  +922B: 22 00 00 00   line#696  TEST 0 0               <16>   if R0 then GOTO <18>
		  +922F: 1E 00 2A 80   line#696  JMP 0 169              <17>   GOTO <187>
		  +9233: 05 00 80 00   line#697  GETUPVAL 0 1           <18>   R0 = Upv#2@v
		  +9237: 0C 40 41 00   line#697  SELF 0 0 -6            <19>   R1 = R0;  R0 = R0["FindFirstChild"]             -- It's Const#6   -- prepare for R0:FindFirstChild()
		  +923B: 81 80 01 00   line#697  LOADK 2 -7             <20>   R2 = "NameEsp"                                  -- It's Const#7
		  +923F: C6 C0 41 00   line#697  GETTABUP 3 0 -8        <21>   R3 = Upv#1@_ENV["Number"]                       -- It's Const#8
		  +9243: 9D C0 00 01   line#697  CONCAT 2 2 3           <22>   R2 = R2..R3
		  +9247: 24 80 80 01   line#697  CALL 0 3 2             <23>   R0 = R0(R1, R2)
		  +924B: 22 40 00 00   line#697  TEST 0 1               <24>   if not R0 then GOTO <26>
		  +924F: 1E C0 1D 80   line#697  JMP 0 120              <25>   GOTO <146>
		  +9253: 06 00 42 00   line#698  GETTABUP 0 0 -9        <26>   R0 = Upv#1@_ENV["Instance"]                     -- It's Const#9
		  +9257: 07 40 42 00   line#698  GETTABLE 0 0 -10       <27>   R0 = R0["new"]                                  -- It's Const#10
		  +925B: 41 80 02 00   line#698  LOADK 1 -11            <28>   R1 = "BillboardGui"                             -- It's Const#11
		  +925F: 85 00 80 00   line#698  GETUPVAL 2 1           <29>   R2 = Upv#2@v
		  +9263: 24 80 80 01   line#698  CALL 0 3 2             <30>   R0@bill = R0(R1, R2)
		  +9267: 41 80 01 00   line#699  LOADK 1 -7             <31>   R1 = "NameEsp"                                  -- It's Const#7
		  +926B: 86 C0 41 00   line#699  GETTABUP 2 0 -8        <32>   R2 = Upv#1@_ENV["Number"]                       -- It's Const#8
		  +926F: 5D 80 80 00   line#699  CONCAT 1 1 2           <33>   R1 = R1..R2
		  +9273: 0A 40 00 81   line#699  SETTABLE 0 -3 1        <34>   R0@bill["Name"] = R1                            -- It's Const#3
		  +9277: 46 00 43 00   line#700  GETTABUP 1 0 -13       <35>   R1 = Upv#1@_ENV["Vector3"]                      -- It's Const#13
		  +927B: 47 40 C2 00   line#700  GETTABLE 1 1 -10       <36>   R1 = R1["new"]                                  -- It's Const#10
		  +927F: 81 40 03 00   line#700  LOADK 2 -14            <37>   R2 = 0                                          -- It's Const#14
		  +9283: C1 80 03 00   line#700  LOADK 3 -15            <38>   R3 = 1                                          -- It's Const#15
		  +9287: 01 41 03 00   line#700  LOADK 4 -14            <39>   R4 = 0                                          -- It's Const#14
		  +928B: 64 80 00 02   line#700  CALL 1 4 2             <40>   R1 = R1(R2, R3, R4)
		  +928F: 0A 40 80 85   line#700  SETTABLE 0 -12 1       <41>   R0@bill["ExtentsOffset"] = R1                   -- It's Const#12
		  +9293: 46 00 44 00   line#701  GETTABUP 1 0 -17       <42>   R1 = Upv#1@_ENV["UDim2"]                        -- It's Const#17
		  +9297: 47 40 C2 00   line#701  GETTABLE 1 1 -10       <43>   R1 = R1["new"]                                  -- It's Const#10
		  +929B: 81 80 03 00   line#701  LOADK 2 -15            <44>   R2 = 1                                          -- It's Const#15
		  +929F: C1 40 04 00   line#701  LOADK 3 -18            <45>   R3 = 200                                        -- It's Const#18
		  +92A3: 01 81 03 00   line#701  LOADK 4 -15            <46>   R4 = 1                                          -- It's Const#15
		  +92A7: 41 81 04 00   line#701  LOADK 5 -19            <47>   R5 = 30                                         -- It's Const#19
		  +92AB: 64 80 80 02   line#701  CALL 1 5 2             <48>   R1 = R1(R2,..,R5)
		  +92AF: 0A 40 80 87   line#701  SETTABLE 0 -16 1       <49>   R0@bill["Size"] = R1                            -- It's Const#16
		  +92B3: 45 00 80 00   line#702  GETUPVAL 1 1           <50>   R1 = Upv#2@v
		  +92B7: 0A 40 80 89   line#702  SETTABLE 0 -20 1       <51>   R0@bill["Adornee"] = R1                         -- It's Const#20
		  +92BB: 0A 40 45 8A   line#703  SETTABLE 0 -21 -22     <52>   R0@bill["AlwaysOnTop"] = true                   -- It's Const#21, Const#22
		  +92BF: 46 00 42 00   line#704  GETTABUP 1 0 -9        <53>   R1 = Upv#1@_ENV["Instance"]                     -- It's Const#9
		  +92C3: 47 40 C2 00   line#704  GETTABLE 1 1 -10       <54>   R1 = R1["new"]                                  -- It's Const#10
		  +92C7: 81 80 05 00   line#704  LOADK 2 -23            <55>   R2 = "TextLabel"                                -- It's Const#23
		  +92CB: C0 00 00 00   line#704  MOVE 3 0               <56>   R3 = R0@bill
		  +92CF: 64 80 80 01   line#704  CALL 1 3 2             <57>   R1@name = R1(R2, R3)
		  +92D3: 4A 00 C6 8B   line#705  SETTABLE 1 -24 -25     <58>   R1@name["Font"] = "GothamBold"                  -- It's Const#24, Const#25
		  +92D7: 4A 80 C6 8C   line#706  SETTABLE 1 -26 -27     <59>   R1@name["FontSize"] = "Size14"                  -- It's Const#26, Const#27
		  +92DB: 4A 40 C5 8D   line#707  SETTABLE 1 -28 -22     <60>   R1@name["TextWrapped"] = true                   -- It's Const#28, Const#22
		  +92DF: 86 00 44 00   line#708  GETTABUP 2 0 -17       <61>   R2 = Upv#1@_ENV["UDim2"]                        -- It's Const#17
		  +92E3: 87 40 42 01   line#708  GETTABLE 2 2 -10       <62>   R2 = R2["new"]                                  -- It's Const#10
		  +92E7: C1 80 03 00   line#708  LOADK 3 -15            <63>   R3 = 1                                          -- It's Const#15
		  +92EB: 01 41 03 00   line#708  LOADK 4 -14            <64>   R4 = 0                                          -- It's Const#14
		  +92EF: 41 81 03 00   line#708  LOADK 5 -15            <65>   R5 = 1                                          -- It's Const#15
		  +92F3: 81 41 03 00   line#708  LOADK 6 -14            <66>   R6 = 0                                          -- It's Const#14
		  +92F7: A4 80 80 02   line#708  CALL 2 5 2             <67>   R2 = R2(R3,..,R6)
		  +92FB: 4A 80 80 87   line#708  SETTABLE 1 -16 2       <68>   R1@name["Size"] = R2                            -- It's Const#16
		  +92FF: 4A 40 47 8E   line#709  SETTABLE 1 -29 -30     <69>   R1@name["TextYAlignment"] = "Top"               -- It's Const#29, Const#30
		  +9303: 4A 80 43 8F   line#710  SETTABLE 1 -31 -15     <70>   R1@name["BackgroundTransparency"] = 1           -- It's Const#31, Const#15
		  +9307: 4A 00 C8 8F   line#711  SETTABLE 1 -32 -33     <71>   R1@name["TextStrokeTransparency"] = 0.5         -- It's Const#32, Const#33
		  +930B: 86 80 48 00   line#712  GETTABUP 2 0 -35       <72>   R2 = Upv#1@_ENV["Color3"]                       -- It's Const#35
		  +930F: 87 C0 48 01   line#712  GETTABLE 2 2 -36       <73>   R2 = R2["fromRGB"]                              -- It's Const#36
		  +9313: C1 40 03 00   line#712  LOADK 3 -14            <74>   R3 = 0                                          -- It's Const#14
		  +9317: 01 01 09 00   line#712  LOADK 4 -37            <75>   R4 = 255                                        -- It's Const#37
		  +931B: 41 41 09 00   line#712  LOADK 5 -38            <76>   R5 = 250                                        -- It's Const#38
		  +931F: A4 80 00 02   line#712  CALL 2 4 2             <77>   R2 = R2(R3, R4, R5)
		  +9323: 4A 80 80 90   line#712  SETTABLE 1 -34 2       <78>   R1@name["TextColor3"] = R2                      -- It's Const#34
		  +9327: 86 80 C0 00   line#713  GETTABUP 2 1 -3        <79>   R2 = Upv#2@v["Name"]                            -- It's Const#3
		  +932B: 1F 80 49 01   line#713  EQ 0 2 -39             <80>   if R2 == "Chest1" then GOTO <82>                -- It's Const#39
		  +932F: 1E 80 04 80   line#713  JMP 0 19               <81>   GOTO <101>
		  +9333: 81 00 0A 00   line#714  LOADK 2 -41            <82>   R2 = "Chest 1"                                  -- It's Const#41
		  +9337: C1 40 0A 00   line#714  LOADK 3 -42            <83>   R3 = " \n"                                      -- It's Const#42
		  +933B: 05 01 00 01   line#714  GETUPVAL 4 2           <84>   R4 = Upv#3@round
		  +933F: 46 81 4A 00   line#714  GETTABUP 5 0 -43       <85>   R5 = Upv#1@_ENV["game"]                         -- It's Const#43
		  +9343: 4C C1 CA 02   line#714  SELF 5 5 -44           <86>   R6 = R5;  R5 = R5["GetService"]                 -- It's Const#44   -- prepare for R5:GetService()
		  +9347: C1 01 0B 00   line#714  LOADK 7 -45            <87>   R7 = "Players"                                  -- It's Const#45
		  +934B: 64 81 80 01   line#714  CALL 5 3 2             <88>   R5 = R5(R6, R7)
		  +934F: 47 41 CB 02   line#714  GETTABLE 5 5 -46       <89>   R5 = R5["LocalPlayer"]                          -- It's Const#46
		  +9353: 47 81 CB 02   line#714  GETTABLE 5 5 -47       <90>   R5 = R5["Character"]                            -- It's Const#47
		  +9357: 47 C1 CB 02   line#714  GETTABLE 5 5 -48       <91>   R5 = R5["Head"]                                 -- It's Const#48
		  +935B: 47 01 CC 02   line#714  GETTABLE 5 5 -49       <92>   R5 = R5["Position"]                             -- It's Const#49
		  +935F: 86 01 CC 00   line#714  GETTABUP 6 1 -49       <93>   R6 = Upv#2@v["Position"]                        -- It's Const#49
		  +9363: 4E 81 81 02   line#714  SUB 5 5 6              <94>   R5 = R5 - R6
		  +9367: 47 41 CC 02   line#714  GETTABLE 5 5 -50       <95>   R5 = R5["Magnitude"]                            -- It's Const#50
		  +936B: 52 81 CC 02   line#714  DIV 5 5 -51            <96>   R5 = R5 / 3                                     -- It's Const#51
		  +936F: 24 81 00 01   line#714  CALL 4 2 2             <97>   R4 = R4(R5)
		  +9373: 41 C1 0C 00   line#714  LOADK 5 -52            <98>   R5 = " M"                                       -- It's Const#52
		  +9377: 9D 40 01 01   line#714  CONCAT 2 2 5           <99>   R2 = R2..R3..R4..R5
		  +937B: 4A 80 80 93   line#714  SETTABLE 1 -40 2      <100>   R1@name["Text"] = R2                            -- It's Const#40
		  +937F: 86 80 C0 00   line#716  GETTABUP 2 1 -3       <101>   R2 = Upv#2@v["Name"]                            -- It's Const#3
		  +9383: 1F 00 4D 01   line#716  EQ 0 2 -53            <102>   if R2 == "Chest2" then GOTO <104>               -- It's Const#53
		  +9387: 1E 80 04 80   line#716  JMP 0 19              <103>   GOTO <123>
		  +938B: 81 40 0D 00   line#717  LOADK 2 -54           <104>   R2 = "Chest 2"                                  -- It's Const#54
		  +938F: C1 40 0A 00   line#717  LOADK 3 -42           <105>   R3 = " \n"                                      -- It's Const#42
		  +9393: 05 01 00 01   line#717  GETUPVAL 4 2          <106>   R4 = Upv#3@round
		  +9397: 46 81 4A 00   line#717  GETTABUP 5 0 -43      <107>   R5 = Upv#1@_ENV["game"]                         -- It's Const#43
		  +939B: 4C C1 CA 02   line#717  SELF 5 5 -44          <108>   R6 = R5;  R5 = R5["GetService"]                 -- It's Const#44   -- prepare for R5:GetService()
		  +939F: C1 01 0B 00   line#717  LOADK 7 -45           <109>   R7 = "Players"                                  -- It's Const#45
		  +93A3: 64 81 80 01   line#717  CALL 5 3 2            <110>   R5 = R5(R6, R7)
		  +93A7: 47 41 CB 02   line#717  GETTABLE 5 5 -46      <111>   R5 = R5["LocalPlayer"]                          -- It's Const#46
		  +93AB: 47 81 CB 02   line#717  GETTABLE 5 5 -47      <112>   R5 = R5["Character"]                            -- It's Const#47
		  +93AF: 47 C1 CB 02   line#717  GETTABLE 5 5 -48      <113>   R5 = R5["Head"]                                 -- It's Const#48
		  +93B3: 47 01 CC 02   line#717  GETTABLE 5 5 -49      <114>   R5 = R5["Position"]                             -- It's Const#49
		  +93B7: 86 01 CC 00   line#717  GETTABUP 6 1 -49      <115>   R6 = Upv#2@v["Position"]                        -- It's Const#49
		  +93BB: 4E 81 81 02   line#717  SUB 5 5 6             <116>   R5 = R5 - R6
		  +93BF: 47 41 CC 02   line#717  GETTABLE 5 5 -50      <117>   R5 = R5["Magnitude"]                            -- It's Const#50
		  +93C3: 52 81 CC 02   line#717  DIV 5 5 -51           <118>   R5 = R5 / 3                                     -- It's Const#51
		  +93C7: 24 81 00 01   line#717  CALL 4 2 2            <119>   R4 = R4(R5)
		  +93CB: 41 C1 0C 00   line#717  LOADK 5 -52           <120>   R5 = " M"                                       -- It's Const#52
		  +93CF: 9D 40 01 01   line#717  CONCAT 2 2 5          <121>   R2 = R2..R3..R4..R5
		  +93D3: 4A 80 80 93   line#717  SETTABLE 1 -40 2      <122>   R1@name["Text"] = R2                            -- It's Const#40
		  +93D7: 86 80 C0 00   line#719  GETTABUP 2 1 -3       <123>   R2 = Upv#2@v["Name"]                            -- It's Const#3
		  +93DB: 1F 80 4D 01   line#719  EQ 0 2 -55            <124>   if R2 == "Chest3" then GOTO <126>               -- It's Const#55
		  +93DF: 1E 00 0F 80   line#719  JMP 0 61              <125>   GOTO <187>
		  +93E3: 81 C0 0D 00   line#720  LOADK 2 -56           <126>   R2 = "Chest 3"                                  -- It's Const#56
		  +93E7: C1 40 0A 00   line#720  LOADK 3 -42           <127>   R3 = " \n"                                      -- It's Const#42
		  +93EB: 05 01 00 01   line#720  GETUPVAL 4 2          <128>   R4 = Upv#3@round
		  +93EF: 46 81 4A 00   line#720  GETTABUP 5 0 -43      <129>   R5 = Upv#1@_ENV["game"]                         -- It's Const#43
		  +93F3: 4C C1 CA 02   line#720  SELF 5 5 -44          <130>   R6 = R5;  R5 = R5["GetService"]                 -- It's Const#44   -- prepare for R5:GetService()
		  +93F7: C1 01 0B 00   line#720  LOADK 7 -45           <131>   R7 = "Players"                                  -- It's Const#45
		  +93FB: 64 81 80 01   line#720  CALL 5 3 2            <132>   R5 = R5(R6, R7)
		  +93FF: 47 41 CB 02   line#720  GETTABLE 5 5 -46      <133>   R5 = R5["LocalPlayer"]                          -- It's Const#46
		  +9403: 47 81 CB 02   line#720  GETTABLE 5 5 -47      <134>   R5 = R5["Character"]                            -- It's Const#47
		  +9407: 47 C1 CB 02   line#720  GETTABLE 5 5 -48      <135>   R5 = R5["Head"]                                 -- It's Const#48
		  +940B: 47 01 CC 02   line#720  GETTABLE 5 5 -49      <136>   R5 = R5["Position"]                             -- It's Const#49
		  +940F: 86 01 CC 00   line#720  GETTABUP 6 1 -49      <137>   R6 = Upv#2@v["Position"]                        -- It's Const#49
		  +9413: 4E 81 81 02   line#720  SUB 5 5 6             <138>   R5 = R5 - R6
		  +9417: 47 41 CC 02   line#720  GETTABLE 5 5 -50      <139>   R5 = R5["Magnitude"]                            -- It's Const#50
		  +941B: 52 81 CC 02   line#720  DIV 5 5 -51           <140>   R5 = R5 / 3                                     -- It's Const#51
		  +941F: 24 81 00 01   line#720  CALL 4 2 2            <141>   R4 = R4(R5)
		  +9423: 41 C1 0C 00   line#720  LOADK 5 -52           <142>   R5 = " M"                                       -- It's Const#52
		  +9427: 9D 40 01 01   line#720  CONCAT 2 2 5          <143>   R2 = R2..R3..R4..R5
		  +942B: 4A 80 80 93   line#720  SETTABLE 1 -40 2      <144>   R1@name["Text"] = R2                            -- It's Const#40
		  +942F: 1E 00 0A 80   line#721  JMP 0 41              <145>   GOTO <187>
		  +9433: 01 80 01 00   line#723  LOADK 0 -7            <146>   R0 = "NameEsp"                                  -- It's Const#7
		  +9437: 46 C0 41 00   line#723  GETTABUP 1 0 -8       <147>   R1 = Upv#1@_ENV["Number"]                       -- It's Const#8
		  +943B: 1D 40 00 00   line#723  CONCAT 0 0 1          <148>   R0 = R0..R1
		  +943F: 06 00 80 00   line#723  GETTABUP 0 1 0        <149>   R0 = Upv#2@v[R0]
		  +9443: 07 80 45 00   line#723  GETTABLE 0 0 -23      <150>   R0 = R0["TextLabel"]                            -- It's Const#23
		  +9447: 46 80 C0 00   line#723  GETTABUP 1 1 -3       <151>   R1 = Upv#2@v["Name"]                            -- It's Const#3
		  +944B: 81 00 0E 00   line#723  LOADK 2 -57           <152>   R2 = "   \n"                                    -- It's Const#57
		  +944F: C5 00 00 01   line#723  GETUPVAL 3 2          <153>   R3 = Upv#3@round
		  +9453: 06 81 4A 00   line#723  GETTABUP 4 0 -43      <154>   R4 = Upv#1@_ENV["game"]                         -- It's Const#43
		  +9457: 0C C1 4A 02   line#723  SELF 4 4 -44          <155>   R5 = R4;  R4 = R4["GetService"]                 -- It's Const#44   -- prepare for R4:GetService()
		  +945B: 81 01 0B 00   line#723  LOADK 6 -45           <156>   R6 = "Players"                                  -- It's Const#45
		  +945F: 24 81 80 01   line#723  CALL 4 3 2            <157>   R4 = R4(R5, R6)
		  +9463: 07 41 4B 02   line#723  GETTABLE 4 4 -46      <158>   R4 = R4["LocalPlayer"]                          -- It's Const#46
		  +9467: 07 81 4B 02   line#723  GETTABLE 4 4 -47      <159>   R4 = R4["Character"]                            -- It's Const#47
		  +946B: 07 C1 4B 02   line#723  GETTABLE 4 4 -48      <160>   R4 = R4["Head"]                                 -- It's Const#48
		  +946F: 07 01 4C 02   line#723  GETTABLE 4 4 -49      <161>   R4 = R4["Position"]                             -- It's Const#49
		  +9473: 46 01 CC 00   line#723  GETTABUP 5 1 -49      <162>   R5 = Upv#2@v["Position"]                        -- It's Const#49
		  +9477: 0E 41 01 02   line#723  SUB 4 4 5             <163>   R4 = R4 - R5
		  +947B: 07 41 4C 02   line#723  GETTABLE 4 4 -50      <164>   R4 = R4["Magnitude"]                            -- It's Const#50
		  +947F: 12 81 4C 02   line#723  DIV 4 4 -51           <165>   R4 = R4 / 3                                     -- It's Const#51
		  +9483: E4 80 00 01   line#723  CALL 3 2 2            <166>   R3 = R3(R4)
		  +9487: 01 C1 0C 00   line#723  LOADK 4 -52           <167>   R4 = " M"                                       -- It's Const#52
		  +948B: 5D 00 81 00   line#723  CONCAT 1 1 4          <168>   R1 = R1..R2..R3..R4
		  +948F: 0A 40 80 93   line#723  SETTABLE 0 -40 1      <169>   R0["Text"] = R1                                 -- It's Const#40
		  +9493: 1E C0 03 80   line#725  JMP 0 16              <170>   GOTO <187>
		  +9497: 05 00 80 00   line#727  GETUPVAL 0 1          <171>   R0 = Upv#2@v
		  +949B: 0C 40 41 00   line#727  SELF 0 0 -6           <172>   R1 = R0;  R0 = R0["FindFirstChild"]             -- It's Const#6   -- prepare for R0:FindFirstChild()
		  +949F: 81 80 01 00   line#727  LOADK 2 -7            <173>   R2 = "NameEsp"                                  -- It's Const#7
		  +94A3: C6 C0 41 00   line#727  GETTABUP 3 0 -8       <174>   R3 = Upv#1@_ENV["Number"]                       -- It's Const#8
		  +94A7: 9D C0 00 01   line#727  CONCAT 2 2 3          <175>   R2 = R2..R3
		  +94AB: 24 80 80 01   line#727  CALL 0 3 2            <176>   R0 = R0(R1, R2)
		  +94AF: 22 00 00 00   line#727  TEST 0 0              <177>   if R0 then GOTO <179>
		  +94B3: 1E C0 01 80   line#727  JMP 0 8               <178>   GOTO <187>
		  +94B7: 05 00 80 00   line#728  GETUPVAL 0 1          <179>   R0 = Upv#2@v
		  +94BB: 0C 40 41 00   line#728  SELF 0 0 -6           <180>   R1 = R0;  R0 = R0["FindFirstChild"]             -- It's Const#6   -- prepare for R0:FindFirstChild()
		  +94BF: 81 80 01 00   line#728  LOADK 2 -7            <181>   R2 = "NameEsp"                                  -- It's Const#7
		  +94C3: C6 C0 41 00   line#728  GETTABUP 3 0 -8       <182>   R3 = Upv#1@_ENV["Number"]                       -- It's Const#8
		  +94C7: 9D C0 00 01   line#728  CONCAT 2 2 3          <183>   R2 = R2..R3
		  +94CB: 24 80 80 01   line#728  CALL 0 3 2            <184>   R0 = R0(R1, R2)
		  +94CF: 0C 40 4E 00   line#728  SELF 0 0 -58          <185>   R1 = R0;  R0 = R0["Destroy"]                    -- It's Const#58   -- prepare for R0:Destroy()
		  +94D3: 24 40 00 01   line#728  CALL 0 2 1            <186>   R0(R1)
		  +94D7: 26 00 80 00   line#732  RETURN 0 1            <187>   RETURN
		Functions: 0

	************ Function#8   (full path: main.8)
	Source line#: 736..769
	Parameters: 0
	Is vararg: no
	VM registers needed: 7
	Constants: 6
	  +9B17:Size=5: 70 61 69 72 73                  Const#1   string    "pairs"
	  +9B1E:Size=4: 67 61 6D 65                     Const#2   string    "game"
	  +9B24:Size=A: 47 65 74 53 65 72 76 69 63 65   Const#3   string    "GetService"
	  +9B30:Size=9: 57 6F 72 6B 73 70 61 63 65      Const#4   string    "Workspace"
	  +9B3B:Size=B: 47 65 74 43 68 69 6C 64 72...   Const#5   string    "GetChildren"
	  +9B48:Size=5: 70 63 61 6C 6C                  Const#6   string    "pcall"
	Upvalues: 2
	  Upv#1 is parent function's Upv#1              name: _ENV
	  Upv#2 is parent function's R0                 name: round
	Locals: 5
	  Local#1   R0   def:<8>    scope:<9..15>       name: (for generator)
	  Local#2   R1   def:<8>    scope:<9..15>       name: (for state)
	  Local#3   R2   def:<8>    scope:<9..15>       name: (for control)
	  Local#4   R3   def:<9>    scope:<10..13>      name: i
	  Local#5   R4   def:<9>    scope:<10..13>      name: v
	Instructions: 16
	  +9AD1: 06 00 40 00   line#737  GETTABUP 0 0 -1         <1>   R0 = Upv#1@_ENV["pairs"]                        -- It's Const#1
	  +9AD5: 46 40 40 00   line#737  GETTABUP 1 0 -2         <2>   R1 = Upv#1@_ENV["game"]                         -- It's Const#2
	  +9AD9: 4C 80 C0 00   line#737  SELF 1 1 -3             <3>   R2 = R1;  R1 = R1["GetService"]                 -- It's Const#3   -- prepare for R1:GetService()
	  +9ADD: C1 C0 00 00   line#737  LOADK 3 -4              <4>   R3 = "Workspace"                                -- It's Const#4
	  +9AE1: 64 80 80 01   line#737  CALL 1 3 2              <5>   R1 = R1(R2, R3)
	  +9AE5: 4C 00 C1 00   line#737  SELF 1 1 -5             <6>   R2 = R1;  R1 = R1["GetChildren"]                -- It's Const#5   -- prepare for R1:GetChildren()
	  +9AE9: 64 00 00 01   line#737  CALL 1 2 0              <7>   R1,.. = R1(R2)
	  +9AED: 24 00 01 00   line#737  CALL 0 0 4              <8>   R0, R1, R2 = R0(R1,..)
	  +9AF1: 1E C0 00 80   line#737  JMP 0 4                 <9>   GOTO <14>                                       -- for R3@i, R4@v in R0, R1, R2 do
	  +9AF5: 46 41 41 00   line#738  GETTABUP 5 0 -6        <10>   R5 = Upv#1@_ENV["pcall"]                        -- It's Const#6
	  +9AF9: AC 01 00 00   line#767  CLOSURE 6 0            <11>   R6 = Function#1
	  +9AFD: 64 41 00 01   line#738  CALL 5 2 1             <12>   R5(R6)
	  +9B01: 1E C1 FF 7F   line#767  JMP 4 0                <13>   CLOSE R3@i,..
	  +9B05: 29 80 00 00   line#737  TFORCALL 0 2           <14>   R3, R4 = R0(R1, R2)
	  +9B09: AA 40 FE 7F   line#737  TFORLOOP 2 -6          <15>   if R3 ~= nil then { R2 = R3;  GOTO <10> }       -- end of loop
	  +9B0D: 26 00 80 00   line#769  RETURN 0 1             <16>   RETURN
	Functions: 1

		************ Function#1   (full path: main.8.1)
		Source line#: 738..767
		Parameters: 0
		Is vararg: no
		VM registers needed: 8
		Constants: 52
		  +9D8F:Size=D: 44 65 76 69 6C 46 72 75 69...   Const#1   string    "DevilFruitESP"
		  +9D9E:Size=6: 73 74 72 69 6E 67               Const#2   string    "string"
		  +9DA6:Size=4: 66 69 6E 64                     Const#3   string    "find"
		  +9DAC:Size=4: 4E 61 6D 65                     Const#4   string    "Name"
		  +9DB2:Size=5: 46 72 75 69 74                  Const#5   string    "Fruit"
		  +9DB9:Size=6: 48 61 6E 64 6C 65               Const#6   string    "Handle"
		  +9DC1:Size=E: 46 69 6E 64 46 69 72 73 74...   Const#7   string    "FindFirstChild"
		  +9DD1:Size=7: 4E 61 6D 65 45 73 70            Const#8   string    "NameEsp"
		  +9DDA:Size=6: 4E 75 6D 62 65 72               Const#9   string    "Number"
		  +9DE2:Size=8: 49 6E 73 74 61 6E 63 65         Const#10  string    "Instance"
		  +9DEC:Size=3: 6E 65 77                        Const#11  string    "new"
		  +9DF1:Size=C: 42 69 6C 6C 62 6F 61 72 64...   Const#12  string    "BillboardGui"
		  +9DFF:Size=D: 45 78 74 65 6E 74 73 4F 66...   Const#13  string    "ExtentsOffset"
		  +9E0E:Size=7: 56 65 63 74 6F 72 33            Const#14  string    "Vector3"
		  +9E16:Size=4: 00 00 00 00                     Const#15  integer   0
		  +9E1B:Size=4: 01 00 00 00                     Const#16  integer   1
		  +9E21:Size=4: 53 69 7A 65                     Const#17  string    "Size"
		  +9E27:Size=5: 55 44 69 6D 32                  Const#18  string    "UDim2"
		  +9E2D:Size=4: C8 00 00 00                     Const#19  integer   200
		  +9E32:Size=4: 1E 00 00 00                     Const#20  integer   30
		  +9E38:Size=7: 41 64 6F 72 6E 65 65            Const#21  string    "Adornee"
		  +9E41:Size=B: 41 6C 77 61 79 73 4F 6E 54...   Const#22  string    "AlwaysOnTop"
		  +9E4D:Size=1: 01                              Const#23  boolean   true
		  +9E50:Size=9: 54 65 78 74 4C 61 62 65 6C      Const#24  string    "TextLabel"
		  +9E5B:Size=4: 46 6F 6E 74                     Const#25  string    "Font"
		  +9E61:Size=A: 47 6F 74 68 61 6D 42 6F 6C 64   Const#26  string    "GothamBold"
		  +9E6D:Size=8: 46 6F 6E 74 53 69 7A 65         Const#27  string    "FontSize"
		  +9E77:Size=6: 53 69 7A 65 31 34               Const#28  string    "Size14"
		  +9E7F:Size=B: 54 65 78 74 57 72 61 70 70...   Const#29  string    "TextWrapped"
		  +9E8C:Size=E: 54 65 78 74 59 41 6C 69 67...   Const#30  string    "TextYAlignment"
		  +9E9C:Size=3: 54 6F 70                        Const#31  string    "Top"
		  +9EA1:Size=16: 42 61 63 6B 67 72 6F 75 6...   Const#32  string    "BackgroundTransparency"
		  +9EB9:Size=16: 54 65 78 74 53 74 72 6F 6...   Const#33  string    "TextStrokeTransparency"
		  +9ED0:Size=8: 00 00 00 00 00 00 E0 3F         Const#34  float     0.5
		  +9EDA:Size=A: 54 65 78 74 43 6F 6C 6F 72 33   Const#35  string    "TextColor3"
		  +9EE6:Size=6: 43 6F 6C 6F 72 33               Const#36  string    "Color3"
		  +9EEE:Size=7: 66 72 6F 6D 52 47 42            Const#37  string    "fromRGB"
		  +9EF6:Size=4: FF 00 00 00                     Const#38  integer   255
		  +9EFC:Size=4: 54 65 78 74                     Const#39  string    "Text"
		  +9F02:Size=2: 20 0A                           Const#40  string    " \n"
		  +9F06:Size=4: 67 61 6D 65                     Const#41  string    "game"
		  +9F0C:Size=A: 47 65 74 53 65 72 76 69 63 65   Const#42  string    "GetService"
		  +9F18:Size=7: 50 6C 61 79 65 72 73            Const#43  string    "Players"
		  +9F21:Size=B: 4C 6F 63 61 6C 50 6C 61 79...   Const#44  string    "LocalPlayer"
		  +9F2E:Size=9: 43 68 61 72 61 63 74 65 72      Const#45  string    "Character"
		  +9F39:Size=4: 48 65 61 64                     Const#46  string    "Head"
		  +9F3F:Size=8: 50 6F 73 69 74 69 6F 6E         Const#47  string    "Position"
		  +9F49:Size=9: 4D 61 67 6E 69 74 75 64 65      Const#48  string    "Magnitude"
		  +9F53:Size=4: 03 00 00 00                     Const#49  integer   3
		  +9F59:Size=2: 20 4D                           Const#50  string    " M"
		  +9F5D:Size=4: 20 20 20 0A                     Const#51  string    "   \n"
		  +9F63:Size=7: 44 65 73 74 72 6F 79            Const#52  string    "Destroy"
		Upvalues: 3
		  Upv#1 is parent function's Upv#1              name: _ENV
		  Upv#2 is parent function's R4                 name: v
		  Upv#3 is parent function's Upv#2              name: round
		Locals: 2
		  Local#1   R0   def:<23>   scope:<24..91>      name: bill
		  Local#2   R1   def:<50>   scope:<51..91>      name: name
		Instructions: 136
		  +9B69: 06 00 40 00   line#739  GETTABUP 0 0 -1         <1>   R0 = Upv#1@_ENV["DevilFruitESP"]                -- It's Const#1
		  +9B6D: 22 00 00 00   line#739  TEST 0 0                <2>   if R0 then GOTO <4>
		  +9B71: 1E C0 1C 80   line#739  JMP 0 116               <3>   GOTO <120>
		  +9B75: 06 40 40 00   line#740  GETTABUP 0 0 -2         <4>   R0 = Upv#1@_ENV["string"]                       -- It's Const#2
		  +9B79: 07 80 40 00   line#740  GETTABLE 0 0 -3         <5>   R0 = R0["find"]                                 -- It's Const#3
		  +9B7D: 46 C0 C0 00   line#740  GETTABUP 1 1 -4         <6>   R1 = Upv#2@v["Name"]                            -- It's Const#4
		  +9B81: 81 00 01 00   line#740  LOADK 2 -5              <7>   R2 = "Fruit"                                    -- It's Const#5
		  +9B85: 24 80 80 01   line#740  CALL 0 3 2              <8>   R0 = R0(R1, R2)
		  +9B89: 22 00 00 00   line#740  TEST 0 0                <9>   if R0 then GOTO <11>
		  +9B8D: 1E 00 1F 80   line#740  JMP 0 125              <10>   GOTO <136>
		  +9B91: 06 40 C1 00   line#741  GETTABUP 0 1 -6        <11>   R0 = Upv#2@v["Handle"]                          -- It's Const#6
		  +9B95: 0C 80 41 00   line#741  SELF 0 0 -7            <12>   R1 = R0;  R0 = R0["FindFirstChild"]             -- It's Const#7   -- prepare for R0:FindFirstChild()
		  +9B99: 81 C0 01 00   line#741  LOADK 2 -8             <13>   R2 = "NameEsp"                                  -- It's Const#8
		  +9B9D: C6 00 42 00   line#741  GETTABUP 3 0 -9        <14>   R3 = Upv#1@_ENV["Number"]                       -- It's Const#9
		  +9BA1: 9D C0 00 01   line#741  CONCAT 2 2 3           <15>   R2 = R2..R3
		  +9BA5: 24 80 80 01   line#741  CALL 0 3 2             <16>   R0 = R0(R1, R2)
		  +9BA9: 22 40 00 00   line#741  TEST 0 1               <17>   if not R0 then GOTO <19>
		  +9BAD: 1E 40 12 80   line#741  JMP 0 74               <18>   GOTO <93>
		  +9BB1: 06 40 42 00   line#742  GETTABUP 0 0 -10       <19>   R0 = Upv#1@_ENV["Instance"]                     -- It's Const#10
		  +9BB5: 07 80 42 00   line#742  GETTABLE 0 0 -11       <20>   R0 = R0["new"]                                  -- It's Const#11
		  +9BB9: 41 C0 02 00   line#742  LOADK 1 -12            <21>   R1 = "BillboardGui"                             -- It's Const#12
		  +9BBD: 86 40 C1 00   line#742  GETTABUP 2 1 -6        <22>   R2 = Upv#2@v["Handle"]                          -- It's Const#6
		  +9BC1: 24 80 80 01   line#742  CALL 0 3 2             <23>   R0@bill = R0(R1, R2)
		  +9BC5: 41 C0 01 00   line#743  LOADK 1 -8             <24>   R1 = "NameEsp"                                  -- It's Const#8
		  +9BC9: 86 00 42 00   line#743  GETTABUP 2 0 -9        <25>   R2 = Upv#1@_ENV["Number"]                       -- It's Const#9
		  +9BCD: 5D 80 80 00   line#743  CONCAT 1 1 2           <26>   R1 = R1..R2
		  +9BD1: 0A 40 80 81   line#743  SETTABLE 0 -4 1        <27>   R0@bill["Name"] = R1                            -- It's Const#4
		  +9BD5: 46 40 43 00   line#744  GETTABUP 1 0 -14       <28>   R1 = Upv#1@_ENV["Vector3"]                      -- It's Const#14
		  +9BD9: 47 80 C2 00   line#744  GETTABLE 1 1 -11       <29>   R1 = R1["new"]                                  -- It's Const#11
		  +9BDD: 81 80 03 00   line#744  LOADK 2 -15            <30>   R2 = 0                                          -- It's Const#15
		  +9BE1: C1 C0 03 00   line#744  LOADK 3 -16            <31>   R3 = 1                                          -- It's Const#16
		  +9BE5: 01 81 03 00   line#744  LOADK 4 -15            <32>   R4 = 0                                          -- It's Const#15
		  +9BE9: 64 80 00 02   line#744  CALL 1 4 2             <33>   R1 = R1(R2, R3, R4)
		  +9BED: 0A 40 00 86   line#744  SETTABLE 0 -13 1       <34>   R0@bill["ExtentsOffset"] = R1                   -- It's Const#13
		  +9BF1: 46 40 44 00   line#745  GETTABUP 1 0 -18       <35>   R1 = Upv#1@_ENV["UDim2"]                        -- It's Const#18
		  +9BF5: 47 80 C2 00   line#745  GETTABLE 1 1 -11       <36>   R1 = R1["new"]                                  -- It's Const#11
		  +9BF9: 81 C0 03 00   line#745  LOADK 2 -16            <37>   R2 = 1                                          -- It's Const#16
		  +9BFD: C1 80 04 00   line#745  LOADK 3 -19            <38>   R3 = 200                                        -- It's Const#19
		  +9C01: 01 C1 03 00   line#745  LOADK 4 -16            <39>   R4 = 1                                          -- It's Const#16
		  +9C05: 41 C1 04 00   line#745  LOADK 5 -20            <40>   R5 = 30                                         -- It's Const#20
		  +9C09: 64 80 80 02   line#745  CALL 1 5 2             <41>   R1 = R1(R2,..,R5)
		  +9C0D: 0A 40 00 88   line#745  SETTABLE 0 -17 1       <42>   R0@bill["Size"] = R1                            -- It's Const#17
		  +9C11: 46 40 C1 00   line#746  GETTABUP 1 1 -6        <43>   R1 = Upv#2@v["Handle"]                          -- It's Const#6
		  +9C15: 0A 40 00 8A   line#746  SETTABLE 0 -21 1       <44>   R0@bill["Adornee"] = R1                         -- It's Const#21
		  +9C19: 0A 80 C5 8A   line#747  SETTABLE 0 -22 -23     <45>   R0@bill["AlwaysOnTop"] = true                   -- It's Const#22, Const#23
		  +9C1D: 46 40 42 00   line#748  GETTABUP 1 0 -10       <46>   R1 = Upv#1@_ENV["Instance"]                     -- It's Const#10
		  +9C21: 47 80 C2 00   line#748  GETTABLE 1 1 -11       <47>   R1 = R1["new"]                                  -- It's Const#11
		  +9C25: 81 C0 05 00   line#748  LOADK 2 -24            <48>   R2 = "TextLabel"                                -- It's Const#24
		  +9C29: C0 00 00 00   line#748  MOVE 3 0               <49>   R3 = R0@bill
		  +9C2D: 64 80 80 01   line#748  CALL 1 3 2             <50>   R1@name = R1(R2, R3)
		  +9C31: 4A 40 46 8C   line#749  SETTABLE 1 -25 -26     <51>   R1@name["Font"] = "GothamBold"                  -- It's Const#25, Const#26
		  +9C35: 4A C0 46 8D   line#750  SETTABLE 1 -27 -28     <52>   R1@name["FontSize"] = "Size14"                  -- It's Const#27, Const#28
		  +9C39: 4A 80 45 8E   line#751  SETTABLE 1 -29 -23     <53>   R1@name["TextWrapped"] = true                   -- It's Const#29, Const#23
		  +9C3D: 86 40 44 00   line#752  GETTABUP 2 0 -18       <54>   R2 = Upv#1@_ENV["UDim2"]                        -- It's Const#18
		  +9C41: 87 80 42 01   line#752  GETTABLE 2 2 -11       <55>   R2 = R2["new"]                                  -- It's Const#11
		  +9C45: C1 C0 03 00   line#752  LOADK 3 -16            <56>   R3 = 1                                          -- It's Const#16
		  +9C49: 01 81 03 00   line#752  LOADK 4 -15            <57>   R4 = 0                                          -- It's Const#15
		  +9C4D: 41 C1 03 00   line#752  LOADK 5 -16            <58>   R5 = 1                                          -- It's Const#16
		  +9C51: 81 81 03 00   line#752  LOADK 6 -15            <59>   R6 = 0                                          -- It's Const#15
		  +9C55: A4 80 80 02   line#752  CALL 2 5 2             <60>   R2 = R2(R3,..,R6)
		  +9C59: 4A 80 00 88   line#752  SETTABLE 1 -17 2       <61>   R1@name["Size"] = R2                            -- It's Const#17
		  +9C5D: 4A 80 C7 8E   line#753  SETTABLE 1 -30 -31     <62>   R1@name["TextYAlignment"] = "Top"               -- It's Const#30, Const#31
		  +9C61: 4A C0 C3 8F   line#754  SETTABLE 1 -32 -16     <63>   R1@name["BackgroundTransparency"] = 1           -- It's Const#32, Const#16
		  +9C65: 4A 40 48 90   line#755  SETTABLE 1 -33 -34     <64>   R1@name["TextStrokeTransparency"] = 0.5         -- It's Const#33, Const#34
		  +9C69: 86 C0 48 00   line#756  GETTABUP 2 0 -36       <65>   R2 = Upv#1@_ENV["Color3"]                       -- It's Const#36
		  +9C6D: 87 00 49 01   line#756  GETTABLE 2 2 -37       <66>   R2 = R2["fromRGB"]                              -- It's Const#37
		  +9C71: C1 40 09 00   line#756  LOADK 3 -38            <67>   R3 = 255                                        -- It's Const#38
		  +9C75: 01 81 03 00   line#756  LOADK 4 -15            <68>   R4 = 0                                          -- It's Const#15
		  +9C79: 41 81 03 00   line#756  LOADK 5 -15            <69>   R5 = 0                                          -- It's Const#15
		  +9C7D: A4 80 00 02   line#756  CALL 2 4 2             <70>   R2 = R2(R3, R4, R5)
		  +9C81: 4A 80 00 91   line#756  SETTABLE 1 -35 2       <71>   R1@name["TextColor3"] = R2                      -- It's Const#35
		  +9C85: 86 C0 C0 00   line#757  GETTABUP 2 1 -4        <72>   R2 = Upv#2@v["Name"]                            -- It's Const#4
		  +9C89: C1 C0 09 00   line#757  LOADK 3 -40            <73>   R3 = " \n"                                      -- It's Const#40
		  +9C8D: 05 01 00 01   line#757  GETUPVAL 4 2           <74>   R4 = Upv#3@round
		  +9C91: 46 01 4A 00   line#757  GETTABUP 5 0 -41       <75>   R5 = Upv#1@_ENV["game"]                         -- It's Const#41
		  +9C95: 4C 41 CA 02   line#757  SELF 5 5 -42           <76>   R6 = R5;  R5 = R5["GetService"]                 -- It's Const#42   -- prepare for R5:GetService()
		  +9C99: C1 81 0A 00   line#757  LOADK 7 -43            <77>   R7 = "Players"                                  -- It's Const#43
		  +9C9D: 64 81 80 01   line#757  CALL 5 3 2             <78>   R5 = R5(R6, R7)
		  +9CA1: 47 C1 CA 02   line#757  GETTABLE 5 5 -44       <79>   R5 = R5["LocalPlayer"]                          -- It's Const#44
		  +9CA5: 47 01 CB 02   line#757  GETTABLE 5 5 -45       <80>   R5 = R5["Character"]                            -- It's Const#45
		  +9CA9: 47 41 CB 02   line#757  GETTABLE 5 5 -46       <81>   R5 = R5["Head"]                                 -- It's Const#46
		  +9CAD: 47 81 CB 02   line#757  GETTABLE 5 5 -47       <82>   R5 = R5["Position"]                             -- It's Const#47
		  +9CB1: 86 41 C1 00   line#757  GETTABUP 6 1 -6        <83>   R6 = Upv#2@v["Handle"]                          -- It's Const#6
		  +9CB5: 87 81 4B 03   line#757  GETTABLE 6 6 -47       <84>   R6 = R6["Position"]                             -- It's Const#47
		  +9CB9: 4E 81 81 02   line#757  SUB 5 5 6              <85>   R5 = R5 - R6
		  +9CBD: 47 C1 CB 02   line#757  GETTABLE 5 5 -48       <86>   R5 = R5["Magnitude"]                            -- It's Const#48
		  +9CC1: 52 01 CC 02   line#757  DIV 5 5 -49            <87>   R5 = R5 / 3                                     -- It's Const#49
		  +9CC5: 24 81 00 01   line#757  CALL 4 2 2             <88>   R4 = R4(R5)
		  +9CC9: 41 41 0C 00   line#757  LOADK 5 -50            <89>   R5 = " M"                                       -- It's Const#50
		  +9CCD: 9D 40 01 01   line#757  CONCAT 2 2 5           <90>   R2 = R2..R3..R4..R5
		  +9CD1: 4A 80 00 93   line#757  SETTABLE 1 -39 2       <91>   R1@name["Text"] = R2                            -- It's Const#39
		  +9CD5: 1E 80 0A 80   line#757  JMP 0 43               <92>   GOTO <136>
		  +9CD9: 06 40 C1 00   line#759  GETTABUP 0 1 -6        <93>   R0 = Upv#2@v["Handle"]                          -- It's Const#6
		  +9CDD: 41 C0 01 00   line#759  LOADK 1 -8             <94>   R1 = "NameEsp"                                  -- It's Const#8
		  +9CE1: 86 00 42 00   line#759  GETTABUP 2 0 -9        <95>   R2 = Upv#1@_ENV["Number"]                       -- It's Const#9
		  +9CE5: 5D 80 80 00   line#759  CONCAT 1 1 2           <96>   R1 = R1..R2
		  +9CE9: 07 40 00 00   line#759  GETTABLE 0 0 1         <97>   R0 = R0[R1]
		  +9CED: 07 C0 45 00   line#759  GETTABLE 0 0 -24       <98>   R0 = R0["TextLabel"]                            -- It's Const#24
		  +9CF1: 46 C0 C0 00   line#759  GETTABUP 1 1 -4        <99>   R1 = Upv#2@v["Name"]                            -- It's Const#4
		  +9CF5: 81 80 0C 00   line#759  LOADK 2 -51           <100>   R2 = "   \n"                                    -- It's Const#51
		  +9CF9: C5 00 00 01   line#759  GETUPVAL 3 2          <101>   R3 = Upv#3@round
		  +9CFD: 06 01 4A 00   line#759  GETTABUP 4 0 -41      <102>   R4 = Upv#1@_ENV["game"]                         -- It's Const#41
		  +9D01: 0C 41 4A 02   line#759  SELF 4 4 -42          <103>   R5 = R4;  R4 = R4["GetService"]                 -- It's Const#42   -- prepare for R4:GetService()
		  +9D05: 81 81 0A 00   line#759  LOADK 6 -43           <104>   R6 = "Players"                                  -- It's Const#43
		  +9D09: 24 81 80 01   line#759  CALL 4 3 2            <105>   R4 = R4(R5, R6)
		  +9D0D: 07 C1 4A 02   line#759  GETTABLE 4 4 -44      <106>   R4 = R4["LocalPlayer"]                          -- It's Const#44
		  +9D11: 07 01 4B 02   line#759  GETTABLE 4 4 -45      <107>   R4 = R4["Character"]                            -- It's Const#45
		  +9D15: 07 41 4B 02   line#759  GETTABLE 4 4 -46      <108>   R4 = R4["Head"]                                 -- It's Const#46
		  +9D19: 07 81 4B 02   line#759  GETTABLE 4 4 -47      <109>   R4 = R4["Position"]                             -- It's Const#47
		  +9D1D: 46 41 C1 00   line#759  GETTABUP 5 1 -6       <110>   R5 = Upv#2@v["Handle"]                          -- It's Const#6
		  +9D21: 47 81 CB 02   line#759  GETTABLE 5 5 -47      <111>   R5 = R5["Position"]                             -- It's Const#47
		  +9D25: 0E 41 01 02   line#759  SUB 4 4 5             <112>   R4 = R4 - R5
		  +9D29: 07 C1 4B 02   line#759  GETTABLE 4 4 -48      <113>   R4 = R4["Magnitude"]                            -- It's Const#48
		  +9D2D: 12 01 4C 02   line#759  DIV 4 4 -49           <114>   R4 = R4 / 3                                     -- It's Const#49
		  +9D31: E4 80 00 01   line#759  CALL 3 2 2            <115>   R3 = R3(R4)
		  +9D35: 01 41 0C 00   line#759  LOADK 4 -50           <116>   R4 = " M"                                       -- It's Const#50
		  +9D39: 5D 00 81 00   line#759  CONCAT 1 1 4          <117>   R1 = R1..R2..R3..R4
		  +9D3D: 0A 40 00 93   line#759  SETTABLE 0 -39 1      <118>   R0["Text"] = R1                                 -- It's Const#39
		  +9D41: 1E C0 03 80   line#761  JMP 0 16              <119>   GOTO <136>
		  +9D45: 06 40 C1 00   line#763  GETTABUP 0 1 -6       <120>   R0 = Upv#2@v["Handle"]                          -- It's Const#6
		  +9D49: 0C 80 41 00   line#763  SELF 0 0 -7           <121>   R1 = R0;  R0 = R0["FindFirstChild"]             -- It's Const#7   -- prepare for R0:FindFirstChild()
		  +9D4D: 81 C0 01 00   line#763  LOADK 2 -8            <122>   R2 = "NameEsp"                                  -- It's Const#8
		  +9D51: C6 00 42 00   line#763  GETTABUP 3 0 -9       <123>   R3 = Upv#1@_ENV["Number"]                       -- It's Const#9
		  +9D55: 9D C0 00 01   line#763  CONCAT 2 2 3          <124>   R2 = R2..R3
		  +9D59: 24 80 80 01   line#763  CALL 0 3 2            <125>   R0 = R0(R1, R2)
		  +9D5D: 22 00 00 00   line#763  TEST 0 0              <126>   if R0 then GOTO <128>
		  +9D61: 1E C0 01 80   line#763  JMP 0 8               <127>   GOTO <136>
		  +9D65: 06 40 C1 00   line#764  GETTABUP 0 1 -6       <128>   R0 = Upv#2@v["Handle"]                          -- It's Const#6
		  +9D69: 0C 80 41 00   line#764  SELF 0 0 -7           <129>   R1 = R0;  R0 = R0["FindFirstChild"]             -- It's Const#7   -- prepare for R0:FindFirstChild()
		  +9D6D: 81 C0 01 00   line#764  LOADK 2 -8            <130>   R2 = "NameEsp"                                  -- It's Const#8
		  +9D71: C6 00 42 00   line#764  GETTABUP 3 0 -9       <131>   R3 = Upv#1@_ENV["Number"]                       -- It's Const#9
		  +9D75: 9D C0 00 01   line#764  CONCAT 2 2 3          <132>   R2 = R2..R3
		  +9D79: 24 80 80 01   line#764  CALL 0 3 2            <133>   R0 = R0(R1, R2)
		  +9D7D: 0C C0 4C 00   line#764  SELF 0 0 -52          <134>   R1 = R0;  R0 = R0["Destroy"]                    -- It's Const#52   -- prepare for R0:Destroy()
		  +9D81: 24 40 00 01   line#764  CALL 0 2 1            <135>   R0(R1)
		  +9D85: 26 00 80 00   line#767  RETURN 0 1            <136>   RETURN
		Functions: 0

	************ Function#9   (full path: main.9)
	Source line#: 771..811
	Parameters: 0
	Is vararg: no
	VM registers needed: 7
	Constants: 6
	  +A2CE:Size=5: 70 61 69 72 73                  Const#1   string    "pairs"
	  +A2D5:Size=4: 67 61 6D 65                     Const#2   string    "game"
	  +A2DB:Size=A: 47 65 74 53 65 72 76 69 63 65   Const#3   string    "GetService"
	  +A2E7:Size=9: 57 6F 72 6B 73 70 61 63 65      Const#4   string    "Workspace"
	  +A2F2:Size=B: 47 65 74 43 68 69 6C 64 72...   Const#5   string    "GetChildren"
	  +A2FF:Size=5: 70 63 61 6C 6C                  Const#6   string    "pcall"
	Upvalues: 2
	  Upv#1 is parent function's Upv#1              name: _ENV
	  Upv#2 is parent function's R0                 name: round
	Locals: 5
	  Local#1   R0   def:<8>    scope:<9..15>       name: (for generator)
	  Local#2   R1   def:<8>    scope:<9..15>       name: (for state)
	  Local#3   R2   def:<8>    scope:<9..15>       name: (for control)
	  Local#4   R3   def:<9>    scope:<10..13>      name: i
	  Local#5   R4   def:<9>    scope:<10..13>      name: v
	Instructions: 16
	  +A288: 06 00 40 00   line#772  GETTABUP 0 0 -1         <1>   R0 = Upv#1@_ENV["pairs"]                        -- It's Const#1
	  +A28C: 46 40 40 00   line#772  GETTABUP 1 0 -2         <2>   R1 = Upv#1@_ENV["game"]                         -- It's Const#2
	  +A290: 4C 80 C0 00   line#772  SELF 1 1 -3             <3>   R2 = R1;  R1 = R1["GetService"]                 -- It's Const#3   -- prepare for R1:GetService()
	  +A294: C1 C0 00 00   line#772  LOADK 3 -4              <4>   R3 = "Workspace"                                -- It's Const#4
	  +A298: 64 80 80 01   line#772  CALL 1 3 2              <5>   R1 = R1(R2, R3)
	  +A29C: 4C 00 C1 00   line#772  SELF 1 1 -5             <6>   R2 = R1;  R1 = R1["GetChildren"]                -- It's Const#5   -- prepare for R1:GetChildren()
	  +A2A0: 64 00 00 01   line#772  CALL 1 2 0              <7>   R1,.. = R1(R2)
	  +A2A4: 24 00 01 00   line#772  CALL 0 0 4              <8>   R0, R1, R2 = R0(R1,..)
	  +A2A8: 1E C0 00 80   line#772  JMP 0 4                 <9>   GOTO <14>                                       -- for R3@i, R4@v in R0, R1, R2 do
	  +A2AC: 46 41 41 00   line#773  GETTABUP 5 0 -6        <10>   R5 = Upv#1@_ENV["pcall"]                        -- It's Const#6
	  +A2B0: AC 01 00 00   line#809  CLOSURE 6 0            <11>   R6 = Function#1
	  +A2B4: 64 41 00 01   line#773  CALL 5 2 1             <12>   R5(R6)
	  +A2B8: 1E C1 FF 7F   line#809  JMP 4 0                <13>   CLOSE R3@i,..
	  +A2BC: 29 80 00 00   line#772  TFORCALL 0 2           <14>   R3, R4 = R0(R1, R2)
	  +A2C0: AA 40 FE 7F   line#772  TFORLOOP 2 -6          <15>   if R3 ~= nil then { R2 = R3;  GOTO <10> }       -- end of loop
	  +A2C4: 26 00 80 00   line#811  RETURN 0 1             <16>   RETURN
	Functions: 1

		************ Function#1   (full path: main.9.1)
		Source line#: 773..809
		Parameters: 0
		Is vararg: no
		VM registers needed: 8
		Constants: 52
		  +A5D2:Size=4: 4E 61 6D 65                     Const#1   string    "Name"
		  +A5D8:Size=7: 46 6C 6F 77 65 72 32            Const#2   string    "Flower2"
		  +A5E1:Size=7: 46 6C 6F 77 65 72 31            Const#3   string    "Flower1"
		  +A5EA:Size=9: 46 6C 6F 77 65 72 45 53 50      Const#4   string    "FlowerESP"
		  +A5F5:Size=E: 46 69 6E 64 46 69 72 73 74...   Const#5   string    "FindFirstChild"
		  +A605:Size=7: 4E 61 6D 65 45 73 70            Const#6   string    "NameEsp"
		  +A60E:Size=6: 4E 75 6D 62 65 72               Const#7   string    "Number"
		  +A616:Size=8: 49 6E 73 74 61 6E 63 65         Const#8   string    "Instance"
		  +A620:Size=3: 6E 65 77                        Const#9   string    "new"
		  +A625:Size=C: 42 69 6C 6C 62 6F 61 72 64...   Const#10  string    "BillboardGui"
		  +A633:Size=D: 45 78 74 65 6E 74 73 4F 66...   Const#11  string    "ExtentsOffset"
		  +A642:Size=7: 56 65 63 74 6F 72 33            Const#12  string    "Vector3"
		  +A64A:Size=4: 00 00 00 00                     Const#13  integer   0
		  +A64F:Size=4: 01 00 00 00                     Const#14  integer   1
		  +A655:Size=4: 53 69 7A 65                     Const#15  string    "Size"
		  +A65B:Size=5: 55 44 69 6D 32                  Const#16  string    "UDim2"
		  +A661:Size=4: C8 00 00 00                     Const#17  integer   200
		  +A666:Size=4: 1E 00 00 00                     Const#18  integer   30
		  +A66C:Size=7: 41 64 6F 72 6E 65 65            Const#19  string    "Adornee"
		  +A675:Size=B: 41 6C 77 61 79 73 4F 6E 54...   Const#20  string    "AlwaysOnTop"
		  +A681:Size=1: 01                              Const#21  boolean   true
		  +A684:Size=9: 54 65 78 74 4C 61 62 65 6C      Const#22  string    "TextLabel"
		  +A68F:Size=4: 46 6F 6E 74                     Const#23  string    "Font"
		  +A695:Size=A: 47 6F 74 68 61 6D 42 6F 6C 64   Const#24  string    "GothamBold"
		  +A6A1:Size=8: 46 6F 6E 74 53 69 7A 65         Const#25  string    "FontSize"
		  +A6AB:Size=6: 53 69 7A 65 31 34               Const#26  string    "Size14"
		  +A6B3:Size=B: 54 65 78 74 57 72 61 70 70...   Const#27  string    "TextWrapped"
		  +A6C0:Size=E: 54 65 78 74 59 41 6C 69 67...   Const#28  string    "TextYAlignment"
		  +A6D0:Size=3: 54 6F 70                        Const#29  string    "Top"
		  +A6D5:Size=16: 42 61 63 6B 67 72 6F 75 6...   Const#30  string    "BackgroundTransparency"
		  +A6ED:Size=16: 54 65 78 74 53 74 72 6F 6...   Const#31  string    "TextStrokeTransparency"
		  +A704:Size=8: 00 00 00 00 00 00 E0 3F         Const#32  float     0.5
		  +A70E:Size=A: 54 65 78 74 43 6F 6C 6F 72 33   Const#33  string    "TextColor3"
		  +A71A:Size=6: 43 6F 6C 6F 72 33               Const#34  string    "Color3"
		  +A722:Size=7: 66 72 6F 6D 52 47 42            Const#35  string    "fromRGB"
		  +A72A:Size=4: FF 00 00 00                     Const#36  integer   255
		  +A730:Size=4: 54 65 78 74                     Const#37  string    "Text"
		  +A736:Size=B: 42 6C 75 65 20 46 6C 6F 77...   Const#38  string    "Blue Flower"
		  +A743:Size=2: 20 0A                           Const#39  string    " \n"
		  +A747:Size=4: 67 61 6D 65                     Const#40  string    "game"
		  +A74D:Size=A: 47 65 74 53 65 72 76 69 63 65   Const#41  string    "GetService"
		  +A759:Size=7: 50 6C 61 79 65 72 73            Const#42  string    "Players"
		  +A762:Size=B: 4C 6F 63 61 6C 50 6C 61 79...   Const#43  string    "LocalPlayer"
		  +A76F:Size=9: 43 68 61 72 61 63 74 65 72      Const#44  string    "Character"
		  +A77A:Size=4: 48 65 61 64                     Const#45  string    "Head"
		  +A780:Size=8: 50 6F 73 69 74 69 6F 6E         Const#46  string    "Position"
		  +A78A:Size=9: 4D 61 67 6E 69 74 75 64 65      Const#47  string    "Magnitude"
		  +A794:Size=4: 03 00 00 00                     Const#48  integer   3
		  +A79A:Size=2: 20 4D                           Const#49  string    " M"
		  +A79E:Size=A: 52 65 64 20 46 6C 6F 77 65 72   Const#50  string    "Red Flower"
		  +A7AA:Size=4: 20 20 20 0A                     Const#51  string    "   \n"
		  +A7B0:Size=7: 44 65 73 74 72 6F 79            Const#52  string    "Destroy"
		Upvalues: 3
		  Upv#1 is parent function's R4                 name: v
		  Upv#2 is parent function's Upv#1              name: _ENV
		  Upv#3 is parent function's Upv#2              name: round
		Locals: 2
		  Local#1   R0   def:<22>   scope:<23..128>     name: bill
		  Local#2   R1   def:<49>   scope:<50..128>     name: name
		Instructions: 171
		  +A320: 06 00 40 00   line#774  GETTABUP 0 0 -1         <1>   R0 = Upv#1@v["Name"]                            -- It's Const#1
		  +A324: 5F 40 40 00   line#774  EQ 1 0 -2               <2>   if R0 ~= "Flower2" then GOTO <4>                -- It's Const#2
		  +A328: 1E 80 00 80   line#774  JMP 0 3                 <3>   GOTO <7>
		  +A32C: 06 00 40 00   line#774  GETTABUP 0 0 -1         <4>   R0 = Upv#1@v["Name"]                            -- It's Const#1
		  +A330: 1F 80 40 00   line#774  EQ 0 0 -3               <5>   if R0 == "Flower1" then GOTO <7>                -- It's Const#3
		  +A334: 1E C0 28 80   line#774  JMP 0 164               <6>   GOTO <171>
		  +A338: 06 C0 C0 00   line#775  GETTABUP 0 1 -4         <7>   R0 = Upv#2@_ENV["FlowerESP"]                    -- It's Const#4
		  +A33C: 22 00 00 00   line#775  TEST 0 0                <8>   if R0 then GOTO <10>
		  +A340: 1E 00 24 80   line#775  JMP 0 145               <9>   GOTO <155>
		  +A344: 05 00 00 00   line#776  GETUPVAL 0 0           <10>   R0 = Upv#1@v
		  +A348: 0C 00 41 00   line#776  SELF 0 0 -5            <11>   R1 = R0;  R0 = R0["FindFirstChild"]             -- It's Const#5   -- prepare for R0:FindFirstChild()
		  +A34C: 81 40 01 00   line#776  LOADK 2 -6             <12>   R2 = "NameEsp"                                  -- It's Const#6
		  +A350: C6 80 C1 00   line#776  GETTABUP 3 1 -7        <13>   R3 = Upv#2@_ENV["Number"]                       -- It's Const#7
		  +A354: 9D C0 00 01   line#776  CONCAT 2 2 3           <14>   R2 = R2..R3
		  +A358: 24 80 80 01   line#776  CALL 0 3 2             <15>   R0 = R0(R1, R2)
		  +A35C: 22 40 00 00   line#776  TEST 0 1               <16>   if not R0 then GOTO <18>
		  +A360: 1E C0 1B 80   line#776  JMP 0 112              <17>   GOTO <130>
		  +A364: 06 C0 C1 00   line#777  GETTABUP 0 1 -8        <18>   R0 = Upv#2@_ENV["Instance"]                     -- It's Const#8
		  +A368: 07 00 42 00   line#777  GETTABLE 0 0 -9        <19>   R0 = R0["new"]                                  -- It's Const#9
		  +A36C: 41 40 02 00   line#777  LOADK 1 -10            <20>   R1 = "BillboardGui"                             -- It's Const#10
		  +A370: 85 00 00 00   line#777  GETUPVAL 2 0           <21>   R2 = Upv#1@v
		  +A374: 24 80 80 01   line#777  CALL 0 3 2             <22>   R0@bill = R0(R1, R2)
		  +A378: 41 40 01 00   line#778  LOADK 1 -6             <23>   R1 = "NameEsp"                                  -- It's Const#6
		  +A37C: 86 80 C1 00   line#778  GETTABUP 2 1 -7        <24>   R2 = Upv#2@_ENV["Number"]                       -- It's Const#7
		  +A380: 5D 80 80 00   line#778  CONCAT 1 1 2           <25>   R1 = R1..R2
		  +A384: 0A 40 00 80   line#778  SETTABLE 0 -1 1        <26>   R0@bill["Name"] = R1                            -- It's Const#1
		  +A388: 46 C0 C2 00   line#779  GETTABUP 1 1 -12       <27>   R1 = Upv#2@_ENV["Vector3"]                      -- It's Const#12
		  +A38C: 47 00 C2 00   line#779  GETTABLE 1 1 -9        <28>   R1 = R1["new"]                                  -- It's Const#9
		  +A390: 81 00 03 00   line#779  LOADK 2 -13            <29>   R2 = 0                                          -- It's Const#13
		  +A394: C1 40 03 00   line#779  LOADK 3 -14            <30>   R3 = 1                                          -- It's Const#14
		  +A398: 01 01 03 00   line#779  LOADK 4 -13            <31>   R4 = 0                                          -- It's Const#13
		  +A39C: 64 80 00 02   line#779  CALL 1 4 2             <32>   R1 = R1(R2, R3, R4)
		  +A3A0: 0A 40 00 85   line#779  SETTABLE 0 -11 1       <33>   R0@bill["ExtentsOffset"] = R1                   -- It's Const#11
		  +A3A4: 46 C0 C3 00   line#780  GETTABUP 1 1 -16       <34>   R1 = Upv#2@_ENV["UDim2"]                        -- It's Const#16
		  +A3A8: 47 00 C2 00   line#780  GETTABLE 1 1 -9        <35>   R1 = R1["new"]                                  -- It's Const#9
		  +A3AC: 81 40 03 00   line#780  LOADK 2 -14            <36>   R2 = 1                                          -- It's Const#14
		  +A3B0: C1 00 04 00   line#780  LOADK 3 -17            <37>   R3 = 200                                        -- It's Const#17
		  +A3B4: 01 41 03 00   line#780  LOADK 4 -14            <38>   R4 = 1                                          -- It's Const#14
		  +A3B8: 41 41 04 00   line#780  LOADK 5 -18            <39>   R5 = 30                                         -- It's Const#18
		  +A3BC: 64 80 80 02   line#780  CALL 1 5 2             <40>   R1 = R1(R2,..,R5)
		  +A3C0: 0A 40 00 87   line#780  SETTABLE 0 -15 1       <41>   R0@bill["Size"] = R1                            -- It's Const#15
		  +A3C4: 45 00 00 00   line#781  GETUPVAL 1 0           <42>   R1 = Upv#1@v
		  +A3C8: 0A 40 00 89   line#781  SETTABLE 0 -19 1       <43>   R0@bill["Adornee"] = R1                         -- It's Const#19
		  +A3CC: 0A 00 C5 89   line#782  SETTABLE 0 -20 -21     <44>   R0@bill["AlwaysOnTop"] = true                   -- It's Const#20, Const#21
		  +A3D0: 46 C0 C1 00   line#783  GETTABUP 1 1 -8        <45>   R1 = Upv#2@_ENV["Instance"]                     -- It's Const#8
		  +A3D4: 47 00 C2 00   line#783  GETTABLE 1 1 -9        <46>   R1 = R1["new"]                                  -- It's Const#9
		  +A3D8: 81 40 05 00   line#783  LOADK 2 -22            <47>   R2 = "TextLabel"                                -- It's Const#22
		  +A3DC: C0 00 00 00   line#783  MOVE 3 0               <48>   R3 = R0@bill
		  +A3E0: 64 80 80 01   line#783  CALL 1 3 2             <49>   R1@name = R1(R2, R3)
		  +A3E4: 4A C0 45 8B   line#784  SETTABLE 1 -23 -24     <50>   R1@name["Font"] = "GothamBold"                  -- It's Const#23, Const#24
		  +A3E8: 4A 40 46 8C   line#785  SETTABLE 1 -25 -26     <51>   R1@name["FontSize"] = "Size14"                  -- It's Const#25, Const#26
		  +A3EC: 4A 00 45 8D   line#786  SETTABLE 1 -27 -21     <52>   R1@name["TextWrapped"] = true                   -- It's Const#27, Const#21
		  +A3F0: 86 C0 C3 00   line#787  GETTABUP 2 1 -16       <53>   R2 = Upv#2@_ENV["UDim2"]                        -- It's Const#16
		  +A3F4: 87 00 42 01   line#787  GETTABLE 2 2 -9        <54>   R2 = R2["new"]                                  -- It's Const#9
		  +A3F8: C1 40 03 00   line#787  LOADK 3 -14            <55>   R3 = 1                                          -- It's Const#14
		  +A3FC: 01 01 03 00   line#787  LOADK 4 -13            <56>   R4 = 0                                          -- It's Const#13
		  +A400: 41 41 03 00   line#787  LOADK 5 -14            <57>   R5 = 1                                          -- It's Const#14
		  +A404: 81 01 03 00   line#787  LOADK 6 -13            <58>   R6 = 0                                          -- It's Const#13
		  +A408: A4 80 80 02   line#787  CALL 2 5 2             <59>   R2 = R2(R3,..,R6)
		  +A40C: 4A 80 00 87   line#787  SETTABLE 1 -15 2       <60>   R1@name["Size"] = R2                            -- It's Const#15
		  +A410: 4A 00 C7 8D   line#788  SETTABLE 1 -28 -29     <61>   R1@name["TextYAlignment"] = "Top"               -- It's Const#28, Const#29
		  +A414: 4A 40 C3 8E   line#789  SETTABLE 1 -30 -14     <62>   R1@name["BackgroundTransparency"] = 1           -- It's Const#30, Const#14
		  +A418: 4A C0 47 8F   line#790  SETTABLE 1 -31 -32     <63>   R1@name["TextStrokeTransparency"] = 0.5         -- It's Const#31, Const#32
		  +A41C: 86 40 C8 00   line#791  GETTABUP 2 1 -34       <64>   R2 = Upv#2@_ENV["Color3"]                       -- It's Const#34
		  +A420: 87 80 48 01   line#791  GETTABLE 2 2 -35       <65>   R2 = R2["fromRGB"]                              -- It's Const#35
		  +A424: C1 C0 08 00   line#791  LOADK 3 -36            <66>   R3 = 255                                        -- It's Const#36
		  +A428: 01 01 03 00   line#791  LOADK 4 -13            <67>   R4 = 0                                          -- It's Const#13
		  +A42C: 41 01 03 00   line#791  LOADK 5 -13            <68>   R5 = 0                                          -- It's Const#13
		  +A430: A4 80 00 02   line#791  CALL 2 4 2             <69>   R2 = R2(R3, R4, R5)
		  +A434: 4A 80 00 90   line#791  SETTABLE 1 -33 2       <70>   R1@name["TextColor3"] = R2                      -- It's Const#33
		  +A438: 86 00 40 00   line#792  GETTABUP 2 0 -1        <71>   R2 = Upv#1@v["Name"]                            -- It's Const#1
		  +A43C: 1F 80 40 01   line#792  EQ 0 2 -3              <72>   if R2 == "Flower1" then GOTO <74>               -- It's Const#3
		  +A440: 1E 40 06 80   line#792  JMP 0 26               <73>   GOTO <100>
		  +A444: 81 40 09 00   line#793  LOADK 2 -38            <74>   R2 = "Blue Flower"                              -- It's Const#38
		  +A448: C1 80 09 00   line#793  LOADK 3 -39            <75>   R3 = " \n"                                      -- It's Const#39
		  +A44C: 05 01 00 01   line#793  GETUPVAL 4 2           <76>   R4 = Upv#3@round
		  +A450: 46 C1 C9 00   line#793  GETTABUP 5 1 -40       <77>   R5 = Upv#2@_ENV["game"]                         -- It's Const#40
		  +A454: 4C 01 CA 02   line#793  SELF 5 5 -41           <78>   R6 = R5;  R5 = R5["GetService"]                 -- It's Const#41   -- prepare for R5:GetService()
		  +A458: C1 41 0A 00   line#793  LOADK 7 -42            <79>   R7 = "Players"                                  -- It's Const#42
		  +A45C: 64 81 80 01   line#793  CALL 5 3 2             <80>   R5 = R5(R6, R7)
		  +A460: 47 81 CA 02   line#793  GETTABLE 5 5 -43       <81>   R5 = R5["LocalPlayer"]                          -- It's Const#43
		  +A464: 47 C1 CA 02   line#793  GETTABLE 5 5 -44       <82>   R5 = R5["Character"]                            -- It's Const#44
		  +A468: 47 01 CB 02   line#793  GETTABLE 5 5 -45       <83>   R5 = R5["Head"]                                 -- It's Const#45
		  +A46C: 47 41 CB 02   line#793  GETTABLE 5 5 -46       <84>   R5 = R5["Position"]                             -- It's Const#46
		  +A470: 86 41 4B 00   line#793  GETTABUP 6 0 -46       <85>   R6 = Upv#1@v["Position"]                        -- It's Const#46
		  +A474: 4E 81 81 02   line#793  SUB 5 5 6              <86>   R5 = R5 - R6
		  +A478: 47 81 CB 02   line#793  GETTABLE 5 5 -47       <87>   R5 = R5["Magnitude"]                            -- It's Const#47
		  +A47C: 52 C1 CB 02   line#793  DIV 5 5 -48            <88>   R5 = R5 / 3                                     -- It's Const#48
		  +A480: 24 81 00 01   line#793  CALL 4 2 2             <89>   R4 = R4(R5)
		  +A484: 41 01 0C 00   line#793  LOADK 5 -49            <90>   R5 = " M"                                       -- It's Const#49
		  +A488: 9D 40 01 01   line#793  CONCAT 2 2 5           <91>   R2 = R2..R3..R4..R5
		  +A48C: 4A 80 00 92   line#793  SETTABLE 1 -37 2       <92>   R1@name["Text"] = R2                            -- It's Const#37
		  +A490: 86 40 C8 00   line#794  GETTABUP 2 1 -34       <93>   R2 = Upv#2@_ENV["Color3"]                       -- It's Const#34
		  +A494: 87 80 48 01   line#794  GETTABLE 2 2 -35       <94>   R2 = R2["fromRGB"]                              -- It's Const#35
		  +A498: C1 C0 08 00   line#794  LOADK 3 -36            <95>   R3 = 255                                        -- It's Const#36
		  +A49C: 01 01 03 00   line#794  LOADK 4 -13            <96>   R4 = 0                                          -- It's Const#13
		  +A4A0: 41 01 03 00   line#794  LOADK 5 -13            <97>   R5 = 0                                          -- It's Const#13
		  +A4A4: A4 80 00 02   line#794  CALL 2 4 2             <98>   R2 = R2(R3, R4, R5)
		  +A4A8: 4A 80 00 90   line#794  SETTABLE 1 -33 2       <99>   R1@name["TextColor3"] = R2                      -- It's Const#33
		  +A4AC: 86 00 40 00   line#796  GETTABUP 2 0 -1       <100>   R2 = Upv#1@v["Name"]                            -- It's Const#1
		  +A4B0: 1F 40 40 01   line#796  EQ 0 2 -2             <101>   if R2 == "Flower2" then GOTO <103>              -- It's Const#2
		  +A4B4: 1E C0 10 80   line#796  JMP 0 68              <102>   GOTO <171>
		  +A4B8: 81 40 0C 00   line#797  LOADK 2 -50           <103>   R2 = "Red Flower"                               -- It's Const#50
		  +A4BC: C1 80 09 00   line#797  LOADK 3 -39           <104>   R3 = " \n"                                      -- It's Const#39
		  +A4C0: 05 01 00 01   line#797  GETUPVAL 4 2          <105>   R4 = Upv#3@round
		  +A4C4: 46 C1 C9 00   line#797  GETTABUP 5 1 -40      <106>   R5 = Upv#2@_ENV["game"]                         -- It's Const#40
		  +A4C8: 4C 01 CA 02   line#797  SELF 5 5 -41          <107>   R6 = R5;  R5 = R5["GetService"]                 -- It's Const#41   -- prepare for R5:GetService()
		  +A4CC: C1 41 0A 00   line#797  LOADK 7 -42           <108>   R7 = "Players"                                  -- It's Const#42
		  +A4D0: 64 81 80 01   line#797  CALL 5 3 2            <109>   R5 = R5(R6, R7)
		  +A4D4: 47 81 CA 02   line#797  GETTABLE 5 5 -43      <110>   R5 = R5["LocalPlayer"]                          -- It's Const#43
		  +A4D8: 47 C1 CA 02   line#797  GETTABLE 5 5 -44      <111>   R5 = R5["Character"]                            -- It's Const#44
		  +A4DC: 47 01 CB 02   line#797  GETTABLE 5 5 -45      <112>   R5 = R5["Head"]                                 -- It's Const#45
		  +A4E0: 47 41 CB 02   line#797  GETTABLE 5 5 -46      <113>   R5 = R5["Position"]                             -- It's Const#46
		  +A4E4: 86 41 4B 00   line#797  GETTABUP 6 0 -46      <114>   R6 = Upv#1@v["Position"]                        -- It's Const#46
		  +A4E8: 4E 81 81 02   line#797  SUB 5 5 6             <115>   R5 = R5 - R6
		  +A4EC: 47 81 CB 02   line#797  GETTABLE 5 5 -47      <116>   R5 = R5["Magnitude"]                            -- It's Const#47
		  +A4F0: 52 C1 CB 02   line#797  DIV 5 5 -48           <117>   R5 = R5 / 3                                     -- It's Const#48
		  +A4F4: 24 81 00 01   line#797  CALL 4 2 2            <118>   R4 = R4(R5)
		  +A4F8: 41 01 0C 00   line#797  LOADK 5 -49           <119>   R5 = " M"                                       -- It's Const#49
		  +A4FC: 9D 40 01 01   line#797  CONCAT 2 2 5          <120>   R2 = R2..R3..R4..R5
		  +A500: 4A 80 00 92   line#797  SETTABLE 1 -37 2      <121>   R1@name["Text"] = R2                            -- It's Const#37
		  +A504: 86 40 C8 00   line#798  GETTABUP 2 1 -34      <122>   R2 = Upv#2@_ENV["Color3"]                       -- It's Const#34
		  +A508: 87 80 48 01   line#798  GETTABLE 2 2 -35      <123>   R2 = R2["fromRGB"]                              -- It's Const#35
		  +A50C: C1 C0 08 00   line#798  LOADK 3 -36           <124>   R3 = 255                                        -- It's Const#36
		  +A510: 01 01 03 00   line#798  LOADK 4 -13           <125>   R4 = 0                                          -- It's Const#13
		  +A514: 41 01 03 00   line#798  LOADK 5 -13           <126>   R5 = 0                                          -- It's Const#13
		  +A518: A4 80 00 02   line#798  CALL 2 4 2            <127>   R2 = R2(R3, R4, R5)
		  +A51C: 4A 80 00 90   line#798  SETTABLE 1 -33 2      <128>   R1@name["TextColor3"] = R2                      -- It's Const#33
		  +A520: 1E 00 0A 80   line#799  JMP 0 41              <129>   GOTO <171>
		  +A524: 01 40 01 00   line#801  LOADK 0 -6            <130>   R0 = "NameEsp"                                  -- It's Const#6
		  +A528: 46 80 C1 00   line#801  GETTABUP 1 1 -7       <131>   R1 = Upv#2@_ENV["Number"]                       -- It's Const#7
		  +A52C: 1D 40 00 00   line#801  CONCAT 0 0 1          <132>   R0 = R0..R1
		  +A530: 06 00 00 00   line#801  GETTABUP 0 0 0        <133>   R0 = Upv#1@v[R0]
		  +A534: 07 40 45 00   line#801  GETTABLE 0 0 -22      <134>   R0 = R0["TextLabel"]                            -- It's Const#22
		  +A538: 46 00 40 00   line#801  GETTABUP 1 0 -1       <135>   R1 = Upv#1@v["Name"]                            -- It's Const#1
		  +A53C: 81 80 0C 00   line#801  LOADK 2 -51           <136>   R2 = "   \n"                                    -- It's Const#51
		  +A540: C5 00 00 01   line#801  GETUPVAL 3 2          <137>   R3 = Upv#3@round
		  +A544: 06 C1 C9 00   line#801  GETTABUP 4 1 -40      <138>   R4 = Upv#2@_ENV["game"]                         -- It's Const#40
		  +A548: 0C 01 4A 02   line#801  SELF 4 4 -41          <139>   R5 = R4;  R4 = R4["GetService"]                 -- It's Const#41   -- prepare for R4:GetService()
		  +A54C: 81 41 0A 00   line#801  LOADK 6 -42           <140>   R6 = "Players"                                  -- It's Const#42
		  +A550: 24 81 80 01   line#801  CALL 4 3 2            <141>   R4 = R4(R5, R6)
		  +A554: 07 81 4A 02   line#801  GETTABLE 4 4 -43      <142>   R4 = R4["LocalPlayer"]                          -- It's Const#43
		  +A558: 07 C1 4A 02   line#801  GETTABLE 4 4 -44      <143>   R4 = R4["Character"]                            -- It's Const#44
		  +A55C: 07 01 4B 02   line#801  GETTABLE 4 4 -45      <144>   R4 = R4["Head"]                                 -- It's Const#45
		  +A560: 07 41 4B 02   line#801  GETTABLE 4 4 -46      <145>   R4 = R4["Position"]                             -- It's Const#46
		  +A564: 46 41 4B 00   line#801  GETTABUP 5 0 -46      <146>   R5 = Upv#1@v["Position"]                        -- It's Const#46
		  +A568: 0E 41 01 02   line#801  SUB 4 4 5             <147>   R4 = R4 - R5
		  +A56C: 07 81 4B 02   line#801  GETTABLE 4 4 -47      <148>   R4 = R4["Magnitude"]                            -- It's Const#47
		  +A570: 12 C1 4B 02   line#801  DIV 4 4 -48           <149>   R4 = R4 / 3                                     -- It's Const#48
		  +A574: E4 80 00 01   line#801  CALL 3 2 2            <150>   R3 = R3(R4)
		  +A578: 01 01 0C 00   line#801  LOADK 4 -49           <151>   R4 = " M"                                       -- It's Const#49
		  +A57C: 5D 00 81 00   line#801  CONCAT 1 1 4          <152>   R1 = R1..R2..R3..R4
		  +A580: 0A 40 00 92   line#801  SETTABLE 0 -37 1      <153>   R0["Text"] = R1                                 -- It's Const#37
		  +A584: 1E C0 03 80   line#802  JMP 0 16              <154>   GOTO <171>
		  +A588: 05 00 00 00   line#804  GETUPVAL 0 0          <155>   R0 = Upv#1@v
		  +A58C: 0C 00 41 00   line#804  SELF 0 0 -5           <156>   R1 = R0;  R0 = R0["FindFirstChild"]             -- It's Const#5   -- prepare for R0:FindFirstChild()
		  +A590: 81 40 01 00   line#804  LOADK 2 -6            <157>   R2 = "NameEsp"                                  -- It's Const#6
		  +A594: C6 80 C1 00   line#804  GETTABUP 3 1 -7       <158>   R3 = Upv#2@_ENV["Number"]                       -- It's Const#7
		  +A598: 9D C0 00 01   line#804  CONCAT 2 2 3          <159>   R2 = R2..R3
		  +A59C: 24 80 80 01   line#804  CALL 0 3 2            <160>   R0 = R0(R1, R2)
		  +A5A0: 22 00 00 00   line#804  TEST 0 0              <161>   if R0 then GOTO <163>
		  +A5A4: 1E C0 01 80   line#804  JMP 0 8               <162>   GOTO <171>
		  +A5A8: 05 00 00 00   line#805  GETUPVAL 0 0          <163>   R0 = Upv#1@v
		  +A5AC: 0C 00 41 00   line#805  SELF 0 0 -5           <164>   R1 = R0;  R0 = R0["FindFirstChild"]             -- It's Const#5   -- prepare for R0:FindFirstChild()
		  +A5B0: 81 40 01 00   line#805  LOADK 2 -6            <165>   R2 = "NameEsp"                                  -- It's Const#6
		  +A5B4: C6 80 C1 00   line#805  GETTABUP 3 1 -7       <166>   R3 = Upv#2@_ENV["Number"]                       -- It's Const#7
		  +A5B8: 9D C0 00 01   line#805  CONCAT 2 2 3          <167>   R2 = R2..R3
		  +A5BC: 24 80 80 01   line#805  CALL 0 3 2            <168>   R0 = R0(R1, R2)
		  +A5C0: 0C C0 4C 00   line#805  SELF 0 0 -52          <169>   R1 = R0;  R0 = R0["Destroy"]                    -- It's Const#52   -- prepare for R0:Destroy()
		  +A5C4: 24 40 00 01   line#805  CALL 0 2 1            <170>   R0(R1)
		  +A5C8: 26 00 80 00   line#809  RETURN 0 1            <171>   RETURN
		Functions: 0

	************ Function#10   (full path: main.10)
	Source line#: 813..848
	Parameters: 0
	Is vararg: no
	VM registers needed: 8
	Constants: 56
	  +ADA7:Size=A: 49 6E 66 41 62 69 6C 69 74 79   Const#1   string    "InfAbility"
	  +ADB3:Size=4: 67 61 6D 65                     Const#2   string    "game"
	  +ADB9:Size=A: 47 65 74 53 65 72 76 69 63 65   Const#3   string    "GetService"
	  +ADC5:Size=7: 50 6C 61 79 65 72 73            Const#4   string    "Players"
	  +ADCE:Size=B: 4C 6F 63 61 6C 50 6C 61 79...   Const#5   string    "LocalPlayer"
	  +ADDB:Size=9: 43 68 61 72 61 63 74 65 72      Const#6   string    "Character"
	  +ADE6:Size=10: 48 75 6D 61 6E 6F 69 64 5...   Const#7   string    "HumanoidRootPart"
	  +ADF8:Size=E: 46 69 6E 64 46 69 72 73 74...   Const#8   string    "FindFirstChild"
	  +AE08:Size=7: 41 67 69 6C 69 74 79            Const#9   string    "Agility"
	  +AE11:Size=8: 49 6E 73 74 61 6E 63 65         Const#10  string    "Instance"
	  +AE1B:Size=3: 6E 65 77                        Const#11  string    "new"
	  +AE20:Size=F: 50 61 72 74 69 63 6C 65 45...   Const#12  string    "ParticleEmitter"
	  +AE31:Size=C: 41 63 63 65 6C 65 72 61 74...   Const#13  string    "Acceleration"
	  +AE3F:Size=7: 56 65 63 74 6F 72 33            Const#14  string    "Vector3"
	  +AE47:Size=4: 00 00 00 00                     Const#15  integer   0
	  +AE4D:Size=A: 41 72 63 68 69 76 61 62 6C 65   Const#16  string    "Archivable"
	  +AE58:Size=1: 01                              Const#17  boolean   true
	  +AE5B:Size=4: 44 72 61 67                     Const#18  string    "Drag"
	  +AE60:Size=4: 14 00 00 00                     Const#19  integer   20
	  +AE66:Size=11: 45 6D 69 73 73 69 6F 6E 4...   Const#20  string    "EmissionDirection"
	  +AE79:Size=4: 45 6E 75 6D                     Const#21  string    "Enum"
	  +AE7F:Size=8: 4E 6F 72 6D 61 6C 49 64         Const#22  string    "NormalId"
	  +AE89:Size=3: 54 6F 70                        Const#23  string    "Top"
	  +AE8E:Size=7: 45 6E 61 62 6C 65 64            Const#24  string    "Enabled"
	  +AE97:Size=8: 4C 69 66 65 74 69 6D 65         Const#25  string    "Lifetime"
	  +AEA1:Size=B: 4E 75 6D 62 65 72 52 61 6E...   Const#26  string    "NumberRange"
	  +AEAE:Size=E: 4C 69 67 68 74 49 6E 66 6C...   Const#27  string    "LightInfluence"
	  +AEBE:Size=C: 4C 6F 63 6B 65 64 54 6F 50...   Const#28  string    "LockedToPart"
	  +AECC:Size=4: 4E 61 6D 65                     Const#29  string    "Name"
	  +AED2:Size=4: 52 61 74 65                     Const#30  string    "Rate"
	  +AED7:Size=4: F4 01 00 00                     Const#31  integer   500
	  +AEDD:Size=16: 4E 75 6D 62 65 72 53 65 7...   Const#32  string    "NumberSequenceKeypoint"
	  +AEF4:Size=4: 01 00 00 00                     Const#33  integer   1
	  +AEF9:Size=4: 04 00 00 00                     Const#34  integer   4
	  +AEFF:Size=4: 53 69 7A 65                     Const#35  string    "Size"
	  +AF05:Size=E: 4E 75 6D 62 65 72 53 65 71...   Const#36  string    "NumberSequence"
	  +AF15:Size=8: 52 6F 74 53 70 65 65 64         Const#37  string    "RotSpeed"
	  +AF1E:Size=4: 0F 27 00 00                     Const#38  integer   9999
	  +AF23:Size=4: 9F 86 01 00                     Const#39  integer   99999
	  +AF29:Size=8: 52 6F 74 61 74 69 6F 6E         Const#40  string    "Rotation"
	  +AF33:Size=5: 53 70 65 65 64                  Const#41  string    "Speed"
	  +AF39:Size=4: 1E 00 00 00                     Const#42  integer   30
	  +AF3F:Size=B: 53 70 72 65 61 64 41 6E 67...   Const#43  string    "SpreadAngle"
	  +AF4C:Size=7: 56 65 63 74 6F 72 32            Const#44  string    "Vector2"
	  +AF55:Size=7: 54 65 78 74 75 72 65            Const#45  string    "Texture"
	  +AF5E:Size=0:                                 Const#46  string    ""
	  +AF60:Size=13: 56 65 6C 6F 63 69 74 79 4...   Const#47  string    "VelocityInheritance"
	  +AF75:Size=7: 5A 4F 66 66 73 65 74            Const#48  string    "ZOffset"
	  +AF7D:Size=4: 02 00 00 00                     Const#49  integer   2
	  +AF83:Size=C: 54 72 61 6E 73 70 61 72 65...   Const#50  string    "Transparency"
	  +AF91:Size=5: 43 6F 6C 6F 72                  Const#51  string    "Color"
	  +AF98:Size=D: 43 6F 6C 6F 72 53 65 71 75...   Const#52  string    "ColorSequence"
	  +AFA7:Size=6: 43 6F 6C 6F 72 33               Const#53  string    "Color3"
	  +AFAF:Size=7: 66 72 6F 6D 52 47 42            Const#54  string    "fromRGB"
	  +AFB8:Size=6: 50 61 72 65 6E 74               Const#55  string    "Parent"
	  +AFC0:Size=7: 44 65 73 74 72 6F 79            Const#56  string    "Destroy"
	Upvalues: 1
	  Upv#1 is parent function's Upv#1              name: _ENV
	Locals: 2
	  Local#1   R0   def:<19>   scope:<20..118>     name: inf
	  Local#2   R1   def:<44>   scope:<56..118>     name: numberKeypoints2
	Instructions: 144
	  +AB61: 06 00 40 00   line#814  GETTABUP 0 0 -1         <1>   R0 = Upv#1@_ENV["InfAbility"]                   -- It's Const#1
	  +AB65: 22 00 00 00   line#814  TEST 0 0                <2>   if R0 then GOTO <4>
	  +AB69: 1E C0 1C 80   line#814  JMP 0 116               <3>   GOTO <120>
	  +AB6D: 06 40 40 00   line#815  GETTABUP 0 0 -2         <4>   R0 = Upv#1@_ENV["game"]                         -- It's Const#2
	  +AB71: 0C 80 40 00   line#815  SELF 0 0 -3             <5>   R1 = R0;  R0 = R0["GetService"]                 -- It's Const#3   -- prepare for R0:GetService()
	  +AB75: 81 C0 00 00   line#815  LOADK 2 -4              <6>   R2 = "Players"                                  -- It's Const#4
	  +AB79: 24 80 80 01   line#815  CALL 0 3 2              <7>   R0 = R0(R1, R2)
	  +AB7D: 07 00 41 00   line#815  GETTABLE 0 0 -5         <8>   R0 = R0["LocalPlayer"]                          -- It's Const#5
	  +AB81: 07 40 41 00   line#815  GETTABLE 0 0 -6         <9>   R0 = R0["Character"]                            -- It's Const#6
	  +AB85: 07 80 41 00   line#815  GETTABLE 0 0 -7        <10>   R0 = R0["HumanoidRootPart"]                     -- It's Const#7
	  +AB89: 0C C0 41 00   line#815  SELF 0 0 -8            <11>   R1 = R0;  R0 = R0["FindFirstChild"]             -- It's Const#8   -- prepare for R0:FindFirstChild()
	  +AB8D: 81 00 02 00   line#815  LOADK 2 -9             <12>   R2 = "Agility"                                  -- It's Const#9
	  +AB91: 24 80 80 01   line#815  CALL 0 3 2             <13>   R0 = R0(R1, R2)
	  +AB95: 22 40 00 00   line#815  TEST 0 1               <14>   if not R0 then GOTO <16>
	  +AB99: 1E C0 1F 80   line#815  JMP 0 128              <15>   GOTO <144>
	  +AB9D: 06 40 42 00   line#816  GETTABUP 0 0 -10       <16>   R0 = Upv#1@_ENV["Instance"]                     -- It's Const#10
	  +ABA1: 07 80 42 00   line#816  GETTABLE 0 0 -11       <17>   R0 = R0["new"]                                  -- It's Const#11
	  +ABA5: 41 C0 02 00   line#816  LOADK 1 -12            <18>   R1 = "ParticleEmitter"                          -- It's Const#12
	  +ABA9: 24 80 00 01   line#816  CALL 0 2 2             <19>   R0@inf = R0(R1)
	  +ABAD: 46 40 43 00   line#817  GETTABUP 1 0 -14       <20>   R1 = Upv#1@_ENV["Vector3"]                      -- It's Const#14
	  +ABB1: 47 80 C2 00   line#817  GETTABLE 1 1 -11       <21>   R1 = R1["new"]                                  -- It's Const#11
	  +ABB5: 81 80 03 00   line#817  LOADK 2 -15            <22>   R2 = 0                                          -- It's Const#15
	  +ABB9: C1 80 03 00   line#817  LOADK 3 -15            <23>   R3 = 0                                          -- It's Const#15
	  +ABBD: 01 81 03 00   line#817  LOADK 4 -15            <24>   R4 = 0                                          -- It's Const#15
	  +ABC1: 64 80 00 02   line#817  CALL 1 4 2             <25>   R1 = R1(R2, R3, R4)
	  +ABC5: 0A 40 00 86   line#817  SETTABLE 0 -13 1       <26>   R0@inf["Acceleration"] = R1                     -- It's Const#13
	  +ABC9: 0A 00 C4 87   line#818  SETTABLE 0 -16 -17     <27>   R0@inf["Archivable"] = true                     -- It's Const#16, Const#17
	  +ABCD: 0A 80 C4 88   line#819  SETTABLE 0 -18 -19     <28>   R0@inf["Drag"] = 20                             -- It's Const#18, Const#19
	  +ABD1: 46 00 45 00   line#820  GETTABUP 1 0 -21       <29>   R1 = Upv#1@_ENV["Enum"]                         -- It's Const#21
	  +ABD5: 47 40 C5 00   line#820  GETTABLE 1 1 -22       <30>   R1 = R1["NormalId"]                             -- It's Const#22
	  +ABD9: 47 80 C5 00   line#820  GETTABLE 1 1 -23       <31>   R1 = R1["Top"]                                  -- It's Const#23
	  +ABDD: 0A 40 80 89   line#820  SETTABLE 0 -20 1       <32>   R0@inf["EmissionDirection"] = R1                -- It's Const#20
	  +ABE1: 0A 00 C4 8B   line#821  SETTABLE 0 -24 -17     <33>   R0@inf["Enabled"] = true                        -- It's Const#24, Const#17
	  +ABE5: 46 40 46 00   line#822  GETTABUP 1 0 -26       <34>   R1 = Upv#1@_ENV["NumberRange"]                  -- It's Const#26
	  +ABE9: 47 80 C2 00   line#822  GETTABLE 1 1 -11       <35>   R1 = R1["new"]                                  -- It's Const#11
	  +ABED: 81 80 03 00   line#822  LOADK 2 -15            <36>   R2 = 0                                          -- It's Const#15
	  +ABF1: C1 80 03 00   line#822  LOADK 3 -15            <37>   R3 = 0                                          -- It's Const#15
	  +ABF5: 64 80 80 01   line#822  CALL 1 3 2             <38>   R1 = R1(R2, R3)
	  +ABF9: 0A 40 00 8C   line#822  SETTABLE 0 -25 1       <39>   R0@inf["Lifetime"] = R1                         -- It's Const#25
	  +ABFD: 0A 80 43 8D   line#823  SETTABLE 0 -27 -15     <40>   R0@inf["LightInfluence"] = 0                    -- It's Const#27, Const#15
	  +AC01: 0A 00 C4 8D   line#824  SETTABLE 0 -28 -17     <41>   R0@inf["LockedToPart"] = true                   -- It's Const#28, Const#17
	  +AC05: 0A 00 42 8E   line#825  SETTABLE 0 -29 -9      <42>   R0@inf["Name"] = "Agility"                      -- It's Const#29, Const#9
	  +AC09: 0A 80 C7 8E   line#826  SETTABLE 0 -30 -31     <43>   R0@inf["Rate"] = 500                            -- It's Const#30, Const#31
	  +AC0D: 4B 00 80 00   line#827  NEWTABLE 1 1 0         <44>   R1@numberKeypoints2 = {}  arr:1, hash:0
	  +AC11: 86 C0 47 00   line#828  GETTABUP 2 0 -32       <45>   R2 = Upv#1@_ENV["NumberSequenceKeypoint"]       -- It's Const#32
	  +AC15: 87 80 42 01   line#828  GETTABLE 2 2 -11       <46>   R2 = R2["new"]                                  -- It's Const#11
	  +AC19: C1 80 03 00   line#828  LOADK 3 -15            <47>   R3 = 0                                          -- It's Const#15
	  +AC1D: 01 81 03 00   line#828  LOADK 4 -15            <48>   R4 = 0                                          -- It's Const#15
	  +AC21: A4 80 80 01   line#828  CALL 2 3 2             <49>   R2 = R2(R3, R4)
	  +AC25: C6 C0 47 00   line#829  GETTABUP 3 0 -32       <50>   R3 = Upv#1@_ENV["NumberSequenceKeypoint"]       -- It's Const#32
	  +AC29: C7 80 C2 01   line#829  GETTABLE 3 3 -11       <51>   R3 = R3["new"]                                  -- It's Const#11
	  +AC2D: 01 01 08 00   line#829  LOADK 4 -33            <52>   R4 = 1                                          -- It's Const#33
	  +AC31: 41 41 08 00   line#829  LOADK 5 -34            <53>   R5 = 4                                          -- It's Const#34
	  +AC35: E4 00 80 01   line#829  CALL 3 3 0             <54>   R3,.. = R3(R4, R5)
	  +AC39: 6B 40 00 00   line#830  SETLIST 1 0 1          <55>   R1@numberKeypoints2[1],.. = R2,..
	  +AC3D: 86 C0 48 00   line#831  GETTABUP 2 0 -36       <56>   R2 = Upv#1@_ENV["NumberSequence"]               -- It's Const#36
	  +AC41: 87 80 42 01   line#831  GETTABLE 2 2 -11       <57>   R2 = R2["new"]                                  -- It's Const#11
	  +AC45: C0 00 80 00   line#831  MOVE 3 1               <58>   R3 = R1@numberKeypoints2
	  +AC49: A4 80 00 01   line#831  CALL 2 2 2             <59>   R2 = R2(R3)
	  +AC4D: 0A 80 00 91   line#831  SETTABLE 0 -35 2       <60>   R0@inf["Size"] = R2                             -- It's Const#35
	  +AC51: 86 40 46 00   line#832  GETTABUP 2 0 -26       <61>   R2 = Upv#1@_ENV["NumberRange"]                  -- It's Const#26
	  +AC55: 87 80 42 01   line#832  GETTABLE 2 2 -11       <62>   R2 = R2["new"]                                  -- It's Const#11
	  +AC59: C1 40 09 00   line#832  LOADK 3 -38            <63>   R3 = 9999                                       -- It's Const#38
	  +AC5D: 01 81 09 00   line#832  LOADK 4 -39            <64>   R4 = 99999                                      -- It's Const#39
	  +AC61: A4 80 80 01   line#832  CALL 2 3 2             <65>   R2 = R2(R3, R4)
	  +AC65: 0A 80 00 92   line#832  SETTABLE 0 -37 2       <66>   R0@inf["RotSpeed"] = R2                         -- It's Const#37
	  +AC69: 86 40 46 00   line#833  GETTABUP 2 0 -26       <67>   R2 = Upv#1@_ENV["NumberRange"]                  -- It's Const#26
	  +AC6D: 87 80 42 01   line#833  GETTABLE 2 2 -11       <68>   R2 = R2["new"]                                  -- It's Const#11
	  +AC71: C1 80 03 00   line#833  LOADK 3 -15            <69>   R3 = 0                                          -- It's Const#15
	  +AC75: 01 81 03 00   line#833  LOADK 4 -15            <70>   R4 = 0                                          -- It's Const#15
	  +AC79: A4 80 80 01   line#833  CALL 2 3 2             <71>   R2 = R2(R3, R4)
	  +AC7D: 0A 80 80 93   line#833  SETTABLE 0 -40 2       <72>   R0@inf["Rotation"] = R2                         -- It's Const#40
	  +AC81: 86 40 46 00   line#834  GETTABUP 2 0 -26       <73>   R2 = Upv#1@_ENV["NumberRange"]                  -- It's Const#26
	  +AC85: 87 80 42 01   line#834  GETTABLE 2 2 -11       <74>   R2 = R2["new"]                                  -- It's Const#11
	  +AC89: C1 40 0A 00   line#834  LOADK 3 -42            <75>   R3 = 30                                         -- It's Const#42
	  +AC8D: 01 41 0A 00   line#834  LOADK 4 -42            <76>   R4 = 30                                         -- It's Const#42
	  +AC91: A4 80 80 01   line#834  CALL 2 3 2             <77>   R2 = R2(R3, R4)
	  +AC95: 0A 80 00 94   line#834  SETTABLE 0 -41 2       <78>   R0@inf["Speed"] = R2                            -- It's Const#41
	  +AC99: 86 C0 4A 00   line#835  GETTABUP 2 0 -44       <79>   R2 = Upv#1@_ENV["Vector2"]                      -- It's Const#44
	  +AC9D: 87 80 42 01   line#835  GETTABLE 2 2 -11       <80>   R2 = R2["new"]                                  -- It's Const#11
	  +ACA1: C1 80 03 00   line#835  LOADK 3 -15            <81>   R3 = 0                                          -- It's Const#15
	  +ACA5: 01 81 03 00   line#835  LOADK 4 -15            <82>   R4 = 0                                          -- It's Const#15
	  +ACA9: 41 81 03 00   line#835  LOADK 5 -15            <83>   R5 = 0                                          -- It's Const#15
	  +ACAD: 81 81 03 00   line#835  LOADK 6 -15            <84>   R6 = 0                                          -- It's Const#15
	  +ACB1: A4 80 80 02   line#835  CALL 2 5 2             <85>   R2 = R2(R3,..,R6)
	  +ACB5: 0A 80 00 95   line#835  SETTABLE 0 -43 2       <86>   R0@inf["SpreadAngle"] = R2                      -- It's Const#43
	  +ACB9: 0A 40 4B 96   line#836  SETTABLE 0 -45 -46     <87>   R0@inf["Texture"] = ""                          -- It's Const#45, Const#46
	  +ACBD: 0A 80 43 97   line#837  SETTABLE 0 -47 -15     <88>   R0@inf["VelocityInheritance"] = 0               -- It's Const#47, Const#15
	  +ACC1: 0A 00 CC 97   line#838  SETTABLE 0 -48 -49     <89>   R0@inf["ZOffset"] = 2                           -- It's Const#48, Const#49
	  +ACC5: 86 C0 48 00   line#839  GETTABUP 2 0 -36       <90>   R2 = Upv#1@_ENV["NumberSequence"]               -- It's Const#36
	  +ACC9: 87 80 42 01   line#839  GETTABLE 2 2 -11       <91>   R2 = R2["new"]                                  -- It's Const#11
	  +ACCD: C1 80 03 00   line#839  LOADK 3 -15            <92>   R3 = 0                                          -- It's Const#15
	  +ACD1: A4 80 00 01   line#839  CALL 2 2 2             <93>   R2 = R2(R3)
	  +ACD5: 0A 80 80 98   line#839  SETTABLE 0 -50 2       <94>   R0@inf["Transparency"] = R2                     -- It's Const#50
	  +ACD9: 86 C0 4C 00   line#840  GETTABUP 2 0 -52       <95>   R2 = Upv#1@_ENV["ColorSequence"]                -- It's Const#52
	  +ACDD: 87 80 42 01   line#840  GETTABLE 2 2 -11       <96>   R2 = R2["new"]                                  -- It's Const#11
	  +ACE1: C6 00 4D 00   line#840  GETTABUP 3 0 -53       <97>   R3 = Upv#1@_ENV["Color3"]                       -- It's Const#53
	  +ACE5: C7 40 CD 01   line#840  GETTABLE 3 3 -54       <98>   R3 = R3["fromRGB"]                              -- It's Const#54
	  +ACE9: 01 81 03 00   line#840  LOADK 4 -15            <99>   R4 = 0                                          -- It's Const#15
	  +ACED: 41 81 03 00   line#840  LOADK 5 -15           <100>   R5 = 0                                          -- It's Const#15
	  +ACF1: 81 81 03 00   line#840  LOADK 6 -15           <101>   R6 = 0                                          -- It's Const#15
	  +ACF5: E4 80 00 02   line#840  CALL 3 4 2            <102>   R3 = R3(R4, R5, R6)
	  +ACF9: 06 01 4D 00   line#840  GETTABUP 4 0 -53      <103>   R4 = Upv#1@_ENV["Color3"]                       -- It's Const#53
	  +ACFD: 07 41 4D 02   line#840  GETTABLE 4 4 -54      <104>   R4 = R4["fromRGB"]                              -- It's Const#54
	  +AD01: 41 81 03 00   line#840  LOADK 5 -15           <105>   R5 = 0                                          -- It's Const#15
	  +AD05: 81 81 03 00   line#840  LOADK 6 -15           <106>   R6 = 0                                          -- It's Const#15
	  +AD09: C1 81 03 00   line#840  LOADK 7 -15           <107>   R7 = 0                                          -- It's Const#15
	  +AD0D: 24 01 00 02   line#840  CALL 4 4 0            <108>   R4,.. = R4(R5, R6, R7)
	  +AD11: A4 80 00 00   line#840  CALL 2 0 2            <109>   R2 = R2(R3,..)
	  +AD15: 0A 80 00 99   line#840  SETTABLE 0 -51 2      <110>   R0@inf["Color"] = R2                            -- It's Const#51
	  +AD19: 86 40 40 00   line#841  GETTABUP 2 0 -2       <111>   R2 = Upv#1@_ENV["game"]                         -- It's Const#2
	  +AD1D: 8C 80 40 01   line#841  SELF 2 2 -3           <112>   R3 = R2;  R2 = R2["GetService"]                 -- It's Const#3   -- prepare for R2:GetService()
	  +AD21: 01 C1 00 00   line#841  LOADK 4 -4            <113>   R4 = "Players"                                  -- It's Const#4
	  +AD25: A4 80 80 01   line#841  CALL 2 3 2            <114>   R2 = R2(R3, R4)
	  +AD29: 87 00 41 01   line#841  GETTABLE 2 2 -5       <115>   R2 = R2["LocalPlayer"]                          -- It's Const#5
	  +AD2D: 87 40 41 01   line#841  GETTABLE 2 2 -6       <116>   R2 = R2["Character"]                            -- It's Const#6
	  +AD31: 87 80 41 01   line#841  GETTABLE 2 2 -7       <117>   R2 = R2["HumanoidRootPart"]                     -- It's Const#7
	  +AD35: 0A 80 00 9B   line#841  SETTABLE 0 -55 2      <118>   R0@inf["Parent"] = R2                           -- It's Const#55
	  +AD39: 1E C0 05 80   line#842  JMP 0 24              <119>   GOTO <144>
	  +AD3D: 06 40 40 00   line#844  GETTABUP 0 0 -2       <120>   R0 = Upv#1@_ENV["game"]                         -- It's Const#2
	  +AD41: 0C 80 40 00   line#844  SELF 0 0 -3           <121>   R1 = R0;  R0 = R0["GetService"]                 -- It's Const#3   -- prepare for R0:GetService()
	  +AD45: 81 C0 00 00   line#844  LOADK 2 -4            <122>   R2 = "Players"                                  -- It's Const#4
	  +AD49: 24 80 80 01   line#844  CALL 0 3 2            <123>   R0 = R0(R1, R2)
	  +AD4D: 07 00 41 00   line#844  GETTABLE 0 0 -5       <124>   R0 = R0["LocalPlayer"]                          -- It's Const#5
	  +AD51: 07 40 41 00   line#844  GETTABLE 0 0 -6       <125>   R0 = R0["Character"]                            -- It's Const#6
	  +AD55: 07 80 41 00   line#844  GETTABLE 0 0 -7       <126>   R0 = R0["HumanoidRootPart"]                     -- It's Const#7
	  +AD59: 0C C0 41 00   line#844  SELF 0 0 -8           <127>   R1 = R0;  R0 = R0["FindFirstChild"]             -- It's Const#8   -- prepare for R0:FindFirstChild()
	  +AD5D: 81 00 02 00   line#844  LOADK 2 -9            <128>   R2 = "Agility"                                  -- It's Const#9
	  +AD61: 24 80 80 01   line#844  CALL 0 3 2            <129>   R0 = R0(R1, R2)
	  +AD65: 22 00 00 00   line#844  TEST 0 0              <130>   if R0 then GOTO <132>
	  +AD69: 1E C0 02 80   line#844  JMP 0 12              <131>   GOTO <144>
	  +AD6D: 06 40 40 00   line#845  GETTABUP 0 0 -2       <132>   R0 = Upv#1@_ENV["game"]                         -- It's Const#2
	  +AD71: 0C 80 40 00   line#845  SELF 0 0 -3           <133>   R1 = R0;  R0 = R0["GetService"]                 -- It's Const#3   -- prepare for R0:GetService()
	  +AD75: 81 C0 00 00   line#845  LOADK 2 -4            <134>   R2 = "Players"                                  -- It's Const#4
	  +AD79: 24 80 80 01   line#845  CALL 0 3 2            <135>   R0 = R0(R1, R2)
	  +AD7D: 07 00 41 00   line#845  GETTABLE 0 0 -5       <136>   R0 = R0["LocalPlayer"]                          -- It's Const#5
	  +AD81: 07 40 41 00   line#845  GETTABLE 0 0 -6       <137>   R0 = R0["Character"]                            -- It's Const#6
	  +AD85: 07 80 41 00   line#845  GETTABLE 0 0 -7       <138>   R0 = R0["HumanoidRootPart"]                     -- It's Const#7
	  +AD89: 0C C0 41 00   line#845  SELF 0 0 -8           <139>   R1 = R0;  R0 = R0["FindFirstChild"]             -- It's Const#8   -- prepare for R0:FindFirstChild()
	  +AD8D: 81 00 02 00   line#845  LOADK 2 -9            <140>   R2 = "Agility"                                  -- It's Const#9
	  +AD91: 24 80 80 01   line#845  CALL 0 3 2            <141>   R0 = R0(R1, R2)
	  +AD95: 0C C0 4D 00   line#845  SELF 0 0 -56          <142>   R1 = R0;  R0 = R0["Destroy"]                    -- It's Const#56   -- prepare for R0:Destroy()
	  +AD99: 24 40 00 01   line#845  CALL 0 2 1            <143>   R0(R1)
	  +AD9D: 26 00 80 00   line#848  RETURN 0 1            <144>   RETURN
	Functions: 0

	************ Function#11   (full path: main.11)
	Source line#: 852..858
	Parameters: 0
	Is vararg: no
	VM registers needed: 3
	Constants: 4
	  +B279:Size=9: 43 68 61 72 61 63 74 65 72      Const#1   string    "Character"
	  +B284:Size=6: 45 6E 65 72 67 79               Const#2   string    "Energy"
	  +B28C:Size=7: 43 68 61 6E 67 65 64            Const#3   string    "Changed"
	  +B295:Size=7: 63 6F 6E 6E 65 63 74            Const#4   string    "connect"
	Upvalues: 3
	  Upv#1 is parent function's R1                 name: LocalPlayer
	  Upv#2 is parent function's Upv#1              name: _ENV
	  Upv#3 is parent function's R2                 name: originalstam
	Instructions: 7
	  +B257: 06 00 40 00   line#853  GETTABUP 0 0 -1         <1>   R0 = Upv#1@LocalPlayer["Character"]             -- It's Const#1
	  +B25B: 07 40 40 00   line#853  GETTABLE 0 0 -2         <2>   R0 = R0["Energy"]                               -- It's Const#2
	  +B25F: 07 80 40 00   line#853  GETTABLE 0 0 -3         <3>   R0 = R0["Changed"]                              -- It's Const#3
	  +B263: 0C C0 40 00   line#853  SELF 0 0 -4             <4>   R1 = R0;  R0 = R0["connect"]                    -- It's Const#4   -- prepare for R0:connect()
	  +B267: AC 00 00 00   line#857  CLOSURE 2 0             <5>   R2 = Function#1
	  +B26B: 24 40 80 01   line#853  CALL 0 3 1              <6>   R0(R1, R2)
	  +B26F: 26 00 80 00   line#858  RETURN 0 1              <7>   RETURN
	Functions: 1

		************ Function#1   (full path: main.11.1)
		Source line#: 853..857
		Parameters: 0
		Is vararg: no
		VM registers needed: 2
		Constants: 4
		  +B2E0:Size=E: 49 6E 66 69 6E 69 74 65 45...   Const#1   string    "InfiniteEnergy"
		  +B2F0:Size=9: 43 68 61 72 61 63 74 65 72      Const#2   string    "Character"
		  +B2FB:Size=6: 45 6E 65 72 67 79               Const#3   string    "Energy"
		  +B303:Size=5: 56 61 6C 75 65                  Const#4   string    "Value"
		Upvalues: 3
		  Upv#1 is parent function's Upv#2              name: _ENV
		  Upv#2 is parent function's Upv#1              name: LocalPlayer
		  Upv#3 is parent function's Upv#3              name: originalstam
		Instructions: 8
		  +B2BA: 06 00 40 00   line#854  GETTABUP 0 0 -1         <1>   R0 = Upv#1@_ENV["InfiniteEnergy"]               -- It's Const#1
		  +B2BE: 22 00 00 00   line#854  TEST 0 0                <2>   if R0 then GOTO <4>
		  +B2C2: 1E C0 00 80   line#854  JMP 0 4                 <3>   GOTO <8>
		  +B2C6: 06 40 C0 00   line#855  GETTABUP 0 1 -2         <4>   R0 = Upv#2@LocalPlayer["Character"]             -- It's Const#2
		  +B2CA: 07 80 40 00   line#855  GETTABLE 0 0 -3         <5>   R0 = R0["Energy"]                               -- It's Const#3
		  +B2CE: 45 00 00 01   line#855  GETUPVAL 1 2            <6>   R1 = Upv#3@originalstam
		  +B2D2: 0A 40 80 81   line#855  SETTABLE 0 -4 1         <7>   R0["Value"] = R1                                -- It's Const#4
		  +B2D6: 26 00 80 00   line#857  RETURN 0 1              <8>   RETURN
		Functions: 0

	************ Function#12   (full path: main.12)
	Source line#: 860..870
	Parameters: 0
	Is vararg: no
	VM registers needed: 2
	Constants: 1
	  +B3CC:Size=5: 70 63 61 6C 6C                  Const#1   string    "pcall"
	Upvalues: 3
	  Upv#1 is parent function's Upv#1              name: _ENV
	  Upv#2 is parent function's R2                 name: originalstam
	  Upv#3 is parent function's R1                 name: LocalPlayer
	Instructions: 4
	  +B3B6: 06 00 40 00   line#861  GETTABUP 0 0 -1         <1>   R0 = Upv#1@_ENV["pcall"]                        -- It's Const#1
	  +B3BA: 6C 00 00 00   line#869  CLOSURE 1 0             <2>   R1 = Function#1
	  +B3BE: 24 40 00 01   line#861  CALL 0 2 1              <3>   R0(R1)
	  +B3C2: 26 00 80 00   line#870  RETURN 0 1              <4>   RETURN
	Functions: 1

		************ Function#1   (full path: main.12.1)
		Source line#: 861..869
		Parameters: 0
		Is vararg: no
		VM registers needed: 2
		Constants: 7
		  +B441:Size=4: 77 61 69 74                     Const#1   string    "wait"
		  +B446:Size=8: 9A 99 99 99 99 99 B9 3F         Const#2   float     0.1
		  +B450:Size=E: 49 6E 66 69 6E 69 74 65 45...   Const#3   string    "InfiniteEnergy"
		  +B460:Size=9: 43 68 61 72 61 63 74 65 72      Const#4   string    "Character"
		  +B46B:Size=6: 45 6E 65 72 67 79               Const#5   string    "Energy"
		  +B473:Size=5: 56 61 6C 75 65                  Const#6   string    "Value"
		  +B47A:Size=C: 69 6E 66 69 6E 69 74 65 73...   Const#7   string    "infinitestam"
		Upvalues: 3
		  Upv#1 is parent function's Upv#1              name: _ENV
		  Upv#2 is parent function's Upv#2              name: originalstam
		  Upv#3 is parent function's Upv#3              name: LocalPlayer
		Instructions: 19
		  +B3EF: 06 00 40 00   line#862  GETTABUP 0 0 -1         <1>   R0 = Upv#1@_ENV["wait"]                         -- It's Const#1
		  +B3F3: 41 40 00 00   line#862  LOADK 1 -2              <2>   R1 = 0.1                                        -- It's Const#2
		  +B3F7: 24 80 00 01   line#862  CALL 0 2 2              <3>   R0 = R0(R1)
		  +B3FB: 22 00 00 00   line#862  TEST 0 0                <4>   if R0 then GOTO <6>
		  +B3FF: 1E 00 03 80   line#862  JMP 0 13                <5>   GOTO <19>
		  +B403: 06 80 40 00   line#863  GETTABUP 0 0 -3         <6>   R0 = Upv#1@_ENV["InfiniteEnergy"]               -- It's Const#3
		  +B407: 22 00 00 00   line#863  TEST 0 0                <7>   if R0 then GOTO <9>
		  +B40B: 1E C0 FD 7F   line#863  JMP 0 -8                <8>   GOTO <1>
		  +B40F: 06 00 40 00   line#864  GETTABUP 0 0 -1         <9>   R0 = Upv#1@_ENV["wait"]                         -- It's Const#1
		  +B413: 41 40 00 00   line#864  LOADK 1 -2             <10>   R1 = 0.1                                        -- It's Const#2
		  +B417: 24 40 00 01   line#864  CALL 0 2 1             <11>   R0(R1)
		  +B41B: 06 C0 40 01   line#865  GETTABUP 0 2 -4        <12>   R0 = Upv#3@LocalPlayer["Character"]             -- It's Const#4
		  +B41F: 07 00 41 00   line#865  GETTABLE 0 0 -5        <13>   R0 = R0["Energy"]                               -- It's Const#5
		  +B423: 07 40 41 00   line#865  GETTABLE 0 0 -6        <14>   R0 = R0["Value"]                                -- It's Const#6
		  +B427: 09 00 80 00   line#865  SETUPVAL 0 1           <15>   Upv#2@originalstam = R0
		  +B42B: 06 80 41 00   line#866  GETTABUP 0 0 -7        <16>   R0 = Upv#1@_ENV["infinitestam"]                 -- It's Const#7
		  +B42F: 24 40 80 00   line#866  CALL 0 1 1             <17>   R0()
		  +B433: 1E 40 FB 7F   line#867  JMP 0 -18              <18>   GOTO <1>
		  +B437: 26 00 80 00   line#869  RETURN 0 1             <19>   RETURN
		Functions: 0

	************ Function#13   (full path: main.13)
	Source line#: 872..888
	Parameters: 0
	Is vararg: no
	VM registers needed: 14
	Constants: 20
	  +B64A:Size=B: 6E 6F 64 6F 64 67 65 63 6F...   Const#1   string    "nododgecool"
	  +B657:Size=4: 6E 65 78 74                     Const#2   string    "next"
	  +B65D:Size=5: 67 65 74 67 63                  Const#3   string    "getgc"
	  +B664:Size=4: 67 61 6D 65                     Const#4   string    "game"
	  +B66A:Size=A: 47 65 74 53 65 72 76 69 63 65   Const#5   string    "GetService"
	  +B676:Size=7: 50 6C 61 79 65 72 73            Const#6   string    "Players"
	  +B67F:Size=B: 4C 6F 63 61 6C 50 6C 61 79...   Const#7   string    "LocalPlayer"
	  +B68C:Size=9: 43 68 61 72 61 63 74 65 72      Const#8   string    "Character"
	  +B697:Size=5: 44 6F 64 67 65                  Const#9   string    "Dodge"
	  +B69E:Size=6: 74 79 70 65 6F 66               Const#10  string    "typeof"
	  +B6A6:Size=8: 66 75 6E 63 74 69 6F 6E         Const#11  string    "function"
	  +B6B0:Size=7: 67 65 74 66 65 6E 76            Const#12  string    "getfenv"
	  +B6B9:Size=6: 73 63 72 69 70 74               Const#13  string    "script"
	  +B6C1:Size=B: 67 65 74 75 70 76 61 6C 75...   Const#14  string    "getupvalues"
	  +B6CE:Size=8: 74 6F 73 74 72 69 6E 67         Const#15  string    "tostring"
	  +B6D8:Size=3: 30 2E 31                        Const#16  string    "0.1"
	  +B6DD:Size=4: 77 61 69 74                     Const#17  string    "wait"
	  +B6E2:Size=8: 9A 99 99 99 99 99 B9 3F         Const#18  float     0.1
	  +B6EC:Size=A: 73 65 74 75 70 76 61 6C 75 65   Const#19  string    "setupvalue"
	  +B6F7:Size=4: 00 00 00 00                     Const#20  integer   0
	Upvalues: 1
	  Upv#1 is parent function's Upv#1              name: _ENV
	Locals: 10
	  Local#1   R0   def:<4>    scope:<7..59>       name: (for generator)
	  Local#2   R1   def:<6>    scope:<7..59>       name: (for state)
	  Local#3   R2   def:<6>    scope:<7..59>       name: (for control)
	  Local#4   R3   def:<7>    scope:<8..57>       name: i
	  Local#5   R4   def:<7>    scope:<8..57>       name: v
	  Local#6   R5   def:<35>   scope:<39..57>      name: (for generator)
	  Local#7   R6   def:<38>   scope:<39..57>      name: (for state)
	  Local#8   R7   def:<38>   scope:<39..57>      name: (for control)
	  Local#9   R8   def:<39>   scope:<40..55>      name: i2
	  Local#10  R9   def:<39>   scope:<40..55>      name: v2
	Instructions: 60
	  +B554: 06 00 40 00   line#873  GETTABUP 0 0 -1         <1>   R0 = Upv#1@_ENV["nododgecool"]                  -- It's Const#1
	  +B558: 22 00 00 00   line#873  TEST 0 0                <2>   if R0 then GOTO <4>
	  +B55C: 1E C0 0D 80   line#873  JMP 0 56                <3>   GOTO <60>
	  +B560: 06 40 40 00   line#874  GETTABUP 0 0 -2         <4>   R0 = Upv#1@_ENV["next"]                         -- It's Const#2
	  +B564: 46 80 40 00   line#874  GETTABUP 1 0 -3         <5>   R1 = Upv#1@_ENV["getgc"]                        -- It's Const#3
	  +B568: 64 C0 80 00   line#874  CALL 1 1 3              <6>   R1, R2 = R1()
	  +B56C: 1E 40 0C 80   line#874  JMP 0 50                <7>   GOTO <58>                                       -- for R3@i, R4@v in R0, R1, R2 do
	  +B570: 46 C1 40 00   line#875  GETTABUP 5 0 -4         <8>   R5 = Upv#1@_ENV["game"]                         -- It's Const#4
	  +B574: 4C 01 C1 02   line#875  SELF 5 5 -5             <9>   R6 = R5;  R5 = R5["GetService"]                 -- It's Const#5   -- prepare for R5:GetService()
	  +B578: C1 41 01 00   line#875  LOADK 7 -6             <10>   R7 = "Players"                                  -- It's Const#6
	  +B57C: 64 81 80 01   line#875  CALL 5 3 2             <11>   R5 = R5(R6, R7)
	  +B580: 47 81 C1 02   line#875  GETTABLE 5 5 -7        <12>   R5 = R5["LocalPlayer"]                          -- It's Const#7
	  +B584: 47 C1 C1 02   line#875  GETTABLE 5 5 -8        <13>   R5 = R5["Character"]                            -- It's Const#8
	  +B588: 47 01 C2 02   line#875  GETTABLE 5 5 -9        <14>   R5 = R5["Dodge"]                                -- It's Const#9
	  +B58C: 62 01 00 00   line#875  TEST 5 0               <15>   if R5 then GOTO <17>
	  +B590: 1E 00 0A 80   line#875  JMP 0 41               <16>   GOTO <58>
	  +B594: 46 41 42 00   line#876  GETTABUP 5 0 -10       <17>   R5 = Upv#1@_ENV["typeof"]                       -- It's Const#10
	  +B598: 80 01 00 02   line#876  MOVE 6 4               <18>   R6 = R4@v
	  +B59C: 64 81 00 01   line#876  CALL 5 2 2             <19>   R5 = R5(R6)
	  +B5A0: 1F 80 C2 02   line#876  EQ 0 5 -11             <20>   if R5 == "function" then GOTO <22>              -- It's Const#11
	  +B5A4: 1E C0 08 80   line#876  JMP 0 36               <21>   GOTO <58>
	  +B5A8: 46 C1 42 00   line#876  GETTABUP 5 0 -12       <22>   R5 = Upv#1@_ENV["getfenv"]                      -- It's Const#12
	  +B5AC: 80 01 00 02   line#876  MOVE 6 4               <23>   R6 = R4@v
	  +B5B0: 64 81 00 01   line#876  CALL 5 2 2             <24>   R5 = R5(R6)
	  +B5B4: 47 01 C3 02   line#876  GETTABLE 5 5 -13       <25>   R5 = R5["script"]                               -- It's Const#13
	  +B5B8: 86 C1 40 00   line#876  GETTABUP 6 0 -4        <26>   R6 = Upv#1@_ENV["game"]                         -- It's Const#4
	  +B5BC: 8C 01 41 03   line#876  SELF 6 6 -5            <27>   R7 = R6;  R6 = R6["GetService"]                 -- It's Const#5   -- prepare for R6:GetService()
	  +B5C0: 01 42 01 00   line#876  LOADK 8 -6             <28>   R8 = "Players"                                  -- It's Const#6
	  +B5C4: A4 81 80 01   line#876  CALL 6 3 2             <29>   R6 = R6(R7, R8)
	  +B5C8: 87 81 41 03   line#876  GETTABLE 6 6 -7        <30>   R6 = R6["LocalPlayer"]                          -- It's Const#7
	  +B5CC: 87 C1 41 03   line#876  GETTABLE 6 6 -8        <31>   R6 = R6["Character"]                            -- It's Const#8
	  +B5D0: 87 01 42 03   line#876  GETTABLE 6 6 -9        <32>   R6 = R6["Dodge"]                                -- It's Const#9
	  +B5D4: 1F 80 81 02   line#876  EQ 0 5 6               <33>   if R5 == R6 then GOTO <35>
	  +B5D8: 1E 80 05 80   line#876  JMP 0 23               <34>   GOTO <58>
	  +B5DC: 46 41 40 00   line#877  GETTABUP 5 0 -2        <35>   R5 = Upv#1@_ENV["next"]                         -- It's Const#2
	  +B5E0: 86 41 43 00   line#877  GETTABUP 6 0 -14       <36>   R6 = Upv#1@_ENV["getupvalues"]                  -- It's Const#14
	  +B5E4: C0 01 00 02   line#877  MOVE 7 4               <37>   R7 = R4@v
	  +B5E8: A4 C1 00 01   line#877  CALL 6 2 3             <38>   R6, R7 = R6(R7)
	  +B5EC: 1E C0 03 80   line#877  JMP 0 16               <39>   GOTO <56>                                       -- for R8@i2, R9@v2 in R5, R6, R7 do
	  +B5F0: 86 82 43 00   line#878  GETTABUP 10 0 -15      <40>   R10 = Upv#1@_ENV["tostring"]                    -- It's Const#15
	  +B5F4: C0 02 80 04   line#878  MOVE 11 9              <41>   R11 = R9@v2
	  +B5F8: A4 82 00 01   line#878  CALL 10 2 2            <42>   R10 = R10(R11)
	  +B5FC: 1F C0 43 05   line#878  EQ 0 10 -16            <43>   if R10 == "0.1" then GOTO <45>                  -- It's Const#16
	  +B600: 1E 80 02 80   line#878  JMP 0 11               <44>   GOTO <56>
	  +B604: 86 02 44 00   line#879  GETTABUP 10 0 -17      <45>   R10 = Upv#1@_ENV["wait"]                        -- It's Const#17
	  +B608: C1 42 04 00   line#879  LOADK 11 -18           <46>   R11 = 0.1                                       -- It's Const#18
	  +B60C: A4 42 00 01   line#879  CALL 10 2 1            <47>   R10(R11)
	  +B610: 86 82 44 00   line#880  GETTABUP 10 0 -19      <48>   R10 = Upv#1@_ENV["setupvalue"]                  -- It's Const#19
	  +B614: C0 02 00 02   line#880  MOVE 11 4              <49>   R11 = R4@v
	  +B618: 00 03 00 04   line#880  MOVE 12 8              <50>   R12 = R8@i2
	  +B61C: 41 C3 04 00   line#880  LOADK 13 -20           <51>   R13 = 0                                         -- It's Const#20
	  +B620: A4 42 00 02   line#880  CALL 10 4 1            <52>   R10(R11, R12, R13)
	  +B624: 86 02 40 00   line#881  GETTABUP 10 0 -1       <53>   R10 = Upv#1@_ENV["nododgecool"]                 -- It's Const#1
	  +B628: A2 42 00 00   line#881  TEST 10 1              <54>   if not R10 then GOTO <56>
	  +B62C: 1E 00 FD 7F   line#881  JMP 0 -11              <55>   GOTO <45>
	  +B630: 69 81 00 00   line#877  TFORCALL 5 2           <56>   R8, R9 = R5(R6, R7)
	  +B634: EA 41 FB 7F   line#877  TFORLOOP 7 -18         <57>   if R8 ~= nil then { R7 = R8;  GOTO <40> }       -- end of loop
	  +B638: 29 80 00 00   line#874  TFORCALL 0 2           <58>   R3, R4 = R0(R1, R2)
	  +B63C: AA C0 F2 7F   line#874  TFORLOOP 2 -52         <59>   if R3 ~= nil then { R2 = R3;  GOTO <8> }        -- end of loop
	  +B640: 26 00 80 00   line#888  RETURN 0 1             <60>   RETURN
	Functions: 0

	************ Function#14   (full path: main.14)
	Source line#: 890..978
	Parameters: 0
	Is vararg: no
	VM registers needed: 10
	Constants: 19
	  +B996:Size=4: 67 61 6D 65                     Const#1   string    "game"
	  +B99C:Size=A: 47 65 74 53 65 72 76 69 63 65   Const#2   string    "GetService"
	  +B9A8:Size=7: 50 6C 61 79 65 72 73            Const#3   string    "Players"
	  +B9B1:Size=B: 4C 6F 63 61 6C 50 6C 61 79...   Const#4   string    "LocalPlayer"
	  +B9BE:Size=8: 47 65 74 4D 6F 75 73 65         Const#5   string    "GetMouse"
	  +B9C8:Size=0:                                 Const#6   string    ""
	  +B9CA:Size=B: 6C 6F 63 61 6C 70 6C 61 79...   Const#7   string    "localplayer"
	  +B9D7:Size=9: 43 68 61 72 61 63 74 65 72      Const#8   string    "Character"
	  +B9E2:Size=C: 57 61 69 74 46 6F 72 43 68...   Const#9   string    "WaitForChild"
	  +B9F0:Size=10: 48 75 6D 61 6E 6F 69 64 5...   Const#10  string    "HumanoidRootPart"
	  +BA01:Size=4: 19 00 00 00                     Const#11  integer   25
	  +BA07:Size=1: 61                              Const#12  string    "a"
	  +BA09:Size=1: 00                              Const#13  boolean   false
	  +BA0C:Size=1: 64                              Const#14  string    "d"
	  +BA0F:Size=1: 77                              Const#15  string    "w"
	  +BA12:Size=1: 73                              Const#16  string    "s"
	  +BA15:Size=7: 4B 65 79 44 6F 77 6E            Const#17  string    "KeyDown"
	  +BA1E:Size=7: 63 6F 6E 6E 65 63 74            Const#18  string    "connect"
	  +BA27:Size=5: 4B 65 79 55 70                  Const#19  string    "KeyUp"
	Upvalues: 1
	  Upv#1 is parent function's Upv#1              name: _ENV
	Locals: 7
	  Local#1   R0   def:<8>    scope:<9..51>       name: mouse
	  Local#2   R1   def:<30>   scope:<31..51>      name: torso
	  Local#3   R2   def:<31>   scope:<32..51>      name: speedSET
	  Local#4   R3   def:<32>   scope:<37..51>      name: keys
	  Local#5   R4   def:<37>   scope:<38..51>      name: e1
	  Local#6   R5   def:<37>   scope:<38..51>      name: e2
	  Local#7   R6   def:<38>   scope:<39..51>      name: start
	Instructions: 51
	  +B8C4: 06 00 40 00   line#891  GETTABUP 0 0 -1         <1>   R0 = Upv#1@_ENV["game"]                         -- It's Const#1
	  +B8C8: 0C 40 40 00   line#891  SELF 0 0 -2             <2>   R1 = R0;  R0 = R0["GetService"]                 -- It's Const#2   -- prepare for R0:GetService()
	  +B8CC: 81 80 00 00   line#891  LOADK 2 -3              <3>   R2 = "Players"                                  -- It's Const#3
	  +B8D0: 24 80 80 01   line#891  CALL 0 3 2              <4>   R0 = R0(R1, R2)
	  +B8D4: 07 C0 40 00   line#891  GETTABLE 0 0 -4         <5>   R0 = R0["LocalPlayer"]                          -- It's Const#4
	  +B8D8: 0C 00 41 00   line#891  SELF 0 0 -5             <6>   R1 = R0;  R0 = R0["GetMouse"]                   -- It's Const#5   -- prepare for R0:GetMouse()
	  +B8DC: 81 40 01 00   line#891  LOADK 2 -6              <7>   R2 = ""                                         -- It's Const#6
	  +B8E0: 24 80 80 01   line#891  CALL 0 3 2              <8>   R0@mouse = R0(R1, R2)
	  +B8E4: 46 00 40 00   line#892  GETTABUP 1 0 -1         <9>   R1 = Upv#1@_ENV["game"]                         -- It's Const#1
	  +B8E8: 4C 40 C0 00   line#892  SELF 1 1 -2            <10>   R2 = R1;  R1 = R1["GetService"]                 -- It's Const#2   -- prepare for R1:GetService()
	  +B8EC: C1 80 00 00   line#892  LOADK 3 -3             <11>   R3 = "Players"                                  -- It's Const#3
	  +B8F0: 64 80 80 01   line#892  CALL 1 3 2             <12>   R1 = R1(R2, R3)
	  +B8F4: 47 C0 C0 00   line#892  GETTABLE 1 1 -4        <13>   R1 = R1["LocalPlayer"]                          -- It's Const#4
	  +B8F8: 08 40 00 83   line#892  SETTABUP 0 -7 1        <14>   Upv#1@_ENV["localplayer"] = R1                  -- It's Const#7
	  +B8FC: 46 00 40 00   line#893  GETTABUP 1 0 -1        <15>   R1 = Upv#1@_ENV["game"]                         -- It's Const#1
	  +B900: 4C 40 C0 00   line#893  SELF 1 1 -2            <16>   R2 = R1;  R1 = R1["GetService"]                 -- It's Const#2   -- prepare for R1:GetService()
	  +B904: C1 80 00 00   line#893  LOADK 3 -3             <17>   R3 = "Players"                                  -- It's Const#3
	  +B908: 64 80 80 01   line#893  CALL 1 3 2             <18>   R1 = R1(R2, R3)
	  +B90C: 47 C0 C0 00   line#893  GETTABLE 1 1 -4        <19>   R1 = R1["LocalPlayer"]                          -- It's Const#4
	  +B910: 47 C0 C1 00   line#893  GETTABLE 1 1 -8        <20>   R1 = R1["Character"]                            -- It's Const#8
	  +B914: 4C 00 C2 00   line#893  SELF 1 1 -9            <21>   R2 = R1;  R1 = R1["WaitForChild"]               -- It's Const#9   -- prepare for R1:WaitForChild()
	  +B918: C1 40 02 00   line#893  LOADK 3 -10            <22>   R3 = "HumanoidRootPart"                         -- It's Const#10
	  +B91C: 64 40 80 01   line#893  CALL 1 3 1             <23>   R1(R2, R3)
	  +B920: 46 00 40 00   line#894  GETTABUP 1 0 -1        <24>   R1 = Upv#1@_ENV["game"]                         -- It's Const#1
	  +B924: 4C 40 C0 00   line#894  SELF 1 1 -2            <25>   R2 = R1;  R1 = R1["GetService"]                 -- It's Const#2   -- prepare for R1:GetService()
	  +B928: C1 80 00 00   line#894  LOADK 3 -3             <26>   R3 = "Players"                                  -- It's Const#3
	  +B92C: 64 80 80 01   line#894  CALL 1 3 2             <27>   R1 = R1(R2, R3)
	  +B930: 47 C0 C0 00   line#894  GETTABLE 1 1 -4        <28>   R1 = R1["LocalPlayer"]                          -- It's Const#4
	  +B934: 47 C0 C1 00   line#894  GETTABLE 1 1 -8        <29>   R1 = R1["Character"]                            -- It's Const#8
	  +B938: 47 40 C2 00   line#894  GETTABLE 1 1 -10       <30>   R1@torso = R1["HumanoidRootPart"]               -- It's Const#10
	  +B93C: 81 80 02 00   line#895  LOADK 2 -11            <31>   R2@speedSET = 25                                -- It's Const#11
	  +B940: CB 00 01 00   line#896  NEWTABLE 3 0 4         <32>   R3@keys = {}  arr:0, hash:4
	  +B944: CA 00 C3 85   line#896  SETTABLE 3 -12 -13     <33>   R3["a"] = false                                 -- It's Const#12, Const#13
	  +B948: CA 00 C3 86   line#896  SETTABLE 3 -14 -13     <34>   R3["d"] = false                                 -- It's Const#14, Const#13
	  +B94C: CA 00 43 87   line#896  SETTABLE 3 -15 -13     <35>   R3["w"] = false                                 -- It's Const#15, Const#13
	  +B950: CA 00 C3 87   line#896  SETTABLE 3 -16 -13     <36>   R3["s"] = false                                 -- It's Const#16, Const#13
	  +B954: 04 01 80 00   line#897  LOADNIL 4 1            <37>   R4@e1, R5@e2 = nil
	  +B958: AC 01 00 00   line#951  CLOSURE 6 0            <38>   R6@start = Function#1
	  +B95C: C7 01 44 00   line#952  GETTABLE 7 0 -17       <39>   R7 = R0@mouse["KeyDown"]                        -- It's Const#17
	  +B960: CC 41 C4 03   line#952  SELF 7 7 -18           <40>   R8 = R7;  R7 = R7["connect"]                    -- It's Const#18   -- prepare for R7:connect()
	  +B964: 6C 42 00 00   line#965  CLOSURE 9 1            <41>   R9 = Function#2
	  +B968: E4 81 80 01   line#952  CALL 7 3 2             <42>   R7 = R7(R8, R9)
	  +B96C: 00 01 80 03   line#965  MOVE 4 7               <43>   R4@e1 = R7
	  +B970: C7 81 44 00   line#966  GETTABLE 7 0 -19       <44>   R7 = R0@mouse["KeyUp"]                          -- It's Const#19
	  +B974: CC 41 C4 03   line#966  SELF 7 7 -18           <45>   R8 = R7;  R7 = R7["connect"]                    -- It's Const#18   -- prepare for R7:connect()
	  +B978: 6C 82 00 00   line#976  CLOSURE 9 2            <46>   R9 = Function#3
	  +B97C: E4 81 80 01   line#966  CALL 7 3 2             <47>   R7 = R7(R8, R9)
	  +B980: 40 01 80 03   line#976  MOVE 5 7               <48>   R5@e2 = R7
	  +B984: C0 01 00 03   line#977  MOVE 7 6               <49>   R7 = R6@start
	  +B988: E4 41 80 00   line#977  CALL 7 1 1             <50>   R7()
	  +B98C: 26 00 80 00   line#978  RETURN 0 1             <51>   RETURN
	Functions: 3

		************ Function#1   (full path: main.14.1)
		Source line#: 899..951
		Parameters: 0
		Is vararg: no
		VM registers needed: 8
		Constants: 40
		  +BD28:Size=8: 49 6E 73 74 61 6E 63 65         Const#1   string    "Instance"
		  +BD32:Size=3: 6E 65 77                        Const#2   string    "new"
		  +BD37:Size=C: 42 6F 64 79 50 6F 73 69 74...   Const#3   string    "BodyPosition"
		  +BD45:Size=8: 42 6F 64 79 47 79 72 6F         Const#4   string    "BodyGyro"
		  +BD4F:Size=4: 4E 61 6D 65                     Const#5   string    "Name"
		  +BD55:Size=7: 45 50 49 58 50 4F 53            Const#6   string    "EPIXPOS"
		  +BD5E:Size=8: 6D 61 78 46 6F 72 63 65         Const#7   string    "maxForce"
		  +BD68:Size=7: 56 65 63 74 6F 72 33            Const#8   string    "Vector3"
		  +BD71:Size=4: 6D 61 74 68                     Const#9   string    "math"
		  +BD77:Size=4: 68 75 67 65                     Const#10  string    "huge"
		  +BD7D:Size=8: 70 6F 73 69 74 69 6F 6E         Const#11  string    "position"
		  +BD87:Size=8: 50 6F 73 69 74 69 6F 6E         Const#12  string    "Position"
		  +BD91:Size=9: 6D 61 78 54 6F 72 71 75 65      Const#13  string    "maxTorque"
		  +BD9B:Size=8: 00 00 00 D0 88 C3 00 42         Const#14  float     9e+009
		  +BDA5:Size=6: 43 46 72 61 6D 65               Const#15  string    "CFrame"
		  +BDAD:Size=4: 77 61 69 74                     Const#16  string    "wait"
		  +BDB3:Size=B: 6C 6F 63 61 6C 70 6C 61 79...   Const#17  string    "localplayer"
		  +BDC0:Size=9: 43 68 61 72 61 63 74 65 72      Const#18  string    "Character"
		  +BDCB:Size=8: 48 75 6D 61 6E 6F 69 64         Const#19  string    "Humanoid"
		  +BDD5:Size=D: 50 6C 61 74 66 6F 72 6D 53...   Const#20  string    "PlatformStand"
		  +BDE3:Size=1: 01                              Const#21  boolean   true
		  +BDE6:Size=1: 70                              Const#22  string    "p"
		  +BDE9:Size=1: 77                              Const#23  string    "w"
		  +BDEC:Size=1: 73                              Const#24  string    "s"
		  +BDEF:Size=1: 61                              Const#25  string    "a"
		  +BDF2:Size=1: 64                              Const#26  string    "d"
		  +BDF5:Size=5: 73 70 65 65 64                  Const#27  string    "speed"
		  +BDFB:Size=4: 01 00 00 00                     Const#28  integer   1
		  +BE01:Size=9: 77 6F 72 6B 73 70 61 63 65      Const#29  string    "workspace"
		  +BE0C:Size=D: 43 75 72 72 65 6E 74 43 61...   Const#30  string    "CurrentCamera"
		  +BE1B:Size=F: 43 6F 6F 72 64 69 6E 61 74...   Const#31  string    "CoordinateFrame"
		  +BE2C:Size=A: 6C 6F 6F 6B 56 65 63 74 6F 72   Const#32  string    "lookVector"
		  +BE37:Size=4: 00 00 00 00                     Const#33  integer   0
		  +BE3D:Size=6: 41 6E 67 6C 65 73               Const#34  string    "Angles"
		  +BE45:Size=3: 72 61 64                        Const#35  string    "rad"
		  +BE49:Size=4: 0F 00 00 00                     Const#36  integer   15
		  +BE4F:Size=3: 46 6C 79                        Const#37  string    "Fly"
		  +BE54:Size=7: 44 65 73 74 72 6F 79            Const#38  string    "Destroy"
		  +BE5D:Size=6: 66 6C 79 69 6E 67               Const#39  string    "flying"
		  +BE64:Size=1: 00                              Const#40  boolean   false
		Upvalues: 4
		  Upv#1 is parent function's Upv#1              name: _ENV
		  Upv#2 is parent function's R1                 name: torso
		  Upv#3 is parent function's R3                 name: keys
		  Upv#4 is parent function's R2                 name: speedSET
		Locals: 3
		  Local#1   R0   def:<5>    scope:<6..183>      name: pos
		  Local#2   R1   def:<10>   scope:<11..183>     name: gyro
		  Local#3   R2   def:<44>   scope:<45..168>     name: new
		Instructions: 183
		  +BA46: 06 00 40 00   line#900  GETTABUP 0 0 -1         <1>   R0 = Upv#1@_ENV["Instance"]                     -- It's Const#1
		  +BA4A: 07 40 40 00   line#900  GETTABLE 0 0 -2         <2>   R0 = R0["new"]                                  -- It's Const#2
		  +BA4E: 41 80 00 00   line#900  LOADK 1 -3              <3>   R1 = "BodyPosition"                             -- It's Const#3
		  +BA52: 85 00 80 00   line#900  GETUPVAL 2 1            <4>   R2 = Upv#2@torso
		  +BA56: 24 80 80 01   line#900  CALL 0 3 2              <5>   R0@pos = R0(R1, R2)
		  +BA5A: 46 00 40 00   line#901  GETTABUP 1 0 -1         <6>   R1 = Upv#1@_ENV["Instance"]                     -- It's Const#1
		  +BA5E: 47 40 C0 00   line#901  GETTABLE 1 1 -2         <7>   R1 = R1["new"]                                  -- It's Const#2
		  +BA62: 81 C0 00 00   line#901  LOADK 2 -4              <8>   R2 = "BodyGyro"                                 -- It's Const#4
		  +BA66: C5 00 80 00   line#901  GETUPVAL 3 1            <9>   R3 = Upv#2@torso
		  +BA6A: 64 80 80 01   line#901  CALL 1 3 2             <10>   R1@gyro = R1(R2, R3)
		  +BA6E: 0A 40 41 82   line#902  SETTABLE 0 -5 -6       <11>   R0@pos["Name"] = "EPIXPOS"                      -- It's Const#5, Const#6
		  +BA72: 86 C0 41 00   line#903  GETTABUP 2 0 -8        <12>   R2 = Upv#1@_ENV["Vector3"]                      -- It's Const#8
		  +BA76: 87 40 40 01   line#903  GETTABLE 2 2 -2        <13>   R2 = R2["new"]                                  -- It's Const#2
		  +BA7A: C6 00 42 00   line#903  GETTABUP 3 0 -9        <14>   R3 = Upv#1@_ENV["math"]                         -- It's Const#9
		  +BA7E: C7 40 C2 01   line#903  GETTABLE 3 3 -10       <15>   R3 = R3["huge"]                                 -- It's Const#10
		  +BA82: 06 01 42 00   line#903  GETTABUP 4 0 -9        <16>   R4 = Upv#1@_ENV["math"]                         -- It's Const#9
		  +BA86: 07 41 42 02   line#903  GETTABLE 4 4 -10       <17>   R4 = R4["huge"]                                 -- It's Const#10
		  +BA8A: 46 01 42 00   line#903  GETTABUP 5 0 -9        <18>   R5 = Upv#1@_ENV["math"]                         -- It's Const#9
		  +BA8E: 47 41 C2 02   line#903  GETTABLE 5 5 -10       <19>   R5 = R5["huge"]                                 -- It's Const#10
		  +BA92: A4 80 00 02   line#903  CALL 2 4 2             <20>   R2 = R2(R3, R4, R5)
		  +BA96: 0A 80 00 83   line#903  SETTABLE 0 -7 2        <21>   R0@pos["maxForce"] = R2                         -- It's Const#7
		  +BA9A: 86 C0 C2 00   line#904  GETTABUP 2 1 -12       <22>   R2 = Upv#2@torso["Position"]                    -- It's Const#12
		  +BA9E: 0A 80 00 85   line#904  SETTABLE 0 -11 2       <23>   R0@pos["position"] = R2                         -- It's Const#11
		  +BAA2: 86 C0 41 00   line#905  GETTABUP 2 0 -8        <24>   R2 = Upv#1@_ENV["Vector3"]                      -- It's Const#8
		  +BAA6: 87 40 40 01   line#905  GETTABLE 2 2 -2        <25>   R2 = R2["new"]                                  -- It's Const#2
		  +BAAA: C1 40 03 00   line#905  LOADK 3 -14            <26>   R3 = 9e+009                                     -- It's Const#14
		  +BAAE: 01 41 03 00   line#905  LOADK 4 -14            <27>   R4 = 9e+009                                     -- It's Const#14
		  +BAB2: 41 41 03 00   line#905  LOADK 5 -14            <28>   R5 = 9e+009                                     -- It's Const#14
		  +BAB6: A4 80 00 02   line#905  CALL 2 4 2             <29>   R2 = R2(R3, R4, R5)
		  +BABA: 4A 80 00 86   line#905  SETTABLE 1 -13 2       <30>   R1@gyro["maxTorque"] = R2                       -- It's Const#13
		  +BABE: 86 80 C3 00   line#906  GETTABUP 2 1 -15       <31>   R2 = Upv#2@torso["CFrame"]                      -- It's Const#15
		  +BAC2: 4A 80 00 87   line#906  SETTABLE 1 -15 2       <32>   R1@gyro["CFrame"] = R2                          -- It's Const#15
		  +BAC6: 86 C0 43 00   line#908  GETTABUP 2 0 -16       <33>   R2 = Upv#1@_ENV["wait"]                         -- It's Const#16
		  +BACA: A4 40 80 00   line#908  CALL 2 1 1             <34>   R2()
		  +BACE: 86 00 44 00   line#909  GETTABUP 2 0 -17       <35>   R2 = Upv#1@_ENV["localplayer"]                  -- It's Const#17
		  +BAD2: 87 40 44 01   line#909  GETTABLE 2 2 -18       <36>   R2 = R2["Character"]                            -- It's Const#18
		  +BAD6: 87 80 44 01   line#909  GETTABLE 2 2 -19       <37>   R2 = R2["Humanoid"]                             -- It's Const#19
		  +BADA: 8A 00 C5 89   line#909  SETTABLE 2 -20 -21     <38>   R2["PlatformStand"] = true                      -- It's Const#20, Const#21
		  +BADE: 87 80 C3 00   line#910  GETTABLE 2 1 -15       <39>   R2 = R1@gyro["CFrame"]                          -- It's Const#15
		  +BAE2: C7 80 C3 00   line#910  GETTABLE 3 1 -15       <40>   R3 = R1@gyro["CFrame"]                          -- It's Const#15
		  +BAE6: C7 40 C5 01   line#910  GETTABLE 3 3 -22       <41>   R3 = R3["p"]                                    -- It's Const#22
		  +BAEA: 8E C0 00 01   line#910  SUB 2 2 3              <42>   R2 = R2 - R3
		  +BAEE: C7 80 42 00   line#910  GETTABLE 3 0 -11       <43>   R3 = R0@pos["position"]                         -- It's Const#11
		  +BAF2: 8D C0 00 01   line#910  ADD 2 2 3              <44>   R2@new = R2 + R3
		  +BAF6: C6 80 45 01   line#911  GETTABUP 3 2 -23       <45>   R3 = Upv#3@keys["w"]                            -- It's Const#23
		  +BAFA: E2 40 00 00   line#911  TEST 3 1               <46>   if not R3 then GOTO <48>
		  +BAFE: 1E 40 02 80   line#911  JMP 0 10               <47>   GOTO <58>
		  +BB02: C6 C0 45 01   line#911  GETTABUP 3 2 -24       <48>   R3 = Upv#3@keys["s"]                            -- It's Const#24
		  +BB06: E2 40 00 00   line#911  TEST 3 1               <49>   if not R3 then GOTO <51>
		  +BB0A: 1E 80 01 80   line#911  JMP 0 7                <50>   GOTO <58>
		  +BB0E: C6 00 46 01   line#911  GETTABUP 3 2 -25       <51>   R3 = Upv#3@keys["a"]                            -- It's Const#25
		  +BB12: E2 40 00 00   line#911  TEST 3 1               <52>   if not R3 then GOTO <54>
		  +BB16: 1E C0 00 80   line#911  JMP 0 4                <53>   GOTO <58>
		  +BB1A: C6 40 46 01   line#911  GETTABUP 3 2 -26       <54>   R3 = Upv#3@keys["d"]                            -- It's Const#26
		  +BB1E: E2 40 00 00   line#911  TEST 3 1               <55>   if not R3 then GOTO <57>
		  +BB22: 1E 00 00 80   line#911  JMP 0 1                <56>   GOTO <58>
		  +BB26: 08 C0 46 8D   line#912  SETTABUP 0 -27 -28     <57>   Upv#1@_ENV["speed"] = 1                         -- It's Const#27, Const#28
		  +BB2A: C6 80 45 01   line#914  GETTABUP 3 2 -23       <58>   R3 = Upv#3@keys["w"]                            -- It's Const#23
		  +BB2E: E2 00 00 00   line#914  TEST 3 0               <59>   if R3 then GOTO <61>
		  +BB32: 1E 80 02 80   line#914  JMP 0 11               <60>   GOTO <72>
		  +BB36: C6 00 47 00   line#915  GETTABUP 3 0 -29       <61>   R3 = Upv#1@_ENV["workspace"]                    -- It's Const#29
		  +BB3A: C7 40 C7 01   line#915  GETTABLE 3 3 -30       <62>   R3 = R3["CurrentCamera"]                        -- It's Const#30
		  +BB3E: C7 80 C7 01   line#915  GETTABLE 3 3 -31       <63>   R3 = R3["CoordinateFrame"]                      -- It's Const#31
		  +BB42: C7 C0 C7 01   line#915  GETTABLE 3 3 -32       <64>   R3 = R3["lookVector"]                           -- It's Const#32
		  +BB46: 06 81 46 00   line#915  GETTABUP 4 0 -27       <65>   R4 = Upv#1@_ENV["speed"]                        -- It's Const#27
		  +BB4A: CF 00 81 01   line#915  MUL 3 3 4              <66>   R3 = R3 * R4
		  +BB4E: 8D C0 00 01   line#915  ADD 2 2 3              <67>   R2@new = R2@new + R3
		  +BB52: C6 80 46 00   line#916  GETTABUP 3 0 -27       <68>   R3 = Upv#1@_ENV["speed"]                        -- It's Const#27
		  +BB56: 05 01 80 01   line#916  GETUPVAL 4 3           <69>   R4 = Upv#4@speedSET
		  +BB5A: CD 00 81 01   line#916  ADD 3 3 4              <70>   R3 = R3 + R4
		  +BB5E: 08 C0 00 8D   line#916  SETTABUP 0 -27 3       <71>   Upv#1@_ENV["speed"] = R3                        -- It's Const#27
		  +BB62: C6 C0 45 01   line#918  GETTABUP 3 2 -24       <72>   R3 = Upv#3@keys["s"]                            -- It's Const#24
		  +BB66: E2 00 00 00   line#918  TEST 3 0               <73>   if R3 then GOTO <75>
		  +BB6A: 1E 80 02 80   line#918  JMP 0 11               <74>   GOTO <86>
		  +BB6E: C6 00 47 00   line#919  GETTABUP 3 0 -29       <75>   R3 = Upv#1@_ENV["workspace"]                    -- It's Const#29
		  +BB72: C7 40 C7 01   line#919  GETTABLE 3 3 -30       <76>   R3 = R3["CurrentCamera"]                        -- It's Const#30
		  +BB76: C7 80 C7 01   line#919  GETTABLE 3 3 -31       <77>   R3 = R3["CoordinateFrame"]                      -- It's Const#31
		  +BB7A: C7 C0 C7 01   line#919  GETTABLE 3 3 -32       <78>   R3 = R3["lookVector"]                           -- It's Const#32
		  +BB7E: 06 81 46 00   line#919  GETTABUP 4 0 -27       <79>   R4 = Upv#1@_ENV["speed"]                        -- It's Const#27
		  +BB82: CF 00 81 01   line#919  MUL 3 3 4              <80>   R3 = R3 * R4
		  +BB86: 8E C0 00 01   line#919  SUB 2 2 3              <81>   R2@new = R2@new - R3
		  +BB8A: C6 80 46 00   line#920  GETTABUP 3 0 -27       <82>   R3 = Upv#1@_ENV["speed"]                        -- It's Const#27
		  +BB8E: 05 01 80 01   line#920  GETUPVAL 4 3           <83>   R4 = Upv#4@speedSET
		  +BB92: CD 00 81 01   line#920  ADD 3 3 4              <84>   R3 = R3 + R4
		  +BB96: 08 C0 00 8D   line#920  SETTABUP 0 -27 3       <85>   Upv#1@_ENV["speed"] = R3                        -- It's Const#27
		  +BB9A: C6 40 46 01   line#922  GETTABUP 3 2 -26       <86>   R3 = Upv#3@keys["d"]                            -- It's Const#26
		  +BB9E: E2 00 00 00   line#922  TEST 3 0               <87>   if R3 then GOTO <89>
		  +BBA2: 1E 80 02 80   line#922  JMP 0 11               <88>   GOTO <100>
		  +BBA6: C6 80 43 00   line#923  GETTABUP 3 0 -15       <89>   R3 = Upv#1@_ENV["CFrame"]                       -- It's Const#15
		  +BBAA: C7 40 C0 01   line#923  GETTABLE 3 3 -2        <90>   R3 = R3["new"]                                  -- It's Const#2
		  +BBAE: 06 81 46 00   line#923  GETTABUP 4 0 -27       <91>   R4 = Upv#1@_ENV["speed"]                        -- It's Const#27
		  +BBB2: 41 01 08 00   line#923  LOADK 5 -33            <92>   R5 = 0                                          -- It's Const#33
		  +BBB6: 81 01 08 00   line#923  LOADK 6 -33            <93>   R6 = 0                                          -- It's Const#33
		  +BBBA: E4 80 00 02   line#923  CALL 3 4 2             <94>   R3 = R3(R4, R5, R6)
		  +BBBE: 8F C0 00 01   line#923  MUL 2 2 3              <95>   R2@new = R2@new * R3
		  +BBC2: C6 80 46 00   line#924  GETTABUP 3 0 -27       <96>   R3 = Upv#1@_ENV["speed"]                        -- It's Const#27
		  +BBC6: 05 01 80 01   line#924  GETUPVAL 4 3           <97>   R4 = Upv#4@speedSET
		  +BBCA: CD 00 81 01   line#924  ADD 3 3 4              <98>   R3 = R3 + R4
		  +BBCE: 08 C0 00 8D   line#924  SETTABUP 0 -27 3       <99>   Upv#1@_ENV["speed"] = R3                        -- It's Const#27
		  +BBD2: C6 00 46 01   line#926  GETTABUP 3 2 -25      <100>   R3 = Upv#3@keys["a"]                            -- It's Const#25
		  +BBD6: E2 00 00 00   line#926  TEST 3 0              <101>   if R3 then GOTO <103>
		  +BBDA: 1E C0 02 80   line#926  JMP 0 12              <102>   GOTO <115>
		  +BBDE: C6 80 43 00   line#927  GETTABUP 3 0 -15      <103>   R3 = Upv#1@_ENV["CFrame"]                       -- It's Const#15
		  +BBE2: C7 40 C0 01   line#927  GETTABLE 3 3 -2       <104>   R3 = R3["new"]                                  -- It's Const#2
		  +BBE6: 06 81 46 00   line#927  GETTABUP 4 0 -27      <105>   R4 = Upv#1@_ENV["speed"]                        -- It's Const#27
		  +BBEA: 19 01 00 02   line#927  UNM 4 4               <106>   R4 = - R4
		  +BBEE: 41 01 08 00   line#927  LOADK 5 -33           <107>   R5 = 0                                          -- It's Const#33
		  +BBF2: 81 01 08 00   line#927  LOADK 6 -33           <108>   R6 = 0                                          -- It's Const#33
		  +BBF6: E4 80 00 02   line#927  CALL 3 4 2            <109>   R3 = R3(R4, R5, R6)
		  +BBFA: 8F C0 00 01   line#927  MUL 2 2 3             <110>   R2@new = R2@new * R3
		  +BBFE: C6 80 46 00   line#928  GETTABUP 3 0 -27      <111>   R3 = Upv#1@_ENV["speed"]                        -- It's Const#27
		  +BC02: 05 01 80 01   line#928  GETUPVAL 4 3          <112>   R4 = Upv#4@speedSET
		  +BC06: CD 00 81 01   line#928  ADD 3 3 4             <113>   R3 = R3 + R4
		  +BC0A: 08 C0 00 8D   line#928  SETTABUP 0 -27 3      <114>   Upv#1@_ENV["speed"] = R3                        -- It's Const#27
		  +BC0E: C6 80 46 00   line#930  GETTABUP 3 0 -27      <115>   R3 = Upv#1@_ENV["speed"]                        -- It's Const#27
		  +BC12: 05 01 80 01   line#930  GETUPVAL 4 3          <116>   R4 = Upv#4@speedSET
		  +BC16: 20 C0 00 02   line#930  LT 0 4 3              <117>   if R4 < R3 then GOTO <119>
		  +BC1A: 1E 40 00 80   line#930  JMP 0 2               <118>   GOTO <121>
		  +BC1E: C5 00 80 01   line#931  GETUPVAL 3 3          <119>   R3 = Upv#4@speedSET
		  +BC22: 08 C0 00 8D   line#931  SETTABUP 0 -27 3      <120>   Upv#1@_ENV["speed"] = R3                        -- It's Const#27
		  +BC26: C7 40 45 01   line#933  GETTABLE 3 2 -22      <121>   R3 = R2@new["p"]                                -- It's Const#22
		  +BC2A: 0A C0 00 85   line#933  SETTABLE 0 -11 3      <122>   R0@pos["position"] = R3                         -- It's Const#11
		  +BC2E: C6 80 45 01   line#934  GETTABUP 3 2 -23      <123>   R3 = Upv#3@keys["w"]                            -- It's Const#23
		  +BC32: E2 00 00 00   line#934  TEST 3 0              <124>   if R3 then GOTO <126>
		  +BC36: 1E 00 04 80   line#934  JMP 0 17              <125>   GOTO <143>
		  +BC3A: C6 00 47 00   line#935  GETTABUP 3 0 -29      <126>   R3 = Upv#1@_ENV["workspace"]                    -- It's Const#29
		  +BC3E: C7 40 C7 01   line#935  GETTABLE 3 3 -30      <127>   R3 = R3["CurrentCamera"]                        -- It's Const#30
		  +BC42: C7 80 C7 01   line#935  GETTABLE 3 3 -31      <128>   R3 = R3["CoordinateFrame"]                      -- It's Const#31
		  +BC46: 06 81 43 00   line#935  GETTABUP 4 0 -15      <129>   R4 = Upv#1@_ENV["CFrame"]                       -- It's Const#15
		  +BC4A: 07 41 48 02   line#935  GETTABLE 4 4 -34      <130>   R4 = R4["Angles"]                               -- It's Const#34
		  +BC4E: 46 01 42 00   line#935  GETTABUP 5 0 -9       <131>   R5 = Upv#1@_ENV["math"]                         -- It's Const#9
		  +BC52: 47 81 C8 02   line#935  GETTABLE 5 5 -35      <132>   R5 = R5["rad"]                                  -- It's Const#35
		  +BC56: 86 81 46 00   line#935  GETTABUP 6 0 -27      <133>   R6 = Upv#1@_ENV["speed"]                        -- It's Const#27
		  +BC5A: 8F C1 48 03   line#935  MUL 6 6 -36           <134>   R6 = R6 * 15                                    -- It's Const#36
		  +BC5E: 64 81 00 01   line#935  CALL 5 2 2            <135>   R5 = R5(R6)
		  +BC62: 59 01 80 02   line#935  UNM 5 5               <136>   R5 = - R5
		  +BC66: 81 01 08 00   line#935  LOADK 6 -33           <137>   R6 = 0                                          -- It's Const#33
		  +BC6A: C1 01 08 00   line#935  LOADK 7 -33           <138>   R7 = 0                                          -- It's Const#33
		  +BC6E: 24 81 00 02   line#935  CALL 4 4 2            <139>   R4 = R4(R5, R6, R7)
		  +BC72: CF 00 81 01   line#935  MUL 3 3 4             <140>   R3 = R3 * R4
		  +BC76: 4A C0 00 87   line#935  SETTABLE 1 -15 3      <141>   R1@gyro["CFrame"] = R3                          -- It's Const#15
		  +BC7A: 1E 80 05 80   line#935  JMP 0 23              <142>   GOTO <166>
		  +BC7E: C6 C0 45 01   line#936  GETTABUP 3 2 -24      <143>   R3 = Upv#3@keys["s"]                            -- It's Const#24
		  +BC82: E2 00 00 00   line#936  TEST 3 0              <144>   if R3 then GOTO <146>
		  +BC86: 1E C0 03 80   line#936  JMP 0 16              <145>   GOTO <162>
		  +BC8A: C6 00 47 00   line#937  GETTABUP 3 0 -29      <146>   R3 = Upv#1@_ENV["workspace"]                    -- It's Const#29
		  +BC8E: C7 40 C7 01   line#937  GETTABLE 3 3 -30      <147>   R3 = R3["CurrentCamera"]                        -- It's Const#30
		  +BC92: C7 80 C7 01   line#937  GETTABLE 3 3 -31      <148>   R3 = R3["CoordinateFrame"]                      -- It's Const#31
		  +BC96: 06 81 43 00   line#937  GETTABUP 4 0 -15      <149>   R4 = Upv#1@_ENV["CFrame"]                       -- It's Const#15
		  +BC9A: 07 41 48 02   line#937  GETTABLE 4 4 -34      <150>   R4 = R4["Angles"]                               -- It's Const#34
		  +BC9E: 46 01 42 00   line#937  GETTABUP 5 0 -9       <151>   R5 = Upv#1@_ENV["math"]                         -- It's Const#9
		  +BCA2: 47 81 C8 02   line#937  GETTABLE 5 5 -35      <152>   R5 = R5["rad"]                                  -- It's Const#35
		  +BCA6: 86 81 46 00   line#937  GETTABUP 6 0 -27      <153>   R6 = Upv#1@_ENV["speed"]                        -- It's Const#27
		  +BCAA: 8F C1 48 03   line#937  MUL 6 6 -36           <154>   R6 = R6 * 15                                    -- It's Const#36
		  +BCAE: 64 81 00 01   line#937  CALL 5 2 2            <155>   R5 = R5(R6)
		  +BCB2: 81 01 08 00   line#937  LOADK 6 -33           <156>   R6 = 0                                          -- It's Const#33
		  +BCB6: C1 01 08 00   line#937  LOADK 7 -33           <157>   R7 = 0                                          -- It's Const#33
		  +BCBA: 24 81 00 02   line#937  CALL 4 4 2            <158>   R4 = R4(R5, R6, R7)
		  +BCBE: CF 00 81 01   line#937  MUL 3 3 4             <159>   R3 = R3 * R4
		  +BCC2: 4A C0 00 87   line#937  SETTABLE 1 -15 3      <160>   R1@gyro["CFrame"] = R3                          -- It's Const#15
		  +BCC6: 1E C0 00 80   line#937  JMP 0 4               <161>   GOTO <166>
		  +BCCA: C6 00 47 00   line#939  GETTABUP 3 0 -29      <162>   R3 = Upv#1@_ENV["workspace"]                    -- It's Const#29
		  +BCCE: C7 40 C7 01   line#939  GETTABLE 3 3 -30      <163>   R3 = R3["CurrentCamera"]                        -- It's Const#30
		  +BCD2: C7 80 C7 01   line#939  GETTABLE 3 3 -31      <164>   R3 = R3["CoordinateFrame"]                      -- It's Const#31
		  +BCD6: 4A C0 00 87   line#939  SETTABLE 1 -15 3      <165>   R1@gyro["CFrame"] = R3                          -- It's Const#15
		  +BCDA: C6 00 49 00   line#941  GETTABUP 3 0 -37      <166>   R3 = Upv#1@_ENV["Fly"]                          -- It's Const#37
		  +BCDE: E2 40 00 00   line#941  TEST 3 1              <167>   if not R3 then GOTO <169>
		  +BCE2: 1E C0 DD 7F   line#941  JMP 0 -136            <168>   GOTO <33>
		  +BCE6: 62 00 00 00   line#942  TEST 1 0              <169>   if R1@gyro then GOTO <171>
		  +BCEA: 1E 40 00 80   line#942  JMP 0 2               <170>   GOTO <173>
		  +BCEE: 8C 40 C9 00   line#943  SELF 2 1 -38          <171>   R3 = R1@gyro;  R2 = R1@gyro["Destroy"]          -- It's Const#38   -- prepare for R1@gyro:Destroy()
		  +BCF2: A4 40 00 01   line#943  CALL 2 2 1            <172>   R2(R3)
		  +BCF6: 22 00 00 00   line#945  TEST 0 0              <173>   if R0@pos then GOTO <175>
		  +BCFA: 1E 40 00 80   line#945  JMP 0 2               <174>   GOTO <177>
		  +BCFE: 8C 40 49 00   line#946  SELF 2 0 -38          <175>   R3 = R0@pos;  R2 = R0@pos["Destroy"]            -- It's Const#38   -- prepare for R0@pos:Destroy()
		  +BD02: A4 40 00 01   line#946  CALL 2 2 1            <176>   R2(R3)
		  +BD06: 08 C0 49 93   line#948  SETTABUP 0 -39 -40    <177>   Upv#1@_ENV["flying"] = false                    -- It's Const#39, Const#40
		  +BD0A: 86 00 44 00   line#949  GETTABUP 2 0 -17      <178>   R2 = Upv#1@_ENV["localplayer"]                  -- It's Const#17
		  +BD0E: 87 40 44 01   line#949  GETTABLE 2 2 -18      <179>   R2 = R2["Character"]                            -- It's Const#18
		  +BD12: 87 80 44 01   line#949  GETTABLE 2 2 -19      <180>   R2 = R2["Humanoid"]                             -- It's Const#19
		  +BD16: 8A C0 C9 89   line#949  SETTABLE 2 -20 -40    <181>   R2["PlatformStand"] = false                     -- It's Const#20, Const#40
		  +BD1A: 08 00 48 8D   line#950  SETTABUP 0 -27 -33    <182>   Upv#1@_ENV["speed"] = 0                         -- It's Const#27, Const#33
		  +BD1E: 26 00 80 00   line#951  RETURN 0 1            <183>   RETURN
		Functions: 0

		************ Function#2   (full path: main.14.2)
		Source line#: 952..965
		Parameters: 1
		Is vararg: no
		VM registers needed: 3
		Constants: 9
		  +C229:Size=6: 50 61 72 65 6E 74               Const#1   string    "Parent"
		  +C231:Size=6: 66 6C 79 69 6E 67               Const#2   string    "flying"
		  +C238:Size=1: 00                              Const#3   boolean   false
		  +C23B:Size=A: 64 69 73 63 6F 6E 6E 65 63 74   Const#4   string    "disconnect"
		  +C247:Size=1: 77                              Const#5   string    "w"
		  +C249:Size=1: 01                              Const#6   boolean   true
		  +C24C:Size=1: 73                              Const#7   string    "s"
		  +C24F:Size=1: 61                              Const#8   string    "a"
		  +C252:Size=1: 64                              Const#9   string    "d"
		Upvalues: 5
		  Upv#1 is parent function's R1                 name: torso
		  Upv#2 is parent function's Upv#1              name: _ENV
		  Upv#3 is parent function's R4                 name: e1
		  Upv#4 is parent function's R5                 name: e2
		  Upv#5 is parent function's R3                 name: keys
		Locals: 1
		  Local#1   R0   parameter  scope:<1..30>       name: key
		Instructions: 30
		  +C1AB: 45 00 00 00   line#953  GETUPVAL 1 0            <1>   R1 = Upv#1@torso
		  +C1AF: 62 00 00 00   line#953  TEST 1 0                <2>   if R1 then GOTO <4>
		  +C1B3: 1E 80 00 80   line#953  JMP 0 3                 <3>   GOTO <7>
		  +C1B7: 46 00 40 00   line#953  GETTABUP 1 0 -1         <4>   R1 = Upv#1@torso["Parent"]                      -- It's Const#1
		  +C1BB: 62 40 00 00   line#953  TEST 1 1                <5>   if not R1 then GOTO <7>
		  +C1BF: 1E C0 01 80   line#953  JMP 0 8                 <6>   GOTO <15>
		  +C1C3: 48 80 C0 80   line#954  SETTABUP 1 -2 -3        <7>   Upv#2@_ENV["flying"] = false                    -- It's Const#2, Const#3
		  +C1C7: 45 00 00 01   line#954  GETUPVAL 1 2            <8>   R1 = Upv#3@e1
		  +C1CB: 4C C0 C0 00   line#954  SELF 1 1 -4             <9>   R2 = R1;  R1 = R1["disconnect"]                 -- It's Const#4   -- prepare for R1:disconnect()
		  +C1CF: 64 40 00 01   line#954  CALL 1 2 1             <10>   R1(R2)
		  +C1D3: 45 00 80 01   line#954  GETUPVAL 1 3           <11>   R1 = Upv#4@e2
		  +C1D7: 4C C0 C0 00   line#954  SELF 1 1 -4            <12>   R2 = R1;  R1 = R1["disconnect"]                 -- It's Const#4   -- prepare for R1:disconnect()
		  +C1DB: 64 40 00 01   line#954  CALL 1 2 1             <13>   R1(R2)
		  +C1DF: 26 00 80 00   line#954  RETURN 0 1             <14>   RETURN
		  +C1E3: 1F 00 41 00   line#956  EQ 0 0 -5              <15>   if R0@key == "w" then GOTO <17>                 -- It's Const#5
		  +C1E7: 1E 40 00 80   line#956  JMP 0 2                <16>   GOTO <19>
		  +C1EB: 08 41 41 82   line#957  SETTABUP 4 -5 -6       <17>   Upv#5@keys["w"] = true                          -- It's Const#5, Const#6
		  +C1EF: 1E 80 02 80   line#957  JMP 0 11               <18>   GOTO <30>
		  +C1F3: 1F 80 41 00   line#958  EQ 0 0 -7              <19>   if R0@key == "s" then GOTO <21>                 -- It's Const#7
		  +C1F7: 1E 40 00 80   line#958  JMP 0 2                <20>   GOTO <23>
		  +C1FB: 08 41 41 83   line#959  SETTABUP 4 -7 -6       <21>   Upv#5@keys["s"] = true                          -- It's Const#7, Const#6
		  +C1FF: 1E 80 01 80   line#959  JMP 0 7                <22>   GOTO <30>
		  +C203: 1F C0 41 00   line#960  EQ 0 0 -8              <23>   if R0@key == "a" then GOTO <25>                 -- It's Const#8
		  +C207: 1E 40 00 80   line#960  JMP 0 2                <24>   GOTO <27>
		  +C20B: 08 41 C1 83   line#961  SETTABUP 4 -8 -6       <25>   Upv#5@keys["a"] = true                          -- It's Const#8, Const#6
		  +C20F: 1E 80 00 80   line#961  JMP 0 3                <26>   GOTO <30>
		  +C213: 1F 00 42 00   line#962  EQ 0 0 -9              <27>   if R0@key == "d" then GOTO <29>                 -- It's Const#9
		  +C217: 1E 00 00 80   line#962  JMP 0 1                <28>   GOTO <30>
		  +C21B: 08 41 41 84   line#963  SETTABUP 4 -9 -6       <29>   Upv#5@keys["d"] = true                          -- It's Const#9, Const#6
		  +C21F: 26 00 80 00   line#965  RETURN 0 1             <30>   RETURN
		Functions: 0

		************ Function#3   (full path: main.14.3)
		Source line#: 966..976
		Parameters: 1
		Is vararg: no
		VM registers needed: 2
		Constants: 5
		  +C361:Size=1: 77                              Const#1   string    "w"
		  +C363:Size=1: 00                              Const#2   boolean   false
		  +C366:Size=1: 73                              Const#3   string    "s"
		  +C369:Size=1: 61                              Const#4   string    "a"
		  +C36C:Size=1: 64                              Const#5   string    "d"
		Upvalues: 1
		  Upv#1 is parent function's R3                 name: keys
		Locals: 1
		  Local#1   R0   parameter  scope:<1..16>       name: key
		Instructions: 16
		  +C31B: 1F 00 40 00   line#967  EQ 0 0 -1               <1>   if R0@key == "w" then GOTO <3>                  -- It's Const#1
		  +C31F: 1E 40 00 80   line#967  JMP 0 2                 <2>   GOTO <5>
		  +C323: 08 40 40 80   line#968  SETTABUP 0 -1 -2        <3>   Upv#1@keys["w"] = false                         -- It's Const#1, Const#2
		  +C327: 1E 80 02 80   line#968  JMP 0 11                <4>   GOTO <16>
		  +C32B: 1F 80 40 00   line#969  EQ 0 0 -3               <5>   if R0@key == "s" then GOTO <7>                  -- It's Const#3
		  +C32F: 1E 40 00 80   line#969  JMP 0 2                 <6>   GOTO <9>
		  +C333: 08 40 40 81   line#970  SETTABUP 0 -3 -2        <7>   Upv#1@keys["s"] = false                         -- It's Const#3, Const#2
		  +C337: 1E 80 01 80   line#970  JMP 0 7                 <8>   GOTO <16>
		  +C33B: 1F C0 40 00   line#971  EQ 0 0 -4               <9>   if R0@key == "a" then GOTO <11>                 -- It's Const#4
		  +C33F: 1E 40 00 80   line#971  JMP 0 2                <10>   GOTO <13>
		  +C343: 08 40 C0 81   line#972  SETTABUP 0 -4 -2       <11>   Upv#1@keys["a"] = false                         -- It's Const#4, Const#2
		  +C347: 1E 80 00 80   line#972  JMP 0 3                <12>   GOTO <16>
		  +C34B: 1F 00 41 00   line#973  EQ 0 0 -5              <13>   if R0@key == "d" then GOTO <15>                 -- It's Const#5
		  +C34F: 1E 00 00 80   line#973  JMP 0 1                <14>   GOTO <16>
		  +C353: 08 40 40 82   line#974  SETTABUP 0 -5 -2       <15>   Upv#1@keys["d"] = false                         -- It's Const#5, Const#2
		  +C357: 26 00 80 00   line#976  RETURN 0 1             <16>   RETURN
		Functions: 0

	************ Function#15   (full path: main.15)
	Source line#: 980..983
	Parameters: 0
	Is vararg: no
	VM registers needed: 5
	Constants: 9
	  +C56D:Size=4: 67 61 6D 65                     Const#1   string    "game"
	  +C573:Size=A: 47 65 74 53 65 72 76 69 63 65   Const#2   string    "GetService"
	  +C57F:Size=B: 56 69 72 74 75 61 6C 55 73...   Const#3   string    "VirtualUser"
	  +C58C:Size=11: 43 61 70 74 75 72 65 43 6...   Const#4   string    "CaptureController"
	  +C59F:Size=B: 42 75 74 74 6F 6E 31 44 6F...   Const#5   string    "Button1Down"
	  +C5AC:Size=7: 56 65 63 74 6F 72 32            Const#6   string    "Vector2"
	  +C5B5:Size=3: 6E 65 77                        Const#7   string    "new"
	  +C5B9:Size=4: 00 05 00 00                     Const#8   integer   1280
	  +C5BE:Size=4: A0 02 00 00                     Const#9   integer   672
	Upvalues: 1
	  Upv#1 is parent function's Upv#1              name: _ENV
	Instructions: 18
	  +C51F: 06 00 40 00   line#981  GETTABUP 0 0 -1         <1>   R0 = Upv#1@_ENV["game"]                         -- It's Const#1
	  +C523: 0C 40 40 00   line#981  SELF 0 0 -2             <2>   R1 = R0;  R0 = R0["GetService"]                 -- It's Const#2   -- prepare for R0:GetService()
	  +C527: 81 80 00 00   line#981  LOADK 2 -3              <3>   R2 = "VirtualUser"                              -- It's Const#3
	  +C52B: 24 80 80 01   line#981  CALL 0 3 2              <4>   R0 = R0(R1, R2)
	  +C52F: 0C C0 40 00   line#981  SELF 0 0 -4             <5>   R1 = R0;  R0 = R0["CaptureController"]          -- It's Const#4   -- prepare for R0:CaptureController()
	  +C533: 24 40 00 01   line#981  CALL 0 2 1              <6>   R0(R1)
	  +C537: 06 00 40 00   line#982  GETTABUP 0 0 -1         <7>   R0 = Upv#1@_ENV["game"]                         -- It's Const#1
	  +C53B: 0C 40 40 00   line#982  SELF 0 0 -2             <8>   R1 = R0;  R0 = R0["GetService"]                 -- It's Const#2   -- prepare for R0:GetService()
	  +C53F: 81 80 00 00   line#982  LOADK 2 -3              <9>   R2 = "VirtualUser"                              -- It's Const#3
	  +C543: 24 80 80 01   line#982  CALL 0 3 2             <10>   R0 = R0(R1, R2)
	  +C547: 0C 00 41 00   line#982  SELF 0 0 -5            <11>   R1 = R0;  R0 = R0["Button1Down"]                -- It's Const#5   -- prepare for R0:Button1Down()
	  +C54B: 86 40 41 00   line#982  GETTABUP 2 0 -6        <12>   R2 = Upv#1@_ENV["Vector2"]                      -- It's Const#6
	  +C54F: 87 80 41 01   line#982  GETTABLE 2 2 -7        <13>   R2 = R2["new"]                                  -- It's Const#7
	  +C553: C1 C0 01 00   line#982  LOADK 3 -8             <14>   R3 = 1280                                       -- It's Const#8
	  +C557: 01 01 02 00   line#982  LOADK 4 -9             <15>   R4 = 672                                        -- It's Const#9
	  +C55B: A4 00 80 01   line#982  CALL 2 3 0             <16>   R2,.. = R2(R3, R4)
	  +C55F: 24 40 00 00   line#982  CALL 0 0 1             <17>   R0(R1,..)
	  +C563: 26 00 80 00   line#983  RETURN 0 1             <18>   RETURN
	Functions: 0

	************ Function#16   (full path: main.16)
	Source line#: 985..989
	Parameters: 0
	Is vararg: no
	VM registers needed: 3
	Constants: 12
	  +C68F:Size=4: 67 61 6D 65                     Const#1   string    "game"
	  +C695:Size=A: 47 65 74 53 65 72 76 69 63 65   Const#2   string    "GetService"
	  +C6A1:Size=7: 50 6C 61 79 65 72 73            Const#3   string    "Players"
	  +C6AA:Size=B: 4C 6F 63 61 6C 50 6C 61 79...   Const#4   string    "LocalPlayer"
	  +C6B7:Size=9: 43 68 61 72 61 63 74 65 72      Const#5   string    "Character"
	  +C6C2:Size=E: 46 69 6E 64 46 69 72 73 74...   Const#6   string    "FindFirstChild"
	  +C6D2:Size=7: 48 61 73 42 75 73 6F            Const#7   string    "HasBuso"
	  +C6DB:Size=11: 52 65 70 6C 69 63 61 74 6...   Const#8   string    "ReplicatedStorage"
	  +C6EE:Size=7: 52 65 6D 6F 74 65 73            Const#9   string    "Remotes"
	  +C6F7:Size=6: 43 6F 6D 6D 46 5F               Const#10  string    "CommF_"
	  +C6FF:Size=C: 49 6E 76 6F 6B 65 53 65 72...   Const#11  string    "InvokeServer"
	  +C70D:Size=4: 42 75 73 6F                     Const#12  string    "Buso"
	Upvalues: 1
	  Upv#1 is parent function's Upv#1              name: _ENV
	Instructions: 21
	  +C635: 06 00 40 00   line#986  GETTABUP 0 0 -1         <1>   R0 = Upv#1@_ENV["game"]                         -- It's Const#1
	  +C639: 0C 40 40 00   line#986  SELF 0 0 -2             <2>   R1 = R0;  R0 = R0["GetService"]                 -- It's Const#2   -- prepare for R0:GetService()
	  +C63D: 81 80 00 00   line#986  LOADK 2 -3              <3>   R2 = "Players"                                  -- It's Const#3
	  +C641: 24 80 80 01   line#986  CALL 0 3 2              <4>   R0 = R0(R1, R2)
	  +C645: 07 C0 40 00   line#986  GETTABLE 0 0 -4         <5>   R0 = R0["LocalPlayer"]                          -- It's Const#4
	  +C649: 07 00 41 00   line#986  GETTABLE 0 0 -5         <6>   R0 = R0["Character"]                            -- It's Const#5
	  +C64D: 0C 40 41 00   line#986  SELF 0 0 -6             <7>   R1 = R0;  R0 = R0["FindFirstChild"]             -- It's Const#6   -- prepare for R0:FindFirstChild()
	  +C651: 81 80 01 00   line#986  LOADK 2 -7              <8>   R2 = "HasBuso"                                  -- It's Const#7
	  +C655: 24 80 80 01   line#986  CALL 0 3 2              <9>   R0 = R0(R1, R2)
	  +C659: 22 40 00 00   line#986  TEST 0 1               <10>   if not R0 then GOTO <12>
	  +C65D: 1E 00 02 80   line#986  JMP 0 9                <11>   GOTO <21>
	  +C661: 06 00 40 00   line#987  GETTABUP 0 0 -1        <12>   R0 = Upv#1@_ENV["game"]                         -- It's Const#1
	  +C665: 0C 40 40 00   line#987  SELF 0 0 -2            <13>   R1 = R0;  R0 = R0["GetService"]                 -- It's Const#2   -- prepare for R0:GetService()
	  +C669: 81 C0 01 00   line#987  LOADK 2 -8             <14>   R2 = "ReplicatedStorage"                        -- It's Const#8
	  +C66D: 24 80 80 01   line#987  CALL 0 3 2             <15>   R0 = R0(R1, R2)
	  +C671: 07 00 42 00   line#987  GETTABLE 0 0 -9        <16>   R0 = R0["Remotes"]                              -- It's Const#9
	  +C675: 07 40 42 00   line#987  GETTABLE 0 0 -10       <17>   R0 = R0["CommF_"]                               -- It's Const#10
	  +C679: 0C 80 42 00   line#987  SELF 0 0 -11           <18>   R1 = R0;  R0 = R0["InvokeServer"]               -- It's Const#11   -- prepare for R0:InvokeServer()
	  +C67D: 81 C0 02 00   line#987  LOADK 2 -12            <19>   R2 = "Buso"                                     -- It's Const#12
	  +C681: 24 40 80 01   line#987  CALL 0 3 1             <20>   R0(R1, R2)
	  +C685: 26 00 80 00   line#989  RETURN 0 1             <21>   RETURN
	Functions: 0

	************ Function#17   (full path: main.17)
	Source line#: 991..999
	Parameters: 1
	Is vararg: no
	VM registers needed: 4
	Constants: 14
	  +C816:Size=4: 67 61 6D 65                     Const#1   string    "game"
	  +C81C:Size=7: 50 6C 61 79 65 72 73            Const#2   string    "Players"
	  +C825:Size=B: 4C 6F 63 61 6C 50 6C 61 79...   Const#3   string    "LocalPlayer"
	  +C832:Size=9: 43 68 61 72 61 63 74 65 72      Const#4   string    "Character"
	  +C83D:Size=E: 46 69 6E 64 46 69 72 73 74...   Const#5   string    "FindFirstChild"
	  +C84D:Size=2: 5F 47                           Const#6   string    "_G"
	  +C851:Size=C: 4E 6F 74 41 75 74 6F 45 71...   Const#7   string    "NotAutoEquip"
	  +C85E:Size=1: 01                              Const#8   boolean   true
	  +C861:Size=4: 77 61 69 74                     Const#9   string    "wait"
	  +C866:Size=8: 00 00 00 00 00 00 E0 3F         Const#10  float     0.5
	  +C870:Size=6: 50 61 72 65 6E 74               Const#11  string    "Parent"
	  +C878:Size=8: 42 61 63 6B 70 61 63 6B         Const#12  string    "Backpack"
	  +C881:Size=8: 9A 99 99 99 99 99 B9 3F         Const#13  float     0.1
	  +C88A:Size=1: 00                              Const#14  boolean   false
	Upvalues: 1
	  Upv#1 is parent function's Upv#1              name: _ENV
	Locals: 1
	  Local#1   R0   parameter  scope:<1..32>       name: Weapon
	Instructions: 32
	  +C790: 46 00 40 00   line#992  GETTABUP 1 0 -1         <1>   R1 = Upv#1@_ENV["game"]                         -- It's Const#1
	  +C794: 47 40 C0 00   line#992  GETTABLE 1 1 -2         <2>   R1 = R1["Players"]                              -- It's Const#2
	  +C798: 47 80 C0 00   line#992  GETTABLE 1 1 -3         <3>   R1 = R1["LocalPlayer"]                          -- It's Const#3
	  +C79C: 47 C0 C0 00   line#992  GETTABLE 1 1 -4         <4>   R1 = R1["Character"]                            -- It's Const#4
	  +C7A0: 4C 00 C1 00   line#992  SELF 1 1 -5             <5>   R2 = R1;  R1 = R1["FindFirstChild"]             -- It's Const#5   -- prepare for R1:FindFirstChild()
	  +C7A4: C0 00 00 00   line#992  MOVE 3 0                <6>   R3 = R0@Weapon
	  +C7A8: 64 80 80 01   line#992  CALL 1 3 2              <7>   R1 = R1(R2, R3)
	  +C7AC: 62 00 00 00   line#992  TEST 1 0                <8>   if R1 then GOTO <10>
	  +C7B0: 1E 40 05 80   line#992  JMP 0 22                <9>   GOTO <32>
	  +C7B4: 46 40 41 00   line#993  GETTABUP 1 0 -6        <10>   R1 = Upv#1@_ENV["_G"]                           -- It's Const#6
	  +C7B8: 4A C0 41 83   line#993  SETTABLE 1 -7 -8       <11>   R1["NotAutoEquip"] = true                       -- It's Const#7, Const#8
	  +C7BC: 46 00 42 00   line#994  GETTABUP 1 0 -9        <12>   R1 = Upv#1@_ENV["wait"]                         -- It's Const#9
	  +C7C0: 81 40 02 00   line#994  LOADK 2 -10            <13>   R2 = 0.5                                        -- It's Const#10
	  +C7C4: 64 40 00 01   line#994  CALL 1 2 1             <14>   R1(R2)
	  +C7C8: 46 00 40 00   line#995  GETTABUP 1 0 -1        <15>   R1 = Upv#1@_ENV["game"]                         -- It's Const#1
	  +C7CC: 47 40 C0 00   line#995  GETTABLE 1 1 -2        <16>   R1 = R1["Players"]                              -- It's Const#2
	  +C7D0: 47 80 C0 00   line#995  GETTABLE 1 1 -3        <17>   R1 = R1["LocalPlayer"]                          -- It's Const#3
	  +C7D4: 47 C0 C0 00   line#995  GETTABLE 1 1 -4        <18>   R1 = R1["Character"]                            -- It's Const#4
	  +C7D8: 4C 00 C1 00   line#995  SELF 1 1 -5            <19>   R2 = R1;  R1 = R1["FindFirstChild"]             -- It's Const#5   -- prepare for R1:FindFirstChild()
	  +C7DC: C0 00 00 00   line#995  MOVE 3 0               <20>   R3 = R0@Weapon
	  +C7E0: 64 80 80 01   line#995  CALL 1 3 2             <21>   R1 = R1(R2, R3)
	  +C7E4: 86 00 40 00   line#995  GETTABUP 2 0 -1        <22>   R2 = Upv#1@_ENV["game"]                         -- It's Const#1
	  +C7E8: 87 40 40 01   line#995  GETTABLE 2 2 -2        <23>   R2 = R2["Players"]                              -- It's Const#2
	  +C7EC: 87 80 40 01   line#995  GETTABLE 2 2 -3        <24>   R2 = R2["LocalPlayer"]                          -- It's Const#3
	  +C7F0: 87 C0 42 01   line#995  GETTABLE 2 2 -12       <25>   R2 = R2["Backpack"]                             -- It's Const#12
	  +C7F4: 4A 80 00 85   line#995  SETTABLE 1 -11 2       <26>   R1["Parent"] = R2                               -- It's Const#11
	  +C7F8: 46 00 42 00   line#996  GETTABUP 1 0 -9        <27>   R1 = Upv#1@_ENV["wait"]                         -- It's Const#9
	  +C7FC: 81 00 03 00   line#996  LOADK 2 -13            <28>   R2 = 0.1                                        -- It's Const#13
	  +C800: 64 40 00 01   line#996  CALL 1 2 1             <29>   R1(R2)
	  +C804: 46 40 41 00   line#997  GETTABUP 1 0 -6        <30>   R1 = Upv#1@_ENV["_G"]                           -- It's Const#6
	  +C808: 4A 40 43 83   line#997  SETTABLE 1 -7 -14      <31>   R1["NotAutoEquip"] = false                      -- It's Const#7, Const#14
	  +C80C: 26 00 80 00   line#999  RETURN 0 1             <32>   RETURN
	Functions: 0

	************ Function#18   (full path: main.18)
	Source line#: 1001..1009
	Parameters: 1
	Is vararg: no
	VM registers needed: 4
	Constants: 13
	  +C9CF:Size=2: 5F 47                           Const#1   string    "_G"
	  +C9D3:Size=C: 4E 6F 74 41 75 74 6F 45 71...   Const#2   string    "NotAutoEquip"
	  +C9E1:Size=4: 67 61 6D 65                     Const#3   string    "game"
	  +C9E7:Size=7: 50 6C 61 79 65 72 73            Const#4   string    "Players"
	  +C9F0:Size=B: 4C 6F 63 61 6C 50 6C 61 79...   Const#5   string    "LocalPlayer"
	  +C9FD:Size=8: 42 61 63 6B 70 61 63 6B         Const#6   string    "Backpack"
	  +CA07:Size=E: 46 69 6E 64 46 69 72 73 74...   Const#7   string    "FindFirstChild"
	  +CA17:Size=4: 54 6F 6F 6C                     Const#8   string    "Tool"
	  +CA1D:Size=4: 77 61 69 74                     Const#9   string    "wait"
	  +CA22:Size=8: 9A 99 99 99 99 99 B9 3F         Const#10  float     0.1
	  +CA2C:Size=9: 43 68 61 72 61 63 74 65 72      Const#11  string    "Character"
	  +CA37:Size=8: 48 75 6D 61 6E 6F 69 64         Const#12  string    "Humanoid"
	  +CA41:Size=9: 45 71 75 69 70 54 6F 6F 6C      Const#13  string    "EquipTool"
	Upvalues: 1
	  Upv#1 is parent function's Upv#1              name: _ENV
	Locals: 1
	  Local#1   R0   parameter  scope:<1..33>       name: ToolSe
	Instructions: 33
	  +C945: 46 00 40 00   line#1002 GETTABUP 1 0 -1         <1>   R1 = Upv#1@_ENV["_G"]                           -- It's Const#1
	  +C949: 47 40 C0 00   line#1002 GETTABLE 1 1 -2         <2>   R1 = R1["NotAutoEquip"]                         -- It's Const#2
	  +C94D: 62 40 00 00   line#1002 TEST 1 1                <3>   if not R1 then GOTO <5>
	  +C951: 1E C0 06 80   line#1002 JMP 0 28                <4>   GOTO <33>
	  +C955: 46 80 40 00   line#1003 GETTABUP 1 0 -3         <5>   R1 = Upv#1@_ENV["game"]                         -- It's Const#3
	  +C959: 47 C0 C0 00   line#1003 GETTABLE 1 1 -4         <6>   R1 = R1["Players"]                              -- It's Const#4
	  +C95D: 47 00 C1 00   line#1003 GETTABLE 1 1 -5         <7>   R1 = R1["LocalPlayer"]                          -- It's Const#5
	  +C961: 47 40 C1 00   line#1003 GETTABLE 1 1 -6         <8>   R1 = R1["Backpack"]                             -- It's Const#6
	  +C965: 4C 80 C1 00   line#1003 SELF 1 1 -7             <9>   R2 = R1;  R1 = R1["FindFirstChild"]             -- It's Const#7   -- prepare for R1:FindFirstChild()
	  +C969: C0 00 00 00   line#1003 MOVE 3 0               <10>   R3 = R0@ToolSe
	  +C96D: 64 80 80 01   line#1003 CALL 1 3 2             <11>   R1 = R1(R2, R3)
	  +C971: 62 00 00 00   line#1003 TEST 1 0               <12>   if R1 then GOTO <14>
	  +C975: 1E 80 04 80   line#1003 JMP 0 19               <13>   GOTO <33>
	  +C979: 46 80 40 00   line#1004 GETTABUP 1 0 -3        <14>   R1 = Upv#1@_ENV["game"]                         -- It's Const#3
	  +C97D: 47 C0 C0 00   line#1004 GETTABLE 1 1 -4        <15>   R1 = R1["Players"]                              -- It's Const#4
	  +C981: 47 00 C1 00   line#1004 GETTABLE 1 1 -5        <16>   R1 = R1["LocalPlayer"]                          -- It's Const#5
	  +C985: 47 40 C1 00   line#1004 GETTABLE 1 1 -6        <17>   R1 = R1["Backpack"]                             -- It's Const#6
	  +C989: 4C 80 C1 00   line#1004 SELF 1 1 -7            <18>   R2 = R1;  R1 = R1["FindFirstChild"]             -- It's Const#7   -- prepare for R1:FindFirstChild()
	  +C98D: C0 00 00 00   line#1004 MOVE 3 0               <19>   R3 = R0@ToolSe
	  +C991: 64 80 80 01   line#1004 CALL 1 3 2             <20>   R1 = R1(R2, R3)
	  +C995: 08 40 80 83   line#1004 SETTABUP 0 -8 1        <21>   Upv#1@_ENV["Tool"] = R1                         -- It's Const#8
	  +C999: 46 00 42 00   line#1005 GETTABUP 1 0 -9        <22>   R1 = Upv#1@_ENV["wait"]                         -- It's Const#9
	  +C99D: 81 40 02 00   line#1005 LOADK 2 -10            <23>   R2 = 0.1                                        -- It's Const#10
	  +C9A1: 64 40 00 01   line#1005 CALL 1 2 1             <24>   R1(R2)
	  +C9A5: 46 80 40 00   line#1006 GETTABUP 1 0 -3        <25>   R1 = Upv#1@_ENV["game"]                         -- It's Const#3
	  +C9A9: 47 C0 C0 00   line#1006 GETTABLE 1 1 -4        <26>   R1 = R1["Players"]                              -- It's Const#4
	  +C9AD: 47 00 C1 00   line#1006 GETTABLE 1 1 -5        <27>   R1 = R1["LocalPlayer"]                          -- It's Const#5
	  +C9B1: 47 80 C2 00   line#1006 GETTABLE 1 1 -11       <28>   R1 = R1["Character"]                            -- It's Const#11
	  +C9B5: 47 C0 C2 00   line#1006 GETTABLE 1 1 -12       <29>   R1 = R1["Humanoid"]                             -- It's Const#12
	  +C9B9: 4C 00 C3 00   line#1006 SELF 1 1 -13           <30>   R2 = R1;  R1 = R1["EquipTool"]                  -- It's Const#13   -- prepare for R1:EquipTool()
	  +C9BD: C6 C0 41 00   line#1006 GETTABUP 3 0 -8        <31>   R3 = Upv#1@_ENV["Tool"]                         -- It's Const#8
	  +C9C1: 64 40 80 01   line#1006 CALL 1 3 1             <32>   R1(R2, R3)
	  +C9C5: 26 00 80 00   line#1009 RETURN 0 1             <33>   RETURN
	Functions: 0

	************ Function#19   (full path: main.19)
	Source line#: 1011..1024
	Parameters: 1
	Is vararg: no
	VM registers needed: 3
	Constants: 27
	  +CBDE:Size=8: 44 69 73 74 61 6E 63 65         Const#1   string    "Distance"
	  +CBE8:Size=8: 50 6F 73 69 74 69 6F 6E         Const#2   string    "Position"
	  +CBF2:Size=4: 67 61 6D 65                     Const#3   string    "game"
	  +CBF8:Size=7: 50 6C 61 79 65 72 73            Const#4   string    "Players"
	  +CC01:Size=B: 4C 6F 63 61 6C 50 6C 61 79...   Const#5   string    "LocalPlayer"
	  +CC0E:Size=9: 43 68 61 72 61 63 74 65 72      Const#6   string    "Character"
	  +CC19:Size=10: 48 75 6D 61 6E 6F 69 64 5...   Const#7   string    "HumanoidRootPart"
	  +CC2B:Size=9: 4D 61 67 6E 69 74 75 64 65      Const#8   string    "Magnitude"
	  +CC36:Size=8: 48 75 6D 61 6E 6F 69 64         Const#9   string    "Humanoid"
	  +CC40:Size=3: 53 69 74                        Const#10  string    "Sit"
	  +CC44:Size=1: 01                              Const#11  boolean   true
	  +CC46:Size=1: 00                              Const#12  boolean   false
	  +CC49:Size=5: 70 63 61 6C 6C                  Const#13  string    "pcall"
	  +CC50:Size=5: 74 77 65 65 6E                  Const#14  string    "tween"
	  +CC57:Size=4: 50 6C 61 79                     Const#15  string    "Play"
	  +CC5D:Size=8: 44 69 73 74 61 6E 63 65         Const#16  string    "Distance"
	  +CC66:Size=4: FA 00 00 00                     Const#17  integer   250
	  +CC6C:Size=6: 43 61 6E 63 65 6C               Const#18  string    "Cancel"
	  +CC74:Size=4: 67 61 6D 65                     Const#19  string    "game"
	  +CC7A:Size=7: 50 6C 61 79 65 72 73            Const#20  string    "Players"
	  +CC83:Size=B: 4C 6F 63 61 6C 50 6C 61 79...   Const#21  string    "LocalPlayer"
	  +CC90:Size=9: 43 68 61 72 61 63 74 65 72      Const#22  string    "Character"
	  +CC9B:Size=10: 48 75 6D 61 6E 6F 69 64 5...   Const#23  string    "HumanoidRootPart"
	  +CCAD:Size=6: 43 46 72 61 6D 65               Const#24  string    "CFrame"
	  +CCB5:Size=2: 5F 47                           Const#25  string    "_G"
	  +CCB9:Size=9: 53 74 6F 70 54 77 65 65 6E      Const#26  string    "StopTween"
	  +CCC4:Size=4: 43 6C 69 70                     Const#27  string    "Clip"
	Upvalues: 1
	  Upv#1 is parent function's Upv#1              name: _ENV
	Locals: 1
	  Local#1   R0   parameter  scope:<1..52>       name: Pos
	Instructions: 52
	  +CB08: 47 40 40 00   line#1012 GETTABLE 1 0 -2         <1>   R1 = R0@Pos["Position"]                         -- It's Const#2
	  +CB0C: 86 80 40 00   line#1012 GETTABUP 2 0 -3         <2>   R2 = Upv#1@_ENV["game"]                         -- It's Const#3
	  +CB10: 87 C0 40 01   line#1012 GETTABLE 2 2 -4         <3>   R2 = R2["Players"]                              -- It's Const#4
	  +CB14: 87 00 41 01   line#1012 GETTABLE 2 2 -5         <4>   R2 = R2["LocalPlayer"]                          -- It's Const#5
	  +CB18: 87 40 41 01   line#1012 GETTABLE 2 2 -6         <5>   R2 = R2["Character"]                            -- It's Const#6
	  +CB1C: 87 80 41 01   line#1012 GETTABLE 2 2 -7         <6>   R2 = R2["HumanoidRootPart"]                     -- It's Const#7
	  +CB20: 87 40 40 01   line#1012 GETTABLE 2 2 -2         <7>   R2 = R2["Position"]                             -- It's Const#2
	  +CB24: 4E 80 80 00   line#1012 SUB 1 1 2               <8>   R1 = R1 - R2
	  +CB28: 47 C0 C1 00   line#1012 GETTABLE 1 1 -8         <9>   R1 = R1["Magnitude"]                            -- It's Const#8
	  +CB2C: 08 40 00 80   line#1012 SETTABUP 0 -1 1        <10>   Upv#1@_ENV["Distance"] = R1                     -- It's Const#1
	  +CB30: 46 80 40 00   line#1013 GETTABUP 1 0 -3        <11>   R1 = Upv#1@_ENV["game"]                         -- It's Const#3
	  +CB34: 47 C0 C0 00   line#1013 GETTABLE 1 1 -4        <12>   R1 = R1["Players"]                              -- It's Const#4
	  +CB38: 47 00 C1 00   line#1013 GETTABLE 1 1 -5        <13>   R1 = R1["LocalPlayer"]                          -- It's Const#5
	  +CB3C: 47 40 C1 00   line#1013 GETTABLE 1 1 -6        <14>   R1 = R1["Character"]                            -- It's Const#6
	  +CB40: 47 00 C2 00   line#1013 GETTABLE 1 1 -9        <15>   R1 = R1["Humanoid"]                             -- It's Const#9
	  +CB44: 47 40 C2 00   line#1013 GETTABLE 1 1 -10       <16>   R1 = R1["Sit"]                                  -- It's Const#10
	  +CB48: 1F 80 C2 00   line#1013 EQ 0 1 -11             <17>   if R1 == true then GOTO <19>                    -- It's Const#11
	  +CB4C: 1E 40 01 80   line#1013 JMP 0 6                <18>   GOTO <25>
	  +CB50: 46 80 40 00   line#1013 GETTABUP 1 0 -3        <19>   R1 = Upv#1@_ENV["game"]                         -- It's Const#3
	  +CB54: 47 C0 C0 00   line#1013 GETTABLE 1 1 -4        <20>   R1 = R1["Players"]                              -- It's Const#4
	  +CB58: 47 00 C1 00   line#1013 GETTABLE 1 1 -5        <21>   R1 = R1["LocalPlayer"]                          -- It's Const#5
	  +CB5C: 47 40 C1 00   line#1013 GETTABLE 1 1 -6        <22>   R1 = R1["Character"]                            -- It's Const#6
	  +CB60: 47 00 C2 00   line#1013 GETTABLE 1 1 -9        <23>   R1 = R1["Humanoid"]                             -- It's Const#9
	  +CB64: 4A C0 C2 84   line#1013 SETTABLE 1 -10 -12     <24>   R1["Sit"] = false                               -- It's Const#10, Const#12
	  +CB68: 46 00 43 00   line#1014 GETTABUP 1 0 -13       <25>   R1 = Upv#1@_ENV["pcall"]                        -- It's Const#13
	  +CB6C: AC 00 00 00   line#1014 CLOSURE 2 0            <26>   R2 = Function#1
	  +CB70: 64 40 00 01   line#1014 CALL 1 2 1             <27>   R1(R2)
	  +CB74: 46 40 43 00   line#1015 GETTABUP 1 0 -14       <28>   R1 = Upv#1@_ENV["tween"]                        -- It's Const#14
	  +CB78: 4C 80 C3 00   line#1015 SELF 1 1 -15           <29>   R2 = R1;  R1 = R1["Play"]                       -- It's Const#15   -- prepare for R1:Play()
	  +CB7C: 64 40 00 01   line#1015 CALL 1 2 1             <30>   R1(R2)
	  +CB80: 46 C0 43 00   line#1016 GETTABUP 1 0 -16       <31>   R1 = Upv#1@_ENV["Distance"]                     -- It's Const#16
	  +CB84: 21 00 C4 00   line#1016 LE 0 1 -17             <32>   if R1 <= 250 then GOTO <34>                     -- It's Const#17
	  +CB88: 1E 00 02 80   line#1016 JMP 0 9                <33>   GOTO <43>
	  +CB8C: 46 40 43 00   line#1017 GETTABUP 1 0 -14       <34>   R1 = Upv#1@_ENV["tween"]                        -- It's Const#14
	  +CB90: 4C 40 C4 00   line#1017 SELF 1 1 -18           <35>   R2 = R1;  R1 = R1["Cancel"]                     -- It's Const#18   -- prepare for R1:Cancel()
	  +CB94: 64 40 00 01   line#1017 CALL 1 2 1             <36>   R1(R2)
	  +CB98: 46 80 44 00   line#1018 GETTABUP 1 0 -19       <37>   R1 = Upv#1@_ENV["game"]                         -- It's Const#19
	  +CB9C: 47 C0 C4 00   line#1018 GETTABLE 1 1 -20       <38>   R1 = R1["Players"]                              -- It's Const#20
	  +CBA0: 47 00 C5 00   line#1018 GETTABLE 1 1 -21       <39>   R1 = R1["LocalPlayer"]                          -- It's Const#21
	  +CBA4: 47 40 C5 00   line#1018 GETTABLE 1 1 -22       <40>   R1 = R1["Character"]                            -- It's Const#22
	  +CBA8: 47 80 C5 00   line#1018 GETTABLE 1 1 -23       <41>   R1 = R1["HumanoidRootPart"]                     -- It's Const#23
	  +CBAC: 4A 00 80 8B   line#1018 SETTABLE 1 -24 0       <42>   R1["CFrame"] = R0@Pos                           -- It's Const#24
	  +CBB0: 46 00 46 00   line#1020 GETTABUP 1 0 -25       <43>   R1 = Upv#1@_ENV["_G"]                           -- It's Const#25
	  +CBB4: 47 40 C6 00   line#1020 GETTABLE 1 1 -26       <44>   R1 = R1["StopTween"]                            -- It's Const#26
	  +CBB8: 1F 80 C2 00   line#1020 EQ 0 1 -11             <45>   if R1 == true then GOTO <47>                    -- It's Const#11
	  +CBBC: 1E 00 01 80   line#1020 JMP 0 5                <46>   GOTO <52>
	  +CBC0: 46 40 43 00   line#1021 GETTABUP 1 0 -14       <47>   R1 = Upv#1@_ENV["tween"]                        -- It's Const#14
	  +CBC4: 4C 40 C4 00   line#1021 SELF 1 1 -18           <48>   R2 = R1;  R1 = R1["Cancel"]                     -- It's Const#18   -- prepare for R1:Cancel()
	  +CBC8: 64 40 00 01   line#1021 CALL 1 2 1             <49>   R1(R2)
	  +CBCC: 46 00 46 00   line#1022 GETTABUP 1 0 -25       <50>   R1 = Upv#1@_ENV["_G"]                           -- It's Const#25
	  +CBD0: 4A C0 42 8D   line#1022 SETTABLE 1 -27 -12     <51>   R1["Clip"] = false                              -- It's Const#27, Const#12
	  +CBD4: 26 00 80 00   line#1024 RETURN 0 1             <52>   RETURN
	Functions: 1

		************ Function#1   (full path: main.19.1)
		Source line#: 1014
		Parameters: 0
		Is vararg: no
		VM registers needed: 6
		Constants: 17
		  +CD48:Size=5: 74 77 65 65 6E                  Const#1   string    "tween"
		  +CD4F:Size=4: 67 61 6D 65                     Const#2   string    "game"
		  +CD55:Size=A: 47 65 74 53 65 72 76 69 63 65   Const#3   string    "GetService"
		  +CD61:Size=C: 54 77 65 65 6E 53 65 72 76...   Const#4   string    "TweenService"
		  +CD6F:Size=6: 43 72 65 61 74 65               Const#5   string    "Create"
		  +CD77:Size=7: 50 6C 61 79 65 72 73            Const#6   string    "Players"
		  +CD80:Size=B: 4C 6F 63 61 6C 50 6C 61 79...   Const#7   string    "LocalPlayer"
		  +CD8D:Size=9: 43 68 61 72 61 63 74 65 72      Const#8   string    "Character"
		  +CD98:Size=10: 48 75 6D 61 6E 6F 69 64 5...   Const#9   string    "HumanoidRootPart"
		  +CDAA:Size=9: 54 77 65 65 6E 49 6E 66 6F      Const#10  string    "TweenInfo"
		  +CDB5:Size=3: 6E 65 77                        Const#11  string    "new"
		  +CDBA:Size=8: 44 69 73 74 61 6E 63 65         Const#12  string    "Distance"
		  +CDC3:Size=4: D2 00 00 00                     Const#13  integer   210
		  +CDC9:Size=4: 45 6E 75 6D                     Const#14  string    "Enum"
		  +CDCF:Size=B: 45 61 73 69 6E 67 53 74 79...   Const#15  string    "EasingStyle"
		  +CDDC:Size=6: 4C 69 6E 65 61 72               Const#16  string    "Linear"
		  +CDE4:Size=6: 43 46 72 61 6D 65               Const#17  string    "CFrame"
		Upvalues: 2
		  Upv#1 is parent function's Upv#1              name: _ENV
		  Upv#2 is parent function's R0                 name: Pos
		Instructions: 24
		  +CCE2: 06 40 40 00   line#1014 GETTABUP 0 0 -2         <1>   R0 = Upv#1@_ENV["game"]                         -- It's Const#2
		  +CCE6: 0C 80 40 00   line#1014 SELF 0 0 -3             <2>   R1 = R0;  R0 = R0["GetService"]                 -- It's Const#3   -- prepare for R0:GetService()
		  +CCEA: 81 C0 00 00   line#1014 LOADK 2 -4              <3>   R2 = "TweenService"                             -- It's Const#4
		  +CCEE: 24 80 80 01   line#1014 CALL 0 3 2              <4>   R0 = R0(R1, R2)
		  +CCF2: 0C 00 41 00   line#1014 SELF 0 0 -5             <5>   R1 = R0;  R0 = R0["Create"]                     -- It's Const#5   -- prepare for R0:Create()
		  +CCF6: 86 40 40 00   line#1014 GETTABUP 2 0 -2         <6>   R2 = Upv#1@_ENV["game"]                         -- It's Const#2
		  +CCFA: 87 40 41 01   line#1014 GETTABLE 2 2 -6         <7>   R2 = R2["Players"]                              -- It's Const#6
		  +CCFE: 87 80 41 01   line#1014 GETTABLE 2 2 -7         <8>   R2 = R2["LocalPlayer"]                          -- It's Const#7
		  +CD02: 87 C0 41 01   line#1014 GETTABLE 2 2 -8         <9>   R2 = R2["Character"]                            -- It's Const#8
		  +CD06: 87 00 42 01   line#1014 GETTABLE 2 2 -9        <10>   R2 = R2["HumanoidRootPart"]                     -- It's Const#9
		  +CD0A: C6 40 42 00   line#1014 GETTABUP 3 0 -10       <11>   R3 = Upv#1@_ENV["TweenInfo"]                    -- It's Const#10
		  +CD0E: C7 80 C2 01   line#1014 GETTABLE 3 3 -11       <12>   R3 = R3["new"]                                  -- It's Const#11
		  +CD12: 06 C1 42 00   line#1014 GETTABUP 4 0 -12       <13>   R4 = Upv#1@_ENV["Distance"]                     -- It's Const#12
		  +CD16: 12 01 43 02   line#1014 DIV 4 4 -13            <14>   R4 = R4 / 210                                   -- It's Const#13
		  +CD1A: 46 41 43 00   line#1014 GETTABUP 5 0 -14       <15>   R5 = Upv#1@_ENV["Enum"]                         -- It's Const#14
		  +CD1E: 47 81 C3 02   line#1014 GETTABLE 5 5 -15       <16>   R5 = R5["EasingStyle"]                          -- It's Const#15
		  +CD22: 47 C1 C3 02   line#1014 GETTABLE 5 5 -16       <17>   R5 = R5["Linear"]                               -- It's Const#16
		  +CD26: E4 80 80 01   line#1014 CALL 3 3 2             <18>   R3 = R3(R4, R5)
		  +CD2A: 0B 41 00 00   line#1014 NEWTABLE 4 0 1         <19>   R4 = {}  arr:0, hash:1
		  +CD2E: 45 01 80 00   line#1014 GETUPVAL 5 1           <20>   R5 = Upv#2@Pos
		  +CD32: 0A 41 01 88   line#1014 SETTABLE 4 -17 5       <21>   R4["CFrame"] = R5                               -- It's Const#17
		  +CD36: 24 80 80 02   line#1014 CALL 0 5 2             <22>   R0 = R0(R1,..,R4)
		  +CD3A: 08 00 00 80   line#1014 SETTABUP 0 -1 0        <23>   Upv#1@_ENV["tween"] = R0                        -- It's Const#1
		  +CD3E: 26 00 80 00   line#1014 RETURN 0 1             <24>   RETURN
		Functions: 0

	************ Function#20   (full path: main.20)
	Source line#: 1026..1028
	Parameters: 1
	Is vararg: no
	VM registers needed: 4
	Constants: 9
	  +CFA6:Size=4: 6D 61 74 68                     Const#1   string    "math"
	  +CFAC:Size=5: 66 6C 6F 6F 72                  Const#2   string    "floor"
	  +CFB3:Size=8: 50 6F 73 69 74 69 6F 6E         Const#3   string    "Position"
	  +CFBD:Size=4: 67 61 6D 65                     Const#4   string    "game"
	  +CFC3:Size=7: 50 6C 61 79 65 72 73            Const#5   string    "Players"
	  +CFCC:Size=B: 4C 6F 63 61 6C 50 6C 61 79...   Const#6   string    "LocalPlayer"
	  +CFD9:Size=9: 43 68 61 72 61 63 74 65 72      Const#7   string    "Character"
	  +CFE4:Size=10: 48 75 6D 61 6E 6F 69 64 5...   Const#8   string    "HumanoidRootPart"
	  +CFF6:Size=9: 4D 61 67 6E 69 74 75 64 65      Const#9   string    "Magnitude"
	Upvalues: 1
	  Upv#1 is parent function's Upv#1              name: _ENV
	Locals: 1
	  Local#1   R0   parameter  scope:<1..14>       name: target
	Instructions: 14
	  +CF68: 46 00 40 00   line#1027 GETTABUP 1 0 -1         <1>   R1 = Upv#1@_ENV["math"]                         -- It's Const#1
	  +CF6C: 47 40 C0 00   line#1027 GETTABLE 1 1 -2         <2>   R1 = R1["floor"]                                -- It's Const#2
	  +CF70: 87 80 40 00   line#1027 GETTABLE 2 0 -3         <3>   R2 = R0@target["Position"]                      -- It's Const#3
	  +CF74: C6 C0 40 00   line#1027 GETTABUP 3 0 -4         <4>   R3 = Upv#1@_ENV["game"]                         -- It's Const#4
	  +CF78: C7 00 C1 01   line#1027 GETTABLE 3 3 -5         <5>   R3 = R3["Players"]                              -- It's Const#5
	  +CF7C: C7 40 C1 01   line#1027 GETTABLE 3 3 -6         <6>   R3 = R3["LocalPlayer"]                          -- It's Const#6
	  +CF80: C7 80 C1 01   line#1027 GETTABLE 3 3 -7         <7>   R3 = R3["Character"]                            -- It's Const#7
	  +CF84: C7 C0 C1 01   line#1027 GETTABLE 3 3 -8         <8>   R3 = R3["HumanoidRootPart"]                     -- It's Const#8
	  +CF88: C7 80 C0 01   line#1027 GETTABLE 3 3 -3         <9>   R3 = R3["Position"]                             -- It's Const#3
	  +CF8C: 8E C0 00 01   line#1027 SUB 2 2 3              <10>   R2 = R2 - R3
	  +CF90: 87 00 42 01   line#1027 GETTABLE 2 2 -9        <11>   R2 = R2["Magnitude"]                            -- It's Const#9
	  +CF94: 65 00 00 01   line#1027 TAILCALL 1 2           <12>   RETURN R1(R2)
	  +CF98: 66 00 00 00   line#1027 RETURN 1 0             <13>   (unreachable instruction)
	  +CF9C: 26 00 80 00   line#1028 RETURN 0 1             <14>   (unreachable instruction)
	Functions: 0

	************ Function#21   (full path: main.21)
	Source line#: 1030..1046
	Parameters: 1
	Is vararg: no
	VM registers needed: 7
	Constants: 22
	  +D14F:Size=8: 44 69 73 74 61 6E 63 65         Const#1   string    "Distance"
	  +D159:Size=8: 50 6F 73 69 74 69 6F 6E         Const#2   string    "Position"
	  +D163:Size=4: 67 61 6D 65                     Const#3   string    "game"
	  +D169:Size=7: 50 6C 61 79 65 72 73            Const#4   string    "Players"
	  +D172:Size=B: 4C 6F 63 61 6C 50 6C 61 79...   Const#5   string    "LocalPlayer"
	  +D17F:Size=9: 43 68 61 72 61 63 74 65 72      Const#6   string    "Character"
	  +D18A:Size=10: 48 75 6D 61 6E 6F 69 64 5...   Const#7   string    "HumanoidRootPart"
	  +D19C:Size=9: 4D 61 67 6E 69 74 75 64 65      Const#8   string    "Magnitude"
	  +D1A6:Size=4: 68 01 00 00                     Const#9   integer   360
	  +D1AC:Size=5: 53 70 65 65 64                  Const#10  string    "Speed"
	  +D1B2:Size=4: B0 04 00 00                     Const#11  integer   1200
	  +D1B7:Size=4: E8 03 00 00                     Const#12  integer   1000
	  +D1BD:Size=A: 47 65 74 53 65 72 76 69 63 65   Const#13  string    "GetService"
	  +D1C9:Size=C: 54 77 65 65 6E 53 65 72 76...   Const#14  string    "TweenService"
	  +D1D7:Size=6: 43 72 65 61 74 65               Const#15  string    "Create"
	  +D1DF:Size=9: 54 77 65 65 6E 49 6E 66 6F      Const#16  string    "TweenInfo"
	  +D1EA:Size=3: 6E 65 77                        Const#17  string    "new"
	  +D1EF:Size=4: 45 6E 75 6D                     Const#18  string    "Enum"
	  +D1F5:Size=B: 45 61 73 69 6E 67 53 74 79...   Const#19  string    "EasingStyle"
	  +D202:Size=6: 4C 69 6E 65 61 72               Const#20  string    "Linear"
	  +D20A:Size=6: 43 46 72 61 6D 65               Const#21  string    "CFrame"
	  +D212:Size=4: 50 6C 61 79                     Const#22  string    "Play"
	Upvalues: 1
	  Upv#1 is parent function's Upv#1              name: _ENV
	Locals: 1
	  Local#1   R0   parameter  scope:<1..54>       name: Pos
	Instructions: 54
	  +D071: 47 40 40 00   line#1031 GETTABLE 1 0 -2         <1>   R1 = R0@Pos["Position"]                         -- It's Const#2
	  +D075: 86 80 40 00   line#1031 GETTABUP 2 0 -3         <2>   R2 = Upv#1@_ENV["game"]                         -- It's Const#3
	  +D079: 87 C0 40 01   line#1031 GETTABLE 2 2 -4         <3>   R2 = R2["Players"]                              -- It's Const#4
	  +D07D: 87 00 41 01   line#1031 GETTABLE 2 2 -5         <4>   R2 = R2["LocalPlayer"]                          -- It's Const#5
	  +D081: 87 40 41 01   line#1031 GETTABLE 2 2 -6         <5>   R2 = R2["Character"]                            -- It's Const#6
	  +D085: 87 80 41 01   line#1031 GETTABLE 2 2 -7         <6>   R2 = R2["HumanoidRootPart"]                     -- It's Const#7
	  +D089: 87 40 40 01   line#1031 GETTABLE 2 2 -2         <7>   R2 = R2["Position"]                             -- It's Const#2
	  +D08D: 4E 80 80 00   line#1031 SUB 1 1 2               <8>   R1 = R1 - R2
	  +D091: 47 C0 C1 00   line#1031 GETTABLE 1 1 -8         <9>   R1 = R1["Magnitude"]                            -- It's Const#8
	  +D095: 08 40 00 80   line#1031 SETTABUP 0 -1 1        <10>   Upv#1@_ENV["Distance"] = R1                     -- It's Const#1
	  +D099: 46 00 40 00   line#1032 GETTABUP 1 0 -1        <11>   R1 = Upv#1@_ENV["Distance"]                     -- It's Const#1
	  +D09D: 20 00 C2 00   line#1032 LT 0 1 -9              <12>   if R1 < 360 then GOTO <14>                      -- It's Const#9
	  +D0A1: 1E 40 00 80   line#1032 JMP 0 2                <13>   GOTO <16>
	  +D0A5: 08 80 C2 84   line#1033 SETTABUP 0 -10 -11     <14>   Upv#1@_ENV["Speed"] = 1200                      -- It's Const#10, Const#11
	  +D0A9: 1E 40 03 80   line#1033 JMP 0 14               <15>   GOTO <30>
	  +D0AD: 46 00 40 00   line#1034 GETTABUP 1 0 -1        <16>   R1 = Upv#1@_ENV["Distance"]                     -- It's Const#1
	  +D0B1: 20 C0 C2 00   line#1034 LT 0 1 -12             <17>   if R1 < 1000 then GOTO <19>                     -- It's Const#12
	  +D0B5: 1E 40 00 80   line#1034 JMP 0 2                <18>   GOTO <21>
	  +D0B9: 08 00 C2 84   line#1035 SETTABUP 0 -10 -9      <19>   Upv#1@_ENV["Speed"] = 360                       -- It's Const#10, Const#9
	  +D0BD: 1E 00 02 80   line#1035 JMP 0 9                <20>   GOTO <30>
	  +D0C1: 46 00 40 00   line#1036 GETTABUP 1 0 -1        <21>   R1 = Upv#1@_ENV["Distance"]                     -- It's Const#1
	  +D0C5: 20 00 C2 00   line#1036 LT 0 1 -9              <22>   if R1 < 360 then GOTO <24>                      -- It's Const#9
	  +D0C9: 1E 40 00 80   line#1036 JMP 0 2                <23>   GOTO <26>
	  +D0CD: 08 80 C2 84   line#1037 SETTABUP 0 -10 -11     <24>   Upv#1@_ENV["Speed"] = 1200                      -- It's Const#10, Const#11
	  +D0D1: 1E C0 00 80   line#1037 JMP 0 4                <25>   GOTO <30>
	  +D0D5: 46 00 40 00   line#1038 GETTABUP 1 0 -1        <26>   R1 = Upv#1@_ENV["Distance"]                     -- It's Const#1
	  +D0D9: 21 40 80 85   line#1038 LE 0 -12 1             <27>   if R1 >= 1000 then GOTO <29>                    -- It's Const#12
	  +D0DD: 1E 00 00 80   line#1038 JMP 0 1                <28>   GOTO <30>
	  +D0E1: 08 00 C2 84   line#1039 SETTABUP 0 -10 -9      <29>   Upv#1@_ENV["Speed"] = 360                       -- It's Const#10, Const#9
	  +D0E5: 46 80 40 00   line#1041 GETTABUP 1 0 -3        <30>   R1 = Upv#1@_ENV["game"]                         -- It's Const#3
	  +D0E9: 4C 00 C3 00   line#1041 SELF 1 1 -13           <31>   R2 = R1;  R1 = R1["GetService"]                 -- It's Const#13   -- prepare for R1:GetService()
	  +D0ED: C1 40 03 00   line#1041 LOADK 3 -14            <32>   R3 = "TweenService"                             -- It's Const#14
	  +D0F1: 64 80 80 01   line#1041 CALL 1 3 2             <33>   R1 = R1(R2, R3)
	  +D0F5: 4C 80 C3 00   line#1041 SELF 1 1 -15           <34>   R2 = R1;  R1 = R1["Create"]                     -- It's Const#15   -- prepare for R1:Create()
	  +D0F9: C6 80 40 00   line#1042 GETTABUP 3 0 -3        <35>   R3 = Upv#1@_ENV["game"]                         -- It's Const#3
	  +D0FD: C7 C0 C0 01   line#1042 GETTABLE 3 3 -4        <36>   R3 = R3["Players"]                              -- It's Const#4
	  +D101: C7 00 C1 01   line#1042 GETTABLE 3 3 -5        <37>   R3 = R3["LocalPlayer"]                          -- It's Const#5
	  +D105: C7 40 C1 01   line#1042 GETTABLE 3 3 -6        <38>   R3 = R3["Character"]                            -- It's Const#6
	  +D109: C7 80 C1 01   line#1042 GETTABLE 3 3 -7        <39>   R3 = R3["HumanoidRootPart"]                     -- It's Const#7
	  +D10D: 06 C1 43 00   line#1043 GETTABUP 4 0 -16       <40>   R4 = Upv#1@_ENV["TweenInfo"]                    -- It's Const#16
	  +D111: 07 01 44 02   line#1043 GETTABLE 4 4 -17       <41>   R4 = R4["new"]                                  -- It's Const#17
	  +D115: 46 01 40 00   line#1043 GETTABUP 5 0 -1        <42>   R5 = Upv#1@_ENV["Distance"]                     -- It's Const#1
	  +D119: 86 41 42 00   line#1043 GETTABUP 6 0 -10       <43>   R6 = Upv#1@_ENV["Speed"]                        -- It's Const#10
	  +D11D: 52 81 81 02   line#1043 DIV 5 5 6              <44>   R5 = R5 / R6
	  +D121: 86 41 44 00   line#1043 GETTABUP 6 0 -18       <45>   R6 = Upv#1@_ENV["Enum"]                         -- It's Const#18
	  +D125: 87 81 44 03   line#1043 GETTABLE 6 6 -19       <46>   R6 = R6["EasingStyle"]                          -- It's Const#19
	  +D129: 87 C1 44 03   line#1043 GETTABLE 6 6 -20       <47>   R6 = R6["Linear"]                               -- It's Const#20
	  +D12D: 24 81 80 01   line#1043 CALL 4 3 2             <48>   R4 = R4(R5, R6)
	  +D131: 4B 41 00 00   line#1043 NEWTABLE 5 0 1         <49>   R5 = {}  arr:0, hash:1
	  +D135: 4A 01 00 8A   line#1044 SETTABLE 5 -21 0       <50>   R5["CFrame"] = R0@Pos                           -- It's Const#21
	  +D139: 64 80 80 02   line#1041 CALL 1 5 2             <51>   R1 = R1(R2,..,R5)
	  +D13D: 4C 40 C5 00   line#1045 SELF 1 1 -22           <52>   R2 = R1;  R1 = R1["Play"]                       -- It's Const#22   -- prepare for R1:Play()
	  +D141: 64 40 00 01   line#1041 CALL 1 2 1             <53>   R1(R2)
	  +D145: 26 00 80 00   line#1046 RETURN 0 1             <54>   RETURN
	Functions: 0

	************ Function#22   (full path: main.22)
	Source line#: 1048..1063
	Parameters: 1
	Is vararg: no
	VM registers needed: 7
	Constants: 28
	  +D40F:Size=8: 44 69 73 74 61 6E 63 65         Const#1   string    "Distance"
	  +D419:Size=8: 50 6F 73 69 74 69 6F 6E         Const#2   string    "Position"
	  +D423:Size=4: 67 61 6D 65                     Const#3   string    "game"
	  +D429:Size=A: 47 65 74 53 65 72 76 69 63 65   Const#4   string    "GetService"
	  +D435:Size=7: 50 6C 61 79 65 72 73            Const#5   string    "Players"
	  +D43E:Size=B: 4C 6F 63 61 6C 50 6C 61 79...   Const#6   string    "LocalPlayer"
	  +D44B:Size=9: 43 68 61 72 61 63 74 65 72      Const#7   string    "Character"
	  +D456:Size=10: 48 75 6D 61 6E 6F 69 64 5...   Const#8   string    "HumanoidRootPart"
	  +D468:Size=9: 4D 61 67 6E 69 74 75 64 65      Const#9   string    "Magnitude"
	  +D472:Size=4: FA 00 00 00                     Const#10  integer   250
	  +D478:Size=5: 53 70 65 65 64                  Const#11  string    "Speed"
	  +D47E:Size=4: 58 02 00 00                     Const#12  integer   600
	  +D483:Size=4: E8 03 00 00                     Const#13  integer   1000
	  +D488:Size=4: C8 00 00 00                     Const#14  integer   200
	  +D48E:Size=C: 54 77 65 65 6E 53 65 72 76...   Const#15  string    "TweenService"
	  +D49C:Size=6: 43 72 65 61 74 65               Const#16  string    "Create"
	  +D4A4:Size=9: 54 77 65 65 6E 49 6E 66 6F      Const#17  string    "TweenInfo"
	  +D4AF:Size=3: 6E 65 77                        Const#18  string    "new"
	  +D4B4:Size=4: 45 6E 75 6D                     Const#19  string    "Enum"
	  +D4BA:Size=B: 45 61 73 69 6E 67 53 74 79...   Const#20  string    "EasingStyle"
	  +D4C7:Size=6: 4C 69 6E 65 61 72               Const#21  string    "Linear"
	  +D4CF:Size=6: 43 46 72 61 6D 65               Const#22  string    "CFrame"
	  +D4D7:Size=4: 50 6C 61 79                     Const#23  string    "Play"
	  +D4DD:Size=2: 5F 47                           Const#24  string    "_G"
	  +D4E1:Size=4: 43 6C 69 70                     Const#25  string    "Clip"
	  +D4E6:Size=1: 01                              Const#26  boolean   true
	  +D4E9:Size=4: 77 61 69 74                     Const#27  string    "wait"
	  +D4EE:Size=1: 00                              Const#28  boolean   false
	Upvalues: 1
	  Upv#1 is parent function's Upv#1              name: _ENV
	Locals: 1
	  Local#1   R0   parameter  scope:<1..57>       name: Pos
	Instructions: 57
	  +D325: 47 40 40 00   line#1049 GETTABLE 1 0 -2         <1>   R1 = R0@Pos["Position"]                         -- It's Const#2
	  +D329: 86 80 40 00   line#1049 GETTABUP 2 0 -3         <2>   R2 = Upv#1@_ENV["game"]                         -- It's Const#3
	  +D32D: 8C C0 40 01   line#1049 SELF 2 2 -4             <3>   R3 = R2;  R2 = R2["GetService"]                 -- It's Const#4   -- prepare for R2:GetService()
	  +D331: 01 01 01 00   line#1049 LOADK 4 -5              <4>   R4 = "Players"                                  -- It's Const#5
	  +D335: A4 80 80 01   line#1049 CALL 2 3 2              <5>   R2 = R2(R3, R4)
	  +D339: 87 40 41 01   line#1049 GETTABLE 2 2 -6         <6>   R2 = R2["LocalPlayer"]                          -- It's Const#6
	  +D33D: 87 80 41 01   line#1049 GETTABLE 2 2 -7         <7>   R2 = R2["Character"]                            -- It's Const#7
	  +D341: 87 C0 41 01   line#1049 GETTABLE 2 2 -8         <8>   R2 = R2["HumanoidRootPart"]                     -- It's Const#8
	  +D345: 87 40 40 01   line#1049 GETTABLE 2 2 -2         <9>   R2 = R2["Position"]                             -- It's Const#2
	  +D349: 4E 80 80 00   line#1049 SUB 1 1 2              <10>   R1 = R1 - R2
	  +D34D: 47 00 C2 00   line#1049 GETTABLE 1 1 -9        <11>   R1 = R1["Magnitude"]                            -- It's Const#9
	  +D351: 08 40 00 80   line#1049 SETTABUP 0 -1 1        <12>   Upv#1@_ENV["Distance"] = R1                     -- It's Const#1
	  +D355: 46 00 40 00   line#1050 GETTABUP 1 0 -1        <13>   R1 = Upv#1@_ENV["Distance"]                     -- It's Const#1
	  +D359: 20 40 C2 00   line#1050 LT 0 1 -10             <14>   if R1 < 250 then GOTO <16>                      -- It's Const#10
	  +D35D: 1E 40 00 80   line#1050 JMP 0 2                <15>   GOTO <18>
	  +D361: 08 C0 42 85   line#1051 SETTABUP 0 -11 -12     <16>   Upv#1@_ENV["Speed"] = 600                       -- It's Const#11, Const#12
	  +D365: 1E C0 00 80   line#1051 JMP 0 4                <17>   GOTO <22>
	  +D369: 46 00 40 00   line#1052 GETTABUP 1 0 -1        <18>   R1 = Upv#1@_ENV["Distance"]                     -- It's Const#1
	  +D36D: 21 40 00 86   line#1052 LE 0 -13 1             <19>   if R1 >= 1000 then GOTO <21>                    -- It's Const#13
	  +D371: 1E 00 00 80   line#1052 JMP 0 1                <20>   GOTO <22>
	  +D375: 08 40 43 85   line#1053 SETTABUP 0 -11 -14     <21>   Upv#1@_ENV["Speed"] = 200                       -- It's Const#11, Const#14
	  +D379: 46 80 40 00   line#1055 GETTABUP 1 0 -3        <22>   R1 = Upv#1@_ENV["game"]                         -- It's Const#3
	  +D37D: 4C C0 C0 00   line#1055 SELF 1 1 -4            <23>   R2 = R1;  R1 = R1["GetService"]                 -- It's Const#4   -- prepare for R1:GetService()
	  +D381: C1 80 03 00   line#1055 LOADK 3 -15            <24>   R3 = "TweenService"                             -- It's Const#15
	  +D385: 64 80 80 01   line#1055 CALL 1 3 2             <25>   R1 = R1(R2, R3)
	  +D389: 4C C0 C3 00   line#1055 SELF 1 1 -16           <26>   R2 = R1;  R1 = R1["Create"]                     -- It's Const#16   -- prepare for R1:Create()
	  +D38D: C6 80 40 00   line#1056 GETTABUP 3 0 -3        <27>   R3 = Upv#1@_ENV["game"]                         -- It's Const#3
	  +D391: CC C0 C0 01   line#1056 SELF 3 3 -4            <28>   R4 = R3;  R3 = R3["GetService"]                 -- It's Const#4   -- prepare for R3:GetService()
	  +D395: 41 01 01 00   line#1056 LOADK 5 -5             <29>   R5 = "Players"                                  -- It's Const#5
	  +D399: E4 80 80 01   line#1056 CALL 3 3 2             <30>   R3 = R3(R4, R5)
	  +D39D: C7 40 C1 01   line#1056 GETTABLE 3 3 -6        <31>   R3 = R3["LocalPlayer"]                          -- It's Const#6
	  +D3A1: C7 80 C1 01   line#1056 GETTABLE 3 3 -7        <32>   R3 = R3["Character"]                            -- It's Const#7
	  +D3A5: C7 C0 C1 01   line#1056 GETTABLE 3 3 -8        <33>   R3 = R3["HumanoidRootPart"]                     -- It's Const#8
	  +D3A9: 06 01 44 00   line#1057 GETTABUP 4 0 -17       <34>   R4 = Upv#1@_ENV["TweenInfo"]                    -- It's Const#17
	  +D3AD: 07 41 44 02   line#1057 GETTABLE 4 4 -18       <35>   R4 = R4["new"]                                  -- It's Const#18
	  +D3B1: 46 01 40 00   line#1057 GETTABUP 5 0 -1        <36>   R5 = Upv#1@_ENV["Distance"]                     -- It's Const#1
	  +D3B5: 86 81 42 00   line#1057 GETTABUP 6 0 -11       <37>   R6 = Upv#1@_ENV["Speed"]                        -- It's Const#11
	  +D3B9: 52 81 81 02   line#1057 DIV 5 5 6              <38>   R5 = R5 / R6
	  +D3BD: 86 81 44 00   line#1057 GETTABUP 6 0 -19       <39>   R6 = Upv#1@_ENV["Enum"]                         -- It's Const#19
	  +D3C1: 87 C1 44 03   line#1057 GETTABLE 6 6 -20       <40>   R6 = R6["EasingStyle"]                          -- It's Const#20
	  +D3C5: 87 01 45 03   line#1057 GETTABLE 6 6 -21       <41>   R6 = R6["Linear"]                               -- It's Const#21
	  +D3C9: 24 81 80 01   line#1057 CALL 4 3 2             <42>   R4 = R4(R5, R6)
	  +D3CD: 4B 41 00 00   line#1057 NEWTABLE 5 0 1         <43>   R5 = {}  arr:0, hash:1
	  +D3D1: 4A 01 80 8A   line#1058 SETTABLE 5 -22 0       <44>   R5["CFrame"] = R0@Pos                           -- It's Const#22
	  +D3D5: 64 80 80 02   line#1055 CALL 1 5 2             <45>   R1 = R1(R2,..,R5)
	  +D3D9: 4C 80 C5 00   line#1059 SELF 1 1 -23           <46>   R2 = R1;  R1 = R1["Play"]                       -- It's Const#23   -- prepare for R1:Play()
	  +D3DD: 64 40 00 01   line#1055 CALL 1 2 1             <47>   R1(R2)
	  +D3E1: 46 C0 45 00   line#1060 GETTABUP 1 0 -24       <48>   R1 = Upv#1@_ENV["_G"]                           -- It's Const#24
	  +D3E5: 4A 40 46 8C   line#1060 SETTABLE 1 -25 -26     <49>   R1["Clip"] = true                               -- It's Const#25, Const#26
	  +D3E9: 46 80 46 00   line#1061 GETTABUP 1 0 -27       <50>   R1 = Upv#1@_ENV["wait"]                         -- It's Const#27
	  +D3ED: 86 00 40 00   line#1061 GETTABUP 2 0 -1        <51>   R2 = Upv#1@_ENV["Distance"]                     -- It's Const#1
	  +D3F1: C6 80 42 00   line#1061 GETTABUP 3 0 -11       <52>   R3 = Upv#1@_ENV["Speed"]                        -- It's Const#11
	  +D3F5: 92 C0 00 01   line#1061 DIV 2 2 3              <53>   R2 = R2 / R3
	  +D3F9: 64 40 00 01   line#1061 CALL 1 2 1             <54>   R1(R2)
	  +D3FD: 46 C0 45 00   line#1062 GETTABUP 1 0 -24       <55>   R1 = Upv#1@_ENV["_G"]                           -- It's Const#24
	  +D401: 4A C0 46 8C   line#1062 SETTABLE 1 -25 -28     <56>   R1["Clip"] = false                              -- It's Const#25, Const#28
	  +D405: 26 00 80 00   line#1063 RETURN 0 1             <57>   RETURN
	Functions: 0

	************ Function#23   (full path: main.23)
	Source line#: 1065..1079
	Parameters: 0
	Is vararg: no
	VM registers needed: 2
	Constants: 1
	  +D620:Size=5: 70 63 61 6C 6C                  Const#1   string    "pcall"
	Upvalues: 1
	  Upv#1 is parent function's Upv#1              name: _ENV
	Instructions: 4
	  +D60A: 06 00 40 00   line#1066 GETTABUP 0 0 -1         <1>   R0 = Upv#1@_ENV["pcall"]                        -- It's Const#1
	  +D60E: 6C 00 00 00   line#1078 CLOSURE 1 0             <2>   R1 = Function#1
	  +D612: 24 40 00 01   line#1066 CALL 0 2 1              <3>   R0(R1)
	  +D616: 26 00 80 00   line#1079 RETURN 0 1              <4>   RETURN
	Functions: 1

		************ Function#1   (full path: main.23.1)
		Source line#: 1066..1078
		Parameters: 0
		Is vararg: no
		VM registers needed: 5
		Constants: 78
		  +DA95:Size=4: 77 61 69 74                     Const#1   string    "wait"
		  +DA9B:Size=2: 5F 47                           Const#2   string    "_G"
		  +DA9F:Size=12: 41 75 74 6F 41 64 76 61 6...   Const#3   string    "AutoAdvanceDungeon"
		  +DAB3:Size=E: 41 75 74 6F 44 6F 75 67 68...   Const#4   string    "AutoDoughtBoss"
		  +DAC3:Size=13: 41 75 74 6F 5F 44 75 6E 6...   Const#5   string    "Auto_DungeonMobAura"
		  +DAD8:Size=D: 41 75 74 6F 46 61 72 6D 43...   Const#6   string    "AutoFarmChest"
		  +DAE7:Size=12: 41 75 74 6F 46 61 72 6D 4...   Const#7   string    "AutoFarmBossHallow"
		  +DAFB:Size=13: 41 75 74 6F 46 61 72 6D 5...   Const#8   string    "AutoFarmSwanGlasses"
		  +DB10:Size=D: 41 75 74 6F 4C 6F 6E 67 53...   Const#9   string    "AutoLongSword"
		  +DB1F:Size=13: 41 75 74 6F 42 6C 61 63 6...   Const#10  string    "AutoBlackSpikeycoat"
		  +DB34:Size=10: 41 75 74 6F 45 6C 65 63 7...   Const#11  string    "AutoElectricClaw"
		  +DB46:Size=12: 41 75 74 6F 46 61 72 6D 4...   Const#12  string    "AutoFarmGunMastery"
		  +DB5A:Size=D: 41 75 74 6F 48 6F 6C 79 54...   Const#13  string    "AutoHolyTorch"
		  +DB69:Size=B: 41 75 74 6F 4C 61 77 52 61...   Const#14  string    "AutoLawRaid"
		  +DB76:Size=C: 41 75 74 6F 46 61 72 6D 42...   Const#15  string    "AutoFarmBoss"
		  +DB84:Size=D: 41 75 74 6F 54 77 69 6E 48...   Const#16  string    "AutoTwinHooks"
		  +DB93:Size=10: 41 75 74 6F 4F 70 65 6E 5...   Const#17  string    "AutoOpenSwanDoor"
		  +DBA5:Size=12: 41 75 74 6F 44 72 61 67 6...   Const#18  string    "AutoDragon_Trident"
		  +DBB9:Size=9: 41 75 74 6F 53 61 62 65 72      Const#19  string    "AutoSaber"
		  +DBC4:Size=14: 41 75 74 6F 46 61 72 6D 4...   Const#20  string    "AutoFarmFruitMastery"
		  +DBDA:Size=E: 54 65 6C 65 70 6F 72 74 49...   Const#21  string    "TeleportIsland"
		  +DBEA:Size=C: 41 75 74 6F 5F 45 76 6F 52...   Const#22  string    "Auto_EvoRace"
		  +DBF8:Size=17: 41 75 74 6F 46 61 72 6D 4...   Const#23  string    "AutoFarmAllMsBypassType"
		  +DC11:Size=11: 41 75 74 6F 4F 62 73 65 7...   Const#24  string    "AutoObservationv2"
		  +DC24:Size=10: 41 75 74 6F 4D 75 73 6B 6...   Const#25  string    "AutoMusketeerHat"
		  +DC36:Size=D: 41 75 74 6F 45 63 74 6F 70...   Const#26  string    "AutoEctoplasm"
		  +DC45:Size=B: 41 75 74 6F 52 65 6E 67 6F...   Const#27  string    "AutoRengoku"
		  +DC52:Size=11: 41 75 74 6F 5F 52 61 69 6...   Const#28  string    "Auto_Rainbow_Haki"
		  +DC65:Size=F: 41 75 74 6F 4F 62 73 65 72...   Const#29  string    "AutoObservation"
		  +DC76:Size=E: 41 75 74 6F 44 61 72 6B 44...   Const#30  string    "AutoDarkDagger"
		  +DC86:Size=9: 53 61 66 65 5F 4D 6F 64 65      Const#31  string    "Safe_Mode"
		  +DC91:Size=C: 4D 61 73 74 65 72 79 46 72...   Const#32  string    "MasteryFruit"
		  +DC9F:Size=D: 41 75 74 6F 42 75 64 79 53...   Const#33  string    "AutoBudySword"
		  +DCAE:Size=D: 41 75 74 6F 4F 64 65 72 53...   Const#34  string    "AutoOderSword"
		  +DCBD:Size=A: 41 75 74 6F 42 6F 75 6E 74 79   Const#35  string    "AutoBounty"
		  +DCC9:Size=B: 41 75 74 6F 41 6C 6C 42 6F...   Const#36  string    "AutoAllBoss"
		  +DCD6:Size=B: 41 75 74 6F 5F 42 6F 75 6E...   Const#37  string    "Auto_Bounty"
		  +DCE3:Size=C: 41 75 74 6F 53 68 61 72 6B...   Const#38  string    "AutoSharkman"
		  +DCF1:Size=12: 41 75 74 6F 5F 4D 61 73 7...   Const#39  string    "Auto_Mastery_Fruit"
		  +DD05:Size=10: 41 75 74 6F 5F 4D 61 73 7...   Const#40  string    "Auto_Mastery_Gun"
		  +DD17:Size=C: 41 75 74 6F 5F 44 75 6E 67...   Const#41  string    "Auto_Dungeon"
		  +DD25:Size=D: 41 75 74 6F 5F 43 61 76 65...   Const#42  string    "Auto_Cavender"
		  +DD34:Size=9: 41 75 74 6F 5F 50 6F 6C 65      Const#43  string    "Auto_Pole"
		  +DD3F:Size=D: 41 75 74 6F 5F 4B 69 6C 6C...   Const#44  string    "Auto_Kill_Ply"
		  +DD4E:Size=C: 41 75 74 6F 5F 46 61 63 74...   Const#45  string    "Auto_Factory"
		  +DD5C:Size=D: 41 75 74 6F 53 65 63 6F 6E...   Const#46  string    "AutoSecondSea"
		  +DD6B:Size=B: 54 65 6C 65 70 6F 72 74 50...   Const#47  string    "TeleportPly"
		  +DD78:Size=B: 41 75 74 6F 42 61 72 74 69...   Const#48  string    "AutoBartilo"
		  +DD85:Size=D: 41 75 74 6F 5F 44 61 72 6B...   Const#49  string    "Auto_DarkBoss"
		  +DD94:Size=9: 47 72 61 62 43 68 65 73 74      Const#50  string    "GrabChest"
		  +DD9F:Size=E: 41 75 74 6F 46 61 72 6D 42...   Const#51  string    "AutoFarmBounty"
		  +DDAF:Size=A: 48 6F 6C 79 5F 54 6F 72 63 68   Const#52  string    "Holy_Torch"
		  +DDBB:Size=8: 41 75 74 6F 46 61 72 6D         Const#53  string    "AutoFarm"
		  +DDC5:Size=4: 43 6C 69 70                     Const#54  string    "Clip"
		  +DDCB:Size=8: 46 61 72 6D 42 6F 73 73         Const#55  string    "FarmBoss"
		  +DDD5:Size=F: 41 75 74 6F 45 6C 69 74 65...   Const#56  string    "AutoElitehunter"
		  +DDE6:Size=C: 41 75 74 6F 54 68 69 72 64...   Const#57  string    "AutoThirdSea"
		  +DDF4:Size=9: 41 75 74 6F 5F 42 6F 6E 65      Const#58  string    "Auto_Bone"
		  +DDFF:Size=D: 41 75 74 6F 46 61 72 6D 43...   Const#59  string    "AutoFarmCandy"
		  +DE0D:Size=1: 01                              Const#60  boolean   true
		  +DE10:Size=4: 67 61 6D 65                     Const#61  string    "game"
		  +DE16:Size=A: 47 65 74 53 65 72 76 69 63 65   Const#62  string    "GetService"
		  +DE22:Size=7: 50 6C 61 79 65 72 73            Const#63  string    "Players"
		  +DE2B:Size=B: 4C 6F 63 61 6C 50 6C 61 79...   Const#64  string    "LocalPlayer"
		  +DE38:Size=9: 43 68 61 72 61 63 74 65 72      Const#65  string    "Character"
		  +DE43:Size=10: 48 75 6D 61 6E 6F 69 64 5...   Const#66  string    "HumanoidRootPart"
		  +DE55:Size=E: 46 69 6E 64 46 69 72 73 74...   Const#67  string    "FindFirstChild"
		  +DE65:Size=8: 42 6F 64 79 43 6C 69 70         Const#68  string    "BodyClip"
		  +DE6F:Size=8: 49 6E 73 74 61 6E 63 65         Const#69  string    "Instance"
		  +DE79:Size=3: 6E 65 77                        Const#70  string    "new"
		  +DE7E:Size=C: 42 6F 64 79 56 65 6C 6F 63...   Const#71  string    "BodyVelocity"
		  +DE8C:Size=4: 4E 61 6D 65                     Const#72  string    "Name"
		  +DE92:Size=6: 50 61 72 65 6E 74               Const#73  string    "Parent"
		  +DE9A:Size=8: 4D 61 78 46 6F 72 63 65         Const#74  string    "MaxForce"
		  +DEA4:Size=7: 56 65 63 74 6F 72 33            Const#75  string    "Vector3"
		  +DEAC:Size=4: A0 86 01 00                     Const#76  integer   100000
		  +DEB2:Size=8: 56 65 6C 6F 63 69 74 79         Const#77  string    "Velocity"
		  +DEBB:Size=4: 00 00 00 00                     Const#78  integer   0
		Upvalues: 1
		  Upv#1 is parent function's Upv#1              name: _ENV
		Locals: 1
		  Local#1   R0   def:<251>  scope:<252..274>    name: Noclip
		Instructions: 276
		  +D63F: 06 00 40 00   line#1067 GETTABUP 0 0 -1         <1>   R0 = Upv#1@_ENV["wait"]                         -- It's Const#1
		  +D643: 24 80 80 00   line#1067 CALL 0 1 2              <2>   R0 = R0()
		  +D647: 22 00 00 00   line#1067 TEST 0 0                <3>   if R0 then GOTO <5>
		  +D64B: 1E 80 43 80   line#1067 JMP 0 271               <4>   GOTO <276>
		  +D64F: 06 40 40 00   line#1068 GETTABUP 0 0 -2         <5>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
		  +D653: 07 80 40 00   line#1068 GETTABLE 0 0 -3         <6>   R0 = R0["AutoAdvanceDungeon"]                   -- It's Const#3
		  +D657: 22 40 00 00   line#1068 TEST 0 1                <7>   if not R0 then GOTO <9>
		  +D65B: 1E 80 38 80   line#1068 JMP 0 227               <8>   GOTO <236>
		  +D65F: 06 40 40 00   line#1068 GETTABUP 0 0 -2         <9>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
		  +D663: 07 C0 40 00   line#1068 GETTABLE 0 0 -4        <10>   R0 = R0["AutoDoughtBoss"]                       -- It's Const#4
		  +D667: 22 40 00 00   line#1068 TEST 0 1               <11>   if not R0 then GOTO <13>
		  +D66B: 1E 80 37 80   line#1068 JMP 0 223              <12>   GOTO <236>
		  +D66F: 06 40 40 00   line#1068 GETTABUP 0 0 -2        <13>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
		  +D673: 07 00 41 00   line#1068 GETTABLE 0 0 -5        <14>   R0 = R0["Auto_DungeonMobAura"]                  -- It's Const#5
		  +D677: 22 40 00 00   line#1068 TEST 0 1               <15>   if not R0 then GOTO <17>
		  +D67B: 1E 80 36 80   line#1068 JMP 0 219              <16>   GOTO <236>
		  +D67F: 06 40 40 00   line#1068 GETTABUP 0 0 -2        <17>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
		  +D683: 07 40 41 00   line#1068 GETTABLE 0 0 -6        <18>   R0 = R0["AutoFarmChest"]                        -- It's Const#6
		  +D687: 22 40 00 00   line#1068 TEST 0 1               <19>   if not R0 then GOTO <21>
		  +D68B: 1E 80 35 80   line#1068 JMP 0 215              <20>   GOTO <236>
		  +D68F: 06 40 40 00   line#1068 GETTABUP 0 0 -2        <21>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
		  +D693: 07 80 41 00   line#1068 GETTABLE 0 0 -7        <22>   R0 = R0["AutoFarmBossHallow"]                   -- It's Const#7
		  +D697: 22 40 00 00   line#1068 TEST 0 1               <23>   if not R0 then GOTO <25>
		  +D69B: 1E 80 34 80   line#1068 JMP 0 211              <24>   GOTO <236>
		  +D69F: 06 40 40 00   line#1068 GETTABUP 0 0 -2        <25>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
		  +D6A3: 07 C0 41 00   line#1068 GETTABLE 0 0 -8        <26>   R0 = R0["AutoFarmSwanGlasses"]                  -- It's Const#8
		  +D6A7: 22 40 00 00   line#1068 TEST 0 1               <27>   if not R0 then GOTO <29>
		  +D6AB: 1E 80 33 80   line#1068 JMP 0 207              <28>   GOTO <236>
		  +D6AF: 06 40 40 00   line#1068 GETTABUP 0 0 -2        <29>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
		  +D6B3: 07 00 42 00   line#1068 GETTABLE 0 0 -9        <30>   R0 = R0["AutoLongSword"]                        -- It's Const#9
		  +D6B7: 22 40 00 00   line#1068 TEST 0 1               <31>   if not R0 then GOTO <33>
		  +D6BB: 1E 80 32 80   line#1068 JMP 0 203              <32>   GOTO <236>
		  +D6BF: 06 40 40 00   line#1068 GETTABUP 0 0 -2        <33>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
		  +D6C3: 07 40 42 00   line#1068 GETTABLE 0 0 -10       <34>   R0 = R0["AutoBlackSpikeycoat"]                  -- It's Const#10
		  +D6C7: 22 40 00 00   line#1068 TEST 0 1               <35>   if not R0 then GOTO <37>
		  +D6CB: 1E 80 31 80   line#1068 JMP 0 199              <36>   GOTO <236>
		  +D6CF: 06 40 40 00   line#1068 GETTABUP 0 0 -2        <37>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
		  +D6D3: 07 80 42 00   line#1068 GETTABLE 0 0 -11       <38>   R0 = R0["AutoElectricClaw"]                     -- It's Const#11
		  +D6D7: 22 40 00 00   line#1068 TEST 0 1               <39>   if not R0 then GOTO <41>
		  +D6DB: 1E 80 30 80   line#1068 JMP 0 195              <40>   GOTO <236>
		  +D6DF: 06 40 40 00   line#1068 GETTABUP 0 0 -2        <41>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
		  +D6E3: 07 C0 42 00   line#1068 GETTABLE 0 0 -12       <42>   R0 = R0["AutoFarmGunMastery"]                   -- It's Const#12
		  +D6E7: 22 40 00 00   line#1068 TEST 0 1               <43>   if not R0 then GOTO <45>
		  +D6EB: 1E 80 2F 80   line#1068 JMP 0 191              <44>   GOTO <236>
		  +D6EF: 06 40 40 00   line#1068 GETTABUP 0 0 -2        <45>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
		  +D6F3: 07 00 43 00   line#1068 GETTABLE 0 0 -13       <46>   R0 = R0["AutoHolyTorch"]                        -- It's Const#13
		  +D6F7: 22 40 00 00   line#1068 TEST 0 1               <47>   if not R0 then GOTO <49>
		  +D6FB: 1E 80 2E 80   line#1068 JMP 0 187              <48>   GOTO <236>
		  +D6FF: 06 40 40 00   line#1068 GETTABUP 0 0 -2        <49>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
		  +D703: 07 40 43 00   line#1068 GETTABLE 0 0 -14       <50>   R0 = R0["AutoLawRaid"]                          -- It's Const#14
		  +D707: 22 40 00 00   line#1068 TEST 0 1               <51>   if not R0 then GOTO <53>
		  +D70B: 1E 80 2D 80   line#1068 JMP 0 183              <52>   GOTO <236>
		  +D70F: 06 40 40 00   line#1068 GETTABUP 0 0 -2        <53>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
		  +D713: 07 80 43 00   line#1068 GETTABLE 0 0 -15       <54>   R0 = R0["AutoFarmBoss"]                         -- It's Const#15
		  +D717: 22 40 00 00   line#1068 TEST 0 1               <55>   if not R0 then GOTO <57>
		  +D71B: 1E 80 2C 80   line#1068 JMP 0 179              <56>   GOTO <236>
		  +D71F: 06 40 40 00   line#1068 GETTABUP 0 0 -2        <57>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
		  +D723: 07 C0 43 00   line#1068 GETTABLE 0 0 -16       <58>   R0 = R0["AutoTwinHooks"]                        -- It's Const#16
		  +D727: 22 40 00 00   line#1068 TEST 0 1               <59>   if not R0 then GOTO <61>
		  +D72B: 1E 80 2B 80   line#1068 JMP 0 175              <60>   GOTO <236>
		  +D72F: 06 40 40 00   line#1068 GETTABUP 0 0 -2        <61>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
		  +D733: 07 00 44 00   line#1068 GETTABLE 0 0 -17       <62>   R0 = R0["AutoOpenSwanDoor"]                     -- It's Const#17
		  +D737: 22 40 00 00   line#1068 TEST 0 1               <63>   if not R0 then GOTO <65>
		  +D73B: 1E 80 2A 80   line#1068 JMP 0 171              <64>   GOTO <236>
		  +D73F: 06 40 40 00   line#1068 GETTABUP 0 0 -2        <65>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
		  +D743: 07 40 44 00   line#1068 GETTABLE 0 0 -18       <66>   R0 = R0["AutoDragon_Trident"]                   -- It's Const#18
		  +D747: 22 40 00 00   line#1068 TEST 0 1               <67>   if not R0 then GOTO <69>
		  +D74B: 1E 80 29 80   line#1068 JMP 0 167              <68>   GOTO <236>
		  +D74F: 06 40 40 00   line#1068 GETTABUP 0 0 -2        <69>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
		  +D753: 07 80 44 00   line#1068 GETTABLE 0 0 -19       <70>   R0 = R0["AutoSaber"]                            -- It's Const#19
		  +D757: 22 40 00 00   line#1068 TEST 0 1               <71>   if not R0 then GOTO <73>
		  +D75B: 1E 80 28 80   line#1068 JMP 0 163              <72>   GOTO <236>
		  +D75F: 06 40 40 00   line#1068 GETTABUP 0 0 -2        <73>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
		  +D763: 07 C0 44 00   line#1068 GETTABLE 0 0 -20       <74>   R0 = R0["AutoFarmFruitMastery"]                 -- It's Const#20
		  +D767: 22 40 00 00   line#1068 TEST 0 1               <75>   if not R0 then GOTO <77>
		  +D76B: 1E 80 27 80   line#1068 JMP 0 159              <76>   GOTO <236>
		  +D76F: 06 40 40 00   line#1068 GETTABUP 0 0 -2        <77>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
		  +D773: 07 C0 42 00   line#1068 GETTABLE 0 0 -12       <78>   R0 = R0["AutoFarmGunMastery"]                   -- It's Const#12
		  +D777: 22 40 00 00   line#1068 TEST 0 1               <79>   if not R0 then GOTO <81>
		  +D77B: 1E 80 26 80   line#1068 JMP 0 155              <80>   GOTO <236>
		  +D77F: 06 40 40 00   line#1068 GETTABUP 0 0 -2        <81>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
		  +D783: 07 00 45 00   line#1068 GETTABLE 0 0 -21       <82>   R0 = R0["TeleportIsland"]                       -- It's Const#21
		  +D787: 22 40 00 00   line#1068 TEST 0 1               <83>   if not R0 then GOTO <85>
		  +D78B: 1E 80 25 80   line#1068 JMP 0 151              <84>   GOTO <236>
		  +D78F: 06 40 40 00   line#1068 GETTABUP 0 0 -2        <85>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
		  +D793: 07 40 45 00   line#1068 GETTABLE 0 0 -22       <86>   R0 = R0["Auto_EvoRace"]                         -- It's Const#22
		  +D797: 22 40 00 00   line#1068 TEST 0 1               <87>   if not R0 then GOTO <89>
		  +D79B: 1E 80 24 80   line#1068 JMP 0 147              <88>   GOTO <236>
		  +D79F: 06 40 40 00   line#1068 GETTABUP 0 0 -2        <89>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
		  +D7A3: 07 80 45 00   line#1068 GETTABLE 0 0 -23       <90>   R0 = R0["AutoFarmAllMsBypassType"]              -- It's Const#23
		  +D7A7: 22 40 00 00   line#1068 TEST 0 1               <91>   if not R0 then GOTO <93>
		  +D7AB: 1E 80 23 80   line#1068 JMP 0 143              <92>   GOTO <236>
		  +D7AF: 06 40 40 00   line#1068 GETTABUP 0 0 -2        <93>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
		  +D7B3: 07 C0 45 00   line#1068 GETTABLE 0 0 -24       <94>   R0 = R0["AutoObservationv2"]                    -- It's Const#24
		  +D7B7: 22 40 00 00   line#1068 TEST 0 1               <95>   if not R0 then GOTO <97>
		  +D7BB: 1E 80 22 80   line#1068 JMP 0 139              <96>   GOTO <236>
		  +D7BF: 06 40 40 00   line#1068 GETTABUP 0 0 -2        <97>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
		  +D7C3: 07 00 46 00   line#1068 GETTABLE 0 0 -25       <98>   R0 = R0["AutoMusketeerHat"]                     -- It's Const#25
		  +D7C7: 22 40 00 00   line#1068 TEST 0 1               <99>   if not R0 then GOTO <101>
		  +D7CB: 1E 80 21 80   line#1068 JMP 0 135             <100>   GOTO <236>
		  +D7CF: 06 40 40 00   line#1068 GETTABUP 0 0 -2       <101>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
		  +D7D3: 07 40 46 00   line#1068 GETTABLE 0 0 -26      <102>   R0 = R0["AutoEctoplasm"]                        -- It's Const#26
		  +D7D7: 22 40 00 00   line#1068 TEST 0 1              <103>   if not R0 then GOTO <105>
		  +D7DB: 1E 80 20 80   line#1068 JMP 0 131             <104>   GOTO <236>
		  +D7DF: 06 40 40 00   line#1068 GETTABUP 0 0 -2       <105>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
		  +D7E3: 07 80 46 00   line#1068 GETTABLE 0 0 -27      <106>   R0 = R0["AutoRengoku"]                          -- It's Const#27
		  +D7E7: 22 40 00 00   line#1068 TEST 0 1              <107>   if not R0 then GOTO <109>
		  +D7EB: 1E 80 1F 80   line#1068 JMP 0 127             <108>   GOTO <236>
		  +D7EF: 06 40 40 00   line#1068 GETTABUP 0 0 -2       <109>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
		  +D7F3: 07 C0 46 00   line#1068 GETTABLE 0 0 -28      <110>   R0 = R0["Auto_Rainbow_Haki"]                    -- It's Const#28
		  +D7F7: 22 40 00 00   line#1068 TEST 0 1              <111>   if not R0 then GOTO <113>
		  +D7FB: 1E 80 1E 80   line#1068 JMP 0 123             <112>   GOTO <236>
		  +D7FF: 06 40 40 00   line#1068 GETTABUP 0 0 -2       <113>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
		  +D803: 07 00 47 00   line#1068 GETTABLE 0 0 -29      <114>   R0 = R0["AutoObservation"]                      -- It's Const#29
		  +D807: 22 40 00 00   line#1068 TEST 0 1              <115>   if not R0 then GOTO <117>
		  +D80B: 1E 80 1D 80   line#1068 JMP 0 119             <116>   GOTO <236>
		  +D80F: 06 40 40 00   line#1068 GETTABUP 0 0 -2       <117>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
		  +D813: 07 40 47 00   line#1068 GETTABLE 0 0 -30      <118>   R0 = R0["AutoDarkDagger"]                       -- It's Const#30
		  +D817: 22 40 00 00   line#1068 TEST 0 1              <119>   if not R0 then GOTO <121>
		  +D81B: 1E 80 1C 80   line#1068 JMP 0 115             <120>   GOTO <236>
		  +D81F: 06 40 40 00   line#1068 GETTABUP 0 0 -2       <121>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
		  +D823: 07 80 47 00   line#1068 GETTABLE 0 0 -31      <122>   R0 = R0["Safe_Mode"]                            -- It's Const#31
		  +D827: 22 40 00 00   line#1068 TEST 0 1              <123>   if not R0 then GOTO <125>
		  +D82B: 1E 80 1B 80   line#1068 JMP 0 111             <124>   GOTO <236>
		  +D82F: 06 40 40 00   line#1068 GETTABUP 0 0 -2       <125>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
		  +D833: 07 C0 47 00   line#1068 GETTABLE 0 0 -32      <126>   R0 = R0["MasteryFruit"]                         -- It's Const#32
		  +D837: 22 40 00 00   line#1068 TEST 0 1              <127>   if not R0 then GOTO <129>
		  +D83B: 1E 80 1A 80   line#1068 JMP 0 107             <128>   GOTO <236>
		  +D83F: 06 40 40 00   line#1068 GETTABUP 0 0 -2       <129>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
		  +D843: 07 00 48 00   line#1068 GETTABLE 0 0 -33      <130>   R0 = R0["AutoBudySword"]                        -- It's Const#33
		  +D847: 22 40 00 00   line#1068 TEST 0 1              <131>   if not R0 then GOTO <133>
		  +D84B: 1E 80 19 80   line#1068 JMP 0 103             <132>   GOTO <236>
		  +D84F: 06 40 40 00   line#1068 GETTABUP 0 0 -2       <133>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
		  +D853: 07 40 48 00   line#1068 GETTABLE 0 0 -34      <134>   R0 = R0["AutoOderSword"]                        -- It's Const#34
		  +D857: 22 40 00 00   line#1068 TEST 0 1              <135>   if not R0 then GOTO <137>
		  +D85B: 1E 80 18 80   line#1068 JMP 0 99              <136>   GOTO <236>
		  +D85F: 06 40 40 00   line#1068 GETTABUP 0 0 -2       <137>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
		  +D863: 07 80 48 00   line#1068 GETTABLE 0 0 -35      <138>   R0 = R0["AutoBounty"]                           -- It's Const#35
		  +D867: 22 40 00 00   line#1068 TEST 0 1              <139>   if not R0 then GOTO <141>
		  +D86B: 1E 80 17 80   line#1068 JMP 0 95              <140>   GOTO <236>
		  +D86F: 06 40 40 00   line#1068 GETTABUP 0 0 -2       <141>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
		  +D873: 07 C0 48 00   line#1068 GETTABLE 0 0 -36      <142>   R0 = R0["AutoAllBoss"]                          -- It's Const#36
		  +D877: 22 40 00 00   line#1068 TEST 0 1              <143>   if not R0 then GOTO <145>
		  +D87B: 1E 80 16 80   line#1068 JMP 0 91              <144>   GOTO <236>
		  +D87F: 06 40 40 00   line#1068 GETTABUP 0 0 -2       <145>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
		  +D883: 07 00 49 00   line#1068 GETTABLE 0 0 -37      <146>   R0 = R0["Auto_Bounty"]                          -- It's Const#37
		  +D887: 22 40 00 00   line#1068 TEST 0 1              <147>   if not R0 then GOTO <149>
		  +D88B: 1E 80 15 80   line#1068 JMP 0 87              <148>   GOTO <236>
		  +D88F: 06 40 40 00   line#1068 GETTABUP 0 0 -2       <149>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
		  +D893: 07 40 49 00   line#1068 GETTABLE 0 0 -38      <150>   R0 = R0["AutoSharkman"]                         -- It's Const#38
		  +D897: 22 40 00 00   line#1068 TEST 0 1              <151>   if not R0 then GOTO <153>
		  +D89B: 1E 80 14 80   line#1068 JMP 0 83              <152>   GOTO <236>
		  +D89F: 06 40 40 00   line#1068 GETTABUP 0 0 -2       <153>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
		  +D8A3: 07 80 49 00   line#1068 GETTABLE 0 0 -39      <154>   R0 = R0["Auto_Mastery_Fruit"]                   -- It's Const#39
		  +D8A7: 22 40 00 00   line#1068 TEST 0 1              <155>   if not R0 then GOTO <157>
		  +D8AB: 1E 80 13 80   line#1068 JMP 0 79              <156>   GOTO <236>
		  +D8AF: 06 40 40 00   line#1068 GETTABUP 0 0 -2       <157>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
		  +D8B3: 07 C0 49 00   line#1068 GETTABLE 0 0 -40      <158>   R0 = R0["Auto_Mastery_Gun"]                     -- It's Const#40
		  +D8B7: 22 40 00 00   line#1068 TEST 0 1              <159>   if not R0 then GOTO <161>
		  +D8BB: 1E 80 12 80   line#1068 JMP 0 75              <160>   GOTO <236>
		  +D8BF: 06 40 40 00   line#1068 GETTABUP 0 0 -2       <161>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
		  +D8C3: 07 00 4A 00   line#1068 GETTABLE 0 0 -41      <162>   R0 = R0["Auto_Dungeon"]                         -- It's Const#41
		  +D8C7: 22 40 00 00   line#1068 TEST 0 1              <163>   if not R0 then GOTO <165>
		  +D8CB: 1E 80 11 80   line#1068 JMP 0 71              <164>   GOTO <236>
		  +D8CF: 06 40 40 00   line#1068 GETTABUP 0 0 -2       <165>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
		  +D8D3: 07 40 4A 00   line#1068 GETTABLE 0 0 -42      <166>   R0 = R0["Auto_Cavender"]                        -- It's Const#42
		  +D8D7: 22 40 00 00   line#1068 TEST 0 1              <167>   if not R0 then GOTO <169>
		  +D8DB: 1E 80 10 80   line#1068 JMP 0 67              <168>   GOTO <236>
		  +D8DF: 06 40 40 00   line#1068 GETTABUP 0 0 -2       <169>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
		  +D8E3: 07 80 4A 00   line#1068 GETTABLE 0 0 -43      <170>   R0 = R0["Auto_Pole"]                            -- It's Const#43
		  +D8E7: 22 40 00 00   line#1068 TEST 0 1              <171>   if not R0 then GOTO <173>
		  +D8EB: 1E 80 0F 80   line#1068 JMP 0 63              <172>   GOTO <236>
		  +D8EF: 06 40 40 00   line#1068 GETTABUP 0 0 -2       <173>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
		  +D8F3: 07 C0 4A 00   line#1068 GETTABLE 0 0 -44      <174>   R0 = R0["Auto_Kill_Ply"]                        -- It's Const#44
		  +D8F7: 22 40 00 00   line#1068 TEST 0 1              <175>   if not R0 then GOTO <177>
		  +D8FB: 1E 80 0E 80   line#1068 JMP 0 59              <176>   GOTO <236>
		  +D8FF: 06 40 40 00   line#1068 GETTABUP 0 0 -2       <177>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
		  +D903: 07 00 4B 00   line#1068 GETTABLE 0 0 -45      <178>   R0 = R0["Auto_Factory"]                         -- It's Const#45
		  +D907: 22 40 00 00   line#1068 TEST 0 1              <179>   if not R0 then GOTO <181>
		  +D90B: 1E 80 0D 80   line#1068 JMP 0 55              <180>   GOTO <236>
		  +D90F: 06 40 40 00   line#1068 GETTABUP 0 0 -2       <181>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
		  +D913: 07 40 4B 00   line#1068 GETTABLE 0 0 -46      <182>   R0 = R0["AutoSecondSea"]                        -- It's Const#46
		  +D917: 22 40 00 00   line#1068 TEST 0 1              <183>   if not R0 then GOTO <185>
		  +D91B: 1E 80 0C 80   line#1068 JMP 0 51              <184>   GOTO <236>
		  +D91F: 06 40 40 00   line#1068 GETTABUP 0 0 -2       <185>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
		  +D923: 07 80 4B 00   line#1068 GETTABLE 0 0 -47      <186>   R0 = R0["TeleportPly"]                          -- It's Const#47
		  +D927: 22 40 00 00   line#1068 TEST 0 1              <187>   if not R0 then GOTO <189>
		  +D92B: 1E 80 0B 80   line#1068 JMP 0 47              <188>   GOTO <236>
		  +D92F: 06 40 40 00   line#1068 GETTABUP 0 0 -2       <189>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
		  +D933: 07 C0 4B 00   line#1068 GETTABLE 0 0 -48      <190>   R0 = R0["AutoBartilo"]                          -- It's Const#48
		  +D937: 22 40 00 00   line#1068 TEST 0 1              <191>   if not R0 then GOTO <193>
		  +D93B: 1E 80 0A 80   line#1068 JMP 0 43              <192>   GOTO <236>
		  +D93F: 06 40 40 00   line#1068 GETTABUP 0 0 -2       <193>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
		  +D943: 07 00 4C 00   line#1068 GETTABLE 0 0 -49      <194>   R0 = R0["Auto_DarkBoss"]                        -- It's Const#49
		  +D947: 22 40 00 00   line#1068 TEST 0 1              <195>   if not R0 then GOTO <197>
		  +D94B: 1E 80 09 80   line#1068 JMP 0 39              <196>   GOTO <236>
		  +D94F: 06 40 40 00   line#1068 GETTABUP 0 0 -2       <197>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
		  +D953: 07 40 4C 00   line#1068 GETTABLE 0 0 -50      <198>   R0 = R0["GrabChest"]                            -- It's Const#50
		  +D957: 22 40 00 00   line#1068 TEST 0 1              <199>   if not R0 then GOTO <201>
		  +D95B: 1E 80 08 80   line#1068 JMP 0 35              <200>   GOTO <236>
		  +D95F: 06 40 40 00   line#1068 GETTABUP 0 0 -2       <201>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
		  +D963: 07 80 4C 00   line#1068 GETTABLE 0 0 -51      <202>   R0 = R0["AutoFarmBounty"]                       -- It's Const#51
		  +D967: 22 40 00 00   line#1068 TEST 0 1              <203>   if not R0 then GOTO <205>
		  +D96B: 1E 80 07 80   line#1068 JMP 0 31              <204>   GOTO <236>
		  +D96F: 06 40 40 00   line#1068 GETTABUP 0 0 -2       <205>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
		  +D973: 07 C0 4C 00   line#1068 GETTABLE 0 0 -52      <206>   R0 = R0["Holy_Torch"]                           -- It's Const#52
		  +D977: 22 40 00 00   line#1068 TEST 0 1              <207>   if not R0 then GOTO <209>
		  +D97B: 1E 80 06 80   line#1068 JMP 0 27              <208>   GOTO <236>
		  +D97F: 06 40 40 00   line#1068 GETTABUP 0 0 -2       <209>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
		  +D983: 07 00 4D 00   line#1068 GETTABLE 0 0 -53      <210>   R0 = R0["AutoFarm"]                             -- It's Const#53
		  +D987: 22 40 00 00   line#1068 TEST 0 1              <211>   if not R0 then GOTO <213>
		  +D98B: 1E 80 05 80   line#1068 JMP 0 23              <212>   GOTO <236>
		  +D98F: 06 40 40 00   line#1068 GETTABUP 0 0 -2       <213>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
		  +D993: 07 40 4D 00   line#1068 GETTABLE 0 0 -54      <214>   R0 = R0["Clip"]                                 -- It's Const#54
		  +D997: 22 40 00 00   line#1068 TEST 0 1              <215>   if not R0 then GOTO <217>
		  +D99B: 1E 80 04 80   line#1068 JMP 0 19              <216>   GOTO <236>
		  +D99F: 06 80 4D 00   line#1068 GETTABUP 0 0 -55      <217>   R0 = Upv#1@_ENV["FarmBoss"]                     -- It's Const#55
		  +D9A3: 22 40 00 00   line#1068 TEST 0 1              <218>   if not R0 then GOTO <220>
		  +D9A7: 1E C0 03 80   line#1068 JMP 0 16              <219>   GOTO <236>
		  +D9AB: 06 40 40 00   line#1068 GETTABUP 0 0 -2       <220>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
		  +D9AF: 07 C0 4D 00   line#1068 GETTABLE 0 0 -56      <221>   R0 = R0["AutoElitehunter"]                      -- It's Const#56
		  +D9B3: 22 40 00 00   line#1068 TEST 0 1              <222>   if not R0 then GOTO <224>
		  +D9B7: 1E C0 02 80   line#1068 JMP 0 12              <223>   GOTO <236>
		  +D9BB: 06 40 40 00   line#1068 GETTABUP 0 0 -2       <224>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
		  +D9BF: 07 00 4E 00   line#1068 GETTABLE 0 0 -57      <225>   R0 = R0["AutoThirdSea"]                         -- It's Const#57
		  +D9C3: 22 40 00 00   line#1068 TEST 0 1              <226>   if not R0 then GOTO <228>
		  +D9C7: 1E C0 01 80   line#1068 JMP 0 8               <227>   GOTO <236>
		  +D9CB: 06 40 40 00   line#1068 GETTABUP 0 0 -2       <228>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
		  +D9CF: 07 40 4E 00   line#1068 GETTABLE 0 0 -58      <229>   R0 = R0["Auto_Bone"]                            -- It's Const#58
		  +D9D3: 22 40 00 00   line#1068 TEST 0 1              <230>   if not R0 then GOTO <232>
		  +D9D7: 1E C0 00 80   line#1068 JMP 0 4               <231>   GOTO <236>
		  +D9DB: 06 40 40 00   line#1068 GETTABUP 0 0 -2       <232>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
		  +D9DF: 07 80 4E 00   line#1068 GETTABLE 0 0 -59      <233>   R0 = R0["AutoFarmCandy"]                        -- It's Const#59
		  +D9E3: 1F C0 4E 00   line#1068 EQ 0 0 -60            <234>   if R0 == true then GOTO <236>                   -- It's Const#60
		  +D9E7: 1E 00 C5 7F   line#1068 JMP 0 -235            <235>   GOTO <1>
		  +D9EB: 06 00 4F 00   line#1069 GETTABUP 0 0 -61      <236>   R0 = Upv#1@_ENV["game"]                         -- It's Const#61
		  +D9EF: 0C 40 4F 00   line#1069 SELF 0 0 -62          <237>   R1 = R0;  R0 = R0["GetService"]                 -- It's Const#62   -- prepare for R0:GetService()
		  +D9F3: 81 80 0F 00   line#1069 LOADK 2 -63           <238>   R2 = "Players"                                  -- It's Const#63
		  +D9F7: 24 80 80 01   line#1069 CALL 0 3 2            <239>   R0 = R0(R1, R2)
		  +D9FB: 07 C0 4F 00   line#1069 GETTABLE 0 0 -64      <240>   R0 = R0["LocalPlayer"]                          -- It's Const#64
		  +D9FF: 07 00 50 00   line#1069 GETTABLE 0 0 -65      <241>   R0 = R0["Character"]                            -- It's Const#65
		  +DA03: 07 40 50 00   line#1069 GETTABLE 0 0 -66      <242>   R0 = R0["HumanoidRootPart"]                     -- It's Const#66
		  +DA07: 0C 80 50 00   line#1069 SELF 0 0 -67          <243>   R1 = R0;  R0 = R0["FindFirstChild"]             -- It's Const#67   -- prepare for R0:FindFirstChild()
		  +DA0B: 81 C0 10 00   line#1069 LOADK 2 -68           <244>   R2 = "BodyClip"                                 -- It's Const#68
		  +DA0F: 24 80 80 01   line#1069 CALL 0 3 2            <245>   R0 = R0(R1, R2)
		  +DA13: 22 40 00 00   line#1069 TEST 0 1              <246>   if not R0 then GOTO <248>
		  +DA17: 1E 00 C2 7F   line#1069 JMP 0 -247            <247>   GOTO <1>
		  +DA1B: 06 00 51 00   line#1070 GETTABUP 0 0 -69      <248>   R0 = Upv#1@_ENV["Instance"]                     -- It's Const#69
		  +DA1F: 07 40 51 00   line#1070 GETTABLE 0 0 -70      <249>   R0 = R0["new"]                                  -- It's Const#70
		  +DA23: 41 80 11 00   line#1070 LOADK 1 -71           <250>   R1 = "BodyVelocity"                             -- It's Const#71
		  +DA27: 24 80 00 01   line#1070 CALL 0 2 2            <251>   R0@Noclip = R0(R1)
		  +DA2B: 0A C0 D0 A3   line#1071 SETTABLE 0 -72 -68    <252>   R0@Noclip["Name"] = "BodyClip"                  -- It's Const#72, Const#68
		  +DA2F: 46 00 4F 00   line#1072 GETTABUP 1 0 -61      <253>   R1 = Upv#1@_ENV["game"]                         -- It's Const#61
		  +DA33: 4C 40 CF 00   line#1072 SELF 1 1 -62          <254>   R2 = R1;  R1 = R1["GetService"]                 -- It's Const#62   -- prepare for R1:GetService()
		  +DA37: C1 80 0F 00   line#1072 LOADK 3 -63           <255>   R3 = "Players"                                  -- It's Const#63
		  +DA3B: 64 80 80 01   line#1072 CALL 1 3 2            <256>   R1 = R1(R2, R3)
		  +DA3F: 47 C0 CF 00   line#1072 GETTABLE 1 1 -64      <257>   R1 = R1["LocalPlayer"]                          -- It's Const#64
		  +DA43: 47 00 D0 00   line#1072 GETTABLE 1 1 -65      <258>   R1 = R1["Character"]                            -- It's Const#65
		  +DA47: 47 40 D0 00   line#1072 GETTABLE 1 1 -66      <259>   R1 = R1["HumanoidRootPart"]                     -- It's Const#66
		  +DA4B: 0A 40 00 A4   line#1072 SETTABLE 0 -73 1      <260>   R0@Noclip["Parent"] = R1                        -- It's Const#73
		  +DA4F: 46 80 52 00   line#1073 GETTABUP 1 0 -75      <261>   R1 = Upv#1@_ENV["Vector3"]                      -- It's Const#75
		  +DA53: 47 40 D1 00   line#1073 GETTABLE 1 1 -70      <262>   R1 = R1["new"]                                  -- It's Const#70
		  +DA57: 81 C0 12 00   line#1073 LOADK 2 -76           <263>   R2 = 100000                                     -- It's Const#76
		  +DA5B: C1 C0 12 00   line#1073 LOADK 3 -76           <264>   R3 = 100000                                     -- It's Const#76
		  +DA5F: 01 C1 12 00   line#1073 LOADK 4 -76           <265>   R4 = 100000                                     -- It's Const#76
		  +DA63: 64 80 00 02   line#1073 CALL 1 4 2            <266>   R1 = R1(R2, R3, R4)
		  +DA67: 0A 40 80 A4   line#1073 SETTABLE 0 -74 1      <267>   R0@Noclip["MaxForce"] = R1                      -- It's Const#74
		  +DA6B: 46 80 52 00   line#1074 GETTABUP 1 0 -75      <268>   R1 = Upv#1@_ENV["Vector3"]                      -- It's Const#75
		  +DA6F: 47 40 D1 00   line#1074 GETTABLE 1 1 -70      <269>   R1 = R1["new"]                                  -- It's Const#70
		  +DA73: 81 40 13 00   line#1074 LOADK 2 -78           <270>   R2 = 0                                          -- It's Const#78
		  +DA77: C1 40 13 00   line#1074 LOADK 3 -78           <271>   R3 = 0                                          -- It's Const#78
		  +DA7B: 01 41 13 00   line#1074 LOADK 4 -78           <272>   R4 = 0                                          -- It's Const#78
		  +DA7F: 64 80 00 02   line#1074 CALL 1 4 2            <273>   R1 = R1(R2, R3, R4)
		  +DA83: 0A 40 00 A6   line#1074 SETTABLE 0 -77 1      <274>   R0@Noclip["Velocity"] = R1                      -- It's Const#77
		  +DA87: 1E 00 BB 7F   line#1076 JMP 0 -275            <275>   GOTO <1>
		  +DA8B: 26 00 80 00   line#1078 RETURN 0 1            <276>   RETURN
		Functions: 0

	************ Function#24   (full path: main.24)
	Source line#: 1081..1093
	Parameters: 0
	Is vararg: no
	VM registers needed: 2
	Constants: 1
	  +E380:Size=5: 70 63 61 6C 6C                  Const#1   string    "pcall"
	Upvalues: 1
	  Upv#1 is parent function's Upv#1              name: _ENV
	Instructions: 4
	  +E36A: 06 00 40 00   line#1082 GETTABUP 0 0 -1         <1>   R0 = Upv#1@_ENV["pcall"]                        -- It's Const#1
	  +E36E: 6C 00 00 00   line#1092 CLOSURE 1 0             <2>   R1 = Function#1
	  +E372: 24 40 00 01   line#1082 CALL 0 2 1              <3>   R0(R1)
	  +E376: 26 00 80 00   line#1093 RETURN 0 1              <4>   RETURN
	Functions: 1

		************ Function#1   (full path: main.24.1)
		Source line#: 1082..1092
		Parameters: 0
		Is vararg: no
		VM registers needed: 3
		Constants: 5
		  +E3C9:Size=4: 67 61 6D 65                     Const#1   string    "game"
		  +E3CF:Size=A: 47 65 74 53 65 72 76 69 63 65   Const#2   string    "GetService"
		  +E3DB:Size=A: 52 75 6E 53 65 72 76 69 63 65   Const#3   string    "RunService"
		  +E3E7:Size=7: 53 74 65 70 70 65 64            Const#4   string    "Stepped"
		  +E3F0:Size=7: 43 6F 6E 6E 65 63 74            Const#5   string    "Connect"
		Upvalues: 1
		  Upv#1 is parent function's Upv#1              name: _ENV
		Instructions: 9
		  +E39F: 06 00 40 00   line#1083 GETTABUP 0 0 -1         <1>   R0 = Upv#1@_ENV["game"]                         -- It's Const#1
		  +E3A3: 0C 40 40 00   line#1083 SELF 0 0 -2             <2>   R1 = R0;  R0 = R0["GetService"]                 -- It's Const#2   -- prepare for R0:GetService()
		  +E3A7: 81 80 00 00   line#1083 LOADK 2 -3              <3>   R2 = "RunService"                               -- It's Const#3
		  +E3AB: 24 80 80 01   line#1083 CALL 0 3 2              <4>   R0 = R0(R1, R2)
		  +E3AF: 07 C0 40 00   line#1083 GETTABLE 0 0 -4         <5>   R0 = R0["Stepped"]                              -- It's Const#4
		  +E3B3: 0C 00 41 00   line#1083 SELF 0 0 -5             <6>   R1 = R0;  R0 = R0["Connect"]                    -- It's Const#5   -- prepare for R0:Connect()
		  +E3B7: AC 00 00 00   line#1091 CLOSURE 2 0             <7>   R2 = Function#1
		  +E3BB: 24 40 80 01   line#1083 CALL 0 3 1              <8>   R0(R1, R2)
		  +E3BF: 26 00 80 00   line#1092 RETURN 0 1              <9>   RETURN
		Functions: 1

			************ Function#1   (full path: main.24.1.1)
			Source line#: 1083..1091
			Parameters: 0
			Is vararg: no
			VM registers needed: 8
			Constants: 70
			  +E807:Size=2: 5F 47                           Const#1   string    "_G"
			  +E80B:Size=12: 41 75 74 6F 41 64 76 61 6...   Const#2   string    "AutoAdvanceDungeon"
			  +E81F:Size=E: 41 75 74 6F 44 6F 75 67 68...   Const#3   string    "AutoDoughtBoss"
			  +E82F:Size=13: 41 75 74 6F 5F 44 75 6E 6...   Const#4   string    "Auto_DungeonMobAura"
			  +E844:Size=D: 41 75 74 6F 46 61 72 6D 43...   Const#5   string    "AutoFarmChest"
			  +E853:Size=12: 41 75 74 6F 46 61 72 6D 4...   Const#6   string    "AutoFarmBossHallow"
			  +E867:Size=13: 41 75 74 6F 46 61 72 6D 5...   Const#7   string    "AutoFarmSwanGlasses"
			  +E87C:Size=D: 41 75 74 6F 4C 6F 6E 67 53...   Const#8   string    "AutoLongSword"
			  +E88B:Size=13: 41 75 74 6F 42 6C 61 63 6...   Const#9   string    "AutoBlackSpikeycoat"
			  +E8A0:Size=10: 41 75 74 6F 45 6C 65 63 7...   Const#10  string    "AutoElectricClaw"
			  +E8B2:Size=12: 41 75 74 6F 46 61 72 6D 4...   Const#11  string    "AutoFarmGunMastery"
			  +E8C6:Size=D: 41 75 74 6F 48 6F 6C 79 54...   Const#12  string    "AutoHolyTorch"
			  +E8D5:Size=B: 41 75 74 6F 4C 61 77 52 61...   Const#13  string    "AutoLawRaid"
			  +E8E2:Size=C: 41 75 74 6F 46 61 72 6D 42...   Const#14  string    "AutoFarmBoss"
			  +E8F0:Size=D: 41 75 74 6F 54 77 69 6E 48...   Const#15  string    "AutoTwinHooks"
			  +E8FF:Size=10: 41 75 74 6F 4F 70 65 6E 5...   Const#16  string    "AutoOpenSwanDoor"
			  +E911:Size=12: 41 75 74 6F 44 72 61 67 6...   Const#17  string    "AutoDragon_Trident"
			  +E925:Size=9: 41 75 74 6F 53 61 62 65 72      Const#18  string    "AutoSaber"
			  +E930:Size=6: 4E 4F 43 4C 49 50               Const#19  string    "NOCLIP"
			  +E938:Size=14: 41 75 74 6F 46 61 72 6D 4...   Const#20  string    "AutoFarmFruitMastery"
			  +E94E:Size=E: 54 65 6C 65 70 6F 72 74 49...   Const#21  string    "TeleportIsland"
			  +E95E:Size=C: 41 75 74 6F 5F 45 76 6F 52...   Const#22  string    "Auto_EvoRace"
			  +E96C:Size=17: 41 75 74 6F 46 61 72 6D 4...   Const#23  string    "AutoFarmAllMsBypassType"
			  +E985:Size=11: 41 75 74 6F 4F 62 73 65 7...   Const#24  string    "AutoObservationv2"
			  +E998:Size=10: 41 75 74 6F 4D 75 73 6B 6...   Const#25  string    "AutoMusketeerHat"
			  +E9AA:Size=D: 41 75 74 6F 45 63 74 6F 70...   Const#26  string    "AutoEctoplasm"
			  +E9B9:Size=B: 41 75 74 6F 52 65 6E 67 6F...   Const#27  string    "AutoRengoku"
			  +E9C6:Size=11: 41 75 74 6F 5F 52 61 69 6...   Const#28  string    "Auto_Rainbow_Haki"
			  +E9D9:Size=F: 41 75 74 6F 4F 62 73 65 72...   Const#29  string    "AutoObservation"
			  +E9EA:Size=E: 41 75 74 6F 44 61 72 6B 44...   Const#30  string    "AutoDarkDagger"
			  +E9FA:Size=9: 53 61 66 65 5F 4D 6F 64 65      Const#31  string    "Safe_Mode"
			  +EA05:Size=C: 4D 61 73 74 65 72 79 46 72...   Const#32  string    "MasteryFruit"
			  +EA13:Size=D: 41 75 74 6F 42 75 64 79 53...   Const#33  string    "AutoBudySword"
			  +EA22:Size=D: 41 75 74 6F 4F 64 65 72 53...   Const#34  string    "AutoOderSword"
			  +EA31:Size=A: 41 75 74 6F 42 6F 75 6E 74 79   Const#35  string    "AutoBounty"
			  +EA3D:Size=B: 41 75 74 6F 41 6C 6C 42 6F...   Const#36  string    "AutoAllBoss"
			  +EA4A:Size=B: 41 75 74 6F 5F 42 6F 75 6E...   Const#37  string    "Auto_Bounty"
			  +EA57:Size=C: 41 75 74 6F 53 68 61 72 6B...   Const#38  string    "AutoSharkman"
			  +EA65:Size=12: 41 75 74 6F 5F 4D 61 73 7...   Const#39  string    "Auto_Mastery_Fruit"
			  +EA79:Size=10: 41 75 74 6F 5F 4D 61 73 7...   Const#40  string    "Auto_Mastery_Gun"
			  +EA8B:Size=C: 41 75 74 6F 5F 44 75 6E 67...   Const#41  string    "Auto_Dungeon"
			  +EA99:Size=D: 41 75 74 6F 5F 43 61 76 65...   Const#42  string    "Auto_Cavender"
			  +EAA8:Size=9: 41 75 74 6F 5F 50 6F 6C 65      Const#43  string    "Auto_Pole"
			  +EAB3:Size=D: 41 75 74 6F 5F 4B 69 6C 6C...   Const#44  string    "Auto_Kill_Ply"
			  +EAC2:Size=C: 41 75 74 6F 5F 46 61 63 74...   Const#45  string    "Auto_Factory"
			  +EAD0:Size=D: 41 75 74 6F 53 65 63 6F 6E...   Const#46  string    "AutoSecondSea"
			  +EADF:Size=B: 54 65 6C 65 70 6F 72 74 50...   Const#47  string    "TeleportPly"
			  +EAEC:Size=B: 41 75 74 6F 42 61 72 74 69...   Const#48  string    "AutoBartilo"
			  +EAF9:Size=D: 41 75 74 6F 5F 44 61 72 6B...   Const#49  string    "Auto_DarkBoss"
			  +EB08:Size=9: 47 72 61 62 43 68 65 73 74      Const#50  string    "GrabChest"
			  +EB13:Size=E: 41 75 74 6F 46 61 72 6D 42...   Const#51  string    "AutoFarmBounty"
			  +EB23:Size=A: 48 6F 6C 79 5F 54 6F 72 63 68   Const#52  string    "Holy_Torch"
			  +EB2F:Size=8: 41 75 74 6F 46 61 72 6D         Const#53  string    "AutoFarm"
			  +EB39:Size=4: 43 6C 69 70                     Const#54  string    "Clip"
			  +EB3F:Size=F: 41 75 74 6F 45 6C 69 74 65...   Const#55  string    "AutoElitehunter"
			  +EB50:Size=C: 41 75 74 6F 54 68 69 72 64...   Const#56  string    "AutoThirdSea"
			  +EB5E:Size=9: 41 75 74 6F 5F 42 6F 6E 65      Const#57  string    "Auto_Bone"
			  +EB69:Size=D: 41 75 74 6F 46 61 72 6D 43...   Const#58  string    "AutoFarmCandy"
			  +EB77:Size=1: 01                              Const#59  boolean   true
			  +EB7A:Size=5: 70 61 69 72 73                  Const#60  string    "pairs"
			  +EB81:Size=4: 67 61 6D 65                     Const#61  string    "game"
			  +EB87:Size=A: 47 65 74 53 65 72 76 69 63 65   Const#62  string    "GetService"
			  +EB93:Size=7: 50 6C 61 79 65 72 73            Const#63  string    "Players"
			  +EB9C:Size=B: 4C 6F 63 61 6C 50 6C 61 79...   Const#64  string    "LocalPlayer"
			  +EBA9:Size=9: 43 68 61 72 61 63 74 65 72      Const#65  string    "Character"
			  +EBB4:Size=E: 47 65 74 44 65 73 63 65 6E...   Const#66  string    "GetDescendants"
			  +EBC4:Size=3: 49 73 41                        Const#67  string    "IsA"
			  +EBC9:Size=8: 42 61 73 65 50 61 72 74         Const#68  string    "BasePart"
			  +EBD3:Size=A: 43 61 6E 43 6F 6C 6C 69 64 65   Const#69  string    "CanCollide"
			  +EBDE:Size=1: 00                              Const#70  boolean   false
			Upvalues: 1
			  Upv#1 is parent function's Upv#1              name: _ENV
			Locals: 5
			  Local#1   R0   def:<242>  scope:<243..251>    name: (for generator)
			  Local#2   R1   def:<242>  scope:<243..251>    name: (for state)
			  Local#3   R2   def:<242>  scope:<243..251>    name: (for control)
			  Local#4   R3   def:<243>  scope:<244..249>    name: _
			  Local#5   R4   def:<243>  scope:<244..249>    name: v
			Instructions: 252
			  +E411: 06 00 40 00   line#1084 GETTABUP 0 0 -1         <1>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#1
			  +E415: 07 40 40 00   line#1084 GETTABLE 0 0 -2         <2>   R0 = R0["AutoAdvanceDungeon"]                   -- It's Const#2
			  +E419: 22 40 00 00   line#1084 TEST 0 1                <3>   if not R0 then GOTO <5>
			  +E41D: 1E C0 38 80   line#1084 JMP 0 228               <4>   GOTO <233>
			  +E421: 06 00 40 00   line#1084 GETTABUP 0 0 -1         <5>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#1
			  +E425: 07 80 40 00   line#1084 GETTABLE 0 0 -3         <6>   R0 = R0["AutoDoughtBoss"]                       -- It's Const#3
			  +E429: 22 40 00 00   line#1084 TEST 0 1                <7>   if not R0 then GOTO <9>
			  +E42D: 1E C0 37 80   line#1084 JMP 0 224               <8>   GOTO <233>
			  +E431: 06 00 40 00   line#1084 GETTABUP 0 0 -1         <9>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#1
			  +E435: 07 C0 40 00   line#1084 GETTABLE 0 0 -4        <10>   R0 = R0["Auto_DungeonMobAura"]                  -- It's Const#4
			  +E439: 22 40 00 00   line#1084 TEST 0 1               <11>   if not R0 then GOTO <13>
			  +E43D: 1E C0 36 80   line#1084 JMP 0 220              <12>   GOTO <233>
			  +E441: 06 00 40 00   line#1084 GETTABUP 0 0 -1        <13>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#1
			  +E445: 07 00 41 00   line#1084 GETTABLE 0 0 -5        <14>   R0 = R0["AutoFarmChest"]                        -- It's Const#5
			  +E449: 22 40 00 00   line#1084 TEST 0 1               <15>   if not R0 then GOTO <17>
			  +E44D: 1E C0 35 80   line#1084 JMP 0 216              <16>   GOTO <233>
			  +E451: 06 00 40 00   line#1084 GETTABUP 0 0 -1        <17>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#1
			  +E455: 07 40 41 00   line#1084 GETTABLE 0 0 -6        <18>   R0 = R0["AutoFarmBossHallow"]                   -- It's Const#6
			  +E459: 22 40 00 00   line#1084 TEST 0 1               <19>   if not R0 then GOTO <21>
			  +E45D: 1E C0 34 80   line#1084 JMP 0 212              <20>   GOTO <233>
			  +E461: 06 00 40 00   line#1084 GETTABUP 0 0 -1        <21>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#1
			  +E465: 07 80 41 00   line#1084 GETTABLE 0 0 -7        <22>   R0 = R0["AutoFarmSwanGlasses"]                  -- It's Const#7
			  +E469: 22 40 00 00   line#1084 TEST 0 1               <23>   if not R0 then GOTO <25>
			  +E46D: 1E C0 33 80   line#1084 JMP 0 208              <24>   GOTO <233>
			  +E471: 06 00 40 00   line#1084 GETTABUP 0 0 -1        <25>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#1
			  +E475: 07 C0 41 00   line#1084 GETTABLE 0 0 -8        <26>   R0 = R0["AutoLongSword"]                        -- It's Const#8
			  +E479: 22 40 00 00   line#1084 TEST 0 1               <27>   if not R0 then GOTO <29>
			  +E47D: 1E C0 32 80   line#1084 JMP 0 204              <28>   GOTO <233>
			  +E481: 06 00 40 00   line#1084 GETTABUP 0 0 -1        <29>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#1
			  +E485: 07 00 42 00   line#1084 GETTABLE 0 0 -9        <30>   R0 = R0["AutoBlackSpikeycoat"]                  -- It's Const#9
			  +E489: 22 40 00 00   line#1084 TEST 0 1               <31>   if not R0 then GOTO <33>
			  +E48D: 1E C0 31 80   line#1084 JMP 0 200              <32>   GOTO <233>
			  +E491: 06 00 40 00   line#1084 GETTABUP 0 0 -1        <33>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#1
			  +E495: 07 40 42 00   line#1084 GETTABLE 0 0 -10       <34>   R0 = R0["AutoElectricClaw"]                     -- It's Const#10
			  +E499: 22 40 00 00   line#1084 TEST 0 1               <35>   if not R0 then GOTO <37>
			  +E49D: 1E C0 30 80   line#1084 JMP 0 196              <36>   GOTO <233>
			  +E4A1: 06 00 40 00   line#1084 GETTABUP 0 0 -1        <37>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#1
			  +E4A5: 07 80 42 00   line#1084 GETTABLE 0 0 -11       <38>   R0 = R0["AutoFarmGunMastery"]                   -- It's Const#11
			  +E4A9: 22 40 00 00   line#1084 TEST 0 1               <39>   if not R0 then GOTO <41>
			  +E4AD: 1E C0 2F 80   line#1084 JMP 0 192              <40>   GOTO <233>
			  +E4B1: 06 00 40 00   line#1084 GETTABUP 0 0 -1        <41>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#1
			  +E4B5: 07 C0 42 00   line#1084 GETTABLE 0 0 -12       <42>   R0 = R0["AutoHolyTorch"]                        -- It's Const#12
			  +E4B9: 22 40 00 00   line#1084 TEST 0 1               <43>   if not R0 then GOTO <45>
			  +E4BD: 1E C0 2E 80   line#1084 JMP 0 188              <44>   GOTO <233>
			  +E4C1: 06 00 40 00   line#1084 GETTABUP 0 0 -1        <45>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#1
			  +E4C5: 07 00 43 00   line#1084 GETTABLE 0 0 -13       <46>   R0 = R0["AutoLawRaid"]                          -- It's Const#13
			  +E4C9: 22 40 00 00   line#1084 TEST 0 1               <47>   if not R0 then GOTO <49>
			  +E4CD: 1E C0 2D 80   line#1084 JMP 0 184              <48>   GOTO <233>
			  +E4D1: 06 00 40 00   line#1084 GETTABUP 0 0 -1        <49>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#1
			  +E4D5: 07 40 43 00   line#1084 GETTABLE 0 0 -14       <50>   R0 = R0["AutoFarmBoss"]                         -- It's Const#14
			  +E4D9: 22 40 00 00   line#1084 TEST 0 1               <51>   if not R0 then GOTO <53>
			  +E4DD: 1E C0 2C 80   line#1084 JMP 0 180              <52>   GOTO <233>
			  +E4E1: 06 00 40 00   line#1084 GETTABUP 0 0 -1        <53>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#1
			  +E4E5: 07 80 43 00   line#1084 GETTABLE 0 0 -15       <54>   R0 = R0["AutoTwinHooks"]                        -- It's Const#15
			  +E4E9: 22 40 00 00   line#1084 TEST 0 1               <55>   if not R0 then GOTO <57>
			  +E4ED: 1E C0 2B 80   line#1084 JMP 0 176              <56>   GOTO <233>
			  +E4F1: 06 00 40 00   line#1084 GETTABUP 0 0 -1        <57>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#1
			  +E4F5: 07 C0 43 00   line#1084 GETTABLE 0 0 -16       <58>   R0 = R0["AutoOpenSwanDoor"]                     -- It's Const#16
			  +E4F9: 22 40 00 00   line#1084 TEST 0 1               <59>   if not R0 then GOTO <61>
			  +E4FD: 1E C0 2A 80   line#1084 JMP 0 172              <60>   GOTO <233>
			  +E501: 06 00 40 00   line#1084 GETTABUP 0 0 -1        <61>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#1
			  +E505: 07 00 44 00   line#1084 GETTABLE 0 0 -17       <62>   R0 = R0["AutoDragon_Trident"]                   -- It's Const#17
			  +E509: 22 40 00 00   line#1084 TEST 0 1               <63>   if not R0 then GOTO <65>
			  +E50D: 1E C0 29 80   line#1084 JMP 0 168              <64>   GOTO <233>
			  +E511: 06 00 40 00   line#1084 GETTABUP 0 0 -1        <65>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#1
			  +E515: 07 40 44 00   line#1084 GETTABLE 0 0 -18       <66>   R0 = R0["AutoSaber"]                            -- It's Const#18
			  +E519: 22 40 00 00   line#1084 TEST 0 1               <67>   if not R0 then GOTO <69>
			  +E51D: 1E C0 28 80   line#1084 JMP 0 164              <68>   GOTO <233>
			  +E521: 06 00 40 00   line#1084 GETTABUP 0 0 -1        <69>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#1
			  +E525: 07 80 44 00   line#1084 GETTABLE 0 0 -19       <70>   R0 = R0["NOCLIP"]                               -- It's Const#19
			  +E529: 22 40 00 00   line#1084 TEST 0 1               <71>   if not R0 then GOTO <73>
			  +E52D: 1E C0 27 80   line#1084 JMP 0 160              <72>   GOTO <233>
			  +E531: 06 00 40 00   line#1084 GETTABUP 0 0 -1        <73>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#1
			  +E535: 07 C0 44 00   line#1084 GETTABLE 0 0 -20       <74>   R0 = R0["AutoFarmFruitMastery"]                 -- It's Const#20
			  +E539: 22 40 00 00   line#1084 TEST 0 1               <75>   if not R0 then GOTO <77>
			  +E53D: 1E C0 26 80   line#1084 JMP 0 156              <76>   GOTO <233>
			  +E541: 06 00 40 00   line#1084 GETTABUP 0 0 -1        <77>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#1
			  +E545: 07 80 42 00   line#1084 GETTABLE 0 0 -11       <78>   R0 = R0["AutoFarmGunMastery"]                   -- It's Const#11
			  +E549: 22 40 00 00   line#1084 TEST 0 1               <79>   if not R0 then GOTO <81>
			  +E54D: 1E C0 25 80   line#1084 JMP 0 152              <80>   GOTO <233>
			  +E551: 06 00 40 00   line#1084 GETTABUP 0 0 -1        <81>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#1
			  +E555: 07 00 45 00   line#1084 GETTABLE 0 0 -21       <82>   R0 = R0["TeleportIsland"]                       -- It's Const#21
			  +E559: 22 40 00 00   line#1084 TEST 0 1               <83>   if not R0 then GOTO <85>
			  +E55D: 1E C0 24 80   line#1084 JMP 0 148              <84>   GOTO <233>
			  +E561: 06 00 40 00   line#1084 GETTABUP 0 0 -1        <85>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#1
			  +E565: 07 40 45 00   line#1084 GETTABLE 0 0 -22       <86>   R0 = R0["Auto_EvoRace"]                         -- It's Const#22
			  +E569: 22 40 00 00   line#1084 TEST 0 1               <87>   if not R0 then GOTO <89>
			  +E56D: 1E C0 23 80   line#1084 JMP 0 144              <88>   GOTO <233>
			  +E571: 06 00 40 00   line#1084 GETTABUP 0 0 -1        <89>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#1
			  +E575: 07 80 45 00   line#1084 GETTABLE 0 0 -23       <90>   R0 = R0["AutoFarmAllMsBypassType"]              -- It's Const#23
			  +E579: 22 40 00 00   line#1084 TEST 0 1               <91>   if not R0 then GOTO <93>
			  +E57D: 1E C0 22 80   line#1084 JMP 0 140              <92>   GOTO <233>
			  +E581: 06 00 40 00   line#1084 GETTABUP 0 0 -1        <93>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#1
			  +E585: 07 C0 45 00   line#1084 GETTABLE 0 0 -24       <94>   R0 = R0["AutoObservationv2"]                    -- It's Const#24
			  +E589: 22 40 00 00   line#1084 TEST 0 1               <95>   if not R0 then GOTO <97>
			  +E58D: 1E C0 21 80   line#1084 JMP 0 136              <96>   GOTO <233>
			  +E591: 06 00 40 00   line#1084 GETTABUP 0 0 -1        <97>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#1
			  +E595: 07 00 46 00   line#1084 GETTABLE 0 0 -25       <98>   R0 = R0["AutoMusketeerHat"]                     -- It's Const#25
			  +E599: 22 40 00 00   line#1084 TEST 0 1               <99>   if not R0 then GOTO <101>
			  +E59D: 1E C0 20 80   line#1084 JMP 0 132             <100>   GOTO <233>
			  +E5A1: 06 00 40 00   line#1084 GETTABUP 0 0 -1       <101>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#1
			  +E5A5: 07 40 46 00   line#1084 GETTABLE 0 0 -26      <102>   R0 = R0["AutoEctoplasm"]                        -- It's Const#26
			  +E5A9: 22 40 00 00   line#1084 TEST 0 1              <103>   if not R0 then GOTO <105>
			  +E5AD: 1E C0 1F 80   line#1084 JMP 0 128             <104>   GOTO <233>
			  +E5B1: 06 00 40 00   line#1084 GETTABUP 0 0 -1       <105>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#1
			  +E5B5: 07 80 46 00   line#1084 GETTABLE 0 0 -27      <106>   R0 = R0["AutoRengoku"]                          -- It's Const#27
			  +E5B9: 22 40 00 00   line#1084 TEST 0 1              <107>   if not R0 then GOTO <109>
			  +E5BD: 1E C0 1E 80   line#1084 JMP 0 124             <108>   GOTO <233>
			  +E5C1: 06 00 40 00   line#1084 GETTABUP 0 0 -1       <109>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#1
			  +E5C5: 07 C0 46 00   line#1084 GETTABLE 0 0 -28      <110>   R0 = R0["Auto_Rainbow_Haki"]                    -- It's Const#28
			  +E5C9: 22 40 00 00   line#1084 TEST 0 1              <111>   if not R0 then GOTO <113>
			  +E5CD: 1E C0 1D 80   line#1084 JMP 0 120             <112>   GOTO <233>
			  +E5D1: 06 00 40 00   line#1084 GETTABUP 0 0 -1       <113>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#1
			  +E5D5: 07 00 47 00   line#1084 GETTABLE 0 0 -29      <114>   R0 = R0["AutoObservation"]                      -- It's Const#29
			  +E5D9: 22 40 00 00   line#1084 TEST 0 1              <115>   if not R0 then GOTO <117>
			  +E5DD: 1E C0 1C 80   line#1084 JMP 0 116             <116>   GOTO <233>
			  +E5E1: 06 00 40 00   line#1084 GETTABUP 0 0 -1       <117>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#1
			  +E5E5: 07 40 47 00   line#1084 GETTABLE 0 0 -30      <118>   R0 = R0["AutoDarkDagger"]                       -- It's Const#30
			  +E5E9: 22 40 00 00   line#1084 TEST 0 1              <119>   if not R0 then GOTO <121>
			  +E5ED: 1E C0 1B 80   line#1084 JMP 0 112             <120>   GOTO <233>
			  +E5F1: 06 00 40 00   line#1084 GETTABUP 0 0 -1       <121>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#1
			  +E5F5: 07 80 47 00   line#1084 GETTABLE 0 0 -31      <122>   R0 = R0["Safe_Mode"]                            -- It's Const#31
			  +E5F9: 22 40 00 00   line#1084 TEST 0 1              <123>   if not R0 then GOTO <125>
			  +E5FD: 1E C0 1A 80   line#1084 JMP 0 108             <124>   GOTO <233>
			  +E601: 06 00 40 00   line#1084 GETTABUP 0 0 -1       <125>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#1
			  +E605: 07 C0 47 00   line#1084 GETTABLE 0 0 -32      <126>   R0 = R0["MasteryFruit"]                         -- It's Const#32
			  +E609: 22 40 00 00   line#1084 TEST 0 1              <127>   if not R0 then GOTO <129>
			  +E60D: 1E C0 19 80   line#1084 JMP 0 104             <128>   GOTO <233>
			  +E611: 06 00 40 00   line#1084 GETTABUP 0 0 -1       <129>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#1
			  +E615: 07 00 48 00   line#1084 GETTABLE 0 0 -33      <130>   R0 = R0["AutoBudySword"]                        -- It's Const#33
			  +E619: 22 40 00 00   line#1084 TEST 0 1              <131>   if not R0 then GOTO <133>
			  +E61D: 1E C0 18 80   line#1084 JMP 0 100             <132>   GOTO <233>
			  +E621: 06 00 40 00   line#1084 GETTABUP 0 0 -1       <133>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#1
			  +E625: 07 40 48 00   line#1084 GETTABLE 0 0 -34      <134>   R0 = R0["AutoOderSword"]                        -- It's Const#34
			  +E629: 22 40 00 00   line#1084 TEST 0 1              <135>   if not R0 then GOTO <137>
			  +E62D: 1E C0 17 80   line#1084 JMP 0 96              <136>   GOTO <233>
			  +E631: 06 00 40 00   line#1084 GETTABUP 0 0 -1       <137>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#1
			  +E635: 07 80 48 00   line#1084 GETTABLE 0 0 -35      <138>   R0 = R0["AutoBounty"]                           -- It's Const#35
			  +E639: 22 40 00 00   line#1084 TEST 0 1              <139>   if not R0 then GOTO <141>
			  +E63D: 1E C0 16 80   line#1084 JMP 0 92              <140>   GOTO <233>
			  +E641: 06 00 40 00   line#1084 GETTABUP 0 0 -1       <141>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#1
			  +E645: 07 C0 48 00   line#1084 GETTABLE 0 0 -36      <142>   R0 = R0["AutoAllBoss"]                          -- It's Const#36
			  +E649: 22 40 00 00   line#1084 TEST 0 1              <143>   if not R0 then GOTO <145>
			  +E64D: 1E C0 15 80   line#1084 JMP 0 88              <144>   GOTO <233>
			  +E651: 06 00 40 00   line#1084 GETTABUP 0 0 -1       <145>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#1
			  +E655: 07 00 49 00   line#1084 GETTABLE 0 0 -37      <146>   R0 = R0["Auto_Bounty"]                          -- It's Const#37
			  +E659: 22 40 00 00   line#1084 TEST 0 1              <147>   if not R0 then GOTO <149>
			  +E65D: 1E C0 14 80   line#1084 JMP 0 84              <148>   GOTO <233>
			  +E661: 06 00 40 00   line#1084 GETTABUP 0 0 -1       <149>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#1
			  +E665: 07 40 49 00   line#1084 GETTABLE 0 0 -38      <150>   R0 = R0["AutoSharkman"]                         -- It's Const#38
			  +E669: 22 40 00 00   line#1084 TEST 0 1              <151>   if not R0 then GOTO <153>
			  +E66D: 1E C0 13 80   line#1084 JMP 0 80              <152>   GOTO <233>
			  +E671: 06 00 40 00   line#1084 GETTABUP 0 0 -1       <153>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#1
			  +E675: 07 80 49 00   line#1084 GETTABLE 0 0 -39      <154>   R0 = R0["Auto_Mastery_Fruit"]                   -- It's Const#39
			  +E679: 22 40 00 00   line#1084 TEST 0 1              <155>   if not R0 then GOTO <157>
			  +E67D: 1E C0 12 80   line#1084 JMP 0 76              <156>   GOTO <233>
			  +E681: 06 00 40 00   line#1084 GETTABUP 0 0 -1       <157>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#1
			  +E685: 07 C0 49 00   line#1084 GETTABLE 0 0 -40      <158>   R0 = R0["Auto_Mastery_Gun"]                     -- It's Const#40
			  +E689: 22 40 00 00   line#1084 TEST 0 1              <159>   if not R0 then GOTO <161>
			  +E68D: 1E C0 11 80   line#1084 JMP 0 72              <160>   GOTO <233>
			  +E691: 06 00 40 00   line#1084 GETTABUP 0 0 -1       <161>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#1
			  +E695: 07 00 4A 00   line#1084 GETTABLE 0 0 -41      <162>   R0 = R0["Auto_Dungeon"]                         -- It's Const#41
			  +E699: 22 40 00 00   line#1084 TEST 0 1              <163>   if not R0 then GOTO <165>
			  +E69D: 1E C0 10 80   line#1084 JMP 0 68              <164>   GOTO <233>
			  +E6A1: 06 00 40 00   line#1084 GETTABUP 0 0 -1       <165>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#1
			  +E6A5: 07 40 4A 00   line#1084 GETTABLE 0 0 -42      <166>   R0 = R0["Auto_Cavender"]                        -- It's Const#42
			  +E6A9: 22 40 00 00   line#1084 TEST 0 1              <167>   if not R0 then GOTO <169>
			  +E6AD: 1E C0 0F 80   line#1084 JMP 0 64              <168>   GOTO <233>
			  +E6B1: 06 00 40 00   line#1084 GETTABUP 0 0 -1       <169>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#1
			  +E6B5: 07 80 4A 00   line#1084 GETTABLE 0 0 -43      <170>   R0 = R0["Auto_Pole"]                            -- It's Const#43
			  +E6B9: 22 40 00 00   line#1084 TEST 0 1              <171>   if not R0 then GOTO <173>
			  +E6BD: 1E C0 0E 80   line#1084 JMP 0 60              <172>   GOTO <233>
			  +E6C1: 06 00 40 00   line#1084 GETTABUP 0 0 -1       <173>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#1
			  +E6C5: 07 C0 4A 00   line#1084 GETTABLE 0 0 -44      <174>   R0 = R0["Auto_Kill_Ply"]                        -- It's Const#44
			  +E6C9: 22 40 00 00   line#1084 TEST 0 1              <175>   if not R0 then GOTO <177>
			  +E6CD: 1E C0 0D 80   line#1084 JMP 0 56              <176>   GOTO <233>
			  +E6D1: 06 00 40 00   line#1084 GETTABUP 0 0 -1       <177>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#1
			  +E6D5: 07 00 4B 00   line#1084 GETTABLE 0 0 -45      <178>   R0 = R0["Auto_Factory"]                         -- It's Const#45
			  +E6D9: 22 40 00 00   line#1084 TEST 0 1              <179>   if not R0 then GOTO <181>
			  +E6DD: 1E C0 0C 80   line#1084 JMP 0 52              <180>   GOTO <233>
			  +E6E1: 06 00 40 00   line#1084 GETTABUP 0 0 -1       <181>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#1
			  +E6E5: 07 40 4B 00   line#1084 GETTABLE 0 0 -46      <182>   R0 = R0["AutoSecondSea"]                        -- It's Const#46
			  +E6E9: 22 40 00 00   line#1084 TEST 0 1              <183>   if not R0 then GOTO <185>
			  +E6ED: 1E C0 0B 80   line#1084 JMP 0 48              <184>   GOTO <233>
			  +E6F1: 06 00 40 00   line#1084 GETTABUP 0 0 -1       <185>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#1
			  +E6F5: 07 80 4B 00   line#1084 GETTABLE 0 0 -47      <186>   R0 = R0["TeleportPly"]                          -- It's Const#47
			  +E6F9: 22 40 00 00   line#1084 TEST 0 1              <187>   if not R0 then GOTO <189>
			  +E6FD: 1E C0 0A 80   line#1084 JMP 0 44              <188>   GOTO <233>
			  +E701: 06 00 40 00   line#1084 GETTABUP 0 0 -1       <189>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#1
			  +E705: 07 C0 4B 00   line#1084 GETTABLE 0 0 -48      <190>   R0 = R0["AutoBartilo"]                          -- It's Const#48
			  +E709: 22 40 00 00   line#1084 TEST 0 1              <191>   if not R0 then GOTO <193>
			  +E70D: 1E C0 09 80   line#1084 JMP 0 40              <192>   GOTO <233>
			  +E711: 06 00 40 00   line#1084 GETTABUP 0 0 -1       <193>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#1
			  +E715: 07 00 4C 00   line#1084 GETTABLE 0 0 -49      <194>   R0 = R0["Auto_DarkBoss"]                        -- It's Const#49
			  +E719: 22 40 00 00   line#1084 TEST 0 1              <195>   if not R0 then GOTO <197>
			  +E71D: 1E C0 08 80   line#1084 JMP 0 36              <196>   GOTO <233>
			  +E721: 06 00 40 00   line#1084 GETTABUP 0 0 -1       <197>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#1
			  +E725: 07 40 4C 00   line#1084 GETTABLE 0 0 -50      <198>   R0 = R0["GrabChest"]                            -- It's Const#50
			  +E729: 22 40 00 00   line#1084 TEST 0 1              <199>   if not R0 then GOTO <201>
			  +E72D: 1E C0 07 80   line#1084 JMP 0 32              <200>   GOTO <233>
			  +E731: 06 00 40 00   line#1084 GETTABUP 0 0 -1       <201>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#1
			  +E735: 07 80 4C 00   line#1084 GETTABLE 0 0 -51      <202>   R0 = R0["AutoFarmBounty"]                       -- It's Const#51
			  +E739: 22 40 00 00   line#1084 TEST 0 1              <203>   if not R0 then GOTO <205>
			  +E73D: 1E C0 06 80   line#1084 JMP 0 28              <204>   GOTO <233>
			  +E741: 06 00 40 00   line#1084 GETTABUP 0 0 -1       <205>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#1
			  +E745: 07 C0 4C 00   line#1084 GETTABLE 0 0 -52      <206>   R0 = R0["Holy_Torch"]                           -- It's Const#52
			  +E749: 22 40 00 00   line#1084 TEST 0 1              <207>   if not R0 then GOTO <209>
			  +E74D: 1E C0 05 80   line#1084 JMP 0 24              <208>   GOTO <233>
			  +E751: 06 00 40 00   line#1084 GETTABUP 0 0 -1       <209>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#1
			  +E755: 07 00 4D 00   line#1084 GETTABLE 0 0 -53      <210>   R0 = R0["AutoFarm"]                             -- It's Const#53
			  +E759: 22 40 00 00   line#1084 TEST 0 1              <211>   if not R0 then GOTO <213>
			  +E75D: 1E C0 04 80   line#1084 JMP 0 20              <212>   GOTO <233>
			  +E761: 06 00 40 00   line#1084 GETTABUP 0 0 -1       <213>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#1
			  +E765: 07 40 4D 00   line#1084 GETTABLE 0 0 -54      <214>   R0 = R0["Clip"]                                 -- It's Const#54
			  +E769: 22 40 00 00   line#1084 TEST 0 1              <215>   if not R0 then GOTO <217>
			  +E76D: 1E C0 03 80   line#1084 JMP 0 16              <216>   GOTO <233>
			  +E771: 06 00 40 00   line#1084 GETTABUP 0 0 -1       <217>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#1
			  +E775: 07 80 4D 00   line#1084 GETTABLE 0 0 -55      <218>   R0 = R0["AutoElitehunter"]                      -- It's Const#55
			  +E779: 22 40 00 00   line#1084 TEST 0 1              <219>   if not R0 then GOTO <221>
			  +E77D: 1E C0 02 80   line#1084 JMP 0 12              <220>   GOTO <233>
			  +E781: 06 00 40 00   line#1084 GETTABUP 0 0 -1       <221>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#1
			  +E785: 07 C0 4D 00   line#1084 GETTABLE 0 0 -56      <222>   R0 = R0["AutoThirdSea"]                         -- It's Const#56
			  +E789: 22 40 00 00   line#1084 TEST 0 1              <223>   if not R0 then GOTO <225>
			  +E78D: 1E C0 01 80   line#1084 JMP 0 8               <224>   GOTO <233>
			  +E791: 06 00 40 00   line#1084 GETTABUP 0 0 -1       <225>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#1
			  +E795: 07 00 4E 00   line#1084 GETTABLE 0 0 -57      <226>   R0 = R0["Auto_Bone"]                            -- It's Const#57
			  +E799: 22 40 00 00   line#1084 TEST 0 1              <227>   if not R0 then GOTO <229>
			  +E79D: 1E C0 00 80   line#1084 JMP 0 4               <228>   GOTO <233>
			  +E7A1: 06 00 40 00   line#1084 GETTABUP 0 0 -1       <229>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#1
			  +E7A5: 07 40 4E 00   line#1084 GETTABLE 0 0 -58      <230>   R0 = R0["AutoFarmCandy"]                        -- It's Const#58
			  +E7A9: 1F 80 4E 00   line#1084 EQ 0 0 -59            <231>   if R0 == true then GOTO <233>                   -- It's Const#59
			  +E7AD: 1E 80 04 80   line#1084 JMP 0 19              <232>   GOTO <252>
			  +E7B1: 06 C0 4E 00   line#1085 GETTABUP 0 0 -60      <233>   R0 = Upv#1@_ENV["pairs"]                        -- It's Const#60
			  +E7B5: 46 00 4F 00   line#1085 GETTABUP 1 0 -61      <234>   R1 = Upv#1@_ENV["game"]                         -- It's Const#61
			  +E7B9: 4C 40 CF 00   line#1085 SELF 1 1 -62          <235>   R2 = R1;  R1 = R1["GetService"]                 -- It's Const#62   -- prepare for R1:GetService()
			  +E7BD: C1 80 0F 00   line#1085 LOADK 3 -63           <236>   R3 = "Players"                                  -- It's Const#63
			  +E7C1: 64 80 80 01   line#1085 CALL 1 3 2            <237>   R1 = R1(R2, R3)
			  +E7C5: 47 C0 CF 00   line#1085 GETTABLE 1 1 -64      <238>   R1 = R1["LocalPlayer"]                          -- It's Const#64
			  +E7C9: 47 00 D0 00   line#1085 GETTABLE 1 1 -65      <239>   R1 = R1["Character"]                            -- It's Const#65
			  +E7CD: 4C 40 D0 00   line#1085 SELF 1 1 -66          <240>   R2 = R1;  R1 = R1["GetDescendants"]             -- It's Const#66   -- prepare for R1:GetDescendants()
			  +E7D1: 64 00 00 01   line#1085 CALL 1 2 0            <241>   R1,.. = R1(R2)
			  +E7D5: 24 00 01 00   line#1085 CALL 0 0 4            <242>   R0, R1, R2 = R0(R1,..)
			  +E7D9: 1E 40 01 80   line#1085 JMP 0 6               <243>   GOTO <250>                                      -- for R3@_, R4@v in R0, R1, R2 do
			  +E7DD: 4C 81 50 02   line#1086 SELF 5 4 -67          <244>   R6 = R4@v;  R5 = R4@v["IsA"]                    -- It's Const#67   -- prepare for R4@v:IsA()
			  +E7E1: C1 C1 10 00   line#1086 LOADK 7 -68           <245>   R7 = "BasePart"                                 -- It's Const#68
			  +E7E5: 64 81 80 01   line#1086 CALL 5 3 2            <246>   R5 = R5(R6, R7)
			  +E7E9: 62 01 00 00   line#1086 TEST 5 0              <247>   if R5 then GOTO <249>
			  +E7ED: 1E 00 00 80   line#1086 JMP 0 1               <248>   GOTO <250>
			  +E7F1: 0A 41 51 A2   line#1087 SETTABLE 4 -69 -70    <249>   R4@v["CanCollide"] = false                      -- It's Const#69, Const#70
			  +E7F5: 29 80 00 00   line#1085 TFORCALL 0 2          <250>   R3, R4 = R0(R1, R2)
			  +E7F9: AA C0 FD 7F   line#1085 TFORLOOP 2 -8         <251>   if R3 ~= nil then { R2 = R3;  GOTO <244> }      -- end of loop
			  +E7FD: 26 00 80 00   line#1091 RETURN 0 1            <252>   RETURN
			Functions: 0

	************ Function#25   (full path: main.25)
	Source line#: 1095..1103
	Parameters: 0
	Is vararg: no
	VM registers needed: 2
	Constants: 56
	  +F420:Size=4: 77 61 69 74                     Const#1   string    "wait"
	  +F426:Size=2: 5F 47                           Const#2   string    "_G"
	  +F42A:Size=E: 41 75 74 6F 44 6F 75 67 68...   Const#3   string    "AutoDoughtBoss"
	  +F43A:Size=13: 41 75 74 6F 5F 44 75 6E 6...   Const#4   string    "Auto_DungeonMobAura"
	  +F44F:Size=D: 41 75 74 6F 46 61 72 6D 43...   Const#5   string    "AutoFarmChest"
	  +F45E:Size=12: 41 75 74 6F 46 61 72 6D 4...   Const#6   string    "AutoFarmBossHallow"
	  +F472:Size=13: 41 75 74 6F 46 61 72 6D 5...   Const#7   string    "AutoFarmSwanGlasses"
	  +F487:Size=D: 41 75 74 6F 4C 6F 6E 67 53...   Const#8   string    "AutoLongSword"
	  +F496:Size=13: 41 75 74 6F 42 6C 61 63 6...   Const#9   string    "AutoBlackSpikeycoat"
	  +F4AB:Size=10: 41 75 74 6F 45 6C 65 63 7...   Const#10  string    "AutoElectricClaw"
	  +F4BD:Size=12: 41 75 74 6F 46 61 72 6D 4...   Const#11  string    "AutoFarmGunMastery"
	  +F4D1:Size=D: 41 75 74 6F 48 6F 6C 79 54...   Const#12  string    "AutoHolyTorch"
	  +F4E0:Size=B: 41 75 74 6F 4C 61 77 52 61...   Const#13  string    "AutoLawRaid"
	  +F4ED:Size=C: 41 75 74 6F 46 61 72 6D 42...   Const#14  string    "AutoFarmBoss"
	  +F4FB:Size=D: 41 75 74 6F 54 77 69 6E 48...   Const#15  string    "AutoTwinHooks"
	  +F50A:Size=10: 41 75 74 6F 4F 70 65 6E 5...   Const#16  string    "AutoOpenSwanDoor"
	  +F51C:Size=12: 41 75 74 6F 44 72 61 67 6...   Const#17  string    "AutoDragon_Trident"
	  +F530:Size=9: 41 75 74 6F 53 61 62 65 72      Const#18  string    "AutoSaber"
	  +F53B:Size=6: 4E 4F 43 4C 49 50               Const#19  string    "NOCLIP"
	  +F543:Size=14: 41 75 74 6F 46 61 72 6D 4...   Const#20  string    "AutoFarmFruitMastery"
	  +F559:Size=E: 54 65 6C 65 70 6F 72 74 49...   Const#21  string    "TeleportIsland"
	  +F569:Size=C: 41 75 74 6F 5F 45 76 6F 52...   Const#22  string    "Auto_EvoRace"
	  +F577:Size=17: 41 75 74 6F 46 61 72 6D 4...   Const#23  string    "AutoFarmAllMsBypassType"
	  +F590:Size=11: 41 75 74 6F 4F 62 73 65 7...   Const#24  string    "AutoObservationv2"
	  +F5A3:Size=10: 41 75 74 6F 4D 75 73 6B 6...   Const#25  string    "AutoMusketeerHat"
	  +F5B5:Size=D: 41 75 74 6F 45 63 74 6F 70...   Const#26  string    "AutoEctoplasm"
	  +F5C4:Size=B: 41 75 74 6F 52 65 6E 67 6F...   Const#27  string    "AutoRengoku"
	  +F5D1:Size=11: 41 75 74 6F 5F 52 61 69 6...   Const#28  string    "Auto_Rainbow_Haki"
	  +F5E4:Size=F: 41 75 74 6F 4F 62 73 65 72...   Const#29  string    "AutoObservation"
	  +F5F5:Size=E: 41 75 74 6F 44 61 72 6B 44...   Const#30  string    "AutoDarkDagger"
	  +F605:Size=9: 53 61 66 65 5F 4D 6F 64 65      Const#31  string    "Safe_Mode"
	  +F610:Size=C: 4D 61 73 74 65 72 79 46 72...   Const#32  string    "MasteryFruit"
	  +F61E:Size=D: 41 75 74 6F 42 75 64 79 53...   Const#33  string    "AutoBudySword"
	  +F62D:Size=D: 41 75 74 6F 4F 64 65 72 53...   Const#34  string    "AutoOderSword"
	  +F63C:Size=B: 41 75 74 6F 41 6C 6C 42 6F...   Const#35  string    "AutoAllBoss"
	  +F649:Size=B: 41 75 74 6F 5F 42 6F 75 6E...   Const#36  string    "Auto_Bounty"
	  +F656:Size=C: 41 75 74 6F 53 68 61 72 6B...   Const#37  string    "AutoSharkman"
	  +F664:Size=12: 41 75 74 6F 5F 4D 61 73 7...   Const#38  string    "Auto_Mastery_Fruit"
	  +F678:Size=10: 41 75 74 6F 5F 4D 61 73 7...   Const#39  string    "Auto_Mastery_Gun"
	  +F68A:Size=C: 41 75 74 6F 5F 44 75 6E 67...   Const#40  string    "Auto_Dungeon"
	  +F698:Size=D: 41 75 74 6F 5F 43 61 76 65...   Const#41  string    "Auto_Cavender"
	  +F6A7:Size=9: 41 75 74 6F 5F 50 6F 6C 65      Const#42  string    "Auto_Pole"
	  +F6B2:Size=D: 41 75 74 6F 5F 4B 69 6C 6C...   Const#43  string    "Auto_Kill_Ply"
	  +F6C1:Size=C: 41 75 74 6F 5F 46 61 63 74...   Const#44  string    "Auto_Factory"
	  +F6CF:Size=D: 41 75 74 6F 53 65 63 6F 6E...   Const#45  string    "AutoSecondSea"
	  +F6DE:Size=B: 54 65 6C 65 70 6F 72 74 50...   Const#46  string    "TeleportPly"
	  +F6EB:Size=B: 41 75 74 6F 42 61 72 74 69...   Const#47  string    "AutoBartilo"
	  +F6F8:Size=D: 41 75 74 6F 5F 44 61 72 6B...   Const#48  string    "Auto_DarkBoss"
	  +F707:Size=8: 41 75 74 6F 46 61 72 6D         Const#49  string    "AutoFarm"
	  +F711:Size=4: 43 6C 69 70                     Const#50  string    "Clip"
	  +F717:Size=F: 41 75 74 6F 45 6C 69 74 65...   Const#51  string    "AutoElitehunter"
	  +F728:Size=C: 41 75 74 6F 54 68 69 72 64...   Const#52  string    "AutoThirdSea"
	  +F736:Size=9: 41 75 74 6F 5F 42 6F 6E 65      Const#53  string    "Auto_Bone"
	  +F741:Size=D: 41 75 74 6F 46 61 72 6D 43...   Const#54  string    "AutoFarmCandy"
	  +F74F:Size=1: 01                              Const#55  boolean   true
	  +F752:Size=5: 70 63 61 6C 6C                  Const#56  string    "pcall"
	Upvalues: 1
	  Upv#1 is parent function's Upv#1              name: _ENV
	Instructions: 221
	  +F0A6: 06 00 40 00   line#1096 GETTABUP 0 0 -1         <1>   R0 = Upv#1@_ENV["wait"]                         -- It's Const#1
	  +F0AA: 24 80 80 00   line#1096 CALL 0 1 2              <2>   R0 = R0()
	  +F0AE: 22 00 00 00   line#1096 TEST 0 0                <3>   if R0 then GOTO <5>
	  +F0B2: 1E C0 35 80   line#1096 JMP 0 216               <4>   GOTO <221>
	  +F0B6: 06 40 40 00   line#1097 GETTABUP 0 0 -2         <5>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
	  +F0BA: 07 80 40 00   line#1097 GETTABLE 0 0 -3         <6>   R0 = R0["AutoDoughtBoss"]                       -- It's Const#3
	  +F0BE: 22 40 00 00   line#1097 TEST 0 1                <7>   if not R0 then GOTO <9>
	  +F0C2: 1E C0 33 80   line#1097 JMP 0 208               <8>   GOTO <217>
	  +F0C6: 06 40 40 00   line#1097 GETTABUP 0 0 -2         <9>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
	  +F0CA: 07 C0 40 00   line#1097 GETTABLE 0 0 -4        <10>   R0 = R0["Auto_DungeonMobAura"]                  -- It's Const#4
	  +F0CE: 22 40 00 00   line#1097 TEST 0 1               <11>   if not R0 then GOTO <13>
	  +F0D2: 1E C0 32 80   line#1097 JMP 0 204              <12>   GOTO <217>
	  +F0D6: 06 40 40 00   line#1097 GETTABUP 0 0 -2        <13>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
	  +F0DA: 07 00 41 00   line#1097 GETTABLE 0 0 -5        <14>   R0 = R0["AutoFarmChest"]                        -- It's Const#5
	  +F0DE: 22 40 00 00   line#1097 TEST 0 1               <15>   if not R0 then GOTO <17>
	  +F0E2: 1E C0 31 80   line#1097 JMP 0 200              <16>   GOTO <217>
	  +F0E6: 06 40 40 00   line#1097 GETTABUP 0 0 -2        <17>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
	  +F0EA: 07 40 41 00   line#1097 GETTABLE 0 0 -6        <18>   R0 = R0["AutoFarmBossHallow"]                   -- It's Const#6
	  +F0EE: 22 40 00 00   line#1097 TEST 0 1               <19>   if not R0 then GOTO <21>
	  +F0F2: 1E C0 30 80   line#1097 JMP 0 196              <20>   GOTO <217>
	  +F0F6: 06 40 40 00   line#1097 GETTABUP 0 0 -2        <21>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
	  +F0FA: 07 80 41 00   line#1097 GETTABLE 0 0 -7        <22>   R0 = R0["AutoFarmSwanGlasses"]                  -- It's Const#7
	  +F0FE: 22 40 00 00   line#1097 TEST 0 1               <23>   if not R0 then GOTO <25>
	  +F102: 1E C0 2F 80   line#1097 JMP 0 192              <24>   GOTO <217>
	  +F106: 06 40 40 00   line#1097 GETTABUP 0 0 -2        <25>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
	  +F10A: 07 C0 41 00   line#1097 GETTABLE 0 0 -8        <26>   R0 = R0["AutoLongSword"]                        -- It's Const#8
	  +F10E: 22 40 00 00   line#1097 TEST 0 1               <27>   if not R0 then GOTO <29>
	  +F112: 1E C0 2E 80   line#1097 JMP 0 188              <28>   GOTO <217>
	  +F116: 06 40 40 00   line#1097 GETTABUP 0 0 -2        <29>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
	  +F11A: 07 00 42 00   line#1097 GETTABLE 0 0 -9        <30>   R0 = R0["AutoBlackSpikeycoat"]                  -- It's Const#9
	  +F11E: 22 40 00 00   line#1097 TEST 0 1               <31>   if not R0 then GOTO <33>
	  +F122: 1E C0 2D 80   line#1097 JMP 0 184              <32>   GOTO <217>
	  +F126: 06 40 40 00   line#1097 GETTABUP 0 0 -2        <33>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
	  +F12A: 07 40 42 00   line#1097 GETTABLE 0 0 -10       <34>   R0 = R0["AutoElectricClaw"]                     -- It's Const#10
	  +F12E: 22 40 00 00   line#1097 TEST 0 1               <35>   if not R0 then GOTO <37>
	  +F132: 1E C0 2C 80   line#1097 JMP 0 180              <36>   GOTO <217>
	  +F136: 06 40 40 00   line#1097 GETTABUP 0 0 -2        <37>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
	  +F13A: 07 80 42 00   line#1097 GETTABLE 0 0 -11       <38>   R0 = R0["AutoFarmGunMastery"]                   -- It's Const#11
	  +F13E: 22 40 00 00   line#1097 TEST 0 1               <39>   if not R0 then GOTO <41>
	  +F142: 1E C0 2B 80   line#1097 JMP 0 176              <40>   GOTO <217>
	  +F146: 06 40 40 00   line#1097 GETTABUP 0 0 -2        <41>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
	  +F14A: 07 C0 42 00   line#1097 GETTABLE 0 0 -12       <42>   R0 = R0["AutoHolyTorch"]                        -- It's Const#12
	  +F14E: 22 40 00 00   line#1097 TEST 0 1               <43>   if not R0 then GOTO <45>
	  +F152: 1E C0 2A 80   line#1097 JMP 0 172              <44>   GOTO <217>
	  +F156: 06 40 40 00   line#1097 GETTABUP 0 0 -2        <45>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
	  +F15A: 07 00 43 00   line#1097 GETTABLE 0 0 -13       <46>   R0 = R0["AutoLawRaid"]                          -- It's Const#13
	  +F15E: 22 40 00 00   line#1097 TEST 0 1               <47>   if not R0 then GOTO <49>
	  +F162: 1E C0 29 80   line#1097 JMP 0 168              <48>   GOTO <217>
	  +F166: 06 40 40 00   line#1097 GETTABUP 0 0 -2        <49>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
	  +F16A: 07 40 43 00   line#1097 GETTABLE 0 0 -14       <50>   R0 = R0["AutoFarmBoss"]                         -- It's Const#14
	  +F16E: 22 40 00 00   line#1097 TEST 0 1               <51>   if not R0 then GOTO <53>
	  +F172: 1E C0 28 80   line#1097 JMP 0 164              <52>   GOTO <217>
	  +F176: 06 40 40 00   line#1097 GETTABUP 0 0 -2        <53>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
	  +F17A: 07 80 43 00   line#1097 GETTABLE 0 0 -15       <54>   R0 = R0["AutoTwinHooks"]                        -- It's Const#15
	  +F17E: 22 40 00 00   line#1097 TEST 0 1               <55>   if not R0 then GOTO <57>
	  +F182: 1E C0 27 80   line#1097 JMP 0 160              <56>   GOTO <217>
	  +F186: 06 40 40 00   line#1097 GETTABUP 0 0 -2        <57>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
	  +F18A: 07 C0 43 00   line#1097 GETTABLE 0 0 -16       <58>   R0 = R0["AutoOpenSwanDoor"]                     -- It's Const#16
	  +F18E: 22 40 00 00   line#1097 TEST 0 1               <59>   if not R0 then GOTO <61>
	  +F192: 1E C0 26 80   line#1097 JMP 0 156              <60>   GOTO <217>
	  +F196: 06 40 40 00   line#1097 GETTABUP 0 0 -2        <61>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
	  +F19A: 07 00 44 00   line#1097 GETTABLE 0 0 -17       <62>   R0 = R0["AutoDragon_Trident"]                   -- It's Const#17
	  +F19E: 22 40 00 00   line#1097 TEST 0 1               <63>   if not R0 then GOTO <65>
	  +F1A2: 1E C0 25 80   line#1097 JMP 0 152              <64>   GOTO <217>
	  +F1A6: 06 40 40 00   line#1097 GETTABUP 0 0 -2        <65>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
	  +F1AA: 07 40 44 00   line#1097 GETTABLE 0 0 -18       <66>   R0 = R0["AutoSaber"]                            -- It's Const#18
	  +F1AE: 22 40 00 00   line#1097 TEST 0 1               <67>   if not R0 then GOTO <69>
	  +F1B2: 1E C0 24 80   line#1097 JMP 0 148              <68>   GOTO <217>
	  +F1B6: 06 40 40 00   line#1097 GETTABUP 0 0 -2        <69>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
	  +F1BA: 07 80 44 00   line#1097 GETTABLE 0 0 -19       <70>   R0 = R0["NOCLIP"]                               -- It's Const#19
	  +F1BE: 22 40 00 00   line#1097 TEST 0 1               <71>   if not R0 then GOTO <73>
	  +F1C2: 1E C0 23 80   line#1097 JMP 0 144              <72>   GOTO <217>
	  +F1C6: 06 40 40 00   line#1097 GETTABUP 0 0 -2        <73>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
	  +F1CA: 07 C0 44 00   line#1097 GETTABLE 0 0 -20       <74>   R0 = R0["AutoFarmFruitMastery"]                 -- It's Const#20
	  +F1CE: 22 40 00 00   line#1097 TEST 0 1               <75>   if not R0 then GOTO <77>
	  +F1D2: 1E C0 22 80   line#1097 JMP 0 140              <76>   GOTO <217>
	  +F1D6: 06 40 40 00   line#1097 GETTABUP 0 0 -2        <77>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
	  +F1DA: 07 80 42 00   line#1097 GETTABLE 0 0 -11       <78>   R0 = R0["AutoFarmGunMastery"]                   -- It's Const#11
	  +F1DE: 22 40 00 00   line#1097 TEST 0 1               <79>   if not R0 then GOTO <81>
	  +F1E2: 1E C0 21 80   line#1097 JMP 0 136              <80>   GOTO <217>
	  +F1E6: 06 40 40 00   line#1097 GETTABUP 0 0 -2        <81>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
	  +F1EA: 07 00 45 00   line#1097 GETTABLE 0 0 -21       <82>   R0 = R0["TeleportIsland"]                       -- It's Const#21
	  +F1EE: 22 40 00 00   line#1097 TEST 0 1               <83>   if not R0 then GOTO <85>
	  +F1F2: 1E C0 20 80   line#1097 JMP 0 132              <84>   GOTO <217>
	  +F1F6: 06 40 40 00   line#1097 GETTABUP 0 0 -2        <85>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
	  +F1FA: 07 40 45 00   line#1097 GETTABLE 0 0 -22       <86>   R0 = R0["Auto_EvoRace"]                         -- It's Const#22
	  +F1FE: 22 40 00 00   line#1097 TEST 0 1               <87>   if not R0 then GOTO <89>
	  +F202: 1E C0 1F 80   line#1097 JMP 0 128              <88>   GOTO <217>
	  +F206: 06 40 40 00   line#1097 GETTABUP 0 0 -2        <89>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
	  +F20A: 07 80 45 00   line#1097 GETTABLE 0 0 -23       <90>   R0 = R0["AutoFarmAllMsBypassType"]              -- It's Const#23
	  +F20E: 22 40 00 00   line#1097 TEST 0 1               <91>   if not R0 then GOTO <93>
	  +F212: 1E C0 1E 80   line#1097 JMP 0 124              <92>   GOTO <217>
	  +F216: 06 40 40 00   line#1097 GETTABUP 0 0 -2        <93>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
	  +F21A: 07 C0 45 00   line#1097 GETTABLE 0 0 -24       <94>   R0 = R0["AutoObservationv2"]                    -- It's Const#24
	  +F21E: 22 40 00 00   line#1097 TEST 0 1               <95>   if not R0 then GOTO <97>
	  +F222: 1E C0 1D 80   line#1097 JMP 0 120              <96>   GOTO <217>
	  +F226: 06 40 40 00   line#1097 GETTABUP 0 0 -2        <97>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
	  +F22A: 07 00 46 00   line#1097 GETTABLE 0 0 -25       <98>   R0 = R0["AutoMusketeerHat"]                     -- It's Const#25
	  +F22E: 22 40 00 00   line#1097 TEST 0 1               <99>   if not R0 then GOTO <101>
	  +F232: 1E C0 1C 80   line#1097 JMP 0 116             <100>   GOTO <217>
	  +F236: 06 40 40 00   line#1097 GETTABUP 0 0 -2       <101>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
	  +F23A: 07 40 46 00   line#1097 GETTABLE 0 0 -26      <102>   R0 = R0["AutoEctoplasm"]                        -- It's Const#26
	  +F23E: 22 40 00 00   line#1097 TEST 0 1              <103>   if not R0 then GOTO <105>
	  +F242: 1E C0 1B 80   line#1097 JMP 0 112             <104>   GOTO <217>
	  +F246: 06 40 40 00   line#1097 GETTABUP 0 0 -2       <105>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
	  +F24A: 07 80 46 00   line#1097 GETTABLE 0 0 -27      <106>   R0 = R0["AutoRengoku"]                          -- It's Const#27
	  +F24E: 22 40 00 00   line#1097 TEST 0 1              <107>   if not R0 then GOTO <109>
	  +F252: 1E C0 1A 80   line#1097 JMP 0 108             <108>   GOTO <217>
	  +F256: 06 40 40 00   line#1097 GETTABUP 0 0 -2       <109>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
	  +F25A: 07 C0 46 00   line#1097 GETTABLE 0 0 -28      <110>   R0 = R0["Auto_Rainbow_Haki"]                    -- It's Const#28
	  +F25E: 22 40 00 00   line#1097 TEST 0 1              <111>   if not R0 then GOTO <113>
	  +F262: 1E C0 19 80   line#1097 JMP 0 104             <112>   GOTO <217>
	  +F266: 06 40 40 00   line#1097 GETTABUP 0 0 -2       <113>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
	  +F26A: 07 00 47 00   line#1097 GETTABLE 0 0 -29      <114>   R0 = R0["AutoObservation"]                      -- It's Const#29
	  +F26E: 22 40 00 00   line#1097 TEST 0 1              <115>   if not R0 then GOTO <117>
	  +F272: 1E C0 18 80   line#1097 JMP 0 100             <116>   GOTO <217>
	  +F276: 06 40 40 00   line#1097 GETTABUP 0 0 -2       <117>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
	  +F27A: 07 40 47 00   line#1097 GETTABLE 0 0 -30      <118>   R0 = R0["AutoDarkDagger"]                       -- It's Const#30
	  +F27E: 22 40 00 00   line#1097 TEST 0 1              <119>   if not R0 then GOTO <121>
	  +F282: 1E C0 17 80   line#1097 JMP 0 96              <120>   GOTO <217>
	  +F286: 06 40 40 00   line#1097 GETTABUP 0 0 -2       <121>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
	  +F28A: 07 80 47 00   line#1097 GETTABLE 0 0 -31      <122>   R0 = R0["Safe_Mode"]                            -- It's Const#31
	  +F28E: 22 40 00 00   line#1097 TEST 0 1              <123>   if not R0 then GOTO <125>
	  +F292: 1E C0 16 80   line#1097 JMP 0 92              <124>   GOTO <217>
	  +F296: 06 40 40 00   line#1097 GETTABUP 0 0 -2       <125>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
	  +F29A: 07 C0 47 00   line#1097 GETTABLE 0 0 -32      <126>   R0 = R0["MasteryFruit"]                         -- It's Const#32
	  +F29E: 22 40 00 00   line#1097 TEST 0 1              <127>   if not R0 then GOTO <129>
	  +F2A2: 1E C0 15 80   line#1097 JMP 0 88              <128>   GOTO <217>
	  +F2A6: 06 40 40 00   line#1097 GETTABUP 0 0 -2       <129>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
	  +F2AA: 07 00 48 00   line#1097 GETTABLE 0 0 -33      <130>   R0 = R0["AutoBudySword"]                        -- It's Const#33
	  +F2AE: 22 40 00 00   line#1097 TEST 0 1              <131>   if not R0 then GOTO <133>
	  +F2B2: 1E C0 14 80   line#1097 JMP 0 84              <132>   GOTO <217>
	  +F2B6: 06 40 40 00   line#1097 GETTABUP 0 0 -2       <133>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
	  +F2BA: 07 40 48 00   line#1097 GETTABLE 0 0 -34      <134>   R0 = R0["AutoOderSword"]                        -- It's Const#34
	  +F2BE: 22 40 00 00   line#1097 TEST 0 1              <135>   if not R0 then GOTO <137>
	  +F2C2: 1E C0 13 80   line#1097 JMP 0 80              <136>   GOTO <217>
	  +F2C6: 06 40 40 00   line#1097 GETTABUP 0 0 -2       <137>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
	  +F2CA: 07 80 48 00   line#1097 GETTABLE 0 0 -35      <138>   R0 = R0["AutoAllBoss"]                          -- It's Const#35
	  +F2CE: 22 40 00 00   line#1097 TEST 0 1              <139>   if not R0 then GOTO <141>
	  +F2D2: 1E C0 12 80   line#1097 JMP 0 76              <140>   GOTO <217>
	  +F2D6: 06 40 40 00   line#1097 GETTABUP 0 0 -2       <141>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
	  +F2DA: 07 C0 48 00   line#1097 GETTABLE 0 0 -36      <142>   R0 = R0["Auto_Bounty"]                          -- It's Const#36
	  +F2DE: 22 40 00 00   line#1097 TEST 0 1              <143>   if not R0 then GOTO <145>
	  +F2E2: 1E C0 11 80   line#1097 JMP 0 72              <144>   GOTO <217>
	  +F2E6: 06 40 40 00   line#1097 GETTABUP 0 0 -2       <145>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
	  +F2EA: 07 00 49 00   line#1097 GETTABLE 0 0 -37      <146>   R0 = R0["AutoSharkman"]                         -- It's Const#37
	  +F2EE: 22 40 00 00   line#1097 TEST 0 1              <147>   if not R0 then GOTO <149>
	  +F2F2: 1E C0 10 80   line#1097 JMP 0 68              <148>   GOTO <217>
	  +F2F6: 06 40 40 00   line#1097 GETTABUP 0 0 -2       <149>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
	  +F2FA: 07 40 49 00   line#1097 GETTABLE 0 0 -38      <150>   R0 = R0["Auto_Mastery_Fruit"]                   -- It's Const#38
	  +F2FE: 22 40 00 00   line#1097 TEST 0 1              <151>   if not R0 then GOTO <153>
	  +F302: 1E C0 0F 80   line#1097 JMP 0 64              <152>   GOTO <217>
	  +F306: 06 40 40 00   line#1097 GETTABUP 0 0 -2       <153>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
	  +F30A: 07 80 49 00   line#1097 GETTABLE 0 0 -39      <154>   R0 = R0["Auto_Mastery_Gun"]                     -- It's Const#39
	  +F30E: 22 40 00 00   line#1097 TEST 0 1              <155>   if not R0 then GOTO <157>
	  +F312: 1E C0 0E 80   line#1097 JMP 0 60              <156>   GOTO <217>
	  +F316: 06 40 40 00   line#1097 GETTABUP 0 0 -2       <157>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
	  +F31A: 07 C0 49 00   line#1097 GETTABLE 0 0 -40      <158>   R0 = R0["Auto_Dungeon"]                         -- It's Const#40
	  +F31E: 22 40 00 00   line#1097 TEST 0 1              <159>   if not R0 then GOTO <161>
	  +F322: 1E C0 0D 80   line#1097 JMP 0 56              <160>   GOTO <217>
	  +F326: 06 40 40 00   line#1097 GETTABUP 0 0 -2       <161>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
	  +F32A: 07 00 4A 00   line#1097 GETTABLE 0 0 -41      <162>   R0 = R0["Auto_Cavender"]                        -- It's Const#41
	  +F32E: 22 40 00 00   line#1097 TEST 0 1              <163>   if not R0 then GOTO <165>
	  +F332: 1E C0 0C 80   line#1097 JMP 0 52              <164>   GOTO <217>
	  +F336: 06 40 40 00   line#1097 GETTABUP 0 0 -2       <165>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
	  +F33A: 07 40 4A 00   line#1097 GETTABLE 0 0 -42      <166>   R0 = R0["Auto_Pole"]                            -- It's Const#42
	  +F33E: 22 40 00 00   line#1097 TEST 0 1              <167>   if not R0 then GOTO <169>
	  +F342: 1E C0 0B 80   line#1097 JMP 0 48              <168>   GOTO <217>
	  +F346: 06 40 40 00   line#1097 GETTABUP 0 0 -2       <169>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
	  +F34A: 07 80 4A 00   line#1097 GETTABLE 0 0 -43      <170>   R0 = R0["Auto_Kill_Ply"]                        -- It's Const#43
	  +F34E: 22 40 00 00   line#1097 TEST 0 1              <171>   if not R0 then GOTO <173>
	  +F352: 1E C0 0A 80   line#1097 JMP 0 44              <172>   GOTO <217>
	  +F356: 06 40 40 00   line#1097 GETTABUP 0 0 -2       <173>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
	  +F35A: 07 C0 4A 00   line#1097 GETTABLE 0 0 -44      <174>   R0 = R0["Auto_Factory"]                         -- It's Const#44
	  +F35E: 22 40 00 00   line#1097 TEST 0 1              <175>   if not R0 then GOTO <177>
	  +F362: 1E C0 09 80   line#1097 JMP 0 40              <176>   GOTO <217>
	  +F366: 06 40 40 00   line#1097 GETTABUP 0 0 -2       <177>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
	  +F36A: 07 00 4B 00   line#1097 GETTABLE 0 0 -45      <178>   R0 = R0["AutoSecondSea"]                        -- It's Const#45
	  +F36E: 22 40 00 00   line#1097 TEST 0 1              <179>   if not R0 then GOTO <181>
	  +F372: 1E C0 08 80   line#1097 JMP 0 36              <180>   GOTO <217>
	  +F376: 06 40 40 00   line#1097 GETTABUP 0 0 -2       <181>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
	  +F37A: 07 40 4B 00   line#1097 GETTABLE 0 0 -46      <182>   R0 = R0["TeleportPly"]                          -- It's Const#46
	  +F37E: 22 40 00 00   line#1097 TEST 0 1              <183>   if not R0 then GOTO <185>
	  +F382: 1E C0 07 80   line#1097 JMP 0 32              <184>   GOTO <217>
	  +F386: 06 40 40 00   line#1097 GETTABUP 0 0 -2       <185>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
	  +F38A: 07 80 4B 00   line#1097 GETTABLE 0 0 -47      <186>   R0 = R0["AutoBartilo"]                          -- It's Const#47
	  +F38E: 22 40 00 00   line#1097 TEST 0 1              <187>   if not R0 then GOTO <189>
	  +F392: 1E C0 06 80   line#1097 JMP 0 28              <188>   GOTO <217>
	  +F396: 06 40 40 00   line#1097 GETTABUP 0 0 -2       <189>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
	  +F39A: 07 C0 4B 00   line#1097 GETTABLE 0 0 -48      <190>   R0 = R0["Auto_DarkBoss"]                        -- It's Const#48
	  +F39E: 22 40 00 00   line#1097 TEST 0 1              <191>   if not R0 then GOTO <193>
	  +F3A2: 1E C0 05 80   line#1097 JMP 0 24              <192>   GOTO <217>
	  +F3A6: 06 40 40 00   line#1097 GETTABUP 0 0 -2       <193>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
	  +F3AA: 07 00 4C 00   line#1097 GETTABLE 0 0 -49      <194>   R0 = R0["AutoFarm"]                             -- It's Const#49
	  +F3AE: 22 40 00 00   line#1097 TEST 0 1              <195>   if not R0 then GOTO <197>
	  +F3B2: 1E C0 04 80   line#1097 JMP 0 20              <196>   GOTO <217>
	  +F3B6: 06 40 40 00   line#1097 GETTABUP 0 0 -2       <197>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
	  +F3BA: 07 40 4C 00   line#1097 GETTABLE 0 0 -50      <198>   R0 = R0["Clip"]                                 -- It's Const#50
	  +F3BE: 22 40 00 00   line#1097 TEST 0 1              <199>   if not R0 then GOTO <201>
	  +F3C2: 1E C0 03 80   line#1097 JMP 0 16              <200>   GOTO <217>
	  +F3C6: 06 40 40 00   line#1097 GETTABUP 0 0 -2       <201>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
	  +F3CA: 07 80 4C 00   line#1097 GETTABLE 0 0 -51      <202>   R0 = R0["AutoElitehunter"]                      -- It's Const#51
	  +F3CE: 22 40 00 00   line#1097 TEST 0 1              <203>   if not R0 then GOTO <205>
	  +F3D2: 1E C0 02 80   line#1097 JMP 0 12              <204>   GOTO <217>
	  +F3D6: 06 40 40 00   line#1097 GETTABUP 0 0 -2       <205>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
	  +F3DA: 07 C0 4C 00   line#1097 GETTABLE 0 0 -52      <206>   R0 = R0["AutoThirdSea"]                         -- It's Const#52
	  +F3DE: 22 40 00 00   line#1097 TEST 0 1              <207>   if not R0 then GOTO <209>
	  +F3E2: 1E C0 01 80   line#1097 JMP 0 8               <208>   GOTO <217>
	  +F3E6: 06 40 40 00   line#1097 GETTABUP 0 0 -2       <209>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
	  +F3EA: 07 00 4D 00   line#1097 GETTABLE 0 0 -53      <210>   R0 = R0["Auto_Bone"]                            -- It's Const#53
	  +F3EE: 22 40 00 00   line#1097 TEST 0 1              <211>   if not R0 then GOTO <213>
	  +F3F2: 1E C0 00 80   line#1097 JMP 0 4               <212>   GOTO <217>
	  +F3F6: 06 40 40 00   line#1097 GETTABUP 0 0 -2       <213>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
	  +F3FA: 07 40 4D 00   line#1097 GETTABLE 0 0 -54      <214>   R0 = R0["AutoFarmCandy"]                        -- It's Const#54
	  +F3FE: 1F 80 4D 00   line#1097 EQ 0 0 -55            <215>   if R0 == true then GOTO <217>                   -- It's Const#55
	  +F402: 1E C0 C9 7F   line#1097 JMP 0 -216            <216>   GOTO <1>
	  +F406: 06 C0 4D 00   line#1098 GETTABUP 0 0 -56      <217>   R0 = Upv#1@_ENV["pcall"]                        -- It's Const#56
	  +F40A: 6C 00 00 00   line#1100 CLOSURE 1 0           <218>   R1 = Function#1
	  +F40E: 24 40 00 01   line#1098 CALL 0 2 1            <219>   R0(R1)
	  +F412: 1E C0 C8 7F   line#1101 JMP 0 -220            <220>   GOTO <1>
	  +F416: 26 00 80 00   line#1103 RETURN 0 1            <221>   RETURN
	Functions: 1

		************ Function#1   (full path: main.25.1)
		Source line#: 1098..1100
		Parameters: 0
		Is vararg: no
		VM registers needed: 4
		Constants: 7
		  +F7A3:Size=4: 67 61 6D 65                     Const#1   string    "game"
		  +F7A9:Size=A: 47 65 74 53 65 72 76 69 63 65   Const#2   string    "GetService"
		  +F7B5:Size=11: 52 65 70 6C 69 63 61 74 6...   Const#3   string    "ReplicatedStorage"
		  +F7C8:Size=7: 52 65 6D 6F 74 65 73            Const#4   string    "Remotes"
		  +F7D1:Size=5: 43 6F 6D 6D 45                  Const#5   string    "CommE"
		  +F7D8:Size=A: 46 69 72 65 53 65 72 76 65 72   Const#6   string    "FireServer"
		  +F7E4:Size=3: 4B 65 6E                        Const#7   string    "Ken"
		Upvalues: 1
		  Upv#1 is parent function's Upv#1              name: _ENV
		Instructions: 11
		  +F771: 06 00 40 00   line#1099 GETTABUP 0 0 -1         <1>   R0 = Upv#1@_ENV["game"]                         -- It's Const#1
		  +F775: 0C 40 40 00   line#1099 SELF 0 0 -2             <2>   R1 = R0;  R0 = R0["GetService"]                 -- It's Const#2   -- prepare for R0:GetService()
		  +F779: 81 80 00 00   line#1099 LOADK 2 -3              <3>   R2 = "ReplicatedStorage"                        -- It's Const#3
		  +F77D: 24 80 80 01   line#1099 CALL 0 3 2              <4>   R0 = R0(R1, R2)
		  +F781: 07 C0 40 00   line#1099 GETTABLE 0 0 -4         <5>   R0 = R0["Remotes"]                              -- It's Const#4
		  +F785: 07 00 41 00   line#1099 GETTABLE 0 0 -5         <6>   R0 = R0["CommE"]                                -- It's Const#5
		  +F789: 0C 40 41 00   line#1099 SELF 0 0 -6             <7>   R1 = R0;  R0 = R0["FireServer"]                 -- It's Const#6   -- prepare for R0:FireServer()
		  +F78D: 81 80 01 00   line#1099 LOADK 2 -7              <8>   R2 = "Ken"                                      -- It's Const#7
		  +F791: C3 00 80 00   line#1099 LOADBOOL 3 1 0          <9>   R3 = true
		  +F795: 24 40 00 02   line#1099 CALL 0 4 1             <10>   R0(R1, R2, R3)
		  +F799: 26 00 80 00   line#1100 RETURN 0 1             <11>   RETURN
		Functions: 0

	************ Function#26   (full path: main.26)
	Source line#: 1105..1117
	Parameters: 1
	Is vararg: no
	VM registers needed: 5
	Constants: 17
	  +FC85:Size=2: 5F 47                           Const#1   string    "_G"
	  +FC89:Size=9: 53 74 6F 70 54 77 65 65 6E      Const#2   string    "StopTween"
	  +FC93:Size=1: 01                              Const#3   boolean   true
	  +FC96:Size=4: 77 61 69 74                     Const#4   string    "wait"
	  +FC9C:Size=5: 74 6F 70 6F 73                  Const#5   string    "topos"
	  +FCA3:Size=4: 67 61 6D 65                     Const#6   string    "game"
	  +FCA9:Size=A: 47 65 74 53 65 72 76 69 63 65   Const#7   string    "GetService"
	  +FCB5:Size=7: 50 6C 61 79 65 72 73            Const#8   string    "Players"
	  +FCBE:Size=B: 4C 6F 63 61 6C 50 6C 61 79...   Const#9   string    "LocalPlayer"
	  +FCCB:Size=9: 43 68 61 72 61 63 74 65 72      Const#10  string    "Character"
	  +FCD6:Size=10: 48 75 6D 61 6E 6F 69 64 5...   Const#11  string    "HumanoidRootPart"
	  +FCE8:Size=6: 43 46 72 61 6D 65               Const#12  string    "CFrame"
	  +FCF0:Size=E: 46 69 6E 64 46 69 72 73 74...   Const#13  string    "FindFirstChild"
	  +FD00:Size=8: 42 6F 64 79 43 6C 69 70         Const#14  string    "BodyClip"
	  +FD0A:Size=7: 44 65 73 74 72 6F 79            Const#15  string    "Destroy"
	  +FD12:Size=1: 00                              Const#16  boolean   false
	  +FD15:Size=4: 43 6C 69 70                     Const#17  string    "Clip"
	Upvalues: 1
	  Upv#1 is parent function's Upv#1              name: _ENV
	Locals: 1
	  Local#1   R0   parameter  scope:<1..47>       name: target
	Instructions: 47
	  +FBC3: 22 40 00 00   line#1106 TEST 0 1                <1>   if not R0@target then GOTO <3>
	  +FBC7: 1E C0 0A 80   line#1106 JMP 0 44                <2>   GOTO <47>
	  +FBCB: 46 00 40 00   line#1107 GETTABUP 1 0 -1         <3>   R1 = Upv#1@_ENV["_G"]                           -- It's Const#1
	  +FBCF: 4A 80 C0 80   line#1107 SETTABLE 1 -2 -3        <4>   R1["StopTween"] = true                          -- It's Const#2, Const#3
	  +FBD3: 46 C0 40 00   line#1108 GETTABUP 1 0 -4         <5>   R1 = Upv#1@_ENV["wait"]                         -- It's Const#4
	  +FBD7: 64 40 80 00   line#1108 CALL 1 1 1              <6>   R1()
	  +FBDB: 46 00 41 00   line#1109 GETTABUP 1 0 -5         <7>   R1 = Upv#1@_ENV["topos"]                        -- It's Const#5
	  +FBDF: 86 40 41 00   line#1109 GETTABUP 2 0 -6         <8>   R2 = Upv#1@_ENV["game"]                         -- It's Const#6
	  +FBE3: 8C 80 41 01   line#1109 SELF 2 2 -7             <9>   R3 = R2;  R2 = R2["GetService"]                 -- It's Const#7   -- prepare for R2:GetService()
	  +FBE7: 01 C1 01 00   line#1109 LOADK 4 -8             <10>   R4 = "Players"                                  -- It's Const#8
	  +FBEB: A4 80 80 01   line#1109 CALL 2 3 2             <11>   R2 = R2(R3, R4)
	  +FBEF: 87 00 42 01   line#1109 GETTABLE 2 2 -9        <12>   R2 = R2["LocalPlayer"]                          -- It's Const#9
	  +FBF3: 87 40 42 01   line#1109 GETTABLE 2 2 -10       <13>   R2 = R2["Character"]                            -- It's Const#10
	  +FBF7: 87 80 42 01   line#1109 GETTABLE 2 2 -11       <14>   R2 = R2["HumanoidRootPart"]                     -- It's Const#11
	  +FBFB: 87 C0 42 01   line#1109 GETTABLE 2 2 -12       <15>   R2 = R2["CFrame"]                               -- It's Const#12
	  +FBFF: 64 40 00 01   line#1109 CALL 1 2 1             <16>   R1(R2)
	  +FC03: 46 C0 40 00   line#1110 GETTABUP 1 0 -4        <17>   R1 = Upv#1@_ENV["wait"]                         -- It's Const#4
	  +FC07: 64 40 80 00   line#1110 CALL 1 1 1             <18>   R1()
	  +FC0B: 46 40 41 00   line#1111 GETTABUP 1 0 -6        <19>   R1 = Upv#1@_ENV["game"]                         -- It's Const#6
	  +FC0F: 4C 80 C1 00   line#1111 SELF 1 1 -7            <20>   R2 = R1;  R1 = R1["GetService"]                 -- It's Const#7   -- prepare for R1:GetService()
	  +FC13: C1 C0 01 00   line#1111 LOADK 3 -8             <21>   R3 = "Players"                                  -- It's Const#8
	  +FC17: 64 80 80 01   line#1111 CALL 1 3 2             <22>   R1 = R1(R2, R3)
	  +FC1B: 47 00 C2 00   line#1111 GETTABLE 1 1 -9        <23>   R1 = R1["LocalPlayer"]                          -- It's Const#9
	  +FC1F: 47 40 C2 00   line#1111 GETTABLE 1 1 -10       <24>   R1 = R1["Character"]                            -- It's Const#10
	  +FC23: 47 80 C2 00   line#1111 GETTABLE 1 1 -11       <25>   R1 = R1["HumanoidRootPart"]                     -- It's Const#11
	  +FC27: 4C 00 C3 00   line#1111 SELF 1 1 -13           <26>   R2 = R1;  R1 = R1["FindFirstChild"]             -- It's Const#13   -- prepare for R1:FindFirstChild()
	  +FC2B: C1 40 03 00   line#1111 LOADK 3 -14            <27>   R3 = "BodyClip"                                 -- It's Const#14
	  +FC2F: 64 80 80 01   line#1111 CALL 1 3 2             <28>   R1 = R1(R2, R3)
	  +FC33: 62 00 00 00   line#1111 TEST 1 0               <29>   if R1 then GOTO <31>
	  +FC37: 1E C0 02 80   line#1111 JMP 0 12               <30>   GOTO <43>
	  +FC3B: 46 40 41 00   line#1112 GETTABUP 1 0 -6        <31>   R1 = Upv#1@_ENV["game"]                         -- It's Const#6
	  +FC3F: 4C 80 C1 00   line#1112 SELF 1 1 -7            <32>   R2 = R1;  R1 = R1["GetService"]                 -- It's Const#7   -- prepare for R1:GetService()
	  +FC43: C1 C0 01 00   line#1112 LOADK 3 -8             <33>   R3 = "Players"                                  -- It's Const#8
	  +FC47: 64 80 80 01   line#1112 CALL 1 3 2             <34>   R1 = R1(R2, R3)
	  +FC4B: 47 00 C2 00   line#1112 GETTABLE 1 1 -9        <35>   R1 = R1["LocalPlayer"]                          -- It's Const#9
	  +FC4F: 47 40 C2 00   line#1112 GETTABLE 1 1 -10       <36>   R1 = R1["Character"]                            -- It's Const#10
	  +FC53: 47 80 C2 00   line#1112 GETTABLE 1 1 -11       <37>   R1 = R1["HumanoidRootPart"]                     -- It's Const#11
	  +FC57: 4C 00 C3 00   line#1112 SELF 1 1 -13           <38>   R2 = R1;  R1 = R1["FindFirstChild"]             -- It's Const#13   -- prepare for R1:FindFirstChild()
	  +FC5B: C1 40 03 00   line#1112 LOADK 3 -14            <39>   R3 = "BodyClip"                                 -- It's Const#14
	  +FC5F: 64 80 80 01   line#1112 CALL 1 3 2             <40>   R1 = R1(R2, R3)
	  +FC63: 4C 80 C3 00   line#1112 SELF 1 1 -15           <41>   R2 = R1;  R1 = R1["Destroy"]                    -- It's Const#15   -- prepare for R1:Destroy()
	  +FC67: 64 40 00 01   line#1112 CALL 1 2 1             <42>   R1(R2)
	  +FC6B: 46 00 40 00   line#1114 GETTABUP 1 0 -1        <43>   R1 = Upv#1@_ENV["_G"]                           -- It's Const#1
	  +FC6F: 4A C0 C3 80   line#1114 SETTABLE 1 -2 -16      <44>   R1["StopTween"] = false                         -- It's Const#2, Const#16
	  +FC73: 46 00 40 00   line#1115 GETTABUP 1 0 -1        <45>   R1 = Upv#1@_ENV["_G"]                           -- It's Const#1
	  +FC77: 4A C0 43 88   line#1115 SETTABLE 1 -17 -16     <46>   R1["Clip"] = false                              -- It's Const#17, Const#16
	  +FC7B: 26 00 80 00   line#1117 RETURN 0 1             <47>   RETURN
	Functions: 0

	************ Function#27   (full path: main.27)
	Source line#: 1119..1131
	Parameters: 0
	Is vararg: no
	VM registers needed: 2
	Constants: 1
	  +FE25:Size=5: 70 63 61 6C 6C                  Const#1   string    "pcall"
	Upvalues: 1
	  Upv#1 is parent function's Upv#1              name: _ENV
	Instructions: 4
	  +FE0F: 06 00 40 00   line#1120 GETTABUP 0 0 -1         <1>   R0 = Upv#1@_ENV["pcall"]                        -- It's Const#1
	  +FE13: 6C 00 00 00   line#1130 CLOSURE 1 0             <2>   R1 = Function#1
	  +FE17: 24 40 00 01   line#1120 CALL 0 2 1              <3>   R0(R1)
	  +FE1B: 26 00 80 00   line#1131 RETURN 0 1              <4>   RETURN
	Functions: 1

		************ Function#1   (full path: main.27.1)
		Source line#: 1120..1130
		Parameters: 0
		Is vararg: no
		VM registers needed: 8
		Constants: 14
		  +FEC6:Size=4: 77 61 69 74                     Const#1   string    "wait"
		  +FECC:Size=5: 70 61 69 72 73                  Const#2   string    "pairs"
		  +FED3:Size=4: 67 61 6D 65                     Const#3   string    "game"
		  +FED9:Size=A: 47 65 74 53 65 72 76 69 63 65   Const#4   string    "GetService"
		  +FEE5:Size=7: 50 6C 61 79 65 72 73            Const#5   string    "Players"
		  +FEEE:Size=B: 4C 6F 63 61 6C 50 6C 61 79...   Const#6   string    "LocalPlayer"
		  +FEFB:Size=8: 42 61 63 6B 70 61 63 6B         Const#7   string    "Backpack"
		  +FF05:Size=B: 47 65 74 43 68 69 6C 64 72...   Const#8   string    "GetChildren"
		  +FF12:Size=3: 49 73 41                        Const#9   string    "IsA"
		  +FF17:Size=4: 54 6F 6F 6C                     Const#10  string    "Tool"
		  +FF1D:Size=E: 46 69 6E 64 46 69 72 73 74...   Const#11  string    "FindFirstChild"
		  +FF2D:Size=13: 52 65 6D 6F 74 65 46 75 6...   Const#12  string    "RemoteFunctionShoot"
		  +FF42:Size=F: 53 65 6C 65 63 74 57 65 61...   Const#13  string    "SelectWeaponGun"
		  +FF53:Size=4: 4E 61 6D 65                     Const#14  string    "Name"
		Upvalues: 1
		  Upv#1 is parent function's Upv#1              name: _ENV
		Locals: 5
		  Local#1   R0   def:<14>   scope:<15..29>      name: (for generator)
		  Local#2   R1   def:<14>   scope:<15..29>      name: (for state)
		  Local#3   R2   def:<14>   scope:<15..29>      name: (for control)
		  Local#4   R3   def:<15>   scope:<16..27>      name: i
		  Local#5   R4   def:<15>   scope:<16..27>      name: v
		Instructions: 31
		  +FE44: 06 00 40 00   line#1121 GETTABUP 0 0 -1         <1>   R0 = Upv#1@_ENV["wait"]                         -- It's Const#1
		  +FE48: 24 80 80 00   line#1121 CALL 0 1 2              <2>   R0 = R0()
		  +FE4C: 22 00 00 00   line#1121 TEST 0 0                <3>   if R0 then GOTO <5>
		  +FE50: 1E 40 06 80   line#1121 JMP 0 26                <4>   GOTO <31>
		  +FE54: 06 40 40 00   line#1122 GETTABUP 0 0 -2         <5>   R0 = Upv#1@_ENV["pairs"]                        -- It's Const#2
		  +FE58: 46 80 40 00   line#1122 GETTABUP 1 0 -3         <6>   R1 = Upv#1@_ENV["game"]                         -- It's Const#3
		  +FE5C: 4C C0 C0 00   line#1122 SELF 1 1 -4             <7>   R2 = R1;  R1 = R1["GetService"]                 -- It's Const#4   -- prepare for R1:GetService()
		  +FE60: C1 00 01 00   line#1122 LOADK 3 -5              <8>   R3 = "Players"                                  -- It's Const#5
		  +FE64: 64 80 80 01   line#1122 CALL 1 3 2              <9>   R1 = R1(R2, R3)
		  +FE68: 47 40 C1 00   line#1122 GETTABLE 1 1 -6        <10>   R1 = R1["LocalPlayer"]                          -- It's Const#6
		  +FE6C: 47 80 C1 00   line#1122 GETTABLE 1 1 -7        <11>   R1 = R1["Backpack"]                             -- It's Const#7
		  +FE70: 4C C0 C1 00   line#1122 SELF 1 1 -8            <12>   R2 = R1;  R1 = R1["GetChildren"]                -- It's Const#8   -- prepare for R1:GetChildren()
		  +FE74: 64 00 00 01   line#1122 CALL 1 2 0             <13>   R1,.. = R1(R2)
		  +FE78: 24 00 01 00   line#1122 CALL 0 0 4             <14>   R0, R1, R2 = R0(R1,..)
		  +FE7C: 1E C0 02 80   line#1122 JMP 0 12               <15>   GOTO <28>                                       -- for R3@i, R4@v in R0, R1, R2 do
		  +FE80: 4C 01 42 02   line#1123 SELF 5 4 -9            <16>   R6 = R4@v;  R5 = R4@v["IsA"]                    -- It's Const#9   -- prepare for R4@v:IsA()
		  +FE84: C1 41 02 00   line#1123 LOADK 7 -10            <17>   R7 = "Tool"                                     -- It's Const#10
		  +FE88: 64 81 80 01   line#1123 CALL 5 3 2             <18>   R5 = R5(R6, R7)
		  +FE8C: 62 01 00 00   line#1123 TEST 5 0               <19>   if R5 then GOTO <21>
		  +FE90: 1E 80 01 80   line#1123 JMP 0 7                <20>   GOTO <28>
		  +FE94: 4C 81 42 02   line#1124 SELF 5 4 -11           <21>   R6 = R4@v;  R5 = R4@v["FindFirstChild"]         -- It's Const#11   -- prepare for R4@v:FindFirstChild()
		  +FE98: C1 C1 02 00   line#1124 LOADK 7 -12            <22>   R7 = "RemoteFunctionShoot"                      -- It's Const#12
		  +FE9C: 64 81 80 01   line#1124 CALL 5 3 2             <23>   R5 = R5(R6, R7)
		  +FEA0: 62 01 00 00   line#1124 TEST 5 0               <24>   if R5 then GOTO <26>
		  +FEA4: 1E 40 00 80   line#1124 JMP 0 2                <25>   GOTO <28>
		  +FEA8: 47 41 43 02   line#1125 GETTABLE 5 4 -14       <26>   R5 = R4@v["Name"]                               -- It's Const#14
		  +FEAC: 08 40 01 86   line#1125 SETTABUP 0 -13 5       <27>   Upv#1@_ENV["SelectWeaponGun"] = R5              -- It's Const#13
		  +FEB0: 29 80 00 00   line#1122 TFORCALL 0 2           <28>   R3, R4 = R0(R1, R2)
		  +FEB4: AA 40 FC 7F   line#1122 TFORLOOP 2 -14         <29>   if R3 ~= nil then { R2 = R3;  GOTO <16> }       -- end of loop
		  +FEB8: 1E 40 F8 7F   line#1128 JMP 0 -30              <30>   GOTO <1>
		  +FEBC: 26 00 80 00   line#1130 RETURN 0 1             <31>   RETURN
		Functions: 0

	************ Function#28   (full path: main.28)
	Source line#: 1133..1137
	Parameters: 0
	Is vararg: no
	VM registers needed: 5
	Constants: 13
	  +100FB:Size=4: 67 61 6D 65                    Const#1   string    "game"
	  +10101:Size=A: 47 65 74 53 65 72 76 69 6...   Const#2   string    "GetService"
	  +1010D:Size=B: 56 69 72 74 75 61 6C 55 7...   Const#3   string    "VirtualUser"
	  +1011A:Size=B: 42 75 74 74 6F 6E 32 44 6...   Const#4   string    "Button2Down"
	  +10127:Size=7: 56 65 63 74 6F 72 32           Const#5   string    "Vector2"
	  +10130:Size=3: 6E 65 77                       Const#6   string    "new"
	  +10134:Size=4: 00 00 00 00                    Const#7   integer   0
	  +1013A:Size=9: 77 6F 72 6B 73 70 61 63 65     Const#8   string    "workspace"
	  +10145:Size=D: 43 75 72 72 65 6E 74 43 6...   Const#9   string    "CurrentCamera"
	  +10154:Size=6: 43 46 72 61 6D 65              Const#10  string    "CFrame"
	  +1015C:Size=4: 77 61 69 74                    Const#11  string    "wait"
	  +10161:Size=4: 01 00 00 00                    Const#12  integer   1
	  +10167:Size=9: 42 75 74 74 6F 6E 32 55 70     Const#13  string    "Button2Up"
	Upvalues: 1
	  Upv#1 is parent function's Upv#1              name: _ENV
	Instructions: 32
	  +10075: 06 00 40 00   line#1134 GETTABUP 0 0 -1         <1>   R0 = Upv#1@_ENV["game"]                         -- It's Const#1
	  +10079: 0C 40 40 00   line#1134 SELF 0 0 -2             <2>   R1 = R0;  R0 = R0["GetService"]                 -- It's Const#2   -- prepare for R0:GetService()
	  +1007D: 81 80 00 00   line#1134 LOADK 2 -3              <3>   R2 = "VirtualUser"                              -- It's Const#3
	  +10081: 24 80 80 01   line#1134 CALL 0 3 2              <4>   R0 = R0(R1, R2)
	  +10085: 0C C0 40 00   line#1134 SELF 0 0 -4             <5>   R1 = R0;  R0 = R0["Button2Down"]                -- It's Const#4   -- prepare for R0:Button2Down()
	  +10089: 86 00 41 00   line#1134 GETTABUP 2 0 -5         <6>   R2 = Upv#1@_ENV["Vector2"]                      -- It's Const#5
	  +1008D: 87 40 41 01   line#1134 GETTABLE 2 2 -6         <7>   R2 = R2["new"]                                  -- It's Const#6
	  +10091: C1 80 01 00   line#1134 LOADK 3 -7              <8>   R3 = 0                                          -- It's Const#7
	  +10095: 01 81 01 00   line#1134 LOADK 4 -7              <9>   R4 = 0                                          -- It's Const#7
	  +10099: A4 80 80 01   line#1134 CALL 2 3 2             <10>   R2 = R2(R3, R4)
	  +1009D: C6 C0 41 00   line#1134 GETTABUP 3 0 -8        <11>   R3 = Upv#1@_ENV["workspace"]                    -- It's Const#8
	  +100A1: C7 00 C2 01   line#1134 GETTABLE 3 3 -9        <12>   R3 = R3["CurrentCamera"]                        -- It's Const#9
	  +100A5: C7 40 C2 01   line#1134 GETTABLE 3 3 -10       <13>   R3 = R3["CFrame"]                               -- It's Const#10
	  +100A9: 24 40 00 02   line#1134 CALL 0 4 1             <14>   R0(R1, R2, R3)
	  +100AD: 06 80 42 00   line#1135 GETTABUP 0 0 -11       <15>   R0 = Upv#1@_ENV["wait"]                         -- It's Const#11
	  +100B1: 41 C0 02 00   line#1135 LOADK 1 -12            <16>   R1 = 1                                          -- It's Const#12
	  +100B5: 24 40 00 01   line#1135 CALL 0 2 1             <17>   R0(R1)
	  +100B9: 06 00 40 00   line#1136 GETTABUP 0 0 -1        <18>   R0 = Upv#1@_ENV["game"]                         -- It's Const#1
	  +100BD: 0C 40 40 00   line#1136 SELF 0 0 -2            <19>   R1 = R0;  R0 = R0["GetService"]                 -- It's Const#2   -- prepare for R0:GetService()
	  +100C1: 81 80 00 00   line#1136 LOADK 2 -3             <20>   R2 = "VirtualUser"                              -- It's Const#3
	  +100C5: 24 80 80 01   line#1136 CALL 0 3 2             <21>   R0 = R0(R1, R2)
	  +100C9: 0C 00 43 00   line#1136 SELF 0 0 -13           <22>   R1 = R0;  R0 = R0["Button2Up"]                  -- It's Const#13   -- prepare for R0:Button2Up()
	  +100CD: 86 00 41 00   line#1136 GETTABUP 2 0 -5        <23>   R2 = Upv#1@_ENV["Vector2"]                      -- It's Const#5
	  +100D1: 87 40 41 01   line#1136 GETTABLE 2 2 -6        <24>   R2 = R2["new"]                                  -- It's Const#6
	  +100D5: C1 80 01 00   line#1136 LOADK 3 -7             <25>   R3 = 0                                          -- It's Const#7
	  +100D9: 01 81 01 00   line#1136 LOADK 4 -7             <26>   R4 = 0                                          -- It's Const#7
	  +100DD: A4 80 80 01   line#1136 CALL 2 3 2             <27>   R2 = R2(R3, R4)
	  +100E1: C6 C0 41 00   line#1136 GETTABUP 3 0 -8        <28>   R3 = Upv#1@_ENV["workspace"]                    -- It's Const#8
	  +100E5: C7 00 C2 01   line#1136 GETTABLE 3 3 -9        <29>   R3 = R3["CurrentCamera"]                        -- It's Const#9
	  +100E9: C7 40 C2 01   line#1136 GETTABLE 3 3 -10       <30>   R3 = R3["CFrame"]                               -- It's Const#10
	  +100ED: 24 40 00 02   line#1136 CALL 0 4 1             <31>   R0(R1, R2, R3)
	  +100F1: 26 00 80 00   line#1137 RETURN 0 1             <32>   RETURN
	Functions: 0

	************ Function#29   (full path: main.29)
	Source line#: 1138..1203
	Parameters: 0
	Is vararg: no
	VM registers needed: 2
	Constants: 4
	  +10255:Size=4: 77 61 69 74                    Const#1   string    "wait"
	  +1025B:Size=2: 5F 47                          Const#2   string    "_G"
	  +1025F:Size=8: 41 75 74 6F 46 61 72 6D        Const#3   string    "AutoFarm"
	  +10269:Size=5: 70 63 61 6C 6C                 Const#4   string    "pcall"
	Upvalues: 1
	  Upv#1 is parent function's Upv#1              name: _ENV
	Instructions: 13
	  +1021B: 06 00 40 00   line#1139 GETTABUP 0 0 -1         <1>   R0 = Upv#1@_ENV["wait"]                         -- It's Const#1
	  +1021F: 24 80 80 00   line#1139 CALL 0 1 2              <2>   R0 = R0()
	  +10223: 22 00 00 00   line#1139 TEST 0 0                <3>   if R0 then GOTO <5>
	  +10227: 1E C0 01 80   line#1139 JMP 0 8                 <4>   GOTO <13>
	  +1022B: 06 40 40 00   line#1140 GETTABUP 0 0 -2         <5>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#2
	  +1022F: 07 80 40 00   line#1140 GETTABLE 0 0 -3         <6>   R0 = R0["AutoFarm"]                             -- It's Const#3
	  +10233: 22 00 00 00   line#1140 TEST 0 0                <7>   if R0 then GOTO <9>
	  +10237: 1E C0 FD 7F   line#1140 JMP 0 -8                <8>   GOTO <1>
	  +1023B: 06 C0 40 00   line#1141 GETTABUP 0 0 -4         <9>   R0 = Upv#1@_ENV["pcall"]                        -- It's Const#4
	  +1023F: 6C 00 00 00   line#1200 CLOSURE 1 0            <10>   R1 = Function#1
	  +10243: 24 40 00 01   line#1141 CALL 0 2 1             <11>   R0(R1)
	  +10247: 1E C0 FC 7F   line#1201 JMP 0 -12              <12>   GOTO <1>
	  +1024B: 26 00 80 00   line#1203 RETURN 0 1             <13>   RETURN
	Functions: 1

		************ Function#1   (full path: main.29.1)
		Source line#: 1141..1200
		Parameters: 0
		Is vararg: no
		VM registers needed: 12
		Constants: 75
		  +10792:Size=4: 67 61 6D 65                    Const#1   string    "game"
		  +10798:Size=A: 47 65 74 53 65 72 76 69 6...   Const#2   string    "GetService"
		  +107A4:Size=7: 50 6C 61 79 65 72 73           Const#3   string    "Players"
		  +107AD:Size=B: 4C 6F 63 61 6C 50 6C 61 7...   Const#4   string    "LocalPlayer"
		  +107BA:Size=9: 50 6C 61 79 65 72 47 75 69     Const#5   string    "PlayerGui"
		  +107C5:Size=4: 4D 61 69 6E                    Const#6   string    "Main"
		  +107CB:Size=5: 51 75 65 73 74                 Const#7   string    "Quest"
		  +107D2:Size=9: 43 6F 6E 74 61 69 6E 65 72     Const#8   string    "Container"
		  +107DD:Size=A: 51 75 65 73 74 54 69 74 6...   Const#9   string    "QuestTitle"
		  +107E9:Size=5: 54 69 74 6C 65                 Const#10  string    "Title"
		  +107F0:Size=4: 54 65 78 74                    Const#11  string    "Text"
		  +107F6:Size=6: 73 74 72 69 6E 67              Const#12  string    "string"
		  +107FE:Size=4: 66 69 6E 64                    Const#13  string    "find"
		  +10804:Size=7: 4E 61 6D 65 4D 6F 6E           Const#14  string    "NameMon"
		  +1080D:Size=B: 53 74 61 72 74 4D 61 67 6...   Const#15  string    "StartMagnet"
		  +10819:Size=1: 00                             Const#16  boolean   false
		  +1081C:Size=11: 52 65 70 6C 69 63 61 74 ...   Const#17  string    "ReplicatedStorage"
		  +1082F:Size=7: 52 65 6D 6F 74 65 73           Const#18  string    "Remotes"
		  +10838:Size=6: 43 6F 6D 6D 46 5F              Const#19  string    "CommF_"
		  +10840:Size=C: 49 6E 76 6F 6B 65 53 65 7...   Const#20  string    "InvokeServer"
		  +1084E:Size=C: 41 62 61 6E 64 6F 6E 51 7...   Const#21  string    "AbandonQuest"
		  +1085C:Size=7: 56 69 73 69 62 6C 65           Const#22  string    "Visible"
		  +10865:Size=A: 43 68 65 63 6B 51 75 65 7...   Const#23  string    "CheckQuest"
		  +10871:Size=4: 77 61 69 74                    Const#24  string    "wait"
		  +10877:Size=3: 54 50 31                       Const#25  string    "TP1"
		  +1087C:Size=B: 43 46 72 61 6D 65 51 75 6...   Const#26  string    "CFrameQuest"
		  +10889:Size=8: 50 6F 73 69 74 69 6F 6E        Const#27  string    "Position"
		  +10893:Size=9: 43 68 61 72 61 63 74 65 72     Const#28  string    "Character"
		  +1089E:Size=10: 48 75 6D 61 6E 6F 69 64 ...   Const#29  string    "HumanoidRootPart"
		  +108B0:Size=9: 4D 61 67 6E 69 74 75 64 65     Const#30  string    "Magnitude"
		  +108BA:Size=4: 03 00 00 00                    Const#31  integer   3
		  +108C0:Size=2: 5F 47                          Const#32  string    "_G"
		  +108C4:Size=8: 41 75 74 6F 46 61 72 6D        Const#33  string    "AutoFarm"
		  +108CD:Size=8: 9A 99 99 99 99 99 B9 3F        Const#34  float     0.1
		  +108D7:Size=A: 53 74 61 72 74 51 75 65 7...   Const#35  string    "StartQuest"
		  +108E3:Size=6: 4E 51 75 65 73 74              Const#36  string    "NQuest"
		  +108EB:Size=6: 4C 51 75 65 73 74              Const#37  string    "LQuest"
		  +108F2:Size=8: 00 00 00 00 00 00 E0 3F        Const#38  float     0.5
		  +108FB:Size=1: 01                             Const#39  boolean   true
		  +108FE:Size=9: 57 6F 72 6B 73 70 61 63 65     Const#40  string    "Workspace"
		  +10909:Size=7: 45 6E 65 6D 69 65 73           Const#41  string    "Enemies"
		  +10912:Size=E: 46 69 6E 64 46 69 72 73 7...   Const#42  string    "FindFirstChild"
		  +10922:Size=3: 4D 6F 6E                       Const#43  string    "Mon"
		  +10927:Size=5: 70 61 69 72 73                 Const#44  string    "pairs"
		  +1092E:Size=B: 47 65 74 43 68 69 6C 64 7...   Const#45  string    "GetChildren"
		  +1093B:Size=8: 48 75 6D 61 6E 6F 69 64        Const#46  string    "Humanoid"
		  +10945:Size=6: 48 65 61 6C 74 68              Const#47  string    "Health"
		  +1094C:Size=4: 00 00 00 00                    Const#48  integer   0
		  +10952:Size=4: 4E 61 6D 65                    Const#49  string    "Name"
		  +10958:Size=4: 74 61 73 6B                    Const#50  string    "task"
		  +1095E:Size=B: 45 71 75 69 70 57 65 61 7...   Const#51  string    "EquipWeapon"
		  +1096B:Size=C: 53 65 6C 65 63 74 57 65 6...   Const#52  string    "SelectWeapon"
		  +10979:Size=8: 41 75 74 6F 48 61 6B 69        Const#53  string    "AutoHaki"
		  +10983:Size=6: 50 6F 73 4D 6F 6E              Const#54  string    "PosMon"
		  +1098B:Size=6: 43 46 72 61 6D 65              Const#55  string    "CFrame"
		  +10993:Size=3: 6E 65 77                       Const#56  string    "new"
		  +10997:Size=4: 02 00 00 00                    Const#57  integer   2
		  +1099C:Size=4: 0F 00 00 00                    Const#58  integer   15
		  +109A2:Size=A: 43 61 6E 43 6F 6C 6C 69 6...   Const#59  string    "CanCollide"
		  +109AE:Size=9: 57 61 6C 6B 53 70 65 65 64     Const#60  string    "WalkSpeed"
		  +109B9:Size=4: 48 65 61 64                    Const#61  string    "Head"
		  +109BF:Size=4: 53 69 7A 65                    Const#62  string    "Size"
		  +109C5:Size=7: 56 65 63 74 6F 72 33           Const#63  string    "Vector3"
		  +109CD:Size=4: 46 00 00 00                    Const#64  integer   70
		  +109D3:Size=B: 56 69 72 74 75 61 6C 55 7...   Const#65  string    "VirtualUser"
		  +109E0:Size=11: 43 61 70 74 75 72 65 43 ...   Const#66  string    "CaptureController"
		  +109F3:Size=B: 42 75 74 74 6F 6E 31 44 6...   Const#67  string    "Button1Down"
		  +10A00:Size=7: 56 65 63 74 6F 72 32           Const#68  string    "Vector2"
		  +10A08:Size=4: 00 05 00 00                    Const#69  integer   1280
		  +10A0D:Size=4: A0 02 00 00                    Const#70  integer   672
		  +10A13:Size=6: 50 61 72 65 6E 74              Const#71  string    "Parent"
		  +10A1A:Size=4: 0A 00 00 00                    Const#72  integer   10
		  +10A1F:Size=4: 01 00 00 00                    Const#73  integer   1
		  +10A24:Size=0:                                Const#74  nil       nil
		  +10A26:Size=6: 4F 6C 64 50 6F 73              Const#75  string    "OldPos"
		Upvalues: 1
		  Upv#1 is parent function's Upv#1              name: _ENV
		Locals: 6
		  Local#1   R0   def:<12>   scope:<13..321>     name: QuestTitle
		  Local#2   R1   def:<130>  scope:<131..257>    name: (for generator)
		  Local#3   R2   def:<130>  scope:<131..257>    name: (for state)
		  Local#4   R3   def:<130>  scope:<131..257>    name: (for control)
		  Local#5   R4   def:<131>  scope:<132..255>    name: i
		  Local#6   R5   def:<131>  scope:<132..255>    name: v
		Instructions: 321
		  +10288: 06 00 40 00   line#1142 GETTABUP 0 0 -1         <1>   R0 = Upv#1@_ENV["game"]                         -- It's Const#1
		  +1028C: 0C 40 40 00   line#1142 SELF 0 0 -2             <2>   R1 = R0;  R0 = R0["GetService"]                 -- It's Const#2   -- prepare for R0:GetService()
		  +10290: 81 80 00 00   line#1142 LOADK 2 -3              <3>   R2 = "Players"                                  -- It's Const#3
		  +10294: 24 80 80 01   line#1142 CALL 0 3 2              <4>   R0 = R0(R1, R2)
		  +10298: 07 C0 40 00   line#1142 GETTABLE 0 0 -4         <5>   R0 = R0["LocalPlayer"]                          -- It's Const#4
		  +1029C: 07 00 41 00   line#1142 GETTABLE 0 0 -5         <6>   R0 = R0["PlayerGui"]                            -- It's Const#5
		  +102A0: 07 40 41 00   line#1142 GETTABLE 0 0 -6         <7>   R0 = R0["Main"]                                 -- It's Const#6
		  +102A4: 07 80 41 00   line#1142 GETTABLE 0 0 -7         <8>   R0 = R0["Quest"]                                -- It's Const#7
		  +102A8: 07 C0 41 00   line#1142 GETTABLE 0 0 -8         <9>   R0 = R0["Container"]                            -- It's Const#8
		  +102AC: 07 00 42 00   line#1142 GETTABLE 0 0 -9        <10>   R0 = R0["QuestTitle"]                           -- It's Const#9
		  +102B0: 07 40 42 00   line#1142 GETTABLE 0 0 -10       <11>   R0 = R0["Title"]                                -- It's Const#10
		  +102B4: 07 80 42 00   line#1142 GETTABLE 0 0 -11       <12>   R0@QuestTitle = R0["Text"]                      -- It's Const#11
		  +102B8: 46 C0 42 00   line#1143 GETTABUP 1 0 -12       <13>   R1 = Upv#1@_ENV["string"]                       -- It's Const#12
		  +102BC: 47 00 C3 00   line#1143 GETTABLE 1 1 -13       <14>   R1 = R1["find"]                                 -- It's Const#13
		  +102C0: 80 00 00 00   line#1143 MOVE 2 0               <15>   R2 = R0@QuestTitle
		  +102C4: C6 40 43 00   line#1143 GETTABUP 3 0 -14       <16>   R3 = Upv#1@_ENV["NameMon"]                      -- It's Const#14
		  +102C8: 64 80 80 01   line#1143 CALL 1 3 2             <17>   R1 = R1(R2, R3)
		  +102CC: 62 40 00 00   line#1143 TEST 1 1               <18>   if not R1 then GOTO <20>
		  +102D0: 1E 40 02 80   line#1143 JMP 0 10               <19>   GOTO <30>
		  +102D4: 08 C0 43 87   line#1144 SETTABUP 0 -15 -16     <20>   Upv#1@_ENV["StartMagnet"] = false               -- It's Const#15, Const#16
		  +102D8: 46 00 40 00   line#1145 GETTABUP 1 0 -1        <21>   R1 = Upv#1@_ENV["game"]                         -- It's Const#1
		  +102DC: 4C 40 C0 00   line#1145 SELF 1 1 -2            <22>   R2 = R1;  R1 = R1["GetService"]                 -- It's Const#2   -- prepare for R1:GetService()
		  +102E0: C1 00 04 00   line#1145 LOADK 3 -17            <23>   R3 = "ReplicatedStorage"                        -- It's Const#17
		  +102E4: 64 80 80 01   line#1145 CALL 1 3 2             <24>   R1 = R1(R2, R3)
		  +102E8: 47 40 C4 00   line#1145 GETTABLE 1 1 -18       <25>   R1 = R1["Remotes"]                              -- It's Const#18
		  +102EC: 47 80 C4 00   line#1145 GETTABLE 1 1 -19       <26>   R1 = R1["CommF_"]                               -- It's Const#19
		  +102F0: 4C C0 C4 00   line#1145 SELF 1 1 -20           <27>   R2 = R1;  R1 = R1["InvokeServer"]               -- It's Const#20   -- prepare for R1:InvokeServer()
		  +102F4: C1 00 05 00   line#1145 LOADK 3 -21            <28>   R3 = "AbandonQuest"                             -- It's Const#21
		  +102F8: 64 40 80 01   line#1145 CALL 1 3 1             <29>   R1(R2, R3)
		  +102FC: 46 00 40 00   line#1147 GETTABUP 1 0 -1        <30>   R1 = Upv#1@_ENV["game"]                         -- It's Const#1
		  +10300: 4C 40 C0 00   line#1147 SELF 1 1 -2            <31>   R2 = R1;  R1 = R1["GetService"]                 -- It's Const#2   -- prepare for R1:GetService()
		  +10304: C1 80 00 00   line#1147 LOADK 3 -3             <32>   R3 = "Players"                                  -- It's Const#3
		  +10308: 64 80 80 01   line#1147 CALL 1 3 2             <33>   R1 = R1(R2, R3)
		  +1030C: 47 C0 C0 00   line#1147 GETTABLE 1 1 -4        <34>   R1 = R1["LocalPlayer"]                          -- It's Const#4
		  +10310: 47 00 C1 00   line#1147 GETTABLE 1 1 -5        <35>   R1 = R1["PlayerGui"]                            -- It's Const#5
		  +10314: 47 40 C1 00   line#1147 GETTABLE 1 1 -6        <36>   R1 = R1["Main"]                                 -- It's Const#6
		  +10318: 47 80 C1 00   line#1147 GETTABLE 1 1 -7        <37>   R1 = R1["Quest"]                                -- It's Const#7
		  +1031C: 47 40 C5 00   line#1147 GETTABLE 1 1 -22       <38>   R1 = R1["Visible"]                              -- It's Const#22
		  +10320: 1F C0 C3 00   line#1147 EQ 0 1 -16             <39>   if R1 == false then GOTO <41>                   -- It's Const#16
		  +10324: 1E 40 0E 80   line#1147 JMP 0 58               <40>   GOTO <99>
		  +10328: 08 C0 43 87   line#1148 SETTABUP 0 -15 -16     <41>   Upv#1@_ENV["StartMagnet"] = false               -- It's Const#15, Const#16
		  +1032C: 46 80 45 00   line#1149 GETTABUP 1 0 -23       <42>   R1 = Upv#1@_ENV["CheckQuest"]                   -- It's Const#23
		  +10330: 64 40 80 00   line#1149 CALL 1 1 1             <43>   R1()
		  +10334: 46 C0 45 00   line#1150 GETTABUP 1 0 -24       <44>   R1 = Upv#1@_ENV["wait"]                         -- It's Const#24
		  +10338: 64 40 80 00   line#1150 CALL 1 1 1             <45>   R1()
		  +1033C: 46 00 46 00   line#1150 GETTABUP 1 0 -25       <46>   R1 = Upv#1@_ENV["TP1"]                          -- It's Const#25
		  +10340: 86 40 46 00   line#1150 GETTABUP 2 0 -26       <47>   R2 = Upv#1@_ENV["CFrameQuest"]                  -- It's Const#26
		  +10344: 64 40 00 01   line#1150 CALL 1 2 1             <48>   R1(R2)
		  +10348: 46 40 46 00   line#1150 GETTABUP 1 0 -26       <49>   R1 = Upv#1@_ENV["CFrameQuest"]                  -- It's Const#26
		  +1034C: 47 80 C6 00   line#1150 GETTABLE 1 1 -27       <50>   R1 = R1["Position"]                             -- It's Const#27
		  +10350: 86 00 40 00   line#1150 GETTABUP 2 0 -1        <51>   R2 = Upv#1@_ENV["game"]                         -- It's Const#1
		  +10354: 8C 40 40 01   line#1150 SELF 2 2 -2            <52>   R3 = R2;  R2 = R2["GetService"]                 -- It's Const#2   -- prepare for R2:GetService()
		  +10358: 01 81 00 00   line#1150 LOADK 4 -3             <53>   R4 = "Players"                                  -- It's Const#3
		  +1035C: A4 80 80 01   line#1150 CALL 2 3 2             <54>   R2 = R2(R3, R4)
		  +10360: 87 C0 40 01   line#1150 GETTABLE 2 2 -4        <55>   R2 = R2["LocalPlayer"]                          -- It's Const#4
		  +10364: 87 C0 46 01   line#1150 GETTABLE 2 2 -28       <56>   R2 = R2["Character"]                            -- It's Const#28
		  +10368: 87 00 47 01   line#1150 GETTABLE 2 2 -29       <57>   R2 = R2["HumanoidRootPart"]                     -- It's Const#29
		  +1036C: 87 80 46 01   line#1150 GETTABLE 2 2 -27       <58>   R2 = R2["Position"]                             -- It's Const#27
		  +10370: 4E 80 80 00   line#1150 SUB 1 1 2              <59>   R1 = R1 - R2
		  +10374: 47 40 C7 00   line#1150 GETTABLE 1 1 -30       <60>   R1 = R1["Magnitude"]                            -- It's Const#30
		  +10378: 61 80 C7 00   line#1150 LE 1 1 -31             <61>   if not (R1 <= 3) then GOTO <63>                 -- It's Const#31
		  +1037C: 1E C0 00 80   line#1150 JMP 0 4                <62>   GOTO <67>
		  +10380: 46 C0 47 00   line#1150 GETTABUP 1 0 -32       <63>   R1 = Upv#1@_ENV["_G"]                           -- It's Const#32
		  +10384: 47 00 C8 00   line#1150 GETTABLE 1 1 -33       <64>   R1 = R1["AutoFarm"]                             -- It's Const#33
		  +10388: 62 40 00 00   line#1150 TEST 1 1               <65>   if not R1 then GOTO <67>
		  +1038C: 1E 00 FA 7F   line#1150 JMP 0 -23              <66>   GOTO <44>
		  +10390: 46 40 46 00   line#1151 GETTABUP 1 0 -26       <67>   R1 = Upv#1@_ENV["CFrameQuest"]                  -- It's Const#26
		  +10394: 47 80 C6 00   line#1151 GETTABLE 1 1 -27       <68>   R1 = R1["Position"]                             -- It's Const#27
		  +10398: 86 00 40 00   line#1151 GETTABUP 2 0 -1        <69>   R2 = Upv#1@_ENV["game"]                         -- It's Const#1
		  +1039C: 8C 40 40 01   line#1151 SELF 2 2 -2            <70>   R3 = R2;  R2 = R2["GetService"]                 -- It's Const#2   -- prepare for R2:GetService()
		  +103A0: 01 81 00 00   line#1151 LOADK 4 -3             <71>   R4 = "Players"                                  -- It's Const#3
		  +103A4: A4 80 80 01   line#1151 CALL 2 3 2             <72>   R2 = R2(R3, R4)
		  +103A8: 87 C0 40 01   line#1151 GETTABLE 2 2 -4        <73>   R2 = R2["LocalPlayer"]                          -- It's Const#4
		  +103AC: 87 C0 46 01   line#1151 GETTABLE 2 2 -28       <74>   R2 = R2["Character"]                            -- It's Const#28
		  +103B0: 87 00 47 01   line#1151 GETTABLE 2 2 -29       <75>   R2 = R2["HumanoidRootPart"]                     -- It's Const#29
		  +103B4: 87 80 46 01   line#1151 GETTABLE 2 2 -27       <76>   R2 = R2["Position"]                             -- It's Const#27
		  +103B8: 4E 80 80 00   line#1151 SUB 1 1 2              <77>   R1 = R1 - R2
		  +103BC: 47 40 C7 00   line#1151 GETTABLE 1 1 -30       <78>   R1 = R1["Magnitude"]                            -- It's Const#30
		  +103C0: 21 80 C7 00   line#1151 LE 0 1 -31             <79>   if R1 <= 3 then GOTO <81>                       -- It's Const#31
		  +103C4: 1E C0 3B 80   line#1151 JMP 0 240              <80>   GOTO <321>
		  +103C8: 46 C0 45 00   line#1152 GETTABUP 1 0 -24       <81>   R1 = Upv#1@_ENV["wait"]                         -- It's Const#24
		  +103CC: 81 40 08 00   line#1152 LOADK 2 -34            <82>   R2 = 0.1                                        -- It's Const#34
		  +103D0: 64 40 00 01   line#1152 CALL 1 2 1             <83>   R1(R2)
		  +103D4: 46 00 40 00   line#1153 GETTABUP 1 0 -1        <84>   R1 = Upv#1@_ENV["game"]                         -- It's Const#1
		  +103D8: 4C 40 C0 00   line#1153 SELF 1 1 -2            <85>   R2 = R1;  R1 = R1["GetService"]                 -- It's Const#2   -- prepare for R1:GetService()
		  +103DC: C1 00 04 00   line#1153 LOADK 3 -17            <86>   R3 = "ReplicatedStorage"                        -- It's Const#17
		  +103E0: 64 80 80 01   line#1153 CALL 1 3 2             <87>   R1 = R1(R2, R3)
		  +103E4: 47 40 C4 00   line#1153 GETTABLE 1 1 -18       <88>   R1 = R1["Remotes"]                              -- It's Const#18
		  +103E8: 47 80 C4 00   line#1153 GETTABLE 1 1 -19       <89>   R1 = R1["CommF_"]                               -- It's Const#19
		  +103EC: 4C C0 C4 00   line#1153 SELF 1 1 -20           <90>   R2 = R1;  R1 = R1["InvokeServer"]               -- It's Const#20   -- prepare for R1:InvokeServer()
		  +103F0: C1 80 08 00   line#1153 LOADK 3 -35            <91>   R3 = "StartQuest"                               -- It's Const#35
		  +103F4: 06 C1 48 00   line#1153 GETTABUP 4 0 -36       <92>   R4 = Upv#1@_ENV["NQuest"]                       -- It's Const#36
		  +103F8: 46 01 49 00   line#1153 GETTABUP 5 0 -37       <93>   R5 = Upv#1@_ENV["LQuest"]                       -- It's Const#37
		  +103FC: 64 40 80 02   line#1153 CALL 1 5 1             <94>   R1(R2,..,R5)
		  +10400: 46 C0 45 00   line#1154 GETTABUP 1 0 -24       <95>   R1 = Upv#1@_ENV["wait"]                         -- It's Const#24
		  +10404: 81 40 09 00   line#1154 LOADK 2 -38            <96>   R2 = 0.5                                        -- It's Const#38
		  +10408: 64 40 00 01   line#1154 CALL 1 2 1             <97>   R1(R2)
		  +1040C: 1E 40 37 80   line#1155 JMP 0 222              <98>   GOTO <321>
		  +10410: 46 00 40 00   line#1156 GETTABUP 1 0 -1        <99>   R1 = Upv#1@_ENV["game"]                         -- It's Const#1
		  +10414: 4C 40 C0 00   line#1156 SELF 1 1 -2           <100>   R2 = R1;  R1 = R1["GetService"]                 -- It's Const#2   -- prepare for R1:GetService()
		  +10418: C1 80 00 00   line#1156 LOADK 3 -3            <101>   R3 = "Players"                                  -- It's Const#3
		  +1041C: 64 80 80 01   line#1156 CALL 1 3 2            <102>   R1 = R1(R2, R3)
		  +10420: 47 C0 C0 00   line#1156 GETTABLE 1 1 -4       <103>   R1 = R1["LocalPlayer"]                          -- It's Const#4
		  +10424: 47 00 C1 00   line#1156 GETTABLE 1 1 -5       <104>   R1 = R1["PlayerGui"]                            -- It's Const#5
		  +10428: 47 40 C1 00   line#1156 GETTABLE 1 1 -6       <105>   R1 = R1["Main"]                                 -- It's Const#6
		  +1042C: 47 80 C1 00   line#1156 GETTABLE 1 1 -7       <106>   R1 = R1["Quest"]                                -- It's Const#7
		  +10430: 47 40 C5 00   line#1156 GETTABLE 1 1 -22      <107>   R1 = R1["Visible"]                              -- It's Const#22
		  +10434: 1F 80 C9 00   line#1156 EQ 0 1 -39            <108>   if R1 == true then GOTO <110>                   -- It's Const#39
		  +10438: 1E 80 34 80   line#1156 JMP 0 211             <109>   GOTO <321>
		  +1043C: 46 80 45 00   line#1157 GETTABUP 1 0 -23      <110>   R1 = Upv#1@_ENV["CheckQuest"]                   -- It's Const#23
		  +10440: 64 40 80 00   line#1157 CALL 1 1 1            <111>   R1()
		  +10444: 46 00 40 00   line#1158 GETTABUP 1 0 -1       <112>   R1 = Upv#1@_ENV["game"]                         -- It's Const#1
		  +10448: 4C 40 C0 00   line#1158 SELF 1 1 -2           <113>   R2 = R1;  R1 = R1["GetService"]                 -- It's Const#2   -- prepare for R1:GetService()
		  +1044C: C1 C0 09 00   line#1158 LOADK 3 -40           <114>   R3 = "Workspace"                                -- It's Const#40
		  +10450: 64 80 80 01   line#1158 CALL 1 3 2            <115>   R1 = R1(R2, R3)
		  +10454: 47 00 CA 00   line#1158 GETTABLE 1 1 -41      <116>   R1 = R1["Enemies"]                              -- It's Const#41
		  +10458: 4C 40 CA 00   line#1158 SELF 1 1 -42          <117>   R2 = R1;  R1 = R1["FindFirstChild"]             -- It's Const#42   -- prepare for R1:FindFirstChild()
		  +1045C: C6 80 4A 00   line#1158 GETTABUP 3 0 -43      <118>   R3 = Upv#1@_ENV["Mon"]                          -- It's Const#43
		  +10460: 64 80 80 01   line#1158 CALL 1 3 2            <119>   R1 = R1(R2, R3)
		  +10464: 62 00 00 00   line#1158 TEST 1 0              <120>   if R1 then GOTO <122>
		  +10468: 1E 00 22 80   line#1158 JMP 0 137             <121>   GOTO <259>
		  +1046C: 46 C0 4A 00   line#1159 GETTABUP 1 0 -44      <122>   R1 = Upv#1@_ENV["pairs"]                        -- It's Const#44
		  +10470: 86 00 40 00   line#1159 GETTABUP 2 0 -1       <123>   R2 = Upv#1@_ENV["game"]                         -- It's Const#1
		  +10474: 8C 40 40 01   line#1159 SELF 2 2 -2           <124>   R3 = R2;  R2 = R2["GetService"]                 -- It's Const#2   -- prepare for R2:GetService()
		  +10478: 01 C1 09 00   line#1159 LOADK 4 -40           <125>   R4 = "Workspace"                                -- It's Const#40
		  +1047C: A4 80 80 01   line#1159 CALL 2 3 2            <126>   R2 = R2(R3, R4)
		  +10480: 87 00 4A 01   line#1159 GETTABLE 2 2 -41      <127>   R2 = R2["Enemies"]                              -- It's Const#41
		  +10484: 8C 00 4B 01   line#1159 SELF 2 2 -45          <128>   R3 = R2;  R2 = R2["GetChildren"]                -- It's Const#45   -- prepare for R2:GetChildren()
		  +10488: A4 00 00 01   line#1159 CALL 2 2 0            <129>   R2,.. = R2(R3)
		  +1048C: 64 00 01 00   line#1159 CALL 1 0 4            <130>   R1, R2, R3 = R1(R2,..)
		  +10490: 1E C0 1E 80   line#1159 JMP 0 124             <131>   GOTO <256>                                      -- for R4@i, R5@v in R1, R2, R3 do
		  +10494: 8C 41 CA 02   line#1160 SELF 6 5 -42          <132>   R7 = R5@v;  R6 = R5@v["FindFirstChild"]         -- It's Const#42   -- prepare for R5@v:FindFirstChild()
		  +10498: 01 02 07 00   line#1160 LOADK 8 -29           <133>   R8 = "HumanoidRootPart"                         -- It's Const#29
		  +1049C: A4 81 80 01   line#1160 CALL 6 3 2            <134>   R6 = R6(R7, R8)
		  +104A0: A2 01 00 00   line#1160 TEST 6 0              <135>   if R6 then GOTO <137>
		  +104A4: 1E 80 1D 80   line#1160 JMP 0 119             <136>   GOTO <256>
		  +104A8: 8C 41 CA 02   line#1160 SELF 6 5 -42          <137>   R7 = R5@v;  R6 = R5@v["FindFirstChild"]         -- It's Const#42   -- prepare for R5@v:FindFirstChild()
		  +104AC: 01 42 0B 00   line#1160 LOADK 8 -46           <138>   R8 = "Humanoid"                                 -- It's Const#46
		  +104B0: A4 81 80 01   line#1160 CALL 6 3 2            <139>   R6 = R6(R7, R8)
		  +104B4: A2 01 00 00   line#1160 TEST 6 0              <140>   if R6 then GOTO <142>
		  +104B8: 1E 40 1C 80   line#1160 JMP 0 114             <141>   GOTO <256>
		  +104BC: 87 41 CB 02   line#1160 GETTABLE 6 5 -46      <142>   R6 = R5@v["Humanoid"]                           -- It's Const#46
		  +104C0: 87 81 4B 03   line#1160 GETTABLE 6 6 -47      <143>   R6 = R6["Health"]                               -- It's Const#47
		  +104C4: 20 80 81 97   line#1160 LT 0 -48 6            <144>   if R6 > 0 then GOTO <146>                       -- It's Const#48
		  +104C8: 1E 40 1B 80   line#1160 JMP 0 110             <145>   GOTO <256>
		  +104CC: 87 01 CC 02   line#1161 GETTABLE 6 5 -49      <146>   R6 = R5@v["Name"]                               -- It's Const#49
		  +104D0: C6 81 4A 00   line#1161 GETTABUP 7 0 -43      <147>   R7 = Upv#1@_ENV["Mon"]                          -- It's Const#43
		  +104D4: 1F C0 01 03   line#1161 EQ 0 6 7              <148>   if R6 == R7 then GOTO <150>
		  +104D8: 1E 40 1A 80   line#1161 JMP 0 106             <149>   GOTO <256>
		  +104DC: 86 C1 42 00   line#1162 GETTABUP 6 0 -12      <150>   R6 = Upv#1@_ENV["string"]                       -- It's Const#12
		  +104E0: 87 01 43 03   line#1162 GETTABLE 6 6 -13      <151>   R6 = R6["find"]                                 -- It's Const#13
		  +104E4: C6 01 40 00   line#1162 GETTABUP 7 0 -1       <152>   R7 = Upv#1@_ENV["game"]                         -- It's Const#1
		  +104E8: CC 41 C0 03   line#1162 SELF 7 7 -2           <153>   R8 = R7;  R7 = R7["GetService"]                 -- It's Const#2   -- prepare for R7:GetService()
		  +104EC: 41 82 00 00   line#1162 LOADK 9 -3            <154>   R9 = "Players"                                  -- It's Const#3
		  +104F0: E4 81 80 01   line#1162 CALL 7 3 2            <155>   R7 = R7(R8, R9)
		  +104F4: C7 C1 C0 03   line#1162 GETTABLE 7 7 -4       <156>   R7 = R7["LocalPlayer"]                          -- It's Const#4
		  +104F8: C7 01 C1 03   line#1162 GETTABLE 7 7 -5       <157>   R7 = R7["PlayerGui"]                            -- It's Const#5
		  +104FC: C7 41 C1 03   line#1162 GETTABLE 7 7 -6       <158>   R7 = R7["Main"]                                 -- It's Const#6
		  +10500: C7 81 C1 03   line#1162 GETTABLE 7 7 -7       <159>   R7 = R7["Quest"]                                -- It's Const#7
		  +10504: C7 C1 C1 03   line#1162 GETTABLE 7 7 -8       <160>   R7 = R7["Container"]                            -- It's Const#8
		  +10508: C7 01 C2 03   line#1162 GETTABLE 7 7 -9       <161>   R7 = R7["QuestTitle"]                           -- It's Const#9
		  +1050C: C7 41 C2 03   line#1162 GETTABLE 7 7 -10      <162>   R7 = R7["Title"]                                -- It's Const#10
		  +10510: C7 81 C2 03   line#1162 GETTABLE 7 7 -11      <163>   R7 = R7["Text"]                                 -- It's Const#11
		  +10514: 06 42 43 00   line#1162 GETTABUP 8 0 -14      <164>   R8 = Upv#1@_ENV["NameMon"]                      -- It's Const#14
		  +10518: A4 81 80 01   line#1162 CALL 6 3 2            <165>   R6 = R6(R7, R8)
		  +1051C: A2 01 00 00   line#1162 TEST 6 0              <166>   if R6 then GOTO <168>
		  +10520: 1E 40 13 80   line#1162 JMP 0 78              <167>   GOTO <246>
		  +10524: 86 41 4C 00   line#1163 GETTABUP 6 0 -50      <168>   R6 = Upv#1@_ENV["task"]                         -- It's Const#50
		  +10528: 87 C1 45 03   line#1163 GETTABLE 6 6 -24      <169>   R6 = R6["wait"]                                 -- It's Const#24
		  +1052C: A4 41 80 00   line#1163 CALL 6 1 1            <170>   R6()
		  +10530: 86 81 4C 00   line#1164 GETTABUP 6 0 -51      <171>   R6 = Upv#1@_ENV["EquipWeapon"]                  -- It's Const#51
		  +10534: C6 C1 47 00   line#1164 GETTABUP 7 0 -32      <172>   R7 = Upv#1@_ENV["_G"]                           -- It's Const#32
		  +10538: C7 C1 CC 03   line#1164 GETTABLE 7 7 -52      <173>   R7 = R7["SelectWeapon"]                         -- It's Const#52
		  +1053C: A4 41 00 01   line#1164 CALL 6 2 1            <174>   R6(R7)
		  +10540: 86 01 4D 00   line#1165 GETTABUP 6 0 -53      <175>   R6 = Upv#1@_ENV["AutoHaki"]                     -- It's Const#53
		  +10544: A4 41 80 00   line#1165 CALL 6 1 1            <176>   R6()
		  +10548: 87 01 C7 02   line#1166 GETTABLE 6 5 -29      <177>   R6 = R5@v["HumanoidRootPart"]                   -- It's Const#29
		  +1054C: 87 81 4D 03   line#1166 GETTABLE 6 6 -55      <178>   R6 = R6["CFrame"]                               -- It's Const#55
		  +10550: 08 80 81 9A   line#1166 SETTABUP 0 -54 6      <179>   Upv#1@_ENV["PosMon"] = R6                       -- It's Const#54
		  +10554: 86 01 46 00   line#1167 GETTABUP 6 0 -25      <180>   R6 = Upv#1@_ENV["TP1"]                          -- It's Const#25
		  +10558: C7 01 C7 02   line#1167 GETTABLE 7 5 -29      <181>   R7 = R5@v["HumanoidRootPart"]                   -- It's Const#29
		  +1055C: C7 81 CD 03   line#1167 GETTABLE 7 7 -55      <182>   R7 = R7["CFrame"]                               -- It's Const#55
		  +10560: 06 82 4D 00   line#1167 GETTABUP 8 0 -55      <183>   R8 = Upv#1@_ENV["CFrame"]                       -- It's Const#55
		  +10564: 07 C2 4D 04   line#1167 GETTABLE 8 8 -56      <184>   R8 = R8["new"]                                  -- It's Const#56
		  +10568: 41 02 0E 00   line#1167 LOADK 9 -57           <185>   R9 = 2                                          -- It's Const#57
		  +1056C: 81 42 0E 00   line#1167 LOADK 10 -58          <186>   R10 = 15                                        -- It's Const#58
		  +10570: C1 82 07 00   line#1167 LOADK 11 -31          <187>   R11 = 3                                         -- It's Const#31
		  +10574: 24 82 00 02   line#1167 CALL 8 4 2            <188>   R8 = R8(R9, R10, R11)
		  +10578: CF 01 82 03   line#1167 MUL 7 7 8             <189>   R7 = R7 * R8
		  +1057C: A4 41 00 01   line#1167 CALL 6 2 1            <190>   R6(R7)
		  +10580: 87 01 C7 02   line#1168 GETTABLE 6 5 -29      <191>   R6 = R5@v["HumanoidRootPart"]                   -- It's Const#29
		  +10584: 8A C1 43 9D   line#1168 SETTABLE 6 -59 -16    <192>   R6["CanCollide"] = false                        -- It's Const#59, Const#16
		  +10588: 87 41 CB 02   line#1169 GETTABLE 6 5 -46      <193>   R6 = R5@v["Humanoid"]                           -- It's Const#46
		  +1058C: 8A C1 CB 9D   line#1169 SETTABLE 6 -60 -48    <194>   R6["WalkSpeed"] = 0                             -- It's Const#60, Const#48
		  +10590: 87 01 CF 02   line#1170 GETTABLE 6 5 -61      <195>   R6 = R5@v["Head"]                               -- It's Const#61
		  +10594: 8A C1 43 9D   line#1170 SETTABLE 6 -59 -16    <196>   R6["CanCollide"] = false                        -- It's Const#59, Const#16
		  +10598: 87 01 C7 02   line#1171 GETTABLE 6 5 -29      <197>   R6 = R5@v["HumanoidRootPart"]                   -- It's Const#29
		  +1059C: C6 81 4F 00   line#1171 GETTABUP 7 0 -63      <198>   R7 = Upv#1@_ENV["Vector3"]                      -- It's Const#63
		  +105A0: C7 C1 CD 03   line#1171 GETTABLE 7 7 -56      <199>   R7 = R7["new"]                                  -- It's Const#56
		  +105A4: 01 C2 0F 00   line#1171 LOADK 8 -64           <200>   R8 = 70                                         -- It's Const#64
		  +105A8: 41 C2 0F 00   line#1171 LOADK 9 -64           <201>   R9 = 70                                         -- It's Const#64
		  +105AC: 81 C2 0F 00   line#1171 LOADK 10 -64          <202>   R10 = 70                                        -- It's Const#64
		  +105B0: E4 81 00 02   line#1171 CALL 7 4 2            <203>   R7 = R7(R8, R9, R10)
		  +105B4: 8A C1 81 9E   line#1171 SETTABLE 6 -62 7      <204>   R6["Size"] = R7                                 -- It's Const#62
		  +105B8: 08 80 49 87   line#1172 SETTABUP 0 -15 -39    <205>   Upv#1@_ENV["StartMagnet"] = true                -- It's Const#15, Const#39
		  +105BC: 86 01 40 00   line#1173 GETTABUP 6 0 -1       <206>   R6 = Upv#1@_ENV["game"]                         -- It's Const#1
		  +105C0: 8C 41 40 03   line#1173 SELF 6 6 -2           <207>   R7 = R6;  R6 = R6["GetService"]                 -- It's Const#2   -- prepare for R6:GetService()
		  +105C4: 01 02 10 00   line#1173 LOADK 8 -65           <208>   R8 = "VirtualUser"                              -- It's Const#65
		  +105C8: A4 81 80 01   line#1173 CALL 6 3 2            <209>   R6 = R6(R7, R8)
		  +105CC: 8C 41 50 03   line#1173 SELF 6 6 -66          <210>   R7 = R6;  R6 = R6["CaptureController"]          -- It's Const#66   -- prepare for R6:CaptureController()
		  +105D0: A4 41 00 01   line#1173 CALL 6 2 1            <211>   R6(R7)
		  +105D4: 86 01 40 00   line#1174 GETTABUP 6 0 -1       <212>   R6 = Upv#1@_ENV["game"]                         -- It's Const#1
		  +105D8: 8C 41 40 03   line#1174 SELF 6 6 -2           <213>   R7 = R6;  R6 = R6["GetService"]                 -- It's Const#2   -- prepare for R6:GetService()
		  +105DC: 01 02 10 00   line#1174 LOADK 8 -65           <214>   R8 = "VirtualUser"                              -- It's Const#65
		  +105E0: A4 81 80 01   line#1174 CALL 6 3 2            <215>   R6 = R6(R7, R8)
		  +105E4: 8C 81 50 03   line#1174 SELF 6 6 -67          <216>   R7 = R6;  R6 = R6["Button1Down"]                -- It's Const#67   -- prepare for R6:Button1Down()
		  +105E8: 06 C2 50 00   line#1174 GETTABUP 8 0 -68      <217>   R8 = Upv#1@_ENV["Vector2"]                      -- It's Const#68
		  +105EC: 07 C2 4D 04   line#1174 GETTABLE 8 8 -56      <218>   R8 = R8["new"]                                  -- It's Const#56
		  +105F0: 41 02 11 00   line#1174 LOADK 9 -69           <219>   R9 = 1280                                       -- It's Const#69
		  +105F4: 81 42 11 00   line#1174 LOADK 10 -70          <220>   R10 = 672                                       -- It's Const#70
		  +105F8: 24 02 80 01   line#1174 CALL 8 3 0            <221>   R8,.. = R8(R9, R10)
		  +105FC: A4 41 00 00   line#1174 CALL 6 0 1            <222>   R6(R7,..)
		  +10600: 86 C1 47 00   line#1175 GETTABUP 6 0 -32      <223>   R6 = Upv#1@_ENV["_G"]                           -- It's Const#32
		  +10604: 87 01 48 03   line#1175 GETTABLE 6 6 -33      <224>   R6 = R6["AutoFarm"]                             -- It's Const#33
		  +10608: A2 01 00 00   line#1175 TEST 6 0              <225>   if R6 then GOTO <227>
		  +1060C: 1E 00 07 80   line#1175 JMP 0 29              <226>   GOTO <256>
		  +10610: 87 41 CB 02   line#1175 GETTABLE 6 5 -46      <227>   R6 = R5@v["Humanoid"]                           -- It's Const#46
		  +10614: 87 81 4B 03   line#1175 GETTABLE 6 6 -47      <228>   R6 = R6["Health"]                               -- It's Const#47
		  +10618: 61 C0 4B 03   line#1175 LE 1 6 -48            <229>   if not (R6 <= 0) then GOTO <231>                -- It's Const#48
		  +1061C: 1E 00 06 80   line#1175 JMP 0 25              <230>   GOTO <256>
		  +10620: 87 81 D1 02   line#1175 GETTABLE 6 5 -71      <231>   R6 = R5@v["Parent"]                             -- It's Const#71
		  +10624: A2 01 00 00   line#1175 TEST 6 0              <232>   if R6 then GOTO <234>
		  +10628: 1E 40 05 80   line#1175 JMP 0 22              <233>   GOTO <256>
		  +1062C: 86 01 40 00   line#1175 GETTABUP 6 0 -1       <234>   R6 = Upv#1@_ENV["game"]                         -- It's Const#1
		  +10630: 8C 41 40 03   line#1175 SELF 6 6 -2           <235>   R7 = R6;  R6 = R6["GetService"]                 -- It's Const#2   -- prepare for R6:GetService()
		  +10634: 01 82 00 00   line#1175 LOADK 8 -3            <236>   R8 = "Players"                                  -- It's Const#3
		  +10638: A4 81 80 01   line#1175 CALL 6 3 2            <237>   R6 = R6(R7, R8)
		  +1063C: 87 C1 40 03   line#1175 GETTABLE 6 6 -4       <238>   R6 = R6["LocalPlayer"]                          -- It's Const#4
		  +10640: 87 01 41 03   line#1175 GETTABLE 6 6 -5       <239>   R6 = R6["PlayerGui"]                            -- It's Const#5
		  +10644: 87 41 41 03   line#1175 GETTABLE 6 6 -6       <240>   R6 = R6["Main"]                                 -- It's Const#6
		  +10648: 87 81 41 03   line#1175 GETTABLE 6 6 -7       <241>   R6 = R6["Quest"]                                -- It's Const#7
		  +1064C: 87 41 45 03   line#1175 GETTABLE 6 6 -22      <242>   R6 = R6["Visible"]                              -- It's Const#22
		  +10650: 1F C0 43 03   line#1175 EQ 0 6 -16            <243>   if R6 == false then GOTO <245>                  -- It's Const#16
		  +10654: 1E 80 EC 7F   line#1175 JMP 0 -77             <244>   GOTO <168>
		  +10658: 1E 40 02 80   line#1175 JMP 0 10              <245>   GOTO <256>
		  +1065C: 08 C0 43 87   line#1177 SETTABUP 0 -15 -16    <246>   Upv#1@_ENV["StartMagnet"] = false               -- It's Const#15, Const#16
		  +10660: 86 01 40 00   line#1178 GETTABUP 6 0 -1       <247>   R6 = Upv#1@_ENV["game"]                         -- It's Const#1
		  +10664: 8C 41 40 03   line#1178 SELF 6 6 -2           <248>   R7 = R6;  R6 = R6["GetService"]                 -- It's Const#2   -- prepare for R6:GetService()
		  +10668: 01 02 04 00   line#1178 LOADK 8 -17           <249>   R8 = "ReplicatedStorage"                        -- It's Const#17
		  +1066C: A4 81 80 01   line#1178 CALL 6 3 2            <250>   R6 = R6(R7, R8)
		  +10670: 87 41 44 03   line#1178 GETTABLE 6 6 -18      <251>   R6 = R6["Remotes"]                              -- It's Const#18
		  +10674: 87 81 44 03   line#1178 GETTABLE 6 6 -19      <252>   R6 = R6["CommF_"]                               -- It's Const#19
		  +10678: 8C C1 44 03   line#1178 SELF 6 6 -20          <253>   R7 = R6;  R6 = R6["InvokeServer"]               -- It's Const#20   -- prepare for R6:InvokeServer()
		  +1067C: 01 02 05 00   line#1178 LOADK 8 -21           <254>   R8 = "AbandonQuest"                             -- It's Const#21
		  +10680: A4 41 80 01   line#1178 CALL 6 3 1            <255>   R6(R7, R8)
		  +10684: 69 80 00 00   line#1159 TFORCALL 1 2          <256>   R4, R5 = R1(R2, R3)
		  +10688: EA 40 E0 7F   line#1159 TFORLOOP 3 -126       <257>   if R4 ~= nil then { R3 = R4;  GOTO <132> }      -- end of loop
		  +1068C: 1E 40 0F 80   line#1182 JMP 0 62              <258>   GOTO <321>
		  +10690: 08 C0 43 87   line#1184 SETTABUP 0 -15 -16    <259>   Upv#1@_ENV["StartMagnet"] = false               -- It's Const#15, Const#16
		  +10694: 46 00 40 00   line#1185 GETTABUP 1 0 -1       <260>   R1 = Upv#1@_ENV["game"]                         -- It's Const#1
		  +10698: 4C 40 C0 00   line#1185 SELF 1 1 -2           <261>   R2 = R1;  R1 = R1["GetService"]                 -- It's Const#2   -- prepare for R1:GetService()
		  +1069C: C1 00 04 00   line#1185 LOADK 3 -17           <262>   R3 = "ReplicatedStorage"                        -- It's Const#17
		  +106A0: 64 80 80 01   line#1185 CALL 1 3 2            <263>   R1 = R1(R2, R3)
		  +106A4: 4C 40 CA 00   line#1185 SELF 1 1 -42          <264>   R2 = R1;  R1 = R1["FindFirstChild"]             -- It's Const#42   -- prepare for R1:FindFirstChild()
		  +106A8: C6 80 4A 00   line#1185 GETTABUP 3 0 -43      <265>   R3 = Upv#1@_ENV["Mon"]                          -- It's Const#43
		  +106AC: 64 80 80 01   line#1185 CALL 1 3 2            <266>   R1 = R1(R2, R3)
		  +106B0: 62 00 00 00   line#1185 TEST 1 0              <267>   if R1 then GOTO <269>
		  +106B4: 1E 80 04 80   line#1185 JMP 0 19              <268>   GOTO <288>
		  +106B8: 46 00 46 00   line#1186 GETTABUP 1 0 -25      <269>   R1 = Upv#1@_ENV["TP1"]                          -- It's Const#25
		  +106BC: 86 00 40 00   line#1186 GETTABUP 2 0 -1       <270>   R2 = Upv#1@_ENV["game"]                         -- It's Const#1
		  +106C0: 8C 40 40 01   line#1186 SELF 2 2 -2           <271>   R3 = R2;  R2 = R2["GetService"]                 -- It's Const#2   -- prepare for R2:GetService()
		  +106C4: 01 01 04 00   line#1186 LOADK 4 -17           <272>   R4 = "ReplicatedStorage"                        -- It's Const#17
		  +106C8: A4 80 80 01   line#1186 CALL 2 3 2            <273>   R2 = R2(R3, R4)
		  +106CC: 8C 40 4A 01   line#1186 SELF 2 2 -42          <274>   R3 = R2;  R2 = R2["FindFirstChild"]             -- It's Const#42   -- prepare for R2:FindFirstChild()
		  +106D0: 06 81 4A 00   line#1186 GETTABUP 4 0 -43      <275>   R4 = Upv#1@_ENV["Mon"]                          -- It's Const#43
		  +106D4: A4 80 80 01   line#1186 CALL 2 3 2            <276>   R2 = R2(R3, R4)
		  +106D8: 87 00 47 01   line#1186 GETTABLE 2 2 -29      <277>   R2 = R2["HumanoidRootPart"]                     -- It's Const#29
		  +106DC: 87 80 4D 01   line#1186 GETTABLE 2 2 -55      <278>   R2 = R2["CFrame"]                               -- It's Const#55
		  +106E0: C6 80 4D 00   line#1186 GETTABUP 3 0 -55      <279>   R3 = Upv#1@_ENV["CFrame"]                       -- It's Const#55
		  +106E4: C7 C0 CD 01   line#1186 GETTABLE 3 3 -56      <280>   R3 = R3["new"]                                  -- It's Const#56
		  +106E8: 01 41 0E 00   line#1186 LOADK 4 -58           <281>   R4 = 15                                         -- It's Const#58
		  +106EC: 41 C1 11 00   line#1186 LOADK 5 -72           <282>   R5 = 10                                         -- It's Const#72
		  +106F0: 81 01 0E 00   line#1186 LOADK 6 -57           <283>   R6 = 2                                          -- It's Const#57
		  +106F4: E4 80 00 02   line#1186 CALL 3 4 2            <284>   R3 = R3(R4, R5, R6)
		  +106F8: 8F C0 00 01   line#1186 MUL 2 2 3             <285>   R2 = R2 * R3
		  +106FC: 64 40 00 01   line#1186 CALL 1 2 1            <286>   R1(R2)
		  +10700: 1E 00 08 80   line#1186 JMP 0 33              <287>   GOTO <321>
		  +10704: 46 40 46 00   line#1188 GETTABUP 1 0 -26      <288>   R1 = Upv#1@_ENV["CFrameQuest"]                  -- It's Const#26
		  +10708: 47 80 C6 00   line#1188 GETTABLE 1 1 -27      <289>   R1 = R1["Position"]                             -- It's Const#27
		  +1070C: 86 00 40 00   line#1188 GETTABUP 2 0 -1       <290>   R2 = Upv#1@_ENV["game"]                         -- It's Const#1
		  +10710: 87 80 40 01   line#1188 GETTABLE 2 2 -3       <291>   R2 = R2["Players"]                              -- It's Const#3
		  +10714: 87 C0 40 01   line#1188 GETTABLE 2 2 -4       <292>   R2 = R2["LocalPlayer"]                          -- It's Const#4
		  +10718: 87 C0 46 01   line#1188 GETTABLE 2 2 -28      <293>   R2 = R2["Character"]                            -- It's Const#28
		  +1071C: 87 00 47 01   line#1188 GETTABLE 2 2 -29      <294>   R2 = R2["HumanoidRootPart"]                     -- It's Const#29
		  +10720: 87 80 46 01   line#1188 GETTABLE 2 2 -27      <295>   R2 = R2["Position"]                             -- It's Const#27
		  +10724: 4E 80 80 00   line#1188 SUB 1 1 2             <296>   R1 = R1 - R2
		  +10728: 47 40 C7 00   line#1188 GETTABLE 1 1 -30      <297>   R1 = R1["Magnitude"]                            -- It's Const#30
		  +1072C: 21 00 D2 00   line#1188 LE 0 1 -73            <298>   if R1 <= 1 then GOTO <300>                      -- It's Const#73
		  +10730: 1E 00 05 80   line#1188 JMP 0 21              <299>   GOTO <321>
		  +10734: 46 40 4D 00   line#1189 GETTABUP 1 0 -54      <300>   R1 = Upv#1@_ENV["PosMon"]                       -- It's Const#54
		  +10738: 5F 40 D2 00   line#1189 EQ 1 1 -74            <301>   if R1 ~= nil then GOTO <303>                    -- It's Const#74
		  +1073C: 1E 80 02 80   line#1189 JMP 0 11              <302>   GOTO <314>
		  +10740: 46 00 46 00   line#1190 GETTABUP 1 0 -25      <303>   R1 = Upv#1@_ENV["TP1"]                          -- It's Const#25
		  +10744: 86 40 4D 00   line#1190 GETTABUP 2 0 -54      <304>   R2 = Upv#1@_ENV["PosMon"]                       -- It's Const#54
		  +10748: C6 80 4D 00   line#1190 GETTABUP 3 0 -55      <305>   R3 = Upv#1@_ENV["CFrame"]                       -- It's Const#55
		  +1074C: C7 C0 CD 01   line#1190 GETTABLE 3 3 -56      <306>   R3 = R3["new"]                                  -- It's Const#56
		  +10750: 01 41 0E 00   line#1190 LOADK 4 -58           <307>   R4 = 15                                         -- It's Const#58
		  +10754: 41 C1 11 00   line#1190 LOADK 5 -72           <308>   R5 = 10                                         -- It's Const#72
		  +10758: 81 01 0E 00   line#1190 LOADK 6 -57           <309>   R6 = 2                                          -- It's Const#57
		  +1075C: E4 80 00 02   line#1190 CALL 3 4 2            <310>   R3 = R3(R4, R5, R6)
		  +10760: 8F C0 00 01   line#1190 MUL 2 2 3             <311>   R2 = R2 * R3
		  +10764: 64 40 00 01   line#1190 CALL 1 2 1            <312>   R1(R2)
		  +10768: 1E 80 01 80   line#1190 JMP 0 7               <313>   GOTO <321>
		  +1076C: 46 80 52 00   line#1192 GETTABUP 1 0 -75      <314>   R1 = Upv#1@_ENV["OldPos"]                       -- It's Const#75
		  +10770: 5F 40 D2 00   line#1192 EQ 1 1 -74            <315>   if R1 ~= nil then GOTO <317>                    -- It's Const#74
		  +10774: 1E C0 00 80   line#1192 JMP 0 4               <316>   GOTO <321>
		  +10778: 46 00 46 00   line#1193 GETTABUP 1 0 -25      <317>   R1 = Upv#1@_ENV["TP1"]                          -- It's Const#25
		  +1077C: 86 80 52 00   line#1193 GETTABUP 2 0 -75      <318>   R2 = Upv#1@_ENV["OldPos"]                       -- It's Const#75
		  +10780: 87 80 46 01   line#1193 GETTABLE 2 2 -27      <319>   R2 = R2["Position"]                             -- It's Const#27
		  +10784: 64 40 00 01   line#1193 CALL 1 2 1            <320>   R1(R2)
		  +10788: 26 00 80 00   line#1200 RETURN 0 1            <321>   RETURN
		Functions: 0

	************ Function#30   (full path: main.30)
	Source line#: 1204..1235
	Parameters: 0
	Is vararg: no
	VM registers needed: 2
	Constants: 3
	  +11037:Size=4: 74 61 73 6B                    Const#1   string    "task"
	  +1103D:Size=4: 77 61 69 74                    Const#2   string    "wait"
	  +11043:Size=5: 70 63 61 6C 6C                 Const#3   string    "pcall"
	Upvalues: 1
	  Upv#1 is parent function's Upv#1              name: _ENV
	Instructions: 10
	  +11009: 06 00 40 00   line#1205 GETTABUP 0 0 -1         <1>   R0 = Upv#1@_ENV["task"]                         -- It's Const#1
	  +1100D: 07 40 40 00   line#1205 GETTABLE 0 0 -2         <2>   R0 = R0["wait"]                                 -- It's Const#2
	  +11011: 24 80 80 00   line#1205 CALL 0 1 2              <3>   R0 = R0()
	  +11015: 22 00 00 00   line#1205 TEST 0 0                <4>   if R0 then GOTO <6>
	  +11019: 1E C0 00 80   line#1205 JMP 0 4                 <5>   GOTO <10>
	  +1101D: 06 80 40 00   line#1206 GETTABUP 0 0 -3         <6>   R0 = Upv#1@_ENV["pcall"]                        -- It's Const#3
	  +11021: 6C 00 00 00   line#1233 CLOSURE 1 0             <7>   R1 = Function#1
	  +11025: 24 40 00 01   line#1206 CALL 0 2 1              <8>   R0(R1)
	  +11029: 1E 80 FD 7F   line#1233 JMP 0 -9                <9>   GOTO <1>
	  +1102D: 26 00 80 00   line#1235 RETURN 0 1             <10>   RETURN
	Functions: 1

		************ Function#1   (full path: main.30.1)
		Source line#: 1206..1233
		Parameters: 0
		Is vararg: no
		VM registers needed: 10
		Constants: 46
		  +11358:Size=2: 5F 47                          Const#1   string    "_G"
		  +1135C:Size=C: 42 72 69 6E 67 4D 6F 6E 7...   Const#2   string    "BringMonster"
		  +1136A:Size=A: 43 68 65 63 6B 51 75 65 7...   Const#3   string    "CheckQuest"
		  +11376:Size=5: 70 61 69 72 73                 Const#4   string    "pairs"
		  +1137D:Size=4: 67 61 6D 65                    Const#5   string    "game"
		  +11383:Size=A: 47 65 74 53 65 72 76 69 6...   Const#6   string    "GetService"
		  +1138F:Size=9: 57 6F 72 6B 73 70 61 63 65     Const#7   string    "Workspace"
		  +1139A:Size=7: 45 6E 65 6D 69 65 73           Const#8   string    "Enemies"
		  +113A3:Size=B: 47 65 74 43 68 69 6C 64 7...   Const#9   string    "GetChildren"
		  +113B0:Size=8: 41 75 74 6F 46 61 72 6D        Const#10  string    "AutoFarm"
		  +113BA:Size=B: 53 74 61 72 74 4D 61 67 6...   Const#11  string    "StartMagnet"
		  +113C7:Size=4: 4E 61 6D 65                    Const#12  string    "Name"
		  +113CD:Size=3: 4D 6F 6E                       Const#13  string    "Mon"
		  +113D2:Size=17: 46 61 63 74 6F 72 79 20 ...   Const#14  string    "Factory Staff [Lv. 800]"
		  +113EB:Size=F: 4D 6F 6E 6B 65 79 20 5B 4...   Const#15  string    "Monkey [Lv. 14]"
		  +113FC:Size=1E: 44 72 61 67 6F 6E 20 43 ...   Const#16  string    "Dragon Crew Warrior [Lv. 1575]"
		  +1141C:Size=1D: 44 72 61 67 6F 6E 20 43 ...   Const#17  string    "Dragon Crew Archer [Lv. 1600]"
		  +1143B:Size=E: 46 69 6E 64 46 69 72 73 7...   Const#18  string    "FindFirstChild"
		  +1144B:Size=8: 48 75 6D 61 6E 6F 69 64        Const#19  string    "Humanoid"
		  +11455:Size=10: 48 75 6D 61 6E 6F 69 64 ...   Const#20  string    "HumanoidRootPart"
		  +11467:Size=6: 48 65 61 6C 74 68              Const#21  string    "Health"
		  +1146E:Size=4: 00 00 00 00                    Const#22  integer   0
		  +11474:Size=8: 50 6F 73 69 74 69 6F 6E        Const#23  string    "Position"
		  +1147E:Size=7: 50 6C 61 79 65 72 73           Const#24  string    "Players"
		  +11487:Size=B: 4C 6F 63 61 6C 50 6C 61 7...   Const#25  string    "LocalPlayer"
		  +11494:Size=9: 43 68 61 72 61 63 74 65 72     Const#26  string    "Character"
		  +1149F:Size=9: 4D 61 67 6E 69 74 75 64 65     Const#27  string    "Magnitude"
		  +114A9:Size=4: DC 00 00 00                    Const#28  integer   220
		  +114AF:Size=4: 53 69 7A 65                    Const#29  string    "Size"
		  +114B5:Size=7: 56 65 63 74 6F 72 33           Const#30  string    "Vector3"
		  +114BE:Size=3: 6E 65 77                       Const#31  string    "new"
		  +114C2:Size=4: 46 00 00 00                    Const#32  integer   70
		  +114C8:Size=6: 43 46 72 61 6D 65              Const#33  string    "CFrame"
		  +114D0:Size=6: 50 6F 73 4D 6F 6E              Const#34  string    "PosMon"
		  +114D8:Size=B: 43 68 61 6E 67 65 53 74 6...   Const#35  string    "ChangeState"
		  +114E4:Size=4: 0E 00 00 00                    Const#36  integer   14
		  +114EA:Size=A: 43 61 6E 43 6F 6C 6C 69 6...   Const#37  string    "CanCollide"
		  +114F5:Size=1: 00                             Const#38  boolean   false
		  +114F8:Size=4: 48 65 61 64                    Const#39  string    "Head"
		  +114FE:Size=8: 41 6E 69 6D 61 74 6F 72        Const#40  string    "Animator"
		  +11508:Size=7: 44 65 73 74 72 6F 79           Const#41  string    "Destroy"
		  +11511:Size=11: 73 65 74 68 69 64 64 65 ...   Const#42  string    "sethiddenproperty"
		  +11524:Size=10: 53 69 6D 75 6C 61 74 69 ...   Const#43  string    "SimulationRadius"
		  +11536:Size=4: 6D 61 74 68                    Const#44  string    "math"
		  +1153C:Size=4: 68 75 67 65                    Const#45  string    "huge"
		  +11541:Size=4: 13 01 00 00                    Const#46  integer   275
		Upvalues: 1
		  Upv#1 is parent function's Upv#1              name: _ENV
		Locals: 5
		  Local#1   R0   def:<15>   scope:<16..187>     name: (for generator)
		  Local#2   R1   def:<15>   scope:<16..187>     name: (for state)
		  Local#3   R2   def:<15>   scope:<16..187>     name: (for control)
		  Local#4   R3   def:<16>   scope:<17..185>     name: i
		  Local#5   R4   def:<16>   scope:<17..185>     name: v
		Instructions: 188
		  +11062: 06 00 40 00   line#1207 GETTABUP 0 0 -1         <1>   R0 = Upv#1@_ENV["_G"]                           -- It's Const#1
		  +11066: 07 40 40 00   line#1207 GETTABLE 0 0 -2         <2>   R0 = R0["BringMonster"]                         -- It's Const#2
		  +1106A: 22 00 00 00   line#1207 TEST 0 0                <3>   if R0 then GOTO <5>
		  +1106E: 1E 80 2D 80   line#1207 JMP 0 183               <4>   GOTO <188>
		  +11072: 06 80 40 00   line#1208 GETTABUP 0 0 -3         <5>   R0 = Upv#1@_ENV["CheckQuest"]                   -- It's Const#3
		  +11076: 24 40 80 00   line#1208 CALL 0 1 1              <6>   R0()
		  +1107A: 06 C0 40 00   line#1209 GETTABUP 0 0 -4         <7>   R0 = Upv#1@_ENV["pairs"]                        -- It's Const#4
		  +1107E: 46 00 41 00   line#1209 GETTABUP 1 0 -5         <8>   R1 = Upv#1@_ENV["game"]                         -- It's Const#5
		  +11082: 4C 40 C1 00   line#1209 SELF 1 1 -6             <9>   R2 = R1;  R1 = R1["GetService"]                 -- It's Const#6   -- prepare for R1:GetService()
		  +11086: C1 80 01 00   line#1209 LOADK 3 -7             <10>   R3 = "Workspace"                                -- It's Const#7
		  +1108A: 64 80 80 01   line#1209 CALL 1 3 2             <11>   R1 = R1(R2, R3)
		  +1108E: 47 C0 C1 00   line#1209 GETTABLE 1 1 -8        <12>   R1 = R1["Enemies"]                              -- It's Const#8
		  +11092: 4C 00 C2 00   line#1209 SELF 1 1 -9            <13>   R2 = R1;  R1 = R1["GetChildren"]                -- It's Const#9   -- prepare for R1:GetChildren()
		  +11096: 64 00 00 01   line#1209 CALL 1 2 0             <14>   R1,.. = R1(R2)
		  +1109A: 24 00 01 00   line#1209 CALL 0 0 4             <15>   R0, R1, R2 = R0(R1,..)
		  +1109E: 1E 00 2A 80   line#1209 JMP 0 169              <16>   GOTO <186>                                      -- for R3@i, R4@v in R0, R1, R2 do
		  +110A2: 46 01 40 00   line#1210 GETTABUP 5 0 -1        <17>   R5 = Upv#1@_ENV["_G"]                           -- It's Const#1
		  +110A6: 47 41 C2 02   line#1210 GETTABLE 5 5 -10       <18>   R5 = R5["AutoFarm"]                             -- It's Const#10
		  +110AA: 62 01 00 00   line#1210 TEST 5 0               <19>   if R5 then GOTO <21>
		  +110AE: 1E 80 15 80   line#1210 JMP 0 87               <20>   GOTO <108>
		  +110B2: 46 81 42 00   line#1210 GETTABUP 5 0 -11       <21>   R5 = Upv#1@_ENV["StartMagnet"]                  -- It's Const#11
		  +110B6: 62 01 00 00   line#1210 TEST 5 0               <22>   if R5 then GOTO <24>
		  +110BA: 1E C0 14 80   line#1210 JMP 0 84               <23>   GOTO <108>
		  +110BE: 47 C1 42 02   line#1210 GETTABLE 5 4 -12       <24>   R5 = R4@v["Name"]                               -- It's Const#12
		  +110C2: 86 01 43 00   line#1210 GETTABUP 6 0 -13       <25>   R6 = Upv#1@_ENV["Mon"]                          -- It's Const#13
		  +110C6: 1F 80 81 02   line#1210 EQ 0 5 6               <26>   if R5 == R6 then GOTO <28>
		  +110CA: 1E C0 13 80   line#1210 JMP 0 80               <27>   GOTO <108>
		  +110CE: 46 01 43 00   line#1210 GETTABUP 5 0 -13       <28>   R5 = Upv#1@_ENV["Mon"]                          -- It's Const#13
		  +110D2: 5F 40 C3 02   line#1210 EQ 1 5 -14             <29>   if R5 ~= "Factory Staff [Lv. 800]" then GOTO <31>   -- It's Const#14
		  +110D6: 1E 00 02 80   line#1210 JMP 0 9                <30>   GOTO <40>
		  +110DA: 46 01 43 00   line#1210 GETTABUP 5 0 -13       <31>   R5 = Upv#1@_ENV["Mon"]                          -- It's Const#13
		  +110DE: 5F 80 C3 02   line#1210 EQ 1 5 -15             <32>   if R5 ~= "Monkey [Lv. 14]" then GOTO <34>       -- It's Const#15
		  +110E2: 1E 40 01 80   line#1210 JMP 0 6                <33>   GOTO <40>
		  +110E6: 46 01 43 00   line#1210 GETTABUP 5 0 -13       <34>   R5 = Upv#1@_ENV["Mon"]                          -- It's Const#13
		  +110EA: 5F C0 C3 02   line#1210 EQ 1 5 -16             <35>   if R5 ~= "Dragon Crew Warrior [Lv. 1575]" then GOTO <37>   -- It's Const#16
		  +110EE: 1E 80 00 80   line#1210 JMP 0 3                <36>   GOTO <40>
		  +110F2: 46 01 43 00   line#1210 GETTABUP 5 0 -13       <37>   R5 = Upv#1@_ENV["Mon"]                          -- It's Const#13
		  +110F6: 1F 00 C4 02   line#1210 EQ 0 5 -17             <38>   if R5 == "Dragon Crew Archer [Lv. 1600]" then GOTO <40>   -- It's Const#17
		  +110FA: 1E C0 10 80   line#1210 JMP 0 68               <39>   GOTO <108>
		  +110FE: 4C 41 44 02   line#1210 SELF 5 4 -18           <40>   R6 = R4@v;  R5 = R4@v["FindFirstChild"]         -- It's Const#18   -- prepare for R4@v:FindFirstChild()
		  +11102: C1 81 04 00   line#1210 LOADK 7 -19            <41>   R7 = "Humanoid"                                 -- It's Const#19
		  +11106: 64 81 80 01   line#1210 CALL 5 3 2             <42>   R5 = R5(R6, R7)
		  +1110A: 62 01 00 00   line#1210 TEST 5 0               <43>   if R5 then GOTO <45>
		  +1110E: 1E 80 0F 80   line#1210 JMP 0 63               <44>   GOTO <108>
		  +11112: 4C 41 44 02   line#1210 SELF 5 4 -18           <45>   R6 = R4@v;  R5 = R4@v["FindFirstChild"]         -- It's Const#18   -- prepare for R4@v:FindFirstChild()
		  +11116: C1 C1 04 00   line#1210 LOADK 7 -20            <46>   R7 = "HumanoidRootPart"                         -- It's Const#20
		  +1111A: 64 81 80 01   line#1210 CALL 5 3 2             <47>   R5 = R5(R6, R7)
		  +1111E: 62 01 00 00   line#1210 TEST 5 0               <48>   if R5 then GOTO <50>
		  +11122: 1E 40 0E 80   line#1210 JMP 0 58               <49>   GOTO <108>
		  +11126: 47 81 44 02   line#1210 GETTABLE 5 4 -19       <50>   R5 = R4@v["Humanoid"]                           -- It's Const#19
		  +1112A: 47 01 C5 02   line#1210 GETTABLE 5 5 -21       <51>   R5 = R5["Health"]                               -- It's Const#21
		  +1112E: 20 40 81 8A   line#1210 LT 0 -22 5             <52>   if R5 > 0 then GOTO <54>                        -- It's Const#22
		  +11132: 1E 40 0D 80   line#1210 JMP 0 54               <53>   GOTO <108>
		  +11136: 47 C1 44 02   line#1210 GETTABLE 5 4 -20       <54>   R5 = R4@v["HumanoidRootPart"]                   -- It's Const#20
		  +1113A: 47 81 C5 02   line#1210 GETTABLE 5 5 -23       <55>   R5 = R5["Position"]                             -- It's Const#23
		  +1113E: 86 01 41 00   line#1210 GETTABUP 6 0 -5        <56>   R6 = Upv#1@_ENV["game"]                         -- It's Const#5
		  +11142: 8C 41 41 03   line#1210 SELF 6 6 -6            <57>   R7 = R6;  R6 = R6["GetService"]                 -- It's Const#6   -- prepare for R6:GetService()
		  +11146: 01 C2 05 00   line#1210 LOADK 8 -24            <58>   R8 = "Players"                                  -- It's Const#24
		  +1114A: A4 81 80 01   line#1210 CALL 6 3 2             <59>   R6 = R6(R7, R8)
		  +1114E: 87 01 46 03   line#1210 GETTABLE 6 6 -25       <60>   R6 = R6["LocalPlayer"]                          -- It's Const#25
		  +11152: 87 41 46 03   line#1210 GETTABLE 6 6 -26       <61>   R6 = R6["Character"]                            -- It's Const#26
		  +11156: 87 C1 44 03   line#1210 GETTABLE 6 6 -20       <62>   R6 = R6["HumanoidRootPart"]                     -- It's Const#20
		  +1115A: 87 81 45 03   line#1210 GETTABLE 6 6 -23       <63>   R6 = R6["Position"]                             -- It's Const#23
		  +1115E: 4E 81 81 02   line#1210 SUB 5 5 6              <64>   R5 = R5 - R6
		  +11162: 47 81 C6 02   line#1210 GETTABLE 5 5 -27       <65>   R5 = R5["Magnitude"]                            -- It's Const#27
		  +11166: 21 C0 C6 02   line#1210 LE 0 5 -28             <66>   if R5 <= 220 then GOTO <68>                     -- It's Const#28
		  +1116A: 1E C0 09 80   line#1210 JMP 0 40               <67>   GOTO <108>
		  +1116E: 47 C1 44 02   line#1211 GETTABLE 5 4 -20       <68>   R5 = R4@v["HumanoidRootPart"]                   -- It's Const#20
		  +11172: 86 41 47 00   line#1211 GETTABUP 6 0 -30       <69>   R6 = Upv#1@_ENV["Vector3"]                      -- It's Const#30
		  +11176: 87 81 47 03   line#1211 GETTABLE 6 6 -31       <70>   R6 = R6["new"]                                  -- It's Const#31
		  +1117A: C1 C1 07 00   line#1211 LOADK 7 -32            <71>   R7 = 70                                         -- It's Const#32
		  +1117E: 01 C2 07 00   line#1211 LOADK 8 -32            <72>   R8 = 70                                         -- It's Const#32
		  +11182: 41 C2 07 00   line#1211 LOADK 9 -32            <73>   R9 = 70                                         -- It's Const#32
		  +11186: A4 81 00 02   line#1211 CALL 6 4 2             <74>   R6 = R6(R7, R8, R9)
		  +1118A: 4A 81 01 8E   line#1211 SETTABLE 5 -29 6       <75>   R5["Size"] = R6                                 -- It's Const#29
		  +1118E: 47 C1 44 02   line#1212 GETTABLE 5 4 -20       <76>   R5 = R4@v["HumanoidRootPart"]                   -- It's Const#20
		  +11192: 86 41 48 00   line#1212 GETTABUP 6 0 -34       <77>   R6 = Upv#1@_ENV["PosMon"]                       -- It's Const#34
		  +11196: 4A 81 01 90   line#1212 SETTABLE 5 -33 6       <78>   R5["CFrame"] = R6                               -- It's Const#33
		  +1119A: 47 81 44 02   line#1213 GETTABLE 5 4 -19       <79>   R5 = R4@v["Humanoid"]                           -- It's Const#19
		  +1119E: 4C 81 C8 02   line#1213 SELF 5 5 -35           <80>   R6 = R5;  R5 = R5["ChangeState"]                -- It's Const#35   -- prepare for R5:ChangeState()
		  +111A2: C1 C1 08 00   line#1213 LOADK 7 -36            <81>   R7 = 14                                         -- It's Const#36
		  +111A6: 64 41 80 01   line#1213 CALL 5 3 1             <82>   R5(R6, R7)
		  +111AA: 47 C1 44 02   line#1214 GETTABLE 5 4 -20       <83>   R5 = R4@v["HumanoidRootPart"]                   -- It's Const#20
		  +111AE: 4A 41 49 92   line#1214 SETTABLE 5 -37 -38     <84>   R5["CanCollide"] = false                        -- It's Const#37, Const#38
		  +111B2: 47 81 49 02   line#1215 GETTABLE 5 4 -39       <85>   R5 = R4@v["Head"]                               -- It's Const#39
		  +111B6: 4A 41 49 92   line#1215 SETTABLE 5 -37 -38     <86>   R5["CanCollide"] = false                        -- It's Const#37, Const#38
		  +111BA: 47 81 44 02   line#1216 GETTABLE 5 4 -19       <87>   R5 = R4@v["Humanoid"]                           -- It's Const#19
		  +111BE: 4C 41 C4 02   line#1216 SELF 5 5 -18           <88>   R6 = R5;  R5 = R5["FindFirstChild"]             -- It's Const#18   -- prepare for R5:FindFirstChild()
		  +111C2: C1 C1 09 00   line#1216 LOADK 7 -40            <89>   R7 = "Animator"                                 -- It's Const#40
		  +111C6: 64 81 80 01   line#1216 CALL 5 3 2             <90>   R5 = R5(R6, R7)
		  +111CA: 62 01 00 00   line#1216 TEST 5 0               <91>   if R5 then GOTO <93>
		  +111CE: 1E C0 00 80   line#1216 JMP 0 4                <92>   GOTO <97>
		  +111D2: 47 81 44 02   line#1217 GETTABLE 5 4 -19       <93>   R5 = R4@v["Humanoid"]                           -- It's Const#19
		  +111D6: 47 C1 C9 02   line#1217 GETTABLE 5 5 -40       <94>   R5 = R5["Animator"]                             -- It's Const#40
		  +111DA: 4C 01 CA 02   line#1217 SELF 5 5 -41           <95>   R6 = R5;  R5 = R5["Destroy"]                    -- It's Const#41   -- prepare for R5:Destroy()
		  +111DE: 64 41 00 01   line#1217 CALL 5 2 1             <96>   R5(R6)
		  +111E2: 46 41 4A 00   line#1219 GETTABUP 5 0 -42       <97>   R5 = Upv#1@_ENV["sethiddenproperty"]            -- It's Const#42
		  +111E6: 86 01 41 00   line#1219 GETTABUP 6 0 -5        <98>   R6 = Upv#1@_ENV["game"]                         -- It's Const#5
		  +111EA: 8C 41 41 03   line#1219 SELF 6 6 -6            <99>   R7 = R6;  R6 = R6["GetService"]                 -- It's Const#6   -- prepare for R6:GetService()
		  +111EE: 01 C2 05 00   line#1219 LOADK 8 -24           <100>   R8 = "Players"                                  -- It's Const#24
		  +111F2: A4 81 80 01   line#1219 CALL 6 3 2            <101>   R6 = R6(R7, R8)
		  +111F6: 87 01 46 03   line#1219 GETTABLE 6 6 -25      <102>   R6 = R6["LocalPlayer"]                          -- It's Const#25
		  +111FA: C1 81 0A 00   line#1219 LOADK 7 -43           <103>   R7 = "SimulationRadius"                         -- It's Const#43
		  +111FE: 06 C2 4A 00   line#1219 GETTABUP 8 0 -44      <104>   R8 = Upv#1@_ENV["math"]                         -- It's Const#44
		  +11202: 07 02 4B 04   line#1219 GETTABLE 8 8 -45      <105>   R8 = R8["huge"]                                 -- It's Const#45
		  +11206: 64 41 00 02   line#1219 CALL 5 4 1            <106>   R5(R6, R7, R8)
		  +1120A: 1E 40 13 80   line#1219 JMP 0 78              <107>   GOTO <186>
		  +1120E: 46 01 40 00   line#1220 GETTABUP 5 0 -1       <108>   R5 = Upv#1@_ENV["_G"]                           -- It's Const#1
		  +11212: 47 41 C2 02   line#1220 GETTABLE 5 5 -10      <109>   R5 = R5["AutoFarm"]                             -- It's Const#10
		  +11216: 62 01 00 00   line#1220 TEST 5 0              <110>   if R5 then GOTO <112>
		  +1121A: 1E 40 12 80   line#1220 JMP 0 74              <111>   GOTO <186>
		  +1121E: 46 81 42 00   line#1220 GETTABUP 5 0 -11      <112>   R5 = Upv#1@_ENV["StartMagnet"]                  -- It's Const#11
		  +11222: 62 01 00 00   line#1220 TEST 5 0              <113>   if R5 then GOTO <115>
		  +11226: 1E 80 11 80   line#1220 JMP 0 71              <114>   GOTO <186>
		  +1122A: 47 C1 42 02   line#1220 GETTABLE 5 4 -12      <115>   R5 = R4@v["Name"]                               -- It's Const#12
		  +1122E: 86 01 43 00   line#1220 GETTABUP 6 0 -13      <116>   R6 = Upv#1@_ENV["Mon"]                          -- It's Const#13
		  +11232: 1F 80 81 02   line#1220 EQ 0 5 6              <117>   if R5 == R6 then GOTO <119>
		  +11236: 1E 80 10 80   line#1220 JMP 0 67              <118>   GOTO <186>
		  +1123A: 4C 41 44 02   line#1220 SELF 5 4 -18          <119>   R6 = R4@v;  R5 = R4@v["FindFirstChild"]         -- It's Const#18   -- prepare for R4@v:FindFirstChild()
		  +1123E: C1 81 04 00   line#1220 LOADK 7 -19           <120>   R7 = "Humanoid"                                 -- It's Const#19
		  +11242: 64 81 80 01   line#1220 CALL 5 3 2            <121>   R5 = R5(R6, R7)
		  +11246: 62 01 00 00   line#1220 TEST 5 0              <122>   if R5 then GOTO <124>
		  +1124A: 1E 40 0F 80   line#1220 JMP 0 62              <123>   GOTO <186>
		  +1124E: 4C 41 44 02   line#1220 SELF 5 4 -18          <124>   R6 = R4@v;  R5 = R4@v["FindFirstChild"]         -- It's Const#18   -- prepare for R4@v:FindFirstChild()
		  +11252: C1 C1 04 00   line#1220 LOADK 7 -20           <125>   R7 = "HumanoidRootPart"                         -- It's Const#20
		  +11256: 64 81 80 01   line#1220 CALL 5 3 2            <126>   R5 = R5(R6, R7)
		  +1125A: 62 01 00 00   line#1220 TEST 5 0              <127>   if R5 then GOTO <129>
		  +1125E: 1E 00 0E 80   line#1220 JMP 0 57              <128>   GOTO <186>
		  +11262: 47 81 44 02   line#1220 GETTABLE 5 4 -19      <129>   R5 = R4@v["Humanoid"]                           -- It's Const#19
		  +11266: 47 01 C5 02   line#1220 GETTABLE 5 5 -21      <130>   R5 = R5["Health"]                               -- It's Const#21
		  +1126A: 20 40 81 8A   line#1220 LT 0 -22 5            <131>   if R5 > 0 then GOTO <133>                       -- It's Const#22
		  +1126E: 1E 00 0D 80   line#1220 JMP 0 53              <132>   GOTO <186>
		  +11272: 47 C1 44 02   line#1220 GETTABLE 5 4 -20      <133>   R5 = R4@v["HumanoidRootPart"]                   -- It's Const#20
		  +11276: 47 81 C5 02   line#1220 GETTABLE 5 5 -23      <134>   R5 = R5["Position"]                             -- It's Const#23
		  +1127A: 86 01 41 00   line#1220 GETTABUP 6 0 -5       <135>   R6 = Upv#1@_ENV["game"]                         -- It's Const#5
		  +1127E: 8C 41 41 03   line#1220 SELF 6 6 -6           <136>   R7 = R6;  R6 = R6["GetService"]                 -- It's Const#6   -- prepare for R6:GetService()
		  +11282: 01 C2 05 00   line#1220 LOADK 8 -24           <137>   R8 = "Players"                                  -- It's Const#24
		  +11286: A4 81 80 01   line#1220 CALL 6 3 2            <138>   R6 = R6(R7, R8)
		  +1128A: 87 01 46 03   line#1220 GETTABLE 6 6 -25      <139>   R6 = R6["LocalPlayer"]                          -- It's Const#25
		  +1128E: 87 41 46 03   line#1220 GETTABLE 6 6 -26      <140>   R6 = R6["Character"]                            -- It's Const#26
		  +11292: 87 C1 44 03   line#1220 GETTABLE 6 6 -20      <141>   R6 = R6["HumanoidRootPart"]                     -- It's Const#20
		  +11296: 87 81 45 03   line#1220 GETTABLE 6 6 -23      <142>   R6 = R6["Position"]                             -- It's Const#23
		  +1129A: 4E 81 81 02   line#1220 SUB 5 5 6             <143>   R5 = R5 - R6
		  +1129E: 47 81 C6 02   line#1220 GETTABLE 5 5 -27      <144>   R5 = R5["Magnitude"]                            -- It's Const#27
		  +112A2: 21 40 CB 02   line#1220 LE 0 5 -46            <145>   if R5 <= 275 then GOTO <147>                    -- It's Const#46
		  +112A6: 1E 80 09 80   line#1220 JMP 0 39              <146>   GOTO <186>
		  +112AA: 47 C1 44 02   line#1221 GETTABLE 5 4 -20      <147>   R5 = R4@v["HumanoidRootPart"]                   -- It's Const#20
		  +112AE: 86 41 47 00   line#1221 GETTABUP 6 0 -30      <148>   R6 = Upv#1@_ENV["Vector3"]                      -- It's Const#30
		  +112B2: 87 81 47 03   line#1221 GETTABLE 6 6 -31      <149>   R6 = R6["new"]                                  -- It's Const#31
		  +112B6: C1 C1 07 00   line#1221 LOADK 7 -32           <150>   R7 = 70                                         -- It's Const#32
		  +112BA: 01 C2 07 00   line#1221 LOADK 8 -32           <151>   R8 = 70                                         -- It's Const#32
		  +112BE: 41 C2 07 00   line#1221 LOADK 9 -32           <152>   R9 = 70                                         -- It's Const#32
		  +112C2: A4 81 00 02   line#1221 CALL 6 4 2            <153>   R6 = R6(R7, R8, R9)
		  +112C6: 4A 81 01 8E   line#1221 SETTABLE 5 -29 6      <154>   R5["Size"] = R6                                 -- It's Const#29
		  +112CA: 47 C1 44 02   line#1222 GETTABLE 5 4 -20      <155>   R5 = R4@v["HumanoidRootPart"]                   -- It's Const#20
		  +112CE: 86 41 48 00   line#1222 GETTABUP 6 0 -34      <156>   R6 = Upv#1@_ENV["PosMon"]                       -- It's Const#34
		  +112D2: 4A 81 01 90   line#1222 SETTABLE 5 -33 6      <157>   R5["CFrame"] = R6                               -- It's Const#33
		  +112D6: 47 81 44 02   line#1223 GETTABLE 5 4 -19      <158>   R5 = R4@v["Humanoid"]                           -- It's Const#19
		  +112DA: 4C 81 C8 02   line#1223 SELF 5 5 -35          <159>   R6 = R5;  R5 = R5["ChangeState"]                -- It's Const#35   -- prepare for R5:ChangeState()
		  +112DE: C1 C1 08 00   line#1223 LOADK 7 -36           <160>   R7 = 14                                         -- It's Const#36
		  +112E2: 64 41 80 01   line#1223 CALL 5 3 1            <161>   R5(R6, R7)
		  +112E6: 47 C1 44 02   line#1224 GETTABLE 5 4 -20      <162>   R5 = R4@v["HumanoidRootPart"]                   -- It's Const#20
		  +112EA: 4A 41 49 92   line#1224 SETTABLE 5 -37 -38    <163>   R5["CanCollide"] = false                        -- It's Const#37, Const#38
		  +112EE: 47 81 49 02   line#1225 GETTABLE 5 4 -39      <164>   R5 = R4@v["Head"]                               -- It's Const#39
		  +112F2: 4A 41 49 92   line#1225 SETTABLE 5 -37 -38    <165>   R5["CanCollide"] = false                        -- It's Const#37, Const#38
		  +112F6: 47 81 44 02   line#1226 GETTABLE 5 4 -19      <166>   R5 = R4@v["Humanoid"]                           -- It's Const#19
		  +112FA: 4C 41 C4 02   line#1226 SELF 5 5 -18          <167>   R6 = R5;  R5 = R5["FindFirstChild"]             -- It's Const#18   -- prepare for R5:FindFirstChild()
		  +112FE: C1 C1 09 00   line#1226 LOADK 7 -40           <168>   R7 = "Animator"                                 -- It's Const#40
		  +11302: 64 81 80 01   line#1226 CALL 5 3 2            <169>   R5 = R5(R6, R7)
		  +11306: 62 01 00 00   line#1226 TEST 5 0              <170>   if R5 then GOTO <172>
		  +1130A: 1E C0 00 80   line#1226 JMP 0 4               <171>   GOTO <176>
		  +1130E: 47 81 44 02   line#1227 GETTABLE 5 4 -19      <172>   R5 = R4@v["Humanoid"]                           -- It's Const#19
		  +11312: 47 C1 C9 02   line#1227 GETTABLE 5 5 -40      <173>   R5 = R5["Animator"]                             -- It's Const#40
		  +11316: 4C 01 CA 02   line#1227 SELF 5 5 -41          <174>   R6 = R5;  R5 = R5["Destroy"]                    -- It's Const#41   -- prepare for R5:Destroy()
		  +1131A: 64 41 00 01   line#1227 CALL 5 2 1            <175>   R5(R6)
		  +1131E: 46 41 4A 00   line#1229 GETTABUP 5 0 -42      <176>   R5 = Upv#1@_ENV["sethiddenproperty"]            -- It's Const#42
		  +11322: 86 01 41 00   line#1229 GETTABUP 6 0 -5       <177>   R6 = Upv#1@_ENV["game"]                         -- It's Const#5
		  +11326: 8C 41 41 03   line#1229 SELF 6 6 -6           <178>   R7 = R6;  R6 = R6["GetService"]                 -- It's Const#6   -- prepare for R6:GetService()
		  +1132A: 01 C2 05 00   line#1229 LOADK 8 -24           <179>   R8 = "Players"                                  -- It's Const#24
		  +1132E: A4 81 80 01   line#1229 CALL 6 3 2            <180>   R6 = R6(R7, R8)
		  +11332: 87 01 46 03   line#1229 GETTABLE 6 6 -25      <181>   R6 = R6["LocalPlayer"]                          -- It's Const#25
		  +11336: C1 81 0A 00   line#1229 LOADK 7 -43           <182>   R7 = "SimulationRadius"                         -- It's Const#43
		  +1133A: 06 C2 4A 00   line#1229 GETTABUP 8 0 -44      <183>   R8 = Upv#1@_ENV["math"]                         -- It's Const#44
		  +1133E: 07 02 4B 04   line#1229 GETTABLE 8 8 -45      <184>   R8 = R8["huge"]                                 -- It's Const#45
		  +11342: 64 41 00 02   line#1229 CALL 5 4 1            <185>   R5(R6, R7, R8)
		  +11346: 29 80 00 00   line#1209 TFORCALL 0 2          <186>   R3, R4 = R0(R1, R2)
		  +1134A: AA 00 D5 7F   line#1209 TFORLOOP 2 -171       <187>   if R3 ~= nil then { R2 = R3;  GOTO <17> }       -- end of loop
		  +1134E: 26 00 80 00   line#1233 RETURN 0 1            <188>   RETURN
		Functions: 0
