# node-web-server

Running node.js web-server using express.js and handlebars 

## To run web-server locally

node src/app.js  

## Structure
.
├── package.json
├── package-lock.json
├── public
│   ├── css
│   │   └── styles.css
│   ├── img
│   │   └── weather.png
│   └── js
│       └── app.js
├── README.md
├── src
│   ├── app.js
│   └── utils
│       ├── forecast.js
│       └── geocode.js
└── templates
    ├── partials
    │   ├── footer.hbs
    │   └── header.hbs
    └── views
        ├── 404.hbs
        ├── about.hbs
        ├── help.hbs
        └── index.hbs