[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/YFgwt0yY)
# MiniTorch Module 2

<img src="https://minitorch.github.io/minitorch.svg" width="50%">


* Docs: https://minitorch.github.io/

* Overview: https://minitorch.github.io/module2/module2/

This assignment requires the following files from the previous assignments. You can get these by running

```bash
python sync_previous_module.py previous-module-dir current-module-dir
```

The files that will be synced are:

        minitorch/operators.py minitorch/module.py minitorch/autodiff.py minitorch/scalar.py minitorch/scalar_functions.py minitorch/module.py project/run_manual.py project/run_scalar.py project/datasets.py



## Output of trained model
### Simple
Time per epoch: 0.098s

Used the following parameters:
* PTS = 50
* DATASET = SIMPLE
* HIDDEN = 2
* RATE = 0.5
* EPOCHS = 500

#### Simple Training Log
```
Epoch: 0/500, loss: 0, correct: 0
Epoch: 10/500, loss: 30.745744187115402, correct: 34
Epoch: 20/500, loss: 26.714661539187404, correct: 38
Epoch: 30/500, loss: 20.3958815169716, correct: 44
Epoch: 40/500, loss: 15.47338748669406, correct: 44
Epoch: 50/500, loss: 11.7072518055109, correct: 49
Epoch: 60/500, loss: 9.191162195138038, correct: 50
Epoch: 70/500, loss: 13.039911417972514, correct: 44
Epoch: 80/500, loss: 15.055233087446926, correct: 43
Epoch: 90/500, loss: 6.7922496734815905, correct: 49
Epoch: 100/500, loss: 5.624612883934182, correct: 49
Epoch: 110/500, loss: 5.238900268528277, correct: 49
Epoch: 120/500, loss: 15.620808042214627, correct: 43
Epoch: 130/500, loss: 7.0074848100752725, correct: 47
Epoch: 140/500, loss: 3.9514472562185206, correct: 50
Epoch: 150/500, loss: 3.500183237773956, correct: 50
Epoch: 160/500, loss: 3.14855544186811, correct: 50
Epoch: 170/500, loss: 2.855335870827056, correct: 50
Epoch: 180/500, loss: 2.6595272310825058, correct: 50
Epoch: 190/500, loss: 9.338979378883979, correct: 46
Epoch: 200/500, loss: 9.874146632945989, correct: 46
Epoch: 210/500, loss: 3.5327338846946206, correct: 49
Epoch: 220/500, loss: 2.3491392257726087, correct: 50
Epoch: 230/500, loss: 2.1416150646950665, correct: 50
Epoch: 240/500, loss: 1.9770962716283829, correct: 50
Epoch: 250/500, loss: 1.8429917788963834, correct: 50
Epoch: 260/500, loss: 1.7250760166230574, correct: 50
Epoch: 270/500, loss: 1.6099720803791229, correct: 50
Epoch: 280/500, loss: 1.516297643719326, correct: 50
Epoch: 290/500, loss: 1.43306468004857, correct: 50
Epoch: 300/500, loss: 1.3584285865686252, correct: 50
Epoch: 310/500, loss: 1.2911332190535216, correct: 50
Epoch: 320/500, loss: 1.2301616175445924, correct: 50
Epoch: 330/500, loss: 1.1746755349665146, correct: 50
Epoch: 340/500, loss: 1.1239763247236405, correct: 50
Epoch: 350/500, loss: 1.0774767092955706, correct: 50
Epoch: 360/500, loss: 1.0346795623866674, correct: 50
Epoch: 370/500, loss: 0.9951615156223141, correct: 50
Epoch: 380/500, loss: 0.9585600480013916, correct: 50
Epoch: 390/500, loss: 0.9245631796628996, correct: 50
Epoch: 400/500, loss: 0.892901161794365, correct: 50
Epoch: 410/500, loss: 0.8708343416674215, correct: 50
Epoch: 420/500, loss: 0.8515096274230338, correct: 50
Epoch: 430/500, loss: 0.8259050895017961, correct: 50
Epoch: 440/500, loss: 0.8012585181284977, correct: 50
Epoch: 450/500, loss: 0.786100531427258, correct: 50
Epoch: 460/500, loss: 0.7673300236753323, correct: 50
Epoch: 470/500, loss: 0.7460948667978814, correct: 50
Epoch: 480/500, loss: 0.7166759736272147, correct: 50
Epoch: 490/500, loss: 0.6920809507613113, correct: 50
Epoch: 500/500, loss: 0.6754303653458914, correct: 50
```
![Simple Final Model](./images/simple_1.png)
![Simple Loss](./images/simple_2.png)


