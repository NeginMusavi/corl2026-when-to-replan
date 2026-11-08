# When Should a Robot Replan? Regret-Guided Update Scheduling in Time-Varying MDPs

**Negin Musavi**, Gokul Puthumanaillam, Ruben Hernandez, William Schafer, Melkior Ornik
*University of Illinois Urbana-Champaign*

*10th Conference on Robot Learning (CoRL 2026), Austin, TX, USA*

📄 [Paper (PDF)](paper.pdf) · 🖼️ [Poster (PDF)](poster.pdf) · 📚 [arXiv:2606.16972](https://arxiv.org/abs/2606.16972)

## Abstract

Robots operating in non-stationary environments must continually adapt their policies as the dynamics drift, but onboard energy and compute budgets cap how often a full state estimation and re-planning step can be performed. This raises a question: when, along a horizon, should a robot spend its limited budget? We formulate this problem in time-varying Markov decision processes (TVMDPs) with a known bound on the rate of transition drift. We model execution as a skip-update scheme in which, at chosen update times, the agent estimates the transition kernel by maximum likelihood and computes a finite-horizon policy, and between updates reuses this policy under a propagated state estimate. We analyze the dynamic regret of this scheme and show how it grows during skip intervals in terms of the properties of the TVMDP and the skip lengths; the resulting bound answers the opening question via an online, regret-guided update rule that allocates the budget adaptively. We evaluate the rule in a simulated Mars-rover navigation task with time-varying slip dynamics and on a Crazyflie quadrotor in indoor obstacle fields. Adaptive allocation outperforms other budgeted baselines.

## Citation

```bibtex
@inproceedings{musavi2026replan,
  title     = {When Should a Robot Replan? Regret-Guided Update Scheduling in Time-Varying {MDP}s},
  author    = {Musavi, Negin and Puthumanaillam, Gokul and Hernandez, Ruben and Schafer, William and Ornik, Melkior},
  booktitle = {Conference on Robot Learning (CoRL)},
  year      = {2026}
}
```
