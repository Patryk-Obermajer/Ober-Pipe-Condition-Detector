<h1>Ober Pipe Condition Classifier</h1>

<h2>Introduction</h2>

We are building a deep learning CNN algorithm for drainage pipe condition classification. We are training this system on manually labelled imagery from drainage CCTV - hours and hours of it.

<h2>Aims</h2>

We are trying to build a model, which will correctly classify drainage condition from CCTV footage without human input.

<h2>Methodology</h2>

We collect and label the CCTV survey imagery, group the images into categories of respective condtion, and load it into Keras/TensorFlow, CNN sequential model and train the system from scratch. We then compile our model and run the algo on a set of previously unseen imagery. We then manually correct the output and train a new model on a larger dataset. It's an iterative process.

<h2>Conclusions</h2>

We completed the first phase of the project and the resutls are satisfactory for some pipe condition scenarios - the model performs well on pipe with water and is rubbish at distinguishing if the pipe is damaged, filled with rubbish/rubble or completely collapsed. We are going to need...

![image](https://github.com/Patryk-Obermajer/Ober-Pipe-Condition-Detector/assets/69651910/3d6c30d0-d4c6-43e7-ba15-7d2f1d9c4f35)
