# NutriAdmin HIPAA Training Docs

This is an overview training of HIPAA, with coverage of key definitions and provisions for the handing of HIPAA-relevant data. The material in this book is intended for individuals who work for organizations that provide technology and technology-enabled services to health systems, payers, physicians, pharma, and other healthcare organizations. It leans more heavily on the use of modern, cloud-based technologies than traditional client side software.

- The license for these docs can be found [here](https://github.com/daticahealth/training/blob/master/LICENSE.md)

# Getting Started

The NutriAdmin HIPAA Training docs are built using [Middleman](https://middlemanapp.com/), a static site generator. Please follow the [installation instructions](https://middlemanapp.com/basics/install/) for Middleman before continuing.

# Attribution

These training materials for NutriAdmin are an adaptation of Datica's training. Quoting Datica:

> Original material and content was created by [Datica Health, Inc,](https://datica.com) and is released as open source. Available educational material for HIPAA is largely outdated in its coverage of technology and utility to vendors is extremely limited. The goal of releasing this as open source is that the growing community of healthcare companies can contribute, enrich, and keep it relevant over time. Please email [training@datica.com](mailto:training@datica.com) with any questions or problems accessing the training.


Once you have Middleman installed and working you can complete the following to get a working copy of these docs on your local machine:

- `git clone https://github.com/catalyzeio/training.git`
- `cd training`
- `bundle install`

**Commands:**

- `rake build` generates the static HTML, CSS, and JavaScript files (`bundle exec middleman build`)
- `rake run` allows you to view the site locally
- `rake sass` compiles styles changes
- `rake serve_static` runs a simple web server in the build directory
