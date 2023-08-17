# Awesome Adaptive Computation

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

Awesome Adaptive Computation is a curated list of Adaptive Computation papers, models, explainers and libraries for Machine Learning.

# Contents

- [Awesome Adaptive Computation](#awesome-adaptive-computation)
- [Contents](#contents)
- [About](#about)
- [Pre-Cursors](#pre-cursors-to-adaptive-computation)
  <!-- - [Algorithm](#algorithm) -->
  <!-- - [System](#system)
  - [Application](#application) -->
  <!-- - [Open-Source System](#open-source-system) -->
- [AI Safety](#ai-safety)

## About

`Adaptive Computation` is the ability of a machine learning system to adjust its `function` and `compute budget` for each example. We can think of this as giving models [System 2](https://en.wikipedia.org/wiki/Thinking,_Fast_and_Slow) thinking.

In this repo, links are organised by topic and have explanations so you can decide what you would like to read. Especially recommended links are starred 🌟

Star this repository to see the latest developments in this research field.

We accept contributions! We strongly encourage researchers to make a pull request with papers, approaches and explanations that they feel others in the community would benefit from 🤗

<!-- ### Survey Papers -->

### Pre-cursors to Adaptive Computation

**Adaptive Mixtures of Local Experts, Jacobs et al (1991)**. [pdf](https://www.cs.toronto.edu/~hinton/absps/jjnh91.pdf)

- Here collaborative, learned Mixture of Experts approaches to handle subsets of the training set are proposed. It's remarkable how close current approaches are to the original gating network. They also show intuitive expert specialisation on the task of vowel discrimination.

<!-- ### Mixture of Experts

### End-to-End Adaptive Computation

### Black-box Adaptive Computation

### Agents & Tools

### Games

### Open Source Libraries -->

<!-- ### Approaches We're Excited To See Explored More -->

### AI Safety

With adaptive computation, we want models to use more compute on harder problems.

For problems where we're concerned about systems failing by not being able to do sufficient computation then Adaptive Computation is very positive for Alignment. We should expect fewer mistakes from a model utilising Adaptive Computation, even on more difficult problems.

However, for problems where we're concerned about systems being deceptive or mesa-optimising increasing the ammount of inference-time compute increases their ability to do so. Here the failure is not a "mistake" but entirely intentional from the system's perspective.

<br>
<br>

---

<br>

Thanks for reading, if you have any suggestions or corrections please submit a pull request!
And please hit the star button to show your appreciation.
