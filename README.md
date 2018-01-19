# Project Duality

![Duality](https://i.imgur.com/icbUnPg.png "Project Duality")

Project Duality is an AI framework intended primarily for personal learning of the fundementals of machine learning. The learning system is intended to be modular via the ability to save or load universally common "knowledge" files *(`*.pdkb` - Project Duality Knowledge Base)* - These files store information stored by an AI in a common manner so that it can be easily ported to other instances. Likewise, AI instances as a whole will be saved to file *(`*.pdi` - Project Duality Instance)* so that they can be ported to other machines with ease. Instances will internally store `.pdkb` files and will not reference external files for the sake of compatibility.

## The primary goals
These are the goals that I have set for the development of Project Duality

* Duality must provide a modular AI framework that is easy to work with in code.

  * The framework must be specifically designed for an environment of tinkering or any other method of testing, and

  * Include the capability to learn from any source of information.

* Run on hardware that may not be viewed as capable of machine learning.

  * And, if applicable, potentially be run on portable devices.
