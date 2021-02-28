>pip install virtualenv 
>>this would install a virtual env


>cd Documents
>>changing dir to where you want your virtual env 

>mkdir Environments
>>creating a new dir insdie which we would create virtual env

>cd Environments
>> inside the working dir

>ls
>> listing the dir files

>virtualenv proect01_env
>>creating a virtual env with name proect01_env

>source proect01_env/bin/activate
>>to activate the virtual env

>deactivate
>>to deactivate the virtual env

>pip list
>>lisiting all the pip installed in the virtual env

>which python
>> python path which is used

>which pip
>> pip path which is used

>python --version
>> tells abt the python version

>pip install numpy
>
>pip install pandas
>>installing python modules

>pip freeze --local > requirements.txt
>>willl freeze the virtual env and will save the versions of modules installe in env in .txt file

>ls
>
>cat requirements.txt
>>will show the versions saved in the virtual env

>rm -rf proect01_env 
>> will remove the virtual env from dir

><h2>
>1. Virtual envs are meant to be for your dependencies and packages and things like tht, but they are not for your project files.
>
>2. You don't waana go in and start building your project files within your virtual envs bcoz you want to be be able to pass these along and throw them away whenever you want, so you don't want to have all of your project files in these virtual envs.
>
>3. They are really just intended to separate out the packages dependencies and the versions you'r going to use from project to project   
</h2>
