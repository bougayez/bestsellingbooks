# Best Selling Books
A website to find best selling books in the current week.

## Where to get your API key?
To get the API key, go to this [website](https://developer.nytimes.com/docs/books-product/1/overview),
create an account and get your key.

## Required libraries
* C++ CROW : [Github](https://github.com/ipkn/crow)
* JSONCONS : [Github](https://github.com/danielaparker/jsoncons)

## Running
To run this project :
  1. Download/clone the project files
  2. Install GNU compiler on your machine
  3. Install CMAKE on your machine
  4. Go to the project directory, then to ``` build ``` directory
  5. Run ``` cmake .. ```
  6. Run ``` make ```
  7. Run ``` ./bestsellingbooks ```
  8. Now the web server started, open a browser and type in ``` localhost:18080 ```
  
## Using Docker
You can use Docker by building the file ``` Dockerfile ```