### DIAG
Time per epoch: 0.133s

Used the following parameters:
* PTS = 50
* DATASET = DIAG
* HIDDEN = 3
* RATE = 0.5
* EPOCHS = 500

#### DIAG Training Log
```
Epoch: 0/500, loss: 0, correct: 0
Epoch: 10/500, loss: 8.71439001268341, correct: 48
Epoch: 20/500, loss: 8.320789749907425, correct: 48
Epoch: 30/500, loss: 8.212509356487896, correct: 48
Epoch: 40/500, loss: 8.11914129050124, correct: 48
Epoch: 50/500, loss: 8.0300081959525, correct: 48
Epoch: 60/500, loss: 7.942310523685263, correct: 48
Epoch: 70/500, loss: 7.853145703176516, correct: 48
Epoch: 80/500, loss: 7.761352879295771, correct: 48
Epoch: 90/500, loss: 7.6654658204872055, correct: 48
Epoch: 100/500, loss: 7.562877458659861, correct: 48
Epoch: 110/500, loss: 7.453607647001386, correct: 48
Epoch: 120/500, loss: 7.334321710260998, correct: 48
Epoch: 130/500, loss: 7.199168580571607, correct: 48
Epoch: 140/500, loss: 7.045568034089806, correct: 48
Epoch: 150/500, loss: 6.8869761104997655, correct: 48
Epoch: 160/500, loss: 6.728148929884745, correct: 48
Epoch: 170/500, loss: 6.553536171257911, correct: 48
Epoch: 180/500, loss: 6.362842937193769, correct: 48
Epoch: 190/500, loss: 6.15207490280932, correct: 48
Epoch: 200/500, loss: 5.918682374343869, correct: 48
Epoch: 210/500, loss: 5.6659464805312325, correct: 48
Epoch: 220/500, loss: 5.429600715843431, correct: 48
Epoch: 230/500, loss: 5.2113328972954465, correct: 48
Epoch: 240/500, loss: 4.9932772349909325, correct: 48
Epoch: 250/500, loss: 4.773497653349825, correct: 48
Epoch: 260/500, loss: 4.540310682855701, correct: 48
Epoch: 270/500, loss: 4.3376212711263715, correct: 48
Epoch: 280/500, loss: 4.125247346752313, correct: 48
Epoch: 290/500, loss: 3.9573228221809047, correct: 48
Epoch: 300/500, loss: 3.805294549918732, correct: 48
Epoch: 310/500, loss: 3.6623503522456033, correct: 48
Epoch: 320/500, loss: 3.548053723036415, correct: 48
Epoch: 330/500, loss: 3.392729068805575, correct: 48
Epoch: 340/500, loss: 3.3703302291568877, correct: 48
Epoch: 350/500, loss: 3.2641194518316183, correct: 48
Epoch: 360/500, loss: 3.1032648771404707, correct: 48
Epoch: 370/500, loss: 2.9788311769482245, correct: 48
Epoch: 380/500, loss: 2.9218314303739827, correct: 48
Epoch: 390/500, loss: 2.907929285332404, correct: 48
Epoch: 400/500, loss: 2.691782608032066, correct: 48
Epoch: 410/500, loss: 2.808912951398827, correct: 48
Epoch: 420/500, loss: 2.566383725471458, correct: 48
Epoch: 430/500, loss: 2.538023955201902, correct: 48
Epoch: 440/500, loss: 2.4636808054288273, correct: 48
Epoch: 450/500, loss: 2.3661787696888137, correct: 49
Epoch: 460/500, loss: 2.3160345076267435, correct: 49
Epoch: 470/500, loss: 2.2969622525051663, correct: 49
Epoch: 480/500, loss: 2.2855751010439893, correct: 48
Epoch: 490/500, loss: 2.1837002867895294, correct: 50
Epoch: 500/500, loss: 2.1277506404693116, correct: 50
```

![DIAG Final Model](./images/diag_1.png)
![DIAG Loss](./images/diag_2.png)

### SPLIT
Time per epoch: 0.267s

Used the following parameters:
* PTS = 50
* DATASET = SPLIT
* HIDDEN = 5
* RATE = 0.5
* EPOCHS = 500

