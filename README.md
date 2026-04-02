# Liquid Light Tech Test

You are tasked with creating a postcode lookup tool which lists attractions ordered by distance from the postcode entered.

We expect this to take around 2–3 hours.

## Brief

### Technical

Using PHP, CSS, HTML and JavaScript add a form to `includes/main.php` which, when submitted, displays a list of closest **5** attractions, ordered by distance from the postcode entered. The data is sourced from `assets/data.csv`.

Use `https://api.getthedata.com` to convert the postcodes to latitude and longitude to allow calculation of distance in miles

**[Documentation to the API](https://www.getthedata.com/apis)**

E.g.

```code
GET https://api.getthedata.com/postcode/{postcode}
```

**Note**: The CSV file is read-only and must not be modified — do not add, remove, or edit any data within it.

### Design

The following mockup has been provided

![Design mockup](./mockup.png)

**Note**: The data in the mockup is example data.

## Considerations

### We are looking for

- Clean, reusable, object-orientated code
- A clean and responsive CSS solution with custom properties and other modern CSS features
- Handling of missing/incomplete data
- Good git practices (e.g. atomic commits, work on a branch)
- JavaScript should be used somewhere in the solution — how and where is up to you.
- Semantic and accessible HTML

### Notes

- Don't fret over the PHP file locations, the contents of the files are more important.
- You only need to support the latest browsers with CSS and JavaScript

## Setup

### System requirements

- Docker

### Getting Started

1. Fork the repository at https://github.com/liquidlight/tech-test-postcode-api — we recommend making your fork **private**
2. Clone your fork locally and create a branch to work on
3. Start the local server from the project root:

```bash
docker run -p 8080:80 -v .:/var/www/html php:8.3-apache
```

4. Visit [http://localhost:8080](http://localhost:8080) and edit your files

## Submission

When you are happy with your work:

1. Open a merge request on your own fork (from your working branch into your `main`)
2. Either share the link with us, or if you kept the repository private, invite `liquidlightuk` as a member so we can review it
