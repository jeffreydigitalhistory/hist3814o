    1  history
    2  mkdir wget-activehistory
    3  cd wget-activehistory/
    4  wget http://activehistory.ca/papers/
    5  ls
    6  wget -r --no-parent -w 2 --limit-rate=20k http://activehistory.ca/papers/
    7  wget -m -w 2 --limit-rate=20k http://activehistory.ca
    8  history > historywgettutorial.md
