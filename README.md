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
    option a) attempt to make contact with 1997mopeds to DL data directly. 
      future updates will have to pulled on a regular basis  
    option b) 
      write and use a Web Crawler to DL the data auto-magically. put crawler on a periodic schedule to pull and update data  
    looks like like a combination of users,text data, and pictures 
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
  
