# Facial Recognition Based Attendance System

# [Watch the video: Link](https://www.youtube.com/watch?v=Fmkfh_XTGDw)
[![Watch the video: Link](https://user-images.githubusercontent.com/48029688/81901761-aada5300-95dc-11ea-8de5-662c326e7edc.gif)](https://youtu.be/Fmkfh_XTGDw)</div>

**Medium Article: [](https://medium.com/@rishabh.rk1705/automatic-facial-recognition-based-attendance-system-bea3be8003fe)**
**Cppsecrets: [](https://cppsecrets.com/users/5271114105115104979810446114107495548525364103109971051084699111109/Advanced-Project-Automatic-Facial-Recognition-Based-Attendance-System.php)**
#### PS: Sorry for the bad quality, in case of any doubts refer the below images

Facial Recognition Based Attendance System using Python, Tensorflow, Keras, SqlLite3, Tkinter, OpenCV for companies, schools, colleges, etc.

Automating attendance using Face Recognition via Neural Networks

The entire process of marking attendance in educational institutions, workplaces, when automized is the best and most cost effective way of making it fool-proof and better.

This makes proxy attendance impossible and the workplace ethics- trustworthy

This, while isn't the perfect way, it's an attempt to do something similar

This is an implementation by me using various methods - Via Multi Threaded Cascaded Neural Networks

Techologies Used:
* Python
* Tensorflow
* Keras
* SqlLite3
* Tkinter
* OpenCV

Using MTCNN we mapped out the 128 feature map from each side of the face to create a 3D grid
like structure.

![MTCNN](./mtcnn.png)

# Note for working: 
**Download models and save at models folder. PS: read models/readme.txt**
Download models at: https://drive.google.com/file/d/0Bx4sNrhhaBr3TDRMMUN3aGtHZzg/view?usp=sharing

## All features and implemetation:

**1. Two Step Verification:**

Login Page made using Tkinter in Python 3, which is linked using a mysqllite3 database.
Once that verification is complete, you will be asked to verify yourself as admin using facial recognition. Only after these two steps will the admin menu open.

![Main](./images/Main.png)

![Webcam](./images/Webcam.png)

**2. The main interface:**

This is the main interface in which you can see the main features and have
necesaary actions taken place.

![Interface](./images/Interface.png)

**3. Click to register new student.**

Add new student into the database and map his/her facial features.

It will be seen as something like this in the **facerec_128D.txt** file.

*{"**Rishabh**": {"**Left**": [[-0.08857411891222, -0.013328742235898972, 0.045192185789346695, 0.06593235582113266, 0.07181892544031143, -0.02451349049806595, -0.0008240576717071235, -0.10689839720726013, 0.004937916528433561, 0.13439585268497467, -0.1266225427389145, 0.06688152998685837, -0.07906737178564072, -0.2503505051136017, -0.09821527451276779, 0.00887088943272829, 0.07310174405574799, 0.04754112288355827, 0.039231643080711365, -0.048129040747880936, 0.08559799194335938, 0.03705426678061485, -0.049444954842329025, 0.021733097732067108, -0.131277933716774, 0.13494974374771118, -0.04066428169608116, -0.011854524724185467, 0.062259819358587265, 0.0764424279332161, 0.09991776943206787, -0.04010583832859993, 0.036400649696588516, -0.08750853687524796, -0.005311599466949701, -0.06827758252620697, -0.08045513182878494, -0.04325050488114357, 0.0635976567864418, -0.08059954643249512, -0.10530292987823486, 0.015154648572206497, -0.11859557032585144, 0.09017852693796158, 0.05019151791930199, 0.09819871932268143, -0.05376705154776573, 0.12599189579486847, -0.10198838263750076, 0.10567402094602585, 0.03724795952439308, -0.023543009534478188, -0.025222115218639374, -0.02436627447605133, 0.06199340894818306, 0.05257124826312065, 0.09913825988769531, -0.15212902426719666, -0.043736133724451065, -0.11437535285949707, -0.19793258607387543, -0.2234376072883606, -0.030257174745202065, -0.003642328782007098, -0.016683151945471764, 0.059480536729097366, -0.028783461079001427, 0.010495315305888653, -0.02444811910390854, -0.06459680944681168, -0.034520987421274185, -0.06521014124155045, -0.028651727363467216, -0.00240131001919508, 0.09791675209999084, 0.03393810614943504, -0.11461859941482544, 0.04570923373103142, -0.09382005780935287, 0.023104486986994743, -0.12004870176315308, -0.09294884651899338, -0.11523831635713577, -0.040725890547037125, 0.10595870763063431, 0.01619560830295086, -0.06328869611024857, 0.09463641047477722, -0.14613036811351776, 0.1686006635427475, 0.02015562355518341, 0.08080480247735977, 0.06503424793481827, 0.04643187299370766, 0.04240923002362251, -0.14089588820934296, 0.05210058018565178, 0.06557077914476395, -0.09871061891317368, -0.20630748569965363, 0.06267132610082626, -0.020570171996951103, 0.04313775524497032, -0.08636415749788284, -0.11732497811317444, -0.032937780022621155, -0.09599996358156204, -0.01282432209700346, 0.003398689441382885, -0.028353899717330933, -0.03610304743051529, 0.07928384095430374, -0.05412999913096428, 0.06276759505271912, 0.09186709672212601, 0.08638894557952881, 0.01919158361852169, -0.07579809427261353, 0.0243211816996336, 0.07186244428157806, 0.052790567278862, -0.11808109283447266, -0.021565617993474007, -0.010558109730482101, 0.0045998296700417995, -0.17246980965137482, 0.0031077908352017403, 0.10488221049308777]], "**Right**": [[-0.12322423607110977, -0.09166958183050156, 0.0030119975563138723, 0.07374182343482971, 0.03698710724711418, -0.05573098734021187, -0.04385635256767273, -0.05670739337801933, -0.030628273263573647, 0.0965498685836792, -0.1603952795267105, 0.044863514602184296, -0.09822320193052292, -0.21349085867404938, -0.07051543891429901, 0.004292635712772608, 0.10493224114179611, 0.06687428802251816, 0.01295499037951231, -0.07349883019924164, 0.05057000368833542, 0.020694905892014503, -0.027202999219298363, -0.02207556739449501, -0.0919264480471611, 0.11229139566421509, -0.05143684148788452, 0.027473922818899155, 0.08050292730331421, 0.09868771582841873, 0.11485501378774643, -0.015976151451468468, 0.10177667438983917, -0.11236434429883957, -0.016733890399336815, -0.005377459805458784, -0.10113469511270523, -0.022559013217687607, 0.032608501613140106, -0.05285423621535301, -0.12459512799978256, 0.0313110277056694, -0.13205775618553162, 0.057603076100349426, 0.09496308118104935, 0.10811097919940948, -0.05295582115650177, 0.16086789965629578, -0.14587527513504028, 0.10840559005737305, 0.06493332982063293, 0.0071846661157906055, -0.013227133080363274, -0.00119835848454386, 0.07649098336696625, 0.06774774938821793, 0.01602318324148655, -0.10919184237718582, 0.014698031358420849, -0.12906238436698914, -0.17284737527370453, -0.2420649230480194, -0.05963245779275894, 0.009172102436423302, 0.03936951979994774, 0.006963794119656086, -0.04228965938091278, 0.03055589459836483, -0.0529898963868618, -0.13618960976600647, -0.07230045646429062, -0.09350531548261642, 0.008212929591536522, -0.05667538568377495, 0.09826629608869553, 0.044655390083789825, -0.10776958614587784, 0.04083753749728203, -0.0769808441400528, 0.0015262780943885446, -0.11382219940423965, -0.04048719257116318, -0.1647450029850006, -0.013006428256630898, 0.06237463653087616, -0.018204638734459877, -0.07192468643188477, 0.0846826583147049, -0.15275610983371735, 0.19314837455749512, 0.0426262728869915, 0.12794964015483856, 0.019906241446733475, 0.019699309021234512, -0.034911222755908966, -0.09784211963415146, 0.05271156132221222, 0.027143143117427826, -0.08809338510036469, -0.13904356956481934, 0.0515521876513958, 0.01055392436683178, 0.05781266465783119, -0.10861864686012268, -0.1330457329750061, -0.05695170536637306, -0.09640974551439285, -0.011350560002028942, 0.06401976197957993, -0.04768972471356392, -0.07988857477903366, 0.07721281796693802, -0.04194026067852974, 0.03974579647183418, 0.15303140878677368, 0.05464969202876091, 0.04337718337774277, -0.06133032962679863, 0.030452147126197815, 0.05700261518359184, 0.048203643411397934, -0.12868882715702057, -0.03181086853146553, 0.01268375851213932, 0.02336101047694683, -0.1532122939825058, 0.015040037222206593, 0.1001887172460556]], "**Center**": [[-0.10967082530260086, -0.06298966705799103, -0.011383222416043282, 0.11461437493562698, 0.03760898485779762, -0.007656498812139034, -0.030709397047758102, -0.10834655165672302, 0.007725639268755913, 0.12123774737119675, -0.14156821370124817, 0.028559843078255653, -0.0785200372338295, -0.22912156581878662, -0.08861233294010162, -0.04266420751810074, 0.10166534036397934, 0.03897407650947571, 0.0028791308868676424, -0.0385410413146019, 0.10671200603246689, -0.004739650525152683, -0.05746972933411598, -0.01709706336259842, -0.08726881444454193, 0.15067297220230103, 0.0029882092494517565, 0.015119166113436222, 0.0757543072104454, 0.057988062500953674, 0.10776271671056747, 0.013821783475577831, 0.07379657030105591, -0.11738615483045578, -0.029304908588528633, -0.056877341121435165, -0.12034665793180466, -0.04799569025635719, 0.047891829162836075, -0.07885117828845978, -0.10633303225040436, -0.002672838978469372, -0.11268853396177292, 0.0616154707968235, 0.07286091893911362, 0.10876667499542236, -0.06929004192352295, 0.1699533313512802, -0.10778924822807312, 0.08526410907506943, 0.06398101150989532, -0.010307646356523037, -0.00972981657832861, -0.013310537673532963, 0.1242566630244255, 0.06968270987272263, 0.05530219152569771, -0.1308509111404419, 0.05558321252465248, -0.1440255045890808, -0.2014542520046234, -0.23179376125335693, -0.020311595872044563, 0.025337493047118187, 0.012508675456047058, 0.023336704820394516, -0.05754031613469124, -0.02776341140270233, -0.07715149223804474, -0.11648695915937424, -0.07794658839702606, -0.1122051402926445, 0.017184695228934288, -0.02500501275062561, 0.060275837779045105, 0.03202875703573227, -0.07855446636676788, 0.04930829629302025, -0.08615235239267349, 0.028393523767590523, -0.1189601719379425, -0.06144094467163086, -0.13767829537391663, -0.021015029400587082, 0.09078904986381531, -0.00970941036939621, -0.10330627113580704, 0.0704386904835701, -0.14051242172718048, 0.12551555037498474, 0.042997896671295166, 0.0928570032119751, 0.01946619525551796, 0.036238349974155426, 0.020949648693203926, -0.13063529133796692, 0.06630231440067291, 0.038655202835798264, -0.11432863026857376, -0.20290106534957886, 0.05083588510751724, -0.03496573865413666, 0.0733042061328888, -0.040517449378967285, -0.14749570190906525, -0.03399404510855675, -0.05033278092741966, -0.008389569818973541, 0.0652705654501915, -0.030615858733654022, -0.0401158481836319, 0.04068402200937271, -0.06507669389247894, 0.08976959437131882, 0.11061953753232956, 0.06556890904903412, 0.03285010904073715, -0.05539695546030998, 0.027370641008019447, 0.06945658475160599, 0.06850945949554443, -0.10180337727069855, -0.008417774923145771, -0.010144680738449097, -0.023704135790467262, -0.11576569080352783, 0.0737953707575798, 0.09932660311460495]]}}*

Using which we can recognise the face and add in the database.

**4. Give attendance.**

In its application, the camera will be open and faces will be recorded and analysed in real
time and if present name will be marked as present in the xlxs sheet.

![Attendance](./images/Attendance.png)

![XLXS_Demo](./images/xlxs.png)

**Creating an optimum solution and a better society.
Viola!**


## Note - check "Testing.txt"
Run in following order:
!python main.py
!python Auth.py
!python screen.py

Further more: 
	
*	To add new entry: !python Add_New.py
*	To verify and give to existing: !python Recog.py
*	To check attendance in terminal: !python attendance.py 

Tested in Following Versions:

*	OS: Ubuntu '19.04'
*	tensorflow == '1.15.0'
*	keras == '2.3.0'
*	tkinter == '8.6'
*	numpy == '1.16.1'
*	opencv == '4.1.2' 
*	python == '3.7.4'
*	pyttsx3 == '2.71'

## Additional Highlights:

* As the next day arises, it is automatically stored in new tab in the xlxs sheet so files arent over-written
* Seeing attendance or editing requires an master face print which can be set earlier so students cant change their records.
* Multiple times and mutiple faces is taken in consideration
* Future Scope: Setting in and out timing as well so as to create a proxy payroll system as well.
