# Unity User Guide

## About

This is a [Unity](https://unity.com/) User guide

I will start at the beginning and work my way through the variations avenues you could have about your game. I will go through 2D and 3D games along with general tips and tricks for solo and team-based projects. Without future ado, let's begin! 

## Index

1. [Installation](#install)
2. [General](#main)
3. [2D](#2D)
   * [General](#2dg)
   * [Movement](#move)
   * Pixelated
4. 3D
   1. General
   2. 
5. [Collaboration](#team)
   * [Unity's Collab](#unity) (recommended)
   * [GitHub](#git)
6. [Resources](#help)

<a name="install"></a>

### Installation

Before installing, note that Unity is completely free forever, if you or your company makes less than $100 000 (USD). 

Follow the link [here](https://store.unity.com/download) and download the free installer (the plus version is definitely not necessary). Follow the instructions and download the installer. The installer is simple and easy however, if you run into trouble, go to this [video](https://www.youtube.com/watch?v=KMuMhA6Lk0I) for Windows. Also note that you will may need a Unity account or just use your Google/ Facebook account to sign in. 

If you want a new version of Unity, go to the Unity Hub and click the **Installs** tab on the left and **add** (top right) the desired version. Afterwards, the installation will take quite a while, even with a fast internet connection. 

When installing Unity, it might ask you to install **Visual Studio** along-side Unity. If you have Visual Studio, do not install again, it should automatically detect the current VS on the system. Otherwise, it is optional and I've heard that MonoDevelop (comes with Unity) is good enough for handling the task Unity puts forth. 

<a name="main"></a>

### General

**Unity** is a 3D game engine built in **C#** but can be used for 2D. Before you freak out about programming, let me assure, you it is quite trivial. If you have programmed before especially in C++, it is a huge plus. If you have not, don't worry, it's just a bunch of copy and pasting. The most important thing is don't be frustrated and 

```c#
Debug.Log() // logs to Unity console
```

is your friend. Also organize your scenes by naming them or using empties as folders (+1 organization). Now, it is time to pick, 2D or 3D. (As a beginner, start with 2D)

<a name="2D"></a>

### 2D

<a name="2dg"></a>

#### General

So you've decide to make a 2D game. Great! Who needs modelling and lighting (It's a lot of work anyways)? 

2D games are secretly 3D, what does that mean? Think of Unity 2D as a bunch of layers like in Photoshop, Gimp, After Effects, or Illustrator. The closest to the camera is picked up first and blocks the ones behind it. As a 2D world, lighting is global (unless you want enable an experimental local lighting feature). Now let's make a play and make it move!

<a name="move"></a>

#### Movement



<a name="team"></a>

### Collaboration

<a name="unity"></a>

#### Unity's Collab

Collaborating will friends can be tough will Unity, especially with git/GitHub, but it you are careful, things could turn out fine.

If you need to collaborate, the best way is to use Unity's Collab feature

![collab](collab.png)

However, note that this only supports 4 people (which is usually enough because only people that will contribute to the codebase should need it)

<a name='git'></a>

#### GitHub

Otherwise if you are a masochistic and decide to GitHub, here are some general practices:

1. Everyone should work on there own branches and work on there own scenes working towards **Prefabs** (ie one person on movement, one on moving platforms, etc.)
2. Optionally, have one person on the master (final) level to peace it together
3. Use [this](https://github.com/github/gitignore/blob/master/Unity.gitignore) gitignore or clone from my projects on GitHub
4. Have the core gameplay done first (especially at a Game Jam)
5. Get to know Git/GitHub and how version control works
6. Remember you can go back to a previous working version
7. Have fun and don't fight with your team members

<a name="Help"></a>

### Resources

* The [Unity User Manual](https://docs.unity3d.com/Manual/index.html) provides some great documentation with code that can for the most part be copied and pasted
* Brackeys [YouTube channel](https://www.youtube.com/user/Brackeys)
* [Lynda.com](https://www.lynda.com/) - If you have a library card, there is a high probability that you have access to Lynda with their organization deal
* Google is your best friend
* Ask on Reddit or Stack Exchange, don't worry they won't bite

