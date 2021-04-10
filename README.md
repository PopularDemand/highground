# High Ground Designs | From [Jekyll Agency](https://github.com/raviriley/agency-jekyll-theme-starter)


The Jekyll structure of this theme includes:

- the `page` layout allows custom pages, as seen in the legal and 404 pages
- `sitetext.yml` enables customization of homepage text
- `navigation.yml` enables fully customizable navigation
- `designs.yml` - High Ground specific service offerings
- `style.yml` enables fully customizable colors, background images, and other style-related things
- `_sass` - sass enabled style files
- `_layouts` - full page wrappers for congruent layouts between website pages
- `_layouts/default.html` - <html> wrapper layout. The parent layout for other layouts.
- `_includes` - templates available for use in multiple files
- `assets` - static images, stylesheets, javascripts, etc

## Installation

```bash
$ git clone git@github.com:HighGroundTech/business_template.git
# or
$ git clone https://github.com/HighGroundTech/business_template.git

$ bundle install
```

## Development
```bash
$ jekyll serve -lw
```

And open your browser at `http://localhost:4000`.

## Development notes

* When creating a new file within the `_sass` directory, you must add the file to the `@import` list within `/assets/css/agency.scss` file

* This theme uses [Bootstrap v5](https://getbootstrap.com) and its included [FontAwesome](https://fontawesome.com/icons) libraries. It's recommended to use the css utilities and icons provided by these libs for ease of development.

## Contributing

This project is intended to be a welcoming space for collaboration. If you have an idea, suggestion, feature request, etc., feel free to open an issue or pull request.
For bug reports, follow the provided template.


<!--

## Example Implementations

- [CV Enterprises](https://cventerprises.org)
- [Mortazavi Lab at UC Irvine](https://mortazavilab.github.io/)

-->