#### SPLIT Training Log
```
Epoch: 0/500, loss: 0, correct: 0
Epoch: 10/500, loss: 34.21839019509963, correct: 26
Epoch: 20/500, loss: 33.96424720669885, correct: 31
Epoch: 30/500, loss: 33.63223678394819, correct: 32
Epoch: 40/500, loss: 33.18669965916978, correct: 31
Epoch: 50/500, loss: 32.590518003601126, correct: 32
Epoch: 60/500, loss: 31.805649913515374, correct: 32
Epoch: 70/500, loss: 30.736316748249294, correct: 35
Epoch: 80/500, loss: 30.551625756844256, correct: 33
Epoch: 90/500, loss: 30.437215882576755, correct: 33
Epoch: 100/500, loss: 29.363881293336078, correct: 33
Epoch: 110/500, loss: 27.902788725843106, correct: 33
Epoch: 120/500, loss: 27.60053630963551, correct: 33
Epoch: 130/500, loss: 26.448799350654443, correct: 35
Epoch: 140/500, loss: 25.159539342219293, correct: 36
Epoch: 150/500, loss: 22.79005687064549, correct: 38
Epoch: 160/500, loss: 20.066489968801392, correct: 41
Epoch: 170/500, loss: 21.826254980679032, correct: 35
Epoch: 180/500, loss: 21.626563430955756, correct: 35
Epoch: 190/500, loss: 17.806764614670577, correct: 40
Epoch: 200/500, loss: 18.393935258586918, correct: 39
Epoch: 210/500, loss: 18.00689522304517, correct: 39
Epoch: 220/500, loss: 15.84914591767905, correct: 42
Epoch: 230/500, loss: 14.682178925697622, correct: 43
Epoch: 240/500, loss: 13.048164354881523, correct: 44
Epoch: 250/500, loss: 12.278345665983027, correct: 45
Epoch: 260/500, loss: 10.870395055485277, correct: 46
Epoch: 270/500, loss: 12.603284755141297, correct: 45
Epoch: 280/500, loss: 9.389511954793385, correct: 45
Epoch: 290/500, loss: 10.665903454049356, correct: 45
Epoch: 300/500, loss: 8.527086538632222, correct: 48
Epoch: 310/500, loss: 8.822452938652281, correct: 47
Epoch: 320/500, loss: 7.661609165182324, correct: 48
Epoch: 330/500, loss: 7.613153591619207, correct: 48
Epoch: 340/500, loss: 6.689462575048152, correct: 48
Epoch: 350/500, loss: 4.379526440384852, correct: 49
Epoch: 360/500, loss: 2.9858236361261428, correct: 50
Epoch: 370/500, loss: 2.603853987048525, correct: 50
Epoch: 380/500, loss: 2.380974232468393, correct: 50
Epoch: 390/500, loss: 2.229939697005624, correct: 50
Epoch: 400/500, loss: 2.3102699174165844, correct: 50
Epoch: 410/500, loss: 22.665075178726006, correct: 39
Epoch: 420/500, loss: 2.87352279611792, correct: 50
Epoch: 430/500, loss: 2.355553694950483, correct: 50
Epoch: 440/500, loss: 2.0917809357304282, correct: 50
Epoch: 450/500, loss: 1.885919070417525, correct: 50
Epoch: 460/500, loss: 1.7199177051470904, correct: 50
Epoch: 470/500, loss: 1.5810581364887304, correct: 50
Epoch: 480/500, loss: 1.464634964727603, correct: 50
Epoch: 490/500, loss: 1.3616031230764782, correct: 50
Epoch: 500/500, loss: 1.2696918507023989, correct: 50
```

![SPLIT Final Model](./images/split_1.png)
![SPLIT Loss](./images/split_2.png)

### XOR
Time per epoch: 1.334s

Used the following parameters:
* PTS = 50
* DATASET = XOR
* HIDDEN = 15
* RATE = 0.1
* EPOCHS = 1250

