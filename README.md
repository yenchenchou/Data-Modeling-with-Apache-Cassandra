# Project Title
Data Modeling with Apache Cassandra using music stream data

## Introduction
The database is about making queries from a music stream data companies with Cassandra

### Prerequisites
The following packages are needed for running the code:
``` Python
import csv
import glob
import json
import numpy as np
import os
import re

import cassandra
import pandas as pd

from cassandra.cluster import Cluster
```

## queries to complete
1. Give the artist, song title and song's length in the music app history that was heard during  sessionId = 338, and itemInSession  = 4

2. Give only the following: name of artist, song (sorted by itemInSession) and user (first and last name) for userid = 10, sessionid = 182
    
3. Give every user name (first and last) in my music app history who listened to the song 'All Hands Against His Own'