
# Burger / Samosa Classifier

This was built with PyTorch/FastAI for the Machine Learning part and Flask as a Webserver. 
For containerization and easy deployment I used Docker.
The dataset used for building the model is Food-101 Dataset which is provided by FastAI
it contains many images of food and i choose the images of Samosa and Burger for building a CNN Classifier.



## Run Model locally ### ( make sure you have installed all the packages)

Clone the project

```bash
  git clone https://github.com/ManthanShettigar/SamosaBurger-CNN-Classifier.git
```

Go to the project directory

```bash
  cd my-project
```

Run model via jupyter-notebook

```bash
  jupyer-notebook
```

  
## Deployment

Command to launch the container:
```bash
docker build -t cburger_samosa_classifier . && docker run --rm -it -p 5000:5000 burger_samosa_classifier

```

  
## Screenshots

![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)

  