#### XOR Training Log
```
Epoch: 10/1250, loss: 33.67885084447656, correct: 31
Epoch: 20/1250, loss: 32.94072460935858, correct: 33
Epoch: 30/1250, loss: 32.30007307599157, correct: 34
Epoch: 40/1250, loss: 31.842837927760247, correct: 34
Epoch: 50/1250, loss: 31.38924042326283, correct: 34
Epoch: 60/1250, loss: 30.91588906681103, correct: 35
Epoch: 70/1250, loss: 30.423850007183812, correct: 35
Epoch: 80/1250, loss: 29.893463467292296, correct: 39
Epoch: 90/1250, loss: 29.32425574810011, correct: 39
Epoch: 100/1250, loss: 28.72997531550218, correct: 40
Epoch: 110/1250, loss: 28.11032613273218, correct: 42
Epoch: 120/1250, loss: 27.45660881197199, correct: 44
Epoch: 130/1250, loss: 26.76695304760652, correct: 44
Epoch: 140/1250, loss: 26.046297525248878, correct: 45
Epoch: 150/1250, loss: 25.291661958315455, correct: 45
Epoch: 160/1250, loss: 24.517797708043705, correct: 45
Epoch: 170/1250, loss: 23.726360283809555, correct: 47
Epoch: 180/1250, loss: 22.917342601048514, correct: 48
Epoch: 190/1250, loss: 22.08942745925328, correct: 48
Epoch: 200/1250, loss: 21.251363036869247, correct: 48
Epoch: 210/1250, loss: 20.341169710693997, correct: 48
Epoch: 220/1250, loss: 19.095073413974248, correct: 47
Epoch: 230/1250, loss: 18.129525673518327, correct: 47
Epoch: 240/1250, loss: 17.32841288122876, correct: 47
Epoch: 250/1250, loss: 16.574517709271017, correct: 47
Epoch: 260/1250, loss: 15.858237224139312, correct: 47
Epoch: 270/1250, loss: 15.209591184268627, correct: 46
Epoch: 280/1250, loss: 14.581697207836394, correct: 46
Epoch: 290/1250, loss: 13.985697941812566, correct: 47
Epoch: 300/1250, loss: 13.4448571850286, correct: 47
Epoch: 310/1250, loss: 12.928924228598085, correct: 47
Epoch: 320/1250, loss: 12.442753782781192, correct: 48
Epoch: 330/1250, loss: 11.987105434408479, correct: 48
Epoch: 340/1250, loss: 11.569658094496303, correct: 47
Epoch: 350/1250, loss: 11.168697040585284, correct: 48
Epoch: 360/1250, loss: 10.792994069597322, correct: 48
Epoch: 370/1250, loss: 10.390840346493173, correct: 48
Epoch: 380/1250, loss: 10.016410626442486, correct: 48
Epoch: 390/1250, loss: 9.70583083064003, correct: 48
Epoch: 400/1250, loss: 9.425582584649344, correct: 48
Epoch: 410/1250, loss: 9.166033596618368, correct: 48
Epoch: 420/1250, loss: 8.925863359444582, correct: 48
Epoch: 430/1250, loss: 8.697944369012438, correct: 48
Epoch: 440/1250, loss: 8.476759523656659, correct: 49
Epoch: 450/1250, loss: 8.268538411211196, correct: 49
Epoch: 460/1250, loss: 8.072220721258857, correct: 49
Epoch: 470/1250, loss: 7.882068433744171, correct: 49
Epoch: 480/1250, loss: 7.69357693463744, correct: 49
Epoch: 490/1250, loss: 7.52320463530366, correct: 49
Epoch: 500/1250, loss: 7.369718780121408, correct: 49
Epoch: 510/1250, loss: 7.220490837876357, correct: 49
Epoch: 520/1250, loss: 7.080972066462328, correct: 49
Epoch: 530/1250, loss: 6.94547347497831, correct: 49
Epoch: 540/1250, loss: 6.816474275911229, correct: 49
Epoch: 550/1250, loss: 6.693722296554867, correct: 49
Epoch: 560/1250, loss: 6.575233257828769, correct: 49
Epoch: 570/1250, loss: 6.4646126957362915, correct: 49
Epoch: 580/1250, loss: 6.359792312458356, correct: 49
Epoch: 590/1250, loss: 6.25525760456811, correct: 49
Epoch: 600/1250, loss: 6.156970782944674, correct: 49
Epoch: 610/1250, loss: 6.05916792026587, correct: 49
Epoch: 620/1250, loss: 5.9660881212091565, correct: 49
Epoch: 630/1250, loss: 5.8732523898864875, correct: 49
Epoch: 640/1250, loss: 5.784090061983664, correct: 49
Epoch: 650/1250, loss: 5.6995021599327815, correct: 49
Epoch: 660/1250, loss: 5.620780842731333, correct: 49
Epoch: 670/1250, loss: 5.5420916434605045, correct: 49
Epoch: 680/1250, loss: 5.466495425964122, correct: 49
Epoch: 690/1250, loss: 5.392623209742365, correct: 49
Epoch: 700/1250, loss: 5.320438537825083, correct: 49
Epoch: 710/1250, loss: 5.250376383501997, correct: 49
Epoch: 720/1250, loss: 5.1830238060276415, correct: 49
Epoch: 730/1250, loss: 5.116620439503594, correct: 49
Epoch: 740/1250, loss: 5.051981636971748, correct: 49
Epoch: 750/1250, loss: 4.988868473084494, correct: 49
Epoch: 760/1250, loss: 4.928673782353368, correct: 49
Epoch: 770/1250, loss: 4.863839935446614, correct: 49
Epoch: 780/1250, loss: 4.8012359714185875, correct: 49
Epoch: 790/1250, loss: 4.739505013920854, correct: 50
Epoch: 800/1250, loss: 4.679980092768374, correct: 50
Epoch: 810/1250, loss: 4.620962938612814, correct: 50
Epoch: 820/1250, loss: 4.564821558475184, correct: 50
Epoch: 830/1250, loss: 4.5105100176108355, correct: 50
Epoch: 840/1250, loss: 4.45818159876792, correct: 50
Epoch: 850/1250, loss: 4.406929710027758, correct: 50
Epoch: 860/1250, loss: 4.356397305942242, correct: 50
Epoch: 870/1250, loss: 4.30757580888041, correct: 50
Epoch: 880/1250, loss: 4.260407843720244, correct: 50
Epoch: 890/1250, loss: 4.2141143983031855, correct: 50
Epoch: 900/1250, loss: 4.168105752622435, correct: 50
Epoch: 910/1250, loss: 4.123509625030556, correct: 50
Epoch: 920/1250, loss: 4.079372996191164, correct: 50
Epoch: 930/1250, loss: 4.0365942283827865, correct: 50
Epoch: 940/1250, loss: 3.9953556465266153, correct: 50
Epoch: 950/1250, loss: 3.955610793574541, correct: 50
Epoch: 960/1250, loss: 3.9169363013932696, correct: 50
Epoch: 970/1250, loss: 3.8749774963615518, correct: 50
Epoch: 980/1250, loss: 3.836803914514133, correct: 50
Epoch: 990/1250, loss: 3.800465022615284, correct: 50
Epoch: 1000/1250, loss: 3.765168874870041, correct: 50
Epoch: 1010/1250, loss: 3.7301838373823206, correct: 50
Epoch: 1020/1250, loss: 3.695497429610783, correct: 50
Epoch: 1030/1250, loss: 3.6630717084713464, correct: 50
Epoch: 1040/1250, loss: 3.630241019106033, correct: 50
Epoch: 1050/1250, loss: 3.6014465966272184, correct: 50
Epoch: 1060/1250, loss: 3.576648047430772, correct: 50
Epoch: 1070/1250, loss: 3.5523489863064923, correct: 50
Epoch: 1080/1250, loss: 3.5259522071803233, correct: 50
Epoch: 1090/1250, loss: 3.499407142872782, correct: 50
Epoch: 1100/1250, loss: 3.4729268271019165, correct: 50
Epoch: 1110/1250, loss: 3.445216994295806, correct: 50
Epoch: 1120/1250, loss: 3.4193998995987602, correct: 50
Epoch: 1130/1250, loss: 3.39386592071243, correct: 50
Epoch: 1140/1250, loss: 3.3710062910988423, correct: 50
Epoch: 1150/1250, loss: 3.343600751191172, correct: 50
Epoch: 1160/1250, loss: 3.31565247808068, correct: 50
Epoch: 1170/1250, loss: 3.2921931274566636, correct: 50
Epoch: 1180/1250, loss: 3.2717610889786357, correct: 50
Epoch: 1190/1250, loss: 3.241747293033006, correct: 50
Epoch: 1200/1250, loss: 3.2230059249092493, correct: 50
Epoch: 1210/1250, loss: 3.1986379154149867, correct: 50
Epoch: 1220/1250, loss: 3.183246813468627, correct: 50
Epoch: 1230/1250, loss: 3.1632083610629693, correct: 50
Epoch: 1240/1250, loss: 3.1532651916725047, correct: 50
Epoch: 1250/1250, loss: 3.1369875337974626, correct: 50
```

![XOR Final Model](./images/xor_1.png)
![XOR Loss](./images/xor_2.png)