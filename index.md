---
layout: default
---

<header>
<h1>Benchmarking the Spectrum<br>of Agent Capabilities</h1>
<h2>Anonymous Website for Peer Review</h2>
</header>

## Play Yourself

```
python3 -m pip install crafter  # Install Crafter
python3 -m pip install pygame   # Needed for human interface
python3 -m crafter.run_gui      # Start the game
```

The key mapping will be printed to the terminal.

<p style="text-align: center">
<video controls style="width: 20em">
<source src="video.mp4"/>
</video>
</p>

## Emergent Behaviors

The video shows behaviors of a DreamerV2 agent trained for 50M steps that
emerge from maximizing the provided reward signal.

<p style="text-align: center">
<video controls style="width: 20em">
<source src="emergent.mp4"/>
</video>
</p>

## Supplementary Files

The supplementary files are available as ZIP files below for anonymous peer
review. They will be made available more easily upon publication.

- Environment code: [crafter.zip](crafter.zip)
- Baseline scores: [scores.zip](scores.zip)
- Baseline code: [baselines.zip](baselinesip)
- Plotting code: [analysis.zip](analysis.zip)
