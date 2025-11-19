# Purpose of this Folder


git clone --no-checkout https://github.com/udacity/cd14641-langgraph-multi-public autonomous_knowledge_agent cd autonomous_knowledge_agent

git sparse-checkout init --cone
git sparse-checkout set project
git checkout main


This folder should contain a fully working project. This will be added to the reviewer toolkit for reviewers to use.

0

I faced the same issue but after lots of research, i found some outcomes which i want to share with you... Please follow my steps sequentially:

python3 -V // check the version of python like 3.8.1
sudo apt install python3-venv // for installing the latest virtual environment library
python3 -m venv my-project-env //create virtual environment, where you can change name of my-project-env into your requirement name..
source my-project-env/bin/activate // activate your evnironment
NOTE: point no-4, please add source word in your command while run poi
