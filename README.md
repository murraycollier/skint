# Skint

Skint is a household money tracker that replaces the `Expenditure.xlsx` workbook with a browser app. It runs in Docker and stores its data in a SQLite file on a Docker volume on your own machine.

Website: https://skint.site

## Download

Download the latest release from the [Releases page](https://github.com/murraycollier/skint/releases/latest):

- `skint.zip`: the app source, Dockerfile and requirements
- `docker-compose.yml`: publishes Skint on port 8080
- `env.example`: the settings file, to copy to `.env`

Then follow the [setup guide](https://skint.site/get-started/) to install Docker and run the app.

## Need help?

Check the [setup guide](https://skint.site/get-started/) first. If that doesn't solve it, [open an issue](https://github.com/murraycollier/skint/issues/new/choose).
