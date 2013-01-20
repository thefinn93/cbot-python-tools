python-cleverbot-tools
======================




A set of Python tools for the Cleverbot artificial intelligence algorithm

Requires:

- BeautifulSoup (for pof site scraping)

- gspread (google docs logging for Omegle bot)

- Django (for a particular unicode string decoding function)

Main files:

- omegle_bot.py: The Omegle cleverbot chat script

- pof_bot.py: The POF cleverbot dating script

The interface between Cleverbot and Python is based on the 'pycleverbot' library:

http://code.google.com/p/pycleverbot/

The interface between Omegle and Python is adapted from the 'pyomegle' library:

http://code.google.com/p/pyomegle/

The logging functionality for Google Spreadsheets uses the 'gspread' library:

https://github.com/burnash/gspread

TODO:
- OKCupid bot is in the works. OKC is much better designed than POF, so this may be tricky. At worst, Selenium might be needed for message automation. This isn't too challenging, but is a bit tedious.
- login information should probably be gathered from command line arguments
- Code for optionally dumping logs to IRC (as opposed to google docs)

