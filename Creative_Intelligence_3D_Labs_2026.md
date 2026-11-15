# CREATIVE INTELLIGENCE LABS

### A 2026 field guide to free 3D, Python, electronics, robotics, AI, and real-world simulation

**Curated by 0xAllow**  
**Updated:** November 14, 2026  
**Theme:** *Explore → Visualize → Simulate → Code → Build → Learn*  

> **The idea:** Intelligence becomes easier to understand when you can see it move. Build circuits before buying components, train neural networks before deploying models, and test robots in simulated worlds before they touch the real one.

This is a practical, categorized collection of interactive websites and free/open-source tools. It favors **hands-on learning, visual intuition, creative experimentation, and real-world transfer** over passive video courses.

## Legend

- **Free** = free to use for the described learning workflow; restrictions or licenses may apply.
- **Freemium** = useful free tier, but private projects, resources, advanced features, or usage may be paid.
- **Open source** = source code is published under an open-source license; hardware and computing are not necessarily free.
- **Browser** = usable directly in a modern web browser, without installing the main simulator.
- **Desktop** = local installation recommended or required for serious use.
- **3D** = genuine three-dimensional visualization or simulation; **2D** is clearly labeled.
- **Physics simulation ≠ hardware validation.** Real sensors, current limits, friction, latency, lighting, and safety still have to be tested.

**A note on availability:** Links and offerings were reviewed against official or primary project pages in November 2026 where possible. Free plans, browser support, and licenses can change. “Free” does not promise unlimited cloud computing or commercial rights.

---

## 01 · Interactive 3D Electronics & Arduino

*See the circuit. Change the code. Watch the system respond.*

