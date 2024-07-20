# SCT_SD_4
Create a program that extracts product information, such as name, prices, and ratings, from an online e-commerce website and stores the data in a structured format like a CSV file.<br/>

This task is achieved using Java and aditional support from libraries to complete the task.It can use either a basic local mock e-commerce website as input by using the file path or an API url of an E-Commerce website to fetch the details namely Name, Price, Rating, Description and Image of the Product and store it in CSV file.<br/>

To run the project typ these commands in the terminal: <br/>
- ```javac -cp "lib/jsoup-1.18.1.jar;lib/commons-csv-1.6.jar;lib/json-20230227.jar" -d bin src/ProductDetailExtractor.java``` <br/>
- ```java -cp "bin;lib/jsoup-1.18.1.jar;lib/commons-csv-1.6.jar;lib/json-20230227.jar" ProductDetailExtractor``` <br/>