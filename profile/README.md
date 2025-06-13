# TravelMate.AI - DBS Coding Camp 2025 Capstone Project 🤖

<div align="center">
    <img src="https://i.postimg.cc/kGz7SVnL/Screenshot-2025-05-20-222015.png" alt="TravelMate.AI" width="20%" />
</div>

## About the Project 🚀
This project is the development of an AI Travel Advisor website, featuring a chatbot capable of providing travel tips, planning assistance, and more. Additionally, it offers a destination recommendation system tailored to the user's preferences. The system leverages an intent classification-based machine learning model, seamlessly integrated into a user-friendly website interface.

**Theme:** Social, Culture, Tourism

**Background:** 
- Difficulty finding personalized travel destinations: Travelers struggle to discover places that truly match their individual preferences in the digital age.
- Inefficient and impersonal planning: The current trip planning process is often inefficient and lacks a personal touch.
- Confusing, scattered information: Information is spread across various platforms without proper integration, leading to confusion.

## Tech Stack ⚙️
- **Python**
- **TensorFlow** / **Keras**
- **Keras Tuner**
- **Scikit-learn**
- **Pandas**, **NumPy**
- **Cosine Similarity**
- **React.js**, **Tailwind CSS**, **Vite**
- **Node.js**, **Express.js**
- **MongoDB** 
- **Vercel**, **Render**, **GitHub**

## Key Features 🧑‍💻

**Machine Learning**
- Tourism spot recommendations
- Natural language understanding
- Contextual responses
- Real-time data processing

**Front End Back End**
- RESTful API integration
- Secure user input handling
- Responsive web interface
- Real-time chat communication
- MongoDB database integration

## Project Structure 📊

