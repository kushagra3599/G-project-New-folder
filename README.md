# HOPECentre-FR-
HOPECenter a website having facilities connecting you to nearest NGO's, making donation using Paytm gateways, and using machine learning(face recognition) to get the live details of missing children's on screen.


PreRequisites for face recognition-
python 2.7
OpenCv 4.x
numpy 1.7
SQLiteStudio.exe

-----------------------------------------------------------------------------------------------------------

Running instruction for face recognition-
open SQLiteStudio.exe and create a database "facerecognition"
set table name = "People"
add 4 coloum of ID,Name,Age,Gender
now run dataSetCreator.py
write 4 details of ID,Name,Age,Gender
run trainner.py
if you want to detect faces and see their data run detector.py
