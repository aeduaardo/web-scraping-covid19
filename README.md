## π About project
This project is an simple API developed to return updated data from COVID-19 in Brazil and in the world.

## π What information does the API provide?
As a whole, the API presents 4 information about COVID-19:

* π· Confirmed cases 
* π₯³ Recovered
* π Confirmed deaths
* β£οΈ Percentage of infected population  

This information is available in 02 (two) different routes: **/national** and **/world**.

#### π΄ NATIONAL
It presents the information cited for Brazil and all its states.  

#### π WORLD
It presents the information mentioned for all cases in the world and also presents the **BIGGEST CASES**, which brings the 20 (twenty) countries with the highest number of cases of the new coronavirus. If you want more countries, access the file [constants.py](constants.py) and change the variable **NUMBER_COUNTRIES**.  


β  Note: **Percentage of infected population** is not official informationand the values ββpresented are the responsibility of the creators of the project. In the /national the percentage of infected population was calculated from population estimates of Brazilian states for the year 2019. For the /world the percentage was obtained based on the world population, set at 7.79 billion, and the index for each country was calculated based on information collected from different sources. Bearing in mind that population data vary due to many factors, the Percentage of infected population is not an accurate data and it is only an estimate.

## π° Technologies
* π [**Python 3.6**]() or later.
* π§ͺ [**Flask**](https://flask.palletsprojects.com/en/1.1.x/)
* πͺ [**BeautifulSoup**](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)
* π [**Requests**](https://requests.readthedocs.io/en/master/)
* πΊ [**Virtualenv**](https://virtualenv.pypa.io/en/latest/)

## π― How to use?

1. Clone this repository.  
    ```
    git clone https://github.com/aeduaardo/covid_api
    ```
2. Install virtualenv. If you already have it, skip this step.
    ```
    pip install virtualenv
    ```
3. Enter the project folder create a new virtualenv.
    ```
    virtualenv venv_name
    ```
4. Start your virtualvenv.
    ```
    Linux: source venv_name/bin/activate

    Windows: venv_name\Scripts\activate
    ```
5. Inside the project folder there is a requirements.txt file, which contains the project requirements, install it.
    ```
    pip install -r requirements.txt
   ```
6. Now, start the project.
    ```
    python app.py
    ```  

## π§± How to contribute?
This project was my own initiative to compose my development portfolio. If you want to contribute to the project, I will be very grateful, I am starting now in development and any support that helps me to evolve will be very well regarded, even criticism. If you want to contribute, send your Pull Requests and I will be happy to evaluate them, just follow the following steps:

1. Fork this repository.  
2. Create a **branch** for your update (git checkout -b feature/feature_name).
3. Commit (git commit -m "your commit").
4. Push (git push origin feature/feature_name).
5. Create a new **Pull Request**.

Contact me:

* π§ E-mail: aeduaardo.dev@gmail.com
* π Linkedin: www.linkedin.com/in/aeduaardo  


## βοΈ License
This project is licensed under the MIT license - see the file [LICENSE](LICENSE) and learn more details. 

