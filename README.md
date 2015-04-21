# LunarLanderGA

This project shows that MLP (Multi layer perceptrons) can be used in videogames to create characters with advanced AI capabilities.
The main advantage of this aproach is the ability that neural networks have to simulate the natural learnig process.

<img src="https://github.com/lopeLH/LunarLanderGA/blob/master/Executable%20JAR/resources/mainImage.png"  width=400 height=400 />

In this example, a neural network is used to play the clasical Lunar Lander game, and trained by means of a Genetic Algorithm that
optimices the MLP performance acording to the fitnes function. The fitness function penalices fuel consumption and inpact velocity
against the floor.

This architecture makes posible creating games where AI characters evolve, making the game harder as the human 
player adquires new skills.

NetBeans project is provided in adition to the executable JAR. The following libraries are used:

- Encog http://www.heatonresearch.com/encog
- Slick2D & LWJGL http://slick.ninjacave.com/ (http://slick.ninjacave.com/wiki/index.php?title=Setting_up_Slick2D_with_NetBeansIDE)
