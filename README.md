# carsharing

## Design choices


### Database
#### possibilities
- mySQL
- SQLite
- postgreSQL
#### our choice: SQLite
- complete database stored in a single cross-platform disk file
- very small and lightweight
- self-contained (no extra dependencies required)
- no seperate server process required (see [backend](#Backend))
- zero configuration / no setup
- cross-platform (Linux, MacOS, Android, iOS, Win32, WinCE, WinRT)

### Backend
... programming language (java, php, python, ...) ... our project: python ... reasons ...
#### possibilities
- Flask
- Django
#### our choice: Flask

### Frontend
#### possibilities
- React
- Angular
- Open UI5
#### our choice: (Open UI5 ??)
