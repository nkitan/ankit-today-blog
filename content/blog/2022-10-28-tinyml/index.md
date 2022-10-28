+++
title = "Going Small: TinyML"
date = 2022-10-28
+++
#### - Ankit Das
### Introduction
The field of deep learning has always been associated with having complex mathematical equations, vast algorithms and a large set of data. The high amount of complexity associated with deep learning has forced engineers to utilize vast computing power spread across vast servers and high performance computers. Most state-of-the-art machine learning algorithms require a large amount of processing power and power consumption to infer knowledge. This limits the use cases of machine learning, more specifically deep learning and allows development of very niche applications. To allow machine learning to truly impact our lives and to broaden its reach, there is a need to perform machine learning on small, low power devices. Fulfilment of this need is the goal of TinyML or Tiny Machine Learning.

### What is TinyML
Machine learning is technology that utilizes demanding mathematical algorithms like k-means, interconnected compute units to make neural networks etc. TinyML aims to implement these demanding algorithms on cheap, power efficient devices which can be run on battery power enabling these applications to be remote and mobile.

### Why TinyML
The objective of TinyML is to bring machine learning to a state where portable devices can be used to perform machine learning tasks while being performant enough to perform real-time inferences. Bringing machine learning to such a state will open a portal to various real world and useful applications such as **AI assisted vision, gesture recognition, audio detecion, object recognition on personal devices, personal assistants outside of phones, autonomous drones, offline smart appliances** etc. which will ultimately benefit the human race in multiple ways. This technology can also be used to develop low-power devices for physical exploratory analysis using robots which will provide great insights and knowledge. The use cases of this technology are virtually endless,

### Processes Involved
Implementation of a complicated mathematical model that required tons of computing and storage power on a low-cost, low-power device is a task of great magnitude. This can not be achieved simply by improving a single aspect of the process, instead, one needs to put extraordinary effort into multiple disciplines requiring optimization at each step. One must maximise the output for all involved fields including hardware and software. This field has been progressing at a fast rate in recent years thanks to the maturing of both underlying hardware and software platforms

### Features of TinyML
* Data Security - Since data is not shared with other devices, data security is maintained.
* Efficiency - Since processing is done on low-power devices instead of huge servers, costs are reduced.
* No connection dependencies - The devices can function without active internet connections which makes them independent.
* Latency - Since there is no data transfer, the transfer latency is non-existent thus improving the run time.

### Economic Value of TinyML
According to a independent study by ABI research, around **2.5 billion devices** using TinyML will reach the market by 2030 and might reach around **70 billion dollars** in economic value in the next 5 years

### Hardware used for TinyML
The most impressive part about TinyML is its abiity to peform tasks on unimpressive hardware. The father of TinyML, Pete Warden says that TinyML should be able to run on less than 1mW of power which allows it to be run with a standard coin battery with a lifetime of months. This kind of requirement eliminates the possibility of using GPUs, ASICs or microprocessers. Instead, microcontrollers like the ATmega 328p or Digital Signal Processors must be used with a few Kbs of RAM and clock speeds of a few MHz

### Software Used for TinyML
The most famous and widely used TinyML framework is **Tensorflow Lite** just like its machine learning counterpart. Tensorflow Lite provides tensorflow models that can be run on embedded devices using microcontrollers with small binaries. Other tools include **CoreML** which is a machine learning library from Apple and **PyTorch Mobile** which is a mobile version of the popular PyTorch deep learning library.
{{ image(src="tfworkflow.png", alt="Tensorflow Lite Workflow") }} 

### Examples of TinyML in the real world
an example of TinyML in the real world is the audio wake detection model used on android phones. Modern android phones can turn on when they hear "Ok Google". This is implemented using a TinyML model sized at **14Kb** which has been implemented to run on a DSP (Digital Signal Processor). Audio based mosquito detection is an interesting application of TinyML.

{{ image(src="okgoogle.png", alt="Ok Google!" 100x100) }} 
{{ image(src="audioword.png", alt="Audio Detection") }} 


### References

1. [What is TinyML, and why does it matter? - Jair Ribiero](https://medium.com/tech-cult-heartbeat/what-is-tinyml-and-why-does-it-matter-f5b164766876)
2. [What is TinyML - Jake Hertz](https://www.allaboutcircuits.com/technical-articles/what-is-tinyml/)
3. [Google Scholar - TinyML](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C5&q=tinyML&btnG=)