| Platform | Format | Access | What you can do | First experiment |
|---|---|---|---|---|
| ⭐ [Learn Arduino — Interactive 3D](https://learn-arduino-red.vercel.app/) | Browser · **3D** | Free learning experience | Explore an Arduino Uno, electronics, code, schematic views, and **16 guided lessons** | Blink an LED, then modify timing and inspect the wiring |
| [Learn Arduino (independent 3D lab)](https://learnarduino.tech/) | Browser · **3D** | Free; open-source project | Build breadboard circuits, use sensors and motors, run simulated Arduino sketches | Make a parking sensor |
| [Tinkercad Circuits](https://www.tinkercad.com/circuits) | Browser · visual circuit workspace | Free account | Connect breadboards, basic components and Arduino, then simulate code | Traffic light with pedestrian button |
| [Wokwi](https://wokwi.com/) | Browser · **2D wiring simulation** | Freemium; free public/community projects | Run firmware on simulated Arduino, ESP32, Raspberry Pi Pico, STM32 and peripherals | ESP32 sensor dashboard |
| [Mokxi](https://mokxi.com/) | Browser · **2D circuit simulation** | Freemium; free simulator | Wire microcontrollers and components; run embedded programs | Two microcontrollers exchanging messages |
| [Falstad Circuit Simulator](https://www.falstad.com/circuit/) | Browser · animated **2D** circuits | Free | Visualize current, voltage, filters, transistors and analog behavior | Explore a resistor-capacitor filter |
| [Curvo Studio](https://curvostudio.com/en) | Browser · **3D** models + graphs | Free | Explore electrical machines, semiconductors, motors and transformers | Vary induction motor parameters |

**Recommended journey:** **Learn Arduino 3D → Tinkercad → Wokwi/Mokxi → a real low-voltage prototype.**

**Important:** The initial `learn-arduino-red.vercel.app` experience and `learnarduino.tech` are separate websites; do not assume they share an author or identical simulator capabilities.

---

## 02 · Python, Creative Coding & 3D Mathematics

*Use code as a sketchbook for motion, geometry, and scientific intuition.*

| Platform | Format | Access | What you can do | First experiment |
|---|---|---|---|---|
| [GlowScript / Web VPython](https://www.glowscript.org/) | Browser · **3D** · VPython-style code | Free; sign-in to create programs | Animate objects, vectors, forces and trajectories | Orbiting planet or bouncing ball |
| [Google Colab](https://colab.research.google.com/) | Browser · Python notebooks | Free tier; compute limits | Run real Python, NumPy, Matplotlib, ML libraries, interactive visualizations | Plot a 3D terrain or simulate a pendulum |
| [GeoGebra 3D Calculator](https://www.geogebra.org/3d) | Browser · **3D** | Free for non-commercial learning | Explore surfaces, vectors, solids and transformations | Visualize intersections of 3D surfaces |
| [p5.js Web Editor](https://editor.p5js.org/) | Browser · creative JavaScript, optional WEBGL **3D** | Free and open source | Build generative art, interactive sketches, particles and audiovisual experiments | Particle swarm reacting to a mouse |
| [Three.js Editor](https://threejs.org/editor/) | Browser · **3D** · JavaScript | Free/open-source ecosystem | Experiment with 3D scenes, lighting, geometry and cameras | Build a miniature virtual laboratory |
| [JupyterLite](https://jupyterlite.github.io/demo/lab/) | Browser · Python notebooks | Free/open source | Run compatible Python notebooks in the browser, without a hosted server | Plot and interact with a numerical model |

**Python note:** p5.js and Three.js use **JavaScript**, not Python. They belong here because creative 3D coding and data visualization make excellent companions to Python-based scientific computing. Google Colab is Python, but interactive 3D requires additional libraries and code.

---

## 03 · Neural Networks, Machine Learning & Explainable AI

*Do not just run a model: watch its decisions form.*

| Platform | Format | Access | What you can do | First experiment |
|---|---|---|---|---|
| ⭐ [TensorFlow Playground](https://playground.tensorflow.org/) | Browser · interactive **2D** | Free | Change neuron counts, layers, activation functions and learning rate; watch decision boundaries | Separate two spirals |
| [TensorFlow Embedding Projector](https://projector.tensorflow.org/) | Browser · interactive **3D** data | Free | Rotate and explore high-dimensional embeddings projected into 3D | Explore clusters of handwritten digits |
| [CNN Explainer](https://poloclub.github.io/cnn-explainer/) | Browser · interactive diagrams | Free | Inspect convolution filters, feature maps, pooling and classification | Follow a picture through a CNN |
| [GAN Lab](https://poloclub.github.io/ganlab/) | Browser · interactive **2D** | Free | Visualize generator/discriminator competition during GAN training | Change the target distribution |
| [Transformer Explainer](https://poloclub.github.io/transformer-explainer/) | Browser · interactive diagrams | Free | Inspect tokenization, attention and next-token probabilities | Change a prompt and watch token predictions |
| [Machine Learning Crash Course](https://developers.google.com/machine-learning/crash-course) | Browser · exercises and visualizations | Free | Connect ML intuition to practical concepts and interactive exercises | Train a simple classifier |

**Learning sequence:** **Playground → CNN Explainer → Embedding Projector → GAN Lab → Transformer Explainer.** These tools explain different kinds of models; they are not interchangeable.

---

## 04 · Computer Vision & AI That Sees

*Train perception on your own images, not only on example datasets.*

| Platform | Format | Access | What you can do | First experiment |
|---|---|---|---|---|
| ⭐ [Google Teachable Machine](https://teachablemachine.withgoogle.com/) | Browser · webcam/images/sound/pose | Free | Create image, audio and pose classification models without writing code | Recognize three desk objects |
| [Roboflow Vision AI Playground](https://playground.roboflow.com/) | Browser · image-based vision demos | Free-to-try models; product tiers may differ | Compare detection, segmentation, OCR, depth and other vision tasks | Compare two object detectors on the same image |
| [Google Quick, Draw!](https://quickdraw.withgoogle.com/) | Browser · interactive drawing | Free | See a classifier guess what you're drawing | Draw the same object in five styles |
| [MediaPipe Studio](https://mediapipe-studio.webapps.google.com/) | Browser · AI demos | Free demos, subject to availability | Try supported perception tasks such as object detection and image classification | Compare landmark/vision model behavior |
| [Hugging Face Spaces](https://huggingface.co/spaces) | Browser · community demos | Mixed: many free demos; limits vary | Experiment with public computer-vision, audio and multimodal AI demos | Test a segmentation or image-captioning Space |

**Privacy reminder:** Check whether an uploaded photo or video is processed locally, sent to a service, retained, or made public. Avoid uploading private images just to test a model.

---

## 05 · Robotics, Autonomous Agents & Physical AI

*Build the mind, body, and world of a machine.*

| Platform | Format | Access | What you can do | First experiment |
|---|---|---|---|---|
| ⭐ [RobotForge](https://robotforge.org/) | Browser · **3D physics** | Free; open source | Use a robotics simulator, URDF viewer, editor, browser CAD and guided tracks | Move a robot arm and inspect its joints |
| [Rocksi](https://rocksi.net/) | Browser · **3D robot arms** | Free; no registration | Program virtual industrial arms with block-based controls | Pick-and-place motion sequence |
| [MuJoCo Live](https://live.mujoco.org/) | Browser · **3D physics viewer** | Free/open-source ecosystem | Inspect articulated bodies and contact dynamics; use local MuJoCo/Python for advanced control and RL | Alter a robot pose and observe dynamics |
| [Webots](https://cyberbotics.com/) | Desktop · **3D physics**; some online demos | Free and open source | Program mobile robots, cameras, LiDAR and simulated environments with Python/ROS | Obstacle-avoiding mobile robot |
| [Gazebo Sim](https://gazebosim.org/) | Desktop · **3D physics** | Free and open source | Build sensor-rich robotics environments with ROS integrations | Navigation with a simulated LiDAR |
| [CARLA](https://carla.org/) | Desktop · **3D autonomous driving** | Free and open source | Simulate traffic, vehicles, cameras, LiDAR, weather and Python-controlled scenarios | Autonomous braking scenario |
| [Unity ML-Agents](https://github.com/Unity-Technologies/ml-agents) | Desktop · **3D + reinforcement learning** | Open-source toolkit; Unity terms apply | Train virtual agents with reward signals and Python ML | Agent learns to reach a target |
| [Open Roberta Lab](https://lab.open-roberta.org/) | Browser · block coding + selected simulations | Free/open source | Program educational robot models and explore simulation tasks | Program a virtual robot route |

**Distinction:** A **3D viewer** is not automatically a complete online AI-training environment. For instance, MuJoCo Live visualizes physics in the browser, while full reinforcement-learning pipelines typically run in local Python environments. Webots, Gazebo, CARLA and Unity ML-Agents are most useful when installed.

**Caution:** Some old links associated with RobotBenchmark have changed ownership or behavior; they are intentionally excluded from this collection.

---

## 06 · Physics, Engineering & Real-World Systems

*Make abstract laws visible, then test the model's limits.*

| Platform | Format | Access | What you can do | First experiment |
|---|---|---|---|---|
| [PhET Interactive Simulations](https://phet.colorado.edu/) | Browser · mostly **2D** interactive | Free educational simulations | Experiment with energy, electricity, forces, chemistry and waves | Build a circuit and measure voltage |
| [GeoGebra 3D](https://www.geogebra.org/3d) | Browser · **3D** | Free non-commercial use | Explore geometry, transformations and mathematical models | Rotate a 3D vector field construction |
| [Falstad Circuit Simulator](https://www.falstad.com/circuit/) | Browser · animated **2D** | Free | Explore how circuit parameters affect voltage and current | Build a resonant circuit |
| [Curvo Studio](https://curvostudio.com/en) | Browser · interactive **3D** engineering models | Free | Change electric-machine and component parameters; view graphs | Explore transformer and motor behavior |
| [Onshape](https://www.onshape.com/) | Browser · **3D CAD** | Free non-commercial/public-document plan, terms apply | Design mechanical parts and assemblies | Model a simple robotic gripper |
| [FreeCAD](https://www.freecad.org/) | Desktop · **3D CAD** | Free/open source | Design parametric mechanical structures for fabrication | Design a sensor mounting bracket |

**Real-world note:** Educational physics demos trade detail for clarity. For engineering validation, cross-check with component data sheets, professional simulation and real measurements.

---

## 07 · Generative Art, Creative Technology & Interactive Worlds

*Where creativity meets intelligence, code becomes a material.*

| Platform | Format | Access | Creative direction |
|---|---|---|---|
| [p5.js Web Editor](https://editor.p5js.org/) | Browser · 2D/**3D** | Free/open source | Generative art, particles, procedural design, interaction |
| [Three.js](https://threejs.org/) | Browser · **3D** library + examples | Free/open source | WebGL worlds, visual storytelling, interactive simulations |
| [ShaderToy](https://www.shadertoy.com/) | Browser · GPU shader graphics | Free public exploration; account/features vary | Procedural environments, light, textures, motion |
| [Spline](https://spline.design/) | Browser · **3D** design | Freemium | Interactive 3D scenes and web experiences |
| [Blender](https://www.blender.org/) | Desktop · **3D** creation | Free/open source | Animation, procedural geometry, rendering, physics and assets |

**Try this:** Generate an artistic robot body in Blender or a browser 3D editor, prototype its mechanics in RobotForge or Webots, and visualize sensor data with Python or p5.js. The pipeline requires manual export, compatible file formats and integration code.

---

## 08 · Start Here: Best Tools by Goal

| You want to… | Start with | Then explore |
|---|---|---|
| **See Arduino in 3D** | [Learn Arduino 3D](https://learn-arduino-red.vercel.app/) | [Wokwi](https://wokwi.com/) |
| **Build a real embedded project virtually** | [Wokwi](https://wokwi.com/) | [Mokxi](https://mokxi.com/) |
| **See live current flow** | [Falstad](https://www.falstad.com/circuit/) | [Curvo Studio](https://curvostudio.com/en) |
| **Learn Python through movement** | [GlowScript](https://www.glowscript.org/) | [Google Colab](https://colab.research.google.com/) |
| **Create a 3D world in code** | [Three.js Editor](https://threejs.org/editor/) | [p5.js](https://editor.p5js.org/) |
| **Understand neural networks visually** | [TensorFlow Playground](https://playground.tensorflow.org/) | [CNN Explainer](https://poloclub.github.io/cnn-explainer/) |
| **Train an AI with a webcam** | [Teachable Machine](https://teachablemachine.withgoogle.com/) | [Roboflow Playground](https://playground.roboflow.com/) |
| **Control an industrial robot in 3D** | [Rocksi](https://rocksi.net/) | [RobotForge](https://robotforge.org/) |
| **Simulate autonomous robots with Python** | [Webots](https://cyberbotics.com/) | [Gazebo](https://gazebosim.org/) |
| **Explore AI learning in a 3D world** | [Unity ML-Agents](https://github.com/Unity-Technologies/ml-agents) | [MuJoCo](https://mujoco.org/) |
| **Simulate self-driving cars** | [CARLA](https://carla.org/) | [Webots](https://cyberbotics.com/) |

---

## 09 · Seven Cross-Disciplinary Projects

These are **creative project ideas**, not claims that all listed platforms automatically integrate.

### Project A: The Intelligent Plant Guardian 🌱

**Combine:** Arduino + electronics + Python + AI + design.

1. Build a virtual moisture monitor in [Learn Arduino 3D](https://learn-arduino-red.vercel.app/).
2. Rebuild or extend the controller logic in [Wokwi](https://wokwi.com/).
3. Plot simulated humidity history in [Google Colab](https://colab.research.google.com/).
4. Train a simple anomaly classifier and evaluate false alerts.
5. Transfer to physical sensors only after checking voltage and wiring.

**What you learn:** sensing, control loops, signal processing, debugging and the gap between simulation and reality.

### Project B: Robot With Reflexes 🤖

**Combine:** 3D robotics + geometry + control algorithms.

1. Explore joints and robot configuration in [RobotForge](https://robotforge.org/).
2. Create a safe pick-and-place sequence in [Rocksi](https://rocksi.net/).
3. Prototype a distance-based obstacle stop rule.
4. Recreate a wheeled robot with a virtual range sensor in [Webots](https://cyberbotics.com/).
5. Compare a hand-written controller with a learned policy.

**Important:** A threshold-based stop controller is **not machine learning**. It becomes an AI-learning experiment only when a model is actually trained and evaluated.

### Project C: A Camera That Understands Objects 👁️

**Combine:** computer vision + classification + interactive feedback.

1. Train classes for a pen, cup and key in [Teachable Machine](https://teachablemachine.withgoogle.com/).
2. Test under different lighting and backgrounds.
3. Compare general-purpose object detectors in [Roboflow Playground](https://playground.roboflow.com/).
4. Build a simple on-screen dashboard in [p5.js](https://editor.p5js.org/).

**What you learn:** datasets, generalization, accuracy, bias and the limitations of recognition.

### Project D: A Neural Network Observatory 🧠

**Combine:** machine learning + visual explanation + art.

1. Classify spirals in [TensorFlow Playground](https://playground.tensorflow.org/).
2. Inspect feature extraction in [CNN Explainer](https://poloclub.github.io/cnn-explainer/).
3. Rotate embedding clusters in [Embedding Projector](https://projector.tensorflow.org/).
4. Create an artistic representation of changing decision boundaries using [p5.js](https://editor.p5js.org/).

**What you learn:** representation, optimization, uncertainty and interpretability.

### Project E: Self-Driving Mini-City 🚗

**Combine:** Python + 3D urban physics + autonomous decisions.

1. Create a simple road scene in [CARLA](https://carla.org/).
2. Add virtual cameras or LiDAR.
3. Implement a conservative rule-based emergency brake.
4. Test scenarios with pedestrians, rain and different lighting.
5. Compare perception errors and braking distances.

**What you learn:** perception, control, safety constraints and why simulated success does not imply road safety.

### Project F: The Physics-to-Python Studio 🔬

**Combine:** mechanics + mathematical thinking + 3D visualization.

1. Try a force or motion experiment in [PhET](https://phet.colorado.edu/).
2. Reproduce the equations in [Google Colab](https://colab.research.google.com/).
3. Animate motion using [GlowScript](https://www.glowscript.org/).
4. Vary mass, friction and initial velocity.
5. Record where simplified mathematical assumptions stop matching physical behavior.

### Project G: A Robot That Learns by Reward 🎯

**Combine:** 3D simulation + Python + reinforcement learning.

1. Create a minimal target-reaching agent in [Unity ML-Agents](https://github.com/Unity-Technologies/ml-agents).
2. Define observations, actions, rewards and episode termination.
3. Compare random actions against a trained policy.
4. Alter the environment to test robustness and overfitting.
5. Visualize success rate and reward history in Python.

**What you learn:** state/action spaces, reinforcement learning, reward design and transfer limitations.

---

## 10 · A Four-Week Creative Intelligence Sprint

| Week | Theme | Deliverable |
|---|---|---|
| **1** | **Electronics & systems**: Learn Arduino 3D, Falstad, Wokwi | A virtual sensor and actuator circuit |
| **2** | **Python & visualization**: GlowScript, Colab, GeoGebra 3D | A moving 3D physics experiment with measurable parameters |
| **3** | **AI & perception**: TensorFlow Playground, Teachable Machine, Roboflow | A tested object-recognition demo with failure cases |
| **4** | **Embodied intelligence**: RobotForge, Rocksi, Webots / Unity ML-Agents | A virtual robot that senses and acts in a simulated environment |

**Capstone:** Build a small *digital twin*: a conceptual link between a physical process, its sensors, a controller, a virtual model, and an AI component. Describe which parts are simulated, which are measured, and which are only visualized.

---

## 11 · What “Free” Really Means in 2026

Before investing time in a tool, check:

1. **Private versus public projects:** Wokwi's community plan focuses on public projects; other services may restrict private storage.
2. **Cloud limits:** Free GPU/CPU availability in Google Colab and hosted AI demos is not guaranteed.
3. **Commercial restrictions:** GeoGebra free use targets non-commercial contexts; CAD and design tools can have separate commercial licenses.
4. **3D versus true simulation:** A visually realistic model may lack real electrical, sensor or contact physics.
5. **Browser versus desktop:** CARLA, Webots, Gazebo and Unity ML-Agents require substantial local setup for their full workflows.
6. **Device safety:** Start with simulated or low-voltage circuits; never treat a browser circuit as proof that real wiring is safe.
7. **Privacy:** Only upload images, videos, designs and datasets you have permission to use.

---

## 12 · Verification & Official Starting Points

Selected official or primary pages supporting this guide:

- [Learn Arduino 3D — public course](https://learn-arduino-red.vercel.app/) · 16 guided lessons.
- [RobotForge](https://robotforge.org/) · Free browser robotics simulator, URDF viewer and curriculum.
- [Rocksi](https://rocksi.net/) · Free browser-based 3D robot-block simulator.
- [Wokwi documentation](https://docs.wokwi.com/) and [Wokwi pricing](https://wokwi.com/pricing) · Embedded simulation and community limits.
- [Mokxi](https://mokxi.com/) · Free editor with paid project/export features.
- [GlowScript](https://www.glowscript.org/) · Web VPython in the browser.
- [Roboflow Playground](https://playground.roboflow.com/) · Interactive vision model comparisons.
- [Teachable Machine](https://teachablemachine.withgoogle.com/) · Browser-based model training.
- [CARLA](https://carla.org/) · Open-source autonomous-driving simulator.
- [Webots](https://cyberbotics.com/) · Robotics simulation.
- [GeoGebra licensing and access](https://www.geogebra.org/) · Free non-commercial educational use.
- [p5.js Web Editor](https://editor.p5js.org/about) · Free browser creative coding.

---

## Manifesto · Create, Understand, Experiment

**Creativity** asks: *What could exist?*  
**Intelligence** asks: *How could it perceive and decide?*  
**Simulation** asks: *What happens when it moves?*  
**Engineering** asks: *Will it work outside the screen?*

The most rewarding learning happens when these questions meet.

**Think in systems. Learn by seeing. Build by experimenting.**

*Curated by **0xAllow** · 2026 edition*
