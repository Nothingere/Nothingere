### Hi there š

<!--
**Nothingere/Nothingere** is a āØ _special_ āØ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- š­ Iām currently working on ...
- š± Iām currently learning ...
- šÆ Iām looking to collaborate on ...
- š¤ Iām looking for help with ...
- š¬ Ask me about ...
- š« How to reach me: ...
- š Pronouns: ...
- ā” Fun fact: ...
-->
README.md
TeamUltroid Logo

Linux - bash -c "$(curl -fsSL https://git.io/JY9UM)"
Windows - cd desktop ; wget https://del.dog/raw/ultroid-termux -o locals.py ; python locals.py
Termux - sh -c "$(curl -fsSL https://del.dog/raw/ultroid-termux-deploy)"
Local Deploy - Traditional Method
Get your Necessary Variables
Clone the repository:
git clone https://github.com/TeamUltroid/Ultroid.git
Go to the cloned folder:
cd Ultroid
Create a virtual env:
virtualenv -p /usr/bin/python3 venv . ./venv/bin/activate
Install the requirements:
pip(3) install -U -r requirements.txt
Generate your SESSION:
For Linux users: bash sessiongen or bash -c "$(curl -fsSL https://del.dog/ultroid)"
For Termux users: sh -c "$(curl -fsSL https://da.gd/termux-tel)"
For Windows Users: cd desktop ; wget https://del.dog/ultroid -o ultroid.py ; python ultroid.py
Fill your details in a .env file, as given in .env.sample. (You can either edit and rename the file or make a new file named .env.)
Run the bot:
Linux Users: bash resources/startup/startup.sh
Windows Users: python(3) -m pyUltroid
