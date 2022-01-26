# PCHS_AIRQ_MAC
Version 3 of the air quality for PCHS sensor. 


<h1> This repo consists of three files, "api.py", "sender.py", and "api"(the executable file). This current repo was rebuilt and reform from the first PCHS air quality repo. </h1>

<h2> How does this repo work? </h2>

<li> This project using the airly api, specifcally the Paulding County Highschool Airly Air Quality Sensors' id and its measurements.</li>
<li> Using different python packages (request package), in the api.py file, it sends a request to the api is and the data is pulled by the computer. </li>
<li> The data pulled by the api is reformated and pushed over to the sender.py file which is again reformated and pushes to the avaiable google sheets </li> 
