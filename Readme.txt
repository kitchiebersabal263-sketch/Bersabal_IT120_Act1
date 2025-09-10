mkdir Bersabal_IT120_Act1
cd Bersabal_IT120_Act1
git init
git config --global user.name "kitchiebersabal263-sketch"
git config --global user.email "kitchiebersabal263@gmail.com"
touch Profile.txt Education.txt Background.txt Readme.txt Test.py
echo "Language Known: English, Cebuano, Filipino, Sign Language" > Background.txt
echo "Elementary School: Calamba Elementary School
Year Graduated: 2017
High School: Calamba National High School
Year Graduated: 2023" > Education.txt
echo "First Name: Kitchie
Middle Name: Awitan
Last Name: Bersabal
Gender: Female
Age: 20
Birthday: July 2, 2005
Contacts: 09993943783" > Profile.txt
echo '' > Readme.txt
echo 'print("Hello, World")' > Test.py
git add .
git commit -m "MASTER: Initial files setup"
git branch -M main
git checkout -b BERSABAL_B1
echo "Birth Place: Cabadbaran City
Religion: Jehovah's Witness
Father's Name: Sandy Bersabal
Father's Occupation: Farmer
Mother's Name: Ardie Bersabal
Mother's Occupation: Vendor" > Profile.txt
git add Profile.txt
git commit -m "B1: Amend Profile with family and religion"
git checkout main
git checkout -b BERSABAL_B2
echo "College: Caraga State University Cabadbaran Campus
Program: Bachelor of Science in Information Technology
Year Level: 3rd Year" > Education.txt
git add Education.txt
git commit -m "B2: Amend Education with college details"
git checkout main
