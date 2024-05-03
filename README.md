# ssh-authentication-hugging-face
This is a GitHub repository with instructions on how to authenticate your identity in a local terminal such as Visual Studio Code in order to clone a Hugging Face Space or any other GitHub Repository.

eval "$(ssh-agent -s)"

# ssh-add <path-to-file>

ssh-add /Users/marencordts/ssh_key_hugging_face

# chmod 600 ~/.<file_name_ssh_key>

chmod 600 /Users/marencordts/ssh_key_hugging_face

# Test ssh-connection: ssh -T git@hf.co

git clone git@hf.co:spaces/IWIHSG/sess

# Activate venv environment

source /Users/marencordts/sess/.venv/bin/activate

