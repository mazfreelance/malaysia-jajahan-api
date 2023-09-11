# Malaysia Jajahan API

A REST API about states in Malaysia.

**This API inspired from [lomotech/jajahan](https://github.com/lomotech/jajahan)**. It is **intentional** for files to be stored this way (json format) as it avoids using any database engine and to be read-only web API.

## Resource

- [sddsa](http://sddsa.mampu.gov.my/)
- [Statistics My](http://statistics.gov.my/)
- [Sabah My](http://www.sabah.gov.my/)

## List of endpoints

The current url is https://mazfreelance.github.io/malaysia-jajahan-api
| Type                                              | End Point                                               | Link                                                                                                               |
| ------------------------------------------------- | ------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------ |
| country                                           | /v1/countries.json                                      | [Test](https://mazfreelance.github.io/malaysia-jajahan-api/v1/countries.json)                                      |
| state                                             | /v1/states.json                                         | [Test](https://mazfreelance.github.io/malaysia-jajahan-api/v1/states.json)                                         |
| dun                                               | /v1/countries.json                                      | [Test](https://mazfreelance.github.io/malaysia-jajahan-api/v1/dun.json)                                            |
| parliament                                        | /v1/countries.json                                      | [Test](https://mazfreelance.github.io/malaysia-jajahan-api/v1/parliament.json)                                     |
| education - level                                 | /v1/educations/level.json                               | [Test](https://mazfreelance.github.io/malaysia-jajahan-api/v1/educations/level.json)                               |
| education - field of study (all)                  | /v1/educations/field-of-study.json                      | [Test](https://mazfreelance.github.io/malaysia-jajahan-api/v1/educations/field-of-study.json)                      |
| education - field of study (board field)          | /v1/educations/field-of-study/board-field.json          | [Test](https://mazfreelance.github.io/malaysia-jajahan-api/v1/educations/field-of-study/board-field.json)          |
| education - field of study (narrow field)         | /v1/educations/field-of-study/narrow-field.json         | [Test](https://mazfreelance.github.io/malaysia-jajahan-api/v1/educations/field-of-study/narrow-field.json)         |
| education - field of study (narrow field details) | /v1/educations/field-of-study/narrow-field-details.json | [Test](https://mazfreelance.github.io/malaysia-jajahan-api/v1/educations/field-of-study/narrow-field-details.json) |
| bank                                              | /v1/bank.json                                           | [Test](https://mazfreelance.github.io/malaysia-jajahan-api/v1/bank.json)                                           |

## Usage

- request

```bash
curl https://mazfreelance.github.io/malaysia-jajahan-api/v1/countries.json
```

- response

```json
[
    {
        "id": "004",
        "name": "Afghanistan",
        "iso_3166_2": "AF",
        "iso_3166_3": "AFG"
    },
    {
        "id": "008",
        "name": "Albania",
        "iso_3166_2": "AL",
        "iso_3166_3": "ALB"
    },
    {
        "id": "010",
        "name": "Antarctica",
        "iso_3166_2": "AQ",
        "iso_3166_3": "ATA"
    },
    {
        "id": "012",
        "name": "Algeria",
        "iso_3166_2": "DZ",
        "iso_3166_3": "DZA"
    },
    {
        "id": "016",
        "name": "American Samoa",
        "iso_3166_2": "AS",
        "iso_3166_3": "ASM"
    }
]
```

## Reference

- [lomotech/jajahan](https://github.com/lomotech/jajahan)

## Contribution

- If you have noticed some mistakes or bugs, or maybe you have any suggestions please create an issue.
- Have you found something new information or bugs? Make a PR and add it to the list!
