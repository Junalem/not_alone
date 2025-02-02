# <img width="120" alt="Screen Shot 2022-11-22 at 5 49 15 PM" src="https://user-images.githubusercontent.com/114731843/205795470-8cfa82c6-526a-46fc-a3bf-595ff7eb0b62.png"> [Not Alone](https://www.not-alone.online/)

Web application developed for [NPO OpSafe](http://opsafeintl.com/) (hosts camps for kids that have suffered from traumatic experiences) for fast finding volunteers over the world and contacting them immediately when you need them by location. Application focused on a database of OpSafe's volunteers and includes a mailer for contacting them.
With this app you can find information about previous camps.

<div class="d-flex">
<img width="400" alt="image" src="https://user-images.githubusercontent.com/114731843/205537638-45a4d380-8129-4921-840e-903396fa95de.png">
<img width="400" height="220" alt="image" src="https://user-images.githubusercontent.com/114731843/205544526-4d73fc99-710f-4b54-9a8f-5813f9d813eb.png">
</div>

### 

Create a new camp and find all upcoming camps by location. Find camps where you are joining. Send messages by location for volunteers by creating new camp.

<div class="d-flex">
<img width="400" alt="image" src="https://user-images.githubusercontent.com/114731843/205541944-47fd1980-c898-4aa8-8402-4757a361a544.png">
<img width="400" alt="image" src="https://user-images.githubusercontent.com/114731843/205542196-e039179d-b802-421d-9a54-c396a601fa1e.png">
</div>

### 

As a user, you can apply for camp and choose a role you would like to help. Also can leave feedback about previous camps (share your experience about camp)

<div class="d-flex">
<img width="400" height="260" alt="image" src="https://user-images.githubusercontent.com/114731843/205542593-eb89d62a-2c54-44ca-9d92-dd85ad81e1df.png">
<img width="400" alt="image" src="https://user-images.githubusercontent.com/114731843/205544146-eeb63fd0-9fa1-4eda-a089-c49ead0e1f99.png">
</div>

### 

As a camp director you can accept volunteers and add them for camp roles.
<img width="1400" alt="image" src="https://user-images.githubusercontent.com/114731843/205543637-ef422c07-1888-40ff-b5c9-e0f907998027.png">

## Getting Started
### Setup

Install gems
```
bundle install
```
Install JS packages
```
yarn install
```

### ENV Variables
Create `.env` file
```
touch .env
```
Inside `.env`, set these variables. 
```
CLOUDINARY_URL=your_own_cloudinary_url_key
MAPBOX_API_KEY=your_own_mapbox_api_url_key
POSTMARK_API_TOKEN=your_own_postmark_api_url_key
```

### DB Setup
```
rails db:create
rails db:migrate
rails db:seed
```

### Run a server
```
rails s
```

## Built With
- [Rails 7](https://guides.rubyonrails.org/) - Backend / Front-end
- [Stimulus JS](https://stimulus.hotwired.dev/) - Front-end JS
- [Heroku](https://heroku.com/) - Deployment
- [PostgreSQL](https://www.postgresql.org/) - Database
- [Bootstrap](https://getbootstrap.com/) — Styling
- [Figma](https://www.figma.com) — Prototyping

## Acknowledgements
Inspired by work of OpSave owner Jonathan Wilson.
## Team Members
- [Yulia Naumenko](https://github.com/Junalem)
- [Keita Wilson](https://github.com/dkwilson1991)
- [Savithri Wewala](https://github.com/Sabi95)
- [Ayhem Chelly](https://github.com/41FUTURE)

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
This project is licensed under the MIT License
