# Prometheus Testing

Sometimes I find myself in the need of a simple and quick setup to start
testing prometheus or the alertmanager.

Just clone this repository, change into it and run

	docker-compose up

Visit http://localhost:9090 for Prometheus, http://localhost:9093 for
AlertManager or if you need http://localhost:3000 for Grafana.

## Alerts

There's already one alert predefined that fires every minute.
Perfect for development.

Just edit `alertmanager/alertmanager.yml` to your needs and alerts will be send to you.
Slack is already predefined, you just need to replace the `slack_api_url` with one of yours.

More examples may be added in the future.

## Grafana

I've set a default password. Visit http://localhost:3000 and you can login with

	admin - prometheus

# Contributing

Fork -> Patch -> Push -> Pull Request

# Authors

* [Matthias Loibl](https://github.com/metalmatze)

# License

MIT
