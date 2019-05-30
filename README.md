# slackit
Helper repository for posting slack webhooks

# Install
git clone https://github.com/mattsoftware/slackit
cd slackit
ln -s `pwd`/slackit_config /etc/

Edit the config file accordingly

# Usage
echo "Send this to slack" | ./slackit "channel"

