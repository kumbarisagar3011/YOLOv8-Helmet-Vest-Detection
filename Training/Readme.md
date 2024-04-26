Training
Download the dataset from the link given in this repo.
I have stored the dataset in a folder called css-data, you can change the name and give its location as a INPUT_DIR.
The path of train ,val , testn number of classes and class names is stored in a dictionary variable and dumped in data.yaml.
yaml : It is a human-readable data serialization format. It is often used for configuration files and data exchange between languages with different data structures.
I have plotted the frequency of each class in train, val and test using seaborn library.
Loaded the pretrained YOLO-nano model. After training the model, I have saved the model as best.pt
The same model is again tested using test data set.
