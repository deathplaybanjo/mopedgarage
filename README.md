# mopedgarage
Remake the garage.1977mopeds.com website

## tasks:  
#### discus adding this module/app to MA host with Simon  
  ###### derrive requirements from existing system  
    expected performance restricitons  
    run testing and initial intensive processes on my home PC
    initial install  
    future data updates  
   
#### frontend  
  TBD  
#### services  
  TBD  
#### backend  
  ###### acquire data  
    write and use a Web Crawler to DL the data auto-magically. put crawler on a periodic schedule to pull and update data  
    looks like a combination of users(1:1) and pictures(x:1) each mapped to "moped project text data"
  ###### webcrawler data input  
    transform data into a useful format  
      look into elactic stack options  
    text and pictures  
    track pages for future updates  
  ###### elaticsearch (lucene)  
    indexing configuration  
    searching by words or phrases  
    sorting  
      most/leaset recent  
      fuzzy  
      phrase  
  
