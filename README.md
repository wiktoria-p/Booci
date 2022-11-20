# Boocci - practice project of an home page online store
## Page description
-browsing the store's offer
-doing online shopping
-displaying discount codes and promotion conditions
### Technologies used
-HTML
-CSS
#### Problems and their solutions
-Footer that didn't want to stay at the bottom of the page
  html, body {
            margin: 0;
            padding: 0;
            width: 100%;
            height: 100%;
        }

        .container {
            min-height: 100%;
            position: relative;
            font-size: 17px;
            overflow-x: hidden;
        }
           footer {
            position: absolute;
            bottom: 0;
            width: 100%;
            margin: 0 auto;
            background-color: rgba(182, 170, 146, 0.74);
        }


        .foot {
            bottom: 0;
            color: black;
            display: flex;
            flex-direction: row;
            flex-wrap: nowrap;
        }
        ##### Planned developmentsnof the project
        -setting responsiveness for mobile devices
        -creating a funcional menu
        -creating an online shopping form
        
