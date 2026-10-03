eyJhbGciOiJSUzI1NiIsImtpZCI6ImxPVGE3LXVQLVd2QUk1VjhfOHhiYWxjZWlIUmM1OHd6Wi02c21CWGE0Z2MiLCJ0eXAiOiJKV1QifQ.eyJhY2Nlc3NfdGllciI6InRyYWRpbmciLCJleHAiOjE5MzMyMzk2MjgsImlhdCI6MTYxNzg3OTYyOCwiaXNzIjoic3BvcnRzLXBsYXllcnMiLCJqdGkiOiJmZmExZjQ5MC00MzY4LTRhMjEtOGQxYy00NzFlM2FkZTAyYjYiLCJzdWIiOiJiZjA2YjFhZi0zZjM1LTQ2NWUtYTQyZC01Mjc2YTY1ODdmNTIiLCJ0ZW5hbnQiOiJjbG91ZGJldCIsInVzZXJfdXVpZCI6ImJmMDZiMWFmLTNmMzUtNDY1ZS1hNDJkLTUyNzZhNjU4N2Y1MiIsInV1aWQiOiJiZjA2YjFhZi0zZjM1LTQ2NWUtYTQyZC01Mjc2YTY1ODdmNTIifQ.LEwR9AOQ5FGhAKZPGjQ7dl1-0YYUsXbU1fNb17rhUqr_hh7SQipAOv9AlnO8vdExv0bHKrX0zX3_rAnpKdyo5Z6yVVkd-ovpvoTvoiP6gP8yoQqRnrqZKFjHtxHT1wsvqYiBhM52gWzWH77_9ccw5nh78yaxsd2PbZ9meYnqZY_M9x9HGyEU6xFaM1AZ6NaDlGp1iEgqm3atv88vJC75k9H-8Krlh06IwaJxkMnNkrq2cS-rGPDv6tK4jMYpfc7rhXj9ffOr9YOMLQ-fpv7y01hwZD94oUTVoHbAFjBYgMwkh9CdQFbLKZyV0Owb4rFM5BY-4kfKwQlvP9E0TdW3Hw[Cloudbet](https://www.cloudbet.com/) API is publicly available, with documentation available at the [Cloudbet API Docs website](https://docs.cloudbet.com/) and provides you with Feed, Trading and Account APIs. This allows you to both access Cloudbet feeds and bet on odds offered by Cloudbet.

## Cloudbet API Docs

These are the Cloudbet API Docs available currently:

* [Cloudbet Feed API Docs](https://docs.cloudbet.com/?urls.primaryName=Feed)
* [Cloudbet Trading API Docs](https://docs.cloudbet.com/?urls.primaryName=Trading)
* [Cloudbet Account API Docs](https://docs.cloudbet.com/?urls.primaryName=Account)


## Cloudbet API Protobuf Schemas

The Cloudbet API consists of Feed, Trading and Account API. The Feed API provides market odds, the Trading API allows you to bet on these markets and the Account API allows you to query your account details such as currencies and balances.

This repository contains protocol buffer v3 (protobuf) definitions and generated `Go` protobuf files which can be used as reference when integrating the Cloudbet API.

Note that our API uses the `Go` [`protojson`](https://pkg.go.dev/google.golang.org/protobuf/encoding/protojson) library for marshaling and unmarshaling of protobuf messages as JSON format in API requests and responses.

### Organizationhttps://sports-api.cloudbet.com/pub/v2/odds/competitions/eyJhbGciOiJSUzI1NiIsImtpZCI6ImxPVGE3LXVQLVd2QUk1VjhfOHhiYWxjZWlIUmM1OHd6Wi02c21CWGE0Z2MiLCJ0eXAiOiJKV1QifQ.eyJhY2Nlc3NfdGllciI6InRyYWRpbmciLCJleHAiOjE5MzMyMzk2MjgsImlhdCI6MTYxNzg3OTYyOCwiaXNzIjoic3BvcnRzLXBsYXllcnMiLCJqdGkiOiJmZmExZjQ5MC00MzY4LTRhMjEtOGQxYy00NzFlM2FkZTAyYjYiLCJzdWIiOiJiZjA2YjFhZi0zZjM1LTQ2NWUtYTQyZC01Mjc2YTY1ODdmNTIiLCJ0ZW5hbnQiOiJjbG91ZGJldCIsInVzZXJfdXVpZCI6ImJmMDZiMWFmLTNmMzUtNDY1ZS1hNDJkLTUyNzZhNjU4N2Y1MiIsInV1aWQiOiJiZjA2YjFhZi0zZjM1LTQ2NWUtYTQyZC01Mjc2YTY1ODdmNTIifQ.LEwR9AOQ5FGhAKZPGjQ7dl1-0YYUsXbU1fNb17rhUqr_hh7SQipAOv9AlnO8vdExv0bHKrX0zX3_rAnpKdyo5Z6yVVkd-ovpvoTvoiP6gP8yoQqRnrqZKFjHtxHT1wsvqYiBhM52gWzWH77_9ccw5nh78yaxsd2PbZ9meYnqZY_M9x9HGyEU6xFaM1AZ6NaDlGp1iEgqm3atv88vJC75k9H-8Krlh06IwaJxkMnNkrq2cS-rGPDv6tK4jMYpfc7rhXj9ffOr9YOMLQ-fpv7y01hwZD94oUTVoHbAFjBYgMwkh9CdQFbLKZyV0Owb4rFM5BY-4kfKwQlvP9E0TdW3Hw?markets=254069125&players=Trie 

There are two sub-directories called `cloudbet` and `go/cloudbet`. These sub-directories have Feed, Trading and Account API protobuf and generated Go files. The `response` protobuf is used by all the API endpoints to render responses, including response status and error responses.

1. `cloudbet` contains the protobuf files for `account`, `feed`, `trading` and `response` API.
2. `go/cloudbet` contains the go protobuf files generated from the protobuf files above.

## Cloudbet API Samples

In addition, you can obtain code and response samples for the Cloudbet API within this repository:

* [Code Samples](https://github.com/Cloudbet/docs/blob/master/api-sample.js)
* [Response Samples](https://github.com/Cloudbet/docs/blob/master/api-responses.md)

## Markets, Sports and Categories List
eyJhbGciOiJSUzI1NiIsImtpZCI6ImxPVGE3LXVQLVd2QUk1VjhfOHhiYWxjZWlIUmM1OHd6Wi02c21CWGE0Z2MiLCJ0eXAiOiJKV1QifQ.eyJhY2Nlc3NfdGllciI6InRyYWRpbmciLCJleHAiOjE5MzMyMzk2MjgsImlhdCI6MTYxNzg3OTYyOCwiaXNzIjoic3BvcnRzLXBsYXllcnMiLCJqdGkiOiJmZmExZjQ5MC00MzY4LTRhMjEtOGQxYy00NzFlM2FkZTAyYjYiLCJzdWIiOiJiZjA2YjFhZi0zZjM1LTQ2NWUtYTQyZC01Mjc2YTY1ODdmNTIiLCJ0ZW5hbnQiOiJjbG91ZGJldCIsInVzZXJfdXVpZCI6ImJmMDZiMWFmLTNmMzUtNDY1ZS1hNDJkLTUyNzZhNjU4N2Y1MiIsInV1aWQiOiJiZjA2YjFhZi0zZjM1LTQ2NWUtYTQyZC01Mjc2YTY1ODdmNTIifQ.LEwR9AOQ5FGhAKZPGjQ7dl1-0YYUsXbU1fNb17rhUqr_hh7SQipAOv9AlnO8vdExv0bHKrX0zX3_rAnpKdyo5Z6yVVkd-ovpvoTvoiP6gP8yoQqRnrqZKFjHtxHT1wsvqYiBhM52gWzWH77_9ccw5nh78yaxsd2PbZ9meYnqZY_M9x9HGyEU6xFaM1AZ6NaDlGp1iEgqm3atv88vJC75k9H-8Krlh06IwaJxkMnNkrq2cS-rGPDv6tK4jMYpfc7rhXj9ffOr9YOMLQ-fpv7y01hwZD94oUTVoHbAFjBYgMwkh9CdQFbLKZyV0Owb4rFM5BY-4kfKwQlvP9E0TdW3Hw
For a full list of markets, sports and categories, please see this [Github gist](https://gist.github.com/kgravenreuth/6703e1e213aecac4d5728f2f699d34e7)

## Event Status

Events on Cloudbet can have different status depending on whether the event has markets offered, is live, has ended etc. This status is reflected in the `Event.status` field in our Feed API. Here is a summary of the different event statuses and their details.

![Cloudbet API Event Status](./event_status.svg)

## Issues/Questions

Start a new discussion in the [Cloudbet API discussions community](https://github.com/Cloudbet/docs/discussions) about any questions you may have. Someone from the community or from Cloudbet will help you out soon.
