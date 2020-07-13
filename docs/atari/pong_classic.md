---
layout: "docu"
actions: "Discrete"
agents: "2"
manual-control: "No"
action-shape: "(1,)"
action-values: "[0,17]"
observation-shape: "(210, 160, 3)"
observation-values: "(0,255)"
---

### Pong: Classic

This environment is part of the [Atari environments](../atari). Please read that page first for general information.

{% include table.md %}


`from pettingzoo.atari import pong_classic_v0`

`agents= ["first_0", "second_0"]`

![pong gif](atari_pong_classic.gif)

*AEC diagram*

Classic two player competitive game of timing.

Get the ball past the opponent.

Scoring a point gives you +1 reward and your opponent -1 reward.

[Official Video Olympics manual](https://atariage.com/manual_html_page.php?SoftwareLabelID=587)

#### Environment parameters

Some environment parameters are common to all Atari environments and are described in the [base Atari documentation](../atari).

Parameters specific to Pong Classic are

```
pong_classic.env(num_players=2)
```

```
num_players: Number of players (must be either 2 or 4)
```