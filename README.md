# Classification-Of-Skin-Lesions-By-Topological-Data-AnalysisAlongside-With-Neural-Network

[Paper Link](https://www.techrxiv.org/articles/preprint/Classification_Of_Skin_Lesions_By_Topological_Data_Analysis_Alongside_With_Neural_Network/12628088)


Authors:
* Naiereh Elyasi*
* Mehdi Hosseini Moghadam**

\* Department of math and computer Sciences, Kharazmi University, Taleghani street, Tehran, Iran

** Department of Engineering, Kharazmi University, Taleghani street, Tehran, Iran

![TDA Result](./Image/Best.PNG?raw=true "Title")

**This notebook  provides the supplementary code for the above article**

# Abstract               

In this paper we use TDA mapper alongside with deep convolutional neural networks in the classification of 7 major skin diseases. First we apply kepler mapper with neural network as one of its filter steps to classify the dataset HAM10000. Mapper visualizes the classification result by a simplicial complex, where neural network can not do this alone, but as a filter step neural network helps to classify data better. Furthermore we apply TDA mapper and persistent homology to understand the weights of layers of mobilenet network in different training epochs of HAM10000. Also we use persistent diagrams to visualize the results of analysis of layers of mobilenet network.


# Data

In this paper we have used the data set HAM10000 .There are a total of 10015 dermatoscopic images of skinlesions labeled with their respective types of skin diseases.The images in the data set are separated into the followingseven types of skin diseases:

* Actinic keratosis is considered to be a noncancerous(benign) type of skin diseases. However, if left un-treated, it usually develops into squamous cell carci-noma (SCC).

* Basal cell carcinoma is a cancerous type of skin lesionthat develops in the basal cell layer located in the lowerpart of the epidermis. It is the most common type ofskin cancer accounting for 80 percent of all cases.

* Benign keratosis is a noncancerous and slow-growingtype of skin diseases. They can be left untreated asthey are typically harmless

* Dermatofibromas are also noncancerous and usuallyharmless, thus no treatment is required. It is com-monly found pinkish in color and appears like a roundbump.

* Melanoma is a type of malignant skin cancer that orig-inated from melanocytes, cells that are responsible forthe pigment of your skin.

* Melanocytic nevi are a benign type of melanocytic tu-mor. Patients with melanocytic nevi are considered tobe at a higher risk of melanoma.

* Vascular lesions are composed of a wide range of skinlesion including cherry angiomas, angiokeratomas, andpyogenic granulomas. They are similarly character-ized as being red or purple in color and are usually araised bump.

![Skin Cancers](./Image/lesions.png?raw=true "Title")
