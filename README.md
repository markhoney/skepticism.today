# Skepticism Today

## Local testing

Ensure Ruby is installed and then install Jekyll:

```sh
gem install jekyll bundler
```

Install the required Gem files using:

```sh
bundle install
```

Then run the server using:

```sh
bundle exec jekyll serve
```

The server should then be available at [http://localhost:4000/](http://localhost:4000/).

## Audio File Data

Audio files should be uploaded to the podcast's [Internet Archive page](https://archive.org/details/skepticism-today), and then a data file must be downloaded and saved to the `_data` directory from the following URL:

[https://archive.org/metadata/skepticism-today?output=json](https://archive.org/metadata/skepticism-today?output=json)

## Styling

The [theme used](https://github.com/jonaharagon/jekyll-bootstrap-theme) by this website is a [Bootstrap 5](https://getbootstrap.com/docs/5.0/getting-started/introduction/) based theme, so any Bootstrap 5 components or classes can be used.

### Favicon

To add icons, use [Favicon Generator](https://realfavicongenerator.net/) and save the resulting files into a folder called `/assets/images/favicon`.

## Feed

The XML feed for the podcast is created using the [Apple Podcast reference](https://help.apple.com/itc/podcasts_connect/), and is tagged with [Apple's Category System](https://podcasts.apple.com/us/genre/podcasts/id26) as Religion & Spirituality -> Religion.
