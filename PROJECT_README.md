# TVS PGMIB PROJECT POC

## Non Technical(`Overview of PGM APP`)

### What is PGM
- Application which encourages a mechanic to buy TVS genuine parts.

### Why we need PGM
- Encourage mechanics to buy genuine parts.

### User journey

- Mechanic login/signup
    - Shows homepage
        - see parts catalogue
        - see training section
        - see reward catalogue section
        - see support section
        - see referral section
        - see accessories catalogue
        - see referral section
    - select parts from parts catalogue
    - locate the dealer store selling the selected parts
    - scan parts to check whether part is genuine or not
    - purchase the parts - `??`
    - refer and reward shows list of referrals and reward earned for that referalls
    - shows training resources for selected parts 

### Features
- Buy genuine parts
- loyality points reward
- parts catalogue
    - contains list of products and information of all the parts needed to create that product which help mechanic in searching a part for particular product
    - `Example`: engine oil,tyres in a bike
- accessories and merchandise
    - contains list of products and information of all the additional parts(`which tvs doesn't manufacture`) needed for a product which help mechanic in searching a part for particular product
    - `Example`: helmet,matting,safety guards in a bike
- training management
    - information related to parts and future launches
- Rewards program
- store list of mechanics who have bought products from the app and also the information about the dealer from whom he has purchased the product
- Support & announcement
- Referral program
- multi language support

## Technical(Architecture && TECHSTACK && TESTING  && DEPLOYMENT)

### Architecture

<br>

![PGM ARCHITECTURE](assets/pgm_architecture.png)

<br>



### Entities | Schema
- mechanics
- parts
- rewards
- catalogues
- accessories
- training
- dealerStores
- products
- referrals
- support
- mechanic_parts
- parts_catalogue
- rewards_catalogue
- training_mechanic
- location

### Architecture

### FAMILIAR
- Web Front Layer – React.js, JavaScript, HTML5 & CSS3
- 
### UNFAMILIAR
- Mobile Front Layer – Flutter (for Android and iOS platforms)
- API Layer – Python/Django
- Database Layer – PostgreSQL   Azure MSSQL
- Notification Layer – Firebase
- File Storage Layer – Azure Blob
- Batch Processes – Azure Function App Instance to be shared to deploy Development Code for Batch Processing
- Microsoft azure
- google maps

### Testing 
- Security testing
- feature testing

## TO-DO
- What is MVVM design pattern
- What is Active/Passive disaster recovery strategy
## Doubts
- Right now do we have repair order functionality in app
- Is the PGM mobile app live
    - If yes on which feature we need to work
    - If no do we need to develop app from scratch
- Is the PGM web app live
    - If yes on which feature we need to work
    - If no do we need to develop the app from scratch
- What type of data is stored in azure storage and database
- Does mechanic can buy parts from PGM app or it is only used to locate the TVS genuine parts





