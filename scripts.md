conda create -p venv python==3.10.9 -y
conda activate venv/

git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/tatz210588/growML.git
git push -u origin main

pip3 install -r requirements.txt