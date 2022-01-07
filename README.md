# Avila_Bible_ESILV

<h2>
  Introduction
  </h2>

<ln>
  
  Avila bible is one of the largest and most spectacular codices in the Spanish National Library. The ornamentation features contrasting Italian and Spanish styles. The Italian decoration depicts the authors of the books and contains numerous capitals, either illuminated or coloured in red, blue, yellow and dark green on lighter backgrounds in the same tone. The colours change in the Spanish decoration, which also has exceptional intertwined initials and whole-page figurative illustrations of subjects such as Noah's Ark, the symbols of the evangelists and scenes from the life of Christ.
  </ln>
  
  <h2>
  Data Description
  </h2>
  
  <ln>
    The Avila data set has been extracted from 800 images of the the "Avila Bible", a giant Latin copy of the whole Bible produced during the XII century between Italy and Spain.  
  
The palaeographic analysis performed on the Avila Bible established that the manuscript contains pages written by 12 different scribe monks throughout the years. The goal of this analysis is to identify which scribe is the author of a certain pattern based on the available attributes. This makes the task a classification problem in which the copyist monk constitutes the class to predict.
  
The prediction task consists in associating each pattern to one of the 12 copyists (labeled as: A, B, C, D, E, F, G, H, I, W, X, Y).
The data have has been normalized, by using the Z-normalization method, and divided in two data sets: a training set containing 10430 samples, and a test set  containing the 10437 samples.

To shorten computation times and to ease the illustation of the behavior of certain algorithms, we restrict our analysis to the patterns associated to 6 out of the 12 scribes. According to the available documentation, the attributes of dataset have already been standardized. A short description of the available attributes follows.
  
  Class distribution (training set)
A: 4286
B: 5  
C: 103 
D: 352 
E: 1095 
F: 1961 
G: 446 
H: 519
I: 831
W: 44
X: 522 
Y: 266

ATTRIBUTE DESCRIPTION

ID      Name    
F1       intercolumnar distance 
F2       upper margin 
F3       lower margin 
F4       exploitation 
F5       row number 
F6       modular ratio 
F7       interlinear spacing 
F8       weight 
F9       peak number 
F10     modular ratio/ interlinear spacing
Class: A, B, C, D, E, F, G, H, I, W, X, Y
  <h2>
    Resources
  </h2>
  
  <ln>
    https://archive.ics.uci.edu/ml/datasets/Avila
  </ln>
  
  <h2>
    Citation
  </h2>
  
  <ln>
    
  To refer to the Avila data set, please cite the following paper:
    
  C. De Stefano, M. Maniaci, F. Fontanella, A. Scotto di Freca, Reliable writer identification in medieval manuscripts through page layout features: The "Avila" Bible case, Engineering Applications of Artificial Intelligence, Volume 72, 2018, pp. 99-110.

  </ln>
