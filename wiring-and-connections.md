#Studio notes — Connections


##ESX 8MD

Port          | Instrument    | Notes
:------------ | :------------ | :------------
1             | KAWAI K1R     |
2             | YAMAHA TX81Z  |
3             | KORG M1R      |
4             | AKAI S950     |
5             | DX7           | Channel 6 
6             | Juno 106      |
7             | SH-101        | Channel 15
8             | MPC 2000XL	  |
9             | 909           |
10            | 808           | Channel 10
11            | 707           | 
12            | DX100         |
13            |               |
14            |               |
15            |               |
16            |               |


###ES4 Controller
MIDI/CV1 Channel = OFF
MIDI Out Channel = Omni Output = 1/[Port#]

##SYNC-GEN II

Port          | Instrument    | Notes
:------------ | :------------ | :------------
1 DIN         | TR-909        | Shift+Tempo mode (twice)
2 DIN         | TB-303
3 DIN         | TR-808        | Kenton rear switch up
4 DIN         | 
5 DIN         | 


##Logic external effects
###Send effects
1. Instrument on track, Send 100% to BUS
1. Use I/O on AUX track, out 3 in 5&6
1. Patch in effect 100% wet
1. Create print track, input 5&6 (latency is negligible)
1. Record print track then disable I/O on AUX track
