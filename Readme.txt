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
git checkout -b BERSABAL_B3
echo "Person to Contact: Ardie Bersabal
Address: Cabadbaran City, Agusan del Norte" > Background.txt
git rm Test.py
git add Background.txt
git commit -m "B3: Add contact & address, remove Test.py"
git checkout main
git checkout -b BERSABAL_B4
git rm Test.py
git add Readme.txt
git commit -m "B4: Add Git commands to Readme and remove Test.py"
git remote add origin https://github.com/kitchiebersabal263-sketch/Bersabal_IT120_Act1.git
git push -u origin main
git push origin BERSABAL_B1
git push origin BERSABAL_B2
git push origin BERSABAL_B3
git push origin BERSABAL_B4
git checkout BERSABAL_B1
git checkout BERSABAL_B4 -- Readme.txt
git add Readme.txt
git commit -m "Update Readme.txt from B4"
git checkout BERSABAL_B2
git checkout BERSABAL_B4 -- Readme.txt
git add Readme.txt
git commit -m "Update Readme.txt from B4"
git checkout BERSABAL_B3
git checkout BERSABAL_B4 -- Readme.txt
git add Readme.txt
git commit -m "Update Readme.txt from B4"
git checkout main
git checkout BERSABAL_B4 -- Readme.txt
git add Readme.txt
git commit -m "Update Readme.txt from B4"
