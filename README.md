# JDEV-Exam
## Requirements
- PHP -> 8.0+
- Composer -> latest version
- MySQL -> 5.8+
- NodeJS -> LTS

## Installation
1. Clone this repository to your local machine
```sh
$ git clone https://github.com/JayEusebio/JDEV-Exam.git
```
2. CD to project directory then setup Composer and NPM
```sh
$ cd path/to/JDEV-Exam
$ composer install
$ npm install
```
3. Migrate your database
```
$ php artisan migrate:fresh
```

## Usage
- Open a terminal instance then run the following
```sh
$ php artisan serve
```
- Open another terminal instance then run the following
```sh
$ npm run dev
```
