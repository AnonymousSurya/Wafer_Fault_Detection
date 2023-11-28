## 📄✏ Wafer Fault Detection Project
**Brief:** In electronics, a **wafer** (also called a slice or substrate) is a thin slice of semiconductor, such as a crystalline silicon (c-Si), used for the fabrication of integrated circuits and, in photovoltaics, to manufacture solar cells. The wafer serves as the substrate(serves as foundation for contruction of other components) for microelectronic devices built in and upon the wafer. 

It undergoes many microfabrication processes, such as doping, ion implantation, etching, thin-film deposition of various materials, and photolithographic patterning. Finally, the individual microcircuits are separated by wafer dicing and packaged as an integrated circuit.
___

### Problem Statement

**Data:** Wafers data


**Problem Statement:** Wafers are predominantly used to manufacture solar cells and are located at remote locations in bulk and they themselves consist of few hundreds of sensors. Wafers are fundamental of photovoltaic power generation, and production thereof requires high technology. Photovoltaic power generation system converts sunlight energy directly to electrical energy.

The motto behind figuring out the faulty wafers is to obliterate the need of having manual man-power doing the same. And make no mistake when we're saying this, even when they suspect a certain wafer to be faulty, they had to open the wafer from the scratch and deal with the issue, and by doing so all the wafers in the vicinity had to be stopped disrupting the whole process and stuff anf this is when that certain wafer was indeed faulty, however, when their suspicion came outta be false negative, then we can only imagine the waste of time, man-power and ofcourse, cost incurred.

**Solution:** Data fetched by wafers is to be passed through the machine learning pipeline and it is to be determined whether the wafer at hand is faulty or not apparently obliterating the need and thus cost of hiring manual labour.
___

#### 
### Task Performed:
* The objective of this project is to determine whether a credit card default will occur or not.
* Dataset is taken from Kaggle and stored in mongodb.
* Performed Exploratory data analysis on the dataset.
* Built components & pipelines in modular format. 
* Used models such as: XGBClassifier, Random forest, SVC, & GradientBoostingClassifier prediction purpose.
* The XGBClassifier performed the best with an accuracy score of 95%.
* Used Flask to build the web app.
* Built CI/CD pipeline with GitHub actions & deployed it through AWS App Runner.


💿 Installing
1. Environment setup.
```
conda create --prefix venv python==3.8 -y
```
```
conda activate venv/
````
2. Install Requirements and setup
```
pip install -r requirements.txt
```
5. Run Application
```
python application.py
```

🔧 Built with
- flask
- Python 3.8
- Machine learning
- Scikit learn
- docker

### Snapshot of the web app:
![Screenshot (135)](https://github.com/AnonymousSurya/Wafer_Fault_Detection/assets/76435009/e89abb03-6758-4c8a-9b46-ad88e4402f64)

