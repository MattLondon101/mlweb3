# mlweb3

**This app exhibits the high accuracy and reliability of the Sequential Model CNN deployed as a web app with Flask and Python**  

Dependencies:  
keras==2.3.1  
tensorflow==1.14.0  
scikit-image==0.17.2  
h5py==2.10.0  


Directions:  
Create an empty directory called uploads in mlweb3.    
Current Labels are: 'airplane', 'automobile', 'bird', 'cat', 'deer', 'dog', 'frog', 'horse', 'ship'  
Place images of these kinds into mlweb3/uploads.  

In Linux Bash:  
```
cd Flask-ML-Web-App
export FLASK_APP=path_to/Flask-ML-Web-App/mlweb3/__init__.py
export FLASK_ENV=development
flask run
```

Output will direct you to localhost http://127.0.0.1:5000/  

Browse to mlweb3/uploads and upload your image.  
The algorithm will classify the image as one of the labels with ~90% confidence.  


Trained via Sequential Model CNN with [CIFAR-10 dataset](https://www.cs.toronto.edu/~kriz/cifar.html).
