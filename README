A module to make integration between your KohanaPHP (v3.x) applications and Google's Analytics API a breeze

Fork of [KohAnalytics](http://github.com/matoakley/KohAnalytics) of [matoakley](http://github.com/matoakley) for Kohana 3.2. Use [GAPI](http://code.google.com/p/gapi-google-analytics-php-interface/)

# Configuration

1. Create `config/kohanalytics.php` (or copy from module directory)
2. Add username, password and report_id data

# Using

1. Statistics for monthes: `Kohanalytics::instance()->monthly_visit_count()`

You can add custom params `$start_date`, `$end_date` and `$metrics` (by default `array('pageviews', 'visits')`)

2. Statistics for days: `Kohanalytics::instance()->daily_visit_count()`

3. Custom statistics: `Kohanalytics::instance()->query('date', array('pageviews', 'visits'), NULL, 100)`