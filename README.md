<!--
 ___ _            _ _    _ _    __
/ __(_)_ __  _ __| (_)__(_) |_ /_/
\__ \ | '  \| '_ \ | / _| |  _/ -_)
|___/_|_|_|_| .__/_|_\__|_|\__\___|
            |_| 
-->
![](https://docs.simplicite.io//logos/logo250.png)
* * *

`ISOLanguages` module definition
================================

[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=simplicite-modules-ISOLanguages&metric=alert_status)](https://sonarcloud.io/dashboard?id=simplicite-modules-ISOCountries)

### Introduction

Languages (ISO 639)

### Import

To import this module:

- Create a module named `ISOLanguages`
- Set the settings as:

```json
{
	"type": "git",
	"origin": {
		"uri": "https://github.com/simplicitesoftware/module-isolanguages.git"
	}
}
```

- Click on the _Import module_ button

### Load data

Languages data is provided as the module's dataset.

Open this dataset and click on the _Apply_ button after having imported the module and made a full clear cache.

`ISOLanguage` business object definition
----------------------------------------

ISO 639 languages

### Fields

| Name                                                         | Type                                     | Required | Updatable | Personal | Description                                                                      |
|--------------------------------------------------------------|------------------------------------------|----------|-----------|----------|----------------------------------------------------------------------------------|
| `isoLngName`                                                 | char(100)                                | yes      | yes       |          | ISO language name                                                                |
| `isoLngCode`                                                 | char(2)                                  | yes*     | yes       |          | 2 digits code (ISO-639-1)                                                        |
| `isoLngCode3`                                                | char(3)                                  | yes      | yes       |          | 3 digits code (ISO-639-3)                                                        |
| `isoLngCode3T`                                               | char(3)                                  | yes      | yes       |          | 3 digits code (ISO 639-2/T)                                                      |
| `isoLngCode3B`                                               | char(3)                                  | yes      | yes       |          | 3 digits code (ISO-639-2/B)                                                      |