**FrontEnd/BackEnd**
```
├───backend
│   ├───config
│   ├───controllers
│   ├───data
│   ├───middleware
│   ├───models
│   ├───node_modules
│   │   ├───.bin
│   │   ├───@mongodb-js
│   │   │   └───saslprep
│   │   │       └───dist
│   │   ├───@types
│   │   │   ├───webidl-conversions
│   │   │   └───whatwg-url
│   │   │       └───lib
│   │   ├───accepts
│   │   ├───anymatch
│   │   ├───balanced-match
│   │   │   └───.github
│   │   ├───bcryptjs
│   │   │   ├───bin
│   │   │   └───umd
│   │   ├───binary-extensions
│   │   ├───body-parser
│   │   │   └───lib
│   │   │       └───types
│   │   ├───brace-expansion
│   │   ├───braces
│   │   │   └───lib
│   │   ├───bson
│   │   │   ├───etc
│   │   │   ├───lib
│   │   │   ├───src
│   │   │   │   ├───parser
│   │   │   │   │   └───on_demand
│   │   │   │   └───utils
│   │   │   └───vendor
│   │   │       ├───base64
│   │   │       └───text-encoding
│   │   │           └───lib
│   │   ├───buffer-equal-constant-time
│   │   ├───bytes
│   │   ├───call-bind-apply-helpers
│   │   │   ├───.github
│   │   │   └───test
│   │   ├───call-bound
│   │   │   ├───.github
│   │   │   └───test
│   │   ├───chokidar
│   │   │   ├───lib
│   │   │   └───types
│   │   ├───concat-map
│   │   │   ├───example
│   │   │   └───test
│   │   ├───content-disposition
│   │   ├───content-type
│   │   ├───cookie
│   │   ├───cookie-signature
│   │   ├───cors
│   │   │   └───lib
│   │   ├───csv-parser
│   │   │   └───bin
│   │   ├───debug
│   │   │   └───src
│   │   ├───depd
│   │   │   └───lib
│   │   │       └───browser
│   │   ├───dotenv
│   │   │   └───lib
│   │   ├───dunder-proto
│   │   │   ├───.github
│   │   │   └───test
│   │   ├───ecdsa-sig-formatter
│   │   │   └───src
│   │   ├───ee-first
│   │   ├───encodeurl
│   │   ├───es-define-property
│   │   │   ├───.github
│   │   │   └───test
│   │   ├───es-errors
│   │   │   ├───.github
│   │   │   └───test
│   │   ├───es-object-atoms
│   │   │   ├───.github
│   │   │   └───test
│   │   ├───escape-html
│   │   ├───etag
│   │   ├───express
│   │   │   └───lib
│   │   ├───fill-range
│   │   ├───finalhandler
│   │   ├───forwarded
│   │   ├───fresh
│   │   ├───function-bind
│   │   │   ├───.github
│   │   │   └───test
│   │   ├───get-intrinsic
│   │   │   ├───.github
│   │   │   └───test
│   │   ├───get-proto
│   │   │   ├───.github
│   │   │   └───test
│   │   ├───glob-parent
│   │   ├───gopd
│   │   │   ├───.github
│   │   │   └───test
│   │   ├───has-flag
│   │   ├───has-symbols
│   │   │   ├───.github
│   │   │   └───test
│   │   │       └───shams
│   │   ├───hasown
│   │   │   └───.github
│   │   ├───http-errors
│   │   │   └───node_modules
│   │   │       └───statuses
│   │   ├───iconv-lite
│   │   │   ├───.github
│   │   │   ├───.idea
│   │   │   │   ├───codeStyles
│   │   │   │   └───inspectionProfiles
│   │   │   ├───encodings
│   │   │   │   └───tables
│   │   │   └───lib
│   │   ├───ignore-by-default
│   │   ├───inherits
│   │   ├───ipaddr.js
│   │   │   └───lib
│   │   ├───is-binary-path
│   │   ├───is-extglob
│   │   ├───is-glob
│   │   ├───is-number
│   │   ├───is-promise
│   │   ├───jsonwebtoken
│   │   │   └───lib
│   │   ├───jwa
│   │   ├───jws
│   │   │   └───lib
│   │   ├───kareem
│   │   ├───lodash.includes
│   │   ├───lodash.isboolean
│   │   ├───lodash.isinteger
│   │   ├───lodash.isnumber
│   │   ├───lodash.isplainobject
│   │   ├───lodash.isstring
│   │   ├───lodash.once
│   │   ├───math-intrinsics
│   │   │   ├───.github
│   │   │   ├───constants
│   │   │   └───test
│   │   ├───media-typer
│   │   ├───memory-pager
│   │   ├───merge-descriptors
│   │   ├───mime-db
│   │   ├───mime-types
│   │   ├───minimatch
│   │   ├───mongodb
│   │   │   ├───etc
│   │   │   ├───lib
│   │   │   │   ├───bulk
│   │   │   │   ├───client-side-encryption
│   │   │   │   │   └───providers
│   │   │   │   ├───cmap
│   │   │   │   │   ├───auth
│   │   │   │   │   │   └───mongodb_oidc
│   │   │   │   │   ├───handshake
│   │   │   │   │   └───wire_protocol
│   │   │   │   │       └───on_demand
│   │   │   │   ├───cursor
│   │   │   │   ├───gridfs
│   │   │   │   ├───operations
│   │   │   │   │   ├───client_bulk_write
│   │   │   │   │   └───search_indexes
│   │   │   │   └───sdam
│   │   │   └───src
│   │   │       ├───bulk
│   │   │       ├───client-side-encryption
│   │   │       │   └───providers
│   │   │       ├───cmap
│   │   │       │   ├───auth
│   │   │       │   │   └───mongodb_oidc
│   │   │       │   ├───handshake
│   │   │       │   └───wire_protocol
│   │   │       │       └───on_demand
│   │   │       ├───cursor
│   │   │       ├───gridfs
│   │   │       ├───operations
│   │   │       │   ├───client_bulk_write
│   │   │       │   └───search_indexes
│   │   │       └───sdam
│   │   ├───mongodb-connection-string-url
│   │   │   └───lib
│   │   ├───mongoose
│   │   │   ├───dist
│   │   │   ├───lib
│   │   │   │   ├───cast
│   │   │   │   ├───cursor
│   │   │   │   ├───drivers
│   │   │   │   │   ├───browser
│   │   │   │   │   └───node-mongodb-native
│   │   │   │   ├───error
│   │   │   │   ├───helpers
│   │   │   │   │   ├───aggregate
│   │   │   │   │   ├───cursor
│   │   │   │   │   ├───discriminator
│   │   │   │   │   ├───document
│   │   │   │   │   ├───error
│   │   │   │   │   ├───indexes
│   │   │   │   │   ├───model
│   │   │   │   │   ├───path
│   │   │   │   │   ├───populate
│   │   │   │   │   ├───projection
│   │   │   │   │   ├───query
│   │   │   │   │   ├───schema
│   │   │   │   │   ├───schematype
│   │   │   │   │   ├───timestamps
│   │   │   │   │   ├───topology
│   │   │   │   │   └───update
│   │   │   │   ├───options
│   │   │   │   ├───plugins
│   │   │   │   ├───schema
│   │   │   │   │   └───operators
│   │   │   │   └───types
│   │   │   │       ├───array
│   │   │   │       │   └───methods
│   │   │   │       └───documentArray
│   │   │   │           └───methods
│   │   │   └───types
│   │   ├───mpath
│   │   │   ├───lib
│   │   │   └───test
│   │   ├───mquery
│   │   │   ├───.github
│   │   │   └───lib
│   │   │       └───collection
│   │   ├───ms
│   │   ├───negotiator
│   │   │   └───lib
│   │   ├───nodemon
│   │   │   ├───bin
│   │   │   ├───doc
│   │   │   │   └───cli
│   │   │   └───lib
│   │   │       ├───cli
│   │   │       ├───config
│   │   │       ├───help
│   │   │       ├───monitor
│   │   │       ├───rules
│   │   │       └───utils
│   │   ├───normalize-path
│   │   ├───object-assign
│   │   ├───object-inspect
│   │   │   ├───.github
│   │   │   ├───example
│   │   │   └───test
│   │   │       └───browser
│   │   ├───on-finished
│   │   ├───once
│   │   ├───parseurl
│   │   ├───path-to-regexp
│   │   │   └───dist
│   │   ├───picomatch
│   │   │   └───lib
│   │   ├───proxy-addr
│   │   ├───pstree.remy
│   │   │   ├───lib
│   │   │   └───tests
│   │   │       └───fixtures
│   │   ├───punycode
│   │   ├───qs
│   │   │   ├───.github
│   │   │   ├───dist
│   │   │   ├───lib
│   │   │   └───test
│   │   ├───range-parser
│   │   ├───raw-body
│   │   ├───readdirp
│   │   ├───router
│   │   │   └───lib
│   │   ├───safe-buffer
│   │   ├───safer-buffer
│   │   ├───semver
│   │   │   ├───bin
│   │   │   ├───classes
│   │   │   ├───functions
│   │   │   ├───internal
│   │   │   └───ranges
│   │   ├───send
│   │   ├───serve-static
│   │   ├───setprototypeof
│   │   │   └───test
│   │   ├───side-channel
│   │   │   ├───.github
│   │   │   └───test
│   │   ├───side-channel-list
│   │   │   ├───.github
│   │   │   └───test
│   │   ├───side-channel-map
│   │   │   ├───.github
│   │   │   └───test
│   │   ├───side-channel-weakmap
│   │   │   ├───.github
│   │   │   └───test
│   │   ├───sift
│   │   │   ├───es
│   │   │   ├───es5m
│   │   │   ├───lib
│   │   │   └───src
│   │   ├───simple-update-notifier
│   │   │   ├───build
│   │   │   └───src
│   │   ├───sparse-bitfield
│   │   ├───statuses
│   │   ├───supports-color
│   │   ├───to-regex-range
│   │   ├───toidentifier
│   │   ├───touch
│   │   │   └───bin
│   │   ├───tr46
│   │   │   └───lib
│   │   ├───type-is
│   │   ├───undefsafe
│   │   │   ├───.github
│   │   │   │   └───workflows
│   │   │   └───lib
│   │   ├───unpipe
│   │   ├───vary
│   │   ├───webidl-conversions
│   │   │   └───lib
│   │   ├───whatwg-url
│   │   │   └───lib
│   │   └───wrappy
│   └───routes
└───frontend
    ├───public
    └───src
        ├───assets
        ├───components
        │   ├───auth
        │   ├───chatbot
        │   ├───sections
        │   └───ui
        ├───contexts
        ├───hooks
        ├───layouts
        ├───lib
        └───pages
```

