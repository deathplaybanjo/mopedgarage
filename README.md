# mopedgarage
Remake the garage.1977mopeds.com website

tasks:
aquire data
  option a) attempt to make contact with 199mopeds to DL data directly
    future updates will have to pulled on a regular basis
  option b) write and use a Web Crawler to DL the data auto-magically
    put crawler on a periodic schedule to pull and update data
  looks like like a combination of users,text data, and pictures
frontend
  TBD
services
  TBD
backend
  webcrawler data input
    transform data into a useful format
      look into elactic stack options
    text and pictures
    track pages for future updates
  elaticsearch (lucene)
    indexing configuration
    searching by words or phrases
    sorting
      most/leaset recent
      fuzzy
      phrase
  
