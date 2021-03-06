# Tech radar

You can access the published radar [here](https://engineering.getadministrate.com/tech-radar/).

## What ?

The Radar is a document that sets out the changes that are currently interesting regarding software development at Administrate.

## Why ?

We have developed this radar because we want to document the usage of technologies in our company in an easy way.
People who want to document something just need to push a new md file in the repository.

![tech-radar](/assets/images/preview.png)
![tech-radar](/assets/images/preview-rings.png)

## How to add new technologies ?

The tech radar is built based on the elements specified in the jekyll collections define in the \_config.yml file.

So, to add content to the radar :

- **Create a new md file** under the desired category folder
  - \_languages-frameworks
  - \_platforms
  - \_techniques
  - \_tools
- **Add meta data to the file** (in the front matter ---)
  - layout: details
  - filename: [name of the md file]
  - name: [title of the page]
  - image: [relative image url]
  - category: [languages-frameworks or platforms or techniques or tools]
  - ring: [Adopt or Trial or Assess or Drop]

Once you have created a new file, you can push it.
The related item will be presented on the radar.

## Update the radar javascript

The javascript source code of the radar is available here : https://github.com/agilepartner/tech-radar-js

To integrate the built code you have to :

- Add front matter at the top of the html file

```
    ---
    title: Radar
    layout: radar
    ---
```

- Add front matter at the top of the main.js file

```
    ---
    ---
```

## Setup your dev environment

```
gem install bundler
bundle install
```

## Serve the radar with jekyll

```
bundle exec jekyll serve
```

## Build the radar with jekyll

```
bundle exec jekyll build
```

## Configuration
To configure the radar you need to set the url property of the _config.yml file :
```
url: "https://[your-user].github.io/"
```

## Serve the radar with Docker
```
docker-compose up
```

## Docker build image
```
docker build -t tech-radar .
```
