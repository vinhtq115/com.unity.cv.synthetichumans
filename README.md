# Cloth-changing SyntheticHumans Package

Modified version of [Unity's SyntheticHumans Package](https://github.com/Unity-Technologies/com.unity.cv.synthetichumans) with cloth-changing feature.

<p align="center">
<img width="350" src="./Documentation~/Images/new_settings.png">
</p>

New "Clothes Per Person" option enables generating additional clothes for the same person. Basically, non-clothing properties like height, weight, face, body, etc. are kept while only clothes are changed.

**Note**:
* Same people in different clothes will be considered as different people with different ID. For example, if "Clothes Per Person" is set to 5, person 1 will be person 1 to 5, person 2 will be 6 to 10, etc.
* Since different clothes are counted as different people, the number of unique people will be decreased. In the example figure above, there will be 150 unique people only.


Below is the original README.md of SyntheticHumans Package:

---
<p align="center">
<img width="500" src="./Documentation~/Images/unity-wide-whiteback.png">
</p>

<p align="center">
<img src="./Documentation~/Images/banner.png">
</p>

# SyntheticHumans Package ([Unity Computer Vision](https://unity.com/computer-vision))

The SyntheticHumans package gives you the ability to procedurally generate and realistically place diverse groups of synthetic humans in your Unity Computer Vision projects. The package gives you control over the distribution of several human properties, as well as a customizable placement system to fit your bespoke contextual needs.

## Getting Started

**[Quick Installation Instructions](https://github.com/Unity-Technologies/com.unity.cv.synthetichumans/wiki/Quick-Installation-Guide)**

Install the SyntheticHumans package into an existing project. Recommended for users with prior Unity experience.

**[Tutorial: Introduction to SyntheticHumans](https://github.com/Unity-Technologies/com.unity.cv.synthetichumans/wiki/Synthetic-Humans-Tutorial)**

Go through a step-by-step tutorial on adding the SyntheticHumans package to a project, customizing its settings, generating humans, animating them, and placing them into your Scenes.

## Package Version Compatibility

The SyntheticHumans package requires the Perception package. The current SyntheticHumans version is compatible with `com.unity.perception: 1.0.0-preview.1`. Older versions of SyntheticHumans may require older versions of Perception.
