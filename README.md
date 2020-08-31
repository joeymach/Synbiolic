# Synbiolic Platform - Unlocking Drug Discovery with AI 
#### Microsoft Imagine Cup Americas Regional Finalist & Runner-Up
End-to-end ML pipeline for drug discovery from generating novel small molecules with **desired effects** to predicting the synthesis (retrosynthesis) pathways of those generated molecules. 

## Check out Synbiolic's Content
- [Website](https://synbiolic.com/)
- [Pitch Video (4:40)](https://www.youtube.com/watch?v=vEfpFVIOYQY)
- [Demo Video (1:03)](https://www.youtube.com/watch?v=Kt6j1dJpIDA&feature=youtu.be)
- [Article about Reinforcement Learning](https://medium.com/datadriveninvestor/drug-design-made-fun-using-reinforcement-learning-212a4f867f33)
- [Article about VAE model](https://towardsdatascience.com/unlocking-drug-discovery-through-machine-learning-part-1-8b2a64333e07)
- Older Version of Synbiolic's Open Source Repo at [William Law's Github](https://github.com/wlawt/synbiolic)

## Media
- [Microsoft Imagine Cup (IC) N.A. Regional Finalist (Top 5 of 28000)](https://blogs.microsoft.com/latinx/2020/03/26/rounding-up-this-years-microsoft-imagine-cup-introducing-the-10-americas-regional-finalist-teams/?_lrsc=80d7de8f-0168-4ffc-8e0e-912c0a0377d5)
- [Microsoft IC Feature](https://news.microsoft.com/en-ca/2020/03/30/team-synbiolic-from-canada-wins-runner-up-position-at-the-2020-microsoft-imagine-cup-americas-regional-finals/)
- [Runner Up Microsoft IC Feature](https://techcommunity.microsoft.com/t5/student-developer-blog/congratulations-to-our-2020-imagine-cup-americas-regional-final/ba-p/1264942)
- [Microsoft IC Pitch](https://www.youtube.com/watch?v=OUDGOfMDOi0)

## Download Repo

#### Clone the repository:

```
git clone https://github.com/joeym-09/Synbiolic.git
cd synbiolic
```

#### To run Synbiolic:

```
npm install
cd client
npm install
cd ../
npm run dev
```

## Walkthrough

#### Landing Page

![Landing page](https://github.com/joeym-09/synbiolic/blob/master/client/src/components/img/landing.png)

#### User onboarding

![User onboarding](https://github.com/joeym-09/synbiolic/blob/master/client/src/components/img/welcome.png)

#### Generate Molecules

![Generate Molecules](https://github.com/joeym-09/synbiolic/blob/master/client/src/components/img/generate.png)

- The number of recommended molecules to generate is 20-50 (for demo purposes).
- It will then take you to all the generated molecules - where you can view the molecules and the plc-50 distribution
- You can save any of the molecules and click on them to bring up the retrosynthesis pathway
- The retrosynthesis pathway will have more details about the molecule itself

#### View saved molecules

![Saved Molecules](https://github.com/joeym-09/synbiolic/blob/master/client/src/components/img/saved.png)

#### View Retrosynthesis Requests

![Retrosynthesis Requests](https://github.com/joeym-09/synbiolic/blob/master/client/src/components/img/retro.png)

## Contributors to Synbiolic

- William Law - [Twitter](https://twitter.com/wlaw_), [Website](https://wlawt.com/), [Github](https://github.com/wlawt)
- Aryan Misra - [Twitter](https://twitter.com/AryanMisra7), [Website](https://aryanmisra.com/), [Github](https://github.com/aryanmisra)
- Joey Mach - [Twitter](https://twitter.com/joeymach_), [Website](http://joeymach.com/), [Github](https://github.com/joeym-09)

## References

- [Deep reinforcement learning for de novo drug design Popova et. al 2018](https://advances.sciencemag.org/content/4/7/eaap7885)
- [DeepChem](https://github.com/deepchem/deepchem)
- [IBM RXN Chem](https://rxn.res.ibm.com/rxn/sign-in)
- [Azure ML](https://azure.microsoft.com/en-ca/services/machine-learning/)
- [Azure API Management](https://azure.microsoft.com/en-us/services/api-management/)
- [RXN Finder API](http://hulab.rxnfinder.org/smi2img/)
