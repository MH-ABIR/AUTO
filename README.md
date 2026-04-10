#run Tools

cd

rm -rf AUTO

git clone --depth=1 https://github.com/MH-ABIR/AUTO

cd AUTO

git pull

python CREATE.py
