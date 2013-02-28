## New Relic Wikipedia Plugin

### Instructions for running the Wikipedia agent

1. Go to <a href="https://github.com/newrelic-platform/newrelic_wikipedia_plugin/tags" target="_blank">the tags list</a> and find the latest tar.zip.
2. Download and extract the source
3. run `bundle install`
4. Copy `config/template_newrelic_plugin.yml` to `config/newrelic_plugin.yml`
5. Edit `config/newrelic_plugin.yml` and replace "YOUR_LICENSE_KEY_HERE" with your New Relic license key
6. Execute `./newrelic_wikipedia_agent`