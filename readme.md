# Artificial Intelligence: From Concepts to Code

Nottingham Trent University Global Summer School, 29 June to 10 July 2026.

This repository contains the Jupyter notebooks and code shared during the course.
New material will be added each day as the course progresses.

## About the course

Artificial intelligence is transforming industries worldwide, from healthcare to finance, from creative industries to scientific research.
At the heart of this revolution lies deep learning, artificial neural networks that learn complex patterns from data.

This ten-day course combines conceptual understanding with practical skills.
You will explore how artificial neural networks work, from individual neurons to the deep architectures that power large language models like ChatGPT.
Through hands-on coding in Python, you will build and train models on real datasets and develop the confidence to apply these techniques to new problems.
By the end of the course, you will understand the principles behind today's most powerful AI applications and have practical experience building and training neural networks yourself.

The course carries 10 UK credit points and is assessed on a pass/fail basis.

## Who the course is for

The course is designed to be accessible to students from diverse backgrounds.
High-school level mathematics (functions and basic algebra) is sufficient preparation.
Programming experience is helpful but not required, and coding concepts are introduced in an accessible way suitable for beginners.

## Course content

### The AI revolution

We begin with an overview of contemporary AI technologies and their capabilities.
We trace the journey from AI's origins in the 1950s through periods of optimism and setbacks to today's breakthroughs.
The central role of artificial neural networks and deep learning in the current state of the art is explained, along with a look at the societal implications of these developments.

### Foundations of neural networks

We explain how artificial neural networks work, covering artificial neurons, activation functions, and how networks learn through backpropagation.
We explore the mathematical principles behind training and the biological inspiration for the architecture.
Participants will implement a neural network from scratch in Python using NumPy, which builds a direct understanding of what is happening inside these models before we move to higher-level tools.

### Multilayer networks for classification

We build and train multilayer perceptrons for classification tasks using PyTorch.
Topics include loss functions, optimisers, overfitting, and regularisation techniques that improve how well a trained model generalises to new data.

### Convolutional neural networks

We introduce convolutional neural networks and their transformative impact on image recognition.
Participants will work with real-world image datasets and learn how these networks automatically detect features, edges, and patterns in visual data without being explicitly told what to look for.

### Large language models and transformers

We explore the transformer architecture that underlies modern large language models such as ChatGPT.
We examine attention mechanisms and how these models process and generate human language, enabling applications from translation to content generation to code assistance.
Participants will work with pre-trained models using the Hugging Face library.

### Real-world applications

We take a comprehensive look at current and emerging AI applications across industries including healthcare, finance, creative arts, and scientific research.
We consider responsible deployment, societal impacts, and future directions in the field.

## Assessment

Assessment is by a portfolio of practical coding exercises and a final project presentation.
Participants will submit documented Python code demonstrating their ability to build, train, and evaluate a neural network, along with a brief written reflection on their approach and results.
The final component is a short in-class presentation on the last day of the course explaining the project and findings.

## Further reading

A companion course book covering deep learning with Python in depth is available at:

https://courses.mjandrews.org/deep-learning-python/

This resource goes into considerably more detail on all the topics covered in the course and is a useful reference throughout and after the two weeks.


## Software

A guide on the installation and set-up of the software that we will use is available [here](software.md).

Two helper Python packages for this course can be installed with the following commands:
```python
pip install git+https://github.com/mark-andrews/nettle.git
pip install git+https://github.com/mark-andrews/nettlelang.git
```

## Timetable

### Week 1

| Date | Session |
|------|---------|
| Monday, 29 June | Introduction |
| Tuesday, 30 June AM | The history of artificial intelligence, from the 1950s to the present |
| Tuesday, 30 June PM | Setting up Python |
| Wednesday, 1 July AM | Introduction to numeric programming in Python, part one |
| Wednesday, 1 July PM | Introduction to numeric programming in Python, part two |
| Thursday, 2 July AM | Building a neural network with NumPy, part one |
| Thursday, 2 July PM | Building a neural network with NumPy, part two |
| Friday, 3 July AM | Training neural networks with PyTorch, part one |
| Friday, 3 July PM | Training neural networks with PyTorch, part two |

### Week 2

| Date | Session |
|------|---------|
| Monday, 6 July AM | Multilayer perceptrons, part one |
| Monday, 6 July PM | Multilayer perceptrons, part two |
| Tuesday, 7 July AM | Convolutional neural networks, part one |
| Tuesday, 7 July PM | Convolutional neural networks, part two |
| Wednesday, 8 July AM | Language models and transformers, part one |
| Wednesday, 8 July PM | Language models and transformers, part two |
| Thursday, 9 July AM | Large language models and the GPT architecture |
| Thursday, 9 July PM | Using pre-trained models with Hugging Face |
| Friday, 10 July | Presentations |
