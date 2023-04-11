# Usage

## Start development server

`docker build -t tkds/wiki:latest `

`docker run -it --rm -d -p 8000:8000 --name wiki -v .:/docs tkds/wiki:latest `

Then open your browser to http://localhost:8000
