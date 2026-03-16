# FlyPuter
A lightweight sensorimotor bridge connecting the FlyWire connectome used by Eon Systems to MuJoCo physics using Brian2.

Start by running "pip install -r requirements.txt" in your terminal. Next create a conda environment and activate it before running it through Jupyter Notebook

The project is built to use Eons Systems repo at [Eon Systems Data Repo](https://github.com/eonsystemspbc/fly-brain) but you can use what you want

## Probably the roadmap(probably)
Making into several modular .py files so people can integrate it (In progress)

Fixing the render call so that it doesn't strangle the performance (In progress)

Making the bridge able to work with MuJoCo or with Unity (Progress kind of started but slow going)

*If you're one of the so far 36 people who've cloned this and you've managed to fix the renderer, feel free to send out a pull request, I'm not used to python as a Java/JS dev, and it's fighting me more than it should*

## Credits & Citations

### Original Data
This project utilizes the **FlyWire Connectome**, a massive collaboration effort by the **FlyWire Consortium** and the **Princeton FlyWire Lab**.
* Data Source: [flywire.ai](https://flywire.ai/)
* Connectome Paper: [Dorkenwald et al., 2024]

### Software
* **Brian2**: For the spiking neural network simulation
* **MuJoCo**: For the physics and sensorimotor environment
