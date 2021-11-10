# wordpress-to-github implementation for digital.ca.gov

This is the [wordpress-to-github](https://www.npmjs.com/package/@cagov/wordpress-to-github) implementation for [digital.ca.gov](https://digital.ca.gov).

## Deploys services to the following Azure Function

- `FA-GO-WORDPRESS-TO-GITHUB-DIGITAL-CA-GOV` - Function app
- `sagowpghubdigitalcagov` - Storage account

## Target site source

https://github.com/cagov/digital.ca.gov

## Referenced WordPress instances

- https://live-digital-ca-gov.pantheonsite.io

## WordPress notification config target

You will need to create a Function Key in the Azure instance to use a trigger. See the [wordpress-to-github readme](https://github.com/cagov/wordpress-to-github#readme).

### Trigger Target

`https://fa-go-wordpress-to-github-digital-ca-gov.azurewebsites.net/WordpressSyncHttpTrigger?code=[Put Function Key Here]`

## Current Configuration

See the [endpoints.json](https://github.com/cagov/services-wordpress-to-github-digital-ca-gov/blob/main/WordpressSync/endpoints.json) file in this project for current configuration.
