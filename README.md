# What is FeedSpora?

FeedSpora posts RSS/Atom feeds to your social network accounts. It currently supports Facebook, Twitter, LinkedIn, Diaspora, Wordpress, Mastodon and Shaarli. It's a bot written in Python3 inspired from [Fefebot](https://github.com/svbergerem/fefebot).

# Installation

- Install dependencies: `pip install -r requirements.txt` (you may want to get `shaarpy` from [its repo](https://github.com/aurelg/shaarpy)).
- Then install FeedSpora with the usual `python setup.py install`.

# Configuration

- Create a config file out of the provided template `feedspora.yml.template`. The `enabled` directive is optional and allow you to selectively enable/disable accounts by setting it to `True` or `False`.

# Usage

- Publish all RSS/Atom entries to your account with: `python -m feedspora`
