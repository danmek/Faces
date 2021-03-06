# Design Document
This project looks at two published machine learning models: a convolutional neural network (CNN) and a vision transformers model. I decided to use them because they represent the most accurate models to this date used for facial recognition. I designed the Google Colab notebook leveraging that code to test a hypothesis and better understand some of the differences between these models. I then decided to design a website to showcase the experiment and main findings. Technically, I wasn't prepared to design my own python implementation of a neural network, but I was able to understand enough to load it into my notebook and play with it to draw some conclusions. Similarly for the website, I decided to leverage a pre-existing template to avoid reinventingthe wheel. It still require a lot of tweaking and adaptation to get it to its final form.
In terms of ethical decisions, one of the main criticisms of facial recognition algorithms is that they perpetuate existing biases in society. While I wasn't training or testing these models, I tried to take into account those known biases and worked with faces of different skin colors and features, such as hairstyle and hair length. I also primarily worked with women's faces, although I benchmarked them agains male faces and they gave similar results for the same experiments. I decided to share both the manipulations, experiments and results in full transparency, with a public GitHub repository, to make sure it is available to be challenged, critiqued and improved.

## Technical Decisions
* Design challenge(s) and how I addressed them

Initially, I wanted to build my website from scratch, but my limited knowledge and time constraints motivated me to look for a more efficient solution in using (and crediting) a pre-existing website design template. I also struggled to design the right experiment using the FaceNet and Transformers models, I struggled with some of the image manipulations and with understanding the different cells and components of the code to get it to do what I wanted it to do.

* New tools and technology used

I learned to use and implement several new tools and technology, including Google Colab, Canva (for image creation), PhotoShop (for image manipulation). I taught myself more complex implementations of HTML, CSS and JavaScript for the web design portion of the project. I also created a GitHub repository to make the website publicly available.

## Ethical Decisions
One of my favorite classes in graduate school has been "PSY 1406: Biological and Artificial Visual Systems". The class focused on learning about human perception, and how AI systems emulate, and sometimes even surpass, human vision capabilities. Among the cutting-edge research in the field of machine vision, we studied two types of model architectures, convolutional neural networks, and vision transformers. Some ethical questions that came up for me in some of their applications for face recognition were around which model was more biased, what it means to be blind to differences, and whether models get more or less biased as they evolve. Some of the answers to these questions remain, but it looks like the Vision Transformers network is more biased to images of long-haired women.

### Intended users
Direct users of this project include students and vision researchers, both in the fields of biologival and artificial vision. This can also be relevant research for companies using computer vision for face recognition.
Indirect users would be those whose faces are being recognized using this technology, the public in general, since facial recognition is becoming more and more commonplace.

### User impact with scale
* Misuse of project features

Some of the project features, such as the display of manipulated images of celebrities for the experiments, could be used for making fun of them, since the resulting images are odd-looking to the human eye. There are also implications in how companies use facial recognition algorithms for law enforcement, targeting and discrimination. These findings at scale can help influence how this technology evolves and becomes more pervasive.
