# Universal Npm Scripts Boilerplate

## About the Project

Boileplate for building small projects with JS and Sass.

### Features
- **Browsersync:** Local server with HMR
- **Imagemin:** Image minifying with Imagemin
- **EditorConfig и Prettier:** Code formatting on commit

### Project Structure
All development takes place in the `src` directory.
- `fonts`
- `img`
- `js`
- `scss`

## Installation and Usage
```
npm install
```

To make the pre-commit hook work, you need to run `npm install` when the project is already initialized as a Git repository.

If the project is initialized as a repository later, you need to additionally execute `npm run prepare`.

### Development
```
npm start
```

### Production
```
npm build
```

## Contact
Dmitry Sviridov  
Telegram: [slamach](https://t.me/slamach)  
Email: sviridov.dvv@gmail.com
