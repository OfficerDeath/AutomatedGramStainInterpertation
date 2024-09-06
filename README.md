#Automated Gram Stain Interpertation

Use the ipynb file to run in google colab. 
![](https://private-user-images.githubusercontent.com/163483028/364887424-7309adfa-7561-43bf-90ab-d692df463064.jpg)
The sepsis diagnosis process relies on a large culturing period and high concentration of bacteria that leave patients waiting for days no closer to regaining their health. This research attempts to analyze the effectiveness of using an automated microscope and neural network to diagnose sepsis before culturing samples. In order to evaluate this method, I constructed an automated microscope and created a training set of images. The images were collected from Gram-stained slides constructed with horse red blood cells and either E.Coli K12 or Stappcoccous Epidermis. These images were used to create a Neural network capable of differentiating between images with only blood cells and images with bacteria and blood cells. The effectiveness of this model was be measured using a separate set of images reserved from the original set. Using the results, the lowest concentration sample that can reliably return an accurate test was be calculated. This lowest reliable concentration combined with the running time of a full slide scan allowed the efficacy of the use of this method to diagnose sepsis to be determined. Training data has be released so that other machine learning models' efficacy can also be tested by future researchers. The model was able to accurately diagnosis sepsis with a 99.90% confidence interval at pre-culture concentrations
