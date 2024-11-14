---
title: Capabilities of the System
---
The system implemented in the Thousand Brains Project is designed to be a general-purpose AI system. It is not designed to solve a specific task or set of tasks. Instead, it is designed to be a platform that can be used to build a wide variety of AI applications. Like an operating system or a programming language does not define what the user applies it to, the Thousand Brains Project will provide the tools necessary to solve many of today's current problems as well as completely new and unanticipated ones without being specific to any one of them.

Even though we cannot predict the ultimate use cases of the system, we want to test it on a variety of tasks and keep a set of capabilities in mind when designing the system. The basic principle here is that **it should be able to solve any task the neocortex can solve**. If we come up with a new mechanism that makes it fundamentally impossible to do something the neocortex can do, we need to rethink the mechanism.

Following is a list of capabilities that we are always thinking about when designing and implementing the system. We are not looking for point solutions for each of these problems but a general algorithm that can solve them all. It is by no means a comprehensive list but should give an idea of the scope of the system.

- Recognizing objects independent of their location and orientation in the world.

- Determining the location and orientation of an object relative to the observer, or to another object in the world.

- Performing learning and inference under noisy conditions.

- Learning from a small number of samples.

- Learning from continuous interaction with the environment with no explicit supervision, whilst maintaining previously learned representations.

- Recognizing objects when they are partially occluded by other objects.

- Learning categories of objects and generalizing to new instances of a category.

- Learning and recognizing compositional objects, including novel combinations of their parts.

- Recognizing objects subject to novel deformations (e.g. Dali's 'melting clocks', a crumpled up t-shirt, or recognizing objects learned in 3D but seen in 2D).

- Recognizing an object independent of its scale, and estimating its scale.

- Modeling and recognizing object states and behaviors (e.g. if a stapler is open or closed; whether a person is walking or running, and how their body evolves over time under these conditions).

- Using learned models to alter the world and achieve goals, including goals that require decomposition into simpler tasks. The highest-level, overarching goals can be set externally.

- Generalizing modeling to abstract concepts derived from concrete models.

- Modeling language and associating it with grounded models of the world.

- Modeling other entities ('Theory of Mind').