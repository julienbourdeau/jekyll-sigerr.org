
### Get data

wget https://pipes.yahoo.com/pipes/pipe.run?_id=6aab152a6c32a6595b2f7506ce3b18d7&_render=json


### Template tags

{% twitter oembed https://twitter.com/rubygems/status/518821243320287232 %}

{% oembed http://www.youtube.com/watch?v=Sv5iEK-IEzw %}

{% gist 1027674 %} 


### Install server

sudo apt-get install ruby ruby-dev make gcc nodejs zlib1g-dev 

npm install -g bower

gem install bundler
gem install ppjson



ppjson -fi _data/XXX.json