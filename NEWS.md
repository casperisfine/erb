# Change Log

## 3.0.0

- Bump `required_ruby_version` to Ruby 2.7+ [#23](https://github.com/ruby/erb/pull/23)
- `ERB::Util.url_encode` uses a native implementation [#23](https://github.com/ruby/erb/pull/23)
- Fix a bug that a magic comment with a wrong format could be detected [#6](https://github.com/ruby/erb/pull/6)

## 2.2.3

- Bump `required_ruby_version` from 2.3 to 2.5 as it has never been supported [#3](https://github.com/ruby/erb/pull/3)

## 2.2.2

- `ERB.version` returns just a version number
- `ERB::Revision` is deprecated

## 2.2.1

- `ERB#initialize` warns `safe_level` and later arguments even without -w

## 2.2.0

- Ruby 3.0 promoted ERB to a default gem
