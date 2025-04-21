# pso-image
Image Segmentation Using PSO
Table of Content
Flight Fare Prediction:
Table of Content
Overview
What is this project about?
🔑 Prerequisites
📖 Data Preprocessing
🚀  Installation
💡 How to Run
Results
Directory Tree
Technologies Used
Future Scope
👏 And it's done!
🙋 Citation
❤️ Owner
👀 License
Overview
This is a Flask web app which shows the images after segmenting using PSO.

What is this project about?
Particle Swarm Optimization (PSO) is a popular optimization technique inspired by the collective behavior of bird flocking or fish schooling. It is commonly used to solve optimization problems in various fields, including image processing.

Image segmentation is the process of partitioning an image into multiple segments or regions based on certain criteria, such as color, texture, or intensity. It is a fundamental task in computer vision, and it has various applications, including object recognition, image analysis, and medical imaging.

PSO can be used for image segmentation because it is a powerful optimization technique that can find the optimal segmentation parameters by searching the solution space efficiently. PSO-based image segmentation algorithms typically define the fitness function based on the similarity of the segmented



Velocity Vector Update Equation:



Position Vector Update Equation:

x
id
(
t
+
1
)
=
x
id
(
t
)
+
v
id
(
t
+
1
)

Inertia Weight:

w
=
w
m
a
x
−
w
m
a
x
−
w
m
i
n
i
t
e
r
m
a
x
×
i
t
e
r

🔑 Prerequisites
All the dependencies and required libraries are included in the file requirements.txt  See here

📖 Data Preprocessing
Data pre-processing is an important step for the creation of a machine learning model. Initially, data may not be clean or in the required format for the model which can cause misleading outcomes. In pre-processing of data, we transform data into our required format. It is used to deal with noises, duplicates, and missing values of the dataset. Data pre-processing has the activities like importing datasets, splitting datasets, attribute scaling, etc. Preprocessing of data is required for improving the accuracy of the model.

🚀  Installation
The Code is written in Python 3.9. If you don’t have Python installed you can find it here. If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after cloning the repository:

Clone the repo
git clone https://github.com/sanyam-katoch10/pso-image.git
Change your directory to the cloned repo
cd iso-image
Now, run the following command in your Terminal/Command Prompt to install the libraries required
python3 -m venv my_env

my_env\Scripts\activate 

pip3 install -r requirements.txt
💡 How to Run
Open terminal. Go into the cloned project directory and type the following command:

python3 app.py
Results
Color Image




Gray Scale Image



Directory Tree
.
├── app.py
├── Dockerfile
├── LICENSE
├── pso.py
├── Readme.md
├── requirements.txt
├── static
│   ├── segmented_image.jpg
│   └── temp.jpg
├── templates
│   ├── index.html
│   └── result.html
└── tests
    ├── image.jpg
    ├── lena.png
    └── tst.jpg
Technologies Used
  

Future Scope
To run it in more speed
Optimize Flask app.py
Optimize this Image Segmentation with different algorithm
Owner
Made with   by Team Roxx
