# Slim application.html

doctype html
html
  head
    title
      | Colombinobakery
    meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0"
    = stylesheet_link_tag    'application', media: 'all', 'data-turbolinks-track' => true
    = javascript_include_tag 'application', 'data-turbolinks-track' => true
    = csrf_meta_tags
  body