**MachineLearning**
```
├── MachineLearning/
│   ├── dataset/
|       ├── cleaned_data_wisata.csv
|       ├── cleaned_data_resto.csv
|       └── cleaned_data_hotel.csv
│   ├── saved_model/
│   ├── data_cleaning.ipynb
│   ├── modelling.ipynb
│   ├── modelling_resto.ipynb
│   ├── modelling_hotel.ipynb
│   └── requirements.txt
```

## Our Team 👥

### Machine Learning Engineer

1. Danish Gyan Pramana
  - Institusi: Universitas Brawijaya
  - Email: danishgyanpramana2018@gmail.com
  - LinkedIn: [Danish Gyan Pramana](www.linkedin.com/in/danishgyanpramana)
  - GitHub: [vynnzz](https://github.com/vynnzz) 

2. Nikola Izzan Ar Rasheed
  - Institusi: Universitas Brawijaya
  - Email: izzannikola@gmail.com
  - LinkedIn: [Nikola Izzan Ar Rasheed](www.linkedin.com/in/nikolaizzan/)
  - GitHub: [nikolaizz](github.com/nikolaizz)

3. Taufik Neldi
  - Institusi: Universitas Brawijaya
  - Email: taufikneldi02@gmail.com
  - LinkedIn: [Taufik Neldi](www.linkedin.com/in/taufik-neldi-90aa50279)
  - GitHub: [Neldi30](https://github.com/Neldi30)

### Frontend/Backend Developer

1. Muhammad Rasyad Putra Ekardi
  - Institusi: Universitas Brawijaya
  - Email: rasyadp.e@gmail.com
  - LinkedIn: www.linkedin.com/in/rasyadekardi
  - GitHub: [rasyadpe](https://github.com/rasyadpe) 

2. Leonardez Flobert Gunawan
  - Institusi: Universitas Tarumanagara
  - Email: 
  - LinkedIn: www.linkedin.com/in/
  - GitHub: [LazerHart](https://github.com/LazerHart) 

3. Zahruldin [INACTIVE]
  - Institusi: Universitas Nurdin Hamzah
  - Email: 
  - LinkedIn: www.linkedin.com/in/
  - GitHub: [](https://github.com/) 

## 🏢 Supporting Institutions
Proyek ini dikembangkan sebagai bagian dari program:
**DBS Coding Camp 2025 By DBS Foundation**

© 2025 TravelMate.AI - DBS Coding Camp 2025 Capstone Project
