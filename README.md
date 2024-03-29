# [Self-Adaptive Swarm Systems (SASS)](https://www.ijcai.org/proceedings/2021/722) -- Abstract

Multi-agent systems (MAS) could play a pivotal role in realizing future intelligent workspaces, especially in building so-called artificial social systems, such as self-driving cars and [multi-robot systems (MRS)](https://ieeexplore.ieee.org/abstract/document/8901075). For example, MAS/MRS cooperates to increase mission performance in many applications, including exploration, surveillance, defense, humanitarian, and emergency missions like urban search and rescue (USAR). In such missions, complex environments such as hazardous, dynamic changing, and adversarial surroundings create a significant challenge to the agents in realizing their full potential. Therefore, this thesis addresses some pressing gaps in the literature in realizing an adaptive MAS by proposing a principled MAS cooperation framework, termed the Self-Adaptive Swarm System (SASS), which bridges communication, planning, decision-making and learning in the distributed MAS.

<div align = center>
<img src="https://github.com/RickYang2016/Qin-Yang-PhD-Dissertation-SASS/blob/main/figures/sass.png" height="230" alt="Hopper-V2 3SABC"><img src="https://github.com/RickYang2016/Qin-Yang-PhD-Dissertation-SASS/blob/main/figures/sass.gif" height="230" width="445" alt="Hopper-V2 3SABC Video"/>
</div>

<div align = center>
<img src="https://github.com/RickYang2016/Qin-Yang-PhD-Dissertation-SASS/blob/main/figures/sass-framework.png" height="230" alt="Hopper-V2 3SABC"><img src="https://github.com/RickYang2016/Qin-Yang-PhD-Dissertation-SASS/blob/main/figures/gut.gif" height="230" width="445" alt="Hopper-V2 3SABC Video"/>
</div>

## ProQuest Version Dissertation: [Self-Adaptive Swarm Systems (SASS)](https://www.proquest.com/docview/2682292438?pq-origsite=gscholar&fromopenview=true) 

## Full Version Download: [Self-Adaptive Swarm Systems (SASS)](https://github.com/RickYang2016/PhD-Dissertation-SASS/blob/main/Yang_Qin_phd_dissertation.pdf)

<!--
## Full Dissertation: [Self-Adaptive Swarm Systems (SASS)](https://esploro.libs.uga.edu/esploro/outputs/9949451030302959) -->

#### Cite the Dissertation:
```
@phdthesis{yang2022self,
  title={Self-Adaptive Swarm System},
  author={Yang, Qin},
  year={2022},
  school={University of Georgia}
}
```

## Contributions

The core scientific contributions of this thesis are as follows: 
* 1) We define a novel human-inspired [`Agent (robot) Needs Hierarchy`](https://ieeexplore.ieee.org/abstract/document/9283249) model to consider an agent’s motivation and requirements based on the current status and assigned tasks; 
* 2) We present a priority-based distributed `Negotiation-Agreement Mechanism` for realizing multi-agent tasks assignment problems, effectively avoiding plan conflicts – Here, we decompose the tasks into `Atomic Operations` and achieve MAS cooperation through a series of simple sub-tasks; 
> *Note: Check the [Link](https://github.com/RickYang2016/Self-Adaptive-Swarm-System_SASS_MRS2019) for more details.

* 3) We introduce a new needs-based agent trust and cooperation mechanism – [`Relative Needs Entropy (RNE)`](https://ieeexplore.ieee.org/abstract/document/9659187) – to create [needs-driven relationships](https://ieeexplore.ieee.org/abstract/document/9292570) among multiple agents in challenging environments; 

> The simulation of two heterogeneous robot teams cooperative achieving tasks in USAR with Unity:
    <div align = center>
    <img src="https://github.com/RickYang2016/PhD-Dissertation-SASS/blob/main/figures/rne.png" height="215" alt="Hopper-V2 3SABC">   <img src="https://github.com/RickYang2016/PhD-Dissertation-SASS/blob/main/figures/rne.gif" height="215" width="400" alt="Hopper-V2 3SABC Video"/>
    </div>
    *Note: Check the [Link1](https://github.com/RickYang2016/Needs-driven-MRS-Cooperation-SSRR2020) and [Link2](https://github.com/RickYang2016/RNE-Agent-Trust-Model-SMC2021) for further reading.

* 4) We build a new hierarchical utility network – [`Game-theoretic Utility Tree (GUT)`](https://arxiv.org/abs/2004.10950) – to realize game-theoretic solutions for the cooperating MAS in the presence of adversarial agents; 
> The simulation of explorers against adversaries with GUT achieving a task in [Explore Domain](https://arxiv.org/abs/2004.10950):
    <div align = center>
    <img src="https://github.com/RickYang2016/PhD-Dissertation-SASS/blob/main/figures/gut.jpg" height="240" alt="Hopper-V2 3SABC">   <img src="https://github.com/RickYang2016/PhD-Dissertation-SASS/blob/main/figures/gut_s.gif" height="240" width="445" alt="Hopper-V2 3SABC Video"/>
    </div>

> The Explore Domain in Robotarium: `Greedy Approach` vs `Random Selection` vs `GUT`
    <div align = center>
    <img src="https://github.com/RickYang2016/PhD-Dissertation-SASS/blob/main/figures/greedy.gif" height="130" width="232" title="Constant Bearing (CB)">   <img src="https://github.com/RickYang2016/PhD-Dissertation-SASS/blob/main/figures/random.gif" height="130" width="232" alt="Hopper-V2 3SABC Video">      <img src="https://github.com/RickYang2016/PhD-Dissertation-SASS/blob/main/figures/gut_explore.gif" height="130" width="232" alt="Hopper-V2 3SABC Video"/>
    </div>
    *Note: Check the [Link](https://github.com/RickYang2016/Game-theortic-Utility-Tree--GUT) for more details.

> The [Pursuit Domain in Robotarium](https://arxiv.org/abs/2206.01109): `Constant Bearing (CB)` vs `Pure Pursuit (PP)` vs `GUT`
    <div align = center>
    <img src="https://github.com/RickYang2016/PhD-Dissertation-SASS/blob/main/figures/cb.gif" height="130" width="232" title="Constant Bearing (CB)">   <img src="https://github.com/RickYang2016/PhD-Dissertation-SASS/blob/main/figures/pp.gif" height="130" width="232" alt="Hopper-V2 3SABC Video">      <img src="https://github.com/RickYang2016/PhD-Dissertation-SASS/blob/main/figures/gut_pursuit.gif" height="130" width="232" alt="Hopper-V2 3SABC Video"/>
    </div>
    *Note: Check the [Link](https://github.com/RickYang2016/Gut-Pursuit-Domain-Robotarium-ISR2022) for more details.

* 5) We propose a novel [`Bayesian Strategy Networks (BSN)`](https://arxiv.org/pdf/2208.06033.pdf) applied to deep reinforcement learning by decomposing tasks into multiple sub-level actions and obtaining the optimal agent policies in unknown and challenging environments.

![image](https://github.com/RickYang2016/PhD-Dissertation-SASS/blob/main/figures/policy_network.png)

<div align = center>
<img src="https://github.com/RickYang2016/PhD-Dissertation-SASS/blob/main/figures/walker2d.png" height="240" alt="Hopper-V2 3SABC"><img src="https://github.com/RickYang2016/PhD-Dissertation-SASS/blob/main/figures/biped_robot.gif" height="240" width="346" alt="Hopper-V2 3SABC Video"/>
</div>

> Demonstration in MuJoCo with OpenAI Gym: `Hopper-v2`, `Walker2d-v2`, `Humanoid-v2`
    <div align = center>
    <img src="https://github.com/RickYang2016/PhD-Dissertation-SASS/blob/main/figures/hopper-v2_3bsac.png" height="120" alt="Hopper-V2 3SABC"><img src="https://github.com/RickYang2016/PhD-Dissertation-SASS/blob/main/figures/hopper-v2_3bsac.gif" height="120" width="82" title="Constant Bearing (CB)">   <img src="https://github.com/RickYang2016/PhD-Dissertation-SASS/blob/main/figures/walker2d_v2_5bsac.png" height="120" alt="Hopper-V2 3SABC"><img src="https://github.com/RickYang2016/PhD-Dissertation-SASS/blob/main/figures/walker2d-v2_5bsac.gif" height="120" width="82" alt="Hopper-V2 3SABC Video">   <img src="https://github.com/RickYang2016/PhD-Dissertation-SASS/blob/main/figures/humanoid-v2_5bsac.png" height="120" alt="Hopper-V2 3SABC"><img src="https://github.com/RickYang2016/PhD-Dissertation-SASS/blob/main/figures/humanoid-v2_3bsac.gif" height="120" width="82" alt="Hopper-V2 3SABC Video"/>
    </div>
    *Note: Check the [Link](https://github.com/RickYang2016/Bayesian-Soft-Actor-Critic--BSAC) for more details.
