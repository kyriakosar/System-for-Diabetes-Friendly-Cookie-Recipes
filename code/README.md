# Computational Creativity - Cookies recipes for diabetic people


## Brief Description
This project shows how a cookie recipe for diabetic people can be generated. The procedure is relatively straightforward. Firstly, we retrieved a large set of recipes for diabetic people. We perform some preprocessing such as cleaning the acquired data and enriching them with more metadata. This results in a complete knowledge base that we utilize for generating novel recipes. The generation process is basically an implementation of evolutionary algorithms consisting of the following five stages: selection, crossover, mutation, normalization, and evaluation. Afterward, we evaluate our system regarding its novelty by comparing the returned recipes to the ones stored in our knowledge base. Finally, we build a cookbook to present the ingredients and the steps for making three tasteful cookie recipes. 


## Files
- web_scraper.ipynb: A python notebook that is able to retrieve recipes from four different webpages. 

- instructions.ipynb: A python notebook for presenting a generated recipe.

- cookieGenerator.ipynb: The main program. It gets a yaml file as input (that represents the knowledge base) and it generates a novel cookie recipe. It also consists the evaluation part regarding the process of examining the creativity of our system.

- recipes.json: the knowledge base with all 91 stored preprocessed recipes.

- tasteofhome.json, everydaydiabetic.json, eatingwell.json, allrecipes.json: the data collected by using the webscraper.ipynb for the corresponding webpages


## How to run 
- Get the four json files with unprocessed data:
    - run all cells in web_scraper.ipynb

- Generate a new recipe:
    - run all cells in cookieGenerator.ipynb


## License
MIT License
