# wordpress-to-github implementation for sand-ca-gov on Pantheon

This is the [wordpress-to-github](https://www.npmjs.com/package/@cagov/wordpress-to-github) implementation for [sandbox](https://dev-sand-ca-gov.pantheonsite.io/).

## Deploys services to the following Azure Function

- `FA-GO-WORDPRESS-TO-GITHUB-SAND-CA-GOV` - Function app

 <!-- - `sagowpghubdroughtcagov` - Storage account -->

## Target site source

https://github.com/cagov/odi-publishing-11ty-sandbox

## Referenced WordPress instances

- https://dev-sand-ca-gov.pantheonsite.io/wp-admin/


<!-- ## WordPress notification config target

You will need to create a Function Key in the Azure instance to use a trigger. See the [wordpress-to-github readme](https://github.com/cagov/wordpress-to-github#setting-trigger-app-keys).

### Trigger Target

`https://fa-go-wordpress-to-github-drought-ca-gov.azurewebsites.net/WordpressSyncHttpTrigger?code=[Put Function Key Here]` -->

## Current Configuration

See the [endpoints.json](https://github.com/cagov/services-wordpress-to-github-sand-ca-gov/blob/main/WordpressSync/endpoints.json) file in this project for current configuration.
