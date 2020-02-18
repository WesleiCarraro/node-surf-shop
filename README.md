# Surf-Shop

This is a node.js MVC application for a surf-shop magazine.

Actually it has some bugs so, if you want to cooperate, feel free. 

But it is kinda considerable app.

````
imports:
const express = require('express');
const engine = require('ejs-mate');
const path = require('path');
const favicon = require('serve-favicon');
const logger = require('morgan');
const cookieParser = require('cookie-parser');
const passport = require('passport');
const User = require('./models/user');
const session = require('express-session');
const mongoose = require('mongoose');
const methodOverride = require('method-override');
const mbxGeocoding = require('@mapbox/mapbox-sdk/services/geocoding');
const faker = require('faker');
const Post = require('./models/post');
const cities = require('./cities');
const crypto = require('crypto');
const cloudinary = require('cloudinary');
const cloudinaryStorage = require('multer-storage-cloudinary');
const passport = require('passport');
const mapBoxToken = process.env.MAPBOX_TOKEN;
const sgMail = require('@sendgrid/mail');
const geocodingClient = mbxGeocoding({ accessToken: mapBoxToken });
const mongoose = require('mongoose');
const Schema = mongoose.Schema;
const mongoosePaginate = require('mongoose-paginate');
const router = express.Router();
const multer = require('multer');

````

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)