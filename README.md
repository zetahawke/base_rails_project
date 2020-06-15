# Rails base project

Rails base website project.

## Description

This rails project contains:
- Ruby latest version
- Rails latest version
- Devise (default user with email created)
- Materialize CSS
- Webpacker with angular
- All JS and CSS tools implemented
- Base routes
- Admin namespace
- Base layout structure
- Slim markup instead of Erb

## Installation

Make sure to have all the necessary stuff to start building this up.

### Pre Requisites
- Ruby 2.6.1
- Rails 6.0.3.1
- Bundler >= 2.14
- Postgresql >= 9.2 (pg_cli and pg gem >= 0.18)

```bash
bundle install
rake db:create
rake db:migrate
yarn install
```

Note: Replace all `Rails base project`, `RailsBaseProject` and `rails_base_project` coincidences in order to replace project name.

## Usage

```bash
rails s (-p port) (-b ip)
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

All Pull Request must be made against 'stable' branch

## License
[MIT](https://github.com/zetahawke/base_rails_project/blob/master/LICENSE)

## Credits
[Zetahawke](https://www.github.com/zetahawke/)