### nan_models

create table sponsort(
  id int primary key autoincrement ,
  nom_entreprise varchar(50),
  email varchar (50),
  telephone varchar (50),
  logo blob
  );

  
create table demande_sponsort(
  id int primary key autoincrement,
  nom_entreprise varchar(50),
  email varchar (50),
  telephone varchar (50),
  message text
  );
  
create table candidats(
  id int primary key autoincrement,
  nom varchar (50),
  prenom varchar (50),
  email  varchar (50),
  telephone varchar (50)
  );
  
create table article_blog(
  id int primary key autoincrement,
  titre varchar (50),
  contenu varchar (50),
  date_publication  date,
  image blob
  );
  
create table  temoignage(
  id int primary key autoincrement,
  auteur varchar (50),
  message varchar (50),
  image blob 
  );
  
create table  newsletter(
  id int primary key autoincrement,
  email varchar (50)
  );

create table foir_aq  (
  id int primary key autoincrement,
  titre_question varchar (50),
  reponse varchar (50)
  );
  
create table projet(
  id int primary key autoincrement,
  titre_projet varchar (50),
  nom_auteur varchar (50),
  description varchar (50),
  date_publication varchar (50),
  github_lien varchar (50)
  );
  
create table service (
   id int primary key autoincrement,
   titre_service varchar (50),
   description varchar (50),
   logo blob
   );
   
   
##   CONFIGURATION 

create table home_config (
  page_title varchar (50),
  page_sub_title varchar (50)
  );
 
create table HomeFirstSectionConfig (
  image blob,
  titre varchar (50),
  description varchar (50),
  second_titlr varchar (50),
  seconddescription varchar (50)
  );
  
create table HomeSecondSectionConfig (
  image blob,
  titre varchar (50),
  description varchar (50),
  second_titlr varchar (50),
  seconddescription varchar (50)
  );
  
create table HomeSponsorConfig (
  titre varchar (50),
  action varchar (50),
  description varchar (50),
  );

create table ThirdSection (
  action varchar (50),
  titre varchar (50),
  );
  
create table newsletterConfig (
  image blob,
  titre varchar (50)
  );

```





    
   



  
  

