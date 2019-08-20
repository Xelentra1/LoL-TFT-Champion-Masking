# League Of Legends - Teamfight Tactics Champion Masking
Its masks selected champions like Gangplank<br>
![Masked Gankplank](https://github.com/tufanYavas/LoL-TFT-Champion-Masking/blob/master/images/maskedimg.png)

### Two in-game settings
- Make window mode borderless in game settings.
![Game Mode Setting](https://github.com/tufanYavas/LoL-TFT-Champion-Masking/blob/master/images/borderlessoption.png)
- Make Hud Scale = 100 in game settings.
![Hud Scale Setting](https://github.com/tufanYavas/LoL-TFT-Champion-Masking/blob/master/images/hudscaleoption.jpg)

### If you wish EXE file
- [Download](https://onedrive.live.com/?authkey=%21AKS5lZGlpXlJOq8&id=DCFFB231A712BAA8%213588&cid=DCFFB231A712BAA8)
- Run TFT Champ Masking.exe
- if you create special coms:
  - Modify comps.txt
  - Rule:
    - ```Comp Name,Champ Name1,Champ Name2,Champ Name3,Champ Name4,Champ Name5,Champ Name6,Champ Name7,Champ Name8,Champ Name9```
    - ```Comp Name2,Champ Name1,Champ Name2,Champ Name3,Champ Name4,Champ Name5,Champ Name6,Champ Name7,Champ Name8,Champ Name9,Champ Name10,Champ Name11```
- Thats All
    
### Else: Installation For Windows
- [Download](https://github.com/UB-Mannheim/tesseract/wiki) and install tesseract.
- Modify ```pytesseract.pytesseract.tesseract_cmd = r'C:\Program Files\Tesseract-OCR\tesseract.exe``` line from ```worker.py``` as your tesseract path.
- ```pip install -r requirements.txt --user```
- ```python main.py```

### Create Special Comps
- Modify ```comp``` dictionary (from ```worker.py```) as you wish. Thats all.

Example:
```
comps = {"Shapeshifter+Wild":["Nidalee",
                              "Elise",
                              "Shyvana",
                              "Gnar",
                              "Swain",
                              "Warwick",
                              "Ahri",
                              "Nidalee",
                              "Rengar",
                              "Gnar"]}
```
![Special Comp](https://github.com/tufanYavas/LoL-TFT-Champion-Masking/blob/master/images/specialcomp.png)
