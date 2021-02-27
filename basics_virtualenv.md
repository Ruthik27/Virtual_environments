pip install virtualenv

cd Documents
mkdir Environments
cd Environments

ls

virtualenv proect01_env

source proect01_env/bin/activate
deactivate


pip list

which python
which pip
python --version

pip install numpy
pip install pandas

pip freeze --local > requirements.txt
ls
cat requirements.txt

rm -rf proect01_env 

><h2>
>1. Virtual envs are meant to be for your dependencies and packages and things like tht, but they are not for your project files.
>
>2. You don't waana go in and start building your project files within your virtual envs bcoz you want to be be able to pass these along and throw them away whenever you want, so you don't want to have all of your project files in these virtual envs.
>
>3. They are really just intended to separate out the packages dependencies and the versions you'r going to use from project to project   
</h2>
