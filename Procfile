python: pip3 install -r requirements.txt
shell: cp local-config.json ~/.local/share/hangupsbot/config.json
shell: sed -i -e 's/xoxb/'"$slack-api-key"'/g' ~/.local/share/hangupsbot/config.json
shell: sed -i -e 's/!team/'"$slack-team"'/g' ~/.local/share/hangupsbot/config.json
shell: sed -i -e 's/!hadmin/'"$hangout-admin"'/g' ~/.local/share/hangupsbot/config.json
python: python3 ./hangupsbot/hangupsbot.py

