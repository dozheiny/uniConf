# Preface

Cheaters have continued to beat anti-cheat software and tools implemented by developers designed to block cheaters.

Most of the anti-cheat systems implemented in **Online Games**
# Unfortunately, Everyone can cheat.

#### Collecting data from user
Everything can collect, even mouse directions
[1](https://mathworld.wolfram.com/Left-HandedCoordinateSystem.html)[2](https://mathworld.wolfram.com/Right-HandedCoordinateSystem.html)
##### Collecting Data is not the best method.

Some games, for example, let clients report their own positions to the server, which then only validates that they are not teleporting, moving too fast, phasing through a wall, hovering off the ground for an extended period of time, etc. This prevents most blatant forms of movement cheating, like teleporting across the map or walking through walls, while still giving players a smooth and rubberband-free gameplay experience. Even on crappy network connections. The catch, of course, is players can still push themselves to run a tiny bit faster than normal, by pushing their speed closer and closer to whatever this speed limit is.

# DPI

**Deep packet inspection** (**DPI**) helps so much to detect cheaters, **Epic Games** and **NVIDIA** favorite method
[1](https://en.wikipedia.org/wiki/Deep_packet_inspection)[2](https://www.ntop.org/products/deep-packet-inspection/ndpi/)[3](https://developer.valvesoftware.com/wiki/Latency_Compensating_Methods_in_Client/Server_In-game_Protocol_Design_and_Optimization)[4](https://www.ntop.org/guides/nDPI/protocols.html#ndpi-protocol-epicgames)[5](https://datatracker.ietf.org/doc/html/rfc3711)

# OK, But what about before 2009?

🪙 Let's create heads or tails game, who's flip the coin and it's heads will win!

```go
type HeadsOrTails uint8

var heads HeadsOrTails = 0
var tails HeadsOrTails = 1
```

## Players, flip the coins!
### 🥅 Goals?
1. Avoid accusing fair players of cheating
2. Catch as many cheaters as possible
3. Make the test as brief as possible


# Frequencies Hypnosis Testing [1](https://en.wikipedia.org/wiki/Statistical_hypothesis_testing)

| | TEST: True Not Cheater | TEST: True Cheater |
|- |- | -|
|ACTUAL: True Not Cheater | 🟢| 🔴 |
|ACTUAL: True Cheater | 🔴 | 🟢 |

# 🥅 Goals?
- [ ] Accuse fewer than 5% of fair players
- [ ]  Catch 80% of cheaters
- [ ]  Make the test Brief as possible 

# 🪙 Unfair Coin?
75% heads and 25% tails!

Probability of five heads in a row from a cheater? 

```
P(🪙) = 0.75 = 75%
P(🪙 x 5) (0.75)**5 = 24%
```

# Probability!

### Flip fair and unfair coin 5 times:
```chart
type: bar
labels: [Fair Coin Probability,Unfair Coin Probability]
series:
  - title: 1
    data: [50,75]
  - title: 2
    data: [25,56.25]
  - title: 3
    data: [12.5,42.188]
  - title: 4
    data: [6.25,31.641]
  - title: 5
    data: [3.125,23.73]
width: 80%
beginAtZero: true
```

| TEST/ACTUAL | Not Cheater | Cheater |
|- |- | -|
| Not Cheater | 🟢 96.9% | 🔴 3.1% |
|Cheater | 🔴 76.3% | 🟢23.7% | 


### Flip fair and unfair coin 20 times:

```chart
type: bar
labels: [Fair Coin Probability,Unfair Coin Probability]
series:
  - title: 1
    data: [50.0,75.0]
  - title: 2
    data: [25.0,56.25]
  - title: 3
    data: [12.5,42.1875]
  - title: 4
    data: [6.25,31.640625]
  - title: 5
    data: [3.125,23.73046875]
  - title: 6
    data: [1.5625,17.7978515625]
  - title: 7
    data: [0.78125,13.348388671875]
  - title: 8
    data: [0.390625,10.01129150390625]
  - title: 9
    data: [0.1953125,7.5084686279296875]
  - title: 10
    data: [0.09765625,5.631351470947266]
  - title: 11
    data: [0.048828125,4.223513603210449]
  - title: 12
    data: [0.0244140625,3.167635202407837]
  - title: 13
    data: [0.01220703125,2.3757264018058777]
  - title: 14
    data: [0.006103515625,1.7817948013544083]
  - title: 15
    data: [0.0030517578125,1.3363461010158062]
  - title: 16
    data: [0.00152587890625,1.0022595757618546]
  - title: 17
    data: [0.000762939453125,0.751694681821391]
  - title: 18
    data: [0.0003814697265625,0.5637710113660432]
  - title: 19
    data: [0.00019073486328125,0.42282825852453243]
  - title: 20
    data: [9.5367431640625e-05,0.3171211938933993]
width: 100%
beginAtZero: true
```

| TEST/ACTUAL | Not Cheater | Cheater |
|- |- | -|
| Not Cheater | 🟢 95.3% | 🔴 4.7% |
|Cheater | 🔴 19.6% | 🟢80.4% | 
# The End
github.com/dozheiny/uniConf/
# References
[Left-Handed Coordinate System -- from Wolfram MathWorld](https://mathworld.wolfram.com/Left-HandedCoordinateSystem.html)
[Right-Handed Coordinate System -- from Wolfram MathWorld](https://mathworld.wolfram.com/Right-HandedCoordinateSystem.html)
[Deep packet inspection - Wikipedia](https://en.wikipedia.org/wiki/Deep_packet_inspection)
[nDPI – ntop.org](https://www.ntop.org/products/deep-packet-inspection/ndpi/)
[Latency Compensating Methods in Client/Server In-game Protocol Design and Optimization - Valve Developer Community (valvesoftware.com)](https://developer.valvesoftware.com/wiki/Latency_Compensating_Methods_in_Client/Server_In-game_Protocol_Design_and_Optimization)
[nDPI Protocols List — nDPI 4.1 documentation (ntop.org)](https://www.ntop.org/guides/nDPI/protocols.html#ndpi-protocol-epicgames)
[RFC 3711 - The Secure Real-time Transport Protocol (SRTP) (ietf.org)](https://datatracker.ietf.org/doc/html/rfc3711)
[Anti-Cheat. How does it work? : gamedev (reddit.com)](https://www.reddit.com/r/gamedev/comments/87i3p1/anticheat_how_does_it_work/)
[How To Catch A Cheater With Math (youtube.com)](https://www.youtube.com/watch?v=XTcP4oo4JI4)
[Statistical hypothesis testing - Wikipedia](https://en.wikipedia.org/wiki/Statistical_hypothesis_testing)