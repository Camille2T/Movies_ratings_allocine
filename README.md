# Movies_ratings_allocine

AlloCiné (http://www.allocine.fr/) is a company which provides information on French cinema and provide ratings from the press and from their users for a large number of movies . 

## Dataset
The dataset has been scrapped by another contributor (a big thanks to him!)  (https://github.com/ibmw/Allocine-project).    
It contains 59,966 movies. 

The Columns :
`movie_title` : the movies title (in French)   
`release_date`: the original release date   
`re_release_date`: the re-release date   
`duration`: the movies length  
`genre` : the movies types (as an array, up to three different types)   
`directors` : movies directors (as an array)   
`actors` : main movie characters (as an array)   
`nationality`: nationality of the movies (as an array)   
`press_rating`: press ratings (from 0 to 5 stars)   
`nber_press_vote`: number of press votes   
`user_rating`: AlloCiné users ratings (from 0 to 5 stars)    
`nber_user_vote` : number of users votes   

## Analysis
The notebook focus on the analysis of the discrepancies between press' and audience's ratings on the 10,424 movies that have both press and users ratings. Three insights are given on potential bias of the critics toward.  
