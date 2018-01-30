# Project Duality

![Duality](https://i.imgur.com/icbUnPg.png "Project Duality")

Project Duality is an AI framework intended primarily for personally learning the fundementals of machine learning. The learning system is intended to be modular via the ability to save or load universally common knowledge files *(`*.pdks` - Project Duality Knowledge Store)* - These files contain information stored/learned by an AI. This knowledge is written in a common format so that it can be easily ported to other instances. Alternatively, entire AI instances (AI with knowledge and any tweaks) will be saved to a file. *(`*.pdi` - Project Duality Instance)* `*.pdi` files will contain embedded `*.pdks` files and will *not* reference external files - This means that any files loaded in will be duplicated for local storage. This is to ensure that portability is maintained. For additional information on the formats and what they do, please see [the format information sheet](https://github.com/XanTheDragon/Project-Duality/blob/master/FORMAT-SPECS.MD).

## The primary goals
These are the goals that I have set for the development of Project Duality

* Duality must provide a modular AI framework that is easy to work with in code.

  * The framework must be specifically designed for an environment of tinkering or any other method of testing, and

  * Include the capability to learn from any source of information defined by the user via provided learning methods that can be expanded upon.

* Run on hardware that may not be viewed as capable of machine learning.

  * And, if applicable, potentially be run on portable devices.
  
* Maintain an energy efficient model that will not introduce extraneous workload on hardware.
