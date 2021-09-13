---
layout: default
---

<center style="margin-bottom: 5em">
<h1>Benchmarking Diverse Agent Capabilities</h1>
<h2>Anonymous Website for Peer Review</h2>
</center>

## Play Yourself

```
python3 -m pip install crafter  # Install Crafter
python3 -m pip install pygame   # Needed for human interface
python3 -m crafter.run_gui      # Start the game
```

The key mapping will be printed to the terminal.

<p style="text-align: center">
<video controls style="width: 30em">
<source src="video.mp4"/>
</video>
</p>

## Emergent Behaviors

The video shows behaviors of a DreamerV2 agent trained for 50M steps that
emerge from maximizing the provided reward signal.

<p style="text-align: center">
<video controls style="width: 30em">
<source src="emergent.mp4"/>
</video>
</p>

## Source Code

The complete code for the environment, baseline agents, and figures in the
paper will be made available upon publication to ensure an anonymous review
period. We will also make the baseline scores available as JSON files.
