# Kulana

Kulana is a self-hostable status page.

## Idea

Status pages and uptime monitoring systems can be [tricky to set up](https://www.atlassian.com/software/statuspage). Even if [they're good](https://betteruptime.com/), there are times when I just wanted to have a personal monitor for the status of a website or web service. Something that runs with minimal configuration, perhaps taking only the URL to monitor and using reasonable defaults for everything else.

The first iteration I have in mind would essentially be a static site generator, with the URLs to monitor in a config file. [Window.localStorage](https://developer.mozilla.org/en-US/docs/Web/API/Window/localStorage) would be used to save a local history of the site uptime. Later, it can piggyback off project-which-I-don't-wish-to-disclose for easy data persistence.
