## 📄✏ Sensor Fault Detection Project
**Brief:** In electronics, a **wafer** (also called a slice or substrate) is a thin slice of semiconductor, such as a crystalline silicon (c-Si), used for the fabrication of integrated circuits and, in photovoltaics, to manufacture solar cells. The wafer serves as the substrate(serves as foundation for contruction of other components) for microelectronic devices built in and upon the wafer. 

It undergoes many microfabrication processes, such as doping, ion implantation, etching, thin-film deposition of various materials, and photolithographic patterning. Finally, the individual microcircuits are separated by wafer dicing and packaged as an integrated circuit.

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

