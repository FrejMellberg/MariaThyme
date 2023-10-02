# MariaThyme
### Multiple remote sensor monitoring through Hibernate backend &amp; Thymeleaf frontend


This was a group-project at Nackademin to learn more about System Integration.
We were four in the group and each one of us used either a Raspberry pi or an arduino
to setup a temperature sensor and send the data to a remote Mariadb-database.
The data from that database was then retrived and handled by a spring boot/Hibernate program
and presented with html/thymeleaf templates in a browser.

<p><br><br></p>

## The Setup

![setup](/arkitektur.png)

### The frontend will display several buttons representing functions 

![frontend](/frontend.png)

#### Functions included in TempController
* Show Everyones Data
* Show individual Data
* Find/show Latest
* Find/Show top-5 Highest Temperature
* Find/Show top-5 Lowest Temperature
